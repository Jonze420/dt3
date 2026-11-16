# DT3 – Dark Tower 3D Shooter

**Repository**: https://github.com/Jonze420/DT3

This repo holds the prototype for **DT3** (Dark Tower 3), a browser‑based 3D third‑person shooter that merges the **Tull** gameplay demo with the **Dark Tower** menu/overworld UI. It runs entirely in the browser (no install) and supports Xbox controllers as well as keyboard & mouse.

## Features
- Babylon.js 3D engine with a simple player sphere and movement.
- Gamepad API support for Xbox controllers.
- Dark Tower hub UI (to be integrated) launches the game scene.
- Procedural wave/level generation (planned).
- Unlockable gear, daily challenges, and leaderboards (future).

## Getting Started
```bash
# Clone the repo
git clone https://github.com/Jonze420/DT3.git
cd DT3

# Install dependencies (Node, Vite, Babylon.js)
npm install

# Development server (Vite)
npm run dev
```

Open http://localhost:5173 (or the port printed) to see the game.

## Project Structure
```
DT3/
├─ src/
│  └─ game/
│     ├─ index.html   # Canvas and Babylon.js CDN
│     └─ main.ts       # Engine, scene, controls
├─ design_dt3.md       # Detailed design outline (artifact)
├─ README.md           # This file
└─ .gitignore          # Node & build artefacts
```

## Contributing
Feel free to open issues or PRs to add features, improve graphics, or integrate the Dark Tower UI.
