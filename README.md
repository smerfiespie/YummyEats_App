# YummyEats_App
CRUD operations 
An API with complex validation for managing dishes and orders for a food delivery app.

 Routes for managing dishes (CRUD - Create, Read, Update, and List)
 Routes for managing orders (CRUDL - Create, Read, Update, Delete, and List)

Middleware functions for validation and error handling
RESTful design principles

## Use Node.js version 18 (node -v).

## Dishes:
- GET /dishes: Lists all dishes.
- POST /dishes: Creates a new dish.
- GET /dishes/:dishId: Retrieves a specific dish by ID.
- PUT /dishes/:dishId: Updates a dish by ID.

## Orders:
- GET /orders: Lists all orders.
- POST /orders: Creates a new order.
- GET /orders/:orderId: Retrieves a specific order by ID.
- PUT /orders/:orderId: Updates an order by ID.
- DELETE /orders/:orderId: Deletes an order by ID (only allowed for pending orders).

## Error Handling:
Error handing with status codes and messages 
