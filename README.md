# Abdalraheem Mokhtar — Portfolio

Single-page portfolio for an applied AI and data builder in Abu Dhabi. Plain HTML and CSS. No build step.

## Run locally

```bash
python -m http.server 8080
```

Open `http://localhost:8080`.

## Publishing

GitHub Pages serves this site at:

`https://abdalraheemmokhtar.github.io/portfolio/`

The site is the repository root (`index.html`, `style.css`, and `assets/`). There is no build. `.nojekyll` is included so Pages serves the files as they are.

Pages for this repository currently publishes the `gh-pages` branch. `.github/workflows/pages.yml` copies this root onto `gh-pages` after each push to `master`, which is what merging does. The public URL does not change.

If that job cannot update `gh-pages`, set Settings, Pages, Deploy from a branch, to `master` and `/ (root)`.
