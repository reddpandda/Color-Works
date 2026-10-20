# Worst-case combined test

Every block has the standard layout, the hidden copy box, a long id, an illustration slot (214 by 200, the arrow as a stand-in) in c1 and a detail cell with a long label, long parts and 15 pairs. Middle-aligned blocks (the J8 cousin: box, label, two-line spacer) and top-aligned blocks (the J7 cousin: box and label only) are paired, each with the pairs list closed and open. W5 and W6 are the easy cases for comparison.

<table>
<tbody>
<tr><td colspan="2" align="center">W1 middle, long id, illustration, pairs closed</td></tr>
<tr><td width="240" valign="middle"><pre><code><rp>text-danger-subtle-disabled-hover-on-fill-primum-subtle-disabled</rp></code></pre><div align="center"><b>text-danger-subtle-disabled-hover-<br>on-fill-primum-subtle-disabled</b></div><pre><br><br></pre></td><td rowspan="2" valign="top">
<table width="100%">
<tbody><tr><td>W1 label: Danger text on the primary fill when a subtle, disabled, hovered state needs a very long explanatory label that wraps onto several lines of the detail cell</td></tr></tbody>
<tbody><tr><td>W1 parts: kind text, type danger, emphasis subtle, state disabled, state hover, on fill primum, emphasis subtle, state disabled</td></tr></tbody>
<tbody><tr><td>W1 pairs with (15):<ul><li><code>text-danger-subtle-disabled-hover-on-fill-primum-subtle-disabled</code></li><li><code>icon-danger-subtle-disabled-hover-on-fill-primum-subtle-disabled</code></li><li><code>line-danger-subtle-disabled-hover-on-fill-primum-subtle-disabled</code></li><li><details><summary>more (12)</summary><ul><li><code>text-danger-subtle-disabled-hover-on-fill-raised-subtle-disabled</code></li><li><code>icon-danger-subtle-disabled-hover-on-fill-raised-subtle-disabled</code></li><li><code>line-danger-subtle-disabled-hover-on-fill-raised-subtle-disabled</code></li><li><code>text-danger-subtle-disabled-hover-on-fill-sunken-subtle-disabled</code></li><li><code>icon-danger-subtle-disabled-hover-on-fill-sunken-subtle-disabled</code></li><li><code>line-danger-subtle-disabled-hover-on-fill-sunken-subtle-disabled</code></li><li><code>text-danger-subtle-disabled-hover-on-fill-primum-subtle-disabled</code></li><li><code>icon-danger-subtle-disabled-hover-on-fill-primum-subtle-disabled</code></li><li><code>line-danger-subtle-disabled-hover-on-fill-primum-subtle-disabled</code></li><li><code>text-danger-subtle-disabled-hover-on-fill-secundum-subtle-disabled</code></li><li><code>icon-danger-subtle-disabled-hover-on-fill-secundum-subtle-disabled</code></li><li><code>line-danger-subtle-disabled-hover-on-fill-secundum-subtle-disabled</code></li></ul></details></li></ul></td></tr></tbody>
</table>
</td></tr>
<tr><td align="center" valign="top"><img src="../../assets/markdowns/arrow-up.svg" width="214" height="200" alt="illustration 214 by 200"></td></tr>
</tbody>
<tbody>
<tr><td colspan="2" align="center">W2 middle, long id, illustration, pairs OPEN</td></tr>
<tr><td width="240" valign="middle"><pre><code><rp>text-danger-subtle-disabled-hover-on-fill-primum-subtle-disabled</rp></code></pre><div align="center"><b>text-danger-subtle-disabled-hover-<br>on-fill-primum-subtle-disabled</b></div><pre><br><br></pre></td><td rowspan="2" valign="top">
<table width="100%">
<tbody><tr><td>W2 label: Danger text on the primary fill when a subtle, disabled, hovered state needs a very long explanatory label that wraps onto several lines of the detail cell</td></tr></tbody>
<tbody><tr><td>W2 parts: kind text, type danger, emphasis subtle, state disabled, state hover, on fill primum, emphasis subtle, state disabled</td></tr></tbody>
<tbody><tr><td>W2 pairs with (15):<ul><li><code>text-danger-subtle-disabled-hover-on-fill-primum-subtle-disabled</code></li><li><code>icon-danger-subtle-disabled-hover-on-fill-primum-subtle-disabled</code></li><li><code>line-danger-subtle-disabled-hover-on-fill-primum-subtle-disabled</code></li><li><details open><summary>more (12)</summary><ul><li><code>text-danger-subtle-disabled-hover-on-fill-raised-subtle-disabled</code></li><li><code>icon-danger-subtle-disabled-hover-on-fill-raised-subtle-disabled</code></li><li><code>line-danger-subtle-disabled-hover-on-fill-raised-subtle-disabled</code></li><li><code>text-danger-subtle-disabled-hover-on-fill-sunken-subtle-disabled</code></li><li><code>icon-danger-subtle-disabled-hover-on-fill-sunken-subtle-disabled</code></li><li><code>line-danger-subtle-disabled-hover-on-fill-sunken-subtle-disabled</code></li><li><code>text-danger-subtle-disabled-hover-on-fill-primum-subtle-disabled</code></li><li><code>icon-danger-subtle-disabled-hover-on-fill-primum-subtle-disabled</code></li><li><code>line-danger-subtle-disabled-hover-on-fill-primum-subtle-disabled</code></li><li><code>text-danger-subtle-disabled-hover-on-fill-secundum-subtle-disabled</code></li><li><code>icon-danger-subtle-disabled-hover-on-fill-secundum-subtle-disabled</code></li><li><code>line-danger-subtle-disabled-hover-on-fill-secundum-subtle-disabled</code></li></ul></details></li></ul></td></tr></tbody>
</table>
</td></tr>
<tr><td align="center" valign="top"><img src="../../assets/markdowns/arrow-up.svg" width="214" height="200" alt="illustration 214 by 200"></td></tr>
</tbody>
<tbody>
<tr><td colspan="2" align="center">W3 top, long id, illustration, pairs closed</td></tr>
<tr><td width="240" valign="top"><pre><code><rp>text-danger-subtle-disabled-hover-on-fill-primum-subtle-disabled</rp></code></pre><div align="center"><b>text-danger-subtle-disabled-hover-<br>on-fill-primum-subtle-disabled</b></div></td><td rowspan="2" valign="top">
<table width="100%">
<tbody><tr><td>W3 label: Danger text on the primary fill when a subtle, disabled, hovered state needs a very long explanatory label that wraps onto several lines of the detail cell</td></tr></tbody>
<tbody><tr><td>W3 parts: kind text, type danger, emphasis subtle, state disabled, state hover, on fill primum, emphasis subtle, state disabled</td></tr></tbody>
<tbody><tr><td>W3 pairs with (15):<ul><li><code>text-danger-subtle-disabled-hover-on-fill-primum-subtle-disabled</code></li><li><code>icon-danger-subtle-disabled-hover-on-fill-primum-subtle-disabled</code></li><li><code>line-danger-subtle-disabled-hover-on-fill-primum-subtle-disabled</code></li><li><details><summary>more (12)</summary><ul><li><code>text-danger-subtle-disabled-hover-on-fill-raised-subtle-disabled</code></li><li><code>icon-danger-subtle-disabled-hover-on-fill-raised-subtle-disabled</code></li><li><code>line-danger-subtle-disabled-hover-on-fill-raised-subtle-disabled</code></li><li><code>text-danger-subtle-disabled-hover-on-fill-sunken-subtle-disabled</code></li><li><code>icon-danger-subtle-disabled-hover-on-fill-sunken-subtle-disabled</code></li><li><code>line-danger-subtle-disabled-hover-on-fill-sunken-subtle-disabled</code></li><li><code>text-danger-subtle-disabled-hover-on-fill-primum-subtle-disabled</code></li><li><code>icon-danger-subtle-disabled-hover-on-fill-primum-subtle-disabled</code></li><li><code>line-danger-subtle-disabled-hover-on-fill-primum-subtle-disabled</code></li><li><code>text-danger-subtle-disabled-hover-on-fill-secundum-subtle-disabled</code></li><li><code>icon-danger-subtle-disabled-hover-on-fill-secundum-subtle-disabled</code></li><li><code>line-danger-subtle-disabled-hover-on-fill-secundum-subtle-disabled</code></li></ul></details></li></ul></td></tr></tbody>
</table>
</td></tr>
<tr><td align="center" valign="top"><img src="../../assets/markdowns/arrow-up.svg" width="214" height="200" alt="illustration 214 by 200"></td></tr>
</tbody>
<tbody>
<tr><td colspan="2" align="center">W4 top, long id, illustration, pairs OPEN</td></tr>
<tr><td width="240" valign="top"><pre><code><rp>text-danger-subtle-disabled-hover-on-fill-primum-subtle-disabled</rp></code></pre><div align="center"><b>text-danger-subtle-disabled-hover-<br>on-fill-primum-subtle-disabled</b></div></td><td rowspan="2" valign="top">
<table width="100%">
<tbody><tr><td>W4 label: Danger text on the primary fill when a subtle, disabled, hovered state needs a very long explanatory label that wraps onto several lines of the detail cell</td></tr></tbody>
<tbody><tr><td>W4 parts: kind text, type danger, emphasis subtle, state disabled, state hover, on fill primum, emphasis subtle, state disabled</td></tr></tbody>
<tbody><tr><td>W4 pairs with (15):<ul><li><code>text-danger-subtle-disabled-hover-on-fill-primum-subtle-disabled</code></li><li><code>icon-danger-subtle-disabled-hover-on-fill-primum-subtle-disabled</code></li><li><code>line-danger-subtle-disabled-hover-on-fill-primum-subtle-disabled</code></li><li><details open><summary>more (12)</summary><ul><li><code>text-danger-subtle-disabled-hover-on-fill-raised-subtle-disabled</code></li><li><code>icon-danger-subtle-disabled-hover-on-fill-raised-subtle-disabled</code></li><li><code>line-danger-subtle-disabled-hover-on-fill-raised-subtle-disabled</code></li><li><code>text-danger-subtle-disabled-hover-on-fill-sunken-subtle-disabled</code></li><li><code>icon-danger-subtle-disabled-hover-on-fill-sunken-subtle-disabled</code></li><li><code>line-danger-subtle-disabled-hover-on-fill-sunken-subtle-disabled</code></li><li><code>text-danger-subtle-disabled-hover-on-fill-primum-subtle-disabled</code></li><li><code>icon-danger-subtle-disabled-hover-on-fill-primum-subtle-disabled</code></li><li><code>line-danger-subtle-disabled-hover-on-fill-primum-subtle-disabled</code></li><li><code>text-danger-subtle-disabled-hover-on-fill-secundum-subtle-disabled</code></li><li><code>icon-danger-subtle-disabled-hover-on-fill-secundum-subtle-disabled</code></li><li><code>line-danger-subtle-disabled-hover-on-fill-secundum-subtle-disabled</code></li></ul></details></li></ul></td></tr></tbody>
</table>
</td></tr>
<tr><td align="center" valign="top"><img src="../../assets/markdowns/arrow-up.svg" width="214" height="200" alt="illustration 214 by 200"></td></tr>
</tbody>
<tbody>
<tr><td colspan="2" align="center">W5 middle, short id, no illustration, 2 pairs (easy case)</td></tr>
<tr><td width="240" valign="middle"><pre><code><rp>fill-raised</rp></code></pre><div align="center"><b>fill-raised</b></div><pre><br><br></pre></td><td rowspan="2" valign="top">
<table width="100%">
<tbody><tr><td>W5 label: raised cards</td></tr></tbody>
<tbody><tr><td>W5 parts: kind fill, type raised</td></tr></tbody>
<tbody><tr><td>W5 pairs with (2):<ul><li><code>text-base-on-fill-raised</code></li><li><code>line-base-on-fill-raised</code></li></ul></td></tr></tbody>
</table>
</td></tr>
<tr><td></td></tr>
</tbody>
<tbody>
<tr><td colspan="2" align="center">W6 middle, short id, illustration, 3 pairs and more (6), closed (typical case)</td></tr>
<tr><td width="240" valign="middle"><pre><code><rp>fill-raised</rp></code></pre><div align="center"><b>fill-raised</b></div><pre><br><br></pre></td><td rowspan="2" valign="top">
<table width="100%">
<tbody><tr><td>W6 label: raised cards</td></tr></tbody>
<tbody><tr><td>W6 parts: kind fill, type raised</td></tr></tbody>
<tbody><tr><td>W6 pairs with (9):<ul><li><code>text-danger-subtle-disabled-hover-on-fill-primum-subtle-disabled</code></li><li><code>icon-danger-subtle-disabled-hover-on-fill-primum-subtle-disabled</code></li><li><code>line-danger-subtle-disabled-hover-on-fill-primum-subtle-disabled</code></li><li><details><summary>more (6)</summary><ul><li><code>text-danger-subtle-disabled-hover-on-fill-raised-subtle-disabled</code></li><li><code>icon-danger-subtle-disabled-hover-on-fill-raised-subtle-disabled</code></li><li><code>line-danger-subtle-disabled-hover-on-fill-raised-subtle-disabled</code></li><li><code>text-danger-subtle-disabled-hover-on-fill-sunken-subtle-disabled</code></li><li><code>icon-danger-subtle-disabled-hover-on-fill-sunken-subtle-disabled</code></li><li><code>line-danger-subtle-disabled-hover-on-fill-sunken-subtle-disabled</code></li></ul></details></li></ul></td></tr></tbody>
</table>
</td></tr>
<tr><td align="center" valign="top"><img src="../../assets/markdowns/arrow-up.svg" width="214" height="200" alt="illustration 214 by 200"></td></tr>
</tbody>
<tbody>
<tr><td colspan="2" align="center">W7 top, short id, illustration, 3 pairs and more (6), closed (typical case)</td></tr>
<tr><td width="240" valign="top"><pre><code><rp>fill-raised</rp></code></pre><div align="center"><b>fill-raised</b></div></td><td rowspan="2" valign="top">
<table width="100%">
<tbody><tr><td>W7 label: raised cards</td></tr></tbody>
<tbody><tr><td>W7 parts: kind fill, type raised</td></tr></tbody>
<tbody><tr><td>W7 pairs with (9):<ul><li><code>text-danger-subtle-disabled-hover-on-fill-primum-subtle-disabled</code></li><li><code>icon-danger-subtle-disabled-hover-on-fill-primum-subtle-disabled</code></li><li><code>line-danger-subtle-disabled-hover-on-fill-primum-subtle-disabled</code></li><li><details><summary>more (6)</summary><ul><li><code>text-danger-subtle-disabled-hover-on-fill-raised-subtle-disabled</code></li><li><code>icon-danger-subtle-disabled-hover-on-fill-raised-subtle-disabled</code></li><li><code>line-danger-subtle-disabled-hover-on-fill-raised-subtle-disabled</code></li><li><code>text-danger-subtle-disabled-hover-on-fill-sunken-subtle-disabled</code></li><li><code>icon-danger-subtle-disabled-hover-on-fill-sunken-subtle-disabled</code></li><li><code>line-danger-subtle-disabled-hover-on-fill-sunken-subtle-disabled</code></li></ul></details></li></ul></td></tr></tbody>
</table>
</td></tr>
<tr><td align="center" valign="top"><img src="../../assets/markdowns/arrow-up.svg" width="214" height="200" alt="illustration 214 by 200"></td></tr>
</tbody>
</table>
