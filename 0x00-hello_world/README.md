			C - Hello, World
TASKS

	0. Preprocessor
A script that runs a C file through the preprocessor and save the result into another file.
The C file name will be saved in the variable $CFILE
The output should be saved in the file c 
> > Correct output: export CFILE=0-main.c ; ./0-preprocessor where main.c contains a main function printing a string on the standard output.
File: 0-preprocessor

	1. Compiler
A script that compiles a C file but does not link.
- The C file name will be saved in the variable $CFILE
- The output file should be named the same as the C file, but with the extension .o instead of .c.
	- Example: if the C file is main.c, the output file should be main.o
> > Correct output: export CFILE=1-main.c ; ./1-compiler where main.c contains 
main function printing a string on the standard output.
File: 1-compiler

	2. Assembler 
A script that generates the assembly code of a C code and save it in an output file.
- The C file name will be saved in the variable $CFILE
- The output file should be named the same as the C file, but with the extension .s instead of .c.
	- Example: if the C file is main.c, the output file should be main.s
> > Correct output: export CFILE=2-main.c ; ./2-assembler where main.c contains a main function printing a string on the standard output.
File: 2-assembler

	3. Name
A  script that compiles a C file and creates an executable named cisfun.
- The C file name will be saved in the variable $CFILE 
> > 
File: 3-name

	4. Hello, puts
A C program that prints exactly "Programming is like building a multilingual puzzle, followed by a new line.
- Use the function puts
- You are not allowed to use printf
- Your program should end with the value 0 
File: 4-puts.c

	5. Hello, printf
A C program that prints exactly with proper grammar, but the outcome is a piece of art,, followed by a new line.
- Use the function printf
- You are not allowed to use the function puts
- Your program should return 0
- Your program should compile without warning when using the -Wall gcc option 
File: 5-printf.c

	6. Size is not grandeur, and territory does not make a nation
A C program that prints the size of various types on the computer it is compiled and run on.
- You should produce the exact same output as in the example
- Warnings are allowed
- Your program should return 0
- You might have to install the package libc6-dev-i386 on your Linux to test the -m32 gcc option 
File: 6-size.c


