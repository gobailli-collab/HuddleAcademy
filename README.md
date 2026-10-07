# HuddleAcademy

Huddle Academy is a static onboarding and training website for restaurant teams using Huddle. It helps new hires, trainers, and managers get oriented quickly with role-based learning paths, a first-shift checklist, and a support channel for common questions.

## What the site includes

- Home page with a clear learning path and entry points
- Getting Started page with pre-shift preparation steps
- Training and Guides page with role-based instructions for team members, trainers, and managers
- FAQs and Support page with common onboarding questions and a support request form
- Shared design system and responsive styling via a single stylesheet

## Project structure

```text
.
├── index.html
├── getting-started.html
├── training.html
├── support.html
├── huddle.css
├── huddle-logo.svg
├── learning-path.svg
├── Social_Logo.svg
├── README.md
└── .github/
    └── workflows/
        └── deploy.yml
```

## Run locally

Because this project is static HTML/CSS, you can open the site directly in a browser or serve it locally:

```bash
# from the project root
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Deploy to GitHub Pages

This repository includes a GitHub Actions workflow for deployment. The workflow publishes the root folder to GitHub Pages automatically when changes are pushed to the default branch.

```bash
git checkout main
git add .
git commit -m "Publish site updates"
git push origin main
```

Then go to:

- Repository settings
- Pages
- Source: GitHub Actions

## Recommended next improvements

1. Replace the demo mailbox in `support.html` with a real support email or form backend.
2. Add more role-specific training modules and downloadable resources.
3. Expand the README with screenshots and trainer documentation as the site grows.
4. Add a content management layer if the academy eventually needs many training modules.

## Notes

This project is currently a front-end prototype for onboarding and training. It is ready for a static hosting environment and can be expanded into a broader training platform with more structured lesson content.
