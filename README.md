# Portfolio Ega Septian — GitHub Pages

Single-page portfolio for **Ega Septian** (Software Development Engineer in Test), ready to publish on GitHub Pages.

## Run locally

```bash
# From project folder
python3 -m http.server 8080
```

Then open in your browser: **http://localhost:8080**

## Deploy to GitHub Pages

1. Create a new repo on GitHub (e.g. `username.github.io` for a user site, or any repo for a project site).
2. Push this project to that repo.
3. On GitHub: **Settings → Pages** → Source: **Deploy from a branch**.
4. Branch: `main` (or `master`), folder **/ (root)**.
5. Save. After the build, the site will be available at:
   - User/org site: `https://username.github.io`
   - Project site: `https://username.github.io/repo-name`

## Portfolio contents

- **Hero**: name, role, tagline, Download CV & Contact buttons
- **About**: QA/SDET experience summary
- **Skills**: automation (Playwright, WebdriverIO, Robot Framework), languages, API, CI/CD
- **Experience**: timeline — Lion Parcel, ICHIGO, Moladin, The FIT Company, OCBC NISP
- **Education**: Gunadarma University, Java & Kotlin/Android certifications
- **Contact**: email, phone, location, LinkedIn

The file `CV - Ega Septian.pdf` in this folder is used as the **Download CV** link in the portfolio.
