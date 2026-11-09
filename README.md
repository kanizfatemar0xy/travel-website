# Travel With Me — Responsive Multipage Travel Gallery

[![Static site checks](https://github.com/kanizfatemar0xy/travel-website/actions/workflows/site-checks.yml/badge.svg)](https://github.com/kanizfatemar0xy/travel-website/actions/workflows/site-checks.yml)

**HTML5 · CSS3 · Responsive Layout · Semantic Markup · GitHub Pages**

A student frontend project by **Kaniz Fatema Roxy**, presenting beaches, mountains, islands and other scenery around Chattogram, Bangladesh. The site demonstrates multipage navigation, responsive design and safe static content.

**[Visit live website](https://kanizfatemar0xy.github.io/travel-website/)** · **[Explore code](index.html)** · **[View tests](tests/test_site.py)** · **[Full developer portfolio](https://kanizfatemar0xy.github.io/travel-website-project/portfolio.html)**

## What you can explore

- Homepage, destination galleries and an informational booking page
- Responsive navigation and layouts for smaller screens
- Local travel photographs, accessible image alternatives and keyboard-friendly links
- Sign-up and booking **demonstration pages only**; no collection of passwords or real payment information
- A placeholder for a future video walkthrough, clearly marked as not yet published

## Getting started

No dependencies or backend are needed. Open `index.html` directly, or run a local web server in the repository directory:

```bash
python -m http.server 8000
```

Open http://localhost:8000 in a browser. To run automated checks, use a **separate terminal**:

```bash
python -m unittest discover -s tests -v
```

These tests check local navigation targets, image assets, basic accessibility markup and the absence of unsafe forms. The [GitHub Actions workflow](.github/workflows/site-checks.yml) runs the same tests on updates.

## Key files

| File | Purpose |
| --- | --- |
| [`index.html`](index.html) | Home page |
| [`tour.html`](tour.html), [`tour2.html`](tour2.html) | Destination galleries |
| [`bookings.html`](bookings.html), [`pform.html`](pform.html) | Informational demo pages |
| [`vid.html`](vid.html) | Video-demo placeholder |
| [`style.css`](style.css) | Responsive frontend styling |
| [`tests/test_site.py`](tests/test_site.py) | Static-site checks |

## Scope and limitations

This is a **frontend demonstration, not a travel agency**. It does not support accounts, travel bookings, payment processing or a real backend. The previous PHP form targets have been removed. Images come from the original student project; their reuse rights should be checked before commercial use. Automated checks do not replace manual mobile-browser or accessibility testing.

**Developer:** [Kaniz Fatema Roxy](https://github.com/kanizfatemar0xy) · [Portfolio](https://kanizfatemar0xy.github.io/travel-website-project/portfolio.html) · [LinkedIn](https://www.linkedin.com/in/kaniz-fatema-roxy)
