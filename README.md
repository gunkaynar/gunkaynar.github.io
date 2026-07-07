# gunkaynar.com

Source for my personal academic website — plain static HTML/CSS, no build step.

Based on the [Carnegie Mellon Computational Imaging Lab personal website template](https://github.com/cmu-ci-lab/website_templates).

## Local development

Just open `index.html` in a browser, or serve the directory with any static file server, e.g.:

```bash
python3 -m http.server 8000
```

## Structure

- `index.html` — the whole site
- `style.css` — styling
- `images/` — photos, icons
- `uploads/` — CV and other downloadable files

## Deployment

Pushes to `main` are published to GitHub Pages automatically via [.github/workflows/deploy.yml](.github/workflows/deploy.yml).
