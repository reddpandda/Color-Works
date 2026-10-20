# Fuzz 1: messy rp and table mixes

Markers are ZZn. END n lines follow each case to detect leaks.

CASE 1 rp opened in one cell, closed in the next.

<table>
<tr><td>r1</td><td>r1</td></tr>
<tr><td><rp>ZZ1a</td><td>ZZ1b</rp></td></tr>
<tr><td>r3</td><td>r3</td></tr>
</table>

END 1

CASE 4 rp opened before the table in the same block, closed inside a cell.

<rp>
<table>
<tr><td>r1</td><td>r1</td></tr>
<tr><td>ZZ4</td><td>ZZ4</rp></td></tr>
<tr><td>r3</td><td>r3</td></tr>
</table>

END 4

CASE 5 rp around the whole table (control, whole table should hide).

<rp>
<table>
<tr><td>ZZ5</td><td>ZZ5</td></tr>
</table>
</rp>

END 5

CASE 6 rp opened at the end of one row, closed at the start of the next.

<table>
<tr><td>r1</td><rp></tr>
<tr></rp><td>ZZ6</td></tr>
<tr><td>r3</td></tr>
</table>

END 6

CASE 7 rp opened in a cell, closed in the next row.

<table>
<tr><td>r1<rp></td></tr>
<tr><td></rp>ZZ7</td></tr>
<tr><td>r3</td></tr>
</table>

END 7

CASE 8 rp across thead and tbody.

<table>
<thead><tr><th><rp>ZZ8a</th></tr></thead>
<tbody><tr><td></rp>ZZ8b</td></tr>
<tr><td>r3</td></tr></tbody>
</table>

END 8

CASE 9 rp straddling a nested table.

<table>
<tr><td>r1</td><td><table><tr><td><rp>ZZ9a</td></tr></table></rp>ZZ9b</td></tr>
<tr><td>r3</td><td>r3</td></tr>
</table>

END 9

CASE 10 ruby and rp opened in one cell, closed in the next.

<table>
<tr><td>r1</td><td>r1</td></tr>
<tr><td><ruby>ZZ10a<rp>(</td><td>ZZ10b</ruby></td></tr>
<tr><td>r3</td><td>r3</td></tr>
</table>

END 10

CASE 11 blank line inside an rp inside a cell.

<table>
<tr><td>r1</td><td>r1</td></tr>
<tr><td><rp>ZZ11a

ZZ11b</rp></td><td>ZZ11c</td></tr>
<tr><td>r3</td><td>r3</td></tr>
</table>

END 11

CASE 12 pipe table, rp opened and closed in different cells of one row.

| a | b |
|---|---|
| <rp>ZZ12a | ZZ12b</rp> |
| r3 | r3 |

END 12

CASE 13 pipe table, rp opened in the header row and closed in the last row.

| <rp>ZZ13h | h |
|---|---|
| ZZ13m | m |
| ZZ13e</rp> | e |

END 13

CASE 14 misordered close tags around a nested table.

<table>
<tr><td>r1</td><td><rp><table><tr><td>ZZ14a</td></tr></rp></table>ZZ14b</td></tr>
<tr><td>r3</td><td>r3</td></tr>
</table>

END 14

CASE 15 rp opened in a cell, closed after the table.

<table>
<tr><td>r1</td></tr>
<tr><td><rp>ZZ15a</td></tr>
<tr><td>ZZ15b</td></tr>
</table>
</rp>

END 15

CASE 16 details inside rp inside a cell.

<table>
<tr><td>r1</td><td><rp><details><summary>ZZ16</summary>x</details></rp>after</td></tr>
<tr><td>r3</td><td>r3</td></tr>
</table>

END 16

CASE 17 template inside a row.

<table>
<tr><td>r1</td><template><td>ZZ17</td></template></tr>
<tr><td>r3</td></tr>
</table>

END 17

CASE 18 template wrapping a row.

<table>
<tr><td>r1</td></tr>
<template><tr><td>ZZ18</td></tr></template>
<tr><td>r3</td></tr>
</table>

END 18

CASE 19 hidden input directly in the table.

<table>
<input type="hidden" name="ZZ19">
<tr><td>r1</td></tr>
<tr><td>r3</td></tr>
</table>

END 19

CASE 20 noscript wrapping a row.

<table>
<tr><td>r1</td></tr>
<noscript><tr><td>ZZ20</td></tr></noscript>
<tr><td>r3</td></tr>
</table>

END 20

CASE 21 html comment wrapping a row.

<table>
<tr><td>r1</td></tr>
<!-- <tr><td>ZZ21</td></tr> -->
<tr><td>r3</td></tr>
</table>

END 21

CASE 22 script and style in the table.

<table>
<tr><td>r1</td></tr>
<script>ZZ22a</script><style>ZZ22b</style>
<tr><td>r3</td></tr>
</table>

END 22

CASE 23 hidden attribute on a cell.

<table>
<tr><td>r1</td><td hidden>ZZ23</td></tr>
<tr><td>r3</td><td>r3</td></tr>
</table>

END 23

CASE 24 utility classes and attributes on cells and spans.

<table>
<tr><td>r1</td><td class="d-none">ZZ24a</td></tr>
<tr><td class="sr-only">ZZ24b</td><td><span class="d-none">ZZ24c</span><div hidden>ZZ24d</div><span aria-hidden="true">ZZ24e</span></td></tr>
<tr><td>r3</td><td>r3</td></tr>
</table>

END 24
