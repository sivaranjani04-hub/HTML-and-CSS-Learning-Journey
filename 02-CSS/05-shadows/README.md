# CSS Shadows

## What is it?
`text-shadow` adds a shadow behind text and `box-shadow` adds a shadow around an element box.

## Syntax
```css
h1  { text-shadow: 2px 2px 4px gray; }
div { box-shadow: 5px 5px 10px 2px gray; }
```

## Important attributes/properties
- `horizontal offset` – first value (right/left)
- `vertical offset` – second value (down/up)
- `blur` – third value
- `spread` – fourth value (box-shadow only)
- `color` – last value
- `inset` – shadow inside the box

## Examples
- `01-text-shadow.html` – simple, blurred, glow and multiple text shadows
- `02-box-shadow.html` – offset, blur, spread, colour, inset and hover

## Key takeaway
- Order: x y blur (spread) colour.
- Negative offsets move the shadow left/up.
- Use `rgba()` for soft shadows.
