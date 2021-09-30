# Graphs

<br>
<hr>

## what is Graph ⁉

> A **_graph_** is a _non-linear data structure_ that can be looked at as a _collection_ of **vertices** (or **nodes**) potentially _connected by line_ segments named \*\*edges\*\*.

<br>

- **Vertex**: also called a **“node”**, is a _data object_ that can have zero or more adjacent vertices.
- **Edge**: is a _connection between two nodes_.
- **Neighbor**: The neighbors of a node are its adjacent nodes, i.e., are connected via an edge.
- **Degree**: The degree of a vertex is the number of edges connected to that vertex.

<br>

> ![Directed vs Undirected](https://sites.google.com/a/cs.christuniversity.in/discrete-mathematics-lectures/_/rsrc/1409480658489/graphs/directed-and-undirected-graph/dir.png)

<br>

### An **Undirected Graph** is a graph where each edge is undirected or bi-directional. This means that the undirected graph does not move in any direction.

### A **Directed Graph** also called a Digraph is a graph where every edge is directed.

> ![Directed vs Undirected](https://i1.wp.com/courses.cs.washington.edu/courses/cse326/00wi/handouts/lecture21/img014.gif)

<br>

> ![Directed vs Undirected](http://pediaa.com/wp-content/uploads/2019/01/Difference-Between-Directed-and-Undirected-Graph-Comparison-Summary.jpg)

<br>

## Complete vs Connected vs Disconnected

### A **complete graph** is when all nodes are connected to all other nodes.

### A **connected graph** is graph that has all of _vertices_/_nodes_ have at least one edge.

### A **disconnected graph** is a graph where some vertices may not have edges.

## A **Cyclic graph** is a graph that has cycles.

<br>

## Graph Representation

- Adjacency Matrix
  > An Adjacency matrix is represented through a 2-dimensional array. If there are n vertices, then we are looking at an n x n Boolean matrix
- Adjacency List

  > An adjacency list is the most common way to represent graphs.<br>
  > An adjacency list is a collection of linked lists or array that lists all of the other vertices that are connected.

[📌 Graphs](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-35/resources/graphs.html) <br>
