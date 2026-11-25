# SEND IT! Used Dirt Bike Inspector

Installable web app for inspecting used dirt bikes before you buy.

- Guided checklist: 38 checks in 7 categories, plus extra checks for the bike type (motocross, trail, dual-sport, enduro), detected from make and model
- Verdict: Send it, Negotiate or Walk away, with dealbreakers flagged
- Offline VIN decode, seller tracking with trust ratings, multi-stop route to Google Maps
- Works offline once installed; data stays on the device (localStorage)

## Install on a phone
Open the site URL in Safari (iPhone) or Chrome (Android), then Share → Add to Home Screen (iPhone) or menu → Install app (Android).

## Files
- `index.html` – the whole app
- `manifest.webmanifest`, `icons/` – install name and home-screen icons
- `sw.js` – offline cache (bump `CACHE` when releasing changes)
