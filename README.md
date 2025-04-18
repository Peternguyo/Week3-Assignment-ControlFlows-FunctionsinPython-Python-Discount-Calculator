# Python Discount Calculator 
This repository contains a Python script (`discount_calculator.py`) that implements a simple discount calculation based on a given percentage. This project was created as part of a Python learning assignment to practice function definition, conditional logic (`if/else`), user input, and basic error handling.

## Overview

The Python script does the following:

1.  **Defines a function `calculate_discount(price, discount_percent)`:**
    * Takes the original `price` of an item and the `discount_percent` as input.
    * Applies the discount **only if** the `discount_percent` is 20% or higher.
    * Returns the final price after the discount or the original price if no discount is applied.

2.  **Prompts the user for input:**
    * Asks the user to enter the original price of an item.
    * Asks the user to enter the discount percentage.

3.  **Utilizes the `calculate_discount` function:**
    * Calls the function with the user-provided price and discount percentage.

4.  **Prints the result:**
    * If a discount of 20% or more was applied, it prints the final discounted price.
    * Otherwise, it indicates that no discount was applied and prints the original price.

5.  **Includes basic error handling:**
    * Uses a `try-except` block to catch potential `ValueError` if the user enters non-numeric input for the price or discount.

## Files in this Repository

* `discount_calculator.py`: The main Python script containing the discount calculation logic and user interaction.
* `README.md`: This file, providing a description of the project.

## How to Run the Script

1.  Make sure you have Python installed on your system.
2.  Save the `discount_calculator.py` file to your local machine.
3.  Open a terminal or command prompt.
4.  Navigate to the directory where you saved the file.
5.  Run the script using the command: `python discount_calculator.py`
6.  Follow the prompts to enter the original price and discount percentage.

## Learning Objectives

This assignment demonstrates understanding of the following Python concepts:

* Function definition and usage.
* Parameters and return values.
* Conditional statements (`if`, `else`).
* User input (`input()`).
* Type conversion (`float()`).
* Basic error handling (`try`, `except`).
* String formatting (f-strings).

## Further Exploration

As a next step, you could consider enhancing this script by:

* Allowing discounts for percentages lower than 20%.
* Adding different discount tiers.
* Implementing a loop to calculate discounts for multiple items.
* Storing item names along with their prices.

Feel free to use and modify this code for your learning purposes!
