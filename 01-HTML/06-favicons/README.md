# Favicons

## What is it?
A favicon is the small icon shown in the browser tab. You add it with a `<link>` element inside `<head>`.

## Syntax
```html
<link rel="icon" type="image/png" href="assets/images/favicon.png">
```

## Important attributes/properties
- `rel="icon"` – says this link is the site icon
- `type` – file format (`image/png`, `image/svg+xml`, `image/x-icon`)
- `href` – relative path to the icon file

## Examples
- `01-favicon.html` – PNG favicon
- `02-svg-and-ico.html` – SVG and ICO favicons

## Key takeaway
- Favicon goes in `<head>`.
- Keep icons in `assets/images/`.
- Browsers cache favicons – refresh hard (Ctrl+F5) if you do not see changes.
