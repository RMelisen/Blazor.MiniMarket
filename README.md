🛒 Product and Shopping Cart Management Application (Blazor Standalone)
Small Blazor Standalone application to manage a list of products and a shopping cart. This application will make no API calls: all data must be stored in memory (in local lists).

🎯 Objectives
The application allows the user to:

- Display the list of available products

- Each product must contain at least: Name, Price, Discount (%), Description.
- Add a new product

- A form will allow to enter the information for a new product.
- Modify an existing product

- The user should be able to modify a product's information (for example, its price or description).
- Delete a product

- The user should be able to remove a product from the list.
- Add a product to the cart

- The user can add one or more products to a shopping cart.
- Manage the quantity of each product in the cart

- If a product is already in the cart, adding the same product should increase the number of units, not create a new line.
- Visually display significant discounts

Any product with a discount of 50% or more must appear with its name in red in the product list.
✅ Technical Constraints
- Use Blazor Standalone only.
- No data persistence (everything is in memory).