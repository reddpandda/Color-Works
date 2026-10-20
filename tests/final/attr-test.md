# Attribute survival test

The same long set of attributes is put on each element. The rendered HTML shows which survive.

Table, row, cells:

<table id="id-table" data-foo="table" data-role="table" data-testid="table" data-clipboard-text="table" aria-label="table" aria-describedby="table" role="table" tabindex="0" lang="fr" dir="rtl" itemprop="table" title="table" translate="no" accesskey="t">
<tr id="id-tr" data-foo="tr" data-role="tr" data-testid="tr" data-clipboard-text="tr" aria-label="tr" aria-describedby="tr" role="row" tabindex="0" lang="fr" dir="rtl" itemprop="tr" title="tr" translate="no" accesskey="r">
<th id="id-th" scope="col" abbr="th-abbr" axis="th-axis" headers="id-td" data-foo="th" data-role="th" aria-label="th" role="columnheader" title="th">th cell</th>
<td id="id-td" scope="row" abbr="td-abbr" axis="td-axis" headers="id-th" data-foo="td" data-role="td" data-testid="td" data-tooltip="td" data-clipboard-text="td" data-clipboard-target="#id-td" data-copy-feedback="td" data-hovercard-type="user" aria-label="td" aria-describedby="td" aria-hidden="false" aria-labelledby="td" role="cell" tabindex="0" lang="fr" dir="rtl" itemprop="td" title="td" translate="no" accesskey="d" contenteditable="true" draggable="true">td cell</td>
</tr>
</table>

Inline and block elements:

<span id="id-span" data-foo="span" data-role="span" data-testid="span" data-clipboard-text="span" aria-label="span" role="note" tabindex="0" lang="fr" dir="rtl" itemprop="span" title="span" translate="no">span text</span>

<a id="id-a" href="#id-td" data-foo="a" data-role="a" data-testid="a" data-clipboard-text="a" aria-label="a" role="note" tabindex="0" lang="fr" itemprop="a" title="a">link text</a>

<div id="id-div" data-foo="div" data-role="div" data-testid="div" data-clipboard-text="div" aria-label="div" role="note" tabindex="0" lang="fr" itemprop="div" title="div">div text</div>

<code id="id-code" data-foo="code" data-role="code" aria-label="code" title="code">code text</code>

<img id="id-img" src="../../assets/markdowns/arrow-up.svg" width="24" data-foo="img" data-role="img" aria-label="img" title="img" alt="img alt">

<details id="id-details" data-foo="details" open><summary id="id-summary" data-foo="summary">summary text</summary>details body</details>

<h3 id="id-h3" data-foo="h3" title="h3">heading text</h3>

End.
