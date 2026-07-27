# Simple Calculator
A simple Python calculator that performs basic arithmetic operations (+, -, *, /, %).
```python
print("Welcome! Ready to calculate your answer?")

num1 = float(input("Enter the first number: "))
num2 = float(input("Enter the second number: "))
operation = input("Choose an operation (+, -, *, /, %): ").strip()

if operation == "+":
    print("Result =", num1 + num2)

elif operation == "-":
    print("Result =", num1 - num2)

elif operation == "*":
    print("Result =", num1 * num2)

elif operation == "/":
    if num2 != 0:
        print("Result =", num1 / num2)
    else:
        print("Error: Division by zero is not allowed.")

elif operation == "%":
    if num2 != 0:
        print("Result =", num1 % num2)
    else:
        print("Error: Modulo by zero is not allowed.")

else:
    print("Error: Invalid operation choice!")

print("Thank you for using the calculator!")

```