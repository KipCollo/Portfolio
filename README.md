# KipCollo — Personal Portfolio

A modern, responsive single-page portfolio for a **DevOps Engineer**, **Fullstack Developer**, and **AWS Developer**.

## Sections

| Section | Description |
|---------|-------------|
| **Hero** | Name, role badges, tagline, CTA buttons, social links |
| **About** | Bio, personal facts, key specialisations |
| **Skills** | Three skill cards — DevOps, Fullstack, AWS Cloud |
| **Projects** | Six featured projects with tech tags and links |
| **Contact** | Info panel + validated contact form |

## Tech Stack

- Plain **HTML5**, **CSS3** (custom properties, Grid, Flexbox)
- Vanilla **JavaScript** (no frameworks, no build step)
- [Font Awesome 6](https://fontawesome.com/) for icons

## Local Development

Just open `index.html` in your browser — no build step required.

```bash
# Option 1: open directly
open index.html

# Option 2: serve with any static server
npx serve .
```

## Deployment

Deploy the repository root as a static site to any host:

- **GitHub Pages** — enable Pages in repo settings, source = `main` branch root
- **AWS S3 + CloudFront** — upload files and point CloudFront to the bucket
- **Netlify / Vercel** — drag-and-drop the folder or connect the repo
