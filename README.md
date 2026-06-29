# Maharani Muse — Homepage

Modern Sri Lankan fashion storefront homepage. Built as a self-contained Design Component (`.dc.html`) — open directly in any browser, no build step.

## Files
- **Maharani Muse Home v2.dc.html** — current homepage (Kelly-Felder-inspired layout, Poppins type, Maharani Muse logo).
- **Maharani Muse Home.dc.html** — earlier version (kept for reference).
- **support.js** — runtime that powers the `.dc.html` components.
- **assets/** — logo (`queen.png`, `logo-*.png`) and product/lookbook imagery.

## Features
- Auto-sliding hero (4 images) with Ken-Burns zoom-out.
- Expanding "Collection" accordion — hover a frame to maximize it.
- Product cards with a slide-up size + colour selector on hover.
- Hamburger drawer, currency switcher (LKR / USD / AED), responsive header.

## Run locally
Just open `Maharani Muse Home v2.dc.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000/Maharani%20Muse%20Home%20v2.dc.html
```

## Push to GitHub
```bash
git init
git add .
git commit -m "Initial commit: Maharani Muse homepage"
git branch -M main
git remote add origin https://github.com/<you>/<repo>.git
git push -u origin main
```

> Images in `assets/` are placeholders — swap with final product photography before launch.
