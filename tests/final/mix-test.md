# Mix test: pipe tables and html tables

Every table has 6 visible rows labelled v1 to v6 (visual order). Note which labels are shaded. My prediction from the HTML is written under each one.

X1 pipe table. Prediction: v3 v5 shaded.

| v1 header | h |
|-----------|---|
| v2 | b |
| v3 | b |
| v4 | b |
| v5 | b |
| v6 | b |

X2 plain html table, no thead. Prediction: v2 v4 v6 shaded.

<table>
<tr><td>v1</td><td>h</td></tr>
<tr><td>v2</td><td>b</td></tr>
<tr><td>v3</td><td>b</td></tr>
<tr><td>v4</td><td>b</td></tr>
<tr><td>v5</td><td>b</td></tr>
<tr><td>v6</td><td>b</td></tr>
</table>

X3 html table with a thead row. Prediction: v3 v5 shaded, same as the pipe table.

<table>
<thead><tr><th>v1 header</th><th>h</th></tr></thead>
<tbody>
<tr><td>v2</td><td>b</td></tr>
<tr><td>v3</td><td>b</td></tr>
<tr><td>v4</td><td>b</td></tr>
<tr><td>v5</td><td>b</td></tr>
<tr><td>v6</td><td>b</td></tr>
</tbody>
</table>

X4 pipe table with an empty header row. Prediction: v1 is a thin blank row, v3 v5 shaded.

| | |
|-|-|
| v2 | b |
| v3 | b |
| v4 | b |
| v5 | b |
| v6 | b |

X5 html table with a thead of TWO rows. Prediction: v1 v2 in thead (unshaded count), v4 v6 shaded.

<table>
<thead>
<tr><th>v1 header</th><th>h</th></tr>
<tr><th>v2 header</th><th>h</th></tr>
</thead>
<tbody>
<tr><td>v3</td><td>b</td></tr>
<tr><td>v4</td><td>b</td></tr>
<tr><td>v5</td><td>b</td></tr>
<tr><td>v6</td><td>b</td></tr>
</tbody>
</table>

X6 html table with a pipe table inside a cell.

<table>
<tr><td>X6 outer v1</td><td>

| in v1 | h |
|-------|---|
| in v2 | b |
| in v3 | b |
| in v4 | b |

</td></tr>
<tr><td>X6 outer v2</td><td>x</td></tr>
</table>

X7 pipe table with an html role block inside a cell.

| h1 | h2 |
|----|----|
| X7 plain | <table><tr><td rowspan="2">X7 span</td><td>r1</td></tr><tr><td>r2</td></tr></table> |
| X7 after | b |

X8 pipe table directly followed by raw tr lines, no blank line. Prediction: the tr lines do not join the table.

| h1 | h2 |
|----|----|
| X8 body | b |
<tr><td>X8 raw tr after</td><td>b</td></tr>

X9 pipe rows written inside an html table block. Prediction: the pipe text leaks out above the table.

<table>
| X9 a | b |
|------|---|
| X9 1 | 2 |
<tr><td>X9 real row</td></tr>
</table>

X10 pipe table, then an html tfoot table separately, same page.

| h1 | h2 |
|----|----|
| X10 body | b |

<table><tfoot><tr><td>X10 foot</td></tr></tfoot></table>

X11 plain html table whose first row uses th cells. Prediction: v2 v4 v6 shaded.

<table>
<tr><th>v1 header</th><th>h</th></tr>
<tr><td>v2</td><td>b</td></tr>
<tr><td>v3</td><td>b</td></tr>
<tr><td>v4</td><td>b</td></tr>
<tr><td>v5</td><td>b</td></tr>
<tr><td>v6</td><td>b</td></tr>
</table>
