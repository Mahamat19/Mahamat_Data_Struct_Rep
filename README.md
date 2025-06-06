# Python Data Structures

A Python package that provides implementations of common data structures such as:

- Singly Linked List
- Stack
- Queue
- Binary Tree
- Array

This package is designed to be an easy-to-use resource for anyone interested in learning or working with fundamental data structures in Python.

---

## Features

- **Singly Linked List**: A linked list where each node points to the next node.
- **Stack**: A LIFO (Last In First Out) data structure where elements are added and removed from the top.
- **Queue**: A FIFO (First In First Out) data structure where elements are added at the rear and removed from the front.
- **Binary Tree**: A tree structure where each node has at most two children, with left and right pointers.

---

## Installation

You can install the package using `pip`:

```bash
pip install python-basic-data-structures
```

---

## Usage

### Singly Linked List

To use the Singly Linked List:

```python
from my_data_structures.linked_list import LinkedList

# Create a LinkedList
ll = LinkedList()

# Insert elements
ll.insertAtBeginning(10)
ll.insertAtEnd(20)
ll.insertAfter(15, 1)

# Display the linked list
ll.display()

# Sort the list
ll.bubble_sort()
ll.display()
```

### Stack

To use the Stack:

```python
from my_data_structures.stack import Stack

# Create a Stack
stack = Stack()

# Push elements
stack.push(10)
stack.push(20)

# Pop elements
stack.pop()

# Display the stack
stack.display()
```

### Queue

To use the Queue:

```python
from my_data_structures.queue import MyQueue

# Create a Queue with a size limit
queue = MyQueue(3)

# Enqueue elements
queue.enqueue(10)
queue.enqueue(20)

# Dequeue elements
queue.dequeue()

# Display the queue
queue.display()
```

### Binary Tree

To use the Binary Tree:

```python
from my_data_structures.binary_tree import BinaryTree

# Create a Binary Tree
bt = BinaryTree()

# Insert elements
bt.insert(10)
bt.insert(20)
bt.insert(5)

# Search for a value
bt.search(15)

# Display the tree in different orders
print(bt.inorder())
print(bt.preorder())
print(bt.postorder())
```

---

## Contributing

Contributions are welcome! If you'd like to improve the project, feel free to fork the repository, make your changes, and submit a pull request. Here are a few ways you can contribute:

- Implementing new data structures.
- Adding tests for existing structures.
- Improving documentation.

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Contact

If you have any questions or suggestions, feel free to open an issue on GitHub or contact me directly:

- **Email**: amahamat@aimsammi.org
- **GitHub**: [@Mahamat19](https://github.com/Mahamat19)

---

You can customize the content according to your needs, but this should serve as a solid base for your project's README. It includes essential sections like an introduction, installation instructions, usage examples, contributing guidelines, and contact information.