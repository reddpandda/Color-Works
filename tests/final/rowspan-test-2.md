# Rowspan test 2

## A. Zebra striping

A1 baseline: id cell starts on row 1.

<table>
<tr>
<td width="240" rowspan="2" valign="top">

```
text-base-on-fill-primum
```

</td>
<td>

parts: kind text, type base

</td>
</tr>
<tr>
<td>

job: text on the main action fill

</td>
</tr>
<tr>
<td rowspan="2" align="center" valign="top"><a href="glossary.md#g-x#gh-light-mode-only"><img src="../../assets/markdowns/arrow-up.svg" width="32" alt="up"></a><a href="glossary.md#g-x#gh-dark-mode-only"><img src="../../assets/markdowns/arrow-up-white.svg" width="32" alt="up"></a></td>
<td>

usage: use on fill-primum

</td>
</tr>
<tr>
<td>

`fill-primum`

</td>
</tr>
</table>

A2 hidden first row before the block.

<table>
<tr hidden><td colspan="2"></td></tr>
<tr>
<td width="240" rowspan="2" valign="top">

```
text-base-on-fill-primum
```

</td>
<td>

parts: kind text, type base

</td>
</tr>
<tr>
<td>

job: text on the main action fill

</td>
</tr>
<tr>
<td rowspan="2" align="center" valign="top"><a href="glossary.md#g-x#gh-light-mode-only"><img src="../../assets/markdowns/arrow-up.svg" width="32" alt="up"></a><a href="glossary.md#g-x#gh-dark-mode-only"><img src="../../assets/markdowns/arrow-up-white.svg" width="32" alt="up"></a></td>
<td>

usage: use on fill-primum

</td>
</tr>
<tr>
<td>

`fill-primum`

</td>
</tr>
</table>

A3 parts as a full-width first row; id spans rows 2-3, arrow beside pairs on row 5.

<table>
<tr>
<td colspan="2">

parts: kind text, type base

</td>
</tr>
<tr>
<td width="240" rowspan="2" valign="top">

```
text-base-on-fill-primum
```

</td>
<td>

job: text on the main action fill

</td>
</tr>
<tr>
<td>

usage: use on fill-primum

</td>
</tr>
<tr>
<td align="center" valign="top"><a href="glossary.md#g-x#gh-light-mode-only"><img src="../../assets/markdowns/arrow-up.svg" width="32" alt="up"></a><a href="glossary.md#g-x#gh-dark-mode-only"><img src="../../assets/markdowns/arrow-up-white.svg" width="32" alt="up"></a></td>
<td>

`fill-primum`

</td>
</tr>
</table>

A4 explicit thead + tbody.

<table>
<thead>
<tr><td colspan="2">header row in thead</td></tr>
</thead>
<tbody>
<tr>
<td width="240" rowspan="2" valign="top">

```
text-base-on-fill-primum
```

</td>
<td>

parts: kind text, type base

</td>
</tr>
<tr>
<td>

job: text on the main action fill

</td>
</tr>
<tr>
<td rowspan="2" align="center" valign="top"><a href="glossary.md#g-x#gh-light-mode-only"><img src="../../assets/markdowns/arrow-up.svg" width="32" alt="up"></a><a href="glossary.md#g-x#gh-dark-mode-only"><img src="../../assets/markdowns/arrow-up-white.svg" width="32" alt="up"></a></td>
<td>

usage: use on fill-primum

</td>
</tr>
<tr>
<td>

`fill-primum`

</td>
</tr>
</tbody>
</table>

A5 thin real first row with a 1px spacer image.

<table>
<tr><td colspan="2"><img src="../../assets/markdowns/spacer.svg" width="1" height="1" alt=""></td></tr>
<tr>
<td width="240" rowspan="2" valign="top">

```
text-base-on-fill-primum
```

</td>
<td>

parts: kind text, type base

</td>
</tr>
<tr>
<td>

job: text on the main action fill

</td>
</tr>
<tr>
<td rowspan="2" align="center" valign="top"><a href="glossary.md#g-x#gh-light-mode-only"><img src="../../assets/markdowns/arrow-up.svg" width="32" alt="up"></a><a href="glossary.md#g-x#gh-dark-mode-only"><img src="../../assets/markdowns/arrow-up-white.svg" width="32" alt="up"></a></td>
<td>

usage: use on fill-primum

</td>
</tr>
<tr>
<td>

`fill-primum`

</td>
</tr>
</table>

A6 bgcolor attributes on the id cell, the arrow cell and a row.

<table>
<tr>
<td width="240" rowspan="2" valign="top" bgcolor="#f6f8fa">

```
text-base-on-fill-primum
```

</td>
<td>

parts: kind text, type base

</td>
</tr>
<tr>
<td>

job: text on the main action fill

</td>
</tr>
<tr>
<td rowspan="2" align="center" valign="top" bgcolor="#ffeb3b"><a href="glossary.md#g-x#gh-light-mode-only"><img src="../../assets/markdowns/arrow-up.svg" width="32" alt="up"></a><a href="glossary.md#g-x#gh-dark-mode-only"><img src="../../assets/markdowns/arrow-up-white.svg" width="32" alt="up"></a></td>
<td>

usage: use on fill-primum

</td>
</tr>
<tr>
<td>

`fill-primum`

</td>
</tr>
</table>

A7 th instead of td for the two left cells.

<table>
<tr>
<th width="240" rowspan="2" valign="top">

```
text-base-on-fill-primum
```

</th>
<td>

parts: kind text, type base

</td>
</tr>
<tr>
<td>

job: text on the main action fill

</td>
</tr>
<tr>
<th rowspan="2" align="center" valign="top"><a href="glossary.md#g-x#gh-light-mode-only"><img src="../../assets/markdowns/arrow-up.svg" width="32" alt="up"></a><a href="glossary.md#g-x#gh-dark-mode-only"><img src="../../assets/markdowns/arrow-up-white.svg" width="32" alt="up"></a></th>
<td>

usage: use on fill-primum

</td>
</tr>
<tr>
<td>

`fill-primum`

</td>
</tr>
</table>

A8 two tbody groups (parity per group).

<table>
<tbody>
<tr><td>g1 r1</td><td>one</td></tr>
<tr><td>g1 r2</td><td>two</td></tr>
</tbody>
<tbody>
<tr><td>g2 r1</td><td>one</td></tr>
<tr><td>g2 r2</td><td>two</td></tr>
</tbody>
</table>

## B. What survives in a cell

<table>
<tr><th width="140">case</th><th>sample</th></tr>
<tr>
<td>B1 details closed</td>
<td>

<details><summary>46 ids</summary>

- `icon-base-on-fill-base`
- `icon-danger-on-fill-base`
- `text-base-on-fill-base`

</details>

</td>
</tr>
<tr>
<td>B2 details open</td>
<td>

<details open><summary>open by default</summary>

body text with `code` and **bold**

</details>

</td>
</tr>
<tr>
<td>B3 details in a list in a cell</td>
<td>

- item one
- <details><summary>nested fold</summary>folded text</details>

</td>
</tr>
<tr>
<td>B4 emphasis</td>
<td>

**bold** *italic* ~~strike~~ `inline` ***both***

</td>
</tr>
<tr>
<td>B5 links</td>
<td>

[relative](glossary.md) [anchor](#a-zebra-striping) https://example.com

</td>
</tr>
<tr>
<td>B6 headings</td>
<td>

### h3 in a cell

#### h4 in a cell

</td>
</tr>
<tr>
<td>B7 blockquote</td>
<td>

> quoted line
> second line

</td>
</tr>
<tr>
<td>B8 lists</td>
<td>

1. ordered
2. ordered
   - nested bullet

- [ ] task open
- [x] task done

</td>
</tr>
<tr>
<td>B9 hr and line breaks</td>
<td>

above

---

below<br>after br<br><br>two br

</td>
</tr>
<tr>
<td>B10 nested table</td>
<td>

<table><tr><td>inner a</td><td>inner b</td></tr></table>

</td>
</tr>
<tr>
<td>B11 keyboard, sub, sup, ins, mark</td>
<td>

<kbd>Ctrl</kbd> H<sub>2</sub>O x<sup>2</sup> <ins>ins</ins> <mark>mark</mark> <small>small</small> <u>under</u> <s>s</s> <del>del</del>

</td>
</tr>
<tr>
<td>B12 abbr and title attrs</td>
<td>

<abbr title="abbr tip">abbr</abbr> <span title="span tip">span title</span> <a href="glossary.md" title="link tip">link title</a>

</td>
</tr>
<tr>
<td>B13 definition list</td>
<td>

<dl><dt>term</dt><dd>definition</dd></dl>

</td>
</tr>
<tr>
<td>B14 picture light and dark</td>
<td>

<picture><source media="(prefers-color-scheme: dark)" srcset="../../assets/markdowns/arrow-up-white.svg"><img src="../../assets/markdowns/arrow-up.svg" width="32" alt="picture"></picture>

</td>
</tr>
<tr>
<td>B15 img width and height</td>
<td>

<img src="../../assets/markdowns/arrow-up.svg" width="20" height="60" alt="w20h60">

</td>
</tr>
<tr>
<td>B16 markdown image</td>
<td>

![md image](../../assets/markdowns/arrow-up.svg)

</td>
</tr>
<tr>
<td>B17 nowrap attribute</td>
<td>

<table><tr><td nowrap>nowrap td text that is deliberately long to see whether it wraps at all</td></tr></table>

</td>
</tr>
<tr>
<td>B18 nobr and wbr</td>
<td>

<nobr>nobr text that is deliberately long to see whether it wraps</nobr> aaaa<wbr>bbbb

</td>
</tr>
<tr>
<td>B19 div and p align</td>
<td>

<div align="center">div center</div><p align="right">p right</p><center>center tag</center>

</td>
</tr>
<tr>
<td>B20 font and style</td>
<td>

<font color="red">font red</font> <span style="color:red">style red</span>

</td>
</tr>
<tr>
<td>B21 pre block</td>
<td>

<pre>raw pre
  keeps   spaces</pre>

</td>
</tr>
<tr>
<td>B22 entities and emoji</td>
<td>

&amp; &lt; &gt; &nbsp;| &#8209; non-breaking-hyphen | :tada: &#x2197; &uarr;

</td>
</tr>
<tr>
<td>B23 math</td>
<td>

$x^2$ and $$y=mx+b$$

</td>
</tr>
<tr>
<td>B24 footnote</td>
<td>

text with a footnote[^1]

[^1]: the note

</td>
</tr>
<tr>
<td>B25 anchors</td>
<td>

<a id="anchor-id"></a><a name="anchor-name"></a>anchors present

</td>
</tr>
<tr>
<td>B26 height attribute on td</td>
<td>

<table><tr><td height="90">td height 90</td></tr></table>

</td>
</tr>
<tr>
<td>B27 table width and border</td>
<td>

<table width="60%" border="2" cellpadding="12" cellspacing="6"><tr><td>table attrs</td></tr></table>

</td>
</tr>
<tr>
<td>B28 colgroup and caption</td>
<td>

<table><caption>caption text</caption><colgroup><col width="100"><col></colgroup><tr><td>c1</td><td>c2</td></tr></table>

</td>
</tr>
<tr>
<td>B29 tfoot</td>
<td>

<table><tbody><tr><td>body</td></tr></tbody><tfoot><tr><td>foot</td></tr></tfoot></table>

</td>
</tr>
<tr>
<td>B30 spacer image</td>
<td>

<img src="../../assets/markdowns/spacer.svg" width="200" height="1" alt="">spacer 200 wide

</td>
</tr>
<tr>
<td>B31 ruby and bdo</td>
<td>

<ruby>漢<rt>kan</rt></ruby> <bdo dir="rtl">abc</bdo>

</td>
</tr>
<tr>
<td>B32 summary link</td>
<td>

<details><summary><a href="glossary.md">link in summary</a></summary>x</details>

</td>
</tr>
</table>
