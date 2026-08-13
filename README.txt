LEDGER — iPhone-ready PWA

Files:
- ledger.html       Main app
- manifest.webmanifest  Home Screen/PWA metadata
- sw.js             Offline cache/service worker
- icon.svg          App icon

HOW TO USE ON IPHONE
1. Upload all four files to a web host (for example Cloudflare Pages or GitHub Pages).
2. Open the resulting HTTPS URL in Safari.
3. Tap Share -> Add to Home Screen -> Add.
4. Launch Ledger from the new Home Screen icon.

IMPORTANT DATA NOTE
Ledger stores its entries in the browser's localStorage on the device. Hosting the app does not automatically sync data between devices. Use the app's Backup/Restore feature to keep a copy of your data before clearing Safari data, deleting the app, or moving to another device.

The service worker only works when the app is served from HTTPS (or localhost during development), not when opened directly as file://.
