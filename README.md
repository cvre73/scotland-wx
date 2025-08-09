# Scotland WX (Single-File)

This repo hosts a single-file version of the Scotland weather dashboard.

## What it includes
- Yr.no forecast chart (Temp, Wind, Gust) + Precip bars
- Live UK radar (RainViewer) + Windy wind/gust layers
- Units toggle with persistence
- Saves selected tab and map position
- Pull-to-refresh
- Apple Watch Ultra quick view: `?mode=ultra`
- Custom app icon embedded

## Publish with GitHub Pages
1. Create a new public repo on GitHub (e.g. `scotland-wx-single`).
2. Upload these files to the repo root:
   - `index.html`
   - `README.md`
3. In GitHub: **Settings → Pages → Build and deployment**
   - Source: **Deploy from a branch**
   - Branch: `main` (or `master`), Folder: **/** (root)
4. Your site will be live at: `https://<your-username>.github.io/scotland-wx-single/`

## Add to Home Screen (iPhone)
- Open the URL in Safari → Share → **Add to Home Screen**.

---
**Note:** As a true single-file page, this build doesn’t use a service worker (browsers require a separate JS file). Live data requires network.
