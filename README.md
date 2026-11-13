# Meet me at Tech Hub Finland Expo · Badge maker

A one-page tool for making a personal "Meet me at Tech Hub Finland Expo" badge (2160×2160 PNG) and sharing it on LinkedIn.

**Event:** Thu 10 Dec 2026 · 15:00–18:30 EET · Tampere · Register at luma.com/bkz94r4l

## Files
- `index.html`: the whole app (HTML, CSS, JS). No build step, no dependencies.
- `template-bg.jpg`: the badge background (logos, EU co-funding, partners, photo frame).
- `lockup.jpg`: Tech Hub Finland lockup used in the page header.

## Editing
- **Caption text:** the `captions` object in `index.html`.
- **Photo frame / name / role positions:** the `BOX`, `NAME` and `ROLE` constants.
- **Background design:** replace `template-bg.jpg` with a new 2160×2160 image that keeps the same photo frame position.

## Hosting
Served with GitHub Pages from the `main` branch (root folder).
