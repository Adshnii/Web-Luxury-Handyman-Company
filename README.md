# Luxury Handyman Company — website

Official English-language website for **Luxury Handyman Company / Solvix.S LLC**.

- Planned GitHub Pages address (not yet enabled): https://adshnii.github.io/Web-Luxury-Handyman-Company/
- Repository: https://github.com/Adshnii/Web-Luxury-Handyman-Company
- Business email: info@luxuryhandymansolvix.com
- Phone / WhatsApp: +1 (239) 776-0639
- Service area: Naples, Bonita Springs and Marco Island, Florida

## Hosting and editing

Deployment plan: configure GitHub Pages to serve the `main` branch from the repository root. Hosting has not yet been enabled; design review is ongoing. `.nojekyll` disables Jekyll. There are no build dependencies, server, database, API keys or paid hosting services.

Edit `index.html` for company content, `styles.css` for design and mobile layouts, and `script.js` for navigation and the email request helper. Images are in `assets/`. Once Pages is enabled, commits to `main` will trigger publication.

The form opens the visitor’s email application with a prepared request. It **does not send email automatically**. WhatsApp, email and phone links also work directly. No request information is stored on the website.

## Business domain

The existing business domain is `luxuryhandymansolvix.com`. It is not connected to this repository yet. See [domain setup](docs/DOMAIN-SETUP.md). Do not add a CNAME file before arranging and checking domain DNS. Existing mail DNS records must be preserved. The older `WEB` repository and its `solvixcompany.com` domain are separate.

## Assets

`assets/logo-black.png` is the owner’s approved crossed-impact-driver artwork, copied from the company’s existing asset repository. `assets/interior.jpg` is illustrative interior imagery from Unsplash, not a photograph of a completed company project. Source: https://images.unsplash.com/photo-1600210492486-724fe5c67fb0 . The visible caption says “Interior inspiration.”

Google Fonts provides Playfair Display and Inter; system serif and sans-serif fonts are fallbacks.

## Project records

[Business content sources](docs/CONTENT-SOURCES.md) · [Work log](docs/WORK-LOG.md) · [Domain setup](docs/DOMAIN-SETUP.md)

Keep website code, assets, configuration and documentation in **this repository**, as requested by the owner. Local files used for implementation and testing are temporary. Do not copy private account records, billing information, verification addresses or credentials into this public repository.
