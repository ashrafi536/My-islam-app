# MY ISLAM — Android/PWA package

This package contains the current MY ISLAM HTML app plus the basic files needed to publish it as an installable web app.

## Publish free
1. Create a public GitHub repository named `my-islam`.
2. Upload every file and folder in this ZIP (especially `index.html`, `manifest.webmanifest`, `service-worker.js`, and `icons/`).
3. In the repository, open Settings → Pages. Under Build and deployment, choose Deploy from a branch, select `main` and `/ (root)`, then Save.
4. Wait for GitHub Pages to publish the HTTPS site. Open the live URL and test it.
5. For APK packaging, open https://www.pwabuilder.com/ and enter the live HTTPS URL.
6. Choose Package for stores → Android → Generate Package. For a shareable APK for direct installation, choose the appropriate Android package option and download the generated package.
7. Test the APK on your phone before sharing it.

## Important
- GitHub Pages is free for public repositories, but the repository source will be public.
- Google Play publishing is separate and requires a Google Play developer account fee.
- Keep any signing key and passwords private and backed up.
- The service worker helps cache the app shell; live prayer-time calculations still depend on the app's own code and available location/network permissions.
