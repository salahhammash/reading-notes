### What is the basic syntax of Python list comprehension, and how does it differ from using a for loop to create a list? Provide an example of a list comprehension that squares the elements in a given list of integers
Python List Comprehension:
List comprehension is a concise way to create lists in Python. It allows you to generate a new list by iterating over an existing iterable and applying a certain expression or conditional statement

((( new_list = [expression for item in iterable if condition] )))
Here, expression is the operation or calculation that you want to perform on each element of the iterable. item refers to the current element being processed in the iterable. The optional if condition allows you to filter elements based on certain criteria.

Using a for loop to create a list requires more code than list comprehension, as it involves initializing an empty list, iterating over the iterable, and appending elements to the list:
numbers = [1, 2, 3, 4, 5]
squares = [num ** 2 for num in numbers]
print(squares)  # [1, 4, 9, 16, 25]

Here, we iterate over the numbers list and square each element using the expression num ** 2, and store the result in the squares list using list comprehension.


### What is a decorator in Python?

A decorator in Python is a special type of function that takes another function as an argument and adds some additional functionality to it without modifying the original function's code. Decorators allow you to modify the behavior of a function or class at runtime.

### Explain the concept of decorators in Python. How do they work, and what are some common use cases for them? Provide an example of a simple decorator function from the reading
Decorators work by wrapping the original function in another function and returning it. When you call the original function, the wrapper function is executed first, and any additional behavior that was added by the decorator is executed before or after the original function.

Common use cases for decorators include:

Adding logging or debugging statements to functions
Timing how long a function takes to execute
Restricting access to certain functions based on user roles or permissions
Caching the results of a function to improve performance

