# Personal website — Ángel Hernando-Veciana

Static site (plain HTML/CSS, no build step) for a personal academic page.
Migrated from the old Google Sites page.

## Files
- `index.html` — Main page (bio + contact)
- `research.html` — Publications, book chapters, working papers
- `teaching.html` — Current and past courses
- `cv.html` — CV (embeds `cv.pdf`)
- `other-activities.html` — Seminars, workshops, outreach
- `style.css` — Shared styles
- `cv.pdf` — CV shown on the CV page
- `cvshortenph.docx` — Editable source of the CV
- `profile.jpg` — Profile photo (optional; add your own)

This is a GitHub **user site** repo (`ahvecian.github.io`), so Pages serves the
files at the repository root and the site lives at `https://ahvecian.github.io/`.

## Preview locally
Open `index.html` directly in a browser, or run:
```
cd ahvecian.github.io
python3 -m http.server 8000
```
Then visit http://localhost:8000

## Publish on GitHub Pages
1. Commit and push this repo with GitHub Desktop (or `git push`).
2. On GitHub: Settings → Pages → Build and deployment →
   Source: **Deploy from a branch** → Branch: **main**, Folder: **/ (root)** → Save.
3. Wait ~1 minute; the site goes live at `https://ahvecian.github.io/`.

To edit content later, open the relevant `.html` file and change the text — no
rebuild needed.
