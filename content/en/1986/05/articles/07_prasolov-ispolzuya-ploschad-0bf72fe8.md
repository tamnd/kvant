---
id: 1986-5-prasolov-ispolzuya-ploschad-0bf72fe8
issue: kvant_1986_5
year: 1986
number: "5"
title: Using the area...
authors:
  - Прасолов В. В.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 18
page_last: 21
page_labels: 16-19
tag: BRO4
lang: en
source: kvant_digital
extraction: vision
content_sha256: 86eda7fb8f31744698654716f5c5c995b85b8c3cb494847dd2e1b519423cfe9e
prompt_sha256: draft-1
translated_from: content/ru/1986/05/articles/07_prasolov-ispolzuya-ploschad-0bf72fe8.md
source_content_sha256: cf322fa8f4cfe551fd2d2aa6a80469b8c1b94258f887545a763994fdc9910087
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 16⟧

Use area...

V. V. PRASOLOV

When solving various mathematical problems, it is often useful to consider some auxiliary element that is not present in the problem statement. We will look at the basic techniques for solving geometric problems using the area of ​​the original polygon.

Technique 1. If a polygon is cut into several polygons, then the sum of their areas is equal to the area of ​​the original polygon.

The best alternative to using this technique is one of the many proofs of the Pythagorean theorem.

Example 1 (Pythagorean theorem). Prove that the sum of the squares of the length is the square of the length of the hypotenuse.

Solution. Let $a, b$ be the lengths of the squares, $c$ the length of the hypotenuse. Let us prove that the sum of the area acts on the side $a$ and $b$ is equal to the area of the square on the side $a$ and $b$ (this is quite obvious), and in the second - on 4 right triangles with squares $a$ and $b$ and a square on the side $c$ (this requires some justification, for example, this: it is clear that all sides of the resulting quadrilaterals are equal to $c$, and the angles are easy to calculate).

Example 2. From the point $O$, lying inside the regular triangle $ABC$, perpendiculars $OA_1, OB_1, OC_1$ are dropped to the sides $BC, AC, AB$, respectively. Prove that the sum $OA_1 + OB_1 + OC_1$ does not depend on the position of the point $O$ and is equal to the height of the triangle.

Solution. Let the length of the side of the triangle $ABC$ be $a$ and the length of the height $h$. It is clear that $S_{ABC} = S_{BCO} + S_{ACO} + S_{ABO}$, that is, $\frac{1}{2}ah =$

⟦folio 17⟧

$$\frac{1}{2} aOA_1 + \frac{1}{2} aOB_1 + \frac{1}{2} aOC_1.$$
Poztou mu $h = OA_1 + OB_1 + OC_1$.

Example 3. A polygon circumscribed about a circle of radius $r$ is arbitrarily cut into triangles. Prove that the sum of the radii of the inscribed circles of these triangles is greater than $r$.

Solution. Let us denote the radii of the inscribed circles of the resulting triangles by $r_1, ..., r_n$, their perimeters by $P_1, ..., P_n$, and their areas by $S_1, ..., S_n$. We denote the area and perimeter of the original polygon by $S$ and $P$. Since $P_i < P$,

$$r_1 + ... + r_n = \frac{2S_1}{P_1} + ... + \frac{2S_n}{P_n} > \frac{2S_1}{P} + ... + \frac{2S_n}{P} = r.$$

Technique 2. The ratio of the lengths of segments can be replaced by the ratio of the areas of triangles.

Example 4. On sides $AB$ and $AC$ of triangle $ABC$ points $C_1$ and $B_1$ are taken, respectively. Let $O$ be the intersection point of the segments $BB_1$ and $CC_1$ (Fig. 2). Compute $\frac{BO}{B_1O}$ if $\frac{BC_1}{AC_1} = \alpha$ and $\frac{CB_1}{AB_1} = \beta$.

Solution. Before we begin to solve this significant part of the applied problem, let us note that it is somewhat complex. Indeed, for any triangle $ABC$ one can take points $B_1$ and $C_1$ dividing its sides $AC$ and $AB$ in given ratios. Why is the type of triangle $ABC$ not specified in the conditions, but only $\frac{BC_1}{AC_1}$ and $\frac{CB_1}{AB_1}$?

Fig. 1.

Fig. 2.

Let's move on to the solution. It is clear that $\frac{BO}{B_1O} = \frac{S_{BOC}}{S_{B1OC}}$. Let us now calculate $\frac{S_{AOC}}{S_{B1OC}}$ and $\frac{S_{BOC}}{S_{AOC}}$. It is clear that $\frac{S_{AOC}}{S_{B1OC}} = \frac{AC}{B_1C} = \frac{AB_1 + B_1C}{B_1C} = 1 + \frac{AB_1}{B_1C}$. Since triangles $BOC$ and $AOC$ have a common side $OC$, the ratio of their areas is equal to the ratio of the lengths of the heights dropped by $OC$. The height ratio is, in turn, $\frac{BC_1}{AC_1}$. Therefore $\frac{S_{BOC}}{S_{AOC}} = \frac{BC_1}{AC_1}$. As a result, we get that $\frac{BO}{B_1O} = \frac{S_{BOC}}{S_{B1OC}} = \frac{S_{BOC}}{S_{AOC}} \cdot \frac{S_{AOC}}{S_{B1OC}} = \alpha(1 + \frac{1}{\beta})$.

Example 5 (Ceva's theorem). On sides $AB$, $BC$, $CA$ of triangle $ABC$ points $C_1$, $A_1$, $B_1$ are taken, respectively. Prove that the lines $AA_1$, $BB_1$, $CC_1$ intersect at one point if and only if $\frac{AB_1}{B_1C} \cdot \frac{CA_1}{A_1B} \cdot \frac{BC_1}{C_1A} = 1$.

Solution. Let first the lines $AA_1$, $BB_1$ and $CC_1$ intersect at the point $O$. As in the previous problem, we get $\frac{CA_1}{A_1B} = \frac{S_{ACO}}{S_{ABO}}$, $\frac{BC_1}{C_1A} = \frac{S_{BCO}}{S_{ACO}}$ and $\frac{AB_1}{B_1C} = \frac{S_{ABO}}{S_{BCO}}$. Multiplying these equalities, we obtain $\frac{AB_1}{B_1C} \cdot \frac{CA_1}{A_1B} \cdot \frac{BC_1}{C_1A} = 1$.

Now suppose that $\frac{AB_1}{B_1C} \times \frac{CA_1}{A_1B} \cdot \frac{BC_1}{C_1A} = 1$, and the path $O$ is a point

⟦folio 18⟧

intersections of the segments $AA_1$ and $BB_1$. Let us denote by $C'_1$ the point of intersection of the straight line $OC$ with the segment $AB$ (Fig. 3). Then, as we have just proved,

$$\frac{AB_1}{B_1C} \cdot \frac{CA_1}{A_1B} \cdot \frac{BC'_1}{C'_1A} = 1 = \frac{AB_1}{B_1C} \cdot \frac{CA_1}{A_1B} \cdot \frac{BC_1}{C_1A}.$$

Consequently, $$\frac{BC'_1}{C'_1A} = \frac{BC_1}{C_1A}.$$ It remains to note that if the point $X$ moves along the segment $AB$ (without going beyond its limits), then the values ​​$\frac{BX}{XA}$ change monotonically, and therefore $C'_1 = C_1$, that is, the lines $AA_1$, $BB_1$ and $CC_1$ intersect at one point.

This replacement theorem deserves some comments about it. Readers who know that all medians of a triangle intersect at one point, as well as all bissertrices and all altitudes, could understand that all these facts are consequences of some more general theorem. This is true: they are consequences of Ceva's theorem, which can be obtained from it by fairly simple calculations. It is also easy to prove that the segments connecting the vertices of the triangle with the points of contact of the inscribed circle with the sides intersect at one point.

There is, however, one difficulty with heights: if the angle $C$ of a triangle $ABC$ is of type, then the height omitted from $C$ falls not on the side $AB$, but on its continuation. It turns out that Ceva's theorem can be reformulated (and, of course, proven) so that it remains true in the case when the points $A_1$, $B_1$, $C_1$ are taken not on the sides $BC$, $CA$, $AB$, but on the lines $BC$, $CA$, $AB$. To do this, you need to assign ± signs to the segments, depending on whether the corresponding vectors are directed in the same direction or in different directions (in the formulation of Cheva’s theorem, only the ratios of the lengths of segments lying on the same straight line are involved). We advise readers to come up with the desired wording themselves.

Example 6. Given a convex polygon $A_1A_2...A_n$. On side $A_1A_2$ points $B_1$ and $D_2$ are taken, on side $A_2A_3$ - points $B_2$ and $D_3$, etc. Thus, if we construct parallelograms $A_1B_1C_1D_1$, ..., $A_nB_nC_nD_n$, then straight lines $A_1C_1$, ..., $A_nC_n$ intersect at one point $O$. Prove that $A_1B_1 \cdot A_2B_2 \cdot ... \cdot A_nB_n = A_1D_1 \cdot A_2D_2 \cdot ... \cdot A_nD_n$.

Solution. Since $A_iB_iC_iD_i$ is a parallelogram and point $O$ lies on the extension of its diagonal $A_iC_i$, from the equality of the areas of triangles $A_iB_iC_i$ and $A_iC_iD_i$ and the similarity messages it follows that $$\frac{A_iB_i}{A_iD_i} = \frac{h_i}{h_{i-1}},$$ where $h_i$ is the distance from point $O$ to side $A_iA_{i+1}$. We are left with the variability of these equalities for $i=1$, ..., $n$.

Technique 3. Various formulas for area will allow you to obtain the corresponding between sides, heights, perimeter, etc.

Example 7. The lengths of the sides of a triangle form an arithmetic progression. Prove that the radius of the inscribed circle of this triangle is equal to 1/3 of one of the altitudes.

Solution. Let the lengths of the sides $a$, $b$, $c$ form an arithmetic progression. Then we get the meter of $p$ equal to $$\frac{3}{2}b.$$ Since $$\frac{1}{2}h_b \cdot b = S = r \cdot p = \frac{3}{2}r \cdot b,$$ we get $r = b/3$.

Example 8. Inside the triangle $ABC$ the point $M$ is taken. Let us denote the distances from the point $M$ to the vertices $A$, $B$, $C$ by $R_a$, $R_b$, $R_c$, and the distances from the point $M$ to the side $BC$, $CA$, $AB$ by $d_a$, $d_b$, $d_c$ respectively.

a) Prove that $a \cdot R_a \geq c \cdot d_c + b \cdot d_b$.

b) (Erdős-Mordell inequality.) Prove that

$$R_a + R_b + R_c \geq 2(d_a + d_b + d_c).$$

Solution. a) Let us drop from the point $B$ and $C$ perpendiculares $BK$ and $CL$ to the straight line

⟦folio 19⟧

muyu MA (Fig. 4). Let $a_1=BK$, $a_2=CL$. It is clear that $a_1+a_2 \leq a$. That's why
$$\frac{1}{2} a R_a \geq \frac{1}{2} a_1 R_a + \frac{1}{2} a_2 R_a = S_{ABM} + S_{ACM} = \frac{1}{2} b d_b + \frac{1}{2} cd_c.$$
Note that in the proof we only use the fact that point M lies inside the angle BAC, and not that point M lies inside the triangle.
6) Applying the inequality to point a) to a point symmetrical to M with respect to the bisector of angle A (this is consistent with the remark to point a)), we obtain the inequality
$$R_a \geq \frac{c}{a} d_b + \frac{b}{a} d_c.$$
Likewise,
$$R_b \geq \frac{c}{b} d_a + \frac{a}{b} d_c$$ and
$$R_c \geq \frac{a}{c} R_b + \frac{b}{c} R_a.$$
Adding these inequalities, we get
$$R_a + R_b + R_c \geq \left( \frac{b}{c} + \frac{c}{b} \right) d_a + \left( \frac{c}{a} + \frac{a}{c} \right) d_b + \left( \frac{b}{a} + \frac{a}{b} \right) d_c \geq 2(d_a + d_b + d_c),$$
since $\frac{x}{y} + \frac{y}{x} \geq 2$.
The Erdős–Mordell inequality has quite a long history. In 1935, the famous Hungarian mathematician P. Erdős suggested that the inequality
$$R_a + R_b + R_c \geq 2(d_a + d_b + d_c),$$
however, he could not prove it. The first to prove this inequality was the English L. J. Mordell in the same 1935, but his proof was quite complex, and only the success of many mathematical reductions proved the Erdős-Mordell inequality to such a simple form in which it is presented here.
Reception 4. If straight, parallel sides are drawn through point E lying inside the parallelogram ABCD and divide it into four parallelograms, then the parallelograms adjacent to vertices B and D are equal in size if and only if point E lies on the diagonal AC.
We invite readers to independently prove this simple statement.
Example 9. Through point M lying inside the parallelogram ABCD, straight lines PR and QS are drawn, parallel sides BC and AB (points P, Q, R, S lie on sides AB, BC, CD, DA, respectively). Prove that the lines BS, PD and MC intersect at one point (Fig. 5).
Solution. Through the point N of the intersection of lines BS and CM we draw lines Q$_1$S$_1$ and P$_1$R$_1$, parallel lines QS and PR (points P$_1$, Q$_1$, R$_1$, S$_1$ lie on the sides AB, BC, CD, DA, respectively). Let us denote the points of intersection of the lines PR and Q$_1$S$_1$, P$_1$R$_1$ and QS by F and G. Since the point M lies on the diagonal NC of the parallelogram NQ$_1$CR$_1$, S$_{FQ_1QM} = S_{MRR_1G}$, that is, S$_{NQ_1QG} = S_{NFRR_1}$. Point N lies on the diagonal BS of the parallelogram ABQS, so S$_{AP_1NS_1} = S_{NQ_1QG} = S_{NFRR_1}$. Therefore, point N lies on the diagonal PD of the parallelogram APRD.

(For the end see p. 43)
