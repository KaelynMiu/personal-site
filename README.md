# Kaelyn Miu personal site

A single-page portfolio built with native HTML, CSS, and JavaScript. The public version reads a transparent clay-character frame atlas and photos from `assets/`; the résumé is intentionally excluded.

To preview it locally, open `index.html` in a browser. If the browser restricts local assets, run this from this folder:

```sh
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

The `.github/workflows/pages.yml` workflow is ready to publish the site to GitHub Pages from the `main` branch. In the repository's Pages settings, choose **GitHub Actions** as the publishing source.
