# Chapter Three
---
---
# Comments, Line Breaks, and Whitespace
---
---
# 1. Comments

Comments are notes written inside the code to help humans understand it.
They are not shown on the webpage.

```html
<!-- This is a comment -->
```

✔ Used to explain code

✔ Ignored by the browser

---
# 2. Line Breaks

A line break moves text to a new line.

In HTML
This is line one `<br>` This is line two

```html
<br> forces the text to go to the next line.
```




👉 Two spaces + Enter create a line break.

---
# 3. Whitespace

Whitespace means spaces, tabs, or empty lines in text.

```html
<p>Hello      World</p>
```


✔ Browsers treat many spaces as one space
✔ Extra spaces do not change the display

# Key Understanding

`<!-- -->` → Comments help developers, not users

`br` →  Line breaks control text layout

`normal space` → Whitespace is mostly ignored by browsers

---
---
# Chapter Four
---
## HTML Attributes (Basic Explanation)
---
**What is an HTML Attribute?**

- An HTML attribute gives extra information about an HTML element.
Attributes are written inside the opening tag.

---
---
---

### **Basic Structure**

`<tagname attribute="value">`



✔ Attribute → describes the element

✔ Value → tells how it behaves

## Common HTML Attributes
## 1. href
```html
<a href="https://example.com">Visit Website</a>
```

---
👉 Tells the link where to go
## 2. src
```html
<img src="image.jpg">
```

👉 Tells the browser which image to show

---
## 3. alt
```html
<img src="logo.png" alt="Company Logo">
```

👉 Shows text if image fails and helps accessibility

---
## 4. title
```html
<p title="Extra info">Hover me</p>
```

👉 Shows text when you hover the mouse

---
## **Key Points**

- `Atr` → Attributes are always in the opening tag

-  Written as → `name="value"`

-  They control behavior and appearance

---

# **HTML IMAGES**
---
```html
<img src="image.jpg" alt="Description of image">
```
- The **<img>** tag is used to display images on a webpage, where src defines the image path and alt provides alternative text if the image cannot load.


# **HTML Links (Anchor Tag)**
---
```html
<a href="https://example.com">Visit Website</a>

```
- The anchor tag `<a>` is used to create links in HTML. The href attribute defines the destination of the link, which can be a website, another page, an email, or a section on the same page. Links help users navigate between pages easily.

---

# **HTML Lists**
---
```html
<ul>
  <li>Item One</li>
  <li>Item Two</li>
</ul>
```

*HTML lists are used to group related items together.*
- `<ul>` creates an unordered list (bullets) 
- `<ol>` creates an ordered list (numbers)
- `<li>` defines each list item. Lists make content clear, organized, and easy to read.



### ***HTML Table Tags (Short Explanation)***

- **`<tr>` (Table Row):** Creates a single row in a table. It represents a **row**, not a column.
- **`<th>` (Table Header):** Defines a header cell. It represents a **column title**.
- **`<td>` (Table Data):** Holds normal table data. It represents a **column value**.

**Summary:**  
- `<tr>` = row  
- `<th>` = columns
- `<td>` = columns



### Example Table

```html
<table border="1">
  <tr>
    <th>Name</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Ali</td>
    <td>20</td>
  </tr>
  <tr>
    <td>Fatima</td>
    <td>22</td>
  </tr>
</table>
```

### **Expected  Output**
```excel
    Name	  Age
    Ali	      20
    Fatima	  22
```


 - `<tr>` → creates rows  
 - `<th>` → header (bold, column title)  
 - `<td>` → normal cell data  

---





# Chapter Four: HTML Form Submission

### *Introduction*

- HTML forms are used to collect data from users, such as 
```php
   ✔️ usernames 
   ✔️ passwords 
   ✔️ messages
   ✔️ other inputs.
```

## Form Structure

- A form is created using the `<form>` tag.
```html
<form action="submit.php" method="post">
  <input type="text" name="username">
  <input type="submit" value="Send">
</form>
```

### Important Attributes

- **`action`** → specifies where send user of data.

- **`method`** → defines how send data (get or post)

---
# ***⚠️Note***
### GET vs POST

- **GET** → Sends data in the URL.  
  - You can see the data in the address bar.  
  - Good for small and non-secret data, like search forms.  

- **POST** → Sends data hidden in the request.  
  - Data is not visible in the URL.  
  - Good for passwords or private information.  
  - Can send more data than GET.




---

# Chapter Five: Media (Video and Audio)

## *Introduction*

- HTML allows you to embed multimedia such as videos and audio directly into a webpage without external plugins.

---

## *Video Element*

```html
<video controls width="300">
  <source src="video.mp4" type="video/mp4">
</video>
```

## Audio Element

```html
<audio controls>
  <source src="sound.mp3" type="audio/mpeg">
</audio>
```

### Advantages

- Makes websites more interactive

- Works on modern browsers

- No extra plugins required



---

# Chapter Six: Divs and Spans

- Div Element

- The `<div>` element is a block-level container used to group and structure content.


```html
<div>
  <h2>Section Title</h2>
  <p>This is a paragraph inside a div.</p>
</div>
```

### Span Element

- The `<span>` element is an inline container used to style or highlight part of a text.

```html
<p>This is a <span>important word</span> in a sentence.</p>
```

---












# Chapter Seven: Semantic HTML Elements

## Introduction

- Semantic HTML elements clearly describe their meaning to both the browser and the developer.  
They help define the structure of a web page in a meaningful way, instead of using only generic tags like `<div>`.

**Semantic elements make your website:**
- Easier to understand
- More accessible
- More SEO-friendly

---

## Common Semantic Elements

### 1. `<header>`

The `<header>` element represents the top section of a page or section.  
It usually contains:
- Website title
- Logo
- Introductory content

#### Example:
```html
<header>
  <h1>My Website</h1>
  <p>Welcome to my website</p>
</header>
```
---
### 2. `<nav>`
The `<nav>` element is used for navigation links.
It tells the browser that these links are used for moving around the website.

**Example:**
```html

<nav>
  <a href="index.html">Home</a>
  <a href="about.html">About</a>
  <a href="contact.html">Contact</a>
</nav>
```
---

### 3. `<section>`
- The `<section>` element groups related content together.
- It usually has a heading and represents a specific topic.

**Example:**
```html

<section>
  <h2>About Us</h2>
  <p>We are a technology company.</p>
</section>
```
---

### 4. `<article>`
The `<article>` element represents independent content that can stand alone.

**Examples include:**

- Blog posts

- News articles

- Comments

**Example:**
```html

<article>
  <h2>Blog Post Title</h2>
  <p>This is a blog post content.</p>
</article>
```
---
### 5. `<footer>`
The `<footer>` element represents the bottom section of a page or section.
It often contains:

- Copyright information

- Contact details

- Extra links

**Example:**
```html
<footer>
  <p>© 2025 My Website. All rights reserved.</p>
</footer>
```
---
## ***Benefits of Semantic HTML***

- Improves SEO by helping search engines understand your content

- Makes code more readable and easier to maintain

- Enhances accessibility for screen readers and assistive technologies

## Conclusion
Semantic HTML elements give meaning to your web page structure.
By using elements like `<header>`, `<nav>`, `<section>`, `<article>`, and `<footer>`, you create modern, clean, and accessible websites.

---

# Chapter Eight: Block vs Inline Elements

## ***Block Elements***

- Take up the full width available

- Start on a new line

---

***Examples***

- `<div>`
- `<p>`
- `<h1>`


## ***Inline Elements***

- Take up only as much width as needed

- Do not start on a new line


### ***Examples:***
- `<span>`
- `<a>`
- `<strong>`


### ***Quick Comparison***
- Block elements → page structure
- Inline elements → text-level formatting



---

### Conclusion

```These chapters provide a strong foundation for understanding modern HTML concepts, helping you build well-structured and accessible web pages.```