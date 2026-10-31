---
id: 1973-8-sharyigin-ob-odnom-geometricheskom-meste-tochek-d327c3c0
issue: kvant_1973_8
year: 1973
number: "8"
title: About one locus of points
authors:
  - Шарыгин И. Ф.
rubric: osnovnye-stati
page_first: 47
page_last: 50
page_labels: 45-48
tag: 6D0Z
lang: en
source: kvant_digital
extraction: vision
content_sha256: 3fc236cdf239c4d2c2f87654a46041b3df46106671d5176dfb614f31b8d190a8
prompt_sha256: draft-1
translated_from: content/ru/1973/08/articles/08_sharyigin-ob-odnom-geometricheskom-meste-tochek-d327c3c0.md
source_content_sha256: a96e207c127d7ddaa5c2df6fce22b09b3a722003518b6e2b2e723d9dfa35f700
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 45⟧

I. F. Sharyzin
About one locus of points

In «Kvant» No. 11 for 1972 in “Problem «Kvant»” problem M174 was proposed. Vom its conditions.

On the sides of triangle ABC, as on the bases, equilateral triangles AB₁C, BA₁C and AC₁B (Fig. 1) are constructed. Prove that the perpendiculars drawn from points A, B and C respectively to the lines B₁C₁, C₁A₁ and A₁B₁ intersect at one point.

The published article describes one fairly general method for solving a problem of this type, in particular, solving problem M174. At the end of the article there are tasks for independent solution.

Quite often there are problems in which it is necessary to prove that some three or more lines intersect at one point. Often these problems can be solved like this: prove that two of the lines under consideration intersect at a point that satisfies some condition that is satisfied by all points of the third line and only they. As an example, we can cite the following two theorems from a school textbook: bicsectrices of the interior angles of a triangle intersect at one point; perpendiculars drawn to the midpoints of the sides of the triangle intersect at one point.

Similarly, if you need to prove that some three or more points lie on one line, then you can try to prove that all the points in question satisfy a condition that is satisfied by all points of some lines and only they (similar reasoning can be carried out not only for lines, but also, for example, for circles).

We will now talk about one geometric location of points that helps solve such problems.

Statement wording

Statement 1. Let A₁ and A₂ be two fixed (different) points of the plane; k, k₁ and k₂ are real numbers. Then the locus of a point M such that

k₁ (A₁M)² + k₂ (A₂M)² = k,
we will:

a) a circle or one point, or an empty set, if k₁ + k₂ ≠ 0;

b) a straight line perpendicular to the segment A₁A₂, if k₁ + k₂ = 0 (but k₁ ≠ 0).

Fig. 1.

⟦folio 46⟧

A generalization of Statement 1 for a large number of points is also true.

Statement 2. Let $A_1, A_2, \dots, A_n$ be fixed points of the plane, $k_1, k_2, \dots, k_n$ (all $k_i \neq 0$) be given numbers. Then the locus of the points $M$ is also that the sum
$$k_1(A_1M)^2 + k_2(A_2M)^2 + \dots + k_n(A_nM)^2$$
constant, we will
a) circle, point or empty set if $k_1 + k_2 + \dots + k_n \neq 0$;
b) a straight line or the entire plane if $k_1 + k_2 + \dots + k_n = 0$.

Using Statement 16, we can prove the following very useful condition.

Statement 3. In order for the redistributions omitted from the points $A_1, B_1$ and $C_1$ to correspond to the sides BC, AC and AB of triangle ABC to intersect at one point, it is necessary and sufficient to satisfy the equality
$$(A_1B)^2 - (BC_1)^2 + (C_1A)^2 - (AB_1)^2 + (B_1C)^2 - (CA_1)^2 = 0.$$ (1)

The following corollary follows from the last statement.

Statement 4. If the redistributions dropped from the vertices $A_1, B_1, C_1$ of the triangle $A_1B_1C_1$ to the sides BC, AC and AB of the triangle ABC intersect at one point, then the redistributions dropped from the points $A, B$ and $C$ to the lines $B_1C_1, A_1C_1$ and $A_1B_1$ also intersect at one point.

Try to prove all these statements yourself. We will first show how to solve problem M174 using statement 3 or 4, and then we will prove the statements themselves.

Solution to problem M174

According to Statement 3, we need to check the following equality (see Fig. 1):
$$(AB_1)^2 - (B_1C)^2 + (CA_1)^2 - (A_1B)^2 + (BC_1)^2 - (C_1A)^2 = 0.$$

Fig. 2.

⟦folio 47⟧

where
$(MD)^2 = \frac{k - k_1(A_1D)^2 - k_2(A_2D)^2}{k_1 + k_2} = C$.

On the right side of the last equality we obtained a constant value and denoted it by $C$. Thus, $(MD)^2$ is constant, that is, the point $M$ lies on a circle with center at point $D$ and radius $\sqrt{C}$, if $C > 0$; coincides with point $D$ if $C = 0$; There are no points $M$ that satisfy the conditions of the problem if $C < 0$.

It is easy to check the converse statement: which point $M$ of the resulting set satisfies the relation $k_1(A_1M)^2 + k_2(A_2M)^2 = k$; to do this, it is enough to substitute the expression for $(MD)^2$ into formula (2).

We considered the case $k_1 > 0$, $k_2 > 0$. The case $k_1 < 0$, $k_2 < 0$ coincides with the considered replacement of the signs $k_1$, $k_2$ and $k$ with the opposite ones, and in the case $k_1 > 0$, $k_2 < 0$ (or $k_1 < 0$, $k_2 > 0$) you can act in the same way as in the very first case, only the point $D$ will lie outside the segment $A_1A_2$ (Fig. 3; do all the calculations yourself). Formula (2) remains in force in any case; we will use this in what follows.

Statement 16. Ratio
$$k_1(A_1M)^2 - k_1(A_2M)^2 = k$$

equivalent ratio
$$(A_1M)^2 - (A_2M)^2 = \frac{k}{k_1}$$.

Fig. 3.

Fig. 4. Fig. 5.

Let $D$ be the projection of the point $M$ onto the line $A_1A_2$. Then, by the Pythagorean theorem (see Fig. 4, 5)
$$(A_1M)^2 = (A_1D)^2 + (MD)^2,$$
$$(A_2M)^2 = (A_2D)^2 + (MD)^2,$$
where
$$(A_1M)^2 - (A_2M)^2 = (A_1D)^2 - (A_2D)^2 = \frac{k}{k_1}.$$

So, the problem has been reduced to finding points $D$ on the line $A_1A_2$ that satisfy the last relation. Such a point is easy to find (check), and it is the only one. point $M$ must lie on the perpendicular restored to line $A_1A_2$ at point $D$.

The converse statement is also true (prove it yourself): for all points of the line perpendicular to the segment $A_1A_2$, the difference between the squares of the distances to $A_1$ and $A_2$ is equal.

Statement 1 has been proven.

Statement 2. We will carry out the proof by induction. For $n = 2$ we have already proved Statement 2. (For $n = 2$ the locus of points is the entire plane if $k_1 + k_2 = 0$ and $A_1$ coincide with $A_2$. Then for all points of the plane $(A_1M)^2 - (A_2M)^2 = 0)$.

Now let statement 2 be true for some $n$. Let us prove that it is also true for $(n + 1)$. Note that if $n \geq 2$ and all $k_1, k_2, \dots, k_n, k_{n+1}$ are not equal to zero, then among them

⟦folio 48⟧

there are two whose sum is not equal to zero. Let it be $k_1$ and $k_2$. Let's take the point $D$, constructed in the proof of statement 1a, and use formula (2). Then equality
$$k_1(A_1M)^2 + k_2(A_2M)^2 + k_3(A_3M)^2 + \dots + k_{n+1}(A_{n+1}M)^2 = k$$
can be written in the form
$$(k_1 + k_2)(DM)^2 + k_3(A_3M)^2 + \dots + k_{n+1}(A_{n+1}M)^2 = k - k_1(A_1D)^2 - k_2(A_2D)^2.$$
Now the one constructed is on the right, and on the next the number of points has decreased by one, but the sum of the coefficients has not changed. According to the induction assumption, for the last equality, Statement 2 holds. This means that it is also true for the $(n+1)$ point. Statement 2 has been proven.

Statement 3. Necessity. Let $P$ be the intersection point of the redistributions omitted from $A_1$, $B_1$ and $C_1$ on BC, AC and AB. Proposition 16 implies the equalities
$$(A_1B)^2 - (CA_1)^2 = (PB)^2 - (CP)^2,$$
$$(B_1C)^2 - (AB_1)^2 = (PC)^2 - (AP)^2,$$
$$(C_1A)^2 - (BC_1)^2 = (PA)^2 - (BP)^2.$$
Adding these three equalities, we find that in this case condition (1) is satisfied.

Adequacy. Let condition (1) be satisfied and let $P$ be the intersection point of the redistributions dropped from $A_1$ to BC and $B_1$ to CA. From statement 16 it follows that
$$(A_1B)^2 - (CA_1)^2 + (B_1C)^2 - (AB_1)^2 = (PB)^2 - (AP)^2.$$
But from condition (1) it follows that the left-hand side of the last equality is equal to $(BC_1)^2 - (C_1A)^2$, that is, $(BC_1)^2 - (C_1A)^2 = (PB)^2 - (AP)^2$, and this means that the point $P$ lies on the redistribution from $C_1$ to AB, which was what needed to be proved.

Statement 4. It follows fairly from the symmetry of condition (1) with respect to $A$ and $A_1$, $B$ and $B_1$, $C$ and $C_1$.

Exercises
1. Using Statement 3, prove that the altitudes of the triangle intersect at one point.

2. Given three pairwise intersecting circles. Prove that all common circles of any two of these circles pass through one point.

3. Prove that if the redistributions dropped from the points $A_1$, $A_2$, ..., $A_n$ onto the lines $B_1B_2$, $B_2B_3$, ..., $B_nB_1$ intersect at one point, then
$$(B_1A_1)^2 - (A_1B_2)^2 + (B_2A_2)^2 - (A_2B_3)^2 + \dots + (B_nA_n)^2 = 0.$$

4. Take three circles, each of which touches one side of the triangle and the continuation of the other two sides. Prove that the redistributions restored to the sides of the triangle at the points of tangency of these circles intersect at one point.

5. Let the distances from some point $M$ to the vertices $A$, $B$ and $C$ of triangle ABC be expressed by the numbers $a$, $b$ and $c$. Prove that for any $d \neq 0$ for any point in the plane the distances to the vertices in the same order cannot be expressed by numbers

$$\sqrt{a^2 + d}, \sqrt{b^2 + d}, \sqrt{c^2 + d}.$$

6. Given a regular triangle ABC and an arbitrary point $D$. $A_1$, $B_1$ and $C_1$ are the centers of the circles inscribed in triangles BCD, ACD and ABD. Prove that the redistributions dropped from vertices $A$, $B$ and $C$ to $B_1C_1$, $A_1C_1$ and $A_1B_1$ respectively intersect at one point.

7. Let $A_1$, $A_2$, $A_3$ and $A_4$ be arbitrary points of the plane. Prove that there are four numbers $x_1$, $x_2$, $x_3$ and $x_4$, not all equal to zero, such that $x_1(A_1M)^2 + x_2(A_2M)^2 + x_3(A_3M)^2 + x_4(A_4M)^2$ is constructed for any point $M$ of this plane.

8. Given triangle ABC. Let us consider all possible pairs of points $M_1$ and $M_2$ such that $AM_1 : BM_1 : CM_1 = AM_2 : BM_2 : CM_2$. Prove that all lines $M_1M_2$ pass through a fixed point of the plane.

9. The circle touches side $AB$ of triangle ABC and the extension side $AC$ and CB respectively at points $M$ and $N$. The other circle touches side $AC$ and the extension side $AB$ and $BC$ respectively at points $P$ and $K$. Prove that the intersection point of lines $MN$ and $PK$ lies at the altitude of triangle ABC passing through vertex $A$.

10. Given two segments $AB$ and $CD$. Find the locus of points $M$ such that the sum $S_{\triangle ABM} + S_{\triangle CDM}$ is constructed.

11. Using the result of the previous problem, prove that the midpoints of the diagonals of the circumscribed quadrilateral and the center of the circle inscribed in it lie on the same straight line (Newton’s problem).

12. Prove that the locus of a point, the relative from which to two fixed points of the plane is constructed and is different from unity, is a circle (Apolloni circle).
