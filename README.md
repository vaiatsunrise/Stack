# Stack
# Aim: To study the concept of Stack in C++ and implement operations like push, pop, and display.
# Tools: GNU g++ compiler for local compilation or any online C++ compiler.

# Theory
A Stack is a linear data structure that follows the LIFO (Last In, First Out) principle.

The last element inserted is the first one to be removed.
It has two main operations:
Push – add an element to the top of the stack.
Pop – remove the top element from the stack.
Representation
Can be implemented using arrays or linked lists.
Requires a pointer/index (top) to keep track of the top element.
Program: Stack Implementation Using Array
# Logic:
A Stack class is created with an array to store elements and an integer top to track the top position.push() adds a new element at the top of the stack.
pop() removes the top element. display() traverses and prints all stack elements. Overflow and underflow conditions are handled using checks on top.

# Algorithm:
Start
Define a class Stack with array and top index.
Initialize top = -1 (empty stack).
Push Operation:
Check if top >= MAX-1 → Overflow
Else increment top and insert value
Pop Operation:
Check if top < 0 → Underflow
Else remove element and decrement top
Display Operation:
Traverse array from 0 to top and print elements
In main(), perform multiple push and pop operations.
End
# Conclusion
Stacks are simple and useful for tasks like expression evaluation, function call tracking, and undo operations. Using arrays, we can efficiently implement stack operations while handling overflow and underflow conditions.
