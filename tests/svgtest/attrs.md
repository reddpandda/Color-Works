# attrs test

Elements with ids starting e- are read from the DOM after render.

<div id="e-div" style="display:flex;color:red;width:50%;margin:10px;float:left;position:absolute;background:url(x);padding:5px;border:1px solid red;font-size:2em" title="t" aria-label="a" data-x="1" role="note" lang="fr" dir="rtl" class="x d-none" tabindex="0" hidden onclick="1" draggable="true" contenteditable="true" translate="no" accesskey="k" itemprop="p" slot="s" popover>div text</div>

<p id="e-p" style="color:red" title="tip" aria-label="al">p text</p>

<p id="e-p-upper" STYLE="color:red">upper</p>

<p id="e-p-sq" style='color:red'>single</p>

<p id="e-p-nq" style=color:red>unquoted</p>

<p id="e-p-sp" style = "color:red">spaced</p>

inline run: <span id="e-span" style="color:red" title="tip" aria-label="al">span</span> <a id="e-a" href="https://example.com" style="color:red" title="tip" aria-label="al">a</a> <kbd id="e-kbd" style="color:red" title="tip">kbd</kbd> <sub id="e-sub" style="color:red" title="tip">sub</sub> <sup id="e-sup" style="color:red" title="tip">sup</sup> <code id="e-code" style="color:red" title="tip">code</code> <b id="e-b" style="color:red" title="tip">b</b> <i id="e-i" style="color:red" title="tip">i</i> <em id="e-em" style="color:red" title="tip">em</em> <strong id="e-strong" style="color:red" title="tip">strong</strong> <ins id="e-ins" style="color:red" title="tip">ins</ins> <del id="e-del" style="color:red" title="tip">del</del> <mark id="e-mark" style="color:red" title="tip">mark</mark> <small id="e-small" style="color:red" title="tip">small</small> <abbr id="e-abbr" style="color:red" title="tip">abbr</abbr> <u id="e-u" style="color:red" title="tip">u</u> <s id="e-s" style="color:red" title="tip">s</s> <q id="e-q" style="color:red" title="tip">q</q> <cite id="e-cite" style="color:red" title="tip">cite</cite> <var id="e-var" style="color:red" title="tip">var</var> <samp id="e-samp" style="color:red" title="tip">samp</samp> <tt id="e-tt" style="color:red" title="tip">tt</tt> <big id="e-big" style="color:red" title="tip">big</big> <strike id="e-strike" style="color:red" title="tip">strike</strike> <font id="e-font" color="red" size="5" face="serif">font</font> <bdo id="e-bdo" dir="rtl">bdo</bdo> <dfn id="e-dfn" title="tip">dfn</dfn> <time id="e-time" datetime="2026-01-01" title="tip">time</time> <data id="e-data" value="1" title="tip">data</data> <img id="e-img" src="../../assets/markdowns/spacer.svg" style="color:red;border:3px solid red;width:50px" title="tip" aria-label="al" alt="alt" align="right" hspace="10" vspace="10" border="2" valign="top" loading="lazy" decoding="async" width="50" height="9">

<h2 id="e-h2" style="color:red" title="tip" align="center">h2</h2>

<blockquote id="e-bq" style="color:red" title="tip">bq</blockquote>

<pre id="e-pre" style="color:red" title="tip">pre</pre>

<ul id="e-ul" style="color:red" title="tip"><li id="e-li" style="color:red" title="tip">li</li></ul>

<ol id="e-ol" style="color:red" start="3" type="a"><li>ol</li></ol>

<dl id="e-dl" style="color:red"><dt id="e-dt" title="tip">dt</dt><dd id="e-dd" style="color:red" title="tip">dd</dd></dl>

<hr id="e-hr" style="color:red" width="50%" size="5" noshade align="left">

<table id="e-table" style="color:red;width:50%" title="tip" border="3" cellpadding="10" cellspacing="5" bgcolor="red" width="300" align="center" frame="box" rules="all" summary="s"><caption id="e-caption" style="color:red">cap</caption><thead id="e-thead" style="color:red"><tr id="e-tr" style="color:red" bgcolor="red"><th id="e-th" style="color:red" title="tip" scope="col" width="100" abbr="x" bgcolor="red" valign="top" nowrap>th</th></tr></thead><tbody id="e-tbody"><tr><td id="e-td" style="color:red" title="tip" width="100" height="50" valign="bottom" align="right" rowspan="1" colspan="1" bgcolor="red" nowrap headers="x" axis="y" char="c">td</td></tr></tbody><tfoot id="e-tfoot"><tr><td>tf</td></tr></tfoot><colgroup id="e-colgroup"><col id="e-col" width="50"></colgroup></table>

<details id="e-details" style="color:red" title="tip" open><summary id="e-summary" style="color:red" title="tip">summary</summary>d text</details>

<center id="e-center">center</center>

<section id="e-section" style="color:red">section</section>

<p id="e-br">line<br id="e-br2" clear="all" style="color:red">break</p>
