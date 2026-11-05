# tommykuan.com

Personal site, served by GitHub Pages from the root of the `gh-pages` branch.

- `index.html` — the whole site: one self-contained page (HTML, CSS and a WebGL "liquid chrome" shader). No build step.
- `assets/TommyKuanResume.pdf` — résumé, kept at its existing public URL.
- `CNAME` — custom domain (`tommykuan.com`). Don't remove.
- `.nojekyll` — tells Pages to serve files as-is instead of running Jekyll.

## Run locally

    python3 -m http.server 8000

Then open http://localhost:8000.

## Deploy

Commit to `gh-pages` and push. Pages rebuilds in a minute or two.
