# Portfolio Website

I'm building this site as my personal developer portfolio. It'll showcase projects, alongside my existing and developing skills and experience. 

## Features
- Clean, responsive layout
- Links to GitHub projects
- Built with HTML, CSS, and JavaScript

More info coming soon!


## Build Steps 

# 🛠️ Personal Project Tutorial Log – Navbar Build

This is a step-by-step log of building the navigation bar for my website. It includes what I did, how I did it, and why certain coding conventions were used (like double underscores, hashtags, timestamps, and Tab indentation). This is for my own understanding and to repeat the process confidently in future projects.

---

## 🕐 [12 May, 10:30 AM] – Project Setup

### ✅ What I did:
- Created a new folder and opened it in Visual Studio Code.
- Created `index.html`, `style.css`, and `script.js` files.
- Opened the Live Server extension to preview my work in real time.

---

## 🕐 [12 May, 10:45 AM] – Basic HTML Layout

### ✅ What I did:
- Typed out basic HTML boilerplate using `! + Tab` shortcut in VS Code.
- Added `<nav>` tag to create a semantic navigation section.
- Created a container `<div>` inside the nav.

### 💡 Why:
- Using semantic tags like `<nav>` improves accessibility and makes the purpose of sections clear to developers and screen readers.

---

## 🕐 [12 May, 11:00 AM] – Building the Navbar

### ✅ What I did:
- Added a logo using:
  ```html
  <a href="/" id="navbar__logo">NEXT</a>

I then added a mobile menu toggle using:
<div class="navbar__toggle" id="mobile-menu">
  <span class="bar"></span>
  <span class="bar"></span>
  <span class="bar"></span>
</div>

Created a list of nav links:
<ul class="navbar__menu">
  <li class="navbar__item">
    <a href="" class="navbar__links">Link</a>
  </li>
</ul>

The <a> tag creates a clickable link (logo in this case).

The three <span class="bar"> elements make the hamburger menu icon for mobile view.

Using a <ul> and <li> structure is best practice for navigation menus.

I used BEM (Block Element Modifier) naming convention for CSS class names.

Example:

navbar → the main block

navbar__container → an element inside navbar

navbar__toggle, navbar__menu, navbar__links etc.

## Why:

Keeps code organized and scalable

Makes it clear where each style belongs

Prevents naming conflicts as the site grows

When I use id="navbar__logo" in HTML, I can target it in CSS using:

#navbar__logo {
  font-size: 1.5rem;
}


### ✅ What I've Built So Far (Summary)
A semantic navigation bar with a logo and mobile menu

Structured and indented HTML using Tab

BEM naming convention for CSS classes

Setup ready for responsive design and JavaScript toggle

