---
id: 1974-2-kushnir-metod-vspomogatelnogo-elementa-ebce4679
issue: kvant_1974_2
year: 1974
number: "2"
title: Helper Method
authors:
  - Кушнир И. А.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 48
page_last: 53
page_labels: 46, 47, 48, 50, 51
tag: P3SM
lang: en
source: kvant_digital
extraction: vision
content_sha256: f57ec7fb05ef24d834d1b1851636b245980ddd6a814b9e2107d7212022414c3b
prompt_sha256: draft-1
translated_from: content/ru/1974/02/articles/12_kushnir-metod-vspomogatelnogo-elementa-ebce4679.md
source_content_sha256: 9fff92e5fedd3328d7e0f386d1f0728df2af4390465ac9fa251445d3795ab47e
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 46⟧

Method
auxiliary
element
I. A. Kushinr

The solution of a large group of problems in geometry is facilitated by the introduction of additional elements that are not directly specified in the conditions of the problem. These elements can be lengths, areas, volumes, angles. With their help, an equation is drawn up where the unknown element is the desired element or an element with the help of which the desired one can be easily found. Sometimes, with the help of this element, it is not an equation that is drawn up, but a correspondence required by the conditions of the problem.

Auxiliary linear element
In planimetric problems, it is convenient to introduce a linear element or a ratio of linear elements if the figures under consideration are similar. Then, using proportions or auxiliary geometric constructions, an equation is drawn up in which the introduced element as a member of the equation is reduced, and it is not difficult to find the required one.

Let's consider the solution to the problem proposed at Novosibirsk State University.

Problem 1 (NSU, 1969). Through a certain point taken inside the triangle, three lines are drawn corresponding to parallel to the sides of the triangle. These lines divide the triangle into six parts, three of which are triangles with areas $S_1, S_2, S_3$. Find the area of ​​this triangle.

Starting to solve, we replace the similarity of triangles with area $S_1, S_2, S_3$ (Fig. 1) and triangle ABC with area S. In addition, the sum of the lengths of sides DQ, QE and FK of small triangles is equal to the length of side BC of triangle ABC. Using these sides as auxiliary elements, we obtain the equation

$$\frac{\sqrt{S_1}}{\sqrt{S}} = \frac{DQ}{BC}, \frac{\sqrt{S_2}}{\sqrt{S}} = \frac{QE}{BC}, \frac{\sqrt{S_3}}{\sqrt{S}} = \frac{FK}{BC}.$$

Let's add them up:

$$\frac{\sqrt{S_1} + \sqrt{S_2} + \sqrt{S_3}}{\sqrt{S}} = \frac{DQ + QE + FK}{BC} = 1.$$

So, $S = \left( \sqrt{S_1} + \sqrt{S_2} + \sqrt{S_3} \right)^2$.

It is recommended to enter an auxiliary segment if linear elements are not given in the problem conditions and you need to find the relationship between angles.

⟦folio 47⟧

Task 2 (MSU, physics department, 1967).
Find the cosine of the angle at the base of an equilateral triangle, knowing that the point of intersection of its altitudes lies on the inscribed circle of the triangle.

By condition, the orthocenter $H$ of triangle $ABC$ ($AB = AC$) must be inside the triangle, so $\angle A < 90^\circ$ (Fig. 2). Let us introduce an auxiliary element $a$—the length of the segment $BD$, denote $\angle ABC$ by $x$, and the center of the inscribed circle by $O$. Then

$$\angle HCD = \frac{\pi}{2} - x, HD = a \mathrm{tg} \left( \frac{\pi}{2} - x \right) = a \mathrm{ctg} x = 2OD, OD = a \mathrm{tg} \frac{x}{2},$$

where

$$\mathrm{ctg} x = 2 \mathrm{tg} \frac{x}{2}, \mathrm{tg}^2 \frac{x}{2} = \frac{1}{5},$$

$$\cos x = \frac{2}{3}.$$

The introduction of an auxiliary element for finding the relationships of various geometric quantities is especially important.

Task 3 (MAN, 1968). The large base of a regular truncated quadrangular paramid forms an angle $\alpha$ with its lateral boundary, and an angle $\beta$ with the plane passing through the adjacent sides of the upper and lower base. Find the ratio of the areas of the bases.

Let us introduce an auxiliary element $a$—the length of the side of the large base of the paramid (Fig. 3). The area of ​​this base will be $a^2$. The side length of the top base can be expressed in terms of $a$, $\alpha$ and $\beta$. Let us consider the auxiliary trapezoid $EE_1F_1F$, which is obtained in the section of the paramid by a plane perpendicular to the base and passing through the midpoints of sides $AB$ and $CD$. Let us introduce more auxiliary segments $E_1H = h, E_1F_1 = x$. Then

$$HF = \frac{1}{2} (a + x),$$

$$EH = \frac{1}{2} (a - x), h = HF \mathrm{tg} \beta =$$

Fig. 2.

$$= \frac{1}{2} (a + x) \mathrm{tg} \beta = EH \mathrm{tg} \alpha =$$

$$= \frac{1}{2} (a - x) \mathrm{tg} \alpha.$$

We obtain the equation $(a + x) \mathrm{tg} \beta = (a - x) \mathrm{tg} \alpha$, from which

$$x = \frac{a \sin (\alpha - \beta)}{\sin (\alpha + \beta)},$$

$$\frac{s}{S} = \frac{x^2}{a^2} = \frac{\sin^2 (\alpha - \beta)}{\sin^2 (\alpha + \beta)}.$$

Auxiliary element - area or volume

The introduction of area and volume as an auxiliary element is similar to the introduction of a linear element. By comparing the areas and volumes of individual parts of the figure, one can obtain either an equation of the relative unknowns of the problem or the necessary correspondence. It is better to find those areas and volumes, the sum (difference) of which gives the area of ​​a given figure, as well as the ratio of areas

⟦folio 48⟧

those figures whose linear elements are either the required ones or are components of the necessary correspondence.

Problem 4 (MSU, Mechanics and Mathematics, 1960). A straight line parallel to the base is drawn through the chain of a regular triangle. An arbitrary point M is taken on this line of the interior triangle. Prove that the distance from point M to the base of the triangle is the arithmetic mean of the distances from point M to the sides of the triangle.

Let $h_1, h_2, h_3$ be the distances from point M to the sides of the triangle BC, AB, AC, respectively (Fig. 4). It is clear that $S_{\triangle AMB} + S_{\triangle CMB} + S_{\triangle AMC} = S_{\triangle ABC}$, or $ah_1 + ah_2 + ah_3 = ah$, where $a$ is the side of triangle ABC, $h$ is its altitude. So $h = h_1 + h_2 + h_3$, but $h_1 = \frac{h}{3}$, so $h_2 + h_3 = h - h_1 = \frac{2}{3}h = 2h_1$, $h_1 = \frac{h_2 + h_3}{2}$.

Problem 5. Given a quadrilateral ABCD circumscribed about a circle. Prove that the square of the distances from the chain of the circle to the opposite vertices is related as the product of the sides, converging at the emix vertices.

The notation is given on figure 5. It is required to prove that $\frac{x^2}{y^2} = \frac{ad}{bc}$.

The heights of triangles AOD and BOC are equal, so

$$\frac{S_{\triangle AOD}}{S_{\triangle BOC}} = \frac{d}{b}.$$

On the other side,

$$\frac{S_{\triangle AOD}}{S_{\triangle BOC}} = \frac{xv \sin \varphi_5}{yz \sin \varphi_6}.$$

Let us prove that $\sin \varphi_5 = \sin \varphi_6$. To do this, note that $\varphi_1 + \varphi_2 + \varphi_3 + \varphi_4 = \pi$ (this is the positive of the sum of all angles of the quadrilateral), $\varphi_1 + \varphi_2 + \varphi_5 = \pi$, $\varphi_4 + \varphi_3 + \varphi_6 = \pi$. It follows that $\varphi_5 + \varphi_6 = \pi$, $\sin \varphi_5 = \sin \varphi_6$, and from formula (2) we obtain

$$\frac{S_{\triangle AOD}}{S_{\triangle BOC}} = \frac{xv}{yz}.$$

From correspondence (1) and (2') we have $\frac{xv}{gz} = \frac{d}{b}$, similarly to $\frac{xz}{yv} = \frac{a}{c}$. Variable the last two equalities, we get

$$\frac{x^2}{y^2} = \frac{ad}{bc},$$

and dividing the first of them by the second, we get

$$\frac{v^2}{z^2} = \frac{cd}{ab}.$$

Let's analyze a problem where the auxiliary element is volume.

*) Additional material on the area method can be read in the magazine «Kvant», 1971, No. 12.

⟦folio 50⟧

Fig. 8.

gonometric functions, then an auxiliary angle is introduced. Then, using the theorem of sines or cosines, solving the triangle to find the components to write a certain condition in the form of an equation.

Task 8 (MSU, Mechanics and Mathematics, 1962). An arbitrary straight line is drawn through the chain of a regular triangle in the emodret plane of the triangle. Prove that the sum of squared distances from the vertices of a triangle to the same straight line does not depend on the choice of straight line.

Let point $O$ be the center of triangle $ABC$ (Fig. 8). Points $D, E, F$ are, respectively, the projections of the vertices $A, B, C$ onto the line $l$, $R$ is the radius of the circle circumscribed about the triangle $ABC$. Let us introduce an auxiliary angle $\varphi$, denoting it $\Rightarrow BOE$. Then

$$\Rightarrow AOD = \Rightarrow AOB - \Rightarrow BOD = \varphi - \frac{\pi}{3}.$$

(check for yourself that the sum in square brackets is $\frac{3}{2}$).

Task 9 (MIPT, 1967). At the base of the direct axis ABCD, a plane is drawn that intersects the upper base $A_1B_1C_1D_1$. The trihedral angles $B$ and $D_1$ contain balls that touch the plane and have radii $r = \frac{a}{5}$, $R = \frac{a}{4}$. Name the height of the paralleleped.

The diagonal section $DBB_1D_1$ of the parallelepiped (Fig. 9) will pass through the centers of the balls $O$ and $O_1$. Let $L$ and $L_1$ be the points of contact of the balls and the bases of the parallelepiped, $N$ and $N_1$ be the points of contact of the balls with a given plane (we do not yet know whether they are located in the parallelepiped)

Fig. 9.

⟦folio 51⟧

or inside it, but we won’t need it), OF and $O_1E_1$ are the bisketrices of the angles NOL and $N_1O_1L_1$ (point $F$ is the middle of BD), $EE_1$ is the height of the parallelepid, $OL = ON = r$, $O_1L_1 = O_1N_1 = R$. Let's put $\Rightarrow BFE_1 = 2\alpha$, $L_1E_1 = x$, $E_1B_1 = y$, $FE = z$. Then

$$h = z \mathrm{tg} 2\alpha, \quad z = FB - BE = \frac{a \sqrt{2}}{2} - y, \quad y = a \sqrt{2} - x - D_1L_1 = a \sqrt{2} - x - R \sqrt{2} \quad \text{и} \quad z = x + R \sqrt{2} - \frac{a \sqrt{2}}{2} = x - \frac{a \sqrt{2}}{4}.$$

From the similarity of triangles $O_1L_1E_1$ and $OLF$ it follows that $\frac{x}{R} = \frac{FL}{r}$, $FL = FB - LB = \frac{a \sqrt{2}}{2} - r \sqrt{2} = \frac{3a \sqrt{2}}{10}; \quad x = \frac{3}{8} a \sqrt{2}, \quad z = \frac{a \sqrt{2}}{8}$.

From triangle $OLF$ there is $\mathrm{tg} \alpha = \frac{r}{FL} = \frac{\sqrt{2}}{3}$, from which $h = \frac{3}{14} a$.

Problem 10 (MSU, Mechanics and Mathematics, 1963). The lateral edge of a regular triangular parallelepid is equal to $b$, the angle between the lateral boundaries is equal to $\varphi$. Find the side of the base.

Let us drop perpendiculars from the points $B$ and $C$ to the lateral edge AS (Fig. 10). It is easy to verify that the base of both these perpendiculars is one point $D$ (prover), and therefore $\star BDC = \varphi$.

Let us introduce the auxiliary angle $\star BAS = \alpha$ and draw the apothem SK

Fig. 10.

pyramids. It is clear that $AB = 2AK = 2b \cos \alpha$. Therefore, to solve the problem it is enough to calculate $\cos \alpha$. Since $\alpha < 90^\circ$, then from the triangle $BAD$ we have $\alpha = \arcsin \frac{BD}{AB}$.

In turn, the length of the segment $BD$ is determined from the triangle $BLD$ (DL is the height of the triangle $BDC$):

$$BD = \frac{BL}{\sin \frac{\varphi}{2}} = \frac{AB}{2 \sin \frac{\varphi}{2}}.$$

$\alpha = \arcsin \frac{1}{2 \sin \frac{\varphi}{2}}$, from

$$AB = b \sqrt{4 - \frac{1}{\sin^2 \frac{\varphi}{2}}}.$$

Nanny has the right

1 (MIPT, 1969). A circle is inscribed in triangle $ABC$, tangent to side $AB$ at point $D$ and side $BC$ at point $E$. Find the angles of the triangle if

$$\frac{BD}{AD} = \frac{1}{2}, \frac{BE}{CE} = \frac{1}{3}.$$

2 (MIPT, 1969). In a regular tetrahedron $ABCD$, the segment $MN$ connects the midpoint of edge $AC$ with the center of face $BDC$, and point $E$ lies at the midpoint of edge $AB$. Find the angle between the segments $MN$ and $DE$.

3 (MEPhI, 1971). In a trapezoid whose bases are $a$ and $b$, a line parallel to the base is drawn through the point of intersection of the diagonals. Find the length of the segment of this straight line cut off by the sides of the trapezoid.

4 (MIET, 1970). Given a triangle $ABC$, on side $AC$ a point $E$ is taken so that $AE : EC = a$, on side $AB$ a point $D$ is taken so that $AD : DB = b$. Segments $CD$ and $BE$ were carried out. Find the ratio of the area of ​​the resulting quadrilateral to the area of ​​the given triangle.

5 (MSU, physicist, 1969). A paramid is inscribed in a ball, the lateral edges of which are equal to $c$. Its base is a rectangle, the sides of which subtend uggs $\alpha$ and $\beta$ radians into sections of the ball by the planes of the lateral faces. Determine the radius of the circumscribed sphere.

6 (MSU, Mechanics and Mathematics, 1961). On a circle of radius $R$, two points $A$ and $B$ are given, the distance between which is $l$. What is the maximum value that the sum $AC^2 + BC^2$ can take if the point $C$ also lies on this circle?

7 (NSU, Mechanics and Mathematics, 1969). The dihedral angle at the lateral edge of a regular quadrangular paramid is equal to $\alpha$, the radius of the inscribed ball is equal to $R$. Find the complete surface of the paramid.
