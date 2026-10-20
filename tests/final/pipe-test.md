# Test 4: pipe table edge cases

Each case says what I expect from GitHub's table rules. Look at the result and tell me where it differs.

P1 escaped pipe outside code. Expect: cell text `a | b`, two columns.

| h1 | h2 |
|----|----|
| a \| b | c |

P2 unescaped pipe inside a code span. Expect: the pipe still splits the cell (3 cells, last cut off).

| h1 | h2 |
|----|----|
| `x | y` | z |

P3 escaped pipe inside a code span. Expect: one cell showing `x | y`.

| h1 | h2 |
|----|----|
| `x \| y` | z |

P4 too many cells in a row. Expect: the extra cell is dropped.

| h1 | h2 |
|----|----|
| 1 | 2 | 3 | 4 |

P5 too few cells. Expect: the missing cell is empty.

| h1 | h2 |
|----|----|
| only |

P6 header only, no body rows. Expect: a header row alone.

| h1 | h2 |
|----|----|

P7 alignment colons. Expect: left, centre, right.

| left | centre | right |
|:-----|:------:|------:|
| l | c | r |

P8 table directly after a paragraph with no blank line. Expect: GitHub may or may not start the table.
paragraph line right before the table
| h1 | h2 |
|----|----|
| 1 | 2 |

P9 empty header cells. Expect: a blank header row.

| | |
|-|-|
| 1 | 2 |

P10 line breaks in a cell with br.

| h1 | h2 |
|----|----|
| line one<br>line two<br><br>line four | x |

P11 table inside a list item.

- item with a table:

  | h1 | h2 |
  |----|----|
  | 1 | 2 |
  | 3 | 4 |

P12 table inside a blockquote.

> | h1 | h2 |
> |----|----|
> | 1 | 2 |
> | 3 | 4 |

P13 table inside an alert.

> [!NOTE]
> | h1 | h2 |
> |----|----|
> | 1 | 2 |
> | 3 | 4 |

P14 table inside details.

<details><summary>P14 open to see the table</summary>

| h1 | h2 |
|----|----|
| 1 | 2 |
| 3 | 4 |

</details>

P15 an html table written inside a pipe cell.

| h1 | h2 |
|----|----|
| <table><tr><td>inner</td></tr></table> | y |
| 3 | 4 |

P16 a pipe inside math in a cell.

| h1 | h2 |
|----|----|
| $a \| b$ | c |

P17 no leading or trailing pipes.

h1 | h2
---|---
1 | 2
3 | 4

P18 header has two columns, delimiter row has three. Expect: not a table.

| h1 | h2 |
|----|----|----|
| 1 | 2 |

P19 details and code in a pipe cell.

| h1 | h2 |
|----|----|
| <details><summary>P19 fold</summary>`code` in fold</details> | y |
| 3 | 4 |

P20 cells with only spaces and a long word, to see column sizing.

| a | averyveryveryveryveryveryveryveryveryveryverylongwordwithoutanybreakpointsatall | c |
|---|---|---|
| 1 | 2 | 3 |
