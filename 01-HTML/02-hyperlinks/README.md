# HTML Hyperlinks

## What is it?
The `<a>` (anchor) element creates a hyperlink that lets users move to another webpage, file, location or email address.

## Syntax
```html
<a href="https://example.com">Visit Example</a>
```

## Important attributes/properties
- `href` – the destination (absolute URL, relative URL or `mailto:`)
- `target="_blank"` – open in a new tab
- `rel="noopener"` – safety when using `_blank`
- `title` – tooltip text on hover
- `mailto:` – opens the email app

## Examples
- `01-external-link.html` – absolute URLs to other websites
- `02-relative-link.html` – links to files in your own project
- `03-target-blank.html` – open in new tab
- `04-title-attribute.html` – tooltip
- `05-email-link.html` – mailto links
- `06-image-link.html` – clickable image
- `07-button-link.html` – button used as a link
- `pages/about.html` – the page the examples link to

## Key takeaway
- `href` is the most important attribute.
- Absolute URL = full address; relative URL = path inside your project.
- `target="_blank"` opens a new tab.
- Wrap an `<img>` or `<button>` in `<a>` to make it clickable.
