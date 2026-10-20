# Hidden copy payload tests

Each block is its own tbody in one table: a white description row, then a shaded row with the id cell on the left and a tall detail cell on the right. Look at the id cell: can you see a box? Where is the copy icon? Where is the label? What does the button paste?

<table>
<tbody>
<tr><td colspan="2">H1 hidden code block only, cell valign top. Expect: no visible text, only the copy icon, and a small empty box.</td></tr>
<tr><td width="240" valign="top"><pre><code><rp>text-base-on-fill-primum</rp></code></pre></td><td>detail<br>line<br>line<br>line<br>line<br>line</td></tr>
</tbody>
<tbody>
<tr><td colspan="2">H2 hidden box, then a bold label under it, cell valign middle.</td></tr>
<tr><td width="240" valign="middle"><pre><code><rp>text-base-on-fill-primum</rp></code></pre><b>text-base-on-fill-primum</b></td><td>detail<br>line<br>line<br>line<br>line<br>line</td></tr>
</tbody>
<tbody>
<tr><td colspan="2">H3 symmetrical: hidden box with the button, bold label, empty pre as a spacer. Cell valign middle. Is the label centred in the cell?</td></tr>
<tr><td width="240" valign="middle"><pre><code><rp>text-base-on-fill-primum</rp></code></pre><div align="center"><b>text-base-on-fill-primum</b></div><pre></pre></td><td>detail<br>line<br>line<br>line<br>line<br>line</td></tr>
</tbody>
<tbody>
<tr><td colspan="2">H4 the long id as a label broken at on with br, centred, symmetrical. The button should paste the id on one line.</td></tr>
<tr><td width="240" valign="middle"><pre><code><rp>text-danger-subtle-disabled-on-fill-primum-subtle-disabled</rp></code></pre><div align="center"><b>text-danger-subtle-disabled-<br>on-fill-primum-subtle-disabled</b></div><pre></pre></td><td>detail<br>line<br>line<br>line<br>line<br>line</td></tr>
</tbody>
<tbody>
<tr><td colspan="2">H5 label as an h3 heading, symmetrical.</td></tr>
<tr><td width="240" valign="middle"><pre><code><rp>text-base-on-fill-primum</rp></code></pre><h3 align="center">text-base-on-fill-primum</h3><pre></pre></td><td>detail<br>line<br>line<br>line<br>line<br>line</td></tr>
</tbody>
<tbody>
<tr><td colspan="2">H6 label as an h4 heading, symmetrical.</td></tr>
<tr><td width="240" valign="middle"><pre><code><rp>text-base-on-fill-primum</rp></code></pre><h4 align="center">text-base-on-fill-primum</h4><pre></pre></td><td>detail<br>line<br>line<br>line<br>line<br>line</td></tr>
</tbody>
<tbody>
<tr><td colspan="2">H7 label as an image (stand-in for an svg label), centred, symmetrical.</td></tr>
<tr><td width="240" valign="middle"><pre><code><rp>text-base-on-fill-primum</rp></code></pre><div align="center"><img src="../../assets/markdowns/arrow-up.svg" width="60" alt="H7 svg label"></div><pre></pre></td><td>detail<br>line<br>line<br>line<br>line<br>line</td></tr>
</tbody>
<tbody>
<tr><td colspan="2">H8 the label image INSIDE the box, with the id hidden by rp next to it. The box is the label.</td></tr>
<tr><td width="240" valign="top"><pre><code><rp>text-base-on-fill-primum</rp><div align="center"><img src="../../assets/markdowns/arrow-up.svg" width="60" alt="H8 svg label in box"></div></code></pre></td><td>detail<br>line<br>line<br>line<br>line<br>line</td></tr>
</tbody>
<tbody>
<tr><td colspan="2">H9 the label text INSIDE the box as a div (visible), plus hidden rp text. Expect the copy value to hold both.</td></tr>
<tr><td width="240" valign="top"><pre><code><rp>text-base-on-fill-primum</rp><div>H9 visible label</div></code></pre></td><td>detail<br>line<br>line<br>line<br>line<br>line</td></tr>
</tbody>
<tbody>
<tr><td colspan="2">H10 hidden box on a WHITE row (this block has no description row above it). Expect a visible grey strip.</td></tr>
</tbody>
<tbody>
<tr><td width="240" valign="top"><pre><code><rp>text-base-on-fill-primum</rp></code></pre></td><td>H10 white row detail<br>line<br>line</td></tr>
</tbody>
<tbody>
<tr><td colspan="2">H11 rp directly in pre, no code element.</td></tr>
<tr><td width="240" valign="top"><pre><rp>text-base-on-fill-primum</rp></pre></td><td>detail<br>line<br>line</td></tr>
</tbody>
<tbody>
<tr><td colspan="2">H12 a nested table in the cell: row 1 holds the hidden box (valign top), row 2 holds the label (valign middle), table height 100 percent.</td></tr>
<tr><td width="240" valign="top"><table width="100%" height="100%"><tr><td valign="top"><pre><code><rp>text-base-on-fill-primum</rp></code></pre></td></tr><tr><td valign="middle" align="center"><b>text-base-on-fill-primum</b></td></tr></table></td><td>detail<br>line<br>line<br>line<br>line<br>line</td></tr>
</tbody>
<tbody>
<tr><td colspan="2">H13 for comparison: the normal fenced block.</td></tr>
<tr><td width="240" valign="top">

```
text-base-on-fill-primum
```

</td><td>detail<br>line<br>line</td></tr>
</tbody>
</table>
