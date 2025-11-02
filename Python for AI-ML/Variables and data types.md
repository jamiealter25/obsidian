#### 1. What is a Variable?

- Think of a **variable** as a **container** or **label** that holds information.
- You can **store values** like numbers, text, or more complex data inside it.
- You can **change** the value of a variable anytime.
```Python
age = 20
name = "Afrid"
```
- Here, 
	- `age` holds the number `20`
	- `name` holds the text `"Afrid"`
---

#### 2. Rules for Naming Variables

- Names must start with a **letter** or **underscore** (`_`), not a number.
- Can contain letters, numbers, and underscores.
- Case-sensitive (`age` ≠ `Age`).
- Avoid Python keywords like `for`, `if`, `while`, etc.

**Good variable names:**
```Python
my_age = 20
userName = "Afrid"
```

**Bad variable names:**
```Python
2age = 20   # starts with number → error
my-age = 20 # dash not allowed → error
```
---

#### 3. Data Types in Python

- Every variable has a **data type** that tells Python what kind of data it is.

**Basic Data Types:**

| Data Type | Description                     | Example               |
| --------- | ------------------------------- | --------------------- |
| `int`     | Integer (whole number)          | `20`, `-5`, `0`       |
| `float`   | Decimal number (floating point) | `3.14`, `0.5`, `-1.0` |
| `str`     | String (text)                   | `"Afrid"`, `'Hello!'` |
| `bool`    | Boolean (True or False)         | `True`, `False`       |

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
