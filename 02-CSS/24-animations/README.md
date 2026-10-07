# CSS Animations

## What is it?
CSS animations change styles gradually over time. You describe the steps with `@keyframes` and attach them to an element with the `animation` properties.

## Syntax
```css
@keyframes slide {
  from { left: 0; }
  to   { left: 300px; }
}
.ball {
  animation: slide 2s ease-in-out 0s infinite alternate forwards;
}
```

## Important attributes/properties
- `@keyframes` – defines the animation steps
- `animation-name` – which keyframes to use
- `animation-duration` – length
- `animation-iteration-count` – how many times (`infinite`)
- `animation-direction` – normal, reverse, alternate
- `animation-delay` – wait before start
- `animation-timing-function` – ease, linear, ease-in, ease-out, ease-in-out
- `animation-fill-mode` – none, forwards, backwards, both
- `animation` – shorthand

## Examples
- `01-basic-keyframes.html` – first animation
- `02-iteration-delay.html` – iteration count and delay
- `03-direction-timing.html` – direction and timing function
- `04-fill-mode.html` – fill mode
- `05-shorthand-transform.html` – shorthand + transform: spin, pulse, bounce
- `06-loader-and-color.html` – loader, colour change, hover animation

## Key takeaway
- Define with `@keyframes`, use with `animation`.
- Use `transform` inside keyframes for smooth movement.
- Use `forwards` to keep the final state.
- Animations play automatically when the page loads.
