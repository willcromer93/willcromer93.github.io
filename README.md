# willcromer93.github.io

Personal portfolio: plain HTML + CSS with no build step.

```
index.html        About / home
data-viz.html     Data Visualization Mini Projects
sports-hub.html   Sports Hub build write-up
assets/style.css  Shared styles (light + dark mode)
assets/headshot.jpg
```

## Adding a project
1. Copy `sports-hub.html` to `new-project.html` and edit the content.
2. Add a `<li>` nav link to the `<nav>` in **every** page.
3. Copy one `<a class="card">` block in `index.html` → `#projects` and point it at the new page.
4. `git add . && git commit -m "Add new project" && git push`
