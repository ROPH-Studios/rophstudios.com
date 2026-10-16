# rophstudios.com

The ROPH Studios website: a static site (plain HTML and CSS, no build step) served by GitHub Pages
at https://rophstudios.com.

- `index.html`: the studio home page and app list
- `furniture-store-games/`: game page and privacy policy (the Play Store privacy URL)
- `clay-coach/`: privacy policy and account-deletion page (both needed for its Play listing)
- `assets/`: stylesheet, logo, icons and screenshots

System fonts only and no scripts or third-party requests, so the site itself sets no cookies and
needs no cookie banner. Preview locally with `python3 -m http.server` and open http://localhost:8000.
