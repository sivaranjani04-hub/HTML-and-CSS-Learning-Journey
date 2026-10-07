# HTML Images

## What is it?
The `<img>` element shows a picture on the page. It is a self-closing element that needs the file location (`src`) and a text description (`alt`).

## Syntax
```html
<img src="assets/dog.jpg" alt="A cartoon dog" width="300">
```

## Important attributes/properties
- `src` – path to the image file
- `alt` – text description for accessibility / broken images
- `width / height` – size in pixels
- `PNG / JPG / GIF` – common image formats (GIF can animate)

## Examples
- `01-basic-image.html` – simplest image
- `02-image-width-height.html` – resizing
- `03-alt-text.html` – alt text
- `04-image-as-link.html` – clickable image
- `05-gif-image.html` – animated GIF
- `06-relative-image-path.html` – paths to nested folders

## Key takeaway
- Always write a meaningful `alt`.
- Use relative paths such as `assets/dog.jpg`.
- Set only width OR height to avoid stretching.
- JPG for photos, PNG for graphics, GIF for simple animations.
