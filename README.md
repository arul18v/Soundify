# Soundify

A responsive, installable personal music player. Bring audio files from your own device and play them in a clean, Spotify-inspired interface.

## Features
- Local audio file import and playback
- Search, liked tracks, playlists
- Shuffle, repeat, seek and volume
- Responsive desktop/mobile layout
- PWA manifest and service worker for installation and app-shell caching

## Run locally
Open `index.html` through a local static server (for example, VS Code Live Server). For PWA installation, serve over HTTPS or localhost.

## Deploy with GitHub Pages
The workflow in `.github/workflows/pages.yml` deploys the site when changes are pushed to `main`. Enable GitHub Pages using GitHub Actions if prompted.

## Music and privacy
Soundify does not include Spotify's catalogue or unlock Spotify Premium. Import audio files you own or are licensed to use. Audio files are read locally in your browser and are not uploaded to a server. Your library is held in the current browser session; refresh/reopen may require importing files again.
