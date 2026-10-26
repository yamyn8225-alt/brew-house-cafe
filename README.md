# Brew House Café — Frontend project

A responsive student demonstration website built with **HTML, CSS, and vanilla JavaScript**.

## Run locally

Open `index.html` in your browser, or open the folder in VS Code and run **Live Server**. No installation or build step is required.

## Pages
- `index.html`: homepage, hero, menu categories, café story
- `menu.html`: 12 demo products, search, category filters, sorting, add-to-cart
- `cart.html`: cart, quantity +/- controls, item removal, totals and empty state
- `about.html`: story and values
- `contact.html`: validated demo contact form

## Structure
- `css/style.css`: all layout, colors, responsive rules
- `js/app.js`: product data, cart storage, navigation, forms and menu behavior
- `images/`: site photography

## Important limitations
- This is a **demo website**; it does not process real orders, payments, emails, or newsletter subscriptions.
- Cart uses your browser's `localStorage` and persists on the same site/origin. For reliable multi-page persistence, run via Live Server rather than opening file URLs if your browser restricts localStorage for `file:` pages.
- The brand, menu, prices, hours, and location are illustrative; edit before using for an actual business.
- Google Fonts are loaded online; local fallback fonts are provided.
- Some menu category photos are low-resolution cropped concept-art assets. Replace with licensed full-resolution product photos if needed.
