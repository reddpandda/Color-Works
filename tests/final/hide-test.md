# Hide test

Each table has rows r1 r2 r3 so zebra parity is visible. Markers HIDE-xx should not be visible if hiding works.

## A. rp in structural positions

A1 rp as a direct child of tr, between the two cells.

<table>
<tr><td>r1 left</td><rp>HIDE-A1</rp><td>r1 right</td></tr>
<tr><td>r2 left</td><td>r2 right</td></tr>
<tr><td>r3 left</td><td>r3 right</td></tr>
</table>

A2a rp as a direct child of tbody, before the first row.

<table>
<tbody>
<rp>HIDE-A2a</rp>
<tr><td>r1 left</td><td>r1 right</td></tr>
<tr><td>r2 left</td><td>r2 right</td></tr>
<tr><td>r3 left</td><td>r3 right</td></tr>
</tbody>
</table>

A2b rp as a direct child of table, before the first row.

<table>
<rp>HIDE-A2b</rp>
<tr><td>r1 left</td><td>r1 right</td></tr>
<tr><td>r2 left</td><td>r2 right</td></tr>
<tr><td>r3 left</td><td>r3 right</td></tr>
</table>

A3 rp wrapping a whole tr (second row).

<table>
<tr><td>r1 left</td><td>r1 right</td></tr>
<rp><tr><td>HIDE-A3 left</td><td>HIDE-A3 right</td></tr></rp>
<tr><td>r3 left</td><td>r3 right</td></tr>
<tr><td>r4 left</td><td>r4 right</td></tr>
</table>

A4 rp wrapping a whole td.

<table>
<tr><td>r1 left</td><rp><td>HIDE-A4</td></rp><td>r1 right</td></tr>
<tr><td>r2 left</td><td>r2 right</td></tr>
<tr><td>r3 left</td><td>r3 right</td></tr>
</table>

A5 rp wrapping an entire nested table inside a cell.

<table>
<tr><td>r1 left</td><td><rp><table><tr><td>HIDE-A5 inner</td></tr></table></rp>after the rp</td></tr>
<tr><td>r2 left</td><td>r2 right</td></tr>
</table>

A6 rp inside a cell with block-ish content (table row inside rp inside td).

<table>
<tr><td>r1 left</td><td><rp><tr><td>HIDE-A6</td></tr></rp>r1 right</td></tr>
<tr><td>r2 left</td><td>r2 right</td></tr>
</table>

## B. Cell-level collapse

B1 three rows: normal, only rp text, truly empty.

<table>
<tr><td>normal row</td><td>text</td></tr>
<tr><td><rp>HIDE-B1a</rp></td><td><rp>HIDE-B1b</rp></td></tr>
<tr><td></td><td></td></tr>
<tr><td>last row</td><td>text</td></tr>
</table>

B2 row with cells holding rp plus height 0.

<table>
<tr height="0"><td height="0"><rp>HIDE-B2a</rp></td><td height="0"><rp>HIDE-B2b</rp></td></tr>
<tr><td>r2</td><td>text</td></tr>
<tr><td>r3</td><td>text</td></tr>
</table>

## C. Ruby family in cells

C1 ruby variants.

<table>
<tr><td>ruby with rp</td><td><ruby>base<rp>(</rp><rt>ann</rt><rp>)</rp></ruby></td></tr>
<tr><td>ruby with rb and rtc</td><td><ruby><rb>base</rb><rt>ann</rt><rtc>RTC-C1</rtc></ruby></td></tr>
<tr><td>rt only, no base</td><td><ruby><rt>HIDE-C1-rt-only</rt></ruby></td></tr>
<tr><td>rp around a whole ruby</td><td><rp><ruby>HIDE-C1<rt>x</rt></ruby></rp>after</td></tr>
</table>

## D. Other hiders in structural positions

D1 details as a child of tr and tbody.

<table>
<tr><td>r1 left</td><details><summary>HIDE-D1 summary</summary>HIDE-D1 body</details><td>r1 right</td></tr>
<tr><td>r2 left</td><td>r2 right</td></tr>
</table>

D2 a row whose cells hold only dark-mode-only links (visible in dark mode only).

<table>
<tr><td><a href="glossary.md#gh-dark-mode-only">D2 dark only left</a></td><td><a href="glossary.md#gh-dark-mode-only">D2 dark only right</a></td></tr>
<tr><td>r2 left</td><td>r2 right</td></tr>
<tr><td>r3 left</td><td>r3 right</td></tr>
</table>

D3 a row whose cells hold only light-mode-only links (visible in light mode only).

<table>
<tr><td><a href="glossary.md#gh-light-mode-only">D3 light only left</a></td><td><a href="glossary.md#gh-light-mode-only">D3 light only right</a></td></tr>
<tr><td>r2 left</td><td>r2 right</td></tr>
<tr><td>r3 left</td><td>r3 right</td></tr>
</table>

## E. Attributes on rows and tables

E1 rowspan 0.

<table>
<tr><td rowspan="0">spans to end</td><td>r1 right</td></tr>
<tr><td>r2 right</td></tr>
<tr><td>r3 right</td></tr>
</table>

E2 cellpadding 0 and cellspacing 0 on the table.

<table cellpadding="0" cellspacing="0">
<tr><td>r1 left</td><td>r1 right</td></tr>
<tr><td></td><td></td></tr>
<tr><td>r3 left</td><td>r3 right</td></tr>
</table>

E3 tr with align, valign, bgcolor and class attributes.

<table>
<tr align="center" valign="bottom" bgcolor="#ffcc00" class="d-none"><td>tr attrs left</td><td>tr attrs right</td></tr>
<tr><td>r2 left</td><td>r2 right</td></tr>
</table>
