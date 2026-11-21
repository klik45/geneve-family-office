# Fiduciaire de la Côte — Family Office & Gestion Privée · Genève

A bespoke, bilingual French/English website dedicated exclusively to the Geneva Family Office. Static HTML, CSS and vanilla JavaScript; no build step, framework, external API or form backend required.

## Contents

- `index.html` — semantic, search-friendly bilingual site and FinancialService structured data.
- `styles.css`, `app.js` — responsive editorial design, accessible language toggle, contact dialog and reduced-motion-aware reveals.
- `assets/` — Fiduciaire de la Côte logo, SVG favicon and optimized WebP Geneva/office photographs.
- `site-preview-standalone.html` — complete, single-file preview with local images, CSS and JS embedded.
- `404.html` — lightweight GitHub Pages fallback.

## Run locally

Open `index.html` in a modern browser, or run `python3 -m http.server 8000` in this directory and visit `http://localhost:8000`. No install or build step. The standalone preview can be opened directly without a server.

## Deploy on GitHub Pages

1. Commit the project files at the repository root and push to GitHub.
2. In **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, and save.
3. GitHub Pages publishes `index.html`; it uses relative asset paths and needs no compilation. For a custom hostname, copy `CNAME.example` to `CNAME`, replace its example hostname with a domain you control, then configure the DNS records with your registrar.

## Features & privacy

- Instant FR/EN toggle; preference remembered locally in the browser.
- Keyboard-accessible landmarks, skip link, focus styling, semantic headings and native contact dialog; motion respects `prefers-reduced-motion`.
- Contact is intentionally private-by-design: the dialog prepares a `mailto:` message addressed to `geneve@fiduciaire-de-la-cote.ch`; no information is submitted to or stored by a backend. Availability of the recipient address has not been independently confirmed.
- No telephone number is displayed. Geneva meetings are by confidential appointment. Map directions open Google Maps in a separate tab.
- Google Fonts are requested from Bunny Fonts; system serif/sans fallbacks remain in the CSS if offline.

## Before publishing

Confirm the contact email `geneve@fiduciaire-de-la-cote.ch`, address formatting, map location and the live `og:image` URL. The uploaded Jet d'Eau image was **not** used: its visible branding identifies another firm. Geneva photographs already present in the supplied workspace were reused instead.
