# Ahdookeh Fashion — Website Preview

A website preview concept for **Ahdookeh Fashion**, a plus-size Afrocentric womenswear brand at 34 Bode Thomas Street, Surulere, Lagos.

> ⚠️ This is an unofficial preview built as a proposal. It is not the brand's official website. Product photos, prices and the size chart are placeholders.

## Features

- Responsive single-page site, tested from 320px phones up to desktop
- Filterable collections: bubu gowns, two-piece sets, evening gowns, aso-ebi
- "Order on WhatsApp" buttons with a pre-written message for each product
- Size guide with a scrollable table on small screens
- Ordering steps, shipping info (Lagos, Nigeria, worldwide) and an embedded store map
- Hidden from search engines (`noindex`) while in preview

## Tech

- Plain HTML, CSS and JavaScript in one file (`index.html`), no build step
- Fonts: Fraunces and Outfit (Google Fonts)
- Deployed on Vercel

## Editing

All the content you'd normally change is in the `<script>` at the bottom of `index.html`:

- **WhatsApp number:** change `const WA = "234..."` (international format, no `+`)
- **Products:** edit the `products` list. Add `img: "photo.jpg"` to any product to replace its placeholder pattern with a real photo.
- **Preview banner:** remove the `<div class="preview">` at the top once the site is approved and goes live.

## Run locally

Open `index.html` in any browser. No install needed.

## Status

Preview / proposal. Built by COLLINS OSAS.
