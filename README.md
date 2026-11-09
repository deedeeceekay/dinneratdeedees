# Dinner at Dee Dee's

Static site for dinneratdeedees.com. Plain HTML and CSS, no build step.

## Run locally
Open `index.html` in a browser, or run `python3 -m http.server` in this folder and go to http://localhost:8000.

## Deploy
- **GitHub Pages:** push to GitHub, then Settings > Pages > deploy from the `main` branch, root folder.
- **Vercel or Netlify:** import the repo, no build command, output folder is the root.

Then point your domain's DNS at the host (the host shows the records to add).

## Still to do
- Home hero background video: currently a labelled placeholder.
- Contact forms: the Send buttons aren't wired up yet. Connect them to Formspree or similar, or use a mailto link.
