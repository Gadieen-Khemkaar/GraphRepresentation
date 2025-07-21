Graph Representation
---
This C++ program reads a graph with n nodes and m edges, and stores it as an adjacency list (used for efficient graph representation).

It uses a vector of vectors to store connections for each node.

For every edge input (u, v), it adds v to u’s list and u to v’s list — assuming it's an undirected graph.

🧠 One-liner:
This code creates an adjacency list representation of an undirected graph using vectors in C++.


---
The indices of the adjacency array correspond to the node of the graph.
ex: Index 1 of the array corresponds to Node 1 of the graph.
and the vector of integers at that particular index(say 1) contains the Node no.s of the nodes that are connected with that particular node represented by the index where the vector is present (Node 1).
---
The loop runs 'm' times because every loop iteration adds 1 edge into the adjacency list.
