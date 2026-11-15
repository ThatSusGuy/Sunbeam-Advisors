# Sunbeam Advisors — website

Static website for Sunbeam Advisors, a Mumbai-based corporate finance advisory firm.

## Pages
- `index.html` — Home
- `about.html` — Firm overview, Managing Partner profile, principles, offices
- `services.html` — Practice areas, engagement process, sector coverage
- `contact.html` — Contact details and enquiry form

## Structure
```
assets/css/styles.css   all styles (responsive, no framework)
assets/js/main.js       mobile menu, footer year, enquiry form
assets/img/mark.svg     logo mark / favicon
```

No build step. Open `index.html` in a browser, or serve the folder with any static host
(GitHub Pages, Netlify, Vercel, S3, cPanel).

## Notes
- **Enquiry form** opens the visitor's email client addressed to sunil@sunbeamadvisors.com.
  To receive submissions directly, point the form at a form service (e.g. Formspree, Netlify Forms)
  and update `assets/js/main.js`.
- **Portrait**: the founder blocks show an "SN" monogram. To use a photograph, add
  `<img src="assets/img/sunil-nimdia.jpg" alt="Sunil Nimdia">` inside each `.portrait` element.
- Fonts: Source Serif 4 and Inter, loaded from Google Fonts.
