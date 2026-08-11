
# List

- Store many items in one place.
- Uses **square brackets `[ ]`**.
- Mutable (can **modify** one item, **multiple items**, or even **replace the entire list**).
```python
# Different types of lists
fruits = ["apple", "banana", "cherry"]
numbers = [1, 2, 3]
mixed = [42, "AI", 3.14, [1, 2], {"model": "GPT"}]  
```
#### List Indexing
- Grabbing an item from a list by its position number.
- First item's position number is **0**
```Python
fruits = ["apple", "banana", "cherry"]

# Position(positive):   0        1          2
# Access:            fruits[0] fruits[1] fruits[2]
# Position(negative):   -3        -2        -1

# Positive indexing
fruits[0] # Output: 'apple'

# Negative indexing
fruits[-1] # Output: 'cherry' (last element) 
```
#### List Slicing
- list slicing is grabbing items in a range
- Syntax structure --> **[start : stop]** or **[start : stop : step]**
- **[1 : 4]** means it'll take the value from place 1 - 3, **stop** value is always the limit.
- step is used to jump specific steps
- **Blank `start`**: Starts at the beginning; **Blank `stop`**: Goes till the end; **Blank both**: full list.

```Python
numbers = [1, 2, 3, 4, 5]

numbers[1:4] # Output: [2, 3, 4]
numbers[:3] # Output: [1, 2, 3]
numbers[::-1] # Output: [5, 4, 3, 2, 1]
```
#### List Comprehensions
- fast way create lists using `for` , `if...else` inside a single line.
- comprehension = [ do this  + for what +  condition ] except `if...else`
```python
# list      = [x        for x in numbers       if x % 2 == 0]
# formula   = [do this      for what               condition]


numbers = [1, 2, 3, 4, 5]

# Basic Comprehensions
squares = [x**2 for x in numbers] # Output: [1, 4, 9, 16, 25]

# IF
evens = [x for x in numbers if x % 2 == 0] # Output: [2, 4]

# IF-ELSE [do this + IF/ELSE + for what]
labels = ["even" if x % 2 == 0 else "odd" for x in numbers]
# Output: ['odd', 'even', 'odd', 'even', 'odd']
```
#### Built-in Methods:  
```Python
numbers = [1, 2, 3, 4, 5]

numbers.append(6)     # Adds given item to the end  
numbers.insert(2, 99) # Inserts 99 at index 2 and shift others to right 
numbers.remove(3)     # finds 3 in list and removes it
numbers.pop()         # Removes last element  
numbers.pop(0)        # Removes first element
numbers.sort()        # Sorts list (ascending by default)  
numbers.reverse()     # Reverses list
```
---

# Dictionary

- A container used to describe a single item/variable through its features (key-value pair).
- Use **curly brackets {}**
- Syntax structure --> variable_name = {"lable/keys" :  value, "label/keys" : value}
- Label/keys must be **unique** and **immutable**.
```python
# basic dictionary structure
person = {"name": "Afrid",
		   "age": 20,
		  "city": "Dhaka"}
```
#### Accessing Values		  
```Python
person["name"]             # Access value by label/key → Afrid
```
#### Checking if label/key exists
```Python
person.get("height", 0.9)  # Returns 0.9 if "height" is missing
```
#### Modifying or Adding Entries
```Python
person["age"] = 21         # Update value
person["country"] = "BD"   # Adds "country"/ updates existing "country"
```
#### Removing label/keys
```Python
person.pop("city")         # Removes "city" and copy value (Not exist = Key error)
person.pop("city", None)   # Removes "city" and copy its value (no error)
del person["city"]         # Removes "city" and no copy (Not exist = Key error)
```
#### Iteration of dictionary
```Python
person = {"name": "Afrid", "age": 20, "city": "Dhaka"}

# .items() for both key and value
for key, value in person.items():
    print(f"{key} = {value}")
	
# .keys() for only key
for key in person.keys():
    print(key)

# .values() for only value
for value in person.values():
    print(value)
```

#### Dictionary Comprehension
```Python
squared = {x: x**2 for x in range(5)}

variable_name =  {"lable/keys" :  value,
```

---
