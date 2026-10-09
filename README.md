# DELTA FINLABS website

## Files
- `index.html` — responsive landing page
- `assets/delta-finlabs-banner.png` — supplied banner image

## Before publishing
Open `index.html` and find `const SITE_LINKS` near the bottom. Replace:
- `PASTE_GOOGLE_FORM_RESPONDER_URL_HERE` with the public Google Form responder URL
- `PASTE_TELEGRAM_URL_HERE` with the public Telegram channel/group URL
- `PASTE_YOUTUBE_CHANNEL_URL_HERE` with the YouTube channel URL

Do not put the private Google Sheets URL, passwords, API keys, customer records, OTPs, or financial credentials in this public repository.

## GitHub Pages
1. Open the `delta-finlabs` repository.
2. Click **Add file → Upload files**.
3. Upload `index.html` and the `assets` folder (including the banner image).
4. Commit to the `main` branch.
5. Open **Settings → Pages**.
6. Under Build and deployment, choose **Deploy from a branch**.
7. Select branch `main`, folder `/(root)`, then **Save**.
8. Wait for the published URL shown on the Pages screen and test it on mobile and desktop.

GitHub repository contents are public. Only publish website code and public assets.
