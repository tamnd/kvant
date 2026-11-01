---
id: 1985-3-resheniya-zadach-m891-m895-f903-f907-1c0660d5
issue: kvant_1985_3
year: 1985
number: "3"
title: Solutions to problems M891—M895; F903—F907
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 30
page_last: 33
page_labels: 28-31
tag: T8MA
lang: en
source: kvant_digital
extraction: vision
content_sha256: 4fa69c5561f1c3d311424ba5f7f06ace5bef438e93e533e2192cdad306693b88
prompt_sha256: draft-1
translated_from: content/ru/1985/03/articles/14_resheniya-zadach-m891-m895-f903-f907-1c0660d5.md
source_content_sha256: 745b7593093f06d36e4cf134ddebb58f92107bd67201a45314dc9004ba934ab1
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 28⟧

—4q, ..., —1984q, 1985q (q>0), respectively.
Prove that one of the balls has an everywhere positive charge density on its surface. The distances between the balls are finite.

V. A. Yasinski

P927. A charged particle flies through a scintillation counter; the scintillating molecules along its trajectory emit light. The light is emitted isotropically (i.e. uniformly in all directions) at each point. What part of the emitted light will leave the scintillator into the air, if the refraction coefficient of the scintillating matter is $n=1.6$? Light absorption in the scintillator may be neglected.

Remark. The solid angle at the vertex of a cone equals $\Omega=2\pi(1-\cos\theta)$, where $\theta$ is the angle between the cone's axis and its generator.

S. A. Khorozov

Problem solutions

M891 — M895; F903 — F907

In this triangle $ABC$ we denote the lengths of sides $BC$ and $CA$ by $a$ and $b$, the lengths of medians $AA_1$ and $BB_1$ by $m_a$ and $m_b$, the point of intersection of the medians by $M$ (see. figure). Since the distance from the middle of a side to the point of intersection of the medians is equal to its third, and the quadrilateral $MA_1CB_1$ is described around a circle, the equality $m_a/3+b/2=m_b/3+a/2$ or

$$m_a + \frac{3b}{2} = m_b + \frac{3a}{2}. \tag{1}$$

Further, triangles $AA_1C$ and $BB_1C$ have equal areas (equal to the area of ​​triangle $ABC$) and a common incircle, so their perimeters are equal: $m_a+a/2+b=m_b+b/2+a$, that is

$$m_a + \frac{b}{2} = m_b + \frac{a}{2}. \tag{2}$$

Subtracting equality (2) from (1), we obtain $a=b$.

Note that the statement of the problem is also true when the circle touches the extensions of two sides of the triangle and two medians.

A. A. Muragov

M892. a) Prove that among the numbers $2^m+2^k$, as well as among the numbers $3^m+3^k$, there is infinitely multiple order, and among the numbers $4^m+4^k$, $5^m+5^k$ and $6^m+6^k$ there is not a single square integer (here $m$ and $k$ are natural numbers, $m \neq k$).
b)* Are there squares among the numbers $7^m+7^k$?

a) Let us first note that if the number $a^m+a^k$ is a square, then there are infinitely many squares of this type: $a^{m+2n}+a^{k+2n}=(a^n)^2 \cdot (a^m+a^k)$ (here $m$ or $k$ can also equal zero). Therefore, the statement of the problem for $a=2$ and $a=3$ follows from the equalities $2^3+2^0=8+1=3^2$, $3^1+3^0=2^2$.

Case $a=4$. Let $4^m+4^k=b^2$, where $b$ is an integer, and $m>k$; then $4^{m-k}+1=(b/2^k)^2$ or $4^n+1=c^2 (n=m-k, c=b/2^k)$. It follows that $(c+2^n)(c-2^n)=1$, which is very much impossible.

⟦folio 29⟧

Case $a=5$. It is easy to see that the number $5^m$ for any $m>1$ ends with the digits 25, so $5^m+5^k$ can only end in 30 (for $k=1$) or 50 (for $k>1$) and, therefore, cannot be a square (a square ending in zero must be divisible by 100).

Case $a=6$. The power of 6 always ends in 6, which means the number $6^m+6^k$ always ends in 2. But squares of integers can only end in 0, 1, 4, 6, 9.

6) Answer: no. Since 7 when divided by 3 leaves a remainder of 1, all powers of seven also have the same remainder. Therefore, the number $7^m+7^k$ gives remainder 2 when divided by 3 and, therefore, cannot be a square $((3n)^2$ is divisible by 3, but $(3n \pm 1)^2 = 3(3n^2 \pm 2n) + 1)$.

A. I. Zaichik, V. N. Dubrovsky

M893. Each two of the n computer blocks are connected by a wire. Is it possible to cover each of these wires in one of n—1 colors so that n—1 wires of different colors come out of each block if a) $n=6$; b) $n=13$?

a) Answer: yes. The required coloring is shown at figure.

6) Answer: no. Indeed, if $m$ perforations of any one color were used, then the number of blocks is $2m$ (the number of ends of all these perforations, and each end is connected to exactly one block). But 13 is an odd number.

This problem is often formulated as a problem of creating a schedule for a circular tourer - in this case, wires of the same color are answered by dividing the tourer sections into pairs for the same type. We have seen that for odd $n$ this problem is unsolvable. It can be proven that for even $n$ it always has a solution (see, for example, the book by O. Ore “Invitation to Number Theory” (M.: Hayka, 1980, Chapter 8, § 3), as well as the solution to problem 1.16 in the book “Correspondence Mathematical Descriptions” (M.: Hayka, 1981, p. 19)).

V. V. Alekseev

M894. a) The sum of the heel of non-negative numbers is 1. Prove that they can be spaced around a circle so that the sum of the heel of pairwise products of neighboring numbers does not exceed 1/5.

b)* There are $n \geqslant 4$ non-negative numbers around the circle, the sum of which is equal to 1. Prove that the sum of all n pairwise products of neighboring numbers does not exceed 1/4.

a) We will prove it by contradiction. Let us assume that for any arrangement of numbers $a, b, c, d, e$ we consider a sum greater than 1/5, in particular (see figure 1 and 2):

$$ab+bc+cd+de+ea > 1/5,$$
$$ac+ce+eb+bd+da > 1/5.$$

From here we get a contradiction:

$$1 = (a+b+c+d+e)^2 = \frac{a^2+b^2}{2} + \frac{b^2+c^2}{2} + \frac{c^2+d^2}{2} +$$
$$+ \frac{d^2+e^2}{2} + \frac{e^2+a^2}{2} + 2[(ab+bc+cd+de+ea) +$$
$$+(ac+ce+eb+bd+da)] \geqslant$$
$$\geqslant 3(ab+bc+cd+de+ea) +$$
$$+ 2(ac+ce+eb+bd+da) > 1$$

(we used the inequality $x^2+y^2 \geqslant 2xy$).

From the solution it is clear that the condition for non-negativity of numbers does not exist. Task approval

⟦folio 30⟧

(with 1/5 replaced by 1/n) is valid for any $n$ numbers.

6) We must prove that for any $n \geqslant 4$ non-negative numbers $a_1, \dots, a_n$ whose sum is 1, the inequality holds
$$a_1a_2 + a_2a_3 + \dots + a_{n-1}a_n + a_na_1 \leqslant 1/4.$$

For even $n (n=2m)$ this inequality is proven indefinitely: let $a_1 + a_3 + \dots + a_{2m-1} = a$; then obviously
$$a_1a_2 + \dots + a_na_1 \leqslant (a_1 + a_3 + \dots + a_{2m-1}) \times \times (a_2 + a_4 + \dots + a_{2m}) = a(1-a) \leqslant 1/4.$$

Now let $n$ be odd and let $a_k$ be the smallest of the given numbers. (For convenience, we will assume that $1 < k < n-1$ - this does not limit the generality for $n \geqslant 4$.) Let us put $b_i = a_i$ for $i=1, \dots, k-1$, $b_k = a_k + a_{k+1}$ and $b_i = a_{i+1}$ for $i=k+1, \dots, n-1$. Applying our inequality to the numbers $b_1, \dots, b_{n-1}$, we get:
$$a_1a_2 + \dots + a_{k-2}a_{k-1} + (a_{k-1} + a_{k+2})b_k + a_{k+2}a_{k+3} + \dots + a_{n-1}a_n + a_na_1 \leqslant 1/4.$$

It remains to take advantage of the fact that
$$a_{k-1}a_k + a_ka_{k+1} + a_{k+1}a_{k+2} \leqslant a_{k-1}a_k + a_{k-1}a_{k+1} + a_{k+1}a_{k+2} \leqslant (a_{k-1} + a_{k+2})b_k.$$

Note that in general points the indicated estimates are exact (they cannot be reduced); in point a) the estimate $1/n$ is achieved when all $n$ numbers are equal, and in point 6) - when two of them are equal to 1/2 and the rest are 0.
S. V. Gashkov, A. N. Dranshinkov

**M895*. Prove that the area of ​​a section of a cube by a plane tangent to the sphere inscribed in it does not exceed half the area of ​​the face of the cube. Unwind the case when this section is a) a triangle, b) a quadrilateral. b) Prove that in case a) the area of ​​the complete surface of the cube of the triangle is less than the area of ​​the face. (The orthogonal projections of these three faces onto the plane of the first face completely cover it, and the areas of the projections are less than the areas of the faces themselves.) However, we will prove a) independently, since this will give a somewhat more general result.

Let us denote the vertices of the triangular section of the cube under consideration by $A, B, C$, the common vertex of the three edges; on which they lie - through $V$, the points of contact of the inscribed sphere with the planes $ABC, VAB, VBC, VCA$ - through $T, K, L, M$ (the last three points, very conveniently, are the centers of the face of the cube; Fig. 1). Due to the equality of tangents drawn to the sphere from one point, $AT=AK=AM, BT=BK=BL, CT=CL=CM$, therefore the triangles $ABK$ and $ABT, BCL$ and $BCT, CAM$ and $CAT$ (Fig. 1), as well as $AVK$ and $AVM, BVK$ and $BVL, CVL$ and $CVM$ (Fig. 2) are pairwise equal and, moreover, equal in size. Consequently, the area of ​​the section $ABC$ is equal to the sum $S_1$ of the areas of the triangles on figure 1, and the area $S_{\text{тетр}}$ of the complete surface of the triangle $VABC$ is equal to the sum of the areas of the quadrilaterals $AKBV, BLCV$ and $CMAV$, that is, twice the sum

⟦folio 31⟧

$S_2$ areas of green, red and yellow triangles on figure 2:
$$S_{\text{тетр}} = 2S_2 = 2(S_{AKV} + S_{BKV} + S_{CLV}) = 2(S_{AKBV} + S_{CLV}).$$

Let $S_0$ be the area of ​​the cube face. Let us prove that for any three points $A, B, C$ on the edges of the cube, emanating from the vertex $V$,
$$S_1 = S_{ABK} + S_{BCL} + S_{CAM} \leq S_0 / 2$$
(1)
(and in particular statement a)).

To do this, note that if two of the three points, for example $B$ and $C$, are closed, then the areas of triangles $ABK$ and $ACM$, and hence always the sum $S_1$, linearly depend on $x=VA$ (for the proof, see figure 3). Therefore, you can always move the point $A$ to the end of the edge so that the value $S_1$ increases (or, in any case, does not decrease). The same can be done sequentially from points $B$ and $C$; therefore, it is enough to prove inequality (1) for points $A, B$ and $C$ located at the vertices of the cube. There are only 4 such locations (up to redesignation); they are shown at figure 4. In two cases $S_1=0$, in the other two $S_1=S_0 / 2$. It is easy to understand that, with the exception of the last two cases, the inequality in (1) is always strict, but the triangle $ABC$ on figure 4, in can be considered as the limit position of the section tangent to the written sphere, therefore the estimate in problem a) is exact.

Let us now prove the inequality
$$S_2 = S_{AKBV} + S_{CLV} < S_0 / 2$$
(and along with it - statement b)).

Let for definition $KB \geqslant KA$. Obviously, the line $KB$ divides the face of the cube into two equal trapezoids of area $S_0 / 2$, one of which - $VBB_1U$ (Fig. 2) consists of four triangles $AKBV$ and $AKB_1U$. Thus, it is enough to prove that
$$S_{CLV} < S_{AKB_1U}.$$
Let us plot the segment $UC_1=VC$ (Fig. 5) on the edge $UV$; then triangles $C_1KU$ and $CLV$ are equal, and $\angle C_1KU = \angle CLV = \angle AKB_1$.

(Indeed, from the equality of single-arm triangles on figure 2 it follows that $2(\angle CLV + \angle AKB) = \angle AKB + \angle BLC + \angle CMA = \angle ATB + \angle BTC + \angle CTA = 360^\circ = 2(\angle AKB_1 + \angle AKB)$.) Therefore, $\angle B_1KU = \angle C_1KA$ (Fig. 5) and, in addition, $KB_1 = KB \geqslant KA$, $KU > KC_1$, therefore $S_{AKC_1} < S_{B_1KU}$, that is
$$S_{CLV} = S_{C_1KU} = S_{AKC_1} + S_{AKU} < S_{B_1KU} + S_{AKU} = S_{AKB_1U}.$$
The same messages as in point a) show that here the estimate is accurate.

6) Let $ABCD$ be a quadrangular section of the cube separating edge $UV$ from it and intersecting the faces with centers $K, L, M, N$ (Fig. 6). As above, it is easy to see that its area is equal to the sum $S_3$ of the areas of triangles $ABK, BCL, CDM$ and $DAN$, which is obviously less than the sum
$$S_4 = S_{ABK} + S_{BLCV} + S_{CDM} + S_{DNAU}.$$

(For the end see page 34)
