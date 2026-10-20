# Standard layout test 4

The picture in c1 is the existing up-arrow sized as a stand-in for an illustration. Ids and pairs are made up.

Q1 id column 240, illustration slot 214 by 120, small detail table (2 pairs).

<table>
<tbody>
<tr><td colspan="2" align="center">Q1 arrow bar</td></tr>
<tr><td width="240" valign="top">

```
fill-raised
```

</td><td rowspan="2" valign="top">
<table width="100%">
<tbody><tr><td>Q1 label: raised cards</td></tr></tbody>
<tbody><tr><td>Q1 parts: kind fill, type raised</td></tr></tbody>
<tbody><tr><td>Q1 pairs with (2):<ul><li><code>text-base-on-fill-raised</code></li><li><code>line-base-on-fill-raised</code></li></ul></td></tr></tbody>
</table>
</td></tr>
<tr><td align="center" valign="top"><img src="../../assets/markdowns/arrow-up.svg" width="214" height="120" alt="Q1 illustration 214 by 120"></td></tr>
</tbody>
</table>

Q2 id column 240, illustration slot 214 by 200, same small detail table. Does the detail cell grow empty space at the bottom?

<table>
<tbody>
<tr><td colspan="2" align="center">Q2 arrow bar</td></tr>
<tr><td width="240" valign="top">

```
fill-raised
```

</td><td rowspan="2" valign="top">
<table width="100%">
<tbody><tr><td>Q2 label: raised cards</td></tr></tbody>
<tbody><tr><td>Q2 parts: kind fill, type raised</td></tr></tbody>
<tbody><tr><td>Q2 pairs with (2):<ul><li><code>text-base-on-fill-raised</code></li><li><code>line-base-on-fill-raised</code></li></ul></td></tr></tbody>
</table>
</td></tr>
<tr><td align="center" valign="top"><img src="../../assets/markdowns/arrow-up.svg" width="214" height="200" alt="Q2 illustration 214 by 200"></td></tr>
</tbody>
</table>

Q3 id column 300, illustration slot 274 by 160, 3 pairs.

<table>
<tbody>
<tr><td colspan="2" align="center">Q3 arrow bar</td></tr>
<tr><td width="300" valign="top">

```
fill-raised
```

</td><td rowspan="2" valign="top">
<table width="100%">
<tbody><tr><td>Q3 label: raised cards</td></tr></tbody>
<tbody><tr><td>Q3 parts: kind fill, type raised</td></tr></tbody>
<tbody><tr><td>Q3 pairs with (3):<ul><li><code>text-base-on-fill-raised</code></li><li><code>icon-base-on-fill-raised</code></li><li><code>line-base-on-fill-raised</code></li></ul></td></tr></tbody>
</table>
</td></tr>
<tr><td align="center" valign="top"><img src="../../assets/markdowns/arrow-up.svg" width="274" height="160" alt="Q3 illustration 274 by 160"></td></tr>
</tbody>
</table>

Q4 long ids in a 240 column: 24, 35 and 58 characters. Does the box scroll, wrap or widen the column? Does the copy button still sit in the box?

<table>
<tbody>
<tr><td colspan="2" align="center">Q4 id of 24 characters</td></tr>
<tr><td width="240" valign="top">

```
text-base-on-fill-primum
```

</td><td rowspan="2" valign="top">Q4 detail cell one</td></tr>
<tr><td></td></tr>
</tbody>
<tbody>
<tr><td colspan="2" align="center">Q4 id of 35 characters</td></tr>
<tr><td width="240" valign="top">

```
text-danger-on-fill-primum-disabled
```

</td><td rowspan="2" valign="top">Q4 detail cell two</td></tr>
<tr><td></td></tr>
</tbody>
<tbody>
<tr><td colspan="2" align="center">Q4 id of 58 characters</td></tr>
<tr><td width="240" valign="top">

```
text-danger-subtle-disabled-on-fill-primum-subtle-disabled
```

</td><td rowspan="2" valign="top">Q4 detail cell three</td></tr>
<tr><td></td></tr>
</tbody>
</table>

Q5 the same three ids in a 300 column.

<table>
<tbody>
<tr><td colspan="2" align="center">Q5 id of 24 characters</td></tr>
<tr><td width="300" valign="top">

```
text-base-on-fill-primum
```

</td><td rowspan="2" valign="top">Q5 detail cell one</td></tr>
<tr><td></td></tr>
</tbody>
<tbody>
<tr><td colspan="2" align="center">Q5 id of 35 characters</td></tr>
<tr><td width="300" valign="top">

```
text-danger-on-fill-primum-disabled
```

</td><td rowspan="2" valign="top">Q5 detail cell two</td></tr>
<tr><td></td></tr>
</tbody>
<tbody>
<tr><td colspan="2" align="center">Q5 id of 58 characters</td></tr>
<tr><td width="300" valign="top">

```
text-danger-subtle-disabled-on-fill-primum-subtle-disabled
```

</td><td rowspan="2" valign="top">Q5 detail cell three</td></tr>
<tr><td></td></tr>
</tbody>
</table>

Q6 the 58-character id broken at on, as it would paste (two lines). Only to see how it looks; the copied text would contain a line break.

<table>
<tbody>
<tr><td colspan="2" align="center">Q6 broken id</td></tr>
<tr><td width="240" valign="top">

```
text-danger-subtle-disabled
on-fill-primum-subtle-disabled
```

</td><td rowspan="2" valign="top">Q6 detail cell</td></tr>
<tr><td></td></tr>
</tbody>
</table>
