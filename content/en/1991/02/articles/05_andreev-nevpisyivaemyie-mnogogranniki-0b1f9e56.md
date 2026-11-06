---
id: 1991-2-andreev-nevpisyivaemyie-mnogogranniki-0b1f9e56
issue: kvant_1991_2
year: 1991
number: "2"
title: Non-inscribed polyhedra
authors:
  - Андреев Е. М.
rubric: osnovnye-stati
page_first: 12
page_last: 18
page_labels: 10, 12, 13, 14, 15, 16
lang: en
source: kvant_digital
extraction: vision
content_sha256: efe901902cb5ff51d5330e5b1cd4b808091d7401d9316e9870193624bf3d99cd
prompt_sha256: draft-1
translated_from: content/ru/1991/02/articles/05_andreev-nevpisyivaemyie-mnogogranniki-0b1f9e56.md
source_content_sha256: cbd05bb703c52d68645dc04a4705e74d5dafb410752c9d57bed6aa3391083269
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 10⟧

---
running_head:
folio:
---

UNFITABLE
POLYhedra

E. ANDREEV

Consider a cube, one of whose vertices is surrounded by a plane (Fig. 1). Is it possible to fit the resulting polyhedron into a sphere? Does the answer to this question depend on what plane the vertex is on? We would like to introduce the reader to the solution to this and similar problems.

Let us assume that we are given a convex polynomial polyhedron, that is, a body in space bounded on all sides by flat polygons - boundaries - and lying on one side of the plane of each of its faces. We need to find out whether a given polyhedron can be inscribed in a sphere.

Let us denote the polyhedron by the letter $M$, number its faces, edges and vertices separately, and denote the $i$th face by $\Gamma_i$, the $i$th edge by $P_i$ and the $i$th vertex by $B_i$. It is customary to say that two faces are adjacent if they have a common edge, and two vertices are adjacent if they are the ends of the same edge.

To solve the problem, we must first check whether all polygons $\Gamma_i$ are inscribed. Then, for each edge $P_k$, consider a pair of faces $\Gamma_i$ and $\Gamma_j$ bordering this edge, and denote by $r_k$ the distance from the point of intersection of the perendluklars, reconstructed from the centers of the circles described around $\Gamma_i$ and $\Gamma_j$, to one of the vertices of the polygon $\Gamma_i$ or $\Gamma_j$; the value $r_k$ obviously does not depend on the choice of vertex (Fig. 2).

Problem 1. Prove that the polyhedron $M$ is inscribed if and only if all polygons $\Gamma_i$ are inscribed, and $r_1=r_2=\ldots=r_m$, where $m$ is the number of edges of the polyhedron.

This or a similar method of checking whether $M$ is inscribed was known for a very long time, but at the beginning of the 20th century it was discovered that in a number of cases it was possible to prove that $M$ is not inscribed without performing calculations.

The first to notice this was the German mathematician E. Steinitz. In 1927, his article was published in which the following theorem was proven.

Steinitz's theorem.

Let all the vertices of the polyhedron $M$ be divided into black and white so that

⟦folio 12⟧

---
running_head:
folio:
---

There are no two black ends. So, the sum of the numbers on the right side is not less than zero, and we came to a contradiction by assuming that the polyhedron $M$ is inscribed.

Before proceeding to the analysis of the result obtained, i.e., before finding out what to replace and what Steinitz’s theorem introduces, it is necessary to show that the theorem is meaningful, i.e., that there are polyhedra that satisfy its conditions. Let us take an octahedron (Fig. 5, a) and on each of its faces as a base we will construct a regular triangular paramid, and we will take the height of the paramid so small that the dihedral angles at the base are less than $25^\circ$. Let us consider the polyhedron $M$, glued from the original octahedron and eight newly constructed paramides (Fig. 5, b).

Problem 2. Prove that the polyhedron $M$ is convex.

Let us declare as white those vertices that were the vertices of the original octahedron, and black as all the rest. It is clear that the conditions of the Steiny theorem

Fig. 5.

tsa are fulfilled. So, we have constructed an example of a polyhedron that cannot be written into a sphere, which can be seen without knowing either the dimensions or angles of the polyhedron, but knowing only its structure.

Let's clarify what structure means. Let's start with the plane. To describe the structure of a convex polygon, one must say how many vertices it has, then it also has how many sides; each side is adjacent to two others, and two sides are stored at each vertex.

The matter is different in space: the dodecahedron (Fig. 6, a) and the decagonal rectangle (Fig. 6, b) have the same number of faces - 12, the same number of edges - 30, the same number of vertices - 20, but the structure is completely different. To describe the structure of a polygon, it is necessary to say not only how many edges, faces and vertices it has, but also how the faces are glued together, i.e. which faces are adjacent, which vertices are neighboring and which faces are preserved in each of the vertices. Two polyhedra have the same structure if they have the same number of vertices, edges and faces and they are composed of these elements in the same way.

Let us call a convex polyhedron $M$ such that neither it itself nor any other polyhedron with the same structure is inscribed and is absolutely inscribed. From Steinitz's theorem it follows that any polyhedron that satisfies its conditions I and II is not only unwritable, but also absolutely unwritable. The polyhedron constructed above (Fig. 5, b) is an example of an absolutely indescribable polyhedron. There is nothing like this on the plane: for every $n \geq 3$ there is an inscribed $n$-gon. Therefore, before Steinitz, it was believed that there are no absolutely indescribable polyhedra. There was even very plausible, but barely complete evidence of this statement. Teleri has a new problem: to find all the absolutely unwritten

⟦folio 13⟧

---
running_head:
folio:
---

polyhedra, or more precisely, to find necessary and sufficient conditions for a polyhedron to be absolutely inscribeable.

We have Steinitz's conditions - a sufficient condition of absolute inwriteability. Could it be necessary? No. This follows from the following tasks.

Problem 3. Let all the vertices of the polyhedron M be divided into black and white so that

1) the number of whites was no greater than the number of blacks;
2) no two black vertices would be adjacent and, for example, there would be two adjacent white vertices.

Prove that the polyhedron M cannot be inscribed in a sphere.

Problem 4. Construct an example of a polyhedron that satisfies the conditions of Problem 3 and does not satisfy the conditions of Steinitz’s theorem.

It is also important to note another thing: if the same number converges at each vertex of the polyhedron M, say,

A)

b)

Fig. 6.

k faces, then M satisfies neither the conditions of Steinitz’s theorem nor the conditions of Problem 3. Assume the opposite, and let m be the number of all edges of the polyhedron, p the number of its black vertices, g its white vertices, p≥g (in Steinitz’s theorem this inequality is strict). Then 2m=k(p+g): each edge has two ends, k edges converge at each vertex. In addition, each edge contains a white vertex, t. e. m≤kg, and in the case of Problem 3 this inequality is strict. On the other hand, p+g≥2g, and under the conditions of Steinitz’s theorem this inequality is strict. So, we get the inequalities

kg≤m≤kg.

If M satisfies the conditions of Steinitz's theorem or the conditions of Problem 3, then one of these inequalities will be constructed, which is impossible.

Let us now dwell on polyhedra, at each vertex of which three faces meet: these polyhedra are in some senses the most typical, but we know nothing about them from the point of view of their inscription.

Let's consider three pairwise intersecting planes. They either form a trihedral angle, or their lines of intersection are parallel, and then we say that they form an infinite trihedral angle. We fix the sphere to the neoctor. Let all the edges of the trihedral angle intersect it, but the vertex does not belong to this sphere, and perhaps there is no vertex at all. It turns out that if the vertex of an angle lies inside the ball, but not on the sphere, then the sum of the relative angles is greater than l, and if it lies outside the ball or the angle is infinite, then it is less than l. Indeed, let us consider the circles cut out by the edges of a trihedral angle on a sphere - the angles between these circles are the relative angles of the trihedral angle. Let's take a point on the sphere that does not belong to one of these circles, and stepeographically project circles from this point onto the plane. There are three possible cases (Fig. 7, a, b, c): in the first - the vertex lies outside the sphere, in the second - on the sphere, in the third - inside

⟦folio 14⟧

---
running_head:
folio:
---

The angle values ​​are preserved during stereographic projection, which means that the angles α, β, γ are equal to the original relative angles. In the first case α+β+γ is less than the sum of the angles △ABC, and in the third case they are larger. The statement has been proven.

Let all the vertices of the polyhedron M be divided into black and white so that two vertices of the same color are not adjacent.

Problem 5. Let all the vertices of the polyhedron M have the same number of faces and all the vertices are divided into black and white so that no two vertices of the same color are adjacent. Prove that the number of black vertices is equal to the number of white vertices.

Problem 6. Prove that the vertices of a polyhedron can be divided into black and white so that no two vertices of the same color are adjacent if and only if each face of the polyhedron has an even number of sides.

Note. To prove it, it is enough to take any vertex and declare it white, its neighbors black, etc. It is necessary to prove that no contradictions arise in this case, i.e., that in every closed broken line composed of the edges of a polyhedron there is an even number of links.

Let's return to the polyhedron M with colored vertices. Since M has three faces at each vertex, the number of white vertices is equal to the number of black vertices. Let's select some of its black vertices (one, two or all) and cut them off using planes. Each vertex is cut off by a single plane that intersects only those edges that emanate from this vertex and does not contain any vertices M. We denote the resulting polyhedron as M'. It differs from M in that together it has some black vertices - triangular faces. Let us prove that the polyhedron M' is absolutely indescribable.

Let us assume that the polyhedron M' or another polyhedron with the same structure is inscribed in a sphere. Let us select three faces that correspond to the three faces of the polyhedron M that belong to one trimmed vertex. These three faces are contracted in pairs, the vertex of the trimmed trihedral angle obviously lies outside the sphere, since the polyhedron is inscribed, therefore the sum of the relative angles for them is less than l. Let us assign to each edge of the polyhedron M a relative angle with the corresponding edge of the polyhedron M'. Then the sum of these assigned angles for all white and for all unseen black ver-

⟦folio 15⟧

---
running_head:
folio:
---

tires is equal to l, and with highlighted black tops it is strictly less than l. As in the proof of Steinitz’s theorem, we write out these equalities and inequalities, multiply the sums corresponding to the white vertices by -1 and add them. The result should be strictly inequality. However, on the left side we get zero, or each of the assigned angles is included in the sum once for a white vertex, and once for a black one. On the right side we will also get zero, since the number of white vertices is equal to the number of black ones. The resulting contradiction (0<0) proves our statement.

Exactly the same reasoning can be verified if the offset vertices are surrounded not by one, but by several planes, as long as the faces converging into them remain pairwise adjacent and do not converge at one vertex.

Other sufficient conditions can be obtained in this way. Now some necessary conditions have become known for a polyhedron to be absolutely non-assignable, but in general the problem has not yet been solved.

The relative angle method allows us to solve other interesting problems.

Task 7. Let three faces converge at each vertex of the polyhedron M, and let each of its faces have an even number of sides. Prove that if all but one of the vertices of a polyhedron M lie on the sphere, then the polyhedron M is inscribed.

Note. Use problem 6. Don't miss this nasty opportunity: edges coming from a vertex that is not on the sphere touch the sphere.

Similar, but more complex

Task 8. Let all the vertices of the polyhedron M be divided into black and white, as described in task 5, and the number of black vertices is equal to the number of white ones. Prove that if all but one of the vertices of a polyhedron M lie on the sphere, then the polyhedron M is inscribed.

Fig. 8.

Thus, if the vertices can be divided into black and white, as described in task 5, then the polyhedron is either absolutely non-attributable or satisfies task 8, i.e., from the fact that all its vertices, except one, lie on the sphere, it follows that it is attached.

The simplest example of an absolutely non-assignable polyhedron is a cube with one median vertex (see Fig. 1).

In conclusion, it remains to admit that Steinitz proved that it is not the theorem that is called by his name, but the dual statement to it, which we will formulate in the form of a problem.

Task 9. Let all the faces of the polyhedron M be divided into black and white so that

1) the number of black faces was greater than the number of white ones;
2) no two black edges are funny.

Prove that the polyhedron M cannot be described around a sphere.

figure 8 shows one of the simplest examples of an absolutely non-assignable polyhedron - a cube in which all vertices are in the middle.

⟦folio 16⟧

---
running_head:
folio:
---

A year ago we started a new series of publications
with the conditions of assignment “Letters on Physics”.
Today we bring to the attention of our readers
Another material from this series. This is the input-
lecture included in the physics course, given in
1918 by the famous Soviet physicist,
the creator of one of the largest physical
scientific schools by academician L. I. Mandel-
strain to students of the Odessa Polytechnic Institute. The topic of the lecture, it seems to us, remains relevant today.
This material was first published in our magazine in July 1979.
