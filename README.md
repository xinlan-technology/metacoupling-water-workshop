<p align="center">
  <img src="assets/images/favicon.svg" width="56" alt="">
</p>

<h1 align="center">Hydrology Beyond the Watershed</h1>

<p align="center">
  <em>A Workshop on Metacoupling as a Lens for Hydrology</em><br>
  <a href="https://xinlan-technology.github.io/metacoupling-water-workshop/"><strong>Visit the website →</strong></a>
</p>

---

Four static pages for an invitation-only online workshop. HTML and CSS only, with two self-hosted fonts (Geist and Geist Mono) and no JavaScript or build step.

## What's here

| Path | Purpose |
| --- | --- |
| `index.html` | Workshop overview, motivation, and discussion topics |
| `plan.html` | Workshop stages, timeline, timing, and coauthor invitation |
| `reading.html` | Five background papers |
| `people.html` | Lead, organizers, participants, and contact email |
| `assets/css/site.css` | Layout, typography, and colors; design tokens are at the top |
| `assets/fonts/` | Geist and Geist Mono as variable WOFF2 files (Latin subset), with their license in `OFL.txt` |
| `assets/images/` | Browser tab icons |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are |

## Preview locally

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

## Notes

- Publish with GitHub Pages from the `main` branch and repository root.
- Relative links support the `/metacoupling-water-workshop/` subpath. Every page includes `noindex, nofollow`.
- Light and dark color schemes follow the reader's system setting.
- In `plan.html`, keep timeline status text and classes together: Upcoming (no class), In progress (`current`), Done (`done`). Update the footer month on all four pages after changes.
