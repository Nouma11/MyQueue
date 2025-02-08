# Queue Implementation Using Linked List in C++

This repository contains an implementation of a **Queue** using a **custom linked list** in C++. No built-in data structures like `std::queue` or `std::list` are used; instead, the queue operations are implemented manually with a linked list.

## Features
- **Print**: Prints all elements in the queue.
- **Push**: Adds an element to the back of the queue.
- **Front**: Retrieves the front element of the queue.
- **Back**: Retrieves the back element of the queue.
- **Size**: Returns the size of the queue.
- **IsEmpty**: Checks if the queue is empty.
- **Pop**: Removes an element from the front of the queue.
- **GetItem**: Retrieves an element at a specific index.
- **Reverse**: Reverses the queue order.
- **UpdateItem**: Updates the value of an element at a specific index.
- **InsertAfter**: Inserts an element after a specific index.
- **InsertAtFront**: Inserts an element at the front of the queue.
- **InsertAtBack**: Inserts an element at the back of the queue.
- **Clear**: Removes all elements from the queue.

## Getting Started
### Prerequisites
- A C++ compiler (GCC, MSVC, Clang, etc.)

### Compilation & Execution
To compile and run the program, use the following commands:
```sh
 g++ main.cpp -o queue
 ./queue
```

## Example Usage
```cpp
clsQueue<int> myQueue;
myQueue.Push(10);
myQueue.Push(20);
myQueue.Push(30);
myQueue.Print(); // Output: 10 20 30
myQueue.Pop();
myQueue.Print(); // Output: 20 30
```

## License
This project is licensed under the MIT License.

