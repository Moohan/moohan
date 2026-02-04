## 2024-07-22 - Semantic Heading Structure

**Learning:** A logical and sequential heading structure (e.g., `h1` -> `h2` -> `h3`) is not just for visual hierarchy, but is critical for screen reader users to navigate and understand the content of a page. Skipping heading levels can be confusing and disrupt the user's mental model of the document.

**Action:** When working with Markdown or HTML, always ensure the heading levels are sequential and logically structured. Do not skip levels for stylistic reasons.

## 2026-02-04 - Markdown Link Tooltip Placement

**Learning:** When wrapping an image in a link in Markdown, placing the `title` attribute on the link part (`[![alt](img_url)](link_url "title")`) rather than the image part (`![alt](img_url "title")`) ensures that the tooltip correctly describes the link's destination, providing better context for both visual and screen reader users.

**Action:** Always prefer placing descriptive tooltips on the outer link element when using linked images in Markdown.
