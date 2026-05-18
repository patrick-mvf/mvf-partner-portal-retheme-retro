# MVF Partner Portal re-theme — retrospective

A single-page stakeholder retro on the experiment of using a `DESIGN.md` + a
"super prompt" to re-theme an existing Lovable project (the MVF Partner Portal)
to match a different Lovable template (the MVF Dashboard Template, Flowbite).

## Run locally

It's a single static `index.html`. Open the file directly in a browser, or:

```sh
python3 -m http.server 4173
# → http://localhost:4173
```

## Deploy

Vercel-ready. No build step, no framework — Vercel will serve `index.html` as a
static site. Import the repo and accept defaults.

## Sources

- `index.html` — the report
- `screenshots/` — captured 2026-05-18 from the live previews:
  - `target-template.png` — `mvf-dashboard-template.lovable.app`
  - `remix-outcome.png` — Partner Portal preview after re-theme
  - `remix-sidebar.png` — sidebar drawer opened
  - `remix-campaigns.png` — `/campaigns` page after re-theme
- Underlying chat log: `~/Downloads/chat-log-retro.md` (not in repo, kept private)
- Underlying remix repo: <https://github.com/patrick-mvf/remix-design-md-super-prompt-of-mvf-partner-portal>
