# CDSA-assignment-
CDSA assignment stack and circular Queue 
A Stack is a linear data structure that follows LIFO (Last In, First Out). It can be implemented using an array and a TOP variable.

* PUSH: Adds an element to the top.
* POP: Removes the top element.
* PEEK: Shows the top element.
* DISPLAY: Shows all elements.
* Overflow: Occurs when we try to insert into a full stack.
* Underflow: Occurs when we try to delete from an empty stack.

Time Complexity: PUSH, POP, PEEK = O(1); DISPLAY = O(n)
Space Complexity: O(n)

⸻

Q2 circular queue

A Circular Queue is a queue that follows FIFO (First In, First Out). It uses an array where the last position connects back to the first position.

* ENQUEUE: Adds an element at the rear.
* DEQUEUE: Removes an element from the front.
* FRONT: Shows the front element.
* DISPLAY: Shows all elements.

A circular queue utilizes memory better because it reuses empty spaces at the beginning of the array.

Time Complexity: ENQUEUE, DEQUEUE, FRONT = O(1); DISPLAY = O(n)
Space Complexity: O(n)

In a linear queue, when REAR reaches the last index, insertion stops even if empty spaces exist at the beginning. This causes memory wastage/false overflow.
