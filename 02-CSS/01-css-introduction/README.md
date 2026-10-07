# CSS Introduction

## What is it?
CSS (Cascading Style Sheets) controls how HTML looks: colours, fonts, spacing and layout. You can add CSS inline, internally or from an external file.

## Syntax
```css
selector {
  property: value;
}

/* link an external file */
<link rel="stylesheet" href="style.css">
```

## Important attributes/properties
- `style attribute` – inline CSS on one element
- `<style>` – internal CSS in the head
- `<link rel="stylesheet" href="...">` – external CSS file
- `element selector` – `p { }`
- `#id selector` – `#intro { }`
- `.class selector` – `.note { }`

## Examples
- `01-inline-css.html` – style attribute
- `02-internal-css.html` – `<style>` tag + element selector
- `03-external-css/` – external `style.css`
- `04-id-selector/` – id selector
- `05-class-selector/` – class selector

## Key takeaway
- External CSS is best: one file styles the whole site.
- `id` = unique (`#`), `class` = reusable (`.`).
- Inline CSS has the highest priority but is hard to maintain.
