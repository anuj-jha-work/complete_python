# Conditionals_and_loops
age = int(input("Enter your age: "))

if age < 13:
    print("You are a child.")
elif age < 18:
    print("You are a teenager.")
else:
    print("You are an adult.")
    The range() function is often used to generate a sequence of numbers.
# Range Function
range(stop): from 0 up to (but not including) stop.
range(start, stop): from start up to stop.
range(start, stop, step): from start up to stop, incrementing by step.

# Print numbers from 1 to 5
for i in range(1, 6):
    print(i)

# Iterate over a list
fruits = ["apple", "banana", "cherry"]
for fruit in fruits:
    print(fruit)

# Loop Control
    for num in range(1, 11):
    if num == 3:
        continue  # Skip printing 3
    if num == 8:
        break     # Stop the loop when num is 8
    print(num)
# Output: 1 2 4 5 6 7