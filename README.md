# Ameer Scrubs Catalog

Live catalog: https://ameerscrubs-catalog.netlify.app

- `index.html` — the whole catalog in one file (photos embedded).
- Stock lives in the `<script type="application/json" id="stock-data">` block inside `index.html`, as `{"updated":"YYYY-MM-DD","rows":[[item name, size, remaining], ...]}` taken from the inventory sheet.
- `og.png` — link preview image. `icon.png` — site icon.

To update stock: replace only that JSON block, commit, and push to `main`. Netlify redeploys automatically.
