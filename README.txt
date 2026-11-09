MY 3D WORLD — ANDROID INSTALLABLE WEB APP

Files:
- index.html: the app
- manifest.webmanifest: install metadata and icon references
- service-worker.js: caches the app shell for repeat visits
- icons/: app icons

IMPORTANT:
1. Upload the CONTENTS of this folder to a static HTTPS host (for example GitHub Pages).
2. Open the published HTTPS address in Chrome on Android.
3. Paste your MapTiler API key in the app and tap Connect.
4. In Chrome, open the three-dot menu and choose "Install app" or "Add to Home screen".

The 3D globe and satellite imagery need internet access. The service worker caches the app shell, not global satellite imagery. GPS generally requires HTTPS and user permission.
Keep your MapTiler key private. For a public site, restrict the key to your published website domain in MapTiler settings. A key embedded in a public website can be seen by visitors, so use provider-side domain restrictions and usage limits.
