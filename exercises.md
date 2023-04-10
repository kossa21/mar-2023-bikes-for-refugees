#### HTML Syntax exercise:

**Tags**: article, h1, p, a
**Attributes**: href

#### HTML Tags exercise:

**Parent tags**: article, p

```
<article>
  <h1>Learning HTML</h1>
  <p>
    <span class="author">Author:</span>
    <a href="http://codeyourfuture.io">Code Your Future</a>
  </p>
  <p>Get to know the HTML basics.</p>
  <a href="http://html5rocks.com">Read Article</a>
</article>
```

```
<p>
    <span class="author">Author:</span>
    <a href="http://codeyourfuture.io">Code Your Future</a>
</p>
```

**Child tags**: h1, p, span, a
`<h1>Learning HTML</h1>`

```
<p>
    <span class="author">Author:</span>
    <a href="http://codeyourfuture.io">Code Your Future</a>
  </p>
```

`<span class="author">Author:</span>`

`<a href="http://codeyourfuture.io">Code Your Future</a>`

`<p>Get to know the HTML basics.</p>`

`<a href="http://html5rocks.com">Read Article</a>`

#### Example HTML/CSS Project exercise:

Even though you have seen previously HTML and CSS together in the same file, with the CSS _embedded_ into the HTML, is a better practice to separate them because this way we have all the CSS in one part and all the HTML in other part.

This way, if we need to make a change only related to styling, for example, we don't have to alter our HTML for any reason. Same if, for example, we just have to change the content of our HTML, we wouldn't touch styling intentionally or **by accident**.

This is known as **separation of concerns**.

#### Semantic HTML exercise

Semantic elements = elements with a meaning.

We don't remove the classes because if we do we would affect the styling.

- Line 23 and 52, change div for header
- Line 169 and 177, change div for footer
- Line 55, add the role='main'
- Line 33 and 48, change div for nav
- Line 75 and 88, 90 and 103, 111 and 126, 141 and 156, change div for article
- Line 106, change div for aside and add the role='complementary'

**Who benefits?**

- The semantic HTML tags help the search engines and other user devices to determine the importance and context of web pages.
- The pages made with semantic elements are much easier to read.
- It has greater accessibility.
- It offers a better user experience.
- People who uses screen readers will benefit a lot.
