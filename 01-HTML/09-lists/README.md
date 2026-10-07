# HTML Lists

## What is it?
Lists group related items. HTML has bullet lists (`<ul>`), numbered lists (`<ol>`) and description lists (`<dl>`). Lists can be placed inside other lists (nested).

## Syntax
```html
<ul>
  <li>Item</li>
</ul>
<ol>
  <li>Item</li>
</ol>
<dl>
  <dt>Term</dt>
  <dd>Description</dd>
</dl>
```

## Important attributes/properties
- `ul` – unordered (bullet) list
- `ol` – ordered (numbered) list; `type`, `start`
- `li` – list item
- `dl / dt / dd` – description list, term, definition
- `list-style-type` – CSS to change bullets

## Examples
- `01-unordered-list.html` – bullets
- `02-ordered-list.html` – numbers, letters, roman
- `03-nested-list.html` – lists inside lists
- `04-description-list.html` – dl, dt, dd

## Key takeaway
- `<li>` always lives inside `<ul>` or `<ol>`.
- Nested list goes inside an `<li>`.
- `<dl>` is for term + description pairs.
