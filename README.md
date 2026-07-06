# MET degradation curve tool

A single-page, offline-capable HTML tool for calibration curves, HPLC-DAD peak-area conversion, and metformin UV/chlorine degradation plots.

## GitHub Pages deployment

1. Create a new GitHub repository, for example `met-degradation-tool`.
2. Upload `index.html` to the repository root.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/ (root)**
5. Save. GitHub Pages will provide a public URL after deployment.

## Notes

- This tool stores project data and format presets in the browser's localStorage.
- Use **匯出 JSON** inside the tool to back up your projects.
- Use **匯出格式預設** to back up chart/style defaults.
- The page does not require external libraries or internet access after loading.
