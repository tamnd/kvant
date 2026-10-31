---
id: 1975-7-fishman-reshenie-zadach-s-pomoschyu-geometricheskih-preobrazovaniy-7b161d9d
issue: kvant_1975_7
year: 1975
number: "7"
title: Solving problems using geometric transformations
authors:
  - Фишман В. М.
rubric: osnovnye-stati
page_first: 32
page_last: 37
page_labels: 30-35
tag: ZH4I
lang: en
source: kvant_digital
extraction: vision
content_sha256: 117cd03347e944225d58cc2172c7624fca43b402016b0e3443c6c56c9f3ce555
prompt_sha256: draft-1
translated_from: content/ru/1975/07/articles/06_fishman-reshenie-zadach-s-pomoschyu-geometricheskih-preobrazovaniy-7b161d9d.md
source_content_sha256: a1f0baee69c4a92892566bb3ee1db014cb44e54991a0be15baf303ad701cbadf
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 30⟧

SOLVING PROBLEMS WITH THE HELP
GEOMETRICAL
TRANSFORMATION

In a school geometry course, you often encounter many geometric transformations of the plane: parapel translations, symmetries, rotations, similarity transformations. The importance of these concepts is evidenced by the fact that when proving the congruence of figures, it uses geometric transformations - displacements. However, geometric transformations are found not only in the formulation of definitions and in the proofs of school theorems; they are used in solving a wide variety of geometric problems. Moreover, transformations do not necessarily have to appear directly in the formulation of problems: it often happens that the formulation of a problem is completely “static” in nature, and the simplest and most elegant solution turns out to be “dynamic”, essentially using various geometric transformations of given figures. In this note we will discuss how you can learn to see this internal “dynamics” of planimetric problems.

Understanding Geometric Transformations

Let's start with the definition of displacement.

About the limit 1. Displacement is the mapping of a plane onto itself, in which the distances between points are preserved.

Let us prove the following theorem about displacements:

Theorem 1. There is one and only one movement that takes vertices A, B and C of a given unexpressed precursor ABC corresponding to vertices A1, B1, C1 of its congestive precursor A1B1C1.

Proof. The existence of such a displacement follows from the fact that triangles ABC and A1B1C1 are congestive. Let us prove that it is unique.

Let F be some displacement of the plane such that F(A) = A1, F(B) = B1, F(C) = C1, and let X be an arbitrary point of the plane. Then the point F(X) must be at distances |XA|, |XB|, |XC| respectively from points A1, B1 and C1.

But three circles with centers at points A1, B1, C1 that do not lie on the same line have at most one common point; This means that the point F(X) is uniquely determined.

Are you familiar with the types of movements:

1. Parallel transfers.
(Parallel transfer is determined by specifying a point and its image).

2. By turning.
(A rotation is determined by specifying its center O, the rotation angle α and the direction of rotation; the angle of rotation α is considered to be within the limits 0° ≤ α ≤ 180°. But if you choose any direction of rotation as positive, and the opposite direction is considered negative, then the rotation is completely determined by specifying its center and the angle of rotation α; the angle of rotation is considered a directed vertex, the numerical value of which can be either positive or negative. Rotation with center O by an angle α denotes

⟦folio 31⟧

$R_0^\alpha$. Now any rotation can be specified by specifying its center and the rotation angle $\alpha$, which lies within $-180^\circ \leq \alpha \leq 180^\circ$. If $\beta = \alpha + 360^\circ$, $n$, where $n$ is an integer and $-180^\circ \leq \alpha \leq 180^\circ$, then the rotation by the angle $\beta$ is called rotation $R^\alpha$.

3. Axial symmetries.

(Axial symmetry is determined by specifying the axis of symmetry - straight line $l$.)

The simplest translation is the identity mapping of the plane, which maps any point $X$ onto itself; it is denoted by the letter $E$, then $E(X) = X$. The identity mapping is considered to be a rotation through zero angle around the center $O$. In a similar way, we can consider the identical mapping as a parallel translation to zero distance. Identity mapping is the only movement that is both a rotation and a translation.

For any center $O$, the rotation by $180^\circ$ in both directions coincides and is a central symmetry (relative to the center of rotation $O$).

It can be proven that any displacement is either a parallel translation or rotation, or a composition of parallel translation or rotation with some axial symmetry. The concept of composition of two geometric transformations will be very important to us later, so we will dwell on it in more detail.

Let the given two maps $F$ and $G$ of a certain set $M$ onto itself. Producing them sequentially, we obtain a new mapping $H$, which maps $x \in M$ to $H(x) = G(F(x))$. This new mapping $H$ is also a mapping of the set $M$ onto itself. It is called the composition of the mapping $F$ and $G$ and is denoted $G \circ F$.

From Definition 1 it follows that the composition of any two translations (that is, mappings of the plane onto itself that preserve the distances between points) is again a translation. Pay attention to the order of recording: when denoting the composition $G \circ F$, we put on the right the designation of the display that is performed first. This replacement is significant; we will see that the composition operation, generally speaking, is not variable

ample - there are mappings $F$ and $G$ for which $G \circ F \neq F \circ G$.

Let us now try to figure out what the composition of the mappings known to us - displacements - is like in specific cases.

The peculiarity of the composition of two parallel translations is displacement - this is one of the reasons why the composition of parallel translations (vectors) is called their addition; the composition of mappings is not called addition).

The case of the composition of two turns is more interesting; Let's move it to him. We will need the following definitions: the point $X_0$ of the set $M$ is called a fixed point of the mapping $G$ of the set $M$ onto itself if $G(X_0) = X_0$.

The characteristic property of turns is described.

Theorem 2. A non-identity displacement is a rotation of a module and a milk module when it has a single fixed module.

Proof. The necessity of the condition is obvious: the only fixed point of rotation to zero angle is the center of rotation.

Sufficiency Let us consider a certain displacement $F$ with a single fixed point $O$. Let us choose some point $A$, different from $O$, and consider its image $B = F(A)$; point $B$ is different from $A$ and lies on the circle $(O; r)$ with center at point $O$ and radius $r = |OA|$.

If for any point $A \widehat{AOB} = 180^\circ$, then $F$ is a symmetry with respect to the point $O$, and the sufficient condition is proved. Suppose now that there exists a point $A$ such that $\widehat{AOB} = \alpha \neq 180^\circ$. Consider the point $F(B) = F^2(A)$ ($F^2$ is shorthand for composition

⟦folio 32⟧

⟦figure⟧
Fig. 1.

⟦figure⟧
Fig. 2.

$F\circ F$). Since movement $F$ preserves distances, point $F(B)$ again lies on circle $(O;r)$ and the distance between points $F(B)$ and $B$ is equal to the distance between points $B$ and $A$. These conditions are satisfied by two points: the point $A$ and the point $C$ of the circle $(O;r)$ such that $B\hat{O}C=\alpha$ (Fig. 1). But if $F(B)=A$, then the midpoint of the segment $AB$ - the point $D$ - is a fixed point of the transformation $F$: $F(D)=D$ (prove!), and this contradicts the fact that the point $O$ is the only fixed point $F$. This means $F(B)=C$, and we have proven that the displacement $F$, like $R_O^\alpha$, takes the points $O$, $A$ and $B$, which do not lie on the same line, to the points $O$, $B$ and $C$, respectively. From Theorem 1 it follows that $F=R_O^\alpha$. The theorem has been proven.

Consider the rotations $R_O^\alpha$ and $R_O^\beta$ with a common center $O$. The result of their composition is a rotation around the same center $O$ by an angle $\alpha+\beta$:
$$R_O^\beta\circ R_O^\alpha=R_O^{\alpha+\beta}.$$

(A complete proof of this formula requires the analysis of a number of special cases - do this yourself.)

Since there is always $\alpha+\beta=\beta+\alpha$, then

$$R^\beta\circ R^\alpha=R^{\beta+\alpha}=R^{\alpha+\beta}=R^\alpha\circ R^\beta,$$

and the composition of turns with a common center is commutative.

Let now there be two turns $R_{O_1}^{\alpha_1}$ and $R_{O_2}^{\alpha_2}$ with different centers
⟦column⟧
$O_1$ and $O_2$ and angles $\alpha_1$ and $\alpha_2$ such that $\alpha_1$ and $\alpha_2$ are of the same sign (that is, the turns are in the same direction) and $|\alpha_1+\alpha_2|\neq 360^\circ$. We will show that in this case their composition $R_{O_2}^{\alpha_2}\circ R_{O_1}^{\alpha_1}$ is a rotation through the angle $\alpha_1+\alpha_2$, and we will find the center of this rotation.

For brevity, let us denote the rotation $R_{O_1}^{\alpha_1}$ by $R_1$, the rotation $R_{O_2}^{\alpha_2}$ by $R_2$. We need to find all the fixed points of displacement $R_2\circ R_1$.

Let us assume that some point of the plane $A$ is a fixed point of displacement $R_2R_1$, that is, that $R_2(R_1(A))=A$. Denoting the point $R_1(A)$ by $B$, we obtain that $R_2(B)=A$. From this equality it follows that the point $O_2$ is equidistant from the points $A$ and $B$; but since $B=R_1(A)$, then the point $O_1$ is equidistant from the points $A$ and $B$; therefore, points $A$ and $B=R_1(A)$ must be symmetrical with respect to straight line $O_1O_2$ (Fig. 2).

Since $A\hat{O}_1B=\alpha_1$, and points $A$ and $B$ are symmetrical with respect to the straight line $O_1O_2$, then the point $A$ must lie on the straight line $l_1$, passing through the point $O_1$ and transforming when rotated around the point $O_1$ by an angle $\alpha_1/2$ into the straight line $O_1O_2$. On the other hand, since $B\hat{O}_2A=\alpha_2$, then the point $A$ must also lie on the line $l_2$, into which the line $O_1O_2$ goes

⟦folio 33⟧

when rotating through an angle $\alpha_2/2$ around point $O_2$. By assumption $\frac{|\alpha_1 + \alpha_2|}{2} \neq 180^\circ$, this means that lines $l_1$ and $l_2$ are not parallel, that is, they intersect at a single point - point $A$. So, the point $A$ of intersection of lines $l_1$ and $l_2$ is the only fixed point of displacement $R_2 \circ R_1$. From Theorem 2 it follows that the displacement $R_2 \circ R_1$ is a rotation around $A$. Let's find the angle of this rotation.

To do this, it is enough to find the image of an arbitrary point different from the center $A$ by rotating $R_2 \circ R_1$ around $A$. The most convenient way is to take point $O_1$. Turn $R_1$ leaves it in place, and turn $R_2$ takes it to a point $C$ such that $|O_2O_1| = |O_2C|$ and $O_1\widehat{O}_2C = \alpha_2$ (Fig. 2). Therefore, the movement of $R_2 \circ R_1$ is a rotation around $A$ by an angle of $\widehat{O_1AC}$. Let us calculate this angle for the case $0^\circ < \alpha_1 + \alpha_2 < 360^\circ$ (Fig. 2).

$$\widehat{CAO}_2 = O_2\widehat{AO}_1 = 180^\circ - \alpha_1/2 - \alpha_2/2,$$
$$O_1\widehat{AC} = 360^\circ - \widehat{CAO}_2 - O_2\widehat{AO}_1 = \alpha_1 + \alpha_2.$$

(For case $-360^\circ < \alpha_1 + \alpha_2 < 0^\circ$ should be used)

Task 3. Composition $R_{02}^{\alpha_2}$. $\circ R_{01}^{\alpha_1}$ of two turns $R_{01}^{\alpha_1}$ and $R_{02}^{\alpha_2}$ with different centers $O_1$ and $O_2$ and destinies of turns $\alpha_1$ and $\alpha_2$ maximizing that $\alpha_1$ and $\alpha_2$ are one-zone sign $u$ $|\alpha_1 + \alpha_2| < 360^\circ$, is a rotation through angle $\alpha_1 + \alpha_2$. The center of this rotation is the point of movement of straight lines $l_1$ and $l_2$, where $l_1$ is a straight line passing through point $O_1$ and transforms when turning around point $O_1$ at an angle $\alpha_1/2$ into straight line $O_1O_2$, and $l_2$ is a straight line at which it turns straight line $O_1O_2$ when rotated around point $O_2$ by angle $\alpha_2/2$.

Note that if conditions 3 are met, the composition $R_{01}^{\alpha_1}$.

Fig. 3.

$\circ R_{02}^{\alpha_2}$ is a rotation by angle $\alpha_1 + \alpha_2$ around $B$, symmetrical to point $A$ relative to line $O_1O_2$. This shows that the composition of turns with different centers is not commutative.

Task 1. Prove that the composition of two rotations with centers $O_1$, $O_2$ and rotation angles $\alpha_1$, $\alpha_2$ such that $\alpha_1$ and $\alpha_2$ are one-zone sign $u$ $|\alpha_1 + \alpha_2| = 360^\circ$, is a parallel translation. Construct this parallel translation given $O_1$, $O_2$, $\alpha_1$. Is the composition of two such turns commutative? (Hint: distance composition is symmetrical relative to two different points.)

Task 2. Find the composition:
a) two axes of symmetry;
b) parallel translation and rotation.

Explore the transportability of the composition of different types of movements.

Exercise

Let us now try to apply the obtained results to the solution of some planimerical problems.

Let's first consider the following problem (it will help us later):

On the plane there are two squares $A_1B_1A_2C_1$ and $A_2B_2A_3C_2$ with a common vertex $A_2$ (see Fig. 3). Let $O_1$ and $O_2$ be the centers of the squares, $B$ the midpoint of the segment $B_1B_2$, $C$ the midpoint of the segment $C_1C_2$. Prove that $O_1BO_2C$ is a square.

Of course, this problem can be solved without geometric transformations by making additional constructions and considering non-constructive triangles. However, what the problem says about “correct”

⟦folio 34⟧

figures - squares - suggests the idea of ​​​​trying to apply geometric transformations to solve it.

Note that a 90° rotation around point $O_1$ moves point $B_1$ to point $A_2$, and a 90° rotation around point $O_2$ moves point $A_2$ to point $B_2$. According to Theorem 3, the composition of these two rotations is a rotation of 180°, that is, central symmetry about some point. Since as a result of the sequential execution of these two turns, point $B_1$ goes to point $B_2$, then the compositions of the considered turns will be symmetrical with respect to certain segment $B_1B_2$ - point $B$. On the other hand, from Theorem 3 it follows that the center of the composition of these two rotations lies at the intersection of two lines passing through the points $O_1$ and $O_2$, respectively, at angles of 45° to the line $O_1O_2$. This means that these lines intersect at the point $B$, and the triangle $O_1BO_2$ is equilateral with a right angle at the vertex $B$. Similarly, it is proved that the triangle $O_1CO_2$ is equilateral, with a right angle at the vertex $C$. The union of these two triangles gives the square $O_1BO_2C$, which is what we needed to prove.

The next two problems are problem M291 and M297 from “Problem «Kvant»” (see «Kvant», 1974, no. 911, 12). Solutions to these problems using geometric transformations turned out to be not only simpler and more elegant, but also more meaningful than traditional solutions based on various artificial techniques.

M291. On sides $A_2A_3$, $A_3A_1$, $A_1A_2$ of triangle $A_1A_2A_3$ squares with centers $O_1$, $O_2$, $O_3$ lying outside the triangle (Fig. 4) are constructed. Prove that:

a) segments $O_1O_2$ and $A_3O_3$ are equal in length and mutually perpendicular;
b) the midpoints of the segments $A_3A_1$, $O_1O_2$, $A_3A_2$ and $A_3O_3$ are the vertices of the square;

Fig. 4.

c) the area of ​​this square is 8 times less than the area of ​​the square with center $O_3$.

Let us denote by $B_1$ the midpoint of the segment $A_3A_2$, and by $B_2$ the midpoint of the segment $A_1A_3$. Applying the result of the previous problem to the squares with centers $O_2$ and $O_3$, we obtain that the triangle $O_2B_1O_3$ is equilateral with a right angle at the vertex $B_1$. Therefore, a 90° rotation around the point $B_1$ transforms the segment $A_3O_3$ into the segment $O_1O_2$, which proves statement a). Since a rotation of 90° around the point $B_2$ takes the point $O_2$ to the point $A_3$, then, applying Theorem 3 to the composition of these two rotations (around the points $B_1$ and $B_2$), we obtain, as in the previous problem, that the triangle is $B_2C_1B_1$, where $C_1$ is the middle of the segment $A_3O_3$ is equilateral with a right angle at the vertex $C_1$. Similarly, the triangle $B_2C_2B_1$, where $C_2$ is the midpoint of the segment $O_1O_2$, is equilateral with a right angle at the vertex $C_2$, and statement b) is proven. Statement c) follows from the fact that the diagonal $B_2B_1$ of the resulting square as the middle line of the triangle $A_1A_2A_3$ is half the size of the side $A_1A_2$ of the square with center $O_3$.

M297. There are 12 points given on the plane, which are the vertices of four squares $A_1B_1A_2C_1$, $A_2C_2A_3B_2$, $A_3B_3A_4C_3$ and $A_4C_4A_1B_4$ (the vertices of each square are listed clockwise, Fig. 5). Prove

⟦folio 35⟧

that $B_1B_2B_3B_4$ and $C_1C_2C_3C_4$ are end-to-end parallelograms, one of which is obtained from the other by rotating by $90^\circ$ (these parallelograms can be degenerate: the vertices of either of them in this case lie on the same straight line).

Let $D_1$ be the midpoint of the segment $A_1A_3$, $D_2$ the midpoint of the segment $A_2A_4$.

Considering the compositions of two corresponding rotations by angles $90^\circ$ (with centers at the corresponding vertices of given squares, see Fig. 5), we, as before, obtain that the triangles $B_1D_1C_2$, $B_3D_1C_4$, $B_4D_1C_3$ and $B_2D_1C_1$ are equilateral with a right angle at the vertex $D_1$.

Therefore, a rotation by an angle $90^\circ$ around the point $D_1$ transforms the quadrilateral $B_1B_4B_3B_2$ into the quadrilateral $C_2C_3C_4C_1$, which proves their congruence (at the same time we obtain that the segments $B_1B_3$ and $C_2C_4$ are equal in length and mutually perpendicular, which is a generalization of statement a) problem M291 to the case of an arbitrary quadrilateral $A_1A_2A_3A_4$).

It remains to prove that, for example, the quadrilateral $B_1B_2B_3B_4$ is a parallelogram. To do this, note that all triangles $C_2D_2B_3$, $C_4D_2B_1$, $C_3D_2B_2$, $C_1D_2B_4$ are equilateral with a right angle at the vertex

Fig. 5.

bus $D_2$. This means that a rotation by an angle $90^\circ$ around the point $D_2$ transforms the quadrilateral $C_2C_3C_4C_1$ into the quadrilateral $B_3B_2B_1B_4$. The composition of two rotations around the point $D_1$ and $D_2$ by angles $90^\circ$ is a central symmetry with respect to some $O_1$ and maps the quadrilateral $B_1B_4B_3B_2$ onto itself such that the vertices $B_1$ and $B_3$, $B_2$ and $B_4$ change in some places. It follows from this that the quadrilateral $B_1B_2B_3B_4$ is centrally symmetric, that is, a parallelogram, and this was what needed to be proven.

Applying Theorem 3 to the composition of rotations by angles $90^\circ$ around the point $D_1$ and $D_2$, we also obtain that the centers $O_1$ and $O_2$ of the parallelograms $B_1B_2B_3B_4$ and $C_1C_2C_3C_4$, and the midpoints $D_1$ and $D_2$ of the diagonals of the quadrilateral $A_1A_2A_3A_4$ are the vertices of the square.

This statement is a generalization of statement b) problem M291 to the case of an arbitrary quadrilateral $A_1A_2A_3A_4$.

Prove now that under conditions problem M297, the midpoints of the row of quadrilaterals $B_1C_2B_3C_4$ and $C_1B_4C_3B_2$ are the vertices of the square. The centers of these squares and the square $D_1O_1D_2O_2$ coincide and lie in the center of the beach of the quadrilateral $A_1A_2A_3A_4$.

And finally, the problem that was proposed in 1961 at the second type of the XXIV Moscow Mathematical Olympiad. Then only two participants of the Olympics solved this problem, both of them using geometric transformations. Telery, when you have mastered the technical geometric transformation, solving it should not present much difficulty for you.

Problem 3. Points $A$ and $B$ move uniformly and with equal angular velocities along the circle $O_1$ and $O_2$ corresponding (industrial arrows). Prove that the vertex $C$ of the regular triangle $ABC$ also extends uniformly along a certain circle.
