# Product Cart Component

This is a simple web component that allows users to view available products and add them to a cart. The component consists of two boxes displayed side by side: one for the available products and the other for the cart. Users can add or remove products from the cart, and the total amount of the cart is displayed at the bottom.

## Features

- Display a list of available products with buttons to add or remove them from the cart.
- Display the cart with the list of products added, along with their quantities and total prices.
- Update the total amount of the cart dynamically as products are added or removed.
- Show a message if no products are added to the cart.

## Usage

1. Clone or download the repository to your local machine.
2. Open the `index.html` file in a web browser.
3. View the available products and interact with the buttons to add or remove products from the cart.
4. Observe the changes in the cart and the total amount as products are added or removed.

## Technologies Used

- HTML
- CSS
- JavaScript

## File Structure

- `index.html`: Contains the HTML structure of the component and the script for functionality.
- `styles.css`: Contains the CSS styles for the component.
- `script.js`:  Contains the JavaScript code that handles user interactions and updates the UI accordingly.
- `README.md`: This file, providing information about the component and its usage.

## How It Works

The component is built using HTML, CSS, and JavaScript. Upon loading the page, the available products are displayed in the left box, with buttons to add or remove them from the cart. The cart is displayed in the right box, initially showing a message if no products are added.

When a user clicks the "+" button next to a product, it is added to the cart. If the same product is already in the cart, its quantity is incremented. If the "-" button is clicked, the quantity of the product in the cart is decremented, and if the quantity becomes zero, the product is removed from the cart.

The total amount of the cart is updated dynamically as products are added or removed. This ensures that users can see the total cost of their selected items at all times.
