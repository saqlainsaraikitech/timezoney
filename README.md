# TimeZoney — Timezone Converter for Creators

![HTML](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JS](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Backend](https://img.shields.io/badge/Backend-None-22c55e)

**TimeZoney** — a fast, SEO-ready timezone converter built for content creators who post across countries.

## What it does

- Auto-detects the visitor's timezone
- Converts posting times across countries — DST-aware
- Country search, quick-time presets, multi-country targeting
- Share panel for converted times
- 9 pages: converter, guide, articles, FAQ (with Google structured data), about, contact + legal pages

## Tech notes

- Pure static HTML/CSS/JS — **no backend, no build step, no dependencies**
- Restrictive Content-Security-Policy baked into every page
- Ad slots wired on all pages (drop in your AdSense code after approval)
- SEO-complete: keyword-rich meta tags, creator-targeted articles, FAQ schema

## Project structure

```
index.html        # the converter app
guide.html        # how-to guide for creators
articles.html     # SEO articles
faq.html          # FAQ + structured data
about.html contact.html
privacy.html terms.html disclaimer.html
assets/           # logo, mark, favicons
```

## Run it

Just open `index.html` in a browser — or upload the folder to any static host
(Hostinger `public_html`, Netlify, Vercel, GitHub Pages).

## License

All rights reserved — DigitalMax / Saqlain Abid.
