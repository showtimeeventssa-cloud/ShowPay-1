# ShowPay Artist

A static, GitHub Pages-ready artist business app for quotes, invoices, clients and schedule.

## Deploy on GitHub Pages
1. Create or open a GitHub repository.
2. Put `index.html`, `manifest.webmanifest`, `sw.js`, and the `assets` folder in the repository root.
3. GitHub → Settings → Pages → Deploy from branch → select the branch and `/root`.
4. Open the published HTTPS URL.
5. On iPhone/Android use the browser's Add to Home Screen / Install App option.

## Important
This build has no external libraries, CDN assets, build step, or server requirement. Data is stored in the browser's localStorage. PDF export uses the browser's native print dialog; choose Save as PDF.

VAT is only added when a VAT number is entered in Settings. The current VAT rate used is 15% for South Africa.
