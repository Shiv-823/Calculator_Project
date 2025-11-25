This file explains how the Calculator.py program works.

Overview

This Python script creates a calculator using the Tkinter library. It has a clean and simple interface where you can click buttons or use your keyboard to perform basic math operations.

Main Functions

append_to_display(value)
Adds a number or symbol to whatever is currently shown on the screen.

clear_display()
Clears everything on the display and resets it.

evaluate_expression()
Solves the math expression written on the display using Python's eval() function.
If the input is incorrect, it shows "Invalid Input".

on_key_press(event)
Handles keyboard inputs.
You can type numbers and operators.

Press Enter to calculate

Press Escape to clear the screen



User Interface

The calculator window has a dark theme.

A label at the top shows what you type and the result.

Buttons for numbers (0–9), decimal point, operators (+, −, ×, ÷), Clear (C), and Equals (=) are arranged neatly in a grid.

Number and operator buttons have a blue-grey color, while the "=" and "C" buttons are orange for better visibility.

The layout automatically adjusts when you resize the window.


Keyboard Support

You don’t have to use the buttons—typing works too:

Numbers and math symbols can be entered directly

Enter = calculate

Escape = clear
