# personal website

A minimal static site in a plain serif style. Two pages: home and CV.
No build step. Published with GitHub Pages at https://brittbesch.github.io

## Files
- `index.html` – home (photo, name, short bio, links)
- `path.html` – CV: education, experience, selected awards
- `styles.css` – styling
- `favicon.svg` – browser-tab icon
- `photo.jpg` – portrait used on the home page

## Preview locally
```bash
python3 -m http.server 8000
```
Then open http://localhost:8000. Double-clicking `index.html` also works.

## Deploying
Pushing to `main` republishes the site. GitHub Pages serves this repo from the
branch root; changes are live within a minute or two.
