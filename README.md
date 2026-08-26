# Help-Deck

**CineVision Toolkit** — a single-file, client-side cinematography analysis workspace for
filmmakers, cinematographers, and photographers.

Open `index.html` in a browser (or deploy the folder). No backend, no build step, works offline.

## Features
- Frame it: aspect-ratio letterbox mattes (2.39, 2.00, 1.85, 16:9, 4:3, 1:1, 9:16, custom)
- Compose: rule of thirds, golden ratio grid + Fibonacci spiral, dynamic-symmetry armature,
  golden triangle, center crosshair, symmetry axes, action/title/custom safe areas
- Expose: real per-pixel false-color monitor, RGB/luminance histogram, exposure statistics
- Color: dominant/tonal palette extraction, eyedropper with pinned samples, temperature estimate
- Analyze: composition balance, sharpness, contrast, negative-space heuristics
- Annotate: arrows, shapes, freehand, text, measurement — undo/redo, exported in PNG snapshots
- **Live camera viewfinder** with all overlays in real time, pinch-to-zoom, torch, and frame capture

> The live camera needs a secure context (`https://` or a locally opened file).

## Deploy
Static site — deploy the folder to any host. On Vercel it serves `index.html` at the root with
no configuration.
