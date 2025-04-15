### HTML Structure Basics

1. `<!DOCTYPE html>` – Defines the document type

2. `<html>`: The root of an HTML document
3. `<head>`: Contains metadata like title and links (e.g. Link to a CSS Stylesheet)
4. `<title>`: Sets the page title (appears in the browser tab)
5. `<body>`: Holds all visible content

### Heading Tags

1. `<h1> to <h6>`: Headings (H1 is the largest, H6 the smallest)

### Links & Navigation

1. `<a href="URL">` : Creates hyperlinks
2. `<nav>` : Semantic HTML to define navigation sections
3. `target="\_blank"` : anchor tag attribute to open links in a new tab

### Media

1. `<video>` : used to embed video content on a web page, allowing users to play, pause, and control video playback directly in the browser
2. `<audio>` : used to embed audio content on a web page, enabling users to play, pause, and control audio playback directly in the browser

### Self Closing Tags

Self-closing (or void) tags in HTML do not have closing tags because they do not contain any content. These tags typically serve as standalone elements.

1. `<img />` : Embeds an image to your application. Note: In HTML5, you don’t need to explicitly close self-closing tags (`<img>` is still valid).
2. `<input />` : Defines an input field in forms.
3. `<br />` : Inserts a line break

### Semantic HTML Tags

Semantic HTML refers to the use of HTML5 tags that clearly describe the meaning of the content inside them. These tags improve readability, SEO, and accessibility,
making it easier for browsers, developers, and search engines to understand the structure of a webpage.

#### Common Semantic HTML Tags

1. `<header>` : Defines the introductory content or navigation links at the top of a page or section.
2. `<nav>` : Represents navigation links within a document.
3. `<section>` : Groups related content together, typically with a heading.
4. `<article>` : Contains independent, self-contained content (e.g., blog posts, news articles).
5. `<aside>` : Represents content that is tangentially related to the main content (e.g., sidebars, ads).
6. `<main>` : Specifies the main content of the document, excluding headers, footers, and sidebars.
7. `<footer>` : Contains footer information like copyright, contact details, or links.
8. `<figure>` : Encapsulates images, diagrams, and illustrations along with captions.
9. `<figcaption>` : Provides a caption or description for a `<figure>`.
10. `<mark>` : Highlights text to draw attention (e.g., search results highlighting).
11. `<time>` : Represents a specific time or date (useful for event timestamps).
12. `<details>` : Creates a collapsible section with extra information.
13. `<summary>` : Provides a heading for the `<details>` element (clickable to show/hide content).

### Table Elements

Tables are used to display structured data in a tabular format.

1. `<table>` : Defines a table.
2. `<tr>` : Defines a row in a table.
3. `<td>` : Defines a cell within a row.
4. `<th>` : Defines a header cell (bold and centered by default).
5. `<thead>` : Groups the header content in a table.
6. `<tbody>` : Groups the body content in a table.
7. `<tfoot>` : Groups the footer content in a table.
8. `<colspan>` : Allows a table cell to span multiple columns.
9. `<rowspan>` : Allows a table cell to span multiple rows.

#### Forms & Input Elements

1. `<form>`: Defines an HTML form used to collect user input.
2. `<input>`: Defines an input field in forms (can have various types like text, password, checkbox, etc.).
3. `<textarea>`: Defines a multiline text input field (useful for longer user inputs).
4. `<button>`: Defines a clickable button, often used to submit forms.
5. `<select>`: Defines a dropdown list for selecting one or more options.
6. `<option>` : Defines options within a `<select>` dropdown.
7. `<label>`: Provides a label for form elements, improving accessibility.
8. `<fieldset>`: Groups related elements in a form, often used with a `<legend>` to provide a title for the group.

### Important HTML Attributes

1. **id** - Specifies a unique identifier for an element.
   <p id="intro">This is an introduction.</p>

2. **class** - Defines one or more class names for styling with CSS or JavaScript.
   <div class="container">Content goes here</div>
3. **href** - Specifies the URL for hyperlinks.
   <a href="https://example.com">Visit Example</a>

4. **src** - Specifies the source URL for images, videos, and scripts.
   <img src="image.jpg" alt="An example image" />

5. **alt** - Provides alternative text for images (useful for accessibility and SEO).
   <img src="logo.png" alt="Company Logo" />
