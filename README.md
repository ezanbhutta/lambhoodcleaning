# Lamb Hood Cleaning — Website

Marketing landing page for **Lamb Hood Cleaning** — NFPA 96 certified commercial kitchen
hood & exhaust cleaning serving the Dallas–Fort Worth metro.

This is **Version 2**: the next evolution of the existing website. Same brand, same colours,
same personality — executed at a higher level of craft. Refined typography, spacing rhythm,
hierarchy, interactions, accessibility, and conversion flow.

## Viewing

`index.html` is a single, self-contained file — just open it in any modern browser:

```bash
open index.html          # macOS
# or serve it
python3 -m http.server   # then visit http://localhost:8000
```

No build step, no dependencies, no network calls at runtime.

## What's inside

- **Fully self-contained** — the brand logo (SVG) and both typefaces are embedded, so the
  page renders identically offline, when deployed, and when exported to PDF.
- **Vanilla HTML / CSS / JS** — no frameworks.
- **Brand system**
  - Colours: navy `#262262`, gold `#ffe169`, paper `#f6f6fb`; heritage peach `#ffab73` (logo).
  - Type: Barlow Condensed (display) + Poppins (body).
- **Sections**: sticky nav + utility bar · hero with inline quote form · trust marquee ·
  reviews · promise / features · how it works · service areas · CTA · contact · footer.
- **Accessibility**: WCAG 2.2 AA focus states, semantic landmarks, labelled forms,
  `prefers-reduced-motion` support, skip link.
- **Responsive**: refined layouts down to small mobile, plus a sticky mobile call/quote bar.

## Structure

```
index.html    # the entire website
README.md
.gitignore
```
