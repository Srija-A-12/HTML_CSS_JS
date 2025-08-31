

# 📂 Horizontal Scrolling Gallery

This project is a **horizontal scrolling image gallery** built using **HTML, CSS, and JavaScript**.
It allows users to scroll through images using:

* **Mouse wheel** (vertical scrolling translates into horizontal scrolling).
* **Navigation buttons** (`Back` and `Next`).
* **Hover effect** (images become colored and zoom in slightly).

---

## 🚀 Features

✅ Smooth horizontal scrolling
✅ Previous/Next buttons to navigate
✅ Hover grayscale-to-color effect
✅ Responsive layout with CSS Grid and Flexbox
✅ Scrollbar hidden for clean design

---

## 📜 Project Structure

```
├── index.html     # Main HTML file
├── styles.css     # CSS styling
└── images/        # Folder containing images (image-1.png, back.png, next.png, etc.)
```

---

## 🖼️ How It Looks

* Background is **dark gray (`#191919`)**
* Gallery is **centered**
* Images are arranged in **rows of 3 using CSS Grid**
* User scrolls **horizontally** through multiple image groups

---

## ⚙️ JavaScript Explanation

```javascript
let scrollContainer = document.querySelector(".gallery");
let backBtn = document.getElementById("backBtn");
let nextBtn = document.getElementById("nextBtn");

// Scroll with mouse wheel
scrollContainer.addEventListener("wheel", (evt) => {
    evt.preventDefault(); // stop vertical scroll
    scrollContainer.scrollLeft += evt.deltaY; // move horizontally
    scrollContainer.style.scrollBehavior = "smooth"; // smooth scroll
});

// Next button → scroll right
nextBtn.addEventListener("click", () => {
    scrollContainer.style.scrollBehavior = "smooth";
    scrollContainer.scrollLeft += 900; // move right by 900px
});

// Back button → scroll left
backBtn.addEventListener("click", () => {
    scrollContainer.scrollLeft -= 900; // move left by 900px
});
```

### 📝 Breakdown

* **`scrollLeft`** → Controls how far content is scrolled horizontally.
* **`evt.deltaY`** → Gets vertical scroll amount (mouse wheel). We redirect it horizontally.
* **`preventDefault()`** → Stops default vertical scrolling.
* **`scrollBehavior = "smooth"`** → Makes scrolling smooth, not instant.

---



# 🟢 **CSS Concepts **



### **1. Margin**

* Space **outside** an element (between element & neighbors).
* Think of it as the "outer gap".

📍 Example  code:

```css
.gallery-wrap{
    margin: 10% auto;
}
```

👉 Puts space around the gallery container.

**Visual:**

```
[ MARGIN ]
------------
|  ELEMENT  |
------------
```

---

### **2. Padding**

* Space **inside** an element (between border & content).
* Think of it as the "inner cushion".

📍 Example in your code:

```css
.gallery div{
    padding: 10px;
}
```

👉 Adds space inside each grid box so the image isn’t sticking to the border.

**Visual:**

```
------------
| PADDING  |
| CONTENT  |
------------
```

---

### **3. Grid**

* A layout system dividing a container into rows & columns.

📍 Example in your code:

```css
.gallery div{
    display: grid;
    grid-template-columns: auto auto auto;
}
```

👉 This means:

* Each `div` inside `.gallery` will display its children (images) in **3 columns**.

**Visual:**

```
| img1 | img2 | img3 |
```

---

### **4. Grid-gap**

* Space **between grid items** (rows/columns).

📍 Example:

```css
grid-gap: 20px;
```

👉 Creates **20px spacing** between each image.

**Visual:**

```
| img1 |---gap---| img2 |---gap---| img3 |
```

---



**A layout model to align elements horizontally or vertically.**

👉 Example:

```css
.gallery-wrap {
  display: flex;
  align-items: center;   /* vertically centered */
  justify-content: center; /* horizontally centered */
}
```

📦📦📦 → neatly arranged in a row.

---

### 🔹 Hover Effects

```css
.gallery div img:hover {
    filter: grayscale(0);   /* show full color */
    transform: scale(1.1);  /* zoom effect */
    cursor: pointer;
}
```

When user hovers:
🖼️ → becomes colored + zooms in slightly.

---

## 🎯 Summary

* **HTML** → Structure of the gallery
* **CSS** → Styling (grid, flexbox, margins, padding, hover effects)
* **JS** → Controls scrolling behavior (wheel + buttons)

---

