# REBUILD OS

REBUILD OS is a private offline-first command center for a 14-day personal reset. Track prayer and focused work alongside math study movement attention sleep and reflection. Keep your daily record in your browser.

## Start here

1. Download or clone this repository.
2. Open `index.html` in a modern browser.
3. Complete the setup flow and begin Day 1.

There is no install step. There is no build step. The core app does not need a server or an internet connection.

## What it does

- Organizes a 14-day cycle into four phases and a final proof day.
- Tracks prayer check-ins with times you set yourself.
- Tracks coding time tasks and a daily main mission.
- Tracks math topics study time questions and confidence.
- Tracks walks workouts attention and sleep.
- Saves journal notes and a daily review.
- Runs a focus timer that can recover its state after a refresh.
- Offers a rescue checklist for days that need a smaller plan.
- Shows cycle analytics streaks milestones and a 14-day heatmap.
- Supports dark and light themes.
- Exports and imports a JSON backup.

## Data and privacy

The app stores its data in `localStorage` under the key `rebuildOS_v1`. No account or backend is used. No external API is required for the core app.

Data belongs to the browser profile used to open the app. Export a JSON backup to move your records to another browser or device. Importing a backup replaces the current app data after creating a local snapshot.

## Project files

- `index.html` provides the app shell.
- `styles.css` contains the responsive layout and theme styles.
- `app.js` contains the app logic and local data handling.

The project uses HTML CSS and vanilla JavaScript. It has no package manager or build tools.

## Open source license

This repository does not include a license yet. Add a `LICENSE` file before publishing if you want to grant others permission to use or modify the code.
