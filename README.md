# Mohammad Oveisi — personal website

Static site for GitHub Pages. Plain HTML and CSS, no build step.

| File | Page |
| --- | --- |
| `index.html` | Home: hero, at a glance, featured work, selected publications, news, about |
| `research.html` | Research project cards (anchors are linked from Home and Publications) |
| `publications.html` | Publications, patents, theses |
| `resume.html` | Résumé |
| `assets/style.css` | Shared styles (light and dark) |
| `assets/social-card.png` | Link-preview image (`og:image`), 1200×630 |

## Preview locally

```bash
python -m http.server 8123
```

Then open http://localhost:8123.

## Deploy

Push to the `main` branch of a repository named `<username>.github.io`. In the repository's Settings → Pages, set the source to "Deploy from a branch", branch `main`, folder `/ (root)`.

## Editing

The header, navigation, and footer are repeated in each page; change all four when the menu changes. Update the "Updated" date in the footer when content changes.
