<a id="top"></a>

# Copy and anchor test

## Glossary (quick pick)

| | id | job | |
|---|---|---|---|
| <a id="g-fill-base"></a> | `fill-base` | page background | [↓](#fill-base) |
| <a id="g-fill-raised"></a> | `fill-raised` | surface above the page | [↓](#fill-raised) |
| <a id="g-text-base"></a> | `text-base` | default text | [↓](#text-base) |

## Option A: fenced block per kind

```
fill-base
fill-raised
```

```
text-base
```

## Option B: HTML pre inside a table cell

| id | job |
|---|---|
| <pre>fill-base</pre> | page background |
| <pre lang="text">fill-raised</pre> | surface |

## Option C: fenced block in a list item

- fill-base
  ```
  fill-base
  ```

## Option D: inline code only

`fill-base` and `text-base`

## Option E: code block inside table cell via HTML

| id | job |
|---|---|
| <div class="highlight"><pre>fill-base</pre></div> | page background |

## Detail table

| | id | job | use / don't use | |
|---|---|---|---|---|
| [↑](#g-fill-base) | <a id="fill-base"></a>`fill-base` | page background | root canvas | [↑](#g-fill-base) |
| [↑](#g-fill-raised) | <a id="fill-raised"></a>`fill-raised` | surface above the page | cards, panels | [↑](#g-fill-raised) |
| [↑](#g-text-base) | <a id="text-base"></a>`text-base` | default text | body copy | [↑](#g-text-base) |

[Back to top](#top)
