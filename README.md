# Splash Content Assets

Public hosting for Splash content assets — connection guide screenshots, social images, dashboards, and other images that need to be fetched by the splashrenewable.co.uk Framer site.

## Structure

```
connection-guides/
  [brand-slug]/
    step-NN_short-description.ext
    logo.png
    charger.png
```

Example raw URL:
`https://raw.githubusercontent.com/andrew-w15/splash-content-assets/main/connection-guides/zeeda-series-k/step-02_login.jpg`

## Conventions

- **Step images:** `step-NN_kebab-description.ext` (e.g. `step-02_login.jpg`)
- **Brand logo:** `logo.png` — must be on white background
- **Charger product photo:** `charger.png`

Images sourced from:
- Splash-branded onboarding PDFs (extracted via `extract_pdf_images.py`)
- Official vendor documentation / manuals
- Vendor press kits (for logos and product photos)

## Licence

All images in this repo are either Splash-created or extracted from publicly available vendor documentation for the purpose of producing connection guides on splashrenewable.co.uk. Redistribution rights follow vendor doc terms.
