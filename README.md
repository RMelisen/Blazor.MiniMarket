# 🛒 Product and Shopping Cart Management Application (Blazor Standalone)

Small Blazor Standalone application to manage a list of products and a shopping cart. This application will make no API calls: all data must be stored in memory.

## 🎯 Objectives

The application allows the user to:

1. **Display the list of available products**

- Each product must contain at least: Name, Price, Discount (%), Description.

 2. **Add a new product**

- A form will allow to enter the information for a new product.

3. **Modify an existing product**

- The user should be able to modify a product's information (for example, its price or description).

4. **Delete a product**

- The user should be able to remove a product from the list.

 5. **Add a product to the cart**

- The user can add one or more products to a shopping cart.

 6. **Manage the quantity of each product in the cart**

- If a product is already in the cart, adding the same product increases the number of units.

 7. Visually display significant discounts

 - Any product with a discount of 50% or more must appear with its name in red in the product list.

## ✅ Technical Constraints

- Blazor Standalone only.
- No data persistence.
