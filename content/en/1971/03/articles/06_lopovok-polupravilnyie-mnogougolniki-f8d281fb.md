---
id: 1971-3-lopovok-polupravilnyie-mnogougolniki-f8d281fb
issue: kvant_1971_3
year: 1971
number: "3"
title: Semiregular polygons
authors:
  - Лоповок Л. М.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 27
page_last: 29
page_labels: 25-27
tag: L1DJ
lang: en
source: kvant_digital
extraction: vision
content_sha256: b8499b329d6ca3494a827b88e6afab5ad404b9718791f1f79b3665b2adbd0d74
prompt_sha256: draft-1
translated_from: content/ru/1971/03/articles/06_lopovok-polupravilnyie-mnogougolniki-f8d281fb.md
source_content_sha256: 5dc29cfc0dbf733c6d8216c8650467ffb38d5506ef29042f23f76616dec5dd29
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 25⟧

SEMI-CORRECT

L. M. Lopovok POLYGONS

By definition, a convex polygon is called regular if it is equiangular and equilateral. However, there is an interesting class of figures that do not possess these two properties at the same time. We will call half-right and the following polygons:

a) equiangular, in which the sides are equal through one;
b) equilateral, in which the angles are equal through one.

An example of a semi-right polygon of the first kind is a rectangle, and an example of the second is a rhombus. From the description of half-right polygons it is clear that each of them has an even number of vertices; let's denote it by $2n$.

Properties of half-right equiangular polygons

1. Opposite sides of an equiangular polygon are parallel.

Indeed, when traversing the polygon, we replace that each side is rotated relative to the previous one by an external angle, that is, by $\frac{180^\circ}{n}$ (Fig. 1). Therefore, side $A_{n+1}A_{n+2}$ is rotated relative to side $A_1A_2$ by the amount of $n$ external angles, that is, by $180^\circ$.

2. If you connect the vertices of a half-right equiangular polygon through one (all odd or all even vertices), you get a regular polygon (Fig. 1).

The proof is not difficult: the triangles $A_1A_2A_3$, $A_3A_4A_5$, $A_5A_6A_7$, ... are equal according to the first criterion, which means $A_1A_3=A_3A_5=\dots$. On the other hand, from the equality of triangles it follows that their corresponding angles are equal. Let us denote the interior angle of an equal $2n$-gon by $\alpha_{2n}$. We find the interior angles of our best polygon: they are equal

$$\alpha_{2n} - (\beta + \gamma) = \alpha_{2n} - (180^\circ - \alpha_{2n}) =$$

$$= 2\alpha_{2n} - 180^\circ = 2 \cdot 180^\circ \left( 1 - \frac{1}{n} \right) -$$

$$- 180^\circ = 180^\circ \left( 1 - \frac{2}{n} \right),$$

Fig. 1.

4. Quantum No. 3

⟦folio 26⟧

as it should be for a regular $n$-gon.

3. A circle can be described around a semi-regular equiangular polygon.

Let us describe a circle around the regular $n$-gon $A_1A_3A_5\dots$ (Fig. 2). The interior angle of an equiangular $2n$-gon is $180^\circ \left(1 - \frac{1}{n}\right)$. It is easy to calculate that $\Rightarrow A_1A_2A_3$ is half the degree value of the arc $A_3A_5A_1$, which means that point $A_2$ lies on the constructed circle. This also applies to other vertices: $A_4$, $A_6$,...

Property 3 is based on two methods for constructing semiregular equiangular polygons.

a) Construct a regular $n$-gon $A_1A_3A_5\dots A_{2n-1}$ and describe a circle around it. Then we find (using a compass) on the circle the points $A_2$, $A_4$, $A_6$,..., $A_{2n}$, located at the same distance from the corresponding vertices of the $n$-gon: $A_1A_2=A_3A_4=..$

b) We construct a triangle $A_1A_2A_3$ using two sides (of arbitrary length) and a known angle between them, and describe a circle around this triangle. Then, knowing the sizes of all sides, we successively find the remaining vertices using the notches of a compass.

4. If the number of vertices of a semiregular equiangular polygon is a multiple of 4, then more diagonals intersect at one point and bisect it.

To prove use 2: these diagonals are also the diagonals of a regular polygon with side four, so they intersect at one point—the center of the polygon's circumscribed circle—and are bisected by that point.

If the number of vertices of a semiregular equiangular polygon is not a multiple of 4, then it is not difficult to construct an example (Fig. 3), when more diagonals intersect at several points.

5. The center of a circle circumscribed about a semiregular equiangular $4n$-gon is its symmetrical center.

From property 4 it follows that with central symmetry with respect to the circle, the vertices of the polygon transform into vertices; therefore, the parties also change sides.

6. The straight line passing through the midpoints of two parallel sides of a semiregular equiangular polygon is its symmetrical axis.

According to the property of parallel chords of a circle, this straight line passes through the center of the circumscribed circle. From the equality of the corresponding chords on both sides of the line, the symmetry of the corresponding vertices follows

⟦folio 27⟧

A polygon with respect to a drawn line (see further Fig. 6).

7. Let a semiregular equiangular polygon have 2n vertices, then the center of the circle circumscribed around it is its symmetric center of order n.

This means that when rotated around the center of the circle by an angle that is a multiple of $\frac{360^\circ}{n}$, the polygon aligns with itself. This follows from properties 2 and 3.

8. The sum of the distances from the interior point to the sides (or their extensions) of a semi-regular equiangular polygon is constructed.

As is known, a semiregular polygon has this property.

If you connect the interior point of the equigon with the vertices, then the sum of the areas of the resulting triangles is equal to the area of ​​the polygon. Denoting the side of the polygon by $a$, and the distance to the side by $x_0, x_1, x_2, x_3, \dots$, we obtain

$$S = \frac{ax_0}{2} + \frac{ax_1}{2} + \frac{ax_2}{2} + \frac{ax_3}{2} + \dots;$$

$$x_0 + x_1 + x_2 + x_3 + \dots = \frac{2S}{a} = \text{const.}$$

Let the side $A_1A_2$ be larger than the side $A_2A_3$ in a given polygon. Let us construct a regular 2n-gon (Fig. 4) on $A_1A_2$. Then all the sides of the original polygon (except three) are respectively parallel to the sides of the regular polygon, and three ($A_1A_2$ and funny with it) lie on the sides of the regular polygon. Therefore, the distances from the internal point $M$ to the side of the correct polygon are as follows:

$$x_0 = y_0, \ x_1 = y_1, \ x_2 = y_2, \ x_3 = y_3 + b_1,$$

$$x_4 = y_4 + b_2, \ x_5 = y_5 + b_3, \dots,$$

where $b_1, b_2, b_3$ are constant, and the required sum

$$y_0 + y_1 + y_2 + y_3 + y_4 + \dots = (x_0 + x_1 + x_2 + x_3 + x_4 + \dots) - (b_1 + b_2 + \dots) = \text{const.}$$

9. If you connect the sides of an equiangular equilateral polygon in series, you get a semi-regular equilateral polygon.

Indeed, by Property 2, all small diagonals of a semiregular equiangular polygon are equal to each other. The sides of the equigon (Fig. 5) are half the size of these diagonals, since it is the average of the linear triangles $A_1A_2A_3, A_2A_3A_4, A_3A_4A_5, \dots$. Using property 7, it is easy to install
