## 2024-07-25 - Semantic Heading Structure
**Learning:** A logical, sequential heading structure (e.g., h1 -> h2 -> h3) in Markdown and HTML is critical for screen reader accessibility. Starting a document with a single H1 heading provides a clear entry point and allows users of assistive technology to easily understand the document's structure and navigate it effectively.
**Action:** In future reviews of Markdown files or HTML content, I will always check that the document begins with a single H1 and that the heading hierarchy is followed correctly, without skipping levels.

## 2024-08-14 - Linked Image Accessibility and Context
**Learning:** When an image is wrapped in a link in Markdown, placing the `title` attribute on the link instead of the image ensures the tooltip describes the destination rather than the image content. Additionally, adding explicit text like "(deprecated)" next to visual indicators like strikethrough ensures screen reader accessibility.
**Action:** Always move title attributes to the anchor tag in Markdown `[![alt](img)](url "title")` and provide explicit textual fallback for visual-only styles.
