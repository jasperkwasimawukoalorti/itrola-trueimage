# itrola true image

**Live site:** https://jasperkwasimawukoalorti.github.io/itrola-trueimage/

A multi-page website for **itrola true image** — a creative studio and organic-wellness hub spanning graphic design, sculpture, textiles, mixed media, and sustainable/organic living.

## About

itrola true image brings together digital art, physical craft, technology, and holistic well-being under one brand. The site is organized into four pillars:

- **Creative Arts & Digital Design** — Graphic Design, Sculpture, Textiles, Mixed Media
- **Software & Hardware Solutions** — software development, embedded systems, systems integration, technical consulting
- **Organic Hub & Sustainable Wellness** — Food Source, Herbal Remedies, Natural First Aid
- **Innovation & Unique Artifacts** — limited-edition and collaborative projects

## Site structure

| File | Page |
|---|---|
| `index.html` | Home / hero |
| `ecosystem.html` | Ecosystem overview |
| `tech-solutions.html` | Software & Hardware Solutions |
| `arts.html` | Arts & design index |
| `graphic-design.html` | Graphic Design |
| `sculpture.html` | Sculpture |
| `textiles.html` | Textiles |
| `mixed-media.html` | Mixed Media |
| `organic-hub.html` | Organic Hub & Wellness |
| `miscellaneous.html` | Miscellaneous / unique artifacts |
| `blog.html` | Blog & Insights |
| `about.html` | Our Philosophy |
| `contact.html` | Contact form |
| `assets/` | Logo and other images |

## Features

- Fully static HTML — no build step required to view or deploy
- Light/dark mode toggle (saved per visitor)
- Live clock and date in the header
- Single hamburger menu as the only navigation, consistent across every page
- Styled with a precompiled Tailwind CSS stylesheet embedded directly in each page (no external CDN dependency, so pages render correctly even on slow connections)

## Updating content

- **Text or images on a single page** — edit the relevant `.html` file directly on GitHub (pencil icon → edit → commit). New images go in `assets/`.
- **Anything shared across all pages** (header, footer, logo, nav, colors) — these are generated from one shared template to keep every page in sync; changes here should go through a full regeneration rather than manual editing of each file.

## License

All rights reserved. See [LICENSE](./LICENSE).
