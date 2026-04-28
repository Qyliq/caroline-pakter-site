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
| Update website content | Edit `index.html` → commit + push to GitHub for backup → deploy separately (drag-drop OR CLI OR set up CI) |
| Deploy via drag-drop | Open `app.netlify.com/projects/melodic-churros-37faf0` → drag the project folder onto the deploy zone |
| Deploy via CLI | `cd` into project root → `SKIP_PREFLIGHT=1 npx netlify deploy --prod --site=eaa51ee2-e5c7-49a4-a59d-2b32a26b68fe --dir=.` (after `netlify login` if session expired) |
| Wire up auto-deploy (one-time) | In the Netlify project page, click "Quick setup" → connect to `Qyliq/caroline-pakter-site` → branch `main` → blank build command → publish dir `.` |
| View live site | https://carolinepakter.com |
| Send outreach email | Use latest `email-outreach-v*.html` template |

## Context

Caroline is a contact/friend. This is a favour project, not MOUVE-related.
