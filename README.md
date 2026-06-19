# Neon Breach

Neon Breach is a static browser first-person game built with Three.js. It runs from a simple local web server or from GitHub Pages.

## Play locally

```powershell
cd "C:\Users\richa\OneDrive\Documentos\Unreal Projects\untitled"
node server.js
```

Open `http://localhost:5173` in a browser.

## Controls

- Move: `W`, `A`, `S`, `D`
- Look: mouse
- Shoot: left click
- Sprint: `Shift`
- Pause: `Esc`
- Refill current cell: `R`

## Goal

Collect all three reactor cores, survive the sentries, and reach the portal after it activates.

## Files

- `index.html` loads the game shell and overlays.
- `src/main.js` contains the Three.js game loop, player controls, enemies, pickups, and objectives.
- `src/styles.css` styles the full-screen browser experience.
- `src/vendor/three.module.js` forwards the browser to the Three.js runtime.
