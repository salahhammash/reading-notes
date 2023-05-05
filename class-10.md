# Stacks and queues in Python

> A stack is a Last-In-First-Out (LIFO) data structure, which means that the last element added to the stack is the first one to be removed. It's like a stack of plates where you can only add or remove plates from the top. A stack supports two main operations: push, which adds an element to the top of the stack, and pop, which removes the top element from the stack.

> A queue is a First-In-First-Out (FIFO) data structure, which means that the first element added to the queue is the first one to be removed. It's like a queue of people waiting in line where the first person to arrive is the first one to leave. A queue also supports two main operations: enqueue, which adds an element to the back of the queue, and dequeue, which removes the front element from the queue.

> - Stacks and queues are both abstract data types, which means that their implementation can vary depending on the programming language and the specific use case.

> - Stacks and queues are often used to manage data in a particular order. For example, a stack might be used to implement an undo feature in a text editor, where each action is added to the stack and can be undone by popping the most recent action off the stack. A queue might be used to manage a list of print jobs, where each job is added to the back of the queue and processed in the order that it was added.

> - In addition to push and pop, stacks may also support other operations like peek, which returns the top element without removing it, and isEmpty, which checks if the stack is empty. Similarly, in addition to enqueue and dequeue, queues may also support operations like peek, which returns the front element without removing it, and size, which returns the number of elements in the queue.

> - Stacks and queues can also be implemented using arrays or linked lists. When using an array, the size of the stack or queue is fixed, but adding or removing elements is faster because it only requires updating the index of the top or front element. When using a linked list, the size of the stack or queue is dynamic, but adding or removing elements can be slower because it may require creating or deleting nodes in the list.

> - There are variations of stacks and queues, such as double-ended queues (dequeues) that support adding or removing elements from both ends, and priority queues that assign a priority to each element and process them in order of priority.

> There are many other dunder methods available in Python, but these are some of the most commonly used ones. They allow Python objects to behave more like built-in types and enable powerful operator overloading, which can make code more concise and expressive.