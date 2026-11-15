# DSA

## Experiment 3: Singly Linked List Operations

* **AIM:** Build a text editor with dynamic line storage to allow insertion, deletion, and normal/reverse display using a singly linked list.


* **Apparatus:** 'C' programming tool (Dev C++).


* **Theory:** A singly linked list is a linear data structure that stores elements of the same data type in non-contiguous memory locations. It consists of nodes that contain a data field and a pointer indicating the address of the next node, with the final node containing a NULL pointer. Because of this structure, data can only be accessed sequentially.


* **Applications:**
* Stacks and queues


* Dynamic memory allocation


* Image viewers




* **Algorithm (Flowchart Style):**
* **Insert Flow:** Start -> Create a new node with data -> Is list empty? -> (If Yes): Set head to new node -> (If No): Traverse to desired position -> Link new node's pointer to next node -> Stop.


* **Delete Flow:** Start -> Is list empty? -> (If Yes): Return -> (If No): Traverse to target node -> Bypass the target node's pointer -> Free the deleted node's memory -> Stop.




* **Output:** The program presents a menu with 10 operations for the linked list. In the sample run provided, the user selects choice 1 to insert "Hello World", choice 2 to insert "This is a test", and choice 7 to display the normal order text, which outputs "Hello World".


* **Result:** The C program successfully executed basic linked list operations, including Insert Front, Insert End, and Display.


* **Conclusion:** Thus, we learned to implement a singly linked list in C and perform insertion, deletion, display, reverse display, and list reversal operations.



## Experiment 4: Binary Search Tree Operations

* **AIM:** Implement Binary Search Tree (BST) operations for an online directory system to keep names sorted, support fast searching, and execute recursive traversals (inorder, preorder, postorder).


* **Theory:** A tree is a non-linear data structure used to represent data in a hierarchical form. In a Binary Search Tree, the value of the left node must be smaller than the parent node, and the value of the right node must be greater than the parent node. This structure quickly allows for maintaining a sorted list and performing efficient lookups.


* **Applications:**
* Multi-level indexing


* Searching algorithms


* TreeMap structures




* **Algorithm (Flowchart Style for Insert/Search):**
* **Flow:** Start -> Is current node NULL? -> (If Yes): Create new node here OR Return 'not found' -> (If No): Compare target value with current node -> Is target < node? -> (If Yes): Move to Left Subtree -> Is target > node? -> (If Yes): Move to Right Subtree -> Repeat loop until placed or found -> Stop.




* **Output:** Specific console output is not provided in the document, but the program is designed to output names from the directory system using inorder, preorder, and postorder traversals.


* **Result:** The Binary Search Tree operations were created and executed, allowing for name insertion and tree traversal.


* **Conclusion:** Thus, the Binary Search Tree was successfully implemented, and the program performs insertion, searching, and recursive inorder, preorder, and postorder traversals.



## Experiment 5: Graph Traversal

* **AIM:** Implement Graph Traversal to design a navigation system for a campus by creating a graph using an adjacency matrix and exploring connectivity with Breadth-First Search (BFS) and Depth-First Search (DFS).


* **Apparatus:** C programming language environment.


* **Theory:** A Graph is a non-linear data structure consisting of vertices (nodes) and edges (connections). Breadth-First Search (BFS) explores the graph level by level using a queue, which is ideal for finding the shortest path in unweighted graphs. Depth-First Search (DFS) explores as deep as possible using recursion or a stack before backtracking.


* **Applications:**
* Finding shortest paths


* Minimum spanning trees


* Organizing data




* **Algorithm (Flowchart Style):**
* **BFS (Level-by-Level):** Start -> Enqueue start node & mark as visited -> Is queue empty? -> (If No): Dequeue node and process it -> Find all unvisited neighbors -> Mark visited & Enqueue them -> Loop back until queue is empty -> Stop.


* **DFS (Deep Search):** Start -> Mark current node as visited & process -> Find adjacent neighbors -> Is neighbor unvisited? -> (If Yes): Recursively call DFS for that neighbor -> Backtrack when no unvisited neighbors remain -> Stop.




* **Output:** Specific console output is not provided in the document, but the program explores and outputs the reachable buildings (nodes) using the BFS and DFS algorithms.


* **Result:** The campus map was successfully represented as a graph using a 2D adjacency matrix, and paths were explored using traversal algorithms.


* **Conclusion:** Thus, graph traversal was successfully implemented using an adjacency matrix in C. Breadth-First Search explores vertices level by level, while Depth-First Search explores as deeply as possible before backtracking.
