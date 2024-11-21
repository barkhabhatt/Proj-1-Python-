# 590016170 BARKHA BHATT 

## Modern GUI Calculator

A sleek and user-friendly calculator application built with Python and Tkinter. This calculator features a modern design with color-coded buttons and smooth operation for basic arithmetic calculations.

## Description

This calculator application provides a graphical user interface for performing basic mathematical operations. It features:
- Clean and intuitive interface
- Color-coded buttons for better user experience
- Error handling for invalid calculations
- Support for basic arithmetic operations (+, -, *, /)

## Screenshots

![image](https://github.com/user-attachments/assets/e18b7a6c-d8d0-42c9-9d6e-9457eed8834b)




## Requirements

- Python 3.x
- Tkinter (usually comes pre-installed with Python)

## Function Descriptions

### Class: CalculatorApp

#### `__init__(self, root)`
- Initializes the calculator window
- Sets up the display and creates the button grid
- Configures the initial styling and layout

#### `button_click(self, value)`
- Handles all button click events
- Parameters:
  -  The value of the button clicked (number, operator, or command)
- Functionality:
  - Processes numeric inputs
  - Handles arithmetic operations
  - Performs calculations when '=' is pressed
  - Clears display when 'C' is pressed
  - Includes error handling for invalid calculations

## Features

1. **Display Window**
   - Large, easy-to-read display
   - Right-aligned text for better readability

2. **Operation Buttons**
   - Addition (+)
   - Subtraction (-)
   - Multiplication (*)
   - Division (/)

3. **Special Buttons**
   - Clear (C): Resets the calculator
   - Equals (=): Computes the result

4. **Color Coding**
   - Numbers: Light gray
   - Operators: Light blue
   - Clear: Light red
   - Equals: Light green
