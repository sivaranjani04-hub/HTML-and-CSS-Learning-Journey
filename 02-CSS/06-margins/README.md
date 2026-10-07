# CSS Margins

## What is it?
Margin is the empty space OUTSIDE an element's border. It pushes other elements away.

## Syntax
```css
div {
  margin: 10px 20px 30px 40px; /* top right bottom left */
}
div { margin: 0 auto; }  /* centre a block with a width */
```

## Important attributes/properties
- `margin-top/right/bottom/left` – one side
- `margin` – shorthand: 1 to 4 values
- `auto` – centres a block element that has a width

## Examples
- `01-margin-sides.html` – four separate sides
- `02-shorthand.html` – 1, 2, 3, 4 value shorthand
- `03-auto-centering.html` – `margin: 0 auto`

## Key takeaway
- Shorthand goes clockwise: top, right, bottom, left.
- Margin = outside space, padding = inside space.
- `margin: 0 auto` centres a block with a fixed width.
