# rophstudios.com

The ROPH Studios website: a static site (plain HTML and CSS, no build step) served by GitHub Pages
at https://rophstudios.com.

- `index.html`: the studio home page and app list
- `furniture-store-games/`: game page and privacy policy (the Play Store privacy URL)
- `seven-feathers/`: game page and privacy policy (linked from the game's grown-ups area)
- `clay-coach/`: Clay Coach's privacy policy and terms of use (linked from the app's sign-in screens
  and About)
- `_drafts/` (when present): pages not published yet; Jekyll skips folders starting with `_`
- `assets/`: stylesheet, logo, icons and screenshots
- `sitemap.xml` and `robots.txt`: for search engines (Google Search Console). Add each new page to
  `sitemap.xml`, and update its `lastmod` when a page changes a lot

System fonts only and no scripts or third-party requests, so the site itself sets no cookies and
needs no cookie banner. Preview locally with `python3 -m http.server` and open http://localhost:8000.
