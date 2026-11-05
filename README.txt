# KCS Electrical Toolkit PWA

## Files
- `index.html`: complete mobile-first calculator app
- `manifest.webmanifest`: install metadata
- `sw.js`: offline cache
- `icons/`: PWA icons

## Free hosting with GitHub Pages
1. Sign in to GitHub and create a **public** repository named `kcs-electrical-toolkit`.
2. Upload all files and the `icons` folder from this ZIP to the repository root.
3. Open repository **Settings → Pages**.
4. Under Build and deployment, select **Deploy from a branch**, choose `main` and `/ (root)`, then Save.
5. Wait for GitHub Pages to publish the site. Open the published HTTPS URL in Chrome on Android.
6. Chrome menu ⋮ → **Install app** or **Add to Home screen**.
7. Open the app once online; then the app shell and calculations are available offline.

You can also deploy the same folder to Netlify Drop or Cloudflare Pages for free.

## Included
Motor, kW/HP, breaker/cable check, fault current estimate, MCB trip bands, DOL, star-delta (both conflicting workbook factor sets), OLR, SMPS, cable and busbar thumb rules, PLC digital I/O, local history, formula register and QC tests.

## Engineering limitations
The cable and busbar current-density values are workbook thumb rules, not standards ampacity. The breaker check is not full protection coordination. V/Z is a simplified fault-current estimate. Verify all final designs against applicable IS/IEC standards, manufacturer data, installation conditions and qualified engineering review.

No backend, login, analytics or external runtime library is used. Calculation data/history stays in the browser's local storage on that device.
