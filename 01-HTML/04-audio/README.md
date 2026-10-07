# HTML Audio

## What is it?
The `<audio>` element plays sound on a web page. You can offer several file formats with `<source>` so that every browser finds one it can play.

## Syntax
```html
<audio controls>
  <source src="assets/audio/melody.mp3" type="audio/mpeg">
  <source src="assets/audio/melody.wav" type="audio/wav">
</audio>
```

## Important attributes/properties
- `controls` – show play/pause/volume
- `autoplay` – start automatically (needs `muted` in most browsers)
- `muted` – start silent
- `loop` – repeat forever
- `src` – file path
- `type` – MIME type: `audio/mpeg` (MP3), `audio/wav` (WAV)

## Examples
- `01-basic-audio.html` – audio without controls is invisible
- `02-controls.html` – controls
- `03-autoplay-muted.html` – autoplay + muted
- `04-loop.html` – loop
- `05-multiple-sources.html` – MP3 + WAV fallback
- `06-relative-audio-path.html` – relative path
- `07-multiple-audio-players.html` – several players

## Key takeaway
- Add `controls` or nothing appears.
- Autoplay needs `muted`.
- Use `<source>` for fallback formats.
- The audio files are simple generated tones in `assets/audio/` – replace them with your own.
