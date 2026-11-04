# Ritesh Singh — Portfolio Website

A responsive, static portfolio built with plain HTML, CSS and JavaScript. No paid backend or database is required.

## Run locally
1. Extract the ZIP.
2. Open `index.html` in a browser.
3. For a local development server, open the folder in VS Code and use the **Live Server** extension, or run `python -m http.server 8000` from this folder and visit `http://localhost:8000`.

## Publish for free

### Option A — GitHub Pages (recommended)
1. Sign in to GitHub and create a **public** repository named `ritesh-portfolio` (or another name).
2. Upload the contents of this folder — `index.html`, `styles.css`, `script.js`, `assets/` and `README.md` — to the repository root. Do not upload only the ZIP.
3. Open the repository **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch **main** and folder **/(root)**, then click **Save**.
6. Wait for the deployment to finish. Your free public URL will look like:
   `https://YOUR-GITHUB-USERNAME.github.io/ritesh-portfolio/`
7. Every time you update files and push/upload them to the `main` branch, GitHub Pages republishes the site.

GitHub Pages provides a free `github.io` subdomain for public repositories on GitHub Free. You do not need to buy a domain or server for this static portfolio.

### Option B — Netlify (also has a free tier)
1. Sign up at Netlify.
2. Choose **Add new site → Deploy manually**.
3. Drag the extracted `ritesh-portfolio` folder (the folder containing `index.html`) into the deploy area.
4. Netlify assigns a free `*.netlify.app` URL. You can change the site name in site settings if the name is available.

## Before publishing — personal checks
- Confirm that the phone number, email, LinkedIn and GitHub links are correct.
- Review the resume PDF in `assets/resume.pdf`.
- Check that you are comfortable making your certificates and resume publicly accessible. Anyone with the site URL can view and download them.
- The Infinite Technologies certificate PDF supplied with the source files could not be read as text, so this site lists the internship based on the resume. Add its certificate image/PDF only after checking it.
- CSRBOX source material describes an AI-powered agricultural insights dashboard concept and tasks. The portfolio labels it as an internship project/concept rather than claiming a finished deployed product.
- The resume mentions IBM SkillsBuild and Infinite Technologies certifications, but their certificate scans were not included as readable images in the supplied set. Upload those scans if you want them displayed in the gallery.

## Editing content
- Main page text and sections: `index.html`
- Colors, layout and responsive styles: `styles.css`
- Mobile menu and footer year: `script.js`
- Images and resume: `assets/`

## Notes
This is a static portfolio. A contact button opens the visitor's email app using a `mailto:` link; it does not store messages in a database. No backend is necessary unless you later want a working contact form, admin panel or dynamic content.
