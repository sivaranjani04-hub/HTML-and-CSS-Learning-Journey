# CSS Position

## What is it?
`position` controls how an element is placed on the page. Together with `top`, `right`, `bottom`, `left` and `z-index` you can move elements around or pin them.

## Syntax
```css
div {
  position: absolute;
  top: 10px;
  right: 20px;
  z-index: 2;
}
```

## Important attributes/properties
- `static` – default, normal flow
- `relative` – offset from its normal place
- `absolute` – placed inside the nearest positioned parent
- `fixed` – pinned to the window
- `sticky` – scrolls then sticks
- `top/right/bottom/left` – offsets
- `z-index` – stacking order

## Examples
- `01-static.html` – default
- `02-relative.html` – relative offset
- `03-absolute.html` – absolute inside a relative parent
- `04-fixed.html` – fixed to the window
- `05-sticky.html` – sticky header
- `06-z-index.html` – overlapping boxes

## Key takeaway
- Make the parent `position: relative` before using `absolute` children.
- `fixed` and `sticky` need scrolling to see the effect.
- `z-index` needs a positioned element.
