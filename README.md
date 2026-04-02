# Personal Landing Page
### [sameen.info](https://www.sameen.info)

Personal landing page for Sameen Islam — AI Engineer.

## Structure

The page is a single-page static site with four sections:

- **Header** — name, title, and links to LinkedIn and GitHub
- **Profile** — career background and links to writing
- **Projects** — ML and software engineering projects with papers and code
- **Contact** — Twitter/LinkedIn links and a contact form via Formspree

Two persistent banners sit between the header and profile sections:
- A **hire banner** with a link to the CV (dismissible)
- A **writing banner** linking to the [technical blog](https://sameen.dev) and [non-technical blog](https://medium.com/@risingdragon111)

## Built with

- [Skeleton](http://getskeleton.com) — lightweight CSS boilerplate
- [Formspree](https://formspree.io) — contact form handling
- [GitHub Pages](https://pages.github.com) — hosting

## Features

- Responsive layout for mobile and desktop
- System-preference dark mode via `prefers-color-scheme`
- Dismissible hire alert banner
- CV available as PDF download

## Local development

No build step required. Open `index.html` directly in a browser or serve with any static file server:

```bash
npx serve .
