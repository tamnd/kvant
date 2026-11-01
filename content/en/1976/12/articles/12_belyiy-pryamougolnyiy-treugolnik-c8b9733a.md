---
id: 1976-12-belyiy-pryamougolnyiy-treugolnik-c8b9733a
issue: kvant_1976_12
year: 1976
number: "12"
title: Right triangle
authors:
  - Белый С. Б.
rubric: raznoe
rubric_sub: Разное
page_first: 52
page_last: 55
page_labels: 50-53
tag: 9U0J
lang: en
source: kvant_digital
extraction: vision
content_sha256: 0344fbda37f9d21a2601d8d09fc8476ad5fa7f431e09665d5746c19cb41a74c1
prompt_sha256: draft-1
translated_from: content/ru/1976/12/articles/12_belyiy-pryamougolnyiy-treugolnik-c8b9733a.md
source_content_sha256: 80317ad1306cbbd8fe76f56f8979c2a2ca3f6831412e8ba7b54c4b6b67b06e43
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 50⟧

S. Belie

Right Triangle

In entrance exams in mathematics, problems involving right-angled triangles are often offered. What do you need to know about a right triangle, besides the Pythagorean theorem, in order to successfully solve such problems? This is what will be discussed in this article.

Stated 1. Values ​​the circle circumscribed about a right triangle coincides with the midpoint of one.

This leads to the following relationship:

$$m = R = \frac{c}{2},$$

where $m$ is the length of the median drawn to the hypotenuse, $R$ is the radius of the circumscribed circle, $c$ is the hypotenuse (see Fig. 1 - it will help you prove this statement).

This relation is often used when solving a problem.

Example 1 (MSU, Faculty of Chemistry, 1974). In a right triangle ABC with legs 3 and 4 (cm), vertex C of the right angle is connected to the middle D unit AB. Find the distance between the centers of the circles described in the rectangle ACD and BCD.

By Statement 1, point D is the center of the circumscribed circle, therefore $|DA| = |DC| = |DB|$. Therefore, triangles ACD and BCD are isosceles (see Fig. 2). The centers of the circles described in

⟦folio 51⟧

Example 3 (MSU, Faculty of Chemistry, 1973). A square is inscribed in a right triangle ABC such that two of its vertices lie on the sinomenuze, and the other two on the kamets. The radius of the circle circumscribed about triangle ABC is related to the radius of the square as 13:6. Find the corners of triangle ABC.

Let $\hat{A} = \alpha$, denote the side of the square by $a$ (see Fig. 4). Then $|AB| = a \text{ctg}\alpha + a + a \text{tg}\alpha$, and

$$\frac{a \text{ctg}\alpha + a + a \text{tg}\alpha}{2a} = \frac{13}{6},$$

from where $\text{ctg}\alpha + \text{tg}\alpha + 1 = 13/3$, $3 \text{tg}^2\alpha - 10 \text{tg}\alpha + 3 = 0$, $\alpha_1 = \text{arctg} 3$, $\alpha_2 = \text{arctg} 1/3$. But angles $\alpha_1$ and $\alpha_2$ complement each other in a straight line. Thus, the angles of triangle ABC are $\text{arctg} 3, \frac{\pi}{2}, \text{arctg} 1/3$.

Statement 2. The height drawn from the vertex of a right angle of a triangle, we divide it into two sub-right triangles, one of which is similar to the given one.

The following relations follow from this statement (for notation, see Fig. 5):

$$h^2 = a'b', a^2 = a'c, b^2 = b'c,$$

$$a^2 + b^2 = c^2, \frac{a^2}{b^2} = \frac{a'}{b'}.$$

Let's add to them the formulas for calculating the area of ​​a right triangle:

$$S = \frac{1}{2}ab = \frac{1}{2}ch = mh = Rh.$$

Example 4 (MIPT, 1962). In a right triangle ABC, the altitude CD is drawn from the vertex of the right angle C. It is known that the radii of the circles described in triangle ACD and BCD are equal to $r_1$ and $r_2$. Find the radius of the circle circumscribed by triangle ABC.

⟦folio 52⟧

Fig. 6.

According to Statement 2, triangles ADC, CDB and ACB are similar (see Fig. 6). And in similar triangles, the radii of the inscribed circles (as well as any other corresponding linear elements) are related as corresponding sides. Then

$$\frac{|AC|}{r_1} = \frac{|BC|}{r_2} = \frac{|AB|}{r} = k.$$

From here, using the Pythagorean theorem, we get:

$$r_1^2 k^2 + r_2^2 k^2 = r^2 k^2, r^2 = r_1^2 + r_2^2, r = \sqrt{r_1^2 + r_2^2}.$$

Comment. The resulting formula $r^2 = r_1^2 + r_2^2$ is of a general nature: for any corresponding linear elements $x, y, z$ of triangles ADC, CDB, ACB (Fig. 6) the dependence $x^2 + y^2 = z^2$ is valid.

To prove this statement, it is enough to substitute $x, y, z$ together with $r_1, r_2, r$.

Example 5 (MIPT, 1969). In a right triangle, the bissertis CD of the right angle C is drawn. It is known that $|AD| = m, |BD| = n$. Find the height dropped from the vertex of angle C.

Let $x$ and $y$ be the lengths of the projections of the legs onto the hypotenuse (Fig. 7). Then

$$\frac{x}{y} = \frac{|AC|^2}{|BC|^2}.$$

But

$$\frac{|AC|}{|BC|} = \frac{|AD|}{|BD|} = \frac{m}{n}$$

(according to the property of bissertitsa). The result is a system

$$\begin{cases} x + y = m + n, \\ \frac{x}{y} = \frac{m^2}{n^2}. \end{cases}$$

Finding from this system $x$ and $y$, we determine the height using the formula $h = \sqrt{xy}$:

$$h = \frac{mn(m + n)}{m^2 + n^2}.$$

Statement 3 (converse to the Pythagorean theorem). If in a triangle the square of one side is equal to the sum of the squares of the other two sides, then it is a right angled triangle.

This statement follows from the cosine theorem, and in some cases it can be very useful.

Example 6. Let $a, b$ be the comets of right angled triangle ABC, $c$ the hypotenuse, $h$ the length of the altitude dropped from vertex C. Prove that the triangle on side $h, c + h, a + b$ is a right angled triangle.

It's easy to check that $(a + b)^2 + h^2 = (c + h)^2$, since this is creamy equal to $ab = ch$. This is where the statement of the problem follows.

The well-known formula is $r = \frac{S}{p}$ (or $S = pr$), where $S$ is the area of ​​the triangle, $p$ is the semiperimeter, $r$ is the radius of the inscribed circle. For a right angled triangle, the radius of the inscribed circle can be calculated using a simpler formula:

$$r = \frac{a + b - c}{2}.$$

Note also the formula

$$2r + 2R = a + b$$

(the last two formulas are equivalent). Try to prove these formulas yourself.

⟦folio 53⟧

Example 7 (MSU, Faculty of Chemistry, 1974). In a right triangle ABC with squares $|AC| = 3$ and $|BC| = 4$ the altitude CD is drawn. The name is consideration between the centers of a circle inscribed in triangles ACD and BCD.

Let $r_1$ and $r_2$ be the radii of the circle inscribed in triangles ACD and BCD, respectively (Fig. 8). Then
$$|O_1O_2| = \sqrt{(r_1 + r_2)^2 + (r_1 - r_2)^2} = \sqrt{2} \cdot \sqrt{r_1^2 + r_2^2}.$$
But $\sqrt{r_1^2 + r_2^2} = r$, where $r$ is the radius of the circle inscribed in triangle ABC (see example 4), therefore
$$|O_1O_2| = \sqrt{2} \cdot r = \sqrt{2} \cdot \frac{|BC| + |AC| - |AB|}{2} = \sqrt{2}.$$
And finally, here is one more statement that can also be useful for solving problems.

Statement 4. In a rectilinear triangle with unequal squares, the bisector of the right angle is divided in half by the angle between the altitude and the median drawn from the vertex of the same angle.

The proof of this statement is clear from figure 9.

Example 8 (MSU, VMK, 1973). In a right triangle ABC, the length of the altitude lowered to the zinometus is $a$, the bisector of the right angle is $b$. Name the area of ​​triangle ABC.

Let's take the median CM (see Fig. 9) and set $\widehat{DCL} = \alpha$; then, according to Statement 4, and $\widehat{LCM} = \alpha$. Next, $\cos \alpha = \frac{a}{b}$, $\cos 2\alpha = 2\cos^2\alpha - 1 = \frac{2a^2 - b^2}{b^2}$, $|CM| = \frac{a}{\cos 2\alpha} = \frac{ab^2}{2a^2 - b^2}$.

Now you can find the area of ​​triangle ABC:
$$S = |CD| \cdot |AM| = |CD| \cdot |CM| = \frac{a^2 b^2}{2a^2 - b^2}.$$
You have probably already noticed that all the problems discussed above were solved using the algebraic method. This is not surprising, since the above formulas represent a powerful arsenal for composing all possible equations. However, you should not think that all problems on right triangles can be solved algebraically - sometimes it is useful to make some additional constructions first.

Example 9 (MIPT, 1971). A circle is circumscribed about a right triangle ABC. The distances from the ends of the methus AB to the straight line tangent to the circle at point C are equal to m and n, respectively. The names of the comets are $|AC|$ and $|BC|$.

Let us draw the height CD (see Fig. 10) and note that $\widehat{ACD} = \widehat{ABC} = \widehat{ACE}$ (the last two angles are changed by the position of the same arc AC). Therefore, triangles AEC and ADC are confluent (by hypotenuse and acute
