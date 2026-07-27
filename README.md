# simple-calculator
A simple Python calculator that performs basic arithmetic operations (+, -, *, /, %).
```python
print("=== Welcome to the Simple Calculator ===")

num1 = float(input("Enter the first number: "))
num2 = float(input("Enter the second number: "))
operation = input("Choose an operation (+, -, *, /, %): ").strip()

result = None

if operation == "+":
    result = num1 + num2

elif operation == "-":
    result = num1 - num2

elif operation == "*":
    result = num1 * num2

elif operation == "/":
    if num2 != 0:
        result = num1 / num2
    else:
        print("Error: Division by zero is not allowed.")

elif operation == "%":
    if num2 != 0:
        result = num1 % num2
    else:
        print("Error: Modulo by zero is not allowed.")

else:
    print("Error: Invalid operation!")

if result is not None:
    print(f"Result = {result}")

print("Thank you for using the calculator!")
```