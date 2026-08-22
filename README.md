# Pure JS Raycaster

A Wolfenstein-3D-style raycasting engine written in plain JavaScript + Canvas — no libraries, no build step, one file. This is the kind of thing people usually reach for C/C++ to write: it casts a ray per screen column against a grid map, fixes fisheye distortion, and shades walls by distance to fake 3D from a 2D map array.

## Run
Open `index.html` in a browser.

## Controls
- `W/S` move, `A/D` or `←/→` turn, or click-drag mouse to look
- Minimap top-right shows your position on the grid

## Why this is a good showcase
- No canvas/webGL 3D APIs used — the "3D" is math (raycasting + projection), same technique as the original Wolfenstein 3D engine, just in JS.
- Edit the `MAP` array (strings of `1`s and `0`s) to build your own level instantly.

## Push to Git
```bash
git init
git add .
git commit -m "Pure JS raycasting engine"
git branch -M main
git remote add origin <your-repo-url>
git push -u origin main
```
