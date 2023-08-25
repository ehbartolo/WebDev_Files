# Notes on WebDev Class

## VS Code Extensions:

+ Live Preview

+ Prettier

+ vscode-icons

## Links
+ https://www.diffchecker.com/
+ colorhunt.co
+ pesticide in chrome

## Notes
boiler plate in vscode: <br>
` ! + Enter`

## Github Pages:
1. Settings
2. Pages
3. Branch: Select branch main

## CSS
### Types of CSS

+ Inline
+ Internal
+ External

### CSS Selectors

1. Element Selector, e.g., `element {color:red;}``
2. Class Selector, many elements, `.classname {}, <element class="classname">`
3. ID Selector, one element, `#id_name{},<element id="id_name">`
4. Attribute Selector, `p[draggable="false"]{}, <p draggable="true">`
5. Universal Selector, `*{}`

### CSS Notes
+ font size: 1px-1/96 inch, 1pt=1/72inch, 1em=100%parent, 1rem=100%root
+ fonts.google
+ Chrome developer tools for inspecting css
+ Chrome tool-> ...(more tools)->CSS overview->Capture overview

### Combining selectors
1. Group selector:<br>
```
selector1, selector2 {attribute: value;}
```
2. Child Selector:<br>
```
selector1 > selector2 {attribute: value;}
```
3. Descendant Selector <br>
Apply to descendant to the left
```
selector_ancestor selector_descendant {attribute: value;}
```
4. Chaining Selector <br>
Apply where ALL selectors are true
```
selector1selector {attribute: value;}
h1.class {attribute: value;}
```

### CSS Positioning

1. Static Positioning
2. Relative Positioning
3. Absolute Positioning
4. Fixed Positioning

### Displays
+ display: inline-block;
+ display: block

### CSS Float

Wrapping text using float and clear
```css
img {float: left; }
footer{clear: left; }
```
### Responsive Web Design
+ Media Query
```css
@media (max-width: 600px){
    h1 {
        font-size: 15px;
    }
}
/* CSS for screens below or equal to 600px wide*/
```

+ CSS Grid
```html
<div class = "grid-container">
    <div class = "first card"></div>
    <div class = "card"></div>
</div>
```
```css
.grid-container {
    display: grid;
    grid-template-columns: 1fr 1fr;
    grid-template-rows: 100px 200px 200px;
    gap: 30px;
}
.first {grid-column: span 2;}
.card {background-color: blue;}

```
+ CSS FlexBox

```html
<div class = "flex-container">
    <div class = "first card"></div>
    <div class = "second card"></div>
</div>
```
```css
.flex-container {
    display: flex;
}
.card {background-color: blue; flex:1}
.first {flex: 2;}
.second{background-color: blue; flex:0.5}
```
+ Bootstrap Framework
```html
<div class = "container">
    <div class = "row">
        <div class = "card col-6"></div>
    </div>
    
</div>
```
```css
.flex-container {
    display: flex;
}
.card {background-color: blue; flex:1}
.first {flex: 2;}
.second{background-color: blue; flex:0.5}
```

### Media Queries
Examples:
```css
@media (min-width: 600px) and (max-width: 900px){
    /* Styles for screens between 600px and 900px */
}
```
```css
@media screen(orientation: landscape){
    /* Styles for lanscape orientation */
}
```

### CSS FlexBox
```html
<div class="container">
 <div class="one"></div>
 <div class="two"></div>
</div>
```
```css
.container {
    display: flex;
    gap: 10px;
}
```

+ https://css-tricks.com/snippets/css/a-guide-to-flexbox/