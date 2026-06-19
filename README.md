# VICJEN Housing Tech

AI-powered real estate platform connecting verified buyers and sellers, valuing land and property, and developing affordable housing across Anambra State and Abuja, Nigeria.

**Live site:** [vicjenhousingtech.org](https://vicjenhousingtech.org)

---

## About

VICJEN Housing Tech is a Nigerian proptech company founded by Victor and Jennifer, headquartered in Anambra State with operations in Abuja. The company operates across the full property value chain:

- **Verified marketplace** — real-time listings connecting buyers directly with reliable, verified sellers
- **AI property valuation** — data-driven valuations for land and property
- **Building cost estimation** — AI-assisted construction and development cost estimates
- **Land and property trading** — direct acquisition and resale
- **Estate development** — building and developing housing stock
- **Affordable letting** — properties let at 10% below average market rate

Alongside the commercial business, VICJEN Housing Tech is committed to ending homelessness through below-market rent and a standing rent-sponsorship pledge for families in need, beginning July 2026.

Read the full founder story and mission on the [About section](https://vicjenhousingtech.org/#story) of the live site.

---

## This repository

This repository contains the source code for the VICJEN Housing Tech marketing website, including a working interactive demo of the property search and AI valuation tools.

### What's included

- `index.html` — the complete site: a single self-contained HTML file with embedded CSS and JavaScript
- `LICENSE.md` — usage rights for this repository

### Live demo features

The site includes a functional, in-browser demo (not a static mockup) under the **Try It Live** section:

- **Property search** — filter a sample set of listings by location, property type, and maximum price
- **AI valuation tool** — enter a property's location, type, size, condition, and road access to generate a live estimated value with a price range and breakdown
- **Contact** — each listing includes a "Contact about this property" button that opens a pre-filled email to the VICJEN Housing Tech team with the listing reference

> The search and valuation tools run on a small, illustrative sample dataset for demonstration purposes. They are not connected to live transaction or seller data. The production version of this platform will run on verified, real-time data.

---

## Tech stack

- Plain HTML, CSS, and vanilla JavaScript — no build step, no dependencies
- Fonts loaded via Google Fonts (Fraunces, Inter, JetBrains Mono)
- Fully responsive, with reduced-motion support for accessibility

## Running locally

This is a static site with no build process. To view it locally, simply open `index.html` in any browser, or serve it with any static file server, for example:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deployment

This site is built to be deployed on any static hosting provider (Netlify, Cloudflare Pages, GitHub Pages) with a custom domain connected via DNS.

---

## Contact

For partnership, investment, grant, or general enquiries:
**contact@vicjenhousingtech.org**

---

© 2026 VICJEN Housing Tech. All rights reserved. See [LICENSE.md](./LICENSE.md) for usage terms.
