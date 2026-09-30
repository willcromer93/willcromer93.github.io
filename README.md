# willcromer93.github.io

Personal portfolio: plain HTML + CSS with no build step.

```
index.html               About / home
data-viz.html            Data Visualization Mini Projects
sports-hub.html          Sports Hub build write-up
mission-control-ai.html  Mission Control VR + AI Agent write-up
404.html                 Custom not-found page (GitHub Pages serves it automatically)
robots.txt, sitemap.xml  Search-engine files; add new pages to the sitemap
assets/style.css         Shared styles (light + dark mode)
assets/*.jpg             Headshot and project images
```

## Adding a project
1. Copy `sports-hub.html` to `new-project.html` and edit the content.
2. Add a `<li>` nav link to the `<nav>` in **every** page.
3. Copy one `<a class="card">` block in `index.html` → `#projects` and point it at the new page.
4. Add the page to `sitemap.xml`, and give it a `<meta name="description">`, canonical link and Open Graph tags like the other pages.
5. `git add . && git commit -m "Add new project" && git push`

## Checklist before publishing
- Every `target="_blank"` link has `rel="noopener"`; no `http://` resources; images have `alt` text.
- Headings don't skip levels (`h1` → `h2` → `h3`).
- Lighthouse (`npx lighthouse <url> --output=json --chrome-flags="--headless"`) scored 98-100 everywhere at last check.
