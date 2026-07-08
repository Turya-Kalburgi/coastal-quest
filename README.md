# Coastal Quest 🏝️

A cozy pixel-art island exploration game that lives in a single HTML file — no dependencies, no build step, everything (world, art, music, sound) generated in code.

**Play:** open `index.html` in a browser, or visit the live deployment.

## How to play

- Every visit generates a new island with 5 hidden items to find.
- **Desktop:** WASD / arrow keys to move.
- **Mobile:** drag anywhere to move (virtual joystick).
- Ride the road on your skateboard, walk the beaches and forest, and when you've found everything, follow the light to the viewpoint.

## Tech

- Single `index.html` (~55 KB) — vanilla JS + Canvas 2D.
- Procedural island generation (seeded, different every run).
- All pixel art drawn in code, no image assets.
- Music and SFX synthesized live with the Web Audio API.
- Mobile-friendly: touch joystick, safe-area insets, no-zoom viewport.
