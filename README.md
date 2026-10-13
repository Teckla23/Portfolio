# Teckla Giramata Musamankanda — Portfolio Website

A single-page personal portfolio (HTML/CSS/JS). All sections — Home, About,
Experience, Education & Skills and Contact — live on one page, and the top
navigation bar smooth-scrolls to each section.

This folder is fully self-contained: every asset (styles, scripts, images,
fonts, favicons) is included locally, so it runs **offline** with no internet
connection and no build step.

---

## How to run it

### Option 1 — Just open it (simplest)
Double-click **`index.html`**, or drag it into any modern browser
(Chrome, Edge, Firefox, Safari).

> Everything works this way. The only thing that needs a server is the
> browser's ability to load the web-app manifest / favicons in some strict
> browsers — the page itself renders fine either way.

### Option 2 — Serve it with a simple local server (recommended)
If you prefer a proper `http://` address (or if a browser blocks a local
asset), open a terminal in this folder and run one of:

```bash
# Python 3 (built in on most systems)
python -m http.server 8000

# or Python 2
python -m SimpleHTTPServer 8000

# or Node.js
npx serve .
```

Then open <http://localhost:8000> in your browser.

---

## Folder structure

```
teckla-portfolio/
├── index.html            # the whole site (all sections on one page)
├── README.md             # this file
├── css/
│   ├── styles.css        # main styles (template design language)
│   └── vendor.css        # third-party base styles
├── js/
│   ├── main.js           # navigation, smooth-scroll, animations
│   └── plugins.js        # bundled third-party scripts
├── fonts/
│   ├── fonts.css         # @font-face rules (self-hosted)
│   └── *.woff2           # DM Serif Display + Roboto Flex font files
├── images/
│   ├── teckla-portrait.png
│   ├── geometric_shape.svg
│   └── icons/icon-quote.svg
├── favicon.ico
├── favicon-16x16.png
├── favicon-32x32.png
├── apple-touch-icon.png
├── android-chrome-192x192.png
├── android-chrome-512x512.png
└── site.webmanifest
```

---

## Customising

- **Photo** — replace `images/teckla-portrait.png` with a real headshot
  (keep the same filename, or update the `src` in `index.html`).
- **Text** — all copy is in `index.html`; edit the section blocks directly.
- **Colours / fonts** — the palette and font variables are at the top of
  `css/styles.css` (look for the `:root { ... }` block).
- **Contact links** — Instagram, LinkedIn and email are in the Contact
  section of `index.html`.

---

## Notes

- No internet connection is required to view the site.
- The fonts (DM Serif Display and Roboto Flex) are self-hosted under
  `fonts/` and are licensed under the SIL Open Font License.
- Tested in current versions of Chrome, Edge, Firefox and Safari, and on
  mobile screen sizes.
