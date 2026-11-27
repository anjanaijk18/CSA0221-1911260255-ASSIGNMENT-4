NAME : J K ANJANAI
REG NO : 1911260255
SUBJECT : C PROGRAMMING
CODE : CSA0221

Compiler Details

Compiler: GCC (GNU Compiler Collection)

Compiler Version: Check using the command:

gcc --version

Programs and Results

Task 4.1 – Automatic Storage Class

File: task4_automatic.c

Demonstrates automatic local variables. The variable is initialized every time the function is called.

Result: Each function call returns 1001.

Compilation and Execution:

gcc task4_automatic.c -o automatic
./automatic

Task 4.2 – Static Storage Class

File: task4_static.c

Demonstrates static local variables that retain their values between function calls.

Result: Generates sequential tokens 1001, 1002 and 1003.

gcc task4_static.c -o static
./static

Task 4.3 – Global Storage Class Using extern

Files: main.c and token.c

Demonstrates global variables shared between multiple source files using the extern keyword.

Result: Generates sequential token numbers using a global counter.

gcc main.c token.c -o global
./global

Task 4.4 – Register Storage Class

File: task5_register.c

Demonstrates the register storage class using a loop variable.

Result: Displays token numbers from 1001 to 1003.

gcc task5_register.c -o register
./register

Task 4.5 – Two Independent Counters

File: task5_two_counters.c

Demonstrates two independent counters for vegetarian and non-vegetarian tokens.

Result: Both counters independently generate 1001, 1002 and 1003.

gcc task4_two_counters.c -o counters
./counters

General Execution Instructions

Open the project folder in VS Code or a terminal.

Ensure GCC is installed.

Open the terminal in the project directory.

Compile the required C program using the GCC command.

Execute the generated program.

Verify the output.

Conclusion

The assignment demonstrates the different storage classes in C: automatic, static, global and register. It also explains variable lifetime, scope, persistence and the use of global variables across multiple source files.
