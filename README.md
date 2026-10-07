# HuddleAcademy

Huddle Academy is a static onboarding and training website for restaurant teams using Huddle. It helps new hires, trainers, and managers get oriented quickly with role-based learning paths, a first-shift checklist, and a support channel for common questions.

## What the site includes

- **Home page** with a clear learning path, role-based entry points, and quick navigation
- **Getting Started page** with pre-shift preparation steps and an onboarding process visual
- **Training and Guides page** with role-based instructions for team members, trainers, and managers, including a role progression visual and resource table
- **Practice Checklist page** with a learning cycle visual and simple coaching steps
- **FAQs and Support page** with common questions, email contact, and a demonstration form with a support pathway visual
- **Shared design system** with responsive styling, Huddle purple branding, and accessible components
- **Educational visuals** including SVG graphics that reinforce learning concepts on each page
- **Google Analytics 4** tracking with Measurement ID G-0W5133Y3XS

## CIS300 Requirements met

- ✓ One home page and four content pages
- ✓ Semantic HTML (`<header>`, `<nav>`, `<main>`, `<footer>` on every page)
- ✓ Unique descriptive page titles and meta descriptions
- ✓ One table with 3+ columns, 1 header row, and 3+ data rows (Training and Guides)
- ✓ One working HTML5 `<video>` element (Getting Started)
- ✓ One working `mailto:` email link (Support)
- ✓ One working external link (Huddle website)
- ✓ One on-site form with 4+ meaningful fields and `action="#"` (Support)
- ✓ One external CSS stylesheet (`huddle.css`)
- ✓ Responsive design with mobile styling
- ✓ Accessible form labels, image alt text, and navigation
- ✓ Educational visuals on each content page

## Project structure

```text
.
├── index.html
├── getting-started.html
├── training.html
├── practice.html
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

## Browser and accessibility

- Works on all modern browsers (Chrome, Firefox, Safari, Edge)
- Responsive design for mobile, tablet, and desktop
- Keyboard navigation and screen reader support
- WCAG 2.1 AA contrast and semantic HTML
- Graceful fallbacks for older browsers