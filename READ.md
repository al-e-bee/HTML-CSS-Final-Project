# Personal Portfolio Landing Page

### _From Figma Design to Responsive Reality_

---

## Project Overview

This project is a high-fidelity recreation of a professional Figma portfolio template, rebranded to showcase my personal identity as a developer. It demonstrates advanced CSS techniques, including custom grid layouts, complex border effects, and mobile-first responsiveness.

## Brand Identity

- **Primary Palette:** Deep Navy (`#002379`) and Warm Cream (`#FFFAE6`).
- **Accent Color:** Vibrant Orange (`#ff5f00`) for Call-to-Action elements.
- **Typography:** A sophisticated mix of _Merriweather_ for headers and _Inter_ for body text.

---

## Technical Deep Dive

### 1. Responsive Layout Architecture

Implemented a global `.container` system that manages a max-width of `1100px`. This ensures the content remains perfectly aligned across ultrawide monitors while remaining fluid on mobile devices.

### 2. Advanced CSS Effects

- **Fading Testimonial Borders:** Created a custom "fade-out" border effect using `::before` pseudo-elements combined with `linear-gradient` and `mask-composite` to allow for both a color fade and rounded corners.
- **Z-Pattern Case Studies:** Utilized `nth-of-type(even)` selectors to automatically flip the layout of every second project card, creating a dynamic visual flow.
- **Interactive Elements:** Integrated Font Awesome icons with Flexbox centering to create perfectly circular, hover-active navigation arrows and social links.

### 3. Dynamic Navigation

- **Smooth Scroll:** Global implementation of `scroll-behavior: smooth` for elegant in-page jumping.
- **Back to Top Logic:** A custom JavaScript-powered button that monitors scroll depth—appearing only after the user has scrolled `400px` and hiding automatically on mobile devices to optimize screen real estate.
- **Mobile Menu:** A fully functional "Hamburger" toggle menu for seamless navigation on small screens.

---

## Mobile-First Optimization

The site features a robust media query breakpoint at `599px` that:

- Converts side-by-side Hero and Case Study layouts into centered vertical stacks.
- Transforms the 2-column testimonial grid into a single-column list.
- Optimizes touch targets for mobile users by hiding non-essential desktop navigation arrows.

---

## How to Run Locally

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/al-e-bee/landing-page-project.git](https://github.com/al-e-bee/landing-page-project.git)
    ```
2.  **Navigate to the project folder:**
    ```bash
    cd landing-page-project
    ```
3.  **Open in Browser:** Launch `index.html` to view the live site.

## Let's Connect

- **GitHub:** [al-e-bee](https://github.com/al-e-bee)
- **LinkedIn:** [Ali Baker](https://linkedin.com/in/ali-baker-6070313b3)

---

_Developed by Ali Baker — 2026_
