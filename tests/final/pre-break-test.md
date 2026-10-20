# Pre break workarounds

GitHub hides br inside code. These try other ways to get two display lines with a one-line copy value and a copy button. Check each row: is the id on two lines, is there a copy button, and what does the button paste?

The id is text-danger-subtle-disabled-on-fill-primum-subtle-disabled, broken after the hyphen before on.

<table>
<tr><td width="120">W1 br between two code elements inside pre</td><td><pre><code>text-danger-subtle-disabled-</code><br><code>on-fill-primum-subtle-disabled</code></pre></td></tr>
<tr><td>W2 br between code and bare text inside pre</td><td><pre><code>text-danger-subtle-disabled-</code><br>on-fill-primum-subtle-disabled</pre></td></tr>
<tr><td>W3 divs inside code</td><td><pre><code><div>text-danger-subtle-disabled-</div><div>on-fill-primum-subtle-disabled</div></code></pre></td></tr>
<tr><td>W4 paragraphs inside code</td><td><pre><code><p>text-danger-subtle-disabled-</p><p>on-fill-primum-subtle-disabled</p></code></pre></td></tr>
<tr><td>W5 spans plus br inside pre, no code</td><td><pre><span>text-danger-subtle-disabled-</span><br><span>on-fill-primum-subtle-disabled</span></pre></td></tr>
<tr><td>W6 divs inside pre, no code</td><td><pre><div>text-danger-subtle-disabled-</div><div>on-fill-primum-subtle-disabled</div></pre></td></tr>
<tr><td>W7 list inside code</td><td><pre><code><ul><li>text-danger-subtle-disabled-</li><li>on-fill-primum-subtle-disabled</li></ul></code></pre></td></tr>
<tr><td>W8 hr inside code between the halves</td><td><pre><code>text-danger-subtle-disabled-<hr>on-fill-primum-subtle-disabled</code></pre></td></tr>
<tr><td>W9 the original br inside code, for reference</td><td><pre><code>text-danger-subtle-disabled-<br>on-fill-primum-subtle-disabled</code></pre></td></tr>
<tr><td>W10 fenced block for reference</td><td>

```
text-danger-subtle-disabled-on-fill-primum-subtle-disabled
```

</td></tr>
</table>
