# Travel With Me | Responsive Multipage Travel Gallery

[![Static site checks](https://github.com/kanizfatemar0xy/travel-website/actions/workflows/site-checks.yml/badge.svg)](https://github.com/kanizfatemar0xy/travel-website/actions/workflows/site-checks.yml)

**HTML5 · CSS3 · Mobile responsive · GitHub Pages · Accessibility basics**

A frontend travel gallery by **Kaniz Fatema Roxy**, featuring destinations around Chattogram, Bangladesh. The project is a static demo, not a booking or payment service.

**[▶ Visit live website](https://kanizfatemar0xy.github.io/travel-website/)** · **[👩‍💻 View full developer portfolio](https://kanizfatemar0xy.github.io/travel-website-project/portfolio.html)** · **[Browse source](index.html)** · **[Site tests](tests/test_site.py)**

## What visitors can try

- Navigate between the home page, destination galleries and informational pages.
- Resize the window or use a phone to inspect the responsive layout.
- Use keyboard navigation and inspect descriptive image alternatives and landmarks.
- View the original HTML/CSS files and the automated local-link and accessibility-structure checks.

**Run locally:** open `index.html` in a browser, or run `python -m http.server 8000` and visit http://localhost:8000.

**Check:** `python -m unittest discover -s tests -v`.

**Limitations:** no live bookings, accounts, payment processing or published video demo. The code deliberately does not request real passwords or payment details. Ensure rights to the example images before any commercial use.


**Live (if GitHub Pages is enabled):** https://kanizfatemar0xy.github.io/travel-website/

## Features
- Homepage and two destination galleries with local images
- Responsive navigation and mobile layouts
- Semantic HTML, alt text, visible keyboard focus and skip navigation
- Informational booking and account pages that **do not collect personal data**
- An honest placeholder for the not-yet-published video walkthrough
- GitHub Actions checks for broken local links, missing images and unsafe demo forms

## Run locally
Clone the repo and open `index.html`, or use `python -m http.server 8000` and visit http://localhost:8000.

## Test
`python -m unittest discover -s tests -v`

This is a **frontend demonstration only**. It does not process bookings, payments or sign-ups. The former PHP-targeted forms were removed because no PHP backend exists on GitHub Pages. Original sample images are retained; confirm rights before commercial use.

[Kaniz Fatema Roxy on GitHub](https://github.com/kanizfatemar0xy)
