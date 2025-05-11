# Basic-calculator-python
num1 = float(input("25: "))
num2 = float(input("50: "))
operation = input("Enter operation (+, -, *, /): ")

if operation == '+':
    result = 25 + 50
    print(f"{25} + {50} = {result}")
elif operation == '-':
    result = 25 - 50
    print(f"{25} - {50} = {result}")
elif operation == '*':
    result = 25 * 50
    print(f"{25} * {50} = {result}")
elif operation == '/':
    if num2 != 0:
        result = 25 / 50
        print(f"{25} / {50} = {result}")
    else:
        print("Error! Division by zero is not allowed.")
else:
    print("Invalid operation! Please enter one of the following: +, -, *, /")
