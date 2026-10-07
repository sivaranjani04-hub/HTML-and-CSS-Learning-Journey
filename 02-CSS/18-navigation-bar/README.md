# CSS Navigation Bar

## What is it?
A navigation bar is a list of links styled as a menu. Lists (`ul > li > a`) are used so the HTML stays meaningful and CSS makes them look like a bar.

## Syntax
```css
ul { list-style-type: none; margin: 0; padding: 0; overflow: hidden; background: #333; }
li { float: left; }
li a { display: block; padding: 14px 18px; color: white; }
```

## Important attributes/properties
- `list-style-type: none` – remove bullets
- `margin / padding: 0` – remove default spacing
- `float: left` – horizontal layout
- `display: block` – make the whole area clickable
- `:hover` – hover colour
- `.active` – current page

## Examples
- `index.html, about.html, products.html, contact.html` – 4 linked pages with the same navbar
- `vertical.html` – vertical navigation
- `style.css` – styles

## Key takeaway
- Build menus with `ul`, `li` and `a`.
- `display: block` on links makes the whole box clickable.
- Mark the current page with `.active`.
