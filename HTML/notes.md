# HTML Notes (Beginner to Pro)

## 1. Introduction to HTML

* **HTML (HyperText Markup Language)** is the standard language for creating web pages.
* HTML documents are made of **elements** represented using **tags**.
* Browsers read HTML and display content visually.

---

## 2. Basic Structure of an HTML Document

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
</head>
<body>
  Content goes here.
</body>
</html>
```

### Key Tags:

* `<!DOCTYPE html>` → Defines HTML5
* `<html>` → Root element
* `<head>` → Metadata, title, links
* `<body>` → Visible content

---

## 3. HTML Elements & Tags

### Common Tags:

* Headings: `<h1>` to `<h6>`
* Paragraph: `<p>`
* Line break: `<br>`
* Horizontal line: `<hr>`
* Comments: `<!-- comment -->`

---

## 4. Text Formatting Tags

* Bold: `<b>`, `<strong>`
* Italic: `<i>`, `<em>`
* Underline: `<u>`
* Small text: `<small>`
* Subscript: `<sub>`
* Superscript: `<sup>`

---

## 5. Links & Anchors

### Basic link:

```html
<a href="https://google.com">Google</a>
```

### New tab:

```html
<a href="https://google.com" target="_blank">Google</a>
```

### Email link:

```html
<a href="mailto:example@mail.com">Send Email</a>
```

---

## 6. Images

```html
<img src="image.jpg" alt="description" width="300" />
```

* `alt` helps SEO + accessibility

---

## 7. Lists

### Unordered List

```html
<ul>
  <li>Item 1</li>
  <li>Item 2</li>
</ul>
```

### Ordered List

```html
<ol>
  <li>Step 1</li>
  <li>Step 2</li>
</ol>
```

### Description List

```html
<dl>
  <dt>HTML</dt>
  <dd>HyperText Markup Language</dd>
</dl>
```

---

## 8. Tables

```html
<table border="1">
  <tr>
    <th>Name</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>John</td>
    <td>20</td>
  </tr>
</table>
```

### Table tags:

* `<table>`
* `<tr>` row
* `<td>` cell
* `<th>` header
* `<caption>` title

---

## 9. Forms

```html
<form action="submit.php" method="POST">
  <label>Name:</label>
  <input type="text" name="username" required />

  <label>Password:</label>
  <input type="password" name="password" />

  <input type="submit" value="Submit" />
</form>
```

### Input Types:

* `text`
* `email`
* `password`
* `number`
* `checkbox`
* `radio`
* `file`
* `date`
* `color`
* `range`
* `submit`

---

## 10. Semantic HTML

Improves SEO & accessibility.

Examples:

* `<header>`
* `<nav>`
* `<section>`
* `<article>`
* `<footer>`
* `<aside>`
* `<main>`

---

## 11. Multimedia

### Audio

```html
<audio controls>
  <source src="song.mp3" type="audio/mpeg" />
</audio>
```

### Video

```html
<video width="400" controls>
  <source src="video.mp4" type="video/mp4" />
</video>
```

---

## 12. Iframes

```html
<iframe src="https://example.com" width="500" height="300"></iframe>
```

Allows embedding websites, maps, videos.

---

## 13. Block vs Inline Elements

### Block elements:

* `<div>`, `<p>`, `<h1>`, `<section>`, `<ul>`

### Inline elements:

* `<span>`, `<a>`, `<img>`, `<strong>`

---

## 14. Div & Span

### Div

Used for layout & grouping

```html
<div class="container"></div>
```

### Span

Used to style inline text

```html
<span class="highlight">Text</span>
```

---

## 15. HTML Entities

Used when symbols conflict with HTML syntax:

* `&lt;` → <
* `&gt;` → >
* `&amp;` → &
* `&copy;` → ©

---

## 16. Meta Tags

```html
<meta name="description" content="Best website" />
<meta name="keywords" content="HTML, CSS" />
```

Helps SEO & responsiveness.

---

## 17. HTML Forms Advanced

### Dropdowns

```html
<select>
  <option>India</option>
  <option>USA</option>
</select>
```

### Textarea

```html
<textarea rows="5" cols="30"></textarea>
```

### Fieldset

```html
<fieldset>
  <legend>Details</legend>
</fieldset>
```

---

## 18. IDs vs Classes

* **ID:** unique, one per element
* **Class:** reusable

```html
<div id="header"></div>
<div class="card"></div>
```

---

## 19. File Paths

### Absolute

```
https://example.com/image.png
```

### Relative

```
/images/photo.png
```

---

## 20. HTML Best Practices

* Use semantic structure
* Keep code clean, commented
* Use proper indentation
* Optimize images
* Always include `alt` text

---

## 21. Advanced Topics

### 1. Canvas API

```html
<canvas id="myCanvas"></canvas>
```

Allows drawing shapes, animations.

### 2. SVG

```html
<svg width="100" height="100">
  <circle cx="50" cy="50" r="40" />
</svg>
```

### 3. Web Storage API

* `localStorage`
* `sessionStorage`

### 4. HTML APIs

* Geolocation
* Drag & Drop
* WebSockets
* Web Workers

---

## 22. Cheatsheet

* `<div>` = block container
* `<span>` = inline text wrapper
* `<table>` = structured data
* `<form>` = input collection
* `<img>` = show image
* `<a>` = hyperlink
* `<section>` = semantic block
* `<iframe>` = embed content

---

## 23. Conclusion

This full guide covers everything from **HTML basics to pro-level concepts**, suitable for learning, revision, or GitHub documentation. Update it as you grow!
