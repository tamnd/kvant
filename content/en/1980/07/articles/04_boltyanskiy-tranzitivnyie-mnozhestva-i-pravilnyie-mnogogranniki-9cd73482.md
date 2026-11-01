---
id: 1980-7-boltyanskiy-tranzitivnyie-mnozhestva-i-pravilnyie-mnogogranniki-9cd73482
issue: kvant_1980_7
year: 1980
number: "7"
title: Transitive sets and regular polyhedra
authors:
  - Болтянский В. Г.
rubric: osnovnye-stati
page_first: 6
page_last: 10
page_labels: 4-8
tag: KWKE
lang: en
source: kvant_digital
extraction: vision
content_sha256: 53c7d7784dfb238d4df5d8d7067fe0b5c05912dbe80e84ad0ff76bbcdb05b022
prompt_sha256: draft-1
translated_from: content/ru/1980/07/articles/04_boltyanskiy-tranzitivnyie-mnozhestva-i-pravilnyie-mnogogranniki-9cd73482.md
source_content_sha256: e018f1d3875b833290c3a05c49739ce101663e743c892f296fec73bd429f40eb
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 4⟧

V. Boltyansky

Transitive sets and regular polyhedra

Figure self-alignment group

A translation $f$ is called a self-alignment of a figure $F$ if it translates this figure into itself: $f(F) = F$. It is easy to prove that the set of all self-combinations of the figure $F$ is a group (for defined groups, see, for example, «Kvant», 1976, no. 10); conditions to denote the group of self-alignments of the figure $F$ by $\Gamma(F)$.

Tasks
1. Indicate all self-alignments: a) circles; b) straight; c) segment.
2. Find a figure $F$ for which the group $\Gamma(F)$ contains exactly three self-alignments.

The group of self-alignments of a figure $F$ exists associated with the “geometry” of this figure. Let, for example, $P$ be a parallelogram that is neither a rectangle nor a rhombus. There are two translations that take $P$ into itself: the identity map $e$ and the symmetry $r$ about the point of intersection of the diagonals.

Problem 3. Prove that there are no self-alignments of such a parallelogram $P$ other than $e$ and $r$.

From the fact that $\Gamma(P)$ contains the central symmetry $r$, all the basic properties of a parallelogram follow: congruence and parallelism of opposite sides, congruence of opposite angles, etc.

The group of self-alignments of a rhombus $Q$, is not a square, contains, in addition to $e$ and $r$, two axial symmetrines $s_1$, $s_2$ with respect to the diagonals, that is, $\Gamma(Q) = \{e, r, s_1, s_2\}$. From the presence in the group $\Gamma(Q)$ of additional (compared to the parallelogram of the promised type) self-alignments, specific properties of the rhombus follow (in addition to the properties inherent in the parallelogram): perpendicularity of the diagonals, coincidence of the diagonals with the bisectors of the angles, etc.

Tasks
4. List all quadrilaterals whose self-alignment group contains exactly two elements.
5. Prove that if the figure $F$ is bounded (that is, contained in some circle), then $\Gamma(F)$ cannot contain a parallel translation different from $e$.

Transitive sets on the plane

The set $H$ is called transitive if any point of this set can be translated to any other point by some self-combination of the set $H$. figure 1 shows a square from which the quadrangles of isosceles right triangles have been cut. The set of all vertices of the resulting set is on the plane, then there is a bounded set; it, by definition, contains exactly some circles. Then there also exists a circle of smallest radius,

Fig. 1.

⟦folio 5⟧

Fig. 2.
containing $H$. Let $K$ be such a smallest circle, $O$ its center.

Let's take two arbitrary points $A, B$ set $H$. Let us show that $|AO| = |BO|$. From here it will follow that $H$ lies on some circle (it is easy to see that this circle bounds the circle $K$).

Due to the transitivity of the set $H$, there is a self-combination $f \in \Gamma(H)$ such that $f(A) = B$. From $H \subset K$ follows $f(H) \subset f(K)$. But $f(H) = H$. So, $H \subset f(K)$. Thus, $H \subset K \cap f(K)$.

Since $f$ is a displacement, $f(K)$ is a circle, load-bearing to the circle $K$. If the circles $K, f(K)$ did not coincide, there would be a circle of smaller radius containing $K \cap f(K)$ and then $H$, which would contradict the choice of circle $K$. So, $f(K) = K$, and therefore $f(O) = O$.

From $f(A) = B, f(O) = O$, and the fact that $f$ is a movement, it follows $|AO| = |BO|$.

Obviously, the empty set, any one-element set, and any two-element set are transitive.

Task 6.
Prove that if a transitive set contains $2k + 1$ points ($k > 0$), then these points serve as the vertices of a regular polygon.

7. a) Prove that if a transitive set contains 4 points, then these points are the vertices of a right polygon.

6) Prove that if a transitive set contains 2k points ($k > 2$), then these points serve as the vertices of two regular $k$-gons inscribed in one circle.

8. Prove that the infinite constraint of the transitive set $H$ always fills the circle containing it completely (that is, there are no other circles of this circle that are free from the point set $H$).

Are there unbounded transitive sets?

Fig. 3.
Of course, there are: for example, the entire plane and any straight line on it. Try to come up with at least one more example.

Let us agree to call a polygon, the set of all vertices of which is transitive, a transitive polygon. Obviously, any regular polygon is transitive. However, the regular polygon $P$ has a deeper property, which can be called strong transitivity: if $A_1, A_2$ are two arbitrary vertices, and $l_1, l_2$ are the sides direct to these vertices (Fig. 2), then there is a self-alignment $f \in \Gamma(P)$ satisfying the conditions: $f(A_1) = A_2, f(l_1) = l_2$.

If the polygon $P$ has the property of strong transivity, then it is regular.

Task 9. Prove that for a regular $n$-gon $P$ the group $\Gamma(P)$ contains $2n$ variables. Make sure that all of these variables are axial symmetries.

Transitive sets in space

We can consider transitive sets in space. For example, the set of all vertices of a direct line, the base of which is a transitive polygon (Fig. 3), is transitive.

Theorem 2. If $H$ is a bounded transitive set in space, then there exists a sphere containing $H$.

The proof is the same as on the plane, only together with the smallest circle we must consider the smallest ball containing $H$. A discerning reader may, however, notice that these proofs are incomplete: it is still necessary to establish the essence of the least

⟦folio 6⟧

shero of a circle (or ball) containing a given bounded set $H$ (this can be deduced, for example, from Weierstrass’s theorem). Let us therefore present other proofs; it does not contain spaces, but is only suitable for a finite set $H$.

Lemma. Let $H = \{A_1, \dots, A_n\}$ be a finite set of points. Then there exists, and only one, point $O$ for which
$$\overrightarrow{OA}_1 + \dots + \overrightarrow{OA}_n = \overrightarrow{0}.$$

(Such a point is called the center of gravity of points $A_1, \dots, A_n$.)

Proof. Let us take an arbitrary point $Q$ and denote by $\overrightarrow{a}$ the vector $\frac{1}{n} (\overrightarrow{QA}_1 + \dots + \overrightarrow{QA}_n)$, and by $O$ the point such that $\overrightarrow{QO} = \overrightarrow{a}$. Then
$$\overrightarrow{OA}_1 + \dots + \overrightarrow{OA}_n = (\overrightarrow{OQ} + \overrightarrow{QA}_1) + \dots$$
$$\dots + (\overrightarrow{OQ} + \overrightarrow{QA}_n) = n \overrightarrow{OQ} + (\overrightarrow{QA}_1 + \dots$$
$$\dots + \overrightarrow{QA}_n) = n (-\overrightarrow{a}) + n\overrightarrow{a} = \overrightarrow{0},$$
that is, the point $O$ is excluding.

Let's prove the only thing. Let $\overrightarrow{O'A}_1 + \dots + \overrightarrow{O'A}_n = \overrightarrow{0}$. Then
$$(\overrightarrow{O'O} + \overrightarrow{OA}_1) + \dots + (\overrightarrow{O'O} + \overrightarrow{OA}_n) = \overrightarrow{0},$$
that is, $n\overrightarrow{O'O} = \overrightarrow{0}$, and therefore $\overrightarrow{O'O} = \overrightarrow{0}$, and therefore the points $O$ and $O'$ coincide.

Let us now prove Theorem 2. Let $H = \{A_1, \dots, A_n\}$ be a transitive set and $O$ the center of gravity of the points $A_1, \dots, A_n$. Let us take an arbitrary self-alignment $f$ set $H$ and denote the images of the point $A_1, \dots, A_n$, $O$ when moving $f$ by $A'_1, \dots, A'_n$, $O'$. From the equality $\overrightarrow{OA}_1 + \dots + \overrightarrow{OA}_n = \overrightarrow{0}$ it follows that $\overrightarrow{O'A'}_1 + \dots + \overrightarrow{O'A'}_n = \overrightarrow{0}$. But $A'_1, \dots, A'_n$ are the same points as $A_1, \dots, A_n$, only taken in some other order (since $f(H) = H$). Therefore, the correspondence $\overrightarrow{O'A'}_1 + \dots + \overrightarrow{O'A'}_n = \overrightarrow{0}$ can be written as $\overrightarrow{O'A}_1 + \dots + \overrightarrow{O'A}_n = \overrightarrow{0}$ by rearranging the terms as needed. According to Lemma, $O'$ coincides with $O$, that is, $f(O) = O$. So, for any self-alignment, the set $H$ point $O$ goes into itself. From here, as in the proof of Theorem 1, it follows that all points in the set $H$ are at the same distance from $O$.

From our proof it is clear that if $H = \{A_1, \dots, A_n\}$ is a transitive set not located in the same plane, and $O$ is the center of the sphere containing the set $H$, then $\overrightarrow{OA}_1 + \dots + \overrightarrow{OA}_n = \overrightarrow{0}$.

A polyhedron, the set of all vertices of which is transitive, is called a transitive polyhedron. According to Theorem 2, there is a sphere passing through its vertices (circumscribed sphere). And from the remark made it follows that if $A_1, \dots, A_n$ are all the vertices of a transitive polygon and $O$ is the center of the sphere described around it, then $\overrightarrow{OA}_1 + \dots + \overrightarrow{OA}_n = \overrightarrow{0}$.

Regular polygons

For polygons, the property of strong transitivity is formed as follows: let $A_1, A_2$ be the transitive vertices of the polygon $M$, $l_1, l_2$ be the edges, straight cheeks to $A_1, A_2$, and $\gamma_1, \gamma_2$ — faces, straight cheeks to $l_1, l_2$; then there must be a self-combination $f \in \Gamma(M)$ satisfying the conditions $f(A_1) = A_2$, $f(l_1) = l_2$, $f(\gamma_1) = \gamma_2$. A polyhedron with the property of strong transivity is called a regular polyhedron $^*$.

Task 10. Prove that the self-combination $f \in \Gamma(M)$, satisfying the conditions $f(A_1) = A_2$, $f(l_1) = l_2$, $f(\gamma_1) = \gamma_2$ (which are discussed in the definition of strong transitivity), is unique.

11. Prove that the number of elements of the group $\Gamma(M)$ is greater than the number of the regular polygon $M$.

Let $M$ be a regular polygon, $\gamma$ its face, $A_1$ and $A_2$ its two vertices, and $l_1, l_2$ the sides of the polygon $\gamma$, straight edges to the vertices $A_1, A_2$. Due to the property of strong transivity, there is a self-combination of $f \in \Gamma(M)$ satisfying the conditions $f(\gamma_1) = \gamma_2$.

*) This definition of a regular polygon is equivalent to the school one (“Geometry 9-10”, § 54). “In one direction” this will now be proven.

⟦folio 7⟧

thief conditions $f(\gamma) = \gamma, f(A_1) = A_2, f(l_1) = l_2$. The first of these equalities means that $f \in \Gamma(\gamma)$. We see that the polygon $\gamma$ is strongly transitive, that is, right and.

From the property of strong transitivity of the polygon $M$ it also follows that all its faces are congruous. Further, from the property of transitivity (hereinafter generalized, not strong) it follows that each vertex is adjacent to the same number of faces. So, all faces of a regular polygon are congruent regular polygons and each vertex has the same number of faces adjacent to it.

Lemma. Let $M$ be a regular polygon, $A$ one of its vertices, $AB_1$, ..., $AB_k$ the edges adjacent to it. Then the polygon $B_1...B_k$ is regular.

Proof. Let us denote by $\gamma_1$, ..., $\gamma_k$ the faces adjacent to the vertex $A$, and by $O$ the center of the sphere described around the polygon $M$ (Fig. 4). Since $|OB_1| = |OB_2| = R$, where $R$ is the radius of the circumscribed sphere, the vectors $\vec{b}_1 = \vec{OB}_1, \vec{b}_2 = \vec{OB}_2$ and $\vec{p} = \vec{B}_1\vec{B}_2$ satisfy the condition $\vec{b}_1^2 = \vec{b}_2^2 = (\vec{b}_1 + \vec{p})^2$, that is, $2\vec{b}_1\vec{p} = -\vec{p}^2$. Since, in addition, $|AB_1| = |AB_2| = a$, where $a$ is the length of the edge of the polygon $M$, the vectors $AB_1 = \vec{a}_1, AB_2 = \vec{a}_2$ satisfy the condition $\vec{a}_1^2 = \vec{a}_2^2 = (\vec{a}_1 + \vec{p})^2$, that is, $2\vec{a}_1\vec{p} = -\vec{p}^2$. So $2\vec{a}_1\vec{p} = 2\vec{b}_1\vec{p}$ is $\vec{p}(\vec{a}_1 - \vec{b}_1) = 0$, which means $(AO) \perp (B_1B_2)$. The same calculation shows that each of the lines $(B_1B_3), ..., (B_1B_k)$ is perpendicular to $(AO)$. Therefore, the plane $\Pi$ passing through the point $B_1$ and perpendicular to the line $AO$ contains all the points $B_1, B_2, ..., B_k$. Further, due to the property of strong transitivity, there is a self-combination of $f \in \Gamma(M)$, which maps vertex $A$, edge $AB_1$ and face $\gamma_1$, respectively, into vertex $A$, edge $AB_2$ and face $\gamma_2$. Specifically, $f(B_1) = B_2$. In this self-alignment, two sides of the face $\gamma_1$, straight to $A$, will go into two sides of the face $\gamma_2$, straight to $A$, that is, $AB_1$ will go to $AB_2$, and $AB_2$ to $AB_3$ (Fig. 4). So, $f(B_2) = B_3$. Reasoning in a similar way, we find that when moving $f$ the points $B_1, ..., B_k$ are rearranged cyclically: $f(B_1) = B_2, f(B_2) = B_3, ..., f(B_{k-1}) = B_k, f(B_k) = B_1$. Hence it follows that the polygon $B_1...B_k$, located in the plane $\Pi$, is regular.

The proven lemma allows one to easily calculate the basic parameters of regular polygons. Let us find, for example, the radius of a sphere circumscribed about a regular polygon with $k$ faces at each vertex that are regular $n$-gons (we denote the edge length by $a$). We have: $AB_1B_2 = \frac{180^\circ}{n}$ (face $\gamma_1$ is a regular $n$-gon). From the triangle $AB_1B_2$ there is a $k$-gon $B_1B_2...B_k$:

⟦folio 8⟧

$$\left| B_1 B_2 \right| = 2a \cos \frac{180^\circ}{n},$$
after which we find $r = \left| QB_1 \right|$ of the circumscribed circle around it (Fig. 5):

$$r = \frac{\left| B_1 B_2 \right|}{2 \sin 180^\circ / k} = a \cdot \frac{\cos 180^\circ / n}{\sin 180^\circ / k}.$$

Next, from the triangle $QAB_1$ and $OAB_1$ there is $\frac{r^2}{a^2} + \frac{|AQ|^2}{a^2} = 1$, $|AQ| = \frac{a^2}{2R}$, that is, $\frac{r^2}{a^2} + \left(\frac{a}{2R}\right)^2 = 1$. Substituting here instead of $r$ its value, we get the following:

$$R = \frac{a}{2\sqrt{1 - \left(\frac{\cos 180^\circ / n}{\sin 180^\circ / n}\right)^2}}.$$

Formula (*) not only gives an expression for the radius of the sphere described around a given regular polyhedron, but also allows you to indicate what values ​​$n$ and $k$ can take. Indeed, since $n \geq 3$, $\frac{180^\circ}{n} \leq 60^\circ$, $\cos \frac{180^\circ}{n} \geq \frac{1}{2}$; therefore, $\sin \frac{180^\circ}{k} > \frac{1}{2}$ (whose radical expression will not be positive), hence $k < 6$. Giving the number $k$ possible values ​​$k = 3, 4, 5$, we find that the radical expression is positive only in five cases, which correspond to five possible regular polyhedra (see “Geometry 9-10”, p. 133).

Task 12.
Use formula (*) to find the radius of the sphere described around each of the regular polyhedra. (Answers to this and subsequent problems will be given in the next issue «Kvant»).

Note. Find the lengths of the sides of the triangles on figure 6 and deduce from this that $\cos 36^\circ = \frac{\xi}{2}$, $\sin 36^\circ = \frac{\sqrt{5}}{2\sqrt{\xi}}$, $\sqrt{3 - 4\cos^2 36^\circ} = \frac{1}{\xi}$, where $\xi = \frac{1 + \sqrt{5}}{2}$.

13. For each regular polyhedron, find the angle at which its edge is visible from the center of the circumscribed sphere.

14. Calculate the surface area of ​​each of the regular polyhedra, knowing $a$ its edges.

15. Prove that for every regular polyhedron there is a sphere touching all its edges.

16. Calculate the height $h$ of a regular paramid, the base of which is the face of a regular polyhedron, and the vertex coincides with the center $O$ of a sphere circumscribed about the polyhedron. Prove that the sphere of radius $h$

Fig. 6.
with center $O$ is contained in a regular polyhedron and touches all its faces (inscribed sphere).

17. Calculate the volume of each of the regular polyhedra, knowing $a$ its edges.

18. Let $M$ be a regular polyhedron. $M^*$ denotes a polyhedron whose vertices are the centers of circles circumscribed around the faces of the polyhedron $M$. Prove that the polyhedron $M^*$ (called the dual of the polyhedron $M$) is regular. What polyhedron is the dual of the cube? Dodecadru?

19. Let $a$ be the magnitude of the dual angle of the regular polyhedron $M$, and $\beta^*$ be the angle at which the edge of the dual polyhedron $M^*$ is visible from the center of the circumscribed sphere. Prove that $\alpha + \beta^* = 180^\circ$. Using this, calculate the dual angle of each of the regular polyhedra.

20. Prove that the midpoints of an edge of a regular polyhedron serve as the vertices of a granitic polyhedron.

figure 7 shows a cuboctahedron - a polyhedron whose vertices are the midpoints of the edges of the cube (or the midpoints of the edges of the octahedron). Many crystallimes have the shape of a cuboctahedron; for example, under certain conditions - crystallization of table salt.

In our discussion of regular polyhedra, the question of their existence remained unexamined. After all, all calculations were carried out under the assumption that there exists a regular polyhedron whose faces are regular $n$-gons, and each vertex has $k$ faces adjacent to it. End-

Fig. 7.
