# HTML Text Formatting

## What is it?
Formatting elements change how text looks or what it means: bold, italic, underline, deleted text, small/big text, subscript, superscript, monospace and highlighted text.

## Syntax
```html
<b>bold</b> <strong>important</strong> <i>italic</i> <em>emphasis</em> <u>underline</u>
<del>deleted</del> <small>small</small> H<sub>2</sub>O x<sup>2</sup> <mark>highlight</mark>
```

## Important attributes/properties
- `<b> / <strong>` – bold / important
- `<i> / <em>` – italic / emphasis
- `<u>` – underline
- `<del>` – strike-through
- `<small>, <big>` – smaller / bigger (`big` is deprecated)
- `<sub>, <sup>` – subscript / superscript
- `<tt>` – monospace (deprecated, use `<code>`)
- `<mark>` – highlight; change colour with `style="background-color:..."`

## Examples
- `01-bold-italic-underline.html` – b, strong, i, em, u
- `02-delete-small-big.html` – del, small, big
- `03-sub-sup.html` – sub, sup
- `04-tt-mark.html` – tt and mark

## Key takeaway
- `<strong>` and `<em>` carry meaning; `<b>` and `<i>` are only visual.
- `<big>` and `<tt>` are old – prefer CSS and `<code>`.
- `<mark>` is a highlighter.
