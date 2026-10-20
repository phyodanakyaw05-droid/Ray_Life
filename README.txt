RAY'S UNI & LIFE PLANNER — iPhone Home Screen web app package

HOW TO PUBLISH:
1. Sign in to GitHub in a browser.
2. Create a NEW repository. If GitHub asks, choose Public for the simplest free GitHub Pages setup. Do not upload private/personal documents.
3. Upload all files in this folder to the repository's top level:
   index.html
   manifest.webmanifest
   service-worker.js
   apple-touch-icon.png
4. In the repository, open Settings > Pages.
5. Under Build and deployment, choose Deploy from a branch, select main and /(root), then Save.
6. Wait for GitHub Pages to publish and open the provided https://...github.io/... URL.
7. On iPhone, open that URL in Safari (not an in-app browser).
8. Tap Share > Add to Home Screen. Leave "Open as Web App" enabled if shown, then tap Add.

IMPORTANT:
- This is an installable web app (PWA/Home Screen web app), not a native App Store app.
- The planner currently stores tasks, notes and settings in the browser's local storage. Data may not sync between devices and can be lost if website data is cleared.
- The service worker caches the main planner files for basic offline access after the first successful load. Offline support can vary by iOS version.
- A public GitHub Pages site is visible to anyone with the link; the planner's locally stored entries are not uploaded by this code.
