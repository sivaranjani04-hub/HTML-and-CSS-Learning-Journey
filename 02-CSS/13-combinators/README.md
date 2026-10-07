# CSS Combinators

## What is it?
Combinators describe the relationship between two selectors: descendant (space), child (`>`), general sibling (`~`) and adjacent sibling (`+`).

## Syntax
```css
div p   { }  /* descendant */
div > p { }  /* child */
h2 ~ p  { }  /* general sibling */
h2 + p  { }  /* adjacent sibling */
```

## Important attributes/properties
- `space` – all descendants
- `>` – direct children only
- `~` – all later siblings
- `+` – only the next sibling

## Examples
- `01-descendant.html` – space
- `02-child.html` – >
- `03-general-sibling.html` – ~
- `04-adjacent-sibling.html` – +
- `05-comparison.html` – all four together

## Key takeaway
- Child (`>`) is stricter than descendant (space).
- Siblings share the same parent and come AFTER.
- `+` = one element, `~` = all following elements.
