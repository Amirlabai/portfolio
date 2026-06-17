# Portfolio site — context

## Purpose

GitHub Pages showcase for Amir Labai: industrial engineering student who builds audit tools, web apps, and automation using AI-assisted development.

## Architecture

- **Static HTML/CSS** at repo root — no build pipeline
- **Pages:** `index.html` (EN), `he.html` (Hebrew RTL)
- **Visual style:** retro brutalism — medium blue-gray palette, 2px hard borders, 4px offset shadows, 4px radius
- **Icons:** devicons CDN for header GitHub/LinkedIn only (no body icons)
- **CV download:** `amir-labai-cv.pdf` linked from header on both pages
- **Deploy:** GitHub Pages from `main` branch root
- **SEO:** meta tags, `robots.txt`, `sitemap.xml`, JSON-LD in each HTML file

## Deploy URL

https://amirlabai.github.io/portfolio/ (GitHub Pages, branch `main`, root)

## Content themes

1. Audit and enterprise (IDEA, PyWebView, licensing)
2. AI-assisted products (Gemini, RAG, ML)
3. Full-stack and web
4. Developer utilities

## Featured projects

Top row on `#projects`: ramadan-tournament, iron-sight, sqwash-pdf, pixelate-subject — WebP previews, outcome lines, GitHub/Live links.

Remaining 8 projects in `<details>` compact list. Private/NDA work uses `.tag--private`.

## Conventions

- Project links: public repos only; private repos listed with NDA tag, no links
- Keep `index.html` and `he.html` in sync when editing copy
- Do not introduce glassmorphism, soft shadows, or gradient backgrounds — brutalist tokens only
- Hebrew tagline: **מהנדס תעשייה וניהול** (not just מהנדס תעשייה)
