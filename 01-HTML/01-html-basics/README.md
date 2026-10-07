# HTML Basics

## What is it?
Every web page is built from HTML elements. This topic covers the basic skeleton of a page (`DOCTYPE`, `html`, `head`, `title`, `body`) and the most common text elements (headings, paragraphs, line breaks, horizontal lines, preformatted text and comments).

## Syntax
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Page title</title>
  </head>
  <body>
    <h1>Heading</h1>
    <p>Paragraph</p>
  </body>
</html>
```

## Important attributes/properties
- `<!DOCTYPE html>` – declares the page as HTML5
- `<html>` – root element that wraps the whole page
- `<head>` – page information (not shown on the page)
- `<title>` – text on the browser tab
- `<body>` – visible content
- `<h1>–<h6>` – headings, largest to smallest
- `<p>` – paragraph
- `<br>` – line break
- `<hr>` – horizontal line
- `<pre>` – keeps spacing as typed
- `<!-- -->` – comment

## Examples
- `01-basic-structure.html` – the minimal page skeleton
- `02-head-and-title.html` – head and title
- `03-headings.html` – h1 to h6
- `04-paragraphs.html` – paragraphs
- `05-line-break.html` – `<br>`
- `06-horizontal-rule.html` – `<hr>`
- `07-preformatted-text.html` – `<pre>`
- `08-comments.html` – HTML comments

## Key takeaway
- Every page needs `<!DOCTYPE html>`, `<html>`, `<head>` and `<body>`.
- Use one `<h1>` per page, then `<h2>`–`<h6>` for sub-sections.
- `<br>` and `<hr>` have no closing tag.
- Comments are for you, not for the visitor.
