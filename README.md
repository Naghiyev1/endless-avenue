# Endless Avenue v4

A responsive retro café racer browser game for GitHub Pages.

## What changed in v4

- Rebuilt the layout so the game adapts to different screen sizes.
- Portrait mode now has a protected playable area, so the bike does not become absurdly huge.
- Mobile controls stay inside the visible screen instead of falling below the fold.
- The canvas uses the full viewport, but the game logic reserves space for controls.
- Bike size is calculated from the playable area, not raw screen height.
- Manifest orientation changed to `any`, so phones are not forced into a broken layout.
- HUD and overlays are more compact on portrait screens.
- Traffic cars have slightly better visual depth with gradients.
- Cache bumped to v4.

## Deploy on GitHub Pages

1. Upload/replace all files in your GitHub repository.
2. Go to Settings → Pages if this is a new repo.
3. Choose Deploy from a branch.
4. Choose `main` and `/root`.
5. Save.

## Important cache note

Because this is a PWA, your phone may keep an older cached version.

After uploading v4:
- Open the game in a browser tab and refresh twice.
- If the home-screen app still shows the old version, delete the icon and add it again.

## Controls

Desktop:
- Arrow Left / A = steer left
- Arrow Right / D = steer right
- Arrow Up / W = accelerate
- Arrow Down / S = brake
- Space = boost
- B = show collision boxes

Mobile:
- Tap/hold left and right zones to steer
- Hold BOOST for a short burst
