# CSS Overflow

## What is it?
`overflow` decides what happens when content is bigger than its box: show it, cut it, or add scrollbars.

## Syntax
```css
div {
  width: 200px;
  height: 100px;
  overflow: auto;
}
```

## Important attributes/properties
- `visible` – default: content spills out
- `hidden` – extra content is cut
- `clip` – cut, no scrolling at all
- `scroll` – always show scrollbars
- `auto` – scrollbars only if needed
- `overflow-x / overflow-y` – control one direction
- `overflow-clip-margin` – how far past the box `clip` allows

## Examples
- `01-visible-hidden-clip.html` – visible, hidden, clip, overflow-clip-margin
- `02-scroll-auto.html` – scroll vs auto
- `03-overflow-x-y.html` – one direction only

## Key takeaway
- Overflow only matters when the box has a fixed height/width.
- `auto` is usually better than `scroll`.
- `hidden` can lose content, so be careful.
