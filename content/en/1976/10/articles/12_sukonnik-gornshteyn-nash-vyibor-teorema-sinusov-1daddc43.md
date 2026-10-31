---
id: 1976-10-sukonnik-gornshteyn-nash-vyibor-teorema-sinusov-1daddc43
issue: kvant_1976_10
year: 1976
number: "10"
title: Our choice is the theorem of sines!
authors:
  - Суконник Я. Н.
  - Горнштейн П. И.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 48
page_last: 52
page_labels: 46-50
tag: 7Q2O
lang: en
source: kvant_digital
extraction: vision
content_sha256: fab3a31f0c4e29f700fb02229389f1740f5506d1ef1993a84efd2b4586fedea0
prompt_sha256: draft-1
translated_from: content/ru/1976/10/articles/12_sukonnik-gornshteyn-nash-vyibor-teorema-sinusov-1daddc43.md
source_content_sha256: b0de61526fe5130fa1f947a1f83887daf433f2981ee2244bdf727787e49ad2f1
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 46⟧

Our choice is the theorem of sines!

In any triangle $ABC$ the sides $|BC| = a, |CA| = b, |AB| = c$ and angles $\widehat{CAB} = \widehat{A}, \widehat{ABC} = \widehat{B}, \widehat{BCA} = \widehat{C}$ are related by the following important relations.

Cosine theorem*). The square of an arbitrary side is equal to the square of the other side of the plane square of the triangle minus the double product of these sides by the cosine of the angle between them, that is
$$a^2 = b^2 + c^2 - 2bc \cos \widehat{A},$$
$$b^2 = c^2 + a^2 - 2ca \cos \widehat{B},$$
$$c^2 = a^2 + b^2 - 2ab \cos \widehat{C}.$$
Theorem of sines. An arbitrary side is equal to the product of the circumscribed circle diameter and the sine of the adjacent angle, that is
$$a = 2R \sin \widehat{A}, b = 2R \sin \widehat{B},$$
$$c = 2R \sin \widehat{C},$$
or, in a more common form,
$$\frac{a}{\sin \widehat{A}} = \frac{b}{\sin \widehat{B}} = \frac{c}{\sin \widehat{C}} = 2R.$$
But if you were asked to use only one of these two theorems and discard the other, which one would you keep? From the sine theorem one can derive the cosine theorem, and from the cosine theorem the sine theorem (though without the proportionality coefficient $2R$ - as in the school textbook). But the theorem

*) On the cosine theorem, see the article by E. G. Gotman “The Cosine Theorem and Its Consequences” («Kvant», 1972, No. 7).

⟦folio 47⟧

hence,

$$|AB| \cdot |CD| + |BC| \cdot |DA| = 4R^2 \left| \sin(\hat{A} + \hat{B} - \alpha) \cdot \sin(\alpha) + \sin(\hat{A} - \alpha) \cdot \sin(\hat{B} - \alpha) \right| = 2R^2 \left| \cos(\hat{A} + \hat{B} - 2\alpha) - \cos(\hat{A} + \hat{B} - 2\alpha) \right| = 4R^2 \sin \hat{A} \sin \hat{B} = (2R \sin \hat{A}) \cdot (2R \sin \hat{B}) = |BD| \cdot |AC|.$$

The most natural application of the theorem of sines appears in cases where the problem involves sides, opposite angles and the radius of a circle circumscribed about a triangle.

Problem 2 (MSU, mechanism, 1961). Given a triangle whose base is $\alpha$ and its vertex angle is $\alpha$. A circle is constructed passing through the center of the inscribed triangle and the ends of the base. Find its radius.

Let $O$ (Fig. 2) be the center of the inscribed circle. Then

$$\widehat{BOC} = 180^\circ - \widehat{OBC} - \widehat{OCB} = 180^\circ - \frac{\hat{B}}{2} - \frac{\hat{C}}{2} = 90^\circ + \frac{\alpha}{2}.$$

Since the triangle $BOC$ is inscribed in the original circle, using the theorem of sines we find this circle:

$$R = \frac{|BC|}{2 \sin \widehat{BOC}} =$$

Fig. 1.

Fig. 2.

Fig. 3.

Problem 3 (MSU, physics, 1962; UrSU, physics, 1973). In an isosceles triangle, the base angle is $\alpha$. The height lowered to the base is greater than the raduisca of the hanging steep by $m$. Determine the base of the triangle and the radius of the main circle.

Let again $O$ be the center of the inscribed circle (Fig. 3). Then

$$|AO| = |AD| - |OD| = h_a - r = m,$$

$$\widehat{AOC} = 90^\circ + \frac{\alpha}{2}, \quad \widehat{ACO} = \frac{\alpha}{2}.$$

Therefore, applying the theorem of sines twice (for triangles $ABC$ and $AOC$), we obtain

$$|BC| = |AC| \cdot \frac{\sin \hat{A}}{\sin \hat{B}} =$$

$$= |AO| \frac{\sin \widehat{AOC}}{\sin \widehat{ACO}} \cdot \frac{\sin \hat{A}}{\sin \hat{B}} = 2m \cos \alpha \cdot \text{ctg} \frac{\alpha}{2},$$

$$R = \frac{|AC|}{2 \sin \hat{B}} = \frac{|AO| \sin \widehat{AOC}}{2 \sin \widehat{ACO} \cdot \sin \hat{B}} = \frac{m \sin \left(90^\circ + \frac{\alpha}{2}\right)}{2 \sin \frac{\alpha}{2} \cdot \sin \alpha} = \frac{m}{4 \sin^2 \frac{\alpha}{2}}.$$

Problem 4. A quadrilateral $ABCD$ is described near the steep slope, the diagonals of which

⟦folio 48⟧

torus intersect at point E. The radiuses of the circles circumscribed about the triangles AEB, BEC and CED, respectively, are equal to $R_1$, $R_2$ and $R_3$.
Find the radius R of the circle circumscribed about the triangle AED.

The quadrilateral ABCD (Fig. 4) is circumscribed about the circle, so the equality holds
$$|AB| + |CD| = |BC| + |AD|.$$
Besides,

$$\sin \widehat{AEB} = \sin \widehat{BEC} =$$
$$= \sin \widehat{CED} = \sin \widehat{DEA}.$$
Then
$$\frac{|AB|}{\sin \widehat{AEB}} + \frac{|CD|}{\sin \widehat{CED}} =$$
$$= \frac{|BC|}{\sin \widehat{BEC}} + \frac{|AD|}{\sin \widehat{DEA}}.$$

Now, by the theorem of sines, we get $R_1 + R_3 = R_2 + R$, whence
$$R = R_1 - R_2 + R_3.$$

Sometimes in problems it is necessary to move from a given known ratio of a side or segments to the corresponding ones between the angles of a triangle. And this is most conveniently done using the theorem of sines.

Problem 5 (Leningrad State University, Faculty of Chemistry, 1973). In equilateral triangle ABC ($|AB| = |BC|$), median AD is drawn. Find angle BAD if the angle at vertex B is α.

From the triangle ABD (Fig. 5), in which $|AB| = 2|BD|$, it follows by the sine theorem

$$2 = \frac{|AB|}{|BD|} = \frac{\sin \widehat{ADB}}{\sin \widehat{BAD}} = \frac{\sin(\alpha + \widehat{BAD})}{\sin \widehat{BAD}} = \sin \alpha \cdot \text{ctg} \widehat{BAD} + \cos \alpha.$$

From here
$$\widehat{BAD} = \arctg \frac{2 - \cos \alpha}{\sin \alpha}.$$

Problem 6. A second regular triangle is inscribed in a given regular triangle, and the ratio of their areas is 3. Prove that the sides of the inscribed triangle are perpendicular to the corresponding sides of the given triangle.

It's easy to prove (prove!) that $|AF|$ is equal to $|BD|$ (Fig. 6). Now from the similarity of triangles ABC and DEF from the theorem of sines we have

$$\sqrt{3} = \sqrt{\frac{S_{\triangle ABC}}{S_{\triangle DEF}}} = \frac{|AB|}{|DF|} =$$
$$= \frac{|AF| + |FB|}{|DF|} = \frac{|BD|}{|DF|} + \frac{|FB|}{|DF|} = \frac{\sin \widehat{BFD}}{\sin \widehat{DBF}} + \frac{\sin \widehat{BDF}}{\sin \widehat{DBF}} = \frac{\sin(120^\circ - \widehat{BDF}) + \sin \widehat{BDF}}{\sin 60^\circ} = 2 \cos(60^\circ - \widehat{BDF})$$
$$\cos(60^\circ - \widehat{BDF}) = \frac{\sqrt{3}}{2}, \widehat{BDF} = 90^\circ$$
(then $|FD| \perp |BC|$) or $\widehat{BDF} = 30^\circ$. (then $|FD| \perp |AB|$).

⟦folio 49⟧

Task 7 (MSU, Mechanics and Mathematics, 1972). In triangle ABC, uelol C is tunoy; bissertis BE uela B we divide side AC into segments AE and EC of length 3 m and 2 m. It is known that point K, lying on the extension of side BC beyond vertex C, is the center of a circle passing through points C, E and the intersection point of bissertis uelela B with bissertis uelela ACK. Determine the distance from point E to side AB.

Obviously, the required distance EH (Fig. 7) will be found if sin $\hat{A}$ becomes known. But first, let's find the relationship between the angles of triangle ABC. Let D be the intersection point of bissertis angles B and ACK. Let's draw the chord EF, then $\hat{EDC} = \hat{EFC}$, but

$$\hat{EDC} = \hat{DCF} - \hat{DBC} = \frac{1}{2} \hat{ACF} - \frac{\hat{B}}{2} = \frac{(180^\circ - \hat{C}) - \hat{B}}{2} = \frac{\hat{A}}{2},$$

$$\hat{EFC} = 90^\circ - \hat{ECF} = 90^\circ - (180^\circ - \hat{C}) = \hat{C} - 90^\circ,$$

pose

$$\frac{\hat{A}}{2} = \hat{C} - 90^\circ, \hat{C} = 90^\circ + \frac{\hat{A}}{2}.$$

By the sine theorem and the bissertis property, from triangle ABC we have

$$\frac{2}{3} = \frac{|EC|}{|AE|} = \frac{|BC|}{|AB|} = \frac{\sin A}{\sin \hat{C}} = \frac{\sin \hat{A}}{\sin \left(90^\circ + \frac{\hat{A}}{2}\right)} = 2 \sin \frac{\hat{A}}{2},$$

$$\sin \frac{\hat{A}}{2} = \frac{1}{3}, \sin \hat{A} = \frac{4\sqrt{2}}{9},$$

$$|EH| = |AE| \cdot \sin \hat{A} = \frac{4\sqrt{2}}{3}.$$

There are times when the product of several segment ratios appears in a problem. And here the application of the theorem of sines leads to a simple solution.

Task 8 (MSU, Faculty of Economics, 1975). Given a triangle ABC, with $|AB| = |AC|$ and $\hat{A} = 80^\circ$. Inside the triangle ABC, a point M is taken, indicating that $\hat{MBC} = 30^\circ$ and $\hat{MCB} = 10^\circ$. Find uelol AMC.

Let us denote the desired angle $\hat{AMC}$ by x (Fig. 8). It's obvious that

$$\hat{ABM} = 20^\circ, \hat{ACM} = 40^\circ, \hat{CMB} = 140^\circ,$$

and then $\hat{AMB} = 220^\circ - x$. According to the conditions and the theorem of sines from triangles AMB and AMC

Fig. 7. Fig. 8. Fig. 9.

⟦folio 50⟧

we have

$$1 = \frac{|AB|}{|AC|} = \frac{|AB|}{|AM|} \cdot \frac{|AM|}{|AC|} = \frac{\sin(220^\circ - x)}{\sin 20^\circ} \cdot \frac{\sin 40^\circ}{\sin x} = \frac{2 \sin(x - 40^\circ) \cos 20^\circ}{\sin x} = \frac{\sin(x - 20^\circ) + \sin(x - 60^\circ)}{\sin x},$$

$$\sin x - \sin(x - 60^\circ) = \sin(x - 20^\circ),$$
$$2 \sin 30^\circ \cdot \cos(x - 30^\circ) = \sin(x - 20^\circ),$$
$$\cos(x - 30^\circ) = \cos(110^\circ - x),$$
$$x = \widehat{AMC} = 70^\circ.$$

Problem 9. In a convex chain ABCD the following wells are given:
$$\widehat{BAC} = 15^\circ, \widehat{CBD} = 90^\circ, \widehat{DCA} = 30^\circ,$$
$$\widehat{ADB} = 75^\circ.$$ Name the well between the diazons.

Let us denote $\widehat{AED}$ by $x$ (Fig. 9).

Then $\widehat{ABE} = x - 15^\circ, \widehat{BCE} = 90^\circ - x,$
$\widehat{CDE} = x - 30^\circ, \widehat{DAE} = 105^\circ - x,$ and from triangles $AEB, BEC, CED$ and $DEA$ by the sine theorem we have
$$\frac{|AE|}{|BE|} = \frac{\sin(x - 15^\circ)}{\sin 15^\circ}, \frac{|BE|}{|CE|} = \frac{\sin(90^\circ - x)}{\sin 90^\circ}, \frac{|CE|}{|DE|} = \frac{\sin(x - 30^\circ)}{\sin 30^\circ},$$
$$\frac{|DE|}{|AE|} = \frac{\sin(105^\circ - x)}{\sin 75^\circ}.$$

Multiplying the written equalities term by term, after reducing the identical factors we obtain
$$\sin(x - 15^\circ) \cdot \sin(90^\circ - x) \times \sin(x - 30^\circ) \cdot \sin(105^\circ - x) = \sin 15^\circ \cdot \sin 90^\circ \cdot \sin 30^\circ \cdot \sin 75^\circ,$$
$$[2 \sin(x - 15^\circ) \cdot \sin(105^\circ - x)] \times [2 \sin(x - 30^\circ) \sin(90^\circ - x)] = 2 \sin 15^\circ \cdot \cos 15^\circ,$$
$$[\cos(2x - 120^\circ) - \cos 90^\circ] \times |\cos(2x - 120^\circ) - \cos 60^\circ| = \frac{1}{2},$$
$$2 \cos^2(2x - 120^\circ) - \cos(2x - 120^\circ) - 1 = 0,$$
whence the desired angle is equal to $60^\circ$.

In the right
1 (MSU, VMK, 1971). In a circle of radius $R$ there are two chords: $AB$ and $AC$. On the chord $AB$ or on its extension, the point $B$ is taken as the point $M$, the distance from which to the straight line $AC$ is equal to the length of the chord $AC$. Similarly, on the chord $AC$ or on its extension, the point $C$ is taken to be the point $N$, the distance from which to the straight line $AB$ is equal to the length of the chord $AB$. Find the length of the segment $MN$.

2 (NSU, mexmat, 1969). Prove that among all triangles with a given base and a given vertex angle, the equilateral triangle has the most perimeter.

3 (MIPT, 1970). In a triangle, the vertex angle $A$ is three times the angle $B$, and the sides $AB, BC, AC$ (in that order) form an arithmetic progression. Find the angles of triangle $ABC$.

4 (MIIT, 1972). In a right triangle, given an acute angle $\alpha$ and a distance $a$ from the vertex of another acute angle to the center of the inscribed circle. Determine the area of ​​the triangle.

5 (MSU, Faculty of Geography, 1969). The line passes through the vertex $B$ of the equilateral triangle $ABC$, intersecting its base $AC$ at the point $D$. It is known that

$$\widehat{ABD} = \frac{1}{3} \widehat{ABC} \text{ и } |AD|:|DC| = 3:4.$$

Acute or obtuse angle $ABC$?
6 (MSU, Faculty of Biology, 1968). In a circular equilateral triangle $ABC$, in which there are $|AB| = |BC|$ and $\widehat{ABC} = \alpha$. From the vertex $A$ a bisecris of the angle $BAC$ is drawn, intersecting the side $BC$ at the point $D$, and the circle at the point $E$. Vertex $B$ is connected by a line segment to point $E$. Find the ratio of the areas of triangles $ABE$ and $BDE$.

7 (MSU, Faculty of Geology, 1975). In the rhombus $ABCD$, from the side $(1 + \sqrt{5})$ с and the acute angle $\widehat{BAD} = 60^\circ$ there is a circle inscribed in the triangle $ABD$. From point $C$ to the circle. a tangent is drawn intersecting side $AB$ at point $E$. Find the length of the segment $AE$.

8. The rounded quadrilateral $ABCD$. Through the point $E$ of intersection of the diagonal, a segment $FH$ is drawn (F lies on $AB$, $H$ on $CD$). Prove that

$$\frac{|FE|}{|EH|} = \sqrt{\frac{|AF|}{|CH|} \cdot \frac{|BF|}{|DH|}}.$$
