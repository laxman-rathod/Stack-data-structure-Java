# Stack data structure in Java

In Java programming language, a stack is a linear data structure that follows the Last In, First Out (LIFO) principle. This means that the last element added to the stack is the first one to be removed. Stacks are used in a variety of applications, and Java provides a built-in class called java.util.Stack to implement stacks. However, it's more common to use the java.util.Deque interface or one of its implementing classes like java.util.ArrayDeque or java.util.LinkedList for stack operations in modern Java programming.

Here's some information about using stacks in Java, along with their pros and cons and their typical operations:

# Pros of Using Stacks:

Simple and Intuitive: Stacks are easy to understand and use, making them suitable for a wide range of applications.

Efficient Operations: Stack operations (push, pop, and peek) have a time complexity of O(1) when implemented with a dynamic array or a linked list.

Undo/Redo Functionality: Stacks are often used to implement undo/redo functionality in applications, like text editors and graphic design tools.

Function Call Management: Stacks are used in programming for function call management. The call stack keeps track of function calls and their local variables, making it essential for the execution of methods and handling recursive calls.

# Cons of Using Stacks:

Fixed Size: If you use an array-based implementation for a stack, it has a fixed size. If you exceed this size, you need to resize the array or use a different data structure.

Inefficient for Random Access: Stacks are not suitable for random access of elements. You can only access the top element of the stack efficiently.

# Operations on a Stack:

Push: This operation adds an element to the top of the stack. In Java, you can use the push() method to add an element to the top of the stack.

Pop: This operation removes and returns the top element of the stack. In Java, you can use the pop() method.

Peek (Top): This operation allows you to view the top element of the stack without removing it. In Java, you can use the peek() method.

isEmpty: You can check if the stack is empty using the isEmpty() method.

Size: You can determine the number of elements in the stack using the size() method.

Clear: To remove all elements from the stack, you can use the clear() method.

# Here's a output of this code:

![Screenshot 1](https://github.com/rathodlucky12/Stack-in-Java/assets/131651450/4ae73f21-c1bd-4f09-a8f8-d53091b2d30e)

![Screenshot 2](https://github.com/rathodlucky12/Stack-in-Java/assets/131651450/56dc2eb5-10cf-474d-9950-5ae045490524)

