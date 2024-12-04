# Class 2: HTML Fundamentals
## Building the Structure of Web Pages

### 1. Introduction to HTML

#### What is HTML?
- HyperText Markup Language
- The skeleton/structure of web pages
- Uses tags to define elements
- Describes the meaning of content (semantics)

#### Basic HTML Document Structure
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <!-- Document metadata goes here -->
</head>
<body>
    <!-- Page content goes here -->
</body>
</html>
```

### 2. Essential HTML Elements

#### Document Metadata
- `<meta>`: Character encoding, viewport settings
- `<title>`: Page title in browser tab
- `<link>`: External resource connections
- `<style>`: Internal CSS styles

#### Text Content Elements
- Headings: `<h1>` through `<h6>`
- Paragraphs: `<p>`
- Lists: 
  * Unordered lists: `<ul>` with `<li>`
  * Ordered lists: `<ol>` with `<li>`
- Text emphasis: `<strong>`, `<em>`
- Links: `<a href="...">`

### 3. Semantic HTML

#### Why Semantic HTML?
- Improves accessibility
- Better SEO (Search Engine Optimization)
- Clearer code structure
- Easier maintenance

#### Key Semantic Elements
- `<header>`: Page or section header
- `<nav>`: Navigation links
- `<main>`: Main content
- `<section>`: Thematic grouping
- `<article>`: Independent content
- `<aside>`: Sidebar content
- `<footer>`: Page or section footer

### 4. Forms and Input Elements

#### Form Basics
- Purpose: Collect user input
- Submit data to servers
- Various types of input fields

#### Common Form Elements
1. Text Inputs:
   - Single line: `<input type="text">`
   - Multi-line: `<textarea>`
   - Password: `<input type="password">`

2. Selection Inputs:
   - Checkboxes: `<input type="checkbox">`
   - Radio buttons: `<input type="radio">`
   - Dropdowns: `<select>` and `<option>`

3. Special Input Types:
   - Date: `<input type="date">`
   - Email: `<input type="email">`
   - Number: `<input type="number">`
   - Color: `<input type="color">`

#### Form Best Practices
- Always use `<label>` with form controls
- Group related fields with `<fieldset>`
- Provide clear submission buttons
- Include proper validation attributes
- Use appropriate input types

### 5. Tables

#### When to Use Tables
- Displaying tabular data
- Comparing information
- Organizing structured content

#### Table Structure
- `<table>`: Container
- `<thead>`: Header section
- `<tbody>`: Main content
- `<tr>`: Table row
- `<th>`: Header cell
- `<td>`: Data cell

### 6. HTML Attributes

#### Common Attributes
- `id`: Unique identifier
- `class`: Styling hooks
- `src`: Source for images/media
- `href`: Links destination
- `alt`: Alternative text
- `title`: Tooltip text

#### Data Attributes
- Custom data storage
- Format: `data-*`
- JavaScript accessibility
- Metadata storage

### 7. Practical Application: TODO List Structure

#### Key Components to Build
1. Task Input Form:
   - Task title input
   - Description textarea
   - Priority selection
   - Due date picker
   - Submit button

2. Task List Display:
   - Task items container
   - Checkbox for completion
   - Task details display
   - Action buttons

3. Navigation Structure:
   - Main menu
   - Category filters
   - Search functionality

### 8. HTML Best Practices

#### Code Quality
- Proper indentation
- Consistent formatting
- Meaningful element names
- Clear document structure

#### Accessibility
- Proper heading hierarchy
- Alternative text for images
- ARIA labels where needed
- Keyboard navigation support

### Homework Assignment

1. HTML Structure Exercise:
   - Create the complete HTML structure for:
     * Task creation form
     * Task list view
     * Task details page
   - Include all necessary semantic elements
   - Implement proper form validation

2. Code Review Task:
   - Review classmates' HTML
   - Check for semantic correctness
   - Verify accessibility features
   - Suggest improvements

### Additional Resources

1. References:
   - MDN HTML Elements Reference
   - W3C HTML Specification
   - HTML5 Doctor (semantic elements guide)

2. Tools:
   - HTML Validators
   - Accessibility checkers
   - HTML5 Outliner

### Next Class Preview
- Introduction to CSS
- Styling HTML elements
- Colors and typography
- Box model concepts 