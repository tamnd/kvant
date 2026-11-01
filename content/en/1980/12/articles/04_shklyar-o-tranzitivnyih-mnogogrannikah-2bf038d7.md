---
id: 1980-12-shklyar-o-tranzitivnyih-mnogogrannikah-2bf038d7
issue: kvant_1980_12
year: 1980
number: "12"
title: About transitive polyhedra
authors:
  - Шкляр А.
rubric: osnovnye-stati
page_first: 11
page_last: 15
page_labels: 9-13
tag: C12Q
lang: en
source: kvant_digital
extraction: vision
content_sha256: 3c0767158140be016f8e4215038d87f2dc27d778a43a425a5abb3988d7089265
prompt_sha256: draft-1
translated_from: content/ru/1980/12/articles/04_shklyar-o-tranzitivnyih-mnogogrannikah-2bf038d7.md
source_content_sha256: e639c104ab6c8bddd396f80ce3810816e92de8515c768ea334658346b9ed40a8
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 9⟧

About transitive polyhedra

Last year, Kiev schoolboy A. Shklyar contributed to the editors of our magazine an article “A geometric method for finding all finite groups of positive displacements of space,” which was based on his own results, additional ones he received at meetings of the mathematical circle of the Kyiv National University.

We would not publish an article on such a non-school topic, but the theorem proved by A. Shklyar allows for reformulation related to the school topic “Polyboundaries”.

Below is an article by A. Shklyar, revised by a member of the editorial team «Kvant» Professor V. G. Boltyansky.

Section 3 gives a simple geometric description of the “structure” of the faces of positive transitive polytopes. In paragraph 4 they are all listed.

1. Movements with a fixed point

Before formulating the problem discussed in this note, let us recall (see A. Sosinsky’s article “Displacements of Space” in «Kvant» No. 8) some facts related to displacements of space. We will assume that the point $O$ is fixed in space, and we will consider only such movements of space at which $O$ remains motionless, that is, turns into itself. An example of such a movement is the rotation of $f$ by a non-rotor angle around the straight line $l$, passing through the point $O$. When moving $f$ of each point of the line $l$ transforms into itself, and there are no other fixed points (unless the angle of rotation is a multiple of 2π).

Note that a rotation is an orientation-preserving movement. (This can be calculated as follows: when turned, a regular screw turns back into a regular screw.) In Sosinsky’s article, it was proven that among the movements that leave the point $O$ fixed, rotations around straight lines passing through $O$, and only they, preserve orientation. Since the composition of two orientation-preserving translations is also orientation-preserving, we conclude that the composition of two rotations about lines passing through the point $O$ is also a rotation about some line through $O$.

2. Positive transitive polygons

Some (non-empty) set of movements $G$ is called a group of movements if it has the following properties:

1) $f \in G \Rightarrow f^{-1} \in G$;
2) $f_1 \in G$ and $f_2 \in G \Rightarrow f_2 \circ f_1 \in G$.

From what was said in the previous paragraph, it is clear that the set of rotations (at all possible angles) around lines passing through $O$ is a group of displacements.

Let now $M$ be some figure in space. The set of all self-alignments of the figure $M$ denotes $\Gamma(M)$ see («Kvant», 1980, no. 7, p. 4), and through $\Gamma_+(M)$ denotes the set of self-alignments of the figure $M$ that preserve orientation. Obviously, each of the set $\Gamma(M), \Gamma_+(M)$ is represented by a group of displacements.

The set $M$ is called transitive if for any points $A$, $B$ of this set in the group $\Gamma(M)$ there is a translation that takes $A$ to $B$. Similarly, the set $M$ is called positive transitive if for any $A$, $B \in M$ there is a self-combination $f \in \Gamma_+(M)$ such that $f(A) = B$.

We call a polytope positive if the sets

⟦folio 10⟧

THE STUFF OF ALL ITS VERTEKS IS POSITIVELY TRANSITIVE. If the polyhedron $M$ is positively transitive, then it is, of course, transitive, and therefore (see Quiet, 1980, No. 7, p. 5, Theorem 2) a sphere can be described around it. Each self-alignment of the polyhedron $M$ translates the center $O$ of this sphere into itself. Posibly, each orientation-preserving self-alignment of the polyhedron $M$ represents a rotation around a certain straight line passing through the point $O$. Now the definition of a positive transitive polyhedron can be formulated as follows: a polyhedron $M$ is called positive transitive if a sphere can be described around it and, at the same time, for any two of its vertices $A, B$ there is a rotation (around a certain straight line passing through the center of the circumscribed sphere), which takes this polyhedron into itself, and the vertex $A$ into $B$.

The goal of our article is to describe all positive transitive polyhedra.

3. What are the edges?

Let $M$ be a positive transitive polyhedron. We fix its face $y$. However, of the two: either there exists a turn $j \in \Gamma_+(M)$, different from the definite one, which takes the face $y$ into itself, or such a turn does not exist.

First, let such a rotation $j$ exist and $l$ be the axis of this rotation. Line $l$ passes through the center $O$ of the circumscribed sphere and intersects the face $y$ at some point $P$.

The point $P$ obviously cannot be the vertex of the polyhedron $M$.

The point $P$ cannot also be an interior point of some edge $AB$ belonging to the face $y$. Let's assume the opposite. For the search $f(P) = P$, the edge $AB$ must also go into itself (since there are no other edges passing through the point $P$). Therefore, $f(A) = B$, $f(B) = A$. It follows that the edge $AB$ is perpedicular to the line $l$ and is divided by the point $P$ in half, and $j$ is a rotation through the angle $j$ around

straight $l$. However, in this case, it is not very $j(\gamma) \neq \gamma$.

This means that the point $P$ is an interior point of the face $y$. Since $j(\gamma) = \gamma$, line $l$ is perpendicular to the plane of face $y$. Let $g \in \Gamma_+(M)$ be the rotation through the smallest (in magnitude) angle that takes face $y$ into itself, and $a$ be the magnitude of this angle. Then the rotation at each of the angles $2a, 3a, \dots$ also translates the face $y$ into itself. From this we can conclude that $a = \frac{2\pi}{k}$, where $k$ is some natural number. In fact, if $k$ is a number such as $(k-1)a < 2\pi$, but already $ka \geq 2\pi$, then with $ka > 2\pi$ it would turn out that a rotation through the angle $ka - 2\pi$ takes the face $y$ into itself, which, however, cannot happen, since $ka - 2\pi < a$. Therefore, $ka = 2\pi$, that is, $g$, is a rotation through the angle $\frac{2\pi}{k}$. Take an arbitrary vertex $A_0$ of face $y$ and put $A_1 = g(A_0)$, $A_2 = g(A_1)$,..., $A_{k-1} = g(A_{k-2})$ (then $g(A_{k-1}) = A_0$). The vertices of the polygon $y$ between $A_0$ and $A_1$ are denoted by $B_1$, $B_2$, ..., $B_{m-1}$. The broken line $p_0 = A_0B_1B_2...B_{m-1}A_1$ (consisting of $m$ links) turns when turning $g$ into a similar broken line $p_1 = g(p_0)$ (going from the point $A_1$ to $A_2$), etc.; finally, the broken line $p_1 = g(p_2)$ contains the points $A_k$ and $A_0$. From this it is clear that the polygon $y$ has $km$ vertices, and the $m$ vertices $A_0$, $B_1$, $B_2,..., B_{m-1}$ are “different” in the sense that no two of them can be combined by any rotation from $\Gamma_+(M)$ that translates the face $y$ into yourself. The remaining vertices are “identical” with any of the vertices $A_0$, $B_1$, $B_2,..., B_{m-1}$. We will call the number $k$ the number of periods of the face $y$.

If $m = 1$, that is, the rotation $g$ transfers the vertex $A_0$ to the neighboring vertex of the face $y$, then there is also a rotation that transfers $A_0$ to any other vertex of this face. Such a face is called transitive. It is easy to see that a transitive face is a regular polygon, and all vertices belonging to this face are constructed in the same way.

If there is no turn $j \in \Gamma_+(M)$, an excellent deferent

⟦folio 11⟧

one that takes the face $\gamma$ into itself, that is, all the vertices of the face $\gamma$ are “different”, we put $k=1$ and by $m$ we denote the number of vertices.

Now the numbers $k$ and $m$ are defined for any face of any positive granite polyhedron.

Lemma 1. For any face $\gamma$ the numbers $k$ and $m$ can take only the following values:
1) $k=1$, $m=3$; 2) $k \geq 2$, $m=2$; 3) $k > 2$, $m=1$.

Proof. Since $M$ is a positive granite polytope, there is a rotation $h_i \in \Gamma_+(M)$ that takes $B_i$ to $A_0 (i=1,2,...,m-1)$. The face $h_i(\gamma)$ is congruent with $\gamma$, but not the same, since the vertices $A_0$ and $B_i$ are “different”. Moreover, all faces $\gamma$, $h_1(\gamma),...,h_{m-1}(\gamma)$ are pairwise distinct (if $h_1(\gamma)=h_2(\gamma)$, then $h_2^{-1} h_1(B_1) = h_2^{-1}(A_0)=B_2$), and they are all adjacent to vertex $A_0$. Therefore, the sum of the angles of polygons $\gamma$, $h_1(\gamma),...,h_{m-1}(\gamma)$ at vertex $A_0$ is less than $2\pi$. This means that the sum of the angles of the polygon $\gamma$ at the vertices $A_0$, $B_1,...,B_{m-1}$ is less than $2\pi$. But the sum of the magnitude of its angles at the vertices $A_0$, $B_1,...,B_{m-1}$ is equal to $\sigma = \frac{1}{k} (km-2)\pi$. Therefore, $\frac{1}{k} (km-2)\pi < 2\pi$, that is, $m-2 < \frac{2}{k}$, $km \geq 3$. From the obtained inequalities $m-2 < \frac{2}{k}$, $km \geq 3$ it follows that for $k$ and $m$ only the indicated values ​​are possible. (Make sure of this.)

Lemma 2. If a non-granite face $\gamma$ is adjacent to the vertex $A_0$, then all other non-granite faces at the vertex $A_0$ are congruent, and the number of non-granite faces adjacent to $A_0$ is $m$.

Proof. In the proof of Lemma 1, we saw that the sum of the angles of the face $\gamma$ for “different” vertices $A_0$, $B_1,...,B_{m-1}$ is equal to $\sigma = \frac{\pi}{k} (km-2)$. For $m=3$, $k=1$ (the first possibility in Lemma 1) we have $\sigma=\pi$; at $m=2$, $k \geq 2$ (second possibility) we have

$$\sigma = \frac{k-1}{k} \cdot 2\pi \geq \pi.$$

Thus, at $m>1$ (that is, for a non-granite face) $\sigma \geq \pi$. Applying the rotations $h_1, h_2,...,h_{m-1}$ from the proof of Lemma 1 to $\gamma$, we obtain at the vertex $A_0$ m congruent non-granite faces $\gamma$, $h_1(\gamma),...,h_{m-1}(\gamma)$ and conclude that the second “set” of non-granite faces at the point $A_0$ cannot be adjacent (the sum of the plane angles at the vertex $A_0$ would be greater than or equal to $2\pi$).

When formulating the following lemma, the conditions for the term “adjacent faces” will be called two faces that have a common side (that is, two faces that only have a common vertex will not be considered funny).

Lemma 3. Any two faces adjacent to some granite face $\gamma$ can be combined by some rotation from $\Gamma_+(M)$, taking $\gamma$ to itself.

We leave the proof of this simple and important lemma to the reader.

4. Description of all positive polyhedra

To list all positive polytopes, consider four possibilities.

A) The polyhedron $M$ contains a non-granite face $\gamma$, different from a triangle, and for this face the number of periods (that is, $k$) is greater than 2. Therefore, by Lemma 1, $m=2$.

Let $A_0$ be some vertex of the face $\gamma$. Then, by Lemma 2, two congruent non-granite faces $\gamma$, $\gamma_1$ are adjacent to the vertex $A_0$, and the rest are granite faces adjacent to $A_0$. It is clear that although there is one granite face (since at least three faces meet at each vertex). In the proof of Lemma 1, we saw that the sum of the angles of the face $\gamma$ at “different” vertices (or, what is the same, the sum of the angles of the faces $\gamma$, $\gamma_1$ at the vertex $A_0$) is equal to

$$\sigma = \frac{\pi}{k} (km-2) = \frac{\pi}{k} (2k-2) = 2\pi - \frac{2\pi}{k}.$$

Since $k>2$, $\sigma \geq 2\pi - \frac{2\pi}{3}$

⟦folio 12⟧

Since the sum of all angles converging at vertex $A_0$ is less than 2π, the sum of the angles of transitive faces at vertex $A_0$ adds up to less than $\frac{2\pi}{3}$, which shows that only one transitive face γ can apply to $A_0$. If this face is a regular $l$-gon, that is, it has an angle $\alpha = \pi - \frac{2\pi}{l}$, then, according to what was said, $\sigma + \alpha < 2\pi$, that is, $(2\pi - \frac{2\pi}{k}) + (\pi - \frac{2\pi}{l}) < 2\pi$. In other words, $\frac{1}{k} + \frac{1}{l} > \frac{1}{2}$. Considering that $k > 2$, $l > 2$, we find from here the following five possibilities:

1) $m = 2$, $k = 3$, $l = 3$;
2) $m = 2$, $k = 3$, $l = 4$;
3) $m = 2$, $k = 3$, $l = 5$;
4) $m = 2$, $k = 4$, $l = 3$;
5) $m = 2$, $k = 5$, $l = 3$.

Positive transitive polyhedra corresponding to these cases are easy to construct: for this you need to “cut off” the vertices at the heel of regular polyhedra (for regular polyhedra, see “Geometry 9-10”, § 54 or «Kvant», 1980, No. 7, p. 6).

To cut off a vertex, you need to lay out segments of equal length, less than half the length of the edge, on all edges coming out of it, and draw a plane through the resulting points (Fig. 1). For example, figure 2 shows a polyhedron corresponding to case 4: it is obtained by the average of the vertices of the cube. It is easy to see that all self-combinations of a cube will transform this polyhedron into themselves and vice versa. Therefore, the group of self-alignments of a polyhedron coincides with the group of self-alignments of a cube. The same applies to the rest of the five cases listed.

Thus, the positive transitive polyhedra corresponding to case A are regular polytopes with mean vertices.

B) The polyhedron M contains a heterpositive face γ, different from the triangle, and for this face $k = 2$. Here also $m = 2$, that is, the face γ is a parallelogram ($m = 2$, $k = 2$), and $\sigma = \frac{\pi}{k}(km - 2) = \pi$. Consequently, the vertex $A_0$ is adjacent to at most two transitive faces.

Let us first consider the subcase when the vertex $A_0$ is adjacent to 2 transitive faces. These faces are not adjacent (otherwise, by Lemma 3, all faces would be congruent to one of them and would be transitive, which is impossible, since there is a heterzitive face γ). Let us assume that these faces are a regular $l_1$-gon and a regular $l_2$-gon, then $\sigma + \left(\pi - \frac{2\pi}{l_1}\right) + \left(\pi - \frac{2\pi}{l_2}\right) < 2\pi$, that is, $\frac{1}{l_1} + \frac{1}{l_2} > \frac{1}{2}$. This gives three more possibilities (we can consider $l_1 \leq l_2$:

6) $m = 2$, $k = 2$, $l_1 = 3$, $l_2 = 3$;
7) $m = 2$, $k = 2$, $l_1 = 3$, $l_2 = 4$;
8) $m = 2$, $k = 2$, $l_1 = 3$, $l_2 = 5$.

Fig. 3.

The corresponding positive transitive polyhedra can be obtained by “cutting off” the vertices and edges of regular polyhedra (at figure 1 the middle path of the vertices is shown, at figure 3 the middle edge path).

The second page of the cover shows polyhedra obtained in this way from the heel of regular polyhedra. From the point of view of our classification, polyhedra 1 and 2 are “identical” - each vertex is adjacent to the same

⟦folio 13⟧

same sets of faces (in the language of “higher” algebra: the self-combination groups of these polyhedra are isomorphic - «Kvant», 1976, No. 10, p. 10; polyhedra 3 and 4 are “identical” in the same sense).

So, in this subcase we get three types of positive transitive polytopes - regular polyhedra with middle vertices and edges.

If only one transitive face ($l$-gon) adjoins the vertex $A_0$, then $\sigma + \left( \pi - \frac{2\pi}{l} \right) < 2\pi$, that is, $-\frac{2\pi}{l} < 0$. In other words, in this case no restrictions are imposed on $l$. We get

9) $m = 2, k = 2, l \geqslant 3$ - any.

The corresponding polyhedron is a regular $l$-gonal prism (Fig. 4).

C) The polyhedron $M$ contains a non-boundary face $\gamma$, which is a triangle ($k = 1, m = 3$).

In this case, $\sigma = \pi$, and therefore three triangles $\gamma, \gamma_1, \gamma_2$ are adjacent to the vertex $A_0 \in \gamma$ and two, one, or no transitive faces may also be adjacent.

If two transitive faces are adjacent to vertex $A_0$ (a regular $l_1$-gon and a regular $l_2$-gon, moreover $l_1 \leqslant l_2$), then there are three possibilities (at figure 5 it is schematically shown how the faces at vertex $A_0$ are adjacent to each other):

10) $m = 3, k = 1, l_1 = 3, l_2 = 3$;
11) $m = 3, k = 1, l_1 = 3, l_2 = 4$;
12) $m = 3, k = 1, l_1 = 3, l_2 = 5$.

Schemes of the vertices of polyhedra 10), 11), 12) are shown in Figures 6—8. Polyhedron 10) is an “irregular icoadr”.

If the vertex $A_0$ is adjacent to one transitive face, a regular $l$-gon, then the correspondence $\sigma + \left( \pi - \frac{2\pi}{l} \right) < 2\pi$ does not give any restrictions on $l$. We get another case:

13) $m = 3, k = 1, l \geqslant 3$.

figure 9 shows the corresponding polyhedron (antiprism).

If the polyhedron has no transitive faces at all, then to each
