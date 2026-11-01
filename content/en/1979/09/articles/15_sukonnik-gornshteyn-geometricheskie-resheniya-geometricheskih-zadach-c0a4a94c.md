---
id: 1979-9-sukonnik-gornshteyn-geometricheskie-resheniya-geometricheskih-zadach-c0a4a94c
issue: kvant_1979_9
year: 1979
number: "9"
title: Geometric solutions to geometric problems
authors:
  - Суконник Я. Н.
  - Горнштейн П. И.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 40
page_last: 44
page_labels: 38-42
tag: 4S9C
lang: en
source: kvant_digital
extraction: vision
content_sha256: 99b68264cb384c565bd253c82624a03c4632ba41a3bb35821b20636b38543b19
prompt_sha256: draft-1
translated_from: content/ru/1979/09/articles/15_sukonnik-gornshteyn-geometricheskie-resheniya-geometricheskih-zadach-c0a4a94c.md
source_content_sha256: 2b4384ab2947b17b794fa3a6ab14ca91fe91065d99f5af34d74dd1416d84a6d8
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 38⟧

Geometric solutions to geometric problems

Dedicated to the memory of Vainman V. Sh., a mathematics teacher in the city of Kyiv.

When solving geometric problems, they first resort to various analytical methods. Currently, the article talks about several geometric methods that make solutions simple and rational. The methods presented are almost identical and, undoubtedly, not new to the reader, but, nevertheless, it seems that the information about them will be useful to everyone who wants to learn how to solve geometric problems well.

1. Let's determine the type of figure.

In some cases, solving the problem will be significantly speeded up if you first determine the type that the original figure may (or may not) have.

Problem 1 (MSU, VMK, 1978). A circle is circumscribed about the triangle AMB, the center of which is at a distance of 10 from the side AM. The extension of the side AM beyond the vertex M cuts off a segment BC equal to 29 from the tangent to the circle drawn through the vertex B. Find the area of ​​the triangle BMC if it is known that the angle ACB is equal to arctan $\frac{20}{21}$.

Let's determine the type of triangle BMC, for which we draw its height $BM_1$, continue it to the intersection with the circle at point $M_2$ and project the center of the circle O onto the side AM and the chord $BM_2$ (Fig. 1). Then, according to the condition,

$$|OK| = 10, |BM_1| = |BC| \sin \widehat{ACB} = 29 \sin \left( \arctg \frac{20}{21} \right) = 29 \cdot \frac{20}{29} = 20 = 2 |OK|, |BM_2| = 2 |BL| = 2 (|BM_1| - |LM_1|) = 2 (|BM_1| - |OK|) = 2 |BM_1| - |BM_2| = |BM_1|.$$

It follows that the points M, $M_1$ and $M_2$ coincide (Fig. 2) and, therefore, the point O lies on [AB] and the triangle BMC is a right triangle. The rest is clear. (Answer.210.)

Problem 2 (MSU, Geology. Faculty, 1978). In triangle ABC, the side is $|AC| = 3, \widehat{BAC} = \frac{\pi}{6}$ and the radius of the circumcircle is 2. Prove that the area of ​​triangle ABC is one side less than 3.

Let us show that $\triangle ABC$ cannot be a right angle. In fact, let us draw in a circle of radius 2 from point A the chords AC, AB$_1$, AB$_2$ and the diameter AD (Fig. 3) so that $|AC| = 3, \widehat{B_1AC} = \widehat{B_2AC} = \frac{\pi}{6}$. The segment AB$_1$ does not coincide with the segment AD, since $\widehat{CAB}_1 = \frac{\pi}{6} \neq \arccos \frac{3}{4} = \arccos \frac{|AC|}{|AD|} = \widehat{CAD}$. Hence $\widehat{ACB}_1 \neq \frac{\pi}{2}$ and $|AB_1| < |AD|$. Therefore $S_{\Delta AB_1} = \frac{1}{2} |AC| \cdot |AB_1| \sin \widehat{B_1AC} < \frac{1}{2} |AC| \cdot |AD| \sin \widehat{B_1AC} = \frac{1}{2} \cdot 3 \cdot 4 \times \sin \frac{\pi}{6} = 3$. Inequality $S_{\Delta AB_2} < 3$ follows easily from $|AB_2| < |AC| = 3$.

2. Let’s “complete” the figure.

Every geometric solution to a geometric problem begins with working on a drawing.

⟦folio 39⟧

At the same time, sometimes in a “natural” drawing (i.e. in a drawing in which only the condition is “depicted”) it is difficult to notice the connections between the data and the original values, and if the figure is “completed”, these connections become obvious.

Problem 3 (MSU, Faculty of Soil Science, 1977). The lengths of the base CD, diagonal BD and lateral side AD of the trapezoid ABCD are equal to each other and equal to p. The length of the side BC is equal to q. Find the length of diagonal AC.

In this trapezoid ABCD (Fig. 4) it is impossible to see the connection between the original diagonal AC and other segments. If, taking into account that point D is equidistant from points A, B and C, draw a circle O(D, p) and “complete” this trapezoid to an isosceles trapezoid ABCE, it is easy to find $|AC| = \sqrt{4p^2 - q^2}$ from the right triangle ACE.

Problem 4 (NSU, 1976). In the trapezoid ABCD with base AB and CD, the bicsectrix of B is perpendicular to the lateral side AD and we intersect it at point E. In what ratio

is the line BE divided by the area of ​​the trapezoid if it is known that the length of the segment AE is twice as long as the segment DE?

If we “complete” this trapezoid ABCD to triangle AFB (Fig. 5), we obtain an equilateral triangle from which segment DC cuts off a similar triangle DFC with similarity coefficient $\frac{1}{4}$. Therefore, the required ratio is $\frac{S_{EDCB}}{S_{\Delta AEB}} = \frac{S_{\Delta EFB} - S_{\Delta DFC}}{S_{\Delta AEB}} = \frac{\frac{1}{2} S_{\Delta AFB} - \left(\frac{1}{4}\right)^2 S_{\Delta AFB}}{\frac{1}{2} S_{\Delta AFB}} = \frac{7}{8}$.

3. Let's describe a circle.

In some cases, an important point in the geometric solution of the problem is the establishment of the conformity of certain angles. Most often, such angles are corresponding in similar triangles

⟦folio 40⟧

or polygon. However, such situations are possible when the congruence of a pair of angles is considered to follow from the congruence of another pair of angles, the values ​​of which are known. For example, near a quadrilateral $ABCD$ if and only if it is possible to describe a circle when $\widehat{ABC} + \widehat{ADC} = 180^\circ$ (“Geometry 8”, p. 113). It is easy to prove that this condition is equivalent to condition $\widehat{ABD} = \widehat{ACD}$. Thus, the equalities $\widehat{ABD} = \widehat{ACD}$, $\widehat{ACB} = \widehat{ADB}$, $\widehat{BAC} = \widehat{BDC}$, $\widehat{CAD} = \widehat{CBD}$ are equivalent to (Fig. 6).

Problem 5 (MIPT, 1976). The point $E$ lies on the side $AC$ of the correct triangle $ABC$; point $K$ is the middle of segment $AE$. The line passing through the point $E$ perpendicularly ($AB$) and the line passing through the point $C$ perpendicularly ($BC$) intersect at the point $D$. Find the corners of triangle $BKD$.

Let line $ED$ intersect line $AB$ at point $F$ (Fig. 7). Then the triangle $AFE$ is rectangular, and $[FK]$ is the median. This means that triangle $AFK$ is a regular triangle, similar to the given triangle $ABC$. Posny $[FK] \parallel [BC]$ and quadrilateral $BFKC$ are equilateral trapezoids. Therefore, describe a circle around it. From $\widehat{BFD} + \widehat{BCD} = 90^\circ + 90^\circ = 180^\circ$ it follows that the point $D$ belongs to the same circle.

Pozny $\widehat{BKD} = \widehat{BFD} = 90^\circ$, $\widehat{KDB} = \widehat{KCB} = 60^\circ$ and $\widehat{DBK} = 30^\circ$.

Problem 6 (MSU, physics, 1974). The point $A$ is taken on the bicsectrix of the angle with vertex $L$. Points $K$ and $M$ are the bases of the perpendiculars dropped from $A$ to the sides of the angle. On the segment $KM$, a point $P$ is taken (|$KP$| < |$PM$|) and through the point $P$, perpendicular to the segment $AP$, a straight line is drawn, intersecting the line $KL$ at the point $Q$ (Between $Q$ and $L$), and the straight line $ML$ at point $S$. It is known that $\widehat{KLM} = \alpha$, |$KM$| = $a$, |$QS$| = $b$. Find the length of the segment $KQ$.

As you know, $|AK| = |AM|$. It is easy to report that $\widehat{AKM} = \widehat{ALK} = \frac{\alpha}{2}$.

Pozny $|AK| = \frac{a}{2\cos \frac{\alpha}{2}}$.

Around the quadrilaterals $APKQ$ ($\widehat{APQ} = \widehat{AKQ} = 90^\circ$) and $APSM$ ($\widehat{APS} + \widehat{AMS} = 90^\circ + 90^\circ = 180^\circ$), circles (Fig. 8) can be described. Searches $AQS = AQP = AKP = AKM = AMK = AMP = ASP = ASQ = \frac{\alpha}{2}$, triangle $AQS$ - equilateral. From $\triangle AQS$ there is $|AQ|$, then from the right triangle $AKQ$ - $|KQ| = \frac{\sqrt{b^2 - a^2}}{2\cos \frac{\alpha}{2}}$.

⟦folio 41⟧

4. "This guiding triangle"

Ponsk geometric solution of the problem can be carried out in the direction of the distance of figures, the properties of which are well studied. However, one of these figures is undoubtedly a triangle. Faithful and kind help - the triangle - the search for the unknown and is sometimes indispensable in our differences, in finding simple and clear solutions. Let us allow ourselves the following advice: if you have difficulty choosing the correct geometric path to solve a problem, look for a triangle!

Problem 7 (MSU, VMK, 1975). Given a rectangular trapezoid, the base of which is equal to a and b (a<b). It is known that a straight line parallel to the base of a certain sea cuts it into two trapezoids, in each of which a circle can be inscribed. Determine the radius of these circles.

Let us extend this trapezoid ABCD to a triangle (Fig. 9). Let the circles inscribed in the trapezoids AEFD and EBCF touch [EF] at points M and N, and their radius will be R and r, respectively. Since this trapezoid is rectangular, |EM|=R, |EN|=r. From the equality |KP|=|KQ| it is easy to deduce |EN|=|MF|. (This statement is of a general nature: in any triangle, the tangent points of the inscribed and outer circles are equidistant from the ends of the side they touch. An inscribed circle is a circle tangent to a side of the triangle and the extension of the other two sides.) So |EF|=R+r. From the similarity of triangles BKC, EKF and AKD we obtain the system

$$\begin{cases} \frac{a}{R+r} = \frac{r}{R}, \\ \frac{R+r}{b} = \frac{r}{R} \end{cases}$$

(in similar triangles, both the radii of the inscribed and the radii of the external circles are treated as corresponding sides), of which $R = \frac{bV_a}{V_a + V_b}$, $r = \frac{aV_b}{V_a + V_b}$.

Fig. 9.

Fig. 10.

Problem 8 (MSU, physics department, 1975). In rectangle ABCD (|BC|>|CD|), diagonals AC and BD intersect at point O. The bisector of angle CAD intersects [BD] at point E. Let F be the base of the perpendicular dropped from point E to side AD; point K is the middle [AD]. Through point E, a perpendicular is also drawn to [AE] until it intersects with the diagonal AC at point H. Find the area ABCD if |OH|=b, |KF|=\frac{4}{3}b.

Let's do [EL] || [AD], where L∈[AO] (Fig. 10). Since $\hat{AEL} = \hat{EAD} = \hat{EAC}$, |AL|=|LE|=2|ME|=2|KF|=\frac{8}{3}b.

Let's continue perpendicular HE until it intersects with [AD] at point G. Triangle AHG is equilateral ([AE] is bisector and altitude). Since [LE] is the middle line in it,

⟦folio 42⟧

Fig. 11.

triangle LHE will also be equilateral. Pozny

$$|OM| = \sqrt{|OL|^2 - |LM|^2} = \sqrt{(|LH| - |OH|)^2 - |ME|^2} = \sqrt{(|LE| - |OH|)^2 - |KF|^2} = \sqrt{\left(\frac{8}{3}b - b\right)^2 - \left(\frac{4}{3}b\right)^2} = b.$$

Using similar triangles ACD and LOM with similarity coefficient

$$\kappa = \frac{|AC|}{|LO|} = \frac{2|AO|}{|LH| - |OH|} = \frac{2(|AL| + |LH| - |OH|)}{|LE| - |OH|} = \frac{2\left(\frac{8}{3}b + \frac{8}{3}b - b\right)}{\frac{8}{3}b - b} = 5,2,$$

find the required area

$$S_{ABCD} = 2S_{\Delta ACD} = 2k^2 S_{\Delta LOM} = k^2 \cdot |LM| \cdot |OM| = (5,2)^2 \cdot \frac{4}{3}b \cdot b = \left(36 \cdot \frac{4}{75}\right)b^2.$$

Problem 9 (MIPT, 1974). An equilateral boundary with bases AD and BC (|AD| > |BC|) is described around the circle. A straight line parallel to the diagonal AC intersects the sides AD and CD of the corresponding one at points M and N and touches the circle at point P. Determine the angles of the boundaries if $\frac{|MP|}{|PN|} = k$.

Consideration of similar triangles ACD and MND (Fig. 11) leads to a simple geometric solution. Let us denote by E, F and G the points of tangency of the circle on the side AD, CD and BC, respectively, by H and Q - the projections of points C and N on the side AD. Let |PN| = 1. Then |MP| = k, |AH| = |AE| + |EH| = |ED| + |GC| = |DF| + |FC| = |DC|. From the properties of similarity and in the triangle MND there will be |MQ| = |DN|. Pozny

$$|MN| = |MP| + |PN| = k + 1, |DQ| = |DE| - |QM| - |ME| = |DF| - |DN| - |MP| = |NF| - |MP| = |NP| - |MP| = 1 - k, 2 |NQ|^2 = (|MQ|^2 + |NQ|^2) - (|DN|^2 - |NQ|^2) = |MN|^2 - |DQ|^2 = (k + 1)^2 - (1 - k)^2 = 4k, |NQ| = \sqrt{2k}.$$

Therefore, tan $\hat{D} = \frac{|NQ|}{|DQ|} = \frac{\sqrt{2k}}{1 - k}, \hat{A} = \hat{D} = \arctg \frac{\sqrt{2k}}{1 - k}, \hat{B} = \hat{C} = \pi - \arctg \frac{\sqrt{2k}}{1 - k}.$

Exercises

1 (MSU, Faculty of Philology, Department of Structure and Applied Linguistics, 1978). The pentagon ABCDE is inscribed in a circle of unit radius. It is known that |AB| = $\sqrt{2}$, $ABE = 45^\circ$, $EBD = 30^\circ$ and |BC| = |CD|. What is the area of ​​the pentagon?

2 (MSU, geological department, 1978). In triangle ABC, the length of side AB is 4. $\widehat{CAB} = \frac{\pi}{3}$, and the radius of the circumscribed circle R is equal to 2.2. Prove that the length of the height dropped from vertex C to side AB is strictly less than $\frac{11\sqrt{3}}{5}$.

3 (NSU, 1976). In parallelogram ABCD, angle BAD is 60°. The circle passing through points A, B and D intersects side CD in the middle. Find the area of ​​the parallelogram if the radius of the circle is R.

4 (MSU, Faculty of Sensory Science, 1977). The base AB of the trapezoid ABCCD is twice the length of the base CD and twice the length of the side AD. The length of the diagonal AC is equal to a, and the length of the lateral side BC is equal to b. Find the area of ​​the trapezoid.

5 (MINT, 1977). The center of the semicircle lies on the larger base AD of the trapezoid ABCCD; all other sides touch the semicircle. Prove that |AD| = |AB| + |CD|.
