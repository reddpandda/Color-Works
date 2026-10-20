# Vertical alignment and pre tests

V1 vertical alignment. The right cell is tall (five lines). Each left cell says how it is aligned. Expect top, middle and bottom to place the text at the top, middle and bottom of its row.

<table>
<tr><td valign="top">V1 left valign top</td><td rowspan="3">right cell<br>line two<br>line three<br>line four<br>line five<br>line six<br>line seven<br>line eight<br>line nine</td></tr>
<tr><td valign="middle">V1 left valign middle</td></tr>
<tr><td valign="bottom">V1 left valign bottom</td></tr>
</table>

V2 valign set on the row (tr) instead of the cell. The cell has no valign.

<table>
<tr valign="middle"><td>V2 tr valign middle</td><td>tall<br>cell<br>four<br>lines</td></tr>
<tr valign="bottom"><td>V2 tr valign bottom</td><td>tall<br>cell<br>four<br>lines</td></tr>
</table>

V3 a fenced code block in a tall row, cell valign middle on the left.

<table>
<tr><td width="240" valign="middle">

```
fill-raised
```

</td><td>V3 tall right cell<br>line two<br>line three<br>line four<br>line five<br>line six</td></tr>
</table>

V4 the nested table in a rowspan cell centred vertically.

<table>
<tr><td width="240">V4 left cell<br>one<br>two<br>three<br>four<br>five<br>six<br>seven<br>eight</td><td valign="middle"><table width="100%"><tbody><tr><td>V4 nested label</td></tr></tbody><tbody><tr><td>V4 nested parts</td></tr></tbody></table></td></tr>
</table>

V5 label rows in a nested table with a tall cell beside it, valign middle on the label cell.

<table width="100%">
<tbody><tr><td valign="middle">V5 label</td><td>tall<br>cell<br>four<br>lines</td></tr></tbody>
</table>

Z1 pre and code with a br in the middle. Display should be two lines. The copy value is what matters.

<table>
<tr><td>Z1</td><td><pre><code>text-danger-subtle-disabled<br>on-fill-primum-subtle-disabled</code></pre></td></tr>
<tr><td>Z2 bare pre with br</td><td><pre>text-danger-subtle-disabled<br>on-fill-primum-subtle-disabled</pre></td></tr>
<tr><td>Z3 wbr</td><td><pre><code>text-danger-subtle-disabled<wbr>on-fill-primum-subtle-disabled</code></pre></td></tr>
<tr><td>Z4 soft hyphen</td><td><pre><code>text-danger-subtle-disabled&shy;on-fill-primum-subtle-disabled</code></pre></td></tr>
<tr><td>Z5 zero width space</td><td><pre><code>text-danger-subtle-disabled&#8203;on-fill-primum-subtle-disabled</code></pre></td></tr>
<tr><td>Z6 pre with wrap attribute</td><td><pre wrap><code>text-danger-subtle-disabled-on-fill-primum-subtle-disabled</code></pre></td></tr>
<tr><td>Z7 pre with width attribute</td><td><pre width="20" cols="20"><code>text-danger-subtle-disabled-on-fill-primum-subtle-disabled</code></pre></td></tr>
<tr><td>Z8 spans inside code</td><td><pre><code><b>text-danger-subtle-disabled</b><br><i>on-fill-primum-subtle-disabled</i></code></pre></td></tr>
<tr><td>Z9 two br and a trailing br</td><td><pre><code>text-danger<br><br>subtle-disabled<br></code></pre></td></tr>
<tr><td>Z10 br with clear attribute</td><td><pre><code>text-danger<br clear="all">subtle-disabled</code></pre></td></tr>
<tr><td>Z11 plain newline inside the code for comparison</td><td><pre><code>text-danger-subtle-disabled
on-fill-primum-subtle-disabled</code></pre></td></tr>
</table>
