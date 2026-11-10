# FinPiece website

The website of **FinPiece: Bills & Expenses**, a private money app for Android that works fully offline.
Live at **https://finpiece.github.io/**

**FinPiece is live on Google Play** (since 10 November 2026):
https://play.google.com/store/apps/details?id=com.finpiece.win

## What is on the page

One page (`index.html`) plus `images/` (app screenshots as WebP, the app icon and the share image):

- what FinPiece does: credit card bills, insurance, expenses, Given-got, To-Do, Doc Vault and money plans
- privacy: 100% offline, encrypted on the phone, no sign-up, no ads, no tracking
- money tips (for financial awareness only, not financial advice), pricing, languages and FAQ
- videos on YouTube

## Links

| What | Link |
|---|---|
| Google Play | https://play.google.com/store/apps/details?id=com.finpiece.win |
| Promo videos (YouTube playlist) | https://www.youtube.com/playlist?list=PLLW2fvzM_CEw |
| Tutorials (YouTube playlist) | https://www.youtube.com/playlist?list=PLR-U2-kN94wM |
| Privacy policy | https://finpiece.github.io/finpiece_privacy_policy/ |
| Delete your data | https://finpiece.github.io/finpiece_privacy_policy/#keeping-and-deleting-your-data |
| Contact | finpiece.win@gmail.com |

The privacy policy lives in its own repository (`finpiece_privacy_policy`), so its address never changes.

## How the site is published

GitHub Pages: Settings › Pages › "Deploy from a branch", branch `main`, folder `/ (root)`. Every commit to `main` is live in
about a minute.

To update it: upload the new `index.html` at https://github.com/finpiece/finpiece.github.io/upload/main and new or changed
images at https://github.com/finpiece/finpiece.github.io/upload/main/images (select the files, not the folder), then
**Commit changes**.

## Preview locally

`python -m http.server 8765 --bind 127.0.0.1` inside this folder, then open http://127.0.0.1:8765/

## History

- **3 Nov 2026**: first "coming soon" page.
- **10 Nov 2026**: FinPiece live on Google Play. Play Store links everywhere, plus a Videos section with the promo and
  tutorial playlists.

---

© 2026 FinPiece. Google Play and YouTube are trademarks of Google LLC.
