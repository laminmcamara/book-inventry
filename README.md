# Book Inventory

A simple and interactive Book Inventory web application built as part of the freeCodeCamp Full Stack Curriculum.

---

## Overview

This project allows users to keep track of their books by managing their Title, Author, Category, Reading Status, and personal Rating. It uses semantic HTML tables styled with CSS and enhanced with JavaScript to dynamically add new books.

---

## Features

- Displays a book inventory with filled-in example entries.
- Books differentiated visually based on reading status: **Read**, **To Read**, and **In Progress**.
- Ratings are represented with colored dots (1 to 3 stars).
- Interactive form to add new books dynamically without page refresh.
- Clear visual feedback and accessibility enhancements (focus and hover styles).

---

## Usage

1. Clone or download this repository.
2. Open the `index.html` file in any modern web browser.
3. The table initially contains example books with placeholders filled for Title, Author, and Category.
4. Use the **Add Book** form above the table to enter new books:
   - Fill in all required fields: Title, Author, Category.
   - Select a Status and Rate from the dropdown menus.
   - Click **Add Book** to add the new entry to the table dynamically.
5. Newly added books will appear styled according to their status and rating.
6. No data persistence, so the added books will reset on page reload.

---

## Project Structure

- `index.html` — Main HTML markup with the form, table, and JavaScript logic.
- `styles.css` — Stylesheet for page styling, responsive layout, and interactive states.

bookinventry.png > this is the visual interpretation of the inventry

---

## Future Improvements

- Add **Edit** and **Delete** functionality for existing book entries.
- Implement persistent storage with `localStorage` or backend API.
- Add search and filter functionality.
- Enhance accessibility and responsive design.

---

## Author

Built and maintained by Lamin M Camara.
laminmasana@gmail.com

---

## License

This project is open-source and free to use for educational purposes.
