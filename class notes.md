#### Semantic HTML

A semantic element clearly describes its meaning to both the browser and the developer.

[w3Schools semantic tags](https://www.w3schools.com/html/html5_semantic_elements.asp)

##### Article

specifies independent, self-contained content. should make sense on its own, and it should be possible to distribute it independently from the rest of the web site.

Examples:

- Forum posts
- Blog posts
- User comments
- Product cards
- Newspaper articles

##### Header

epresents a container for introductory content or a set of navigational links for a document or **for a section**.

typically contains:

- one or more heading elements (`<h1> - <h6>`)
- logo or icon

You can have several **`<header>`** elements in one HTML document. However, `<header>` cannot be placed within a `<footer>`, `<address>` or another `<header>` element.

##### Footer

defines a footer for a document or section.

typically contains:

- authorship information
- copyright information
- contact information
- sitemap
- back to top links
- related documents

You can have several `<footer>` elements in one document.

##### Nav

defines a set of navigation links.

NOT all links of a document should be inside a `<nav>` element. The `<nav>` element is intended only for major blocks of navigation links.

Browsers, such as screen readers for disabled users, can use this element to determine whether to omit the initial rendering of this content.

##### Aside

The `<aside>` element defines some content aside from the content it is placed in (like a sidebar).

The `<aside>` content should be indirectly related to the surrounding content.

**Role=complementary**

The complementary landmark role is used to designate a supporting section that relates to the main content, yet can stand alone when separated. These sections are frequently presented as sidebars or call-out boxes.

#### main role

The main landmark role is used to indicate the primary content of a document. Can be used by assistive technology such as screen readers to quickly identify and navigate to large sections of the document.

There should only be one main landmark role per document.
