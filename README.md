# Persona Studio — Integrated UI Prototype

Persona Studio is a desktop-first user persona development interface assembled from the supplied Google Stitch screens. The screens share local navigation and retain their original visual designs.

## Screens

- Dashboard (`index.html`)
- Projects (`projects.html`)
- Create Persona (`create-persona.html`)
- Persona Library (`persona-library.html`)
- Research & Insights (`research-insights.html`)
- Compare Personas (`compare-personas.html`)
- Reports & Exports (`reports.html`)
- Settings & Theme (`settings.html`)
- Persona Profile (`persona-profile.html`)
- Sign In (`sign-in.html`)
- Create Account (`create-account.html`)
- Forgot Password (`forgot-password.html`)
- Reset Password (`reset-password.html`)

## Run locally

1. Extract the ZIP.
2. Open the folder in VS Code.
3. Recommended: use the VS Code Live Server extension and open `index.html` with Live Server.
4. Alternatively, open `index.html` directly in a modern browser. Some browser restrictions may affect local file behaviour.

## Current integration scope

- Local page-to-page navigation for the main sidebar.
- Original Stitch HTML and styling retained.
- A small compatibility script provides basic form feedback and reads saved theme values if present.

## Important limitations

This is an integrated **frontend prototype**, not a production backend. Authentication is not secure or connected to an identity provider. User records are not yet backed by a database. CRUD operations, verified PDF/CSV exports, email-based password reset, and fully global theme controls still require implementation and testing. Do not enter real passwords or sensitive research data.

The screens load Tailwind CSS and fonts from external CDNs, so an internet connection is needed for the intended appearance.
