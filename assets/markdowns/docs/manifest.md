# Assets manifest

Where every SVG in `assets/markdowns/` came from. Nothing here was drawn by hand except the spacer.

## Arrows: `arrow-up`, `arrow-down`, `arrow-left`, `arrow-right`

- Source: GitHub Octicons, `primer/octicons`, files `icons/arrow-up-24.svg`, `arrow-down-24.svg`, `arrow-left-24.svg`, `arrow-right-24.svg`.
- Fetched from commit `6dbe38e4e9b4987b2c9332d719c57fbbdd083e2d`.
- License: MIT, Copyright (c) 2026 GitHub Inc. (text below).
- Path data is unchanged. The files are used as shipped (they draw black by default).

## Digits: `circle-number-0` to `circle-number-9`, `square-number-0` to `square-number-9`

- Source: Tabler Icons, `tabler/tabler-icons`, files `icons/outline/circle-number-N.svg` and `icons/outline/square-number-N.svg`.
- Fetched from commit `a4ce1404bc6d24d3c365afe7b258d6bf6f48d62d`.
- License: MIT, Copyright (c) 2020-2026 Paweł Kuna (text below).
- Path data is unchanged. The only edits: the leading XML comment block was removed and the markup was put on one line. Stroke is left as `currentColor`, which draws black when the file is used in an `img` tag.
- Usage: circle = a page you can go to, square = the page you are on.

## White copies: every file ending in `-white.svg`

- Each is the matching black file with one colour attribute changed so it shows on a dark background: `fill="#fff"` on the Octicons arrows, `stroke="#fff"` on the Tabler digits. No path data was touched.
- Why two copies: GitHub cannot recolour an image, and an image inside a link cannot be swapped by theme any other way. The Markdown shows one or the other with the `#gh-light-mode-only` and `#gh-dark-mode-only` link suffixes.

## Spacer: `spacer.svg`

- Authored for this project. It is an empty SVG, 1200 by 1 pixels, with no shapes. It is placed in one definition cell per table to make the table fill the page width.

## License text (applies to Octicons and Tabler Icons)

MIT License

Copyright (c) 2026 GitHub Inc. (Octicons)
Copyright (c) 2020-2026 Paweł Kuna (Tabler Icons)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
