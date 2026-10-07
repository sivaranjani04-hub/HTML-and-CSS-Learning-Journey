# CSS Display

## What is it?
`display` controls how an element is laid out: as a block, inline text, or inline-block. `display: none` removes it from the page.

## Syntax
```css
div { display: block; }
span { display: inline-block; width: 100px; }
.hidden { display: none; }
```

## Important attributes/properties
- `block` – starts on a new line, full width, accepts width/height
- `inline` – flows with text, ignores width/height
- `inline-block` – flows with text but accepts width/height
- `none` – element removed

## Examples
- `01-block-inline-inline-block.html` – visual comparison
- `02-display-none.html` – display none vs visibility hidden
- `03-changing-defaults.html` – turning links into blocks and list items into inline-blocks

## Key takeaway
- Block = new line; inline = same line.
- Inline elements ignore width and height.
- `inline-block` gives you both.
