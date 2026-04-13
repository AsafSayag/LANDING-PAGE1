# TBOOK Landing Page

Static landing site for TBOOK.

## Files

- `index.html` — main landing page
- `contact.html` — contact / CTA destination page
- `faq.html` — FAQ page
- `privacy.html` — privacy policy page
- `tbook_he.html` — alternate Hebrew landing page variant

## Run locally

Because this repo is plain HTML, you can open `index.html` directly in a browser.

If you want a local server instead:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## What was fixed

- Added the missing `contact.html` page.
- Existing links to `contact.html` from the main CTA and other pages now resolve correctly.
- Added this `README.md`.

## Notes

- Contact details currently used across the site:
  - Phone: `052-560-3424`
  - Email: `1@tbook.co.il`
- `privacy.html` already uses the same contact details, so the new contact page matches the current site content.
