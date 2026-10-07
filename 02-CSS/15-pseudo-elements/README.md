# CSS Pseudo-elements

## What is it?
A pseudo-element styles a specific PART of an element (first letter, first line, selected text) or inserts content before/after it.

## Syntax
```css
p::first-letter { font-size: 3em; }
.note::before { content: "⚠ "; }
li::marker { color: red; }
```

## Important attributes/properties
- `::first-letter / ::first-line` – style the start of text
- `::selection` – highlighted text
- `::before / ::after` – insert content
- `content` – required for before/after
- `::marker` – list bullet/number

## Examples
- `01-first-letter-line.html` – drop cap and first line
- `02-selection.html` – selection colour
- `03-before-after.html` – symbols and emojis with content
- `04-marker.html` – styled list markers

## Key takeaway
- Pseudo-elements use TWO colons (`::`).
- `::before` and `::after` need `content`.
- The inserted content is not in the HTML.
