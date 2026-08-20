COMPTIA DATA+ DA0-002 PRACTICE SYSTEM — HOSTING PACKAGE

This folder is ready for static web hosting. The app is fully client-side.
Learner names, scores, saved sessions, and history are stored in each person's browser local storage and are not sent to a server by the app.

FILES
- index.html — the complete practice app
- manifest.webmanifest — install/home-screen metadata
- icon-192.png and icon-512.png — app icons
- .nojekyll — makes GitHub Pages serve the files directly
- netlify.toml — optional Netlify static-host configuration

NETLIFY (simple method)
1. Sign in to Netlify.
2. Create a new site using its manual/deploy-drop option.
3. Upload this whole folder (or the ZIP contents).
4. Netlify will provide an HTTPS address you can text to anyone.

GITHUB PAGES
1. Create a repository.
2. Upload all files in this folder to the repository root.
3. In the repository Pages settings, publish from the branch/root containing index.html.
4. Share the HTTPS Pages address.

PHONE USE
- Open the hosted HTTPS link in Safari or Chrome.
- On iPhone/iPad, Share > Add to Home Screen can install it like an app.
- On Android, the browser may offer Add to Home screen / Install app.

IMPORTANT
- Score history is device/browser-specific. Sharing the hosted link does not share another learner's scores.
- Clearing browser/site data removes locally stored history unless the user first exports their score history to CSV.
- If you replace index.html with an updated version later while keeping the same domain, existing browser local storage should remain available because it is tied to that website origin.
