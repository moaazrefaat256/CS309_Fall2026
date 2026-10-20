# CS309_Fall2026 Assignment 3

This is the updated version of my web project for Assignment 3.

In this assignment, I focused on client-side form validation using JavaScript and dynamic table rendering with real-time search filtering.

---

## What's New in Assignment 3

* **Registration Form Validation (`validation.html`)**:
  * Added input fields for Name, Email, Password, Confirm Password, and Age.
  * Implemented real-time JavaScript validation checking user input as they type.
  * Displayed short error messages directly beneath each corresponding field when validation fails.
  * Prevented form submission if any field is invalid or missing.

* **Dynamic Data Table (`data.html`)**:
  * Created an array of objects in JavaScript representing person records.
  * Dynamically built and rendered the table rows using JavaScript.
  * Added a live search input box that filters the table rows instantly as the user types without requiring a button click.

* **External Styling (`css/style.css`)**:
  * Separated all CSS styling into an external stylesheet located in the `css/` folder.
  * Cleaned up the HTML markup to maintain a clean and modular project structure.

---

## File Structure

* `validation.html` - Registration form page with real-time JavaScript validation.
* `data.html` - Data table page with dynamic rendering and live search filtering.
* `css/style.css` - External stylesheet containing clean layout and styling rules.

---

## How to Run

1. Open `validation.html` or `data.html` in any web browser.
2. Test the form validation by submitting empty fields or mismatched passwords.
3. Test the data table by typing into the search box to filter records instantly.
