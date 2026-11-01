---
id: 1981-6-boltyanskiy-topologiya-grafov-d1e0b07f
issue: kvant_1981_6
year: 1981
number: "6"
title: Graph topology
authors:
  - Болтянский В. Г.
rubric: osnovnye-stati
page_first: 7
page_last: 11
page_labels: 5-9
tag: N96C
lang: en
source: kvant_digital
extraction: vision
content_sha256: a055686d426aedd4385be7ee796d5014ccc63f49e318c324a6589b9d3d1dee3d
prompt_sha256: draft-1
translated_from: content/ru/1981/06/articles/05_boltyanskiy-topologiya-grafov-d1e0b07f.md
source_content_sha256: 4f963c8f66a3eea66062c13211f6ef7d19550adcc36bbfb857fb925965a86d1e
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 5⟧

V. Boltyansky

Graph topology

The famous French mathematician Andre Weil once said that “the devil of abstract algebra and the angel of topology” are fighting for the soul of every mathematician. In this article on graphs, we will listen primarily to the voice of the angel of topology, although the easy-to-help devil will also have his say.

A graph (finite) is a set of points (vertices of the graph) connected - on the plane or in space - by a finite number of arcs (edges of the graph), and the arcs intersect only at the vertices *) (Fig. 1).

In most of the article it will be important for us that a graph is a certain figure (the set of all points of arcs); the selected points of this figure are

*) In general graph theory, a slightly different - “abstract” - definition of a graph is accepted (cf. «Kvant», 1981, No. 3, p. 18).

vertices - we will often ignore them.

Which graphs are the same?

The angel of topology considers geometric graphs identical - such graphs $G_1$ and $G_2$ for which there is a continuous (without discontinuities) and inverse (without sclive) mapping $h$: $G_1 \rightarrow G_2$ set $G_1$ onto the entire set $G_2$ (such a mapping is called geometric*)).

*) When determining the geometricity of an arbitrary figure, the continuity of the inverse mapping $h^{-1}$ is also required (for finite graphs it is carried out automatically, which the angel of topology told us to leave without proof).

⟦folio 6⟧

From this definition it follows that two geometric graphs, in particular, if, by bending and stretching the edges as desired, but without allowing breaks and slivian ones, one of them can be superimposed on the other. figure 2, $a$ shows how a circle can be turned into a figure eight; however, this does not mean that the circle and the eight are geometric (after all, during this transformation, two points were squashed together). A circle can also be turned into a half-circle, but to do this it needs to be torn apart and only then straightened. Since discontinuities are not allowed, such a transformation will not be geometrism; besides, semiperval is not a graph. And here is the outline of a triangle and the outline of a square geometrine, and both of them are geometries of a circle, as shown in figure 2, $6$.

Note that it is not always possible, as in this example, to realize the geometric mapping $h$: $G_1 \rightarrow G_2$ by bending, stretching and rolling graphs in the space itself. Thus, a pair of interlocked circles (Fig.3) of geometrine are not interlocked, although in space it is impossible to disengage them without breaking them.

As the example with a triangle and a square shows, in geometrima the vertex does not have to turn into a vertex. We will return to this later.

Example 1. Let's imagine the letters of the Russian alphabet in the form of lines. The letters G, L, M, P, S are geometric to each other. The letters E, U, T, Ch, Sh, C, E are also geometric to each other, but not geometric to the previously mentioned letters. The letter O is not geometric

no other letter of the Russian alphabet *).

It is respectful to compare the concept of geometrization and the concept of constructability of figures. In geometry, displacements are considered, that is, mappings that preserve distances between points. Two figures that are converted into one another (“combined”) by means of displacement are called congestive and are considered identical (from a geometric point of view). Topologists consider mappings that are more general than displacements, namely geometric mappings, which may not preserve distances, but only preserve the continuity of the arrangement of points in figures (do not allow breaks and slivers). Therefore, two geometric figures are considered (from a topological point of view) as identical.

The simplest invariants

The properties of figures that are preserved during the transition from a figure to a geometric figure are called topological properties of figures, or topological invariants (from the Latin word invariant - unchanging). Topology is the study of the topological properties of figures.

Most often, topological invariants that are numbers (or other algebraic objects) are used, since

⟦folio 7⟧

It is convenient to handle such invariants. They are used mainly to solve a seemingly hopeless problem: to prove that two figures $A$ and $B$ are not geomethorphic.

Indeed, in proving that something can be forgiven (in our case, geomethorphism $h: A \rightarrow B$), it is enough to come up with one version of this construction. How can you prove that something cannot be built? To do this, you need to go through all possible construction options (for us - mappings $h: A \rightarrow B$) and check that not a single option is suitable (is not geometorphism). But there are infinitely many general mappings $h: A \rightarrow B$, it is impossible to check all of them. How would it be?

This is where numerical invariants help. Let each figure $A$ of the class under consideration be assigned a number $q(A)$, and the same number is assigned to geometorphic figures. Let the figures $A$ and $B$ be such that $q(A) \neq q(B)$. then they cannot be geomethorphic, it is impossible to construct geomethorphism $h: A \rightarrow B$!

The amazing simplicity of this reasoning hides its depth and importance. The printing appears to have deceived us by hiding the difficulty of the task in an unknown place. This is not surprising: invariants have appeared - numbers behind which the devil of abstract algebra, a great cunning and hoaxer, hides.

Example 2. The letter $B$ is a figure consisting of two unrelated parts. Most of the remaining letters of the Russian alphabet consist of one coherent piece (the exceptions are the letters $I$, $E$). The number of connections of “pieces” of which a figure consists (also called the number of components of a figure) is a topological invariant. Therefore, the letter $B$ is not geometomorphic to, for example, the letter $O$, the letter $П$, the letter $Ц$, etc.

Example 3. On the figure eight (Fig. 4, $a$) there is such a point $x$ that after removing it (Fig. 4, $b$) we get an incoherent figure (containing more than one component). A point with this property is called a splitting point of the figure. No point of the figure eight other than $x$ is a splitting point (Fig. 4, $b$).

If the point $x$ of the figure $A$ is a partitioning point, it remains so for any geomethorism of the figure $A$, similarly for a non-partitioning point. Therefore, the number of dividing points of a given figure is its topological invariant, and the number of non-dividing points is also a topological invariant.

Tasks

1. For each letter of the Russian alphabet, indicate how many breaking and non-breaking dots it contains. Prove that the letters $O$, $Г$, $T$, $B$ are not geomethorphic in pairs.

2. Prove that for any natural number $n$ there exists a figure containing an equal number of $n$ dividing points, as well as a figure containing an equal number of $n$ non-dividing points.

Example 4. Let $A$ be a graph and $x$ its vertex. The number of edges of the graph $A$ converging into $x$ is called the index of the vertex $x$ in the graph $A$ (in this case, a netla - an edge with a beginning and an end in the same vertex $x$ - is counted as two edges, or it is included in $x$ with both of its ends). On figure 5 vertices $a, b, c, d$ have indices 1, 2, 3, 4 respectively. The number of vertices with index $n \neq 2$ contained in a graph is a topological invariant. Why do we have to exclude vertices at index 2?

Tasks

3. Prove that the letters $IO$ and $Ф$ are not geomethorphic. Not indicated. Take advantage of the fact that the number of vertices at index $k (k \neq 2)$ is an invariant.

4. Form the necessary and sufficiently conditional condition, under which a figure composed of a finite number of arcs is geometorphic to a circle.

5. Let $G$ be a graph. By $a_k(G)$ we denote the number of vertices of this graph having indices $k$. Prove that the number of edges of the graph is $G$

⟦folio 8⟧

right

$$\frac{1}{2} (a_1(G) + 2a_2(G) + 3a_3(G) + \dots).$$

6. Prove that in every graph the number of vertices with an odd index is even.

Königsberg places

A graph is called unicursal (or Eulerian) if it can be “drawn with one stroke,” that is, it can be walked all over in a continuous motion without passing the same edge twice. The property of a graph being unicursal is obviously a topological invariant. However, this topological invariant is not new, but is expressed through the concept of a vertex index (see Problem 9).

Tasks

7. Prove that if each vertex of a graph has an index that does not change two, then from the edges of this graph it is possible to construct a line homeomorphic to a circle.

8. Prove that if all the vertices of a connected graph have an even index, then this graph can be “drawn with one stroke”, starting from an arbitrary vertex and returning to the same vertex.

9. Prove that a connected graph is unicursal if and only if it contains at most two vertices of odd index.

The problem of Königsberg places, considered by Euler, is related to unicursal graphs. At that time in Königsberg there were seven places across the Pregel River (Fig. 6, a). The task is to find out whether it is possible, while walking around the city, to pass through each place exactly once. Let us compare a certain graph with the city plan: the vertex L denotes the left bank, Π the right bank, A and B the islands, and the edges of the graph correspond to the places (Fig. 6, b). In this graph, all four vertices have an odd index. Therefore, the graph is not unicursal, and therefore the required route does not exist.

Tasks

10. Prove that by adding one more place (where the corner is on the plan of Figure 6, a), we will get a city map according to which we can go through each place once.

11. A complete graph is a graph without loops in which any two vertices are connected by exactly one edge. In what case is a complete graph unicursal?

How to build a connected graph

Any graph can be “constructed” by adding one edge after another (of course, the vertices of the graph will also need to be marked). The numbering of the edges of the graph on figure 7 is chosen so that when drawing the graph in accordance with this numbering, connected graphs are always obtained. If, however, we numbered the edges in the reverse order, then when drawing, we would initially end up with an incoherent graph. It turns out that in every connected graph there is such a numbering of edges that when drawing the graph in accordance with this numbering, connected graphs are always obtained. This statement can be called the “connected graph drawing theorem.”

Tasks

12. Prove that any connected graph can be “drawn with one stroke” if you allow each graph to be traversed edgewise up to a time.

13. Derive from the statement of the previous problem a theorem about drawing connected graphs.

⟦folio 9⟧

14. Prove that any two vertices of a connected graph $G$ can be connected into $G$ by a simple chain of edges—a chain such that the union of the edges of this chain is a line homeomorphic to a segment.

How many trees are there in the forest?
A contour in a graph is a closed chain of edges, the union of which is a line homeomorphic to the segment (Fig. 8). A connected graph that does not contain a single contour is called a tree (Fig. 9). Let us prove that in any tree the number of vertices and the number of edges $P$ are related by the relation

$$B - P = 1.$$ (1)

To prove this, let us use induction on the number of edges $P$. For $P = 1$ (the tree consists of only one edge and has two vertices), relation (1) is valid. Suppose that for any tree with $n$ edges, relation (1) has already been proven, and let $G$ be a tree with $n + 1$ edges. Since the graph $G$ is connected, it can be obtained from some connected graph $G'$ by adding one edge $r$. The graph $G'$ contains $n$ edges and is also a tree (why?). By the induction hypothesis, relation (1) is valid for the graph $G'$, and therefore it has $n + 1$ vertices. Let us now note that only one of the added edges $r$ is a vertex of the graph $G'$ (otherwise, by virtue of Problem 14, when adding the edge $r$ a contour would appear in the graph $G$ - see Fig. 10). Therefore, when adding edge $r$, one new edge and one new vertex appear in graph $G$. In other words, the graph $G$ has $n + 2$ vertices and $n + 1$ edges, and therefore relation (1) is valid for it. The induction performed proves equality (1) for any tree.

The difference $B - P$ is called the Euler characteristic of the graph $G$ and is denoted by $\chi(G)$. Thus, equality (1) means that the Euler characteristic of any tree is equal to 1.

Exercise

15. A graph that does not contain contours is called a forest. It is clear that if the graph $G$ is a forest, then each of its components is a tree. Prove that if $G$ is a forest, then the number of trees that “grow” in the forest (that is, the number of components of the graph $G$) is $\chi(G)$.

16. Prove that if the graph $G$ is a tree, then every two of its vertices can be connected by only one simple chain. Is the opposite true?

Maximum tree and current systems

Now let $G$ be a connected graph that is not a tree. Then $G$ has a contour; let $r_1$ be any edge included in this contour (Fig. 11, a). By removing the edge $r_1$ from $G$, we obtain a connected graph $G'$ (since the ends of the discarded
