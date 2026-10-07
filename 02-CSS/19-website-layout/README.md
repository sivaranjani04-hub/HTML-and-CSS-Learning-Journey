# Website Layout

## What is it?
A website layout divides a page into meaningful areas using semantic HTML elements. CSS then arranges them (here with a small Flexbox container).

## Syntax
```css
<header></header>
<nav></nav>
<main>
  <section></section>
  <article></article>
</main>
<aside></aside>
<footer></footer>
```

## Important attributes/properties
- `header` – top of the page
- `nav` – navigation links
- `main` – main content
- `section` – group of related content
- `article` – independent piece of content
- `aside` – side content
- `footer` – bottom of the page

## Examples
- `index.html` – complete layout
- `style.css` – layout styles including a mobile media query

## Key takeaway
- Semantic HTML helps SEO, accessibility and readability.
- Use `div` only when no semantic tag fits.
- Resize the window: below 700px the sidebar moves below the content.
