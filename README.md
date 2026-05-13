# Matthew Tian — Personal Portfolio

A minimal, editorial-style personal portfolio website built with vanilla HTML, CSS, and JavaScript. Designed to showcase projects, skills, and experience as a Computer Science & Economics student at Wilfrid Laurier University.

**Live site:** [https://matthew-tian5.github.io/My-Website/](https://matthew-tian5.github.io/)

---

## Overview

This portfolio was designed from scratch with a focus on clean typography, intentional whitespace, and smooth interactions — no frameworks, no build tools, just HTML, CSS, and a little JavaScript.

The design draws from editorial portfolio aesthetics: thin Josefin Sans headings, a warm off-white palette, and a full-bleed hero with a side-by-side headshot layout.

---

## Sections

| Section | Description |
|---|---|
| **Hero** | Full-viewport intro with headshot, stats, and animated text |
| **About** | Bio, interest pills, and quick-stat highlights |
| **Skills** | Four-column grid: Languages, Frameworks, CS Concepts, Tools |
| **Projects** | Six pinned GitHub projects with tags and direct links |
| **Experience** | Timeline of education (WLU, Google Certificate, High School) and work (RunwayTo, Blowout Technologies, Enactus, Freelance) |
| **Contact** | Contact links and a message form |

---

## Tech Stack

- **HTML5** — semantic structure
- **CSS3** — custom properties, CSS Grid, Flexbox, animations, media queries
- **Vanilla JavaScript** — scroll effects, IntersectionObserver for reveal animations, hamburger menu
- **Google Fonts** — Josefin Sans (display), DM Sans (body)
- **GitHub Pages** — hosting and deployment

No frameworks. No dependencies. No build step.

---

## Features

- Fully responsive — desktop, tablet, and mobile
- Hamburger nav with slide-in overlay on mobile
- Scroll-triggered fade-up animations via IntersectionObserver
- Active nav link tracking on scroll
- Frosted glass nav bar effect on scroll
- Hero photo with left and bottom gradient blending
- Hover animations on project cards
- Smooth scroll navigation

---

## Project Structure

```
/
├── index.html
├── style.css
├── images/
│   ├── favicon.png
│   ├── logo-white.png
│   ├── headshot.png
│   └── logos/          # Org logos for experience timeline
└── fonts/              # Local font fallbacks (optional)
```

---

## Running Locally

No build process needed.

```bash
git clone https://github.com/Matthew-Tian5/www.Matthew-Tian5.github.io.git
cd www.Matthew-Tian5.github.io
open index.html
```

Or use a local server to avoid path issues:

```bash
# Python
python3 -m http.server 8000

# Node
npx serve .
```

Then visit `http://localhost:8000`.

---

## Deployment

Deployed via **GitHub Pages** from the `main` branch. Every push to `main` updates the live site automatically.

> **Note:** GitHub Pages runs on Linux and is case-sensitive. Make sure all image paths in HTML exactly match filenames on disk — including extension case (`.png` not `.PNG`) and folder name case (`images/` not `Images/`).

---

## Customization

All content is in `index.html` and all styles in `style.css`. Colours are controlled by CSS variables at the top of `style.css`:

```css
:root {
  --bg: #ECEAE5;      /* page background */
  --bg2: #E4E1DB;     /* alternate section background */
  --text: #1a1a18;    /* primary text */
  --muted: #7e7c75;   /* secondary / muted text */
  --border: #d0cdc7;  /* dividers and card borders */
}
```

---

## License

Open source under the [MIT License](LICENSE). Feel free to use it as a template — just swap in your own content.

---

*Built by Matthew Tian · CS & Economics @ Wilfrid Laurier University*