# jaedonjensen.github.io

Personal portfolio served by GitHub Pages at https://jaedonjensen.com.

## Architecture
- Static site: plain HTML + CSS (+ minimal JS). No build step, no framework.
- `CNAME` maps the custom domain — never delete or rename it.
- Pages deploys automatically from `main`.
- Redesign in progress on branch `redesign` (replacing the StyleShout "Augustine" template).

## Conventions
- Colors, spacing, fonts live as CSS custom properties (design tokens) in `:root`.
- Dark theme only (decided 2026-11-20); no theme toggle.
- Images in `images/`; project screenshots in `images/projects/`.
- Keep JS tiny and dependency-free.

## Run locally
    python3 -m http.server 8000   # then open http://localhost:8000

## Deploy
Merge to `main` and push (from the desktop). Pages rebuilds in ~1 minute.
