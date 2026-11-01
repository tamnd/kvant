---
id: 1984-11-gritsaenko-tri-resheniya-odnoy-zadachi-488c726e
issue: kvant_1984_11
year: 1984
number: "11"
title: Three solutions to one problem
authors:
  - Грицаенко Н. П.
rubric: shkola-v-kvante
page_first: 31
page_last: 32
page_labels: 29-30
tag: N08J
lang: en
source: kvant_digital
extraction: vision
content_sha256: dfd8205ca5a4d2c1654f9102f01fa8d8e280a218987cfee0064a5cb51529080f
prompt_sha256: draft-1
translated_from: content/ru/1984/11/articles/10_gritsaenko-tri-resheniya-odnoy-zadachi-488c726e.md
source_content_sha256: df1e32e0d991c155ef097f69e5f147f5e66c2409eabfa75c2c9c50b9b7b487c6
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 29⟧

Mathematics 8,9,10

The note published below, “On one way to solve some equations,” presents the possibility of deduction to some extent conditionally, since each of these notes can be useful not only for students of the indicated classes.

About one way to solve some equations

Consider the following problem:
1. Solve the equation
$$ (2x-1)\sqrt{x-2}=7\sqrt{2}. $$
(1)

Traditional squaring of both sides results in a cubic equation
$$ 4x^3-12x^2+9x-100=0, $$
and many solvers try to find another way to solve the problem.

Probably, many agreed that we can try to find one of the roots of the equation by equating the corresponding factors:
$$ \begin{cases} 2x-1=7, \\ \sqrt{x-2}=\sqrt{2}, \end{cases} $$
whence $x=4$.

Unfortunately, they stop there and write out the answer. As a result, the solution contains a gross error, despite the correct answer: we “guessed” the (single) root of the equation, but did not prove that there are no more roots.

In this case, it is easy to prove that equation (1) has no other roots, since for $x>4$ we have $2x-1>7$, $\sqrt{x-2}>\sqrt{2}$ and the left side is greater than the right, and for $x<4$ (from the domain of definition of the equation) $2x-1<7$, $\sqrt{x-2}<\sqrt{2}$, therefore the left side is less than the right.

Let us emphasize once again that the solution consists of two parts:
1) we “guess” the root (or roots) of the equation;
2) We prove that the equation has no more roots.

Note that the method of equation of roots used to solve (1) is also suitable in the case when instead of a product, a sum is taken into the equation. For example, in this problem:
2. Solve the equation:
$$ 2x+\sqrt{x-2}=8+\sqrt{2}. $$

The number of factors (terms) in such problems can be large; in this case, some of the factors should be set equal to 1, as, for example, in the following problem:
3. Solve the equation:
$$ (2y-1)\sqrt{y-2}\sqrt{y-3}=7\sqrt{2}. $$
Note that the methods for guessing roots may be different. Consider, for example, the following problem:
4. Solve the equation:
$$ 2a+\sqrt{a-2}+\sqrt{a-3}=9+\sqrt{2}. $$
(2)

It is natural to assume that $\sqrt{a-2}=\sqrt{2}$, hence $a=4$. After this it is easy to check that for $a=4$
$$ 2a+\sqrt{a-3}=2\cdot4+\sqrt{1}=9. $$

Let us now prove (similar to Problem 1) that equation (2) has no other roots:
1) For $a>4$ we have $2a>8$, $\sqrt{a-2}>\sqrt{2}$, $\sqrt{a-3}>1$, so the left side is larger than the right;
2) at $a<4$ (from the domain of definition of the equation) the left side is smaller than the right.

V. E. Olkhov

Three solutions to one problem

It often follows that we do not finish our reasoning and abandon the ideas that arise in our minds. In this problem, using the example of one problem, it is shown how different ideas, far from each other in the initial stages, can lead to the goal if you show realness in searching for a solution.

Problem. Construct a right triangle using the hypotenuze and bisection of the right angle.

The problem seems relatively simple, but it was not possible to solve it “on the fly.”

As you know, solving a construction problem consists of 4 points: 1) analysis,

⟦folio 30⟧

2) construction, 3) proof, 4) research. We will begin with an examination of what is common to all three ways of solving problems. Let $c, l_c, m_c, h_c$ be the length of the corresponding hypotenuse and the bisector, median and height drawn from the vertex of the right angle. In a right-angled triangle we have $m_c = c/2 = R$, where $R$ is the radius of the circle circumscribed around the triangle.

The bisector $CD$ of the angle $C$ (Fig. 1) passes through the point $K$ - the middle of the arc $AB$. Therefore (if $|AC| \neq |BC|$) it lies between the median and the height, and its projection onto the hypotenuse is less than the projection of the median onto the hypotenuse. This implies inequality $h_c \leq l_c \leq m_c = c/2$ (the equalities are achieved for an equilateral triangle). Therefore, for $l_c > c/2$ there are no solutions, for $l_c \leq c/2$ a solution exists and is unique.

Note that for $l_c = c/2$ the triangle is equilateral, in this case the construction and proof are very complicated. In what follows we will assume that $l_c < c/2$ (and the triangle is equilateral).

First idea. The center of the circle circumscribed around the triangle lies in the middle of the enotenuse, and the bisector of the right angle passes through the middle of the arc (semicircle) $AB$, which does not contain the point $C$. We will consider a triangle inscribed in a circle. Then, perhaps, it will be possible to find a relationship between the data and the elements appearing in the drawing, resulting from the properties of a triangle inscribed in a circle.

Analysis. Let triangle $ABC$ be the desired one. Let us describe a circle around it (see Fig. 1). Let $M$ and $K$ be the intersection points of the circle and its diameter,

$$\begin{align*}
\perp &= \perp \\
M &= M \\
K &= K
\end{align*}$$

perpendicular $AB$. Then the arcs $AK$ and $KB$ are equal, so $CK$ is the bisector of the angle $C$. Triangle $MCK$ is rectangular. Obviously, to solve the problem it is enough to express the length of the segment $CK$ in terms of $c$ and $l_c$.

Triangles $MCK$ and $KOD$ are similar at two angles. Let us denote the length of the segment $DK$ by $x$. Then

$$\frac{|CK|}{|KM|} = \frac{|OK|}{|DK|} \text{ или } \frac{l_c + x}{c} = \frac{c/2}{x},$$

whence $x^2 + l_c x - c^2/2 = 0$. That's why,

$$x = -l_c/2 + \sqrt{l_c^2/4 + c^2/2}$$

(it is clear that only the positive root of the equation is suitable). Next

$$|CK| = l_c + x = l_c/2 + \sqrt{l_c^2/4 + c^2/2}. \tag{1}$$

Construction. Let's construct the segment $d = \sqrt{l_c^2/4 + c^2/2}$ as the hypotenuse of a right triangle with legs $l_c/2$ and $c/\sqrt{2}$, then the segment $l_c/2 + d$. After this, we will construct a right triangle $CMK$ along the hypotenuse $|MK| = c$ and leg $|CK| = l_c/2 + d$, draw a circle of diameter $MK$ and construct the diameter $AB$ of this circle, the perpendicular diameter $MK$. Triangle $ABC$ required (see Fig. 1).

Proof. By construction, $|AB| = c, MK$ and $AB$ are mutually perpendicular diameters, therefore $AK = KB = 90^\circ, ACK = KCB = 45^\circ$, that is, $CK$, is the bisector of the (right) angle $C$. It remains to show that $|CD| = l_c$, where $D$ is the intersection point of the segments $CK$ and $AB$.

Let's carry out the proof by contradiction. Let, for example, $|CD| = f > l_c$. Then in triangle $ABC$ the length of the hypotenuse is $c$, and the bisector is $CD - f$, therefore, according to (1)

$$|CK| = \frac{f}{2} + \sqrt{\frac{f^2}{4} + \frac{c^2}{2}} > \frac{l_c}{2} +$$

$$+ \sqrt{\frac{l_c^2}{4} + \frac{c^2}{2}} = |CK|$$

(by construction), contradiction. The case $|CD| = f < l_c$ is treated similarly.

When presenting the second and third methods of solving the problem, we will limit ourselves to analysis only. Conduct the construction and proof yourself.

Second idea. Is the desired triangle connected with other triangles that have common elements with it?
