# Surface test

This README is shown on the folder page. Compare it with the same file opened directly, and in the mobile app.

S1 id and arrow block, id spans two rows:

<table>
<tr><td colspan="2">S1 parts: kind text, type base</td></tr>
<tr><td width="240" rowspan="2" valign="top">

```
text-base-on-fill-primum
```

</td><td>S1 job</td></tr>
<tr><td>S1 usage</td></tr>
<tr><td align="center" valign="top"><a href="../final/glossary.md#gh-light-mode-only"><img src="../../assets/markdowns/arrow-up.svg" width="32" alt="up"></a><a href="../final/glossary.md#gh-dark-mode-only"><img src="../../assets/markdowns/arrow-up-white.svg" width="32" alt="up"></a></td><td>

<details><summary>S1 pairs: 3 ids</summary>

- `fill-primum`
- `fill-base`
- `fill-raised`

</details>

</td></tr>
</table>

S2 colour block in a cell:

<table>
<tr><td>S2 rule block</td><td>

$\color{#336699}{\rule{40px}{20px}}$

</td></tr>
</table>

S3 tfoot first:

<table>
<tfoot><tr><td>S3 src1 foot</td></tr></tfoot>
<tbody><tr><td>S3 src2 body</td></tr><tr><td>S3 src3 body</td></tr></tbody>
</table>

S4 picture light and dark:

<picture><source media="(prefers-color-scheme: dark)" srcset="../../assets/markdowns/arrow-up-white.svg"><img src="../../assets/markdowns/arrow-up.svg" width="32" alt="S4 picture"></picture>

S5 pipe table with rowspan-free cells, escaped pipe, short row:

| a | b | c |
|:--|:-:|--:|
| left | centre | right |
| `x \| y` | only two |
| one |
