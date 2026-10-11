# GEIDA Training site

MkDocs Material site for the IsDB GEIDA Staff Certification Programme (developed by Terra, Expo City Dubai). Originally built in Claude chat; now maintained here.

- Content lives in `docs/` (Markdown); navigation is defined explicitly in `mkdocs.yml` `nav:` — every new page must be added there.
- Slide PDFs go in `docs/assets/slides/`; recordings are YouTube embeds; some decks/videos link to SharePoint.
- Batch 1 URLs (`agenda.md`, `day-1/`…`day-4/`, `resources/`, `glossary.md`) were circulated to participants — do not move or rename them.
- See `UPDATE_NOTES.md` for the September 2026 restructure and open items.
- Remote: `git@github.com:spareeth/geida_foundation.git`, branch `main`. Commit messages are short lowercase phrases (e.g. "added batch 2 online session1 recordings").
- Workflow ends at `git push` to `main`; the user deploys to the server separately. Do not add deployment steps.

## Local build (Windows)

Use the `.venv/` virtual environment.

```
python -m venv .venv
.venv\Scripts\pip install -r requirements.txt
.venv\Scripts\mkdocs serve   # http://127.0.0.1:8000
.venv\Scripts\mkdocs build   # output in site/ (gitignored)
```

Run `mkdocs build` after edits to check for broken links (a few pre-existing anchor INFO messages in `agenda.md` are known).
