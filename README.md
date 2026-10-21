# NEXORIA — The Mind Territory Game

A mobile-friendly, local two-player tactical board-game prototype. Two people play face-to-face on the same phone or tablet. No multiplayer networking is included in this version.

## Core mechanics
- Each player starts with three pieces on opposite edges of a 7×7 board.
- On your turn, select one of your pieces and move it one square in any of the eight directions.
- Landing on an opponent's piece captures it.
- The central Nexus awards one point when a player's turn begins with their piece on it.
- First player to 3 Nexus points wins.
- Two Rift portals connect across the board; landing on one teleports a piece to the other if its destination is unoccupied.
- No dice and no random move outcome: strategy drives the game.

## Controls
Tap a piece, then tap a highlighted destination. Buttons provide undo, end turn, and new match. Works with touch and mouse.

## Run locally
Open `index.html` in a modern browser.

## Publish free with GitHub Pages
1. Create a public repository named `nexoria-game`.
2. Upload `index.html` and `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Select **Deploy from a branch**, branch `main`, folder `/(root)`, and Save.
5. Wait for deployment. GitHub will show the published URL in Pages settings.

## Backend path (future)
This build is pass-and-play and stores no online account data. To add online matches, use a backend such as Supabase or a small Node.js/WebSocket service for room creation, turn validation, reconnects, and anti-cheat. GitHub Pages alone cannot run a server backend.

## Prototype status
The game is playable but is an early prototype. It needs playtesting, balancing, visual polish, accessibility review, and additional mechanics before being treated as a finished release.
