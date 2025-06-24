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

```js 

document.getElementById("heading");

```

---

## ✅ Common Methods:

| Method                          | Description                                   |
| ------------------------------- | --------------------------------------------- |
| `getElementById("id")`          | Select one element by ID                      |
| `getElementsByClassName("cls")` | Select all elements by class (HTMLCollection) |
| `getElementsByTagName("tag")`   | Select all elements by tag                    |
| `querySelector("selector")`     | Select the **first** match (CSS style)        |
| `querySelectorAll("selector")`  | Select **all** matches (NodeList)             |


---

## 🧪 Example:

### HTML:

```html 

<h1 id="title">Welcome</h1>

```

### JavaScript:

```js 

const title = document.getElementById("title");
title.innerText = "Hello Sajid!"; // Changes text

```

---

## 🛠️ Manipulating DOM Elements

### ☑️ 1. Change Text or HTML

```js

element.innerText = "New Text";   // Just text
element.innerHTML = "<b>Bold</b>"; // Includes HTML

```

### ☑️ 2. Change Style

```js 

element.style.color = "red";
element.style.backgroundColor = "black";

```

### ☑️ 3. Change Attributes

```js 

element.setAttribute("class", "active");
const cls = element.getAttribute("class");

```

### ☑️ 4. Add/Remove Classes

```js 

element.classList.add("highlight");
element.classList.remove("highlight");
element.classList.toggle("highlight");

```

### ☑️ 5. Create New Elements

```js 

const newPara = document.createElement("p");
newPara.innerText = "This is new!";
document.body.appendChild(newPara);

```

### ☑️ 6. Remove Elements

```js 

element.remove();

```

---

[Download DOM Cheatsheet](asset/javascript_dom_cheatsheet.pdf)
