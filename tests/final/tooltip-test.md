# Tooltip test

Hover each item for about 2 seconds and note whether a tooltip appears, and what it says. Each tooltip text names its case.

Icons come from `main` by absolute URL. Case 1 is plain text; cases 2 to 8 use an icon.

## 1. Markdown link with a title, text only

[Hover this link](https://github.com/reddpandda/Color-Works "CASE-1 markdown link title")

## 2. Markdown image with a title, no link

![Page 5](https://raw.githubusercontent.com/reddpandda/Color-Works/main/assets/markdowns/numbers/black-circle-filled/number_05.svg "CASE-2 markdown image title")

## 3. HTML image with a title, no link

<img src="https://raw.githubusercontent.com/reddpandda/Color-Works/main/assets/markdowns/numbers/black-circle-filled/number_05.svg" width="40" title="CASE-3 img title" alt="Page 5">

## 4. Link with a title around an image with no title

<a href="https://github.com/reddpandda/Color-Works" title="CASE-4 link title"><img src="https://raw.githubusercontent.com/reddpandda/Color-Works/main/assets/markdowns/numbers/black-circle-filled/number_05.svg" width="40" alt="Page 5"></a>

## 5. Link with no title around an image with a title

<a href="https://github.com/reddpandda/Color-Works"><img src="https://raw.githubusercontent.com/reddpandda/Color-Works/main/assets/markdowns/numbers/black-circle-filled/number_05.svg" width="40" title="CASE-5 img title inside link" alt="Page 5"></a>

## 6. Both have titles (which one wins)

<a href="https://github.com/reddpandda/Color-Works" title="CASE-6 OUTER link title"><img src="https://raw.githubusercontent.com/reddpandda/Color-Works/main/assets/markdowns/numbers/black-circle-filled/number_05.svg" width="40" title="CASE-6 INNER img title" alt="Page 5"></a>

## 7. Light and dark suffix pair with titles

<a href="https://github.com/reddpandda/Color-Works"><img src="https://raw.githubusercontent.com/reddpandda/Color-Works/main/assets/markdowns/numbers/black-circle-filled/number_05.svg#gh-light-mode-only" width="40" title="CASE-7 light title" alt="Page 5"><img src="https://raw.githubusercontent.com/reddpandda/Color-Works/main/assets/markdowns/numbers/white-circle-filled/number_05.svg#gh-dark-mode-only" width="40" title="CASE-7 dark title" alt="Page 5"></a>

## 8. Centered pagination row with titles

<p align="center">
  <a href="https://github.com/reddpandda/Color-Works"><img src="https://raw.githubusercontent.com/reddpandda/Color-Works/main/assets/markdowns/numbers/black-circle-filled/number_04.svg" width="40" hspace="4" title="CASE-8 page 4" alt="Page 4"></a>
  <a href="https://github.com/reddpandda/Color-Works"><img src="https://raw.githubusercontent.com/reddpandda/Color-Works/main/assets/markdowns/numbers/black-box-filled/number_05.svg" width="40" hspace="4" title="CASE-8 page 5 current" alt="Page 5, current"></a>
  <a href="https://github.com/reddpandda/Color-Works"><img src="https://raw.githubusercontent.com/reddpandda/Color-Works/main/assets/markdowns/numbers/black-circle-filled/number_06.svg" width="40" hspace="4" title="CASE-8 page 6" alt="Page 6"></a>
</p>

## 9. Inside a table cell

| Case | Item |
| --- | --- |
| 9a image link | <a href="https://github.com/reddpandda/Color-Works"><img src="https://raw.githubusercontent.com/reddpandda/Color-Works/main/assets/markdowns/numbers/black-circle-filled/number_05.svg" width="40" title="CASE-9a cell img title" alt="Page 5"></a> |
| 9b text link | <a href="https://github.com/reddpandda/Color-Works" title="CASE-9b cell link title">hover</a> |

## 10. Other elements

<abbr title="CASE-10a abbr title">abbr</abbr> · <span title="CASE-10b span title">span</span> · <sub title="CASE-10c sub title">sub</sub>
