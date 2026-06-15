# Gleec Finery UI Options Deck

This repository hosts the **Gleec Slovakia × Finery Markets — UI integration options** presentation.

It is an interactive, self-contained HTML deck (slide navigation, hover effects,
clickable elements, and animations) served as a static site.

## Contents

- `index.html` — the full interactive presentation. Everything (styles, scripts,
  images, fonts) is embedded inside this single file, so it runs directly in any
  modern browser with no build step.

## Viewing locally

Open `index.html` in a browser, or serve the folder over HTTP:

```bash
npx http-server .
# then open the printed http://localhost:8080 URL
```

## Deployment

The deck is deployed as a static site (Vercel). `index.html` loads directly from
the root URL — no nested path required.

---

_Confidential — Gleec internal product strategy material._
