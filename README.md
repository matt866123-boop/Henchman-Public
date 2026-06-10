# HENCHMAN — solo OSR referee toolkit

Self-contained build for static hosting (GitHub Pages, Netlify, etc).

## Deploy on GitHub Pages
1. Create a new public repo (e.g. `henchman`)
2. Upload everything in this folder: **Add file → Upload files** → drag in `index.html`, `manifest.webmanifest`, `icon-180.png`, `icon-512.png`
3. Repo **Settings → Pages** → Source: *Deploy from a branch* → `main` / `(root)` → Save
4. After ~1 minute your app is live at `https://<your-username>.github.io/henchman/`

## Install on iPhone (true full screen)
Open the URL in Safari → Share → **Add to Home Screen**. It launches standalone — no browser chrome, full screen, with the HM icon.

## Your data
- Saves live in the browser's localStorage on this device (~5 MB). Keep uploaded map images modest, or skip "include images" on export.
- Migrate from the claude.ai version: there, **Camp → Export JSON** → here, **Camp → Import**.
- Back up the same way, any time.

## Updating
Replace `index.html` in the repo with a newer build (Upload files again → commit). Hard-refresh the app (or re-add to home screen) to pick it up.
