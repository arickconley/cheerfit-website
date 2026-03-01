# CheerFit Website

Marketing landing page for [CheerFit](https://cheerfit.arick.io/) — the personal workout app for cheerleaders and gymnasts.

## Hosting

The site is hosted on **Cloudflare Pages**, deployed automatically from the `main` branch of this repo.

- **URL:** https://cheerfit.arick.io/
- **Build:** No build step — static HTML served directly
- **Branch:** `main` triggers automatic deploys

## Structure

```
index.html          Landing page
privacy-policy.html Privacy policy
robots.txt          Search engine crawler rules
sitemap.xml         Sitemap for search engines
favicon.ico         Browser tab icon
img/                Screenshots, OG image, and favicon PNGs
```

## Local Development

```bash
python3 -m http.server 8000 --directory .
```

Then open http://localhost:8000.
