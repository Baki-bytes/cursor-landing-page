    # Cursor Landing Page — Recreated Sections ✅

## Overview
This repository contains a static recreation of a Cursor-style landing page (HTML/CSS). It includes the main visual sections and styling used for the project.

---

## 🔧 Sections recreated
- **Header / Navigation** (`nav`) — brand, features, enterprise, pricing, sign in / download
- **Hero / Main** (`.main-section-upper`) — headline, subtext, CTA and hero image
- **Customer logos** (trusted-by row)
- **Feature containers** — three feature panels that highlight product areas
- **Testimonials** — quote cards with avatars and attribution
- **Testing / Product cards** — model/feature highlight cards
- **Changelog** — release notes list
- **Final call / Join CTA** — final section with image and button
- **Recent highlights / Bottom cards** — blog/news/updates area

---

## 🎨 Fonts & Colors
**Fonts used**
- Primary: `CursorGothic` (fallbacks: system-ui, Helvetica, Arial)
- UI / headings: `Space Grotesk`
- Google fonts preloaded: `Plus Jakarta Sans`, `Roboto`, `Space Grotesk` (see `<link>` in `cursor.html`)

**Color palette**
- Background: `#14120B` (deep dark)
- Primary text: `#EDECEC` / rgb(237,236,236)
- Secondary background/card: `#1B1913`
- Muted grays: `#999393`, `#333D3F`
- Accent links: inline `red` used for some links
- CSS variable: `--text-color: rgba(237, 236, 236, 0.6)`

---

## 📸 Screenshots (recommended)
Include live screenshots in the repo for quick evaluation.

Suggested folder: `Assets/screenshots/`
- `Assets/screenshots/hero.png` — hero + nav
- `Assets/screenshots/features.png` — feature containers
- `Assets/screenshots/testimonials.png` — testimonials section

How to capture (Windows): use Snipping Tool or press `PrtScn`, save as PNG, and add to the suggested folder.

Embed screenshots in this README using markdown:

```md
![Hero screenshot](Assets/screenshots/hero.png)
```

---

## 🚀 Host the site (public GitHub + GitHub Pages)
1. Create a **public** GitHub repo and push the project (all files in root). Example commands:

```bash
git init
git add .
git commit -m "Initial site recreation"
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```

2. In GitHub, go to **Settings → Pages** and set the source to branch `main` and folder `/ (root)` (or use `gh-pages` branch). Save — GitHub will provide a site URL.

Alternative hosting: Netlify or Vercel (drag & drop or connect repo) for automatic deploys.

> Note: Make repository public for easy evaluation and provide the GitHub Pages URL or Netlify/Vercel URL in your submission.

---

## ▶️ Run locally
- Open `Landing page/cursor.html` in a browser, or run a simple server (recommended):

```bash
# Python 3
python -m http.server 8000
# then open http://localhost:8000/Landing%20page/cursor.html
```

or install `Live Server` in VS Code and open the file.

---