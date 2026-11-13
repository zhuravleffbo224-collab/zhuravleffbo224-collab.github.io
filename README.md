# 3KLIK — GitHub Pages deployment

This folder contains the complete static website:
- `index.html` — pages and layout
- `style.css` — styling
- `app.js` — navigation, Explore, Create, Stats, Profile and local storage

## Publish
1. Create a public GitHub repository.
2. Upload the **contents** of this folder to the repository root (not the ZIP itself).
3. In repository Settings → Pages → Build and deployment, select **Deploy from a branch**, branch **main**, folder **/(root)** and Save.
4. Wait for GitHub Pages to publish the URL shown in Settings → Pages.

## Important limitations
Coins created by visitors are saved only in their own browser's localStorage; they are not shared across users. The site has no server, blockchain minting, trading, live price feeds, or wallet connection. The unavailable financial controls remain disabled.

To update the site, replace the changed files in the same repository and commit.

## Token address on Home
The homepage shows the supplied Solana token address with a one-click Copy address button. It uses the Clipboard API on HTTPS (GitHub Pages) and a fallback for local files.
