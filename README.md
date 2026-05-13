
# jorgepetris.com

Personal professional website for Jorge Petris, hosted with GitHub Pages.

The site is a static HTML/CSS page for presenting freelance software development
services with a focus on backend development, cloud infrastructure, and UI/UX
support.

## Current Site

- Professional services landing page for business inquiries and verification.
- Backend-first positioning, followed by cloud delivery and UI/UX support.
- English content by default.
- Spanish content available through the language toggle.
- Browser language detection switches first-time Spanish-language visitors to
  Spanish automatically.
- Visitor language preference is saved in `localStorage`.

## Project Structure

```text
.
├── CNAME
├── index.html
├── styles.css
├── README.md
└── LICENSE
```

## Files

- `index.html`: Page structure, English fallback content, Spanish translation
  map, and the language toggle script.
- `styles.css`: Layout, responsive behavior, profile panel, service cards,
  contact section, footer, and language toggle styling.
- `CNAME`: Custom domain configuration for GitHub Pages.

## Local Preview

This project does not require a build step.

Open `index.html` directly in a browser, or serve the folder with any static
file server if you want to test it through `http://localhost`.

## Deployment

The site is intended to be deployed through GitHub Pages. Since the project is
static, deployment only requires the repository contents to be pushed to the
configured Pages branch.

## Content Notes

The copy is intentionally concise and service-oriented rather than resume-like.
It presents:

- Backend development with Java, Spring Boot, REST, and GraphQL.
- Architecture experience with microservices, event-driven systems, and MVC.
- Cloud and CI/CD work with AWS, Jenkins, Maven, and Gradle.
- UI/UX support with React, TypeScript, and design systems.
