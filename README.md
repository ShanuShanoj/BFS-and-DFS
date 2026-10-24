# Challenge 17 - File System Representation and Search Using BFS and DFS

## Aim
To develop a C program to represent a file system as a graph using an adjacency matrix and search for a specified file using BFS and DFS algorithms.

## Description
This program represents files and directories as nodes in a graph. The connections between nodes are represented using an adjacency matrix.

Breadth-First Search (BFS) and Depth-First Search (DFS) are implemented to search for a specified file from a given starting node.

The program displays the traversal order and whether the file is found using both algorithms.

## Algorithms Used
1. Breadth-First Search (BFS)
2. Depth-First Search (DFS)

## Technologies Used
- C Programming
- Graph
- Adjacency Matrix

## How to Run
1. Download the source code.
2. Compile the program using a C compiler.
3. Run the program.
4. Enter the number of files and directories.
5. Enter the file names.
6. Enter the adjacency matrix.
7. Enter the starting node.
8. Enter the file to search.

## Sample Input
```text
5
root
documents
photos
notes
music
0 1 1 0 0
1 0 0 1 0
1 0 0 0 1
0 1 0 0 0
0 0 1 0 0
0
notes
```

## Sample Output
```text
BFS Traversal: root documents photos notes music
File found using BFS!

DFS Traversal: root documents notes photos music
File found using DFS!
```

## Result
The file system was represented using an adjacency matrix, and BFS and DFS algorithms were implemented successfully to search for a specified file.

