# Linked List Operations in C

This documentation provides an overview and explanation of the C code that implements basic linked list operations. These operations include inserting a node at the beginning of the linked list, deleting a node with a specific data value, and displaying the linked list. The code also includes a simple menu-driven user interface to interact with the linked list.

## Table of Contents
1. [Introduction](#introduction)
2. [Code Overview](#code-overview)
3. [Functions](#functions)
    - [createNode](#createnode)
    - [insertAtBeginning](#insertatbeginning)
    - [deleteNode](#deletenode)
    - [display](#display)
4. [Main Function](#main-function)
5. [Usage](#usage)
6. [Contributing](#contributing)
7. [License](#license)

---

## Introduction

This C code demonstrates the implementation of a singly linked list and provides the following operations:

1. **Insert at the Beginning:** Inserts a new node with the provided data at the beginning of the linked list.
2. **Delete a Node:** Deletes a node with the specified data value from the linked list.
3. **Display the Linked List:** Displays the elements of the linked list in order.
4. **Exit:** Exits the program.

## Code Overview

The code defines a structure for a node in the linked list, where each node contains an integer `data` and a pointer to the next node. It also defines functions to create a new node, insert a node at the beginning, delete a node, and display the linked list. The main function provides a menu-driven interface for the user to interact with the linked list.

## Functions

### createNode

```c
struct Node* createNode(int data);
```

- This function creates a new node with the given integer data and returns a pointer to the newly created node.
- If memory allocation fails, it prints an error message and exits the program.

### insertAtBeginning

```c
struct Node* insertAtBeginning(struct Node* head, int data);
```

- Inserts a new node with the provided data at the beginning of the linked list.
- Returns a pointer to the new head of the linked list.

### deleteNode

```c
struct Node* deleteNode(struct Node* head, int data);
```

- Deletes a node with the specified data value from the linked list.
- Returns a pointer to the new head of the linked list after deletion.

### display

```c
void display(struct Node* head);
```

- Displays the elements of the linked list in order.
- If the linked list is empty, it prints a message indicating that the list is empty.

## Main Function

The `main` function provides a menu-driven interface to interact with the linked list. Users can choose from the following options:

1. Insert at the beginning
2. Delete a node
3. Display the linked list
4. Exit the program

The program continues to run until the user chooses to exit.

## Usage

Compile and run the program to perform linked list operations interactively. Follow the on-screen prompts to insert, delete, and display elements in the linked list.

Example:

```shell
Linked List Operations:
1. Insert at the beginning
2. Delete a node
3. Display the linked list
4. Exit
Enter your choice: 1
Enter data to insert: 42

Linked List: 42 -> NULL

Linked List Operations:
1. Insert at the beginning
2. Delete a node
3. Display the linked list
4. Exit
Enter your choice: 3
Linked List: 42 -> NULL

Linked List Operations:
1. Insert at the beginning
2. Delete a node
3. Display the linked list
4. Exit
Enter your choice: 2
Enter data to delete: 42

Linked List: NULL

Linked List Operations:
1. Insert at the beginning
2. Delete a node
3. Display the linked list
4. Exit
Enter your choice: 4
Exiting the program.
```

## Contributing

Contributions and improvements to this code are welcome. Feel free to submit issues or pull requests on the GitHub repository.

## License

This code is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
