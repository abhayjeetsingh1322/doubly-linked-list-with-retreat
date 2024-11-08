# Doubly-Linked List with Retreat

## Description
The **Doubly-Linked List with Retreat** project implements a `List` data structure using a doubly-linked list of nodes. This implementation enhances the functionality of the standard `ListKernel` interface by adding support for the **`retreat`** and **`moveToFinish`** methods. These methods enable efficient backward navigation and direct movement to the end of the list, with all operations designed to run in constant time.

This project emphasizes:
- Kernel-level programming with custom doubly-linked lists.
- Optimizing navigation operations for constant-time performance.
- Designing and executing a systematic test plan to ensure correctness.

---

## Objectives
1. Implement the `ListKernel` interface using a doubly-linked list structure.
2. Extend functionality with the **`retreat`** and **`moveToFinish`** methods.
3. Optimize all operations, including backward navigation, to achieve constant-time execution.
4. Develop a comprehensive specification-based test plan.

---

## Features
### 1. Efficient List Representation
- Represents the list as a doubly-linked chain of nodes.
- Supports efficient navigation in both forward and backward directions.

### 2. Key Operations
- **`addRightFront`**: Inserts an element at the front of the right string.
- **`removeRightFront`**: Removes the front element of the right string.
- **`advance`**: Moves the "cursor" one step forward.
- **`retreat`**: Moves the "cursor" one step backward.
- **`moveToStart`**: Moves the "cursor" to the start of the list.
- **`moveToFinish`**: Moves the "cursor" to the end of the list.
- **`leftLength`**: Returns the number of elements in the left string.
- **`rightLength`**: Returns the number of elements in the right string.

---

## Technologies Used
- **Java**: For implementing the doubly-linked list and kernel methods.
- **JUnit**: For unit testing and validating the implementation.

---

## How to Run
### Prerequisites
- Java Development Kit (JDK)
- Any Java-compatible IDE or terminal

### Steps
1. Clone the repository:
   ```bash
   git clone [repository URL]
