# CSS Height and Width

## What is it?
`width` and `height` set the size of an element. Use `min-` and `max-` versions to make sizes flexible, and `box-sizing` to control how padding and border are counted.

## Syntax
```css
div {
  width: 50%;
  max-width: 400px;
  height: 100px;
  box-sizing: border-box;
}
```

## Important attributes/properties
- `width / height` – size
- `max-width / max-height` – upper limit
- `min-width / min-height` – lower limit
- `px, %, vh, vw` – units
- `auto` – browser decides
- `box-sizing` – `content-box` or `border-box`

## Examples
- `01-width-height-units.html` – px, %, auto, vw, vh
- `02-min-max.html` – min and max
- `03-box-sizing.html` – content-box vs border-box

## Key takeaway
- `%` is relative to the parent; `vw`/`vh` to the screen.
- `max-width` makes images and boxes responsive.
- Most projects use `box-sizing: border-box`.
