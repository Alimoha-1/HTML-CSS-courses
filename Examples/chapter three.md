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
- `<th>` 
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

