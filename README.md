# Caducus Worldbuilding Repository

This repository is set up to keep canon worldbuilding data in plain-text Markdown while publishing a browsable website via GitHub Pages.

## Goals

- **Human-friendly editing:** write and review in Markdown.
- **AI-friendly structure:** stable filenames, consistent frontmatter, and lightweight metadata.
- **Easy publishing:** automatic deploy to GitHub Pages on every push to `main`.

## Repository Layout

```text
canon/                   # Source of truth for canonical lore
  entities/
  locations/
  factions/
  timelines/
  systems/
  glossary/

templates/               # Copy-ready templates for new entries
docs/                    # Homepage and supporting site docs
.github/workflows/       # CI + GitHub Pages deploy pipeline
```

## How to Use

1. Add or edit canon files under `canon/`.
2. Use templates from `templates/` for consistency.
3. Keep frontmatter fields and IDs stable.
4. Push to GitHub; Pages auto-updates the published site.

## Local Preview (optional)

This site uses [MkDocs](https://www.mkdocs.org/).

```bash
python -m pip install -r requirements.txt
mkdocs serve
```

Then open `http://127.0.0.1:8000`.

## Suggested GitHub Setup

1. Create a GitHub repo and push this project.
2. In **Settings → Pages**, ensure source is **GitHub Actions**.
3. Protect `main` branch and require PRs.
4. Optionally add issue templates for "new lore entry" and "canon change request".
