# simple-calculator
A simple Python calculator that performs basic arithmetic operations (+, -, *, /).
```python
print("Welcome! Ready to calculate your answer?")
num1 = float(input("Enter the first number: "))
num2 = float(input("Enter the second number: "))
operation = input("Choose an operation (+,-,/,*): ")

if operation == "+":
    print("Result:", num1 + num2)
elif operation == "-":
    print("Result:", num1 - num2)
elif operation == "*":
    print("Result:", num1 * num2)
elif operation == "/":
    if num2 != 0:
        print("Result:", num1 / num2)
    else:
        print("Error: Division by zero is not allowed!")
else:
    print("Error: Invalid operation choice!")
```
