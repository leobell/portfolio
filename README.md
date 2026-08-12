# Leonardo Bell — Portfolio

A personal portfolio website showcasing my projects, skills and credentials as a full-stack developer. Built from scratch with plain HTML, Tailwind CSS and vanilla JavaScript — no framework, no build step.

**Live site:** _add your Netlify URL here once deployed_

## Design

Dark editorial theme (charcoal background, beige typography) with purple and blue accent colors, serif display font (Fraunces) for headlines and Inter for body text. The homepage navigation is built as four large stacked words instead of a traditional menu, inspired by minimalist designer portfolios.

## Tech stack

- **HTML5** — semantic markup, multi-page structure
- **Tailwind CSS** (via CDN, with a custom theme config) — utility-first styling, no build tooling required
- **Vanilla JavaScript** — `IntersectionObserver` for scroll-reveal animations
- **Google Fonts** — Fraunces (serif) and Inter (sans-serif)

## Features

- Multi-page site: Home, About, Projects, Credentials, Contact, plus a dedicated detail page per project
- Fixed sidebar navigation on desktop (social links + rotated home/copyright labels), collapsible top bar on mobile
- Staggered entrance animation on the homepage hero (fade + rise)
- Hover skew effect on the main navigation words
- Scroll-reveal animations (fade-in on scroll) across content sections
- Animated scrolling tech-stack ticker
- Decorative animated gradient lines as background accents
- Fully responsive, mobile-first layout

## Project structure

```
portfolio/
├── index.html              # Home — hero navigation + tech ticker
├── about.html               # About page
├── projects.html             # Projects overview (grid)
├── credentials.html          # Skills + honors/certifications
├── contact.html              # Contact page
├── style.css                 # Custom keyframes (fadeInUp, marquee, drift, reveal)
├── script.js                  # Scroll-reveal logic (IntersectionObserver)
├── tailwind-config.js        # Shared Tailwind theme (colors, fonts)
├── projects/
│   └── e-learning-platform.html   # Case study page for a specific project
├── assets/
│   └── e-learning/            # Project screenshots
└── files/
    └── master-web-developer.pdf  # Certification file
```

## Pages

| Page | Description |
|---|---|
| `index.html` | Homepage with animated hero navigation (About / Projects / Credentials / Contact) |
| `about.html` | Bio and background |
| `projects.html` | Grid of projects, linking to individual case study pages |
| `projects/e-learning-platform.html` | Detailed case study: MERN stack e-learning platform |
| `credentials.html` | Technical skills and honors/certifications |
| `contact.html` | Direct email and social links |

## Running locally

No build step needed — it's static HTML/CSS/JS.

1. Clone or download this repository
2. Open `index.html` directly in a browser, or serve the folder with any static server (e.g. VS Code's Live Server extension) for the best experience

## Deployment

Deployed as a static site (e.g. via Netlify drag-and-drop, or GitHub Pages). Since it's fully static, it can be hosted on any static file host.

## Author

**Leonardo Bell**
Full-stack developer — MERN stack

- Email: bellleonardo04@gmail.com
- GitHub: _add your profile link_
- LinkedIn: _add your profile link_
