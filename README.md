# DarknessTyranno website

Publisher website: <https://darknesstyranno.github.io/>

Plain HTML and CSS, hosted on GitHub Pages. No build step, dependency install, analytics, cookies or backend.

## Pages

- `index.html` — publisher introduction and contact
- `spriteless-ui-pro/index.html` — Pro user guide: components, baking, Prefabs and troubleshooting
- `spriteless-ui/index.html` — Core user guide: installation, shapes and Inspector settings
- `styles.css` — shared responsive styles
- `docs.css` — documentation layout, component references and mobile contents
- `assets/` — approved brand artwork and rendered product examples, not package source

Update the corresponding HTML page to edit copy. Update all three navigation/footer copies together. Pro is marked **Preparing for release**; add the verified Asset Store URL and revise that status when the product is published.

## Documentation screenshots

The guides describe user actions and Inspector controls, not code structure. Keep labels and screenshots in sync with the released package. Component screenshots sit next to their usage instructions; rendered examples illustrate the result separately.

The six approved screenshots are in `assets/screenshots/`: `pro-group.png`, `pro-polygon.png`, `pro-effects.png`, `pro-cutout.png`, `pro-baker.png` and `core-image.png`. To replace one, update the image and its intrinsic width/height in the HTML. Use a `figure` with class `doc-screenshot`, meaningful alt text and a short caption. Keep UI text readable and remove private project names, paths and account details before publishing. Each screenshot links to the original image for closer inspection.

Section IDs are public deep links. Keep existing IDs when reorganizing the guide.

## Local preview

Serve this directory with any local static HTTP server. For example, if Python is installed:

```sh
python -m http.server 4173 --bind 127.0.0.1
```

Open `http://127.0.0.1:4173/`.

## GitHub Pages

In **Settings → Pages**, select **Deploy from a branch**, branch **main**, folder **/(root)**. The `.nojekyll` file keeps publication as plain static files.

The public website repository does not contain the private SpriteLess UI Pro package. The free Core package's MIT license does not automatically apply to this website or its brand artwork.
