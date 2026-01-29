# ⚡ STRIKE

A high-fidelity, hackathon-grade frontend landing experience built with pure HTML5 + CSS3 — no JavaScript required. STRIKE demonstrates advanced layout engineering, modern UI aesthetics, responsive design, and accessibility using only semantic HTML and expressive CSS.

Live demo : https://kxnux-builds.github.io/Portfolio/

---

Table of contents
- [About](#about)
- [Demo / Preview](#demo--preview)
- [Key features](#key-features)
- [Built with](#built-with)
- [File structure](#file-structure)
- [Local preview / Development](#local-preview--development)
- [Accessibility & performance](#accessibility--performance)
- [Customization & extension notes](#customization--extension-notes)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## About

STRIKE is a futuristic educational platform landing experience created under a strict "no JavaScript" constraint (e.g., a hackathon challenge). It focuses on visual hierarchy, responsive behavior, accessible markup, and production-quality styling achieved solely with HTML and CSS.

This repository contains a complete static frontend: a multi-section landing page with a hero, features, courses/mentors sections, and a dedicated login UI.

---

## Demo / Preview

To preview the site, open `index.html` in a browser, or serve the repository with a small static server (recommended for consistent font loading).

Example (from project root):

- Open directly:
  - Double-click `index.html` or open it from your browser: `file:///path/to/STRIKE/index.html`

- Recommended: quick local server
```bash
# Using Python 3
python -m http.server 8000

# Then open:
http://localhost:8000/index.html
```

You can also open `login.html` to preview the styled login UI.

---

## Key features

- Modern, neon-inspired UI and premium landing page aesthetics
- Fully responsive (mobile-first) using Flexbox & CSS Grid
- Advanced CSS-only interactivity and animations (keyframes, transitions)
- Accessible semantic HTML and keyboard-friendly focus states
- Reduced-motion support via `prefers-reduced-motion`
- Dedicated login page UI (frontend-only—no backend/auth logic)

---

## Built with

- HTML5 (semantic structure)
- CSS3 (variables, Flexbox, Grid, keyframes, media queries)
- Google Fonts (Orbitron, Poppins)
- Font Awesome (icons) — referenced in markup/styles if present

---

## File structure

```text
STRIKE/
├── LICENSE
├── README.md
├── index.html       # Main landing page
├── login.html       # Login UI page
├── style.css        # Main stylesheet for landing page
├── login.css        # Styles for the login page
├── mentor1.png      # Image asset
├── mentor2.png      # Image asset
```

---

## Local preview & development

1. Clone the repository:
```bash
git clone https://github.com/kxnux-builds/STRIKE.git
cd STRIKE
```

2. Start a local server (recommended so fonts and relative assets load correctly):
```bash
python -m http.server 8000
# or use your preferred static server / Live Server extension
```

3. Open:
- http://localhost:8000/index.html
- http://localhost:8000/login.html

4. Editing notes:
- style.css — main layout, themes, animations
- login.css — login page styling
- index.html / login.html — semantic markup; update content, copy, or images as needed

---

## Accessibility & performance

STRIKE was designed with accessibility and performance in mind:
- Semantic HTML elements for document structure
- Keyboard-friendly focus styles
- `prefers-reduced-motion` support to respect users' motion preferences
- High contrast and clear type hierarchy for readability
- Minimal external dependencies (no JS) reduces runtime overhead

Consider adding an automated accessibility audit (Lighthouse, aXe) for further validation.

---

## Customization & extension notes

- Fonts: The project references Google Fonts — update the font link in the head of `index.html`/`login.html` to swap styles.
- Colors / theme: use the CSS variables at the top of `style.css` to quickly rebrand.
- Images: Replace `mentor1.png` / `mentor2.png` with optimized images (webp or compressed PNG/JPG).
- Interactivity: Since the project intentionally omits JS, prefer CSS-only UI patterns for dropdowns, tabs, and modals. If you later add JS, keep progressive enhancement in mind.

---

## Credits & Links

- Author: Kishanu Mondal
- GitHub: https://github.com/kxnux-builds
- LinkedIn: https://www.linkedin.com/in/kishanu-mondal/
- X (Twitter): https://x.com/Kxnux_Dev

---

## License

See the LICENSE file for license details:
[LICENSE](./LICENSE)

---