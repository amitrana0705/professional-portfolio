# Amit Rana — DevOps Engineer portfolio

Responsive, dependency-free portfolio for GitHub Pages. Built with HTML, CSS and JavaScript.

## Run locally

Open `index.html` in a browser, use VS Code Live Server, or from this folder run:

```bash
python -m http.server 8000
```

Open http://localhost:8000. No Node.js, build step or API keys required.

## Important: verify before publishing

- Overall IT experience is approximately 18 years; **focused DevOps experience is approximately 2–3 years**. Do not conflate the two.
- Previous CV describes the 2019–present role as DevOps Engineer, but recent DevOps work began later. Confirm role titles and the timeline with your employment records.
- Employer/client names and work descriptions come from an earlier CV. Confirm what may be disclosed publicly.
- GH-900 is marked **training in progress**, not an earned certification.
- Projects are **planned demos**, not completed professional projects. Replace status and add repository links when built.
- Review all skills for accuracy and remove anything not personally used.
- Replace LinkedIn and email placeholders in `index.html` with real clickable links.
- Add your own approved resume to `assets/resume/` and link it from the homepage if desired.
- Never commit credentials, secrets, client code or proprietary documents.

## Deploy to existing GitHub repository

Copy the **contents** of this folder into the root of your local `professional-portfolio` clone (not a nested folder). From PowerShell:

```powershell
cd F:\live-projects\professional-portfolio
git status
git add .
git commit -m "Update DevOps portfolio and career positioning"
git push origin main
```

Then open repository Settings → Pages → Deploy from a branch → `main` → `/ (root)` → Save. On GitHub Free, the repository must be public for Pages.

Expected URL: https://amitrana0705.github.io/professional-portfolio/ (after successful deployment).

## Files

- `index.html`: all page copy and sections
- `css/style.css`: navy-blue theme and responsive styling
- `js/script.js`: mobile menu and dynamic copyright year
