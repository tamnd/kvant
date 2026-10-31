---
id: 1976-3-shirshov-model-keli-kleyna-geometrii-lobachevskogo-7c9ac7be
issue: kvant_1976_3
year: 1976
number: "3"
title: Cayley-Klein model of Lobachevsky geometry
authors:
  - Ширшов А. И.
rubric: osnovnye-stati
page_first: 20
page_last: 26
page_labels: 18, 20, 21, 22, 23, 24
tag: 0TTQ
lang: en
source: kvant_digital
extraction: publisher
content_sha256: cb86bfe6ae157d0a5854b63fcea9abcf1249422beffb46bfa29e8f3ece2bb66f
prompt_sha256: draft-1
translated_from: content/ru/1976/03/articles/05_shirshov-model-keli-kleyna-geometrii-lobachevskogo-7c9ac7be.md
source_content_sha256: b3ee912d1d30da85d94adab2ec74455cc74b98a79b2eda4ecd98f59100d2eeb3
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦figure⟧

## Cayley-Klein model of Lobachevsky geometry

This article discusses the model of the Lobachevsky plane, which is different from the model of Henri Poincaré, which is described in the article by S. Gindikin

"The Magical World of Henri Poincaré"

.

### Definition of "plane"

In Euclidean geometry, we have points and straight lines of an ordinary plane, and with the help of well-known displacements (parallel translations, axial and central symmetries and rotations) we can translate any point of the plane into any other, any two points lying at a given distance into other two points lying at the same distance, and any two straight lines into two straight lines forming the same angle. Now we will consider geometry, the *points* of which will be the internal points of a certain circle (without points of the circle bounding it), and the *straight lines* will be all possible chords of this circle (without ends); Let's describe all the *movements* of such a “plane”, and then introduce the *distance* between the “points” and the *angles* between the “straight lines” so that they are preserved under the specified movements.

We can check that the geometry that we will construct is “no worse” than Euclidean: all axioms will be satisfied in it, except for the “parallel axiom”: it is easy to see that now through a “point” outside the “line” it is possible to draw more than one that “does not intersect” it. On figure 1, through the point $A$, which does not lie on the chord $L$, two chords are drawn - $L_1$ and $L_2$, having $L$ at a common end; these chords $L_1$ and $L_2$ are called *parallel* $L$, since we consider them as straight chords without ends, and from our new point of view the line $L$ does not intersect either $L_1$ or $L_2$. (Let us also note that the lines “not intersecting” with $L$ are located in the area bounded by the lines $L_1$ and $L_2$, shaded in blue, and the lines intersecting with $L$ are in the unshaded area.) This means that the “new” geometry will be nothing other than *Lobachevsky geometry*. This model of Lobachevsky geometry is called the *Cayley-Klein model*; it was already mentioned in the articles by S. Gindikin “The Magical World of Henri Poincaré” (see p. 9) and “Felix Klein” (see «Kvant» No. 12, 1975).

⟦figure⟧
Fig. 1

⟦figure⟧
Fig. 2

### Definition of movements

We will need the result of problem M305a), the solution of which was published in «Kvant» No. 9 for 1975 (p. 35).

Let the chords $AA'$ and $BB'$ be ours. the circles intersect at the point $P$, which does not lie on the circle (Fig. 2). Consider the chords $AB$ and $A'B'$ and draw a line through the point $P$ intersecting these chords at the points $C$ and $C'$, respectively. Let, further, $|AP|\cdot|A'P|=t$, $|AC|\cdot|CB|=s$, $|CP|=q$, $|C'P|=q'$. Then, as follows from the solution to problem M305a), $q'=\dfrac{qt}{s+q^2}$. If we now draw an arbitrary chord $A_1B_1$ through the point $C$ and construct chords $A_1A_1'$, $B_1B_1'$ passing through the point $P$, then the chord $A_1'B_1'$ will pass through the point $C'$, because the quantities $q$, $t$, $s$ will not change.

So, with any point $P$ that does not lie on the circle, we can associate some *mapping* $\phi_P$ of our circle onto itself: we need to draw an arbitrary chord $AB$ through the point $C$ of the circle, construct a chord $A'B'$ corresponding to the chord $AB$ relative to the selected point $P$, and the image of the point $C$ consider the point $C'$ of intersection of the straight line $CP$ with the chord $A'B'$ (we call the image of the point $C$ the point $C'$, to which the point $C$ goes when mapping $\phi_P$: $C'=\phi_P(C)$; mapping $\phi_P$, can be correctly defined for points lying on the circle; think about how).

From the above it follows that the position of the point $C'$ does not depend on the choice of chord $AB$. Let's call the mapping $\phi_P$ an *elementary displacement* of the first or second kind, depending on whether the point $P$ is inside or outside the circle.

Let us also include among the elementary displacements of the second kind mappings that are axial symmetries with respect to any diameter $d$ of our circle; let us denote these mappings by $\phi_d$.

Comment. An elementary displacement $\phi_P$ of the first kind leaves the only point $P$ fixed, and an elementary displacement of the second kind leaves all points of the chord connecting the points of tangency of two tangents to the circle drawn from the point $P$ fixed.

We will now consider as a movement any mapping resulting from the sequential execution of several elementary movements.

Elementary displacements, and therefore displacements, translate all points of any chord into points of a certain chord, and the image of the intersection of two chords during any displacement coincides with the intersection of the images of these chords.

Our movements transform straight lines into straight lines, and any point of the first straight line can be translated to any point of the second (check this).

Problem 1. An isosceles trapezoid is inscribed in a circle, the sides of which intersect at the point $P$, and the diagonals at the point $Q$; $d$ is the diameter lying on the straight line $PQ$. Prove that $\phi_d=\phi_P\phi_Q=\phi_Q\phi_P$ ($\phi_M\phi_N$ means sequential execution of moves $\phi_M$ and $\phi_N$).

Now we need to determine the “distances” between the points of our circle and the “angles” between straight lines so that they are preserved during the described movements.

### Distances and angles

Let $C$ and $D$ be two points of our circle. Let us draw a “straight line” through them—the chord $AB$, connect the points $A$, $C$, $D$ and $B$ with some point $P$, which does not lie on the circle, and denote the angles formed at the point $P$ by $\alpha$, $\gamma$ and $\beta$ (see Fig. 2). Consider the relation $\dfrac{|AD|\cdot|BC|}{|AC|\cdot|BD|}$. We have:
$$
\dfrac{|AD|\cdot|BC|}{|AC|\cdot|BD|}=\dfrac{S_{APD}\cdot S_{PBC}}{S_{PAC}\cdot S_{DPB}}=
\dfrac{|AP\cdot|PD|\sin(\alpha+\gamma)\cdot|PC|\cdot|PB|\sin(\beta+\gamma)}{|AP|\cdot|PC|\sin\alpha\cdot|PD|\cdot|PB|\sin\beta}=
\dfrac{\sin(\alpha+\gamma)\sin(\beta+\gamma)}{\sin\alpha\sin\beta}.\tag1
$$
(Here $S_{XYZ}$ is the normal area of ​​triangle $XYZ$.)

It is clear that if $C'$ and $D'$ are the images of points $C$ and $D$ under elementary displacements $\phi_P$ (or $\phi_d$), then $$
\dfrac{|A'D'|\cdot|B'C'|}{|A'C'|\cdot|B'D'|}=\dfrac{|AD|\cdot|BC|}{|AC|\cdot|BD|}
$$
(since the angles $\alpha$, $\beta$ and $\gamma$ do not change their magnitude), and, therefore, elementary displacements, and therefore displacements in general, preserve this relationship.

Let's define the “distance” between any two points $C$ and $D$ like this:
$$
\rho(C,D)=\log_q\dfrac{|AD|\cdot|BC|}{|AC|\cdot|BD|},
$$
where $q\gt1$ is some fixed number.

Important note. When determining the distance, the order of the points on the line $AB$ is important, namely: if we are looking for the distance $\rho(C,D)$, then the point $A$ is the point adjacent to $C$, and the point $B$ is the point adjacent to $D$; if we are looking for $\rho(D,C)$, then $A$ is the point adjacent to $D$ (accordingly, $B$ is the point adjacent to $C$).

For the usual distance between points $C$ and $D$ we will retain the notation $|CD|$. From formula (1) it follows that $\rho(C,D)\ge0$, and $\rho(C,D)=0$ only in the case when the points $C$ and $D$ coincide (i.e. $\gamma=0$). Also, $\rho(C,D)=\rho(D,C)$. If there are three points, $C$, $D$ and $E$, lying on the same line, and the point $D$ is located between the points $C$ and $E$, then $$
\rho(C,D)+\rho(D,E)=\rho(C,E)
$$
(check both statements).

Problem 2. Prove that for arbitrary three points $A$, $B$ and $C$ the “*triangle inequality*” holds:
$$
\rho(A,C)+\rho(B,C)\ge\rho(A,B).
$$

Thus, the distance $\rho$ behaves like a normal one.

Problem 3. Prove that for any line $AB$, any point $C$ on it and any positive number $t$ one can find exactly two different points $D$ and $D_1$ on the line $AB$ such that $\rho(C,D)=\rho(C,D_1)=t$. In other words, prove that a segment of any length can be drawn from a point.

We will call two figures (for example, triangles, segments, angles) *congruent* if there is a displacement that takes one of them to the other.

From the fact that the distance is maintained during movements, it follows that congruent segments have equal lengths.

Problem 4. Prove the existence and uniqueness of the midpoint of the segment.

Problem 5. Prove that segments of the same length are congruent.

All that remains is to enter the angle value.

Let there be some angle with the vertex at the point $C$, - angle $C$. Let's take any displacement that takes the point $C$ to the center of a given circle, and set the value of the angle $C$ equal to the Euclidean value of the angle (with the vertex in the center of the circle) to which the angle $C$ goes during this displacement. From what follows it will follow that this value does not depend on the choice of displacement. (Try to get this yourself by proving that *rotations around the center* of our circle are also translations in Lobachevsky geometry.)

### Cosine theorem

Let us introduce the following notation: if $l$ is some segment, then $|l|$ is its usual (Euclidean) length, $\{l\}$ is its length in the new sense, and $[l]=\dfrac{q^{\{l\}}-1}{q^{\{l\}}+1}$ ($q\gt1$ is the base of the logarithm in the definition of distance $\rho$). Note that the value $[l]$ is always less than one (but greater than zero).

⟦figure⟧
Fig. 3

Consider a triangle $ABC$ whose vertex $C$ coincides with the center of the circle. Let $|BC|=a$, $|AC|=b$, $|AB|=c$, and $r$ be the radius of the circle. Let's continue side $AB$ to the intersection with the circle at points $M$ and $N$, connect points $M$ and $N$ with vertex $C$ (Fig. 3) and denote the resulting angles by $\alpha$, $\gamma$ and $\beta$ ($\gamma$ is the angle at the vertex $C$ of triangle $ABC$). Then $\widehat{MNC}=\widehat{NMC}=\dfrac\pi2-\dfrac{\alpha+\beta+\gamma}2$, and using the usual theorem of sines we find:
$$
\begin{align*}
\dfrac{|a|}r&=\dfrac{\cos\dfrac{\alpha+\beta+\gamma}2}{\cos\dfrac{\alpha-\beta+\gamma}2},\tag2\\
\dfrac{|b|}r&=\dfrac{\cos\dfrac{\alpha+\beta+\gamma}2}{\cos\dfrac{-\alpha+\beta+\gamma}2}.\tag3
\end{align*}
$$
Next:
$$
\{a\}=\log_q\dfrac{r\cdot(r+|a|)}{r\cdot(r-|a|)}=\log_q\dfrac{r+|a|}{r-|a|},
$$
and therefore
$$
[a]=\dfrac{|a|}r.\tag4
$$
Likewise,
$$
[b]=\dfrac{|b|}r.\tag5
$$

By virtue of formula (1)
$$
\{c\}=\log_q\dfrac{\sin(\alpha+\gamma)\sin(\beta+\gamma)}{\sin\alpha\sin\beta},
$$
Means,
$$
[c]=\dfrac{\sin(\alpha+\gamma)\sin(\beta+\gamma)-\sin\alpha\sin\beta}{\sin(\alpha+\gamma)\sin(\beta+\gamma)+\sin\alpha\sin\beta}.\tag6
$$

From relations (4)—(6), taking into account (2) and (3), with simple but rather cumbersome calculations we obtain that $$
\dfrac{(1-[a]^2)(1-[b]^2)}{1-[c]^2}=(1-[a]\cdot[b]\cos\gamma)^2.\tag7
$$
Relation (7) is an analogue of the cosine theorem in ordinary geometry. Since the quantities $[a]$, $[b]$ and $[c]$, and therefore $\{a\}$, $\{b\}$, $\{c\}$, do not change when moving, this relationship justifies the definition of the angle given in the previous paragraph.

Let us now prove two remarkable statements of Lobachevsky geometry.

### Two theorems

Theorem 1. *The sum of the angles of any triangle is less* $\pi$.

⟦figure⟧
Fig. 4

Proof. Let us first consider a right triangle $ABC$, with a right angle at vertex $C$: $\widehat{C}=\dfrac\pi2$ (Fig. 4). From the cosine theorem it follows that $$
(1-[a]^2)(1-[b]^2)=1-[c]^2,\tag8
$$
or $$
[c]^2=[a]^2+[b]^2-[a]^2\cdot[b]^2
$$
Further, from the same theorem (see Fig. 4)
$$
\dfrac{(1-[a]^2)(1-[c]^2)}{1-[b]^2}=(1-[a]\cdot[c]\cos\beta)^2;
$$
Substituting expression (8) for $1-[c]^2$ here, we obtain
$$
\dfrac{(1-[a]^2)^2(1-[b])^2}{1-[b]^2}=(1-[a]\cdot[c]\cos\beta)^2,
$$
where
$$
1-[a]^2=1-[a]\cdot[c]\cos\beta,
$$
and $$
\cos\beta=\dfrac{[a]}{[c]},
$$
i.e. $\beta=\arccos\dfrac{[a]}{[c]}$. Similarly, $\alpha=\arccos\dfrac{[b]}{[c]}$ and we get that $$
\alpha+\beta=\arccos\dfrac{[a]}{[c]}+\arccos\dfrac{[b]}{[c]}=\arccos\dfrac{[a]\cdot[b]-
\sqrt{([c]^2-[a]^2)([c]^2-[b]^2)}}{[c]^2}.
$$
Since $[c]^2=[a]^2+[b]^2-[a]^2\cdot[b]^2$, the expression under the sign of the last arc cosine can be transformed into this:
$$
\dfrac{[b]}{[c]}=\arccos\dfrac{[a]\cdot[b]-\sqrt{([c]^2-[a]^2)([c]^2-[b]^2)}}{[c]^2}=
\dfrac{[a]\cdot[b]}{[c]^2}{\left(1-\sqrt{(1-[a]^2)(1-[b]^2)}\right)},
$$
and since $0\lt[a]\lt1$ and $0\lt[b]\lt1$ (see earlier remark), the last expression is positive; this means the arc cosine of it is strictly less than $\dfrac\pi2$, and we get that $\alpha+\beta\lt\dfrac\pi2$, i.e.
$$
\alpha+\beta+\widehat{C}\lt\dfrac\pi2+\dfrac\pi2=\pi.
$$
The case of a right triangle is analyzed.

⟦figure⟧
Fig. 5

Now consider an arbitrary triangle $ABC$ and assume that $\{c\}$ is its longest side. Let us drop the perpendicular $CD$ from point $C$ to side $AB$. It splits our triangle $ABC$ into two rectangular ones: triangle $ACD$ with “acute” angles $\alpha$ and $\gamma$ and triangle $BCD$ - with angles $\delta$ and $\beta$ (Fig. 5). According to what has been proven, $\alpha+\gamma\lt\dfrac\pi2$ and $\beta+\delta\lt\dfrac\pi2$, whence the sum of the angles of the triangle $ABC$: $\alpha+\beta+\gamma+\delta$ is less than $\pi$.

Let the reader not be confused by the expression “let’s drop the perpendicular.” It is easy to check that the facts we used in the proof of Theorem 1 are not based on the parallelism axiom, and if desired, all of them can be proved, as in ordinary geometry.

Theorem 2. The fourth criterion for the congruence of triangles. *If the angles of one triangle are correspondingly congruent to the angles of another triangle, then these triangles are congruent.*

Proof. Let us denote the quantities $[a]$, $[b]$ and $[c]$ for triangle $ABC$ by $x$, $y$ and $z$; the cosines of the angles respectively lying opposite the sides $a$, $b$ and $c$ are through $m$, $n$ and $p$. Using the cosine theorem (7), we obtain a system of three equations with three unknowns $x$, $y$ and $z$:
$$
\def\|{\vphantom{y}}
\left\{\begin{array}{l}
\sqrt{\|1-x^2}\,(1-myz)=\sqrt{\|1-y^2}\,\sqrt{\|1-z^2};\\
\sqrt{\|1-y^2}\,(1-nxz)=\sqrt{\|1-x^2}\,\sqrt{\|1-z^2};\\
\sqrt{\|1-z^2}\,(1-pxy)=\sqrt{\|1-x^2}\,\sqrt{\|1-y^2}
\end{array}\right.
$$
(the values ​​$m$, $n$ and $p$ are given to us, since the angle values ​​are known).

This system has the only positive solution:
$$
x=\dfrac D{np+m},\quad y=\dfrac D{mp+n},\quad z=\dfrac D{mn+p},
$$
where $$
D^2=m^2+n^2+p^2+2mnp-1
$$
(check!). Consequently, specifying the angles uniquely determines the sides of the triangle, and Theorem 2 is proven.

### Squares. Applications

We do not have the opportunity to talk in detail about the theory of areas in Lobachevsky geometry. Therefore, we will limit ourselves to only brief remarks. Let us assume that each polygon $T$, not necessarily convex (but without self-intersection), is associated with some positive number $S(T)$, and:

1. if the polygon $T$ is divided into some polygons $T_1$, $T_2$, $\ldots$, $T_k$, then $$
S(T)=S(T_1)+S(T_2)+\ldots+S(T_k);
$$
2. if the polygons $T_1$ and $T_2$ are congruent, then $S(T_1)=S(T_2)$.

Then we will say that $S(T)$ is the area of ​​the polygon $T$.

We leave it to the readers to prove or verify with simple examples that in the Lobachevsky plane as an area $n$-square $T$ the value can be taken
$$
S(T)=\lambda[(n-2)\pi-(\alpha_1+\alpha_2+\ldots+\alpha_n)],
$$
where $\lambda$ is an arbitrary fixed positive number (proportionality coefficient), $n$ is the number of sides, and $\alpha_1$, $\alpha_2$, $\ldots$, $\alpha_n$ are the interior angles of the polygon.

Note. Note that the value $(n-2)\pi$ is the sum of the internal angles of the $n$-gon $T$ in Euclidean geometry, i.e., that the value $S(T)$ is proportional to the difference between the sums of the angles of the polygon in Euclidean geometry and Lobachevsky geometry; try to prove the stated statement for triangles. The article “The Magical World of Henri Poincaré” will help you.

The areas of curvilinear figures (for example, the area of ​​a circle) are calculated, as usual, using the passage to the limit. Prove, for example, that the area of ​​a circle of radius $R$ is
$$
\lambda\pi{\left(q^{\frac{\scriptstyle R}{\scriptstyle4}}-q^{-\frac{\scriptstyle R}{\scriptstyle4}}\right)}^2.
$$

And in conclusion, we note the following circumstance. All of the above results can serve as a source for many problems in ordinary geometry, and can also be used in solving problems.

⟦figure⟧
Fig. 6

Let's explain this with an example.

*Through the point $P$ lying on the diameter $AB$* (Fig. 6), *the chords $MM'$ and $NN'$ are drawn. It is necessary to prove that the chord $TT'$, perpendicular to the diameter and passing through the point $P$, is intersected by the chords $MN$ and $M'N'$ at points $S$ and $S'$, equidistant from the point $P$.*

Solution. Moving $\phi_P$ translates chord $MN$ into chord $M'N'$, and moves chord $TT'$ into itself. Therefore, point $S$ goes to point $S'$ and $\rho(P,S)=\rho(P,S')$, i.e.
$$
\dfrac{|TP|\cdot|TS'|}{|TS|\cdot|T'P|}=\dfrac{|T'P|\cdot|TS'|}{|TP|\cdot|T'S'|}{,}
\quad\text{и}\quad|TP|=|T'P|;
$$
it follows from this that $|SP|=|S'P|$.

Problem 6. Prove a similar statement for the case when the point $P$ lies on the extension of the diameter $AB$.
