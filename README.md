# VICJEN Housing Tech

AI-powered real estate platform connecting verified buyers and sellers, valuing land and property in real time, and developing affordable housing across Anambra State and Abuja, Nigeria.

**Live site:** [vicjenhousingtech.org](https://vicjenhousingtech.org)

---

## About

VICJEN Housing Tech is a Nigerian proptech company founded by Victor and Jennifer, headquartered in Anambra State with operations in Abuja. The company operates across the full property value chain:

- **Verified marketplace** — real-time listings connecting buyers directly with reliable, verified sellers
- **AI property valuation** — real-time, data-driven valuations for land and property
- **Building cost estimation** — AI-assisted construction and development cost estimates
- **Land and property trading** — direct acquisition and resale
- **Estate development** — building and developing housing stock
- **Affordable letting** — properties let at 10% below average market rate

### Mission and Vision

**Mission:** To give every Nigerian buyer and seller a property transaction they can trust, using AI-driven, real-time valuation built on verified, current housing data, while housing the families that the market leaves behind through below-market rent and direct rent relief.

**Vision:** A Nigeria where no family is left to rebuild alone, where every property transaction is verified and every valuation reflects real, current data, and where affordable, trustworthy housing is available to all.

### Social impact

VICJEN Housing Tech was founded by Victor and Jennifer, whose families were both displaced by insecurity in Northern Nigeria and forced to rebuild from nothing. Both of their fathers died while trying to rebuild a home for their families; both houses remain unfinished today. This history shapes the company's commitment to affordable, below-market housing, and a standing pledge, beginning in 2027, to sponsor one family's full year of rent, every year, funded from company profit.

Read the full founder story on the [About section](https://vicjenhousingtech.org/#story) of the live site.

---

## This repository

This repository contains the source code for the VICJEN Housing Tech marketing website, including a working interactive demo of the property search and AI valuation tools, and the company's logo assets.

### What's included

- `index.html` — the complete site: a single self-contained HTML file with embedded CSS and JavaScript
- `logo/` — the VICJEN Housing Tech logo in SVG and PNG, for both light and dark backgrounds
- `LICENSE.md` — usage rights for this repository

### Live demo features

The site includes a functional, in-browser demo (not a static mockup) under the **Try It Live** section:

- **Property search** — filter a sample set of listings by location, property type, and maximum price
- **AI valuation tool** — enter a property's location, type, size, condition, and road access to generate a live estimated value with a price range and breakdown
- **Contact** — each listing includes a "Contact about this property" button that opens a pre-filled email to the VICJEN Housing Tech team with the listing reference

> The search and valuation tools run on a small, illustrative sample dataset for demonstration purposes. They are not yet connected to live transaction or seller data. The production version of this platform will run on verified, real-time data.

---

## Tech stack

**Current (demo/prototype):**
- Plain HTML, CSS, and vanilla JavaScript, no build step, no dependencies
- Fonts loaded via Google Fonts (Fraunces, Inter, JetBrains Mono)
- Fully responsive, with reduced-motion support for accessibility

**Planned (production):**
- Amazon RDS / DynamoDB for property and transaction data
- Amazon S3 for property images and title documents
- AWS Lambda and API Gateway for backend search and valuation logic
- Amazon SageMaker, to train a valuation model on verified Nigerian transaction data, replacing the current rule-based estimation logic
- Amazon Cognito for buyer, seller, and admin authentication

## Running locally

This is a static site with no build process. To view it locally, simply open `index.html` in any browser, or serve it with any static file server, for example:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deployment

This site is deployed on Netlify with a custom domain connected via DNS.

---

## Contact

For partnership, investment, grant, or general enquiries:
**contact@vicjenhousingtech.org**

---

© 2026 VICJEN Housing Tech. All rights reserved. See [LICENSE.md](./LICENSE.md) for usage terms.
