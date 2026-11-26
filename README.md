# TayyabInfo landing page

A responsive, dark, orange-accented static website inspired by the supplied car-rental template and adapted for a managed IT / digital services business in Pakistan.

## Files

- `index.html` — all landing-page sections and content
- `shared.css` — shared design tokens, reset, typography and reusable controls
- `main.css` — page-specific layout, visual components and responsive breakpoints
- `main.js` — mobile navigation and dynamic footer year

## Run locally

```bash
python3 -m http.server 8000
```

Open http://localhost:8000.

No framework, build step, package install or JavaScript dependency is required.

## Before launch

- Confirm that all listed services match what you actually offer.
- Replace `hello@tayyabinfo.com` with your working business email if different.
- Add your WhatsApp / phone details and connect a real contact form backend.
- Replace CSS-built artwork with optimized local photographs if you want real project imagery.
- Add individual service pages later; the service links currently point to the enquiry section.
- Test on real phones, then run Lighthouse and accessibility checks.

## Performance

The hero and service illustrations are CSS-built, so there are no large stock-photo downloads. Google Fonts is optional and falls back to system fonts if unavailable.
