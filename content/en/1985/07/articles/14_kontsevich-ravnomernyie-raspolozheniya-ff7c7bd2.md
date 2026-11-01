---
id: 1985-7-kontsevich-ravnomernyie-raspolozheniya-ff7c7bd2
issue: kvant_1985_7
year: 1985
number: "7"
title: Uniform Arrangements
authors:
  - Концевич М. Л.
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 53
page_last: 54
page_labels: 51-52
tag: Y1O3
lang: en
source: kvant_digital
extraction: vision
content_sha256: d6198e8ffda926a978730b0fb381d87fdd2538862403d69f5dd3d8cbc8ff2bdc
prompt_sha256: draft-1
translated_from: content/ru/1985/07/articles/14_kontsevich-ravnomernyie-raspolozheniya-ff7c7bd2.md
source_content_sha256: e40bfddf7f8b0ed5e0fdec3d95325d259b3e3e95b7ea178ac09e87e6e29274f7
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 51⟧

Uniform Arrangements

M. L. KONTSEVICH

Let there be $n$ points on the circle, and some $k$ of them are selected - we will call them black, and the rest - white. It is easy to indicate the most uneven arrangement of $k$ black dots among the others: you need to arrange them all in a row. It turns out that you can give a completely natural definition for the most uniform distribution of black dots. Such uniform arrangements are found in many mathematical, and not only mathematical, situations. They are discussed in this article; Here is the solution problem M818 from the “Kwana Problem”, published in No. 9, 1983.

Definition, examples and basic theory

Let us call the arrangement of black dots uniform if for each natural number $m < n$ (where $n$ is the total number of points - black and white), the number of black dots in sets of $m$ consecutive points on the circle differ from each other by no more than 1. For example, the arrangement of 4 points among 9 on figure 1 is uniform - this can easily be verified by enumeration, and the arrangement of 7 points among 17 on figure 2 not evenly. The uniform arrangement of $k$ black dots among $n$ points on the circle will be denoted by $P(n; k)$. Note that changing the colors - black to white - turns $P(n; k)$ into $P(n; n-k)$, so you can always reduce up to the next $k \leq n/2$.

The location $P(12; 5)$ is especially familiar to us - it is the location of the five short (less than 31 days) months of the year, as well as the five black keys among the 12 keys of one; octaves; It is easy to see that these are the same arrangements: January corresponds to nota “F”, February - “F sharp”, etc., so to play the chromatic scale, it is enough to remember how many days there are in each of the 12 months (Fig. 3, 4). The depiction of uniform arrangements not on a circle, but in the form of a periodic sequence of black and white points on a straight line, encountered in the last example, turns out to be very convenient for new interpretations and generalizations, which we indicate in the final problems.

The outer circles figure 5 and 6 show the locations of $P(17; 7)$ and $P(84; 19)$. We oblige the general manner in which they are constructed; at the same time the following will be proven

⟦folio 52⟧

Main theorem: for any natural numbers n and k (k≤n) there is a uniform arrangement P(n;k), and only (up to the division of points along the circle without changing the order of their arrangement).

This is what was required to be done in problem M818.

Lemma "about descent"
and construction of P(n;k)

Conditions: the distance between the two extreme points A and B of a segment of m consecutive points on the circle is considered equal to m-1 (in this case, there are also m-2 points between A and B); Below we will also call this distance the “length” of the segment AB and denote |AB|.

Let's first consider the obvious case when n is divisible by k. When placing k black points at equal distances d=n/k from each other, we obtain a uniform arrangement P(n;k): among m vertices located in a row, there will always be [m/d] or [m/d]+1 black points ([x] is an integer part of the number x). For any other arrangement of k black dots, their location will not be uniform: among the distance between neighboring black dots, there will be at least one no less than d+1 and one no more than d-1, so among m=d consecutive dots there may be both 2 and 0 black dots.

For arbitrary n and k, as a similar thinning shows, the distances between neighboring black points of uniform location should also differ from each other by no more than 1. In total, all these k distances are equal to n, so if n=kd+r (we divided n by k with a remainder), then r of these distances have length d+1, and the rest - d. But it is also important (compare figure 2 and 5) that r longer segments are equal to all k segments along the circle.

For example, on figure 2 (with an uneven arrangement), the sequence of lengths and short segments, written clockwise from the point with an asterisk, looks like this: dkdkkk, and on figure 5 (for P(17;7)) - dkdkkk. It can be seen that in the second sequence the letters d are evenly spaced, but in the first they are not. It is convenient to again depict such sequences as points on a smaller circle: long segments are black, short segments are white (Fig. 5, 6). And here is the key lemma. Let there be k black points among n points on the circle, diluting it into segments of length d+1 and d. In order for the arrangement of black dots to be uniform, it is necessary and sufficient that the corresponding arrangement of r black dots among k points on the smaller circle be uniform.

According to this lemma, which we will prove below, the existence and uniqueness of P(k;r) implies the existence and uniqueness of P(n;k). From here we immediately obtain a proof of the main theorem (by induction) and a convenient way to construct uniform arrangements for any n and k. After all, the nominal “descent” can be continued: k divide (with remainder r₂<r) by r₁=r, then r₁ (with remainder r₃<r₂) by r₂, etc., until some remainder r₁-1 is divided into the next r₂. (This is the famous Euclidean algorithm for finding the most common divisor of the numbers n and k: r₅=GCD (n;k).) Thus, after several steps of descent we arrive at the very extreme case P(r₅-1;r₅), when r₅-1 is divisible by r₅. Having done for a given pair of numbers n and k necessary divisions with a remainder (as in the Euclidean algorithm), we learned how the whole arrangement P(r₅-1;r₅), P(r₅-2;r₅-1),...· leads to P(n;k) and can “grow” the arrangement P(n;k) (as shown in figure 6), building from “beads” of two colors in concentric tiers-circles. Practice building these “necklaces.” In our examples, n and k are coprime, that is, r₅=1 and descent leads to a location of the form P(r₅-1;1) with a single point highlighted among the rest. Note that the practical descent can be somewhat accelerated; if at some step there are more than half of the black dots, then you can “mark the color” (move from the pair (n, k) to the pair (n;n-k)), so that at each step the number of dots will decrease by more than half.

Proof of the lemma

In order (say, clockwise) the black dots are: B₁, B₂, ..., Bₖ. The distance (the absence is clockwise) from B₁ to the qth black point B₁+q from it is denoted by |B₁B₁+q|, here B₁+1=B₁, B₁+2=B₂, etc. Among the segments B₁B₁+1, B₁+1B₂+2, ..., B₁+q-1B₁+qexactly |B₁B₁+q|—qd have length d+1, the rest have length d. Thus, we must prove that the uniformity of the location of the point B₁ is equivalent to the condition: for each q<k distances |B₁B₁+q| differ from each other by no more than 1. Proof in both directions is by contradiction. If our location is not uniform, then it will find two segments of the same length, on one of which there are only q-1 black dots B₁+1, ..., B₁+q-1, on the other - at least 2 large ones B₁, B₁+1, ..., B₁+q, but then |B₁B₁+q|—|B₁B₁+q|≥2. Conversely, if the last inequality is satisfied, then the segment B₁B₁+q contains q+1 black points, and the segment of the same length, starting from the point next to B₁, contains at least two less.
