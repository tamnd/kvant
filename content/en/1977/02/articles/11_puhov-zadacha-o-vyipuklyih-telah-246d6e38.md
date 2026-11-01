---
id: 1977-2-puhov-zadacha-o-vyipuklyih-telah-246d6e38
issue: kvant_1977_2
year: 1977
number: "2"
title: Convex body problem
authors:
  - Пухов С.
rubric: raznoe
rubric_sub: Разное
page_first: 32
page_last: 35
page_labels: 30-33
tag: PNF0
lang: en
source: kvant_digital
extraction: vision
content_sha256: 698741a3bdc1d37ffd2990b096c5d4ca7785dec642b7a8ce2a639ba829c3f2cd
prompt_sha256: draft-1
translated_from: content/ru/1977/02/articles/11_puhov-zadacha-o-vyipuklyih-telah-246d6e38.md
source_content_sha256: 6cbac3e49d8f5164b54e87c4bb477279d094b718753bc3657aebbf93ca4ce88b
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 30⟧

S. Pukhov

Problem
about convex bodies

This note is devoted to the solution problem M380, which was published in “Problem «Kvant»” (see No. 3 for 1976). Let us recall its formulation.

a) There is a convex figure on the bottom plane and inside it there is a point O. For each straight line l passing through the point O, a redistribution is drawn at the point O and on it, on both sides of the point O, two segments are laid out, the lengths of which are equal to the length of the segment obtained when this figure intersects with the straight line l. The union of all these segments is a new figure with a center of symmetry O. Will the resulting figure be convex?

b) A convex centrally symmetric place with center O is given in space. For each plane α passing through point O, a redistribution is drawn at point O and two segments are laid on it on both sides of this point O, the lengths of which are equal to the sectional area of ​​the given place by plane α. The union of all these segments is a new place with the same center of symmetry O. Prove that the resulting place can be convex.

Comment. In task b) it is assumed that some units are fixed. Then the area unit is determined automatically. And the process of laying down segments should be understood as follows: the segment contains as many units of length as the number of units of area the redefined section contains.

We will not define here what a convex set, body, figure is, nor will we list the properties of convex sets - all these concepts are included in the school geometry course, and they can be found in school textbooks. In addition, we will not give a strict definition of area. It turns out that any flat convex figure has area in the same sense in which a triangle, square or circle has area. You can read about this in detail, for example, in the Encyclopedia of Elementary Mathematics, Volume V, articles by V. A. Rokhli and on “Area and Volume”, or in the book by V. Blyashke “Circle and Ball”. In general, many interesting books have been written about convex sets. Some of them are mentioned at the end of the note.

So, let's learn how to solve problem M380.

A negative answer to the question posed in task a) is given by the following example.

Consider a convex quadrilateral ABCD, whose diagonals AC and BD are mutually perpendicular and intersect at point O (Fig.1). Let $|AO| = |BO| = |CO| = \sqrt{2}$ and $|DO| = \frac{\sqrt{2}}{2}$. Let's start implementing the construction described in point a). On the rays OB and OC we plot the segments OP1 and OP2, congruent segments AC and BD, respectively; points P1 and P2 are points of the new set. On the bisketris of the angle BOC we plot the segment OP congruent to the segment EF (which lies on the bisketris of the angles AOB and COD).

Fig. 1.

⟦folio 31⟧

Let us show that the segment $OP$ does not intersect the segment $P_1P_2$. Since $P$ is the boundary point of the new figure, it will follow that the new figure is non-convex.

Let us denote the point of intersection of the bicsectrix of the angle $BOC$ with the segment $P_1P_2$ by $Q$ ($Q \in [P_1P_2]$). We need to prove that the segment $OP$ is shorter than the segment $OQ$, i.e., that $|OP| < |OQ|$.

It is not difficult to calculate that $|OE| = 1$, $|OF| = \frac{2}{3}$, i.e., that $|EF| = |OP| = \frac{5}{3}$. But $|OQ| = \frac{12}{7}$ (do all the calculations yourself). Since $\frac{5}{3} < \frac{12}{7}$, we obtain that $|OP| < |OQ|$, that is, the new figure obtained from the quadrilateral we have chosen $ABCD$ according to the “resith” described in problem a), is indeed non-convex.

In the right. Prove that the figure resulting from the quadrilateral we have chosen, other than a parallelogram, in which the point of intersection of its diagonals is taken as the point $O$, is also non-convex.

Let us now proceed to the proof of the statement formulated in paragraph 6) of the problem. For convenience, we denote the new body by the letter $V$, and the body from which it is obtained by the letter $W$.

We will say that the boundary point $P$ of the new body $V$ corresponds to the section $\omega$ of the old body $W$ by the plane $\alpha$ passing through the center of symmetry $O$, if the segment $OP$ is perpendicular to the plane $\alpha$, and its length is equal to the section area $\omega$: $|OP| = S_\omega$. Each section corresponds to two points symmetrical with respect to $O$; thus, the new body $V$ is also symmetrical with respect to the point $O$.

Since the body $V$ is formed by a collection of segments “sticking out” from the center $O$, its convexity will follow from the fact that, together with any two boundaries of the body $W$, the body $V$ also belongs to the entire segment $P_1P_2$ (think about it).

So, let points $P_1$ and $P_2$ of body $V$ correspond to two different sections $\omega_1$ and $\omega_2$ of body $W$ by planes $\alpha_1$ and $\alpha_2$ passing through the center of symmetry $O$. Let $Q$ be an arbitrary interior point of the segment $P_1P_2$. It is necessary to prove that $Q \in V$. Let us draw through $O$ a plane perpendicular to the segment $OQ$, and let $P$ be a point lying on the ray $OQ$, corresponding to the section $\omega$ of the body $W$ by the plane $\alpha$. Obviously, the point $Q$ will belong to the body $V$ if and only if $|OQ| \leq |OP|$. Thus, the solution to problem 6) comes down to proving this inequality. Let's go through it in a few steps.

1. Let us project (orthogonally) the sections $\omega_1$, $\omega_2$ and $\omega$ onto the plane passing through the points $O$, $P_1$ and $P_2$ (the plane of Figure 2); then sections $\omega$, $\omega_1$ and $\omega_2$ turn into segments. Let $[B_1C_1]$, $[B_2C_2]$ and $[BC]$ be these segments.

Note that the colored rays at figure are obtained from the red rays by rotating 90° around the point $O$, and that the long red segments $OP_1$, $OP_2$ and $OP$ are equal to the areas of the sections $\omega_1$, $\omega_2$ and $\omega$ respectively. Below, using the convexity of the body $W$ and the Cavalieri principle *), we will derive a correspondence.

*) Bonaventura Cavalieri (1598-1647) - famous Italian mathematician. Its principle has already been discussed in «Kvant»—see. No. 6 for 1972 and No. 8 for 1975. Cavalieri's principles are also in the school textbook - see. "Algebra and beginnings of analysis 10", p. 98.

⟦folio 32⟧

Fig. 3.

carrying for the planes of these sections, from which it will follow that the segment OP intersects the segment $P_1P_2$.

It is clear that the plane sections $\omega$, $\omega_1$ and $\omega_2$ intersect along a common segment $O_1O_2$ (Fig. 3). Let us draw a plane through points $B_1$ and $B_2$ parallel to this segment; Let's call it $\alpha''$. Any plane parallel to $\alpha''$ intersects sections $\omega_1$, $\omega_2$ and $\omega$ along parallel segments $\Delta_1$, $\Delta_2$, $\Delta$ (see Fig. 3), and if you mix $\alpha''$ parallel to itself, then the segments $\Delta_1$ will exhaust all sections $\omega_1$, the segments $\Delta_2$ will exhaust all sections $\omega_2$, and the segments $\Delta$ (see Fig. 3) will exhaust part $\omega$ of the section $\omega$. Moreover, the ratio in which the segment $\Delta$ divides the sides of the trapezoid with the bases $\Delta_1$ and $\Delta_2$ is the same for all planes $\alpha''$; let's set it equal to $\mu: \lambda$, where $\mu + \lambda = 1$ - see figure 4, a. Let's explain why this is so. Let's project all our sections onto a plane passing through the center $O$, perpendicular to the segment ku $O_1O_2$; we get the picture shown in figure 4, b. The section $\omega$, $\omega_1$ and $\omega_2$ correspond to colored segments, the family of the plane $\alpha''$ corresponds to the family of parallel lines $l''$, and each trem segments $\Delta_1$, $\Delta_2$ and $\Delta$ are three points lying on one of the lines of the family $l''$. It is clear that all midpoints (common correspondence to the segments $\Delta$) divide each of the segments enclosed between the edges by straight lines (projections of sections $\omega_1$ and $\omega_2$) in the same ratio.

2. Let us now consider the plane $\alpha'$ passing through the segment $O_1O_2$ and perpendicular to the planes $\alpha''$. Let's project sections $\omega_1$, $\omega_2$ and $\omega$ onto $\alpha'$. Due to the choice of plane $\alpha''$, the projections of sections $\omega_1$ and $\omega_2$ ($np. \omega_1$ and $np. \omega_2$) onto plane $\alpha'$ have the same height (Fig. 5). Segments $\Delta_1$ and $\Delta_2$ are projected into segments lying on the same straight line, without length distortion. It is obvious that $|\Delta| \geqslant \lambda |\Delta_1| + \mu |\Delta_2|$ (since $\lambda |\Delta_1| + +\mu |\Delta_2|$ is the line of the segment $\Delta$, parallel to the bases of the trapezoid of length $|\Delta_1|$ and $|\Delta_2|$, dividing the sides in relation to $\mu: \lambda$ and lying inside the trapezoid, and the segment $\Delta$ is not shorter, which follows from body convexity $W$).

We now develop the projections of sections $\omega_1$ and $\omega_2$ (in the plane $\alpha'$) along the straight line on which their common base is located - see figure 6; it shows only the upper halves of the projections, parallel to $W$ centrally symmetrically. In the interval between these “developed” projections, we will draw another figure in which:

a) the height is the same as for $np. \omega_1$ and $np. \omega_2$;

⟦folio 33⟧

6) the base is the same as $np.\omega_1$, $np.\omega_2$;
c) if $a$ and $b$ are the lengths of the segments resulting from the intersection of $np.\omega_1$ and $np.\omega_2$ of some line parallel to the base, then the length of the segment of intersection of this line with the new figure is $\lambda a + \mu b$ ($\lambda$ and $\mu$ are those mentioned above).

3. Let us now try to find out how the areas of the projections $\omega_1$, $\omega_2$ and the new figure are related to each other, and how the area of ​​the new figure is related to the area of ​​the projection of the section $\omega$. To do this, we need three properties of area (we will not prove them, since we do not strictly define area).

The first property is the Cavalieri prizzit. Prisicite Cavalieri states that if two figures lying in the same plane have the property that any line parallel to a given line (lying in the same plane), at the intersection with this figure, gives constructive segments, then these two figures are equal in size.

The second property is a generalization of Cavalieri's prizzite. Let three figures $F$, $F_1$ and $F_2$ be given on the plane, such that any line parallel to a given line lying in the plane of the figures intersects these figures along segments of length $f$, $f_1$ and $f_2$, and each time $f = f_1 + f_2$. Then $S_F = S_{F_1} + S_{F_2}$ (derive this property from the Cavalieri prizzite).

And finally, the third property: when a figure is stretched relative to a certain axis with a coefficient of $k$, its area is multiplied by $k$.

From Cavalieri's prizzite it immediately follows that the area of ​​the figure constructed on figure 6 is the same as that of the projection onto the plane
