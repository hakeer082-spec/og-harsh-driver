# OG HARSH DRIVER — ट्रक वाला

A mobile-first desi highway music website.

## Files
- `index.html` — website structure
- `style.css` — screenshot-inspired black/gold mobile design
- `script.js` — working browser audio player, search, filters and favorites
- `tracks.json` — 64 song listings
- `truck-hero.png` — decorated Rajasthan truck hero artwork

## Run
Keep all files in one folder. For local testing, run `python -m http.server 8000` in this folder and visit `http://localhost:8000`.

## Audio
Song metadata is provided, not copyrighted MP3s. Select a track and attach an MP3 you own or have permission to use, or a direct audio URL whose host permits playback. The HTML audio element plays the actual file; unavailable audio is never faked. Device-attached files are temporary and must be reattached after reload.

## GitHub Pages
Create a public repository, upload all files to its root, then open Settings → Pages → Deploy from a branch → `main` → `/ (root)` → Save. Wait for GitHub's published URL.

## Netlify
Upload the complete folder to Netlify Drop or connect the repository. Keep all assets together.
