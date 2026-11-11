MELAN — DIRECT TURSO / GITHUB PACKAGE

1. Open config.js in a text editor.
2. Replace YOUR-DATABASE with your Turso database hostname.
3. Replace PASTE_NEW_TURSO_AUTH_TOKEN_HERE with a NEW Turso auth token.
4. Save config.js.
5. In GitHub repository, upload and commit these six files to the repository ROOT:
   index.html, config.js, manifest.json, logo-96.png, icon-192.png, icon-512.png
6. Wait for the GitHub Pages deployment (or your existing GitHub-connected hosting) to finish.
7. Open the site and press Ctrl+Shift+R.

IMPORTANT SECURITY LIMITATION:
This version connects directly from the browser to Turso, matching the original MELAN code.
The database token in config.js is visible to anyone who can access the website.
Use only a restricted/temporary token and sample data. Do not use real student data.
Revoke the old token that was previously exposed and create a new one.
No Cloudflare Worker is required for this version.
