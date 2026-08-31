# Traveon Systems Innovation — Website

Static site for Traveon Systems Innovation Limited (Dubai, DIFC).

## Files

- `index.html` — page content and structure
- `styles.css` — all styling
- `script.js` — nav toggle, scroll effects, reveal animations, contact form
- `assets/logo-mark-square.png` — company logo mark, used in the header and footer
- `assets/favicon-32.png`, `assets/favicon-180.png`, `assets/favicon-512.png` — favicon at the sizes browsers/devices ask for, generated from the same mark

No build step — plain HTML/CSS/JS. The hero and about photos are hot-linked from Unsplash (free stock, no download needed); fonts load from Google Fonts.

## How to publish on GitHub

1. Create a new repository on GitHub (e.g. `traveon-website`).
2. Upload these files keeping the folder structure (everything in `assets/` must stay inside an `assets` folder).
3. Go to the repo's **Settings → Pages**, set Source to the `main` branch (root), and save.
4. Your site will be live at `https://<your-username>.github.io/<repo-name>/` within a minute or two.

## Notes

- The contact form currently opens the visitor's email client via a `mailto:` link (see the note under the form). Swap this for a real form handler or CRM integration before launch, as noted on the site itself.
- Update `info@traveonsystems.com` throughout if the real contact email differs.
