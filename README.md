# Diggibyte Agentic Journey

This project is a static landing page for the Diggibyte employee upskilling program. It is built with plain HTML and CSS and does not require a build step.

## Project structure

- `index.html` – page structure and content
- `css/styles.css` – all styling and layout rules
- `assets/logo.png` – branding asset used in the header

## Open locally

You can open the page directly in a browser:

- Double-click `index.html`, or
- Run a local web server:

```bash
cd /Users/diggibyte/Documents/projects/presales/LnD
python3 -m http.server 8000
```

Then open http://localhost:8000 in your browser.

## Best practices used

- Separate structure and presentation by keeping HTML and CSS in distinct files.
- Use semantic sections such as `header`, `nav`, `section`, and `footer`.
- Keep colors, spacing, and typography in a CSS variable system (`:root`).
- Use responsive layout rules for smaller screens.
- Maintain a clean asset folder for images and static files.
- Use descriptive class names and organized CSS sections.

## Notes

The design is intentionally simple and maintainable, making it easy to update content, add sections, or reuse the structure for future landing pages.
