# Teckla Giramata Musamankanda — Portfolio Website

A single-page personal portfolio (HTML/CSS/JS) tracking professional milestones, education backgrounds, and technical credentials. All sections — Home, About, Experience, Education & Skills, and Contact — live on one page, and the top navigation bar smooth-scrolls to each section [cite: 1, 2].

This folder is fully self-contained: every asset (styles, scripts, images, fonts, favicons) is included locally, so it runs **offline** with no internet connection and no build step [cite: 1].

---

## Features
- **About Me Section:** Minimalist introduction presenting professional credentials as an L1 IT Support Desktop Engineer at CCI Rwanda [cite: 2].
- **Technical Projects Section:** Showcases enterprise support tracks and custom web codebase infrastructure layouts [cite: 2].
- **Education & Skills Section:** Highlights timeline milestones at St. Joseph Integrated Technical College, training certifications including the CCI IT Academy, and ALX tracks [cite: 2].
- **Contact Section:** Aggregates direct contact link pathways including an official email, Instagram page, and LinkedIn profile networks [cite: 1, 2].

---

## How to run it

### Option 1 — Just open it (simplest)
Double-click **`index.html`**, or drag it into any modern browser (Chrome, Edge, Firefox, Safari) [cite: 1, 2].

> Everything works this way. The only thing that needs a server is the browser's ability to load the web-app manifest / favicons in some strict browsers — the page itself renders fine either way [cite: 1].

### Option 2 — Serve it with a simple local server (recommended)
If you prefer a proper `http://` address (or if a browser blocks a local asset), open a terminal in this folder and run one of [cite: 1, 2]:

```bash
# Python 3 (built in on most systems)
python -m http.server 8000

# or Python 2
python -m SimpleHTTPServer 8000

# or Node.js
npx serve .
```

Then open <http://localhost:8000> in your browser [cite: 1].

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

- **Photo** — replace `images/teckla-portrait.png` with a real headshot (keep the same filename, or update the `src` in `index.html`) [cite: 1].
- **Text** — all copy is in `index.html`; edit the section blocks directly [cite: 1].
- **Colours / fonts** — the palette and font variables are at the top of `css/styles.css` (look for the `:root { ... }` block) [cite: 1].
- **Contact links** — Instagram, LinkedIn and email are in the Contact section of `index.html` [cite: 1].

---

## License
This project is distributed for educational purposes. Users are free to modify, reuse, or redistribute the underlying codebase template configuration layout rules. However, you are strictly forbidden from copying or utilizing the original author's name, profile summary text, or portrait photograph files [cite: 2].


---

## Contributors & Project Roles
- **Teckla Giramata Musamankanda** — Project Owner & Core Developer [cite: 2]
  - Responsible for core project structure, single-page UI architecture, layouts, scripts, styling variables, and primary codebase configurations.
- **Jules NIZEYIMANA (julesni)** — Frontend Contributor (UI/UX - Integration Hub) [cite: 2]
  - **Email:** julesni57@gmail.com
  - **Trello Assigned Task:** Implement and integrate the dedicated Contact Info layout module.
  - **Role Scope:** Responsible for developing the site's communication bridge, wiring up active target references to the author's primary email interface, interactive Instagram node, and professional LinkedIn networks [cite: 2].

---

## Notes

- No internet connection is required to view the site [cite: 1].
- The fonts (DM Serif Display and Roboto Flex) are self-hosted under `fonts/` and are licensed under the SIL Open Font License [cite: 1].
- Tested in current versions of Chrome, Edge, Firefox and Safari, and on mobile screen sizes [cite: 1].