# cristobalbozdogan.com — static replica

A static HTML/CSS replica of [cristobalbozdogan.com](https://cristobalbozdogan.com), built from the live site's pages and blog posts.

## Structure

- `index.html` — home page (hero, The Strategy, Industry Insights & Thoughts, resume CTA)
- `blog/index.html` — blog index with all 11 posts
- `resume/index.html` — resume / CV page
- `post/<slug>/index.html` — one page per blog post
- `assets/style.css` — shared stylesheet

## Run locally

Open `index.html` in a browser, or serve the folder with any static server, e.g.:

```
python3 -m http.server 8000
```

then visit http://localhost:8000

## Deploy

Deployed on Netlify from this repository's `main` branch (publish directory: repo root).
