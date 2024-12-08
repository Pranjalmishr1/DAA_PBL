# DAA_PBL
Fibonacci heaps are an effective data structure that may be used to create priority queues. They provide better reduced time complexity than conventional binary heaps for important operations like insertion, deletion, and minimal element finding. This article explores the topic of Java Fibonacci heaps, describing their implementation, structure, and uses.

A Fibonacci heap is formed up of several trees, each of which is a min-heap. The structure maintains references to the roots of all trees using a root list, and the trees are unordered. Fibonacci Heaps' key features are as follows:

Minimum Pointer: A pointer to the tree root with the smallest key.
Root List: A circular doubly linked list containing all tree roots.
Degree: The number of children a node has.
Marked Nodes: Nodes that have lost a child since the last time they were made the child of another node.
Visual representation of a Fibonacci heap:
![image](https://github.com/user-attachments/assets/bfdd77e5-d506-4b61-b833-9a7cd07c89f5)
