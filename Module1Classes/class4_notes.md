# Class 4: CSS Layout
## Creating Responsive Layouts

### 1. CSS Positioning

#### Position Properties
- `static` (default)
- `relative`
- `absolute`
- `fixed`
- `sticky`

#### Positioning Context
- Document flow
- Containing blocks
- Stacking context
- Z-index

### 2. Flexbox Layout

#### Flex Container Properties
- `display: flex`
- `flex-direction`
- `justify-content`
- `align-items`
- `flex-wrap`
- `gap`

#### Flex Item Properties
- `flex-grow`
- `flex-shrink`
- `flex-basis`
- `align-self`
- `order`

### 3. CSS Grid

#### Grid Container Properties
- `display: grid`
- `grid-template-columns`
- `grid-template-rows`
- `grid-gap`
- `grid-template-areas`

#### Grid Item Properties
- `grid-column`
- `grid-row`
- `grid-area`
- `justify-self`
- `align-self`

### 4. Responsive Design

#### Viewport Meta Tag

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

#### Media Queries

```css
@media screen and (max-width: 768px) {
    /* Tablet styles */
}

@media screen and (max-width: 480px) {
    /* Mobile styles */
}
```

#### Responsive Units
- Relative units: `em`, `rem`
- Viewport units: `vh`, `vw`
- Percentages: `%`
- Flexible grids
- Auto-fit/auto-fill

### 5. Layout Best Practices

#### Mobile-First Approach
- Start with mobile layout
- Progressive enhancement
- Performance considerations
- Content priority

#### Common Patterns
- Navigation patterns
- Card layouts
- Grid systems
- Responsive images
- Typography scaling

### 6. Practical Application: TODO List Layout

#### Desktop Layout
1. Two-Column Layout:
   - Navigation sidebar
   - Main content area
   - Fixed header

2. Task List Grid:
   - Responsive card layout
   - Equal-width columns
   - Dynamic spacing

#### Mobile Layout
1. Single Column:
   - Stacked navigation
   - Full-width cards
   - Floating action buttons

2. Touch Considerations:
   - Larger tap targets
   - Touch-friendly spacing
   - Swipe actions

### 7. Advanced Layout Techniques

#### CSS Custom Properties

```css
:root {
    --main-color: #333;
    --spacing-unit: 1rem;
}
```

#### Layout Debugging
- Border debugging
- Grid overlays
- Flexbox debugging
- Browser DevTools

### Homework Assignment

1. Layout Implementation:
   - Create responsive TODO list layout
   - Implement both desktop and mobile views
   - Add navigation menu
   - Style task cards

2. Testing Task:
   - Test on different devices
   - Verify breakpoints
   - Check accessibility
   - Document layout decisions

### Additional Resources

1. References:
   - Flexbox Guide (CSS-Tricks)
   - Grid Guide (CSS-Tricks)
   - MDN Layout Documentation

2. Tools:
   - Browser DevTools
   - Responsive Design Checker
   - Grid Generator 