# Test 7: combinations

C1 baseline role block: parts row, id spanning two rows, arrow and pairs row.

<table>
<tbody>
<tr><td colspan="2">C1 parts: kind text, type base</td></tr>
<tr><td width="240" rowspan="2" valign="top">

```
text-base-on-fill-primum
```

</td><td>C1 job: text on the main action fill</td></tr>
<tr><td>C1 usage: use on fill-primum</td></tr>
<tr><td align="center" valign="top"><a href="glossary.md#gh-light-mode-only"><img src="../../assets/markdowns/arrow-up.svg" width="32" alt="up"></a><a href="glossary.md#gh-dark-mode-only"><img src="../../assets/markdowns/arrow-up-white.svg" width="32" alt="up"></a></td><td>C1 pairs: <code>fill-primum</code></td></tr>
</tbody>
</table>

C2 three role blocks stacked in ONE table, each in its own tbody. Expect: each block restarts its stripes.

<table>
<tbody>
<tr><td colspan="2">C2 block 1 parts</td></tr>
<tr><td width="240" rowspan="2" valign="top">

```
fill-base
```

</td><td>C2 block 1 job</td></tr>
<tr><td>C2 block 1 usage</td></tr>
<tr><td align="center" valign="top">up</td><td>C2 block 1 pairs</td></tr>
</tbody>
<tbody>
<tr><td colspan="2">C2 block 2 parts</td></tr>
<tr><td width="240" rowspan="2" valign="top">

```
fill-raised
```

</td><td>C2 block 2 job</td></tr>
<tr><td>C2 block 2 usage</td></tr>
<tr><td align="center" valign="top">up</td><td>C2 block 2 pairs</td></tr>
</tbody>
<tbody>
<tr><td colspan="2">C2 block 3 parts</td></tr>
<tr><td width="240" rowspan="2" valign="top">

```
fill-overlay
```

</td><td>C2 block 3 job</td></tr>
<tr><td>C2 block 3 usage</td></tr>
<tr><td align="center" valign="top">up</td><td>C2 block 3 pairs</td></tr>
</tbody>
</table>

C3 everything at once: tooltip title, itemprop, math swatch, details in the pairs cell, code block.

<table>
<tbody>
<tr><td colspan="2" itemprop="text-base-on-fill-primum" title="C3 tooltip on the parts cell">C3 parts: kind text, type base</td></tr>
<tr><td width="240" rowspan="2" valign="top">

```
text-base-on-fill-primum
```

</td><td>

C3 job $\color{#336699}{\rule{24px}{12px}}$

</td></tr>
<tr><td><a id="c3-anchor" title="C3 link tooltip" href="#c3-anchor">C3 usage with an anchor</a></td></tr>
<tr><td align="center" valign="top">up</td><td>

<details><summary>C3 pairs: 3 ids</summary>

- `fill-primum`
- `fill-base`
- `fill-raised`

</details>

</td></tr>
</tbody>
</table>

C4 nested table in the pairs cell, with a code block in a nested cell.

<table>
<tbody>
<tr><td colspan="2">C4 parts</td></tr>
<tr><td width="240" rowspan="2" valign="top">

```
fill-base
```

</td><td>C4 job</td></tr>
<tr><td>C4 usage</td></tr>
<tr><td align="center" valign="top">up</td><td><table><tr><td>C4 inner r1</td><td>a</td></tr><tr><td>C4 inner r2</td><td>b</td></tr><tr><td>C4 inner r3</td><td>c</td></tr></table></td></tr>
</tbody>
</table>

C5 a whole table inside details inside a cell of another table.

<table>
<tr><td>C5 outer r1</td><td>

<details><summary>C5 open</summary>

<table><tr><td>C5 inner r1</td></tr><tr><td>C5 inner r2</td></tr></table>

</details>

</td></tr>
<tr><td>C5 outer r2</td><td>x</td></tr>
</table>

C6 the id cell and arrow cell both shaded: rows are parts, id span two, arrow span two.

<table>
<tbody>
<tr><td colspan="2">C6 parts</td></tr>
<tr><td width="240" rowspan="2" valign="top">

```
text-base-on-fill-primum
```

</td><td>C6 job</td></tr>
<tr><td>C6 usage</td></tr>
<tr><td rowspan="2" align="center" valign="top">up</td><td>C6 pairs a</td></tr>
<tr><td>C6 pairs b</td></tr>
</tbody>
</table>

C7 thead holds the parts row, tbody holds the rest. Expect: id cell on a white row, since thead does not count.

<table>
<thead>
<tr><td colspan="2">C7 parts in thead</td></tr>
</thead>
<tbody>
<tr><td width="240" rowspan="2" valign="top">

```
text-base-on-fill-primum
```

</td><td>C7 job</td></tr>
<tr><td>C7 usage</td></tr>
<tr><td align="center" valign="top">up</td><td>C7 pairs</td></tr>
</tbody>
</table>

C8 a role block as a pipe table with a link, code and details (no rowspan possible).

| id | parts | job |
|----|-------|-----|
| `text-base-on-fill-primum` | kind text, type base | text on the main action fill |
| [up](glossary.md) | <details><summary>pairs: 3 ids</summary>`fill-primum` `fill-base` `fill-raised`</details> | usage |
