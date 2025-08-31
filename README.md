
# 🚀 Learning 30 Days, 30 Projects — HTML,CSS,Java Script Series

Welcome to my **30 days, 30 projects journey**! 🎉
Each day, I’ll create a small project using **HTML, CSS, and JavaScript**, and learn something new.

---

## 📅 Day 1 — 29.08.2025

**Project:** Drag & Drop 👐
**Duration:** \~10 minutes
**Skills Learned:**

* Connecting **HTML + CSS + JavaScript** for the first time
* Using **draggable attribute**
* JavaScript **DOM methods** and **event listeners**
* `dragstart`, `dragover`, `drop` events
* Moving elements dynamically with `appendChild`

**Project Description:**
I created two boxes (`left` and `right`) and added draggable list items. I learned how to drag items from one box to another, and also learned **how to use JS to control the DOM** dynamically.

---

### ⚡ Quick Emoji Cheat Sheet — JS Methods / Events Used

* 🏷️ `document.getElementsByClassName()` → select all elements with a class
* 🎯 `document.getElementById()` → select a single element with an ID
* ✋ `draggable="true"` → make element draggable
* 🚀 `dragstart` → fires when dragging starts
* 🛬 `dragover` → fires when dragging over a drop zone (must call `e.preventDefault()`)
* 👐 `drop` → fires when you release the dragged element on a drop zone
* 📦 `e` → event object, tells you what happened
* 🎯 `e.target` → the element being dragged
* 🚫 `e.preventDefault()` → allow drop by canceling default behavior
* 👂 `addEventListener()` → attach event handler to element
* 🧺 `appendChild()` → move/attach element into another element
* ✋ `selected` → variable holding the dragged element
* 🔄 `for...of` → loop through all items

---

### 📂 Folder Structure

```
HTML_JS_Series/
│── DragAndDrop/       # Day 1 project
│   │── index.html
│   │── style.css
│   │── script.js
│   │── README.md      # This explains the project in detail
```

---

### ✅ Takeaways

* Learned **how to connect HTML, CSS, and JS together**
* Understood **event objects, targets, and drag-drop mechanics**
* Ready to practice **more JS methods** in the next projects

---


# 🌐 Day 2 — Simple Website Project

**Project Date:** 30.08.2025
**Duration:** ~40 Mins

---

## 📝 Project Description

For Day 2 of my **30 Days, 30 Projects — HTML, CSS, JavaScript Series**, I built a **basic website** using only HTML and CSS (with optional JavaScript if needed).

This project helped me understand how to:

* Structure a webpage with semantic **HTML elements**
* Apply **CSS styling** for layout, colors, and typography
* Create a **navigation bar / sections** for a clean UI
* Organize content like **header, about section, and footer**

---

## 🛠️ Skills Learned

* 📄 Writing semantic HTML (`<header>`, `<section>`, `<footer>`)
* 🎨 CSS basics (colors, fonts, margins, paddings)
* 🧱 Layout design with **flexbox / grid**
* 🔗 Creating **links, buttons, and navigation menus**
* 🎯 Importance of folder structure in projects

---

## ⚡ Features of the Website

✔️ A clean **homepage layout**
✔️ Responsive **navigation bar**
✔️ Styled **text and sections** with CSS
✔️ Ready to expand with **JavaScript interactivity**

---

## ⚡ Quick Emoji Cheat Sheet

🧭 `<nav>` → Navigation bar
🏷️ `.class` → Apply style to multiple elements
🎯 `#id` → Target a unique element
📐 `position` → Relative & absolute positioning
🧩 `flexbox` → Flexible alignment and layout
✨ `:hover` → Interactive hover effect
🎬 `transition` → Smooth animations
📝 `font-family` → Control text style

---


## 📂 Folder Structure

```
HTML_JS_Series/
│── Website/          # Day 2 project
│   │── index.html    # Main HTML file
│   │── style.css     # Stylesheet for website
│   │── script.js     # (Optional, for future interactivity)
│   │── README.md     # Project documentation
```

---

## ✅ Takeaways

* Learned to **design a simple static website**
* Understood **CSS styling & layout** more clearly
* Set the foundation for future projects where I’ll add **interactivity with JavaScript**

---
Perfect 👍 Here’s a clean **Day 3 README** for your **Horizontal Scrolling Gallery** project:

---

# 📅 Day 3 — Horizontal Scrolling Gallery

**Project Date:** 31.08.2025
**Duration:** \~60 minutes

---

## 📝 Project Description

For Day 3 of my **30 Days, 30 Projects — HTML, CSS, JavaScript Series**, I built a **Horizontal Scrolling Image Gallery**.
This project allows users to:

* Scroll horizontally using the **mouse wheel**
* Navigate with **Next** ⏭️ and **Back** ⏮️ buttons
* Enjoy a **smooth scrolling animation**
* See images in **grayscale** that turn **colorful & zoom** on hover 🎨

This project combines **HTML (structure)**, **CSS (design & layout)**, and **JavaScript (scrolling behavior)**.

---

## 🛠️ Skills Learned

* 🎯 DOM selection with `querySelector()` & `getElementById()`
* 🖱️ Handling `wheel` events for horizontal scroll
* 🚫 Using `preventDefault()` to stop vertical scroll
* 📜 Understanding `scrollLeft` and smooth scrolling behavior
* 🎨 CSS Grid & Flexbox combination for layout
* ✨ Hover effects (`filter`, `transform`, `transition`)

---

## ⚡ Quick Emoji Cheat Sheet — CSS + JS Concepts

### 🟦 JavaScript

* 🖱️ `wheel` → detects mouse scroll
* 🚫 `preventDefault()` → stops normal vertical scroll
* ↔️ `scrollLeft` → moves container horizontally
* 🖲️ `addEventListener()` → attach scroll & button actions
* 🖼️ `querySelector()` → grab first matching element
* ⏮️ `backBtn` / ⏭️ `nextBtn` → scroll buttons

### 🎨 CSS

* 📐 `margin` → space outside element
* 🧱 `padding` → space inside element
* 🧩 `display: grid` → arrange items in rows/columns
* 🧭 `grid-gap` → spacing between grid cells
* 📦 `flexbox` → align gallery & buttons
* 🎬 `transition` → smooth effect
* ✨ `:hover` → interactive styling
* 🎨 `filter: grayscale()` → black & white effect

---

## 📂 Folder Structure

```
HTML_JS_Series/
│── HorizontalGallery/   # Day 3 project
│   │── index.html       # Main HTML file  # Scrolling logic
│   │── styles.css       # Styling (layout, hover, effects)
│   │── images/          # back.png, next.png, image-1.png … image-6.png
│   │── README.md        # Project documentation
```

---

## ✅ Takeaways

* Learned to **convert vertical scroll → horizontal scroll**
* Understood how to use **scrollLeft** for controlling horizontal movement
* Practiced **CSS Grid + Flexbox** for a mixed layout
* Added **hover animations** for better UI/UX
* First real project combining **all 3 (HTML + CSS + JS) in sync** 🎉

---


