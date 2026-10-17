# Shivansh Tiwari — Personal Portfolio

**Live site:** https://shivanshencored.github.io/ShivanshPortfolio/

A fast, single-page portfolio about Shivansh's interests in AI, fintech, finance and entrepreneurship. It shows his interests, a research project in progress, and a learning journey, and has a working contact form.

## Features
- Responsive design for phones, tablets and desktops
- Interests section: pinned horizontal scroll on desktop, swipe carousel on touch devices
- Smooth animations with GSAP and ScrollTrigger (reduced-motion preferences respected)
- Contact form via [Formspree](https://formspree.io), with validation and spam protection
- SEO: meta tags, Open Graph / Twitter cards, JSON-LD (Person, WebSite), sitemap and robots.txt
- Accessibility: skip link, keyboard focus styles, semantic HTML, ARIA labels

## Project structure
| File | Purpose |
|---|---|
| `index.html` | The whole site: HTML, CSS and JavaScript |
| `img.png` / `img.webp` | Hero portrait (WebP is served first, PNG is the fallback) |
| `og-image.png` | 1200×630 preview image for shared links |
| `sitemap.xml` / `robots.txt` | Search engine files |

## Editing content
All text content lives in the `SITE` object near the top of the `<script>` in `index.html`: interests, projects, journey steps, social links and the form endpoint. Edit it there; no HTML changes needed. To add a project, copy the project block inside `projects`.

Colours and fonts are CSS variables at the top of the `<style>` block.

## Run locally
Open `index.html` in a browser, or run `python3 -m http.server` in this folder and visit `http://localhost:8000`.

## Deploy
Hosted with GitHub Pages: **Settings → Pages → Deploy from a branch → `main` / root**. Every commit to `main` updates the site within a minute or two.

## Tech
HTML5, CSS3, vanilla JavaScript, [GSAP 3.12](https://gsap.com) (loaded from cdnjs), Google Fonts (Space Grotesk, Inter, IBM Plex Mono, Cormorant Garamond).

## Contact
- YouTube: [@ShivanshEncored](https://www.youtube.com/@ShivanshEncored)
- GitHub: [ShivanshEncored](https://github.com/ShivanshEncored)
- X: [@ShivanshTiwariS](https://x.com/ShivanshTiwariS)

© Shivansh Tiwari. All rights reserved.
