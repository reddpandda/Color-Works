# Fuzz 2: messy rp and table mixes, reset after each case

A stray closer block follows each case so one leak cannot hide the next.

CASE 1 rp opened in one cell, closed in the next.

<table>
<tr><td>r1</td><td>r1</td></tr>
<tr><td><rp>ZZ1a</td><td>ZZ1b</rp></td></tr>
<tr><td>r3</td><td>r3</td></tr>
</table>

END 1

</rp></rp></rp>

CASE 4 rp opened before the table in the same block, closed inside a cell.

<rp>
<table>
<tr><td>r1</td><td>r1</td></tr>
<tr><td>ZZ4</td><td>ZZ4</rp></td></tr>
<tr><td>r3</td><td>r3</td></tr>
</table>

END 4

</rp></rp></rp>

CASE 6 rp opened at the end of one row, closed at the start of the next.

<table>
<tr><td>r1</td><rp></tr>
<tr></rp><td>ZZ6</td></tr>
<tr><td>r3</td></tr>
</table>

END 6

</rp></rp></rp>

CASE 7 rp opened in a cell, closed in the next row.

<table>
<tr><td>r1<rp></td></tr>
<tr><td></rp>ZZ7</td></tr>
<tr><td>r3</td></tr>
</table>

END 7

</rp></rp></rp>

CASE 8 rp across thead and tbody.

<table>
<thead><tr><th><rp>ZZ8a</th></tr></thead>
<tbody><tr><td></rp>ZZ8b</td></tr>
<tr><td>r3</td></tr></tbody>
</table>

END 8

</rp></rp></rp>

CASE 9 rp straddling a nested table.

<table>
<tr><td>r1</td><td><table><tr><td><rp>ZZ9a</td></tr></table></rp>ZZ9b</td></tr>
<tr><td>r3</td><td>r3</td></tr>
</table>

END 9

</rp></rp></rp>

CASE 10 ruby and rp opened in one cell, closed in the next.

<table>
<tr><td>r1</td><td>r1</td></tr>
<tr><td><ruby>ZZ10a<rp>(</td><td>ZZ10b</ruby></td></tr>
<tr><td>r3</td><td>r3</td></tr>
</table>

END 10

</rp></rp></rp>

CASE 11 blank line inside an rp inside a cell.

<table>
<tr><td>r1</td><td>r1</td></tr>
<tr><td><rp>ZZ11a

ZZ11b</rp></td><td>ZZ11c</td></tr>
<tr><td>r3</td><td>r3</td></tr>
</table>

END 11

</rp></rp></rp>

CASE 12 pipe table, rp opened and closed in different cells of one row.

| a | b |
|---|---|
| <rp>ZZ12a | ZZ12b</rp> |
| r3 | r3 |

END 12

</rp></rp></rp>

CASE 13 pipe table, rp opened in the header row and closed in the last row.

| <rp>ZZ13h | h |
|---|---|
| ZZ13m | m |
| ZZ13e</rp> | e |

END 13

</rp></rp></rp>

CASE 14 misordered close tags around a nested table.

<table>
<tr><td>r1</td><td><rp><table><tr><td>ZZ14a</td></tr></rp></table>ZZ14b</td></tr>
<tr><td>r3</td><td>r3</td></tr>
</table>

END 14

</rp></rp></rp>

CASE 15 rp opened in a cell, closed after the table.

<table>
<tr><td>r1</td></tr>
<tr><td><rp>ZZ15a</td></tr>
<tr><td>ZZ15b</td></tr>
</table>
</rp>

END 15

</rp></rp></rp>
