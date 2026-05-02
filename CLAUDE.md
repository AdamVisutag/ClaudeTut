# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project overview

A single-file browser game. Everything — markup, styles, and logic — lives in `tictactoe.html`. No build step, no dependencies, no package manager.

## Running the game

Open `tictactoe.html` directly in a browser:

```powershell
start tictactoe.html
```

There is no dev server, bundler, or test suite.

## Architecture

`tictactoe.html` is self-contained in three sections:

- **CSS** (inside `<style>`) — dark-theme layout using CSS Grid for the 3×3 board. Cell states (`x`, `o`, `taken`, `win`) are toggled via class names.
- **HTML** — nine `.cell` divs identified by `data-i` (0–8), a `#status` line, a `#scores` strip, and a `#restart` button.
- **JavaScript** (inside `<script>`) — plain vanilla JS, no framework. Key pieces:
  - `board`: flat 9-element array, indices match `data-i`.
  - `WINS`: hardcoded array of the 8 winning index triples, checked after every move.
  - `checkWinner()`: iterates `WINS`, returns `{ winner, line }` or `{ winner: 'draw' }` or `null`.
  - `init()`: resets `board`, `current`, `over`, and all cell classes without re-rendering the DOM.
  - Score state (`scores.X / O / D`) is kept in memory only; it resets on page reload.

## Git & GitHub

- Remote: `https://github.com/AdamVisutag/ClaudeTut`
- Branch: `master`
- Commit and push after every meaningful change:

```powershell
git add tictactoe.html
git commit -m "your message"
git push
```
