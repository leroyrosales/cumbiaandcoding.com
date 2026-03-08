# Cumbia & Coding

A one-page resource shrine for dev + design: curated links, a cumbia/tejano playlist, and good taste. No hustle, no CTAs—just bookmarks and music.

**Live:** [cumbiaandcoding.com](https://cumbiaandcoding.com)

## What’s in it

- **Playlist** — Cumbia/Tejano YouTube playlist for building and fixing
- **Resources** — Cheatsheets, docs, learning (MDN, web.dev, PHP, WordPress, performance, etc.)
- **Toolbox** — Generators, image tools, validators, playgrounds, editors, hosting, CMS
- **Design** — Inspiration, UX, typography, color, accessibility
- **Careers + Fun** — Job boards, podcasts, videos, engineering blogs, weird internet

## Tech

- **Single HTML file** — `index.html` with inline CSS
- **No JavaScript** — Smooth scroll and “Back to top” use CSS and anchor links
- **No build step** — Open the file in a browser or serve the folder with any static server

Focused on:

- **Accessibility** — Skip link, semantic markup, `aria-*`, `focus-visible`, reduced motion
- **Performance** — One request for the page, lazy-loaded iframe
- **Semantic structure** — Sections, articles, landmarks for screen readers

## Run locally

Serve the project root with any static server, for example:

```bash
# Python 3
python3 -m http.server 8000

# Node (npx)
npx serve .

# PHP
php -S localhost:8000
```

Then open `http://localhost:8000` (or the port your server uses).

Or open `index.html` directly in a browser (some features like smooth scroll to anchors work the same).

## Project layout

```
.
└── index.html   # Single-page site (HTML + inline CSS)
```

## Author

**Leroy Rosales** — [Email](mailto:leroyrosales@gmail.com) · [GitHub](https://github.com/leroyrosales) · [LinkedIn](https://www.linkedin.com/in/leroyrosales/)

Cumbia & Coding is a personal project and not affiliated with any of the linked resources.

---

© 2026 Cumbia & Coding.
