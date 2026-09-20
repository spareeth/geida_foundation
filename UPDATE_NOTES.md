# Site restructure — September 2026

## What changed

The site moves from a single Batch 1 resource site to a programme hub covering all GEIDA training events.

**New top-level sections:** Foundation Level — Batch 1 · Foundation Level — Batch 2 · Executive Briefing — HoDs · Foundation Level — Batch 3 (placeholder).

**Existing Batch 1 URLs are unchanged.** `agenda.md`, `day-1/` to `day-4/`, `resources/` and `glossary.md` all stay where they are, so links already circulated to Batch 1 participants continue to work. Only the root page changes: it is now the programme hub, and the Batch 1 landing content has moved to `batch-1/index.md`.

### Files added

| File | Purpose |
|---|---|
| `docs/batch-1/index.md` | Batch 1 landing page (content from the previous home page) |
| `docs/batch-2/index.md` | Batch 2 overview — the three parts |
| `docs/batch-2/agenda.md` | In-person day agenda, 10 September |
| `docs/batch-2/morning.md` | Morning session — recording, decks, content |
| `docs/batch-2/afternoon.md` | Afternoon session — recording, deck, content |
| `docs/batch-2/part-3.md` | Part 3 online follow-up — dates, structure, preparation |
| `docs/executive-session/index.md` | Executive Briefing, 9 September — recording, deck, outline |
| `docs/batch-3/index.md` | Batch 3 placeholder |
| `docs/resources/preparatory-batch-2.md` | Part 1 preparatory materials |
| `docs/stylesheets/extra.css` | Custom styles — top-level sidebar items, responsive video embeds |

### Files modified

| File | Change |
|---|---|
| `docs/index.md` | Rewritten as the programme hub |
| `docs/resources/index.md` | Preparatory materials card added, wording generalised |
| `mkdocs.yml` | `site_name`, `site_description`, `copyright`, full `nav` restructure; `navigation.sections` and `navigation.expand` removed so sidebar sections are collapsible and closed by default; `extra_css` added |

---

## Before publishing — items needing input

The Part 1 preparatory links are now in place, taken from the 1 September welcome email. Remaining items:

1. **Part 3 recordings** — `docs/batch-2/part-3.md` ends with a note that recordings will be published as the sessions are delivered. Add them after each session.
2. **SharePoint link access** — the five Part 1 videos, and the Batch 2 and Executive Briefing decks all point to SharePoint and are set to external sharing. If any access issue is reported, export the decks to PDF into `docs/assets/slides/` alongside the Batch 1 decks and update the links.
3. **YouTube visibility** — confirm whether the three recordings should stay unlisted or be made public, and check the afternoon recording for eToolkit credentials visible on screen before wider circulation.

---

## Building locally

```
pip install -r requirements.txt
mkdocs serve      # preview at http://127.0.0.1:8000
mkdocs build      # static output in site/
```

The build is clean apart from one pre-existing warning: `day-2/afternoon.md` links to `assets/slides/WaPOR_data_history.pdf`, which is not in the repository.
