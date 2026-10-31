---
id: 1973-11-ovchinnikov-sharyigin-chislovyie-dannyie-v-geometricheskih-zadachah-3d4c74f7
issue: kvant_1973_11
year: 1973
number: "11"
title: Numerical data in geometric problems
authors:
  - Овчинников С. В.
  - Шарыгин И. Ф.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 54
page_last: 58
page_labels: 52-56
tag: 27S0
lang: en
source: kvant_digital
extraction: vision
content_sha256: 27388e28200b65cf4a42cffef3720673ef962edb0f8d06117fdd9818e02086dc
prompt_sha256: draft-1
translated_from: content/ru/1973/11/articles/11_ovchinnikov-sharyigin-chislovyie-dannyie-v-geometricheskih-zadachah-3d4c74f7.md
source_content_sha256: f61adac7daff3ad343b2b3ce52fd2ca87088ffc377678ea8e10183b609f0e746
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 52⟧

Numerical data in geometric problems
S. V. Ovchinnikov, I. F. Sharytsin

In most standard school problems, numbers play no role at all. As a rule, such problems can be solved in a general form, using “letter” notation, and then substitute these numbers into the resulting answer. However, often using a "specification" of numerical data produces a simpler solution. In this note, we will show with examples how numerical data influences the solution of a problem in different ways.

Let's start with the problem proposed at the entrance exams to the Faculty of Chemistry of Moscow State University in 1970.

Problem 1. Chord AB we connect the arc of a circle equal to 120°. Point C lies on the emoy duo, and point D lies on the chord AB. In this case AD = 2, BD = 1, DC = √2. The simimplicum of triangle ABC.

Note that ∠ODC = 90°. Indeed, let us continue the segment CD until it intersects the circle (Fig. 1). Since AD ​​· BD = CD × DE, then DE = CD = √2 and OD ⊥ CE. From △AOF we find the radius of the circle. It is equal to √3, so from triangle OFD we get that ∠FDO = 60°. Hence ∠CDA = 30°, ∠CDB = 150°.

Using the formula to determine the area of ​​a triangle based on two sides and the angle between them, we find that S△ADC = √2/2, S△CDB = √2/4. Hence S△ABC = 3/4 √2.

Analyzing the solution given, we see that the numerical data in the problem were chosen “very well.” If we try to solve this problem in a general form, that is, we take arbitrary numbers as initial data, we will very quickly see that the solution turns out to be prohibitively cumbersome. (Try to solve this problem in general form. It will be a useful exercise.) Here is a typical problem in which numerical data does not play any role. They are used only at the last stage when substituting into the general answer and are for illustrative purposes.

Problem 2 (geofakt of Moscow State University, 1968). In triangle ABC, the bicector AD and BAC and the bicsectrix CF and ACB are drawn (the D part lies on the side BC, the part F lies on the AB side). Naimplicit ratio of the areas of a triangle

⟦folio 53⟧

Fig. 2.

ABC and AFD spoolers, if it is known that AB = 21, AC = 28, CB = 20.

Let us denote the sides of the triangle AB, BC and CA respectively by c, a and b (Fig. 2). Using the property of the bisector of an angle of a triangle inside it, we find that

$$AF = \frac{bc}{a+b}, \quad BD = \frac{ac}{b+c}.$$

From here

$$\frac{S_{\triangle ABD}}{S_{\triangle ABC}} = \frac{BD}{BC} = \frac{c}{b+c},$$

$$\frac{S_{\triangle AFD}}{S_{\triangle ABD}} = \frac{AF}{AB} = \frac{b}{(a+b)},$$

$$\frac{S_{\triangle ABC}}{S_{\triangle AFD}} = \frac{(a+b)(b+c)}{bc}$$

Substituting their numerical values ​​for a, b and c, we find $$\frac{S_{\triangle ABC}}{S_{\triangle AFD}} = 4,$$ and therefore the exception is 4.

The following problem can be solved in general form, but the solution exists is simplified if you use numerical values ​​in time.

Problem 3 (Mechanics and Mathematics, Moscow State University, 1969). The rectilinear projections of triangle ABC onto two mutually perperdicular planes are right triangles with sides equal to 1. Find the perimeter of triangle ABC if it is known that AB = $$\frac{\sqrt{5}}{2}$$.

Let us denote the planes on which the triangle ABC is projected by P and Q (Fig. 3). Obviously, we can assume that one of the vertices of the triangle, for example A, lies on the common edge R of the planes P and Q. Since the projections of the side AB and AC on the planes P and Q are equal, points A, B and C lie in the bisector plane S of the dihedral angle formed by the planes P and Q. We denote the projections of points B and C on Q by D and E. Let us drop the redistribution curve BF from point B to the edge R, $\Rightarrow BFD = 45^\circ$.

In further calculations, it would be possible not to fix the length of the segment AB, but to consider it to be an arbitrary value a. In this case, the decision can also be completed. But this particular value of $AB = \frac{\sqrt{5}}{2}$ allows the creature to simplify the solution.

Indeed, from triangle ABD we find: BD = $$\frac{1}{2} (\Rightarrow ADB = 90^\circ, AB и AD данные).$$ Since $\Rightarrow BFD = 45^\circ$, then FD = BD = $$\frac{1}{2}$$ and in triangle AFD we have $\Rightarrow AFD = 90^\circ, \Rightarrow FAD = 30^\circ$. From this we consistently obtain that AE ⊥ AF, $\Rightarrow CAE = 45^\circ, \Rightarrow CEA = 90^\circ, AC = \sqrt{2}$. From the rectangular trapezoid CBDE we have $(CE - BD)^2 + DE^2 = BC^2$. Hence BC = $$\frac{\sqrt{5}}{2}$$, and the perimeter of triangle ABC is $$\sqrt{5} + \sqrt{2}$$.

If the problem is considered with numerical data, the

⟦folio 54⟧

Although the volume of calculations helped us, sometimes they, on the contrary, create computational difficulties and even obscure the simple geometric meaning of the problem.

Problem 4 (Geological Department of Moscow State University, 1971). In triangle ABC, a bisector BD is drawn from sides AB = 3 cm, BC = 4 cm and AC = 5 cm. Triangle ABD and BCD have inscribed circles that touch BD at points M and N, respectively. Determine the length of the segment MN.

The numerical data for this problem shows that the triangle is right angled. This may lead to trying to solve the problem using the metric properties of a right triangle.

In fact, the problem has a simple geometric solution for an arbitrary triangle ABC. Let us denote AB by c, BC by a and AC by b (Fig. 4). By the bisector property, AD = \frac{bc}{a+c}, CD = \frac{ab}{a+c}.

Let us introduce the unknowns x = BM, y = MN and z = ND. Since the tangents drawn from one point to the circle are equal, we can construct the following system of equations:

$$\begin{cases} x + y + \left( \frac{ab}{a+c} - z \right) = a, \\ x + \left( \frac{bc}{a+c} - z - y \right) = c. \end{cases}$$

Subtracting from the first equation

swarm, we'll get

$$2y + \frac{ab}{a+c} - \frac{bc}{a+c} = a - c,$$

where

$$y = \frac{1}{2} \frac{(a-c)(a+c-b)}{a+c}.$$

Substituting their values ​​for a, b and c, we find that MN = \frac{1}{7}.

Now we will consider problems in which specially selected numerical data dramatically simplifies the solution of the problem.

Problem 5. In triangle ABC, sides AB = 4, AC = \sqrt{17} and BC = 5 are given. On side AB, point D is taken, indicating that AD = 1. The distance between the centers of the circles circumscribed about triangles ADC and DBC lies at the midpoints of sides AC and BC, and the required distance is equal to the length of the midline parallel to AB, that is, 2 (Fig. 5). That CD is a height follows from the equality

$$BC^2 - AC^2 = BD^2 - DA^2 = 8.$$

How is it agreed that CD is the height? After all, it is clear from the decision that this agreement is the main point in the decision - all other differences are trivial. We are not co-

Fig. 4.

Fig. 5.

⟦folio 55⟧

We try (and we cannot) explain how to guess, but it points to one important circumstance. We are talking about a drawing. A carefully and competently executed drawing is a very good help in solving a problem. This applies to any geometry problem, both with numerical and alphabetic data. If the data is numeric, then the given dimensions of the figure should be reflected in the drawing. For example, if in a disassembled problem you make a drawing in compliance with the given proportions, then it is quite easy to see that CD is the height.

Assignment 6 (geology department of Moscow State University, 1970). In ABCD, the bases AD = 39 cm, BC = 26 cm and the sides AB = 5 cm, CD = 12 cm are known. Find the radius of the circle that passes through points A and B and touches side CD or its extension.

Let's complete the trapezoid to triangle AED (Fig. 6). From the similarity of triangles BEC and AED we easily obtain BE = 10 cm, CE = 24 cm. If the drawing is done carefully, then you can notice that $\angle AED = 90^\circ$: This is easy to prove: $AE^2 + ED^2 = AD^2$. Let O be the center of a circle passing through A and B and touching ED at point G. Let us drop from O the transition OF to AB, then F is the midpoint of the chord AB. Obviously OG = EF = 12.5 cm. Hence the required radius is 12.5 cm.

In the following tasks, the numerical data shows the weights of the light...

Fig. 6.

Fig. 7.

different. When studying such a problem in advance, it is difficult to predict exactly how this data will influence the solution, but once you start solving the problem, at some points it becomes clear that only with these data can you get an answer. As a rule, in such problems, let the solutions be very clear, although it is not clear from the very beginning whether it will lead to an answer.

Task 7 (Binology Faculty of Moscow State University, 1970). On the sides of a convex quadrilateral ABCD, the area of ​​which is equal to 1, points are taken: K on AB, L on BC, M on CD and N on AD. At the same time $\frac{AK}{KB} = 2, \frac{BL}{LC} = \frac{1}{3}, \frac{CM}{MD} = 1, \frac{DN}{NA} = \frac{1}{5}$. Find the area of ​​the hexagon AKLCMN.

The ratio of the areas of triangles KBL and ABC is $\frac{BK \cdot BL}{AB \cdot BC} = \frac{1}{12}$ (Fig. 7). The ratio of the areas of triangles MND and ADC is $\frac{DN \cdot DM}{AD \cdot CD} = \frac{1}{12}$. Thus, the sum of the areas of triangles KBL and MND is $\frac{1}{12}$, hence the required area is $\frac{11}{12}$.

It is clear that such a problem in general does not have a unique solution.

Task 8 (Ural State University of Mechanics and Mathematics, 1968). Three points A, B and C are connected directly

⟦folio 56⟧

moline roads. Adjacent to the road segment AB is a square field with side equal to $\frac{1}{2} AB$. The road segment BC is adjacent to a square field with a side equal to BC, and the road segment CA is adjacent to a rectangular forest plot with a length equal to CA and a width of 4 km. The forest area is 20 km² greater than the sum of the square fields. Find the area of ​​the forest.

At first glance, there is too little data to solve the problem. However, let's move on to the calculations. Let us denote the sides of the triangle AB, BC and CA by c, a, b, respectively. Then from the problem conditions we have: $4b = 20 + \frac{c^2}{4} + a^2$. Let's use the triangle inequality $b \leq a + c$ and substitute b into it, expressed in terms of a and c:

$$\frac{1}{4}\left(20 + \frac{c^2}{4} + a^2\right) \leq a + c.$$

After simple transformations of this inequality we obtain: $\left(\frac{c}{2} - 4\right)^2 + (a - 2)^2 \leq 0$, whence $c = 8(\text{km})$, $a = 2(\text{km})$, and $b = a + c = 10(\text{km})$. The forest area is 40 km².

The chosen solution path is the only possible one in this problem. But the fact that it leads to an answer turns out to be a consequence of specially selected data. As a result of this selection, three points A, B and C turned out to lie on the same line and the problem data was enough to obtain the answer.

Exercises

1. (Mechanics and Mathematics of Moscow State University, 1969). The rectangular projections of a plane quadrilateral onto two mutually perpendicular planes are squares on side 2. The odane of the diagonals of the quadrilateral is $\sqrt{14}$. Find another diagonal.

2. In acute triangle ABC, given $AB = 15$, $BC = 10$ and angle BAC is equal to arccos $\frac{7}{9}$. A circle is circumscribed around triangle ABC and a chord BE is drawn through point D lying on AC at a distance of 9 from A. Find the area of ​​triangle AEC.

3. Given a triangle ABC with sides 5, 2 and $\sqrt{22}$, with $AC = \sqrt{22}$. Point D is taken on AC so that BD = 3. Find the distance between point D and the center of the circle circumscribed around triangle ABC.

4. (Faculty of Physics, Moscow State University, 1971). A sphere is inscribed into a regular triangular line SABC, all of whose edges are equal to a. A point M is taken on the edge SA so that AM = MS, and a point N is taken on the edge BC so that 2CN = NB. The pit MN intersects the sphere at two points P and Q. Find the length of the segment PQ.

5. (Department of Chemistry, Moscow State University, 1971). In triangle ABC, the median BD is drawn from the side AB = $\sqrt{3}$ cm, BC = = 4 cm, AC = $\sqrt{7}$ cm. The inscribed circles of triangles ABD and BDC touch BD at points M and N, respectively. Determine the length of the segment MN.

6. (Faculty of Geography, Moscow State University, 1971). Two circles of radius r touch each other. In addition, each of them touches from the outside a triangle of radius R at points A and B of the corresponding one. Determine the radius r if AB = 12 cm, R = 8 cm.

7. (Biology department of Moscow State University, 1971). A regular triangle ABC with a side equal to 3 is inscribed in a circle. Point D lies on the circle, and the length of the chord AD is equal to $\sqrt{3}$. Find the lengths of the chords BD and CD.

8. (Biology Faculty of Moscow State University, 1970). Given a triangle ABC whose area is equal to one. On the median AK, BL and CN of triangle ABC the corresponding points P, Q and R are taken so that

$$\frac{AP}{PK} = 1, \frac{BQ}{QL} = \frac{1}{2}, \frac{CR}{RN} = \frac{5}{4}.$$

Find the area of ​​triangle PQR.

9. (Economic Faculty of Moscow State University, 1970). The volume of a block in the shape of a straight parallelepiped is 150 cm³, the total surface area is 280 cm², and the perimeter of the base is 40 cm. Find the dimensions of the block.

10. (Economic Faculty of Moscow State University, 1971). A ball of radius R is inscribed at two angles at an angle of 60°. Find the radius of a ball inscribed at the same angle and tangent to the dango ball, if it is known that the straight line connecting the centers of both balls forms an angle of 45° with the edge at two angles.

11. Given a triangle with sides AB = 4, BC = 3 and AC = 5. Point D is taken on side AB so that DB = $\frac{7}{8}$. A circle is drawn through points C, D and B and intersects AC at point E. Find the length of segment BE.
