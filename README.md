# levanu-site

Corporate landing page for **Leva Nu Pty Ltd**, the Australian parent company behind [Sture](https://sture.io).

Lives at [levanu.com.au](https://levanu.com.au) (Cloudflare Pages).

## Why this exists

Vendor and grant forms (e.g. GCP for Startups, AWS Activate, DASA, AFWERX) verify that the billing-admin email domain matches the company website domain. Sture's product site is at `sture.io`, but the company entity's email is `@levanu.com.au` — so the entity needs a corporate web presence on its own domain.

This site is intentionally minimal: parent-company facts, one-line about, link to the product. The marketing investment lives on [sture.io](https://sture.io).

## Files

- `index.html` — single-page corporate site (inline CSS, no build step)
- `logo.jpg` — Leva Nu wordmark on brand-blue background (copied from `Forge/brand/sture/LevaNuLogoWhiteOnBlue.jpg`)

## Deploy

Cloudflare Pages auto-deploys on push to `main`.

## TODO

- [x] ~~Sample the exact brand blue from `logo.jpg`~~ — sampled as `#0071FE` (rgb(0, 113, 254)).
- [ ] Add a favicon (export from `brand/sture/LevaNuLogo.afdesign` in the Forge repo).
- [ ] Optional: re-export `logo.jpg` as an SVG for crisp rendering at large sizes.
