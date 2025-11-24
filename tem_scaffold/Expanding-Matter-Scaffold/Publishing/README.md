# Publishing (Optional)

These files enable a free documentation site with **MkDocs + Material**.
Nothing runs automatically; keep these here until you’re ready.

## Steps to enable

1) Install dependencies locally:
   ```bash
   pip install -r Publishing/requirements.txt
   ```

2) Local preview:
   ```bash
   mkdocs serve
   ```

3) GitHub Pages (one time):
   - Create folder: `.github/workflows/` at the repo root (if it doesn’t exist)
   - Move **Publishing/gh-pages.yml** to `.github/workflows/gh-pages.yml`
   - Commit & push
   - In GitHub → **Settings → Pages**, set source to the `gh-pages` branch (if not already)

Your site will publish from the `docs/` directory.
