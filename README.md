# Gaurav — Personal Portfolio Website

A polished, dark-themed personal portfolio website for **Gaurav**, a Data Analyst and Aspiring Data Scientist. The site closely mirrors the reference screenshots provided.

---

## 🚀 Live Entry Point

- **Main page:** `index.html`

---

## ✅ Completed Features

- **Sticky Navigation Bar** — Logo on left, section links on right, theme toggle icon
- **Hero Section** — Bold headline, animated typing subtitle, CTA buttons (View Projects / Download Resume), key stats
- **Particle Canvas Background** — Animated floating dots and connections in the hero
- **About Section** — Profile placeholder, bio text, contact details, social links
- **Technical Skills Section** — 4 skill cards (Programming, Data Analysis, Visualization, Tools) with animated progress bars
- **Projects Section** — 6 project cards with colorful banner images, problem/approach/insights, tech tags, and hover overlay links
- **Education / Timeline** — 4 timeline entries with icons, dates, and tag pills
- **Contact Section** — Contact info panel + full contact form with simulated submission
- **Footer** — Name, tagline, social icons, copyright
- **Back-to-Top Button** — Appears after scrolling 400px
- **Dark / Light Theme Toggle** — Persisted in `localStorage`
- **Responsive Design** — Hamburger menu on mobile, fluid grids at all breakpoints
- **Scroll Animations** — Intersection Observer-based fade-in for cards and sections
- **Active Nav Highlighting** — Current section link is highlighted on scroll

---

## 📁 File Structure

```
index.html          ← Main single-page application
css/
  style.css         ← All styles (dark/light theme, layout, animations)
js/
  main.js           ← All interactivity (theme, nav, particles, skill bars, form)
README.md
```

---

## 🔮 Features Not Yet Implemented

- Real resume PDF download
- Live contact form submission (needs a backend / email service like EmailJS)
- Real profile photo
- Real project links and GitHub URLs
- Kaggle / portfolio links

---

## 📌 Recommended Next Steps

1. Replace placeholder social/project links with real URLs
2. Add a real resume PDF and link it to the Download Resume button
3. Integrate **EmailJS** for functional contact form email delivery
4. Add a real profile photo to the About section
5. Deploy via the **Publish tab** to get a live URL

---

## 🛠️ Tech Stack

- HTML5, CSS3 (Custom Properties / CSS Variables), Vanilla JavaScript
- Google Fonts — Inter
- Font Awesome 6 (via jsDelivr CDN)
- Intersection Observer API for scroll animations
- Canvas API for particle animation
