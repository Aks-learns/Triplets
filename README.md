# Triplet Trainer

A quick-fire game for memorising Pythagorean triplets, such as 3-4-5, 5-12-13 and 8-15-17, and spotting their multiples. Fast recall saves real time on CAT geometry questions. It's a single HTML file that you can install on your phone and use offline.

**▶ Play it here: https://aks-learns.github.io/Triplets/**

## Modes

- **Real or fake**: is this set of sides a true triplet?
- **Missing side**: fill in the third side
- **Find the base**: recognise which primitive triplet a scaled set comes from
- **60-second blitz**: as many as you can in one minute

Each round uses lives and a combo multiplier (×2 at 5 correct in a row, up to ×4 at 20), and the app keeps your best score. Triplets come in three difficulty tiers, from 3-4-5 up to 119-120-169.

## Run it

Open the live link above, or download `index.html` and open it in any browser. On a phone, use "Add to Home Screen" to install it as an app. It then works offline, because a service worker (`sw.js`) caches it.

## Files

| File | Purpose |
|---|---|
| `index.html` | The whole app: markup, styles and logic |
| `manifest.webmanifest`, `icon-*.png`, `apple-touch-icon.png` | Lets you install it as an app |
| `sw.js` | Service worker for offline use |
