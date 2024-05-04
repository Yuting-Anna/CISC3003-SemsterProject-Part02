# CISC3003-SemsterProject-Part02
# Simple Shopping Cart System Using PHP PDO and MySQL Database 

## Project Overview

This project is a simple PHP-based Shopping Cart System website that allows users to add product and view products, add products to a shopping cart, check out and fill in onformation, and view orders. The website includes functionalities such as product display, shopping cart management, order processing.


## Technology Stack

- **Frontend**: HTML, CSS, JavaScript (using the SweetAlert library for pop-up notifications)
- **Backend**: PHP, PDO for MySQL (used for database interactions)
- **Database**: MySQL (used to store user information, product details, shopping cart, and order data)

## Security Features

- **Data Validation**: All data received from users is filtered and validated to prevent SQL injections and XSS attacks.
- **File Management**: Uploaded files (such as product images) are renamed to unique IDs to avoid filename conflicts and potential security risks.

## Page Components

- `add_product.php`: Adds new products to the database.
- `checkout.php`: Users fill in checkout information and submit orders.
- `orders.php`: Displays all orders of a user.
- `shopping_cart.php`: Manages the user's shopping cart, including adding, deleting items, or emptying the cart.
- `view_order.php`: Views detailed information of a single order, including the option to cancel the order.
- `view_products.php`: Displays all products available for purchase, with options to add to cart or buy now.

## Conclusion

This project is a Shopping Cart System website. This multi-page website has response design to adapt to different screen sizes.
