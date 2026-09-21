# Portfolio Site

Danielle LaBruzzo's personal portfolio — a static site (HTML/CSS/JS, no build step) hosted on GitHub Pages.

## Editing content

- **Text/sections**: edit `index.html` directly. Each section is clearly labeled with an `id` (`about`, `projects`, `skills`, `contact`).
- **Projects**: the three cards in the `#projects` section are placeholders — replace the title, description, tags, and `href` link in each `<article class="card">` block.
- **Colors/spacing**: edit `styles.css`. Colors are defined once as CSS variables at the top (`:root`), including a dark-mode variant.
- **Mobile menu behavior**: `script.js`.

## Running locally

This site has no dependencies. Open `index.html` directly in a browser, or serve it locally:

```bash
ruby -run -e httpd . -p 4173
```

Then visit `http://localhost:4173`.

## Deploying updates

Changes pushed to the `main` branch of this repo are published automatically to
`https://dandml1017.github.io/`.

```bash
git add -A
git commit -m "Update content"
git push
```
