DailyFlow PWA Package
=====================
Files included:
- index.html      (Main app with PWA manifest & service worker links)
- manifest.json   (App metadata & icons for Android/PWABuilder)
- sw.js           (Offline caching service worker)
- icons/          (192x192 and 512x512 PNG app icons)

Quick Steps to Publish:
1. Upload the contents of this folder to any free HTTPS host (e.g., GitHub Pages, Cloudflare Pages, or Netlify).
2. Open https://www.pwabuilder.com/ and paste your live HTTPS URL.
3. Choose Android -> Package for Store to download your .aab, .apk, and assetlinks.json.
4. Upload assetlinks.json to https://your-domain/.well-known/assetlinks.json on your host.
5. Upload the .aab file to Google Play Console (Closed Testing -> 12 testers for 14 days -> Production).
