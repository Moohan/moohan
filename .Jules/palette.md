## 2024-07-25 - Semantic Heading Structure
**Learning:** A logical, sequential heading structure (e.g., h1 -> h2 -> h3) in Markdown and HTML is critical for screen reader accessibility. Starting a document with a single H1 heading provides a clear entry point and allows users of assistive technology to easily understand the document's structure and navigate it effectively.
**Action:** In future reviews of Markdown files or HTML content, I will always check that the document begins with a single H1 and that the heading hierarchy is followed correctly, without skipping levels.

## 2026-01-30 - Accessible Linked Images
**Learning:** For linked images, placing the `title` attribute on the surrounding `<a>` tag rather than the `<img>` tag provides clearer context for the link's destination. The `alt` text should remain on the image to describe its content, while the link's `title` (appearing as a tooltip) should inform the user where the link will take them.
**Action:** When creating or auditing linked images (like social badges or stat cards), ensure the `alt` text describes the image and the `title` attribute is applied to the link and describes the destination.
