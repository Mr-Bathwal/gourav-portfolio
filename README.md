# Gourav Bathwal — Portfolio

**Live:** https://mr-bathwal.github.io/gourav-portfolio/

An "Aurora"-themed personal portfolio — an animated hero, a live **Aurora Ops**
agent-console demo, a filterable project grid, skills, and contact. It's a single
self-contained `index.html` (inline CSS + JS, no build step, no dependencies),
deployed to GitHub Pages automatically on every push to `main`.

## Files
- `index.html` — the entire site (styles + script inlined)
- `Gourav_Bathwal_Resume_WithPortfolio.pdf` — résumé, linked from the site
- `Gourav_Bathwal_Resume_WithPortfolio.txt` — plain-text résumé
- `.github/workflows/deploy.yml` — GitHub Pages deployment
- `.nojekyll` — disables Jekyll processing

## Editing
Everything is in `index.html`:
- **Projects** — the `PROJECTS` array in the `<script>` near the bottom. Each entry is
  `{ t: title, cat: 'ai'|'blockchain'|'fullstack'|'frontend', url, d: description, tags: [...] }`.
- **Colors** — the CSS variables at the top (`--violet #A78BFA`, `--blue #60A5FA`, `--teal #5EEAD4`).
- **Social links** — replace the `href="#"` placeholders (LinkedIn / LeetCode) in the Contact section.

Preview locally by opening `index.html` in a browser.
