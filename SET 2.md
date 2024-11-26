### 10 HTML Questions - SET 2

---

### 1. **What is the difference between `<b>` and `<strong>` tags in HTML?**
**Answer:**  
- **`<b>`**: Represents bold text for styling purposes only, without any semantic meaning.
- **`<strong>`**: Represents text with strong emphasis, which is often rendered as bold. It also carries semantic meaning, indicating that the content is important or emphasized.

---

### 2. **Explain the purpose of the `<iframe>` tag in HTML.**
**Answer:**  
The `<iframe>` tag is used to embed another HTML document within the current page, such as another webpage or a third-party service (e.g., YouTube videos or Google Maps). Example:
```html
<iframe src="https://www.example.com" width="600" height="400"></iframe>
```
It allows for embedding external content without navigating away from the current page.

---

### 3. **What is the difference between the `<link>` and `<a>` tags in HTML?**
**Answer:**  
- **`<link>`**: Used to link external resources (like stylesheets) to the current document. It is placed inside the `<head>` section.
  Example:  
  ```html
  <link rel="stylesheet" href="styles.css">
  ```
- **`<a>`**: Used to create hyperlinks that allow users to navigate between pages or to different locations within the same page.
  Example:  
  ```html
  <a href="https://www.example.com">Click here</a>
  ```

---

### 4. **What is the use of the `action` and `method` attributes in a form tag?**
**Answer:**  
- **`action`**: Specifies the URL where the form data will be sent for processing when the form is submitted. Example: `<form action="/submit" method="POST">`.
- **`method`**: Defines the HTTP method to use when submitting the form data. Common methods are:
  - **`GET`**: Appends form data to the URL.
  - **`POST`**: Sends form data in the body of the HTTP request.

---

### 5. **What is the difference between the `inline` and `block` display properties in CSS?**
**Answer:**  
- **`inline`**: Elements with this display property only take up as much width as necessary and do not start on a new line. Example: `<span>`.
- **`block`**: Elements with this display property take up the full width available and start on a new line. Example: `<div>`.

---

### 6. **What are the various input types available in HTML forms?**
**Answer:**  
HTML provides several input types for various kinds of user inputs, such as:
- **`<input type="text">`**: For text input.
- **`<input type="password">`**: For password input (characters are hidden).
- **`<input type="email">`**: For email addresses (with validation).
- **`<input type="number">`**: For numeric input.
- **`<input type="radio">`**: For single-choice selection.
- **`<input type="checkbox">`**: For multiple-choice selection.
- **`<input type="file">`**: For file uploads.
- **`<input type="submit">`**: For submitting the form.

---

### 7. **What is the difference between `<ol>` and `<ul>` tags?**
**Answer:**  
- **`<ol>`**: Represents an ordered (numbered) list. Example:  
  ```html
  <ol>
    <li>First item</li>
    <li>Second item</li>
  </ol>
  ```
- **`<ul>`**: Represents an unordered (bulleted) list. Example:  
  ```html
  <ul>
    <li>First item</li>
    <li>Second item</li>
  </ul>
  ```

---

### 8. **What are the `<meta>` tags for defining character encoding in HTML?**
**Answer:**  
The `<meta>` tag can be used to specify the character encoding for the HTML document. The most common character encoding is UTF-8. Example:
```html
<meta charset="UTF-8">
```
This ensures that the browser correctly displays special characters and supports internationalization.

---

### 9. **What is the `<canvas>` tag and what is it used for in HTML?**
**Answer:**  
The `<canvas>` tag is used to draw graphics, such as shapes, images, and animations, on the fly using JavaScript. It provides a rectangular area within a webpage where you can render dynamic graphics. Example:
```html
<canvas id="myCanvas" width="500" height="500"></canvas>
<script>
  var ctx = document.getElementById("myCanvas").getContext("2d");
  ctx.fillStyle = "blue";
  ctx.fillRect(10, 10, 150, 100);
</script>
```

---

### 10. **What is the `target` attribute in the `<a>` tag and how is it used?**
**Answer:**  
The `target` attribute specifies where the linked document will open when the user clicks on a link. Common values are:
- **`_blank`**: Opens the link in a new tab or window.
- **`_self`**: Opens the link in the same frame (default behavior).
- **`_parent`**: Opens the link in the parent frame (if inside a frame).
- **`_top`**: Opens the link in the full window (topmost frame).

Example:
```html
<a href="https://www.example.com" target="_blank">Open in a new tab</a>
```
