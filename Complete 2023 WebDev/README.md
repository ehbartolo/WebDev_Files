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