# Prabhupada Conscious Creations ❤️

A single-page website for a devotional handmade craft business: pipe cleaner flowers, lotus holders, garlands and malas, and pottery and altar decor. Customers browse the catalog and place orders directly over WhatsApp (+91 9064897128).

## Features
- Saffron, maroon and gold devotional theme with a subtle lotus pattern
- Light, Dark and System theme modes, remembered between visits
- Hero with Bhagavad-gītā 9.26 (Devanagari, transliteration, translation)
- Product catalog with category tabs, live search, badges, prices, and a lightbox for larger photos
- One-tap WhatsApp ordering for each product
- Custom order form that formats the request and opens WhatsApp
- Footer honoring Śrīla Prabhupāda, with quotes and contact links

## Technology
Plain HTML, CSS and JavaScript in one file (`index.html`), with no build step. Images are served through the Netlify Image CDN (`/.netlify/images`), so visitors receive resized WebP versions.

## Adding your own products and photos
1. Put your photos in the `img/` folder.
2. Open `index.html` and find the `PRODUCTS` list (marked `PRODUCT CATALOG`) near the bottom.
3. Add or edit entries with a title, category, image paths, tag (`Best Seller`, `New` or empty), price text, search keywords and a description. A product with several images gets thumbnails in the lightbox.

## Running locally
```bash
netlify dev
```
Netlify Dev is needed for the image CDN URLs to work locally. Any static server will show the page, but the images won't load without it.
