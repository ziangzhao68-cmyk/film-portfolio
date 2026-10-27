# Personal Design Portfolio

A cloud-first portfolio workspace for motion-led personal design work.

## Stack

- Semantic HTML
- CSS custom properties and responsive layout
- Vanilla JavaScript for scroll reveals, pointer glow, progress, and project filtering
- GitHub Pages deployment through Actions

## Content model

Keep each project in the `#work` section of `index.html`. Replace the concept copy and gradient art with your real project links or media when ready. The current cards are intentionally labeled as concept studies so placeholder content is easy to spot.

## Design rules

- Use one strong visual idea per project.
- Keep motion subtle and purposeful.
- Preserve `prefers-reduced-motion` behavior.
- Keep the contact action visible on small screens.
- Avoid adding app features that are unrelated to showing work.

## Deploy

Pushes to `main` publish the static site through `.github/workflows/pages.yml`. Enable GitHub Pages for the repository with **GitHub Actions** as the source once in the repository settings.
