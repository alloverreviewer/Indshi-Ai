INDSHI AI — GitHub Pages + PWABuilder package

CONTENTS
- index.html: the app page
- manifest.json: PWA metadata and icon declarations
- sw.js: service worker
- app-favicon.jpg: image filename already referenced by index.html
- icon-192.png and icon-512.png: install icons for PWA Builder

GITHUB PAGES DEPLOYMENT
1. Extract this ZIP.
2. Upload/commit all six files to the same published directory as index.html. For a project site, that usually means the repository's published root (or the configured /docs folder; keep all files together there).
3. Do not upload only the ZIP; extract it first.
4. Wait for GitHub Pages to finish deploying.
5. Open the deployed HTTPS URL and verify that /manifest.json, /sw.js, /icon-192.png and /icon-512.png each load without a 404.

PWABUILDER
1. Enter the deployed HTTPS website URL in PWABuilder.
2. Review its manifest and service-worker checks before packaging.
3. The icons included here are fallback generated INDSHI-style icons. Replace them with the official approved INDSHI/India Turns Pink logo assets if you have those files, preserving 192x192 and 512x512 PNG sizes.

IMPORTANT
- Keep all files at the same relative directory level. This package uses relative paths to support GitHub Pages project sites.
- Service workers and PWA install prompts require HTTPS (GitHub Pages provides HTTPS when enabled) or localhost.
- A service worker does not force installation; the browser/user must approve installation.
- The app contains external services/iframes; offline mode can cache the app shell but cannot make external services work offline.
