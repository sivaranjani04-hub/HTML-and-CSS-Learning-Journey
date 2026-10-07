# CSS Icons (Font Awesome)

## What is it?
Icons can be added with an icon library. This example uses Font Awesome Free, which is stored locally in `assets/fontawesome/` so it works offline.

## Syntax
```html
<link rel="stylesheet" href="assets/fontawesome/css/all.min.css">
<i class="fa-solid fa-house"></i>
<i class="fa-brands fa-youtube"></i>
```

## Important attributes/properties
- `fa-solid / fa-brands` – icon style
- `fa-house, fa-youtube, fa-x-twitter, fa-tiktok` – icon name
- `font-size` – icon size
- `color` – icon colour
- `:hover` – hover colour
- `margin` – spacing between icons

## Examples
- `01-icons-basic.html` – home, X/Twitter, YouTube, TikTok and more
- `02-size-color-hover.html` – size, colour, hover and spacing

## Key takeaway
- Dependency: Font Awesome Free (v7) – icons are fonts, so `font-size` and `color` work on them.
- Files in `assets/fontawesome/` (css + webfonts) must stay together.
- Font Awesome Free is licensed under CC BY 4.0 (icons), SIL OFL 1.1 (fonts) and MIT (code); see `assets/fontawesome/LICENSE.txt`.
- Alternative: use the official CDN kit from fontawesome.com (needs internet and an account).
