#### 1. `if` Statement
- Runs code **only if** a condition is true.
```Python
age = 18
if age >= 18:
	print("You are an adult.")  # You are an adult.
```
---

#### 2. `else` Statement
- Runs code if the `if` condition is false.
```Python
age = 16
if age >= 18:
	print("You are an adult.")
else:
	print("You are a minor.")   # You are a minor.
```
---

#### 3. `elif` Statement
- (Short for **else if**) — lets you check **multiple conditions** one by one.
```Python
marks = 75
if marks >= 90:
	print("Grade A")
elif marks >= 75:
	print("Grade B")
elif marks >= 50:
	print("Grade C")
else:
	print("Fail")   # Grade B
```
---

**Important Notes:**
- Python uses **indentation** (spaces or tabs) to group code blocks.
- Conditions use **comparison operators** like `==`, `!=`, `<`, `>`, `<=`, `>=`.
- Logical operators like `and`, `or`, `not` can combine conditions.

**Example with multiple conditions:**
```Python
x = 10
if x > 5 and x < 15:
	print("x is between 5 and 15")
else:
	print("x is not in the range")   # x is between 5 and 15
```
---
