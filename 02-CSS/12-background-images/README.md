# CSS Background Images

## What is it?
`background-image` puts a picture behind an element. Other properties control repeating, position, size and scrolling behaviour.

## Syntax
```css
div {
  background-image: url("assets/background.jpg");
  background-repeat: no-repeat;
  background-position: center;
  background-size: cover;
}
```

## Important attributes/properties
- `background-image` – `url("path")`
- `background-repeat` – `repeat`, `no-repeat`, `repeat-x`, `repeat-y`
- `background-position` – `center`, `top left`, ...
- `background-attachment` – `scroll` or `fixed`
- `background-size` – `cover`, `contain`, px

## Examples
- `01-background-image-repeat.html` – repeat options
- `02-position-size.html` – position, cover, contain
- `03-fixed-attachment.html` – fixed background

## Key takeaway
- The path in `url()` is relative to the CSS file.
- `cover` fills the box; `contain` shows the whole image.
- Set a `background-color` as a fallback.
