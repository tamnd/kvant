---
id: 1975-11-kats-o-ploskih-pravilnyih-grafah-f2bddbb1
issue: kvant_1975_11
year: 1975
number: "11"
title: On planar regular graphs
authors:
  - Кац М. Г.
rubric: osnovnye-stati
page_first: 14
page_last: 17
page_labels: 12-15
tag: 85P8
lang: en
source: kvant_digital
extraction: vision
content_sha256: c4f52bcc518b56493d6a2cada98cbc5f215d978368e38dc7f3b849a3a7a4cd7f
prompt_sha256: draft-1
translated_from: content/ru/1975/11/articles/04_kats-o-ploskih-pravilnyih-grafah-f2bddbb1.md
source_content_sha256: 0f9ab18cac0fc99898f253c6aa43c3fee67e717aa3b18507cb9d613846ade63f
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 12⟧

On planar regular graphs

M. G. Katz

Let's start with definitions.
A graph is a finite set of points and curves connecting them on a plane (we will call these points vertices, and the curves edges).
We will consider graphs with the following properties:
1) the edges of the graph do not intersect (graphs with this property are called flat);
2) no two vertices are connected by more than one edge;
3) any two vertices of the graph are connected by a link of edges (such a graph is called connected);
4) each edge connects two different vertices.

If you cut the plane along the edges of the graph, then it will split into several parts - the faces of the graph. The unlimited part will be called the outer edge. The remaining faces are internal.

A face is called $n$-edge if the number of edges encountered when traversing the face along its boundaries is equal to $n$. Example. On figure 1,a there is only one face - an external six-fin, on figure 1,6 - two faces: an internal three-fin and an external three-fin.

An edge is called external (respectively internal) if, when traversing the internal faces of the graph, it occurs once or twice, respectively. Example. On figure 2, edge $a$ is external, edge $b$ is internal; on figure 1,a there are neither external nor internal edges.

Let us denote by $B$, $P$ and $\Gamma$, respectively, the number of vertices, edges and all faces of the graph, including the external one. These three quantities are related by the famous Euler formula $^*$

$$B - P + \Gamma = 2.$$

Let us denote by $a_i$ the number of $i$-edge faces, including the external one. Then the following relation is valid:

$$2P = 3a_3 + 4a_4 + 5a_5 + \dots$$

Prove it yourself.

Since $\Gamma = a_3 + a_4 + \dots$, then correspondence (1) can be written in the form

$$2P = 3\Gamma + a_4 + 2a_5 + \dots,$$

or

$$\Gamma = \frac{2}{3}P - \frac{1}{3}(a_4 + 2a_5 + \dots).$$

Substituting this value $\Gamma$ into Euler’s formula, we get

$$B - P + \frac{2}{3}P - \frac{1}{3}(a_4 + 2a_5 + \dots) = 2,$$

*) See «Kvant», 1974, No. 8.

⟦folio 13⟧

$$3B - P = 6 + \sum_{i=1}^{i+3} i a_{i+3}.$$

Let us call the degree $\deg V_i$ of a vertex $V_i$ the number of edges emanating from this vertex. Since each edge connects two vertices, then $\sum_{i=1}^{i+3} \deg V_i = 2P$.

Let us introduce the quantities $\deg V$, called the average degree of the graph:

$$\deg V = \frac{\sum_{i=1}^{i+3} \deg V_i}{B}.$$

It follows from the definition that $\sum_{i=1}^{i+3} \deg V_i = B \deg V$, that is, $2P = B \cdot \deg V$, whence $P = \frac{1}{2} B \cdot \deg V$.

Substituting this expression for $P$ into formula (2), we obtain

$$3B - \frac{1}{2} B \cdot \deg V = 6 + \sum_{i=1}^{i+3} i a_{i+3},$$

or

$$B \cdot (6 - \deg V) = 12 + 2 \sum_{i=1}^{i+3} i a_{i+3}.$$

Thus, the average degree of a graph is always less than 6, but it can be as close to 6 as you like—prove it.

We call a graph a $n$-gon if each of its vertices has the same number of edges. Obviously, the average degree of a regular graph is equal to the number of edges emerging from each vertex (we will simply call it the degree of a regular graph).

From formula (3) it follows

Theorem 1. The degree of a regular graph does not exceed 5.

A very interesting type of regular graphs are graphs of degree 5. Let's see how many vertices a regular graph of degree 5 can have.

It is obvious (see formula (3)) that a regular graph of this degree cannot have less than 12 vertices. A regular graph with 12 vertices actually exists and is represented by the projection of the icosahedron onto the plane (Fig. 3). From the parity of the product $B \cdot \deg V = 2P$ we see that there are no graphs of degree 5 with an odd number of vertices.

Now we will describe a method for constructing regular graphs with any fourREM number of vertices (not less than 12), except for graphs with 14, 18 and 22 vertices. For graphs with 14 and 18 vertices, see the substitution at the end of the statistic; a graph with 22 vertices is depicted at figure 4.

Take the convex $n$-gon $A = (A_1, A_2, \dots, A_n)$. Inside it we place the $n$-gon $B = (B_1, B_2, \dots, B_n)$. By connecting the midpoints of adjacent sides of the $n$-gon $B$, we obtain a $n$-gon $C = (C_1, C_2, \dots, C_n)$, where $C_i$ is the midpoint of $B_i B_{i+1}$, $i = 1, 2, \dots, n-1$; $C_n$ - middle of $B_n B_1$.

Fig. 3.

Fig. 4.

⟦folio 14⟧

Fig. 5.

By connecting the midpoints of the connecting sides of the $n$-gon $C$, we obtain the $n$-gon $D = (D_1, \dots, D_n)$, where $D_i$ is the midpoint of $C_{i-1}C_i$, $i = 2, \dots, n$; $D_1$ is the middle of side $C_nC_1$. Now connecting $A_i$ with $B_i$, $B_{i+1}$ and $C_i$, and $B_i$ with $D_i$, we obtain a graph of degree 5 with $4n$ vertices. An example of constructing a graph with 20 vertices (for $n = 5$) is shown in figure 5.

Let us now show how we can add 2 more vertices to the already constructed graph with $4n$ vertices.

Let us remove one of the external edges of the graph with $4n$ vertices. There are two vertices in the graph, from which there are 4 edges each - on figure 6 these are vertices $A$ and $B$. Let's choose a point on a non-neighboring edge—point $C$, and connect it to the vertices $A$ and $B$. The vertex $C$ was added to the vertices of the original graph, from which 4 edges emerge. Let's remove one more external edge and similarly construct the point $C'$. By connecting point $C$ with point $C'$, we obtain a new graph of degree 5, which already has 2 more vertices than the original one (see Fig. 6).

Note that the described addition of two vertices to a graph with $4n$ vertices is possible only in the case when the original graph has at least six external edges (because our construction does not provide a construction method for graphs with 14, 18 and 22 vertices).

So, it's proven.

Theorem 2. The number of vertices of a regular graph of degree 5 can be

⟦folio 15⟧

two non-endpoints of any two non-coinciding edges of this face. This proves Theorem 3 for graphs of degree 3.

2°. Graphs of degree 4. From formula (3) we find that a regular graph of degree 4 has at least six vertices. A graph with six vertices is depicted in figure 7. From formula (3) it also follows that a graph of degree 4 with a number of vertices strictly greater than 6 always has a non-triedge face. Let's discard (see Fig. 8) the edge AB of this face and connect the vertices A and B with any point on an edge that is not adjacent to the edge AB (an edge will still be found, since a non-three-edge face is chosen). Thus, one vertex is added to the original graph with the number of vertices strictly greater than 6 (an example of construction is at figure 8). The basis of the induction can be the graph with 8 vertices shown in figure 9.

So, we have proven that there are graphs of degree 4 with 6 vertices and with any number of vertices, at least 8.

Let us prove that there is no graph of degree 4 with 7 vertices. To do this, we prove that such a graph contains a subgraph depicted in figure 10, which, as is known, does not fit into the plane without self-intersections.

Consider an arbitrary vertex A of the source graph and the vertices A₁, A₂, A₃, A₄ from which it is connected. The remaining two peaks of our

Fig. 9. Fig. 10.

We denote the second graph by A' and A''. There are two possible cases.

1°. The vertices A' and A'' are not connected to each other.

Then, in order for four edges to come out of A' and A'', they must be connected to all four vertices A₁, ..., A₄ (four edges already come out of vertex A. In this case, it is easy to select the desired subgraph: as vertices I II, III (see Fig. 10) we can take vertices A, A' and A'', and as vertices IV, V, VI - vertices A₁, A₂, A₃.

2°. The vertices A' and A'' are connected to each other.

In this case, three more edges emerge from the vertices A' and A'' to some of the vertices A₁, ..., A₄. Therefore, at least two of the vertices A₁, ..., A₄ are connected to both A' and A''. Let these be vertices A₁ and A₂. The distance is again two cases.

1) One of the vertices A₃ and A₄ is connected to both A' and A''. In this case, the required subgraph is a subgraph with vertices A, A', A'', A₁, A₂, A₃.

2) A₃ and A₄ are connected exactly to one of the vertices A' and A'', say A₃ to A', and A₄ to A''. Let's discard the edge AA₄ and replace the two edges A₃A₄*) and A₄A'' with one edge A₃A'''. The required subgraph has been obtained - it is a subgraph with vertices A, A', A'', A₁, A₂, A₃.

Sweeping. From formulas (3) and (1) it follows that a regular graph of degree 5 with 14 vertices should have only one with four edges and 22 with three edges. By non-presidential enumeration one can verify that such a graph does not exist.

For a degree 5 graph with 18 vertices, there are three possibilities:

1) 3 four ribs, 26 three ribs;
2) 1 five-rib, 1 four-rib, 27 three-rib;
3) 1 six-rib, 28 three-rib.

In this case, enumeration is not provided, and the question of the existence of a regular graph of degree 5 with 18 vertices remains open.

*) The edge A₃A₄, very indo, must exist.
