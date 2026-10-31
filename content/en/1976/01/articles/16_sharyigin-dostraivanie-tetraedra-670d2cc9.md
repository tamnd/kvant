---
id: 1976-1-sharyigin-dostraivanie-tetraedra-670d2cc9
issue: kvant_1976_1
year: 1976
number: "1"
title: Completing the tetrahedron
authors:
  - Шарыгин И. Ф.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 63
page_last: 66
page_labels: 61-64
tag: HEZN
lang: en
source: kvant_digital
extraction: publisher
content_sha256: 76f0b30008a9fcde3c8af4873f5264f8221c977121f9e2230649a985321b3f20
prompt_sha256: draft-1
translated_from: content/ru/1976/01/articles/16_sharyigin-dostraivanie-tetraedra-670d2cc9.md
source_content_sha256: bca0e7262a55b22b39b7beba3bfc2f5b92489d7c3ec4d129591dd4a0543c1796
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

## Completing the tetrahedron

One of the beautiful techniques that can be used when solving geometric problems is to replace the geometric figure being studied with another, in some sense more convenient. So, for example, if the problem statement includes a triangle in which the median is drawn, it is often useful to complete this triangle to a parallelogram, extending the median to a distance equal to itself. This article discusses several problems about a triangular pyramid - a tetrahedron - which can be solved by building the tetrahedron into another polyhedron (usually a parallelepiped).

The first method of completing a pyramid to a parallelepiped is shown in figure 1. Here $AA_1BD$ is this pyramid, and the planes of faces $DCC_1D_1$, $CBB_1C_1$ and $A_1B_1C_1D_1$ of the parallelepiped pass through one vertex of the pyramid and are parallel to the face of the pyramid opposite this vertex.

Problem 1. (Item a) of the problem was proposed at the entrance exam at the Faculty of Mechanics and Mathematics of Moscow State University.) *Given a triangular pyramid $AA_1BD$, in which the edges $AA_1$, $AB$ and $AD$ are pairwise perpendicular, and their lengths are $a$, $b$, respectively, $c$.*

1. *Prove that the vertex $A$ of the pyramid, the point of intersection of the medians of the face $A_1BD$ and the center of the circumscribed ball lie on the same straight line.*
2. *Find the radius of the sphere circumscribed about this pyramid.*

Let's build the pyramid $AA_1BD$ up to a parallelepiped (rectangular!), as shown in figure 1. Then the ball circumscribed about this pyramid is simultaneously a circumscribed ball for the entire parallelepiped. The radius of this ball is equal to half the diagonal of the parallelepiped, namely $\dfrac12\sqrt{a^2+b^2+c^2}$, this is the answer to point b).

⟦figure⟧
Fig. 1

To prove the statement of point a), consider the rectangle $AA_1C_1C$ (we recommend making a separate drawing for it). The center $O$ of the ball is on the diagonal $AC_1$, the median $A_1O_1$ of the triangle $A_1BD$ intersects $AC_1$ at the point $M$, and if we prove that $\dfrac{|A_1M|}{|MO_1|}=2$, then this will mean that $M$ is the point of intersection of the medians of the triangle $A_1BD$; Thus we will prove the statement of point a). From the similarity of triangles $A_1C_1M$ and $AO_1M$ it follows:
$$
\dfrac{|A_1M|}{|MO_1|}=\dfrac{|A_1C_1|}{|AO_1|}=2,
$$
Q.E.D.

Another common way of building a tetrahedron into a parallelepiped is as follows. Let us draw a plane through each edge of the tetrahedron parallel to the opposite edge. These planes will limit a certain parallelepiped (Fig. 2), the diagonals of the faces of which will be the edges of the original tetrahedron.

⟦figure⟧
Fig. 2

A little practical advice: it is more convenient to start a drawing with an image of a parallelepiped.

Problem 2. *Find the radius of a ball touching all edges of a regular tetrahedron whose edge length is $a$.*

As is easy to see from figure 2, the parallelepiped constructed in the described way will be a cube with edge $\dfrac a{\sqrt2}$; the ball inscribed in this cube will be the desired one. Answer: $\dfrac a{2\sqrt2}$.

The first of the proposed methods of completing a tetrahedron to a parallelepiped is convenient when plane angles are given at one of the vertices of the tetrahedron (especially if they are all straight), the second is used in problems in which crossing edges of the tetrahedron appear.

Problem 3. *The lengths of two crossing edges of a tetrahedron are $a$, the other two crossing edges are $b$ and the remaining two are $c$. Find the distance between the center of a ball inscribed in a tetrahedron and the center of a ball touching one of the faces of the tetrahedron and the extensions of the remaining faces.*

On figure 3 $ABCD$ is a given tetrahedron, and the parallelepiped is limited by planes passing through the edges of the tetrahedron parallel to the opposite edges. Since the diagonals of each face are equal to the opposite edges of the tetrahedron, which are equal by condition, then all the faces of the parallelepiped are rectangles, and the parallelepiped itself is rectangular.

⟦figure⟧
Fig. 3

The center of the ball inscribed in the tetrahedron $ABCD$ coincides with the point of intersection of the diagonals of the parallelepiped (prove it!), and the center of the ball touching the face $DCB$ of the tetrahedron (from what follows it is clear that the answer does not depend on the choice of face) and the extensions of its remaining faces coincides with the vertex $L$ of the parallelepiped (it is equidistant from the faces $DCB$ and $ACD$ - for proof, consider the pyramid $B'LCD$, where $|B'L|=|LB|$, equal to the pyramid $BLCD$; points $A$, $D$, $B'$ and $C$ lie in the same plane, it is similarly proven that point $L$; equidistant from planes $DCB$ and $ACB$, $DCB$ and $ADB$).

This means that the distance referred to in the problem statement is equal to half the length of the diagonal of the parallelepiped. Let us denote by $x$, $y$, $z$ the lengths of the edges of the parallelepiped (see Fig. 3). Using the Pythagorean theorem we obtain a system of three equations:
$$
\left\{\begin{array}{l}
x^2+y^2=a^2,\\
x^2+z^2=b^2,\\
y^2+z^2=c^2,
\end{array}\right.
$$
adding which, we find that $$
\dfrac{|AL|}2=\dfrac12\sqrt{x^2+y^2+z^2}=\dfrac12\sqrt{\dfrac{a^2+b^2+c^2}2}.
$$

Problem 4. *The section of a tetrahedron by a plane parallel to its two intersecting edges and equidistant from these edges has area $S$. The distance between these crossing edges of the tetrahedron is $h$. Find the volume of the tetrahedron.*

⟦figure⟧
Fig. 4

Let $ABCDA_1B_1C_1D_1$ be a parallelepiped bounded by planes passing through the edges of the tetrahedron parallel to the opposite edges (Fig. 4). Then the volume of the tetrahedron $A_1BC_1D$ is equal to the volume of the parallelepiped minus the volumes of four triangular pyramids (one of them $A_1ABD$), the volume of each of which is equal to $\dfrac16$ of the volume of the parallelepiped (why?). So, $V_{\text{тетр}}=\dfrac13V_{\text{пар}}$. Let the crossing edges referred to in the condition be $A_1C_1$ and $BD$, and $KLMN$ be the section of the parallelepiped by the plane passing through the midpoints $AA_1$, $BB_1$, $CC_1$ and $DD_1$. Then the vertices of the section referred to in the condition will be the midpoints of the sides of the parallelogram $KLMN$. Therefore, the area of ​​the parallelogram $KLMN$ is $2S$ and equal to the area of ​​the base $ABCD$ of the parallelepiped. Now let’s find the volumes of the parallelepiped and tetrahedron:
$$
V_{\text{тетр}}=\dfrac13V_{\text{пар}}=\dfrac23Sh.
$$

Using the problem just solved, it is not difficult to prove the validity of *Simpson's formula*, which is used to calculate the volume of polyhedra of a special type.

Given a polyhedron, all of whose vertices lie in two parallel planes located at a distance $h$ from each other. Let $S_1$ be the area of ​​a face lying in one plane, $S_2$ the area of ​​a face located in the second plane, and $S_{\text{ср}}$ the cross-sectional area of ​​a polyhedron by a plane located at a distance $\dfrac h2$ from each of these planes. Then the formula for the volume of the polyhedron is valid:
$$
V=\dfrac h6(S_1+S_2+4S_{\text{ср}}).
$$

To prove this, check that this formula is correct if the polyhedron is a tetrahedron, and then split an arbitrary polyhedron, the vertices of which are located in two parallel planes, into tetrahedra with vertices in the same planes: the areas of the faces of tetrahedrons located in one plane will add up to $S_1$, those located in the second plane will add up to $S_2$, and the sum of the areas of the average cross sections of tetrahedra is equal to $S_{\text{ср}}$ of the polyhedron.

In conclusion, we give an example of a problem in which it turns out to be more convenient to build a tetrahedron not into a parallelepiped, but into a triangular prism.

Problem 5. *In a tetrahedron, the areas of two faces are $S_1$ and $S_2$, the dihedral angle between them is $\alpha$, the areas of the other two faces are $Q_1$ and $Q_2$, the angle between them is $\beta$. Prove that*
$$
S_1^2+S_2^2-2S_1S_2\cos\alpha=Q_1^2+Q_2^2-2Q_1Q_2\cos\beta.
$$

⟦figure⟧
Fig. 5

Let us first prove that if the area of ​​one side face of a triangular prism is $S$, the other two faces have areas $S_1$ and $S_2$, and the dihedral angle between them is $\alpha$, then $$
S_1^2+S_2^2-2S_1S_2\cos\alpha=S^2.
$$

Indeed, let the plane $ABC$ (Fig. 5) be perpendicular to the lateral edges of the prism, $\angle BAC=\alpha$. Let us write down the cosine theorem for the triangle $ABC$
$$
|BC|^2=|AB|^2+|AC|^2-2|AB|\cdot|AC|\cos\alpha.
$$
It remains to multiply the last equality by $l^2$, where $l$ is the length of the side edge of the prism.

Let us now turn to the solution of Problem 5. Let $ABCD$ be the given tetrahedron, $S_{\triangle ABD}=S_1$, $S_{\triangle ADC}=S_2$, $S_{\triangle ABC}=Q_1$, $S_{\triangle DBC}=Q_2$, the dihedral angle at edge $AD$ is equal to $\alpha$, and at edge $BC$ - $\beta$. Consider a triangular prism with base $ABC$, one of whose side edges is $AD$ (Fig. 6). Let us denote by $S$ the area of ​​the parallelogram $BB_1C_1C$, then according to the formula we just proved
$$
4S_1^2+4S_2^2-8S_1S_1\cos\alpha=S^2,
$$
Moreover, $S$ can be easily expressed through the lengths of the edges $BC$ and $AD$ and the angle $\phi$ between them: $S=|AD|\cdot|BC|\sin\phi$.

⟦figure⟧
Fig. 6

If we consider another triangular prism with base $ACD$ and side edge $BC$, we get
$$
4Q_1^2+4Q_2^2-8Q_1Q_2\cos\beta=S^2.
$$
This implies the statement of Problem 5.

### Exercises

1. Prove that the sum of the squares of the lengths of the edges of a tetrahedron is equal to four times the sum of the squares of the distances between the midpoints of its crossing edges.
2. (MSU, Faculty of Physics, 1964.) Given a tetrahedron $ABCD$. Prove that its edges $AD$ and $BC$ are mutually perpendicular if and only if the equality holds
$$
|AB|^2+|DC|^2=|AC|^2+|DB|^2.
$$
3. The lengths of two opposite edges of the tetrahedron are equal to $a$, the lengths of the other two opposite edges are equal to $b$, and the remaining two are equal to $c$. Find
the volume of this tetrahedron;
radius of a sphere circumscribed around it.
4. The lengths of the two opposite edges of the tetrahedron are $a$ and $a_1$, the angle between them is $\alpha$, the lengths of the other two edges are respectively $b$ and $b_1$, the angle between them is $\beta$ and, finally, the lengths of the two remaining edges are $c$ and $c_1$, the angle between them $\gamma$ $\Big(\alpha$, $\beta$, $\gamma\le\dfrac\pi2\Big)$
Prove that one of the numbers $aa_1\cos\alpha$, $bb_1\cos\beta$, $cc_1\cos\gamma$ is equal to the sum of the other two.
Find the angles $\alpha$, $\beta$ and $\gamma$, given $a$, $a_1$, $b$, $b_1$, $c$, $c_1$.
