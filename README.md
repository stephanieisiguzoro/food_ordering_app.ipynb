# Food Ordering Application

A Python-based command-line application that simulates a food ordering system. Users can browse a menu, add items to their cart, and receive a detailed receipt upon checkout.

## Overview

This project demonstrates core programming concepts including user input validation, data structure manipulation, and modular function design. The application provides an interactive ordering experience with error handling to ensure data integrity.

## Features

- **Interactive Menu Display**: Browse available food items with pricing
- **Input Validation**: Ensures users enter valid menu choices and quantities
- **Shopping Cart Management**: Add multiple items in varying quantities
- **Dynamic Price Calculation**: Automatically calculates totals for individual items and entire orders
- **Detailed Receipt Generation**: Provides itemized order summary with total cost

## Menu Items

| Item | Price (₦) |
|------|-----------|
| Pizza | 6,500 |
| Burger | 3,000 |
| Noodles | 1,300 |

## Technical Skills Demonstrated

- **Data Structures**: Dictionary manipulation for cart management
- **Input Validation**: Error handling for user inputs
- **Function Modularity**: Separation of concerns across multiple functions
- **Control Flow**: Loops and conditional statements
- **User Interface**: Command-line interaction design

## How It Works

1. User selects items from the displayed menu
2. System validates the selection and prompts for quantity
3. Items are added to the shopping cart with calculated totals
4. User can continue ordering or exit to checkout
5. Final receipt displays all ordered items with a grand total

## Code Structure

The application consists of several key functions:
- `display_menu()`: Shows available food options
- `get_user_choice()`: Captures and validates menu selection
- `get_quantity()`: Validates quantity input
- `add_to_cart()`: Manages cart updates and price calculations
- `place_order()`: Orchestrates the ordering workflow
- `check_out()`: Generates final receipt

## Use Case

This project showcases programming fundamentals applicable to:
- E-commerce platforms
- Point-of-sale systems
- Inventory management
- Customer-facing applications

## Technologies Used

- Python 3
- Jupyter Notebook
- Standard library (unittest for testing)

---

*This project was developed as part of my programming coursework and demonstrates my ability to build functional applications from scratch.*
