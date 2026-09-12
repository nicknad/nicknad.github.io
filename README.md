# nicknad.github.io

Personal website for Nick Nadolski, published with GitHub Pages at
https://nicknad.github.io.

## Pages

| File | Purpose |
| --- | --- |
| `index.html` | Home: intro, experience, education, selected projects |
| `projects.html` | All public GitHub projects |
| `blogs.html` | Blog index |
| `blog/*.html` | Individual blog posts |
| `css/style.css` | Site styles (light and dark via `prefers-color-scheme`) |
| `js/main.js` | Footer year |

## Adding a blog post

1. Copy an existing post in `blog/` and rename the file.
2. Update the title, meta description, date, and content.
3. Add an entry to the list in `blogs.html`.

There is no build step: plain HTML, CSS, and a few lines of JavaScript.

## Preview locally

Open `index.html` in a browser, or serve the directory:

```
python -m http.server
```
