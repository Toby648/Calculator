# Calculator

A Python 3 calculator used from the Terminal, built step by step in SCCM4910.
## What it will do
Add, subtract, multiply and divide two numbers; display the result.
## How to run it
Enter the venv using: source /opt/python-venv/sccm-4910/bin/activate
Run: ./run.sh

Enter the first number, operator (+ - * /), then second number.
The program prints Result: followed by the answer.

To stop the program, press ctrl + c

#How to test it
Make sure you are in the venv and have pytest installed
Run: ./check.sh

This should output that all tests have passed and should have an exit status of 0 if there are no errors.
