Here are 5 HTML interview questions and answers presented in a text format:

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

These questions and answers target fundamental and practical HTML knowledge essential for interviews.
