# Bryan A. Batula — Personal Portfolio

A clean, responsive personal portfolio website built with pure **HTML5** and **CSS3** — no frameworks, no dependencies, no build tools required.

---

## Preview

Open `index.html` directly in any modern browser to view the portfolio locally.

---

## Structure

```
Portfolio/
├── index.html      # Main HTML file (all sections)
├── style.css       # All styling and responsive rules
└── README.md       # This file
```

---

## Sections

| # | Section | Description |
|---|---------|-------------|
| 01 | **About** | Professional summary, contact info, and key highlights |
| 02 | **Skills** | Technical competencies grouped by category |
| 03 | **Projects** | Featured project cards with tech stacks |
| 04 | **Experience** | OJT timeline with role details |
| 05 | **Education & Certs** | Degree and Google Cybersecurity Certificate |
| 06 | **Contact** | Clickable contact cards (email, phone, LinkedIn, GitHub) |

---

## Customization

### Update your social links
In `index.html`, search for the placeholder `href="#"` values and replace them with your real URLs:

```html
<!-- Hero social links -->
<a href="https://linkedin.com/in/YOUR-PROFILE" ...>
<a href="https://github.com/bryanbatula" ...>

<!-- Contact section -->
<a href="https://linkedin.com/in/YOUR-PROFILE" ...>
<a href="https://github.com/bryanbatula" ...>
```

### Update project links
The **Personal Portfolio Website** project already points to your live site and GitHub repo:

```html
<a href="https://github.com/bryanbatula/MyPortfolio" ...>  <!-- GitHub repo -->
<a href="https://bryanbatula.github.io/MyPortfolio/" ...>  <!-- Live demo -->
```

For other projects, replace the `href="#"` placeholders with your real repo and demo URLs.

### Change the accent color
In `style.css`, update the `--accent` variable at the top of the file:

```css
:root {
  --accent: #63b3ed; /* Change this to any color */
}
```

---

## Features

- **Zero dependencies** — no npm, no bundler, opens straight in a browser
- **Responsive** — works on desktop, tablet, and mobile
- **Scroll animations** — elements fade in as you scroll using Intersection Observer
- **Sticky navbar** — transparent on top, frosted glass effect on scroll
- **Mobile menu** — hamburger toggle for small screens
- **External fonts** — Inter (body) + JetBrains Mono (accents) via Google Fonts
- **Icons** — Font Awesome 6 via CDN

---

## Tech Stack

- HTML5
- CSS3 (Custom Properties, Grid, Flexbox, Animations)
- Vanilla JavaScript (navbar behavior, scroll animations)
- Google Fonts — [Inter](https://fonts.google.com/specimen/Inter), [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono)
- Font Awesome 6

---

## Contact

**Bryan A. Batula**
- Email: izme.bryanbatula@gmail.com
- Phone: +63 955-261-0754
- Location: Dolores, Eastern Samar, PH
