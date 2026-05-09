# Structured Programming: C Fundamentals (Midterm Notes)

## 1. Problem Solving and Methodology (Week 1)
* **Steps:** Problem definition ➡️ Analysis ➡️ Solution design (Algorithm) ➡️ Implementation ➡️ Testing/Evaluation.
* **Algorithm:** A finite sequence of well-defined steps to solve a problem.
* **Tools:**
  * **Flowcharts:** Graphical representation of logic.
  * **Pseudocode:** Structured, English-like description of the code.
* **Debugging:** Identifying and fixing errors in the code.
  * *Error Types:* Syntax (grammar/rules), Runtime (crashes during execution), Logical (incorrect output/behavior).

## 2. Programming Language Fundamentals & Paradigms (Week 2)
* **Definition:** A system of communication (intermediate language) used to direct computer activities.
* **Classification by Level:**
  * **Low-Level:** **1GL:** Machine Language (binary code). **2GL:** Assembly Language (mnemonics).
  * **High-Level:** User-friendly, English-like syntax (**3GL:** C, Pascal; **4GL:** SQL).
* **Translators:** 
  * **Assembler:** Converts assembly code to machine code.
  * **Compiler:** Translates the *entire* program at once; results in faster execution (e.g., C, C++).
  * **Interpreter:** Translates *line-by-line*; results in slower execution (e.g., Python).
* **Programming Paradigms:**
  * **Structured:** Focuses on structured control flows (`if`, loops). Avoids `goto` (spaghetti code).
  * **Procedural:** Programs are divided into blocks called **procedures** or **functions**. Top-down approach.
  * **Object-Oriented (OOP):** Based on **Objects** (data + methods). Concepts: Encapsulation, Inheritance. Bottom-up approach.

## 3. Introduction to C, Tokens & Data Types (Week 3)
* **History:** Developed in 1972 by Dennis Ritchie at Bell Laboratories for UNIX.
* **Program Structure:**
  * **Preprocessor Directives:** e.g., `#include <stdio.h>`.
  * **Main Function:** `int main() { ... }` (Entry point).
  * **Statements:** Must end with a semicolon (`;`).
* **Tokens:** The smallest meaningful units (keywords, identifiers, constants, strings, operators).
* **Keywords:** Predefined reserved words (e.g., `int`, `return`). **Cannot** be variable names.
* **Identifiers:** User-defined names. Must start with a letter or `_`, case-sensitive.
* **Data Types and Format Specifiers:**

| Data Type | Size | Format Specifier | Example | Description |
|---|---|---|---|---|
| `int` | 4 bytes | `%d` | `int age = 20;` | Whole numbers |
| `float` | 4 bytes | `%f` | `float pi = 3.14;` | Fractional (6-7 decimals) |
| `double` | 8 bytes | `%lf` | `double e = 2.718;`| High-precision fractional |
| `char` | 1 byte | `%c` | `char grade = 'A';`| Single characters |

## 4. Expressions, Operators, and I/O (Week 4)
* **Expression:** A combination of constants, variables, and operators.
* **Statement:** An expression terminated by a semicolon (`;`).
* **Operators:**
  * **Arithmetic:** `+`, `-`, `*`, `/`, `%` (modulus = remainder).
  * **Relational:** `==`, `!=`, `>`, `<`, `>=`, `<=` (Returns true/false).
  * **Logical:** `&&` (AND), `||` (OR), `!` (NOT).
  * **Increment/Decrement:** `++` and `--` (Prefix: `++a`, Postfix: `a++`).
* **Input and Output Functions:**
  * `printf("Age: %d\n", age);` - Outputs formatted text to screen.
  * `scanf("%d", &age);` - Reads from keyboard (uses `&` to target address).
* **Common Library Functions:** (Requires `#include` header)
  * `<stdio.h>`: `printf()`, `scanf()`, `puts()`, `gets()`.
  * `<math.h>`: `pow(x, y)`, `sqrt(x)`, `abs(x)`.
  * `<string.h>`: `strlen()`, `strcpy()`, `strcmp()`.

## 5. Control Structures & Loops (Week 5)
* **Conditional Structures:**
  * **`if-else`:** Two paths.
    ```c
    if (age >= 18) {
        printf("Adult");
    } else {
        printf("Minor");
    }
    ```
  * **Ternary Operator:** One-line alternative: `(age >= 18) ? printf("Adult") : printf("Minor");`
  * **`switch` Statement:** Cleaner than long `if-else` chains. Cannot test `float`.
    ```c
    switch (grade) {
        case 'A': 
            printf("Excellent"); 
            break;
        default: 
            printf("Invalid");
    }
    ```
* **Loops (Iteration Control):**
  * **`for` Loop:** When exact iterations are known.
    ```c
    for (int i = 0; i < 5; i++) {
        printf("%d", i);
    }
    ```
  * **`while` Loop:** Entry-controlled. Used when iterations are unknown.
  * **`do-while` Loop:** Exit-controlled. Executes **at least once** regardless of condition.
  * **Control Statements:** `break` (exits loop), `continue` (skips iteration).

## 6. Functions (Week 5)
* **Definition:** Self-contained block to perform a task. Promotes **reusability** and **modularity**.
* **Core Elements:**
  1. **Prototype (Declaration):** Tells compiler what to expect.
     ```c
     int add(int a, int b);
     ```
  2. **Definition:** Actual logic/body.
     ```c
     int add(int a, int b) {
         return a + b;
     }
     ```
  3. **Call:** Invoking it in your code.
     ```c
     int result = add(5, 3);
     ```
* **Parameters vs. Arguments:** 
  * **Parameters:** Variables in declaration (`a`, `b`). 
  * **Arguments:** Passed values during call (`5`, `3`).
