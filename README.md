# LINE-5

A browser-based puzzle game played on an infinite grid. Place pieces to complete lines of exactly 5, chaining moves to build the highest score possible.

## How to Play

Each turn you place one piece on the board. A valid move must complete a line of exactly 5 connected pieces — horizontal, vertical, or diagonal. The piece you place must be the one that completes the line; the other 4 must already be on the board.

Click any **orange** or **green** circle to place a piece there. If only one line is possible, it is placed immediately. If multiple lines are possible, you enter selection mode:

- **Move the mouse** around the cell — the preview snaps to the closest direction
- **Click** on the same cell to cycle through the available options
- **Double-click** or **long press** to confirm the highlighted line
- **Right-click** or **Esc** to cancel

The game ends when no valid move exists anywhere on the board.

## Color Hints

| Color | Meaning |
|-------|---------|
| 🟠 Orange | Valid move — place a piece here |
| 🟢 Green | Strategic move — aligned with another valid move at distance ≥ 9, with no gaps or used segments between them |
| 🔵 Blue | Initial piece (placed at game start) |
| 🔴 Red | Piece you placed (shows move number) |

## Controls

| Input | Action |
|-------|--------|
| Click orange/green circle | Place a piece |
| Click same cell again | Cycle line direction |
| Double-click / long press | Confirm selected direction |
| Right-click / Esc | Cancel selection |
| Scroll wheel | Zoom in / out |
| Click and drag | Pan the grid |
| Ctrl+Z | Undo last move |

## Features

- **Infinite grid** — pan and zoom freely in any direction
- **High score** — your best score is saved and displayed at all times
- **Auto-save** — the game state is saved after every move and restored when you reopen the page
- **Undo** — step back one move at a time
- **Dark / Light theme** — toggle with the ☀️/🌙 button, preference is remembered
- **Visual line selection** — no popups; choose direction by moving the mouse

## Running the Game

The game is a single self-contained HTML file with no dependencies.

Open the HTML file in any modern browser

Or host it on any static file server — no build step required.

## Scoring

Each piece placed scores **1 point**. The goal is to keep finding valid moves for as long as possible. Green-highlighted moves indicate positions that are geometrically aligned with other valid moves — these are often good candidates for chaining future plays.
