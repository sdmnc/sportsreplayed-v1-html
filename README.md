# SportsReplayed — v1 (static HTML)

The first prototype of [SportsReplayed](https://sportsreplayed.com), a "Letterboxd for sports" where fans track, rate and review matches they've watched.

This version is a static mockup built with plain **HTML and CSS**: a landing page with a trending-matches carousel, plus login and registration pages.

## Pages

- `index.html` — landing page with hero section and match carousel
- `login.html` — sign-in form
- `register.html` — sign-up form

## Run locally

No build step. Open `index.html` in a browser, or serve the folder:

```bash
npx serve .
```

## Project evolution

1. **v1 — static HTML** (this repo)
2. [v2 — vanilla JS](https://github.com/sdmnc/sportsreplayed-v2-vanilla-js): multi-page app wired to a REST API
3. [v3 — React](https://github.com/sdmnc/sportsreplayed-v3-react): rewrite with React, TypeScript and Vite

The current production site runs on Next.js.
