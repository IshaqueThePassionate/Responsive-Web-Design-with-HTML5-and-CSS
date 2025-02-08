# **Basic Structure of an HTML Page** 🏗️🌐

## Introduction ✨
An HTML page follows a **standard structure** that ensures proper document formatting and readability across web browsers. Below is a **basic HTML template**:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8" />
    <title>Web Page Structure</title>
</head>
<body>
</body>
</html>
```

This structure forms the foundation of an HTML document, ensuring it is correctly interpreted by web browsers. 📄💡

## Understanding HTML Tags & Elements 🏷️
When writing HTML, content is placed inside **tags** or **elements**.

### 1️⃣ **HTML Tags** 🔖
Tags are enclosed within **angle brackets** (`< >`) and define the purpose of the enclosed content. Most HTML elements consist of **an opening tag** and **a closing tag**:

✅ **Example of an opening and closing tag:**
```html
<p>This is a paragraph.</p>
```
- `<p>` → **Opening tag**
- `</p>` → **Closing tag**
- Content (`This is a paragraph.`) is wrapped between the tags.

### 2️⃣ **Void Elements (Self-Closing Tags)** 🚀
Some elements **do not wrap around content** and are called **void elements**. These tags **self-close**, meaning they **don’t need a closing tag**.

✅ **Example of a void element:**
```html
<meta charset="utf-8" />
```
- `<meta>` is **self-closing** because it does not contain inner content.

### 3️⃣ **List of Void Elements** 📜
Void elements do not require a closing tag. The following are **recognized void elements**:

🔗 [List of Void Elements](https://html.spec.whatwg.org/multipage/syntax.html#void-elements)

**Current void elements include:**
- `<area>`
- `<base>`
- `<br>`
- `<col>`
- `<embed>`
- `<hr>`
- `<img>`
- `<input>`
- `<link>`
- `<meta>`
- `<param>`
- `<source>`
- `<track>`
- `<wbr>`

## The `<head>` and `<body>` Sections 📌
### 1️⃣ **The `<head>` Section** 🧠
The `<head>` section contains metadata and settings for the page. This includes:
- Character encoding (`<meta charset="utf-8">`)
- Page title (`<title>Web Page Structure</title>`)
- Links to stylesheets (`<link rel="stylesheet" href="styles.css">`)

### 2️⃣ **The `<body>` Section** 💻
The `<body>` section is where the main **visible content** of the webpage is written. It contains:
- **Headings** (`<h1>` to `<h6>`)
- **Paragraphs** (`<p>`)
- **Lists** (`<ul>`, `<ol>`)
- **Images** (`<img>`)
- **Links** (`<a>`)
- **Forms** (`<form>`)

## Conclusion 🎯
Understanding the **basic structure of HTML** is the first step toward web development. The `<head>` contains important metadata, but the **majority of web content is placed in the `<body>` section**.


