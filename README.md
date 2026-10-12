# Manash's Observatory

A cinematic, interactive space playground that runs entirely in the browser. No build step, no dependencies: one `index.html`.

## What you can do

- **Travel:** scroll through a living starfield and shifting nebula. Hold `W` to warp.
- **Scale of the universe:** slide from a hydrogen atom to the observable universe and see how long light takes to cross each size.
- **Time dilation:** approach a black hole and watch your clock fall behind the one back home. Try the Miller's planet preset.
- **Wormhole:** steer the tunnel with your pointer, hold to dive, and emerge near a different galaxy.
- **Gravity sandbox:** throw planets, plant stars and change the strength of gravity.
- **Drake equation:** adjust seven guesses and see how many civilisations might be out there.
- **Hidden anomalies:** seven faint glowing dots hide true space facts. Your discoveries are remembered in your browser.
- **Crop screenshot:** drag a rectangle over the page to capture it as a PNG (see notes below).
- **Sound:** an ambient drone and small tones. Sound starts off.

## Run it

Open `index.html` in any modern browser. An internet connection is only needed for the Google Fonts (Sora and Inter); the page falls back to system fonts offline.

## Notes

- **Screenshot crop:** it captures the starfield and the experiment canvases (black hole, wormhole, gravity). Frosted text panels are HTML and are not included. When opened locally, the Download button saves the PNG. On some hosted pages downloads are blocked, so right-click or long-press the preview image to save it.
- Facts in the page are simplified for readability. The Drake equation values are illustrative guesses, not measurements.
- Respects `prefers-reduced-motion`.

## Tech

Plain HTML, CSS and JavaScript with Canvas 2D, Web Audio and CSS backdrop-filter. No frameworks.

## License

MIT. See `LICENSE`.
