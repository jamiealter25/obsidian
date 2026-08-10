

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
- Syntax is **[start : stop]** or **[start : stop : step]**
- **[1 : 4]** means it'll take the value from place 1
- step is used to jump specific steps
- **Blank `start`**: Starts at the beginning; **Blank `stop`**: Goes till the end; **Blank both**: full list.

```Python
numbers = [1, 2, 3, 4, 5]

numbers[1:4] # Output: [2, 3, 4]
numbers[:3] # Output: [1, 2, 3]
numbers[::-1] # Output: [5, 4, 3, 2, 1]
```

| **Action**            | **Syntax**        | **Example**           |                       | **Result**     |
| --------------------- | ----------------- | --------------------- | --------------------- | -------------- |
| Change **one** item   | `list[index]`     | `nums = [1, 2, 3]`    | `nums[1] = 9`         | `[1, 9, 3]`    |
| Change **some** items | `list[start:end]` | `nums = [1, 2, 3, 4]` | `nums[1:3] = [8, 9]`  | `[1, 8, 9, 4]` |
| Replace **all** items | `list[:]`         | `nums = [1, 2, 3]`    | `nums[:] = [4, 5, 6]` | `[4, 5, 6]`    |

# List Comprehensions

- A **compact way** to create lists using a single line of code.
- Combines **loop** and **expression** inside `[]`.
- Often used for **cleaner, faster** list creation.

- 
```python
squares = [x * x for x in range(5)]
print(squares)  # Output: [0, 1, 4, 9, 16]
```
---
# create:  
numbers = [1, 2, 3, 4, 5]  

  
#  :  

 

  
# List Comprehensions:  
squares = [x**2 for x in range(6)] # [0, 1, 4, 9, 16, 25]  
evens = [x for x in numbers if x % 2 == 0] # [2, 4]  
  
# Built-in Methods:  
numbers.append(6) #Adds one item to the end  
numbers.pop() # Removes last element  
numbers.pop(0) # Removes first element  
numbers.insert(2, 99) # Inserts 99 at index 2  
numbers.remove(3) # emoves the first occurrence of 3  
numbers.sort() # Sorts in-place (ascending by default)  
numbers.reverse() # Reverses the list in-place