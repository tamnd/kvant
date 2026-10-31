---
id: 1973-7-resheniya-zadach-m170-m173-f188-f192-6a5678c5
issue: kvant_1973_7
year: 1973
number: "7"
title: Solutions to problems M170—M173; F188—F192
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 28
page_last: 30
page_labels: 26-28
tag: PT4C
lang: en
source: kvant_digital
extraction: vision
content_sha256: 10f77b41223782f9977845a6ed0dd509e794dfba9007900390b1136202831e7f
prompt_sha256: draft-1
translated_from: content/ru/1973/07/articles/07_resheniya-zadach-m170-m173-f188-f192-6a5678c5.md
source_content_sha256: 8f074fe59e394b1271d75a1ba0d97a0c3be5e8c75d0b034c3985d4811ab08699
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 26⟧

Problem solutions

M170—M173; F188—F192

M170. a) Let $M$ and $N$ be the tangent points of the circle inscribed in triangle ABC on the sides AB and AC, P be the point of intersection of line MN with the bisector of angle B. Prove that angle BPC is right.

b). Prove a more general fact: if a point O located inside a triangle, the maxim that $BOC - BAO = 90^\circ$, M and N are the bases of the perpendiculars dropped from the point O to the sides AB and AC, P is the intersection point of the lines BO and MN, then $BPC = 90^\circ$ (Fig. 1).

Problem a), indeed, is a special case 6): if O is the center of the incircle, then BOC in the sum with the angles OCB and OBC is equal to 180°, and BAO in the sum with the same angles is equal to half the sum of the angles of the triangle, that is, 90°.

Let us immediately solve problem 6). To determine the point, let P lie on the continuation of the segment MN beyond the point N, as on our figure. (Other cases are broken down in a similar way; you can easily handle them on your own.) By condition $OMA = ONA = 90^\circ$, therefore, the vector of the quadrilateral OMNA can be described by a circle, therefore,

$$OMM = OAM = BAO.$$

Let us now show that points O, N, P and C lie on the same circle. Indeed, $CNP = MNA = 90^\circ - MNO = 90^\circ - BAO = 180^\circ - BAO$.

Using the conditions of the problem: $BOC - BAO = 90^\circ$, we obtain $CNP = CPO$.

Finally, since the quadrilateral CONP is cyclic, the equality $CPO = CNO = 90^\circ$ we need follows.

I. F. Sharytsin

M171. A regular six-dimensional plank is drawn on the plane, the side length of which is equal to 1. Using a ruler, construct a segment of length $\sqrt{7}$.

You can easily prove that the length of the red segments on figure 2 is equal to $\sqrt{7}$.

Fig. 2.

M172. Prove that for any prime p the number $\underline{11\dots1}$ $\underline{22\dots2}$ $\underline{33\dots3}$ $\dots$ $\underline{99\dots9}$ $= \underline{10\dots02}$ $\underline{0\dots03}$ $\dots$ $\underline{0\dots08}$ $\underline{0\dots09}$ $= 10^8p + 2 \cdot 10^7p + 3 \cdot 10^6p + \dots + 8 \cdot 10^p + 9 = C$, $\underline{11\dots1} = E$.

It is clear that $B = E \cdot C$, $C - A = (10^8p - 10^8) + 2 (10^7p - 10^7) + 3 (10^6p - 10^6) + \dots + 8 (10^p - 10)$, $10^p - 10 = (9 \cdot E + 1) - 10 = 9 (E - 1)$.

According to Fermat's little theorem (see «Kvant» No. 10 (1972)), the number $n^p$ - n is divisible by $p$ for any prime $p$ and any natural

⟦folio 27⟧

In particular, $10^p - 10, 10^2p - 10^2, \dots, 10^8p - 10^8$ is divisible by $p$. So $C - A$ is divisible by $p$, and $9(E - 1)$ is divisible by $p$.

Since the sum of the digits of the number $A$ is 45, then $A$ is divisible by 9, and therefore $A(E - 1)$ is divisible by 9 $(E - 1)$. Therefore, $A(E - 1)$ is divisible by $p$.

Thus, $B - A = EC - AE + AE - A = E(C - A) + A(E - 1)$ is divisible by $p$, which is what needed to be proved.

M. L. Gerver

M173. In the square table $4 \times 4$ of distances the numbers are 1, 2, 3, ..., 16 max., that the sum of the numbers in all rows in each row, in each column and on each of the two diagonals is equal to the same number, with 1 and 16 standing in opposite corners of the table. Let us prove that in this quadratic the sum of any two numbers located symmetrically about the center is equal to 17. For numbers 1 and 16 this is true by condition. Let's assume that 1 is in the upper left corner, and 16 is in the lower right, then the other two numbers on the same diagonal - let's denote them by $a$ and $a'$ - satisfy the equality $a + a' = 17$. Let us always agree to denote the additional number $x$ up to 17 by $x' : x' = 17 - x$.

Let us now use the notation given on figure 3 ($S_i$ denote the sums of numbers in the corresponding cells).

The following equalities are true:
$$S_1 + c + d + a + a' + S_2 + S_3 + c + d + a + a' + S_4 + 2(b + c + d + e) = 34 \cdot 6$$

Fig. 3.

Fig. 4.

Fig. 5.

⟦folio 28⟧

Fig. 6.

F188. A refrigerator with a capacity of $P$ in a time of $t$ turned $n$ liters of water into ice, which initially had a temperature of $t^\circ$ C. How much water was released in the room during this time?

From the principle of operation of any refrigeration unit, it follows that both all the energy consumed by the refrigerator from the network, and the energy that is separated from the cooled products (in this case, water) are converted into heat. This means that the amount of heat released in the room during time $t$, $Q = P\tau + c_B m_B t^\circ + \lambda m_B$,

where $m_B = n$ is the mass of water expressed in kcal, $c_B$ is the specific heat capacity of water and $\lambda$ is the specific heat of melting of ice.

I. Sh. Slobodetsky

F189. The charge $q = 10^{-8}$ to is uniformly distributed over the soul of a circle of radius $R = 1$ cm with a distance angle of water and $\lambda = 2/3$ π radians. Determine the electric field strength at the center of the circle.

a) The volume of the arcs is divided into $n$ equal parts, each of which has a charge $q/n$. When reaching a large $n$ ($\pi R/n \ll R$), these charges can be considered accurate. Each of the charges creates a field in the center of the circle with a strength $\Delta E_i$ equal in magnitude

$$\Delta E_i = k \frac{q}{nR^2},$$

where $k = \frac{1}{4\pi\epsilon_0} = 9.10^9 \text{ nm}^2/\text{k}^2$. The directions of vectors $\Delta E_i$ are shown in figure 6,a.

To find the total field strength $E = \sum_{i=1}^{n} \Delta E_i$, we will only add these vectors, placing the beginning of each vector at the end of the previous one (Fig. 6.6). The greater the value of $E$, the higher the accuracy of determination of $n$.

It is easy to notice that when $n$ reaches a large broken line, which is formed by adding the vectors $\Delta E_i$, one can notice a semicircle, and the magnitude of the vector $E$ is numerically equal to its diameter. For a semicircle, $l$ is equal to

$$l = n \Delta E_i = n \frac{kq}{nR^2} = \frac{kq}{R^2}.$$

On the other hand, $l = \pi E/2$.

From here

$$E = \frac{2l}{\pi} = \frac{2kq}{\pi R^2} = 5.7 \cdot 10^5 \text{ σ/m}.$$

6) The problem for an arc with an arbitrary opening angle $\varphi$ is solved similarly. In this case, the vector $E$ is the chord of the circular arc (Fig. 7.6). The length of the arc is $l = n \Delta E_i$, the central angle is $\varphi$ (pad) ($\varphi$ is the maximum angle between the vectors $\Delta E_i$).

Let us denote the radius of the circle $r$ and express through it the length of the arc $l$ and the chord $E$:

$$l = r \varphi, \quad E = 2r \sin \frac{\varphi}{2}.$$

But $l = n \Delta E_i = kq/R^2$ therefore

$$E = 2 \frac{kq}{\varphi R^2} \sin \frac{\varphi}{2}.$$

For $\varphi = 2/3$ π we get

$$E = 7.4 \cdot 10^5 \text{ σ/m}.$$

V. G. Svetmozarov

F190. The load is tied on a rope to a square beam $c$ by edge $a$ (Fig. 8). Rope length $l = na$ ($n$ is an integer). The load is given a speed of $V$ in the direction perpendicular to the rope. How long will it take for the entire rope to wrap around the beam?

Let us consider the case when at the initial moment the rope is parallel to one of the side faces of the beam ($\alpha = 0$). The load begins to move around the edge $A$ along a circle of radius $l$ with a linear speed $V$. After a quarter turn, the rope touches the edge of the beam, the load becomes at the same linear speed along a circle of radius $l - a$. After another quarter turn, the radius of the circle will become $l - 2a$, etc.
