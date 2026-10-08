# IOEDR Project Page

Project page for **Incremental Open-Ended Deep Research with Structured Harness** (IOEDR).

Built with the [Academic Project Page Template](https://github.com/eliahuhorwitz/Academic-project-page-template) (original-version).

## Structure
- `index.html` — main page
- `static/images/` — figures (`profile.png`, `method.png`, `evidence_pool.png`, logos)
- `static/pdfs/` — put `ioedr.pdf` and optional `supplementary_material.pdf` here
- `static/css/`, `static/js/` — Bulma + carousel assets

## Local preview
```bash
cd ioedr-project-page
python3 -m http.server 8000
# open http://localhost:8000
```

## Deploy as GitHub Pages
1. Create a new repo (e.g. `ioedr-project.github.io` or any repo with Pages enabled).
2. Push the contents of this directory to the repo root (branch `main`).
3. In repo Settings → Pages, set source to `main` / `/ (root)`.

The `.nojekyll` file is included so GitHub Pages serves `static/` as-is.

## TODO
- Replace placeholder links (arXiv ID, GitHub repo URL, author pages) in `index.html`.
- Drop the paper PDF at `static/pdfs/ioedr.pdf`.
