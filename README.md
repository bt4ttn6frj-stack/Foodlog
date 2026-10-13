# FoodLog v2 — free-first prototype

## Included
- Mobile-friendly calorie and macro diary
- Plain-language food matching against a built-in reference list
- Indian and vegetarian foods included in the starter list
- Review estimate before logging
- Daily calorie and protein goals
- Saved meals, custom foods, recent-day summary, CSV export
- PWA manifest, icon, and offline service worker

## Important
This version does not call ChatGPT, an AI API, or an online nutrition database. Estimates come from the built-in reference list and simple portion rules. They are approximate and should be checked, especially for homemade meals, oils, recipes, and branded products. Unrecognised items are flagged rather than silently guessed.

## Run locally
Open `index.html` in a browser. PWA installation/offline caching works best after hosting over HTTPS.

## Publish free with GitHub Pages
1. Create a GitHub account (if needed) and a new public repository named `foodlog`.
2. Upload `index.html`, `manifest.json`, `service-worker.js`, and `icon.svg` to the repository root.
3. In repository Settings → Pages, choose deploy from branch, select `main` and `/ (root)`, and save.
4. Wait for GitHub Pages to publish the site. Open the HTTPS site on iPhone Safari.
5. Tap Share → Add to Home Screen. If offered, enable Open as Web App.
6. Test adding foods, then export CSV regularly as a backup.

Free hosting terms and features can change. If you later add an AI API, never put its secret API key in browser-side JavaScript; use a secure backend.
