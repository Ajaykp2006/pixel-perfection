# Prodesk IT - Project Context for AI Assistants

## Overview
This project is a landing page for **Prodesk IT**, a digital agency that builds digital experiences. The website highlights the company's focus on empowering businesses through web development, SEO optimization, and digital marketing strategies.

## Tech Stack
* **HTML5:** Structures the content, including a navigation bar, hero section, services grid, and a footer.
* **CSS3:** Handles styling with a focus on responsiveness and theming, utilizing CSS variables defined in a `:root` selector for colors, backgrounds, and shadows.
* **Vanilla JavaScript:** Manages interactive frontend elements, specifically a dark mode toggle and a mobile hamburger menu.

## Key Features
* **Theming (Dark/Light Mode):** The website supports a dynamic dark mode feature. The JavaScript checks `localStorage` for the saved theme upon DOM load and allows users to toggle between modes, appending or removing the `dark-mode` class on the document body. The CSS defines distinct background and text colors for the default light mode and the `.dark-mode` override.
* **Responsive Navigation:** The header contains a navigation menu that adapts to mobile devices. On viewports smaller than 768px, a hamburger menu button (☰) becomes visible. Clicking this button uses JavaScript to toggle an `active` class on the navigation links, transforming them into a dropdown menu.
* **Services Section:** A CSS Grid layout (`grid-template-columns: repeat(auto-fit, minmax(300px, 1fr))`) displays three core service cards: SEO Optimization, Web Development, and Digital Marketing. These cards feature a hover effect that translates them upwards and applies a shadow.
* **Footer:** Contains a copyright notice for 2026 and inline SVG social media icons for Twitter, LinkedIn, and GitHub.

## File Structure
* `index.html`: Contains the main semantic structure, including the `#home` and `#services` sections.
* `style.css`: Contains all visual styling, media queries for mobile responsiveness, and custom CSS theme variables.
* `response.js`: Handles DOM manipulation via event listeners for the `#theme-toggle` button, `#mobile-menu-btn`, and includes demo alert functionality for a `#contact-form` submission.
