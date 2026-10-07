# CSS Image Gallery

## What is it?
An image gallery shows several pictures with descriptions. Each item is a container with an image and a caption; `inline-block` places them side by side.

## Syntax
```css
.gallery { display: inline-block; margin: 8px; border: 1px solid #ccc; }
.gallery img { width: 280px; height: 187px; }
.gallery:hover { border-color: blue; }
```

## Important attributes/properties
- `display: inline-block` – items side by side
- `width / height` – image size
- `border, margin, padding` – spacing and frame
- `:hover` – hover effect
- `target="_blank"` – open full image in new tab

## Examples
- `index.html` – gallery of 6 images
- `assets/thumbN.jpg` – small previews
- `assets/photoN.jpg` – full size images (generated placeholders - replace with your own photos)

## Key takeaway
- Wrap each image + caption in a container.
- Use small thumbnails and link to the large file.
- Replace the placeholders with your own images, keeping the same file names.
