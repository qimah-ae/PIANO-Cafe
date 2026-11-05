# PIANO CAFÉ — concept by Qimah

Independent, bilingual German/English website demonstration. Not commissioned or approved by the café. No orders, payments, tracking, forms or backend.

## Run

From `/workspace/PIANO-Cafe`, run `npm run dev` (Python 3 required). Serves on port 3000. No package installation or build is required. The site can be hosted as static files. Use an HTTP server because the scripts use ES modules.

`npm run check` validates JavaScript syntax. Browser validation during delivery covered desktop (1440 px), mobile (390 px), images, language persistence between pages, category filtering, contact/directions links, and absence of JavaScript errors. External destination availability and real ordering were not tested.

## Editing

- `menu-data.js`: curated menu entries, source snapshot, prices and categories.
- `i18n.js`: complete English text mapping, accessible labels, language preference. German is the default. Choice is saved locally; unavailable local storage is handled.
- `app.js`: shared header/footer and both page layouts.
- `styles.css`: responsive design and reduced-motion support.
- `speisekarte.html`: dedicated menu entry point.

## Placeholder assets and confirmation

The text wordmark is a temporary interpretation, not the official logo. The piano illustration and schematic location card are original CSS artwork; the latter is not a geographic map. Photos are stock mood images, never actual café/product images. Locally stored WebP files were resized from images distributed by Start Bootstrap Business Casual (MIT; included license). Upstream attributes its photography to Unsplash. Source files: https://github.com/StartBootstrap/startbootstrap-business-casual/tree/master/src/assets/img — `intro.jpg` (barista), `about.jpg` (interior), `products-01.jpg` (coffee), `products-02.jpg` (croissants). These images are illustrative and do not establish the café's food presentation, staff or premises. Original authorised café photography should replace them before an official launch.

Confirm with the café before commercial publication: authorisation and official logo; photo rights; current menu, ingredient descriptions, prices, allergens, availability; opening hours; contact details and outgoing links; applicable legal/privacy operator information. Exact hours are deliberately omitted. No current performance schedule or promotional cappuccino offer is claimed. Price snapshots come from the user-supplied brief (Wolt and NeoTaste), not a current verification. Descriptions are editorial concept copy rather than ingredient specifications. No placeholder legal policy is presented as complete.

## Preview

The development server starts with `npm run dev`. Screenshots in `preview/` show desktop and mobile views. This is a reviewable sample, not a published official website.
