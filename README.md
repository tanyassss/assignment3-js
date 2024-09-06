# Event Handling Practice

This project demonstrates basic event handling in JavaScript. It includes a webpage with several buttons, each of which responds to different events such as click, mouseover, mouseout, and double-click. The JavaScript code handles these events to perform various actions like changing button colors, displaying messages, hiding messages, and hiding buttons.

## Project Structure

- `index.html`: The main HTML file containing the button elements and associated messages.
- `script.js`: The JavaScript file containing event handling logic and DOM manipulations.

## How to Use

1. **Open `index.html` in a web browser.**

2. **Button Interactions:**
   - **Click**: Changes the button's background color to light blue.
   - **Mouseover**: Displays a message below the button.
   - **Mouseout**: Hides the message when the mouse moves away from the button.
   - **Double-click**: Hides the button from view.

## Code Explanation

### HTML Structure

- The HTML file includes:
  - Three buttons with unique `id` attributes.
  - Associated `div` elements with the class `message` to display messages when the mouse is over the buttons.

### JavaScript Code

- **`changeColor(event)`**: Changes the button's background color to light blue on click.
- **`showMessage(event)`**: Displays the associated message when the mouse is over the button.
- **`hideMessage(event)`**: Hides the associated message when the mouse moves away from the button.
- **`hideButton(event)`**: Hides the button when it is double-clicked.
- **Event Listeners**: Attached to each button to handle `click`, `mouseover`, `mouseout`, and `dblclick` events.

## How to Run

1. **Clone this repository to your local machine:**
   ```bash
   git clone <https://github.com/tanyassss/assignment3-js>
