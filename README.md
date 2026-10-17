# Blocklogic Studio website

Static site for **[blocklogic.studio](https://blocklogic.studio)** (or your Netlify URL).

## Deploy on Netlify

1. Push this repo to GitHub (`blocklogic-studios/website`).
2. [Netlify](https://app.netlify.com) → Add new site → Import from Git.
3. Build command: leave empty or use the one in `netlify.toml`.
4. Publish directory: `.` (repo root).
5. Add custom domain → then update `canonical` / `sitemap.xml` / `robots.txt` if the domain isn’t `blocklogic.studio`.

## Google Search Console

1. https://search.google.com/search-console
2. Add property → URL prefix → your live Netlify or custom domain.
3. Verify via DNS or HTML file (drop Google’s file in this repo root).
4. Submit `https://YOUR_DOMAIN/sitemap.xml`

## Screenshots

Put images here:

- `assets/addons/carriercore-preview.png`
- `assets/addons/financecore-preview.png`

## Donate / contact

Edit `donate.html` and `contact.html` with real Ko-fi, Sponsors, and email when ready.
