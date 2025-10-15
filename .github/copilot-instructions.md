# Copilot Instructions for Adiogoman.github.io

## Project Overview
This is a static website for Al duqum International Overseas Group. The codebase consists of HTML files for different pages (`index.html`, `about.html`, `contact.html`, `services.html`), a single CSS file (`style.css`), and a minimal README. There are no build scripts, frameworks, or external dependencies.

## Architecture & Structure
- All content is static and served directly as HTML/CSS.
- Each HTML file represents a separate page; navigation is handled via standard anchor tags.
- Styling is centralized in `style.css`.
- No JavaScript, backend, or dynamic data flows are present.

## Developer Workflows
- **Editing:** Directly modify HTML and CSS files. No compilation or build steps required.
- **Previewing:** Open HTML files in a browser to view changes. No local server is needed.
- **Adding Pages:** Duplicate an existing HTML file, update content and navigation links.
- **Styling:** Add or update CSS rules in `style.css`.

## Project-Specific Conventions
- Keep navigation menus consistent across all HTML files.
- Use semantic HTML tags for structure (e.g., `<header>`, `<nav>`, `<main>`, `<footer>`).
- Place all custom styles in `style.css`; avoid inline styles.
- Maintain a simple, readable layout—no complex CSS frameworks.

## Integration Points
- No external libraries or APIs are integrated.
- All assets (if any) should be placed in a dedicated folder (e.g., `assets/`), though none exist yet.

## Examples
- To add a new service page:
  1. Copy `services.html` to `new-service.html`.
  2. Update the content and navigation links in all HTML files.
  3. Add any new styles to `style.css`.

## Key Files
- `index.html`: Main landing page.
- `about.html`, `contact.html`, `services.html`: Other site pages.
- `style.css`: Central stylesheet.
- `README.md`: Project summary.

---
For questions or unclear conventions, ask the user for clarification or examples from existing files.
