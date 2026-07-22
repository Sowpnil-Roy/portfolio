# Sowpnil Roy — Portfolio

A fast, single-page personal portfolio (Home · Publications · Showcase) with light/dark mode.
Built as a static site — no build step, no framework. Just open `index.html`.

## Files
- `index.html` — the whole site (structure, styles, and interactivity).
- `assets/profile.jpg` — profile photo (replace with your own, keep the same name).
- `assets/Sowpnil_Roy_CV.pdf` — CV opened by the "Curriculum Vitae" button.

## Publish free on GitHub Pages
Your site will be live at **https://<username>.github.io/**

1. Put these files in the **root** of your GitHub Pages repo
   (for a user site, the repo must be named `<username>.github.io`).
2. Commit and push:
   ```bash
   git add -A
   git commit -m "Publish portfolio"
   git push
   ```
3. In the repo: **Settings → Pages** → Source: **Deploy from a branch** →
   Branch: `main` / folder: `/ (root)` → **Save**.
4. Wait ~1 minute, then open `https://<username>.github.io/`.

## Editing later
- Text, links, publications, and projects live in the `<script>` block near the
  bottom of `index.html` (the `PUBS`, `PROJECTS`, and `HONORS` lists) — edit the
  strings and links there.
- To change the photo, replace `assets/profile.jpg` (same filename).
- To change the CV, replace `assets/Sowpnil_Roy_CV.pdf` (or update the link in `index.html`).
