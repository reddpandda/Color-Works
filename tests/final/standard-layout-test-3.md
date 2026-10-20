# Standard layout test 3

Grid: row a is the arrow bar (a1 and a2 merged). Row b has the id (b1) and the detail cell (b2). Row c has an empty cell (c1) and the detail cell continues down (b2 and c2 merged). The ids and pairs are made up.

S1 one block with 10 pairs: 3 shown, then more (7).

<table>
<tbody>
<tr><td colspan="2" align="center"><a href="glossary.md#g-text-base-on-fill-primum#gh-light-mode-only"><img src="../../assets/markdowns/arrow-up.svg" width="32" alt="up"></a><a href="glossary.md#g-text-base-on-fill-primum#gh-dark-mode-only"><img src="../../assets/markdowns/arrow-up-white.svg" width="32" alt="up"></a></td></tr>
<tr><td width="240" valign="top">

```
text-base-on-fill-primum
```

</td><td rowspan="2" valign="top">
<table width="100%">
<tbody><tr><td>S1 label: text on the main action fill</td></tr></tbody>
<tbody><tr><td>S1 parts: kind text, type base, emphasis default, state default, on fill-primum</td></tr></tbody>
<tbody><tr><td>S1 usage: use on fill-primum. Override: none. Equivalent: none.</td></tr></tbody>
<tbody><tr><td>S1 pairs with (10):<ul><li><code>fill-primum</code></li><li><code>fill-primum-hover</code></li><li><code>fill-primum-active</code></li><li><details><summary>more (7)</summary><ul><li><code>fill-primum-selected</code></li><li><code>fill-primum-disabled</code></li><li><code>fill-primum-subtle</code></li><li><code>fill-primum-subtle-hover</code></li><li><code>fill-primum-subtle-active</code></li><li><code>fill-primum-subtle-selected</code></li><li><code>fill-primum-subtle-disabled</code></li></ul></details></li></ul></td></tr></tbody>
</table>
</td></tr>
<tr><td></td></tr>
</tbody>
</table>

S2 three blocks in ONE table, each block in its own tbody. Prediction: each looks like S1.

<table>
<tbody>
<tr><td colspan="2" align="center"><a href="glossary.md#g-fill-base#gh-light-mode-only"><img src="../../assets/markdowns/arrow-up.svg" width="32" alt="up"></a><a href="glossary.md#g-fill-base#gh-dark-mode-only"><img src="../../assets/markdowns/arrow-up-white.svg" width="32" alt="up"></a></td></tr>
<tr><td width="240" valign="top">

```
fill-base
```

</td><td rowspan="2" valign="top">
<table width="100%">
<tbody><tr><td>S2 block 1 label: page background</td></tr></tbody>
<tbody><tr><td>S2 block 1 parts: kind fill, type base</td></tr></tbody>
<tbody><tr><td>S2 block 1 pairs with (3):<ul><li><code>text-base-on-fill-base</code></li><li><code>icon-base-on-fill-base</code></li><li><code>line-base-on-fill-base</code></li></ul></td></tr></tbody>
</table>
</td></tr>
<tr><td></td></tr>
</tbody>
<tbody>
<tr><td colspan="2" align="center"><a href="glossary.md#g-fill-raised#gh-light-mode-only"><img src="../../assets/markdowns/arrow-up.svg" width="32" alt="up"></a><a href="glossary.md#g-fill-raised#gh-dark-mode-only"><img src="../../assets/markdowns/arrow-up-white.svg" width="32" alt="up"></a></td></tr>
<tr><td width="240" valign="top">

```
fill-raised
```

</td><td rowspan="2" valign="top">
<table width="100%">
<tbody><tr><td>S2 block 2 label: raised cards</td></tr></tbody>
<tbody><tr><td>S2 block 2 parts: kind fill, type raised</td></tr></tbody>
<tbody><tr><td>S2 block 2 pairs with (2):<ul><li><code>text-base-on-fill-raised</code></li><li><code>line-base-on-fill-raised</code></li></ul></td></tr></tbody>
</table>
</td></tr>
<tr><td></td></tr>
</tbody>
<tbody>
<tr><td colspan="2" align="center"><a href="glossary.md#g-fill-overlay#gh-light-mode-only"><img src="../../assets/markdowns/arrow-up.svg" width="32" alt="up"></a><a href="glossary.md#g-fill-overlay#gh-dark-mode-only"><img src="../../assets/markdowns/arrow-up-white.svg" width="32" alt="up"></a></td></tr>
<tr><td width="240" valign="top">

```
fill-overlay
```

</td><td rowspan="2" valign="top">
<table width="100%">
<tbody><tr><td>S2 block 3 label: floating panels</td></tr></tbody>
<tbody><tr><td>S2 block 3 parts: kind fill, type overlay</td></tr></tbody>
<tbody><tr><td>S2 block 3 pairs with (2):<ul><li><code>text-base-on-fill-overlay</code></li><li><code>line-base-on-fill-overlay</code></li></ul></td></tr></tbody>
</table>
</td></tr>
<tr><td></td></tr>
</tbody>
</table>

S3 control: the same three blocks all inside ONE tbody. Prediction: the stripes drift, so block 2 is shaded on the wrong rows.

<table>
<tbody>
<tr><td colspan="2" align="center">S3 block 1 arrow bar</td></tr>
<tr><td width="240" valign="top">

```
fill-base
```

</td><td rowspan="2" valign="top">S3 block 1 detail cell</td></tr>
<tr><td></td></tr>
<tr><td colspan="2" align="center">S3 block 2 arrow bar</td></tr>
<tr><td width="240" valign="top">

```
fill-raised
```

</td><td rowspan="2" valign="top">S3 block 2 detail cell</td></tr>
<tr><td></td></tr>
<tr><td colspan="2" align="center">S3 block 3 arrow bar</td></tr>
<tr><td width="240" valign="top">

```
fill-overlay
```

</td><td rowspan="2" valign="top">S3 block 3 detail cell</td></tr>
<tr><td></td></tr>
</tbody>
</table>
