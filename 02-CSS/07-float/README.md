# CSS Float

## What is it?
`float` moves an element to the left or right so that text wraps around it (like an image in a newspaper).

## Syntax
```css
img {
  float: left;
  margin: 0 15px 10px 0;
}
.clear { clear: both; }
```

## Important attributes/properties
- `float` – `left`, `right`, `none`
- `margin` – space between float and text
- `clear` – `both` stops wrapping
- `overflow: auto` – makes a parent contain floated children

## Examples
- `01-float-left-right.html` – image with wrapping text
- `02-clearing-floats.html` – collapsed parent and two fixes
- `03-float-layout.html` – sidebar + content layout using float

## Key takeaway
- Floated elements leave the normal flow.
- Use `clear: both` or `overflow: auto` to contain floats.
- Modern layouts use Flexbox (topic 22), but float is still good for wrapping text.
