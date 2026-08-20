# Ravi Teja Alli Portfolio

A responsive static portfolio for **ravitejaalli.com**.

## Files

- `index.html` - site content, SEO metadata, Open Graph/Twitter cards, and Person JSON-LD
- `styles.css` - responsive visual design
- `script.js` - mobile navigation and reveal effects
- `site.webmanifest` - PWA/install metadata and icons
- `robots.txt` / `sitemap.xml` - crawler directives
- `404.html` - themed not-found page
- `assets/` - optimized photos, favicon, apple-touch-icon, and résumé

## Preview locally

From this folder:

```bash
python3 -m http.server 8080
```

Then open `http://localhost:8080`.

## Deployment

This is a static site, so it can be deployed to any static hosting provider. Upload the contents of this folder to the hosting root, then point `ravitejaalli.com` and `www.ravitejaalli.com` to that host using the DNS records provided by the hosting service.

Some hosts (e.g. Netlify) serve `404.html` automatically; on others you may need to configure the not-found page.

## Before launch

1. Verify résumé dates, metrics, and contact details (`assets/Ravi_Resume.pdf`).
2. Add analytics only if you actually want visitor tracking.
3. Test on desktop and mobile before changing DNS.

## Notes

- `Inter` is loaded from Google Fonts. To self-host (privacy/perf), download the font and swap the `<link>` in `index.html` for a local `@font-face`.
- Open Graph/Twitter images and canonical/sitemap URLs are hard-coded to `https://www.ravitejaalli.com/`. Update them if the final domain differs.
