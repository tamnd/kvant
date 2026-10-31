---
id: 1973-1-lopovok-vpisannyiy-shestiugolnik-2933f136
issue: kvant_1973_1
year: 1973
number: "1"
title: Inscribed hexagon
authors:
  - Лоповок Л. М.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 20
page_last: 24
page_labels: 18, 20, 21, 22
tag: J81S
lang: en
source: kvant_digital
extraction: vision
content_sha256: 42733569d7b2fecd6c1add1a1c6b32e08cd0409a3cf65e2a383f10dbaa9f44c1
prompt_sha256: draft-1
translated_from: content/ru/1973/01/articles/07_lopovok-vpisannyiy-shestiugolnik-2933f136.md
source_content_sha256: 3c034f901ccd5d3c983d5aac3a8d9824b6d53f2892a1a365b3a2669cea324c17
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 18⟧

In the “Mathematics circle” section we publish notes in which we are talking about tasks close to the cyclic program in mathematics. In general, these notes are structured as meanings of a mathematical circle: the cycle offers several places of dreug-related tasks. Some of them are solved in the text, while others - both lecture and more difficult - are left for independent solution.

As a rule, our “Mathematical Circle” is available in cycles, we are talking about regular hexagons. Meanwhile, an arbitrary convex hexagon in a circle deserves special attention, since it has a number of interesting properties.

More than 330 years ago, the famous French mathematician Blaise Pascal (then a 16-year-old boy) studied certain properties of a hexagon inscribed in a finite section (that is, a circle, ellipse, hyperbola or parabola). At the same time, he discovered the theorem that now bears his name: if a hexagon is inscribed in a finite section, then the points of intersection of its opposite sides (or their extensions) lie on the same straight line. Pascal carried out his research using the means of so-called projective geometry. We will consider the property of a convex hexagon inscribed in a circle. This simplification of the problem allows us to remain within the scope of elementary geometry.

Angles

The sums taken through one corner of an inscribed convex hexagon are equal to each other.

Let (Fig. 1) be a convex hexagon $A_1A_2A_3A_4A_5A_6$ inscribed in a circle. Let us denote its arcs $A_1A_2$, $A_2A_3$, ..., $A_6A_1$ of the corresponding arc by $2x_1$, $2x_2$, ..., $2x_6$. Then by the property of inscribed angles $\Rightarrow A_1=x_2+x_3+x_4+x_5$, $\Rightarrow A_3=x_1+x_4+x_5+x_6$, $\Rightarrow A_5=x_1+x_2+x_3+x_6$.

Because $\Rightarrow A_1+\Rightarrow A_3+\Rightarrow A_5=2x_1+2x_2+2x_3+2x_4+2x_5+2x_6=360^\circ$.

Since the sum of the interior angles of a convex hexagon is $720^\circ$, then $\Rightarrow A_2+\Rightarrow A_4+\Rightarrow A_6=360^\circ$.

⟦folio 20⟧

(obviously this can always be done).

Let $A_1A_2 \cdot A_3A_4 \cdot A_5A_6 = A_2A_3 \cdot A_4A_5 \cdot A_6A_1$; diagonals $A_1A_4$ and $A_2A_5$ intersect at point $M$, and diagonal $A_3A_6$ does not pass through this point (Fig. 3). Consider a hexagon $A_1A_2A_3A_4A_5B$ inscribed in the same circle, with the point $B$ lying at the intersection of the circle and the line $A_3M$; this hexagon has more and more diagonals passing through the point $M$.

Then, by the proven theorem
$$A_1A_2 \cdot A_3A_4 \cdot A_5B = A_2A_3 \times A_4A_5 \cdot BA_1.$$
Compare this equality with the conditions, we see that
$$\frac{A_5A_6}{A_5B} = \frac{A_6A_1}{BA_1}.$$
But if the point $B$ (lying between $A_5$ and $A_1$) lies between $A_5$ and $A_6$, then from the condition $\bigcup A_1A_5 < 180^\circ$ we obtain:
$$A_5B < A_5A_6, BA_1 > A_6A_1,$$
where
$$\frac{A_5A_6}{A_5B} > 1 > \frac{A_6A_1}{BA_1}$$

- strict inequality instead of equality. The case when the point $B$ lies between $A_1$ and $A_6$ is considered similarly. Therefore, the assumption that the third larger diagonal of the original hexagon does not pass through the point $M$ is incorrect.

Thus, the equality of products is the side of the convex

Fig. 4.

hexagon, taken through one, is a necessary and sufficient condition for the intersection of the large diagonals of the hexagon at one point.

Metric correspondence between the sides and major diagonals of an inscribed convex hexagon

The product of the major diagonals of an inscribed convex hexagon is equal to the sum of the products of its sides taken through one, and the products of its opposite sides by the major diagonal separating them (at figure 4 $xyz = abc + a_1b_1c_1 + aa_1x + bb_1y + cc_1z$).

As is known, the product of the diagonals of an inscribed quadrilateral is equal to the sum of the products of the opposite sides of the quadrilateral (Ptolemy's theorem).

The designations of all elements of the hexagon are given on figure 4. By Ptolemy’s theorem, from the quadrilateral $A_2A_3A_5A_6$ one finds
$$xy = cc_1 + de$$
And
$$xyz = cc_1z + dez.$$
But $e$ and $z$ are diagonals of the cyclic quadrilateral $A_1A_3A_4A_5$. Therefore $ez = fa_1 + gb$. Thus,
$$xyz = cc_1z + dfa_1 + dgb.$$

From the cyclic quadrilateral $A_1A_2A_3A_6$ one finds $df = ax + b_1c_1$, and from the quadrilateral $A_1A_2A_5A_6$:$dg = ac + b_1y$. Substituting these values, we obtain the required equality.

Calculating the diagonals of an inscribed convex hexagon along its sides is a very difficult task. Only in the case where the cyclic hexagon is half-right ($a = b = c, a_1 = b_1 = c_1$) is the solution simple. Since all angles of such a hexagon are equal to $120^\circ$, the minor diagonal is defined as the third side of the triangle whose two sides are equal to $a$

⟦folio 21⟧

Fig. 5.
and $a_1$, and the angle between them is $120^\circ$. Therefore, $\alpha = \sqrt{a^2 + aa_1 + a_1^2}$. The major diagonal is the base of a trapezoid, the sides of which are equal and form angles of $60^\circ$ with the base. Such a trapezoid has a larger base equal to the sum of the second base and the side, that is
$$x = a + a_1.$$

Some points

We will need one property of a triangle - Menelaus' theorem.

Let a straight line not passing through the vertex of triangle ABC intersect its sides AB, BC, CA or their extensions of the corresponding points C$_1$, A$_1$ and B$_1$ (an example of such a configuration is given in figure 5); moeda

$$\frac{AC_1}{BC_1} \cdot \frac{BA_1}{CA_1} \cdot \frac{CB_1}{AB_1} = 1.$$

It is also easy to prove the validity of Menelaus' theorem in the case when the line intersects only the continuation side of the triangle - do it yourself.

Let a convex hexagon hang in a circle and extend its corresponding extension at points K, L and M (Fig. 6). Then points K, L and M lie on the same line.

The extensions of the side $A_1A_2$, $A_3A_4$ and $A_5A_6$ intersect at points B, C and D. The distance of the intersection of the triangle BCD by the lines $KA_2A_3$, $LA_5A_4$, $MA_6A_1$ (the techniques are written not with two points, as usual, but with trays to show the point at which the line intersects the continuation

⟦folio 22⟧

Fig. 7.

below the corresponding side of triangle BCD). According to Menelaus’ theorem for these lines we have:

$$\frac{BA_2}{A_2D} \cdot \frac{DK}{KC} \cdot \frac{CA_3}{A_3B} = -1;$$

$$\frac{BL}{LD} \cdot \frac{DA_5}{A_5C} \cdot \frac{CA_4}{A_4B} = -1;$$

$$\frac{CM}{MB} \cdot \frac{BA_1}{A_1D} \cdot \frac{DA_6}{A_6C} = -1.$$

Variable these equalities, we get:

$$\frac{BL \cdot DK \cdot CM}{LD \cdot KC \cdot MB} \times$$

$$\times \frac{BA_2 \cdot CA_3 \cdot DA_5 \cdot CA_4 \cdot BA_1 \cdot DA_6}{A_2D \cdot A_3B \cdot A_5C \cdot A_4B \cdot A_1D \cdot A_6C} = -1.$$

(*)

By the property of secants drawn to a circle from one point, $BA_1 \cdot BA_2 = BA_3 \cdot BA_4; CA_3 \cdot CA_4 = CA_5 \cdot CA_6; DA_5 \cdot DA_6 = DA_1 \cdot DA_2$.

Therefore the second fraction in (*) is equal to 1. Thus,

$$\frac{BL}{LD} \cdot \frac{DK}{KC} \cdot \frac{CM}{MB} = -1.$$

And this, as we know, proves that points K, L and M lie on the same line.

The intersection point of diagonals $A_1A_3$ and $A_2A_4$, $A_2A_5$ and $A_3A_6$, $A_1A_5$ and $A_4A_6$ (Fig. 7) also lie on the same straight line.

To prove it, he uses the theorem of sines (the sides of a triangle proportional to the sines of opposite angles) and the theorem inverse to Menelaus’ theorem for the triangle $A_1A_3E$ and points B, C, D:

$$\frac{A_1B}{BA_3} = \frac{A_1B}{A_2B} \cdot \frac{A_2B}{BA_3} =$$

$$= \frac{\sin(x_4 + x_5 + x_6)}{\sin x_2} \cdot \frac{\sin x_1}{\sin x_3};$$

$$\frac{A_3C}{CE} = \frac{A_3C}{CA_5} \cdot \frac{CA_5}{CE} =$$

$$= \frac{\sin x_2}{\sin x_5} \cdot \frac{\sin(x_3 + x_4 + x_6)}{\sin x_1};$$

$$\frac{ED}{DA_1} = -\frac{ED}{A_1D} =$$

$$= -\frac{ED}{DA_6} \cdot \frac{DA_6}{A_1D} = -\frac{\sin x_3}{\sin(x_1 + x_2 + x_5)} \times \frac{\sin x_5}{\sin(x_1 + x_2 + x_3)}.$$

Variable these equalities, we get:

$$\frac{A_1B}{BA_3} \cdot \frac{A_3C}{CE} \cdot \frac{ED}{DA_1} =$$

$$= -\frac{\sin(x_3 + x_4 + x_6)}{\sin(x_1 + x_2 + x_3)} \cdot \frac{\sin(x_4 + x_5 + x_6)}{\sin(x_1 + x_2 + x_5)}.$$

Since $x_1 + x_2 + x_3 + x_4 + x_5 + x_6 = 180^\circ$, then

$$\sin(x_1 + x_2 + x_3) = \sin(x_4 + x_5 + x_6)$$

And

$$\sin(x_1 + x_2 + x_5) = \sin(x_3 + x_4 + x_6)$$

Hence,

$$\frac{A_1B}{BA_3} \cdot \frac{A_3C}{CE} \cdot \frac{ED}{DA_1} = -1.$$

And this proves that points B, C and D lie on the same line.

Similarly, it can be shown that the intersection points of diagonals $A_1A_3$ and $A_2A_6$, $A_3A_5$ and $A_4A_6$, $A_1A_4$ and $A_2A_5$, as well as the intersection points of diagonals $A_1A_5$ lie on the same straight line
