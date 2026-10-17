# Style hide test

Row 0 control: no style.

Row 1 bare style (control):

<style>.m1{color:red}</style>

Row 2 span hidden:

<span hidden><style>.m2{color:red}</style></span>

Row 3 span with id and hidden:

<span id="s3" hidden><style>.m3{color:red}</style></span>

Row 4 span hidden="hidden":

<span hidden="hidden"><style>.m4{color:red}</style></span>

Row 5 span hidden="true":

<span hidden="true"><style>.m5{color:red}</style></span>

Row 6 div hidden:

<div hidden><style>.m6{color:red}</style></div>

Row 7 span inline style display none:

<span style="display:none"><style>.m7{color:red}</style></span>

Row 8 span aria-hidden:

<span aria-hidden="true"><style>.m8{color:red}</style></span>

Row 9 details closed:

<details><summary>d</summary><style>.m9{color:red}</style></details>

End.
