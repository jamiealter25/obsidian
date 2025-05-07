
### Module 00 - Syntax
- **Syntax** is the set of **rules** that define **how you should write code** so that Python can understand and run it correctly.

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
- we'll see how to assign Data Types in '**Module 4 - User Input**'
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
	- `**` --> Exponent `2 ** 3 = 8`
	- `%`  --> Modulus/Remainder `22 % 8 = 6`
	- `//` --> Integer division `22 // 8 = 2`
- Comparison Operators
	- `==` --> Equal to `5 == 5`
	- `!=` --> Not equal to `5 != 3`
	- `>=` --> Greater or equal `8 >= 5`
	- `<=` --> Less or equal `3 <= 8`
- Assignment Operators
	- |Long way|Short way|What it means|
|---|---|---|
|`count = count + 1`|`count += 1`|Add 1 to count|
|`x = x - 2`|`x -= 2`|Subtract 2 from x|
|`total = total * 3`|`total *= 3`|Multiply total by 3|
|`score = score / 2`|`score /= 2`|Divide score by 2|

### Module 4 - User Input
- **User input** lets your program **ask the user** to type something when it runs.
- This makes your code **interactive**.
- Whatever the user types is taken in as a **string**, so if you need numbers, you often convert it as below.
	- #example 
	- `weight = float(input("Enter your weight in kg: "))`

### Module 5 - Comment
- Use the `#` symbol at the beginning of a line to make it a comment about code
	- #example 
	- `# this is a comment`

### Module 6 - Use of colon (:)
- Whenever the next line is indented, the current line must end with `:`
- use case --> `if`, `elif`, `else`, `for`, `while`, `def` (function definitions), `class` (class definitions)

### Module 7 -  If....Else (conditional statements)
- It basically means If **this** is true, then **do this**, else (if it’s not true), **do something else**.
- Use `if` & `else` for two arguments.
- Use `if`, `elif` & `else` for more than two arguments.
- #example 
- score = 75
	if score >= 90:
	    print("Grade: A")
	elif score >= 75:
	    print("Grade: B")
	else:
	    print("Grade: C")

### Module 8 - Loops
- `while` loops --> It keeps running **as long as** the condition stays `True`.
	- #example 
	- count = 1
		while count <= 5:
	    print(count)
	    count = count + 1
- `for` loops --> Used when you **already know** how many times to loop.
	- #example 
	- for number in range(1, 6):
	    print(number)
