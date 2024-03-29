# Class-35:

### Graphs:
A graph is a non-linear data structure that can be looked at as a collection of vertices (or nodes) potentially connected by line segments named edges.

#### Terminology:
- Vertex - Also called a node, is a data object that can have zero or more adjacent vertices.
- Edge - Is a connection between two nodes.
- Neighbor - The neighbors of a node are its adjacent nodes.
- Degree - Is the number of edges connected to that vertex.

#### Directed vs Undirected
- An Undirected Graph is a graph where each edge is undirected or bi-directional. This means that the undirected graph does not move in any direction.
- A Directed Graph also called a Digraph is a graph where every edge is directed. Unlike an undirected graph, a Digraph has direction. Each node is directed at another node with a specific requirement of what node should be referenced next.

#### Complete vs Connected vs Disconnected
- A complete graph is when all nodes are connected to all other nodes.
- A connected graph is graph that has all of vertices/nodes have at least one edge.
- A disconnected graph is a graph where some vertices may not have edges.

#### Acyclic vs Cyclic
- An acyclic graph is a directed graph without cycles, a cycle is when a node can be traversed through and potentially end up back at itself.
- A Cyclic graph is a graph that has cycles, a cycle is defined as a path of a positive length that starts and ends at the same vertex.
