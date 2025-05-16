# 🌐 Portfolio Website

This is my personal developer portfolio site, built from scratch using HTML, CSS, and JavaScript. The purpose of this project is to practice fundamental web development skills and create a clean, responsive portfolio that showcases my work, skills, and learning progress.

---

## Features So Far

- Responsive navigation bar
- Semantic HTML structure
- Gradient-styled logo
- CSS structured using BEM (Block Element Modifier) naming convention
- Clean layout with Flexbox
- Git version control and incremental commits

---

## Tech Stack

- HTML5
- CSS3 (Flexbox, Gradients, Responsive Layout)
- JavaScript (planned)
- Git & GitHub

---

## Project Setup

- Created a new project folder in VS Code
- Files: `index.html`, `style.css`, `script.js`
- Live preview using Live Server extension

---

## Build Log

### [12 May, 10:45 AM] – Basic HTML Layout

- Used `! + Tab` in VS Code to generate HTML boilerplate
- Added `<nav>` element with semantic structure
- Inserted a `<div>` container inside the nav
- Applied BEM naming to prepare for organized CSS

### [12 May, 11:00 AM] – Navigation Bar Structure

- Added logo with:
  ```html
  <a href="/" id="navbar__logo">NEXT</a>
Added mobile menu toggle (hamburger icon):

html
Copy
Edit
<div class="navbar__toggle" id="mobile-menu">
  <span class="bar"></span>
  <span class="bar"></span>
  <span class="bar"></span>
</div>

Added a list of navigation links using <ul> and <li>

Began using BEM naming (e.g. navbar__container, navbar__menu, etc.)

### [13 May, 11:30 AM] – CSS Setup and Navbar Styling

Added global CSS reset:

css
Copy
Edit
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Courier New', Courier, monospace;
}
Styled .navbar:

Set height, background color, and Flexbox alignment

Used position: sticky and z-index to keep navbar fixed and layered above other content

## Navbar Logo Styling

[13 May, later] – Styled the Logo with Gradient Text
Replaced id="navbar__logo" with class="navbar__logo" to follow BEM convention

Applied a linear gradient background clipped to text for visual impact

css
Copy
Edit
.navbar__logo {
  background-color: #ff8177;
  background-image: linear-gradient(to top, #ff0804 0%, #ffb199 100%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-decoration-color: transparent;
  display: flex;
  align-items: center;
  cursor: pointer;
  text-decoration: none;
  font-size: 2rem;
}

## Why I Made the Change

IDs (#) should be unique and are not reusable

BEM and class-based styling (.) are more flexible and scalable

Using .navbar__logo keeps naming consistent with the rest of the layout

## What I've Learned So Far

Semantic HTML improves accessibility and structure

Flexbox is a powerful tool for aligning and spacing content

BEM naming helps organize and scale CSS

Gradient text effects using background-clip and text-fill-color

The importance of committing meaningful changes using Git


### [16 May] – Navbar Styling Implementation


Implemented a responsive navigation menu using Flexbox for horizontal alignment and spacing.

.navbar__menu set up as a flex container to align items centrally.

.navbar__item given a fixed height of 80px for consistent vertical spacing.

.navbar__links styled to:

Use full height and padding for a larger click target

Center content both vertically and horizontally

Transition to a highlight color (#f77062) on hover for interactivity

Button Design
Created a .button class with:

Centered content using Flexbox

Full height and width for a uniform clickable area

Rounded corners and no outline or border

Default background color of #f77062 with a smooth hover transition to #4837ff

Buttons wrapped in .navbar__btn to ensure alignment within the navbar layout

Icon Spacing
Applied a right margin (0.5rem) to .fa-gem to create visual separation from adjacent text or elements



