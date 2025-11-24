# Expanding Matter (TEM) — Working Manuscripts

This repository is an **active research space** for the Theory of Expanding Matter (TEM): drafts, proofs, notes, figures, and publishing scaffolding.
It is organized to work well with **plain Markdown**, **Obsidian**, **VS Code**, and (optionally) **MkDocs + Material** when you want a free docs site.

## Layout

- `docs/` — your primary content (works out‑of‑the‑box for MkDocs if you later enable publishing)
  - `Manuscripts/` — papers/chapters (TEM‑00, TEM‑01, TEM‑02, …)
  - `Proofs/` — detailed proofs and derivations (e.g., Proofs‑Only)
  - `Glossary/` — shared terms, notation, style
  - `Notes/` — scratch, daily logs, ideas
  - `Figures/` — images/diagrams used by manuscripts
  - `Templates/` — authoring templates (paper, theorem, proof)
  - `javascripts/` — MathJax config for live math when publishing
- `Publishing/` — optional files for **MkDocs + GitHub Pages**; nothing auto‑runs until you move the workflow file into `.github/workflows/`.
- `mkdocs.yml` — optional site config (harmless if unused).

## Quick start (no publishing)

1. Put your `.md` documents in `docs/Manuscripts/` (and link them from `docs/index.md`).
2. Keep proofs in `docs/Proofs/`, glossary/style in `docs/Glossary/`, images in `docs/Figures/`.
3. Commit and push like any normal Git repo.

## Optional free publishing (MkDocs + Material)

- Requirements (local): `pip install -r Publishing/requirements.txt`
- Local preview: `mkdocs serve` (opens http://127.0.0.1:8000/)
- One‑time setup for GitHub Pages:
  1. Move `Publishing/gh-pages.yml` to `.github/workflows/gh-pages.yml`
  2. Commit & push; then in GitHub → **Settings → Pages**, set source to the `gh-pages` branch (if not auto‑enabled).
  3. Your site will be published from the content under `docs/`.

## File naming (suggestion)

Use `TEM-XX_Title_With_Underscores.md` for manuscripts, e.g.
- `TEM-00_Existential_Necessity_of_Expansion.md`
- `TEM-01_Rational_Resonance_Radix.md`
- `TEM-02_Projective_Completeness_Theorem.md`

## Git hygiene

- Large binaries (>100 MB) don’t belong in Git without LFS; keep figures small when possible.
- Obsidian cache/workspace files are ignored by default (see `.gitignore`).

---

_Scaffold generated 2025-11-24._
