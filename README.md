# Pratik V. Tanikella — Personal Portfolio

This repository contains a single-page, dark-green themed personal portfolio for Pratik V. Tanikella.

Files
- `index.html` — main site markup and styles
- `img1.jpeg` — hero / face photo (must be present in the same folder)
- `newfav.png` — logo used in the top-left
- `trynew23.avif` — fallback image used in some places

Preview Locally
1. Open the site directly in a browser: double-click `index.html`.
2. Or run a simple local server from the project folder (recommended):

```bash
# Python 3 (works on macOS/Linux/Windows with Python installed)
python3 -m http.server 8000
# then open http://localhost:8000 in your browser
```

Quick edits
- To change the hero photo, replace `img1.jpeg` with your photo (same filename) or update the `src` in `index.html`.
- To change the logo, replace `newfav.png` (or update `src` in `index.html`).
- Styling lives inline in `index.html` in the `<style>` block — small, focused edits are simple there.

Deploying (options)

1) GitHub Pages (static, free)
- Create a GitHub repo and push this folder to the repository root.
- In the repo settings → Pages, select the `main` branch (or `gh-pages`) and root folder.
- Optionally add a `CNAME` file with your custom domain and add DNS records at your registrar.

Commands to push (example):
```bash
git init
git add .
git commit -m "Initial portfolio"
git branch -M main
# create repo on GitHub and follow instructions to add remote
git remote add origin https://github.com/<your-username>/<repo>.git
git push -u origin main
```

2) Netlify (recommended for easy custom domain + HTTPS)
- Create a Netlify account and either drag-and-drop the site folder to Netlify's deploy UI or connect the GitHub repo.
- Configure your custom domain in Netlify and follow their DNS verification instructions.

3) Vercel
- Connect the GitHub repo to Vercel and deploy. Add a custom domain via Vercel's dashboard and follow DNS steps.

4) FTP / SFTP
- Upload the build files to your hosting provider's `public_html` (or appropriate) folder and point your domain to that host.

Custom Domain & DNS
- After buying a domain, add an `A` record (or CNAME) per provider instructions.
  - GitHub Pages: use `A` records or a `CNAME` file; check GitHub Pages docs.
  - Netlify/Vercel: typically a CNAME to the provider record or Netlify/Vercel will provide exact records to add.

Notes & Next Steps I can help with
- Create a GitHub repo and push this site for you (I can provide commands or push if you provide access).
- I can deploy to Netlify/Vercel and configure your domain (you can update DNS or give access to change it).
- Create a downloadable resume PDF and link it on the site.

If you want me to deploy the site, tell me which provider you prefer and whether you'll share repo access or prefer step-by-step commands you run locally.
