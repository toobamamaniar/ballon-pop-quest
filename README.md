# Skyloons: support site

Support and legal pages for [Skyloons](https://play.google.com/store/apps/details?id=com.maniar.balloonpopquest)
(also known as Balloon Pop Quest), served as a static site through GitHub Pages
from `main`.

## Pages

- `index.html`: home page with the Google Play link and screenshots
- `faq.html`
- `privacy-policy.html`
- `terms.html`
- `data-deletion.html`

URLs of these pages are referenced from the Play Console, so keep the file
names as they are.

## Editing

Plain HTML and CSS, no build step. Shared styling is in `styles.css` (the
"Paper sky" look from the app's menus). Fredoka is hosted in `fonts/`
(SIL Open Font License, see `fonts/OFL.txt`), so the pages make no requests to
third parties. Push to `main` and Pages publishes it.

When the game changes, update the numbers and wording in the FAQ and the
"Last updated" dates on the privacy policy, terms and data deletion pages.

## Local preview

```bash
python3 -m http.server 4173
```

Then open `http://127.0.0.1:4173`.
