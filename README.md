# Work of Human Hands (reading site)

Static site with the full text of Rev. Anthony Cekada's *Work of Human Hands:
A Theological Critique of the Mass of Paul VI* (2nd ed., SGG Resources, 2015),
a table of contents, client-side search over book.json, and light/dark themes.

## Deploy on Render
1. Push this folder to a GitHub repository.
2. On render.com: New +, Static Site, connect the repo.
3. Build command: (empty). Publish directory: `.`
4. The site will be available at workofhumanhands.onrender.com (set the name
   of the service to `workofhumanhands`).

The included render.yaml preconfigures the SPA rewrite. No server code; the
site is fully static (index.html + book.json).
