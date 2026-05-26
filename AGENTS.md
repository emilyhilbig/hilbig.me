# AGENTS.md

## Project
This is Emily Hilbig's personal GitHub Pages website.

## Structure
- `index.html` is the main page.
- `css/website.css` contains the custom styling.
- `css/reset.css` is the CSS reset.
- `images/` contains public image assets.
- `EmilyHilbigResume.pdf` is the linked resume.
- `CNAME` configures the custom domain.

## Local Preview
Open `index.html` directly in a browser, or run:

```sh
python3 -m http.server 8000
```

Then visit `http://localhost:8000/`.

## Guidelines
- Keep the site static and GitHub Pages-compatible.
- Preserve `CNAME`.
- Keep the resume link working.
- Compress large photo assets before referencing them.
- Do not commit `.DS_Store`.
- Avoid adding build tooling unless explicitly requested.
