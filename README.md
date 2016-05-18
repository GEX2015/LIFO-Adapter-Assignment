# LIFO-Adapter-Assignment
LIFO FIFO Adapter assignment

You willl create two adapter classes, using class templates,  that wrap std::list and create two specifict container types. Because you are using class templates your containers will be generic, they can hold anytype of object.

1. LIFO, last in first out, also known as a stack, 

class name Lifo
mehtods 
size()    returns the number of elements in the container
clear()   remove all elements from the container
empty() return true if the stack is empty
push()   add an element to the container
pop()    return the last element put in the continer, and remove it from the container
peek()   return teh last element in the container (dont remove it from the container
print() print the contents of the stack to stdout

1. FIFO, first in first out, also known as a queue, 

class name Fifo
mehtods 
size()    returns the number of elements in the container
clear()   remove all elements from the container
empty() return true if the stack is empty, false if not
push()   add an element to the queue
pop()    return the first element put in the queue, and remove it from the container
peek()   return teh first element in the queue (dont remove it from the container
print()  print the contents of the queue to stdout

Each adapter class is to be defined and implemented in a .h file, you must have a main program that demonstrates using each to hold int and string, it's enough to put a few items in the container, use pop() to show the correct item is returned and then use print() to display the rest of the container. 
