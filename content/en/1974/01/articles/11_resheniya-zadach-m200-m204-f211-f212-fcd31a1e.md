---
id: 1974-1-resheniya-zadach-m200-m204-f211-f212-fcd31a1e
issue: kvant_1974_1
year: 1974
number: "1"
title: Solutions to problems M200—M204; F211, F212
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 46
page_last: 49
page_labels: 44-47
tag: 97KB
lang: en
source: kvant_digital
extraction: vision
content_sha256: ab0767603f0b96185ad3769ae037e870f8fb92b550048b3c1f8053fa717f3a05
prompt_sha256: draft-1
translated_from: content/ru/1974/01/articles/11_resheniya-zadach-m200-m204-f211-f212-fcd31a1e.md
source_content_sha256: be87316085b7355e243744616885a2c5efc152bde7055219a60f4cef2e9e8af2
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 44⟧

Problem solutions

M200—M204; F211, F212

M200. a) On figure 1 there are six lobes, which lie three on four straight. Prove that there are 24 ways to map this set of six lobes onto itself so that every three lobes lying on the same line are mapped into three lobes also lying on the same line.

b) On figure 2.nine lobes lie three on the nine straight lines, and through each moka there are three with the maximum value of the “Pascal configuration”. In how many ways can the set of our nine lobes be mapped onto itself so that each triple of lobes lying on one of the nine lobes is mapped onto a triple of lobes that lies on some straight line from our configuration?

b) Same question for the Desarada configuration (of ten lobes and ten straights) shown in figure 3.

a) Everything is available 6! = 720 ways to map a set of six points onto itself. But not all of these mappings satisfy the conditions of the problem. It is more convenient to find direct mappings of our configuration. If for each of our four straight lines it is indicated which straight line it maps onto, then the image of each point will thereby be determined (which point of our configuration is the point of intersection of certain two straight lines included in the configuration). A set of four straight lines can be mapped onto itself 4! = 24 ways.

b) Note one of the spicy configurations l. Let us denote the three configuration points lying on it A, B and C. Six more configuration lines pass through these points. The remaining 9 - 1 - 6 = 2 are straight lines that do not pass through any points A, B and C. Let us denote them p and q (Fig. 4).

Map the straight line l onto any of the nine straight configurations - onto the straight line l1. This can be done in nine different ways. Points A, B and C will come to be mapped onto points A1, B1, C1 lying on line l1. This can be done 3! =

⟦folio 45⟧

and $Y_1$ points $X$ and $Y$, which must be pairwise intersection points of configuration lines distinct from $l_1$ passing through points $A_1$ and $B_1$ (prove it!). In total there are $10 \cdot 6 \cdot 2 = 120$ mappings that intersect us.

Notes. Note that behind the words “prove” there is still quite a large part of the solution hidden. In future issues we will discuss other approaches to solving problem M200.

A. N. Kolmodorov

**M201. The straight line $l_1$ intersects the sides $a$, $b$ and from the triangle or their continuation at points $A_1$, $B_1$ and $C_1$ of the corresponding direct intersection is still quite a large part of the solution. In future issues we will discuss other approaches to solving problem M200.

We will solve the problem using vectors. This way (as well as the solution by the coordinate method) is good in that it allows you to cover all cases with one reasoning and not worry about how the lines $l_1$ and $l_2$ are located relative to a given triangle.

⟦folio 46⟧

Fig. 7.

mine is $AB$ (Fig. 7). We must find a condition under which $B'_1$ coincides with $C_1$, that is, $\overrightarrow{AB'_1} = \overrightarrow{AC'_1}$ or, equivalently,

$$\frac{\overrightarrow{AB'_1}}{\overrightarrow{C'_1B'_1}} = \frac{\overrightarrow{AC'_1}}{\overrightarrow{C'_1C'_1}}$$

(the relation $\frac{\overrightarrow{AM}}{\overrightarrow{C'_1M}} = k$ is uniquely determined by the position of the point $M \in (AB)$, since from $\frac{\overrightarrow{AM}}{\overrightarrow{C'_1A} + \overrightarrow{AM}} = k$ it follows that $\overrightarrow{AM} = \frac{k}{1-k} \cdot \overrightarrow{C'_1A}$).

Equality (3) is equivalent to:

$$\frac{\overrightarrow{AC'_1}}{\overrightarrow{C'_1C'_1}} \cdot \frac{\overrightarrow{C'_1B'_1}}{\overrightarrow{AB'_1}} = 1,$$

$$\frac{\overrightarrow{AC'_1}}{\overrightarrow{BC'_1}} \cdot \frac{\overrightarrow{BC'_1}}{\overrightarrow{C'_1C'_1}} \cdot \frac{\overrightarrow{C'_1B'_1}}{\overrightarrow{AB'_1}} = 1,$$

and this is equivalent to (1).

**M202.** Prove that from the sequence $a, a+d, a+2d, \dots, a+nd, \dots$, which is an infinite arithmetic progression ($d \neq 0$), it is possible to choose a sequence that is an infinite geometric progression when the relation $a/d$ is rational.

Let $a/d$ be rational: very indo, we can assume that $a$ and $d$ are of the same sign. Then

$$\frac{a}{d} = \frac{s}{r},$$

where $s$ and $r$ are natural numbers. Then for any non-negative integer $m$ the number $(1+r)^m-1$ is divisible by $(1+r)-1=r$, so the number

$$n_m = \frac{a(1+r)^m-a}{d} =$$

$$= s \frac{a(1+r)^m-a}{sd} = s \frac{(1+r)^m-1}{r}$$

—integer and non-negative; therefore, each term of the geometric progression $a(1+r)^m$, $(m=0,1,2,\dots)$ has the form

$$a(1+r)^m = a + n_m d,$$

that is, it belongs to an arithmetic progression.

Example The arithmetic progression $\frac{1}{5} + \frac{3}{7}n(n=0,1,2,\dots)$, where $\frac{a}{d} = \frac{1.7}{5.3} = \frac{7}{15}$, contains the subsequence $\frac{1}{5} \cdot (15+1)^m = \frac{16}{5}m$ ($m$ is any non-negative integer).

Conversely, let the arithmetic progression $a+nd$ ($d \neq 0$) contain at least three consecutive terms of the geometric progression. Let it be her members

$$a+kd, a+ld, a+md \ (k < l < m).$$

Then $(a+ld)^2 = (a+kd)(a+md)$, from where

$$a(2l-k-m) = d(km-l^2).$$

Here $2l-k-m \neq 0$. Indeed, if $2l-k-m = 0$, then $km-l^2 = 0$. But then $(k-m)^2 = (k+m)^2 - 4km = 4l^2 - 4l^2 = 0$, and therefore $k = m$, which contradicts the assumption $k < l < m$.

Therefore the relation $\frac{a}{d} = \frac{km-l^2}{2l-k-m}$ is rational.

**M203.** a) Prove that if the projections of the point of intersection of the diagonals $AC$ and $BD$ are satisfied then the intersections of ABCD on the lines

⟦folio 47⟧

Fig. 9.

Connect AB, BC, CD and DA in series with four straight lines (Fig. 8), then these straight lines will touch the same circle.

6) Form and prove the converse theorem.

Solving problem a), we must that the centrocircle inscribed in the quadrilateral KLMN (OK, OL, OM, ON are perpendiculars dropped from the point O of the intersection of diagonals AC and BD to the sides AB, BC, CD, DA) is point O.

In order to prove this, it is enough to prove that all four spectrices of the corners of the quadrilateral KLMN pass through O. Let us prove this for the point K (since all four vertices are included in the condition of being perfectly symmetric, this has been proven).

Since quadrilaterals AKON and BLOK are inscribed in circles (with diameters AO and BO corresponding) and ABCD is also inscribed (by condition), then
$$NKO = NAO = DAC = DBC = OBL = OKL.$$
So, we have proven that OK is a bissertis of angle K.

The statement of the problem is proved in a similar way in the case when the projections fall on the extension of the side, but the circle can then touch the extended sides of the quadrilateral KLMN.

As for problem b), its solution turns out to be ambiguous. This is what this is all about.

We consider the theorem “if Q, then P” to be the converse of the theorem “if P, then Q” (here P and Q are somehow a statement). But most meaningful theorems have a more complex structure, including a number of individual requirements in the “conditions” and “conclusions”; for example, “if P₁, P₂ and P₃, then Q₁ and Q₂.” In such a situation, they often not only invert the theorem - say, “if Q₁ and Q₂, then P₁, P₂ and P₃”, but also compose other components:

"If P₁, P₂, Q₁ and Q₂, then P₃",

“If the point of intersection of the diagonals of a convex quadrilateral ABCD is equally distant from the four straight lines connecting its projections onto adjacent sides of the quadrilateral, then the quadrilateral ABCD is cyclic.

2. If through the vertices K, L, M, N of a quadrilateral circumscribed about a circle with center O, draw perpendiculars to the segments OK, OL, OM, ON of the corresponding one, then the quadrilateral KLMN is circumscribed about a circle with center O, then ABCD can be inscribed in the circle, and the center of the circle coincides with P.

3. Let K, L, M and N be the projections of the intersection point P of diagonals AC and BD of a convex quadrilateral ABCD onto its sides AB, BC, CD, DA. If the quadrilateral KLMN is circumscribed about a circle with center O, then ABCD can be inscribed in the circle, and the center of the circle coincides with P.

Some readers formulate a stronger theorem - 2 or 3, and prove a weaker one - 1 (that is, they silently assume that the center O and the intersection point of the diagonals AC and BD must coincide). We will prove 2 and 3.

2. Let us denote by A, B, C, D the intersection points of adjacent perpendiculars to bissertics OK, OL, OM, ON (Fig. 9) and connect these points with O. Using the fact that the quadrilaterals AKON, BLOK, CMOL, DNOM are inscribed, it is easy to prove that each quadrilateral with the same letters α, β, γ, δ is equal. After this it will be clear that α + β + γ + δ = BAD + BCD = ABC + ADC.

ABCD poses - inscribed. Next,
$$AOC = \left(\frac{\pi}{2} - \beta\right) + \left(\frac{\pi}{2} - \delta\right) + \left(\frac{\pi}{2} - \alpha\right) + \left(\frac{\pi}{2} - \gamma\right) = \pi,$$
poses the straight line A + C > D + B. Let us then prove that KLMN is not described, that is, that the bissertis angles K, L, M, N do not intersect at one point. Namely, we will prove that the bissertis of angles K and N intersect inside AKPN (similarly, the bissertis of angles L and M intersect inside CMPL).
