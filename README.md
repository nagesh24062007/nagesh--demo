# nagesh--demo
This my Frist Repo
CALCULATOR USING PAYTHON

 def calculator():
  
    num1 = float(input("Enter first number: "))
    operator = input("Enter operator (+, -, *, /,%): ")
    num2 = float(input("Enter second number: "))

    if operator == "+":
        result = num1 + num2
    elif operator == "-":
        result = num1 - num2
    elif operator == "*":
        result = num1 * num2
    elif operator == "/":
        if num2 != 0:
            result = num1 / num2
        else:
            return " Division by zero!"
    
    elif operator.lower() == "%": 
        if num2 != 0:
            result = num1 % num2
        else:
            return " Division by zero in modulus!"
    else:
        return "Invalid operator!"

    return f"Result: {result}"


print(calculator())

