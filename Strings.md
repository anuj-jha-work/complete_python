text = "Hello, World!"

# Indexing
first_char = text[0]   # 'H' [cite: 2666]
last_char = text[-1]   # '!' [cite: 2670]

# Slicing
substring1 = text[0:5]   # 'Hello' [cite: 2710]
substring2 = text[7:]    # 'World!' (slice till the end) [cite: 2711]
substring3 = text[:5]    # 'Hello' (slice from the start) [cite: 2712]
substring4 = text[::2]   # 'Hlo ol' (every second character) [cite: 2714]

# Useful Methods:
.lower(): Returns a new string in all lowercase.
.upper(): Returns a new string in all uppercase.
.strip(): Returns a new string with leading/trailing whitespace removed.
.replace(old, new): Returns a new string where occurrences of old are replaced with new.
.split(delimiter): Splits the string at the delimiter and returns a list of substrings.
.find(substring): Returns the index of the first occurrence of the substring, or -1 if not found

# String Formatting
Used to insert variables into a string in a clean way.
# .format() Method:

quantity = 3
item_number = 567
price = 49.95
my_order = "I want {} pieces of item {} for {} dollars." [cite: 2779]
print(my_order.format(quantity, item_number, price))
# f-Strings (Formatted String Literals): (Modern and preferred method)

name = "Alice"
age = 30
print(f"My name is {name} and I am {age} years old.")