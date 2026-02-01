# iPAW — GitHub Pages site

Single-page static site for **Institute for the Protection of Australian Wildlife (iPAW™)**.

## Local preview

Open `index.html` directly in a browser, or run a tiny server:

```bash
cd conserve-nature.github.io
python3 -m http.server 8080
```

Then visit: <http://localhost:8080>

## Deploy

This repo is intended for **GitHub Pages**.

- Static HTML/CSS (no Jekyll). We include a `.nojekyll` file.
- Add a `CNAME` file later when the domain is ready (e.g. `ipaw.org.au`).

## Assets

Place images in:

- `assets/images/hero.jpg`
- `assets/images/project-edge-ai.jpg`
- `assets/images/project-models.jpg`
- `assets/images/project-field-tools.jpg`

The layout works even if images are missing (placeholders will show).
