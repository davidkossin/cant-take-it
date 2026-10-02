# Godot V2 (HTML5 export)

This folder is the **Godot 4.7.2** build of *You Can't Take It With You* (project `/workspace/cant-take-it-v2/`, label `2.0.0-dev`).

- Live path: `https://davidkossin.github.io/cant-take-it/v2/` (also `https://dkossin.com/cant-take-it/v2/`)
- **V1** (web JS v0.5.11) remains at the parent directory: `../` / `https://davidkossin.github.io/cant-take-it/`
- Finance numbers match web v0.5.11 — see Godot project `PORT.md`.

Re-export:

```bash
godot --path /workspace/cant-take-it-v2 --headless \
  --export-release "Web" /workspace/cant-take-it-repo/v2/index.html
```
