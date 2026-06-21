# HTML Elements Directory

---

## 1. Text Layout & Headings
These tags are used to structure text content, manage headings, and control text spacing on a webpage.

- `<h1>` to `<h6>` – Heading tags used to define titles on a page. `<h1>` represents the most important/largest heading, while `<h6>` is the smallest.
    <details>
    <summary>View Allowed Attributes</summary>

    * **Global Attributes:** (Applicable to all headings)
    * `id`, `class`, `style`, `title`, `hidden`, `dir`, `lang`, `data-*`
    * **Tag-Specific Attributes:**
    * *None* (Headings rely strictly on Global attributes for styling and scripting).
    </details>

---

- `<p>` – Paragraph tag. It automatically adds vertical blank space before and after your block of text.
    <details>
    <summary>View Allowed Attributes</summary>

    * **Global Attributes:** (Applicable to paragraphs)
    * `id`, `class`, `style`, `title`, `hidden`, `dir`, `lang`, `data-*`
    * **Tag-Specific Attributes:**
    * *None* (Modern HTML5 handles paragraph alignment purely via CSS classes/styles).
    </details>

---

- `<span>` – An inline text container. Used to wrap a specific part of a text to style it differently without breaking onto a new line.
    <details>
    <summary>View Allowed Attributes</summary>

    * **Global Attributes:** (Crucial for `<span>` since it has no default styling)
    * `id` – Extremely common for JavaScript manipulation.
    * `class` – The most common attribute used with span to style inner text blocks via CSS.
    * `style`, `title`, `hidden`, `dir`, `lang`, `data-*`
    * **Tag-Specific Attributes:**
    * *None* (Acts purely as a structural hook for CSS and JS).
    </details>

---

- `<pre>` – Preformatted text. It prints the text exactly as typed inside your code editor, preserving all extra spaces and line breaks.
    <details>
    <summary>View Allowed Attributes</summary>

    * **Global Attributes:** (Applicable to preformatted blocks)
    * `id`, `class`, `style`, `title`, `hidden`, `dir`, `lang`, `data-*`
    * **Tag-Specific Attributes:**
    * *Note:* Older HTML versions used `width`, but it is completely deprecated now. Use CSS rules inside `style` or `class` for layouts.
    </details>