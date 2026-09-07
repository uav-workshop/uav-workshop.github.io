# AI-Enabled Next-Generation UAV Communications — Workshop Website

A responsive, dependency-free single-page website matching the visual identity of the workshop brochure.

## Files
- `index.html` — all workshop text/content
- `styles.css` — colors, layout and responsive design
- `script.js` — mobile navigation
- `assets/` — IIT (ISM), centenary, ANRF and UAV hero artwork

## Editing
Open `index.html` in any text editor and replace placeholders such as:
- `DD–DD Month 2026`
- speaker names/institutes
- convenor/co-convenors
- fees
- registration link
- contact email

The visual theme can be changed at the top of `styles.css` under `:root`.

## Preview locally
Just double-click `index.html`, or run:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Publishing
This is a static site and can be hosted directly on GitHub Pages, institute web hosting, Netlify, Cloudflare Pages, or any standard web server.
