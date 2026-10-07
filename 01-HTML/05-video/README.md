# HTML Video

## What is it?
The `<video>` element plays video files directly in the browser without any plugin.

## Syntax
```html
<video width="320" controls>
  <source src="assets/video/sample.mp4" type="video/mp4">
  <source src="assets/video/sample.webm" type="video/webm">
</video>
```

## Important attributes/properties
- `controls` – show player controls
- `width / height` – size in pixels
- `autoplay + muted` – auto start silently
- `loop` – repeat
- `poster` – image shown before playing
- `type` – `video/mp4`, `video/webm`

## Examples
- `01-basic-video.html` – simplest video
- `02-width-height.html` – sizing
- `03-autoplay-muted-loop.html` – autoplay, muted, loop
- `04-multiple-sources.html` – MP4 + WebM fallback
- `05-video-link.html` – linking to a video, `target="_blank"`

## Key takeaway
- MP4 is the safest format; add WebM as a fallback.
- Autoplay requires `muted`.
- `assets/video/sample.*` are small generated test clips – replace them with your own.
