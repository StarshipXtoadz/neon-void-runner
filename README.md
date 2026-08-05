# Neon Void Runner

A neon cyberpunk endless runner — side-scrolling, auto-fire, two-hit hull, juice-heavy VFX, pause menu, and a points shop.

**Play:** https://starshipxtoadz.github.io/neon-void-runner/

## Controls

| Input | Action |
|--------|--------|
| **↑ / W** or **↓ / S** | Move ship up / down |
| **Touch & drag** | Mobile vertical control |
| **Pause (top-left ⏸)** | Open pause menu |
| **Esc / P** | Pause / resume (desktop) |

## Gameplay

- Auto-scrolling void that speeds up over time
- **2 hull hits** to die on the starter ship (first strike damages, second kills)
- Temporary **shield orbs** still absorb a hit without spending hull
- Obstacles: asteroids, energy barriers, enemy drones
- Power-ups: Shield, Rapid Fire, Slow-Mo
- Score banks into **shop points** when a run ends

## Pause menu

- **Resume** — back to the run  
- **Shop** — spend points  
- **Quit to Home** — title screen  

## Shop

Spend banked points on:

| Item | Effect |
|------|--------|
| **Game Continue** | Revive mid-run after death (keep score) |
| **Aegis Hull** | Ship withstands **4** enemy attacks |
| **Pulse Razor** | Much faster single-cannon fire rate |
| **Trinity Gunship** | Rapid fire **+ three cannons** |

Each upgrade shows its cost and a plain-language description of the improvement.

On death you can also **use/buy a continue**, start a new run, open the shop, or return home.

## Tech

Single self-contained `index.html` — Canvas 2D, no dependencies. Progress saves in `localStorage`.
