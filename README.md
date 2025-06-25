# 🛍️ Product Filter E-commerce Website

A clean and responsive **product filtering app** built with HTML, CSS, and JavaScript. This mini project lets users **filter food items** like Pizza, Cake, and Ice Cream using buttons or a live search box.

---

## 🔍 Overview

This is a simple front-end project that demonstrates:

- 🧠 Category-based filtering using buttons  
- 🧃 Live search functionality with JavaScript  
- 📸 Responsive grid layout for product images  
- ✨ Hover zoom effects on images
- 

## 🎯 Features

✅ Filter by product category (Pizza, Cake, Ice Cream)  
✅ Search products live by typing  
✅ Highlight active filter button  
✅ Smooth image zoom on hover  
✅ Fully responsive layout  

---


## 🛠️ Tech Stack

| Technology | Usage |
|------------|-------|
| HTML5      | Page structure |
| CSS3       | Styling & layout |
| JavaScript | Logic, filtering, and DOM interaction |
| Google Fonts | Beautiful, modern typography (Inter) |

---
## 📦 How It Works

### 🔘 Filter Buttons

- Buttons use `data-filter` attributes (`pizza`, `cake`, `icecream`, `all`)
- On click, it filters `.box` elements by comparing with their `data-item`

### 🔍 Live Search

- Textbox filters products in real-time
- Matches input with `data-item` values

### 🧠 JavaScript Logic

| Functionality | Description |
|---------------|-------------|
| `setActiveBtn()` | Highlights the clicked filter button |
| `searchBox.addEventListener()` | Filters as you type |
| `buttons.forEach()` | Filters by category on click |

---



