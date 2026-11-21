# krosebrook.github.io

Static developer site and open-source index for [Kyle Rosebrook](https://github.com/Krosebrook), built with semantic HTML, WCAG 2.2 AA contrast and focus states, `llms.txt` discovery metadata, and zero runtime JavaScript frameworks.

## Deployment

- `.nojekyll` and `index.html` at the repository root serve automatically on `https://krosebrook.github.io/` from `main` (`/`).
- `workflows-ready/pages.yml` provides an optional 40-character SHA-pinned GitHub Actions Pages workflow (`actions/checkout`, `actions/configure-pages`, `actions/upload-pages-artifact`, `actions/deploy-pages`) if switching Pages source to GitHub Actions.

## Local or Codespaces preview

Open in GitHub Codespaces (`.devcontainer/devcontainer.json` forwards port `8080`) or run locally:

```bash
python3 -m http.server 8080
```
