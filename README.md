# Grocery List Application

This project is a simple, responsive Grocery List web application where users can add items to a list, cross them off, and clear the list when needed. The application features interactive functionalities implemented using JavaScript and styled with CSS for a visually appealing experience.

## Features

- Add grocery items to the list.
- Cross off items by clicking on them.
- Clear the entire list by clicking the pencil icon.
- Fully responsive design, optimized for both desktop and mobile screens.

## Technologies Used

- **HTML5** for the structure of the application.
- **CSS3** for styling and layout.
- **JavaScript** for interactivity.
- **Font Awesome** for icons.

## File Structure

```
.
|-- index.html    # Main HTML file
|-- style.css     # Stylesheet
|-- script.js     # JavaScript file for interactivity
```

## How to Run

1. Clone or download this repository to your local machine.
2. Open the `index.html` file in a web browser to view the application.

## Usage

1. Type an item into the input box.
2. Press **Enter** to add the item to the list.
3. Click an item to mark it as completed (strikethrough).
4. Click the pencil icon to clear all items from the list.

## Code Overview

### HTML (`index.html`)
- The structure includes a container for the grocery list with an input field, a clear button (pencil icon), and a display area for the items.
- The `id` attributes are used to target elements in the JavaScript file.

### CSS (`style.css`)
- Styles for the container and elements to ensure a neat layout.
- Responsive styles using media queries for better display on small screens.

### JavaScript (`script.js`)
- Adds functionality:
  - Handles `Enter` key press to add an item.
  - Allows clicking items to mark them as completed with a strikethrough.
  - Clears the entire list when the pencil icon is clicked.

## Responsive Design
- The application adjusts its layout for devices with smaller screens using a media query targeting screens with a width of 320px or less.

## External Resources
- [Font Awesome](https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.2/css/all.min.css): Used for the pencil icon.

## Future Enhancements
- Add local storage support to persist the list items.
- Include options to delete individual items.
- Enhance the UI with animations.

---

Enjoy using the Grocery List application!

