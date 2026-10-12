# Bashers & Dinkers — Pickleball Queue Manager (Skill Ratings)

## Features
- Responsive static website for GitHub Pages
- Add players with a skill rating from 1.0 to 5.0 (0.5 increments)
- Multiple courts and doubles matches
- Queue priority: fewest games played, then highest waiting score
- Skill-balanced teams: minimize the difference between the two teams' average ratings
- Partner rotation: among equally skill-balanced team splits, prefer fewer repeat partnerships; randomize exact ties
- Score entry, win/loss records, player rankings, point differential, and match history
- Browser-local persistence with localStorage

## Deploy/update on GitHub Pages
1. Extract this ZIP.
2. Open your existing `pickleball-queue` repository.
3. Upload the new `index.html` (replace the old file) and commit changes.
4. Keep GitHub Pages configured for branch `main`, folder `/(root)`.
5. Refresh the published URL.

## Important
This version stores session data in the current browser/device only. It does not synchronize multiple devices. A shared club queue needs a backend such as Supabase with appropriate access controls.
