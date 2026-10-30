# Mark Gonzales — Portfolio

A responsive, static personal portfolio built with HTML, CSS, and JavaScript. It can be deployed directly to Vercel without a build step.

## Before publishing
1. Open `index.html`.
2. Replace `your.email@example.com` with your real email address.
3. Add your LinkedIn profile URL, if you have one.
4. Check that every project description and link reflects your actual work.
5. Add a professional photo if you want one; the current design uses a code illustration instead.

## Run locally
Open `index.html` in your browser, or use the Live Server extension in VS Code.

## Deploy to Vercel
### Option A — GitHub (recommended)
1. Create a GitHub repository named `mark-gonzales-portfolio`.
2. Upload `index.html`, `style.css`, `script.js`, and `README.md` to the repository root.
3. Sign in to Vercel with GitHub.
4. Choose **Add New → Project**, then import the portfolio repository.
5. For a static site, leave the framework preset as **Other** and leave build/output settings empty unless Vercel asks otherwise.
6. Click **Deploy**. Vercel will provide a public `*.vercel.app` URL.
7. Whenever you push changes to the connected GitHub repository, Vercel can redeploy the site.

### Option B — Vercel CLI
Install Node.js, then run:
```bash
npm install -g vercel
vercel
```
Follow the prompts in this folder. When ready to publish production changes, run:
```bash
vercel --prod
```

## Notes
- This portfolio is static and does not need a database.
- The LGU Bato, Leyte project links to the GitHub repository provided in the page. Confirm that it is public and the URL is correct before publishing.
