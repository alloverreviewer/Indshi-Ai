INDSHI AI — GitHub Pages + PWABuilder deployment package (v31)

FILES
- index.html
- manifest.json
- sw.js
- icon-192.png
- icon-512.png
- icon-maskable-512.png
- favicon.png
- favicon.ico
- app-favicon.jpg

DEPLOY
1. Extract this ZIP.
2. Upload/replace all files in the SAME directory that GitHub Pages publishes.
3. Commit and wait for GitHub Pages deployment.
4. Open your deployed HTTPS site. Verify these exact paths load (adapt if your site has a repository subpath):
   ./manifest.json
   ./sw.js
   ./icon-192.png
   ./icon-512.png
   ./icon-maskable-512.png
   ./favicon.ico
5. Enter the full deployed HTTPS URL into https://www.pwabuilder.com/ and run the checks.

IMPORTANT
- Do not upload the ZIP itself as the website.
- For a GitHub project site, use the full URL such as https://USERNAME.github.io/REPOSITORY/ in PWABuilder.
- All files must be at the same published root as index.html.
- GitHub Pages must be HTTPS.
- A PWA install prompt is controlled by browser eligibility and user action; the page cannot force installation.
- If PWABuilder still reports an error, send a screenshot of its exact diagnostics. This package cannot fix repository settings or a deployment URL that points to the wrong folder.
