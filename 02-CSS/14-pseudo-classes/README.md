# CSS Pseudo-classes

## What is it?
A pseudo-class styles an element in a special state, such as when the mouse is over it (`:hover`) or when it is the first child.

## Syntax
```css
a:hover { color: red; }
li:first-child { font-weight: bold; }
```

## Important attributes/properties
- `:link / :visited` – unvisited / visited links
- `:hover` – mouse over
- `:active` – being clicked
- `:focus` – selected input
- `:first-child / :last-child` – first / last child
- `:nth-child(n)` – pattern like `2`, `even`, `3n`

## Examples
- `01-link-states.html` – link, visited, hover, active
- `02-focus.html` – focus
- `03-first-last-child.html` – first and last child
- `04-nth-child.html` – nth-child

## Key takeaway
- Pseudo-classes use ONE colon.
- Link order: link, visited, hover, active.
- `nth-child(even)` is great for striped tables.
