# To-Do list

This is a simple to-do list application implemented in JavaScript. The application allows users to add items to a to-do list, mark items as done by clicking on them, and prevent entering items by pressing enter in a text area.

## Getting Started

To use this application, simply open the `index.html` file in your web browser. You can then start adding items to your to-do list.

## Usage

- To add a new item to the list, type the item into the input field and press "Enter" or click the "Add" button.
- To mark an item as done, click on the item in the list. Clicking again will undo the "done" status.
- To prevent adding an item when pressing "Enter" in a text area (e.g., when editing an existing item), the application checks if the key pressed is not the "Enter" key.

## Code overview

- The JavaScript code listens for click events on the list items (`<li>` elements) and toggles their "done" class when clicked.
- The `displayListItem` function adds a new item to the list based on user input.
- The `checkEnter` function prevents the default behavior of the "Enter" key when pressed in a form element.
- The `send` function is triggered when the form is submitted and adds the inputted item to the list.

## Credits

This application was created by @maesangaline.

---

A demo of this app can be found [here](https://codepen.io/maesangaline/pen/PoowpQX).
