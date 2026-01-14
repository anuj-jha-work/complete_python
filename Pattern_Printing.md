Example 1: Solid Rectangle of Stars
This pattern prints a rectangle of * symbols. The number of rows is determined by user input n, and each row has 5 stars.

Goal: Print n rows, each with 5 stars.
Logic: The outer loop runs n times for the rows. The inner loop runs 5 times for the columns in each row.

# Code from source [cite: 827]
n = int(input("Enter number of rows: "))
for i in range(n):  # Outer loop for rows
    for j in range(5):  # Inner loop for columns
        print("*", end="")
    print()  # Move to the next line after each row

    
Example 2: Right-Angled Triangle of Stars
This pattern prints a triangle where the number of stars in each row increases by one.


Goal: Print n rows, where row i has i stars.
Logic: The outer loop iterates from 1 to n. The inner loop also iterates up to the current row number (i + 1) to print the corresponding number of stars.

# Code from source [cite: 837]
n = int(input("Enter number of rows: "))
for i in range(n):  # Outer loop for rows (0 to n-1)
    for j in range(i + 1):  # Inner loop for columns
        print("*", end="")
    print() # Move to the next line