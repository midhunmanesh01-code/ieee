# IEEE SB CEC — Landing Page

A clean, lightweight static landing page created for a task assigned by IEEE SB CEC. The project is intentionally minimal: a single HTML file styled with a companion CSS file. It's ideal for demonstrating a simple project landing, event information, or a student portfolio entry without any build tools or dependencies.

## Highlights
- Minimal, dependency-free static site
- Easy to preview locally or deploy (GitHub Pages, Netlify, etc.)
- Ready to extend with images, JavaScript, or additional pages

## Use cases
a project landing for IEEE SB CEC tasks, a simple event page, or a demo for web fundamentals.

## Files
- `index.html` — main page (entry point)
- `style.css` — styles used by the page
- `README.md` — this document

## Features
- Simple, responsive layout (if responsive styles are included)
- Clear separation of structure (`index.html`) and presentation (`style.css`)
- No build step: works by opening `index.html` in any modern browser

## Preview / How to view
1. Double-click `index.html` or open it from your browser's "Open File" menu.
2. To serve locally (recommended for testing relative asset paths), run a simple HTTP server. For example, using Python 3:

```bash
python -m http.server 8000
# then open http://localhost:8000 in your browser
```

## Development & Extending
- Add JavaScript by creating a `script.js` and including it in `index.html`.
- Add images in an `assets/` or `images/` folder and reference them with relative paths.
- For multiple pages, copy `index.html` to additional HTML files and update the navigation links.

## Deployment
- Deploy to GitHub Pages by pushing this folder to a repository and enabling Pages in the repository settings.
- Or use static-hosting services like Netlify or Vercel (drop folder or connect the repo).

## Project structure
- `index.html` — entry point
- `style.css` — main stylesheet
- `README.md` — project description (this file)

## About the author
Midhun Manesh -- A student member of IEEE SB CEC with an interest in web development, UX design, and lightweight static sites. This project showcases a minimal landing page template useful for demos and small events. 

## Credits
- Created for a web development task assigned by IEEE SB CEC.

## License
- © IEEE SB CEC
---
