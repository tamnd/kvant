---
id: 1977-8-rabinovich-affinnyie-zadachi-i-teoremyi-b94941ab
issue: kvant_1977_8
year: 1977
number: "8"
title: Affine problems and theorems
authors:
  - Рабинович В. Л.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 40
page_last: 43
page_labels: 38, 40, 41
tag: F9MH
lang: en
source: kvant_digital
extraction: vision
content_sha256: d385c970a98bf6dbaac62023fe59516ee683e5c4e5b7bbafe7c84462d66db968
prompt_sha256: draft-1
translated_from: content/ru/1977/08/articles/10_rabinovich-affinnyie-zadachi-i-teoremyi-b94941ab.md
source_content_sha256: 58b110e96f77b6692cd0b30b19f2867afcd1f82dba6e87d6e87d2bc9bbce16cc
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 38⟧

V. Rabinovich

Affine problems and theorems

Can the parallelogram problem be solved for a square? Is it enough to prove the triangle theorem for equilateral triangles? It turns out that sometimes it is possible, sometimes it is enough. Such problems and theorems are discussed in this article.

1. Concurrent Engineering

Let there be two planes $\alpha$ and $\beta$ and a line $a$ intersecting each of these planes (Fig. 1). Let us define the mapping $\Pi_a$ of the plane $\alpha$ onto the plane $\beta$ as follows: to an arbitrary point $A \in \alpha$ we assign a point $A' \in \beta$, at which the line passing through the point $A$ and parallel to the line $a$ intersects with the plane $\beta$. Using general function notation, we will write $\Pi_a (A) = A'$. The mapping $\Pi_a$ is naturally called parallel projection. Obviously, if $A \neq B$ ($A \in \alpha$ and $B \in \alpha$), then $\Pi_a (A) \neq \Pi_a (B)$. Thus, parallel projection is an inverse mapping (“Algebra 8”, paragraph 20)*. Therefore we can talk about an inverse mapping. The mapping $\Pi_a^{-1}$, inverse to the parallel projection $\Pi_a$, will obviously be a parallel projection of the plane $\beta$ onto the plane $\alpha$: $\Pi_a^{-1} (A') = A$.

Parallel projection $\Pi_a$ transforms any figure $\Gamma$ on the plane $\alpha$ into some figure $\Pi_a (\Gamma)$ on the plane $\beta$ (Fig. 1) - the image of the function $\Gamma$ under the mapping $\Pi_a$.

1. Prove that the image of a line under parallel projection is a straight line and, moreover, if the point $A$ lies between $B$ and $C$, then $\Pi_a (A)$ lies between $\Pi_a (B)$ and $\Pi_a (C)$.

From here it obviously follows that the image of a segment is a segment, the image of a polygon is a polygon (with the same number of sides).

U razzhenne 2. Prove that parallel projection preserves parallelism: if $l \parallel m$, then $\Pi_a (l) \parallel \Pi_a (m)$.

This means that the image of parallelism is parallelism. 3. Prove that the ratio of the lengths of parallel segments is an invariant of parallel projection: if the segments $AB$, $CD$ lie on one line (or on parallel lines) in the plane $\alpha$, then $\frac{|AB|}{|CD|} = \frac{|A'B'|}{|C'D'|}$ (here $A' = \Pi_a (A)$, etc.).

Therefore, if $AK$ is the median of triangle $ABC$ ($\triangle ABC \subset \alpha$), then $A'K'$ is the median of triangle $A'B'C'$.

U razzhenne 4. Prove that the ratio of the areas of figures is an invariant of parallel projection: if $\Gamma \subset \alpha$ and $\Delta \subset \alpha$, then $\frac{S(\Gamma)}{S(\Delta)} = \frac{S(\Pi_a (\Gamma))}{S(\Pi_a (\Delta))}$. Indication. Upon proof it is allowed

*) Parallel design, discussed in this article, is a mapping of a plane (to a plane). Parallel projection from §12 of “Geometry 9” is a mapping of space (onto a plane). It is not the opposite.

⟦folio 40⟧

From exercise 2, 10 it follows that this theorem is an afficine theorem. According to Exercise 7, among the affine images of the given trapezoid $ABCD$ there is an isosceles trapezoid. Having carried out the corresponding parallel projection P, we move from the trapezoid $ABCD$ to the isosceles trapezoid $A'B'C'D'$. The diagonals $AC$ and $BD$ of the trapezoid $ABCD$ will transform into the diagonals $A'C'$ and $B'D'$ of the trapezoid $A'B'C'D'$, the points $O, K, P, Q$ into the points of the corresponding one, $O' = [A'C'] \cap [B'D']$, $K' = (A'B') \cap (C'D')$, $P' = (K'O') \cap [B'C']$ and $Q' = (K'O') \cap [A'D']$ (Fig. 3).

In the equilateral trapezoid $A'B'C'D'$, as is known, $|A'C'| = |B'D'|$ and $B' \hat{A}'D' = C' \hat{D}'A'$ (problem 2 to paragraph 50 of “Geometry 7”). From here it is easy to deduce that $|A'K'| = |D'K'|$ and $A' \hat{K}'Q' = D' \hat{K}'Q'$. Consequently, in the equilateral triangle $A'K'D'$ the segment $K'Q'$ is a bicector, and therefore also the median: $|A'Q'| = |Q'D'|$. Similarly, it is proved that $|B'P'| = |P'C'|$.

Let us now perform the reverse parallel projection $\Pi^{-1}$. With $\Pi^{-1}$, “everything” will go “back”: $A'$ - to $A, B'$ - to $B$, etc. From Exercise 10 it follows that $|BP| = |PC|$ and $|AQ| = |QD|$.

In fact, if we have checked in advance that the theorem we are proving is an afficine one, and we prove it in this way (by passing to an afficine image), then there is no need to do reverse engineering: the correctness of the conclusion of the theorem being proved follows simply from its afficiness.

This way one can prove - in principle - any affinity theorem.

In practice 14. Prove the theorems from exercises 12, 13 in this way.

4. View from above

In fact, a more natural definition of an affective image would be the following: a plane figure $\Delta$ is called an affiliate image of a plane figure $\Gamma$ if it can be obtained from $\Gamma$ by the composition of a finite number of parallel projections. Similarly, the property of a plane figure is naturally called afficine if it is preserved under the composition of a finite number of parallel projections.

Thus, the definition of the concept of an affective image (in contrast to the one that was defined in paragraph 2) is transitive: if $\Delta$ is an affiliated image of a (flat) figure $\Gamma$, and $\Sigma$ is an affiliated image of a figure $\Delta$, then $\Sigma$ is an affiliated image of a figure $\Gamma$. Since this concept is also symmetrical (if $\Delta$ is an affiliate image of the figure $\Gamma$, then $\Gamma$ is an affiliate image of the figure $\Delta$) and reflective (any flat figure $\Gamma$ is an affiliate image of itself), we can (= reasonably) give the following definition: two flat figures $\Gamma$, $\Delta$ are called afficino equivalent if one of them is an afficinal image of the other.

Instead of the theorems from exercises 5-7, we can now formulate more studied theorems: all afficino triangles are equivalent, all afficino parallelgrams are equivalent, all afficino trapezoids are equivalent.

In school geometry, figures are actually considered up to congruence, that is, congruent figures are, as it were, identified and considered equivalent. Therefore, this geometry can be considered as a science of properties

⟦folio 41⟧

figures that do not change with changes.

Geometry on the plane, which is based on compositions of a finite number of parallel projections *) (such compositions are called affine transformations of the plane), i.e., geometry in which affinely equivalent figures are plotted is called affine geometry. Affine geometry is the science of the properties of a figure that do not change under affine transformations. This article introduced you to some of the concepts of this geometry.

Exercise
1. Through the point $P$ lying inside the triangle $ABC$, straight lines $l, m, n$ are drawn, parallel, corresponding to [$AB$, $BC$, $CA$]. Let $l \cap [BC] = A_1$, $m \cap [AC] = B_1$, $n \cap [AB] = C_1$. Prove that $\frac{|PA_1|}{|AB|} + \frac{|PB_1|}{|BC|} + \frac{|PC_1|}{|CA|} = 1$.

2. Prove Menalay's theorem: if the line $l$ intersects the side $AB$ of the triangle $ABC$ at the point $R$, the side $BC$ at the point $P$ and the continuation of the side $AC$ at the point $Q$, then $\frac{|PB| \cdot |QC| \cdot |RA|}{|PC| \cdot |QA| \cdot |RB|} = 1$.

3. In the triangle $ABC$, through the points $L \in [AC]$ and $K \in [AC]$, as well as $|AL| = |CK|$, the corresponding lines $l \parallel AB$ and $k \parallel BC$ are drawn. Let $k \cap l = O$. Prove that the line $BO$ passes through the middle of the segment $AC$.

4. On the sides $AB, BC, CD, DA$ parallel to the gram $ABCD$ the corresponding points $P, Q, R$ and $S$ are taken. Find the plane of the quadrilateral $A_1B_1C_1D_1$ formed by the intersection of lines $AR, BS, CP$ and $DQ$, if the plane of the original parallel gram $ABCD$ is $t$, $|AS| = |CQ|$, $|BP| = |DR|$ and $\frac{|AS|}{|AD|} = \frac{|DR|}{|CD|}$.

5. In parallel to the gram $ABCD$, the points $A_1, B_1, C_1, D_1$ lie, correspondingly, on $[AB], [BC], [CD]$ and $[DA]$. On the sides $A_1B_1, B_1C_1, C_1D_1$ and $D_1A_1$ of the quadrilateral $A_1B_1C_1D_1$ the corresponding points are taken

*) In this article, parallel projection is considered as a mapping of one plane, generally speaking, onto another. But as a result of the composition of such mappings, we can achieve the location of the image in the original plane.

$A_2, B_2, C_2$ and $D_2$. It is known that $\frac{|AA_1|}{|BA_1|} = \frac{|BB_1|}{|CB_1|} = \frac{|CC_1|}{|DC_1|} = \frac{|DD_1|}{|AD_1|} = \frac{|A_1D_2|}{|D_1D_2|} = \frac{|D_1C_2|}{|C_1C_2|} = \frac{|C_1B_2|}{|B_1B_2|} = \frac{|B_1A_2|}{|A_1A_2|}$.

Prove that the quadrilateral $A_2B_2C_2D_2$ is a parallelogram whose sides are parallel to the side $BC$ – into $n$ equal parts. Straight lines are drawn through the division points as shown in figure 4. What part of the area of ​​the parallelogram $ABCD$ is the area of ​​the quadrilateral $NFGH$?

8. In the trapezoid $ABCD$ ([AD] || [BC]) through the point $B$ there is a straight line parallel to $CD$ and intersecting with $AC$ at the point $P$, and through $C$ there is a straight line parallel to $AB$ and intersecting with $BD$ at the point $P$. Prove that $[PQ] || [AD]$.

9. In the trapezoid $ABCD$ ([AD] || [BC]) through the point $C$ there is a line parallel to $AB$ and intersecting $BD$ at the point $P$. It is known that $|BO| = |PD|$, where $O = [AC] \cap [BD]$. Prove that $|AD|^2 = |BC|^2 + |AD| \cdot |BC|$.
