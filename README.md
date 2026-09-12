# Peyton Yen — One-Page Real Estate Site

A luxury single-page website (static HTML, no build step required).

## Files
- `index.html` — the entire website (all CSS + JS inline)
- `peyton.jpg` — Peyton's headshot (referenced by index.html — keep it in the same folder)
- `vercel.json` — Vercel config (clean URLs + security headers)

## Already wired
- Headshot: Peyton's photo is built into the hero.
- Contact form: embedded live Tally form (https://tally.so/r/ODENvk) with an
  "open in new tab" fallback button. Submissions go to your Tally account.

## Deploy to Vercel — pick one

### Option A — Drag & drop (easiest, no install)
1. Go to https://vercel.com/new
2. Click **"Deploy"** → look for the option to upload / drag a folder,
   or use the Vercel dashboard "Add New… → Project → Deploy a template/upload".
   (Simplest: install the CLI, Option B — the dashboard upload flow changes often.)

### Option B — Vercel CLI (recommended, ~1 minute)
1. Install once:  `npm i -g vercel`
2. From inside this folder, run:  `vercel deploy --prod`
3. First run asks you to log in (browser) and confirm project settings — accept defaults.
4. It prints your live URL, e.g. `https://peyton-yen.vercel.app`

No token needed — the CLI logs you in through the browser.

### Option C — GitHub + Vercel (best for ongoing edits)
1. Create a new GitHub repo and push these files.
2. In Vercel: **Add New → Project → Import** the repo → **Deploy**.
3. Every future edit you push auto-deploys.

## One thing left to confirm
- **Email:** `peyton.yen@charneybrokerage.com` is a best-guess placeholder
  (the source page hid the real address). Search for it in `index.html` and
  replace with her real address if different (it appears twice).
