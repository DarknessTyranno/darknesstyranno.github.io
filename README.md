# DarknessTyranno website

Publisher website: <https://darknesstyranno.github.io/>

Plain HTML and CSS, hosted on GitHub Pages. No build step, dependency install, analytics, cookies or backend.

## Pages

- `index.html` — publisher introduction and contact
- `spriteless-ui-pro/index.html` — Pro overview, examples, workflow and current scope
- `spriteless-ui/index.html` — free Core overview and Git URL installation
- `styles.css` — shared responsive styles
- `assets/` — approved brand artwork and rendered product examples, not package source

Update the corresponding HTML page to edit copy. Update all three navigation/footer copies together. Pro is marked **Preparing for release**; add the verified Asset Store URL and revise that status when the product is published.

## Local preview

Serve this directory with any local static HTTP server. For example, if Python is installed:

```sh
python -m http.server 4173 --bind 127.0.0.1
```

Open `http://127.0.0.1:4173/`.

## GitHub Pages

In **Settings → Pages**, select **Deploy from a branch**, branch **main**, folder **/(root)**. The `.nojekyll` file keeps publication as plain static files.

The public website repository does not contain the private SpriteLess UI Pro package. The free Core package's MIT license does not automatically apply to this website or its brand artwork.
