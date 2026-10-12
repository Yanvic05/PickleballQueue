# Bashers & Dinkers — Pickleball Queue Manager

A responsive, static website that can be hosted for free on GitHub Pages.

## Features
- Add/remove players
- Multiple courts and simultaneous doubles matches
- Queue priority: fewest games played, then highest waiting score
- Automatic doubles team split that discourages repeat partnerships
- Start/finish match controls
- Player balance and completed match history
- Saves the session in the current browser using localStorage

## Deploy on GitHub Pages
1. Sign in to GitHub and create a new repository, for example `pickleball-queue`.
2. Upload `index.html` to the repository root (and optionally this README).
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then click **Save**.
6. Wait for GitHub Pages to publish. Your URL will look like `https://YOUR-USERNAME.github.io/pickleball-queue/`.

## Important limitation
This is a static, browser-local version. `localStorage` keeps data on the same browser/device, but does not sync queue changes between different phones or computers. It is not a real-time shared database. For a club-wide shared queue, connect the app to a backend such as Supabase and add authentication/security rules.

## Notes
- The app starts with 12 sample players so you can test it. Use **Reset session** to clear the sample session and start with a blank roster.
- Fairness is based on completed games first and waiting score second. This is a transparent practical heuristic, not a guarantee of perfect fairness in every possible session.
