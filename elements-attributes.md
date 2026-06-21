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

- `<p>` – Paragraph tag. It automatically adds vertical blank space before and after your block of text.
    <details>
    <summary>View Allowed Attributes</summary>

    * **Global Attributes:** (Applicable to paragraphs)
        * `id`, `class`, `style`, `title`, `hidden`, `dir`, `lang`, `data-*`
    * **Tag-Specific Attributes:**
        * *None* (Modern HTML5 handles paragraph alignment purely via CSS classes/styles).
    </details>

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

- `<pre>` – Preformatted text. It prints the text exactly as typed inside your code editor, preserving all extra spaces and line breaks.
    <details>
    <summary>View Allowed Attributes</summary>

    * **Global Attributes:** (Applicable to preformatted blocks)
        * `id`, `class`, `style`, `title`, `hidden`, `dir`, `lang`, `data-*`
    * **Tag-Specific Attributes:**
        * *Note:* Older HTML versions used `width`, but it is completely deprecated now. Use CSS rules inside `style` or `class` for layouts.
    </details>

---

## 2. Text Formatting (Inline Styles)
Used to highlight, emphasize, or style specific words or sentences within your text blocks.

- `<strong>` or `<b>` – Used to make text **Bold**.
    <details>
    <summary>View Allowed Attributes</summary>

    * **Global Attributes:**
        * `id`, `class`, `style`, `title`, `hidden`, `dir`, `lang`, `data-*`
    * **Tag-Specific Attributes:**
        * *None*
    </details>

- `<em>` or `<i>` – Used to make text *Italic*.
    <details>
    <summary>View Allowed Attributes</summary>

    * **Global Attributes:**
        * `id`, `class`, `style`, `title`, `hidden`, `dir`, `lang`, `data-*`
    * **Tag-Specific Attributes:**
        * *None*
    </details>

- `<u>` – Adds a solid underline underneath a specific piece of text.
    <details>
    <summary>View Allowed Attributes</summary>

    * **Global Attributes:**
        * `id`, `class`, `style`, `title`, `hidden`, `dir`, `lang`, `data-*`
    * **Tag-Specific Attributes:**
        * *None*
    </details>

- `<mark>` – Highlights the text with a bright yellow background color.
    <details>
    <summary>View Allowed Attributes</summary>

    * **Global Attributes:**
        * `id`, `class`, `style`, `title`, `hidden`, `dir`, `lang`, `data-*`
    * **Tag-Specific Attributes:**
        * *None*
    </details>

- `<sub>` – Subscript text. It pushes characters slightly downward.
    <details>
    <summary>View Allowed Attributes</summary>

    * **Global Attributes:**
        * `id`, `class`, `style`, `title`, `hidden`, `dir`, `lang`, `data-*`
    * **Tag-Specific Attributes:**
        * *None*
    </details>

- `<sup>` – Superscript text. It pushes characters slightly upward.
    <details>
    <summary>View Allowed Attributes</summary>

    * **Global Attributes:**
        * `id`, `class`, `style`, `title`, `hidden`, `dir`, `lang`, `data-*`
    * **Tag-Specific Attributes:**
        * *None*
    </details>

- `<del>` – Strikethrough text. Draws a horizontal line right through the center.
    <details>
    <summary>View Allowed Attributes</summary>

    * **Global Attributes:**
        * `id`, `class`, `style`, `title`, `hidden`, `dir`, `lang`, `data-*`
    * **Tag-Specific Attributes:**
        * `cite` – A URL pointing to a document explaining why the text was deleted.
        * `datetime` – Specifies the exact date and time when the text was removed.
    </details>

---

## 3. Structural & Semantic Layout Elements
The core block-level elements used to divide and organize a webpage into standard layout sections. All these semantic layout tags rely strictly on structural architecture and CSS, meaning they share the same attribute rules.

- `<div>` – A generic block-level division container.
    <details>
    <summary>View Allowed Attributes</summary>

    * **Global Attributes:** (Crucial for styling layout blocks)
        * `id`, `class`, `style`, `title`, `hidden`, `dir`, `lang`, `data-*`
    * **Tag-Specific Attributes:**
        * *None*
    </details>

- `<header>` – Represents the top introduction section.
    <details>
    <summary>View Allowed Attributes</summary>

    * **Global Attributes:**
        * `id`, `class`, `style`, `title`, `hidden`, `dir`, `lang`, `data-*`
    * **Tag-Specific Attributes:**
        * *None*
    </details>

- `<nav>` – Navigation block reserved for menus.
    <details>
    <summary>View Allowed Attributes</summary>

    * **Global Attributes:**
        * `id`, `class`, `style`, `title`, `hidden`, `dir`, `lang`, `data-*`
    * **Tag-Specific Attributes:**
        * *None*
    </details>

- `<main>` – Wraps the dominant unique content of the page.
    <details>
    <summary>View Allowed Attributes</summary>

    * **Global Attributes:**
        * `id`, `class`, `style`, `title`, `hidden`, `dir`, `lang`, `data-*`
    * **Tag-Specific Attributes:**
        * *None*
    </details>

- `<section>` – Groups related content or themes together.
    <details>
    <summary>View Allowed Attributes</summary>

    * **Global Attributes:**
        * `id`, `class`, `style`, `title`, `hidden`, `dir`, `lang`, `data-*`
    * **Tag-Specific Attributes:**
        * *None*
    </details>

- `<article>` – A self-contained, independent piece of content.
    <details>
    <summary>View Allowed Attributes</summary>

    * **Global Attributes:**
        * `id`, `class`, `style`, `title`, `hidden`, `dir`, `lang`, `data-*`
    * **Tag-Specific Attributes:**
        * *None*
    </details>

- `<aside>` – Sidebar content indirectly related to the page.
    <details>
    <summary>View Allowed Attributes</summary>

    * **Global Attributes:**
        * `id`, `class`, `style`, `title`, `hidden`, `dir`, `lang`, `data-*`
    * **Tag-Specific Attributes:**
        * *None*
    </details>

- `<footer>` – Represents the bottom-most section of your page layout.
    <details>
    <summary>View Allowed Attributes</summary>

    * **Global Attributes:**
        * `id`, `class`, `style`, `title`, `hidden`, `dir`, `lang`, `data-*`
    * **Tag-Specific Attributes:**
        * *None*
    </details>

---

## 4. Media & Hyperlinks
Tags used to integrate external resources, media playback, and web connections. These tags carry highly critical specific attributes.

- `<a>` – Anchor tag used to create clickable hyperlinks.
    <details>
    <summary>View Allowed Attributes</summary>

    * **Global Attributes:**
        * `id`, `class`, `style`, `title`, `hidden`, `dir`, `lang`, `data-*`
    * **Tag-Specific Attributes:**
        * `href` – The destination URL or file path the link points to.
        * `target` – Where to open the link (e.g., `_blank` opens it in a brand new tab).
        * `download` – Prompts the browser to download the linked file instead of opening it.
        * `rel` – Specifies the relationship with the linked page (e.g., `noopener` for safety with `_blank`).
    </details>

- `<img>` – A stand-alone tag used to render images on the screen.
    <details>
    <summary>View Allowed Attributes</summary>

    * **Global Attributes:**
        * `id`, `class`, `style`, `title`, `hidden`, `dir`, `lang`, `data-*`
    * **Tag-Specific Attributes:**
        * `src` – The relative path or web URL link of your image file.
        * `alt` – Alternative text to display if the image breaks or for screen readers.
        * `width` & `height` – Overrides structural image sizes in pixels or percentages.
        * `loading` – Controls performance loading mechanics (e.g., `lazy` delays loading off-screen images).
    </details>

- `<audio>` – Embeds an audio player directly onto the layout.
    <details>
    <summary>View Allowed Attributes</summary>

    * **Global Attributes:**
        * `id`, `class`, `style`, `title`, `hidden`, `dir`, `lang`, `data-*`
    * **Tag-Specific Attributes:**
        * `src` – The file path link to the audio file.
        * `controls` – Adds native play, pause, and volume UI controls to the page.
        * `autoplay` – Starts playing the audio file instantly when the page loads.
        * `loop` – Restarts the track automatically once it ends.
        * `muted` – Mutes the audio track by default.
    </details>

- `<video>` – Embeds a native video player directly onto the layout.
    <details>
    <summary>View Allowed Attributes</summary>

    * **Global Attributes:**
        * `id`, `class`, `style`, `title`, `hidden`, `dir`, `lang`, `data-*`
    * **Tag-Specific Attributes:**
        * `src` – The path link to the video file.
        * `controls` – Shows the standard play, pause, timeline, and volume buttons.
        * `autoplay` – Starts the video instantly when the page loads (requires `muted` to trigger on most browsers).
        * `loop` – Plays the video on repeat indefinitely.
        * `muted` – Forces the video to be silent by default.
        * `poster` – A URL pointing to an image placeholder to show before the video plays.
        * `width` & `height` – Explicit structural sizing dimensions.
    </details>

- `<iframe>` – Inline Frame. Loads an external webpage inside a window.
    <details>
    <summary>View Allowed Attributes</summary>

    * **Global Attributes:**
        * `id`, `class`, `style`, `title`, `hidden`, `dir`, `lang`, `data-*`
    * **Tag-Specific Attributes:**
        * `src` – The complete URL address of the embedded webpage.
        * `width` & `height` – Sizing dimensions for the interactive frame window.
        * `loading` – Can be set to `lazy` for performance optimization.
        * `sandbox` – Imposes high-security restrictions on the embedded content.
    </details>

---

## 5. Lists (Ordered & Unordered)
Used to showcase multiple items systematically in a clean sequence.

- `<ul>` – Unordered List. Groups items into a standard bulleted list.
    <details>
    <summary>View Allowed Attributes</summary>

    * **Global Attributes:**
        * `id`, `class`, `style`, `title`, `hidden`, `dir`, `lang`, `data-*`
    * **Tag-Specific Attributes:**
        * *None* (List bullet designs like circles or squares are configured in CSS).
    </details>

- `<ol>` – Ordered List. Groups items into a sequential numbered list block.
    <details>
    <summary>View Allowed Attributes</summary>

    * **Global Attributes:**
        * `id`, `class`, `style`, `title`, `hidden`, `dir`, `lang`, `data-*`
    * **Tag-Specific Attributes:**
        * `type` – Sets the numbering type: `1` (numbers), `a` (lowercase letters), `A` (uppercase letters), `i` (lowercase Roman numerals), or `I` (uppercase Roman numerals).
        * `start` – Defines the specific starting integer value of your list (e.g., `start="5"` makes it start from 5).
        * `reversed` – Swaps the list numbering to countdown in descending order.
    </details>

- `<li>` – List Item. The actual single line item that must sit inside a parent list.
    <details>
    <summary>View Allowed Attributes</summary>

    * **Global Attributes:**
        * `id`, `class`, `style`, `title`, `hidden`, `dir`, `lang`, `data-*`
    * **Tag-Specific Attributes:**
        * `value` – Only applicable inside an `<ol>` parent tag. It changes the sequence rank number of that specific line item and shifts succeeding points relative to it.
    </details>

---

## 6. Forms & User Inputs
Used to build interactive fields, capture user data, and handle submissions.

- `<form>` – The master data collection container.
    <details>
    <summary>View Allowed Attributes</summary>

    * **Global Attributes:**
        * `id`, `class`, `style`, `title`, `hidden`, `dir`, `lang`, `data-*`
    * **Tag-Specific Attributes:**
        * `action` – The backend API endpoint URL where the form data goes upon submission.
        * `method` – The HTTP protocol used to transfer data (`get` reveals data in URL, `post` hides data securely inside body payload).
        * `target` – Where to show the response page after form validation completes (e.g., `_blank`).
    </details>

- `<input>` – A stand-alone element that acts based entirely on its structural type.
    <details>
    <summary>View Allowed Attributes</summary>

    * **Global Attributes:**
        * `id`, `class`, `style`, `title`, `hidden`, `dir`, `lang`, `data-*`
    * **Tag-Specific Attributes:**
        * `type` – Critical configuration setting: `text`, `password`, `email`, `number`, `checkbox`, `radio`, `submit`, `file`.
        * `name` – Set identity name key sent along to the backend servers during form submission.
        * `value` – Specifies the default or programmatic text data mapped inside the field.
        * `placeholder` – Displays faint inline guide text which vanishes when user typing triggers.
        * `required` – A true boolean tag option blocking form submission unless this field contains data.
        * `disabled` – Locks down the field to prevent the user from typing or interacting with it.
        * `min` & `max` – Enforces specific numeric value floor and ceiling rules.
    </details>

- `<label>` – Provides a readable text caption attached to an input field.
    <details>
    <summary>View Allowed Attributes</summary>

    * **Global Attributes:**
        * `id`, `class`, `style`, `title`, `hidden`, `dir`, `lang`, `data-*`
    * **Tag-Specific Attributes:**
        * `for` – Must match the exact `id` string attribute of an adjacent input element to cleanly bind them together natively.
    </details>

- `<textarea>` – Creates a large, multi-line expandable text input box.
    <details>
    <summary>View Allowed Attributes</summary>

    * **Global Attributes:**
        * `id`, `class`, `style`, `title`, `hidden`, `dir`, `lang`, `data-*`
    * **Tag-Specific Attributes:**
        * `name`, `placeholder`, `required`, `disabled` – Identical properties to text inputs.
        * `rows` – Sets the specific visual height capacity layout counted in line heights.
        * `cols` – Sets the specific structural width counted in text character sizing widths.
    </details>

- `<select>` – Creates a standard dropdown menu container.
    <details>
    <summary>View Allowed Attributes</summary>

    * **Global Attributes:**
        * `id`, `class`, `style`, `title`, `hidden`, `dir`, `lang`, `data-*`
    * **Tag-Specific Attributes:**
        * `name` – The data identity key for the selection block.
        * `required` & `disabled` – Controls input flow operations.
        * `multiple` – Allows the user to select more than one option from the dropdown block simultaneously.
    </details>

- `<option>` – Defines an individual selectable item inside a drop-down menu.
    <details>
    <summary>View Allowed Attributes</summary>

    * **Global Attributes:**
        * `id`, `class`, `style`, `title`, `hidden`, `dir`, `lang`, `data-*`
    * **Tag-Specific Attributes:**
        * `value` – The actual text value data sent to the database servers if this item is selected.
        * `selected` – Forces this specific list item selection option to be open and pre-filled by default.
        * `disabled` – Grays out the text item preventing user selection.
    </details>

- `<button>` – Creates a clickable interface button.
    <details>
    <summary>View Allowed Attributes</summary>

    * **Global Attributes:**
        * `id`, `class`, `style`, `title`, `hidden`, `dir`, `lang`, `data-*`
    * **Tag-Specific Attributes:**
        * `type` – Governs its behavior: `submit` (transmits form data blocks), `reset` (wipes form values cleanly), or `button` (blank click listener for JavaScript logic).
        * `name` & `value` – Identifiers sent to backend handlers if clicked.
        * `disabled` – Freezes functionality completely.
    </details>

---

## 7. Table Elements
Used to display structured, grid-based data in rows and columns.

- `<table>` – The master container tag that wraps a complete data table layout.
    <details>
    <summary>View Allowed Attributes</summary>

    * **Global Attributes:**
        * `id`, `class`, `style`, `title`, `hidden`, `dir`, `lang`, `data-*`
    * **Tag-Specific Attributes:**
        * *Note:* Older layout attributes like `border`, `cellpadding`, and `cellspacing` are completely deprecated in HTML5. Use CSS styling properties instead.
    </details>

- `<tr>` – Table Row. Creates a horizontal row container for table cells.
    <details>
    <summary>View Allowed Attributes</summary>

    * **Global Attributes:**
        * `id`, `class`, `style`, `title`, `hidden`, `dir`, `lang`, `data-*`
    * **Tag-Specific Attributes:**
        * *None* (Row alignments are handled via CSS).
    </details>

- `<th>` – Table Header. Creates a bold, centered heading cell at the top of a column or row.
    <details>
    <summary>View Allowed Attributes</summary>

    * **Global Attributes:**
        * `id`, `class`, `style`, `title`, `hidden`, `dir`, `lang`, `data-*`
    * **Tag-Specific Attributes:**
        * `colspan` – Specifies the number of columns a single header cell should stretch across horizontally.
        * `rowspan` – Specifies the number of rows a single header cell should stretch across vertically.
        * `scope` – Defines whether the header cell is for a column (`col`), row (`row`), column group (`colgroup`), or row group (`rowgroup`).
    </details>

- `<td>` – Table Data. Creates a standard individual cell to hold regular content inside a row.
    <details>
    <summary>View Allowed Attributes</summary>

    * **Global Attributes:**
        * `id`, `class`, `style`, `title`, `hidden`, `dir`, `lang`, `data-*`
    * **Tag-Specific Attributes:**
        * `colspan` – Specifies the number of columns the data cell should span across horizontally.
        * `rowspan` – Specifies the number of rows the data cell should span across vertically.
    </details>

- `<thead>` – Groups the header content at the very top of a table.
    <details>
    <summary>View Allowed Attributes</summary>

    * **Global Attributes:**
        * `id`, `class`, `style`, `title`, `hidden`, `dir`, `lang`, `data-*`
    * **Tag-Specific Attributes:**
        * *None*
    </details>

- `<tbody>` – Groups the primary body data rows of the table.
    <details>
    <summary>View Allowed Attributes</summary>

    * **Global Attributes:**
        * `id`, `class`, `style`, `title`, `hidden`, `dir`, `lang`, `data-*`
    * **Tag-Specific Attributes:**
        * *None*
    </details>

- `<tfoot>` – Groups the summary or total rows at the very bottom of the table.
    <details>
    <summary>View Allowed Attributes</summary>

    * **Global Attributes:**
        * `id`, `class`, `style`, `title`, `hidden`, `dir`, `lang`, `data-*`
    * **Tag-Specific Attributes:**
        * *None*
    </details>

---

## 8. Document Metadata (Head Section Tags)
These tags sit exclusively inside the `<head>` tag and provide background data to the browser, not directly visible on the page layout.

- `<title>` – Sets the text displayed on the browser tab for that specific webpage.
    <details>
    <summary>View Allowed Attributes</summary>

    * **Global Attributes:** (Rarely used here, but technically valid)
        * `id`, `dir`, `lang`
    * **Tag-Specific Attributes:**
        * *None*
    </details>

- `<meta>` – A stand-alone tag used to specify character encodings, page descriptions, keywords, and author details for SEO.
    <details>
    <summary>View Allowed Attributes</summary>

    * **Global Attributes:**
        * `id`, `class`, `style`, `title`, `hidden`
    * **Tag-Specific Attributes:**
        * `charset` – Declares the character encoding for the document (almost always `charset="UTF-8"`).
        * `name` – Defines the type of metadata being specified (e.g., `viewport`, `description`, `keywords`, `author`).
        * `content` – Gives the actual value associated with the `name` or `http-equiv` attribute.
        * `http-equiv` – Provides an HTTP header equivalent for the information value (e.g., `refresh`, `content-type`).
    </details>

- `<link>` – A stand-alone tag used to link external resources, most commonly used to attach CSS stylesheets.
    <details>
    <summary>View Allowed Attributes</summary>

    * **Global Attributes:**
        * `id`, `class`, `style`, `title`, `hidden`
    * **Tag-Specific Attributes:**
        * `href` – The URL path to the external resource file you are linking.
        * `rel` – Required option defining the relationship with the current document (e.g., `rel="stylesheet"` or `rel="icon"`).
        * `type` – Specifies the exact MIME type of the linked file (e.g., `text/css`).
        * `media` – Defines which device type or media query rule the linked document applies to (e.g., `screen` or `print`).
    </details>

- `<style>` – Allows you to write raw internal CSS rules directly inside the HTML document.
    <details>
    <summary>View Allowed Attributes</summary>

    * **Global Attributes:**
        * `id`, `class`, `title`, `dir`, `lang`
    * **Tag-Specific Attributes:**
        * `media` – Specifies which device target rules the styling blocks should deploy against (e.g., `print`).
    </details>

- `<script>` – Used to embed or point to an external JavaScript file to add interactivity to your page.
    <details>
    <summary>View Allowed Attributes</summary>

    * **Global Attributes:**
        * `id`, `class`, `style`, `title`, `hidden`, `data-*`
    * **Tag-Specific Attributes:**
        * `src` – The relative or absolute path URL to an external script file.
        * `async` – A boolean flag enabling the script to execute asynchronously while the browser parses the HTML layout.
        * `defer` – A boolean flag forcing the script to only execute after the structural HTML document parsing finishes completely.
        * `type` – Defines the script environment layout (e.g., `type="module"` for modern JavaScript modules).
    </details>

---

## 9. Interactive & Advanced Semantic Elements
Modern structural tags used to handle user-triggered drop-downs or layout highlights.

- `<details>` – Creates an interactive, expandable widget that users can click to open and reveal more hidden content.
    <details>
    <summary>View Allowed Attributes</summary>

    * **Global Attributes:**
        * `id`, `class`, `style`, `title`, `hidden`, `dir`, `lang`, `data-*`
    * **Tag-Specific Attributes:**
        * `open` – A boolean attribute that forces the dropdown widget to stay fully expanded and open by default when the page finishes loading.
    </details>

- `<summary>` – Defines the visible heading or caption that a user clicks on to toggle the `<details>` block open or closed.
    <details>
    <summary>View Allowed Attributes</summary>

    * **Global Attributes:**
        * `id`, `class`, `style`, `title`, `hidden`, `dir`, `lang`, `data-*`
    * **Tag-Specific Attributes:**
        * *None* (Acts strictly as the clickable header hook for `<details>`).
    </details>

- `<figure>` – Encapsulates self-contained media elements like images, diagrams, or code snippets, grouping them together with a caption.
    <details>
    <summary>View Allowed Attributes</summary>

    * **Global Attributes:**
        * `id`, `class`, `style`, `title`, `hidden`, `dir`, `lang`, `data-*`
    * **Tag-Specific Attributes:**
        * *None*
    </details>

- `<figcaption>` – Provides a readable text title or description for its parent `<figure>` element.
    <details>
    <summary>View Allowed Attributes</summary>

    * **Global Attributes:**
        * `id`, `class`, `style`, `title`, `hidden`, `dir`, `lang`, `data-*`
    * **Tag-Specific Attributes:**
        * *None*
    </details>

- `<progress>` – Displays a visual status bar indicating the completion progress of a specific task or download.
    <details>
    <summary>View Allowed Attributes</summary>

    * **Global Attributes:**
        * `id`, `class`, `style`, `title`, `hidden`, `dir`, `lang`, `data-*`
    * **Tag-Specific Attributes:**
        * `value` – Specifies the exact status progress completion value achieved so far.
        * `max` – Establishes the upper numeric benchmark layout bound of the progress bar scale (defaults to 1.0 if not explicitly defined).
    </details>

---