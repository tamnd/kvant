---
id: 2024-9-zaslavskiy-markelov-trisektsiya-ugla-i-drugie-klassicheskie-zadachi-ea546078
issue: kvant_2024_9
year: 2024
number: "9"
title: Angle trisection and other classical problems
authors:
  - Заславский А. А.
  - Маркелов С. В.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 37
page_last: 42
page_labels: 36-40
tag: PUDB
lang: en
source: kvant_digital
content_sha256: 3888602409a0bcaeef424fab25f3a45799f3794127d49e209f74d4e3ecca1636
prompt_sha256: draft-1
translated_from: content/ru/2024/09/articles/08_zaslavskiy-markelov-trisektsiya-ugla-i-drugie-klassicheskie-zadachi-ea546078.md
source_content_sha256: 19939f42b843e664d689f2026a6e2df4f83d0040f592f03c10fead69bbe85ed9
translation_model: draft
translation_run: en-draft-2026-11-03
translation_quality: draft
---

⟦folio none⟧

M A T H E A T I C H E K K R UZH OK

Angle trisection and other classical problems

A. ZASLAVSKY, S. MARKELOV

We know that the problem has no solution. We want to know how to solve it. A.Strugatsky, B.Strugatsky. "Monday starts on Saturday"

In school geometry, construction problems, as a rule, need to be solved with a compass and a ruler. The reason for this is historical tradition: these were the instruments that the geometers of Ancient Greece used. They formulated three problems that have become classic, one of which is trisection, or dividing a given angle into three equal parts, and the other two - doubling the cube, i.e. constructing a cube with a volume twice the given one, and squaring the circle, i.e. constructing a square whose area is equal to the area of ​​a given circle. The fact that it is impossible to solve all these problems using only a compass and a ruler without divisions was proven in the 19th century, when the problems were reformulated in algebraic language. For example, the problem of trisection of the angle M S 3 reduces to solving the cubic equation $x^{3} 3 x 1 0$. This equation has no rational roots, and it can be proven that its roots are not quadratic rationalities and cannot be constructed with a compass and straightedge (for more information on the proof of the impossibility of constructions, see [1]). However, you can try to solve the problem if a wider arsenal of tools is allowed, and also if some curve is previously drawn on the plane. The project proposed by the authors of the article at the XXXVI Summer Conference of the Tournament of Cities in August 2024 was devoted to these methods.

DOI: https://doi.org/10.4213/kvant20240903

Let's start with two problems known since ancient times.

⟦column⟧

Task 1. Divide a given angle into three equal parts using a compass and a ruler on which a unit segment is marked. The ruler can be applied to the plane so that it passes through a previously constructed point, and the ends of the segment marked on it lie on the previously drawn lines. Solution. Let us denote this angle by M and on the unit circle with center O take points A and B such that AOB M. Using a ruler with a marked unit segment, draw a straight line through B intersecting the circle and the continuation of the segment AO beyond the point O at points X, Y such that XY = 1 (Fig. 1). Then OBX OXB 2 XYA and AOB OBY OYB 3 XYA, therefore, XYA M 3.

⟦figure⟧

Fig. 1

Definition. Let the point move uniformly along a ray rotating at a constant angular velocity around its origin. Then the curve it describes is called the Archimedes spiral.

Problem 2. Let an Archimedes spiral be drawn on a plane. Divide this angle using a compass and ruler: a) into three equal parts; b) into n equal parts. Solution. a) Let us draw two rays from the center O of the spiral, forming an angle M, and find the points X, Y of their intersection with the spiral (Fig. 2). Let us plot the segment OX c OX on OY, divide the segment X c Y into three equal parts and draw through the dividing points a circle with center O intersecting the spiral at points P and Q. Then XOP POQ QOY. b) The solution is similar to the previous paragraph. The set of curves in the presence of which the trisection of an angle becomes feasible,

⟦folio 36⟧

---
running_head:
folio:
---

Using segments of lengths $\cos \frac{\varphi}{3}$ and $\cos \varphi$ on a trigonometric circle, it is easy to construct the angle $\frac{\varphi}{3}$.
c) If $b = 1/2$, $a = 1$, the root of the resulting equation is $\sqrt[3]{2}$.
The described method of angle trisection is a modification of the method proposed by R. Descartes in the book “La géométrie” (see Russian translation [2]). A description of this method can also be read in [3].

Problem 4. a) The hyperbola $xy = C$ is drawn on the plane. A circle with center $A$ lying on the hyperbola passes through the point symmetrically $A$ with respect to the center of the hyperbola (Fig. 4). Prove that

Problem 3. a) Let the parabola $y = x^2$ be drawn on the plane. A circle with center at point $A (a; b)$ passes through the vertex of the parabola (Fig. 3). Write an equation whose roots are the abscissa of the remaining points of intersection of the circle and the parabola.
b) Using a drawing on the parabolic plane, divide the given angle into three equal parts.
c) Using paraboly, solve the problem of doubling the cube.

Solution. a) Consider the system of equations given by a parabolic and a circle:
$$\begin{cases} y = x^2, \\ (x - a)^2 + (y - b)^2 = a^2 + b^2. \end{cases}$$
Eliminating $y$ and considering that the root $x = 0$ corresponds to the vertex, we arrive at the equation
$$x^3 - (2b - 1)x - 2a = 0.$$
b) If $b = 2$, $a = \cos \varphi$, the roots of the resulting equation are $2\cos \frac{\varphi + 2k\pi}{3}$, $k = 0, 1, 2.$

Fig. 4
In other cases, the intersection points of a hyperbola and a circle are the vertices of a regular triangle.
b) Using an equilateral hyperboly drawn on the plane, divide the given angle into three equal parts.

Solution. a) The first (algebraic) method. Let the point $A$ have coordinates $(r\cos \varphi; r\sin \varphi)$. Then the circle can be specified by parametric equations:
$$\begin{cases} x = r\cos \varphi + 2r\cos t, \\ y = r\sin \varphi + 2r\sin t. \end{cases}$$
Substituting these expressions into the hyperbola equation, after simple transformations we obtain
$$\cos \frac{t - \varphi}{2}\sin \frac{3t + \varphi}{2} = 0.$$

⟦folio 37⟧

---
running_head:
folio:
---

The first factor corresponds to a point symmetrical $A$ relative to the center of the hyperbola, the second determines the three points forming a regular triangle.

The second (geometric) method. Let us use the property of an equilateral hyperbola, which can be read, for example, in [4]. Consider the triangle $\Delta$ formed by the intersection points of a circle and a hyperbola. An equilateral hyperbola circumscribed about a triangle passes through its orthocenter, and a point symmetrical to the orthocenter relative to the center of the hyperbola lies on the circumcircle of the triangle. Therefore, $A$ is the ortcenter of $\Delta$. Since $A$ is also the circumcenter of $\Delta$, the triangle $\Delta$ is regular.

6) Let us take a point $A$ on the hyperbola such that the ray $OA$ forms an angle $\varphi$ with the abscissa axis, draw a circle with center $A$ passing through the point, symmetrically $A$ relative to the center of the hyperbola, and find the point $B$ of intersection of the circle with hyperbole (Fig. 5). Then the angle between

Fig. 5

the straight line $AB$ and the x-axis is $\varphi/3$. To verify this, write an equation for the line passing through the points $A$ and $B$ and find its slope.

Problem 5. a) A hyperbola is drawn on the plane; its asymptotes form an angle $2\pi/3$. A circle passes through the vertex of one vertex of a hyperbola and the focus of another

⟦folio 38⟧

---
running_head:
folio:
---

The root $z = -1$ corresponds to the vertex of the hyper-
pain. The second set is reduced to the form
$(z - a)^3 - 3$, therefore the other three
the roots are the vertices of the correct
triangle.
6) The eccentricity of the hyperbola in the case
specifying it by the canonical equation is equal to
$$e = \sqrt{1 + \frac{b^2}{a^2}}.$$
Let a circle with center $O$ passing
through the vertex $V$ and focus $F$ of the hyperbola,
intersects the hyperbola at the point $P$ (Fig. 7).

Fig. 7

Then $\angle POF = \angle VOF/3$. Try it yourself
prove this fact.
Do the Summer Cities Tourism Conference
the authors of the article did not know what
horse-drawn horses other than those listed above,
allow trisection of the angle.
At the conference, A. Sokolov proposed al-
Trisection algorithm using arbitrary
different from the horse-drawn parabola.

Task 6. Trisection the angle,
using free horse racing, excellent
from a parabola.

Solution. Let us choose a coordinate system in
which a given tram, different from a parabola,
has the equation $y^2 = (e^2 - 1)(x^2 - 1)(e -$
eccentricity). Take a circle with center at point $(e^2/8; b)$ passing through
the top of the tram $(-1; 0)$.

Having excluded the equations from the system, I set
dividing the circle and conca, $y$ and dividing
the resulting equation for $(x + 1)$, we obtain
$$x^3 - \frac{3}{2}x^2 - \left(\frac{15}{16} + \alpha\right)x + \left(\frac{25}{16} + \alpha\right) = 0,$$
where $\alpha = 4b^2(e^2 - 1)/e^4$. Having made a replacement
$t = (x - 1/2)/k,$
$k = \sqrt{3/4 + 4\alpha/3},$
Let's put this equation in the form
$$4t^3 - 3t + 3/8k = 0.$$
At
$$b^2 = \frac{27e^4}{64(e^2 - 1)} \left( \frac{1}{16\cos^2\varphi} - 1 \right)$$
we find that $t = \cos \frac{\varphi}{3}$. Moreover, for the ellipse
sa $(e < 1)$ must satisfy the condition
$\cos \varphi \ge 1/4$, and for a hyperbola – counter-
false. But an arbitrary angle can be
bet as a sum or difference of parts,
satisfying this condition.

Other trisection problems

Although this can be done using a compass and
ruler trisection of an arbitrary angle is not
perhaps for many angles this problem can be solved
Reshima. Moreover, among them there are corners,
which cannot be constructed with compasses and lines
neykoy. For example, consider the following
a simple way to trisection an angle equal to $2\pi/n,$
for any $n$ not a multiple of 3.

Problem 7. Regular $n$-gon with centrifugal
rum $O$ is inscribed in a regular triangle
(Fig. 8, here $n = 7$). Prove that
$\angle A = \angle O/3$.

⟦folio 39⟧

---
running_head:
folio:
---

Solution. Let $BC$ be the side of the $n$-gon lying on the base of the triangle, and $X, Y$ be the vertices through which the sides pass. Then the triangle $AXY$ is regular (Fig. 9). One of the sides of the $n$-gon containing $X$ forms an angle with $BC$ greater than $60^\circ$, and the other forms a lesser angle. This uniquely defines the vertex $X$: at $n = 3k + 1$ we have $BX = XY = YC$, and at $n = 3k - 1$ we have $CX = XY = YB$. In the first case
$$\angle BAC = \pi/3 - 2\angle CAY = \angle XYC - \pi/3 = \angle BOC/3.$$
In the second
$$\angle BAC = 2\angle BAY - \pi/3 = 2\pi/3 - \angle AYB = \pi/3 - \angle XYB = \angle BOC/3.$$
Let us now assume that, in addition to a compass and a ruler, we have a “trisector” (i.e., a tool for dividing an arbitrary angle into three equal parts). Let's try to find out how much this increases our capabilities in construction tasks. In particular, the question asked what regular polygons can be constructed using a compass, a ruler and a trisector.

Problem 8. Using a compass, ruler and trisector, construct a regular heptagon.

Solution. Let $\Omega$ be a circle with center at the origin and radius 6 (Fig.10). Let's take points $A(6;0), Q(-3;0), R(3;0)$. Let $K, L$ be the vertices of two regular triangles with base $QR$. Let's construct an arc $KL$ with a center at point $P(-1;0)$ and divide it into three equal parts by points $S$ and $T$. The points $B$ and $G$ of intersection of the line $ST$ with the circle $\Omega$ is the vertex of the regular heptagon $ABCDEFG$.

To justify the construction, we show that if the point $B$ is the vertex of a regular heptagon, then its projection onto the segment $QA$ coincides with the projection of the point $S$. To do this, let us verify the equality
$$PB \cos \frac{2\pi}{7} = PS \cos \angle SPA - OP,$$
i.e.
$$6 \cos \frac{2\pi}{7} = \sqrt{28} \cos \frac{\arccos(1/\sqrt{28})}{3} - 1.$$
Direct verification shows that both the left and right sides of this equality satisfy the equation $x^3 - 21x - 7 = 0$, which has a single positive root.
Other examples of constructing regular polygons with circumference, ruler and trisector can be found in [5].

Problem 9*. What other regular polygons can be constructed using a trisector, a compass and a ruler? (Recall that according to Gauss’s theorem, using a compass and a straightedge, one can construct a regular $N$-gon whenever $N = 2^m p_1 \dots p_k$, where $p_1, \dots, p_k$ are various prime numbers of the form $2^{2l} + 1$.)

Answer: $N = 2^m 3^n p_1 \dots p_k$, where $p_1, \dots, p_k$ are various prime numbers of the form $2^p 3^q + 1$. In particular, you can construct 13- and 19-gons, but you cannot construct an 11-gon. (See the proof of Gauss's theorem in [6].)

In conclusion, two more problems about trisection using unusual tools.

Problem 10. Given a rectangular sheet of paper $ABCD$ and a point $X$ on side $BC$. Exist in straight lines, divide

⟦folio 40⟧

---
running_head:
folio:
---

Angle XAD into three equal parts (Fig. 11).
There are no tools, you can only squeeze the sheet and move the intersection points of the force lines. In this case, it is possible to ensure that during the next step, two previously offset points fall on two previously constructed lines.

Solution. Let us mark a point P on side AB that is sufficiently close to A, according to the sheet along the straight line PP' || AD and mark a point Q on AB such that AP = PQ. Let's bend the sheet along a straight line so that Q falls on the straight line AX at some point Q', and A falls on the point A' on PP'.

Let M be the midpoint of A'Q', T be the projection of A' onto AD. Points A, Q, Q', A' form an equilateral trapezoid, therefore A'M = AP = A'T. Primangular triangles ATA', AMA' and AMQ' are equal, so rays AA' and AM divide angle XAD into equal parts.

Task 11. a) “Half-meter” is a device that, for any convex figure and a point on its boundary, constructs a straight line dividing the area of ​​the figure in half. Using a half-meter, a compass and a ruler, divide the given angle into three equal parts.

b) Divide the angle into n equal parts using a half-measure.

c) Using a half-meter, a compass and a ruler, draw a circle.

Solution. a) Construct a sector OAB with ∠AOB = φ and divide its area in half by a straight line passing through A and intersecting the segment OB at point C (Fig. 12). Let us take a point D outside the sector such that S_OAD = 2S_OAC/3, and draw a straight line through O dividing the area of ​​the figure ODAB (see the figure bounded by the same color at figure 12). This line divides angle AOB in the ratio 1:2.

6) This problem is solved similarly to the previous paragraph.

c) Construct a straight line AC, dividing the area of ​​the sector OAB with the right angle AOB in half. Then the problem comes down to constructing a square whose area is 8 times the area of ​​triangle OAC.

We invite readers to think about whether it is possible to double a cube using a half-meter, a compass and a ruler.

The authors thank B.R. Frenkin for his assistance in preparing the project and rare «Kvant» for useful comments that made it possible to improve the personal level of the article.

References

1. M. Alexnovits, A. Kanel-Belov, A. Suleikin. The complexity of algorithms for constructing compasses and rulers. – Mathematical education, ser. 3, issue 33, 2024, pp. 155–181.

2. R. Decarm. Geometry. With an appendix of selected works of P. Fermat and correspondence of Descartes. – M.: URSS, 2010.

3. W. Y. P. Ball, G. S. M. Coxemer. Mathematical research. – M.: Mir, 1986.

4. A. Akopyan, A. Zaslavsky. Geometric properties of second order curves. – M.: MTsNMO, 2011.

5. A. M. Gleason. Angle Trisection, the Heptagon, and the Triskaidecagon. – The American Mathematical Monthly, vol. 95, 1988, No. 3, p. 185–194.

6. A.V. Skopenkov. Resolution in radials. In the book “Elements of Mathematics in Problems.” – M.: MTsNMO, 2018.
