---
id: 1973-8-foss-elementyi-teorii-grafov-6233be9d
issue: kvant_1973_8
year: 1973
number: "8"
title: Elements of graph theory
authors:
  - Фосс В.
rubric: raznoe
page_first: 57
page_last: 61
page_labels: 55-59
tag: OOGN
lang: en
source: kvant_digital
extraction: vision
content_sha256: 5f8faf5af3e1c6c450c825d8c09d79f548848655884c4049c7f0d7e293ef5294
prompt_sha256: draft-1
translated_from: content/ru/1973/08/articles/11_foss-elementyi-teorii-grafov-6233be9d.md
source_content_sha256: f899575134e8e5702765ac3ef7546db3fba20898b5bd32936fd927d1bdda5bf2
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 55⟧

Elements of graph theory

The foundations of the mathematical discipline called graph theory were laid in one of the works of Leonhard Euler, published in 1736, but graph theory has only become especially important in recent decades *).

What is a "graph"?

Before defining this concept, let's look at a few examples.

Example 1. Team 6 took part in the volleyball competition: $M_1$, $M_2$, $M_3$, $M_4$, $M_5$, $M_6$. Each of them met with each other, the results of the matches are shown in the table.

| $M_i$ | The team won | The team lost |
| :--- | :--- | :--- |
| $M_1$ | $M_2$, $M_3$, $M_4$ | $M_5$, $M_6$ |
| $M_2$ | $M_3$, $M_4$, $M_5$, $M_6$ | $M_1$ |
| $M_3$ | $M_4$, $M_5$, $M_6$ | $M_1$, $M_2$ |
| $M_4$ | — | $M_1$, $M_2$, $M_3$, $M_5$, $M_6$ |
| $M_5$ | $M_1$, $M_4$, $M_6$ | $M_2$, $M_3$ |
| $M_6$ | $M_1$, $M_4$ | $M_2$, $M_3$, $M_5$ |

On figure 1 each command $M_i$ is designated by the corresponding power

W. Voß. "Atz der Graphentheorie". "Alpha" No. 6, 1972 and No. 1, 1973. Translation and processing by A.Ya. Halamizer.

*) This issue publishes another article on graphs (see page 49).

⟦folio 56⟧

mochiki. In the same way, the structural formula of benzene (Fig. 4a) can be represented by a diagram consisting of lines and lobes (Fig. 46).

Example 4. Connecting regular polyerganics with vertices and edges can be easily depicted with a diagram consisting of lobes and lines (Fig. 5).

In these examples, diagrams made up of points and lines connecting them are graphs. Let us now give a definition of the concept “graph”.

Definition 1. We say that a graph is given if the data:

1) some finite set X whose elements are represented by points; these elements can denote people, objects, events, states, etc.;

2) some set U of ordered or unordered pairs (a, b), with a∈X, b∈X; each similar pair corresponds to a diagram of lines (connections) connecting points a and b (if the pair is ordered, then the direction of the connection is indicated by an arrow).

In this case, points a and b can have more than one connection. If for a given pair (a, b) there are r(r > 1) such connections, then they are distinguished using indices, for example, (a, b)₁, (a, b)₂, ..., (a, b)ₙ.

The sets X and U define the graph G = [X, U]. A graph is called directed if the elements of the set U are ordered pairs of points (see Fig. 1), and undirected otherwise (see Fig. 2, 3, 4).

The elements of the set X are called the vertices of the graph, the elements of the set U are called the edges or sides of the graph G.

Points a and b are called the ends of an edge (a, b) or edges (a, b)ᵢ.

It should be emphasized that figure of different types can represent the same graph if every two corresponding points are connected by the same number of edges (or equally directed

⟦folio 57⟧

Friend). On figure 6 different images of the same graph are given.

Next, it is necessary to define two more important concepts and make some general comments. After this, it will be possible to formulate and prove a simple but very important theorem (Theorem 1).

Definition 2. Two vertices are called connected if they are connected by an edge. A vertex is said to be incident to an edge if it serves as the end of that edge.

Definition 3. If a given vertex is incident to exactly r edges in G, then r is called the connection of the given vertex in G.

So, for example, on figure 2, vertex A has connectivity 4, vertex D has connectivity 2, and the remaining vertices have connectivity 1.

In what follows, by graph we will mean an undirected graph; When considering a directed graph, we will specifically highlight this each time.

We do not consider edges of the form (a, a) further, that is, we exclude *loops* from consideration (see Fig. 7a).

Otherwise, there are vertices in graphs that are not incident to any edge. Such vertices are called isolated.

We will consider only finite graphs containing a finite set of vertices and a finite set of edges.

Definition 4. A graph G is called simple if it does not contain doubling edges, that is, any two vertices in G are connected by at most one edge (there are doubling edges on figure 76).

Now try to solve several problems.

Task 1. On a plane, n circles are given, drawn by the numbers 1, 2, . . . , n. The graph G = [X, U] is defined as follows: X = {1, 2, . . . , n} and (i, j)∈U if and only if the i-th and j-th circles have at least one common point. Construct a graph G for the ninth circles shown in figure 8.

Task 2. A graph G is called complete if every two vertices are connected by one and only one edge (figure 9 shows complete n-graphs for n=3, 4 and 5). How many edges does a complete n-graph have?

Task 3. Do Figures 10a and 106 represent the same graph? Figure 10v and 10g?

Task 4. Determine the connectivity of the vertices of each of the graphs shown in figure 5.

Some theorems and their applications

Theorem 1. Let |X| = n — number of vertices, |U| — number of edges u

⟦folio 58⟧

$s_1, s_2, \dots, s_n$ — connections of the vertices of the graph $G = [X, U]$. Then
$$\sum_{i=1}^{n} s_i = 2 |U|,$$
Perhaps the sum of the connections of all vertices of the graph $G$ is twice the number of its edges.

Proof. Let's replace each edge with two halves (Fig. 11). Then each half of the edge will have one and only one incident vertex. If a vertex $a_i \in X$ has a connection $s_i$, then it is incidental to $s_i$ halves of edges; This means that the sum $\sum_{i=1}^{n} s_i$ is equal to the number of all halves or, what is the same, twice the number of edges.

Between the graphs shown on figure 2 and figure 36, one fundamental difference can be seen. In the graph at figure 36, each vertex is connected (by edges) to every other; in the graph on figure the two vertices $E$ and $F$ are not connected to the vertices $A$, $B$, $C$, $D$. To clarify this distinction

$$\text{Pic. 12.}$$

In order to do so, it is necessary to introduce definitions 5–9.

Definition 5. $(a_1, a_2) \times (a_2, a_3)(a_3, a_4) \dots (a_{n-1}, a_n)$ is called a sequence of edges. Here $a_i$ denotes vertices, and $(a_i, a_j)$ denotes edges. A sequence of edges is called closed if $a_n = a_1$, otherwise it is called open.

Definition 6. A sequence of edges in which each edge of the graph $G$ occurs at most once is called an integer *).

Moreover. The same vertices can appear in a chain more than once.

Definition 7. An open integer in which each vertex appears at most once is called empty.

Definition 8. A closed whole in which each vertex occurs at most once is called a col **).

So, for example, in the graph at figure 12
$$(a_1, a_2)(a_2, a_3)(a_3, a_8)(a_8, a_9) \times (a_9, a_3)(a_3, a_7)(a_7, a_4)(a_4, a_6) \times (a_6, a_5)(a_5, a_4)(a_4, a_7)(a_7, a_3) \times (a_3, a_9)(a_9, a_8)(a_8, a_3)(a_3, a_2)$$
— a sequence of edges that is not empty;
$$(a_1, a_2)(a_2, a_3)(a_3, a_8)(a_8, a_9) \times (a_9, a_3)(a_3, a_7)$$ — sequence of edges;
$$(a_3, a_7)(a_7, a_4)(a_4, a_3)$$ - kolcho;
$$(a_1, a_2)(a_2, a_3)(a_3, a_7)(a_7, a_4) \times (a_4, a_5)$$ is a path connecting vertex $a_1$ with vertex $a_5$.

Definition 9. A graph $G$ in which every two vertices $a_i$ and $a_j$ are connected by at least one path is called connected.

*) By definition 5, an integer can be open or closed.

**) A colcho that is better than one of the other cyclic permutations of edges (for example, (1, 2) (2, 3) (3, 1) and (2, 3) (3, 1) (1, 2)) will be considered identical. (Approx. Transl.)

⟦folio 59⟧

A disconnected graph consists of at least two connected components.

So, for example, the graphs in Figures 13 c, d, e, f are disconnected and consist of 2, 2, 4, 3 components, respectively.

Probably, the abundance of definitions and notes has already bored the reader. Unfortunately, they were absolutely necessary for further understanding.

Doesn't the following statement seem strange to you:

The number of people, which of whom has an odd number of friends is even?

Using the theorem to which we now proceed, it is not difficult to prove this statement.

Theorem 2. In every connection in a graph G, the number of vertices with an odd connection is even.

Proof. Let us denote the sum of connectivity of “odd” vertices (that is, the sum of odd x terms in formula (*)) by Σ₁, and the sum of connectivity of “even” vertices (that is, the sum of even terms in (*)) by Σ₂. Then by Theorem 1

$$\Sigma_1 + \Sigma_2 = \sum_{i=1}^{|X|} s_i = 2 |U|,$$

where

$$\Sigma_1 = 2 |U| - \Sigma_2. \quad (*)$$

Numbers 2 |U| and Σ₂, and therefore their difference, which is on the right side of equality (**), are even, and then the left side (the sum of odd terms is Σ₁) is an even number. Next, it is easy to prove (by contradiction) that the number of (odd!) terms in this sum is even. The theorem is proven.

We leave the reader to solve the following problems.

Task 5. Seven friends, going on vacation, agreed that each of them would send postcards to three of the others.

Is it possible that each of them will receive postcards from exactly those friends that he writes himself?

Task 6. Is there a graph with six vertices whose connectivity is 2, 3, 3, 4, 4, 4?

Problem 7. Is there a simple graph (containing more than one vertex) such that no two nodes have the same connectivity?

Problem 8. Let G be a (finite) simple graph, each vertex of which has a connection g. Prove that 2 |U| = g |X|.

In «Kvant» No. 3, 1973 on p. 4 there was a typo. The last sentence in the left column should look like this: This is nothing more than M times

$$M = \lg e = 0,43429$$

relative rate of change of y with change of t:

$$\frac{1}{y} \lim_{\Delta t \to 0} \frac{\Delta y}{\Delta t} = \frac{y'}{y} = \ln \frac{\lg a}{M}.$$
