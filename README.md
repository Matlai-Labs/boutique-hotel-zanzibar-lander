# Boutique Hotel Zanzibar — Meta ads landing page

Static landing page for Boutique Hotel Matlai's Meta ad campaigns.
Live URL: https://boutique-hotel-zanzibar.com

**Noindexed.** This domain serves paid traffic only — the main site at hotelmatlai.com is the SEO-indexed canonical.

## Files
- `index.html` — smart browser-language redirect entry point
- `index.{en,de,es,fr,it,pl}.html` — language-specific landing pages
- `media/` — drone video + poster image
- `.nojekyll` — disables Jekyll processing on GitHub Pages
- `CNAME` — custom domain config for GitHub Pages
- `robots.txt` — crawling allowed (so noindex meta is read)

## Tracking
- GTM container: GTM-5X45TN7 (routes GA4 + Meta Pixel + Microsoft Clarity)
- All tracking gated by Klaro GDPR consent banner

## Source
Built from `matlai_wix/.tmp/homepage-redesign/`. Translations in `translations.json` regenerate via `build-langs.js`.
