# Cleaners Payment Monitoring System

A web-based system for monitoring per-student cleaning-fee collections, with daily input and automatic weekly and monthly reports.

**Live app:** publish `index.html` via GitHub Pages (see below), then open the link it gives you.

## What it does
- Daily collection input per student
- Weekly collection summary (per student + totals)
- Monthly lumpsum collection report
- Dashboard: collected, expected, outstanding, collection rate, paid/partial/unpaid
- Add students one-by-one or bulk paste / CSV upload
- Searchable payment log, CSV export, print
- Secure login — data stored online in Supabase, shared across all signed-in users

## Publish (GitHub Pages)
1. Create a public repository.
2. Upload **`index.html`** (and this README, plus the empty `.nojekyll` file).
3. **Settings → Pages → Deploy from a branch → main → /(root) → Save.**
4. Wait ~1 minute; your link appears at the top of the Pages settings.

## First-time login
Before you can sign in, create an account: Supabase dashboard → Authentication → Users → Add user (Auto Confirm). Full steps are in `DEPLOYMENT_GUIDE.md`.

## Custom domain (GoDaddy)
See `DEPLOYMENT_GUIDE.md`, Part C.
