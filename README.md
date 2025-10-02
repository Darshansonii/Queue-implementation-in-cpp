# Queue-implementation-in-cpp

AIM
--------------------------------------------------
The aim of this project is to implement and demonstrate the working of a Queue data structure in C++ by performing the fundamental operations:
1. Enqueue (Insertion)
2. Dequeue (Deletion)
3. Peek (Accessing the front element)
4. Display (Traversing all elements)

The project helps in understanding how data is managed in a FIFO (First In – First Out) manner and its importance in solving real-world problems like scheduling, buffering, and resource management.


--------------------------------------------------
THEORY
--------------------------------------------------
A Queue is a linear data structure that follows the FIFO (First In, First Out) principle. 
The element inserted first is removed first.

It has two pointers:
- Front → Points to the element to be removed next.
- Rear  → Points to the position where the new element will be inserted.

CHARACTERISTICS:
1. Insertion is done at the rear end.
2. Deletion is done from the front end.
3. Can be implemented using arrays, linked lists, or STL in C++.

TYPES OF QUEUE:
1. Simple Queue – Basic FIFO queue.
2. Circular Queue – Connects rear to front to avoid wasted space.
3. Priority Queue – Elements removed based on priority.
4. Double-Ended Queue (Deque) – Insertion and deletion allowed at both ends.

APPLICATIONS:
- CPU and process scheduling in operating systems.
- Managing print jobs in printers.
- Packet switching in networking.
- Customer service systems and ticket counters.
- Traffic and resource management.

ADVANTAGES:
- Simple and efficient for sequential processing.
- Useful in real-world problems requiring orderly execution.
- Forms the basis of advanced structures like priority queues and deques.

LIMITATIONS:
- Fixed size in array implementation may cause overflow or unused memory.
- Searching elements is inefficient since traversal is needed.
- Linked list implementation uses extra memory for pointers.


--------------------------------------------------
ALGORITHM
--------------------------------------------------
ENQUEUE (Insert)
1. Check if the queue is full. If yes, display "Overflow".
2. Increment rear = rear + 1.
3. Insert the element at queue[rear].

DEQUEUE (Delete)
1. Check if the queue is empty. If yes, display "Underflow".
2. Retrieve the element at queue[front].
3. Increment front = front + 1.

PEEK (Front Element)
1. If the queue is empty, display "Queue Empty".
2. Otherwise, return queue[front].

DISPLAY
1. Check if the queue is empty.
2. If not empty, traverse from front to rear and print all elements.


--------------------------------------------------
CONCLUSIONS
--------------------------------------------------
- The queue follows the FIFO principle, ensuring orderly execution.
- Implementation of enqueue and dequeue operations helps in understanding sequential data management.
- Queues are widely applicable in CPU scheduling, job handling, printers, and communication systems.
- They are simple to implement yet form the basis for priority queues, circular queues, and deques.
- Learning queue implementation in C++ strengthens knowledge of arrays, pointers, and dynamic memory handling.
