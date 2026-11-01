# AMC Infotech Solution — Full Editable Project

This export contains the website's original HTML, CSS, JavaScript and six transparent PNG product-image atlases, recovered from the original source repository. The original site was authored directly as a static website in a folder named `dist`; it was not a React/Vite project. Here those editable files are organized under `src/`, with original images under `public/` and portable development/build commands added. No source functionality has been removed.

## Run locally

Install Node.js 18 or newer, open Terminal in this folder, then run:

```sh
npm run dev
```

Open http://localhost:5173. Save changes and refresh the browser. No npm dependencies or install step are required.

## Build and host

```sh
npm run build
npm run preview
```

The build copies the editable source and images into `dist/`. Upload the **contents** of `dist/` to your hosting web root (for example, Hostinger `public_html`). The generated `dist/` is also included for convenience. Edit `src/` and `public/`, then build again; direct edits to `dist/` will be overwritten by the next build.

## Where to edit

| File or folder | Purpose |
| --- | --- |
| `src/index.html` | Page sections, navigation, FAQs, dialogs and map embed |
| `src/style.css` | Typography, colors, responsive layout and animations |
| `src/app.js` | Product data, prices, search, filters, galleries, zoom, shortlist and valuation checklist |
| `public/images/products/` | All six original transparent PNG image atlases |
| `scripts/` | Development server and static build scripts |
| `package.json` | Local run/build commands; no third-party dependencies |
| `dist/` | Ready-to-upload copy generated from the source |
| `ASSET_SOURCES.md` | Reference-image source notes |

## Current functionality and launch setup

The export includes the animated hero, product search/filter/sort, specification dialogs, photo-angle galleries and zoom, browser-local shortlist with text download, sell-laptop valuation checklist download, responsive navigation and Google Map.

This is a frontend storefront. Checkout, payments, order management, a database, admin authentication and delivered enquiries are not implemented. Collection entries and prices are samples; images are model references rather than photos of exact stock. Replace them with actual inventory and confirm warranty/return terms and contact details before customer launch. The map currently points to Sanjay Place, Agra rather than an exact shop pin.

Google Fonts and the embedded Google Map require internet access. Product images are included locally. Image atlases contain multiple angles; `galleries`, `photoRegions` and `photoMarkup` in `src/app.js` define their display crops. See `ASSET_SOURCES.md` for original image provenance.
