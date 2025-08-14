# SDL2 WebAssembly Game Template

This repo contains a minimal SDL2 C game compiled to WebAssembly using GitHub Actions and deployed via GitHub Pages.

## Features

- Simple SDL2 game loop in `main.c`
- Compiles with Emscripten to `index.html` + `.wasm` + `.js`
- Auto-deployed to GitHub Pages on push

## How to Use

1. Edit `main.c` with your SDL2 game code.
2. Commit and push to the `main` branch.
3. The GitHub Actions workflow will build and deploy automatically.
4. Access your game at `https://<your-username>.github.io/<repo-name>/`

## Requirements

- No local IDE or terminal needed.
- Requires GitHub Pages enabled on this repo (usually done automatically by the workflow).

## Notes

- This template is designed for school-issued Chromebooks with restricted terminal access but GitHub available.
- You can extend this with keyboard/mouse input, audio, textures, etc.

---

Have fun coding games that run directly in your browser!
