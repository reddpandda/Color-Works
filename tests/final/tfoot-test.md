# Test 1: tfoot and row groups

Each row is labelled with its position in the SOURCE order. Check two things: the order the rows appear on screen, and which rows are shaded.

T1 tfoot written first in the source, then tbody.

<table>
<tfoot>
<tr><td>src1 foot-a</td><td>foot</td></tr>
<tr><td>src2 foot-b</td><td>foot</td></tr>
</tfoot>
<tbody>
<tr><td>src3 body-a</td><td>body</td></tr>
<tr><td>src4 body-b</td><td>body</td></tr>
<tr><td>src5 body-c</td><td>body</td></tr>
</tbody>
</table>

T2 thead written last in the source.

<table>
<tbody>
<tr><td>src1 body-a</td><td>body</td></tr>
<tr><td>src2 body-b</td><td>body</td></tr>
</tbody>
<thead>
<tr><td>src3 head-a</td><td>head</td></tr>
</thead>
</table>

T3 the id and arrow block with a tfoot first. The id cell spans two rows inside the tbody.

<table>
<tfoot>
<tr><td colspan="2">src1 foot: parts</td></tr>
</tfoot>
<tbody>
<tr><td rowspan="2" valign="top">src2 body id</td><td>src2 job</td></tr>
<tr><td>src3 usage</td></tr>
<tr><td>src4 arrow</td><td>src4 pairs</td></tr>
</tbody>
</table>

T4 three tbody groups of different lengths.

<table>
<tbody><tr><td>g1 r1</td><td>one</td></tr></tbody>
<tbody><tr><td>g2 r1</td><td>one</td></tr><tr><td>g2 r2</td><td>two</td></tr><tr><td>g2 r3</td><td>three</td></tr></tbody>
<tbody><tr><td>g3 r1</td><td>one</td></tr><tr><td>g3 r2</td><td>two</td></tr></tbody>
</table>

T5 rowspan across two tbody groups (does it stay inside the first?).

<table>
<tbody>
<tr><td rowspan="3">span 3</td><td>g1 r1</td></tr>
<tr><td>g1 r2</td></tr>
</tbody>
<tbody>
<tr><td>g2 r1</td><td>g2 r1 right</td></tr>
</tbody>
</table>

T6 nested table inside a cell, zebra of the inner table.

<table>
<tr><td>outer r1</td><td><table><tr><td>in r1</td></tr><tr><td>in r2</td></tr><tr><td>in r3</td></tr></table></td></tr>
<tr><td>outer r2</td><td>x</td></tr>
</table>

# Test 2: colour without images

M1 colour block with rule:

<table>
<tr><td>M1 rule block</td><td>

$\color{#336699}{\rule{40px}{20px}}$

</td></tr>
<tr><td>M2 textcolor</td><td>

$\textcolor{#cc3300}{M2 red text}$

</td></tr>
<tr><td>M3 colorbox</td><td>

$\colorbox{#ffcc00}{M3 yellow box}$

</td></tr>
<tr><td>M4 fcolorbox</td><td>

$\fcolorbox{#cc3300}{#ffeeee}{M4 framed}$

</td></tr>
<tr><td>M5 three swatches</td><td>

$\color{#d73a49}{\rule{24px}{24px}}\ \color{#22863a}{\rule{24px}{24px}}\ \color{#0366d6}{\rule{24px}{24px}}$

</td></tr>
<tr><td>M6 white and black swatch</td><td>

$\color{#ffffff}{\rule{24px}{24px}}\ \color{#000000}{\rule{24px}{24px}}$

</td></tr>
<tr><td>M7 colored square character</td><td>

$\color{#336699}{\blacksquare}$ and $\textcolor{#336699}{\text{■}}$

</td></tr>
<tr><td>M8 coloured emoji squares</td><td>

🟥🟧🟨🟩🟦🟪🟫⬛⬜ and :red_circle: :large_blue_circle: :green_circle:

</td></tr>
<tr><td>M9 mark</td><td><mark>M9 mark text</mark></td></tr>
</table>

M10 display math block outside a table:

$$\color{#336699}{\rule{120px}{12px}}$$
