---
id: 1981-4-sefibekov-o-ploschadi-mnogougolnika-c3d86c35
issue: kvant_1981_4
year: 1981
number: "4"
title: About the area of ​​a polygon
authors:
  - Сефибеков С. Р.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 22
page_last: 23
page_labels: 20-21
tag: 7UJI
lang: en
source: kvant_digital
extraction: vision
content_sha256: 948536a5f016bfa285b993e1cc7029f15979f5c8e0239ff18a3eb392f7720331
prompt_sha256: draft-1
translated_from: content/ru/1981/04/articles/07_sefibekov-o-ploschadi-mnogougolnika-c3d86c35.md
source_content_sha256: 4084bb0f455f7b6ea28c85371c33751972d96747ace7e634e202602dc17890cb
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 20⟧

6) * Check that when transforming the plane $(x; y) \rightarrow (x'; y')$, where
$$x' = x \cos \varphi - y \sin \varphi,$$
$$y' = x \sin \varphi + y \cos \varphi,$$
The area of ​​the polygon does not change. (This transformation is a rotation by an angle φ around the origin.)
c) The same for the transformation $x' = kx, y' = y/k$ (k is a fixed number); This is the so-called divergent turn.
d) How many times does the area change during the transformation $x' = ax + by, y' = cx + dy$? (Answer: This coefficient is the same for all polygons; it is equal to the modulo of the determinant $\left| \begin{array}{cc} a & b \\ c & d \end{array} \right|$.)
13. Formula (2) is also true for a small polygon. To prove it, it is convenient to use the following lemma: Let MP be a ray emanating from a certain point M. If M lies in a non-polygon, then, going around the polygon counterclockwise, we will intersect the ray MP an even number of times (equally - from right to left and from left to right); if point M lies inside the polygon, then - an odd number of times (from right to left - one time more).
14. Let the polygon be cut by a broken linear line into two parts. Check that the areas determined by formula (2) for each part add up to expression (2) for the entire polygon.
This fact (aditivity), together with the results of exercises 3 and 12 a), 6) (invariance of relative translations, symmetries and rotations) makes it possible to take number (2) as determining the area of ​​the polygon.
15. Let all sides of the polygon $A_1B_1A_2B_2...A_mB_m$ be $A_k(a_k; b_k), B_k(a_k+1; b_k), k=1, ..., m$, with $B_m(a_1; b_m)$. Write down the area formula for such a polygon.

Fig. 5. The numbers indicate how many times (taking into account the direction) the polygon goes around the vector of each piece.

nikka. Check it out for a hexagon with vertices $(-1; 0), (2; 0), (2; 5), (3; 5), (3; 7), (-1; 7)$. (This formula was useful to us in solving problem M608 - see «Kvant», 1980, No. 11.)
16. Find out what formula (2) gives for any $n$ points of the $A_1, A_2, ..., A_n$ plane.
The answer is as follows: let the closed broken line $A_1A_2...A_n$ divide the plane into $r$ a piece of area $S_1, ..., S_r$; then the right side of formula (2) is equal to the sum $k_1S_1 + ... + k_rS_r$, where the integer $k_j$ shows how many turns the broken line $A_1A_2...A_n$ of the vector $j$ of the piece makes (and turns counterclockwise are considered positive, clockwise - negative, see Fig. 5).

S. Sefibekov

About the area of ​​a polygon

The article by N. Vaguten discusses the formula for the area of ​​a polygon and its applications. Another proof of this formula is given in the note published below.

For the area of ​​the $S_n$ $n$-gon $A_1A_2...A_n$ the formula is valid
$$S_n = \frac{1}{2} \left| (x_1y_2 + x_2y_3 + ... + x_ny_1) - (y_1x_2 + y_2x_3 + ... + y_nx_1) \right|,$$
in which $(x_1; y_1), (x_2; y_2), ..., (x_n; y_n)$ are the coordinates of the vertices $A_1, A_2, ..., A_n$.

Prove formula (2) first for a right triangle with legs parallel to the coordinate axes (Fig. 1), then for a triangle whose one side is parallel to one of the coordinate axes (Fig. 2), and then for the general case (Fig. 3).

If you have solved this problem to the end, you will have some time to solve the following one.

⟦folio 21⟧

Fig. 1.

Fig. 5.

Task 2. Prove formula (1) for a convex quadrilateral.
Note. Break the quadrilateral into two triangles (using a diagonal - see Fig. 4) and apply problem 1.

Task 3. Prove formula (1) for a convex n-sleeve.
Note. Use the method of mathematical induction to represent the given convex n-sleeve $A_1A_2A_3...A_n$ as the union of a $(n - 1)$-sleeve $A_2A_3...A_n$ and a triangle $A_1A_2A_3$ (Fig. 5). For readers unfamiliar with the method of mathematical induction, we suggest solving Problem 3 for $n = 5$.

Let us now move on to the following arbitrary (not necessarily convex) polygon.

Task 4. Prove formula (1) for an arbitrary quadrilateral.
Task 5*. Prove formula (1) for an arbitrary n-reservist.
Note. Prove that in any n-space it is possible to draw a diagonal that lies entirely inside it and apply the method of mathematical induction.

Fig. 2.

Fig. 3.

Fig. 4.
