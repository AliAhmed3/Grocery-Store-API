# Grocery-Store-API-Testing
API Testing Project using Postman.

# About The Project

This project foucses on testing the Grocery-Store-API with Postman, Performing a range of API testing techniques to validate the functionality of essential endpoints and assess the system's reliability. The test suite features detailed test cases for creating, retrieving, updating, and deleting bookings.

## The API is available at
https://simple-grocery-store-api.glitch.me

## Overview
This API enables you to place a grocery order that will be prepared for in-store pickup.

## Key Features

- **Test Cases**: Tests for CRUD (Create, Read, Update, Delete) operations.
- **Postman Collection**: Configured in advance for ease of use and scalability.
- **Assertions**: Verified the status codes, response bodies, and headers using Postman assertions.
  
## API Scenarios Tested

- **Status**: retrieve the status of the API.
- **Products**: Verified Get all products and Returns a single product from the inventory..
- **Cart**: Verified Get a cart, Get cart items, Create a new cart, Add an item to cart, Modify an item in the cart, Replace an item in the cart,Delete an item in the cart.
- **Orders**: Verified Get all orders, Get a single order, Create a new order, Update an order, Delete an order.
- **API Authentication**: Tested Register a new API client.
## How to Run the Tests

1. Clone the repository:
   ```bash
   git clone https://github.com/AliAhmed3/Grocery-Store-API.git
   ```

2. Import the Postman collection from the `/Postman` folder into your Postman application.

3. Run the collection manually in Postman or by **Newman** for automation:
   ```bash
   newman run Grocery Store API.postman_collection.json
   ```
   you can also add: -r htmlextra at the end of the previous command to generate a HTML reporter which enable users to view better custom templates and provide an Interactive Report.
