[README.md](https://github.com/user-attachments/files/27562510/README.md)
# Bible Study Tracker PWA

A private, installable Bible study tracker for two study partners.

## Features

- Daily calendar check-ins for two people
- Individual streaks, together streak, and total together days
- Session notes saved locally in the browser
- Month-by-month Bible reading plan
- Verse of the day
- Settings for partner names
- Export/import backup file
- Installable PWA with offline support

## Files

- `index.html` - the full app
- `manifest.json` - PWA install metadata
- `sw.js` - offline service worker
- `icons/` - app icons

## GitHub Pages Deployment

1. Create a new GitHub repository.
2. Upload all files in this folder.
3. Go to **Settings > Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/root` folder.
6. Open the published GitHub Pages URL.

## Install Prompt

The app includes install prompt logic. On supported browsers, the **Install App** button appears when the browser fires the `beforeinstallprompt` event.

## Data Storage

Progress is saved in `localStorage` on the current device. Use **Export backup** before clearing browser data or switching devices.


Default study partners: Melvin and Monique.
