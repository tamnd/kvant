---
id: 1989-2-gotman-geometricheskie-preobrazovaniya-7ae16cce
issue: kvant_1989_2
year: 1989
number: "2"
title: Geometric transformations
authors:
  - Готман Э. Г.
rubric: shkola-v-kvante
page_first: 52
page_last: 55
page_labels: 50, 51, 53
tag: Y43W
lang: en
source: kvant_digital
extraction: vision
content_sha256: 012a6729c1e3276f34ace798f147696ec3fe70ee71d176ecde2f67d7ea3fbeba
prompt_sha256: draft-1
translated_from: content/ru/1989/02/articles/13_gotman-geometricheskie-preobrazovaniya-7ae16cce.md
source_content_sha256: 258fcadb8259c519ecc5653808e4c20eaeebdec2683264ddaca4f4741e71c387
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 50⟧

Math 8-10

Geometric transformations

Part I: Movements

The published note is addressed to eighth-graders, but it will undoubtedly be useful to ninth- and tenth-graders who are ready to compete at the Olympics or enter buses.

E. G. GOTMAN

Transformations of the plane - motion and similarity - in many cases allow you to economically and elegantly solve geometric problems. In the last two years «Kvant» has addressed this topic twice (see No. 12 of 1986 and No. 8 of 1987). Of course, we do not assume that the reader is familiar with this article and will first present the theoretical information necessary to solve the problems.

Let us recall the basic definitions.

Movement is a transformation of the plane in which the distance between the images of any two points is equal to the distance between these points. Let us highlight three special types of movement.

A rotation around a point O by an angle α is a transformation in which the point O transforms into itself, and an arbitrary point A, different from O, transforms into a point A' such that OA'=OA and the angle between OA and the ray OA', absent in the counterclockwise direction, is equal to α. By emphasizing that our turn is always a counterclockwise turn; Let's say a 30° clockwise turn is a 330° turn for us.

Parallel transfer to vector α is a transformation in which an arbitrary point A goes into

⟦folio 51⟧

which point $A'$ such that the vector $\overline{AA'}$ is equal to $\bar{a}$.

Basic symmetry with the axis $l$ is a transformation in which an arbitrary point $A$ goes to the point $A'$, symmetrically $A$ relative to the straight line $l$. The points of the straight line $l$ remain motionless during this transformation.

Obviously, rotation around a point, parallel translation and axial symmetry preserve the distances between points and, therefore, are motion. We do not see central symmetry as a separate type of movement: it is a special case of rotation - a rotation around the symmetry by $180^\circ$.

We will use the following notations: $R_O^a$ - rotation around the point $O$ by an angle $\alpha$, $T_a$ - parallel translation to the vector $a$, $S_l$ - axial symmetry with the axis $l$. By $E$ we denote a point transformation (in which all points are transformed into itself). For example, parallel translation to the zero vector is a point-action transformation: $T_0 = E$. Likewise, rotating (around any point) by $360^\circ$ returns all points to their original position: $R_O^{360^\circ} = E$. Let's add to this that it is always $R_O^{a+360^\circ} = R_O^a$, so it is advisable to set the rotation angles with an accuracy of $360^\circ$. Typically, the notation $R_O^a$ assumes $0 \leqslant \alpha < 360^\circ$.

It is obvious that with any movement of symmetry, the aligned rays transform into simultaneous rays. It is also clear that for any parallel transfer, an arbitrary ray transforms into a ray simultaneous with it. The situation is different when turning.

Theorem 1. When turning, the angle between an arbitrary ray and its image is equal to the angle of rotation.

Proof. In the particular case when the beginning of a given ray coincides with the center $O$ of the rotation, this statement is obvious. If the beginning of a given ray $k$ is different from $O$, then from the point $O$ we draw a ray $h$, simultaneous with the ray $k$ (Fig. 1). Since any movement transforms simultaneous rays into simultaneous rays, the images of $k'$ and $h'$ rays $k$ and $h$ are also

Fig. 1.

co-directed. Therefore, the angle between $k$ and $k'$ is equal to the angle between $h$ and $h'$, i.e. equal to the rotation angle.

This simple theorem can already be used effectively in solving problems.

Exercises

1. On the sides $AC$ and $BC$ of the triangle $ABC$ all of its equilateral triangles $ACB_1$ and $BCA_1$ are constructed. Prove that the segments $AA_1$ and $BB_1$ are equal. Find the angle between lines $AA_1$ and $BB_1$.

Note. Make sure that by rotating the vector of point $C$ by $60^\circ$ the segment $B_1B$ can be combined with the segment $AA_1$ (triangle $ABC$ is considered positively oriented *).

2. On the sides $AC$ and $BC$ of the triangle $ABC$ all of its squares $ACA_1A_2$ and $BCB_1B_2$ are constructed. Prove that a) the segments $AB_1$ and $A_1B$ are equal and perpendicular; b) the centers of the constructed squares and the midpoints of the segments $AB$ and $A_1B_1$ are the vertices of the triangle $A'B'C'$. Otherwise

*) Nominally, the triangle $ABC$ is considered positively oriented if the traversal of its vertices in order $A, B, C$ occurs counterclockwise, and negatively oriented otherwise. (It is worth noting that triangles $ABC$ and $ACB$, which geometrically do not differ from each other, are oriented in the opposite way.)

⟦folio 53⟧

by the number of fixed points: when parallelly transferred to a non-zero vector, all points change their position, i.e. there are no fixed points; with a non-zero rotation there is only one fixed point - the center of rotation. The identity transformation leaves all points of the plane fixed.

Movement composition

The nontrivial nature of Theorem 2 most often manifests itself in a situation where motion of the first kind is considered, from the construction of which it is not clear that it is a rotation or parallel translation. An example of such a movement is the composition of two or more movements of the first kind.

The composition of two transformed ones is called the transformation that is obtained if you first apply the first transformation, and then the second. The composition of the transformation $F$ and $G$ is denoted by the symbol $G \circ F$. (Thus, the transformation $G \circ F$ consists of applying first $F$ and then $G$; this order of notation is justified by the fact that if $A$ is an arbitrary point, then $G \circ F(A) = G(F(A))$.) Obviously, the composition of two motions of the first kind is a motion of the first kind. In view of this, an unexpected consequence follows from Theorem 2.

Corollary 1. The composition of two rotations is either a rotation, a parallel translation, or an identical transformation.

We will qualify this statement by indicating when which of these three possibilities is realized.

Fig. 3.

Theorem 3. Let $R_{a_1}^{a_1} u R_{a_2}^{a_2}$ be two rotations, $0 < a_1 < 360^\circ$ and $0 < a_2 < 360^\circ$, and let $F = R_{a_2}^{a_2} \circ R_{a_1}^{a_1}$ be their composition. 1) The transformation $F$ is identical if and only if $O_1 = O_2$ and $a_1 + a_2 = 360^\circ$. 2) If $a_1 + a_2 = 360^\circ$ but $O_1 \neq O_2$, then $F$ is a parallel transfer. 3) If $a_1 + a_2 \neq 360^\circ$, then $F$ is a rotation through an angle $a_1 + a_2$ around some point.

We leave the proof of this theorem to the reader, limiting ourselves to describing the construction of the center $O$ of the resulting rotation in case 3).

If $O_1 = O_2$, then $O$ is the same as $O_1$ and $O_2$. Let $O_1 \neq O_2$. Let us take advantage of the fact that $O$ is a fixed point of the composition $F$. Let $R_{a_1}^{a_1}(O) = O'$; then $R_{a_2}^{a_2}(O') = O$ (Fig. 3). It follows that $O_1 O' = O_1 O$ and $O_2 O' = O_2 O$, due to which the points $O$ and $O'$ are symmetrical to the relative straight line $O_1 O_2$. Considering that $\angle OO_1 O' = a_1$ and $\angle O' O_2 O = a_2$, we obtain the following result. If $O_1 \neq O_2$ and $a_1 + a_2 < 360^\circ$, then the triangle $OO_1 O_2$ is oriented differently and $\angle OO_1 O_2 = 180^\circ - \frac{a_1}{2}$, $\angle O_1 O_2 O = 180^\circ - \frac{a_2}{2}$.

Exercise 3. Prove that the composition of a parallel translation and a rotation is a rotation through the same angle. Find the center of this rotation.

4. Prove that the composition of an even number of symmetrical axes is a parallel translation, or a rotation, or an identical transformation.

As we have seen, the composition of two rotations is a real transformation only if the centers of the rotations coincide. It turns out that the composition of three rotations can be the same transformation even in the case when the centers of the rotations are different. For example, if $ABC$ is a negatively oriented equilateral triangle, then $R_{C}^{120^\circ} \circ (R_{B}^{120^\circ} \circ R_{A}^{120^\circ}) = R_{C}^{120^\circ} \circ R_{C}^{240^\circ} = \angle R_{C}^{360^\circ} = E$.

Derive the following statements from Theorem 3 yourself:
