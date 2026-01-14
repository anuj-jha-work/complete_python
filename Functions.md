# A function definition
def greet(name):              # 'name' is a parameter [cite: 2094]
    """This function greets the person passed in as a parameter."""
    print("Hello, " + name + "!")

# A function call
greet("Alice")                # "Alice" is an argument


# Default Arguments: A parameter is given a default value in the definition. If the argument isn't passed, the default is used.

def greet(name, message="Hello"): [cite: 2037]
    print(message, name)

greet("Alice") # Output: Hello Alice
greet("Bob", "Hi") # Output: Hi Bob


# Arbitrary Arguments (*args and **kwargs):
*args: Allows a function to accept any number of non-keyword arguments, which are collected into a tuple.

**kwargs: Allows a function to accept any number of keyword arguments, which are collected into a dictionary.

