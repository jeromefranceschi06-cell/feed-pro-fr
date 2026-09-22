# REDESIGN_NOTES — Feed Pro landing (2026-09-22 PT)

Direction: **dark sophisticated editorial ecommerce** — one accent (champagne gold `#d4a574`), cream type, Instrument Serif + DM Sans.

## Concrete changes

1. **Committed to one visual system** — near-black `#050507`, cream text, single gold accent; removed teal/blue button split and busy multi-glow.
2. **Gen assets as primary product story** — hero uses `assets/gen/hero-phones.png`; transform band uses `before-after.png`; truth + buy use `product-zip.png` (Pillow mocks demoted to strip/gallery/colors).
3. **Story hierarchy that converts** — Dream → Before/After → What it is (ZIP) → See it → Value stack → Colors → How → FAQ → Price/CTA sticky.
4. **Product truth in &lt;5s** — ZIP one-liner in hero, truth band, FAQ, and buy card; “Pas une formation” kept explicit.
5. **Typography upgrade** — Instrument Serif for H1/H2 dream lines; DM Sans for UI; italic gold accents for emotional beats.
6. **Product ZIP made tangible** — dedicated two-column truth section with gen ZIP render + scannable value pills.
7. **Before/After sells the dream** — full-bleed gen comparison before the pack dump; no income claims.
8. **Tighter copy** — short dream line (fierté / clarté / soulagement); stack cards numbered 01–04; 3-step how; FAQ still 3 items.
9. **Gallery curated, not a wall** — masonry with featured grids + phone triple; phone strip of 4 mocks under gallery.
10. **Sticky mobile CTA + refined nav** — gold pill CTA; SEO guide links preserved; article pages inherit new shared chrome via `styles.css`.
11. **OG image refreshed** — `og:image` / Twitter / schema point to `assets/gen/og-banner.png`.
12. **Buy card premium** — bordered gold card with gen product visual + price stack; Payhip CTA unchanged (`https://payhip.com/b/SoUNM`).

## Overnight polish (2026-09-22 ~22:40 PT)

13. **QA live** — all gallery/gen/mocks HTTP 200; Payhip `SoUNM` ×6 (nav/hero/truth/buy/sticky + schema); OG/Twitter → `assets/gen/og-banner.png`.
14. **Muted contrast** — `#9a948a` → `#aea89e` (~8.6:1 on bg).
15. **FR micro-copy** — “Fini le design à zéro”; “Tout dedans”; sticky “ZIP · 29 €”; less anglicisms.
16. **New assets** — `color-pack-showcase.png`, `quote-card.png` (intention, no fake customer); before-after FR caption band (webp/jpg).
17. **Before/after EN overlay** — original gen EN slogans covered by FR band.

## Luxury + 4-colors integrate (2026-09-22 ~22:45 PT)

18. **`assets/gen/4colors-grid.png`** — prominent hero of `#couleurs` (before phone cards).
19. **`assets/gen/bg-luxury.png`** — subtle hero backdrop via `.hero-luxury` (dark overlay + cover).
20. **`/creatives`** — ads gallery (`assets/ads/*` + gen grid/OG); sitemap + footer/guides links.
21. **EN watermark scan** — live gen/ads reviewed; before-after already FR-banded (webp/jpg); no remaining EN slogans on homepage-linked images.
