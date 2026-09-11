# lingshu-website

Source for the LingShu AI Infra organization website.

**Live**: https://lingshu-ai-infra.github.io/lingshu-website/

## Structure

```
lingshu-website/
├── index.html         # single-page site
├── style.css          # all styles (no framework)
├── assets/
│   ├── logo.svg       # nav + footer logo
│   └── favicon.svg    # browser tab icon
├── .nojekyll          # skip Jekyll on GitHub Pages
└── README.md
```

## Local preview

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Deploy

Push to `main` — GitHub Pages publishes automatically.

## Tech

- Pure HTML + CSS (no npm, no build step)
- Dark hero / light content / accent `#00d4aa` (cyan-green)
- Responsive (mobile-first)