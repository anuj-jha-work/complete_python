# Important: The input() function always returns the data as a string.

Python

name = input("Enter your name: ")
print("Hello, " + name)
# Typecasting (Type Conversion)
This is necessary when you get string input but need a number.

Common typecasting functions: int(), float(), str().

The type() function returns the data type of a variable.
# Input is a string "25"
age_str = input("Enter your age: ")

# Typecast the string to an integer
age_int = int(age_str) [cite: 384, 385]

print("You will be", age_int + 1, "next year.")
print(type(age_str))  # Output: <class 'str'>
print(type(age_int))  # Output: <class 'int'>