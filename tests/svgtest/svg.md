# svg test

S1 light/dark media query inside svg: <img id="s1" src="dark.svg" alt="S1">

S2 global css inside svg, with a victim paragraph and table after it: <img id="s2" src="reach.svg" alt="S2">

<p id="victim">VICTIM paragraph ZQ_victim</p>

<table id="victim-table"><tr><td id="victim-td">VICTIM cell ZQ_vcell</td></tr></table>

S3 foreignObject text box: <img id="s3" src="textbox.svg" alt="S3">

S4 embedded font (top row should be squares, triangle, diamond if the font loaded, bottom row is the monospace fallback): <img id="s4" src="font.svg" alt="S4">

S5 whole contact sheet: <img id="s5" src="sheet.svg" alt="S5">

S6 view ids: <img id="s6a" src="sheet.svg#v-a" alt="S6a"> <img id="s6b" src="sheet.svg#v-b" alt="S6b" width="100"> ![S6c](sheet.svg#v-c)

S7 svgView fragment: <img id="s7" src="sheet.svg#svgView(viewBox(300,0,100,100))" alt="S7" width="100">

S8 target sprite: <img id="s8a" src="target.svg#t1" alt="S8a"> <img id="s8b" src="target.svg#t2" alt="S8b"> <img id="s8c" src="target.svg" alt="S8c-blank-expected">

S9 inline svg with use, hidden defs in rp: <rp><svg width="10" height="10"><defs><g id="zq_g"><rect width="10" height="10"/></g></defs></svg></rp><svg id="s9" width="40" height="40"><use href="#zq_g"/><rect width="40" height="40" fill="red"/></svg> end of S9.

S10 linked slice with link title: [<img id="s10" src="sheet.svg#v-d" alt="S10" width="100">](https://example.com "tip on link")

S11 transform sprite, one file, four crops: <img id="s11a" src="sprite.svg#c-a" alt="S11a"> <img id="s11b" src="sprite.svg#c-b" alt="S11b"> <img id="s11c" src="sprite.svg#c-c" alt="S11c" width="50"> <img id="s11d" src="sprite.svg#c-d" alt="S11d">
