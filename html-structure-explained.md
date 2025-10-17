# **Understanding HTML Structure**
*Created by Crazy Nets – Web Development Course*

---

## 🧱 **What Is an HTML Document?**

Every web page starts with a **structured HTML document**. HTML stands for **HyperText Markup Language**, and it tells the browser how to display text, images, links, and other content.

Let’s look at a simple example:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>My First Web Page</title>
  </head>
  <body>
    <h1>Hello, Crazy Nets!</h1>
    <p>Welcome to your first web development lesson.</p>
  </body>
</html>
```

---

## 🔍 **Tag-by-Tag Explanation**

### `<!DOCTYPE html>`
This declaration tells the browser that the document is written in **HTML5**, the latest standard.  
It should always appear at the very top of the page.

### `<html>`
The **root element** that contains all the other HTML elements. Everything inside `<html>` and `</html>` belongs to your web page.

### `<head>`
The head section includes information **about** the web page (metadata), not visible to users.  
Common elements inside `<head>` include:
- `<title>` — Sets the title that appears on the browser tab.
- `<meta>` — Defines character encoding, page description, and more.
- `<link>` — Connects external resources like CSS files.

### `<body>`
Everything inside the `<body>` tag is **visible content** — what users actually see on the web page.  
This includes headings, paragraphs, images, links, buttons, and more.

Example:

```html
<body>
  <h1>Hello, Crazy Nets!</h1>
  <p>Welcome to your first web development lesson.</p>
</body>
```

---

## ⚠️ **Common Mistakes to Avoid**

1. ❌ **Forgetting to close tags**
   ```html
   <p>This paragraph is not closed
   ```
   ✅ Always close every tag properly:
   ```html
   <p>This paragraph is closed correctly.</p>
   ```

2. ❌ **Placing content outside `<html>` or `<body>`**
   Content should always go inside the `<body>` section.

3. ❌ **Wrong nesting of elements**
   ```html
   <p><strong>Text</p></strong> <!-- Wrong -->
   ```
   ✅ Correct nesting:
   ```html
   <p><strong>Text</strong></p>
   ```

4. ❌ **Missing `<!DOCTYPE html>`**
   Without it, browsers may not render your page correctly.

---

## 🧠 **Mini Quiz**

1. What does the `<head>` section contain?  
   a) Visible content  
   b) Metadata and page info  
   c) Images  
   **Answer:** b)

2. What tag defines the visible part of a web page?  
   a) `<meta>`  
   b) `<title>`  
   c) `<body>`  
   **Answer:** c)

3. True or False: You can write content outside the `<html>` tag.  
   **Answer:** False

---

*Created by **Crazy Nets** — Building the Next Generation of Web Developers.*
