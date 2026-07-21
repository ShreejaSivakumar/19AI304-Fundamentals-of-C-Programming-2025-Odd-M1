# 19AI304-Fundamentals-of-C-Programming-2025-Odd-M1
### Step 2: 
  Include the standard input-output library: #include<stdio.h>.
### Step 3: 
  Inside the main() function, use printf() to display each literal along with its size in bytes using sizeof() :
  
   3.1 Integer literal (e.g., 10) using `%d`
   
   3.2 Float literal (e.g., 3.14) using `%f`
   
   3.3 Character literal (e.g., 'A') using `%c`
   
   3.4 String literal (e.g., "Hello C") using `%s`
   
### Step 4: 
   Stop
# Program:
```
#include <stdio.h>

int main()
{
    int num = 100;            // Integer literal
    float pi = 3.14;          // Float literal
    char grade = 'A';         // Character literal
    char name[] = "Saveetha"; // String literal

    printf("Integer Literal: %d\n", num);
    printf("Float Literal: %.2f\n", pi);
    printf("Character Literal: %c\n", grade);
    printf("String Literal: %s\n", name);

    return 0;
}
```

# Output:
<img width="1490" height="541" alt="image" src="https://github.com/user-attachments/assets/ac3242ab-9ab4-4cf8-8049-6c8871a732b1" />

# Result: 
Thus, the program was implemented and executed successfully, and the required output was obtained.


# 19AI304-Fundamentals-of-C-Programming-2025-Odd
# IAPR-1- Module 1 - FoC
# Ex.No:2
  Build a C program to display the value of a macro constant and a constant variable.
# Date : 17/04/2026
# Aim:
  To build a C program that demonstrates the use of macro constants and constant variables.
# Algorithm:
### Step 1:
  Start  
### Step 2: 
  Include the standard input-output library: #include<stdio.h>.
### Step 3: 
  Define a macro constant `PI` with value `3.14159` using `#define`.
### Step 4: 
   Inside `main()`:
   
   4.1 Declare a constant integer variable `DAYS`
   
   4.2 Initialize it with the value `7`
