# Command-Line-Interpreter

A basic command line interpreter which takes linux commands as inputs, executes them and displays appropriate output.

This program utilizes exec() family functions.

Main function is the parent process. It creates a child process to execute the command through defined function execute(). 

To run this program:
- Save the interpreter.c file in a Linux environment.
- Compile the file using a C compiler
- Run the program  --->  ./interpreter
