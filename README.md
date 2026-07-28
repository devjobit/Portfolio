# Jobit Joseph Shijo — Portfolio

Professional portfolio site for AI/ML & Backend engineering roles.

## Quick start

Open `index.html` in a browser, or serve locally:

```bash
# Python
python -m http.server 8080

# Node (npx)
npx serve .
```

Then visit `http://localhost:8080`.

## Before deploying

1. **Add your résumé** — Place your PDF at `assets/resume.pdf` (linked from nav and contact section).
2. **Update college name** — In `index.html`, add your university name under the Education section if desired.
3. **Add project repo links** — Crop Detection, ALLOY-GPT, and E-Commerce projects can get GitHub links when repos are public.

## Deploy to GitHub Pages

```bash
git init
git add .
git commit -m "Add professional portfolio site"
git remote add origin https://github.com/devjobit/devjobit.git
git push -u origin main
```

In GitHub → Settings → Pages → Source: deploy from `main` branch, root folder.

Your site will be live at `https://devjobit.github.io`.

## Structure

```
jobit-portfolio/
├── index.html          # Main page
├── css/style.css       # Styles
├── js/main.js          # Nav, scroll reveal, copy email
├── assets/
│   ├── favicon.svg
│   └── resume.pdf      # ← add your résumé here
└── README.md
```

## Features

- Recruiter-focused sections: hero stats, education timeline, leadership, projects with metrics
- Mobile navigation with hamburger menu
- Active section highlighting on scroll
- SEO: Open Graph, Twitter cards, JSON-LD structured data
- Accessibility: skip link, ARIA labels, reduced-motion support
- One-click email copy
- Print-friendly layout
