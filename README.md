# FinPiece website (coming-soon page)

One page, `index.html`, plus `images/` (WebP copies of `appScreenshots/`, the icon and the feature graphic as the share image).
Features shown are those of v2.3.1. Google Play only, no iPhone.

## Publish on GitHub Pages (https://finpiece.github.io/)

1. On GitHub, signed in to the account that owns `finpiece_privacy_policy`, create a **public** repository named exactly
   `finpiece.github.io`.
2. Upload `index.html` and the whole `images/` folder (keep the folder name) to the repository root and commit.
3. Settings › Pages: Source = "Deploy from a branch", branch `main`, folder `/ (root)`. The site is live in about a minute.
4. The privacy policy keeps its own address: https://finpiece.github.io/finpiece_privacy_policy/

## When FinPiece is live on Google Play

Replace the two "Coming soon on Google Play" buttons (hero and the last section) with a link to
`https://play.google.com/store/apps/details?id=com.finpiece.win`, and change "coming soon" wording in the badge, the nav pill,
the FAQ "When can I download FinPiece?" and the final section.

## Preview locally

`python -m http.server 8765 --bind 127.0.0.1` inside this folder, then open http://127.0.0.1:8765/
