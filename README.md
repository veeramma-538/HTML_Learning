Official Website to learn HTML


https://developer.mozilla.org/en-US/docs/Web/HTML

# 🌐 HTML Course — Learning 

Welcome to the **HTML Course ** 📚  
This repository contains well-organized notes to help you learn **HTML from basics to advanced**.  
Perfect for beginners, students, and web developers refreshing their knowledge.

---

## 🧭 Table of Contents

1. [Introduction to HTML](#1-introduction-to-html)  
2. [Basic Structure](#2-basic-structure)  
3. [Headings, Paragraphs & Text](#3-headings-paragraphs--text)  
4. [Links & Images](#4-links--images)  
5. [Lists](#5-lists)  
6. [Tables](#6-tables)  
7. [Forms & Input Elements](#7-forms--input-elements)  
8. [Semantic HTML](#8-semantic-html)  
9. [Multimedia Elements](#9-multimedia-elements)  
10. [HTML5 Features](#10-html5-features)  
11. [Best Practices](#11-best-practices)  
12. [Mini Projects](#12-mini-projects)  
13. [References](#13-references)

---

## 1️⃣ Introduction to HTML

 1.Inventor: Tim Berners-Lee at CERN.

2. When: concept 1989; first working system (HTML, HTTP, first browser/editor) implemented in 1990–1991.

3. Why: to share documents across disparate research computers using hyperlinks.

4. Early milestones: HTML 1.0 (early 1990s), formal specs through the IETF/W3C later, CSS and JavaScript arrived later to separate style & behavior.

5.Modern era: HTML evolved through major versions (HTML 2.0, 3.2, 4.01) to HTML5 (finalized ~2014), which standardized modern multimedia & APIs.

 6.Legacy: HTML remains the backbone of the web—semantic, extensible, and continuously evolving via WHATWG and W3C.



- **HTML** = *HyperText Markup Language*  
- It defines the **structure** of a webpage  
- Uses **tags** enclosed in angle brackets (`< >`)  
- Example:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>My First Page</title>
  </head>
  <body>
    <h1>Hello, World!</h1>
    <p>This is my first HTML page.</p>
  </body>
</html>

----

2️⃣ Basic Structure

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Page Title</title>
  </head>
  <body>
    <!-- Content goes here -->
  </body>
</html>

  <!DOCTYPE html> → Declares HTML5
  <html> → Root element
  <head> → Metadata, title, links
  <body> → Visible content

----

3️⃣ Headings, Paragraphs & Text
<h1>Main Heading</h1>
<h2>Sub Heading</h2>
<p>This is a paragraph.</p>
<b>Bold</b> <i>Italic</i> <u>Underline</u>
<br /> <!-- Line Break -->
<hr /> <!-- Horizontal Line -->
📝 Tip: Use <strong> and <em> for semantic importance instead of <b> and <i>.

-----

4️⃣ Links & Images
<a href="https://github.com" target="_blank">Visit GitHub</a>

<img src="image.jpg" alt="Description of image" width="300" />


target="_blank" opens link in a new tab

Always include alt text for accessibility

-----

5️⃣ Lists
<ul>
  <li>Unordered item 1</li>
  <li>Unordered item 2</li>
</ul>

<ol>
  <li>Ordered item 1</li>
  <li>Ordered item 2</li>
</ol>

------

6️⃣ Tables
<table border="1">
  <tr>
    <th>Name</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Alice</td>
    <td>20</td>
  </tr>
</table>


<th> = Table Header

<td> = Table Data

------

7️⃣ Forms & Input Elements
<form action="/submit" method="post">
  <label for="name">Name:</label>
  <input type="text" id="name" name="name" required />
  
  <label for="email">Email:</label>
  <input type="email" id="email" name="email" required />

  <input type="submit" value="Submit" />
</form>


📝 Common Input Types:

text, email, password, checkbox, radio, file, date, range

-----

8️⃣ Semantic HTML

Semantic tags give meaning to the structure:

<header>Site Header</header>
<nav>Navigation Menu</nav>
<main>Main Content</main>
<section>Section Content</section>
<article>Blog Post</article>
<aside>Sidebar</aside>
<footer>Site Footer</footer>
✅ Improves SEO, accessibility, and code readability.

-------

9️⃣ Multimedia Elements
<video controls width="400">
  <source src="video.mp4" type="video/mp4" />
</video>

<audio controls>
  <source src="audio.mp3" type="audio/mpeg" />
</audio>

------

🔟 HTML5 Features

<canvas> for drawing graphics
<svg> for vector images
<audio> & <video> without plugins
Local storage APIs
New input types (e.g. date, color, range)

-------

📝 11. Best Practices

✅ Use proper indentation
✅ Use semantic tags
✅ Include alt for images
✅ Validate your HTML (W3C Validator
)

❌ Don’t use deprecated tags (<center>, <font> etc.)

-------

💻 12. Mini Projects

Here are a few beginner-friendly project ideas:

📝 Simple Portfolio page
📰 Blog layout using semantic tags
📅 Event registration form
🍽️ Restaurant menu page

---------

📚 13. References

W3Schools HTML Tutorial
MDN Web Docs
FreeCodeCamp HTML Course

---------

🧑‍💻 Contributing

Contributions are welcome!
If you'd like to improve these notes or add examples, feel free to open a pull request.

