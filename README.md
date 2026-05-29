# Deploy to GitHub Pages (Free)

## Files needed in your repository:
- `index.html` (the complete app)
- `manifest.json`
- `service-worker.js`
- `icon-192.png` (192x192 app icon — any PNG image)
- `icon-512.png` (512x512 app icon — any PNG image)

## Steps:
1. Create a free account at [github.com](https://github.com)
2. Create a new repository (e.g. `student-mark-record`)
3. Upload all 5 files to the repository
4. Go to **Settings** > **Pages** > **Source**: "Deploy from branch main"
5. Your app will be live at: `https://[username].github.io/student-mark-record/`
6. Open this URL in Chrome or Edge
7. Chrome shows "Install" icon in address bar — click to install

## Install on Android:
1. Open the URL in Chrome on Android
2. Tap the 3-dot menu > **Add to Home screen**
3. The app icon appears on your home screen
4. Opens in standalone mode (no browser UI)

## Install on Windows/Mac:
1. Open URL in Chrome or Edge
2. Click the install icon (⬇) in the address bar or the top bar of the application canvas
3. Click **Install** in the popup
4. App opens in its own window like a native app

## HTTPS requirement:
PWAs require HTTPS. GitHub Pages provides this automatically.
If hosting elsewhere, ensure your server uses HTTPS.
(Exception: localhost works without HTTPS for testing.)
