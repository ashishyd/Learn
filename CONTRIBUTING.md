
---

### A. Docs Folder (`docs/`)

- **Purpose:** Houses the main documentation.
- **Files to Include:**
    - **index.md:** Acts as the home page or entry point to the documentation. It can provide an overview and link to all relevant parts.
    - **article.md:** The main technical reading article, broken into sections with headings, subheadings, code blocks, and references.
    - **references.md:** A curated list of further readings, bibliographies, links, or cited works.
    - **additional-topics.md:** For supplementary content such as deep dives, FAQs, or case studies.

#### Tips:
- Use clear, hierarchical headings (H1, H2, H3…) for a logical flow.
- Incorporate links and cross-references between files.
- Use Markdown syntax for code blocks, images, links, and lists.

---

### B. Figures Folder (`figures/`)

- **Purpose:** Store images, diagrams, charts, or other visual aids used in your documentation.
- **Structure:**
    - Organize sub-folders (e.g., `diagrams/`, `screenshots/`) if you have many image types.
- **Usage:** Link images in your Markdown files with relative paths to ensure portability across different environments.

#### Example in Markdown:
```markdown
![Architecture Diagram](../figures/diagrams/diagram1.png)
