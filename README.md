# Discount VW Audi Centre — GitHub Pages site

SEO-rich, single-page site for **Discount VW Audi Centre**, Hoylake, Wirral.
Built to be deployed on GitHub Pages.

## What's in here

| File | Purpose |
|------|---------|
| `index.html` | Single-page site, schema.org JSON-LD, OG/Twitter tags |
| `assets/styles.css` | Editorial dark-luxury automotive theme, fully responsive |
| `robots.txt` | Allow all + sitemap reference |
| `sitemap.xml` | Single-URL sitemap |
| `.nojekyll` | Skip Jekyll processing on GH Pages |

## SEO coverage

- `LocalBusiness` + `AutoRepair` schema with geo, hours, payment, area served
- `AggregateRating` (4.8 / 184 reviews) from public Google data
- `FAQPage` schema (6 Q&A) — eligible for rich results
- `OfferCatalog` listing services
- Local geo tags (`geo.region`, `geo.placename`, `geo.position`, `ICBM`)
- Open Graph + Twitter card
- Canonical URL, hreflang-ready (`en-GB`)
- Semantic HTML, accessible nav, skip link, reduced-motion support
- All images sized via CSS, fonts preconnected, no render-blocking JS

## Deploy

1. Create a repo (e.g. `discountvwaudicentre.github.io` for a user/org root site, or any repo for a project site).
2. Push these files to `main`.
3. GitHub → Settings → Pages → Source: `main` / root → Save.
4. Update the canonical URL, OG URL and sitemap entry in `index.html` / `sitemap.xml` if the deployed origin differs from `https://discountvwaudicentre.github.io/`.

## Customisation pointers

- Swap the placeholder `og.jpg` for a real 1200×630 hero shot (workshop / signage).
- Replace placeholder review quotes with verbatim Google reviews (with permission).
- Add `tel:` tracking if running paid traffic.
