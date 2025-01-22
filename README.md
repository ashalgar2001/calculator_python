Calculator Project

This is a simple Python-based calculator that performs basic arithmetic operations: addition, subtraction, multiplication, and division. The calculator allows users to perform continuous calculations or start a new calculation after each result.

Features --
Operations Supported:

Addition (+)
Subtraction (=)
Multiplication (*)
Division (/)

Interactive User Experience:
Continuously calculate using the result of the previous calculation.
Option to start a new calculation or exit the program.
Clear Screen: Resets the interface when starting a new calculation (platform-specific).

Prerequisites --

To run this project, you need:
Python 3 installed on your system.

How to Run --

Copy the script into a file named calculator.py.
Open your terminal or command prompt.
Navigate to the directory containing the calculator.py file.
Run the script using the command:
python calculator.py

How to Use --

Start the Program:
When you run the script, you’ll be prompted to enter the first number.

Choose an Operation:
The available operations will be displayed (+, =, *, /).
Pick an operation by entering the corresponding symbol.

Enter the Next Number:
Provide the second number for the operation.

View Result:
The program will display the result of the calculation.

Choose Next Step:
Enter y to continue calculating with the result.
Enter n to start a new calculation.
Enter x to exit the program.

Code Explanation --

Arithmetic Operations: Defined as individual functions (add, subtract, multiply, divide) that take two parameters and return the result.

Operation Dictionary: Maps operation symbols (+, =, *, /) to their corresponding functions for easy access.

User Interaction:
Prompts the user for inputs (numbers and operation choice).
Uses a loop to allow continuous calculations until the user exits.

Clear Screen:
The os.system('cls') command clears the console when a new calculation begins (works on Windows).

License --
This project is open-source and free to use.
