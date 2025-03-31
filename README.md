# COMP 248 - Assignment 3

## Written by:
**Julian Vafiadis**  
Student ID: 40310616  
For COMP 248 Section H – Fall 2024

---

## Overview

This repository contains two Java programs developed for **COMP 248**:

1. **ATM System**: A simple ATM simulation that allows users to check balance, deposit money, and withdraw money. The withdrawal option ensures that the requested amount is dispensed in $50, $10, and $5 bills.
2. **Inventory Management System**: A program to manage an inventory of 5 products. Users can view the product list, update quantities, search for products, and find the product with the lowest quantity and highest price.

---

## Features

### ATM System

- **Check Balance**: Displays the current account balance.
- **Deposit**: Allows the user to deposit money, ensuring the deposit amount is a multiple of 5 and between $5 and $10,000.
- **Withdraw**: Allows the user to withdraw money, dispensing it in $50, $10, and $5 bills. The withdrawal is validated against the current balance and the required multiple of 5.
- **Exit**: Exits the ATM system with a goodbye message.

### Inventory Management System

- **Display Products**: Shows the name, price, and quantity of all products in the inventory.
- **Update Quantity**: Allows users to update the stock quantity of a specific product.
- **Search for Product**: Allows users to search for a product by name and display its details.
- **Find Lowest Quantity Product**: Displays the product with the lowest stock quantity.
- **Find Highest Price Product**: Displays the product with the highest price in the inventory.
- **Exit**: Exits the program.

---

## Usage

1. **ATM System**:  
   - When prompted, select an option (1-4) to interact with the ATM.
   - Deposit amounts must be multiples of 5, and withdrawals will be split into $50, $10, and $5 bills.

2. **Inventory Management System**:  
   - Enter the details of 5 products (name, price, quantity) when prompted.
   - Navigate the menu to view product details, update stock, or search for specific products.

---

## How to Run

1. Clone or download this repository to your local machine.
2. Open the project folder in your favorite Java IDE (e.g., IntelliJ IDEA, Eclipse).
3. Compile and run the program(s) of your choice.
4. Follow the on-screen prompts to interact with the programs.

---

## Dependencies

- Java (JDK 8 or higher) is required to run these programs.

---

## Author

**Julian Vafiadis**  
Student at Concordia University
