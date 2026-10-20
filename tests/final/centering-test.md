# Label centring tests

Standard layout: each block has a white description row, a shaded row with the id cell (b1) and a tall detail cell that spans down, and an empty cell c1 under the id. The id cell holds a hidden copy box on top, a label, and a spacer below. Screenshot the page and I will measure how far each label sits from the middle of b1.

<table>
<tbody>
<tr><td colspan="2">K0 baseline: spacer is an empty pre.</td></tr>
<tr><td width="240" valign="middle"><pre><code><rp>text-base-on-fill-primum</rp></code></pre><div align="center"><b>text-base-on-fill-primum</b></div><pre></pre></td><td rowspan="2" valign="top">detail<br>line<br>line<br>line<br>line<br>line<br>line<br>line</td></tr>
<tr><td></td></tr>
</tbody>
<tbody>
<tr><td colspan="2">K1 spacer is a pre holding one empty line (br).</td></tr>
<tr><td width="240" valign="middle"><pre><code><rp>text-base-on-fill-primum</rp></code></pre><div align="center"><b>text-base-on-fill-primum</b></div><pre><br></pre></td><td rowspan="2" valign="top">detail<br>line<br>line<br>line<br>line<br>line<br>line<br>line</td></tr>
<tr><td></td></tr>
</tbody>
<tbody>
<tr><td colspan="2">K2 spacer is a pre holding a non-breaking space.</td></tr>
<tr><td width="240" valign="middle"><pre><code><rp>text-base-on-fill-primum</rp></code></pre><div align="center"><b>text-base-on-fill-primum</b></div><pre>&nbsp;</pre></td><td rowspan="2" valign="top">detail<br>line<br>line<br>line<br>line<br>line<br>line<br>line</td></tr>
<tr><td></td></tr>
</tbody>
<tbody>
<tr><td colspan="2">K3 h3 label with the K1 spacer.</td></tr>
<tr><td width="240" valign="middle"><pre><code><rp>text-base-on-fill-primum</rp></code></pre><h3 align="center">text-base-on-fill-primum</h3><pre><br></pre></td><td rowspan="2" valign="top">detail<br>line<br>line<br>line<br>line<br>line<br>line<br>line</td></tr>
<tr><td></td></tr>
</tbody>
<tbody>
<tr><td colspan="2">K4 h4 label with the K1 spacer.</td></tr>
<tr><td width="240" valign="middle"><pre><code><rp>text-base-on-fill-primum</rp></code></pre><h4 align="center">text-base-on-fill-primum</h4><pre><br></pre></td><td rowspan="2" valign="top">detail<br>line<br>line<br>line<br>line<br>line<br>line<br>line</td></tr>
<tr><td></td></tr>
</tbody>
<tbody>
<tr><td colspan="2">K5 two-line label (long id broken at on) with the K1 spacer.</td></tr>
<tr><td width="240" valign="middle"><pre><code><rp>text-danger-subtle-disabled-on-fill-primum-subtle-disabled</rp></code></pre><div align="center"><b>text-danger-subtle-disabled-<br>on-fill-primum-subtle-disabled</b></div><pre><br></pre></td><td rowspan="2" valign="top">detail<br>line<br>line<br>line<br>line<br>line<br>line<br>line</td></tr>
<tr><td></td></tr>
</tbody>
<tbody>
<tr><td colspan="2">K6 thirds idea: the id cell has height 144 (three thirds of 48), valign middle, K1 spacer.</td></tr>
<tr><td width="240" height="144" valign="middle"><pre><code><rp>text-base-on-fill-primum</rp></code></pre><div align="center"><b>text-base-on-fill-primum</b></div><pre><br></pre></td><td rowspan="2" valign="top">detail<br>line<br>line<br>line<br>line<br>line<br>line<br>line</td></tr>
<tr><td></td></tr>
</tbody>
<tbody>
<tr><td colspan="2">K7 thirds idea, taller: id cell height 210, label valign middle, box on top, spacer below.</td></tr>
<tr><td width="240" height="210" valign="middle"><pre><code><rp>text-base-on-fill-primum</rp></code></pre><div align="center"><b>text-base-on-fill-primum</b></div><pre><br></pre></td><td rowspan="2" valign="top">detail<br>line<br>line<br>line<br>line<br>line<br>line<br>line</td></tr>
<tr><td></td></tr>
</tbody>
<tbody>
<tr><td colspan="2">K8 the id cell valign top, label directly under the box, no spacer. The title look.</td></tr>
<tr><td width="240" valign="top"><pre><code><rp>text-base-on-fill-primum</rp></code></pre><div align="center"><b>text-base-on-fill-primum</b></div></td><td rowspan="2" valign="top">detail<br>line<br>line<br>line<br>line<br>line<br>line<br>line</td></tr>
<tr><td></td></tr>
</tbody>
<tbody>
<tr><td colspan="2">K9 a tall detail cell (20 lines): where does the id cell and its label sit?</td></tr>
<tr><td width="240" valign="middle"><pre><code><rp>text-base-on-fill-primum</rp></code></pre><div align="center"><b>text-base-on-fill-primum</b></div><pre><br></pre></td><td rowspan="2" valign="top">detail<br>line<br>line<br>line<br>line<br>line<br>line<br>line<br>line<br>line<br>line<br>line<br>line<br>line<br>line<br>line<br>line<br>line<br>line<br>line</td></tr>
<tr><td></td></tr>
</tbody>
</table>
