# Bashers & Dinkers Queue Manager — Version 7

A polished, responsive static web app for pickleball club queueing, court management, player balance, rankings, and match history.

## Deploy to GitHub Pages

1. Extract this ZIP.
2. Open your existing `pickleball-queue` GitHub repository.
3. Upload `index.html`, `logo.jpg`, and `README.md` from the `bashers-dinkers-skill-rating` folder to the repository root (replace existing files when prompted).
4. Commit to the `main` branch.
5. Keep GitHub Pages configured for `main` / `/(root)`.

## Add your club's official logo

The official Bashers & Dinkers logo is included as `logo.jpg` and displayed in the header. Upload it beside `index.html` so the header image loads correctly.

## Included features

- Responsive sporty dark-green, lime, and white dashboard.
- Registered / Playing / Waiting overview.
- Add players with skill ratings and edit ratings later.
- Multiple court management.
- Balanced, Social Mix, Skill Separated, and Winners / Losers matching modes.
- Match score entry, rankings, win/loss statistics, point differential, and match history.
- Browser localStorage persistence.

## Important limitation

This is a static GitHub Pages app. Data is stored in the browser/device being used; it does not sync in real time between multiple phones. Shared club-wide data would require a backend/database.

## Existing data

The app uses the same localStorage key as the prior version, so upgrading the HTML should preserve data in the same browser unless site data is cleared.
