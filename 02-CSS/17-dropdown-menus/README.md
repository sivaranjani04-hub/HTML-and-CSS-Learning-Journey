# CSS Dropdown Menus

## What is it?
A dropdown menu shows a list of links when the user hovers over a button. It uses `display: none` by default and `display: block` on hover.

## Syntax
```css
.dropdown-content { display: none; position: absolute; }
.dropdown:hover .dropdown-content { display: block; }
```

## Important attributes/properties
- `.dropdown` – container with `position: relative`
- `.dropbtn` – button
- `.dropdown-content` – hidden list
- `display: none / block` – hide / show
- `position: absolute` – floats the list under the button

## Examples
- `index.html` – two working dropdown menus
- `style.css` – styles

## Key takeaway
- Hide with `display: none`, show on `:hover`.
- The parent needs `position: relative`.
- Content uses `position: absolute` so it does not push the page.
