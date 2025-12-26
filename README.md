# AI-Slop

**Little Meadow Garden** is a cozy, cottagecore mini garden you can plant and water until everything blooms — no stress, no losing.

- **Repo**: [`https://github.com/razer43/AI-Slop.git`](https://github.com/razer43/AI-Slop.git)
- **Live (GitHub Pages)**: enable Pages, then open [`https://razer43.github.io/AI-Slop/`](https://razer43.github.io/AI-Slop/)

## How to play

- **Plant**: pick a seed, then click a soil tile.
- **Water**: switch to 💧 and click planted tiles to help them grow faster.
- **Stages**: seed → sprout → bloom
- **Time of day**: use **🌤 Cycle time** to switch Morning / Afternoon / Evening.

### Keyboard shortcuts

- **1**: Plant tool
- **2**: Water tool
- **T**: Cycle time
- **S**: Save

## Features

- **Single-file** HTML/CSS/JS (no build step, no dependencies)
- **Autosave** + manual save to browser storage (`localStorage`, key: `little_meadow_garden_v1`)
- **Gentle wind audio** (WebAudio; requires a click/tap to enable in most browsers)
- **Butterflies** that drift around your garden

## Run locally

- **Fastest**: open `AI Slop.html` in your browser.
- **Recommended** (runs like a real site):

```bash
python -m http.server 8000
```

Then open `http://localhost:8000/` (the root `index.html` redirects into the game).

## Publish on GitHub Pages

1. Push this repo to GitHub.
2. In GitHub: **Settings → Pages**
3. **Source**: “Deploy from a branch”
4. **Branch**: `main` / `(root)`
5. Wait ~1–2 minutes, then open your Pages URL.

## Files

- `AI Slop.html` — the full game
- `index.html` — small redirect so the GitHub Pages root loads the game
- `README.md` — this file

## License

MIT — see `LICENSE`.


