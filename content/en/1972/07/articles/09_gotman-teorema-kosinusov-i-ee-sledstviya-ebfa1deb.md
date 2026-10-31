---
id: 1972-7-gotman-teorema-kosinusov-i-ee-sledstviya-ebfa1deb
issue: kvant_1972_7
year: 1972
number: "7"
title: The cosine theorem and its consequences
authors:
  - Готман Э. Г.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 31
page_last: 34
page_labels: 29-32
tag: G2GT
lang: en
source: kvant_digital
extraction: vision
content_sha256: 51fc246c8da7d61712b23a9d7bfacce9bbd11cb27f43ef89b575b0ebc57351f7
prompt_sha256: draft-1
translated_from: content/ru/1972/07/articles/09_gotman-teorema-kosinusov-i-ee-sledstviya-ebfa1deb.md
source_content_sha256: 645ae642aea29c17e27d3e832185c3644891ab07c774a82487539fb494fdc46a
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 29⟧

This article explains how to use the cosine theorem to solve a variety of geometric problems. CAMA cosine theorem is not proven.

To calculate the elements of a triangle from two sides and the angle between them or from three sides, the correspondence is used

$$a^2 = b^2 + c^2 - 2bc \cos A,$$

called the "theorem of cosines".

The cosine theorem can also be used to solve more difficult problems.

Example 1. Find the area of ​​a parallelogram if its sides a and b and the acute angle α between the diagonals are known.

Solution. Let $ABCD$ be a parallelogram, with $AB = a$ and $BC = b$ (Fig. 1). We will assume that $a > b^*$. Then the angle $BOC$ between the diagonals is acute, and according to the conditions of the problem $\Rightarrow BOC = \alpha$.

If we denote the length of the diagonal $AC$ by 2x, and the length of the diagonal by $*$) If $a = b$, then the parallelogram is a rhombus, and the angle between the diagonals is a straight line.

BD through 2y, then the area of ​​the parallelogram $S$ is equal to 2xysinα. From triangles $AOB$ and $BOC$, using the cosine theorem, we find sides a and b:

$$a^2 = x^2 + y^2 + 2xycos\alpha,$$
$$b^2 = x^2 + y^2 - 2xycos\alpha.$$

Because

$$a^2 - b^2 = 4xycos\alpha,$$

where

$$xy = \frac{a^2 - b^2}{4cos\alpha}.$$

Hence,

$$S = \frac{(a^2 - b^2)sin\alpha}{2cos\alpha}$$

or

$$S = \frac{a^2 - b^2}{2}tg\alpha.$$

Notes. If $A$ is the angle of a parallelogram, then $S = absinA$, which implies that $0 < S \leq ab$. Because

$$\frac{a^2 - b^2}{2}tg\alpha \leq ab$$ and

$$tg\alpha \leq \frac{2ab}{a^2 - b^2}.$$

Thus, for the problem to have a solution, it is necessary to choose the parameters a, b and α so that the inequalities are satisfied

$$a > b > 0, \alpha \leq arctg \frac{2ab}{a^2 - b^2}.$$

⟦folio 30⟧

Using well-known formulas of geometry and trigonometry, from the cosine theorem one can derive some relations connecting the elements of any triangle.

Example 2. Prove that the sides, sides and area S of triangle ABC satisfy the relations

$$\text{ctg } A + \text{ctg } B + \text{ctg } C = \frac{a^2 + b^2 + c^2}{4S}.$$

Solution. From the formula $S = \frac{1}{2} bc \sin A$ we find that $bc = \frac{2S}{\sin A}$. Substituting the expression $\frac{4S}{\sin A}$ into the formula $a^2 = b^2 + c^2 - 2bc \cos A$ together with $2bc$, we obtain the relation

$$a^2 = b^2 + c^2 - 4S \text{ctg } A.$$ (1)

Hence,

$$\text{ctg } A = \frac{b^2 + c^2 - a^2}{4S}.$$

If, in accordance with this formula, we express through the sides of the triangle $ctg B$ and $ctg C$ and add the resulting expressions, then we obtain the identity

$$\text{ctg } A + \text{ctg } B + \text{ctg } C = \frac{a^2 + b^2 + c^2}{4S}.$$

Example 3. Prove that for any triangle the following inequalities hold:

a) $\sin \frac{A}{2} \leqslant \frac{a}{2\sqrt{bc}}$,

b) $\text{tg} \frac{A}{2} \leqslant \frac{a}{2h_a}$,

$a, b, c$ are the sides of triangle ABC and $h_a$ is the altitude drawn from vertex A.

Solution. a) Formula (*) can be written as follows:

$$a^2 = (b - c)^2 + 2bc (1 - \cos A).$$

If $1 - \cos A$ is now replaced by $2\sin^2 \frac{A}{2}$, then we arrive at the following formula

$$a^2 = (b - c)^2 + 4bc \sin^2 \frac{A}{2}.$$ (2)

Then

$$a^2 \geqslant 4bc \sin^2 \frac{A}{2},$$

or

$$\sin \frac{A}{2} \leqslant \frac{a}{2\sqrt{bc}},$$

and equality is achieved only at $b = c$.

6) Formula (2) can easily be reduced to this form:

$$a^2 = (b - c)^2 + 4S \text{tg} \frac{A}{2}.$$ (3)

To do this, it is enough to perform the following transformations:

$$bc \sin^2 \frac{A}{2} = \frac{2S}{\sin A} \sin^2 \frac{A}{2} =$$

$$= \frac{2S\sin^2 \frac{A}{2}}{2\sin \frac{A}{2}\cos \frac{A}{2}} = S \text{tg} \frac{A}{2}.$$

Formula (3) implies the inequality $a^2 \geqslant 4S \text{tg} \frac{A}{2}$, whence $tg \frac{A}{2} \leqslant \frac{a^2}{4S}$.

Taking into account that $S = \frac{1}{2} ah_a$, we obtain the inequality $tg \frac{A}{2} \leqslant \frac{a}{2h_a}$.

From the above examples it is clear that the formula

$$a^2 = b^2 + c^2 - 2bc \cos A$$

using simple transformations to one of types 1-3. The following relations are derived similarly:

$$a^2 = (b + c)^2 - 4bc \cos^2 \frac{A}{2},$$ (4)

$$a^2 = (b + c)^2 - 4S \text{tg} \frac{A}{2}.$$ (5)

Let us now consider several problems that can be solved using formulas (1)–(5).

Example 4. Calculate the area of ​​a triangle given its sides.

⟦folio 31⟧

Solution. Let us rewrite correspondences (3) and (5) as follows:

$$4S \mathrm{tg} \frac{A}{2} = a^2 - (b - c)^2,$$
$$4S \mathrm{ctg} \frac{A}{2} = (b + c)^2 - a^2.$$

If the perimeter of a triangle is denoted by 2p, then
$$a^2 - (b - c)^2 = (a + b - c) \times (a + c - b) = 4(p - b) \times (p - c),$$
$$(b + c)^2 - a^2 = (a + b + c) \times (b + c - a) = 4p(p - a).$$

Hence,

$$S \mathrm{tg} \frac{A}{2} = (p - b)(p - c),$$
$$S \mathrm{ctg} \frac{A}{2} = p(p - a).$$

Variable these equalities term by term, we obtain Heron’s well-known formula for calculating the area of ​​a triangle

$$S^2 = p(p - a)(p - b)(p - c).$$

Example 5. Given an equilateral triangle ABC with side a. Through point M lying on side AB, straight lines are drawn parallel to sides AC and BC of the triangle, intersecting these sides at points K and L, respectively. Calculate the area of ​​the triangle KLM if KL = d (Fig. 2).

Solution. Let us denote the segments KM and LM by x and y, respectively. Triangles AKM and BLM are equilateral, therefore

![Рис. 2.](image)

Example 6. Divide this triangle into two equal parts using a segment of the shortest length.

Solution. Let the segment MN divide the area of ​​triangle ABC in half (Fig. 3). If points M and N lie on the sides of angle BAC and S is the area of ​​triangle ABC, then the area of ​​triangle AMN is equal to $\frac{1}{2}S$, and according to formula (3)

$$MN^2 = (AM - AN)^2 + 2S \mathrm{tg} \frac{A}{2},$$

From here we immediately find that for AM = AN the segment MN has the shortest length equal to $\sqrt{2S \mathrm{tg} \frac{A}{2}}$.

⟦folio 32⟧

Fig. 3.

The length of segment AM is easy to calculate since $S = AM^2 \sin A = \frac{1}{2} bc \sin A,$

where

$$AM = \sqrt{\frac{bc}{2}}.$$

It is clear that if the ends of the segment MN lie on the sides of angle B of the triangle, then the shortest length of this segment is $\sqrt{2S \mathrm{tg} \frac{B}{2}}.$

Let $a < b < c,$ then

$$\sqrt{2S \mathrm{tg} \frac{A}{2}} < \sqrt{2S \mathrm{tg} \frac{B}{2}} < \sqrt{2S \mathrm{tg} \frac{C}{2}}.$$

To Posny, the length of the minimal segment MN is equal to $\sqrt{2S \mathrm{tg} \frac{A}{2}}.$ At the same time $AM = AN = \sqrt{\frac{bc}{2}}.$

Constructing the segment MN is always possible; since $c < a + b < 2b,$ then $\sqrt{\frac{bc}{2}} < b$ and even more so $\sqrt{\frac{bc}{2}} < c.$

In conclusion, we present several problems that we present to the reader to solve independently.

1. On the sides of a triangle with angle $60^\circ$ there are equilateral triangles outside its construction. Prove that the sum of the areas of the given triangle and the triangle constructed on the side opposite the angle at $60^\circ,$ is equal to the sum of the areas of the two triangles.

2. On the sides of the triangle $ABC,$ the angle $C$ is equal to $135^\circ,$, outside it the squares $ABMN, BCKL$ and $CAPQ.$ are constructed. Prove that the area of ​​the hexagon $KLMNPQ$ is equal to twice the area of ​​the square $ABMN.$

3. Calculate the area of ​​the parallelogram $ABCD,$ if $AB=5, BC=2$ and the angle between its diagonals is $45^\circ.$

4. Express the trigonometric functions of the polyline angles of a triangle in terms of its sides.

5. Prove that the sides of the triangle $ABC$ satisfy the equality $a^2 + b^2 = 2c^2$ if and only if the angles of the triangle are related by the relations

$$\text{ctg} A + \text{ctg} B = 2 \text{ctg} C.$$

6. The sides of the triangle $ABC$ are connected by the dependencies $a^2 + b^2 = nc^2,$ where $n>1.$ Prove that $\cos C \geq \frac{n-1}{n}.$

7. Prove that the angles of any triangle satisfy the inequality.

$$\text{tg} \frac{A}{2} + \text{tg} \frac{B}{2} + \text{tg} \frac{C}{2} \leq \text{ctg} A + \text{ctg} B + \text{ctg} C.$$

8. An equilateral triangle with side $a.$ is inscribed in a circle. Prove that $x^2 + y^2 + z^2 = 2a^2,$ where $x, y, z$ are the distances from an arbitrary point on the circle to the vertices of the triangle.

9. A circle is inscribed in triangle $ABC$ and touches sides $AB$ and $AC$ at points $M$ and $N.$ Determine the angle $A$ of the triangle if $\frac{AM}{MB} = \frac{1}{6}$ and $\frac{AN}{NC} = \frac{1}{7}.$

10. Find the area of ​​the triangle $ABC,$ knowing the angle $A$ and the segments $m$ and $n,$ into which the tangent point of the inscribed circle divides the side $BC.$

11. Given a line $l$ and two points $A$ and $B,$ not lying on it. Find on the line $l$ the point $M,$ for which the ratio $\frac{AM}{BM}$ takes $a)$ the most value; $6)$ most meaning.

12. Prove that the angles of any triangle satisfy the inequality

$$\sin \frac{A}{2} \sin \frac{B}{2} \sin \frac{C}{2} \leq \frac{1}{8}.$$

13. A trapezoid with bases $a$ and $b$ ($a > b$) is described around a circle of radius $r$. Calculate the angle between its sides.

14*) Prove that for any triangle $ABC$ the following relation holds:

$$16S^2 = (a^2 + c^2 - b^2)(a^2 + b^2 - c^2) + (b^2 + c^2 - a^2)(a^2 + b^2 - c^2) + (b^2 + c^2 - a^2)(a^2 + b^2 - b^2).$$

*) This problem was sent by our reader V.P. Gasparin.
