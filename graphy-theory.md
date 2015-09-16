## Graph

A graph consists of V, the set of vertices, and E, the set of edges in which each edge is associated with either one or two vertices of V. Edges are said to connect two vertices or endpoints.

$$G = (V, E)$$

## Undirected Graphs

Simple graphs, multigraphs, and pseudo graphs are among the collection of graphs in which the order of the associated vertices in the pair representing an edge has no meaning. Thus, the edge associated with the vertices u and v can be represented by both ordered pairs (u, v) and (v, u).

#### Simple Graph

A graph in which each edge connects two, different vertices and no two edges connect the same pair of vertices.

#### Multigraphs

A graph in which a pair of vertices are connected by more than one edge. An edge of **multiplicity**, m, has m edges connecting the same pair of vertices.

#### Psuedo Graphs

A graph or multigraph that contains an edge connecting any vertex with itself. This type of edge is known as a **loop**

## Directed Graphs

A directed graph or diagraph is a graph in which each edge is associated with an ordered pair of vertices. The directed edge or arch begins at the initial vertex, u and ends at a terminal vertex, v.

#### Simple Directed Graph

A directed graph in which the graph that contains no loops and no multiple directed edges. Since at most one edge is associated with an ordered pair, both directed edges (u, v) and (v, u) can exist in a simple directed graph.

#### Directed Multigraphs

A directed graph that has multiple directed edges from one vertex to a second. The m edges associated with the same ordered pair (u, v) derive (u, v) is an edge of **multiplicity** m

## Mixed Graph

A graph that contains directed and undirected edges.

## Ways to Describe Undirected Graphs

#### Adjacency and Incidence  

Two vertices u and v in a Graph G are **adjacent** in G if u and v are endpoints of an edge e of G therefore e is **incident** with vertices u and v. 

#### Degree 

The degree is the number of edges incident to a given vertex. Each loop contributes twice to the degree. The degree is denoted:

$$deg(v)$$

#### Hand Shaking Theorem

$$2m = \sum\limits_{v\in V} deg(v)$$

The sum of the degrees of the vertices is twice the number of edges.


#### Even Number of Vertices of Odd Degree

$$2m = \sum\limits_{v\in V}deg(v) = \sum\limits_{v\in V_1}deg(v) + \sum\limits_{v\in V_2}deg(v)$$

The sum is even since it is 2m. Partition the set of vertices V into subsets $$V_1$$ and $$V_2$$ where the vertices are of even degree and the vertices are of odd degree respectively. Since the sum of even numbers is even and the sum is even the sum of odd numbers must be even as well. Therefore there must be an even number of odd degree vertices  in order for the sum of odd degree vertices to be even. 

## Ways to Describe Directed Graphs

#### In-Degree
The _in-degree_ of a vertex v is the number of edges with v as its terminal vertex.

$$deg^-(v)$$ 

#### Out-Degree

The _out-degree_ of a vertex is the number of edges with v as its initial vertex.

$$deg^+(v)$$

#### Sum of Degrees of Vertices

$$ 
\sum\limits_{v\in V}deg^-(v) = \sum\limits_{v\in V}deg^+(v) = \left| {E} \right| $$

For every endpoint that attributes to the _in-degree_ there is an initial vertex to the edge attributing to an _out-degree_. Therefore both sums are equal to the number of edges.

## Simple Graphs

#### Complete

#### Cycle

#### Wheel

#### _n_-cubes

#### Bipartite

A simple graph is bipartite if the set of vertices V can be partitioned into two disjoint sets $$V_1$$ and $$V_2$$ such that every edge in G connects two vertices in $$V_1$$ or two vertices in $$V_2$$. 

#### Bipartite Coloring

A simple graph is bipartite if and only if it is possible to assign one of two different colors to each vertex so that no two adjacent vertices are assigned the same color.

## New From Old

#### Union

The union of two simple graphs $$ G_1 = (V_1, V_2) \mbox{and} G_2 = (V_2, V_2) $$ returns a graph with vertex set $$ V_1 \cup V_2 $$ and edge set $$ E_1 \cup E_2 $$

$$ G_1 \cup G_2 $$

#### Subgraph

The subgraph of a graph $$G = (V, E)$$ is a graph $$H = (N, C)$$, where $$N \subseteq V$$ and $$C \subseteq E$$

$$G_1\subseteq G_2$$


#### Proper Subgraph

A subgraph is a proper subgraph if $$H\not = G$$

$$G_1\subset G_2$$

#### Removing Edges

The resulting subgraph from removing an edge from a graph G has the same vertex set and its edge set is E - e. 

$$G - e = (V, E - \{ e \})$$

##Graph Invariants
Two graphs may have the same form if there is a one-to-one correspondence between their vertex sets that preserves the relationships, also known as the edges, between the vertices. In chemistry when two different molecules have the same chemical formula but different tertiary shapes they are isomorphic.

A chemical formula corresponds to the number of vertices, degree of vertices, and number of edges and the digraph representation corresponds to the tertiary structure of the molecule. Thus, if a one to one and onto function exists then the graphs $$G_1$$ and $$G_2$$ are isomorphic. 

#### Isomorphism

The simple graphs $$G_1 = (V_1, E_1)$$ and $$G_2 = (V_2, E_2)$$ are isomorphic if there exists a one-to-one and onto function _f_ from $$V_1$$ and $$V_2$$ with the property that $$a$$ and $$b$$ are adjacent in $$G_1$$ if and only if $$f(a)$$ and $$f(b)$$ are adjacent in $$G_2$$, for all $$a$$ and $$b$$ in $$V_1$$.

#### Graph Invariants

A property of a graph that is preserved in graph isomorphism is a **graph invariant**. The number of vertices, number of edges, and number of vertices of each degree are all properties that are preserved in isomorphism. However determining whether a graph is not isomorphic is not as clear of a procedure. When a graph does not preserve graph invariants then it is **nonisomorphic**

#### Self Complementary

A simple graph G is called self-complementary if $$G$$ and $$\overline{G}$$ are isomorphic.
