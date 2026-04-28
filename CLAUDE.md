# Caroline Pakter Website

> Personal website for Caroline Pakter (singer/performer)

## What This Is

Simple static website for Caroline Pakter, a Jewish singer. Single-page site with bio, performances, and contact.

## Key Files

| File | Purpose |
|------|---------|
| `index.html` | The website |
| `images/` | Photos and album art |
| `email-outreach-v*.html` | Email templates for booking outreach |
| `CAROLINE-PAKTER-WEBSITE-REFERENCE.md` | Full project reference |

## Deployment

- **Host:** Netlify
- **Custom domain:** `carolinepakter.com`
- **Project name + ID:** look up in Netlify dashboard or `netlify status` (intentionally not committed to this public repo)
- **Deploy method as of 28 Apr 2026:** wired to GitHub for continuous deployment from `main`. Push to main → Netlify auto-builds. (Pre-28 Apr the site was deployed via manual Netlify Drop — switched to git-connected so all updates flow through the same `git push` workflow used for the rest of the Qyliq client portfolio.)
- **CLI deploy alternative (if CI is ever down):** `SKIP_PREFLIGHT=1 npx netlify deploy --prod --site=<site-id> --dir=.` (requires `netlify login` first; site ID is in the dashboard or `netlify status` output)

## Common Tasks

| Task | How |
|------|-----|
| Update website content | Edit `index.html` → `git commit -am "..." && git push origin main` → live in ~60s (Netlify CI) |
| View live site | https://carolinepakter.com |
| Manual deploy via drag-drop (fallback) | Open the Netlify dashboard → find the site → drag the project folder onto the deploy zone |
| CLI deploy (fallback) | `cd` into project root → `SKIP_PREFLIGHT=1 npx netlify deploy --prod --site=<site-id> --dir=.` (look up site-id in Netlify dashboard or `netlify status`; run `netlify login` first if session expired) |
| Send outreach email | Use latest `email-outreach-v*.html` template |

> Operational identifiers (Netlify project name, site ID, badge URL) live in the private ledger at `~/.claude/ledger/caroline-pakter-site.md`, not here — this file is in a public repo.

## Context

Caroline is a contact/friend. This is a favour project, not MOUVE-related.
