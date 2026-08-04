# Neon Void Runner

A neon cyberpunk endless runner — side-scrolling, auto-fire, one-hit death, juice-heavy VFX.

## Play

Open `index.html` in a modern browser (Chrome, Safari, Firefox, Edge):

```bash
open index.html
```

Or serve locally:

```bash
python3 -m http.server 8080
# then visit http://localhost:8080
```

## Controls

| Input | Action |
|--------|--------|
| **↑ / W** or **↓ / S** | Move ship up / down |
| **Touch & drag** | Mobile vertical control |
| **Any key / tap** | Start from title screen |

The ship auto-fires. Survive as long as you can.

## Gameplay

- **Avoid** neon asteroids, energy barriers, and enemy drones
- **Collect** glowing orbs for score and power-ups:
  - **Shield** — absorbs one hit
  - **Rapid fire** — triple-shot burst
  - **Slow-mo** — briefly slows the void
- **One-hit death** → dramatic explosion → instant restart
- High score is saved in `localStorage`

## Tech

Single self-contained `index.html` — Canvas 2D, no dependencies.
