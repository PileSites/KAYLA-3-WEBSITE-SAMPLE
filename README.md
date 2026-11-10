# Kayla 3 Investment Ltd Website

A bespoke, static website for **Kayla 3 Investment Ltd**—an automotive partner in Uganda offering vehicle sales, bespoke importation, sourcing and rentals. Built with semantic HTML, custom CSS and vanilla JavaScript (no framework, no build step).

## Project structure

- `index.html` — page structure, content, SEO metadata and structured data
- `styles.css` — visual design system, layout and responsive behavior
- `app.js` — routing, catalogue filters, saved vehicles, comparisons, gallery, and enquiry flows
- `vehicles.js` — catalogue data (replace preview records with verified inventory before publishing)
- `config.js` — business and contact configuration (placeholders until confirmed)

## Run locally

Open `index.html` directly, or run `python -m http.server 8000` from this folder and browse to `http://localhost:8000`.

## Before publishing

1. Replace preview inventory records in `vehicles.js` with verified vehicle details, imagery, pricing (UGX), condition, import status and availability.
2. Add confirmed phone/WhatsApp numbers, email, address, opening hours and official social links in `config.js` and site content.
3. Confirm the production domain and update canonical, sitemap and Open Graph URLs accordingly.
4. Use only imagery and brand assets Kayla 3 is authorized to publish.

**Note:** Enquiry forms validate in the browser and prepare a WhatsApp message when a destination number is configured. No form data is stored or transmitted to a server.
