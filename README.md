# Learn DOM concept In JavaScript

Let’s dive deep into the DOM (Document Object Model) in JavaScript — but in a clear, beginner-friendly, and structured way. This is a core concept for web development and essential for any frontend developer like you!

## 🌐 What is the DOM?

### DOM = Document Object Model

🌟The DOM is a tree-like structure that represents your HTML document as JavaScript objects. It allows JavaScript to interact with, modify, or read the HTML and CSS of a webpage.

## 📜 HTML Example:

```html 

<!DOCTYPE html>
<html>
  <head><title>My Page</title></head>
  <body>
    <h1 id="heading">Hello Sajid!</h1>
    <button onclick="changeText()">Click Me</button>
  </body>
</html>

```

## 📌 DOM View (Tree):

```less 

document
 └── html
      ├── head
      └── body
           ├── h1 (id="heading")
           └── button (onclick="...")

```

## 🧠 Why is DOM Important?

It allows you to:

- Add/change/remove HTML elements ✅

- Handle user events (click, type, scroll, etc.)✅

- Change CSS dynamically ✅

- Make dynamic UI like forms, games, animations, etc. ✅


## 🔍 Accessing the DOM

Everything starts from the document object:

```javascript 

document.getElementById("heading")

```

[Download DOM Cheatsheet](asset/javascript_dom_cheatsheet.pdf)
