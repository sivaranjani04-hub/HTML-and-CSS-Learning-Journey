# CSS Flexbox

## What is it?
Flexbox is a one-dimensional layout system. Put `display: flex` on a parent and its children (flex items) can be aligned, spaced, wrapped and resized easily.

## Syntax
```css
.container {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  gap: 10px;
}
.item { flex: 1; }
```

## Important attributes/properties
- `display: flex` – creates a flex container
- `flex-direction` – row, row-reverse, column, column-reverse
- `justify-content` – main-axis alignment: flex-start, flex-end, center, space-between, space-around, space-evenly
- `align-items` – cross-axis alignment
- `align-self` – align a single item
- `flex-wrap / align-content` – wrapping and spacing of lines
- `gap` – space between items
- `flex-grow / flex-shrink / flex-basis` – item sizing
- `order` – visual order

## Examples
- `01-flex-container.html` – display flex
- `02-flex-direction.html` – direction
- `03-justify-content.html` – justify-content values
- `04-align-items.html` – align-items values
- `05-flex-wrap.html` – wrap and align-content
- `06-gap.html` – gap
- `07-align-self.html` – align-self
- `08-flex-grow-shrink.html` – grow, shrink, basis
- `09-order.html` – order
- `10-flexbox-complete-example.html` – navbar + cards + footer

## Key takeaway
- Container properties go on the parent, item properties on the children.
- `justify-content` = main axis, `align-items` = cross axis.
- `flex: 1` makes items share space equally.
- Each example has its own `.css` file with the same name.
