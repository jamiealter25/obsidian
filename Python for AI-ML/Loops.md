#### 1. `for` Loop
- Used to iterate over a sequence (like a list, string, or range).

**Example: Loop through a list**
```Python
fruits = ["apple", "banana", "cherry"] for fruit in fruits:
	print(fruit)    # apple banana cherry
```

**Example: Loop using `range()`**
```Python
for i in range(5):  # 0 to 4
	print(i)    # 0 1 2 3 4
```
---

#### 2. `while` Loop
- Repeats as long as a condition is true.
```Python
count = 0
while count < 5:
	print(count)
	count += 1  # increment count     # 0 1 2 3 4
```
---

**Important Notes**
- Make sure `while` loops **eventually stop** by changing the condition inside the loop, or else you get an **infinite loop**.
- You can use `break` to exit a loop early.
- Use `continue` to skip the rest of the current loop iteration and move to the next one.

**Example with `break` and `continue`:**
```Python
for i in range(10):
	if i == 5:
		break      # exit loop when i == 5
	if i % 2 == 0:
		continue   # skip even numbers
	print(i)   # 1 3
```
---
