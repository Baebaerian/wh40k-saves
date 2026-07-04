# wh40k-saves

Published board-state snapshots from the [wh40k-simulator](https://github.com/Baebaerian/wh40k-simulator) Deploy & Move tab, viewable on a phone via GitHub Pages.

- `index.json` — list of published saves (title, dispositions, layout, PNG filename, timestamps).
- `saves/` — the PNG snapshots themselves.
- `index.html` — standalone viewer (no build step): pick a disposition/layout pairing, tap a save to view it full-screen.

This repo is written to by the simulator's "Publish to phone" action (via the GitHub Contents API) and is not meant to be edited by hand.
