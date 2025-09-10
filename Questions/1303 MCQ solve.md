Here are all the questions from the provided "Computer Programming (DCSA 1303)" exam papers, organized by similar topics, with the correct answer indicated for each.

***

### **Similar & Repeated Questions by Topic**

#### **1. C Language Fundamentals (Variables, Data Types, Keywords)**

*   **Keywords and Identifiers**
    *   (Term 191, Q3): **Which of the following is not keyboard of 'C' programming language?**
        (a) int, (b) register, (c) auto, (d) function.
        **Answer: (d) function**
    *   (Term 191, Q15), (Term 211, Q29): **All keywords in C are in-**
        (a) Lower Case letters, (b) Upper Case letters, (c) Camel Case letters, (d) None.
        **Answer: (a) Lower Case letters**
    *   (Term 191, Q38), (Term 211, Q5): **A C variable cannot start with?**
        (a) An alphabet, (b) A special symbol other than underscore, (c) A number, (d) Both b and c.
        **Answer: (d) Both b and c.**
    *   (Term 201, Q34), (Term 211, Q32): **Which of the following is not a valid C variable name?**
        (a) int number;, (b) float rate;, (c) int variable_count;, (d) int $main;
        **Answer: (d) int $main;** ($ is not allowed in identifiers)
    *   (Term 211, Q15): **Which of the following is not keyword of 'C' programming language?**
        (a) int, (b) register, (c) auto, (d) function
        **Answer: (d) function**
    *   (Term 201, Q35), (Term 211, Q23): **Which of the following are tokens in C?**
        (a) Keywords, (b) Constants, (c) Identifiers, (d) All of this above
        **Answer: (d) All of this above**

*   **Data Types and Size**
    *   (Term 191, Q2): **Which format specifier is used to print the values of double type variable-**
        (a) %lf, (b) %lu, (c) %ld, (d) %f.
        **Answer: (a) %lf** (While `%f` often works for printing doubles due to promotion, `%lf` is the technically correct and specific format specifier for `double` in `scanf` and is commonly used for `printf` as well for consistency).
    *   (Term 191, Q11), (Term 231, Q12): **Which is correct with respect to size of the datatypes?**
        (a) char> int > float, (b) int > char> float, (c) char< int < double, (d) double > char > int.
        **Answer: (c) char < int < double**
    *   (Term 191, Q13), (Term 201, Q29): **The C language defines ___ fundamental data types.**
        (a) 5, (b) 3, (c) 6, (d) 4
        **Answer: (a) 5** (Typically refers to `int`, `char`, `float`, `double`, and `void`)
    *   (Term 231, Q1): **Which format specifier is used to print the values of double type variable**
        (a) %lf, (b) %lu, (c) %ld, (d) %f
        **Answer: (a) %lf**
    *   (Term 231, Q8): **The C language consists of ___ number of keywords.**
        (a) 32, (b) 40, (c) 36, (d) 30
        **Answer: (a) 32**

*   **Constants**
    *   (Term 191, Q7), (Term 211, Q1): **Character constants should be enclosed between -**
        (a) Single quotes, (b) Double quotes, (c) Both a and b, (d) None of These.
        **Answer: (a) Single quotes**
    *   (Term 201, Q19), (Term 221, Q15): **The following is an invalid real number**
        (a) 0.0, (b) 5000.0067, (c) 1,00.08, (d) -50.26e-18.
        **Answer: (c) 1,00.08** (Commas are not allowed within numbers)
    *   (Term 231, Q21), (Term 221, Q4): **Which of the following is the valid expression for character constant?**
        (a) 'A', (b) "A", (c) 'A, (d) "A""
        **Answer: (a) 'A'**

*   **Operators and Precedence**
    *   (Term 191, Q17): **The precedence of arithmetic operators from highest to lowest is--**
        (a) %, *, /, +, -, (b) %, +, /, *, -, (c) +, -, %, *, /, (d) %, +, -, *, /.
        **Answer: (a) %, *, /, +, -** (Note: `*`, `/`, `%` have the same precedence)
    *   (Term 221, Q5): **The most commonly used assignment is.**
        (a) ==, (b) =, (c) >=, (d) +
        **Answer: (b) =**
    *   (Term 231, Q3): **Which of the following is not a relational operator?**
        (a) >=, (b) !=, (c) <, (d) !
        **Answer: (d) !** (`!` is the logical NOT operator)
    *   (Term 211, Q18): **Which of the following is not a relational operator?**
        (a) >=, (b) !=, (c) <, (d) !
        **Answer: (d) !**
    *   (Term 191, Q18): **Which of the following is not an arithmetic operation?**
        (a) a *= 10;, (b) a /= 10;, (c) a != 10;, (d) a %= 10;
        **Answer: (c) a != 10;** (`!=` is a relational operator)

*   **Type Conversion**
    *   (Term 191, Q28), (Term 231, Q2): **Explicit type conversion is known as-**
        (a) conversion, (b) separation, (c) disjunction, (d) casting
        **Answer: (d) casting**

*   **Static Variables**
    *   (Term 191, Q9), (Term 211, Q17): **A static variable by default gets initialized to-**
        (a) 0, (b) Blank space, (c) 1, (d) Garbage value.
        **Answer: (a) 0**

#### **2. Control Structures**

*   **Loops (General)**
    *   (Term 191, Q14), (Term 201, Q37), (Term 231, Q14): **do-while loop terminates when conditional expression returns?**
        (a) zero, (b) 1 / One, (c) -1, (d) Non-zero.
        **Answer: (a) zero**
    *   (Term 191, Q19): **The following code 'for(;;)' represents an infinite loop. It can be terminated by.**
        (a) break, (b) exit(0), (c) abort(), (d) All of the above.
        **Answer: (d) All of the above.**
    *   (Term 221, Q10): **The while statement is used to carry out**
        (a) looping operation, (b) logical test, (c) numerical calculation, (d) all of the above
        **Answer: (a) looping operation**

*   **`continue` Statement**
    *   (Term 191, Q25): **'continue' statement is used**
        (a) to go to the next iteration in a loop, (b) come out of a loop, (c) exit and return to the main function, (d) restarts iterations from beginning of loop.
        **Answer: (a) to go to the next iteration in a loop**
    *   (Term 231, Q6): **Continue statement is used for-**
        (a) to go to the next iteration in a loop, (b) exit and return to the main function, (c) come out of a loop, (d) restarts iterations from beginning of loop
        **Answer: (a) to go to the next iteration in a loop**

*   **Unconditional Control (goto)**
    *   (Term 191, Q5), (Term 231, Q4), (Term 211, Q9): **Which among the following is an unconditional control structure?**
        (a) for, (b) do-while, (c) if-else, (d) goto.
        **Answer: (d) goto**
    *   (Term 221, Q16): **In general form, the goto statement is written as**
        (a) goto statement, (b) goto label, (c) goto {expression}, (d) goto
        **Answer: (b) goto label**

#### **3. Arrays**

*   **Declaration and Size**
    *   (Term 191, Q31), (Term 231, Q7), (Term 211, Q4): **Maximum number of elements in the array declaration int a is**
        (a) 32, (b) 42, (c) 40, (d) 28.
        **Answer: (c) 40** (5 * 8 = 40)
    *   (Term 191, Q37): **Which of the following statement are correct about an array?**
        (a) The array int num; can store 25 elements, (b) It is necessary to initialized the array at the time of declaration, (c) The expression num designated the very first element..., (d) The expression num designated the 16th element...
        **Answer: (a) The array int num; can store 25 elements**
    *   (Term 221, Q12): **What is the correct syntax to declare a one-dimensional array in C?**
        (a) int array[];, (b) int array[size];, (c) array[] = int;, (d) int[] array;
        **Answer: (b) int array[size];**

*   **Initialization and Indexing**
    *   (Term 191, Q21): **Which one is correct initialization of an array with all elements as zero?**
        (a) int array = {};, (b) int array = {0};, (c) int a=0,b=0,c=0; int array={a,b,c};, (d) All of the mentioned.
        **Answer: (b) int array = {0};**
    *   (Term 191, Q24): **In C Programming array index is always starts from:**
        (a) 0, (b) 1, (c) 2, (d) 3.
        **Answer: (a) 0**
    *   (Term 201, Q21), (Term 211, Q22): **Subscript of array**
        (a) must be positive integer, (b) no restriction about +ve or -ve, (c) must begin from 0, (d) none of above.
        **Answer: (c) must begin from 0**

*   **Problems/Characteristics of Arrays**
    *   (Term 201, Q23), (Term 201, Q25), (Term 211, Q33): **Problem of using array is**
        (a) array size must be mentioned previously, (b) array size can not be altered at any time, (c) deletion and insertion of elements in sorted list, (d) none of the above.
        **Answer: (b) array size can not be altered at any time** (This is a primary limitation of static arrays in C)

#### **4. Pointers**

*   **Declaration and Operators**
    *   (Term 191, Q8), (Term 221, Q3): **An Ampersand before the name of a variable denotes-**
        (a) Actual Value, (b) Variable Name, (c) Address, (d) Data Type.
        **Answer: (c) Address**
    *   (Term 191, Q40), (Term 231, Q15): **The operator used to get value at address stored in a pointer variable is-**
        (a) &&, (b) *, (c) &, (d) ||.
        **Answer: (b) ***
    *   (Term 191, Q35), (Term 231, Q11), (Term 211, Q27): **What is size of generic pointer in c?**
        (a) 0, (b) 1, (c) 2, (d) Undefined.
        **Answer: (c) 2** (On a 16-bit system. On 32-bit systems it's 4, on 64-bit it's 8. 2 is a common answer for older compilers/systems.)
    *   (Term 231, Q9): **Which of the following is the correct way of declaring a float pointer:**
        (a) float ptr;, (b) *float ptr;, (c) float *ptr;, (d) None of the above.
        **Answer: (c) float *ptr;**
    *   (Term 221, Q27): **When a pointer variable is declared, the variable name must be preceded by**
        (a) Asterisk (*) sign, (b) & sign, (c) %% sign, (d) (**) sign
        **Answer: (a) Asterisk (*) sign**

#### **5. Functions and Recursion**

*   **Function Basics**
    *   (Term 221, Q17): **Function prototypes are usually written**
        (a) at the end of the programme, (b) middle of the programme, (c) at the beginning of a programme, (d) all of the above
        **Answer: (c) at the beginning of a programme**
    *   (Term 221, Q18): **Passing by value is restricted to an one way transfer of**
        (a) information, (b) data, (c) information and data, (d) arguments
        **Answer: (a) information**

*   **Recursion**
    *   (Term 191, Q10), (Term 231, Q16): **Recursion is sometimes called?**
        (a) Circular definition, (b) Union, (c) Complex definition, (d) Procedure
        **Answer: (a) Circular definition**
    *   (Term 191, Q12), (Term 201, Q38), (Term 211, Q36): **Recursive functions are executed in which order-**
        (a) Parallel order, (b) Iterative order, (c) Last in first out, (d) Random order.
        **Answer: (c) Last in first out**

#### **6. C Environment and General Programming**

*   **Platform Availability**
    *   (Term 191, Q6), (Term 231, Q5): **C language is available for which of the following Operating Systems?**
        (a) Unix, (b) DOS, (c) Windows, (d) All of these.
        **Answer: (d) All of these.**

*   **Header Files**
    *   (Term 191, Q30): **Header files in C contain-**
        (a) Compiler commands, (b) Header information of C, (c) Library functions, (d) Operators for files.
        **Answer: (c) Library functions** (Declarations for library functions)
    *   (Term 221, Q2): **Which header file should be included to use the printf and scanf functions in C?**
        (a) stdlib.h, (b) string.h, (c) math.h, (d) stdio.h
        **Answer: (d) stdio.h**

*   **Standard I/O and Functions**
    *   (Term 191, Q26), (Term 221, Q14), (Term 231, Q19): **Identify the wrong statement**
        (a) putchar(65), (b) putchar('x'), (c) putchar("x"), (d) putchar('\n').
        **Answer: (c) putchar("x")** (`putchar` takes an integer/char, not a string literal)

*   **Program Development and Languages**
    *   (Term 201, Q30), (Term 221, Q1): **Which of the following is not high level language?**
        (a) PASCAL, (b) C, (c) Machine language, (d) LISP.
        **Answer: (c) Machine language**
    *   (Term 201, Q28), (Term 211, Q30): **You cannot run program before**
        (a) correcting logical errors, (b) correcting your data structure, (c) correcting your compiling errors, (d) none of the above.
        **Answer: (c) correcting your compiling errors**
    *   (Term 211, Q38), (Term 221, Q29): **Which one is known as translator of source program into machine language?**
        (a) compilation, (b) portability, (c) execution, (d) booting.
        **Answer: (a) compilation**

*   **Rounding a Float**
    *   (Term 191, Q34), (Term 201, Q22), (Term 231, Q10): **We want to round off x, a float, to an int value, The correct way to do is**
        (a) y=(int)x+0.5, (b) y=int(x+0.5), (c) y=(int)(x + 0.5), (d) y=(int)((int)x +0.5).
        **Answer: (c) y = (int)(x + 0.5);**

*   **Specific Function Values**
    *   (Term 201, Q20), (Term 221, Q20): **What will be the value of the following function: round(-4.667)**
        (a) -5, (b) -4, (c) 5, (d) 4
        **Answer: (a) -5**
    *   (Term 191, Q4), (Term 191, Q29 - duplicate): **What will be the output ? void main () { printf("\n %d %d", 10&20, 10/20); }**
        (a) 0 0, (b) 20 20, (c) 10 10, (d) 0 30.
        **Answer: (a) 0 0** (Bitwise AND of 10 (`01010`) and 20 (`10100`) is 0. Integer division 10/20 is 0.)

***

### **Unique Questions (Appearing in Only One Term)**

*   (Term 191, Q1): **The ___ structure involves repeating a sequence until a condition is met.**
    (a) loop, (b) sequence, (c) conditional, (d) selection.
    **Answer: (a) loop**
*   (Term 191, Q20): **Which of the following are correct syntaxes to send an array as a parameter to function?**
    (a) func(&array), (b) func(&&array), (c) func(*array), (d) func(array[size]).
    **Answer: (c) func(*array)** (or func(array[]))
*   (Term 191, Q22): **An array of similar data types which themselves are collection of dissimilar data type are:**
    (a) Linked List, (b) Trees, (c) Array of structure, (d) All of the above.
    **Answer: (c) Array of structure**
*   (Term 191, Q23): **Which of the following function compares 2 strings with case-insensitively?**
    (a) strcmp(s, t), (b) strcmpcase(s, t), (c) strcasecmp(s, t), (d) strchr(s, t)
    **Answer: (c) strcasecmp(s, t)** (Note: This is not a standard C library function, but common in Unix-like systems)
*   (Term 191, Q27): **The programming tool that uses linked symbols to show the sequence of steps needed to solve a programming problem.**
    (a) grid table, (b) pseudocode, (c) algorithm, (d) flow chart.
    **Answer: (d) flow chart**
*   (Term 191, Q32): **The case keyword is followed by**
    (a) Float values, (b) Character values, (c) Int values, (d) Both b and c.
    **Answer: (d) Both b and c.** (case labels must be integer constants, which includes character constants)
*   (Term 191, Q33): **For 16-bit compiler allowable range for integer constant is-**
    (a) -304e38 to 304e38, (b) 32668 to 32667, (c) -32767 to 32768, (d) -32768 to 32767.
    **Answer: (d) -32768 to 32767.**
*   (Term 191, Q36): **The expression X=4+2%8 evaluates-**
    (a) 6, (b) 6, (c) 4, (d) None. (Typo in options)
    **Answer: 6** (2%8 is 2, then 4+2 is 6)
*   (Term 191, Q39): **The break statement is used to exit from:**
    (a) an if statement, (b) a program, (c) a for loop, (d) the main() function.
    **Answer: (c) a for loop** (and while, do-while, switch)
*   (Term 201, Q24): **If you want to get access to the 10th character of student name you have to give the following reference**
    (a) student, (b) student.std-CRS, (c) student.std-GPA, (d) student.std-NAM.
    **Answer: (d) student.std-NAM.** (assuming std-NAM is the character array for the name)
*   (Term 201, Q26): **The input variable of read statement are separated by**
    (a) tab, (b) blank space, (c) commas, (d) line feed.
    **Answer: (c) commas**
*   (Term 201, Q27): **Semicolons are used as**
    (a) instructions, (b) I/O statements, (c) separator of statements, (d) none of the above.
    **Answer: (c) separator of statements** (More accurately, a statement terminator)
*   (Term 201, Q31): **In ___-down design is often desirable to**
    (a) write an incomplete program sketch, (b) write individual modules first, (c) do the documentation first, (d) code first.
    **Answer: (a) write an incomplete program sketch**
*   (Term 201, Q32): **The fan-out of a module should be within**
    (a) 7 ± 2, (b) 8 ± 2, (c) 9 ± 2, (d) 11 ± 2.
    **Answer: (a) 7 ± 2** (A software engineering heuristic)
*   (Term 201, Q36): **Which one supports the similarity of Warnier-Orr diagram and structured chart?**
    (a) Repetition symbol, (b) Main structure, (c) Tree structure, (d) Looping.
    **Answer: (c) Tree structure**
*   (Term 201, Q39): **Which of the following data type must be initialized before using?**
    (a) Pointer, (b) Character, (c) Integer, (d) Array.
    **Answer: (a) Pointer**
*   (Term 201, Q40): **Break points are placed**
    (a) where errors can be determined, (b) where errors can be occurred, (c) all of the above, (d) none of the above.
    **Answer: (b) where errors can be occurred**
*   (Term 231, Q13): **Which of the following is the correct way of writing comments?**
    (a) */comments/*;, (b) /*comments*/;, (c) **comments**;, (d) {comments};
    **Answer: (b) /*comments*/;**
*   (Term 231, Q18): **Which of the following declaration throw run-time error?**
    (a) int **c = &c;, (b) int **c = &*c;, (c) int **c = *c;, (d) None of the above.
    **Answer: (d) None of the above.** (These are compile-time errors, not run-time errors)
*   (Term 231, Q20): **What is the correct syntax to include a header file in C?**
    (a) #include <filename.h>;, (b) include <filename.h>;, (c) #include "filename.h";, (d) #include {filename.h};
    **Answer: (c) #include "filename.h";** (and `<filename.h>`)
*   (Term 231, Q23): **The getchar function is a part of the standard C**
    (a) I/O library, (b) input library, (c) output library, (d) all of the above
    **Answer: (a) I/O library** (`stdio.h`)
*   (Term 231, Q24): **Most C compiler will generate**
    (a) error message, (b) diagnostic message, (c) debugging message, (d) syntactic error
    **Answer: (b) diagnostic message**
*   (Term 231, Q25): **The while statement is used to carry out**
    (a) looping operation, (b) logical test, (c) numerical calculation, (d) all of the above
    **Answer: (a) looping operation**
*   (Term 231, Q26): **Which of the following correctly declares an array in C?**
    (a) int arr;, (b) array int;, (c) int arr();, (d) int arr;
    **Answer: (a) int arr;**
*   (Term 231, Q30): **Which of the following is often to as global variables?**
    (a) Automatic variables, (b) External variables, (c) Static variables, (d) Automatic and External variables
    **Answer: (b) External variables**
*   (Term 231, Q31): **What is the maximum number of arguments that can be passed to a function in C?**
    (a) 127, (b) 255, (c) 512, (d) No limit
    **Answer: (d) No limit** (The C standard does not specify a limit, though implementations will have one)
*   (Term 231, Q33): **Structure declarations are somewhat more complicated than**
    (a) pointer declaration, (b) array declaration, (c) array and pointer declaration, (d) function declaration
    **Answer: (b) array declaration**
*   (Term 231, Q34): **The typedef feature allows users to define new data types that are equivalent to**
    (a) existing data types, (b) new data types, (c) initial data types, (d) all of the above
    **Answer: (a) existing data types**
*   (Term 231, Q35): **The pointer ptvar is often referred to as**
    (a) null pointer, (b) a stream pointer, (c) buffer area, (d) all of the above
    **Answer: (b) a stream pointer**
*   (Term 231, Q36): **The syntax of library function fclose is**
    (a) ffclose(ptvar);, (b) close(ptvar);, (c) fclose(ptvar);, (d) fclosed(ptvar);
    **Answer: (c) fclose(ptvar);**
*   (Term 231, Q39): **A external variable declaration must begin with the storage-class specifies**
    (a) Auto, (b) Extern, (c) Static, (d) Extern and Static
    **Answer: (b) Extern**
*   (Term 231, Q40): **Each pointer will indicate the beginning of a separate**
    (a) (n-1) dimensional array, (b) 2n-dimensional array, (c) n-dimensional array, (d) (2n-1) dimensional array
    **Answer: (c) n-dimensional array**
*   (Term 221, Q6): **Which of the following is library function in C?**
    (a) printf(...), (b) &&, (c) print(...), (d) printf.
    **Answer: (d) printf.**
*   (Term 221, Q7): **Each character group must begin with a sign**
    (a) %, (b) *, (c) #, (d) $
    **Answer: (a) %**
*   (Term 221, Q9): **Which one is not the debugging technique?**
    (a) Error isolation, (b) Tracing, (c) Watch values, (d) calculation
    **Answer: (d) calculation**
*   (Term 221, Q13): **What does the "sizeof" operator return in C?**
    (a) The size of a variable in bytes, (b) The value of a variable, (c) The data type of a variable, (d) The address of a variable
    **Answer: (a) The size of a variable in bytes**
*   (Term 221, Q19): **Which type of operator can not be used for character type data?**
    (a) arithmetic, (b) relational, (c) logical, (d) none of the above.
    **Answer: (d) none of the above.** (All can be used, as chars are treated as integers)
*   (Term 221, Q21): **Recursion is a process by which a function calls itself**
    (a) repeatedly, (b) only one time, (c) two times, (d) all of the above
    **Answer: (a) repeatedly**
*   (Term 221, Q22): **Which of the following is often to as global variables?**
    (a) Automatic variables, (b) External variables, (c) Static variables, (d) Automatic and External variables
    **Answer: (b) External variables**
*   (Term 221, Q23): **Within a multi-file program, a function definition may be either**
    (a) External or Static, (b) Static or Automatic, (c) External or Automatic, (d) Automatic or Static
    **Answer: (a) External or Static**
*   (Term 221, Q24): **An entire array can be passed to be a function as**
    (a) a function, (b) an argument, (c) data, (d) function and argument
    **Answer: (b) an argument**
*   (Term 221, Q26): **What does indicate a subscripted variable?**
    (a) Pointer address of specific data, (b) memory element, (c) relative position of data from beginning, (d) Individual item of data
    **Answer: (d) Individual item of data**
*   (Term 221, Q28): **What does the acronym "SQL" stand for in the context of databases?**
    (a) Structured Query Language, (b) Simple Query Language, (c) Standard Query Language, (d) System Query Language
    **Answer: (a) Structured Query Language**
*   (Term 221, Q30): **Which of the following is NOT a control structure in programming?**
    (a) Sequence, (b) Loop, (c) Function, (d) Decision
    **Answer: (c) Function**
*   (Term 221, Q32): **What is the purpose of the "if-else" statement in programming?**
    (a) To declare a variable, (b) To perform arithmetic operations, (c) To control the flow of program execution based on a condition, (d) To define a function
    **Answer: (c) To control the flow of program execution based on a condition**
*   (Term 221, Q33): **Which of the following is NOT a fundamental data structure in programming?**
    (a) Array, (b) Stack, (c) Queue, (d) Object
    **Answer: (d) Object**
*   (Term 221, Q35): **a data file must be created before it can be**
    (a) processed, (b) closed, (c) opened, (d) stated
    **Answer: (a) processed**
*   (Term 221, Q37): **What is the purpose of the "break" statement in a loop?**
    (a) To terminate the loop and exit..., (b) To skip the current iteration..., (c) To restart the loop..., (d) To pause the execution...
    **Answer: (a) To terminate the loop and exit the loop's block of code**
*   (Term 221, Q38): **What does the term "IDE" stand for in software development?**
    (a) Integrated Development Environment, (b) Interface Design Element, (c) Interactive Debugging Environment, (d) Intermediate Data Exchange
    **Answer: (a) Integrated Development Environment**
*   (Term 221, Q39): **Which of the following is NOT a programming paradigm?**
    (a) Procedural, (b) Object-oriented, (c) Functional, (d) Linear
    **Answer: (d) Linear**
*   (Term 221, Q40): **What is the purpose of a loop in programming?**
    (a) To perform a specific action based on a condition, (b) To define a function, (c) To declare variables, (d) To perform arithmetic operations
    **Answer: (a) To perform a specific action based on a condition** (More accurately, to repeat an action)
*   (Term 211, Q2): **FOR and DO-WHILE loops are**
    (a) I/O, (b) Structural, (c) Sequence control statements, (d) none of the above.
    **Answer: (c) Sequence control statements**
*   (Term 211, Q3): **Which one of the following statement is true?**
    (a) Algorithm is a part of programming, (b) Algorithm is a part of system design, (c) Algorithm is a part of problem solving, (d) Algorithm is a part of system analysis
    **Answer: (c) Algorithm is a part of problem solving**
*   (Term 211, Q6): **By default a function returns a value of ____ type.**
    (a) int, (b) float, (c) void, (d) char
    **Answer: (a) int**
*   (Term 211, Q7): **Pointer data types are used to**
    (a) construct dynamic structured data types, (b) records, (c) files, (d) static structured data types.
    **Answer: (a) construct dynamic structured data types**
*   (Term 211, Q10): **Which one is valid?**
    (a) Stack is accessible only from top, (b) Stack is accessible only from bottom, (c) Stack is accessible insertion from top and deletion from bottom, (d) Stack is accessible insertion from bottom and deletion from top
    **Answer: (c) Stack is accessible insertion from top and deletion from bottom**
*   (Term 211, Q11): **Let x=4, y=5, x=++y. What is the value of (x,y)?**
    (a) 4,5, (b) 4,6, (c) 3,5, (d) 6,6
    **Answer: (d) 6,6** (y becomes 6, then x is assigned the value 6)
*   (Term 211, Q12): **Recursive function is flexible in**
    (a) array, (b) linked list, (c) data structure, (d) variable declaration.
    **Answer: (b) linked list**
*   (Term 211, Q13): **Which one represents start and end blocks of a flowchart?**
    (a) Ellipse, (b) Circle, (c) Rectangle, (d) Cone
    **Answer: (a) Ellipse**
*   (Term 211, Q14): **Which of the following languages is nearest to structured English?**
    (a) High Level, (b) Pascal or C, (c) Machine, (d) Macro assembler
    **Answer: (b) Pascal or C**
*   (Term 211, Q16): **For call by reference the value of the parameter must be**
    (a) expression, (b) operator, (c) variable, (d) array.
    **Answer: (c) variable** (Specifically, the address of a variable)
*   (Term 211, Q19): **Which type of operator cannot be used for character type data?**
    (a) arithmetic, (b) relational, (c) logical, (d) none of the above
    **Answer: (d) none of the above**
*   (Term 211, Q24): **Generally errors occurred in WHILE and REPEAT loops. This is due to misunderstanding on**
    (a) number of iterations, (b) concept of semicolons, (c) concept of BEGIN - END, (d) none of the above.
    **Answer: (a) number of iterations**
*   (Term 211, Q25): **Switch statement accepts**
    (a) int, (b) char, (c) long, (d) All of the above.
    **Answer: (d) All of the above.**
*   (Term 211, Q26): **Which programming language does not support recursion?**
    (a) C, (b) PASCAL, (c) PROLOG, (d) FORTRAN
    **Answer: (d) FORTRAN** (Early versions like FORTRAN 77)
*   (Term 211, Q28): **The input variable of read statement are separated by**
    (a) tab, (b) blank space, (c) commas, (d) line feed.
    **Answer: (c) commas**
*   (Term 211, Q31): **Which keyword can be used for coming out of recursion?**
    (a) break, (b) return, (c) Both (a) and (b), (d) Exit
    **Answer: (b) return**
*   (Term 211, Q34): **A function has no arguments but it may**
    (a) return a value, (b) not return a value, (c) call a function, (d) None of the mentioned.
    **Answer: (a) return a value**
*   (Term 211, Q37): **The keyword 'break' cannot be simply used within**
    (a) do-while, (b) if-else, (c) for, (d) while.
    **Answer: (b) if-else**
*   (Term 211, Q39): **Break points are placed**
    (a) where errors can be determined, (b) where errors can be occurred, (c) all of the above, (d) none of the above.
    **Answer: (b) where errors can be occurred**
*   (Term 211, Q40): **Standard functions are included with C compilers, which are**
    (a) Modifiable in, (b) Rewriteable, (c) Not rewritable, (d) None of these.
    **Answer: (c) Not rewritable**