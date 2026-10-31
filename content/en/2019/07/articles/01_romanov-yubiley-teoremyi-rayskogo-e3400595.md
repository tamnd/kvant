---
id: 2019-7-romanov-yubiley-teoremyi-rayskogo-e3400595
issue: kvant_2019_7
year: 2019
number: "7"
title: Anniversary of Raisky's theorem
authors:
  - Романов А.
rubric: osnovnye-stati
page_first: 12
page_last: 14
page_labels: 11-12
tag: PUP5
lang: en
source: kvant_digital
extraction: native
content_sha256: aaa9ebafce18d001a704232f38caa83130a01685a1126f01c3094e226bc2eede
prompt_sha256: draft-1
translated_from: content/ru/2019/07/articles/01_romanov-yubiley-teoremyi-rayskogo-e3400595.md
source_content_sha256: ed163731a6a90dd67969094266626e07e129a5645108be689d0df1822a5181f5
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio none⟧

Anniversary of Raisky's theorem

A.ROMANOV

50

YEARS AGO, an article by school student Dmitry Raisky [1] with significant progress in the problem posed by Hadwiger [2] was submitted to the MAGAZINE “MATHEMATICAL NOTES”. Dmitry proved the following theorem: When coloring a plane in three colors (partitioning it into three disjoint sets), you can always choose the color in which all distances are realized, i.e. for any positive d there are two points at a distance d colored in the chosen color. Raisky's theorem is a noticeable strengthening of the theorem proved in 1961 by the Moser brothers that when a plane is colored with three colors, there will be two points of the same color at a distance of 1. When preparing the article [1] for publication, the theorem was generalized to N-dimensional space and significantly edited. As a result, the student’s work turned out to be difficult to read and inaccessible to young mathematicians. Here I tried to reproduce the original solution. I am grateful to N.N. Konstantinov, who in 1971 told me the proof of Raisky’s theorem. Konstantinov helped Dmitry in preparing the article and without his participation the publication would hardly have been possible.

⟦column⟧

The product defined in this way contains at most $n_{◊} k$ different vectors, since the sums of vectors for different pairs can be $совпадать.^{Лемма} 1.$ If we consider rotations of a k-beam by an arbitrary angle, then only for a finite number of rotation angles the product of a fixed n-beam and a rotated k-beam will contain less than $n_{◊} k$ different vectors. Indeed, it is possible to choose two different vectors a, b from an n-beam and two different vectors c, d from a k-beam in only a finite number of ways. For each such quadruple of vectors, consider rotations of the k-beam through an angle D and compare the sums of the vectors $a_{+} c_{D}$ and $b_{+} d_{D}$. Since the circles intersect at most two points, at most two angles D can give equality to these sums, which proves Lemma $1.^{Лемма} 2.$ If the product of an n-beam and a k-beam contains n ◊ k different vectors, then the n ◊ k ends of these vectors form n figures obtained by parallel translation of the k-pointer, and k figures obtained

Auxiliary Lemmas

Let a figure of n different points be given on the plane—an n-pointer. Let's choose one of these points and call an n-beam a set of vectors going out from this point to all points of the n-pointer (one of the vectors of the n-beam is a null vector). Let us define the product of an n-beam and a k-beam as a bundle of vectors a + c, where vector a is taken from the n-beam, and c from the k-beam.

DOI: https://doi.org/10.4213/kvant20190702

⟦figure⟧

Fig. 1

defined by parallel translation of the n-point (Fig.1).

Proof of the theorem

Suppose that the statement is false and there is a coloring of the plane in three colors for which it is impossible to choose a color in which all distances are realized. Then for this coloring book each color has

⟦folio 11⟧

ANNIVERSARY

THEOREMS

the distance that cannot exist between two points is colors. Consider the 7-point probe proposed by the Moser brothers, which Raisky called a “probe” (Fig.2). All drawn segments have length 1. By simple enumeration you can verify that if from

PARADISE

⟦column⟧

in any probe for color 1 out of 7 points there are no more than two colors 1, in any probe for color 2 out of 7 points there are no more than two colors 2, and in any probe for color 3 out of 7 points there are no more than two colors 3. Thus, no more than $2_{◊} 7^{2}$ points can be colored in each color, in total no more than $6_{◊} 7^{2}$ points out of $7^{3}$ can be colored. The proof is complete.

Multidimensional case

⟦figure⟧

Fig. 2

choose any three of these seven points, then there are two selected points connected by a segment. The Moser theorem immediately follows from this. For each color we will have our own 7-point probe, in which instead of 1 there will be the distance missing in this color. Let's choose an arbitrary point on the plane and consider all vectors of the beams to come out from this point. Let's number the colors arbitrarily and consider a probe for color 1. In each of the three 7-point probes, choose one of the 7 points, for example $A_{4}$. Then each probe has its own 7-beam. By Lemma 1, we rotate the 7-point probe for color 2 by such an angle that the product of 7-beams 1 and 2 contains $7^{2}$ different vectors (it was a 49-beam), and rotate the 7-point probe for color 3 by such an angle that the product of the 49-beam and this 7-beam contains $7^{3}$ different vectors. By Lemma 2, the ends of these $7^{3}$ vectors - $7^{3}$ different points on the plane - form 49 probes for color 3, they also form 49 probes for color 2 and 49 probes for color 1. To complete the proof, it is enough to note that in

Raisky's article provides a proof of the theorem for an n-dimensional space: Let the sets $A_{1}, A_{2},^{…}, A_{n} +_{1}$ form a covering of the n-dimensional Euclidean space $R^{n} (n >$ 1); then among them there is a set $A_{i}$ such that for every d > 0 there is a pair of points from this set, the distance between which is equal to d. To prove the theorem in this form, no new ideas are required, except for the construction of the probe in $R^{n}$ and the proof of Lemma 1. In order not to sacrifice the accessibility of the presentation, we consider the case of three-dimensional space; for large dimensions the difficulties are purely technical. (Note that in Raisky's article the proof was significantly edited; here I tried to reproduce the original version.) Let's build a probe for $R^{3}$. Raisky called a spindle a 5-point vertex of four vertices of a regular tetrahedron with side d and another point b, symmetrical to one of its vertices - vertex a - relative to the face (Fig.3). He called a probe a 9-point probe, obtained from two spindles, combined by vertices a and rotated so that the distance between the points b of these spindles was also equal to d (Fig.4). Fig. 3

⟦folio 12⟧

KVANT 2019/№7

⟦column⟧

Lemma 2 changes slightly. The product of an n-beam and a k-beam contains n k vectors, taking into account multiplicity, and the n k ends of these vectors form n figures obtained by parallel translation of the k-pointer, and k figures obtained by parallel translation of the n-pointer. Each point of the product of sheaves occurs in these figures as many times as the multiplicity of the point. With this approach, the multidimensional case differs from the two-dimensional case only in the design of the probe.

Top estimate

⟦figure⟧

Fig. 4

Obviously, such a spindle rotation exists. The proof of Lemma 1 needs minor modification. For a given n-pointer, choose a plane in $R^{3}$ so that the projection of the n-pointer onto this plane contains n different points. Let us choose the initial position (rotation) of the k-pointer relative to this plane so that its projection contains k different points. On the plane we have an n-beam and a k-beam, for which Lemma 1 is valid. Let us consider the rotation of the original k-beam around a straight line perpendicular to the chosen plane. The projection onto the plane contains $n_{◊} k$ different vectors, which proves Lemma 1 for $R^{3}$. The rest of the proof remains unchanged.

Before the publication of Raisky's article, a coloring of the plane in 7 colors was known, in which any two points at a distance of 1 are colored in different colors. This coloring is based on dividing the plane into equal regular hexagons. S.B. Stechkin noticed (and, with Raisky’s permission, inserted it into the article) that the plane can be divided into 6 sets such that not all distances are realized on each of them. The design element consists of 4 regular hexagons and 8 regular triangles. By means of parallel transfers, the entire plane is paved with this element, as shown in Fig.

Optimization of the proof of Raisky's theorem

The proposed proof does not use ideas missing from Raisky's original version. It turns out that we can refuse to consider rotations that make the points not coincident (Lemma 1). Instead, each vector of the product of an n-beam and a k-beam can be assigned a multiplicity - the number of options for choosing a vector from an n-beam and a vector from a k-beam for which the sums of the vectors coincide.

⟦figure⟧

Fig. 5

Figure 5. All triangles are open, and the bottom and right vertices of the hexagons do not belong to these figures. If we take the side of the triangle to be 1, then the distance $d_{1} = 2$ is not realized equally on the sets $A_{1},^{…}, A_{4}$

(Continued on page 23)
