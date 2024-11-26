# HTML Basics: A Comprehensive Beginner's Roadmap

## Introduction
This guide provides a thorough introduction to HTML, covering essential concepts and techniques for web development beginners. From understanding basic structure to creating interactive elements, this roadmap will help you build a solid foundation in HTML.

## Table of Contents
1. [Introduction to HTML](#1-introduction-to-html)
2. [Basic Document Structure](#2-basic-structure-of-an-html-document)
3. [Text Content](#3-text-content)
4. [Lists](#4-lists)
5. [Links](#5-links)
6. [Images](#6-images)
7. [Basic Tables](#7-basic-tables)
8. [Forms](#8-forms-basics)
9. [Practice Projects](#practice-projects)

---

## 1. Introduction to HTML
HTML (HyperText Markup Language) is the standard language for creating web pages. It uses elements (tags) to describe the structure of a web page.

### Key Concepts
- **HTML Tags**: Define page structure
- **Attributes**: Provide additional information about elements

**Example:**
```html
<p class="example">This is a paragraph with a class attribute.</p>
```

## 2. Basic Document Structure
Every HTML document follows a specific structure:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Basic HTML Structure</title>
  </head>
  <body>
    <h1>Welcome to HTML!</h1>
    <p>This is a basic webpage.</p>
  </body>
</html>
```

## 3. Text Content
### Headings
HTML provides six levels of headings:
```html
<h1>Main Heading</h1>
<h2>Subheading</h2>
```

### Paragraphs and Breaks
```html
<p>A paragraph of text.</p>
<p>Line one.<br>Line two.</p>
<hr> <!-- Horizontal line -->
```

## 4. Lists
### Unordered Lists
```html
<ul>
  <li>Bullet Point 1</li>
  <li>Bullet Point 2</li>
</ul>
```

### Ordered Lists
```html
<ol>
  <li>First Step</li>
  <li>Second Step</li>
</ol>
```

## 5. Links
### Creating Hyperlinks
```html
<a href="https://example.com">Visit Website</a>
<a href="https://example.com" target="_blank">Open in New Tab</a>
```

## 6. Images
```html
<img src="image.jpg" alt="Image Description" width="300" height="200">
```

## 7. Basic Tables
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

## 8. Forms (Basics)
```html
<form action="/submit" method="post">
  <label for="name">Name:</label>
  <input type="text" id="name" name="name">
  <input type="submit" value="Submit">
</form>
```

## Practice Projects
1. **Simple Webpage**
   - Create a page with a heading
   - Add a paragraph
   - Include an image
   - Create a list

2. **Student Grade Table**
   - Design a table showing student names and grades

3. **Contact Form**
   - Create a form with:
     - Name field
     - Email field
     - Message textarea
     - Submit button

---

## Development Tips
- Use a modern text editor (VS Code, Sublime Text)
- Test your HTML in multiple browsers
- Use semantic HTML for better accessibility
- Practice, practice, practice!

*Happy Coding!*
