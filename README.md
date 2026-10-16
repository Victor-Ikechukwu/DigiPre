# DigiPre

A static digital CV website for **Dr. Agughasi Victor Ikechukwu**, designed for GitHub Pages.

## Local preview

Because this is a plain static site, you can open `index.html` directly or serve the folder locally:

```bash
cd /home/runner/work/DigiPre/DigiPre
python -m http.server 8000
```

Then open `http://localhost:8000`.

## GitHub Pages deployment

This repository includes `.github/workflows/deploy-pages.yml`, which deploys the repository contents to GitHub Pages using official actions:

- `actions/configure-pages`
- `actions/upload-pages-artifact`
- `actions/deploy-pages`

Deployments run on pushes to `main` and on manual workflow dispatch.

## Published URL

Once Pages is enabled for this repository, the site URL is:

- https://victor-ikechukwu.github.io/DigiPre/
