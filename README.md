# 🧡 Swiggy Front-End Clone

A pixel-perfect, fully responsive web clone of the Swiggy home landing page built from scratch. This project was developed to practice semantic HTML structures, advanced CSS layout systems, pixel-accurate alignment, and layering mechanics.

Live Demo Link: 👉https://github.io
 

---

## 🚀 Key Visual & Functional Features

### 1. Fixed Header Navigation
* **Sleek Layout:** Features a high-contrast navigation panel utilizing a solid orange background brand identity.
* **Component Tags:** Clean inline button elements for operational links like `Sign In`, `Get the App`, and `Swiggy Corporate`.

### 2. Dual-Input Hero Section
* **Centered Controls:** Custom Flexbox wrapper grouping both the **Delivery Location** and **Main Menu Search Bar** side-by-side.
* **Proportional Scaling:** Dynamic sizing controls allowing the search bar to occupy twice the width of the location tracker.

### 3. Edge-Locked Floating Assets
* **Absolute Positioning:** Visual background objects (Veggies Bag on the left, Sushi Plate on the right) anchored directly to the left and right screen boundaries.
* **Layout Isolation:** Integrated with strategic `z-index` layering to ensure input elements remain clean and fully clickable over images.

### 4. Interactive Double-Row Food Carousel
* **Compact Tracking:** Dynamic vertical multi-row flex container rendering 14 staple categories like Biryani, Pizzas, and Burgers across two alternating horizontal rows.
* **Micro-Animations:** Fluid layout transformations triggering hover scale shifts (`scale(1.06)`) on food thumbnails.
* **Seamless Scroll:** Native browser scroll tracks are hidden globally to retain modern UI/UX principles.

### 5. Instamart Grocery Section & Cities Map
* **Categorized Blocks:** Structured item cells built over a clean gray background grid layer (`#f4f4f5`) to catalog grocery segments.
* **CSS Grid Gridwork:** A highly structured 4-column framework displaying cities with food delivery across a uniform system.

### 6. Corporate Footer Index
* **Dark-Mode Footer:** A robust brand directory matching Swiggy’s actual site experience.
* **Bottom Legal Strip:** Final interface wrapper managing platform accessibility terms, cookie directives, and inline social icons.

---

## 🛠️ Architecture & Tech Stack

* **HTML5 Markup:** Strict compliance using semantic layout tags (`<nav>`, `<main>`, `<section>`, `<footer>`).
* **CSS3 Custom Layouts:** Advanced Flexbox row/column handling, explicit CSS Grid rules, viewport height math (`calc(100vh - 150px)`), overlay rules (`position: absolute`), and hidden scroll engines.
