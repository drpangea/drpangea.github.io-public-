# Alex Sample — Campaign Website (placeholder)

This repository contains a minimal static campaign site prepared for GitHub Pages.

Pages included:
- index.html — main landing page
- about.html — candidate and committee info
- issues.html — issues positions
- volunteer.html — volunteer sign-up (uses external form endpoint)
- donate.html — donation landing page (links to external processor)
- privacy.html — placeholder privacy policy
- style.css — site styles
- assets/og-image.svg — placeholder social preview image

Site will be served at: https://drpangea.github.io once pushed to the repository named `drpangea.github.io`.

Placeholders to replace before going public:
- Candidate name, biography, committee & treasurer fields
- Replace `https://example-processor.example/donate` with your approved donation processor link (ActBlue / WinRed / Donorbox / etc.).
- Replace Formspree action in volunteer.html with your form/CRM endpoint.
- Replace privacy policy text with counsel-approved language.
- Replace the social preview image (assets/og-image.svg) with a production PNG (1200x630) and update meta tags if necessary.
- Add a favicon at assets/favicon.ico if desired.

Quick local preview:
- From the folder, run a simple local server:
  - python3 -m http.server 8000
  - open http://localhost:8000 in your browser

Deployment notes:
- If you create a repository named `drpangea.github.io` and push these files to the `main` branch, GitHub Pages will serve the site at `https://drpangea.github.io/`.
- No custom domain is configured in this archive.

See the commit & push instructions below for exact commands.