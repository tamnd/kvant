---
id: 1991-3-orach-teorema-menelaya-c94304d0
issue: kvant_1991_3
year: 1991
number: "3"
title: Menelaus' theorem
authors:
  - Орач Б. Г.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 54
page_last: 57
page_labels: 52, 53, 55
lang: en
source: kvant_digital
extraction: vision
content_sha256: bc409f828fc3666c0c9800cc0d6d9cf6d7de8207b7f6197c24b61c137829a546
prompt_sha256: draft-1
translated_from: content/ru/1991/03/articles/17_orach-teorema-menelaya-c94304d0.md
source_content_sha256: 82ec5a6e53dead7e4f0100ae96dea9cfc5307ae6e6b425582757d58b061e6705
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 52⟧

---
running_head:
folio:
---

Menelaus' theorem

V. ORACH

Menelaus' theorem is beautiful and simple. In the school course, this theorem was lost somewhere among the problems. Meanwhile, it is included in the golden fund of ancient Greek mathematics.

Let $\triangle ABC$ be intersected by a line not parallel to side AB and intersecting its two sides AC and BC, respectively, at points $B_1$ and $A_1$, and line AB at point $C_1$ (Fig. 1), then

$$\frac{AB_1}{B_1C} \cdot \frac{CA_1}{A_1B} \cdot \frac{BC_1}{C_1A} = 1.$$

(To avoid getting confused about the order in which the letters appear in the formula, follow the following rule: move along the contour of the triangle from the vertex to the point of intersection with the line and from the point of intersection to the next vertex.)

⟦folio 53⟧

---
running_head:
folio:
---

It remains to multiply the resulting proportions:

$$\frac{AB_1}{B_1C} \cdot \frac{CA_1}{A_1B} \cdot \frac{BC_1}{C_1A} = \frac{m \cdot n \cdot l}{n \cdot l \cdot m} = 1.$$

The theorem has been proven.

This theorem should guide us in the Arabic translation of the book “Spherics” by Menelaus of Alexandria (1st century AD).

To demonstrate its effectiveness, let's consider solving one problem in two ways: vector and using Menelaus' theorem.

Problem 1. Let AD be the median of $\triangle ABC$ (Fig. 2). Point K is taken on AD so that AK:KD=3:1. In what ratio does the line BK divide the area $\triangle ABC$?

Obviously, the ratio of the areas of triangles ABP and CBP is equal to the ratio of the segments AP and PC. So, solving the problem comes down to finding the AP/PC ratio.

Vector solution. The vector $\overline{AK}$ can be expressed in two ways through the vectors $\overline{AB}$ and $\overline{AC}$. First of all, $\overline{AK} = \frac{3}{4} \overline{AD}$. But $\overline{AD} = \frac{1}{2} (\overline{AB} + \overline{AC})$ (formula for the middle of a segment). Means,

$$\overline{AK} = \frac{3}{4} \cdot \frac{1}{2} (\overline{AB} + \overline{AC}) = \frac{3}{8} \overline{AB} + \frac{3}{8} \overline{AC}.$$

Let's denote it by $\frac{PK}{KB} = \frac{m}{n}, \overline{AP} = x \cdot \overline{AC}$.

Applying the segment division theorem to BP in this relation, we have

$$\overline{AK} = \frac{m}{m+n} \overline{AB} + \frac{n}{m+n} \overline{AP}.$$

But $AP = x \cdot \overline{AC}$ means

$$\overline{AK} = \frac{m}{m+n} \overline{AB} + \frac{nx}{m+n} \overline{AC}.$$

Comparing (1) and (2), we get

$$\frac{m}{m+n} \overline{AB} + \frac{nx}{m+n} \overline{AC} = \frac{3}{8} \overline{AB} + \frac{3}{8} \overline{AC}.$$

Using the uniqueness of the decomposition of the vector AK into two non-clinging vectors AB and AC, we obtain the system

$$\begin{cases} \frac{m}{m+n} = \frac{3}{8}, \\ \frac{n}{m+n} = \frac{3}{8x}, \end{cases}$$

whence $x = 3/5$, i.e. $AP/AC = 3/5$, and

$$\frac{AP}{PC} = \frac{3}{2}.$$

Solution using Menelaus' theorem. Applying this theorem to triangle ACD and secant line BP, we have

$$\frac{AP}{PC} \cdot \frac{CB}{BD} \cdot \frac{DK}{AK} = 1,$$

$$\frac{AP}{PC} \cdot 2 \cdot \frac{1}{3} = 1, \quad \frac{AP}{PC} = \frac{3}{2}.$$

The advantage of using Menelaus' theorem is very great.

Very often, when solving a problem, it is not Menelaus’ theorem itself that is needed, but the theorem converse to it.

Consider triangle ABC. Let the points A$_1$, B$_1$, C$_1$ belong to the lines BC, AC, AB, respectively, that is, lie on the sides of the triangle or their extensions (Fig. 3).

⟦folio 55⟧

---
running_head:
folio:
---

1. On sides AB and AC of triangle ABC there are points M and N, respectively, such that $\frac{AM}{MB} = \frac{CN}{NA} = \frac{1}{2}$. In what ratio does the intersection point S of segments BN and CM divide each of these segments?
2. In △ABC, the bicsectrix AD divides BC in the ratio 2:1. In what ratio does the median CE divide this bicector?
3. In triangle ABC, point D is taken on side AB, and points E and F on side BC so that AD:DB = 3:2, BE:EC = 1:3 and BF:FC = 4:1. In what ratio does line AE divide segment DF?
4. The orthocenter H of triangle ABC bisects the altitude. Prove that $\cos \angle C = \cos \angle A \cdot \cos \angle B$, where $\angle A, \angle B, \angle C$ are the angles at the vertices.
5. In a regular triangle ABC with side a, point E is the midpoint of BC, D is the midpoint of AC, $F \in DC$, $BF \cap DE = M$, $S_{ABMD} = \frac{5}{8} S_{ABC}$. Find MF (Fig. 6).
6. Given a parallelogram ABCD. Point M divides segment AD in relation to p, and point N divides segment DC in relation to q. Lines BM and AN intersect at point S. Calculate the ratio AS:SN (Fig. 7).
7. Through the midpoint M of side BC of parallelogram ABCD, whose area is 1, and vertex A, draw a straight line intersecting diagonal BD at point Q. Find the area of ​​quadrilateral QMCD (Fig. 8).
8. The sides △ABC are separated by points M, N and P so that AM:MB = BN:NC = CP:PA = 1:4. Find the ratio of the area of ​​the triangle bounded by lines AN, BP and CM to the area of ​​triangle ABC (Fig. 9).

Minimum amount and minimum amount
(For the beginning, see p. 49)

Gelder's alignment. It is clear that the first is a special case of the second for $p = q = 2$. Therefore, if we introduce the “long” vector $(a; b)$ according to the rule $|(a; b)|_p = (a^p + b^p)^{\frac{1}{p}}$, it turns out that the scalar product of two vectors
$(a; b) \cdot (c; d) \leq |(a; b)|_p \cdot |(c; d)|_q$
does not exceed the product of their “lengths”.
In this state, the geometric interpretation of Hölder's inequality and its meaning.
So the method is clear. We have proven quite a large number of inequalities (including several classical ones) using a modest set of functions. It is possible that readers will be able to prove other interpretive inequalities using this method.

Y expansion 4. Prove the following inequalities $a_1, \dots, a_n, b_1, \dots, b_n$ are positive numbers
a) $\sqrt[n]{a_1 \dots a_n} + \sqrt[n]{b_1 \dots b_n} \leq \sqrt[n]{(a_1 + b_1) \dots (a_n + b_n)}$,
b) $(a_1^p + \dots + a_n^p)^{\frac{1}{p}} \cdot (b_1^q + \dots + b_n^q)^{\frac{1}{q}} \leq a_1 b_1 + \dots + a_n b_n$ if $q < 0$ and $\frac{1}{p} + \frac{1}{q} = 1$
(Hölder’s inequality “on the contrary”),
d) $(a_1^p + \dots + a_n^p)^{\frac{1}{p}} + (b_1^q + \dots + b_n^q)^{\frac{1}{q}} \geq ((a_1 + b_1)^p + \dots + (a_n + b_n)^p)^{\frac{1}{p}}$, where $p > 1$ (Minkowski inequality). Prove that if $p < 1$, then the inequality is reversed.

Directions. a) Expand the linear function $y = a_1 x_1 + \dots + a_n x_n$ of $n$ variables onto the set consisting of the set $(x_1, \dots, x_n)$ such that $x_1 \dots x_n = n$. 6) Put $b_1 = \dots = b_n = 1$ within the inequality limits. d) Consider again the linear function $y = a_1 x_1 + \dots + a_n x_n$ on the set given by the conditions:
$x_1^q + \dots + x_n^q = 1$,
where the number $q$ is determined by the condition $\frac{1}{p} + \frac{1}{q} = 1$.
