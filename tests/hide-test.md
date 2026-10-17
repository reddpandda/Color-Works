# hide test

Each line has a label, then a probe token like ZQ01v. If a token is visible on the rendered page, that trick did not hide it.

00 control visible span: <span>ZQ00v</span>

01 dialog: <dialog>ZQ01v</dialog>

02 rp: <ruby>a<rp>ZQ02v</rp><rt>b</rt></ruby>

03 map: <map name="m"><area alt="x">ZQ03v</map>

04 abbr title: <abbr title="ZQ04v">hover</abbr>

05 template: <template>ZQ05v</template>

06 noscript: <noscript>ZQ06v</noscript>

07 object: <object>ZQ07v</object>

08 applet: <applet>ZQ08v</applet>

09 canvas: <canvas>ZQ09v</canvas>

10 audio: <audio>ZQ10v</audio>

11 video: <video>ZQ11v</video>

12 datalist: <datalist id="d">ZQ12v</datalist>

13 progress: <progress>ZQ13v</progress>

14 meter: <meter>ZQ14v</meter>

15 select: <select><option>ZQ15v</option></select>

16 title: <title>ZQ16v</title>

17 head: <head>ZQ17v</head>

18 hidden attr: <span hidden>ZQ18v</span>

19 hidden until-found: <span hidden="until-found">ZQ19v</span>

20 style display none: <span style="display:none">ZQ20v</span>

21 aria-hidden: <span aria-hidden="true">ZQ21v</span>

22 class d-none: <span class="d-none">ZQ22v</span>

23 class sr-only: <span class="sr-only">ZQ23v</span>

24 popover: <span popover>ZQ24v</span>

25 inert: <span inert>ZQ25v</span>

26 font white: <font color="white">ZQ26v</font>

28 md image alt: ![ZQ28v](../assets/markdowns/spacer.svg)

29 img title: <img src="../assets/markdowns/spacer.svg" title="ZQ29v" alt="">

31 math phantom: $\phantom{ZQ31v}$

33 link reference definition:

[ZQ33v]: https://example.com/

35 dark-only link text: <a href="#gh-dark-mode-only">ZQ35v</a>

36 light-only link text: <a href="#gh-light-mode-only">ZQ36v</a>

37 sepia suffix: <a href="#gh-sepia-mode-only">ZQ37v</a>

38 dark-dimmed suffix: <a href="#gh-dark-dimmed-mode-only">ZQ38v</a>

39 high-contrast suffix: <a href="#gh-dark-high-contrast-mode-only">ZQ39v</a>

40 colorblind suffix: <a href="#gh-light-colorblind-mode-only">ZQ40v</a>

41 svg text: <svg><text>ZQ41v</text></svg>

43 math tag: <math>ZQ43v</math>

44 iframe: <iframe>ZQ44v</iframe>

45 textarea: <textarea>ZQ45v</textarea>

46 button hidden: <button hidden>ZQ46v</button>

47 input hidden: <input type="hidden" value="ZQ47v">

49 details closed: <details><summary>s</summary>ZQ49v</details>

50 comment: <!-- ZQ50v -->

62 slot: <slot>ZQ62v</slot>

64 script: <script>ZQ64v</script>

65 noframes: <noframes>ZQ65v</noframes>

66 xmp: <xmp>ZQ66v</xmp>

99 end marker visible: <span>ZQ99v</span>
