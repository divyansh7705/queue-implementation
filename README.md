# queue-implementation
## Aim :-
To use excepttion handling.
## Software used:-
vs code 
## Theory:-
Definition - A queue is a linear data structure that follows the First In, First Out (FIFO) principle.<br> This means that the first element added to the queue will be the first one to be removed.<br> 
Queues are widely used in various applications, such as scheduling processes, managing requests in a service, and handling asynchronous data.

### Key Characteristics<br>
FIFO Structure: The first element added to the queue is the first to be removed.<br>
### Operations<br>
 -Enqueue: Add an element to the rear of the queue.<br>
 -Dequeue: Remove and return the front element of the queue.<br>
 -Peek/Front: Return the front element without removing it.<br>
 -isEmpty: Check if the queue is empty.<br>
 -isFull: Check if the queue is full (only applicable in fixed-size queues).<br>
### Implementation<br>
Queues can be implemented using two primary methods: arrays and linked lists. eg- <br>
```
struct Queue {
    int arr[MAX]; // Array to hold queue elements
    int front;    // Index of the front element
    int rear;     // Index of the rear element
};
```
## Algorithm :-


Here’s an algorithm section that can be added to the **README** file for the provided queue implementation:

---

## Algorithm

Here’s a structured algorithm for the provided C++ code that demonstrates the use of the `queue` class from the C++ Standard Library.

### Algorithm

### 1. **Initialization**

**Input**: None

**Steps**:
1. Include necessary headers:
   - `#include <iostream>` for input and output operations.
   - `#include <queue>` to use the queue data structure.
2. Use the `std` namespace to avoid prefixing standard functions and classes.

**Output**: A queue object `q` of type `int`.

### 2. **Adding Elements to the Queue (push)**

**Input**: Integers to be added to the queue.

**Steps**:
1. Call `q.push(30)` to add `30` to the queue.
2. Call `q.push(20)` to add `20` to the queue.
3. Call `q.push(10)` to add `10` to the queue.

**Output**: The queue now contains the elements `[30, 20, 10]`.

### 3. **Print Front Element Before Pop**

**Input**: None

**Steps**:
1. Retrieve the front element using `q.front()`.
2. Print the retrieved front element.

**Output**: Displays the message "Front element before pop: 30".

### 4. **Remove the Front Element from the Queue (pop)**

**Input**: None

**Steps**:
1. Call `q.pop()` to remove the front element of the queue.

**Output**: The queue now contains the elements `[20, 10]`, with `30` removed.

### 5. **Print Front Element After Pop**

**Input**: None

**Steps**:
1. Retrieve the new front element using `q.front()`.
2. Print the retrieved front element.

**Output**: Displays the message "Front element after pop: 20".

### 6. **End of Program**

**Input**: None

**Steps**:
1. Return `0` to indicate that the program has executed successfully.

---

## conclusion :-
We learnt to use queue implementation.
