# Assignment: Simple Login Page (Step-by-Step Guide)

## Step 1: Page Structure
1. Create HTML boilerplate:
   - `<!DOCTYPE html>`, `<html>`, `<head>`, `<body>`
2. Add a **title** inside `<head>`

---

## Step 2: Header Section
- Use `<header>` element
- Include:
  - Website title (`<h1>`)
  - Short welcome message (`<p>`)

**Tip:** `<header>` is a block element, it starts on a new line and takes full width.

---

## Step 3: Login Form Section
- Use `<section>` to contain the form
- Inside `<section>`, create `<form>`:
  - `action` → where form data will be sent (e.g., `submit.php`)
  - `method="post"` → send data securely
- Add **username** and **password** input fields:
  - Use `<label>` + `<input>`
  - Add `placeholder` and `name` attributes
- Group label + input inside `<div>` (block element)

---

## Step 4: Submit Button
- Use `<input type="submit">`
- Add a value like “Login”

---

## Step 5: Footer Section
- Use `<footer>` element
- Include copyright or contact info

---

## Step 6: Best Practices
- Add **comments** to explain your code
  ```html
  <!-- This is the username input -->
