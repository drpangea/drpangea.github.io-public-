# Loren Bibler for Progress — Campaign Website (updated)

This repository contains a static campaign site for Loren Bibler, ready for GitHub Pages.

Contents:
- index.html — home page with hero + headshot
- about.html — bio and headshot
- issues.html — positions
- volunteer.html — volunteer signups (uses external form endpoint)
- donate.html — PayPal integration (hosted_button_id=YSFQ734WTYC28)
- privacy.html — placeholder privacy policy
- style.css — site styles
- assets/ — SVG placeholders and (after you add them) headshot images

HEADSHOT: adding your supplied photo
1. Save your original photo into a temporary folder as headshot-source.jpg.
2. Create responsive sizes using ImageMagick and put them in assets/.
3. Commit & push.

Notes
- The donate page uses your PayPal hosted button ID (YSFQ734WTYC28). Test the flow to verify PayPal pre-fills amounts when redirected with &amount=VALUE; if PayPal does not accept that parameter for hosted buttons we can switch to an official PayPal hosted-button form or Smart Buttons.
- Replace placeholder Formspree endpoint and privacy/legal text with counsel-approved language before collecting data or donations.
- Footers throughout now read: "Updated and maintained by Bibler for Progress Inc".