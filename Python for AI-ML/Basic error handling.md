#### 1. What is Error Handling?
- When Python runs into a problem (like dividing by zero or opening a missing file), it **throws an error** and stops your program.  
- With **`try` and `except`**, you can **catch** that error and handle it gracefully instead of crashing.
---

#### 2. Basic Syntax
```Python
try:        # Code that might cause an error
	x = 10 / 0
except:     # Code that runs if there's an error
	print("Oops! Something went wrong.")   # Oops! Something went wrong.
```
---

#### 3. Handling Specific Errors
- It’s better to **catch specific errors** so you don’t hide other problems.
```Python
try:
	num = int("abc")                 # This will cause ValueError
except ValueError:
	print("Invalid number format!")  # Invalid number format!
```
---

#### 4. Using `else` and `finally`
- **`else`** → Runs if there’s **no error**.
- **`finally`** → Runs **no matter what** (good for cleanup tasks).
```Python
try:
	num = int(input("Enter a number: "))
except ValueError:
	print("That's not a number!")
else:
	print(f"You entered {num}")
finally:
	print("Program finished.")
```
---
