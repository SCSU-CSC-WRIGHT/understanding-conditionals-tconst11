# flow-control-conditions

## Temperature Check
Write a Python program that asks the user to input the current temperature in Celsius. If the temperature is above 30 degrees, print "It's a hot day." Otherwise, print "The weather is cool."

temperature = float(input("Enter the current temperature in Celsius: "))

if temperature > 30:
  print("It's a hot day.")
else:
  print("The weather is cool.")
  
## Number Comparison
Write a program that asks the user to input two numbers. Use an if condition to print which number is larger or if they are equal.
num1 = float(input("Enter the first number: "))
num2 = float(input("Enter the second number: "))

if num1 > num2:
  print(f"{num1} is larger.")
elif num1 < num2:
  print(f"{num2} is larger.")
else: 
  print("Both numbers are equal.") 
## Password Checker
Set an admin password. Ask the user to input a password. If the entered password matches the admin password, print "Access granted." If not, print "Access denied."
admin_password = "blahblahblah11"
user_password = input("Enter the password: ")

if user_password == admin_password:
  print("Access granted.")
else:
  print("Access denied.")
## Simple Calculator
Write a program that asks the user for two numbers and an arithmetic operator (+, -, *, /). Use if statements to perform the corresponding arithmetic operation and print the result.
num1 = float(input("Enter the first number: "))
operator = input("Enter on operator (+, -, *, /): ")
num2 = float(input("Enter the second number: "))

if operator == "+":
  print(f"Result: {num1 + num2}")
elif operator == "-":
  print(f"Result: {num1 - num2}")
elif operator == "*":
  print(f"Result: {num1 * num2}")
elif operator == "/":
  if num2 != 0:
    print(f"Result: {num1 / num2}")
  else:
    print("Error!")
else:
  print("Invalid operator.")
  
## Positive, Negative, or Zero
Write a program that asks the user for a number. Check whether the number is positive, negative, or zero, and print an appropriate message.
num = float(input("Enter a number: "))

if num > 0:
  print("The number is positive.")
elif num < 0:
  print("The number is negative.")
else num == 0:
  print("The number is zero.")
  
## Day of the Week
Create a program that asks the user to input a number between 1 and 7. Use an if statement to print the day of the week (e.g., 1 = Monday, 2 = Tuesday, etc.).
day_number = int(input("Enter a number between 1 and 7: "))

if day_number ==  1:
  print("Monday")
elif day_number == 2:
  print("Tuesday")
elif day_number ==3:
  print("Wednesday")
elif day_number == 4:
  print("Thursday")
elif day_number == 5:
  print("Friday")
elif day_number == 6:
  print("Saturday")
elif day_number == 7:
  print("Sunday")
else:
  print("Error in input! Enter a number between 1 and 7.:)
  
