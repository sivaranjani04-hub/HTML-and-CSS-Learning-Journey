# HTML Buttons

## What is it?
The `<button>` element creates a clickable button. With CSS you can change its size, colours and shape. A button can act as a link, and `onclick` can run a small piece of JavaScript.

## Syntax
```html
<button>Click me</button>
<a href="page.html"><button>Go</button></a>
<button onclick="alert('Hi')">Alert</button>
```

## Important attributes/properties
- `button` – the button element
- `font-size` – text size
- `background-color` – button colour
- `color` – text colour
- `border-radius` – rounded corners
- `onclick` – JavaScript to run on click (only used in example 05)
- `disabled` – makes the button unclickable

## Examples
- `01-basic-button.html` – plain buttons
- `02-styled-button.html` – inline style and class styling
- `03-button-link.html` – button as an external link
- `04-button-to-page.html + next-page.html` – button linking to another HTML page
- `05-onclick-javascript.html` – onclick demo

## Key takeaway
- Wrap a button in `<a>` to make it a link.
- Style buttons with CSS classes.
- `onclick` is the only JavaScript in this repo.
