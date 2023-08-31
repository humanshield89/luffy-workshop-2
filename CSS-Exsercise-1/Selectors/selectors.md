### Exercise 1: Basic Element and Class Selectors

Create a CSS rule that selects all paragraphs (`<p>`) on the page and changes their text color to red. Also, select all
elements with the class `highlight` and give them a yellow background color.

```html
<!DOCTYPE html>
<html>
<head>
    <style>
        /* Your CSS rule goes here */
    </style>
</head>
<body>

<p>This is a paragraph.</p>
<p class="highlight">This is a highlighted paragraph.</p>

</body>
</html>
```

### Exercise 2: ID Selector

Create a CSS rule that selects an element with the ID `header` and gives it a background color of blue and a white text
color.

```html
<!DOCTYPE html>
<html>
<head>
    <style>
        /* Your CSS rule goes here */
    </style>
</head>
<body>
<header id="header">Header Section</header>
</body>
</html>
```

### Exercise 3: Descendant Selector

Apply a CSS rule that selects all list items (`<li>`) that are descendants of an element with the class `menu`. Give
those list items a bold font weight.

```html
<!DOCTYPE html>
<html>
<head>
    <style>
        /* Your CSS rule goes here */
    </style>
</head>
<body>

<nav class="menu">
    <ul>
        <li>Item 1</li>
        <li>Item 2</li>
    </ul>
</nav>

</body>
</html>
```

### Exercise 4: Direct Child Selector

Select all immediate `<span>` children of `<div>` elements and give them a border.

```html
<!DOCTYPE html>
<html>
<head>
    <style>
        /* Your CSS rule goes here */
    </style>
</head>
<body>

<div>
    <span>This is a direct child span.</span>
    <p>This is a paragraph.</p>
</div>

</body>
</html>

```

### Exercise 5: Adjacent Sibling Selector

Select all elements with the class `info` that are immediately followed by an element with the class `note`. Change the
font style of the `info` element to italic.

```html
<!DOCTYPE html>
<html>
<head>
    <style>
        /* Your CSS rule goes here */
    </style>
</head>
<body>

<p class="info">This is an informative paragraph.</p>
<p class="note">This is a note.</p>
<p class="info">Another informative paragraph.</p>
<p class="note">Another note.</p>

</body>
</html>

```

### Exercise 6: Attribute Selector

Apply a CSS rule that selects all anchor elements (`<a>`) with a `target` attribute set to `_blank`. Give them a
different background color.

```html
<!DOCTYPE html>
<html>
<head>
    <style>
        /* Your CSS rule goes here */
    </style>
</head>
<body>

<a href="https://www.example.com" target="_blank">Open in new tab</a>
<a href="https://www.example2.com">Regular link</a>

</body>
</html>
```

### Exercise 7: Pseudo-class Selector

Create a rule that selects all links (`<a>`) that are being hovered over and underline them.

```html
<!DOCTYPE html>
<html>
<head>
    <style>
        /* Your CSS rule goes here */
    </style>
</head>
<body>

<a href="#">Hover over me</a>

</body>
</html>
```

### Exercise 8: Pseudo-element Selector

Select the first line of every paragraph and make it bold using the `::first-line` pseudo-element.

```html
<!DOCTYPE html>
<html>
<head>
    <style>
        /* Your CSS rule goes here */
    </style>
</head>
<body>

<p>This is the first line of a paragraph. It should be bold.</p>
<p>This is the first line of another paragraph. It should also be bold.
    <br>But this line should not be bold.
</p>

</body>
</html>

```

### Exercise 9: Grouping Selectors

Select all headers (`<h1>`, `<h2>`, `<h3>`, etc.) and give them a consistent font family and size.

```html
<!DOCTYPE html>
<html>
<head>
    <style>
      h1, h2, h3, h4, h5, h6 {
        font-family: Arial, sans-serif;
        font-size: 24px;
      }
    </style>
</head>
<body>

    <h1>Header 1</h1>
    <h2>Header 2</h2>
    <h3>Header 3</h3>

</body>
</html>
```
### Exercise 10: Combining Selectors

```html
<!DOCTYPE html>
<html>
<head>
    <style>
        /* Your CSS rule goes here */
    </style>
</head>
<body>

<div class="content">
    <p>This is a paragraph inside a content section.</p>
    <p>Another paragraph here.</p>
</div>

</body>
</html>

```



Create a rule that selects all paragraphs (`<p>`) that are descendants of a `<div>` with the class `content`. Give them
a margin of 10 pixels.

