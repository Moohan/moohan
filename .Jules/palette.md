## 2024-07-25 - Semantic Heading Structure
**Learning:** A logical, sequential heading structure (e.g., h1 -> h2 -> h3) in Markdown and HTML is critical for screen reader accessibility. Starting a document with a single H1 heading provides a clear entry point and allows users of assistive technology to easily understand the document's structure and navigate it effectively.
**Action:** In future reviews of Markdown files or HTML content, I will always check that the document begins with a single H1 and that the heading hierarchy is followed correctly, without skipping levels.

## 2025-02-02 - Link vs Image Tooltips in Markdown
**Learning:** When an image is wrapped in a link in Markdown, placing the `title` attribute on the link part (`[![alt](img_url)](link_url "title")`) rather than the image part ensures that the tooltip accurately describes the link's destination and provides a better experience for sighted users. It also avoids potential redundancy or confusion when screen readers announce the link and its content separately.
**Action:** Always prefer placing `title` attributes on the link component of linked images to provide clear context on the link's destination.
