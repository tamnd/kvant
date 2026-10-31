---
id: 1971-6-sidorov-zadachi-po-geometrii-db822bc1
issue: kvant_1971_6
year: 1971
number: "6"
title: Geometry problems
authors:
  - Сидоров Ю. В.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 54
page_last: 56
page_labels: 52-54
tag: 2HFM
lang: en
source: kvant_digital
extraction: vision
content_sha256: 10789fd156f1430fabb75a5b6f4e31ef06110a0bf5c181b9185e9a7a95e4bd8b
prompt_sha256: draft-1
translated_from: content/ru/1971/06/articles/13_sidorov-zadachi-po-geometrii-db822bc1.md
source_content_sha256: 254cb9c2d31a9d8d8482a4d25f78af58e2ecff34f7d2e7f48042abd81cf92f88
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 52⟧

Yu. V. Sidorov

In application exams at institutes, a lot of space is devoted to geometry problems. The conditions of most problems are formulated quite simply: in some geometric figures, several elements or correspondences between elements are specified and it is required to find an unknown element or an unknown correspondence between elements.

Such “standard” task conditions are understandable to every applicant. However, geometric problems and examples of their solution are so diverse that it is impossible to come up with any convenient classification by which one could find out the solution to each specific problem. That is why there are almost no descriptions of problem solving methods in textbooks and teaching aids. To learn how to solve geometric problems, you need to have a firm knowledge and good understanding of the basic theorems of geometry, the main thing is to constantly practice and regularly solve various problems.

In recent years, most schoolchildren solve geometric problems only in the “algebraic way”, which consists of the following. Unknown elements of a geometric figure are denoted by $x$, $y$, $z$, ..., and several correspondences between known and unknown elements are calculated. Then the resulting system of algebraic and trigonometric equations is solved and those elements or correspondence are found according to the conditions of the problem.

This formatted approach to solving geometric problems is often one of the simplest and allows you to quickly get an answer. Naturally, there may be a desire to solve all problems in this way. However, an applicant who has learned, without hesitation, to “transform” any geometric problem into an algebraic one, encounters insurmountable difficulties in the application exams if it turns out that his solution method does not lead to the desired result.

Almost every problem can be solved in different ways. Those works of applicants in which the shortest and most elegant way to solve the problem is found are highly rated. Only extensive and constant training allows you to learn to find the most diverse solution. A successful choice of unknowns, a convenient drawing, additional geometric constructions and a neat design of the solution help to correctly understand the problem and find the easiest way to solve it. Let's look at specific examples.

At the written exam in mathematics at MIPT, the following problem was proposed.

1. The bisectors AM and BN of triangle ABC intersect at point O. It is known that $AO = \sqrt{3}MO$, $NO = (\sqrt{3} - 1)BO$. Named triangles ABC.

Many applicants tried to solve this problem in the following way.

⟦folio 53⟧

Let $AB=a$, $\Rightarrow BAC=x$, $\Rightarrow ABC=y$ (Fig. 1). Let us find the length of the segment $AN$ from the triangle $ABN$ (by the property of the bicsectrix of the interior angle of a triangle and by the theorem of sines):

$$AN = AB \frac{NO}{BO} = a (\sqrt{3} - 1) = \frac{a \sin \frac{y}{2}}{\sin \left(x + \frac{y}{2}\right)}$$

Similarly, from the triangle $ABM$ we find:

$$BM = \frac{a}{\sqrt{3}} = \frac{a \sin \frac{x}{2}}{\sin \left(\frac{x}{2} + y\right)}$$

Thus, the system of equations is obtained:

$$\begin{cases} \sin \left(\frac{x}{2} + y\right) = \sqrt{3} \sin \frac{x}{2}, \\ (\sqrt{3} - 1) \sin \left(x + \frac{y}{2}\right) = \sin \frac{y}{2}. \end{cases}$$

Most of the applicants who solved the problem in this way were unable to find a solution to this rather complex system. But the bad thing is not that they did not solve the resulting system, but that they did not try to find another way to solve this problem. This problem is easier to solve in the following way (also algebraic).

Let $AB=x$, $BC=y$, $AC=z$. From triangles $ABM$ and $ABN$, by the property of the bicsectrix of the interior angle of a triangle, we obtain:

$$\frac{BM}{AB} = \frac{MO}{AO} = \frac{1}{\sqrt{3}},$$

$$\frac{AN}{AB} = \frac{NO}{BO} = \sqrt{3} - 1.$$

Hence $BM = \frac{x}{\sqrt{3}}, AN = x (\sqrt{3} - 1)$. From triangle $ABC$ we have:

$$\frac{AN}{CN} = \frac{AB}{BC}, \quad \frac{BM}{CM} = \frac{AB}{AC},$$

that is

$$\begin{cases} \frac{x (\sqrt{3} - 1)}{z - x (\sqrt{3} - 1)} = \frac{x}{y}, \\ \frac{x}{y \sqrt{3} - x} = \frac{x}{z}. \end{cases}$$

From this system of equations one finds: $y = x \sqrt{3}, z = 2x$. It follows that $x^2 + y^2 = z^2$ and by the converse of the Pythagorean theorem, $\Rightarrow ABC = \frac{\pi}{2}$.

Hence,

$$\Rightarrow BAC = \arcsin \frac{y}{z} = \frac{\pi}{3},$$

$$\Rightarrow ACB = \frac{\pi}{6}.$$

Let's consider one more problem.

2. On the side $BC$ of the triangle $ABC$ there is a point $M$, and on the side $AC$ there is a point $N$ such that $MN \parallel AB$. It is known that $AB=AN=1$ cm, $CM = \sqrt{3}$ cm. Find the length of the segment $MN$.

It is natural to try to solve this problem in the following way. Let us denote $MN$ by $x$ (Fig. 2). Then $CN = \sqrt{3} - x^2$ and from the similarity of triangles we obtain the equation

$$\frac{\sqrt{3} - x^2}{1 + \sqrt{3} - x^2} = x,$$

which can easily be converted to the form $x^4 - 2x^3 - x^2 + 6x - 3 = 0$.

It is difficult to find a solution to this equation, and therefore we must try to find another way to solve the problem. On-

⟦folio 54⟧

Fig. 2.

For example, problem 2 can be solved as follows.

Let us denote $MN$ by $x$, $CN$ by $y$. Then it is easy to obtain the following system of equations:

$$\begin{cases} x^2 + y^2 = 3, \\ \frac{y + 1}{y} = \frac{1}{x}. \end{cases}$$

From the second equation of this system we find:

$$y - x = xy, \quad x^2 + y^2 - 2xy = x^2y^2.$$

Subtracting the first equation of the system from this equation, we obtain:

$$(xy)^2 + 2xy - 3 = 0, \quad xy = -1 \pm 2.$$

Considering that $x > 0, y > 0$, we obtain the system

$$\begin{cases} xy = 1, \\ y - x = 1, \end{cases}$$

from which we find the answer:

$$x = \frac{1}{2} (\sqrt{5} - 1) (\text{см}).$$

From the examples considered, it is clear how a successful choice of unknowns

Fig. 3.

quantities helps to simplify the solution of a geometric problem in an algebraic way. Let us give examples of problems for which it is useful to make additional geometric constructions.

3. The trapezius $ABCD$ lateral side $AB$ is perpendicular to the base, the diagonals are mutually perpendicular $u \frac{AD}{BC} = k$. Find the ratio $\frac{BD}{AC}$.

Solved and e. Through the point $B$ we draw a line parallel to the diagonal $AC$ until it intersects with the line $AD$ at the point $M$ (Fig. 3). Then, by the theorem on the property of the perpendicular dropped from the vertex of the right angle of the triangle $BMD$, we have

$$BD = \sqrt{DM \cdot AD},$$

$$BM = \sqrt{DM \cdot AM}.$$

Considering that $AC = BM, AM = BC$, we find

$$\frac{BD}{AC} = \frac{BD}{BM} = \frac{\sqrt{DM \cdot AD}}{\sqrt{DM \cdot AM}} = \sqrt{\frac{AD}{BC}} = \sqrt{k}.$$

4. On sides $AC$ and $BC$ of triangle $ABC$ there are points $N$ and $M$, respectively, so that

$$\frac{AN}{CN} = n, \quad \frac{BM}{CM} = m.$$

Lines $AM$ and $BN$ intersect at point $O$.

Find relation

$$\frac{AO}{MO} u \frac{BO}{NO}.$$

Solved and e. Let's carry out $MK \parallel BN$ (Fig. 4). From the similarity of triangles $BCN$ and $CKM$ we find $CK$:

$$CK = CN \frac{CM}{BC} = CN \frac{CM}{CM + BM} = CN \frac{1}{1 + m}.$$

Hence,

$$KN = CN - CK = CN \left(1 - \frac{1}{1 + m}\right) = CN \frac{m}{1 + m}.$$
