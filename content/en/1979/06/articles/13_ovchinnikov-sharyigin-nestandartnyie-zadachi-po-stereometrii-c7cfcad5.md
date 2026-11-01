---
id: 1979-6-ovchinnikov-sharyigin-nestandartnyie-zadachi-po-stereometrii-c7cfcad5
issue: kvant_1979_6
year: 1979
number: "6"
title: Non-standard problems in stereometry
authors:
  - Овчинников С. В.
  - Шарыгин И. Ф.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 35
page_last: 39
page_labels: 33-37
tag: NY81
lang: en
source: kvant_digital
extraction: vision
content_sha256: ba6b9275c4e03dda78cb41f10e23cb02f95fca145d40fcc992996851c8f750d6
prompt_sha256: draft-1
translated_from: content/ru/1979/06/articles/13_ovchinnikov-sharyigin-nestandartnyie-zadachi-po-stereometrii-c7cfcad5.md
source_content_sha256: 254d303388ebb8acf48d061baa71da3760db539dcc5269e19a2056c946a87607
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 33⟧

Non-standard problems in stereometry

Anyone who is preparing for a written exam in mathematics and studying the MSU options from previous years in this regard will pay attention to the fact that, as a rule, each option is quite sharply divided into two parts: three or four relatively easy problems and one or two significantly more difficult ones. The “difficult” ones include either a non-standard algebraic (or trigonometric) problem or a stereometry problem.

To count on a successful written exam, you need to pay more attention to solving non-standard problems. About non-standard problems in stereometry *), displayed from the Moscow State University variants, other details in this article.

First of all, we emphasize the importance of constructing a successful drawing. When constructing, we must remember that projection violates many of the correspondences between the elements of the constructed figure. It is necessary to “keep in mind” the true angles and lengths all the time. There is no need to clutter the drawing with details that are difficult to depict. For example, as a rule, there is no need to depict spheres or bisector planes in the drawing. On the other hand, a successful additional construction can not only clarify the structure of the spatial configuration, but also give a good idea for solving the problem. It is very useful to depict important plane elements of a given stereometric figure, for example, faces, sections or projections, in a separate drawing.

Task 1 (BMK, 1974). In the triangular pair IDE SABC, the sums of the three plane angles at each of the vertices B and C are equal to 180° and |SA| = |BC|. Find the volume of the paramide if the area of ​​the face SBC is 100 cm² and the distance from the center of the circumscribed sphere to the plane of the base is 3 cm.

Solution. The first condition of the problem is the most “inconvenient” to use. To make it more visual, consider the unfolding $S_1S_2S_3$ ABC of the SABC paramide (Fig. 1). From the first condition it follows that the points $S_1$, $B$, $S_3$ lie on the same line, as do the points $S_1$, $C$, $S_2$. Since BC is the middle line in the triangle $S_1S_2S_3$, $|S_2S_3| = 2 |BC|$. On the other hand, according to the conditions of the problem, $|AS_3| = |AS_2| = |BC|$. Thus, the triangle $AS_2S_3$ turns out to be and the correct development is the development depicted on figure 2. It immediately follows that all faces are congested triangles. This means (prove it!), the distances from the center of the circumscribed ball to all faces are equal. If we connect the center of the circumscribed sphere with all the vertices, then our paramide is divided into four equal-sized paramides, the volume of each of which is equal to $\frac{1}{3} \cdot 3 \cdot 100 \text{ см}^3 = 100 \text{ см}^3$.

*) You can read about more standard approaches to solving stereometric problems (in particular, about the use of vectors and coordinates) in «Kvant» - 1978, No. 11, p. 42 and 1979, no. 1, p. 45.

⟦folio 34⟧

The volume of the original paramida is 400 cm³.

Problem 2 (Mekhmat, 1975).
A ball of unit radius is inscribed in a regular triangular paramid SABC with vertex S and base ABC; the dihedral angle between the base of the paramid and the lateral face is 60°. Prove that there is a unique plane intersecting the edges of the base AB and BC at some points M and N such that |MN| = 5, touching the ball at a point equidistant from points M and N, and intersecting the continuation of the height of the paramid SK beyond point K at some point D. Find the length of the segment SD.

Solution (Fig. 3). Let us note right away that the initial data completely determines our paramida.

Fig. 3.

Fig. 4.

Fig. 5.

Let's calculate, for example, the length of the side of the base. For this purpose, let us consider a section passing through the height of the paramidus SK and the side edge SB. (Such a section is often used in solving the problem of a regular paramid.) This section intersects the face ASC along the apothem SL (Fig. 4a); point O on it is the center of the inscribed ball. Since now the points M and N are uniquely determined by the conditions of the problem. Since the plane of the base also touches the ball, it follows from the conditions of the problem that |MK| = |KN| (proof!). Let |AM| = x. Then the prior 尼 is either |CN| = x, or |BN| = x (proof!).

Let's consider the first case (Fig. 5a). Since the line MN is parallel to the base AC, $\frac{|MB|}{|AB|} = \frac{|MN|}{|AC|} = \frac{5}{6}$, whence x = 1. Note, in particular, that |PK| = |KL| — $|PL| = \frac{\sqrt{3}}{2} < 1$. Consequently, the plane passing through (MN) and touching the ball intersects the extension of [SK] beyond the point K.

Moving on to the second case (Fig. 5b), we calculate the value x using the cosine theorem for triangle MBN. We get x = $\frac{9 - 4\sqrt{3}}{3}$. (Do the calculations yourself and justify why it is enough to limit yourself to this value for x.) Let us now determine the distance from point K to the segment MN. To do this, calculate the area of ​​the triangle MKN:

$$S_{MKN} = S_{MBK} + S_{KBN} - S_{MBN} = \frac{1}{2} (6 - x) 2\sqrt{3} \cdot \frac{1}{2} + \frac{1}{2} x\sqrt{3} - \frac{1}{2} (6 - x) x \frac{\sqrt{3}}{2} = \frac{25\sqrt{3}}{12}.$$

Hence,

$$KP = \left(2 \cdot \frac{25\sqrt{3}}{12}\right); 5 = \frac{5\sqrt{3}}{6} > 1.$$

This means that the plane passing through (MN) and tangent to the ball is transferred

⟦folio 35⟧

cuts (SK) “above” the point $K$, which contradicts the conditions of the problem. Thus, the second case is impossible. The existence and uniqueness of the desired plane has been proven.

Let's move on to calculating the length of the segment $SD$. On figure 6 the same section is again depicted as on figure 4, $a$. From the similarity of triangles $PKD$ and $QOD$ we easily find $|KD| = 6$. Hence $|SD| = |KD| + |SK| = 9$.

Problem 3 (BMK, 1975). Given a triangular paramida $ABCD$. The edges $AC$ and $BD$ and $AD$ and $BC$ of this paramda are crossed, the edges $AB$ and $CD$ are equal, all the edges of the paramda touch the ball of radius $r$. The most implicate facet is $ABC$.

Solution e. Let us draw a plane through the edge $AD$ perpendicular to the edge $BC$ (Fig. 7). Obviously (why?), this plane contains the height of the paramda, and $(DE) \perp (BC)$. $|BE|^2 = |AB|^2 - |AE|^2 = |BD|^2 - |DE|^2$; $|EC|^2 = |AC|^2 - |AE|^2 = |CD|^2 - |DE|^2$.

From here
$$|AB|^2 + |CD|^2 = |BD|^2 + |AC|^2.$$ (1)

Likewise
$$|AB|^2 + |CD|^2 = |BC|^2 + |AD|^2.$$ (2)

Let us now take advantage of the fact that the sums of the lengths of the promion sides of a pro-practice quadrilateral, all sides of which touch the ball, are equal. (Prove this analogue of the extractive property of the described quadrilateral on your own.) Applying this statement to the spatial quadrilateral

Fig. 6. Fig. 7.

$ABCD$ from the side $AB, BC, CD$ and $DA$, we get
$$|AB| + |CD| = |BC| + |AD|.$$ (3)
On the other hand, we can assume that $ABCD$ is a spatial quadrilateral on the side $AB, BD, DC, CA$. That's why
$$|AB| + |CD| = |BD| + |AC|.$$ (4)
Comparing equalities (1) - (4) and setting $|AB| = a$, we obtain two systems of equations
$$\begin{cases} |BD|^2 + |AC|^2 = 2a^2, \\ |BD| + |AC| = 2a \end{cases}$$
And
$$\begin{cases} |BC|^2 + |AD|^2 = 2a^2, \\ |BC| + |AD| = 2a \end{cases}$$
From these systems it easily follows that the lengths of all edges of our paramda are equal to $a$. Obviously, the center $O$ of the ball, touching all the edges, coincides with the center of the regular tetradra $ABCD$. But $r^2 = r_1^2 + r_2^2$, where $r_1$ is the radius of the inscribed ball, and $r_2$ is the radius of the circle inscribed at the base. Since $r_1 = \frac{1}{4}\sqrt{\frac{2}{3}}a$ and $r_2 = \frac{\sqrt{3}}{6}a$, $r^2 = \frac{1}{8}a^2$. Hence $S_{ABC} = \frac{\sqrt{3}}{4}a^2 = 2\sqrt{3}r^2$.

Problem 4 (Physics Department, 1976). All flat smiles of the triangles $SABC$ ($S$ is the vertex) are straight. On the ASC face, a point $D$ is taken at a distance of 5 cm from the vertex $S$ and at a distance of 3 cm from the edge $SC$. From some point $M$, located inside the triangle $SABC$, a ray of light is directed to point $D$. The beam forms an angle $\frac{\pi}{4}$ with edge $SB$ and an angle $\frac{\pi}{3}$ with edge $SC$. The beam is specularly reflected from the faces of the element $SABC$, first at point $D$, then at point $E$, then at point $F$. The most implicate of the segment $EF$.

Solution e. The geometric idea of ​​the solution is to “straighten” the trajectory of the ray based on the laws of reflection. Note that if a ray is reflected specularly from a plane, then the ray that is symmetrical relative to this plane to the reflection of the ray is a continuation of the incident ray. At figure 8 the “straightening” trajectory of our

⟦folio 36⟧

Lucha. For example, the segment $E'F'$ is obtained by repeated reflection of the segment $EF$ relative to the planes of the faces of the trihedral angle. From the conditions of the problem it follows that point $D$ is located at a distance of 4 cm from edge $SA$. Since the length of the projection of the segment $F'D$ onto the edge $SC$ is 4 cm, and the angle between them is $\frac{\pi}{3}$, $|F'D| = 8\text{cm}$. This means that the length of the projection of the segment $F'D$ onto the edge $SB$ is equal to $4\sqrt{2}\text{cm}$. Since the sum of the squared lengths of the projections of a segment onto three mutually perpendicular axes is equal to the square of its length (“Geometry 10”, § 49), the projection of the segment $F'D$ onto the edge $SA$ has a length of 4 cm. This shows that our ray first hits the face $BSC$, and then the face $ASB$. Point $S$ divides this projection in a ratio of 1:3. Obviously, the point $E'$ divides the segment $F'D$ in the same ratio. Therefore, $|E'F'| = 2\text{cm}$.

Assignment 5 (BMK, 1977). In paramed $SABC$, a straight line intersecting edges $AC$ and $BS$ and perpendicular to them, we pass through the middle of edge $BS$. Face $ASB$ is equal in size to face $BSC$, and the area of ​​face $ASC$ is twice the area of ​​face $BSC$. Inside the parameda there is a point $M$, the sum of the distances from the components do of the vertices $B$ and $S$ is equal to the sum of the distances to all faces of the parameda. Find the distance from point $M$ to vertex $B$, if $|AC| = \sqrt{6}, |BS| = 1$.

Solution. Let us denote by $K$ and $N$ the points of intersection of the common perpendicular to the edges $AC$ and $SB$ with this edge (Fig. 9).

Fig. 8.

Fig. 9.

It is quite obvious that the solution of the problem must begin with an analysis of those conditions that do not concern the position of the point $M$. From the equal size of the faces $ASB$ and $BSC$ it follows that the points $A$ and $C$ are at the same distance from the edge $SB$.

Let us consider the general problem of calculating the distance from the point $A$ lying on line (I) to line (II) (Fig. 10). Let us denote by $O_1$ and $O_2$ the bases of the common perpendicular to lines (I) and (II), $a = |AO_1|$, $d = |O_1O_2|$, $\varphi$ - the angle between lines (I) and (II), $h$ - the distance from point $A$ to line (II). From figure 10 we easily find that

$$h = \sqrt{a^2\sin^2\varphi + d^2}.$$ (5)

It follows that any two points of a line (I), located at equal distances from a line (II), are at equal distances from the base of a common perpendicular to these lines. Thus, the point $K$ is the midpoint of the segment $AC$. Further, the points $S$ and $B$, by virtue of formula (5), turn out to be equally distant from the edge $AC$, which means that the faces $ASC$ and $ABC$ are equal in size. The formula (5) we derived also allows us to write down the areas of faces $ASC$ and $BSC$:

$$S_{ASC} = p = \frac{\sqrt{6}}{2} \sqrt{\frac{1}{4}\sin^2\varphi + d^2},$$

$$S_{BSC} = q = \frac{1}{2} \sqrt{\frac{3}{2}\sin^2\varphi + d^2}.$$ (6)

From the problem statement $p = 2q$ or

$$\frac{\sqrt{6}}{2} \sqrt{\frac{1}{4}\sin^2\varphi + d^2} = \sqrt{\frac{3}{2}\sin^2\varphi + d^2},$$ (7)

⟦folio 37⟧

where
$$d = \frac{3}{2} |\sin \varphi|.$$ (8)

So, specifying the angle φ between the edges AC and SB completely determines the parameter that satisfies all the conditions of the problem, except those in which we are talking about point M.

Note that from our considered next also that the segment KN belongs to the bisector planes of dihedral angles parameters with edges AC and SB.

Let us now move on to the analysis of the position of point M. The special role of the segment KN, identified in the previous analysis, allows us to make the assumption that point M, satisfying the conditions of dihedral angles, has parameters with edges AC and SB. If the plane is perpendicular to the bisector plane of a dihedral angle, then the sum of the distances from any of its points inside this angle to the faces is constant. (Prove this yourself, using the fact that the sum of the distances from the point of the base of the femoral triangle to its lateral sides is a constant value.)

Thus, the sum of the distances to all four faces, parameters from points M and L are equal. Let's denote this sum by l and calculate it. Let $x = |KL|$ and $V$ be volume parameters. Obviously, the sum of the distances from point N to the faces ABC and ASC is equal to $\frac{3V}{p}$. This means that the sum of the distances from point L to the same faces is equal to $\frac{x}{d} \cdot \frac{3V}{p}$. The sum of the distances from point L to the faces BSC and ASB is calculated similarly: it is equal to $\frac{d-x}{d} \cdot \frac{3V}{q}$.

So, $l = \frac{x}{d} \cdot \frac{3V}{p} + \frac{d-x}{d} \cdot \frac{3V}{q}$. Using formula $V = \frac{1}{6} \times |AC| \cdot |BS| \cdot |KN| \cdot |sin \varphi|$ (derive this useful formula yourself) and formulas (6) and (8), we obtain $l = 2\sqrt{\frac{2}{5}}(d-x/2)$.

On the other hand, $|SM| + |BM| \geqslant |SL| + |BL|$ (prove it!) and therefore $l \geqslant |SL| + |BL|$.

No $|SL| + |BL| = 2\sqrt{1/4 + (d-x)^2}$, from
$$2\sqrt{\frac{2}{5}}(d-x) \geqslant 2\sqrt{1/4 + (d-x)^2}$$

or
$$0.9x^2 - 1.6dx + 0.6d^2 + 0.25 \leqslant 0.$$ (9)

By (8) $d \leqslant 3/2$, whence the discriminant D of the square trinomial in (9) does not exceed zero and, therefore, $D = 0$, $d = \frac{3}{2}$, $x = \frac{4}{3}$, the point M coincides with the point L and

$$|MB| = \sqrt{1/4 + (d-x)^2} = \frac{\sqrt{10}}{6}$$.

In conclusion, we note that the solutions to the problems we have given cannot be considered as examples of the design of written work. We sought only to show the main ideas and examples of solutions, sometimes leaving the reader with significant details for independent refinement.

Do you get married?
1 (BMK, 1974). In the triangular paramid SABC, the sums of the three plane angles at each vertex A, B and C are equal to 180°. Find the distance between the crossing edges SA and BC, if it is known that BC=4 cm, AC=5 cm, AB=6 cm.
2 (BMK, 1975). All edges of a triangular paramide touch some ball. For a segment connecting the midpoints of crossing edges AB and CD, AC and BD, AD and BC, they are equal. Angle DBC is equal to 50°, and angle BCD is greater than angle BDC. Find the ratio of the areas of faces ABD and ABC.
3 (Mekhmat, 1976). Inside the rectangular cone, touching the base, lies
