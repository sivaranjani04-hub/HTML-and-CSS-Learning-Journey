# Span and Div

## What is it?
`<div>` and `<span>` are generic containers with no meaning of their own. `<div>` is a block-level container and `<span>` is an inline container. They are mostly used together with CSS.

## Syntax
```html
<div class="box">Block container</div>
<p>Some <span class="red">inline</span> text</p>
```

## Important attributes/properties
- `div` – block-level: starts on a new line, takes full width
- `span` – inline: stays in the line, as wide as its content
- `class` – name used by CSS to style the element
- `style` – inline CSS

## Examples
- `01-span-inline.html` – span styling words inside text
- `02-div-block.html` – div as a block / card
- `03-span-vs-div.html` – side-by-side comparison
- `style.css` – colours and borders so boxes are visible

## Key takeaway
- div = block (new line); span = inline (same line).
- Use `span` to style part of a sentence, `div` to group sections.
- Neither has a visual effect until you add CSS.
