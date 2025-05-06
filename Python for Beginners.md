
### Module 0 - Print
- Use `print()` to **show messages** or **results** on the screen.
- Whatever you put inside `"` or `'` will be shown **exactly as it is**.
	- #example 
	- `print("Hello World")`
	- `" "` is used to show the exact text that you gave

### Module 1 - Variables
- A **variable** is like a **label** or **name** that stores a value in memory.
- Think of it like a **container** that holds something you can use later.
	- #example
	- `name = "Khalid"`
	- Here, `name` is the **variable**, and `"Khalid"` is the **value** (a string) assigned to it using `=`.
	- to print this run `print(name)`
	- to print this with a message run `print("Hi," + name)`
	- or `print("Hi,",name)`
	- or `print(f"Hello, {name}")`
	- The `f` before the string means it's a **formatted string**, allowing you to include the value of `name` inside the message.

### Module 2 - Data Types
- When you give a value to Python, it has a **type** — it helps Python understand what the value is and how to treat it.
- we'll see how to assign Data Types in 'Module 0 - User Input'
	- #example 
	- `name = "Khalid"` --> Text  # str  (String)
	- `age = 25` --> Whole numbers  # int (short for integer)
	- `price = 10.25`--> Decimal numbers  # float (short for floating-point number)
	- `is_active = True`-->True or False values  # bool (short for boolean)

### Module 3 - Operators
- operators are basically the signs that you use to do math
	- #example 
	- `+`  --> Addition `2 + 2 = 4`
	- `-`  --> Subtraction  `5 - 2 = 3`
	- `*`  --> Multiplication `5 * 5 = 25`
	- `/`  --> Division `25 / 5 = 5`
### Module 4 - User Input
- **User input** lets your program **ask the user** to type something when it runs.
- This makes your code **interactive**.
- Whatever the user types is taken in as a **string**, so if you need numbers, you often convert it as below.
	- #example 
	- `weight = float(input("Enter your weight in kg: "))`
