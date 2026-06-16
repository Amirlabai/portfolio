# Portfolio site — context

## Purpose

GitHub Pages showcase for Amir Labai: industrial engineering student who builds audit tools, web apps, and automation using AI-assisted development.

## Architecture

- Static site: `index.html` (EN), `he.html` (HE), `style.css`
- Visual style: medium blue-gray palette, retro borders (2px), offset shadows, 4px radius; no JS
- No JavaScript, no build pipeline
- Language switch via header link between the two HTML files
- SEO: `favicon.svg`, `robots.txt`, `sitemap.xml`, Open Graph + JSON-LD in both pages
- Project previews: SVG images in `images/` (featured section)

## Deploy URL

https://amirlabai.github.io/portfolio/ (GitHub Pages, branch `main`, root)

## Content themes

1. Audit and enterprise (IDEA, PyWebView, licensing)
2. AI-assisted products (Gemini, RAG, ML)
3. Full-stack and web
4. Developer utilities

## Featured projects (v2)

Top row on `#projects`: ramadan-tournament, iron-sight, sqwash-pdf, pixelate-subject — each with preview image, outcome line, and links where public.

Remaining 8 projects live in a `<details>` compact list. Private/NDA work uses `.tag--private`.

## Conventions

- Project links: public repos only (GitHub + Live where deployed); private repos listed with NDA tag, no links
- Keep `index.html` and `he.html` in sync when editing projects or structure
