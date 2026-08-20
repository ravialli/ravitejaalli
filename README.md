# Ravi Teja Alli Portfolio

A responsive static portfolio for **ravitejaalli.com**.

## Files

- `index.html` - site content and SEO metadata
- `styles.css` - responsive visual design
- `script.js` - mobile navigation and reveal effects
- `assets/` - optimized photos, favicon, and résumé

## Preview locally

From this folder:

```bash
python3 -m http.server 8080
```

Then open `http://localhost:8080`.

## Deployment

This is a static site, so it can be deployed to any static hosting provider. Upload the contents of this folder to the hosting root, then point `ravitejaalli.com` and `www.ravitejaalli.com` to that host using the DNS records provided by the hosting service.

## Before launch

1. Verify résumé dates, metrics, and contact details.
2. Replace the DOCX résumé with a PDF if you want the résumé button to open universally in-browser.
3. Add analytics only if you actually want visitor tracking.
4. Add a GitHub link after choosing which repositories you want public.
5. Test on desktop and mobile before changing DNS.
