# my_list = ["apple", "banana", "cherry"] [cite: 869]
# Common Operations:
Access Items: Use the index (0-based) my_list[1] returns "banana".

Get Length: len(my_list) returns 3.

Add Items:
my_list.append("orange") adds to the end.
my_list.insert(1, "orange") adds at a specific index.

Remove Items:
my_list.remove("banana") removes the specified item.
my_list.pop(1) removes the item at the specified index.
Slicing: my_list[1:3] extracts a new list ['banana', 'cherry'].

2. Tuples ()
Ordered: 
Immutable: 
Allows Duplicates: 
Syntax: Created using round brackets ().
my_tuple = ("apple", "banana", "cherry") [cite: 1132]

Usage: Because they are immutable, tuples are faster than lists and can be used as keys in a dictionary.

3. Sets {}
# Properties:
Unordered: 
Mutable: 
No Duplicates: 
Syntax: Created using curly brackets {}.

my_set = {"apple", "banana", "cherry"} [cite: 1302]
Common Operations:
Add Item: my_set.add("orange").
Remove Item: my_set.remove("banana") (will raise an error if the item doesn't exist).
Set Operations:
set1.union(set2): Returns a new set with all items from both sets.
set1.intersection(set2): Returns a new set with only items present in both sets.

4. Dictionaries {key: value}
# Properties:
Ordered 
Mutable: 
Key-Value Pairs: 
No Duplicate Keys: 
Syntax: Created with curly brackets {} containing key-value pairs.

this_dict = {
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
} [cite: 1557, 1559, 1561]
Common Operations:


Access Value: Use the key this_dict["model"] returns "Mustang".

Add/Update Item: this_dict["color"] = "red" adds a new pair, or updates the value if the key exists.

Remove Item: this_dict.pop("model") removes the item with the specified key.

Get Keys/Values: this_dict.keys() and this_dict.values().