### 1.  Variables and Data Types
- Integers, floats
- Strings
- Booleans
- None

```python
name = "Afrid"
age = 20
is_learning = True
```

---

### 2.  Control Flow
- if, elif, else
- while, for loops
- break, continue

```python
for i in range(5):
    if i == 3:
        break
    print(i)
```

---

### 3.  Data Structures
- Lists – ordered collections
- Dictionaries – key-value pairs
- Tuples – immutable lists
- Sets – unique items

```python
fruits = ["apple", "banana"]
profile = {"name": "Afrid", "age": 20}
```

---

### 4.  Functions
- Defining and calling functions
- Parameters and return values
- *args and **kwargs (later on)

```python
def greet(name):
    return f"Hello, {name}!"
```

---

### 5.  Classes & Objects (Basic OOP)
- class, __init__, self
- Instance vs class variables
- Very useful in AI frameworks like PyTorch

```python
class Student:
    def __init__(self, name):
        self.name = name
```

---

### 6.  File I/O
- Reading from and writing to files

```python
with open("data.txt", "r") as file:
    content = file.read()
```

---

### 7.  Basic Error Handling
- try, except, finally

```python
try:
    x = 5 / 0
except ZeroDivisionError:
    print("Cannot divide by zero!")
```

---

### 8.  List Comprehensions
- Clean, one-line loops for list creation

```python
squares = [x*x for x in range(5)]
```

---

### 9.  Importing Modules
- Built-in modules: math, random, datetime
- External libraries: numpy, pandas (later for AI)

```python
import math
print(math.sqrt(16))
```

| Topic                | Why It Matters                           |
| -------------------- | ---------------------------------------- |
| Variables & types    | Foundation of everything                 |
| Loops & conditionals | Core logic handling                      |
| Lists/dicts          | You use them *all the time*              |
| Functions            | Code reuse & modularity                  |
| Classes (OOP)        | Needed for real-world code, AI libraries |
| File I/O             | For working with data                    |
| Error handling       | To make stable apps                      |
| List comprehensions  | Clean & readable logic                   |
| Modules              | Use others' code smartly                 |
