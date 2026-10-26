# Copilot instructions for malak-portfolio

## Project overview

This repository is a lightweight personal portfolio site built as a static HTML project. Keep it simple, fast, and easy to preview without a build step.

## Core conventions

- Prefer plain HTML, CSS, and minimal JavaScript unless a feature clearly requires something else.
- Keep the site accessible and mobile-friendly.
- Favor simple, readable structure over frameworks or heavy tooling.
- Maintain a clean separation between content, presentation, and behavior.
- Use semantic HTML where possible (`header`, `main`, `section`, `footer`, etc.).

## Repository expectations

- The main entry point is `index.html`.
- Static assets should live in clearly named folders such as `assets/`, `css/`, or `js/` when needed.
- Keep files small and readable.
- Prefer incremental improvements over large rewrites.
- If adding new sections, preserve a professional portfolio aesthetic and consistent spacing/typography.

## Working rules for AI-assisted changes

- Do not introduce framework dependencies or a build pipeline for simple page updates.
- Avoid unnecessary libraries, animations, or external dependencies unless explicitly requested.
- Preserve existing content, branding, and user intent when editing.
- When adding text, keep it concise, polished, and relevant to a portfolio.
- If the site is being expanded, maintain a single-page structure unless the user asks for multiple pages.

## Validation

- There is no app build step in this repo by default.
- To preview locally, run:
  - `python3 -m http.server 8000`
  - then open `http://localhost:8000`
- Check that changes render correctly in a browser and do not break the page structure.

## Anti-patterns to avoid

- Do not add a bundler or framework for a single static page.
- Do not create overly complex state management for simple portfolio content.
- Do not break accessibility with low-contrast text, missing labels, or non-semantic markup.
- Do not leave placeholder lorem ipsum, broken links, or empty sections.
- Do not over-engineer the project beyond a polished personal landing page.

## Example prompts

- "Create a clean personal portfolio landing page with hero, about, projects, and contact sections."
- "Add a dark mode toggle with CSS variables and minimal JavaScript."
- "Improve the typography and spacing on the homepage for a more modern design."
- "Add a project card grid with responsive layout and hover effects."
- "Replace placeholder content with my real bio, skills, and contact details."

## Related agent customizations to consider next

- `/create-instruction ...` for a front-end-specific instruction set focused on HTML/CSS polish and accessibility.
- `/create-prompt ...` for reusable prompts like “build a portfolio homepage” or “add a contact section.”
- `/create-skill ...` for a reusable portfolio design skill covering hero layout, responsive cards, and CTA styling.

These customizations would help future work stay consistent with the project’s lightweight static-site approach while speeding up common portfolio updates.
