# Revenue Reps

A single-file goal tracker for business owners: set a leads/sales target, plan your daily reps, run a timer, tick a checklist, and watch your progress and analytics.

No build step, no dependencies. The whole app is `index.html`.

## Put it online (GitHub Pages)

1. Create a new repository on GitHub (for example `revenue-reps`).
2. Upload the files in this folder (`index.html`, `README.md`, `.nojekyll`) to the repository root.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then **Save**.
5. After a minute or two your app is live at `https://YOUR-USERNAME.github.io/revenue-reps/`.

## Notes

- Data is stored in each user's own browser (localStorage). It does not sync between devices, and clearing browser data erases it.
- To update the app, edit `index.html` in the repository. Everyone using the link gets the new version.
- Light and dark mode follow the device setting.
