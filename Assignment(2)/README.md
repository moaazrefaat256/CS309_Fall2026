\# CS309\_Fall2026 Assignment 2 



This is the updated version of my Campus Cafe website for Assignment 2. 



I expanded the original setup to make it responsive, added new CSS components, built in dark mode, and improved the accessibility score.



\---



\## What's New in Assignment 2



Responsive Design: Used CSS Grid and media queries so the page layout adjusts to screen size. It goes from 1 column on mobile, to 2 columns on tablets, and 3 columns on desktop screens.



Component Library:

&#x20;  Form Controls: Custom styled input fields, select dropdowns, and buttons.

&#x20;  CSS-Only Modal: A popup window for promotions made entirely with CSS using the `:target` selector (no JavaScript used).

&#x20;  Alert Box: A styled notification banner at the top of the home page for updates/announcements.



Dark Mode Support: Added `@media (prefers-color-scheme: dark)` so the website automatically switches to a dark color scheme based on system settings.



Accessibility Fixes: Added proper labels, proper contrast ratios, focus outlines for keyboard navigation, and ARIA attributes. Tested it with Chrome DevTools Lighthouse to make sure the Accessibility score is well above 90.



\---



\## File Structure



index.html - Main page with the new grid layout, alert banner, menu table, and CSS modal.

about.html - Info page updated with responsive card layouts.

contact.html - Form page with updated custom styled form elements.

css/style.css - Contains all styles, media queries, CSS variables, and dark mode rules.



\---



\## How to Run



Just open `index.html` in any web browser or use VS Code Live Server. 

You can resize the browser window or use DevTools to test the responsive breakpoints and dark mode.

