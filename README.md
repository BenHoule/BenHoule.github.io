# BenHoule.github.io

A basic website container for hosting a Godot WebAssembly game.

## Features

- Clean, responsive design that adapts to different screen sizes
- Loading progress indicator for game assets
- Fullscreen support
- Modern gradient background
- Mobile-friendly layout

## How to Use

1. Export your Godot game for Web (HTML5):
   - In Godot, go to Project → Export
   - Select "HTML5" as the export preset
   - Export the project (this will generate `.wasm`, `.pck`, and `.js` files)

2. Copy the exported files to this repository:
   - `index.wasm` - The compiled game engine
   - `index.pck` - The game assets and scripts
   - `index.js` - The Godot engine loader

3. Update `index.html`:
   - Uncomment the script tag at the bottom: `<script src="index.js"></script>`
   - Uncomment the game initialization code in the script section

4. Commit and push the changes to GitHub

5. Your game will be available at: https://BenHoule.github.io

## File Structure

```
.
├── index.html    # Main HTML file with game container
├── style.css     # Styling for the game container
├── index.js      # Godot engine loader (to be added)
├── index.wasm    # Compiled game engine (to be added)
└── index.pck     # Game assets (to be added)
```

## Customization

You can customize the appearance by editing `style.css`:
- Background gradient colors
- Game container size and aspect ratio
- Loading indicator style
- Mobile breakpoints

## Browser Support

This container works with all modern browsers that support:
- WebAssembly
- Canvas API
- ES6 JavaScript

Recommended browsers: Chrome, Firefox, Safari, Edge (latest versions)