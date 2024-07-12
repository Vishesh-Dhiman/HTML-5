# HTML (HyperText Markup Language)

HTML is the standard markup language used to create web pages. It describes the structure of a webpage and consists of a series of elements that tell the browser how to display the content.

## Basic Structure of an HTML Document

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1>Hello, World!</h1>
    <p>This is a paragraph.</p>
</body>
</html>
```

## HTML Tags

HTML tags are the building blocks of HTML. They are used to create elements and define the content within an HTML document. Here is a table explaining some common HTML tags:

| Tag        | Description                                                             | Example                                     |
|------------|-------------------------------------------------------------------------|---------------------------------------------|
| `<!DOCTYPE>`| Defines the document type and version of HTML                           | `<!DOCTYPE html>`                           |
| `<html>`   | Root element of an HTML document                                         | `<html lang="en">`                           |
| `<head>`   | Container for metadata (data about data) and links to scripts/styles     | `<head>`                                    |
| `<title>`  | Specifies the title of the document                                      | `<title>Document</title>`                   |
| `<meta>`   | Provides metadata such as charset, author, viewport settings             | `<meta charset="UTF-8">`                    |
| `<link>`   | Used to link to external resources such as stylesheets                   | `<link rel="stylesheet" href="styles.css">` |
| `<script>` | Used to define client-side JavaScript                                    | `<script src="script.js"></script>`         |
| `<body>`   | Contains the content of the HTML document                                | `<body></body>`                             |
| `<h1>` to `<h6>` | Define HTML headings, with `<h1>` being the highest (or most important) and `<h6>` the least | `<h1>Heading 1</h1>` to `<h6>Heading 6</h6>` |
| `<p>`      | Defines a paragraph                                                      | `<p>This is a paragraph.</p>`               |
| `<a>`      | Defines a hyperlink                                                      | `<a href="https://example.com">Link</a>`    |
| `<img>`    | Embeds an image                                                          | `<img src="image.jpg" alt="Description">`   |
| `<ul>`     | Defines an unordered list                                                | `<ul><li>Item 1</li><li>Item 2</li></ul>`   |
| `<ol>`     | Defines an ordered list                                                  | `<ol><li>Item 1</li><li>Item 2</li></ol>`   |
| `<li>`     | Defines a list item                                                      | `<li>List item</li>`                        |
| `<div>`    | Defines a division or section                                            | `<div>Content</div>`                        |
| `<span>`   | Defines a span of text                                                   | `<span>Text</span>`                         |
| `<form>`   | Defines an HTML form for user input                                      | `<form action="/submit"></form>`            |
| `<input>`  | Defines an input control                                                 | `<input type="text" name="name">`           |
| `<button>` | Defines a clickable button                                               | `<button>Click me</button>`                 |

## Semantic vs Non-Semantic Elements

### Semantic Elements

Semantic elements clearly describe their meaning in a human- and machine-readable way. Examples include:

- `<article>`: Defines an article
- `<aside>`: Defines content aside from the page content
- `<details>`: Defines additional details that the user can view or hide
- `<figcaption>`: Defines a caption for a `<figure>` element
- `<figure>`: Specifies self-contained content, like illustrations, diagrams, photos, etc.
- `<footer>`: Defines a footer for a document or section
- `<header>`: Defines a header for a document or section
- `<main>`: Specifies the main content of a document
- `<mark>`: Defines marked/highlighted text
- `<nav>`: Defines navigation links
- `<section>`: Defines a section in a document
- `<summary>`: Defines a visible heading for a `<details>` element

### Non-Semantic Elements

Non-semantic elements do not clearly describe their meaning and are generally used for styling purposes. Examples include:

- `<div>`: Defines a division or section
- `<span>`: Defines a span of text

## Additional Useful HTML Information

### Forms and Inputs

HTML forms are used to collect user input. Here is a basic example of a form:

```html
<form action="/submit" method="post">
    <label for="name">Name:</label>
    <input type="text" id="name" name="name">
    <input type="submit" value="Submit">
</form>
```

### HTML Entities

HTML entities are used to display reserved characters or invisible characters. Some examples:

- `&lt;` for `<`
- `&gt;` for `>`
- `&amp;` for `&`
- `&quot;` for `"`
- `&apos;` for `'`

### Comments

HTML comments are used to leave notes or comments in the code and are not displayed in the browser. They are written as:

```html
<!-- This is a comment -->
```

### Multimedia

HTML supports multimedia such as images, videos, and audio. Examples:

#### Images

```html
<img src="image.jpg" alt="Description">
```

#### Videos

```html
<video width="320" height="240" controls>
    <source src="movie.mp4" type="video/mp4">
    Your browser does not support the video tag.
</video>
```

#### Audio

```html
<audio controls>
    <source src="audio.mp3" type="audio/mpeg">
    Your browser does not support the audio element.
</audio>
```

### Links and Navigation

Links are created using the `<a>` tag. Here is an example:

```html
<a href="https://example.com">Visit Example</a>
```

### Tables

HTML tables are used to display data in a tabular format. Example:

```html
<table>
    <tr>
        <th>Header 1</th>
        <th>Header 2</th>
    </tr>
    <tr>
        <td>Data 1</td>
        <td>Data 2</td>
    </tr>
</table>
```

This guide covers the basics and some advanced features of HTML. With these fundamentals, you can start creating and structuring your web pages effectively.
```

This Markdown guide provides a detailed overview of HTML, from basic structure and tags to semantic elements and multimedia. If you need any more specific information or examples, feel free to ask!
