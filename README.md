# NetVibe — Indian Cinema (Web)

This is the webapp source for NetVibe. Host it on **GitHub Pages** so the NetVibe Android app loads the latest version automatically — no reinstall needed.

## Setup

1. **Create a GitHub repository** (e.g., `username/netvibe`)
2. Push these files to the repo
3. Go to **Settings → Pages** and enable GitHub Pages from the `main` branch
4. Note your URL: `https://username.github.io/netvibe`
5. In the NetVibe app, go to **Settings** and enter that URL as the "GitHub Pages URL"
6. Restart the app — it will now load from GitHub Pages

## Updates

- Edit files in your repo, push to GitHub
- GitHub Pages rebuilds automatically
- The app loads the latest version on next startup
- No APK rebuild or reinstall needed

## Customizing Stream Providers

Edit `index.html` — search for `DEFAULT_SCRAPER_CONFIG` and modify the `scrapers` array. Or host your own config JSON and set the "Scraper Config URL" in Settings.

## Important

The app bundles no ads. Third-party embed providers (VidSrc, EmbedSu, etc.) are used for video streaming — these may show ads within their embedded players. You can replace them via the scraper config.
