# Alireza Karimi — personal academic website

Source for my personal website, served by GitHub Pages.

Plain HTML and CSS: no build step, no dependencies. The only script is the Google Analytics tag (ID `G-DXT0W7WXR1`) in `index.html` and `404.html`.

```
index.html               the whole site (one page)
assets/css/style.css     styles (light and dark mode follow the OS setting)
assets/img/              profile photo and favicon
assets/Alireza_Karimi_CV.pdf
404.html, robots.txt, sitemap.xml, .nojekyll
```

## Updating

- **Content:** edit `index.html`, commit, and push to `main`. GitHub Pages redeploys in about a minute.
- **CV:** replace `assets/Alireza_Karimi_CV.pdf` and keep the same file name, so existing links keep working.
- **Preview locally:** `python3 -m http.server 8000`, then open http://localhost:8000.
- After a significant change, update `Last updated` in the footer and `<lastmod>` in `sitemap.xml`.
