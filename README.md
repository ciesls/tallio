# Tallio — shared expenses for two

Public product and support website, hosted on [GitHub Pages](https://ciesls.github.io/tallio/).
The site is plain HTML and CSS; GitHub Pages serves the repository root from `main`.

- `index.html`: product description, feature tour, Free and Pro, and frequently asked questions.
- `support.html`: contact and troubleshooting.
- `styles.css`: shared responsive design.
- `screenshots/`: displayed images use the approved ASC design and current app captures, with silver iPhone 17 Pro frames applied using frames-cli and transparent WebP exports without marketing headlines. Dated image URLs keep cached older assets from appearing on the page.
- Shortcuts, Siri, and Apple Intelligence copy reflects the current native actions and their language, Pro, and device requirements.
- `sitemap.xml`: public page URLs.

The privacy policy lives at [`legal/privacy.html`](legal/privacy.html) so the product, support, and legal pages deploy together.

To preview locally, run `python3 -m http.server 8000` and open `http://localhost:8000`.
No package installation or build step is required.

Tallio 1.0 is available on the [App Store](https://apps.apple.com/app/id6793468900).
Download links and the official Apple badge point to that listing. Tallio is free; Tallio Pro
is a one-time household unlock. Prices verified on Apple’s public listings on October 15, 2026:
US $4.99 and 24,99 zł in Poland. Other storefront prices may vary.

Internal links and assets are relative so the site supports both the `/tallio/` project path
and a future custom-domain root. When a domain is purchased, configure it in GitHub Pages,
set the domain provider's DNS records, and update canonical, Open Graph, Twitter image,
and sitemap URLs. Keep HTTPS enabled.


September 22 product refresh: compact interactive feature tour, Siri and Shortcuts stories, Free/Pro comparison, and fresh Activity captures from app commit 4d5a1cc on iOS 27. Activity images use frames-cli silver iPhone 17 Pro frames (1350×2760). No mailing-list data is collected. Product styles are in product.css; support and legal documents retain styles.css.

September 28: Tallio Pro shows US $4.99 as a one-time purchase, with local storefront prices varying. Analytics, category detail, budgets, and recurring images were refreshed from app source dbfcb805 using isolated sample data and the same silver frames-cli device treatment.
