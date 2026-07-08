# Chhapac.decks — one-pager website

Single-page site for Chhapac's pitch deck arm.

- `index.html` — the entire site (self-contained: styles, scripts, and SVG assets inline; only external dependency is Google Fonts)
- `vercel.json` — config for optional Vercel hosting

## Deploy targets
- HostGator: upload `index.html` to `public_html/pitch-chhapac-com`
- GitHub Pages: Settings → Pages → deploy from `main` branch
- Vercel: `vercel deploy --prod`
