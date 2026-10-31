---
id: 1972-4-evtushik-pryamaya-i-ploskost-8fa9ce6b
issue: kvant_1972_4
year: 1972
number: "4"
title: Straight and plane
authors:
  - Евтушик Л. Е.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 56
page_last: 61
page_labels: 54, 57, 58, 59
tag: KQIM
lang: en
source: kvant_digital
extraction: vision
content_sha256: fc4571ee46deca415d25139471f5c53ef30a1f7aa98e1e5efd956480c8c6277e
prompt_sha256: draft-1
translated_from: content/ru/1972/04/articles/14_evtushik-pryamaya-i-ploskost-8fa9ce6b.md
source_content_sha256: 9ab0cc9c841d0f2cf0941b3e6a5ca201c310f0a52608adbe5aaa232cd0500d01
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 54⟧

In 1962, those entering the International Mathematics Faculty of Moscow State University were so many with such a problem.

Problem 1. In the triangular paramid ABCD, the height AK passes through the point K of intersection of the heights of the base BCD, and the lateral edges AB and AC are mutually redistributed. Find the ratio of the areas of the lateral boundaries ADB and ADC, if AB=b, AC=c.

This new development was beyond the comprehension of most schoolchildren. Why? Is the task really that difficult? We advise you to think for yourself about this and other honorable competition problems that will be considered here, and if you have difficulties, we will try together to understand the principles of failure.

Many people seem to have decided that everything depends on clever calculations, because they are used to solving mostly calculation problems in school. Meanwhile, the twist of the problem is “only” to prove that AD⊥AB, AD⊥AC, and then everything is simple:

$$S_{\Delta ADB} = \frac{1}{2} AD \cdot AB = \frac{1}{2} AD \cdot b,$$

$$S_{\Delta ADC} = \frac{1}{2} AD \cdot AC = \frac{1}{2} AD \cdot c,$$

$$\frac{S_{\Delta ADB}}{S_{\Delta ADC}} = \frac{b}{c}.$$

Thus, the main thing in the problem is the proof of a fact, which, as we will see, is based on the important section of stereometry “Straight lines and planes”. We will return to our example later. And now let me emphasize that the reason for many failures in stereometry is the underestimation of the section “Straight lines and planes.” The theorems in this section are often taught formulaically and are not applied to solving a sufficient number of server stereometric problems. Meanwhile, the solution to a stereometric problem is almost always based on theorems expressing the relationship between straight lines and planes: parallelism and peredericularity, angles and distances, belonging and intersection. It will be very useful if, when analyzing our solutions, you notice the places where this or that theorem is applied, and clearly formulate each of them.

Let us take the relation of pre-precursority between a line and a plane, which plays a decisive role in the first problem, and in many other problems. This theorem is well known.

Theorem 1. If a straight line h is pre-prediccular to two straight lines m and n by planes P passing through the point K of intersection of h with the plane P, then the straight line h is pre-predicular to any straight line of the plane P passing through K.

⟦folio 57⟧

The plane $P$ will not change if the plane $P$ is replaced by the plane $P' \parallel P$ (Fig. 5).

Indeed, the figure $A_1D_1C_1B_1A_2D_2C_2B_2$ is a rectangular prism, and the two projections of the quadrilateral $(A_1B_1C_1D_1$ and $A_2B_2C_2D_2)$ are its equal bases. Therefore, the projections of the quadrilateral $ABCD$ remain squares from the side $a$, if we assume that the planes $Q'$ and $Q''$, each parallel to itself, are intersected at the point $A$. This will simplify the drawing and calculations.

2. If the projection of the quadrilateral $ABCD$ is a square, then the quadrilateral $ABCD$ itself is a parallelogram.

This follows from the fact that the plane $ADD_1A_1$ (Fig. 5) is parallel to the plane $BCC_1B_1$ $(A_1D_1 \parallel B_1C_1$ and $AA_1 \parallel BB_1)$, and in this case $AD \parallel BC$; similar to $AB \parallel DC$.

3. By condition $AB' = AB'' = a$. Let us draw the plane $BB'B''B'''$ through the projecting perpendiculars $BB'$ and $BB''$ (Fig. 4). This plane is perpendicular to both the $Q'$ plane and the $Q''$ plane (by what theorem?).

Therefore, line $l$ is perpendicular to planes $BB'B''B'''$ and $\Rightarrow B'B''B''' = 90^\circ$ (planes $Q'$ and $Q''$ are perpendicular). Thus, $BB'B''B'''$ is rectangular. But the right triangle $ABB'$ is equal to the triangle $ABB''$ (remember that $AB' = AB'' = a$), so $BB' = BB''$ and, therefore,

$$BB' = B'B''$$

Similarly, it is proved that

$$DD' = D'D''$$

(no matter how the point $D$ is located relative to the plane $Q'$ and $Q''$).

On this basis, we finally carry out several calculations.

CALCULATING. Since by condition there are $AB = \frac{a}{2}\sqrt{5}$ and $AB' = a$, then $B'B'' = BB' = \sqrt{\left(\frac{a}{2}\sqrt{5}\right)^2 - a^2} = \frac{a}{2}$. Therefore, in a right triangle, $AB'$ will not change if the plane is $P' \parallel P$ (Fig. 5).

Fig. 5.

the square $AB'B'''$ is executed corresponding to: $B'B''' = \frac{1}{2}AB'$ and $\Rightarrow B'AB''' = 30^\circ$. But $\Rightarrow B'AD' = 90^\circ$ means $\Rightarrow D'AD''' = 60^\circ$. This means that $AD' = a$, we find

$$DD' = D'D'' = \frac{a\sqrt{3}}{2}$$

And finally, from the right triangle $ADD'$ we find

$$AD = \sqrt{a^2 + \left(\frac{a\sqrt{3}}{2}\right)^2} = \frac{a}{2}\sqrt{7}$$

Since $ABCD$ is a parallelogram, its perimeter is equal to

$$2(AB + AD) = a(\sqrt{5} + \sqrt{7})$$

The following problem was presented in the written exam of the Faculty of Physics of Moscow State University in 1964.

Problem 4. Two loops $Ax \perp AB$ and $By \perp AB$ emanate from the ends of the segment $AB = a$, and $Ax \perp By$. On the lutz $Ax$ there is a segment $AP = u$, and on the lutz $By$ there is a segment $BQ = v$ poppy, which is $2uv = a^2$. Prove that consideration from the middle of the segment $AB$ to the line $PQ$ is equal to $\frac{a}{2}$.

⟦folio 58⟧

If you think about the conditions of the problem, you will notice the unexpectedness of the fact that we have to prove. In fact, the segment $PQ$ (Fig. 6) does not occupy a fixed position, since the segments $AP=u$ and $BQ=v$ can change, as long as $2uv=a^2$ remains constant. And yet, the distance from the middle $AB$ to the moving segment $PQ$ must remain unchanged, namely $\frac{a}{2}$.

Solved and e. Since $AB \perp AP$, then $BP^2=u^2+a^2$. But $BQ \perp AB$ and $BQ \perp AP$ (by condition), therefore, by Theorem 2, the line $BQ$ is perpendicular to the plane $ABP$, and therefore $BQ \perp BP$, that is, $\triangle BQP$ is straight, and $PQ^2=BP^2+BQ^2=u^2+a^2+v^2$. And since $2uv=a^2$, then $PQ^2=u^2+2uv+v^2=(u+v)^2$, that is, $PQ=u+v$.

So we found that it is always $PQ=BQ+AP$. This fact, as we will see, is the reason why $OK=\frac{AB}{2}$. To be convinced of this, just look closely at figure 6 and see its space. If we carefully separate the right triangles $OBQ$ and $OAP$ from the figure and place them in the same plane with the triangle $OPQ$, then we can notice that the triangle composite of $OBQ$ and $OAP$ (Fig. 7, a) turns out to be equal to the triangle $OPQ$ (Fig. 7, b) precisely because $PQ=PA+BQ$. This proves that $OK=\frac{a}{2}$.

Task. 5. (MSU, mechanism, 1971). All faces of a triangular paramid are equal equilateral triangles, and the height of the paramid coincides with the height of one of its side faces. Find a paramid object if the distance between the largest promirovolochny edges is equal to one.

Solved and e. Let $ABCD$ be the given paramid (Fig. 8), where, according to the conditions, $AB=AC=BD=CD$ and $AD=BC$ (it is not difficult to show that exactly two opposite edges of the paramid must be equal to the base of an equilateral triangle). Let us denote the length of the height $DK$ of the paramid by $h$ (we do not yet know where the point $K$ lies). First of all, we have to find out which edges of the paramid will be the largest and on which face the height of the paramid lies.

The height of the paramid cannot lie either in the face $ADC$ or in the face $ABD$ equal to it, since the similar height of the other face would be greater than $h$ (the length of the inclined one is greater than the length of the perpendicular). Therefore, the height of the paramid $DK$ must lie in the face $BDC$, and therefore $DK \perp AK$.

⟦folio 59⟧

Fig. 9.

But by condition $DK=AK=h$, therefore $AD=BC=h\sqrt{2}$, $KC=\frac{h}{2}\sqrt{2}$ and $DC=\sqrt{h^2+\left(\frac{h}{2}\sqrt{2}\right)^2}=h\sqrt{\frac{3}{2}}$.

So, the edges $AD$ and $BC$ are larger than the edges $AB$, $AC$, $BD$, $CD$. Let us drop a perpendicular from point $K$ to edge $AD:KM \perp AD$. Once $BC \perp DK$ and $BC \perp AK$, then $BC \perp KM$. Consequently, $KM$ is the common perpendicular of the edges $AD$ and $BC$, and by assumption it is equal to 1; but in the isosceles right triangle $ADK$ the equalities $KM=\frac{1}{2}AD=\frac{h}{2}\sqrt{2}$ are satisfied, whence $\frac{1}{2}h\sqrt{2}=1$, $h=\sqrt{2}$.

Problem 6. (MSU, Mechanics and Mathematics, 1965). In the triangular paramid $SABC$ the flat lines at the vertex $S$ are straight. Prove that the vertex $S$, the point $G$ of intersection of the medians of the base $ABC$ and the center $O$ of the circumscribed ball belong to the same straight line.

Solution. The point $P$ (Fig.9) is the center of the circle circumscribed about the triangle $ABC$, since $AP=PC$, $\Rightarrow ASC=90^\circ$. The straight line connecting the center of the ball with the center of the section circle is perpendicular to the section plane, that is, $PO \perp ACS$. Same as $QO \perp BCS$. But $SB \perp ACS$ and $AS \perp BCS$, because all flat lines at the vertex $S$ are straight. This means that $PO \parallel SB$ and points $P, O, S$ and $B$ lie in the same plane, as well as $OQ \parallel AS$ and points $O, Q, A$ lie in the same plane. These planes have two (non-coinciding) common points $S$ and $O$, so the straight line $SO$ is the line of intersection of these planes. In the first plane lies the median $BP$, and in the second - the median $AQ$, therefore, the point $G$ of intersection of the medians lies in both planes, that is, on the straight line $SO$ of the intersection of the planes, and this was what needed to be proven.

Exercises

1. Prove the theorem about three perpendiculars based on Theorem 2.
2. Prove that all regular triangular lines and all triangular lines with right plane angles at the vertex are orthocentric lines.
3. (MSU, Mechanics and Mathematics, 1969). The rectilinear projections of triangle $ABC$ onto two mutually perpendicular planes are regular triangles with sides equal to 1. Find the perimeter of triangle $ABC$ if it is known that $AB=\frac{1}{2}\sqrt{5}$.
4. (MSU, Mechanics and Mathematics, 1970). A segment $AB$ of unit length, which is a chord of a sphere of radius 1, is located at an angle $π/3$ to the diameter $CD$ of this sphere. The distance from the end $C$ of the diameter to the nearest end $A$ of the chord is $\sqrt{2}$. Determine the dimensions of the segment $BD$.
5. (MSU, Mechanics and Mathematics, 1971). The base of a quadrangular paramid is a square, and all the side faces are right triangles, in which the vertices of right angles lie on the base of the paramid. Find the volume of the paramid if its height is equal to one and one of the two-dimensional angles at the vertex is $120^\circ$.
6. (Faculty of Physics, Moscow State University, 1970). In the triangular paramid $SABC$ all edges are equal to each other. On the edge $SA$ we take a point $M$ such that $SM=MA$, on the edge $SB$ we take a point $N$ such that $SN=SB/3$. Through the points $M$ and $N$ a plane is drawn parallel to the medians $ABC$. Find the ratio of the volume of a triangular paramid, cut off from the original drawn plane, to the volume of the paramid $SABC$.
7. Three mirrors form a triangular angle, all of whose two-dimensional angles are right angles. Show that a ray of light that led to this triangular angle along the straight line $l$, after reflection from the mirror surfaces, will go along a straight line parallel to $l$.
8. Construct a segment of a given length, parallel to a given plane, and the ends of the segment must lie on two intersecting lines.
