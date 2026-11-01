---
id: 1990-3-erdniev-mantsaev-teoremyi-chevyi-i-menelaya-b70c2138
issue: kvant_1990_3
year: 1990
number: "3"
title: Theorems of Ceva and Menelaus
authors:
  - Эрдниев Б. П.
  - Манцаев Н.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 58
page_last: 61
page_labels: 56-59
lang: en
source: kvant_digital
extraction: vision
content_sha256: 00fe223b480c36bcf39c117f20aa69eee6a9a774d7c49157df08203c631667dd
prompt_sha256: draft-1
translated_from: content/ru/1990/03/articles/13_erdniev-mantsaev-teoremyi-chevyi-i-menelaya-b70c2138.md
source_content_sha256: b8b94f135b8b7badcc1379eb1d4cb895454e08edc28e4e01fdbf4a4a36d29f8b
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 56⟧

---
running_head:
folio:
---

Ceva's theorems
and Menelaus

V. ERDNIEV,
N. MANTSAYEV

From your school course you know theorems about remarkable points in a triangle: three bissertrices (medians, altitudes) intersect at one point. These properties are a consequence of the theorems that this article is devoted to. So, we will talk about the theorems of Ceva and Menelaus, as well as some of their generalizations to three-dimensional space.

Menelaus' theorem

This theorem was proven by the ancient Greek mathematician Menelaus

Alexandria in the 1st century AD.

Theorem 1. Let points $A_1$ and $C_1$ lie on sides BC and AB of triangle ABC (Fig. 1), and point $B_1$ on the extension of side AC of this triangle. In order for the points $A_1$, $B_1$, $C_1$ to lie on the same line, it is necessary and sufficient that the equality

$$\frac{AC_1}{C_1B} \cdot \frac{BA_1}{A_1C} \cdot \frac{CB_1}{B_1A} = 1.$$

Proof. First we prove the necessity. Let the points $A_1$, $B_1$, $C_1$ lie on the line $l$ and $AA_0 = h_1$, $BB_0 = h_2$, $CC_0 = h_3$ - perpendiculars dropped respectively from the point $A$, $B$, $C$ to the line $l$ (see Fig. 1). From the similarity of triangles $AA_0C_1$ and $BB_0C_1$ we obtain

$$\frac{AC_1}{C_1B} = \frac{h_1}{h_2}.$$

Similarly, considering other pairs of similar triangles, we obtain

⟦folio 57⟧

---
running_head:
folio:
---

$$\frac{BA_1}{A_1C} = \frac{h_2}{h_3}, \frac{CB_1}{B_1A} = \frac{h_3}{h_1}.$$

Variable proportions obtained, we arrive at the required equality.

Adequacy. Let the points $A_1, B_1, C_1$ (Fig. 2) lying on the lines $BC, AC, AB$ be such that
$$\frac{AB_1}{B_1C} \cdot \frac{CA_1}{A_1B} \cdot \frac{BC_1}{C_1A} = 1.$$
Let us prove that the points $A_1, B_1, C_1$ lie on the same line.
Let us draw the line $A_1B_1$ and prove that the point $C_1$ belongs to it.
Let's assume that this is not the case. First, notice that line $A_1B_1$ is not parallel to line $AB$ (why?). Let $T$ be the intersection point of lines $A_1B_1$ and $AB$ (see Fig. 2). Then
$$\frac{AB_1}{B_1C} \cdot \frac{CA_1}{A_1B} \cdot \frac{BT}{TA} = 1.$$ (1)

From the condition and equality (1) it follows that
$$\frac{BT}{TA} = \frac{BC_1}{C_1A}.$$

Since the points $T$ and $C_1$ lie outside the segment $AB$, their coincidence easily follows from the following lemma.

Lemma. Let $A$ and $B$ be two distinct points. Then for any $k > 0, k \neq 1$ on the line $AB$ there are two and only two points $U$ and $V$ as well as $\frac{AU}{UB} = \frac{AV}{VB} = k$, and one of these points belongs to the segment $AB$, and the other lies outside the segment $AB$.

Proof. Let us introduce coordinates on the straight line $AB$, taking the point $A$ as the origin of coordinates (Fig. 3). Let $k > 1$ for definiteness. the coordinate of the desired point $U$, lying inside the segment $AB$, satisfies the equation $\frac{u}{b - u} = k$, whence $u = \frac{k}{k + 1} b$.

The point $V$ outside the segment $AB$ is uniquely found from the equation $\frac{v}{v - b} = k$, whence $v = \frac{kb}{k - 1}$.

The case $0 < k < 1$ differs from the distance only in that the point $V$ should be sought to the left of the point $A$.

Menelaus' theorem is often formulated differently, using the concept of the relationship between directed

⟦folio 58⟧

---
running_head:
folio:
---

We assume that $\frac{AU}{UB} = k$ if $\vec{AU} = k\vec{UB}$. It is clear that if the vectors $\vec{AU}$ and $\vec{UB}$ are equally directed, then $k > 0$. If these vectors are oppositely directed, then $k < 0$, and, of course, the number $|k|$ is equal to the ratio of the lengths of the segments $AU$ and $UB$.

With this understanding of the relationship between segments, Menelaus' theorem is formulated as follows. Let three points $A_1, B_1, C_1$ lie on lines BC, AC and AB, respectively. In order for these points to belong to the same line, it is necessary and sufficient that

$$\frac{AC_1}{C_1B} \cdot \frac{BA_1}{A_1C} \cdot \frac{CB_1}{B_1A} = -1.$$

We encourage readers to prove this theorem as an exercise.

Menelaus's theorema allows for an interesting stereometric generalization.

Theorema 2. If the plane $\mu$ intersects the edges AB, BC, CD and DA of the tetrahedron ABCD at points $A_1, B_1, C_1, D_1$, then

$$\frac{AA_1}{A_1B} \cdot \frac{BB_1}{B_1C} \cdot \frac{CC_1}{C_1D} \cdot \frac{DD_1}{D_1A} = 1.$$ (2)

Conversely, if equality (2) is satisfied for four points $A_1, B_1, C_1, D_1$ lying respectively on the edges AB, BC, CD, DA of the tetrahedron, then these four points lie in the same plane.

Proof. Let $h_1, h_2, h_3, h_4$ be the distance from points A, B, C, D, respectively, to the plane $\mu$ (Fig. 4). Then

$$\frac{AA_1}{A_1B} = \frac{h_1}{h_2}, \frac{BB_1}{B_1C} = \frac{h_2}{h_3}, \frac{CC_1}{C_1D} = \frac{h_3}{h_4},$$

$$\frac{DD_1}{D_1A} = \frac{h_4}{h_1}.$$

It remains to multiply the resulting ratios.

To prove the converse theorem, we draw the plane $A_1B_1C_1$. Let this plane intersect edge DA at point T (Fig. 5). According to proven

$$\frac{AA_1}{A_1B} \cdot \frac{BB_1}{B_1C} \cdot \frac{CC_1}{C_1D} \cdot \frac{DD_1}{D_1A} = 1,$$

and according to the condition

$$\frac{AA_1}{A_1B} \cdot \frac{BB_1}{B_1C} \cdot \frac{CC_1}{C_1D} \cdot \frac{DD_1}{D_1A} = 1.$$

Pozotomu

$$\frac{DT}{TA} = \frac{DD_1}{D_1A},$$

and, by the lemma, the points T and D$_1$ coincide. The statement has been proven.

⟦folio 59⟧

---
running_head:
folio:
---

1. Prove that if all sides of a spatial quadrilateral touch a certain sphere, then the four points of contact lie in the same plane.
2. Prove that the segments connecting the midpoints of opposite edges of a tetrahedron intersect at one point.

**Ceva's theorem**

This remarkable theorem was proved in the 17th century by the ingredient and mathematician Cheva.

Theorem 3. Let the points $A_1, B_1, C_1$ lie on sides BC, AC and BA of triangle ABC (Fig. 6), respectively. In order for the segments $AA_1, BB_1$ and $CC_1$ to intersect at one point, it is necessary and sufficient that the correspondence

$$\frac{AC_1}{C_1B} \cdot \frac{BA_1}{A_1C} \cdot \frac{CB_1}{B_1A} = 1.$$ (3)

(The segments $AA_1, BB_1$ and $CC_1$ are sometimes called.)
Proof. Necessity. Let the segments $AA_1, BB_1$ and $CC_1$ intersect at point M inside triangle ABC (Fig. 7). Let us denote by $S_1, S_2, S_3$ the areas of triangles AMC, CMB and AMB, and by $h_1, h_2$ the distances from points A and B to line MC, respectively.

Then

$$\frac{AC_1}{C_1B} = \frac{h_1}{h_2} = \frac{S_1}{S_2},$$

analgoric

$$\frac{BA_1}{A_1C} = \frac{S_3}{S_1}, \frac{CB_1}{B_1A} = \frac{S_2}{S_3}.$$

Having tested the obtained proportions, we are convinced of the validity of the theorem.

Adequacy. Let the points $A_1, B_1, C_1$ lie on the sides BC, CA and AB of the triangle and let (3) be satisfied, M is the intersection point of the segments $AA_1$ and $BB_1$, and the segment CM intersects the side AB at point Q. Then, according to what has already been proven,

$$\frac{AQ}{QB} \cdot \frac{BA_1}{A_1C} \cdot \frac{CB_1}{B_1A} = 1,$$

So

$$\frac{AQ}{QB} = \frac{AC_1}{C_1B}.$$

The word lemma implies a coincidence of points: $Q=C_1$. Sufficiency has been proven.

Exercise

3. Prove that the following segments in a triangle intersect at one point: a) medians; b) bisectors; b) height; d) segments connecting the vertices of the triangle from the point of contact of the opposite sides with the incircle (Gergon point); d) segments passing through the vertices and dividing the perimeter in half; e) segments connecting the vertices of the triangle from the point of contact of the opposite sides with the inscribed circles.

Let us now turn to the spatial generalization of Ceva's theorem.

Theorem 4. Let M be a point inside the triangle ABCD, $A_1, B_1, C_1$ and $D_1$ the intersection points of the planes CMD, AMD, AMB and CMB with the edges (Fig. 8) AB, BC, CD and DA, respectively. Then

$$\frac{AA_1}{A_1B} \cdot \frac{BB_1}{B_1C} \cdot \frac{CC_1}{C_1D} \cdot \frac{DD_1}{D_1A} = 1.$$ (4)

Conversely, if correspondence (4) is satisfied for the point $A_1, B_1, C_1, D_1$ lying on the corresponding edges, then the planes ABC, BCD, CDA and DAB pass through one point.

The proof of necessity is easy to obtain by noting that the points $A_1, B_1, C_1$ and $D_1$ (see Fig. 8) lie in the same plane (this is the plane passing through the lines $A_1C_1$ and $B_1D_1$, intersecting at the point M), and applying Menelaus’ theorem.

The converse theorem can be proved in the same way as the converse theorem of Menelaus in space: you need to draw a plane through the points $A_1, B_1, C_1$ and prove with the help of the lemma that this plane intersects the edge DA at the point $D_1$.

Exercise

4. Let triangle ABC have three chains $AA_1, BB_1$ and $CC_1$ intersecting at point O. Then

$$\frac{OA_1}{A_1A} + \frac{OB_1}{B_1B} + \frac{OC_1}{C_1C} = 1.$$

5. Prove that the median of a triangle is at one point (the median of a triangle is the segment connecting its vertex with the center of the opposite face).

6. In triangle ABCD, the sums of opposite edges are equal. Prove that there is a sphere tangent to all the edges of this triangle.
