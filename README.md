# Oueue
A queue in C is basically a linear data structure to store and manipulate the data elements. It follows the order of First In First Out (FIFO).

In queues, the first element entered into the array is the first element to be removed from the array.

For example, let’s consider the scenario of a bus-ticket booking stall. Here, the fashion of a C programming queue is followed. The tickets are distributed on the first-come-first-serve basis i.e. the first one to enter is the first one to be served with the tickets.

A queue is open at both ends. One end is provided for the insertion of data and the other end for the deletion of data.

isEmpty(): To check if the queue is empty
isFull(): To check whether the queue is full or not
dequeue(): Removes the element from the frontal side of the queue
enqueue(): It inserts elements to the end of the queue
Front: Pointer element responsible for fetching the first element from the queue
Rear: Pointer element responsible for fetching the last element from the queue
