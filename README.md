# Md Refayatul Islam Portfolio

Static personal portfolio for Md Refayatul Islam, a Computer Science & Engineering student at Bangladesh University of Professionals.

The site presents projects, skills, experience, education, volunteer work, and contact links in a single-page layout. The current visual direction is adapted from the `open-design` project's `open-design-landing` / Atelier Zero style: warm paper texture, strong editorial typography, side rails, coral accents, and grid-based resume sections.

## Files

- `index.html` - page content and section structure
- `styles/main.css` - responsive visual system and layout
- `js/main.js` - navigation, theme toggle, section reveal, project filtering, scroll progress
- `assets/Rifat.jpg` - profile image

## Run Locally

This is a static site. You can open `index.html` directly, or run a local server:

```bash
python -m http.server 8010 --bind 127.0.0.1
```

Then visit:

```text
http://127.0.0.1:8010/index.html
```

## Deploy

The site can be deployed to any static host such as Cloudflare Pages, GitHub Pages, Netlify, or Vercel. Use the repository root as the publish directory.

## Design Notes

- Keep the palette warm and restrained.
- Avoid generic stock imagery for project cards unless the images are real project screenshots.
- Keep copy specific and grounded; avoid broad template phrases.
- Add new projects as `.project-card` entries with a matching `data-category` for filtering.
