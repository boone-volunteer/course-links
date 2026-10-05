# Course Links Page

A free, Linktree-style links page for Art of Living teachers — no subscriptions, no build step. Just one file: `index.html`.

## For another teacher: make your own in 5 minutes

1. Fork this repo (or copy `index.html` into a new repo).
2. Open `index.html` and edit **only the config block** near the top of the `<script>`:
   - `SITE` — your name, tagline, photo URL, email, phone.
   - `COURSES` — your course list. One entry per course:
     `title, dates, times, format ("online" | "inperson"), venue, price, wasPrice, instructor, url`.
   - `SERIES` — recurring free series (weekly meditation, yoga, etc.).
   - `RESEARCH` — your research highlights (optional).
   - `EXTRA_LINKS` — socials, WhatsApp groups, anything else (optional).
3. Commit and push. GitHub Pages serves it automatically.

No code changes needed below the config block.

## Enable GitHub Pages (first time)

1. Create a repo named `<username>.github.io` (exactly — this gives the clean
   `https://<username>.github.io/` URL with no repo suffix).
2. Copy `index.html` (and this README) into the repo, push.
3. Settings → Pages → Deploy from a branch → `main` / `/(root)` → Save.
Your page goes live at `https://<username>.github.io/` within a minute or two.

## Local preview

Just open `index.html` in a browser — everything runs from the single file.
