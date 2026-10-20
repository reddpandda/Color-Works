# Standard layout test

The ids and pairs below are made up for the test.

L1 as described: arrow bar on top (white), then the id and label row (even, shaded), then an empty cell and a cell holding a nested table with no stripes. Pairs with is a bulleted list, 3 shown, then more. Prediction: the last row is WHITE, because it is the third row.

<table>
<tbody>
<tr><td colspan="2" align="center"><a href="glossary.md#g-text-base-on-fill-primum#gh-light-mode-only"><img src="../../assets/markdowns/arrow-up.svg" width="32" alt="up"></a><a href="glossary.md#g-text-base-on-fill-primum#gh-dark-mode-only"><img src="../../assets/markdowns/arrow-up-white.svg" width="32" alt="up"></a></td></tr>
<tr><td width="240" valign="top">

```
text-base-on-fill-primum
```

</td><td>L1 label: text on the main action fill</td></tr>
<tr><td></td><td>
<table width="100%">
<tbody><tr><td>L1 parts: kind text, type base, emphasis default, state default, on fill-primum</td></tr></tbody>
<tbody><tr><td>L1 usage: use on fill-primum. Override: none. Equivalent: none.</td></tr></tbody>
<tbody><tr><td>L1 pairs with (10):<ul><li><code>fill-primum</code></li><li><code>fill-primum-hover</code></li><li><code>fill-primum-active</code></li><li><details><summary>more (7)</summary><ul><li><code>fill-primum-selected</code></li><li><code>fill-primum-disabled</code></li><li><code>fill-primum-subtle</code></li><li><code>fill-primum-subtle-hover</code></li><li><code>fill-primum-subtle-active</code></li><li><code>fill-primum-subtle-selected</code></li><li><code>fill-primum-subtle-disabled</code></li></ul></details></li></ul></td></tr></tbody>
</table>
</td></tr>
</tbody>
</table>

L2 the same with only 3 pairs, so there is no more fold.

<table>
<tbody>
<tr><td colspan="2" align="center"><a href="glossary.md#g-fill-sunken#gh-light-mode-only"><img src="../../assets/markdowns/arrow-up.svg" width="32" alt="up"></a><a href="glossary.md#g-fill-sunken#gh-dark-mode-only"><img src="../../assets/markdowns/arrow-up-white.svg" width="32" alt="up"></a></td></tr>
<tr><td width="240" valign="top">

```
fill-sunken
```

</td><td>L2 label: recessed areas</td></tr>
<tr><td></td><td>
<table width="100%">
<tbody><tr><td>L2 parts: kind fill, type sunken</td></tr></tbody>
<tbody><tr><td>L2 usage: use for wells and inputs</td></tr></tbody>
<tbody><tr><td>L2 pairs with (3):<ul><li><code>text-base-on-fill-sunken</code></li><li><code>icon-base-on-fill-sunken</code></li><li><code>line-base-on-fill-sunken</code></li></ul></td></tr></tbody>
</table>
</td></tr>
</tbody>
</table>

L3 to get the nested-table cell shaded too: the detail cell is moved to the second row of its own tbody, with a usage bar above it as the first row. Prediction: id and label row shaded, usage bar white, detail row shaded.

<table>
<tbody>
<tr><td colspan="2" align="center"><a href="glossary.md#g-text-base-on-fill-primum#gh-light-mode-only"><img src="../../assets/markdowns/arrow-up.svg" width="32" alt="up"></a><a href="glossary.md#g-text-base-on-fill-primum#gh-dark-mode-only"><img src="../../assets/markdowns/arrow-up-white.svg" width="32" alt="up"></a></td></tr>
<tr><td width="240" valign="top">

```
text-base-on-fill-primum
```

</td><td>L3 label: text on the main action fill</td></tr>
</tbody>
<tbody>
<tr><td colspan="2">L3 usage: use on fill-primum. Override: none. Equivalent: none.</td></tr>
<tr><td></td><td>
<table width="100%">
<tbody><tr><td>L3 parts: kind text, type base, emphasis default, state default, on fill-primum</td></tr></tbody>
<tbody><tr><td>L3 pairs with (10):<ul><li><code>fill-primum</code></li><li><code>fill-primum-hover</code></li><li><code>fill-primum-active</code></li><li><details><summary>more (7)</summary><ul><li><code>fill-primum-selected</code></li><li><code>fill-primum-disabled</code></li><li><code>fill-primum-subtle</code></li><li><code>fill-primum-subtle-hover</code></li><li><code>fill-primum-subtle-active</code></li><li><code>fill-primum-subtle-selected</code></li><li><code>fill-primum-subtle-disabled</code></li></ul></details></li></ul></td></tr></tbody>
</table>
</td></tr>
</tbody>
</table>

L4 two L1 roles stacked in one table, each role in its own tbody. Prediction: both look like L1.

<table>
<tbody>
<tr><td colspan="2" align="center">L4 role 1 arrow bar</td></tr>
<tr><td width="240" valign="top">

```
fill-base
```

</td><td>L4 role 1 label: page background</td></tr>
<tr><td></td><td>
<table width="100%">
<tbody><tr><td>L4 role 1 parts</td></tr></tbody>
<tbody><tr><td>L4 role 1 pairs with (2):<ul><li><code>text-base-on-fill-base</code></li><li><code>line-base-on-fill-base</code></li></ul></td></tr></tbody>
</table>
</td></tr>
</tbody>
<tbody>
<tr><td colspan="2" align="center">L4 role 2 arrow bar</td></tr>
<tr><td width="240" valign="top">

```
fill-raised
```

</td><td>L4 role 2 label: raised cards</td></tr>
<tr><td></td><td>
<table width="100%">
<tbody><tr><td>L4 role 2 parts</td></tr></tbody>
<tbody><tr><td>L4 role 2 pairs with (2):<ul><li><code>text-base-on-fill-raised</code></li><li><code>line-base-on-fill-raised</code></li></ul></td></tr></tbody>
</table>
</td></tr>
</tbody>
</table>
