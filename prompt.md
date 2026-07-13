# Prodesk IT - Project Context for AI Assistants

## Overview
This project is a landing page for **Prodesk IT**, a digital agency that builds digital experiences. The website highlights the company's focus on empowering businesses through web development, SEO optimization, and digital marketing strategies.


## AI Prompt Log: Core Functionality & Debugging
To accelerate the development process and resolve specific blockers, I utilized AI (Gemini) during this sprint. Below is the log of the prompts used:

**Prompt 1**
* **Tool Used:** Gemini
* **Prompt:** "How do I implement a dark and light mode toggle using CSS variables and JavaScript, and ensure the user's preference is saved when they refresh the page?"
* **Help Received:** Learned how to use `localStorage` in JavaScript to store the theme state. Understood the logic of toggling a `.dark-mode` class on the `<body>` element to seamlessly switch between the color variables defined in the `:root` CSS selector.

**Prompt 2**
* **Tool Used:** Gemini
* **Prompt:** "How can I create a mobile hamburger menu that hides the navigation links by default on small screens and reveals them in a dropdown when clicked?"
* **Help Received:** Understood how to combine CSS media queries (`display: none` by default on mobile) with JavaScript. Learned to use an event listener on the hamburger button (`#mobile-menu-btn`) to toggle an `.active` class on the navigation container, switching its display to `flex` when triggered.

**Prompt 3**
* **Tool Used:** Gemini
* **Prompt:** "My logo image is stretching and breaking the navbar layout. How do I size the `<img>` tag correctly so it fits well within the header without distortion?"
* **Help Received:** Learned to apply a specific fixed height (e.g., `height: 80px`) alongside `width: auto` to the `.custom-logo` class. This ensures the image maintains its original aspect ratio while perfectly fitting into the flexbox layout of the navigation bar.

**Prompt 4**
* **Tool Used:** Gemini
* **Prompt:** "The page refreshes instantly every time I try to test my contact form submission. How can I debug this to stop the refresh and just show a success message?"
* **Help Received:** Identified the default behavior of HTML forms. Learned to pass the `event` object into the submit listener and utilize `event.preventDefault()` to stop the page reload. This allowed for the implementation of a custom `alert()` and the `contactForm.reset()` method to clear the inputs.

**Prompt 5**
* **Tool Used:** Gemini
* **Prompt:** "How can I make this layout friendly to mobile devices and ensure it looks polished on smaller screens?"
* **Help Received:** Understood the importance of fluid grid definitions (`minmax(300px, 1fr)`) to prevent card breakage on mobile views. Learned to configure clean spacing using fluid padding/margin rules (`rem` or `em` units rather than fixed pixels) and applied targeted media queries to ensure layout elements stack neatly, keeping touch targets large enough for a smooth mobile user experience.
