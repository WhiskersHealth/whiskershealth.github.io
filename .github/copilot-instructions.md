# Copilot Instructions for Whiskers Health Organisation Website

## Project Overview
This is a static website for Whiskers Health Organisation, focused on cat adoption and veterinary resources. The site is built with plain HTML, CSS (Tailwind), and optional JavaScript for interactivity. There is no build system or backend—edits are made directly to HTML files.

## Key Files & Structure
- `index.html`: Main landing page, includes "Cats for Adoption" section. Most updates happen here.
- `adopt.html`, `application.html`, etc.: Other static pages for adoption, emergencies, policies, etc.
- `assets/images/`: Store all local images (cats, team, events). Use descriptive filenames and reference with relative paths.
- `assets/icons/`: Store custom SVG/PNG icons for UI or social media.
- `css/`: For custom CSS overrides or additions. Tailwind is used for most styling.
- `js/`: For custom JavaScript (future features, interactivity).
- `cats/`: Contains templates for individual cat stories.

## Editing Content
- To update cats for adoption, edit the card blocks in `index.html`.
- To add a new cat, copy an existing card block, update details, and add a new image to `assets/images/`.
- To update social sharing previews, edit meta tags in the `<head>` of `index.html` (see README for details).

## Conventions & Patterns
- Use relative paths for images and icons (e.g., `/assets/images/cat1.jpg`).
- Keep HTML semantic and readable; use comments to mark major sections.
- CSS customizations go in `css/custom.css` if needed.
- JavaScript files should be referenced in HTML via `<script src="/js/filename.js"></script>`.
- No build or test workflow—changes are live once HTML/CSS/JS files are updated.

## Integration Points
- No external dependencies except Tailwind (via CDN in HTML).
- No backend or API integration.
- For social sharing, meta tags in HTML control preview appearance on platforms.

## Examples
- Adding a cat: Edit `index.html`, add a card block, upload image to `assets/images/`, update image path.
- Customizing styles: Add rules to `css/custom.css` and link in HTML.
- Adding interactivity: Create a JS file in `js/`, reference in HTML.

## Additional Notes
- For major changes, review comments in `index.html` and the main README.
- No automated deployment—manual updates only.

---
For questions or unclear patterns, review the main README or ask for clarification.
