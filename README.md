# Diggibyte Agentic Journey

This project is a static landing page for the Diggibyte employee upskilling program. It is built with plain HTML and CSS and does not require a build step.

## Project structure

- `index.html` – page structure and content
- `css/styles.css` – all styling and layout rules
- `assets/logo.png` and `assets/logo_dark.png` – branding assets, switched by the theme toggle

## Open locally

You can open the page directly in a browser:

- Double-click `index.html`, or
- Run a local web server:

```bash
cd path/to/this/repo
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

## Program content ownership

The page is the single source of truth for the upskilling program. Before changing any week, track or rubric, check that these stay consistent:

- The impact dimension count in the hero stat matches the number of rows in the impact table.
- Every recognition tier referenced in the copy is defined in the tier table.
- Course links point at catalog entries, not session-scoped enrolment URLs, which expire.
- Product names follow current Databricks naming (Lakeflow, Unity Catalog, Databricks AI Search, Lakebase, Mosaic AI, Agent Bricks, Asset Bundles, Databricks Apps).

## Notes

The design is intentionally simple and maintainable, making it easy to update content, add sections, or reuse the structure for future landing pages.
