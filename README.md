# Level 1 Wine Study Room

An interactive, installable study companion for the WSET Level 1 Award in Wines, with a 30-question mock exam. It works offline once installed.

 https://blueview-j.github.io/wine-study1/

An independent study aid, not produced or endorsed by the Wine & Spirit Education Trust.

## Files
- `index.html` – the app
- `manifest.webmanifest` – app name, colours and icons for installing
- `sw.js` – saves the app on your phone so it works offline
- `icon-192.png`, `icon-512.png`, `apple-touch-icon.png` – home-screen icons

## Updating
1. Upload the new `index.html`.
2. In `sw.js`, change `wine-study-v1` to `wine-study-v2` (then v3, and so on) and commit.
3. Open the app once while online, close it and reopen it to see the new version.
