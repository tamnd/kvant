---
id: 1977-10-geydman-gomotetiya-i-zamechatelnyie-tochki-v-treugolnike-5e2ac1e4
issue: kvant_1977_10
year: 1977
number: "10"
title: Homotheties and remarkable points in a triangle
authors:
  - Гейдман Б. П.
rubric: po-stranitsam-shkolnyh-uchebnikov
rubric_sub: По страницам школьных учебников
page_first: 50
page_last: 51
page_labels: 48-49
tag: 4OXW
lang: en
source: kvant_digital
extraction: vision
content_sha256: 3b7dbb5494bc08fd55601ab0eb6c94fd1a7689b5155d499d9be5b09a609d826b
prompt_sha256: draft-1
translated_from: content/ru/1977/10/articles/10_geydman-gomotetiya-i-zamechatelnyie-tochki-v-treugolnike-5e2ac1e4.md
source_content_sha256: 4d6685a4b8f6ba3fba0b1f895f930e434cc4137ab0836296b81ba2ca25a98d34
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 48⟧

Homotheties and remarkable points in a triangle

In this article we will explain how homothety is used to solve many difficult planning problems - in particular, problems about remarkable points in a triangle.

Grapecia problem

Let's start with the problem about grapezot. Here is its wording:

Prove that the straight line passing through the point of intersection of the extended lateral sides of the grapez and the point of intersection of its diagonals passes through the midpoints of the bases of the grapez.

How to solve it? Let's draw a grapecia, continue its sides, draw diagonals, and connect the midpoints of the bases (see Fig. 1). We see that many pairs of similar triangles are formed. Associated with such figures is the mapping of the plane onto itself, which is called geometry. Under homothety with center O and coefficient $k \neq 0$, the image of an arbitrary point X is a point $X_1$ such that $\overrightarrow{OX_1} = k\overrightarrow{OX}$ (see “Geometry 7”, item 79). Let's try to solve our grapezoic problem using homothety.

Let $S$ be the intersection point of the extended lateral sides $AB$ and $CD$ of the $ABCD$ curve, $O$ the intersection point of its diagonals (Fig. 1).

Consider two homotheties: $H_S$ with center $S$ and $H_O$ with center $O$, passing the base $AD$ of the grapecy into the base $BC$. The midpoint $M$ of the segment $AD$ in both homotheties goes to the midpoint $N$ of the segment $BC$, and then the points $M$ and $N$ lie on the straight line $OS$ passing through the centers of the homothety $H_S$ and $H_O$.

Let's look at this solution in more detail.

A homothety $H_S$ is defined by its center $S$ and a pair of corresponding points $A$ and $B$. By the property of homothety, the straight line $AD$ will then transform into the parallel line $BC$. The image of the point $D$ will be on the line $BC$. On the other hand, the point corresponding to the point $D$ lies on the line $SD$ passing through the center of the homothety $S$.

Thus, the homothety $H_S$ takes the point $D$ to the point of intersection of the lines $BC$ and $SD$, i.e., to the point $C$, and the base of the grapecia $AD$ to the base $BC$: $H_S([AD]) = [BC]$.

Similarly, it is proved that $H_0([AD]) = [CB]$ (the homothety $H_O$ is given by the center $O$ and the pair of corresponding points $A$ and $C$).

The homothety transforms the middle of a segment into the middle of the image of this segment, since with homothety all distances between points are multiplied by the same number equal to the modulo of the homothety coefficient.

And, finally, the midpoints of the bases of the grapecia, as the corresponding homothety points, lie on a straight line passing through its center.

Triangle center of gravity

Let us now prove, using the result of the grapecia problem, the theorem about the medians of a triangle, namely, we will prove that the medians of a triangle intersect at one point and are divided at it in the ratio 2:1, counting from the vertex.

Proof. Let $AD$, $BE$ and $CF$ be the medians of triangle $ABC$ (Fig. 2). In the graphecia $AFDC$, the medians $AD$ and $CF$ serve as diagonals, and then the point $M$ of their intersection lies on the straight line connecting the middle $E$ of the base $AC$ of the graphezia with the intersection point of the extended lateral sides $AF$ and $CD$, then there is - with the vertex $B$ of the triangle. Thus, the point $M$ of intersection of medians $AD$ and $CF$ lies and

⟦folio 49⟧

Orthocenter of the triangle
Let's prove one more theorem.

The altitudes of a triangle intersect at one point. (The point where the altitudes intersect is called the orthocenter of the triangle.)

Proof. Let $M$ be the center of gravity of the given triangle $ABC$; $F, D$ and $E$ are the middle of its side (Fig. 3). Let's consider a ready-made $H_M^{-2}$ with a center at the point $M$ and a coefficient $k = -2$. This ready-made one transforms the points $F, D$ and $E$, respectively, into the vertices $C, A$ and $B$ of the triangle $ABC$, and the altitudes of the triangle $FDE$ into the altitudes of the triangle $ABC$. But the altitudes of the triangle $FDE$, being the perpendicular bisectors to the sides of the triangle $ABC$, intersect at one point $O$ - the center of the circle circumscribed about the triangle $ABC$. Consequently, their images (when preparing $H_M^{-2}$) also intersect at one point $R$ (the orthocenter of the triangle $ABC$).

Along the way, we proved the following important corollary:

The center of gravity $M$ of any triangle, its orthocenter $R$ and the center $O$ of the circle circumscribed around it lie on the same straight line (it is called Euler’s straight line), and the point $M$ is located between the points $O$ and $R$ so that $|MR| = 2 |OM|$.

Exercise

1. Find ready-made ones that convert one of two given parallel segments to the other.
2. A circle and two points $A$ and $B$ on it are given on the plane. Let $N$ be an arbitrary point of this circle, $M$ the center of gravity of triangle $ABN$. Find the set of point $M$.
3. Two concentric circles are given on a plane. Draw a chord in the larger of them so that it is divided by a smaller circle into three congested parts.
4. Two circles touch externally. The points of tangency of common external tangents are connected in series. Prove that a circle can be inscribed in the resulting quadrilateral.
5. Given an acute angle $AOB$ and points $C$ inside it. Find a point $M$ on side $OB$, equidistant from side $OA$ and from point $C$.
6*. Prove that in any triangle the bases of the altitudes, the midpoints of the sides, and the midpoints of the segments connecting the orthocenter with the vertices of the triangle lie on the same circle. (This circle is called the circle of nine lobes.)
