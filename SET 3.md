10 HTML Questions - SET 3

---

### **1. What is the difference between HTML and XHTML?**  
**Answer:**  
- **HTML**:  
  - A standard markup language for creating web pages.  
  - It is forgiving of syntax errors (e.g., unclosed tags).  
- **XHTML**:  
  - A stricter, XML-based version of HTML.  
  - It requires proper nesting, lowercase tags, and attributes, and all tags must be closed.  

---

### **2. Explain the difference between inline, block, and inline-block elements.**  
**Answer:**  
- **Inline**:  
  - Does not start on a new line.  
  - Examples: `<span>`, `<a>`.  
- **Block**:  
  - Starts on a new line and takes up the full width available.  
  - Examples: `<div>`, `<p>`.  
- **Inline-block**:  
  - Behaves like an inline element but allows setting width and height.  

---

### **3. What is the purpose of the `<doctype>` declaration in HTML?**  
**Answer:**  
The `<!DOCTYPE>` declaration defines the document type and version of HTML being used. It must appear at the very top of an HTML document to ensure the browser renders the page in standards mode.  
Example: `<!DOCTYPE html>` for HTML5.

---

### **4. What is the difference between the `<link>` and `<a>` tags?**  
**Answer:**  
- `<link>`:  
  - Used to define a relationship between the current document and an external resource, such as a stylesheet.  
  - Example: `<link rel="stylesheet" href="styles.css">`.  
- `<a>`:  
  - Used to create hyperlinks to other pages or locations within the same page.  
  - Example: `<a href="https://example.com">Visit Example</a>`.

---

### **5. How can you make an HTML form accessible?**  
**Answer:**  
To make forms accessible:  
1. Use the `<label>` tag with the `for` attribute linked to the `id` of form inputs.  
   Example: `<label for="email">Email:</label> <input id="email" type="text">`.  
2. Use the `aria-*` attributes for additional accessibility if necessary.  
3. Group related fields with `<fieldset>` and `<legend>`.  
4. Provide helpful placeholder text or default values.

--- 
Here are 5 additional HTML interview questions and answers:

---

### **6. What is the difference between `<head>` and `<body>` tags in HTML?**  
**Answer:**  
- **`<head>`**:  
  - Contains metadata about the HTML document.  
  - Includes elements like `<title>`, `<meta>`, `<link>`, `<style>`, and `<script>`.  
  - Example:  
    ```html
    <head>
      <title>Page Title</title>
      <meta charset="UTF-8">
    </head>
    ```  
- **`<body>`**:  
  - Contains the visible content of the webpage.  
  - Includes elements like headings, paragraphs, images, and forms.  
  - Example:  
    ```html
    <body>
      <h1>Welcome to My Website</h1>
    </body>
    ```  

---

### **7. What is the purpose of the `<canvas>` element in HTML?**  
**Answer:**  
The `<canvas>` element is used to draw graphics on a webpage using JavaScript. It is commonly used for creating charts, animations, and games.  
Example:  
```html
<canvas id="myCanvas" width="400" height="300"></canvas>
<script>
  const canvas = document.getElementById("myCanvas");
  const ctx = canvas.getContext("2d");
  ctx.fillStyle = "blue";
  ctx.fillRect(50, 50, 100, 100);
</script>
```

---

### **8. What are void elements in HTML? Provide examples.**  
**Answer:**  
Void elements are HTML elements that do not have closing tags. They are self-closing by nature.  
Examples:  
- `<img>`: Used for images.  
- `<br>`: Inserts a line break.  
- `<hr>`: Inserts a horizontal rule.  
- `<input>`: Used for form inputs.  
- `<meta>`: Provides metadata.  

---

### **9. How do you create a table in HTML?**  
**Answer:**  
To create a table in HTML, use the `<table>` tag along with `<tr>` (table row), `<td>` (table cell), and `<th>` (table header).  
Example:  
```html
<table border="1">
  <tr>
    <th>Name</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>John</td>
    <td>25</td>
  </tr>
  <tr>
    <td>Jane</td>
    <td>30</td>
  </tr>
</table>
```

---

### **10. What is the difference between `<script>` and `<noscript>` tags in HTML?**  
**Answer:**  
- **`<script>`**:  
  - Used to include JavaScript code in the HTML document.  
  - Example:  
    ```html
    <script>
      console.log("Hello, World!");
    </script>
    ```  
- **`<noscript>`**:  
  - Provides alternative content to be displayed if JavaScript is disabled or not supported by the browser.  
  - Example:  
    ```html
    <noscript>Your browser does not support JavaScript.</noscript>
    ```

--- 
