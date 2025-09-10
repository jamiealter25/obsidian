### **Part 1: High-Priority Topics (Similar & Recurring Questions)**

This section covers the most critical and frequently asked questions.

#### **Topic 1: Function Fundamentals**

*   **Question:** (201, B#5) / (221, B#5) Why procedures are used in writing computer programs? / (221, A#10) Write the concept of "function" in programming.
*   **Answer:**
    *   **Concept of a Function:** A function is defined as **“A function is a block of code that performs a particular task”**. Every C program is composed of functions, with `main()` being the mandatory starting point. Functions are used to break large, complex programs into smaller, manageable, and logical parts. (Page 138).
    *   **Why Functions are Used:** Using user-defined functions is necessary for complex programs to avoid them becoming "too large and difficult." The main reasons are:
        1.  **Modularity:** They provide modularity to the program.
        2.  **Debugging and Maintenance:** It is "easy to locate and segregate a defective function for further exploration," which makes debugging, testing, and maintaining code simpler.
        3.  **Code Reusability:** You only have to write the function once, and you can "just have to call the function by its name to use it from anywhere of a program." A function can also be used by many other programs.
*   **Page Number(s):** 138, 139.

*   **Question:** (191, B#7) / (201, B#7) / (221, B#4) What is meant by function argument, function call and return value? Explain with example.
*   **Answer:**
    *   **Function Argument:** Arguments (also called parameters) are the data sent to a function. There are two types: **actual arguments** (in the calling function) and **formal arguments** (in the called function). The "values of actual arguments are assigned to the formal arguments on a one to one manner."
    *   **Function Call:** To use a function, "we will have to call that function to perform the defined task. A function can be called by using the function name in a statement of program." When a function is called, the program's control "is transferred to the called function."
    *   **Return Value:** A function may return a value to the function that called it. The `return-type` in the function definition specifies the data type of the value the function returns. The `return` statement is used to send this value back.
*   **Page Number(s):** 142, 143, 154.

*   **Question:** (191, B#2) / (201, B#3) / (211, B#5) / (221, B#7) / (231, B#5) What do you understand by call by value and call by reference in function? Describe it with proper example.
*   **Answer:** The textbook describes the mechanisms for passing parameters without using the exact terms "call by value" or "call by reference."
    *   **Call by Value ("Pass-by-Value"):** This is the default method in C. The textbook explains that "The values of actual arguments are assigned to the formal arguments on a one to one manner." This means that only a *copy* of the variable's value is passed to the function. Any changes made to the parameter inside the function do not affect the original variable in the calling function.
    *   **Call by Reference ("Pass-by-Reference"):** This is achieved using pointers. Pointers "can be used to pass information back and forth between the calling function and called function." Instead of passing a copy of the value, you pass the memory address of the variable. This allows the function to directly access and modify the original variable's value. The textbook states, "By using pointers we can access a data which is available outside a function."
*   **Page Number(s):** 154 (for value passing), 190 (for pointer benefits related to reference).

*   **Question:** (191, A#2) / (231, A#10) Why use return statement in C programming language? / What is the purpose of the return statement in a function?
*   **Answer:** A `return` statement has two purposes:
    1.  It immediately exits the function it is in and transfers program control back to the statement following the function call.
    2.  It can be used to "return a value" to the calling function. The value returned must match the `return-type` specified in the function's definition.
*   **Page Number(s):** 17, 142.

#### **Topic 2: Variable Scope & Storage Classes**

*   **Question:** (191, A#3) / (201, A#3) / (221, A#8) / (231, A#4) Define/Differentiate between local variable and global variable.
*   **Answer:**
    *   **Local Variable:** "A local variable is a variable that is declared inside a particular function... Local variable can be used only in the function in which it is declared." They are also called *automatic variables* because they are "created when the function is called and automatically destroyed when the function is exited."
    *   **Global Variable:** "A global variable is a variable that is declared outside all functions." They are also called *external variables*. They "are both alive and active throughout the entire program" and can be accessed and modified by any function in the program (provided the function is below the global variable's declaration).
*   **Page Number(s):** 167, 168.

*   **Question:** (191, B#3) / (231, B#4) Describe why storage classes are used in C programming language. Explain static and external storage class with examples.
*   **Answer:** (The textbook does not explicitly state *why* storage classes are used, but it describes their function, which is to define the scope and lifetime of variables).
    *   **External Storage Class (`extern`):** This refers to **global variables**. "A global variable is a variable that is declared outside all functions... also referred to as external variables." They are used when a variable must be accessible by multiple functions in the program. (See Program 7.9.2 for an example).
    *   **Static Storage Class (`static`):** (The purpose of the `static` keyword is described in the "Unique Questions" analysis, but not defined in detail in the provided textbook pages. The text only shows `static int a=10; //Visibility is within main block` on page 26, which is an incorrect use of the term `static` as its purpose is to preserve the variable's value between function calls, not just define visibility).
*   **Page Number(s):** 168, 174 (for global/external).

#### **Topic 3: Looping Constructs and Control**

*   **Question:** (191, B#1) / (221, A#3) / (231, B#3) How to differentiate while and do while statement? Explain it with proper example.
*   **Answer:** The main difference is when the loop's condition is tested:
    *   **`while` loop:** This is an **entry-controlled loop**. In a `while` loop, "the control conditions are tested before the start of the loop execution." This means if the condition is false initially, "the body of the loop will not be executed" at all.
    *   **`do-while` loop:** This is an **exit-controlled loop**. In this loop, "the control conditions are tested at the end of the body of the loop." As a result, "the body is executed unconditionally for the first time," meaning it will always run at least once, even if the condition is false.
*   **Page Number(s):** 69, 70, 76.

*   **Question:** (191, A#6) / (201, A#9) / (221, A#5) / (231, A#2) Why continue statement are use in C? / Define break statement and continue statement.
*   **Answer:**
    *   **`break` statement:** "The `break` statement allows us to departure a loop from any point within its body... when the `break` statement is encountered inside a loop, the loop is immediately terminated, and program control resumes at the next statement following the loop."
    *   **`continue` statement:** The `continue` statement "is used to avoid the remainder of the current pass through a loop." When it is encountered, it "causes the loop to be continued with the next iteration after skipping any statements in between." It essentially tells the compiler to "Skip the following statements and continue with the next iteration."
*   **Page Number(s):** 87, 90.

#### **Topic 4: Arrays, Pointers, and Strings**

*   **Question:** (191, A#10) What is the main functionality of array?
*   **Answer:** "An array is a one kind of data structure that can store a fixed-size sequential collection of elements of the same type. An array is used to store a collection of same type of data." Its main functionality is to handle large amounts of similar types of data efficiently, avoiding the "tedious and impracticable" process of creating hundreds of individual variables.
*   **Page Number(s):** 101.

*   **Question:** (191, B#4) / (221, B#6) What is string constant? How string constant differ from character constant?
*   **Answer:**
    *   **String Constant:** "String constants are the constants which are enclosed in a pair of double-quote marks." For example: `"Bangladesh"`. A string is an array of characters terminated by a null character (`\0`).
    *   **Character Constant:** "A character constant is a constant which uses single quotation around characters." For example: `'a'`. It represents a single character value.
*   **Page Number(s):** 28.

*   **Question:** (191, A#7) / (231, A#6) What is pointer notation?
*   **Answer:** Pointer notation refers to how pointers are declared and used.
    *   **Declaration:** A pointer is declared using the asterisk (`*`) operator: `data-type * pointer_name;`. For example, `int *ptr;` declares `ptr` as a pointer to an integer.
    *   **Address-of Operator (`&`):** The `&` operator is used to get the memory address of a variable to assign it to a pointer: `ptr = &value;`.
    *   **Indirection Operator (`*`):** The `*` operator is also used to access the value at the address stored in a pointer (dereferencing): `x = *ptr;`.
*   **Page Number(s):** 188, 193.

#### **Topic 5: Conditional Logic**

*   **Question:** (191, A#5) / (211, A#2) / (231, A#7) What happens when we run a program containing a switch?
*   **Answer:** "A `switch` statement tests the value of a given variable or expression against a list of `case` values. When `case` is matched or found then block of statements associated with that case is executed." The `break` statement at the end of a case block causes an exit from the `switch` statement. If `break` is omitted, the program will continue to execute the statements in the following `case`(s). If no match is found, the optional `default` block is executed.
*   **Page Number(s):** 64.

*   **Question:** (201, A#5) / (211, A#9) What is a decision structure? Write the pseudocode format for a decision structure.
*   **Answer:** A decision structure is a programming construct that allows a program "to change the order of execution of statements based on certain conditions."
    *   **Pseudocode (Format for `if-else`):** The general structure is:
        ```
        if ( condition is true )
            execute statement-block-1
        else
            execute statement-block-2
        ```
*   **Page Number(s):** 42, 47.

***

### **Part 2: Unique Questions (Standalone Topics)**

This section covers less frequent but important topics.

#### **C Keywords & Syntax**

*   **Question:** (191, A#4) What are the keywords in C? What restrictions apply to their use?
*   **Answer:**
    *   **Keywords:** "Keywords are pre-defined words in a C compiler. Each keyword is meant to perform a specific function." Examples include `int`, `float`, `if`, `else`, `for`, `while`, `return`. A full list is on page 22.
    *   **Restriction:** The main restriction is that "these reserved words cannot be used as constants or variables or any other identifier names."
*   **Page Number(s):** 22.

*   **Question:** (211, A#1) Write the format specifier available in C language.
*   **Answer:** Format specifiers are used in functions like `printf()` and `scanf()` to define the data type. Common specifiers include:
    *   `%d`: Integer
    *   `%f`: Float
    *   `%c`: Single character
    *   `%s`: String
    *   `%lf`: Double / Long double
*   **Page Number(s):** 18.

*   **Question:** (221, A#4) Explain the difference between the "++i" and "i++" increment operators in C.
*   **Answer:**
    *   **`i++` (Postfix):** This operator "will return the current value and then increment."
    *   **`++i` (Prefix):** This operator "will increment... and then return the value (so it will return one greater than the original value)."
*   **Page Number(s):** 36.

#### **Conceptual & Definitions**

*   **Question:** (211, A#3) How does a structure differ from an array?
*   **Answer:** The primary difference is the type of data they can hold.
    *   An **array** "is used to store a collection of **same type of data**." (Page 101).
    *   A **structure** is used "to represent a collection of **different types of data items** using a single name." (Page 179).
*   **Page Number(s):** 101, 179.

*   **Question:** (211, A#10) Why 'main' function is used in C?
*   **Answer:** The `main()` function is essential because it "starts the execution of C program." It is a mandatory function that designates where the program begins.
*   **Page Number(s):** 17, 138.

*   **Question:** (221, A#1) Define the term "algorithm" in the context of computer programming.
*   **Answer:** From a programming point of view, "An algorithm is a step by step procedure (technique) for solving any problem." It refers "to the logic of a program and step by step description of how to arrive at the solution of a given problem."
*   **Page Number(s):** 13.

*   **Question:** (231, A#1) What is the significance of the #include directive in C?
*   **Answer:** The `#include` directive is a pre-processor command. Its main work "is to initialize the environment of program, i.e to link the program with the header file <stdio.h>." Header files contain standard library functions, and "To use any of the standard functions, the appropriate header file must be included."
*   **Page Number(s):** 17.

#### **Deeper Conceptual Questions (from Section B)**

*   **Question:** (191, B#5) Describe how the for loop works. Give an example for for loop.
*   **Answer:** A `for` loop is an entry-controlled loop that executes in four steps:
    1.  **Initialization:** Performed once at the beginning to declare and initialize a loop control variable (e.g., `i=1`).
    2.  **Test-condition:** The relational expression is evaluated (e.g., `i<=10`). If true, the loop body executes. If false, the loop terminates.
    3.  **Body Execution:** The statements inside the loop are executed.
    4.  **Increment/Decrement:** The loop control variable is updated (e.g., `i++`). After this, the control jumps back to Step 2 (the test condition).
    *   **Example:** Program 5.4.1 on page 81 demonstrates a `for` loop that displays numbers from 1 to 10.
*   **Page Number(s):** 80-81.

*   **Question:** (211, B#3) Explain the memory representation of two dimensional arrays with proper example.
*   **Answer:** "A two-dimensional array can be considered as a table which will have x number of rows and y number of columns." In memory, 2D arrays are stored in "contiguous memory location row wise." This means that after all elements of the first row (`a[0][0]`, `a[0][1]`, etc.) are stored, the elements of the next row (`a[1][0]`, `a[1][1]`, etc.) immediately follow them in memory. The address of each element can be calculated from the base address and the size of the data type.
    *   **Example:** Figure 6.3.2 and Table 2 on pages 114-115 illustrate how an integer array `int a[4][3]` is stored, showing the memory address for each element.
*   **Page Number(s):** 114, 115.

*   **Question:** (211, B#7) Explain the advantage and disadvantage of pointer.
*   **Answer:**
    *   **Advantages:** Pointers reduce program storage space and complexity, reduce execution time (increasing speed), provide an alternate way to access array elements, and are essential for dynamic memory allocation and building complex data structures (like linked lists).
    *   **Disadvantages:** "Uninitialized pointers might cause segmentation fault." Dynamically allocated memory "needs to be freed explicitly" to avoid memory leaks. Pointers can be "slower than normal variables," and if "updated with incorrect values, it might lead to memory corruption."
*   **Page Number(s):** 190, 191.

*   **Question:** (221, B#2) Write the concept of "recursion" in programming...
*   **Answer:** "In programming language, recursion is a technique or process to calling a function repeatedly. In general, recursion is nothing more than a function that calls itself." A function of this type is called a **recursive function**. When using recursion, it is critical "to define an exit condition from the function; otherwise it will go into an infinite loop." Recursive functions are helpful for solving mathematical problems like factorials and Fibonacci series.
*   **Page Number(s):** 162.

*   **Question:** (231, B#8) Describe how a function is declared and defined in C. What are function prototypes...
*   **Answer:**
    *   **Function Prototype (Declaration):** A function prototype "is a declaration of a function that specifies the function's name and type signature... but omits the function body." It tells the compiler the function's return type, name, and the types of arguments it accepts. It is declared before `main()` and ends with a semicolon. Example: `int summation(int value1, int value2);`
    *   **Function Definition:** This is the full implementation of the function. It consists of the **function header** (`return-type function_name(parameter list)`) and the **function body** (the statements inside the curly braces `{}`).
*   **Page Number(s):** 141, 142.