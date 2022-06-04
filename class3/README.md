# Class-03:

### Openning and closing files:

We use the command open() to open a file and close() to close it, and we should always close the file after we finish editing it.
There is another argument and its built-in, this argument is a string that contains multiple characters to represent how you want to open the file. The default method for openning the file is 'r', which represents opening the file in read-only mode, and for openning the file for writing purposes we use the command 'w', 'rb' to open it in binary mode read/write using byte data, we also can append to a file by using the string 'a' in the second argument.

### Exceptions:

An exception is an unusual condition in a program resulting in the interruption in the flow of the program.
Syntax errors occur when the parser detects an incorrect statement.

#### Raising exceptions: 

We can use raise to throw an exception if a condition occurs.

You can also start by making an assertion in Python. We assert that a certain condition is met. If this condition turns out to be True, the program can continue. If the condition turns out to be False, you can have the program throw an AssertionError exception.

#### The try and except Block: Handling Exceptions:

The try and except block in Python is used to catch and handle exceptions. Python executes code following the try statement as a “normal” part of the program. The code that follows the except statement is the program’s response to any exceptions in the preceding try clause.

The else statement, you can instruct a program to execute a certain block of code only in the absence of exceptions.

Everything in the finally clause will be executed.








