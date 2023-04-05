### What is the purpose of the ‘with’ statement when opening a file in Python, and how does it help manage resources while reading and writing files? 

In Python, the 'with' statement is used to open a file and perform operations on it while ensuring that the file is closed properly after the operations are complete. This is done by using the 'context manager' protocol, which provides a convenient way to manage resources like files, sockets, and database connections.

### Explain the difference between the ‘read()’ and ‘readline()’ methods for file objects in Python. Provide examples of when to use each method. 
read ():
This reads from the file based on the number of size bytes. If no argument is passed or None or -1 is passed, then the entire file is read.
The read() method reads the entire content of the file into a string or bytes object, depending on the mode in which the file was opened. This method reads the entire file from the current position of the file pointer to the end of the file, or to the number of bytes specified in the argument.

when to use it :
Use read() method when you want to read the entire content of the file, or a specific number of bytes from the current position of the file pointer

     
readline () :
This reads at most size number of characters from the line. This continues to the end of the line and then wraps back around. If no argument is passed or None or -1 is passed, then the entire line (or rest of the line) is read

The readline() method reads a single line from the file and returns it as a string. This method reads a line from the current position of the file pointer up to the end of the line (i.e., until it encounters a newline character)


when to use it :
Use readline() method when you want to read one line at a time from the file. This method is useful when you want to read a file line by line and perform some operation on each line.


### Briefly describe the concept of exception handling in Python. How can the ‘try’, ‘except’, and ‘finally’ blocks be used to handle exceptions and ensure proper execution of code? Provide a simple example.

The try, except, and finally blocks are used to handle exceptions and ensure proper execution of code.
By using exception handling, you can handle errors in a controlled manner and ensure that your program continues to execute, even when unexpected situations occur.
In Python, exception handling is a way to deal with errors and unexpected situations that may arise during the execution of a program. When an error occurs in Python, it raises an exception, which can be caught and handled by the program using exception handling.

example :

<!-- 
try:
    num1 = int(input("Enter a number: "))
    num2 = int(input("Enter another number: "))
    result = num1 / num2
    print("The result is:", result)
except ValueError:
    print("Please enter a valid number.")
except ZeroDivisionError:
    print("Cannot divide by zero.")
finally:
    print("Program execution completed.")
 -->

    in this example, the program asks the user to enter two numbers and divides them. If the user enters a non-numeric value or tries to divide by zero, the program catches the corresponding exception in the except block and prints an error message. Finally, the program prints a message indicating that program execution has completed.