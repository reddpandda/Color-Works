# Copy button test 2

GitHub adds a `data-snippet-clipboard-copy-content` attribute to code blocks. These cases try to supply my own value, and to put an image in the block.

For each row: does a copy button appear on hover, and what does it paste?

<table>
<tr><td>F2 own attribute, different text shown</td><td><div class="snippet-clipboard-content notranslate position-relative overflow-auto" data-snippet-clipboard-copy-content="COPIED-F2"><pre class="notranslate"><code>SHOWN-F2</code></pre></div></td></tr>
<tr><td>F3 own attribute, image only inside the block</td><td><div class="snippet-clipboard-content notranslate position-relative overflow-auto" data-snippet-clipboard-copy-content="COPIED-F3"><img src="../../assets/markdowns/arrow-up.svg" width="32" alt="F3 image"></div></td></tr>
<tr><td>F4 own attribute, pre and image in one block</td><td><div class="snippet-clipboard-content notranslate position-relative overflow-auto" data-snippet-clipboard-copy-content="COPIED-F4"><pre class="notranslate"><code>SHOWN-F4</code></pre><img src="../../assets/markdowns/arrow-up.svg" width="32" alt="F4 image"></div></td></tr>
<tr><td>F5 own attribute, plain text only</td><td><div class="snippet-clipboard-content notranslate position-relative overflow-auto" data-snippet-clipboard-copy-content="COPIED-F5">SHOWN-F5 text only</div></td></tr>
<tr><td>F6 highlight class with own attribute</td><td><div class="highlight notranslate position-relative overflow-auto" data-snippet-clipboard-copy-content="COPIED-F6"><pre>SHOWN-F6</pre></div></td></tr>
<tr><td>F7 pre with the attribute on the pre</td><td><pre data-snippet-clipboard-copy-content="COPIED-F7">SHOWN-F7</pre></td></tr>
<tr><td>F8 fenced block with image above it in the same cell</td><td><img src="../../assets/markdowns/arrow-up.svg" width="32" alt="F8 image">

```
SHOWN-F8
```

</td></tr>
</table>
