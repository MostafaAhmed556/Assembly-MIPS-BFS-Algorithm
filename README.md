# Assembly MIPS BFS Algorithm

This project implements breadth-first search (BFS) and Conversion of representations algorithms on a perfectly balanced binary tree using MIPS architecture and programmed in MARS assembly. The project also includes procedures to convert between two different array representations of the binary tree.

## Features

- **Breadth-First Search (BFS):** Implements BFS on a binary tree represented as an array.
- **Array Representations:** Supports two different array representations of the binary tree.
- **Conversion Procedures:** Converts between the two array representations.

## Project Description

### Binary Tree Representation

A binary tree is a data structure where each node can have a maximum of two children. The tree has a root node (the top element). This project uses two ways to save the elements of the binary tree in an array:

- **Representation 1:** The elements of the tree are saved in an array in depth-order.
- **Representation 2:** The elements of the tree are saved in an array in breadth-order.

### Procedures

1. **Convert from Representation 1 to Representation 2:** The output is an array with the new representation.
2. **Convert from Representation 2 to Representation 1:** The output is an array with the new representation.
4. **Breadth-First Search on Representation 1:** Takes a value as an input and performs BFS on the tree, returning the level at which the element was found or -1 if not found.
5. **Breadth-First Search on Representation 2:** Takes a value as an input and performs BFS on the tree, returning the level at which the element was found or -1 if not found.


## Setup Instructions

To set up and run the project, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/MostafaAhmed556/Assembly-MIPS-BFS-Algorithm.git
   ```
2. **Open the project in MARS IDE.**

3. **Run the MIPS assembly program:**
   - Load the program file into the MARS simulator.
   - Assemble and run the program to execute the BFS and Conversion algorithms.

## Usage Instructions

- **Breadth-First Search:** Use the provided procedures to perform BFS on the binary tree.
- **Conversion Procedures:** Convert between the two array representations using the provided procedures.

## Team Collaborators

- Mostafa Ahmed
- [Ziad Hamdy](https://github.com/ZiadHamdyMohamed)
- [Amr Khaled](https://github.com/AmrKhaled05)

## License

This project is licensed under the MIT License.
