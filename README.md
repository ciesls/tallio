# Tallio — shared expenses for two

Public product and support website, hosted on [GitHub Pages](https://ciesls.github.io/tallio/).
The site is plain HTML and CSS; GitHub Pages serves the repository root from `main`.

- `index.html`: product description, feature tour, Free and Pro, and frequently asked questions.
- `support.html`: contact and troubleshooting.
- `styles.css`: shared responsive design.
- `screenshots/`: real iPhone Simulator captures using sample data. The seven website images in `screenshots/framed/` were refreshed 9 September 2026 using silver iPhone 17 Pro frames applied with frames-cli, with transparent WebP exports and no embedded marketing headlines.
- `sitemap.xml`: public page URLs.

The privacy policy lives at [`legal/privacy.html`](legal/privacy.html) so the product, support, and legal pages deploy together.

To preview locally, run `python3 -m http.server 8000` and open `http://localhost:8000`.
No package installation or build step is required.

The site currently says “Coming soon to the App Store.” When the public listing is available,
replace that launch status with the verified App Store URL and the official download badge.
Do not use a guessed App Store URL.

Internal links and assets are relative so the site supports both the `/tallio/` project path
and a future custom-domain root. When a domain is purchased, configure it in GitHub Pages,
set the domain provider's DNS records, and update canonical, Open Graph, Twitter image,
and sitemap URLs. Keep HTTPS enabled.
