# 🍽 Mama's Kitchen — Website

A simple restaurant website built with plain HTML and CSS.

---

## 📁 File Structure

```
restaurant.html   ← the entire website (one file)
```

---

## 🚀 How to Run

1. Download `restaurant.html`
2. Double-click the file
3. It opens straight in your browser — done!

> No installs. No server. No setup needed.

---

## 🗂 How the Website is Built

The site is one single HTML file with five sections that flow top to bottom:

### 1. 🔴 Navigation Bar
- Shows the restaurant logo on the left
- Has three links: **Menu**, **About**, **Contact**
- Clicking a link smoothly scrolls to that section on the page

### 2. 🏠 Hero Section
- The welcome banner at the top
- Has a heading, a short description, and a **"See Our Menu"** button
- The button scrolls the user down to the Menu section

### 3. 🍲 Menu Section
- Displays 6 food/drink items in a grid
- Each item has an emoji icon, a name, a short description, and a price in **KES**
- Cards lift up slightly when you hover over them

### 4. 📖 About Section
- A short paragraph about the restaurant's story
- Centered text on a warm background

### 5. 📍 Contact Section
- Shows three pieces of info side by side:
  - Address
  - Phone number
  - Opening hours

### 6. 🔻 Footer
- Simple footer with copyright text at the bottom

---

## ✏️ How to Customize

| What to change | Where to find it |
|---|---|
| Restaurant name | `<div class="logo">` and `<title>` |
| Hero text | Inside `<section class="hero">` |
| Menu items | Each `<div class="menu-card">` block |
| Prices | `<div class="price">` inside each card |
| About story | Inside `<section id="about">` |
| Address & phone | Inside `<section id="contact">` |
| Colors | `#c0392b` (red) in the `<style>` block |

---

## 🛠 Built With

- HTML5
- CSS3
- [Google Fonts](https://fonts.google.com/) — Playfair Display & Lato

---

*Made with ❤️ in Nairobi.*