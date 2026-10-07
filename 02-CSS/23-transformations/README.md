# CSS Transformations

## What is it?
`transform` moves, rotates, scales or skews an element without affecting the layout of other elements. Several transforms can be combined in one property.

## Syntax
```css
.box {
  transform: translate(20px, 10px) rotate(15deg) scale(1.2);
}
```

## Important attributes/properties
- `translateX/Y, translate` – move
- `rotate` – turn (deg)
- `scale, scaleX, scaleY` – resize
- `skew, skewX, skewY` – slant
- `multiple values` – space-separated, applied right-to-left in effect

## Examples
- `01-translate.html` – translateX, translateY, translate
- `02-rotate.html` – rotate
- `03-scale.html` – scale, scaleX, scaleY
- `04-skew.html` – skew
- `05-multiple-transforms.html` – combining transforms and order

## Key takeaway
- `transform` does not move neighbours.
- Combine functions in a single `transform` line.
- The order of functions changes the result.
