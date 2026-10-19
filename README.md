# Little Days — Baby Tracker (PWA)

No Google account, backend, or subscription is required for parents using the app. Records stay in the device's IndexedDB. A browser's private/incognito mode or clearing site data may delete records. **Export backups regularly.**

## Free publishing with GitHub Pages
1. Create a free GitHub account (the publisher needs an account; app users do not).
2. Create a **public** repository named `little-days`.
3. Upload **all six** app files from this folder to the repository root: `index.html`, `app.js`, `manifest.webmanifest`, `sw.js`, `icon-192.png`, `icon-512.png`.
4. Go to Settings → Pages → Build and deployment. Choose **Deploy from a branch**, branch **main**, folder **/(root)**, and save.
5. Wait for the published HTTPS address (normally `https://YOUR-USERNAME.github.io/little-days/`).
6. iPad/iPhone: open that URL in Safari → Share → Add to Home Screen. Android: open in Chrome → menu → Install app or Add to Home screen.
7. Test adding entries, closing/reopening, airplane mode after first successful load, export, and restore.

## Important
- Opening `index.html` directly from a file does not reliably support service workers or PWA installation. Host via HTTPS.
- The GitHub repository must contain only the app code, **not any private baby records or backup files**.
- No sync between devices, login, cloud backup, notification reminders, feeding stopwatch, or edit/delete controls in this starter version.
- Backups are unencrypted files: keep them in a private place.
- The app is not a medical device or diagnostic tool.
- This is a starter prototype, not a security-reviewed production app. Test before sharing widely.
