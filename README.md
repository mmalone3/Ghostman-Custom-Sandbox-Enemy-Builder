# Ghostman: Custom Sandbox & Enemy Builder

A standalone HTML5 Canvas action-game sandbox for designing enemy encounters, testing player abilities, and saving custom gameplay configurations.


## Project Overview

Ghostman runs entirely in the browser from a single `index.html` file. It uses vanilla JavaScript, HTML5 Canvas, CSS, the Web Audio API, and LocalStorage, with no frameworks, build tools, package installation, or external assets required.

### Highlights

- Real-time Canvas game loop with keyboard controls, collision detection, particles, screen shake, procedural sound effects, and high-DPI rendering.
- Configurable bombs, projectiles, orbital attackers, collapsing rings, sweeping beams, and grid hazards.
- Adjustable telegraph timing, speed, radius, damage, spawn count, and automatic spawn intervals.
- Dash, spin dodge, directional shield, and vanish abilities with distinct counters and cooldowns.
- Collectible spawning, score tracking, health management, partner selection, and personal-best timing.
- Playtesting tools including slow motion, enemy freeze, invincibility, unlimited cooldowns, and hitbox visualization.
- Built-in and user-created presets saved locally in the browser with LocalStorage.
- Responsive control panel for spawning enemies and changing gameplay settings while the game is running.

## Controls

| Action | Input |
|---|---|
| Move | `WASD` or Arrow Keys |
| Shield / Parry | `Space` |
| Vanish / Phase Shift | `J` |
| Dash / Grapple Strike | `Shift` or `K` |
| Spin Dodge / Deflect | `L` or `Q` |
| Pause / Resume | `P` or the on-screen button |

## Run Locally

Download `index.html`, then open it in a modern desktop browser. No local server or installation is required.

## Repository Files

Only these two files are required for the public GitHub repository:

```text
CustomPlayTest/
|-- index.html
`-- README.md
```

- `index.html` contains the complete game, interface, styles, audio, and JavaScript logic.
- `README.md` contains the project documentation.


## Technology

JavaScript | HTML5 Canvas | CSS3 | Web Audio API | LocalStorage | GitHub Pages
