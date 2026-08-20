# New Port Richey Lorcana Store Tier Tracker

Unofficial community tracker centered on **New Port Richey, Florida**. It collects Ravensburger Play Hub stores within 40 miles during the weekly sync and displays a **15-mile default radius** on the website. Users can expand the radius up to 40 miles and optionally include stores with zero events.

The tier estimates use a rolling 365-day proxy and the published Standard/Legendary maintenance thresholds. Stores with less than one year of recorded Play Hub activity use estimated prorated thresholds and are marked with an asterisk.

## GitHub Pages setup

Recommended repository name: `Lorcana-New-Port-Richey-Store-Tracker`

1. Create a new public GitHub repository with that name.
2. Upload the **contents** of this project folder.
3. Go to **Settings → Pages → Source: GitHub Actions**.
4. Open **Actions → Update Play Hub data and deploy site** and run it once manually.
5. After the green check, the expected Pages URL is:

   `https://gregs-maker.github.io/Lorcana-New-Port-Richey-Store-Tracker/`

The included workflow refreshes Play Hub data every Monday.

## Local use

```bash
npm install
npm run sync
npm start
```

Then open `http://localhost:4173`.

## Discord report

The website includes **Copy Discord Report**. It always generates the default 15-mile, active-stores-only report centered on New Port Richey and includes a link to the New Port Richey tracker.
