# CSS Pagination

## What is it?
Pagination is a row of links (Previous, 1, 2, 3, Next) used to move between pages. CSS makes the links look like buttons and highlights the active page.

## Syntax
```css
.pagination a { padding: 8px 16px; border: 1px solid #ddd; }
.pagination a.active { background: #3f51b5; color: white; }
.pagination a:hover:not(.active) { background: #ddd; }
```

## Important attributes/properties
- `.pagination` – container
- `a` – page links
- `.active` – current page
- `:hover` – hover effect
- `float / inline-block` – puts links on one line

## Examples
- `index.html` – page 1
- `page2.html` – page 2
- `page3.html` – page 3
- `page4.html` – page 4
- `style.css` – shared pagination styles

## Key takeaway
- Each page is a separate HTML file linked together.
- The `.active` class moves to the current page in each file.
- `:hover:not(.active)` avoids changing the active page on hover.
