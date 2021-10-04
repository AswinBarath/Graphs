# Graphs 

Problems on Graph Data Structure and popular algorithms associated with Graphs

## Tasks

- [ ] Theoretical concepts
	- [x] [What is a graph?](#what-is-a-graph)
	- [x] [Types of graph](#types-of-graph)
	- [x] [Degree in a graph](#degrees-in-a-graph)
	- [x] [Path in a graph](#path-in-a-graph)
- [ ] Problems
- [ ] Patterns

---

## What is a Graph?

- Graph is a data structure
- Graph has two components, namely:
	- Node/vertex
	- Edge
<p>
	<img src="https://media.geeksforgeeks.org/wp-content/cdn-uploads/undirectedgraph.png" width="600px" />
</p>

---

## Types of graph

- There are two types of graphs:
	- **Undirected graphs**
	- **Directed graphs**
- Consider 2 nodes `v1` and `v2`:
	- There are two edges `v1v2` and `v2v1` in an undirected graph
	- There is only one edge `v1v2` in a directed graph
<p>
	<img src="https://ehindistudy.com/wp-content/uploads/2015/11/wpid-differencebetween_directed_undirected_graphs1.jpg" width="600px" />
</p>


## Undirected cyclic graph

- A cycle is a path through which we can come back to the starting position
- If there's a cycle in an Undirected graph we can call it as an Undirected cyclic graph

<p>
	<img src="https://miro.medium.com/max/1400/1*lsf_f_JGXKA_JEPzFNMwCQ.png" width="800px" />
</p>


### Undirected acyclic graph

- When there's not a cycle we can call it as an Undirected acyclic graph


### Directed cyclic graph

- A cycle is a path through which we can come back to the starting position
- If there's a cycle in an Undirected graph we can call it as an Undirected cyclic graph


### Directed acyclic graph (DAG)

- When there's not a cycle we can call it as an Undirected acyclic graph


### Undirected Weighted graphs

- Thw edges in this graph have weights

### Directed Weighted graphs

- Thw edges in this graph have weights


---

## Degrees in a graph

- Degrees in a graph
	- **Degree of a vertex** is the number of incoming and outgoing edges to the vertex in a graph
	- The **Degree(v2)** = 2 in the above undirected graph
	- The **InDegree(v2)** = 1 in the above directed graph
	- The **OutDegree(v2)** = 1 in the above directed graph
<p>
	<img src="https://ehindistudy.com/wp-content/uploads/2015/11/wpid-differencebetween_directed_undirected_graphs1.jpg" width="600px" />
</p>

- **Property of Degree in an undirected graph**
	- Total degree of nodes = 2 * Edges
	- The total number of degree of all the **nodes** is equal to **twice of the number of all the edges** in an undirected graph

---

## Path in a graph

- **Path** in an undirected graph
	- The sequence of nodes/vertex such that none of the nodes are visited twice
	- Examples:
		- `v2 v3 v1`
		- `v2 v1`
		- `v3 v2`
<p>
	<img src="https://ehindistudy.com/wp-content/uploads/2015/11/wpid-differencebetween_directed_undirected_graphs1.jpg" width="600px" />
</p>

- **Path** in a directed graph
	- The sequence of directed nodes/vertex such that none of the nodes are visited twice
	- Examples:
		- `v1 v2 v3`
		- `v1 v3`
		- `v2 v3`

---
