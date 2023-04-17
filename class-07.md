## Explain the concept of variable scope in Python and describe the difference between local and global scope. Provide an example illustrating the usage of both
Variable Scope in Python:
In Python, the scope of a variable determines its visibility and accessibility within the code. The variable scope defines where the variable is created and where it can be accessed.
>>> Local Scope:
Variables declared inside a function or a block of code have a local scope. They can only be accessed within the function or block of code where they are defined.

>>> Global Scope:
Variables declared outside of any function or block of code have a global scope. They can be accessed anywhere within the code, including within functions.




### How do the global and nonlocal keywords work in Python, and in what situations might you use them?
Global and Nonlocal keywords in Python:
a- Global Keyword:
The global keyword is used to create a global variable inside a function. By default, if a variable is defined inside a function, it has a local scope, but the global keyword can be used to make a variable global.

    

b- Nonlocal Keyword:
The nonlocal keyword is used to refer to a variable defined in the nearest enclosing scope outside of the current function. It is useful when you want to modify a variable that is not in the global scope but is not a local variable either

### In your own words, describe the purpose and importance of Big O notation in the context of algorithm analysis
Big O notation is a mathematical notation that is used to describe the time complexity of an algorithm. It helps to understand the performance of an algorithm in terms of its input size. Big O notation is important in the context of algorithm analysis because it allows us to compare different algorithms and choose the best one for a particular problem

### To simulate a dice roll using Python, you can use the random module. The randint() function from the random module can be used to generate a random integer between 1 and 6, representing a dice roll.

This code simulates a dice roll by generating a random integer between 1 and 6 using the randint() function from the random module. To calculate the probability of rolling a 6 over a large (random.randint(1,6))