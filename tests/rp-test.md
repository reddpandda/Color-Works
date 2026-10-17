# rp style test

Visible paragraph A. ZQ_A_visible

T1 single-line style, inline markdown and html hidden: <rp id="hide1"><style>#hide1{display:none} h1{font-family:Georgia,serif;color:#b3261e;border-bottom:3px double #b3261e} body{background:#fffaf0} a{color:#1b6ca8}</style>ZQ_T1_text **ZQ_T1_bold** [ZQ_T1_link](https://example.com) ![ZQ_T1_alt](../assets/markdowns/arrow-up.svg) <b>ZQ_T1_htmlbold</b> `ZQ_T1_code`</rp> end of T1 line.

T2 multi-line paragraph: <rp id="hide2"><style>
#hide2{display:none}
h1{letter-spacing:.05em}
p{line-height:1.7}
</style>ZQ_T2_text
second line ZQ_T2_line2</rp> end of T2.

T3 blank line inside: <rp id="hide3"><style>#hide3{display:none}</style>ZQ_T3_before

ZQ_T3_after</rp> end of T3.

T4 list inside: <rp id="hide4">

- ZQ_T4_item

</rp> end of T4.

Visible paragraph B. ZQ_B_visible
