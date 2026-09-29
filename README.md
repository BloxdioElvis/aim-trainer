# Strafe — Aim Laboratory

A focused, browser-based aim trainer designed around fast feedback and measurable improvement. It runs entirely in the browser with no account, server, or build step required.

## Features

- **Five drills:** Flick Standard, Flow Tracking, Reaction Test, Target Switch, and Precision.
- **Canvas gameplay:** requestAnimationFrame rendering, device-pixel-ratio scaling, lightweight target management, and no gameplay DOM churn.
- **Full local persistence:** settings, crosshair configuration, personal bests, and mode breakdowns are stored in localStorage.
- **Crosshair editor:** color, size, thickness, gap, opacity, center dot, and quick presets.
- **Session results:** score, hits, misses through shot counts, accuracy, reaction time, targets/second, and personal-best detection.
- **Data portability:** export and import settings and records as JSON.
- **Responsive dark UI:** works on desktop and smaller displays, with fullscreen support.

## Run locally

This is a static web app. You can open `index.html` directly, or serve the directory with any static server:

```bash
python3 -m http.server 8080
```

Then open `http://localhost:8080`.

## Controls

- **Right mouse button:** shoot
- **Mouse movement:** aim naturally via the cursor
- **Esc:** pause / resume
- **F:** fullscreen

The context menu is prevented on the game canvas so right-click shooting remains uninterrupted.

## Browser support

Use a current version of Chrome, Edge, Firefox, or Safari. The app uses standard Canvas 2D, ES modules, localStorage, FileReader, and the Fullscreen API.

## License

MIT
