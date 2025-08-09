# Scotland WX — Single File (Scotland-First)

Single-file weather dashboard for Scotland. Loads immediately with preset coordinates (Stonehaven area), then upgrades to GPS if allowed.

## Features
- Yr.no/MET Norway hour-by-hour chart: Temp, Wind, Gust + Precip bars
- RainViewer radar (Leaflet)
- Windy wind & gust overlays (tabs)
- Units toggle with persistence (m/s, mph, knots, Beaufort)
- Remembers selected tab
- Pull-to-refresh-like UX (pull in Safari refreshes data)
- Apple Watch Ultra quick view: `?mode=ultra`
- Embedded iOS icon (data URI)

## Publish on GitHub Pages
1. Create a new **public** repo on GitHub (e.g. `scotland-wx-single`).
2. Upload these two files to the repo root:
   - `index.html`
   - `README.md`
3. In GitHub: **Settings → Pages → Build and deployment**
   - Source: **Deploy from a branch**
   - Branch: `main` (or `master`), Folder: **/** (root)
4. Your site will be live at: `https://<your-username>.github.io/<repo-name>/`

### Add to Home Screen (iPhone)
Open the URL in Safari → Share → **Add to Home Screen**.
