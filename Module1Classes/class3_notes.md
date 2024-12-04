# Class 3: Introduction to CSS
## Styling Web Pages

### 1. CSS Fundamentals

#### What is CSS?
- Cascading Style Sheets
- Controls the visual presentation
- Separates style from structure
- Multiple ways to apply styles

#### CSS Syntax

```css
selector {
    property: value;
    another-property: value;
}
```

### 2. Ways to Include CSS

#### 1. Inline CSS
- Using `style` attribute
- Highest specificity
- Hard to maintain

```html
<div style="color: blue; margin: 10px;">
```

#### 2. Internal CSS
- Using `<style>` tag in HTML
- Applies to single page

```html
<style>
    .class-name {
        property: value;
    }
</style>
```

#### 3. External CSS
- Separate .css file
- Linked using `<link>` tag
- Best for maintenance

```html
<link rel="stylesheet" href="styles.css">
```

### 3. Selectors and Specificity

#### Basic Selectors
- Element: `p`, `div`, `span`
- Class: `.classname`
- ID: `#idname`
- Universal: `*`

#### Combinators
- Descendant: `div p`
- Child: `div > p`
- Adjacent: `div + p`
- Sibling: `div ~ p`

#### Specificity Hierarchy
1. Inline styles
2. IDs
3. Classes, attributes, pseudo-classes
4. Elements, pseudo-elements

### 4. Colors and Typography

#### Color Properties
- `color`: Text color
- `background-color`: Background
- `border-color`: Border color

#### Color Values
- Keywords: `red`, `blue`
- Hex: `#FF0000`
- RGB: `rgb(255, 0, 0)`
- RGBA: `rgba(255, 0, 0, 0.5)`

#### Typography Properties
- `font-family`
- `font-size`
- `font-weight`
- `line-height`
- `text-align`
- `text-decoration`

### 5. Box Model

#### Components
- Content
- Padding
- Border
- Margin

#### Properties
- `width`, `height`
- `padding`, `padding-*`
- `border`, `border-*`
- `margin`, `margin-*`

#### Box-Sizing

```css
* {
    box-sizing: border-box;
}
```

### 6. Practical Application: TODO List Styling

#### Basic Styles
1. Container Styling:
   - Width constraints
   - Centered layout
   - Background colors
   - Padding for spacing

2. Form Styling:
   - Input field dimensions
   - Button appearances
   - Spacing between elements
   - Focus states

3. Task List Styling:
   - List item padding
   - Hover effects
   - Completion status
   - Priority indicators

### 7. CSS Best Practices

#### Organization
- Logical grouping
- Consistent naming
- Comments for sections
- Modular approach

#### Performance
- Efficient selectors
- Minimize redundancy
- Optimize specificity
- Reduce file size

### Homework Assignment

1. Styling Exercise:
   - Style the TODO list HTML:
     * Color scheme implementation
     * Typography setup
     * Form styling
     * List item styling
   - Add hover effects
   - Implement transitions

2. CSS Organization Task:
   - Create modular CSS file
   - Document styles with comments
   - Optimize selectors
   - Test cross-browser

### Additional Resources

1. References:
   - MDN CSS Reference
   - CSS-Tricks
   - Google Fonts
   - Color palette tools

2. Tools:
   - CSS Validators
   - Browser DevTools
   - CSS Preprocessors intro 