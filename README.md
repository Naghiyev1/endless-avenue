# Endless Avenue v2

A retro café racer browser game for GitHub Pages.

## What changed in v2

- Rebuilt collision detection using actual on-screen rectangles.
- Fixed false crashes when steering left/right on an empty road.
- Made the collision box smaller than the visual bike, so it feels fair.
- Redrew the bike from a rear-view perspective so it no longer looks sideways.
- Redrew the rider to look more natural.
- Added debug collision boxes: press `B` while playing.
- Bumped the offline cache to v2.

## What it is

Endless Avenue is a lightweight pseudo-3D arcade motorcycle game. You ride through an endless New York-inspired city with changing districts, traffic, speed, distance scoring, and local high score storage.

## Files

- `index.html` — the full game
- `manifest.json` — makes it installable on phones
- `sw.js` — enables offline loading after the first visit
- `icons/` — app icons

## Deploy on GitHub Pages

1. Create a new GitHub repository.
2. Upload all files and folders in this ZIP.
3. Go to Settings → Pages.
4. Choose Deploy from a branch.
5. Choose `main` and `/root`.
6. Save.

Your game will be live at:

`https://YOURUSERNAME.github.io/YOUR-REPO-NAME/`

## Controls

Desktop:
- Arrow Left / A = steer left
- Arrow Right / D = steer right
- Arrow Up / W = accelerate
- Arrow Down / S = brake
- Space = boost

Mobile:
- Tap/hold left and right zones to steer
- Hold BOOST for a short burst

## Add to phone

iPhone:
Open the live page in Safari → Share → Add to Home Screen.

Android:
Open the live page in Chrome → menu → Add to Home screen or Install app.
