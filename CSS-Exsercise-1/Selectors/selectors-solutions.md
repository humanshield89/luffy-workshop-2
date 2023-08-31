## Solution Exercise 1

```html
<!DOCTYPE html>
<html>
<head>
    <style>
        p {
            color: red;
        }

        .highlight {
            background-color: yellow;
        }
    </style>
</head>
<body>

<p>This is a paragraph.</p>
<p class="highlight">This is a highlighted paragraph.</p>

</body>
</html>
```

## Solution Exercise 2

```html
<!DOCTYPE html>
<html>
<head>
    <style>
        #header {
            background-color: blue;
            color: white;
        }
    </style>
</head>
<body>

<header id="header">Header Section</header>

</body>
</html>
```

## Solution Exercise 3

```html
<!DOCTYPE html>
<html>
<head>
    <style>
        .menu li {
            font-weight: bold;
        }
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

## Solution Exercise 4

```html
<!DOCTYPE html>
<html>
<head>
    <style>
        div > span {
            border: 1px solid black;
        }
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

## Solution Exercise 5

```html
<!DOCTYPE html>
<html>
<head>
    <style>
        .info + .note {
            font-style: italic;
        }
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

## Solution Exercise 6

```html
<!DOCTYPE html>
<html>
<head>
    <style>
        a[target="_blank"] {
            background-color: lightblue;
        }
    </style>
</head>
<body>

<a href="https://www.example.com" target="_blank">Open in new tab</a>
<a href="https://www.example2.com">Regular link</a>

</body>
</html>
```

## Solution Exercise 7

```html
<!DOCTYPE html>
<html>
<head>
    <style>
        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

<a href="#">Hover over me</a>

</body>
</html>
```

## Solution Exercise 8

```html
<!DOCTYPE html>
<html>
<head>
    <style>
        p::first-line {
            font-weight: bold;
        }
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

## Solution Exercise 9

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

## Solution Exercise 10

```html
<!DOCTYPE html>
<html>
<head>
    <style>
        .content p {
            margin: 10px;
        }
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