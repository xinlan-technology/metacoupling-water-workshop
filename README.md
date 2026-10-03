<p align="center">
  <img src="assets/images/favicon.svg" width="56" alt="">
</p>

<h1 align="center">Hydrology Beyond the Watershed</h1>

<p align="center">
  <em>A Workshop on Metacoupling as a Lens for Hydrology</em><br>
  <a href="https://xinlan-technology.github.io/metacoupling-water-workshop/"><strong>Visit the website →</strong></a>
</p>

---

A single-page website for a small, invitation-only online workshop. It is plain HTML and CSS (no JavaScript, framework, or build step) and is served directly by GitHub Pages from the `main` branch.

## What's here

| Path | Purpose |
| --- | --- |
| `index.html` | All page content and structure |
| `assets/css/site.css` | Layout, typography, and colors; design tokens are at the top |
| `assets/fonts/` | Self-hosted Newsreader font and its license |
| `assets/images/` | Browser tab icons |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are |

## Preview locally

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

## Notes

- All asset paths are relative, so the site works under the `/metacoupling-water-workshop/` subpath.
- The page asks search engines not to index it. To allow indexing, remove the `robots` meta tag from `index.html`.
- Newsreader is by Production Type, used under the [SIL Open Font License 1.1](assets/fonts/OFL.txt).
