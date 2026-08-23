# String Manipulation

 **1. Creating Strings**
```Python
s1 = "Hello"
s2 = 'World'
s3 = """Multi-line string here"""
```
---
 
 **2. Changing Case**
```Python
text = "hello world"
print(text.upper())   # HELLO WORLD
print(text.lower())   # hello world
print(text.title())   # Hello World
print(text.capitalize())  # Hello world
```
---

**3. Removing Spaces & Characters**
```Python
txt = "   Afrid   "
print(txt.strip())   # removes spaces: "Afrid"
print(txt.lstrip())  # removes spaces from left
print(txt.rstrip())  # removes spaces from right
```
---

**4. Joining Strings**
```Python
words = ["I", "love", "Python"]
print(" ".join(words))  # I love Python
print("-".join(words))  # I-love-Python
```
---

**5. Splitting Strings**
```Python
sentence = "I-love-Python"
print(sentence.split("-"))  # ['I', 'love', 'Python']
```
---

**6. Replacing Text**
```Python
text = "I like Java"
print(text.replace("Java", "Python"))  # I like Python
```
---

**7. Finding Text**
```Python
text = "Hello World"
print(text.find("World"))  # 6
print(text.find("Afrid"))  # -1 (not found)
```
---

**8. Checking Content**
```Python
word = "Python3"
print(word.isalpha())   # False (because of the '3')
print(word.isdigit())   # False
print("123".isdigit())  # True
print("hello".isalpha()) # True
print("abc123".isalnum()) # True
```
---

**9. String Slicing**
```Python
text = "Hello World"
print(text[0:5])   # Hello
print(text[:5])    # Hello
print(text[6:])    # World
print(text[-5:])   # World
```
---

**10. String Formatting**
```Python
name = "Afrid"
age = 20
print(f"My name is {name} and I am {age} years old.")
print("My name is {} and I am {} years old.".format(name, age))
```
---

- In array to select the last item, put [-1]
```Python
my_list = [1,2,3]
print(my_list[-1])    #output will be 3
```
---
- `spe` (separate) won't work sometimes. check below.
```Python
print("Afrid"*3, sep = " ")          # output - AfridAfridAfrid
print(" ".join("Afrid" * 3))         # output - A f r i d A f r i d A f r i d
print(" ".join(["Afrid"] * 3))       # output - Afrid Afrid Afrid
```
---

#### 4. Checking Data Types

- Use `type()` function:
```Python
a = 10
b = 3.14
c = "Hello"
d = True
print(type(a))  # <class 'int'>
print(type(b))  # <class 'float'>
print(type(c))  # <class 'str'>
print(type(d))  # <class 'bool'>
```
---

#### 5. Changing Data Types (Type Casting)

- You can convert one data type to another:
```Python
num_str = "100"
num_int = int(num_str)     # Convert string to int
num_float = float(num_str) # Convert string to float
print(num_int + 50)        # 150
print(num_float + 0.5)     # 100.5
```
---

#### 6. Variables are Dynamic

- Python lets you change the value and type of a variable anytime:
```Python
x = 10      # x is int
x = "ten"   # now x is str
```
---

### Module 17 - Boolean & Comparison
- `True`, `False`, `==`, `!=`, `>`, `<`
```python
42 == 42  # True
```

**Boolean Operators:**
- `and`, `or`, `not`
```python
True and False  # False
not True        # False
```

---

### Module 18 - Truthy and Falsey
- `""`, `0`, `None` → Falsey
- Others → Truthy
```python
if name:
    print("You entered a name")
```

---

### Module 19 - Break & Continue
```python
while True:
    print("Hello")
    break
```

---

### Module 20 - Standard Modules
```python
import math, random, sys
from random import *
sys.exit()
```

---

### Module 21 - Return Statement
```python
def add_one(n):
    return n + 1
```

---

### Module 22 - Print Options
```python
print("Hello", end=" ")
print("World")
print("A", "B", "C", sep="-")  # A-B-C
```

---

### Module 23 - Scope
- Global can't access local.
- Local can read global.
```python
def greet():
    global name
    name = "Alice"
```

---

### Module 24 - Error Handling
```python
try:
    print(42 / 0)
except ZeroDivisionError:
    print("Can't divide by zero.")
```

---

### Module 25 - More on Lists
```python
spam = ['cat', 'rat']
spam[1] = 'bat'  # Change item
del spam[0]      # Delete item
42 in spam       # Check if value exists
```

---

### Module 26 - range() vs list()
```python
list(range(0, 10, 2))  # [0, 2, 4, 6, 8]
```

---

### Module 27 - Multiple Assignment & Swap
```python
a, b = 'A', 'B'
a, b = b, a
```

---

### Module 28 - List Methods
```python
spam = ['hi']
spam.append('bye')
spam.remove('hi')
spam.sort()
```