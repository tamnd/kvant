---
id: 1977-11-resheniya-zadach-m431-m433-f442-f444-5a773a40
issue: kvant_1977_11
year: 1977
number: "11"
title: Solutions to problems M431—M433; F442—F444
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 51
page_last: 53
page_labels: 49-51
tag: 32ZX
lang: en
source: kvant_digital
extraction: vision
content_sha256: 1a7d08b26669a814ca1f81eff07b1a8bf50d85d079a74b08c3c80314ad507338
prompt_sha256: draft-1
translated_from: content/ru/1977/11/articles/13_resheniya-zadach-m431-m433-f442-f444-5a773a40.md
source_content_sha256: 6544da969551fc965bf41179e9a3871c911adfd75ea89f2c62fee8b55b9c429a
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 49⟧

Problem solutions
M431—M433; F442—F444

M431. Cylindrical trees grow in the forest. Connectivity is necessary to stretch a wire through the forest from point A to point B, the distance between them is equal to l. Prove that for this purpose, a piece of wire 1.6 l long is sufficient for connectivity.

Let's connect points A and B. In areas where there are no trees, we will draw a wire along this grama. In the same place where the straight line AB intersects the contour of the trunk, let us run the wire along the smaller of the two circles, limiting the section of the trunk by a plane perpendicular to the trunk (see Fig. 1). Let us show that in this case the length of the wire does not exceed $\frac{\pi l}{2}$.

Let $a_1, \dots, a_n$ be the lengths of straight sections of the wire, and $b_1, \dots, b_k$ be the lengths of straight sections AB located inside the trunks. Since each $b_i$ ($i=1, \dots, k$) does not exceed the diameter of the corresponding circle, the total length of the curved sections of the wire does not exceed $\frac{\pi b_1}{2} + \dots + \frac{\pi b_k}{2}$, and the total length of the wire does not exceed $\frac{\pi l}{2}$, it is impossible to replace less in this inequality, since it is easy to indicate an example when a wire of length wire $\frac{\pi l}{2}$ is required: a single tree of diameter l grows in the forest, and points A and B are diametrically opposite points of the circumference of its trunk.

A. Altschiller

Fig. 1.

M432. Is there a perfect square whose sum of digits is equal to
a) 1977;
b) 1978?
c) Find out which natural numbers can be the sum of the digits of the square of an integer.

Let's immediately solve point b) of the problem. First of all, we note that the sum of the digits of a square cannot be arbitrary. Indeed, the square of a lover's number by 9 either gives, when divided by 9, the remainders 1, 4, 7. By dividing by 9, the same is true for the sum of the digits of a square, so that for a square the sum of the digits can be of the form 9k, or 9k+1, or 9k+4, or 9k+7. Let us show that all such numbers can indeed be sums.

Indeed, the number 9k is the sum of the digits of the square of the number $10^k-1$:

$$(10^k-1)^2 = (10^k-2) \cdot 10^k + 1 = \underbrace{99 \dots 98}_{k} \underbrace{00 \dots 01}_{k};$$

⟦folio 50⟧

number $9k+1$ ($k \neq 0$) - sum of digits of the square of number $10^k-2$:
$$(10^k-2)^2 = (10^k-4) \cdot 10^k + 4 = \underbrace{99 \ldots 96}_{k} \underbrace{00 \ldots 04}_{k}$$

(scase $k=0$ veryident: $1=1^2$); number $9k+4$ ($k \neq 0$) - sum of digits of the square of number $10^k-3$:
$$(10^k-3)^2 = (10^k-6) \cdot 10^k + 9 = \underbrace{99 \ldots 94}_{k} \underbrace{00 \ldots 09}_{k}$$

(for $k=0$ we get the number 4, and $4=2^2$). The number $9k+7$ is the sum of the digits of the square of the number $10^k+1-5$:
$$(10^k+1-5)^2 = (10^k+1-10) \cdot 10^k+1 + 25 = \underbrace{99 \ldots 90}_{k+1} \underbrace{00 \ldots 025}_{k+1}$$

Thus, the number 1978 can be the sum of the digits of the square, but 1977 cannot.

L. Limanov

M433. In the convex heel
side ABCDE side
BC is parallel to the diagonal
AD, CD side - diagonals
BE, side DE - diagonals
AC and AE side -
diagonals BD (Fig. 2). Prove that side AB is parallel to diagonal CE.

Fig. 2.

Let $F = [AD] \cap [BE]$, $G = [AC] \cap [BE]$ and $K = [BD] \cap [AC]$ (see Fig. 2).

From the similarity of triangles $AEF$ and $BCD$ it follows that
$$\frac{|AF|}{|EF|} = \frac{|BC|}{|CD|}.$$ Therefore, $$\frac{|AF| + |BC|}{|EF| + |CD|} = \frac{|BC|}{|CD|}$$

and $$\frac{|AD|}{|BE|} = \frac{|BC|}{|CD|},$$ since $|BC| = |DF|$, $|BF| =$
$= |CD|$, that is
$$\frac{|BC|}{|AD|} = \frac{|CD|}{|BE|}.$$ (1)

Similarly, from the similarity of triangles $BKC$ and $AED$ we obtain that
$$\frac{|AE|}{|BD|} = \frac{|DE|}{|AC|}.$$ (2)

Finally, from the similarity of triangles $BKG$ and $AGE$
$$\frac{|BG|}{|BK|} = \frac{|CD|}{|AE|},$$ from $$\frac{|BE|}{|BD|} = \frac{|CD|}{|AE|},$$

or
$$\frac{|CD|}{|BE|} = \frac{|AE|}{|BD|}.$$ (3)

From correspondence (1) - (3) it follows that
$$\frac{|BC|}{|AD|} = \frac{|CD|}{|BE|} = \frac{|AE|}{|BD|} = \lambda.$$ (4)

Next:
$$\vec{BC} + \vec{CD} + \vec{DE} + \vec{EA} + \vec{AB} = \vec{0},$$
$$\vec{AD} + \vec{BE} + \vec{DB} + \vec{CA} + \vec{EC} = \vec{0},$$

and $$\vec{BC} = \lambda \vec{AD}, \vec{CD} = \lambda \vec{BE}, \vec{DE} = \lambda \vec{CA}, \vec{EA} = \lambda \vec{DB}.$$

Posetom
$$\vec{0} = \lambda (\vec{AD} + \vec{BE} + \vec{CA} + \vec{DB}) + \vec{AB} = -\lambda \vec{EC} + \vec{AB},$$

whence $$\vec{AB} = \lambda \vec{EC},$$ which means parallelism of side $AB$ of diagonal $EC$.

A shorter solution is obtained using the coangular coordinate system. Let the points $D, C$ and $E$ have coordinates $D(0; 0), C(1; 0), E(0; 1)$ (Fig. 2). Then $A$ and $B$ have coordinates $(1; a)$ and $(b; 1)$, since $(CD) \parallel (BE), (DE) \parallel (AC).$

⟦folio 51⟧

The parallelism conditions $(AE) \parallel (BD)$ and $(BC) \parallel (AD)$ are written as follows:

$$\frac{a-1}{1-0} = \frac{1-0}{b-0} \quad \text{и} \quad \frac{1-0}{b-1} = \frac{a-0}{1-0},$$

that is, $b(a-1)=1$, $a(b-1)=1$, whence $a=b$ and $\frac{a-1}{1-b} = \frac{1-0}{0-1}$, that is, $(AB) \parallel (EC)$.

Note that the spotty $ABCDE$, which is discussed in this problem, can be turned into a regular one by an affine transformation (or simply a skew).

I. Klumova, E. Turkevich

F442. Balls with masses 1, 2, 3 and 4 ke are connected by light rods, each 1 m long. The rods are fastened together so that they form a cross (Fig.3). The system can rotate freely in the surrounding axis passing through point O perpendicular to the plane figure. Find the amplitude of the system’s oscillations if at the initial moment the rod connecting the balls with the masses $m_2=2$ke and $m_4=4$ke was vertical and the balls were motionless.

Fig. 3.

F443. As you know, the globe makes a complete revolution around its axis in 23 hours 56 minutes 4 seconds. Therefore, during the day, all watches whose dial is divided into 24 hours must stand for almost 4 minutes. This amounts to almost a complete revolution around its axis in 23 hours 56 minutes 4 seconds. Therefore, it is still observed on each earth that the stars in the sky in time $T$ make a complete revolution around their axis in 23 hours 56 minutes 4 s, the Sun “circulates” the Earth in 24 hours (and it is precisely 24 hours, in connection with this, that the dial of all earthly clocks is divided).

This happens because during a full revolution around its axis, the Earth in its orbital motion around the Sun manages to advance approximately 1/365 of an hour of the orbital length (Fig. 5). For example, although the globe makes a complete revolution around its axis, therefore the earthly observer saw the Sun, roughly speaking, in the same place (and noted, for example, the onset of noon on his watch), the globe must additionally make 1/365 of an hour of rotation, which takes almost 4 minutes.

B. Bukhovtsev
