# Drain Pros static website

A responsive, image-free, single-page website for Drain Pros. It uses semantic HTML, plain CSS, and a small vanilla JavaScript file. No package installation, build step, image asset, or external font is required.

## Files

- `index.html` — full homepage, service descriptions, two service-area panels, complete commercial plumbing article, contact form UI, and footer.
- `style.css` — responsive visual system, layout, CSS-only abstract decorations, hover states, animation, focus styles, and reduced-motion handling.
- `script.js` — responsive menu, keyboard escape handling, current-year label, form validation feedback, and progressive reveal animation.
- `manus-routes.json` — page route manifest for the one-page homepage.

## Run locally

Open `index.html` directly in a modern browser, or serve this folder from any static web host. For a local HTTP preview with Python installed:

```sh
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Before launch

The contact form is front-end only and does not transmit personal information. Connect a trusted form endpoint or your own server-side handler before inviting real enquiries. Add verified business contact details and confirm the desired emergency-service expectations for each region; this sample deliberately does not invent a phone number, email address, licensing claim, or response-time promise.

The homepage article is complete original copy. Its second paragraph contains the only hyperlink inside the article, using the requested anchor text and target URL. No images are used; decorative artwork is CSS-only.
