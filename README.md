Name: Yogita Dixit Company: CODTECH IT SOLUTIONS ID: CT6WDS1632  Mentor name: Muzammil Ahmed Domain: Web Development Duration: August to September 2024
# Overview
![Screenshot 2024-08-21 211156](https://github.com/user-attachments/assets/5f7258cb-fab0-4412-923f-5e3a6430975a)

![Screenshot 2024-08-21 211226](https://github.com/user-attachments/assets/ecbb76bd-5504-4ee6-805c-03fe9888e2ad)

This e-commerce platform is a basic web application built using HTML, CSS, and JavaScript. It simulates the core functionalities of an online shopping website, enabling users to browse products, add items to a cart, make purchases, and manage their orders. Here's an overview of the key components and features:

### 1. **Homepage (index.html)**
   - **Product Display**: The homepage displays a list of products fetched from a JSON file (`products.json`). Each product is shown with its name, image, price, and an "Add to Cart" button.
   - **Search Functionality**: Users can search for products by typing keywords into the search bar. The search results dynamically filter the displayed products.
   - **Filters**: Users can filter products by category. Checkboxes allow users to select which categories they want to view.

### 2. **Cart Page (cart.html)**
   - **Cart Items Display**: This page displays the items that users have added to their cart. Each item shows its name and price.
   - **Checkout Button**: Users can proceed to the checkout page by clicking the "Checkout" button.

### 3. **Checkout Page (checkout.html)**
   - **Payment Form**: A simple payment form is provided where users can enter their card number, expiry date, and CVV to simulate a purchase.
   - **Order Placement**: Upon form submission, the order is recorded, and the cart is cleared. The user is then redirected to the orders page.

### 4. **Orders Page (orders.html)**
   - **Order History**: Displays a list of all the orders that the user has placed. Each order shows the product name and price.

### 5. **Product Data (products.json)**
   - **JSON File**: This file contains an array of product objects, each with an `id`, `name`, `price`, `image`, and `category`. The data is used to populate the homepage with product information.

### 6. **User Interactions and Local Storage**
   - **Adding to Cart**: When a user adds a product to the cart, it is stored in the browser's local storage. This allows the cart to persist across page reloads and different sessions.
   - **Order Management**: Orders are also stored in local storage, allowing users to view their order history even after closing the browser.

### 7. **Design and User Interface**
   - **Responsive Design**: The platform is styled with basic CSS to be responsive and user-friendly. It includes a header with navigation, a search bar, and a footer.
   - **Product Cards**: Products are displayed in a grid layout, with each product card showing the product's image, name, and price.

### 8. **JavaScript Functionality (script.js)**
   - **Dynamic Content**: The product list, cart items, and order history are dynamically generated using JavaScript based on the data stored in `products.json` and local storage.
   - **Event Handling**: Various event listeners handle user actions such as adding items to the cart, searching for products, and submitting the payment form.

### 9. **Features Summary**
   - **Product Browsing**: Users can view products, search by name, and filter by category.
   - **Shopping Cart**: Users can add products to the cart and view the cart contents.
   - **Checkout Process**: Users can enter payment details and place an order.
   - **Order History**: Users can view a list of their past orders.
   - **Data Persistence**: Local storage is used to persist cart items and orders between sessions.

### 10. **Potential Enhancements**
   - **User Authentication**: Implementing login and registration for personalized user accounts.
   - **Backend Integration**: Connecting to a backend server for product management, order processing, and secure payment handling.
   - **Advanced Search and Filtering**: Adding more advanced search options, sorting, and filtering by price, rating, etc.
   - **Real Payment Gateway**: Integrating with a real payment gateway like Stripe or PayPal for secure transactions.

This platform serves as a foundational project for understanding the core concepts of e-commerce development. It provides a hands-on opportunity to learn how to manage products, handle user interactions, and store data locally using web technologies.
