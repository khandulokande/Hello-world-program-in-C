# Hello World Program in C
In this repository I'm covered hello world program in c. 

```bash
#include <stdio.h>

int main() {
    printf("Hello World");
    return 0;
}
```

```bash
#include <stdio.h>
```
This line is a preprocessor directive. It tells the compiler to include the standard input-output library before actual compilation starts. The stdio.h header file contains definitions for various input and output functions, including printf.
Functionality: Without including stdio.h, you wouldn't be able to use the printf function because the compiler wouldn't recognize it.


```bash
int main() {
  // code here
}
```
This defines the main function, which is the entry point of any C program. The execution of the program starts from the main function.
The int before main specifies that the function returns an integer value to the operating system upon completion. This return value is typically used to indicate whether the program ended successfully or if there was an error.

```bash
printf("Hello World");
```
This line calls the printf function to print the string "Hello World" to the console.
printf is a standard library function declared in stdio.h. It formats and prints a series of characters and values to the standard output (usually the screen). In this case, it prints the string literal "Hello World".
The "Hello World" inside the parentheses is a string literal, which is a sequence of characters enclosed in double quotes.


```bash
return 0;
```
This statement indicates that the main function returns the integer value 0 to the operating system.
Returning 0 from the main function typically signifies that the program has executed successfully. Non-zero return values usually indicate some kind of error or abnormal termination.


## Execution Flow
### Compilation
When the code is compiled, the preprocessor replaces #include <stdio.h> with the contents of the stdio.h header file, which contains declarations for all the input-output functions.
### Start
The main function is where the program starts execution.
### Output
The printf function is called, which outputs the string "Hello World" to the console.
### Termination
The return 0; statement is executed, which terminates the program and returns the value 0 to the operating system, indicating successful completion.


## Example Run
When you run this program, the console will display:

```bash
Hello World
```

And the program will exit, returning 0 to the operating system, which signifies that the program executed without any errors.

Thank you.
