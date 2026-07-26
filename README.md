# Synapse Healthcare — Website

Official website for **Synapse Healthcare Solutions** — *"Progress Through Synergy"*.

A fully static, dependency-free single-page site built from the company write-up. It presents:

- **About Synapse** — who we are and why "Synapse"
- **Vision & Mission**
- **Core Values** — Commitment, Trust, Relationship Beyond Transaction, Innovation, Spirit of Exploration
- **Products & Services** — CashlessHub, ClaimXpert, Marketing (Digital), LegitMate, Virtual Medical Assessment, CareWell

## Stack

Plain HTML + CSS + vanilla JavaScript. No build step, no frameworks.

- `index.html` — all page content
- `styles.css` — design system (Fraunces + Manrope, ivory/teal/amber palette)
- `script.js` — sticky header, mobile nav, scroll reveals, animated synapse-network hero canvas

## Run locally

Open `index.html` directly in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# → http://localhost:8000
```

## Deploy

Any static host works (GitHub Pages, Netlify, Vercel) — point it at the repository root.
