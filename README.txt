MY TITHE JOURNEY — INSTALLABLE WEB APP PACKAGE

This package adds a web app manifest, app icons, and a service worker for app-shell caching/offline opening.

PUBLISHING:
1. Open the GitHub repository for My Tithe Journey.
2. Upload/replace index.html in the repository root.
3. Upload manifest.webmanifest and service-worker.js to the same root.
4. Create an icons folder and upload icon-192.png and icon-512.png inside it.
5. Wait for GitHub Pages to publish.
6. Open the site in Chrome on Android. Use Chrome menu (three dots) > Install app or Add to Home screen.

IMPORTANT LIMITATIONS:
- This creates an installable PWA, not a signed Android APK yet.
- The existing app saves records in this browser/device. It does not add cloud backup or cross-device sync.
- The current reminder feature is an in-app reminder shown when the app is opened on selected days. It does not send reliable notifications while closed.
- Test the updated site before relying on it for important records. Export records regularly as a backup.
