# Ruby and rp hide results

How to read this page: every table has a visible row before and after the test row. Each test carries a marker word like `HIDE-A1`. If you can see the marker on screen, the hide FAILED. If the marker is gone, the hide WORKED. A line under each test says what I saw in GitHub's rendered HTML, so you can compare it with what you see.

## 0. Controls (these should work)

C1 inline `rp` in a paragraph: before <rp>HIDE-C1-inline</rp> after. Expected: you see only "before  after".

C2 `rp` inside a cell with normal text:

<table>
<tr><td>row 1 left</td><td>row 1 right</td></tr>
<tr><td>row 2 left <rp>HIDE-C2</rp>after</td><td>row 2 right</td></tr>
<tr><td>row 3 left</td><td>row 3 right</td></tr>
</table>

Expected: no `HIDE-C2` visible. (If it is visible, `rp` does not hide text in your browser and every result below is moot.)

## 1. rp between table parts (hide a row or cell)

A1 `rp` between two cells of a row. HTML showed: `rp` moved out and placed before the table.

<table>
<tr><td>row 1 left</td><rp>HIDE-A1</rp><td>row 1 right</td></tr>
<tr><td>row 2 left</td><td>row 2 right</td></tr>
<tr><td>row 3 left</td><td>row 3 right</td></tr>
</table>

A2 `rp` before the first row, directly in the table. HTML showed: `rp` moved out before the table.

<table>
<rp>HIDE-A2</rp>
<tr><td>row 1 left</td><td>row 1 right</td></tr>
<tr><td>row 2 left</td><td>row 2 right</td></tr>
<tr><td>row 3 left</td><td>row 3 right</td></tr>
</table>

A3 `rp` wrapped around a whole row. HTML showed: an empty `rp` and the row still present. Marker should be VISIBLE if that is true.

<table>
<tr><td>row 1 left</td><td>row 1 right</td></tr>
<rp><tr><td>HIDE-A3 left</td><td>HIDE-A3 right</td></tr></rp>
<tr><td>row 3 left</td><td>row 3 right</td></tr>
</table>

A4 `rp` wrapped around a whole cell. HTML showed: an empty `rp` and the cell still present.

<table>
<tr><td>row 1 left</td><rp><td>HIDE-A4</td></rp><td>row 1 right</td></tr>
<tr><td>row 2 left</td><td>row 2 right</td></tr>
</table>

## 2. rp around a whole nested table (this one hid in my render)

A5 HTML showed: the nested table is inside the `rp`. Expected: no `HIDE-A5` visible, and the text "after the rp" visible.

<table>
<tr><td>row 1 left</td><td><rp><table><tr><td>HIDE-A5 inner</td></tr></table></rp>after the rp</td></tr>
<tr><td>row 2 left</td><td>row 2 right</td></tr>
</table>

## 3. Empty and collapsed rows (do they take up space?)

B1 row 2 holds only `rp` text, row 3 is empty. Look at how tall rows 2 and 3 are. In my render they were thin lines, not zero.

<table>
<tr><td>row 1 left</td><td>row 1 right</td></tr>
<tr><td><rp>HIDE-B1a</rp></td><td><rp>HIDE-B1b</rp></td></tr>
<tr><td></td><td></td></tr>
<tr><td>row 4 left</td><td>row 4 right</td></tr>
</table>

B2 same with `height="0"` on the row and cells.

<table>
<tr height="0"><td height="0"><rp>HIDE-B2a</rp></td><td height="0"><rp>HIDE-B2b</rp></td></tr>
<tr><td>row 2 left</td><td>row 2 right</td></tr>
<tr><td>row 3 left</td><td>row 3 right</td></tr>
</table>

B3 table with `cellpadding="0" cellspacing="0"` and an empty middle row.

<table cellpadding="0" cellspacing="0">
<tr><td>row 1 left</td><td>row 1 right</td></tr>
<tr><td></td><td></td></tr>
<tr><td>row 3 left</td><td>row 3 right</td></tr>
</table>

## 4. Other ruby elements

C1 ruby with `rp`. Expected: the base word with a small annotation above it, no parentheses.

<table>
<tr><td>ruby with rp</td><td><ruby>base<rp>(</rp><rt>ann</rt><rp>)</rp></ruby></td></tr>
<tr><td>`rb` and `rtc` (HTML showed these tags removed)</td><td><ruby><rb>base</rb><rt>ann</rt><rtc>RTC-C1</rtc></ruby></td></tr>
<tr><td>`rt` with no base text</td><td><ruby><rt>HIDE-C1-rt-only</rt></ruby></td></tr>
<tr><td>`rp` around a whole ruby</td><td><rp><ruby>HIDE-C1<rt>x</rt></ruby></rp>after</td></tr>
</table>

## 5. Other hiders in table structure

D1 `details` between cells. HTML showed: moved out before the table. The words `HIDE-D1` may appear above the table as a fold.

<table>
<tr><td>row 1 left</td><details><summary>HIDE-D1 summary</summary>HIDE-D1 body</details><td>row 1 right</td></tr>
<tr><td>row 2 left</td><td>row 2 right</td></tr>
</table>

E1 a row with `align`, `valign`, `bgcolor` and `class="d-none"`. Expected: row visible, no yellow, since the attributes are stripped.

<table>
<tr align="center" valign="bottom" bgcolor="#ffcc00" class="d-none"><td>attrs left</td><td>attrs right</td></tr>
<tr><td>row 2 left</td><td>row 2 right</td></tr>
</table>

E2 a row with the `hidden` attribute. HTML showed: attribute stripped. Expected: the row is visible.

<table>
<tr><td>row 1 left</td><td>row 1 right</td></tr>
<tr hidden><td>HIDE-E2 left</td><td>HIDE-E2 right</td></tr>
<tr><td>row 3 left</td><td>row 3 right</td></tr>
</table>

## What to report back

- Is `HIDE-C1-inline` and `HIDE-C2` gone? (If not, stop: `rp` is not hiding for you.)
- Which of `HIDE-A1`, `A2`, `A3`, `A4`, `A5`, `B1`, `B2`, `D1`, `E2` can you see?
- In B1, B2 and B3, do the empty rows look like thin lines, or are they gone?
