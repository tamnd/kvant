---
id: 1991-10-ponarin-garmonicheskiy-chetyirehugolnik-ea9f279f
issue: kvant_1991_10
year: 1991
number: "10"
title: Harmonic quadrilateral
authors:
  - Понарин Я. П.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 50
page_last: 54
page_labels: 48-52
lang: en
source: kvant_digital
extraction: vision
content_sha256: df0a8fefbe3da54dc93825931ff3d9dd797cf1742150c403cc0ad580340395ef
prompt_sha256: draft-1
translated_from: content/ru/1991/10/articles/15_ponarin-garmonicheskiy-chetyirehugolnik-ea9f279f.md
source_content_sha256: a8db9df0b6a7c3d331af97a6fe4e6917516c9e5c1e78ce8367281b69cabd83e2
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 48⟧

---
running_head:
folio:
---

= $\frac{AM}{MB}$, with $\lambda > 0$ if the vectors $\vec{AM}$ and $\vec{MB}$ are coincident, and $\lambda < 0$ if their directions are opposite (you can easily see that this relation can be treated like ordinary fractions).*)

If the given points are $A$ and $B$ and $\lambda = \frac{AM}{MB} \neq -1$, then the point $M$ is uniquely defined. Indeed, let us assume that we find two points $M$ and $N$ such that

$$\frac{AM}{MB} = \frac{AN}{NB}.$$

Let's add one to both sides of this equality:

$$\frac{AM}{MB} + \frac{MB}{MB} = \frac{AN}{NB} + \frac{NB}{NB}.$$

Then

$$\frac{AM}{MB} + \frac{MB}{MB} = \frac{AN}{NB} + \frac{NB}{NB},$$

i.e.

$$\frac{AB}{MB} = \frac{AB}{NB},$$

Means,

$$\overrightarrow{MB} = \overrightarrow{NB} \text{ и } M = N.$$

It is common to say that the point $M$ divides the segment $AB$ in relation to $\lambda$. Note that a point can divide a segment while being outside it!

For $\lambda > 0$, the point $M$ belongs to the segment $AB$, and for $\lambda < 0$ it is located outside it on the straight line $AB$. In particular, if $\lambda = 1$, then $M$ is the middle of $AB$; if $\lambda = -1$, this means that $\overrightarrow{AM} = -\overrightarrow{MB}$, i.e. points $A$ and $B$ coincide. Therefore, $\lambda = -1$ should be excluded by us (if $A$ and $B$ coincide, the point $M$ is given incompletely).

About the limit. An ordered quadruple of points on a line ($A, B; C, D$) is called a harmonic if the point

*) To distinguish the ratio of directed segments from the ratio of their lengths, we will put a line above the designation of the segment as a sign that a direction is given on it.

⟦folio 49⟧

---
running_head:
folio:
---

Books C and D divide segment AB in relations that differ only in sign:

$$\frac{AC}{CB} = -\frac{AD}{DB}.$$ In this case, the pair of points A, B is called basic, and the pair C, D is called dividing.

However, the basis and dividing pairs can be reversed, since if $$\frac{AC}{CB} = -\frac{AD}{DB},$$ then also $$\frac{CA}{AD} = -\frac{CB}{BD}.$$ In other words, if the ordered four (A, B; C, D) is harmonic, then the ordered four (C, D; A, B) will also be harmonic.

Check for yourself that the harmony of the four points will be preserved if you change the order of the points in the basic or dividing pair.

Harmonic quadruples of dots are quite common, although you may not have replaced them. Here is one example. Let a triangle ABC be given and the bicsectrices of its internal and external angles at vertex C intersect the straight line AB at points M and N (Fig. 2). Then the ordered quadruple (A, B; M, N) is harmonic, since, as is known,

$$\frac{AM}{MB} = \frac{AC}{BC} \text{ и } \frac{AN}{NB} = -\frac{AC}{BC}.$$

Exercise. Prove that the harmonic quadruple (A, B; C, D) is completely determined by its third points.

figure 3 shows how to construct the fourth point, D, from those of the others. Here, through points A and B, two straight lines parallel to each other are arbitrarily drawn, and through point C, a straight line is drawn, intersecting them at points P and Q, respectively. Point S on line BQ is such that QB=BS. Then the point of intersection of lines PS and AB is the required one.

Exercise. Prove that the point constructed in this way is indeed the missing point of the harmonic quadruple.

The same construction allows us to find the missing point D in the case when point C is located outside the segment AB (Fig. 4).

Exercise. Find the gap in the construction method described above (hint: remember that the value $\lambda = -1$ is missing).

Now everything is ready to present to you

Harmonic quadrangle

Determined. A quadrilateral inscribed in a circle is called harmonic if the product of the lengths of its opposite sides are equal.

⟦folio 50⟧

---
running_head:
folio:
---

From this definition, the connection between the harmonic quadrilateral and the harmonic quadrangles of points is not yet clear. It will become clear below.

An obvious example of a harmonic quadrilateral is the inscribed deltode (Fig. 5), a quadrilateral with perpendicular diagonals, one of which bisects the other. In particular, it can be a square.

Another particular type of harmonious quadrilateral is the harmonic trapezoid (Fig. 6). It is clear that it is equilateral. Let $AB$ and $CD$ be the bases of the harmonic trapezoid $ABCD$. Let's denote $AB=a$, $CD=b$, $AD=BC=c$, $AC=BD=d$. According to the definition of a harmonic quadrilateral $ab=c^2$, i.e., the lateral side of a harmonic trapezoid is the geometric mean of its bases. In addition, in any cyclic quadrilateral, the product of the lengths of the diagonals is equal to the sum of the products of its opposite sides (Ptolemy's theorem*)). Therefore, $d^2=ab+c^2$ and, therefore, $d^2=2c^2$, whence $d=c\sqrt{2}$, i.e., the diagonal of a harmonic trapezoid with side side $c$ is equal to the diagonal of a square with side side $c$. If the circumcircle has radius $R$, then $d<2R$, therefore $c<R\sqrt{2}$ (in case of equality $c=R\sqrt{2}$ the trapezoid becomes an inscribed square).

Thus, a harmonic trapezoid can be defined by two bases $a$ and $b$, from which the lateral side and diagonal are simply constructed. It can also be specified by the radius of the circumscribed circle and the side edge, with the help of which all other elements can be easily found.

Let's now consider

General properties of harmonic quadrilaterals

Let us agree to say that in the quadrilateral $ABCD$ the sides $AB$ and $BC$

*) See, for example, «Kvant», 1991, No. 4, p. 42.

adjacent to the diagonal $AC$. Sides $AD$ and $DC$ are also adjacent to it.

Theorem 1. In a harmonic quadrilateral, each of the diagonals is divided by the point of their intersection in relation to the squares of the adjacent side.

Indeed, consider the harmonious quadrilateral $ABCD$. Let $M$ be the intersection point of its diagonals (Fig. 7). Triangles

⟦folio 51⟧

---
running_head:
folio:
---

$$AM \cdot MC = BM \cdot MD$$ and $$\frac{BM}{MC} = \frac{AB}{CD}.$$

From the similarity of triangles AMD and BCM we also have
$$\frac{MD}{MC} = \frac{AD}{BC}.$$

Variable obtained proportions term by term:
$$\frac{BM \cdot MD}{MC^2} = \frac{AD \cdot AB}{BC \cdot CD}.$$

But $AM \cdot MC = BM \cdot MD$ therefore
$$\frac{AM \cdot MC}{MC^2} = \frac{AD \cdot AB}{BC \cdot CD},$$
or
$$\frac{AM}{MC} = \frac{AD \cdot AB}{BC \cdot CD}.$$ (*)

Since the quadrilateral ABCD is harmonic, then $AD \cdot BC = AB \cdot CD$, whence
$$CD = \frac{AD \cdot BC}{AB}.$$

Substituting this expression into (*), we get
$$\frac{AM}{MC} = \frac{AD \cdot AB}{BC} \cdot \frac{AB}{AD \cdot BC} = \frac{AB^2}{BC^2}.$$

Likewise
$$\frac{AM}{MC} = \frac{AD^2}{DC^2}$$ and $$\frac{BM}{MD} = \frac{BC^2}{CD^2} = \frac{AB^2}{AD^2}.$$

Comment. It is known that the straight line passing through the vertex of a triangle and dividing its opposite side in relation to the squares of the adjacent sides is symmetry to the median relative to the bisector of the angle at this vertex. It is called the simedian of the triangle*).

Theorem 2. Two opposite vertices of a harmonious quadrilateral, the point of intersection of its diagonals and the point of intersection of straight lines.
*) You can read more about this in the book by S.I. Zetel “New Geometry of the Triangle” (Uchredgiz, 1962, pp. 100-103).

mine, containing these vertices, with a tangent to the circumcircle at the third vertex form a harmonious quadrangular four-duck of points.

In fact, the empty tangent at vertex B intersects the line AC at point P (Fig. 8). Then $\angle BAC = \angle CBD$ (to be convinced of this, it is enough to remember that the vertical angle is equal to half the central one, based on the same arc); therefore, triangles BCP and BAP are similar. Pozotomu
$$AP \cdot PC = BP^2$$
And
$$\frac{BP}{PC} = \frac{AB}{BC}.$$

Dividing both sides of the first equality by $PC^2$, we get
$$\frac{AP}{PC} = \frac{BP^2}{PC^2}$$

and therefore
$$\frac{AP}{PC} = \frac{AB^2}{BC^2}.$$

If we now apply Theorem 1 for a harmonious quadrilateral and take into account the direction of the vectors, we finally obtain: $$\frac{AM}{MC} = -\frac{AP}{PC}$$. Points M and P divide segment AC into

⟦folio 52⟧

---
running_head:
folio:
---

and externally in equal abscylotic magnitude relationships.

Consequence. The tangent circles to the circumscribed circle of a harmonic quadrangle at its opposite vertices intersect on a straight line containing its diagonal, or parallel to this diagonal.

Indeed, if a tangent is drawn at the vertex $D$, then, according to Theorem 2, it will intersect the line $AC$ at a point that, together with the same points $A, C, M$, constitutes a four-unit harmonic. This property, of course, also holds for the tangents at the vertices $A$ and $C$. The parallelism of tangents and diagonals occurs in the case of a divisor.

Theorem 3. If the tangents at the ends of one diagonal of an inscribed quadrilateral intersect on a line containing the second diagonal, or are parallel to it, then this quadrilateral is harmonic.

Indeed, the proof of Theorem 2 yielded the equality $\frac{AP}{PC} = \frac{AB^2}{BC^2}$, which is true for any cyclic quadrilateral $ABCD$. By condition, the tangent at the point $D$ intersects $AC$ at the same point $P$, therefore also $\frac{AP}{PC} = \frac{AD^2}{DC^2}$. Therefore, $\frac{AB}{BC} = \frac{AD}{DC}$, i.e., the quadrilateral $ABCD$ is harmonic.

This theorem is the basis for the method of constructing a harmonious quadrilateral $ABCD$ given the vertices $A, B$ and $C$.

We describe a circle around the triangle $ABC$ and draw a tangent to it through the vertex $B$. If the segments $AB$ and $BC$ are not equal, then it will intersect the line $AC$ at some point $P$. Now just draw the second tangent to our circle through $P$, and we will get the missing vertex of the harmonious quadrilateral. If $AB=BC$ and the tangent at the point $B$ is parallel to $AC$, this means that the required quadrilateral is a divisor, therefore ver-
bus $D$ is the point of intersection of the middle perpendicular to $AC$ with the circle. In the general case, you can do it a little differently: if $K$ is the point of intersection of the tangents at the given vertices $A$ and $C$, then vertex $D$ is the second point of intersection of the line $BK$ with the circle.

Theorem 4. In a harmonic quadrilateral, the distances from the point of intersection of the diagonals do of the sides are proportional to the lengths of these sides.

Take a look at figure 9. Let us denote the distances of the point $M$ to the lines $AB, BC, CD, DA$ of the corresponding $h_1, h_2, h_3, h_4$. The ratio of the areas of triangles $AMB$ and $BMC$ is $AM:MC$. On the other hand, the ratio of these same areas is $\frac{AB \cdot h_1}{BC \cdot h_2}$. By Theorem 1 $\frac{AM}{MC} = \frac{AB^2}{BC^2}$ and therefore $h_1:h_2 = AB:BC$. Similar to $h_2:h_3 = BC:CD$ and $h_3:h_4 = CD:DA$.

In conclusion, one more note. Four complete numbers $a, b, c, d$ form a harmonious quadrilateral if

$$\frac{a-b}{b-c} = -\frac{a-d}{d-c}.$$

The next issue of our magazine for this year describes an article by Yu. Solovyov on complete numbers, where, in particular, their geometric representation is described. Each of the numbers $a, b, c, d$ corresponds to a point on the plane $A, B, C, D$. If the complete numbers form a harmonious quadrilateral, then $ABCD$ is a harmonious quadrilateral, and vice versa.
