# CSS Fonts

## What is it?
CSS controls the typeface, size, weight and style of text. You can use system fonts, Google Fonts (from the internet) or your own font files with `@font-face`.

## Syntax
```css
p {
  font-family: Arial, sans-serif;
  font-size: 18px;
  font-weight: bold;
  font-style: italic;
}

@font-face {
  font-family: "MyFont";
  src: url("assets/fonts/MyFont.ttf");
}
```

## Important attributes/properties
- `font-family` – font list with fallbacks
- `font-size` – `px` or `em`
- `font-weight` – `normal`, `bold`, 100–900
- `font-style` – `italic`, `oblique`
- `@font-face` – use your own font file
- `Google Fonts` – `<link>` to fonts.googleapis.com

## Examples
- `01-font-family.html` – fallback fonts
- `02-font-size.html` – px and em
- `03-weight-and-style.html` – weight and style
- `04-google-fonts.html` – Google Fonts (internet needed)
- `05-font-face-local.html` – local font in `assets/fonts/` (Pacifico, SIL Open Font License)

## Key takeaway
- Always add a generic fallback (`sans-serif`, `serif`, ...).
- `em` is relative, `px` is fixed.
- Local fonts work offline; Google Fonts need internet.
