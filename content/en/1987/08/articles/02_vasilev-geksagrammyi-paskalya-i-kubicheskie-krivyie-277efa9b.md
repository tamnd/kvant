---
id: 1987-8-vasilev-geksagrammyi-paskalya-i-kubicheskie-krivyie-277efa9b
issue: kvant_1987_8
year: 1987
number: "8"
title: Pascal's hexagrams and cubic curves
authors:
  - Васильев Н. Б.
rubric: osnovnye-stati
page_first: 4
page_last: 10
page_labels: 2-8
tag: A6G7
lang: en
source: kvant_digital
extraction: vision
content_sha256: ef6613c3505ede5dab93da7baa9cd51f369d37ef0a1c3694d8f54cbb4bbcf724
prompt_sha256: draft-1
translated_from: content/ru/1987/08/articles/02_vasilev-geksagrammyi-paskalya-i-kubicheskie-krivyie-277efa9b.md
source_content_sha256: 10f89639b1e20ad21b8660b38c2d927006ea04d3bd2fb5da2e0561969848fb7d
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 2⟧

PASCAL'S HEXAGRAMS
AND CUBIC CURVES

Candidate of Physical and Mathematical Sciences
N. B. VASILIEV

In 1640, Blaise Pascal (he was then seventeen years old) discovered the remarkable property of a six-link closed broken line inscribed in a circle. In the emerging configuration (Fig. 1), which Pascal called the “mystical hexagram,” some three points of intersection inevitably turn out to lie on the same straight line. Pascal published his discovery in the form of a poster, published in fifty copies for distribution and forwarding to individual scientists. Pascal’s work and Gerard Desargues’s short work, “A Sample of One of the General Methods for Using Perspective,” published four years earlier, laid the foundation for a new mathematical discipline—project geometry. It was then that it was realized that “ancient knowledge is not everything” (Pierre Fermat’s expression) - until then, the achievements of the geometers of Ancient Greece were considered unsurpassed.

With the name of one of the last ancient geometers - Pappus of Alexandria, who lived in the 3rd century AD. e., - a related theorem about a six-link broken line, similar to Pascal’s theorem; This is where we will begin the story.

We strongly recommend that you conduct an experimental test of these theorems:

make a few round and neat drawings - this will not only convince you of the validity of the theorems, but also allow you to understand the delight that enveloped Pascal and his contemporaries (and perhaps Pappus) in their time.

We will not dwell on geometric proofs and numerous corollaries of the theorems of Pappus and Pascal, touching upon only one important topic - the use of geometric transformations, including central projection. Our main goal is to show that the properties of the “hexagram” are only part of the manifestation of a more general fact related to algebraic geometry, one of the most profound branches of mathematics of the 19th and 20th centuries. We will see that the same fact obliges the main property of the operation of “addition of points” on a cubic curve (its applications in number theory are discussed in the last issue of Kwan).

In the final series figure the points of three colors and the straight lines connecting them form configurations where there are amazing coincidences of intersection points (which arose in the configurations of Pappus and Pascal).

Fig. 1. Pascal’s theorem. Whatever six points are taken on the circle and no matter how their numbers are numbered 1, 2, 3, 4, 5, 6, the intersection points of the lines 12 and 45, 23 and 56, 34 and 61 will lie on one line (it is called the Pascal line of the inscribed six-link hexagon 123456). Another formulation: the intersection points of the other false sides of an inscribed hexagon or their extensions lie on the same straight line.

⟦folio 3⟧

Pappus's theorems

Let's start with a comparatively simple theorem about 6 points lying on two lines a and b (Fig. 2a).

Theorem 1a. Let the vertices of a six-link closed broken line lie alternately on two straight lines. If two pairs of opposite links of this broken line (1-e and 4-e, 2-e and 5-e) are parallel, then the remaining pair of links (3-e and 6-e) are parallel.

The idea of ​​proof to students using geometric transformations. Let straight lines a and b intersect at point O (Fig. 2b). Consider two geometries with center O: one that takes the straight line $A_1B_1$ to $A_3B_2$, and the other that takes $A_3B_3$ to $A_2B_1$. Their composition—the result of sequential execution of these geometries—translates the line $A_1B_3$ into $A_2B_2$, therefore $A_1B_3 \parallel A_2B_2$. Note that it is convenient to follow the transformations of the point $A_1$ by applying the geometries in one order: $A_1 \rightarrow A_3 \rightarrow A_2$, and the points $B_3$ in another: $B_3 \rightarrow B_1 \rightarrow B_2$. The result, of course, does not depend on the order in which the two geometries are applied: their composition is also a geometry with center O, the coefficient of which is equal to the product of the coefficients of these two geometries. In the case when the lines a and b are parallel (Fig. 2b), in the same reasoning the geometry must be replaced by parallel translations.

Thus, Theorem 1a is simply a geometric expression

Fig. 3. Pappus confiduration of 9 points and 9 lines. Whatever tracks of points $A_1$, $A_2$, $A_3$ and $B_1$, $B_2$, $B_3$ on lines a and b, points $C_1$, $C_2$, $C_3$ are the intersections of lines $A_1B_1$ and $A_3B_2$, $A_2B_2$ and $A_1B_3$, $A_3B_3$ and $A_2B_1$ will lie on the same line (Theorem 1).

commutativity of multiplication (and addition) of numbers; this explains the important role of Pappus's theorem in the foundations of geometry (see, for example, the book [5]).

Pappus's 6-point theorem is only a very special case of a much deeper theorem (also named after him) about a configuration consisting of 9 points and 9 lines (Fig. 3).

Theorem 1. Let three red lines intersect three red lines at two straight points. If two trains of black dots lie on two straight lines (other than red and blue), then the remaining train of black dots lies on a straight line.

The Pappus configuration is replaced by the fact that all three straight lines - blue, red and black - participate in it equally: at each of the 9 points three straight lines of different colors intersect.

Having started to build such a configuration, we will find that if the first six points $A_1$ are unsuccessfully chosen,

Fig. 2. Pappus hexadrams. The poles of the vertices of the broken line $A_1B_1A_2B_2A_3B_3$ lie alternately on two straight lines a and b: the first four are chosen arbitrarily, then $A_3$ and $B_3$ are constructed so that $B_2A_3 \parallel A_1B_1$, $A_3B_3 \parallel B_1A_2$, then necessarily $B_3A_1 \parallel A_2B_2$ (Theorem 1 a). Proof: a), b) equality variables $OA_1/OA_3 = OB_1/OB_2$ and $OA_3/OA_2 = OB_3/OB_1$; c) adding the equalities $\overrightarrow{A_1A_3} = \overrightarrow{B_1B_2}$ and $\overrightarrow{A_3A_2} = \overrightarrow{B_3B_1}$, we obtain $\overrightarrow{A_1A_2} = \overrightarrow{B_3B_2}$.

⟦folio 4⟧

Fig. 4. Reduction of Pappus’s general theorem to a special case (Theorem 1a). We draw the Pappus configuration on glass or arbitrary dimensions, place it in an inclined plane so that the straight line $C_1C_2$ is horizontal, and project it onto the horizontal plane using a light source $S$ - the center of the projection - located above the plane at the same height as the straight line $C_1C_2$. The projection produces a Pappian heskadrama: pairs of lines of different directions intersecting at points $C_1, C_2$ and $C_3$ are projected into pairs of parallel lines, therefore $C_3$ lies on the line $C_1C_2$.

$B_1, A_2, B_2, A_3, B_3$ new points $C_1, C_2, C_3$ may be far outside the drawing. For example, at $A_1B_1 \parallel A_3B_2$ the point $C_1$ will simply “go to infinity”. (In this case, the line $C_2C_3$ will also be parallel to $A_1B_1$ and $B_2A_3$.) If two of the three points $C_1, C_2$ and $C_3$ “go to infinity”, then according to Theorem 1 a and the third should also be “at infinity”; in this case it is convenient to say that all three points $C_1, C_2, C_3$ lie on the same “veclon projection” (Fig. 4); artists since Leonardo da Vinci and Albrecht Dürer have called it “linear perspective.” A projection with center $S$ assigns to each point $M$ the intersection point $M'$ of straight line $SM$ with some plane $p$ (projection plane). It is important that in this case the images of the point of one line of new ones lie on the same line, although some intersecting lines turn into parallel ones (their intersection point “goes to infinity”) and vice versa.

Desargues’ idea underlying design geometry is remarkable: mentally supplement the plane with “points at infinity”, in each of which straight lines parallel to each other intersect, and consider all these points to lie on one “line at infinity” - then with the central projection of one plane onto another, no exclusionary ones arise, this transformation becomes mutually significant. This “project” point of view will be a constant side theme of our story, but we will not develop it in detail here (see [1], [2]).

Pascal configurations

Pascal's theorem can be given the same colorful appearance as Pappus's 9-point theorem.

Theorem 2. Let three red lines intersect three half lines at ten black points. If six of these points lie on the same circle, then the other three lie on the same straight line (Fig. 1).

In a certain sense, the “inverse” theorem is also true.

Theorem 2'. If out of the number of black points where the red tracks intersect with three half lines, three lie on a straight line, and another five lie on a circle, then the point also lies on the same circle.

As Pascal himself immediately realized, his theorem can be significantly generalized: along with a circle, an ellipse, a hyperbola or a parabola can appear in it, or any of these curves can be obtained by the central projection of a circle. Therefore, from the Pascal configuration for a circle, one can obtain a configuration for any of these curves.

All these curves are called second-order curves, since from them we can define an equation of the form $P(x, y) = 0$, where $P$ is a polynomial of the second degree:

$$P(x, y) = ax^2 + bxy + cy^2 + dx + ey + f.$$

It is curious that Pascal's theorem remains true for the degenerate case when the polynomial $P$ is decomposed into two linear factors: in this case of the second order $P(x, y) = 0$ turns into a pair of lines, and Pascal's theorem turns into Pappus's theorem.

There are many different proofs of Pascal's theorem for the circle (see, for example, «Kvant» 1982, No. 7, p. 2, books [1], [2], [3]).

⟦folio 5⟧

Cubic curves

An algebraic curve of triangular order, or cubic curve, is the set of points $(x, y)$ satisfying $P(x, y) = 0$, where $P$ is a polynomial of triangular degree: $P(x, y) = ax^3 + bx^2y + \dots + l$ (10 terms in total). Note that this definition does not depend on the choice of coordinate system: when moving from one coordinate system to another, even oblique, the old coordinates are expressed through the new ones using linear formulas

$$x = a_1x' + b_1y' + c_1, \quad y = a_2x' + b_2y' + c_2,$$

In new coordinates, the curve will also be defined by a polynomial of triangular degree.

A cubic curve is called reducible if the polynomial $P(x, y)$ is decomposed into the product of polynomials of lower (first and second) degrees, and non-conductive otherwise. We will sometimes denote such a curve by the letter $\Omega$ - some of the cubic curves that are very diverse in shape have a positive form. For example, the curve $(x + 1)(x^2 + y^2 - 1) + \varepsilon = 0$ for small $\varepsilon$ (say $\varepsilon = 0,001$) is very close to the reducible curve $(x + 1)(x^2 + y^2 - 1) = 0$, consisting of a line $x = -1$ and a circle $x^2 + y^2 = 1$. If the polynomial is expanded into the product of three linear polynomials: $P = L_0L_1L_2$, then the curve $P(x, y) = 0$ will be the union of three straight lines $L_0 = 0$, $L_1 = 0$, $L_2 = 0$.

It turns out that any polynomial of triangular degree can be represented as the sum of two such “strongly reducible” polynomials; this will be clear from the proof of the following theorem about 9 points on a cubic curve.

Theorem 3. Let three straight curves intersect three black points. If you use three black dots on a certain cubic curve, then the ninth lecture is on the same cubic curve.

In the special case when the curve is reducible, this yields the theorems of Pappus and Pascal: if the curve splits into three (black) straight lines, then Theorem 3 turns into Theorem 1, and if into a straight line and a second-order curve, then into Theorems 2 and 2'. Thus, having proven Theorem 3, we will obtain all previous results simultaneously, and at once in the general case!

Let the lines $R_i = 0$ and $L_j = 0$ intersect at the point $A_{ij}$ (Fig. 5; $i$ and $j$ belong to the values ​​0,1 and 2). Let us prove that if all points $A_{ij}$, except $A_{22}$, lie on the cubic curve $P(x, y) = 0$, then so does $A_{22}$. Let us put $K = L_0L_1L_2$, $\Gamma = R_0R_1R_2$ and prove that for some numbers $\lambda$ and $\mu$ the current action $P = \lambda K + \mu \Gamma$ is satisfied. From here it will follow that $P = 0$ is at point $A_{22}$: after all, $K = 0$ is on the red lines, $\Gamma = 0$ is on the blue lines, so both of these equalities are satisfied at the black points.

It is convenient to assume that the lines $L_0 = 0$ and $R_0 = 0$ are the coordinate axes, so $L_0(x, y) = x$, $R_0(x, y) = y$ (this can be achieved by replacing the variables according to formulas (1)); while $K(x, y)$

⟦folio 6⟧

looks like
$$x(x - \alpha_1 - \gamma_1 y)(x - \alpha_2 - \gamma_2 y),$$
where $\alpha_1$ and $\alpha_2$ are the coordinates of points $A_{01}$ and $A_{02}$ on the $Ox$ axis. Since the curve $P(x, y) = 0$ passes through the points $A_{00}$, $A_{01}$ and $A_{02}$, the polynomial $P(x, 0)$ - i.e. $P$, considered on the axis $y = 0$, is formed at 0 with $x$ equal to 0, $\alpha_1$ and $\alpha_2$, therefore $P(x, 0) = \lambda x(x - \alpha_1)(x - \alpha_2)$ with some $\lambda$, hence $P(x, 0) = \lambda K(x, 0)$. Similarly, we prove that $P(0, y) = \mu \Gamma(0, y)$ for some $\mu$ (here the points $A_{00}$, $A_{10}$ and $A_{20}$ are used).

Let us now consider the polynomial $G = P - \lambda K - \mu \Gamma$. It is identically equal to 0 for $x = 0$ (after all, $K$ contains the polynomial $x$), as well as for $y = 0$, so it must have the form $G = xyG_1$, where $G_1$ is a polynomial of degree no higher than one (after all, degree $G$ is no higher than three). On the other hand, at the points $A_{11}$, $A_{12}$ and $A_{21}$, where $G = 0$ and $xy \neq 0$, the polynomial $G_1$ must vanish, and these points do not lie on the same line. This is possible only if $G_1$, and with it $G$, which is the same, are equal to 0.

Theorem 3 is proven.

Adding points on a cubic curve

Many interesting geometric properties of cubic curves, as well as their various applications in analysis, number theory, and even combinatorics (coding theory), are associated with the operation of point addition. The existence of such a natural operation is a characteristic property of (irreducible) curves of the third degree, and its geometric definition is based on the fact that a straight line intersecting the curve $\Omega$ at two points must also have a third point of intersection with it. We will see that Theorem 3 expresses a remarkable property of this operation - associativity: $A + (B + C) = (A + B) + C$.

The sum $A + B$ of two points $A, B$ of the curve $\Omega$ is defined as follows. At $\Omega$ some “starting” point $E$ is selected. Using two points $A, B$, the third point $D$ of the intersection of the straight line $AB$ with $\Omega$ is constructed, and then the third point of intersection.

Fig. 6. Addition of points on the graph $y = x^3$. When the points of this graph lie on the same straight line if and only if the sum of their abscissas is 0.

Fig. 7. Associativity of addition of a point on a cubic curve. The equality $A + (B + C) = (A + B) + C$ follows from the 9-point theorem.

sections with $\Omega$ line $DE$; this is, by definition, the point $A + B$.

The points on the curve $y = x^3$ (Fig. 6) are especially simple to add up: if we take the origin of coordinates (0; 0) as the initial point $E$, then the sum of the point with the abscissas $x_1$ and $x_2$ will be the point with the abscissa $x_1 + x_2!$. Indeed, three points $A(x_1; x_1^3), B(x_2; x_2^3), D(x_3; x_3^3)$ lie on the same line if the condition is satisfied

$$\frac{x_1^3 - x_2^3}{x_1 - x_2} = \frac{x_2^3 - x_3^3}{x_2 - x_3},$$

which after simplified takes the form

$$x_1 + x_2 + x_3 = 0;$$

and since $E$ is the center of symmetry of the graph $y = x^3$, the point $A + B$ (the third point of intersection of the straight line $DE$ with this graph) has coordinates $(-x_3; -x_3^3)$, i.e. the abscissa $-x_3 = x_1 + x_2$.

In order for the operation of addition of a point to be defined for any two points, it is necessary to make several clarifications: take into account the points of tangency of the lines with $\Omega$ as double (and for points of intersection - triple) points of intersection, add “pointless” points to the curve, discard “special” points that appear on some curves. This was discussed in more detail in article 10. P. Solviev in the previous issue «Kvant».

For such an addition, a point on the curve $\Omega$ has the commutative property $A + B = B + A$ very/no (the line $AB$ coincides with the line $BA$). But associativity is not so easy to prove. This can be done using Theorem 3 by drawing 7 straight lines (Fig. 7). By this theorem, the point $X$ of intersection of the lines connecting $A$ with $B + C$ and $A + B$ with $C$ lies on $\Omega$, so

$$A + (B + C) = (A + B) + C = Y.$$

Construction of polygrams

Let's call a polygram a triple of infinite sequences of points on the plane - red ($A_k$), black ($B_l$) and blue ($C_m$), for which the following condition is satisfied: if $k + l +$

⟦folio 7⟧

+m=0, then the points $A_k$, $B_l$ and $C_m$ lie on the same straight line ($k, l, m=0, \pm 1, \pm 2, \dots$).

This infinite configuration was dedicated to problem M585 from the "Quantum Problem". (It’s interesting that the author of the problem, V.V. Batyrev, wrote the problem for us when he was still a 10th-class student, and now he graduated from the mechanism of Moscow State University and became its research assistant - specializing in algebraic geometry.) The simplest polygram is easy to construct on checkered paper (Fig. 8), but it turned out that there are many different polygrams, and their description of the theorem does not always contain the entire content of our stat, including even “adding points” on cubic curve.

Try to experimentally test and then justify the following statements (figure 9-11 will help with this, where some examples of polygrams are depicted; the numbers placed only at some of the first points - the rest can be easily restored from them).

1. For any three straight lines $a, b, c$, using arbitrarily given points $A_0$ (on $a$), $B_0$ and $B_1$ (on $b$), a unique polygram is constructed in which all points $A_k$ lie on $a, B_l$ on $b$ and $C_m$ on $c$.

2. Let a circle $\sigma$ (it can also be an ellipse, hyperbola or parabola) and three points: $A_0$ on $\sigma$, $B_0$ and $B_1$ not lying on $\sigma$ be given. Then there is a unique polygram in which all points $A_k$ and $C_m$ lie on $\sigma$, and $B_l$ on the straight line $B_0B_1$.

3. If an irreducible cubic curve $\Omega$ is given and there are three points $A_0, B_0$ and $B_1$ on it, then from them the polygram lying on $\Omega$ can be uniquely reconstructed, and it can be written as a triple of argumentative progressions $A_k=A_0+kD$, $B_l=B_0+lD$, $C_m=C_0+mD$ (D is a point on $\Omega$, defined by condition $B_0+D=B_1$); however, if D is a point on the (non-singular) curve $\Omega$ such that $nD=D+\dots+D=E$, the polygram will not be infinite, but periodic (such configurations are considered in article [4] in connection with the problem of how many tracks from a given number of points in the plane can lie on straight lines).

4. Let six points $A_0, A_{-1}, A_1, B_0, B_1$ and $B_2$ be given on the plane (in general position). Using them, a polygram is uniquely reconstructed, all points of which automatically appear on a non-singular curve.

To prove general statements about polygrams, the following messages are useful. The central projection of any polygram is again a polygram. Each 9 points of the polygram $A_k, A_{k+r}, A_{k+s}, B_l, B_{l+r}, B_{l+s}, C_m, C_{m+r}, C_{m+s}$, where $k+l+m+r+s=0$, form a configuration that satisfies the conditions of Theorem 3; in particular, for a polygram on three straight lines (Fig. 9) they form 9 points

Fig. 8. Example of a polygram. Given infinite sequences of red, black and blue points, numbered by integers, they form a polygram: three different points $A_k, B_l$ and $C_m$ lie on the same straight line if the sum of their numbers $k+l+m$ is equal to 0. (In this example, $B_{-k-m}$ is the midpoint of the segment $A_kC_m$ for any $k$ and $m$).

Fig. 9. Polygrams on three straight lines. On each of them, there is an infinite number of ways to select three points of different points, which serve as the vertices of the Papna configuration of 9 points.

a) The sets of red and blue points are metric with respect to each black point $B_l$, with the coefficient metric equal to $k_n=k_0q^l$.

b) This polygram, entirely arranged in three poles, can be obtained centralized by the number 1, 1/2, 1/3, ….

It is also possible to construct polygrams on three straight lines intersecting in pairs at three different points. Such polygrams can be obtained centralized by the number 1, 1/2, 1/3, ….

⟦folio 8⟧

Fig. 10. Polygrams on a line and a circle (Fig. 10) - Pascal configurations.

There are an infinite number of ways to highlight the Pascal configuration.
a) The ratio of the distances from the points of each cet to the ends of the diameter PQ: $A_kP/A_kQ$, $C_mP/C_mQ$ and $B_lQ/B_lP$ form geometric cuts with the same value q.

6) If this trigram is designed in such a way that straight line b with black dots is displayed at an infinite distance, and the circle - again into a circle, then the images of the colored (as well as head) points with adjacent numbers will be spaced from each other by the same arc $\Theta \cdot 360^\circ$ of the circle; with the playable $\Theta$ the red and blue dots will densely fill the circle, and with the rational $\Theta$ the polygram will turn out to be periodic.

Fig. 11. Polygram on the graph $y=x^3 - ax$. The projections of the points of each cet on the tangent Ot in the direction of the Oy axis constitute a series of equihistoric points - an arithmetic cut.

Pascal configurations, and for the polygram on a line and a circle (Fig. 10) - Pascal configurations.

The scale of points with integer numbers that arose during the construction of polygrams suggests that there is a continuous analogue of polygrams; in fact, it turns out that the points of any - reducible or irreducible - cubic curve $\Omega$ can be associated with numerical values ​​$t$ - introduce a “good parametrization” on the curve $\Omega$ - so that for any straight line intersecting $\Omega$ at three points with parameters $t_1, t_2, t_3$, the condition $t_1 + t_2 + t_3 = 0$ is satisfied. (If the curve $\Omega$ contains an oval, a circle at figure 106, then the value of the parameter $t$ is determined up to the addition of an integer multiple of the “period”, $T$, at which the value $t$ changes when going around the oval.) As we saw (Fig. 6), on the curve $y=x^3$ a “good parameter” is the abscissa of point $(x, y)$. Let's give another example. Let $\Omega$ consist of three straight lines $AB, BC, CA$. The condition that points $M, N, L$ lying respectively on these lines are located on the same line has the form

$$\frac{MA}{MB} \cdot \frac{NB}{NC} \cdot \frac{LC}{LA} = 1$$

(Menelaus' theorem). Here, the “good parameter” $t$ on each line can be taken to be the logarithm of the corresponding ratio: if the product of three numbers is 1, then the sum of their logarithms is 0. In the same way, you can explicitly indicate a “good parameterization” for other reducible and special cubic curves, such as $y^2=x^3$ and the “Descartes leaf” $y^2=x^3-x^2$ (see the first pages of the book [6]).

For irreducible irreducible cubic curves, the existence of a “good parameterization” is closely related to the operation of point addition, and its explicit expression requires familiarity with the theory of elliptic functions, a beautiful area of ​​mathematical analysis that was studied by many of the greatest mathematicians of the 19th century.

Relatively recently (1976), the American mathematician F. Griffithist noted that a “good parameterization” was written - a characteristic property of third-order nominal curves: if three pieces of curves with parameters $t_1, t_2$ and $t_3$ are located on the plane, so that through each point of one of them a straight line can be drawn intersecting the other two, and at the same time the condition is always satisfied for the parameters of the three intersection points $t_1+t_2+t_3=0$, then all these three pieces are contained in one cubic curve. (This is a continuous analogue of the statement that any polygraph lies on a cubic curve.)

1. Yaglom I. M. Geometric transformations, part II - M.: Leningrad: Gostekhidat, 1956.
2. Prasolov V.V. Problems in planimetry, part II - M.: Nayka, 1986.
3. Sharygin I. F. Problems in geometry. Planimetry. - M.: Nayka, 1986.
4. Mathematical flower garden. - M.: Mir, 1983 (article by S. Barr “How to tell trees”, pp. 117-129).
5. Artin E. Geometric allebra. - M.: Nayka, 1969.
6. Shafarevich I. R. Fundamentals of allebraic geometry. - M.: Nayka, 1972 (and plan 1988).
