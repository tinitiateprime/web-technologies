**CSS Tutorial Outline**
 **1. Introduction to CSS**  
- **Keywords** :
  - CSS (Cascading Style Sheets)

  - CSS Syntax: Selectors, Properties, Values

  - CSS inclusion methods: Inline CSS, Internal CSS, External CSS
 
  - Linking CSS to HTML: `<link rel="stylesheet" href="styles.css">`
**2. CSS Selectors**  
- **Basic Selectors**  
  - Element selector: `p {color: blue;}`
 
  - Class selector: `.className {color: red;}`
 
  - ID selector: `#idName {font-size: 20px;}`
 
  - Universal selector: `* {margin: 0;}`
 
- **Advanced Selectors**  
  - Grouping selectors: `h1, h2, p {font-family: Arial;}`
 
  - Descendant selector: `div p {color: green;}`
 
  - Child selector: `div > p {color: yellow;}`
 
  - Attribute selectors: `input[type="text"]`
 
  - Pseudo-classes: `a:hover`, `input:focus`
 
  - Pseudo-elements: `p::before`, `p::after`
**3. Box Model**  
- **Box Model Concepts** 
  - Content

  - Padding

  - Border

  - Margin
 
- **CSS Properties**  
  - `width`, `height`, `padding`, `margin`, `border`
 
  - `box-sizing: border-box;`


  - **Styling**
  - Colors (hex, rgb, rgba, hsl, hsla)
  - Backgrounds (color, images, gradients)
  - Borders (width, style, color, radius)
  - Text properties (font-family, font-size, font-weight, line-height, text-align, etc.)
  - Lists (list-style-type, list-style-position, list-style-image)
  - Tables (border-collapse, border-spacing)

**4. Colors and Backgrounds**  
- **Color Properties**  
  - Named colors: `red`, `blue`
 
  - Hexadecimal: `#ff0000`
 
  - RGB: `rgb(255,0,0)`
 
  - RGBA (with transparency): `rgba(255, 0, 0, 0.5)`
 
- **Background Properties**  
  - `background-color`, `background-image`, `background-repeat`, `background-position`, `background-size`
**5. Typography**  
- **Text Properties**  
  - `font-family`, `font-size`, `font-weight`, `font-style`
 
  - `color`, `text-align`, `line-height`, `letter-spacing`
 
  - `text-decoration`, `text-transform`
 
- **Web Fonts**  
  - Importing Google Fonts: `@import url('https://fonts.googleapis.com/css?family=Roboto');`
 
  - Font-face: `@font-face`
**6. Layout with CSS**  
- **Display Properties**  
  - `display: block`, `display: inline`, `display: inline-block`, `display: none`
 
- **Positioning**  
  - `position: static`, `relative`, `absolute`, `fixed`, `sticky`
 
  - `top`, `right`, `bottom`, `left`
 
  - `z-index`
 
- **Float and Clear**  
  - `float`, `clear`

  - Float-based layouts
 
- **Flexbox Layout**  
  - `display: flex`
 
  - Flex container: `justify-content`, `align-items`, `align-self`, `flex-wrap`, `flex-direction`
 
  - Flex items: `flex-grow`, `flex-shrink`, `flex-basis`
 
- **Grid Layout**  
  - `display: grid`
 
  - Defining columns and rows: `grid-template-columns`, `grid-template-rows`
 
  - Grid areas and spans: `grid-area`, `grid-column`, `grid-row`




  - **Responsive Design**
  - Media queries
  - Responsive units (%, em, rem, vw, vh)
  - Responsive images and videos
**7. CSS Units**  
- **Length Units**  
  - Absolute units: `px`, `cm`, `mm`, `in`, `pt`, `pc`
 
  - Relative units: `%`, `em`, `rem`, `vh`, `vw`, `vmin`, `vmax`
 
- **Responsive Design**  
  - Media queries: `@media (max-width: 600px) { ... }`

  - Fluid layouts and breakpoints
  
**8. Transitions and Animations**  
- **CSS Transitions**  
  - `transition-property`, `transition-duration`, `transition-timing-function`, `transition-delay`
 
- **CSS Animations**  
  - `@keyframes`, `animation-name`, `animation-duration`, `animation-timing-function`, `animation-iteration-count`




  
- **Advanced Topics**
  - Pseudo-elements (::before, ::after)
  - Pseudo-classes (:hover, :focus, :active, :nth-child, etc.)
  - CSS Variables
  - CSS Functions (calc(), var(), attr(), etc.)

- **Best Practices**
  - Naming conventions (BEM, OOCSS, SMACSS)
  - Code organization and structure
  - Performance optimization (minification, avoiding excessive specificity)

- **Tools**
  - CSS preprocessors (Sass, Less)
  - CSS frameworks (Bootstrap, Tailwind CSS)
  - CSS linting tools (Stylelint)
  - Browser Developer Tools
**9. CSS Preprocessors**  
- **Introduction to Sass/SCSS**  
  - Variables: `$primary-color: blue;`

  - Nesting selectors
 
  - Mixins: `@mixin rounded { border-radius: 5px; }`
 
  - Partials and imports: `@import 'file';`
 
  - Extends: `@extend .classname;`

  ## Miscellaneous

45. `opacity` - Sets the opacity level for an element.
46. `cursor` - Sets the type of cursor to display when pointing over an element.
47. `overflow` - Specifies what happens if content overflows an element's box.
48. `transform` - Applies transformations to an