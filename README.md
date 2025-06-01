# Calculator App

A basic calculator GUI application built with Python and Tkinter. It supports addition, subtraction, multiplication, division, parentheses, decimal numbers, and exponentiation.

## Features

- Basic User-friendly graphical interface  
- Basic arithmetic operations: `+`, `-`, `*`, `/`
- Parentheses for grouping expressions `( )`  
- Decimal point support  
- Exponentiation using `^` symbol (interpreted as power)  
- Clear and reset functionality  
- Error handling for invalid inputs and division by zero  

## How to Run

1. Make sure you have Python installed (version 3.x recommended).  
2. Tkinter is included by default in most Python installations.  
3. Save the code to a file, for example, `calculator.py`.  
4. Run the program using the command:  
   ```bash
   python calculator.py
5. The calculator window will open. Use the buttons to enter expressions and calculate results.

## Running the standalone executable [No need to clone repo]
If you have the standalone executable created using PyInstaller (Calculator.exe):
Locatation:   
      
      \dist\Calculator.exe

1. Download or copy the Calculator.exe file to your computer.
2. Double-click the executable to launch the calculator app.
3. Use the buttons to enter expressions and calculate results.

## How It Works

- The app uses the `eval()` function to compute the result from the entered expression, replacing `^` with `**` for exponentiation.
- Input is gathered through buttons that append characters to the current equation shown on the display.
- The equals button evaluates the expression and shows the result.
- The clear button resets the input field.
- Basic error handling displays "Error" on invalid input or divide-by-zero cases.

## Dependencies

- Python standard library  
- Tkinter GUI toolkit (usually included with Python)
