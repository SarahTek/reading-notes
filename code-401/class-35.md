# Graphs
 What is Graph?

- A graph is a non-linear data structure that can be looked at as a collection of vertices (or nodes) potentially connected by line segments named edges.

- Vertex - A vertex, also called a “node”, is a data object that can have zero or more adjacent vertices.
- Edge - An edge is a connection between two nodes.
- Neighbor - The neighbors of a node are its adjacent nodes, i.e., are connected via an edge.
- Degree - The degree of a vertex is the number of edges connected to that vertex.

## Directed vs Undirected

- An Undirected Graph is a graph where each edge is undirected or bi-directional. This means that the undirected graph does not move in any direction.
- A Directed Graph also called a Digraph is a graph where every edge is directed.
Unlike an undirected graph, a Digraph has direction. Each node is directed at another node with a specific requirement of what node should be referenced next.

## Acyclic vs Cyclic

- An `acyclic graph` is a directed graph without cycles.
- A `Cyclic graph` is a graph that has cycles.

a sparse graph is when there are very few connections. a dense graph is when there are many connections

## Adjacency List

- An adjacency list is a collection of linked lists or array that lists all of the other vertices that are connected.

## Weighted Graphs

- A weighted graph is a graph with numbers assigned to its edges. These numbers are called weights.Within adjacency lists, you must include both the weight and the name of the adjacent vertex.

## Traversals

- `Breadth first traversal` is when you visit all the nodes that are closest to the root as possible.breadth first traversal uses a `Queue` to visit all children at a given level,
- The `Depth first traversal` uses a `Stack` to visit all children of a given subtree. where we visit nodes via recursive calls. Recursive calls use a call stack internally.

### Resources

[Graphs](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-35/resources/graphs.html)
