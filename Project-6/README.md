# 🌐 Simple Website Landing Page

This project is a clean and modern **landing page website** built using only **HTML and CSS**.
It demonstrates layout design, navigation bar styling, background image overlay, and centered content positioning.

---

## 📌 Project Overview

This webpage contains:

* Fixed navigation bar
* Logo section
* Menu links
* Full-screen background image
* Centered heading text
* Subtitle text
* Two styled buttons

The design is simple, responsive-friendly, and beginner-friendly.

---

## 🛠 Technologies Used

* HTML5
* CSS3
* Google Fonts (Poppins)

---

## 📂 Folder Structure

```
Project-6
│── index.html
│── app.css
│── images/
      └── layout.jpg
```

---

## 🧱 HTML Structure Explanation

### 1️⃣ Navigation Bar

```
<nav>
```

Used for top menu section.

Contains:

* Logo
* Menu links

---

### 2️⃣ Logo Section

```
<div class="logo">
```

Displays site name **LogicHuntress**

---

### 3️⃣ Menu List

```
<ul>
```

Contains navigation links:

* Home
* About
* Services
* Contact
* Feedback

---

### 4️⃣ Background Image Section

```
<div class="img"></div>
```

Used to display full-screen background image using CSS.

---

### 5️⃣ Center Content

```
<div class="center">
```

Contains:

* Main title
* Subtitle
* Buttons

---

## 🎨 CSS Styling Explanation

### ✔ Reset Styles

```
* { margin:0; padding:0; box-sizing:border-box; }
```

Removes default browser spacing.

---

### ✔ Navbar Styling

* Dark background
* Fixed position
* Flexbox alignment
* Hover effect on links

---

### ✔ Background Image

```
background: url(images/layout.jpg) no-repeat center;
background-size: cover;
```

Makes image fill entire screen.

---

### ✔ Overlay Effect

```
.img::before
```

Adds dark transparent layer above image for better text visibility.

---

### ✔ Center Alignment Trick

```
top:50%;
left:50%;
transform: translate(-50%,-50%);
```

Perfectly centers content horizontally & vertically.

---

### ✔ Buttons

* Border styled
* Hover effect
* Smooth transition

---

## 🎯 Features

✔ Fixed Navbar
✔ Fullscreen Background
✔ Overlay Effect
✔ Centered Content
✔ Hover Animations
✔ Clean UI Design

---

## 🚀 How to Run Project

1. Download project files
2. Open folder
3. Double click **index.html**

---

## 📚 Learning Concepts Used

* Flexbox layout
* Positioning
* Pseudo elements
* Hover effects
* Transform property
* Background image handling

---

## 💡 Author

Created by **LogicHuntress** ✨

---

⭐ If you like this project, give it a star on GitHub!
