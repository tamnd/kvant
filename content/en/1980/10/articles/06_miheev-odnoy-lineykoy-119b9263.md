---
id: 1980-10-miheev-odnoy-lineykoy-119b9263
issue: kvant_1980_10
year: 1980
number: "10"
title: With one ruler
authors:
  - Михеев Ю. В.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 28
page_last: 31
page_labels: 26-29
tag: DTYE
lang: en
source: kvant_digital
extraction: vision
content_sha256: 670ae4e52890b290e45656a00b47a2195adb3b0fa935bf91060b6ae5db2a14f3
prompt_sha256: draft-1
translated_from: content/ru/1980/10/articles/06_miheev-odnoy-lineykoy-119b9263.md
source_content_sha256: 317e487abced8a4f6f8e1071069c672ff7c6274a4f906f7333a335985f233cf5
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 26⟧

Yu. Mikheev

With one ruler

In this math club lesson we will solve problems involving construction with one ruler. What can be constructed in this way from these four points? We provide some answer to this question. At the same time, the M625 problem will be solved.

Given a finite set of points, a ruler and a pencil. What new points can be constructed then?

Let us clarify the formulation of the problem. A point will be considered constructed if it is one of the data or is the intersection of two constructed lines; in turn, we will consider a straight line to be constructed if it passes through the constructed (in part, given) points. The general problem is to describe the set of points that can be constructed from a given finite set of points.

It is clear that if given two or three points, no new points can be constructed (Fig. 1); if the given four points, some three of which (or all four) lie on the same straight line, then, very conveniently, no new points can be constructed (Fig. 2); if there are four points on one, some three of which (or all four) lie on the same straight line, then, very conveniently, no new points can be constructed (Fig. 3).

Fig. 1.

Fig. 2.

Fig. 3.

⟦folio 27⟧

Fig. 4.

The solution is shown at figure 5; It shows in black the already constructed point $F$ - the middle of $[PQ]$. The equality $|P'Q'| = |Q'R'|$ follows from the similarity of the triangles $\Delta PMF \sim \Delta R'MQ', \Delta FMQ \sim \Delta Q'MP'$ and the equality $|PF| = |FQ|$.

Problem 3. Construct a segment of length $n \cdot |P'Q'|$.

To do this, you simply need to repeat the procedure used in the previous task $n - 1$ times. In figure 6 the construction is shown for $n = 3$.

Of course, in a similar way, we can construct a segment of length $m \cdot |PQ|$ on the prime $PQ$.

Problem 4. Divide the segment $P'Q'$ into $m$ equal parts.

Solution. First, on the base $PQ$ we build $m - 1$ of congestion segments $PQ_2, Q_2Q_3, \ldots, Q_{m-1}Q_m$. Then we construct $(PP')$ and $(Q_mQ')$ and connect their intersection point $A$ with points $Q_2, Q_3, \ldots, Q_{m-1}$. The resulting $m - 1$ lines divide $[P'Q']$ into $m$ equal parts. For $m = 4$ the design is shown at figure 7.

(Note that the construction fails if $(PP') \parallel (Q_mQ')$. But this difficulty is easy to get around: you can sleep

Fig. 5.

Fig. 6.

Fig. 7.

Start doubling $[PQ]$, then construct $m$ segments congruent to the doubled segment, and then repeat the construction indicated in the previous paragraph.)

For what follows, we will have to assume that these points $F, Q, P'Q'$ are rational, that is, they have rational coordinates with respect to some coordinate systems.

Problem 5. Construct an arbitrary rational point $S$ on the prime $PQ$.

Solution. For rational points $P, Q, S$ the relation $|PS|$: $|PQ|$ is rational (prove!), and therefore $|PS| = \frac{m}{n}|PQ|$, where $m, n \in \mathbb{N}$. Therefore, it is enough to divide the segment $PQ$ into $n$ equal parts and postpone the resulting segment $m$ times from the point $P$.

In the same way, we can construct any rational point $T \in (P'Q')$.

Problem 6. Construct an arbitrary rational point $T$ on the plane.

⟦folio 28⟧

Solution. Let's say point $T$ has already been constructed. Let's draw straight lines $TP'$ and $TQ'$; they will intersect*) ($PQ$) at points $E$ and $F$. Since the straight lines $TP'$, $TQ'$, $PQ$ are heterogeneous (that is, written in the form of linear equations with divergent coefficients), the coordinates of the point $E$ and $F$ are obtained as solutions to systems of linear equations with divergent coefficients and therefore are also heterogeneous. Knowing how to build $E$ and $F$, we will also build the point $T$.

So, starting from a trapezoid with different vertices, you can construct any point with different directions! It’s natural to ask: what points can be constructed? It turns out - none.

Problem 7. Prove that any point constructed by one ruler from a set of points of different shapes is of different shapes.

Indeed, a straight line passing through points of different directions is heterogeneous, and the point of intersection of different lines (as a solution to a system of linear equations with coefficients of different directions) is also heterogeneous.

Let us note in passing that we have solved problem $M625a$).

Now let $A, B, C, D$ be four rational points, heterogonal, and the intersection point of heterogonal straight lines (as a solution to a system of linear equations with heterogonal coefficients) also heterologous.

Let us note in passing that we have solved problem $M625a$).

Now let $A, B, C, D$ be four rational points, heterogonal, and the intersection point of heterogonal straight lines (as a solution to a system of linear equations with heterogonal coefficients) also heterologous.

Let us note in passing that we have solved problem $M625a$).

*) Otherwise $T \in (P'Q')$, and this case has already been dealt with.

Rally lines. But this is precisely the most difficult part of our constructions.

By condition, the points $A, B, C, D$ either form a convex quadrilateral, different from a parallelogram, or one of the points located inside a triangle formed by the other triangles. By drawing straight lines in each of these cases, as in Figures 8 and 6, we obtain the same configurations. Therefore, we introduce new notations (see figure 9, in which the data and the constructed points do not differ).

However, it does not follow from our conditions that the lines $EF$ and $MN$ intersect: they can also be parallel. When will this happen?

Problem 8. Prove that if $|MK| = |KN|$, then $(MN) \parallel (EF)$.

The solution is easy to obtain if you remember the solution to Problem 2.

Problem 9. In the case when $|MK| = 2|KN|$, construct a line parallel to $(MN)$.

Solution. First we prove that in our case $|MN| = |NL|$. To do this, we will have to apply the theorems of Cheva and Menelaus (their proofs can be read, for example, in «Kvant», 1976, No. 11, p. 22). The first of these theorems states that if the vertices of the triangle $EFK$ (Fig. 9) respectively lie on the lines $MS, SN, NM$, then

$$\frac{|MK|}{|KN|} \cdot \frac{|NF|}{|FS|} \cdot \frac{|SE|}{|EM|} = 1.$$ (1)

The second states that if the points $E, F, L$ lie respectively on the lines $SM, SN, MN$ and are located

⟦folio 29⟧

we are on the same straight line, then

$$\frac{|ML|}{|LN|} \cdot \frac{|NF|}{|FS|} \cdot \frac{|SE|}{|EM|} = 1.$$ (2)

Comparing these equalities, we obtain $|ML| = 2|NL|$, whence $|MN| = |NL|$. And now the construction of a parallel line is easily obtained in a way known to us (Fig. 10).

Problem 10. In the case when $2|MK| = 3|KN|$, construct a line parallel to (MN).

Note. Show that $|MN| = 2|NL|$, (Fig. 11), and apply Problem 9.

Problem 11. Construct a line parallel to line MN, in the general case.

The solution is suggested to us by previous problems. Let $|MK|$: $|KN| = p:q$, where $p > q$ (the case $p < q$ is a witness to this variable of points). We will reason by induction on $l$. The basis of induction, that is, the case $l = 1$, has already been analyzed (Problem 8). Let us assume that for $p, q \leq l$ we are able to construct a straight line parallel to (MN) from the points M, K, L. Let now $|MK|:|KN| = (l + 1):q$. Comparing (1) and (2), we obtain

$$\frac{|MN|}{|ML|} = \frac{l + 1 - q}{q}$$

and you can use the induction hypothesis, according to which from the points M, N, L you can construct a line parallel to the line (MN).

Thus, we have proven the following theorem (and successfully solved problem M625):

Theorem. The set of points that can be constructed by a single ruler from four rational points in general position consists of all rational points of the plane.

Obviously, increasing the number of initial rational points does not change the set of points that can be constructed.

Probably, the reader would like to know what points can be constructed based on four points in general position, not all of whose coordinates are rational. Unfortunately, in order to formulate a good and accurate answer, it is necessary to involve concepts from projective geometry. However, it is intuitively clear that in this case a set of points is obtained that is very “similar” to the set of all rational points. More precisely, this set is “projectively equivalent” to the set of rational points.

Exercises

1. Using a compass and a ruler, starting from four points in general position, construct a point that cannot be constructed with a ruler alone (with a compass it is allowed to construct a circle $O(A, |AB|)$, where $A, B$ are the constructed points; the intersection points of the constructed circle with the constructed straight line are considered constructed).

2. Given three points O, A, B and two parallel lines l, m, with A, B ∈ l and O∉ l, O∉ m. Build with one ruler

a) a line passing through O parallel to l;

b) a line passing through A parallel to OB.

3*. Given five points (0,0), (1,0), (1,1), (0,2), ($\sqrt{3}$, 0). What points can be constructed from them with one ruler?
