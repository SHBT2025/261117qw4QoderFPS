# BERTH//4 — Salvage Protocol

> A single-file procedural FPS built with WebGL2. Zero external assets. ~140 KB.

## About

The port's security grid has gone rogue. Drone swarms and patrol hounds now hold **Berth 4** against the sunset. You are the last salvage operator on site. Clear every wave. Reclaim the dock.

**Built entirely with Qwen 4.0 (通义千问 4.0) — one HTML file, no build tools, no external dependencies.**

## Quick Start

Just open `index.html` in a desktop browser. That's it.

```bash
# Or serve locally
python -m http.server 8000
# → http://localhost:8000
```

## Controls

| Key | Action |
|---|---|
| `W A S D` | Move |
| Mouse | Look |
| `Left Click` | Fire |
| `Right Click` | Aim down sights |
| `Shift` | Sprint |
| `Space` | Jump |
| `R` | Reload |
| `Esc` | Pause |
| `M` | Mute audio |

> Headphones recommended. Desktop + mouse for best experience.

## Features

- **Single file** — everything (rendering, audio, game logic) is in one `index.html`
- **Zero assets** — all textures, models, and sounds are procedurally generated at runtime
- **WebGL2** — raw WebGL2, no game engine
- **Wave-based combat** — clear escalating waves of drones and patrol hounds
- **Threat levels** — Standard / Veteran difficulty
- **Synthwave atmosphere** — neon cyan × magenta against a sunset dockyard

## Tech Notes

- Pure WebGL2 rendering pipeline
- Procedural texture generation via canvas
- Web Audio API for synthesized SFX and ambient music
- ~140 KB total file size

## Credits

- **Game design & code:** Generated with [Qwen 4.0](https://tongyi.aliyun.com/) (通义千问 4.0)
- **Inspiration:** Reverse-engineered from a 1.4 MB viral web game demo

## License

MIT
