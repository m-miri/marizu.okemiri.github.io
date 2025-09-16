# Jekyll + HTML5 UP "Twenty" Scaffold

This repo converts the static "Twenty" template into Jekyll layouts/includes so you get reusable nav/footer, Markdown pages, and a Projects collection.

## What you still need
1) Copy **/assets** and **/images** from the original "Twenty" download into this repo (overwrite folders here).
2) Edit `_config.yml` (title, description, links).
3) Commit and push to GitHub → Settings → Pages → deploy.

## File map
- `_layouts/default.html` and `_layouts/page.html`: page shells
- `_includes/`: head, header, banner, footer, scripts
- `_projects/`: example case studies
- Top-level pages: `index.md`, `about.md`, `projects.md`, `contact.md`

## Deploy
- GitHub Pages → "Deploy from a branch" (main / root).
- Optional custom domain: add a `CNAME` file with your domain.
