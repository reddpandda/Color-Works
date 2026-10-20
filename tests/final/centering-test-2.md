# Label centring tests, round 2

The spacer is now two lines tall, to cancel the 16px margin the box has but the spacer lacks. Predicted offsets are in each description. Screenshot it and I will measure.

<table>
<tbody>
<tr><td colspan="2">J0 bold label, spacer pre with two br. Prediction: about -1.</td></tr>
<tr><td width="240" valign="middle"><pre><code><rp>text-base-on-fill-primum</rp></code></pre><div align="center"><b>text-base-on-fill-primum</b></div><pre><br><br></pre></td><td rowspan="2" valign="top">detail<br>line<br>line<br>line<br>line<br>line<br>line<br>line</td></tr>
<tr><td></td></tr>
</tbody>
<tbody>
<tr><td colspan="2">J1 h3 label, two-br spacer. Prediction: about -5.</td></tr>
<tr><td width="240" valign="middle"><pre><code><rp>text-base-on-fill-primum</rp></code></pre><h3 align="center">text-base-on-fill-primum</h3><pre><br><br></pre></td><td rowspan="2" valign="top">detail<br>line<br>line<br>line<br>line<br>line<br>line<br>line</td></tr>
<tr><td></td></tr>
</tbody>
<tbody>
<tr><td colspan="2">J2 h4 label, two-br spacer. Prediction: about -5.</td></tr>
<tr><td width="240" valign="middle"><pre><code><rp>text-base-on-fill-primum</rp></code></pre><h4 align="center">text-base-on-fill-primum</h4><pre><br><br></pre></td><td rowspan="2" valign="top">detail<br>line<br>line<br>line<br>line<br>line<br>line<br>line</td></tr>
<tr><td></td></tr>
</tbody>
<tbody>
<tr><td colspan="2">J3 two-line bold label, two-br spacer.</td></tr>
<tr><td width="240" valign="middle"><pre><code><rp>text-danger-subtle-disabled-on-fill-primum-subtle-disabled</rp></code></pre><div align="center"><b>text-danger-subtle-disabled-<br>on-fill-primum-subtle-disabled</b></div><pre><br><br></pre></td><td rowspan="2" valign="top">detail<br>line<br>line<br>line<br>line<br>line<br>line<br>line</td></tr>
<tr><td></td></tr>
</tbody>
<tbody>
<tr><td colspan="2">J4 bold label, three-br spacer (overshoot, to bracket).</td></tr>
<tr><td width="240" valign="middle"><pre><code><rp>text-base-on-fill-primum</rp></code></pre><div align="center"><b>text-base-on-fill-primum</b></div><pre><br><br><br></pre></td><td rowspan="2" valign="top">detail<br>line<br>line<br>line<br>line<br>line<br>line<br>line</td></tr>
<tr><td></td></tr>
</tbody>
<tbody>
<tr><td colspan="2">J5 h4 label, one-br spacer plus an empty pre (about 36px extra).</td></tr>
<tr><td width="240" valign="middle"><pre><code><rp>text-base-on-fill-primum</rp></code></pre><h4 align="center">text-base-on-fill-primum</h4><pre><br></pre><pre></pre></td><td rowspan="2" valign="top">detail<br>line<br>line<br>line<br>line<br>line<br>line<br>line</td></tr>
<tr><td></td></tr>
</tbody>
<tbody>
<tr><td colspan="2">J6 valign top control: bold label under the box, no spacer.</td></tr>
<tr><td width="240" valign="top"><pre><code><rp>text-base-on-fill-primum</rp></code></pre><div align="center"><b>text-base-on-fill-primum</b></div></td><td rowspan="2" valign="top">detail<br>line<br>line<br>line<br>line<br>line<br>line<br>line</td></tr>
<tr><td></td></tr>
</tbody>
<tbody>
<tr><td colspan="2">J7 valign top control: h4 label under the box, no spacer.</td></tr>
<tr><td width="240" valign="top"><pre><code><rp>text-base-on-fill-primum</rp></code></pre><h4 align="center">text-base-on-fill-primum</h4></td><td rowspan="2" valign="top">detail<br>line<br>line<br>line<br>line<br>line<br>line<br>line</td></tr>
<tr><td></td></tr>
</tbody>
<tbody>
<tr><td colspan="2">J8 tall detail (20 lines), bold label, two-br spacer.</td></tr>
<tr><td width="240" valign="middle"><pre><code><rp>text-base-on-fill-primum</rp></code></pre><div align="center"><b>text-base-on-fill-primum</b></div><pre><br><br></pre></td><td rowspan="2" valign="top">detail<br>line<br>line<br>line<br>line<br>line<br>line<br>line<br>line<br>line<br>line<br>line<br>line<br>line<br>line<br>line<br>line<br>line<br>line<br>line</td></tr>
<tr><td></td></tr>
</tbody>
<tbody>
<tr><td colspan="2">J9 tall detail (20 lines), valign top, bold label, no spacer.</td></tr>
<tr><td width="240" valign="top"><pre><code><rp>text-base-on-fill-primum</rp></code></pre><div align="center"><b>text-base-on-fill-primum</b></div></td><td rowspan="2" valign="top">detail<br>line<br>line<br>line<br>line<br>line<br>line<br>line<br>line<br>line<br>line<br>line<br>line<br>line<br>line<br>line<br>line<br>line<br>line<br>line</td></tr>
<tr><td></td></tr>
</tbody>
</table>
