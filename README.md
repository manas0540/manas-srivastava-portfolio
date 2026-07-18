# Manas Srivastava — Portfolio

**The Timeless Analyst** — a single-page portfolio for a Data Analyst & AI
profile, built with plain HTML, CSS, and JavaScript. No frameworks, no build
step — clone it and open it.

🔗 **Live site:** _add your GitHub Pages link here once deployed_ (see
[Deploying](#deploying-to-github-pages) below)

---

## About

I'm a Data Analyst & AI profile — I combine data, analytics, and applied AI
to turn raw, messy datasets into decisions. This site is my portfolio:
profile, skills, work experience, projects, achievements, volunteering,
education, and certifications, all in one page.

- 700,000+ records analyzed across projects
- Up to 95% model accuracy achieved
- Top 0.9% globally, TCS CodeVita Season 12 (537,000+ participants)
- Selected trainee, McKinsey & Company Forward Program
- Walmart Sparkathon Awardee
- Freelance Data Analyst since January 2026

## Features

- Single self-contained `index.html` — no build tools, no dependencies to install
- Fully responsive (mobile → desktop)
- Respects `prefers-reduced-motion` for accessibility
- Scroll-reveal animations and a typed SQL-query hero effect
- Live GitHub avatar pulled automatically from the GitHub API
- Drop-in image support for achievements/certificates (see
  [`assets/images/README.md`](assets/images/README.md)) — add a file with the
  right name and it shows up automatically, no code edits required

## Tech stack

| Layer      | Choice                                  |
|------------|-------------------------------------------|
| Markup     | HTML5                                     |
| Styling    | Plain CSS (custom properties, CSS Grid/Flexbox) |
| Behavior   | Vanilla JavaScript (no frameworks)        |
| Fonts      | [Fraunces](https://fonts.google.com/specimen/Fraunces) (display), [IBM Plex Sans](https://fonts.google.com/specimen/IBM+Plex+Sans) (body), [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) (data/labels) — via Google Fonts CDN |

## Folder structure

```
manas-srivastava-portfolio/
├── index.html                          # the entire site
├── README.md                           # this file
├── .gitignore
└── assets/
    └── images/
        ├── README.md                   # exact filenames the site looks for
        ├── sih.jpg                     # (add) Smart India Hackathon photo
        └── genius-olympiad-certificate.jpg   # (add) Physics Olympiad certificate
```

## Getting started

Clone the repo and open the file directly — no install step required.

```bash
git clone https://github.com/manas0540/manas-srivastava-portfolio.git
cd manas-srivastava-portfolio
open index.html   # macOS
# or just double-click index.html on Windows/Linux
```

## Adding your own images

The site is pre-wired to display images for a couple of achievement entries
the moment you drop the right file into `assets/images/`. Full instructions,
exact filenames, and how to add more (project screenshots, etc.) are in
[`assets/images/README.md`](assets/images/README.md).

## Deploying to GitHub Pages

1. Push this repo to GitHub (see [Pushing to GitHub](#pushing-to-github) below).
2. On GitHub, go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to `Deploy from a branch`.
4. Set **Branch** to `main` and folder to `/ (root)`, then **Save**.
5. GitHub will publish the site at:
   `https://manas0540.github.io/manas-srivastava-portfolio/`
6. Come back and drop that link into the "Live site" line at the top of this
   README.

## Pushing to GitHub

This repo is already initialized locally with an initial commit. To push it:

```bash
# 1. Create an empty repository on GitHub named manas-srivastava-portfolio
#    (github.com/new — do NOT initialize it with a README/license/gitignore)

# 2. Point your local repo at it and push
git remote add origin https://github.com/manas0540/manas-srivastava-portfolio.git
git branch -M main
git push -u origin main
```

After that, every future update is just:

```bash
git add .
git commit -m "Describe what changed"
git push
```

## Editing content

Everything lives in `index.html` — it's organized into clearly labeled
sections (`<!-- HERO -->`, `<!-- PROJECTS -->`, `<!-- CERTIFICATIONS -->`,
etc.) so you can find and edit any block directly without hunting through a
build pipeline.

## Contact

- Email: srivastavamanas990@gmail.com
- Phone: +91-6392617264
- GitHub: [github.com/manas0540](https://github.com/manas0540)
- LinkedIn: [linkedin.com/in/manas-srivastava](https://www.linkedin.com/in/manas-srivastava-28010125b/)

---

© 2026 Manas Srivastava — The Timeless Analyst.
