# Tetris

A simple, self-contained Tetris game in a single HTML file. It has no dependencies and needs no build step.

## Play

Open `index.html` in any modern browser, then press **Start** or **Enter**.

| Key | Action |
| --- | --- |
| ← / → | Move |
| ↑ or X | Rotate |
| ↓ | Soft drop |
| Space | Hard drop |
| P | Pause / resume |

On a phone or tablet, the board fits the screen and on-screen buttons appear below it: ◀ ▶ move, ▼ soft drop, ⟳ rotate, ⤓ hard drop, ❚❚ pause. Hold ◀, ▶ or ▼ to repeat. You can also use gestures on the board: tap to rotate, drag sideways to move, and swipe down to hard drop.

## Features

- All seven tetrominoes with a 7-bag randomizer
- Ghost piece showing where the piece will land
- Simple wall kicks when rotating near walls
- Next-piece preview
- Scoring of 100 / 300 / 500 / 800 × level for 1–4 lines, plus drop points
- Level goes up every 10 lines, and pieces fall faster
