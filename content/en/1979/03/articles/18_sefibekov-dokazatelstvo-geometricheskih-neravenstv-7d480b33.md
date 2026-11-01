---
id: 1979-3-sefibekov-dokazatelstvo-geometricheskih-neravenstv-7d480b33
issue: kvant_1979_3
year: 1979
number: "3"
title: Proof of geometric inequalities
authors:
  - Сефибеков С. Р.
rubric: raznoe
rubric_sub: Разное
page_first: 53
page_last: 55
page_labels: 51, 53
tag: EXHL
lang: en
source: kvant_digital
extraction: vision
content_sha256: 771d80f7601df7d4bee2f5c2308592b2b43e1d9189f2fce6edde1dd4b6e5e72a
prompt_sha256: draft-1
translated_from: content/ru/1979/03/articles/18_sefibekov-dokazatelstvo-geometricheskih-neravenstv-7d480b33.md
source_content_sha256: 6b546bab066a8d5115575709b6ad8a6ba1f7238474d34ee2d01e11d776eeea17
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 51⟧

S. Sefibekov

Proof of geometric inequalities

In mathematical problems, the following example is often useful: finding the same quantity in two ways and equating the expressions obtained for it. Let us, for example, find the area of ​​a certain figure in two ways. If one of the expressions for the area includes, say, the sine of some angle $\alpha$, then using the correspondence $\sin \alpha \leq 1$ from the resulting equality we can obtain some interesting inequality. In the article by S. Sefibekov, this example was used throughout the problem. These problems are accessible to eighth-graders, but they are also interesting for university applicants—problems of this type come across in oral exams.

The key to solving the problems below is the three area formulas. As is known (“Geometry 8”, paragraph 108), the area of ​​a triangle is equal to half the product of two (any) sides of it and the sine of the angle between them:

$$S = \frac{1}{2} ab \sin \alpha$$

Deduce from this that the area of ​​a convex quadrilateral is equal to half the product of its diagonals and the sine of the angle between them*):

$$S = \frac{1}{2} l_1 l_2 \sin \alpha.$$

Prove also that the area of ​​the circumscribed polygon

*) Why is it not necessary to specify which angle between the diagonals will be considered?

$$S = \frac{1}{2} Pr.$$

Problem 1. Prove that the product of any two side triangles is not less than the product of its perimeter and the radius of the inscribed circle: $ab \geq Pr$.

Solution. It is enough to equate expressions (1) and (3) for the area of ​​the triangle and take into account that $\sin \alpha \leq 1$.

Comment. From the solution it is clear that if the angle between sides with lengths $a$ and $b$ is not straight, then $ab > Pr$.

From inequality (4) and the replacement it follows that for any triangle

$$ab + bc + ca > 3Pr.$$

Problem 2. Prove that the radius $R$ of a circumscribed circle around an arbitrary triangle, the radius $r$ of the circumscribed circle and its perimeter $P$ satisfy the inequality

a) $R > \frac{\sqrt{3}}{3} \sqrt{Pr}$,

if the triangle is acute or obtuse;

b) $R \geq \frac{\sqrt{2}}{2} \sqrt{Pr}$,

if the triangle is right angled.

Solution. a) Connect the center $O$ of the circumscribed circle with the vertices of the triangle.

For an acute triangle (Fig. 1)

$$S_{ABC} = S_{AOB} + S_{BOC} + S_{COA}.$$

Fig. 1.

⟦folio 53⟧

On the other hand, according to formula (1)
$$S_{AOB} = \frac{1}{2} |OA| \cdot |OB| \cdot \sin \widehat{AOB}. \quad (18)$$
FROM (17) and (18)
$$P_1 r_1 \leq |OA| \cdot |OB|. \quad (19)$$
Likewise,
$$P_2 r_2 \leq |OB| \cdot |OC|, \quad (20)$$
$$P_3 r_3 \leq |OC| \cdot |OD|, \quad (21)$$
$$P_4 r_4 \leq |OD| \cdot |OA|. \quad (22)$$
FROM (19) - (22) the required inequality is easily obtained.
Equality is achieved when $[AC] \perp [BD]$. From (16) and (13) the inequality is easily obtained:
$$S_{AOB} \cdot S_{BOC} \cdot S_{COD} \cdot S_{DOA} \leq \frac{1}{16} |OA|^2 \cdot |OB|^2 \cdot |OC|^2 \cdot |OD|^2.$$
Problem 5. Prove that for a convex quadrilateral ABCD the following inequality holds:
$$S_{ABCD} \leq \frac{a^2 + b^2 + c^2 + d^2}{4}, \quad (23)$$
food $a, b, c, d$—the length of its side.
Solution. Let's break it down. A quadrilateral diagonal into two triangles (Fig. 3). Then
$$S_{ABCD} = S_{ABC} + S_{ADC}.$$
According to formula (1)
$$S_{ABC} = \frac{1}{2} ab \sin \widehat{B}.$$

From here and from the inequality $ab \geq \frac{a^2 + b^2}{2}$ we obtain
$$S_{ABC} \leq \frac{a^2 + b^2}{4}. \quad (24)$$
Likewise
$$S_{ADC} \leq \frac{c^2 + d^2}{4}. \quad (25)$$
From (24) and (25) we obtain the required inequality.
If $\widehat{B} = \widehat{D} = 90^\circ$ and $a = b = c = d$, i.e., the quadrilateral ABCD is a square, then correspondence (23) turns into an equality.
In conclusion, here are three tasks to solve on your own.
Problem 6. Prove that for a gravetion with height $h$, diaeons $l_1, l_2$ and bases $a, b$
$$h \leq \frac{l_1 l_2}{a + b}.$$
Problem 7. Prove that for the line ABC
$$S_{ABC} < \frac{1}{6} (a^2 + b^2 + c^2),$$
food $a, b, c$—side lengths.
Problem 8. Prove that for a convex quadrilateral ABCD
$$S_{ABCD} < \frac{1}{6} (a^2 + b^2 + c^2 + d^2 + e^2 + f^2),$$
food $a, b, c, d$—lengths in diaeons.
Build a polyhedron!
(Starts on p. 50)
The polyhedron on the second page of the cover is obtained from this diagram in a somewhat more complex way: in it, the “surroundings” of vertices 3 and 7 are used five times - from them the dome of the model with vertex 9 is formed. The side surfaces are also obtained from the diagram.
How to build diagrams? This is done using equally semi-right polyhedra.
Such polyhedra are replaced by the fact that all their faces are equal: for any two faces of such a polyhedron, one can specify a displacement of space such that the polyhedron will transform into itself, and the first face will transform into the second. Let's take any such polyhedron and consider the planes of all its faces. Let's fix one of these planes (let's call it $\Pi$). In it, the remaining planes are “carved out” by a system of straight lines. Exactly the same systems form in the remaining planes. Let us now consider the polyhedral line $l$ of the system. It is the intersection of the plane $\Pi$ and the plane of another face. During a rotation that transforms this plane into the plane $\Pi$, the straight line $l$ will go into some straight line $l'$ of the plane $\Pi$. It turns out that line $l'$ is obtained from line $l$ either by rotation (in the plane $\Pi$) about their common point, or by parallel translation. Remains on the turning point line with corresponding jocks and arrows for parallel transfers.
The diagram on figure was obtained from an equalized half-right hexadecagon («Kvant», 1976, No. 1).
Advice. When making a diagram on a larger scale, take advantage of the fact that the pentagon ABCD is correct.
