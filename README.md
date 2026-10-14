# Barn Door Quote Calculator

A simple web page that gives customers an instant price estimate for a custom
sliding barn door. Pick the width, style, finish, hardware, and installation —
the estimate updates live.

## How to use it

Open `index.html` in any web browser. No server, no build step, no dependencies.

To put it online for free: enable **GitHub Pages** in this repo's Settings →
Pages → Deploy from branch → `main`. The calculator will then live at a public
URL you can share on Facebook Marketplace.

## How the pricing works

All prices live in the `PRICE TABLE` section near the bottom of `index.html`:

- `BASE_PRICE` — starting price for a solid wood door up to 36" (CA$400)
- Width, style, finish, hardware, and installation add fixed amounts on top
- `ESTIMATE_SPREAD` — quotes are shown as a range (price → price + spread)

Change any number there and reload the page — nothing else to edit.

## Files

- `index.html` — the whole calculator: layout, styling, and price logic in one file
- `README.md` — this file
