# Tall cell layout test

Goal: only the id cell (with the copy button) is shaded, everything else is white. The arrow sits above the id. The right side is one tall cell holding a nested table.

B1 nested table with one tbody per row (all white), 3 pairs shown in full.

<table>
<tbody>
<tr>
<td width="240" align="center" valign="top"><a href="glossary.md#g-text-base-on-fill-primum#gh-light-mode-only"><img src="../../assets/markdowns/arrow-up.svg" width="32" alt="up"></a><a href="glossary.md#g-text-base-on-fill-primum#gh-dark-mode-only"><img src="../../assets/markdowns/arrow-up-white.svg" width="32" alt="up"></a></td>
<td rowspan="2" valign="top">
<table width="100%">
<tbody><tr><td>B1 parts: kind text, type base</td></tr></tbody>
<tbody><tr><td>B1 job: text on the main action fill</td></tr></tbody>
<tbody><tr><td>B1 usage: use on fill-primum</td></tr></tbody>
<tbody><tr><td>B1 pairs: <code>fill-primum</code> <code>fill-base</code> <code>fill-raised</code></td></tr></tbody>
</table>
</td>
</tr>
<tr>
<td valign="top">

```
text-base-on-fill-primum
```

</td>
</tr>
</tbody>
</table>

B2 same layout, 12 pairs: first 5 shown, the rest behind a more fold.

<table>
<tbody>
<tr>
<td width="240" align="center" valign="top"><a href="glossary.md#g-fill-base#gh-light-mode-only"><img src="../../assets/markdowns/arrow-up.svg" width="32" alt="up"></a><a href="glossary.md#g-fill-base#gh-dark-mode-only"><img src="../../assets/markdowns/arrow-up-white.svg" width="32" alt="up"></a></td>
<td rowspan="2" valign="top">
<table width="100%">
<tbody><tr><td>B2 parts: kind fill, type base</td></tr></tbody>
<tbody><tr><td>B2 job: the page background</td></tr></tbody>
<tbody><tr><td>B2 usage: use for the page surface</td></tr></tbody>
<tbody><tr><td>B2 pairs: <code>text-base-on-fill-base</code> <code>text-link-on-fill-base</code> <code>text-placeholder-on-fill-base</code> <code>icon-base-on-fill-base</code> <code>line-base-on-fill-base</code> <details><summary>more (7)</summary><code>text-primum-on-fill-base</code> <code>text-secundum-on-fill-base</code> <code>text-tertium-on-fill-base</code> <code>text-quartum-on-fill-base</code> <code>text-danger-on-fill-base</code> <code>text-success-on-fill-base</code> <code>text-warning-on-fill-base</code></details></td></tr></tbody>
</table>
</td>
</tr>
<tr>
<td valign="top">

```
fill-base
```

</td>
</tr>
</tbody>
</table>

B3 for comparison: the nested table without separate tbody groups, so it has its own stripes.

<table>
<tbody>
<tr>
<td width="240" align="center" valign="top">up</td>
<td rowspan="2" valign="top">
<table width="100%">
<tr><td>B3 parts: kind text, type base</td></tr>
<tr><td>B3 job: text on the main action fill</td></tr>
<tr><td>B3 usage: use on fill-primum</td></tr>
<tr><td>B3 pairs: <code>fill-primum</code></td></tr>
</table>
</td>
</tr>
<tr>
<td valign="top">

```
text-base-on-fill-primum
```

</td>
</tr>
</tbody>
</table>

B4 for comparison: no nested table, the right cell is plain lines.

<table>
<tbody>
<tr>
<td width="240" align="center" valign="top">up</td>
<td rowspan="2" valign="top">B4 parts: kind text, type base<br>B4 job: text on the main action fill<br>B4 usage: use on fill-primum<br>B4 pairs: <code>fill-primum</code></td>
</tr>
<tr>
<td valign="top">

```
text-base-on-fill-primum
```

</td>
</tr>
</tbody>
</table>

B5 two roles in one table, each in its own tbody. Expect: both id cells shaded.

<table>
<tbody>
<tr>
<td width="240" align="center" valign="top">up</td>
<td rowspan="2" valign="top">
<table width="100%">
<tbody><tr><td>B5 role 1 parts</td></tr></tbody>
<tbody><tr><td>B5 role 1 job</td></tr></tbody>
<tbody><tr><td>B5 role 1 pairs: <code>fill-primum</code></td></tr></tbody>
</table>
</td>
</tr>
<tr>
<td valign="top">

```
text-base-on-fill-primum
```

</td>
</tr>
</tbody>
<tbody>
<tr>
<td width="240" align="center" valign="top">up</td>
<td rowspan="2" valign="top">
<table width="100%">
<tbody><tr><td>B5 role 2 parts</td></tr></tbody>
<tbody><tr><td>B5 role 2 job</td></tr></tbody>
<tbody><tr><td>B5 role 2 pairs: <code>fill-base</code></td></tr></tbody>
</table>
</td>
</tr>
<tr>
<td valign="top">

```
text-base-selected-on-fill-base
```

</td>
</tr>
</tbody>
</table>
