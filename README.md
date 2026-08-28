# Natalia Henry — academic website

A minimal static site (plain HTML/CSS/JS) styled after the al-folio academic
theme. No build step — GitHub Pages serves the files as-is. All links are
relative, so it works both at a root domain and under `/nat_website/`.

## Pages
- `index.html` — About
- `research.html` — Research
- `teaching.html` — Teaching
- `cv.html` — CV

## How to update the placeholders I left

**Photo (About):** Add your image at `assets/img/natalia.jpg`, then in
`index.html` replace the `<div class="photo-placeholder">…</div>` block with:
```html
<img src="assets/img/natalia.jpg" alt="Natalia Henry">
```

**Bio (About):** Edit the paragraph under `class="profile-body"` in `index.html`.

**CV link:** In `cv.html`, replace `href="#"` with your Dropbox URL.
Append `?raw=1` to open the PDF in the browser, or `?dl=1` to force a download.

**Social links (About):** Add `<a>` tags inside `<div class="social">` in
`index.html` (e.g. Google Scholar, LinkedIn, ORCID, X/Twitter).

## Publishing on GitHub Pages
Push to `main`, then in the repo: **Settings → Pages → Build and deployment →
Source: Deploy from a branch → Branch: `main` / root**. The site will appear at
`https://nathenry-dev.github.io/nat_website/`.
