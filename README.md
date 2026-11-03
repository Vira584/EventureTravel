# EVENTURA Travel — website

Premium, elegant and romantic multi-page static website for EVENTURA Travel, built with plain HTML, CSS and JavaScript. Ready for GitHub Pages.

## Pages
- Home
- Journeys & occasions (catalog + occasion filter)
- Services and Basic / Comfort / Premium packages
- About
- How it works
- Reviews (intentionally marked as forthcoming; no fake testimonials)
- Blog / travel ideas
- Contacts
- Individual trip request
- Budget matching
- Local demo admin panel

## Run locally
Open `index.html` in a browser. For best local testing, use a simple static server (VS Code Live Server).

## Publish on GitHub Pages
1. Create a repository and upload the contents of this folder (not the ZIP itself).
2. In the repository, open **Settings → Pages**.
3. Select **Deploy from a branch**, choose `main` and `/ (root)`, then save.
4. Wait for the Pages URL to appear.

## Demo limitations / production checklist
- The enquiry form stores submissions in `localStorage` in the visitor's browser only. It does not email the owner or submit to a server. Connect Formspree, Netlify Forms, or a backend before production.
- Admin panel is a local demo, not secured, and only shows orders saved in that same browser. Do not use it for real customer data.
- Online payments are not activated. For actual payments, integrate a provider such as Stripe or a locally available payment gateway via a secure backend; never place secret keys in static JavaScript.
- Social links are placeholder entry points; update them to official EVENTURA profiles.
- Journey names, prices and packages are illustrative starting content. Confirm real offers, pricing, destinations and legal travel terms before publishing.
- Google Fonts and Unsplash imagery are loaded from external services and require internet access.

## Language
Use the language toggle in the top navigation. The choice is stored in the browser.

## Footer
Every page includes the requested credit:
`© 2026 Лесик Віра. Усі права захищено. Розроблено: v.lesyk@knute.edu.ua`
