# Energy Log

A personal energy tracker. Log a 0 to 10 energy level with optional caffeine, activity, mood and notes, then see it charted over 24 hours, 7 days or a month, with trends by time of day and activity.

Plain HTML, CSS and JavaScript. No build step. Logs are stored in the browser on the device (localStorage).

## Deploy to GitHub Pages

1. Create a repo (for example `energy-log`) and add every file in this folder to its root.
2. In the repo: Settings > Pages > Deploy from a branch > `main`, folder `/ (root)`.
3. Open `https://<username>.github.io/energy-log/`.

## Add to Home Screen

- iPhone: open the site in Safari, tap Share, then Add to Home Screen.
- Android: open it in Chrome, tap the menu, then Install app.

## Updating

Edit the files and push. Bump `CACHE` in `sw.js` (v1 to v2) when you change files so old caches are cleared.
