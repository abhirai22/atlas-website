# ATLAS Business Solutions LLP — Website

Static site. No build step, no dependencies.

## Structure
```
index.html          Home
about.html          Vision, brands, structure, roadmap
contact.html        ATLAS Pulse request form + FAQ
privacy.html        Privacy policy (linked from every footer)
services/           One page per wing (axis, orbit, cosmos, platforms)
_headers            Security headers (Cloudflare Pages)
_redirects          /services -> AXIS
sitemap.xml         Replace REPLACE-WITH-YOUR-DOMAIN before launch
```

## Deploy (Cloudflare Pages)
Framework preset: **None**
Build command: *(leave blank)*
Build output directory: `/`

## Before launch
- [ ] Wire the contact form to a form service (Formspree / Web3Forms / Cloudflare Worker)
- [ ] Add a phone number on contact.html
- [ ] Have privacy.html reviewed by counsel
- [ ] Replace REPLACE-WITH-YOUR-DOMAIN in sitemap.xml and robots.txt
- [ ] Swap raster logos for vector originals if available
