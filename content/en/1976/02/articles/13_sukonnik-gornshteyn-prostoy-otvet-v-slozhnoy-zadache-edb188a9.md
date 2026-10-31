---
id: 1976-2-sukonnik-gornshteyn-prostoy-otvet-v-slozhnoy-zadache-edb188a9
issue: kvant_1976_2
year: 1976
number: "2"
title: A simple answer to a “complex” problem
authors:
  - Суконник Я. Н.
  - Горнштейн П. И.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 48
page_last: 52
page_labels: 46-50
tag: R33P
lang: en
source: kvant_digital
extraction: vision
content_sha256: 40519e5c0e1afcd45548950acdddba219f99f24ffcd21178fb2489bd7f31c3b0
prompt_sha256: draft-1
translated_from: content/ru/1976/02/articles/13_sukonnik-gornshteyn-prostoy-otvet-v-slozhnoy-zadache-edb188a9.md
source_content_sha256: a89877da8f813be4e46cd67feec7cc2052cc769082f344efe0b3816fe512257f
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 46⟧

A simple answer to a “Complex” problem

This article again raises the question of how planimerical problems should be solved - “algebraic” or “purely geometric”? *) Of course, it would be unreasonable to contrast these two methods; the main task when preparing for entrance exams is to learn how to combine them. The concept of a “purely geometric” solution is not always advisable - only if it comes to mind quickly enough. We only want to warn the future applicant against puzzling calculations in a relatively simple geometric problem, which can be easily solved using a “purely geometric” idea. The problems discussed in this article allow for different, sometimes very cumbersome, solutions, although the answers are always simple. Using their examples, you can easily see how important it is to be able to think “geometrically” and apply the generally well-known theorems of planimerism. Of course, finding a simple geometric solution requires some creativity. The ability to “solve a problem correctly” is an art that can only be mastered by constantly developing your geometric thinking and intuition. And for this, solve as many problems as possible, and remember that Japanese solving is a creative process.

*) See also the article by S. V. Romanov and I. F. Shara G. In “Algebraic method for solving geometric problems”, «Kvant», 1975, No. 11.

Let's start with these two problems.

Problem 1 (MAI, 1973). In a right triangle, one of the acute angles is equal to α. On the zion segments formed by the base of a height lowered onto it, as on diameters, semicircles are constructed, located on the same side as the given triangle. The name of the length of the segments of kamets enclosed inside these semicircles.

First decision. Let $CAB$ be a given triangle (angle $A$ is a right angle), $AD$ its height, points $E$ and $F$ the intersection points of semicircles with legs $AC$ and $AB$ (see Fig. 1). Obviously $(DE) \perp (AC)$ and $(DF) \perp (AB)$. Pozotomu

$$\begin{cases} |DF|^2 = |AF| \cdot |FB|, \\ |DE|^2 = |AE| \cdot |EC|. \end{cases}$$

Let's introduce the unknowns: $x = |DF| = |AE|$ and $y = |AF| = |DE|$.

Then, denoting $|AC| = b$ and $|AB| = c$, we obtain the system:

$$\begin{cases} x^2 = y(c - y), \\ y^2 = x(b - x), \end{cases}$$

where

$$x = \frac{bc^2}{b^2 + c^2}, \quad y = \frac{b^2c}{b^2 + c^2}.$$

But

$$|FB| = c - y = \frac{c^3}{b^2 + c^2}, \quad |EC| = b - x = \frac{b^3}{b^2 + c^2}.$$

⟦folio 47⟧

Hence,

$$\frac{|FB|}{|EC|} = \frac{c^3}{b^3}.$$

But $\frac{c}{b} = \text{tg}\alpha$ means $\frac{|FB|}{|EC|} = \text{tg}^3\alpha$.

Second solution. Note that

$$\widehat{DCE} = \widehat{DAF} = \widehat{BDF} = x.$$

Because

$$\frac{|FB|}{|EC|} = \frac{|DF| \cdot \text{tg}\alpha}{|EC|} = \frac{(|AF| \cdot \text{tg}\alpha) \cdot \text{tg}\alpha}{|EC|} = \frac{|DE| \cdot \text{tg}^2\alpha}{|EC|} = \text{tg}^3\alpha.$$

We see that to obtain the answer there is no need to introduce any unknowns or compose algebraic systems - it is enough to just notice that the three angles listed are congruent.

Problem 2. Given a triangle ABC. A circle is drawn that touches side BC at the base of the altitude AD of length h and passes through the middle of side AC of length b. The name is the diameter of this circle.

First decision. figure 2 shows one of the possible arrangements: the diameter DF of the circle is less than the height, the circle intersects the side AC at two points K and E, of which the upper point E is the middle, and does not intersect the second side of the triangle.

Let us denote the diameter of the exclusion circle by x: $|DF| = x$, and the length of the chord $KE$ by y: $|KE| = y$.

Fig. 2.

Applying the theorems on a tangent and a secant, as well as on two secants drawn to a circle from one point (C and A, respectively), we obtain

$$|CD|^2 = |CK| \cdot |CE|,$$

$$|AF| \cdot |AD| = |AE| \cdot |AK|.$$

From here we have

$$\begin{cases}
b^2 - h^2 = \frac{b}{2} \left( \frac{b}{2} - y \right), \\
h(h - x) = \frac{b}{2} \left( \frac{b}{2} + y \right).
\end{cases}$$

Solving this system for x, we find $|DF| = x = \frac{b^2}{2h}$.

However, this solution cannot be considered exhaustive - after all, other possibilities remain unexamined (for example, when $|DF| > |AD|$, and the second intersection point is on the continuation of side AC). Analysis of each of these cases leads to different systems and, moreover, requires the use of different theorems (in case $|DF| > |AD|$ the theorem about two intersecting chords will be needed).

Now we will give another, geometric solution to this problem; see for yourself that it no longer depends on how the circle intersects the sides of a given triangle.

Second solution. Let's connect point E with points D and F. Since DE is the median drawn to the hypotenuse of the right angled triangle CAD, we have: $|DE| = |AE| = \frac{b}{2}$, and $\widehat{EDF} = \widehat{EAD}$ (angles at the base of an equilateral triangle). Therefore, right angled triangles DEF and ADC are similar. From here

$$\frac{|DF|}{|AC|} = \frac{|DE|}{|AD|},$$

or

$$|DF| = \frac{|AC| \cdot |DE|}{|AD|},$$

that is

$$|DF| = \frac{b^2}{2h}.$$

⟦folio 48⟧

Fig. 3.

Often solving geometric problems using algebraic methods leads to complex irrational equations. Sometimes, thanks to additional messages, this can be avoided. Here are two typical tasks.

Problem 3 (LSU, 1973). Determine the height of the trapezoid if the lengths of its bases are 6 and 11, the length of one of the sides is 4, and the sum of the angles at the bottom base is $\frac{\pi}{2}$.

First decision. Let us draw the heights $BE$ and $CF$ (Fig. 3) in the trapezoid $ABCD$ and place $|BE| = |CF| = x$. We will assume that $|AB| = 4$. From the right triangle $AEB$ we find $|AE| = \sqrt{16-x^2}$. That's why

$$|FD| = |AD| - (|AE| + |EF|) = (|AD| - |BC|) - |AE| = 5 - \sqrt{16-x^2}.$$

Since the sum of the angles at the base $AD$ is $\frac{\pi}{2}$, the right triangles $AEB$ and $CF$ are similar; hence,

$$\frac{|BE|}{|FD|} = \frac{|AE|}{|CF|}.$$

We get the irrational equation

$$\frac{x}{5 - \sqrt{16-x^2}} = \frac{\sqrt{16-x^2}}{x},$$

from which we find the height of the trapezoid:

$$x = |BE| = 2,4.$$

Second solution. Let's make an additional construction: draw $(BK)$ parallel to $(CD)$. We obtain (see Fig. 3 and the conditions of the problem) a right-angled triangle $ABK$, from which the height of the trapezoid can easily be found:

$$|BE| = \frac{|AB| \cdot |BK|}{|AK|} = \frac{|AB| \cdot \sqrt{|AK|^2 - |AB|^2}}{|AK|} = \frac{|AB| \cdot \sqrt{(|AD| - |BC|)^2 - |AB|^2}}{|AD| - |BC|} = \frac{4 \cdot \sqrt{(11-6)^2 - 16}}{11-6} = 2,4.$$

Problem 4. On the sides $AD$ and $CD$ of the square $ABCD$, from side 3 two points $M$ and $N$ are taken so that the length of the broken line $MDN$ is equal to the square. Lines $AM$ and $BN$ intersect at point $E$. Find the length of the segment $ME$ if $|NE| = 4$.

First decision. Let us denote the length of the segment $DN$ (Fig. 4) by $x$. Then $|DE| = \sqrt{16-x^2}$. From the similarity of triangles $NDE$ and $BAE$ we have

$$\frac{|DN|}{|AB|} = \frac{|DE|}{|AE|},$$

that is

$$\frac{x}{3} = \frac{\sqrt{16-x^2}}{3 + \sqrt{16-x^2}}.$$

This irrational equation is related to the following equations of the fourth degree

$$x^4 - 6x^3 + 2x^2 + 96x - 144 = 0.$$

⟦folio 49⟧

Fig. 5.

The polynomial obtained on the left side is decomposed into the product of two square triangles: $x^2 + 2x - 6$ and $x^2 - 8x + 24$. Therefore $(x^2 + 2x - 6)(x^2 - 8x + 24) = 0$.

This equation has a single positive root:

$$x = |DN| = \sqrt{7} - 1.$$

Now we can easily find

$$|ME| = |MD| + |DE| = 3 - |DN| + \sqrt{16 - |DN|^2} = 3 - \sqrt{7} + 1 + \sqrt{16 - (\sqrt{7} - 1)^2} = 4 - \sqrt{7} + \sqrt{(V\overline{7} + 1)^2} = 5.$$

The simple answer suggests that there is another, less complex solution. Here it is.

Second solution. Since triangles BCN and NDE are similar, then

$$\frac{|BC|}{|CN|} = \frac{|DE|}{|DN|},$$

or

$$\frac{3}{3 - |DN|} = \frac{|DE|}{|DN|},$$

that is

$$3(|DE| - |DN|) - |DN| \cdot |DE| = 0.$$

Taking into account that $|MD| = 3 - |DN|$, and $|DN|^2 + |DE|^2 = 16$, we obtain

$$|ME| = |MD| + |DE| = (3 - |DN|) + |DE| = \sqrt{(3 - |DN| + |DE|)^2} = \sqrt{9 + 16 + 2 \cdot 0} = 5.$$

With some ingenuity, we were able to do without the irrational equation, which, according to ourselves, was not so common to solve!

One of the most common methods for solving planimetric problems among applicants is the use of trigonometry. Of course, this is a very important and useful method - sometimes the introduction of trigonometric functions is a natural and justified path to a solution. However, in each specific case, you should consider whether there is a simpler, geometric solution. Here's a case in point.

Problem 5 (MSU, Faculty of Computational Mathematics and CyberNETics, 1971). In triangle ABC, side AC is greater than side AB, and the angle at vertex A is equal to α. Point R is taken on side AC, so $|AB| = |RC|$. Let E be the midpoint of segment AR, D the midpoint of side BC. Find the angle CED.

First solution (trigonometric). Let us denote the lengths of the sides of triangle ABC by the letters a, b, c, the values ​​of its angles by the letters A, B, C, respectively, and the values ​​of the desired angle CED by the letter x.

Then (see Fig. 5):

$$\widehat{CDE} = 180^\circ - (C + x),$$

$$|CD| = \frac{a}{2},$$

$$|CE| = |CR| + |RE| = c + \frac{b - c}{2} = \frac{b + c}{2}.$$

Using the theorem of sines to find triangle CDE:

$$\frac{|CE|}{\sin CDE} = \frac{|CD|}{\sin CED},$$

that is

$$\frac{b + c}{\sin (C + x)} = \frac{a}{\sin x};$$

from triangle ABC:

$$\frac{a}{\sin A} = \frac{b}{\sin B} = \frac{c}{\sin C},$$

⟦folio 50⟧

that is
$$\frac{b+c}{\sin B+\sin C} = \frac{a}{\sin A}.$$

Dividing correspondence (1) by correspondence (2), we obtain
$$\frac{\sin B + \sin C}{\sin(C+x)} = \frac{\sin A}{\sin x},$$
or, since $B = 180^\circ - (A+C)$,
$$\frac{\sin(A+C) + \sin C}{\sin A} = \frac{\sin(C+x)}{\sin x},$$

that is
$$\frac{2\sin\left(\frac{A}{2} + C\right)\cos\frac{A}{2}}{2\sin\frac{A}{2}\cos\frac{A}{2}} = \frac{\sin(C+x)}{\sin x},$$
where
$$x = \frac{A}{2} = \frac{\alpha}{2}.$$

Second solution (geometric). We will now even present two geometric solutions.

1°. Let us draw the middle line $DF$ in triangle $ABC$. We have
$$|FE| = |CE| - |CF| = \frac{b+c}{2} - \frac{b}{2} = \frac{c}{2} = |DF|,$$
that is, the triangle $DFE$ is isosceles. Pozny
$$\widehat{CED} = \frac{1}{2}\widehat{CFD} = \frac{1}{2}\widehat{CAB} = \frac{\alpha}{2}.$$

2°. Let us carry out the bissertis $AK$ of the angle $A$ of the triangle $ABC$. Then
$$\frac{|CK|}{|CA|} = \frac{a}{b+c}.$$
but also $\frac{|CD|}{|CE|} = \frac{a}{b+c}$, which means that triangles $CDE$ and $CKA$ are similar, and the segment $DE$ is parallel to $AK$.
Therefore, $\widehat{CED} = \widehat{CAK} = \frac{\alpha}{2}$.

Isn’t it right, the “tigonometric” solution to this problem cannot be called successful? - both geometric solutions are certainly more elegant. But in some senses they are more difficult - after all, it was necessary to make additional contracts

Exercises
1 (LSU, 1973). In the rectangular $ABCD$ we have: $|AB| = a$, $|AD| = b$ ($a > b$). Find on the side $AB$ the point $E$ for which $\angle CED \cong \angle AED$.
2 (NSU, 1967). In a flat convex quadrilateral $ABCD$, the points $E, F, K, L$ are the midpoints of side $AB, BC, CD, DA$. The segments $EK$ and $FL$ divide this quadrilateral into four smaller quadrilaterals. Prove that the sum of the areas of those of these quadrilaterals that have vertices at points $A$ and $C$ is equal to the sum of the areas of the other two quadrilaterals.
3 (NSU, 1974). In the trapezoid $ABCD$, the side $CD$ is perpendicular to the base $AD$, $|BC| = a$, $|AD| = b$, $a < b$. Based on $AD$, there is a point $M$ such that ($MB$) is perpendicular to ($AC$) and ($MC$) is perpendicular to ($BD$). Find the height of the trapezoid.
4 (MIPT, 1970). Given a trapezoid $ABCD$ with bases $|AB| = a$, $|CD| = b$ ($a < b$). The circle passing through vertices $A, B$ and $C$ touches [AD]. Find the length of diagonal $AC$.
5 (MIPT, 1973). Two circles of radii $R$ and $r$ ($R > r$) have an external tangency at point $A$. Through the point $B$, taken on the larger circle, a straight line is drawn, touching the smaller circle at the point $C$. Find the length of the segment $BC$ if the length of the chord $AB$ is equal to $a$.
6 (MIPT, 1973). In an equal trapezoid $ABCD$ the angle at the base $AD$ is equal to $\frac{24}{25}$. A circle of radius $R$ touches the base $AD$, the side $AB$ and passes through the vertex $C$; it cuts off on the side $BC$ and $CD$ the congruent segments $MC$ and $NC$, respectively. Find the length of the segment $BM$.
7 (MSU, Binofak, 1973). There are two diameters $AB$ and $CD$ in a circle, $M$ is a certain point. It is known that $|AM| = 15$, $|BM| = 20$ and $|CM| = 24$. What is $|DM|$ equal to?
8 (MSU, Faculty of Geology, 1974). Given a right triangle $ABC$ with a right angle at the vertex $C$. Angle $CAB$ is equal to $\alpha$. The bissertis of angle $ABC$ intersects leg $AC$ at point $K$. On the side $BC$, as a diameter, a circle is constructed that intersects the hypotenuse $AB$ at point $M$. Find the angle $AMK$.
