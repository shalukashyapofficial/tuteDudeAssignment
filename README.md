**Task 1: Perform Basic Mathematical Operations**
Problem Statement: Write a Python program that does the following:
  1.  Takes two numbers as input from the user.
  2.  Performs the basic mathematical operations on these two numbers:
            o	Addition
            o	Subtraction
            o	Multiplication
            o	Division
**Solution**
1. I have added two variable with num1 and num2 to get the input from user.
2. Convert the input from String to int by using e.g. num1 = int(input("Enter first number"))
3. Once we have the user input now we need to the calculation use below code for addition/substraction and so on.
     # Addition
addition = num1 + num2
print("Addition :",addition)

# Substraction
subtraction = num1 - num2
print("Substraction :",subtraction)

#Multiplication
multiplication = num1 * num2
print("Multiplication :",multiplication)

#Division
division = num1 / num2
print("Division :",division)

**Task 2: Create a Personalized Greeting**
Problem Statement: Write a Python program that:
1.  Takes a user's first name and last name as input.
2.  Concatenates the first name and last name into a full name.
3.  Prints a personalized greeting message using the full name.
**Solution**
input1 = input("Enter your first name: ")
input2 = input("Enter your second name: ")

print(f"Hello!,{input1} {input2}!  Welcome to Python!")


