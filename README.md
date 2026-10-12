# Bashers & Dinkers Queue Manager

## GitHub Pages deployment
1. Upload `index.html` to the root of your `pickleball-queue` repository, replacing the existing file.
2. Commit the change to the `main` branch.
3. Keep GitHub Pages configured for `main` / `(root)`.

## Session setup
- **Courts:** 1–6 courts.
- **Balanced:** balances team-average ratings, discourages repeat partners, and avoids selecting a four-player lineup with exactly one 3.0 player whenever a valid alternative is available.
- **Social Mix:** keeps queue rotation first and randomizes teams; ratings are not used to select teams.
- **Skill Separated:** selects a narrow skill-rating group and pairs similar ratings together. It may leave a court waiting if there are not enough comparable players.
- **Winners / Losers:** after a scored match, tries to put two winners and two losers in the next lineup.

Player ratings are editable in **Player Balance**. Ratings affect future lineups, not matches already in progress. The app stores data in the current browser's local storage; it does not synchronize data between devices.
