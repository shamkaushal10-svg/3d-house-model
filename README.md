# 3D House Model

Interactive 3D contemporary villa visualizer for a Kerala-style residential elevation. The project renders a modern Habrick villa in WebGL and lets users explore materials, lighting, camera angles, landscaping, and pool options directly in the browser.

## Features

- Full-screen Three.js 3D villa scene
- Orbit, zoom, and pan camera controls
- Preset camera views for isometric, front elevation, carport, balcony, and pool areas
- Exterior paint finish selector
- Timber accent selector for louvers and entry door
- Glass tint selector for windows and balcony glazing
- Daylight, sunset, and midnight lighting presets
- Toggleable landscaping and splash pool
- Interactive architectural hotspots
- Lead inquiry form UI for design consultation requests
- Responsive layout for desktop and mobile screens

## Tech Stack

- HTML5
- CSS3
- JavaScript
- Three.js
- OrbitControls
- GSAP
- Font Awesome
- Google Fonts

## Project Structure

```text
3d-house-model/
├── index.html
└── README.md
```

## Run Locally

No build step is required. Open `index.html` directly in a browser, or serve the folder with a local static server.

```bash
cd /home/sham/3d-house-model
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Browser Requirements

Use a modern browser with WebGL support, such as Chrome, Edge, Firefox, or Safari.

## Notes

External assets load from CDNs:

- Three.js
- OrbitControls
- GSAP
- Font Awesome
- Google Fonts

Internet access is required for those CDN resources unless they are replaced with local files.
