---
id: 1985-4-resheniya-zadach-m896-m900-f908-f912-36871dc8
issue: kvant_1985_4
year: 1985
number: "4"
title: Solutions to problems M896—M900; F908—F912
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 41
page_last: 47
page_labels: 39, 40, 41, 43, 44
tag: 88RS
lang: en
source: kvant_digital
extraction: vision
content_sha256: 0dcfd52eda1298348c2581001052b01f3cf059dc0cde101dc111bb97f7f51052
prompt_sha256: draft-1
translated_from: content/ru/1985/04/articles/16_resheniya-zadach-m896-m900-f908-f912-36871dc8.md
source_content_sha256: 235c9d7070b7a0887df40e8f8b5126ed1df7f7804aa0f403ba0402564d0221cd
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 39⟧

Problem solutions

M896 — M900; F908 — F912

First decision. Let $M$ and $N$ be the midpoints of $AB$ and $CD$, $h_M$ and $h_N$ - the distances from points $M$ and $N$ to lines $CD$ and $AB$, $a$ and $b$ - side lengths $AB$ and $CD$ (Fig. 1). Obviously, lines $BC$ and $AD$ are parallel if and only if each of them is parallel to the midline $MN$ of the quadrilateral, that is, when $S_{MNB}=S_{MNC}$ and $S_{MNA}=S_{MND}$. (The letter $S$, as usual, denotes the areas of the corresponding triangles.) And since $S_{MNA}=S_{MNB}=\frac{1}{2} \cdot \frac{AB}{2} \cdot h_N=\frac{a/h_N}{4}$ and, similarly, $S_{MNC}=S_{MND}=\frac{bh_M}{4}=\frac{ab}{8}$ (by condition $h_M=a/2$), lines $BC$ and $AD$ are parallel if and only if $h_N=b/2$, that is, when a circle with a diameter $CD$ touches $AB$.

Second solution. Let us first assume that the lines $AB$ and $CD$ intersect at the point $O$ (Fig. 2). We perform sequential symmetry with respect to the bisector of the angle $AOD$ and prepare with the center $O$ and the coefficient $OC/OB$ (so that the point $B$ goes to $C$). In this case, the point $A$ will go to some point $D'$ on the ray $OD$, and a circle with a diameter $AB$ will go into a circle with a diameter $CD'$, which, obviously, touches the line $AB$. The techniques $BC$ and $AD'$ are parallel, since $OC:OB=OD':OA$. Therefore, to complete the proof, it remains to note that a circle with diameter $CD$ touches a line $AB$ if and only if $D=D'$.

The case $AB\parallel CD$ is considered in a similar way: you just need to take a straight line equal to the length of $AB$ and $CD$ as the axis of symmetry, and replace the finished one with a parallel translation.

N. B. Vasiliev, V. N. Dubrovsky

◆ Answer: one of the required pairs is $x=1$, $y=18$.

Let's transform this expression:

$(x+y)^7-x^7-y^7$
$=7x^6+21x^5y^2+35x^4y^3+35x^3y^4+21x^2y^5+7xy^6$
$=7xy(x^5+3x^4y+5x^3y^2+5x^2y^3+3xy^4+y^5)$
$=7xy(x+y)(x^4+2x^3y+3x^2y^2+2xy^3+y^4)$
$=7xy(x+y)(x^2+xy+y^2)^2$.

In order for this expression to be divisible by $7^7$, it is necessary that $x^2+xy+y^2$ is divisible by $7^3$ (by convention, $xy(x+y)$ is not divisible by $7$). Let's put $x=1$ and try to find a $y$ such that $1+y+y^2=7^3=343$. This quadratic equation has roots $y_1=18$ and $y_2=-19$, thus one of the solutions to the problem is (1; 18).

It can be shown that all pairs of integers $(x, y)$ for which $x^2+xy+y^2$ is divisible by $7^3$ (that is, solutions to our problem) are described by the formulas: $(343n+k, 343m+18k), (343n+18k,$

⟦folio 40⟧

M898*. For odd natural numbers $a < b < c < d$ the following conditions hold: $ad = bc$, $a + d = 2^k$ and $b + c = 2^m$, where $k$ and $m$ are non-toric natural numbers. Prove that $a) a = 1$;
b) for each $m \geqslant 3$ there is, and only one, set of numbers $a, b, c, d, k$ that satisfies these conditions.

◆
a) Let us first establish that $k > m$. Using the data, there is only one set of numbers $a, b, c, d, k$ that satisfies these conditions.

$$2^k - 2^m = a + d - (b + c) = a - b + d - \frac{ad}{b} = \frac{d}{b} (b - a) - (b - a) = (b - a) \left( \frac{d}{b} - 1 \right) > 0$$

(since $b > a$, $d > b$), therefore $k > m$.

Let us now prove that $a + b = 2^{m-1}$. The equality $ad = bc$ can be rewritten as $a(2^k - a) = b(2^m - b)$, that is, $b^2 - a^2 = 2^m b - 2^k a = 2^m (b - 2^{k-m} a)$. Thus, the product of $b + a$ and $b - a$ is divisible by $2^m$ (we saw that $2^{k-m}$ is an integer). At the same time, their sum is $2b$, and $b$ is an odd number, so they cannot be divisible by 4 at the same time. And since these numbers are even, one of them must be divisible by $2^{m-1}$ (and the other only by $2^1$). But $b - a < b < (b + c)/2 = 2^{m-1}$, therefore $a + b$ is divisible by $2^{m-1}$. Taking into account the inequality $a + b < b + c = 2^m$ we conclude that $a + b = 2^{m-1}$.

Thus, $b = 2^{m-1} - a$ is therefore $c = 2^m - b = 2^{m-1} + a$, and $ad = bc = 2^{2m-2} - a^2$ is therefore $a(a + d) = 2^{2m-2}$. Since $a$ is an odd number, the last equality is only possible for $a = 1$.

b) From those obtained at the end of point a) it corresponds that the numbers $a, b, c, d$ and $k$ satisfy the conditions of the problem if and only if $a = 1$, $b = 2^{m-1} - 1$, $c = 2^{m-1} + 1$, $d = 2^{2m-2} - 1$, $k = 2m - 2$ for $m \geqslant 3$.

A. P. Savin

◆
a) First of all, note that it is enough to prove the statement of the problem for an equality of the form

$$x_1 + \dots + x_m = 0.$$

(The general case will be reduced to this if we transfer all terms from the right side to the left and take into account that the rounding of the number $-y_i$ coincides with the rounding of $y_i$, taken with a minus sign, since $-[y_i] - 1 \leqslant -y_i \leqslant -[y_i]$).

We will round the numbers $x_i$ in equality (*) one by one: one of them will be rounded, and we will simultaneously change some other by the same amount in the opposite direction - this equality will not be violated. All you have to do is make sure that the rounding of numbers that change remains the same. After no more than $m - 1$ such steps, we will round all the numbers in the equality (*), and it will still be true.

So, the path in equality (*) is non-integer numbers. Obviously there are at least two, say $x_i$

⟦folio 41⟧

and $x_j$ Let us assume that the distance $d$ from $x_i$ to the nearest integer $x_i'$ is not greater than the same distance for $x_j$. Replace $x_i$ with $x_i'$, and $x_j$ with $x_j' = x_j + (x_i - x_i')$. In this case, the number of roundings of terms will increase, their sum remains zero, and the rounding of the number $x_j'$ will be the same as for $x_j$, since $[x_j] \leqslant x_j' \leqslant [x_j] + 1$.

6), c We will act according to the same plan as in point a). Let's add the number $-a_j$, $i=1, ..., m$ to the $i$-th row, under the $j$-th column - the number $-b_j$, $j=1, ..., n$, and in the lower right corner of this extended table we put the sum of all these numbers $s = a_1 + ... + a_m = b_1 + ... + b_n$. Obviously, it is enough to prove statement 6) (or c)) for a new table, that is, provided that the sums of numbers in all rows and columns are equal to zero. In order for these conditions to be preserved when rounding the next number, we will need to change an entire integer of numbers along with this number, and their rounding must remain the same. Let us describe the construction of such an integer.

Let's take some non-integer number $x_1$ from the table; in the same line with it there is necessarily another non-integer number $x_2$, in the same column with $x_2$ there is a non-integer $x_3$, in the same column with $x_3$ there is a non-integer $x_4$, etc. (see figure 1, 2). At some point, we will inevitably come to a number that is in the same row (row or column) with the number encountered earlier. Let $x_k$ be the first such number and let it be, say, in the same column as $x_k$ ($l < k$).

Suppose $x_{l+1}$ is on the same line as $x_l$ (Fig. 1). Then consider the integer numbers $x_p, x_{l+1}, ..., x_k$. Any two consecutive numbers in this integer are in the same row (next to $x_k$ we consider $x_l$), and at each step the integer “turns to $90^\circ$”, therefore, in the same line, as well as in the same column with any of them, there is exactly one more, and the total number of numbers in the integer is even. Let's choose the one that is close to an integer (if there are several of them, then any of them), let this number be $x_i$, and the closest integer be $x_i + d$. Let's replace $x_i$ with its rounding $x_i + d$ and, moving along the integer, we will alternately add $-d$ or $d$ to each next number (replace $x_{i+1}$ with $x_{i+1} - d$, $x_{i+2}$ with $x_{i+2} + d$, etc.). When we go through the entire integer, we will get a new table with zero sums in rows and columns, the rounding of all non-integer numbers in it will be the same as before, and the number of integers will increase.

If it turns out that $x_{l+1}$ is in the same column as $x_l$ (Fig. 2), then exactly the same reasoning must be checked with the whole $x_{l+1}, x_{l+2}, ..., x_k$.

After several repetitions of this operation, all numbers in the table will become integers.

For problem c) we have successfully proven that the sum of the roundings of the numbers in the original table that we have constructed is a rounding of their sum.

A. P. Savin

⟦folio 43⟧

=2, where B, P and G are the number of its vertices, edges and faces *)). We will derive (2) by following one of the many proofs of Euler's formula.

Let us calculate the sum $\sigma$ of all angles of all polygons of the “red” tiling in two ways. The sum of the angles at the vertices of the polygon P is equal to $(m-2)\pi$, and the sum of the angles at the $q_k$ “internal” vertices is $2q_k\pi$. Therefore, $\sigma = (m-2+2q_k)\pi$. On the other hand, by adding the sum of the angles of each of the polygons of the partition, that is, the value $(k-2)\pi$, where $k$ is the number of sides of the polygon, we find that $\sigma = (N-2n_k)\pi$, where $N$ is the sum of the side numbers of all these polygons, equal to $m+2p_k$. Thus, $m-2+2q_k = m+2p_k-2n_k$, which implies (2).

M. D. Kovalev

F908. Airplanes fly in one straight line towards each other with the same speed v. Maximum detection range - l. However, after detecting another plane, it makes a turn without changing its speed, and flies parallel to the second plane, which continues to fly at speed $\vec{v}$. Will planes lose sight of each other after turning if the acceleration during the turn is a? How long after detection should the turn begin so that at the end of the turn the distance between the aircraft is the smallest?

$$L^2 = x^2 + y^2 = (l - \pi R - 2v\tau)^2 + 4R^2.$$

It is clear that the value of $L$ (τ) is minimal with the minimum possible value of $|x(\tau)|$ (y does not depend on τ). In this regard, two cases arise: at $l \geqslant \pi R$ the beginning $L = 2R$ is reached at $x=0$, that is, when

$$\tau = \frac{l - \pi R}{2v} = \frac{1}{2} \left( \frac{l}{v} - \frac{\pi v}{a} \right);$$

at $l < \pi R$ the value of $L$ is minimal at $\tau=0$ and is equal to $L = \sqrt{4R^2 + (l - \pi R)^2}$.

In the case of $l \geqslant \pi R$, the starting $L = 2R$ has completed the maximum detection range. Let's find in what direction $l = l_0$ the planes will still remain within visibility after the turn, that is, when

$$L^2 = 4R^2 + (l_0 - \pi R)^2 = l_0^2.$$

Solving this equation for $l_0$, we obtain

$$l_0 = \frac{4 + \pi^2}{2\pi} R = \frac{4 + \pi^2}{2\pi} \frac{v^2}{a}.$$

So, at $l \geqslant l_0$ the planes do not consume each other out of sight. In the opposite case ($l < l_0$), after turning around, they are outside the detection range.

I. I. Sparrow

*) See, for example, the article by M. Shubin “Topology and terrain” («Kvant», 1982, No. 8, p. 14).

⟦folio 44⟧

F909. There are two balls on a weightless slide formed by two main planes, each of which makes an angle α with the horizontal plane (see figure). The slide can slide along a horizontal plane without a triangle. The upper ball, whose mass is m₁, is released. Under what conditions does the lower ball, whose mass is m₂, then begin to “climb” up the hill?

It is clear that if the second ball is light enough, it will begin to climb the hill. Let's find its limiting mass m₀², at which it has not yet begun to rise, but has already stopped pressing the right inclined plane.

Since the slide is not weighty, in this case the sum of the horizontal projections of pressure forces acting on the slide from the side of the balls must be equal to zero. This means that (see figure)

$$N_1 \sin \alpha = N_2 \sin \alpha,$$

In addition, since the second ball does not rise, the projections of the accelerations of the balls on the normal to the right inclined plane must be the same (and equal to the projection of the acceleration of the slide on this direction). As can be seen from figure, the angle between the force N₂ and the right inclined plane is 90°—2α, and therefore the last condition can be written in the form

$$\frac{m_1 g \cos \alpha - N_1}{m_1} = \frac{m_2^0 g \cos \alpha - N_2 \cos 2\alpha}{m_2^0}.$$

From here is:

$$m_2^0 = m_1 \cos 2\alpha.$$

Thus, the bottom ball will “climb” onto the slide if the condition m₂ < m₁ cos 2α is met.

A. I. Buzdin

F910. A uniformly growing rubber ring of mass m is attached to a cylinder of radius R. The length of the ring in the unstretched state is equal to πR, the area of ​​rubber is k. The cylinder begins to spin with a constant angular acceleration β. After what time does the ring begin to slip relative to the cylinder if the coefficient of friction between the ring and the cylinder is μ? What will be the angular velocity of the ring?

Consider a small ring element that is visible from the center of the ring at angle Δα (see figure).

The mass of this element is Δm = $\frac{m}{2\pi} \cdot \Delta\alpha$. It is acted upon by the forces $\vec{N}$ of the normal reaction from the side of the cylinder, the friction force Fτ and the tension force from the neighboring sections of the ring (we neglect the gravitational force). Since the ring grows uniformly, the tension forces are the same in absolute value and equal to T=kπ(2R-R)=kπR. The equal force of all these forces gives the ring element an acceleration $\vec{a}$. The projection $\vec{a}$ on the radial direction is the centripetal acceleration a₁(t) at a given time, and the projection $\vec{a}$ on the tangent direction to the cylinder is the tangential acceleration a₇(t) at a given moment. Since the linear velocity v(t) is related to the angular velocity ω(t) by the correspondence v(t)=ω(t) R=βRt (t=0 is the beginning of rotation),

$$a_1(t) = \frac{(v(t))^2}{R} = \beta^2 Rt^2,$$

$$a_7(t) = (v(t))' = \beta R.$$

Let the slipping of the ring begin at time t after the start of rotation. According to Newton's second law, for 0 < t < τ

$$2T \cdot \frac{\Delta\alpha}{2} - N(t) = \Delta m \cdot a_1(t) = \frac{m}{2\pi} \cdot \Delta\alpha \cdot \beta^2 Rt^2,$$

(1)

$$F_{τp} = \Delta m \cdot a_7(t) = \frac{m}{2\pi} \cdot \Delta\alpha \cdot \beta R$$

(2)

⟦folio none⟧

(we taught that $\Delta \alpha$ insisted little that $\sin \frac{\Delta a}{2} \approx \frac{\Delta a}{2}$).

All this time $F_{\text{tp}}$ is the strength of the friction of rest. As the speed increases, the force $N(t)$ decreases. Compliance decreases the maximum value $\mu \cdot N(t)$ of the static friction force; at time $\tau$ it will be equal to the value $F_{\text{tp}} = \Delta m \cdot \beta R$ - scaling will begin.

Substituting $t = \tau$ and $F_{\text{tp}} = \mu \cdot N(\tau)$ into (1) and (2), we find the value of $\tau$:

$$\tau = \sqrt{\left(\frac{2\mu k\pi^2}{m} - \beta\right)/\mu\beta^2}.$$

A. A. Lapides

F911. figure shows a graph of changes in the pressure of powder gases in the steering wheel as the bullet moves into the steering wheel. Determine the speed of gunpowder (in kk/s) at pressure $p_{\text{max}}$, if the speed of the bullet at this moment is $v$. The transverse area of ​​the second is so wound s. The temperature of the powder gases is considered constant. It is known that the powder gases, which form a mass of gunpowder M during acceleration, create a pressure of $p_0$ in a volume of $V_0$.

The change in the pressure of the powder gases in the table occurs due to a change in the mass of the exploding gunpowder and due to a change in the volume occupied by the gases as the bullet moves. For the first reason, there should be an increase in pressure, for the second, a decrease. As can be seen from figure, the first trend prevails in section 1–2, and the second trend prevails in section 2–3. At time $\tau$, when the pressure is $p_{\text{max}}$, the increase in pressure due to the abrasion of gunpowder compensates for the increase in pressure due to the advancement of the bullet.

Let us write down the equation of state of gases at that moment of time $\tau$, when their pressure is equal to $p_{\text{max}}$:

$$p_{\text{max}} V = \frac{m}{\mu} RT,$$

where $m$ is the mass of gunpowder that had been used up by this time, $V$ is the volume of space per bullet. Let the mass of gunpowder $\Delta m$ accumulate over a short period of time $\Delta t$, during which the pressure can be considered constant and equal to $p_{\text{max}}$. The volume of the pool space during this time increased by $\Delta V_1 = vs \cdot \Delta t$

(Δτ insisted little that the speed of the $v$ bullet can be considered constant). The gas pressure did not change during time $\Delta t$; this means that the gas formed when the mass $\Delta m$ of gunpowder is reduced, at a pressure $p_{\text{max}}$ occupies exactly the volume $\Delta V_1$, that is

$$p_{\text{max}} \cdot \Delta V_1 = \frac{\Delta m}{\mu} RT,$$ or $p_{\text{max}} vs \cdot \Delta t = \frac{\Delta m}{\mu} RT$.

From the last equality we find the pressure $\tau$:

$$\frac{\Delta m}{\Delta t} = p_{\text{max}} vs \cdot \frac{\mu}{RT}$$

From the conditions of the problem it is known that $p_0 V_0 = \frac{M}{\mu} RT$. From this we find that $\frac{RT}{\mu} = \frac{p_0 V_0}{M}$, and we finally get

$$\frac{\Delta m}{\Delta t} = \frac{M p_{\text{max}} sv}{p_0 V_0}$$

L. G. Markovich
