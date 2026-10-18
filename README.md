# yuzudo.app

The website of **yuzudo**, the fruity focus timer for Android. Plain HTML and CSS, served by GitHub Pages at https://yuzudo.app. No build step, no JavaScript, no cookies, no analytics and no third-party requests.

## Structure

| Path | Page |
|---|---|
| `/` and `/de/` | Home (English, German) |
| `/support/` and `/de/support/` | Support and FAQ |
| `/privacy/` and `/de/datenschutz/` | Privacy policy |
| `/imprint/` and `/de/impressum/` | Imprint. The contact block sits between `<!-- IMPRINT:START -->` and `<!-- IMPRINT:END -->`. |
| `404.html` | Not-found page (both languages, root-relative links) |
| `css/site.css` | The only stylesheet; colours, type and layout tokens at the top |
| `fonts/` | Self-hosted Sniglet and Fredoka (WOFF2) with their licences |
| `img/brand/` | Wordmarks: `-a` for light grounds, `-b` for dark grounds |
| `img/fruits/`, `img/art/` | Fruit and stats art (SVG; grid fruits as WebP) |
| `img/screens/` | App screenshots (WebP, 600 px wide) |
| `favicon.*`, `apple-touch-icon.png`, `icon-*.png`, `site.webmanifest` | Icons, made from the app icon |
| `og.png` | Social preview image (1200 × 630), made from the Play feature graphic |
| `CNAME`, `.nojekyll`, `robots.txt`, `sitemap.xml` | Hosting and crawler files |

Each page is a folder with an `index.html`, so URLs stay clean. Links are root-relative (`/support/`), so preview the site from its root, e.g. `python3 -m http.server` in this folder.

## Brand rules kept here

- The name is always lowercase: yuzudo, yuzudo+.
- The wordmark and the standalone app icon never appear on the same page; the icon is used only for favicons and the web manifest.
- The only published contact address is hi@yuzudo.app.

## Licences

- Fonts: [Sniglet](fonts/sniglet/OFL.txt) and [Fredoka](fonts/fredoka/OFL.txt), both under the SIL Open Font License 1.1.
- Brand art (wordmarks, app icon, fruit and stats art, screenshots): © yuzudo, all rights reserved.
