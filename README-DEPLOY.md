# BrowserSignal — Evergreen + Verified Release Desk (#18)

**Prepared:** 9 November 2026. **Default assumed domain:** https://browsersignal.vercel.app.

## Deploy to GitHub + Vercel
1. Extract this ZIP and upload **the contents** to your repository root (not the enclosing folder).
2. Connect the repository to Vercel as a static site. No build command is required.
3. If Vercel gives you a different domain, replace every `https://browsersignal.vercel.app` in all `.html`, `sitemap.xml` and `robots.txt` with your **actual production domain** before requesting Google indexing or AdSense review.
4. Test the homepage, /guides/, /journal/, two tools, source pages, contact, privacy, ads.txt and sitemap.xml on a real browser.
5. Add your actual production domain to Google Search Console; submit `https://yourdomain/sitemap.xml`, check indexing and fix coverage errors.
6. Use the same domain in your AdSense Sites settings. For other regions, consider consent and CMP setup before enabling personalized ads.
7. Review editorial articles, third-party links and the site owner identity, edit any outdated material and publish only after you are satisfied the instructions are accurate.

## Included
- 18 independently topic-focused evergreen guides + 2 dated browser release explainers.
- Issue Pathfinder: interactive symptom routing that runs locally.
- Fix Log: saves draft to localStorage, exports a local TXT, and can clear it.
- About, Contact, Editorial, Sources, Privacy, Terms, Advertising Disclosure.
- SEO: meta descriptions, canonical URLs, Article JSON-LD, sitemap, robots.
- Flat SVG illustration; no third-party image assets, external fonts or API keys.

## AdSense configuration
Publisher: `ca-pub-9692973918767107`. Script included once on homepage and each substantive article/release page. The script is **not** included on tools, legal, article indexes, or pure navigation pages, to avoid ad serving on pages with little editorial content. `ads.txt` uses the same publisher ID. No manual display ad slots are installed. Ad appearance requires Google approval and/or your AdSense settings.

Contact: rafliraflu@gmail.com.

## Content trust / editorial caveat
- The copy is AI-assisted and should be editorially reviewed by the publisher prior to launch. No fabricated named experts or unverified first-hand testing claims are included.
- Release desk is an editorial snapshot as of 9 November 2026, **not a live feed**. Update with newly verified source links and accurate dates; do not automatically publish mass-generated trends.
- Original illustrative cases are examples, not reports of actual incidents.
- AdSense approval is never guaranteed by a page count, word count, domain or script.

## Quick checks
- Every link works, no browser console errors.
- Each HTML page resolves with HTTP 200.
- Canonical points to final domain.
- `ads.txt` shows `pub-9692973918767107`.
- Mobile nav, guide search, Pathfinder and Fix Log work.
- Google Search Console finds sitemap and indexes key pages.
