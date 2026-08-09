# Platform 1888

Static one-page website for Platform 1888, a Vietnamese kitchen and coffee shop in Geebung, QLD, right next to Geebung Station.

Live site: https://platform1888.com.au/

## Structure

- `index.html`: the entire site (hero, about, menu, location and hours, contact form)
- `assets/logo.jpeg`: site logo used for social sharing
- `assets/favicon/`: favicon set (PNG, ICO, SVG, web manifest) plus `apple-touch-icon.png` and Android Chrome icons
- `favicon.ico`: root-level favicon fallback
- `robots.txt`: crawler rules and sitemap reference
- `sitemap.xml`: sitemap for search engines

## Running locally

No build step is required. Serve the folder with any static file server, for example:

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000 in a browser.

## Deployment

Publish the contents of this folder as-is to the web host serving `platform1888.com.au`.
