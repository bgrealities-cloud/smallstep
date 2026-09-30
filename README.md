# Smallstep

A free, mobile-first focus, habit and goals tracker. Plain HTML, CSS and JavaScript. No dependencies, subscriptions, trackers, login or external data services.

## What it does

- One daily focus, with completion and undo.
- Habit check-ins, a rolling seven-day view and a consecutive-day streak.
- Editable goals with progress and a next small step.
- Ideas board: Explore, In progress, Next action, optional notes and links.
- Private-to-your-browser local storage, JSON backup and restore.
- Home Screen manifest and offline support after an initial successful online visit.

Starts empty. No example numbers are passed off as real progress. Dates use your device's local calendar.

## Privacy and limits

The source code and site are public. Personal entries stay in browser localStorage and are not uploaded to GitHub. Browser storage is not encrypted; do not use this for passwords or sensitive information. Other people using this browser can see its entries. Private browsing, clearing website data, switching browser/device or Home Screen context can lose or separate data. Export a backup regularly. Backup files contain your entries and should stay private.

This is a manual dashboard, not a live connection to accounts or an automatic property analysis service. Habit streaks reflect self-reported check-ins, not study duration. Goals and board items are limited to 100 each.

## Free hosting

Enable GitHub Pages from the repository's `main` branch, root directory. The files need no build process. Open the published site on your phone. In Safari use Share > Add to Home Screen.

## Development

Serve this directory with a static server, for example `python3 -m http.server 8080`. No package install or API keys are needed. When changing the offline asset set, increment the cache version in `sw.js`.
