# HTML Basics

**Presenters:** Ali Mohamoud, Shadia Mustafe, Hafsa Mouse 

---

## What is HTML?

- **HTML (Hypertext Markup Language)** is a standard markup language used to create web pages.  
- HTML uses **tags** to structure content and create elements on a web page.  
- HTML works together with **CSS** for styling and **JavaScript** for interactivity.  

---

## Basic Structure

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Page Title</title>
  </head>
  <body>
    <!-- Content goes here -->
  </body>
</html>
```
---
---

# Explanation:
```html

<html> → Root element

<head> → Metadata, like <title>, <meta>, <link>

<title> → Page title (browser tab)

<meta> → Metadata, charset, viewport etc.

<link> → External resources, e.g., CSS

<body> → Visible page content
```
---

# Text & Headings

```html
<h1>Main Title</h1>
<h2>Sub Title</h2>
<p>This is a <strong>bold</strong> and <em>italic</em> paragraph.</p>
<p>Underlined: <u>Important</u></p>
<a href="https://example.com" target="_blank">Visit Example</a>
```
---

# Lists
```html

<ul>
  <li>Apples</li>
  <li>Bananas</li>
  <li>Oranges</li>
</ul>

<ol>
  <li>Step 1</li>
  <li>Step 2</li>
  <li>Step 3</li>
</ol>
```
---

# Images & Media
```html

<img src="cat.jpg" alt="Cute Cat" width="200">

<audio controls>
  <source src="song.mp3" type="audio/mpeg">
</audio>

<video width="320" height="240" controls>
  <source src="movie.mp4" type="video/mp4">
</video>
```
---
# Links
```html

<a href="https://google.com" target="_blank">Open Google</a>
href → URL

target="_blank" → Open in new tab
```
---

# Forms
```html

<form action="/submit">
  <label>Name:</label>
  <input type="text" name="username">
  
  <label>Message:</label>
  <textarea name="message"></textarea>
  
  <button type="submit">Send</button>
  
  <select name="options">
    <option value="1">Option 1</option>
    <option value="2">Option 2</option>
  </select>
</form>
```
---

# Tables
```html

<table border="1">
  <tr>
    <th>Name</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Ali</td>
    <td>25</td>
  </tr>
  <tr>
    <td>Fatima</td>
    <td>22</td>
  </tr>
</table>
```
---


# Sections
```html

<div class="container">
  <header>
    <h1>Welcome</h1>
  </header>
  
  <nav>
    <a href="/">Home</a> |
    <a href="/about">About</a>
  </nav>
  
  <section>
    <h2>About Us</h2>
    <p>This is a section about us.</p>
  </section>
  
  <footer>
    <p>© 2025 Ali Mohamoud</p>
  </footer>
</div>
```
---

# Semantic Elements
```html

<main>
  <article>
    <h2>News</h2>
    <p>This is an article about HTML.</p>
  </article>
  
  <aside>
    <p>Sidebar info</p>
  </aside>
  
  <figure>
    <img src="html-logo.png" alt="HTML Logo">
    <figcaption>HTML Logo</figcaption>
  </figure>
  
  <p>Highlighted text: <mark>Important</mark></p>
</main>
```

# Note:
 
```html 
The <meta>  tag provides invisible information about the webpage, such as 
```

1. **charset**:  Specifies the character encoding for the webpage.
2. **description**:  Provides a short summary of the webpage.
3. **author**:  Specifies the creator or owner of the webpage.
4. **viewport**:  Controls how the webpage is displayed on different devices, especially mobile.
```html
  which browsers and search engines use.

```
---
---
```c
Conclusion
HTML is the foundation of the web.

Knowing tags and elements is essential for creating structured & accessible web pages.

HTML is used for static websites, dynamic apps, and emails.

Happy coding! 😍