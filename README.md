# Weekz

Weekz is a simple weekly routine planner. Add recurring activities to each day, choose colors, and view your schedule on a timeline. Routine data and appearance settings are stored in your browser.

## Run locally

Open `index.html` in a modern browser, or serve this folder over HTTP to enable the installable app and offline support. The service worker and web manifest are included for progressive web app support.

## Files

- `index.html` — primary app entry point
- `weekz.html` — standalone copy of the app
- `manifest.webmanifest` — install and display settings
- `sw.js` — offline app shell caching
- `icons/` — app icons

## Privacy

Weekz stores routine data in browser local storage. It does not send routine data to a server.
