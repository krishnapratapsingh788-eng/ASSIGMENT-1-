# ASSIGMENT-1-
🧮 Task 1: Perform Basic Mathematical Operations
Problem Statement
Write a Python program that:
1.Takes two numbers as input from the user.
2.Performs the following mathematical operations:
 Addition
 Subtraction
 Multiplication
 Division
3.Displays the result of each operation on the screen.
"""Expected Output Example"""
Enter the first number: 10
Enter the second number: 5
Addition: 15
Subtraction: 5
Multiplication: 50
Division: 2.0

😀 Task 2: Create a Personalized Greeting
Problem Statement
Write a Python program that:
 1.Takes the user’s first name and last name as input.
 2.Combines them into a full name.
 3.Prints a personalized greeting message using the full name.
"""Expected Output Example"""
  Enter the first name: John
  Enter the last name: Doe
  Hello, John Doe! Welcome to the Python program.
# TASK 1: Perform Basic Mathematical Operations

#🧾 Sample Combined Code (task 1 and task 2)

x = int(input("Enter the first number: "))
y = int(input("Enter the second number: "))

addition = x + y
subtraction = x - y
multiplication = x * y

# Handle division by zero
if y != 0:
    division = x / y
else:
    division = "Undefined (cannot divide by zero)"

print("Addition:", addition)
print("Subtraction:", subtraction)
print("Multiplication:", multiplication)
print("Division:", division)


# TASK 2: Create a Personalized Greeting

first_name = input("Enter the first name: ")
last_name = input("Enter the last name: ")

full_name = first_name + " " + last_name

print("Hello, " + full_name + "! Welcome to the Python program.")
