# Mohammad Oveisi — personal website

Static site for GitHub Pages. Plain HTML and CSS, no build step.

| File | Page |
| --- | --- |
| `index.html` | Home: bio, at a glance, news |
| `research.html` | Research projects |
| `publications.html` | Publications, patents, theses |
| `resume.html` | Résumé |
| `assets/style.css` | Shared styles (light and dark) |

## Preview locally

```bash
python -m http.server 8123
```

Then open http://localhost:8123.

## Deploy

Push to the `main` branch of a repository named `<username>.github.io`. In the repository's Settings → Pages, set the source to "Deploy from a branch", branch `main`, folder `/ (root)`.

## Editing

The header, navigation, and footer are repeated in each page; change all four when the menu changes. Update the "Updated" date in the footer when content changes.
