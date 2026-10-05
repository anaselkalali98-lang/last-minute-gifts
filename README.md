# Cadeaux de dernière minute

One-page French storefront for flower-and-chocolate gift packs delivered in Casablanca, Morocco. Customers choose a pictured pack and contact the seller on WhatsApp to confirm availability and delivery.

*Boutique en français de coffrets cadeaux de fleurs et de chocolats, livrés à Casablanca. Les commandes se font par WhatsApp.*

## Features

- Six pictured gift packs priced from 149 to 500 dh.
- WhatsApp order links prefilled with the selected pack and price.
- Delivery information, ordering steps, and frequently asked questions.
- Mobile-friendly layout and floating WhatsApp button.

## Tech

- Plain HTML, CSS, and JavaScript in `index.html`; no framework or build step.
- Google Fonts: Young Serif and Figtree.

## Project structure

```
index.html                    the whole page
logo.svg                      French wordmark and gift-box logo
favicon.svg                   compact gift-box browser icon
photos/                       six current gift-pack product photos
```

## Customize

- **WhatsApp number:** change `NUM` in the script at the bottom of `index.html` (international format, no `+`).
- **Prices and texts:** edit the product cards directly in `index.html`.
- **Photos:** replace the files in `photos/` and keep the same names.

## Deploy

This is a static site. On Netlify choose *Add new site → Import an existing project → GitHub*, leave the build command empty and the publish directory blank. Every commit redeploys the site.

## Note on product photos

The photos illustrate the gift-pack styles. Flowers, chocolate brands, exact contents, availability, and delivery fees should be confirmed with the customer before the order is finalized.

## Author

Made by Maicon, Casablanca.
