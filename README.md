# The AM Group — Premium Homepage Redesign

Premium, conversion-focused homepage for **The AM Group** (Construction, Development & Real Estate Investment), built as a static GitHub Pages-ready website.

**Live site (original):** https://theamgrp.com/
**This redesign:** static demo hosted via GitHub Pages from this repository.

## About the business
- **Name:** The AM Group
- **Founded:** 2015, New York City
- **Office:** 589 8th Avenue, 3rd Floor, New York, NY 10018
- **Contact:** info@theamgrp.com
- **Focus:** Multifamily, industrial and tech-flex development in Pittsburgh & Zelienople, PA
- **Partners:** Scott Wolkowitz, Tom Sabol PE, Matthew Cypher PhD (Chief Investment Advisor)

## Portfolio featured
1. 51 Bridge — Pittsburgh, PA (Tech Flex, acquired Sep 2020, Westinghouse 100%)
2. The Stanza — Pittsburgh, PA (Multifamily, acquired May 2023, Now Leasing)
3. 1520 Smallman — Pittsburgh, PA (Development Site, acquired Oct 2018)
4. Zelienople Industrial Park — Zelienople, PA (Industrial, 488,000 RSF, acquired May 2022)
5. Matthew's Lofts — Pittsburgh, PA (For-Sale Residential, acquired Jan 2018, exit Dec 2021)

## Design system
- **Fonts:** Montserrat (headings) + Inter (body)
- **Colors:** Deep navy ink `#0C1A2B`, brass accent `#C6A15B`, stone `#F5F2EC`
- **Style:** Editorial/architectural — sharp corners, hairline rules, numbered sections, full-bleed photography
- **Responsive:** Mobile-first, tested at 360 / 390 / 430 / 768 / 1024 / 1280 / 1440px

## Project structure
```
.
├── index.html
├── css/style.css
├── js/script.js
├── assets/
│   ├── images/   (hero, portfolio, construction photography)
│   └── logo/     (logo.svg wordmark)
├── .nojekyll
└── README.md
```

## Run locally
```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Deploy to GitHub Pages
1. Push to GitHub.
2. Repository → Settings → Pages → Source: Deploy from branch → `main` (or this branch) / root.
3. Visit `https://<username>.github.io/<repo>/`.

## Notes
- All content is sourced from the official website (theamgrp.com) — no invented business facts.
- Portfolio photography is AI-generated conceptual imagery (not presented as actual project photos).
- Demo page includes `noindex` so it does not compete with the original site in search results.
