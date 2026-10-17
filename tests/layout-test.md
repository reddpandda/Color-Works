<a id="top"></a>

# Layout test

## Glossary grid (ids only, columns by kind)

| fill | text | icon | line | ring | font |
|---|---|---|---|---|---|
| <a id="g-fill-base"></a>`fill-base` [↓](#fill-base) | <a id="g-text-base"></a>`text-base` [↓](#text-base) | <a id="g-icon-base"></a>`icon-base` [↓](#icon-base) | <a id="g-line-base"></a>`line-base` [↓](#line-base) | <a id="g-ring-focus"></a>`ring-focus` [↓](#ring-focus) | <a id="g-font-body"></a>`font-body` [↓](#font-body) |
| <a id="g-fill-raised"></a>`fill-raised` [↓](#fill-raised) | <a id="g-text-muted"></a>`text-muted` [↓](#text-muted) | <a id="g-icon-muted"></a>`icon-muted` [↓](#icon-muted) | <a id="g-line-strong"></a>`line-strong` [↓](#line-strong) | | <a id="g-font-heading"></a>`font-heading` [↓](#font-heading) |
| <a id="g-fill-raised-hover"></a>`fill-raised-hover` [↓](#fill-raised-hover) | <a id="g-text-danger"></a>`text-danger` [↓](#text-danger) | | | | |

---

## Detail as plain text

### Variant 1: arrows in a three-cell table row

| | | |
|:--|:--:|--:|
| [↑](#g-fill-base) | <a id="fill-base"></a>**`fill-base`** | [↑](#g-fill-base) |

Job: page background.
Use: root canvas. Don't use: cards.
Pairs with: `text-base`.
Default: none.

```
fill-base
```

### Variant 2: heading with left arrow, right arrow aligned by HTML

<h4 id="fill-raised"><a href="#g-fill-raised">↑</a> fill-raised <span style="float:right"><a href="#g-fill-raised">↑</a></span></h4>

Job: surface above the page.

```
fill-raised
```

### Variant 3: HTML div with align

<div align="left"><a href="#g-fill-raised-hover">↑</a> <a id="fill-raised-hover"></a><b><code>fill-raised-hover</code></b></div>
<div align="right"><a href="#g-fill-raised-hover">↑</a></div>

Job: raised surface under pointer.

```
fill-raised-hover
```

### Variant 4: plain heading, one arrow

#### [↑](#g-text-base) `text-base` <a id="text-base"></a>

Job: default text.

```
text-base
```

### Variant 5: blockquote-free line with non-breaking spacing

[↑](#g-text-muted)&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;<a id="text-muted"></a>**`text-muted`**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;[↑](#g-text-muted)

Job: supporting text.

```
text-muted
```
