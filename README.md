# Jamison Shaver — Personal Site

Personal marketing site for Jamison Shaver, built to support his search for product leadership and executive roles. Live at [jamison-shaver.github.io](https://jamison-shaver.github.io/).

## Pages

- `index.html` — Home
- `experience.html` — Career history (EagleView, Nstream, MARSEC, GE, U.S. Marine Corps) and education
- `about.html` — Background, leadership/product philosophy, and additional credentials
- `contact.html` — Contact details and links

## Structure

```
assets/
  css/style.css     shared stylesheet for all pages
  img/              photos, crests, and the favicon/emblem
  js/main.js        mobile nav toggle
  docs/             downloadable resume PDF
```

Plain HTML/CSS/JS — no build step, no dependencies.

## Hosting

Hosted on GitHub Pages directly from the `main` branch. Pushing to `main` updates the live site automatically (usually within a minute or two).

## Making changes

```
git add -A
git commit -m "Describe the change"
git push
```

When `assets/css/style.css` changes, bump the `?v=N` query string on the stylesheet `<link>` tag in all four HTML pages so browsers pick up the update instead of serving a cached copy.
