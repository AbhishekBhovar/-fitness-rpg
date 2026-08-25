# Fitness Level Up — Clean GitHub Pages Build

This is the clean Character Fitness RPG build for the `-fitness-rpg` GitHub Pages repository.

## Important
- Upload the **contents of this folder to the repository root**, not the outer folder itself.
- This build intentionally contains no Harry Potter app files.
- It keeps the existing `fitnessRPGv11` localStorage key, so browser-saved Fitness Level Up results can continue to load on the same GitHub Pages URL.
- The service worker is scoped to this app and only removes caches whose names start with `character-fitness-rpg-`; it does not delete caches belonging to the HP app.

## Expected repository root
- `index.html`
- `manifest.webmanifest`
- `service-worker.js`
- `icon-192.png`
- `icon-512.png`
- `apple-touch-icon.png`
- `assets/` (26 character images)

After deployment, first test: https://abhishekbhovar.github.io/-fitness-rpg/
