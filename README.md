# SHIFT — Two Worlds

A tiny single-file browser action game for **Game Off 2026** (theme: **SHIFT**).

Switch between a white world and a black world. The same place has different
platforms in each world — swap worlds to reach the flag.

## Play

Open `index.html` in any modern browser. No build step, no dependencies,
no server needed. Works with keyboard, and on touch devices with the
on-screen buttons.

## Controls

| Input | Action |
|---|---|
| ← → / A D | Move |
| ↑ / Space / W | Jump |
| Shift / X | Switch worlds |
| Hold Shift (on a purple block) | Reverse gravity |
| P | Pause (with fast travel) |
| R | Restart from checkpoint |
| M | Mute |
| E | Map editor (place blocks, C to copy) |

## Mechanics

- **Two worlds** — yellow platforms exist only in the white world, blue
  platforms only in the black world. The other world's platforms are shown
  faintly, so you can plan your switches.
- **Gravity blocks** (purple) — hold Shift while standing on one to flip
  gravity and walk on the ceiling. Release Shift to fall back down.
- **Lifts** (orange) — they move up and down when you switch worlds.
  Ride one up to reach a high ledge.
- **Spikes and pits** — touching spikes or falling off the stage costs a life.
- **One seamless world, 9 coins** — five areas stitched into a single scrolling
  world. Later areas combine all the mechanics.
- **Checkpoints and fast travel** — touch a flag to set your respawn point.
  From the pause screen you can warp to any checkpoint you have activated.
- **Auto-save** — checkpoints, coins and best time are saved in your browser,
  so you can continue where you left off.
- **Hidden room** — after your first clear, a locked door in the ceiling opens
  to a secret room with extra coins.
- **No-gravity challenge** — clear the world without ever reversing gravity
  to earn a crown. Collect every coin for the COIN MASTER title.
- **Tutorial signs** — walk up to a signpost to see a hint.
- **Map editor** — press E to place blocks and coins, and C to copy the world
  data as JSON.
- Best clear time is saved in your browser.

## About

- Made for Game Off 2026. Submission deadline: December 1, 2026, 13:37 PST.
- The in-game text is in Japanese and English (toggle in the title screen or settings).
- Single HTML file (`index.html`), everything inline.
