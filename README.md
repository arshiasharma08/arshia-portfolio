# Arshia Sharma — Portfolio

Personal portfolio site for Arshia Sharma, a Data Science student at Purdue
University (The Data Mine Learning Community) interested in machine learning,
data engineering, and software development.

Live: https://arshia-portfolio.onrender.com

## About

A single-page portfolio designed to read like a personal site rather than a
résumé dump — an intro, experience, projects, skills, coursework, and a way
to get in touch. Built plain HTML/CSS/JS, no framework or build step.

## Structure

```
.
├── index.html                 # all page content/sections
├── style.css                  # design tokens + styles
├── script.js                  # nav toggle, active-link highlight, scroll reveal
├── Arshia_Sharma_Resume.pdf   # résumé, linked from the hero + contact sections
└── NOTES.md                   # what still needs to be filled in (screenshots, etc.)
```

## Sections

- **Hero** — intro, links, and an `arshia.json`-styled code card
- **About** — short bio
- **Experience** — NexGen Tech Solutions, Zimetrics LLC
- **Projects** — [Sonar.ai](https://github.com/arshiasharma08/sonar-music-ai),
  [Purdue Research Matchmaker](https://github.com/arshiasharma08/purdue_research)
- **Skills** — grouped by languages / data + ml / tools + platforms / web
- **Coursework** — current Purdue courses + education
- **Contact** — email, LinkedIn, GitHub, résumé (view + download)

## Design

- **Palette** — warm cream background, charcoal text, Purdue gold used
  sparingly, soft lavender as a secondary accent
- **Type** — Manrope (headings/body), JetBrains Mono (labels, tags, code
  details)
- Responsive down to mobile, respects `prefers-reduced-motion`, semantic HTML
  with visible focus states

See `NOTES.md` for outstanding items before this fully replaces the live site
(project screenshots, confirming the Matchmaker's live URL if one exists).

## Running locally

No build step — just open `index.html` in a browser, or serve the folder:

```
python3 -m http.server 8000
```

## Deploying

Static site, deployable as-is:

- **Render** — Static Site, no build command, publish directory `.`
- **Netlify / Vercel** — drag-and-drop the folder or connect the repo

## Tech

HTML5 · CSS3 · JavaScript · Google Fonts (Manrope, JetBrains Mono)

---

Built by Arshia Sharma.
