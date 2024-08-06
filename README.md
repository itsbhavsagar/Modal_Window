
# Modal Window

This project demonstrates a simple modal window implementation using HTML, CSS, and JavaScript. The modal window is displayed when a button is clicked and can be closed by either clicking a close button, the overlay, or pressing the `Escape` key.

## Files

- `index.html`: Contains the structure of the modal and buttons.
- `style.css`: Defines the styling for the modal, buttons, and overlay.
- `script.js`: Manages the functionality of opening and closing the modal.

## Installation

1. Clone the repository or download the files.
2. Ensure you have a modern web browser to view the project.

## Usage

1. Open `index.html` in a web browser.
2. Click any of the "Show modal" buttons to open the modal window.
3. The modal can be closed by:
   - Clicking the `×` button.
   - Clicking outside the modal on the overlay.
   - Pressing the `Escape` key on the keyboard.

## Code Explanation

### HTML (`index.html`)

- The file includes a basic HTML structure with buttons to open the modal.
- The modal window and overlay are initially hidden using the `hidden` class.
- The modal content includes a title, a paragraph of text, and a close button.

### CSS (`style.css`)

- **General Styling**: Sets base styles for body, buttons, and text.
- **Modal Styling**: Centers the modal window, adds padding, border radius, and shadow.
- **Overlay Styling**: Covers the entire viewport with a semi-transparent background.

### JavaScript (`script.js`)

- **Selectors**: Targets modal, overlay, close button, and open buttons.
- **Functions**:
  - `openModal()`: Shows the modal and overlay.
  - `closeModal()`: Hides the modal and overlay.
- **Event Listeners**:
  - Adds click event listeners to open buttons to trigger `openModal()`.
  - Adds click event listeners to the close button and overlay to trigger `closeModal()`.
  - Adds a keyboard event listener to close the modal with the `Escape` key.

## Contributing

Feel free to fork the repository and submit pull requests if you have suggestions or improvements.

## License

This project is licensed under the MIT License 
