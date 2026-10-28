# Prism Stack 3D

A falling-block puzzle game rendered in 3D with Three.js, built to play on Android phones (and desktop browsers).
Everything is in `index.html`; there is no build step.

## Features

- Standard modern rules: 7-bag randomizer, SRS rotation with wall kicks, hold, 3-piece preview, ghost piece,
  lock delay with move resets, T-spin detection, combos, back-to-back bonus, all-clear bonus, 20 levels.
- 3D well with glossy rounded blocks, bloom, chromatic aberration, a piece-colored light, a starfield that
  warps on big clears, exploding debris and sparks on line clears, hard-drop trails and shockwaves,
  camera shake and impact bounce, level-colored neon frame, and a red warning glow when the stack gets high.
- Synthesized sound effects and music (Web Audio, no audio files), plus vibration feedback on Android.
- Touch gestures and on-screen buttons. The game auto-lowers its resolution if the frame rate drops.

## Controls

| Touch | Buttons | Keyboard | Action |
| --- | --- | --- | --- |
| Drag sideways | ◀ ▶ | ← → | Move |
| Tap | ⟳ / ⟲ | ↑ or X / Z | Rotate right / left |
| Drag down | ▼ | ↓ | Soft drop |
| Flick down | ⤓ | Space | Hard drop |
| Flick up, or tap HOLD | | C or Shift | Hold |
| | ❚❚ | P or Esc | Pause |

## Play on your phone

1. In this repo, open **Settings → Pages**, set **Source** to *Deploy from a branch*, pick this branch and `/ (root)`, and save.
2. Open the Pages URL in Chrome on Android, then use **⋮ → Add to Home screen** (or **Install app**).
   It launches fullscreen in portrait and works offline after the first load.

To run locally: `python3 -m http.server` in this folder, then open `http://localhost:8000`.
