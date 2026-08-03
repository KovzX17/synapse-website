# Synapse Healthcare — Website

Official website for **Synapse Healthcare Solutions** — *"Progress Through Synergy"*.

A fully static, dependency-free single-page site. Copy and product imagery come from the
company brochure; the Vision, Mission and Core Values sections come from the company write-up.
It presents:

- **Hero** — "Smart Solutions for Smarter Healthcare Business"
- **Trust bar** — the four brochure proof points
- **About Synapse** — who we are and why "Synapse"
- **Vision & Mission**
- **Core Values** — Commitment, Trust, Relationship Beyond Transaction, Innovation, Spirit of Exploration
- **Our Solutions** — CashlessHub, ClaimXpert, Marketing, LegitMate, Virtual Medical Assessment, CareWell
- **Contact** — the brochure's contact details, plus the promise strip in the footer

## Stack

Plain HTML + CSS + vanilla JavaScript. No build step, no frameworks.

- `index.html` — all page content
- `styles.css` — design system (Fraunces + Manrope, ivory/teal/amber palette)
- `script.js` — sticky header, mobile nav, scroll reveals, animated synapse-network hero canvas
- `images/` — brand logo and the six product visuals
- `fonts/` — self-hosted Fraunces + Manrope woff2

## Images

`images/logo.png` is the supplied stacked brand logo with its background keyed to transparency.
`images/logo-horizontal.png` is a horizontal lockup of that same artwork (mark beside wordmark)
for the slim nav bar. The six product visuals are extracted from the brochure's solution cards.

## Run locally

Open `index.html` directly in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# → http://localhost:8000
```

## Deploy

Any static host works (GitHub Pages, Netlify, Vercel) — point it at the repository root.
