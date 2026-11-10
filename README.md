# Ameer Scrubs Catalog

Live catalog: https://ameerscrubs.github.io/catalog

- `index.html` — the whole catalog in one file (photos in img/).
- Stock lives in the `<script type="application/json" id="stock-data">` block inside `index.html`, as `{"updated":"YYYY-MM-DD","rows":[[item name, size, remaining], ...]}` taken from the inventory sheet.
- `og.png` — link preview image. `icon.png` — site icon.

To update stock: replace only that JSON block, commit, and push to `main`. GitHub Pages republishes automatically.
