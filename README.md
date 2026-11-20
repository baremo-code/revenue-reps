# Revenue Reps

A single-page goal tracker for business owners: set a leads/sales target, plan your daily reps, run a timer, tick a checklist, and watch your progress and analytics.

No build step and no dependencies.

## Files

| File | What it does |
|---|---|
| `index.html` | The whole app |
| `manifest.webmanifest` | Lets people install it to their home screen |
| `sw.js` | Makes it work offline (and updates itself when you change `index.html`) |
| `icon-192.png`, `icon-512.png`, `apple-touch-icon.png` | App icons (placeholders) |
| `.nojekyll` | Stops GitHub Pages from processing the files |

## Put it online (GitHub Pages)

1. Upload **all** the files in this folder to the repository root, replacing any existing ones.
2. **Settings → Pages → Deploy from a branch → `main` / `(root)` → Save.**
3. Live at `https://YOUR-USERNAME.github.io/REPO-NAME/`.

## Installing as an app

- **iPhone:** open the link in Safari, tap Share, then Add to Home Screen.
- **Android / desktop Chrome:** use Install in the browser menu.

Install it before using it. On iPhone the installed app keeps its own storage, separate from Safari.

## Data

Data is stored in the user's own browser (localStorage) and the app asks the browser to keep it. It does not sync between devices. Users can **Export backup** and **Import backup** from the Backup card at the bottom of the app.

## Updating

Edit or re-upload `index.html`. Changes show up within a couple of minutes. If you change any other file, also change the cache name in `sw.js` (`rr-v1` to `rr-v2`) so devices refresh it.
