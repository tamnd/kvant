---
id: 1975-4-resheniya-zadach-m280-m285-f291-f295-ebe723f7
issue: kvant_1975_4
year: 1975
number: "4"
title: Solutions to problems M280—M285; F291—F295
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 29
page_last: 38
page_labels: 27, 28, 29, 30, 31, 32, 33, 34, 36
tag: G9EZ
lang: en
source: kvant_digital
extraction: vision
content_sha256: ee407f615d23fb0eb553f9735a06de4de2891a1ea84177f86750bf353101f447
prompt_sha256: draft-1
translated_from: content/ru/1975/04/articles/08_resheniya-zadach-m280-m285-f291-f295-ebe723f7.md
source_content_sha256: 71681615cc9f57c3de695607491eb988ecdbc588e77cd96ce7aee485e7e031c7
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 27⟧

The solution has two parts. First, we will prove that the area of ​​the common part is not less than half the area of ​​the triangle $A_1B_1C_1$ and $KLM$, if the points $K$, $L$ and $M$ lie correspondingly on the segments $AB_1$, $CA_1$ and $BC_1$?

Fig. 1.

Fig. 2.

Fig. 3.

M280. Given a triangle $ABC$ of area 1. Let $A_1, B_1$ and $C_1$ be the midpoints of sides $BC$, $AC$ and $AB$ accordingly. What is the minimum area that the common part of the triangle $A_1B_1C_1$ and $KLM$ can have if the points $K$, $L$ and $M$ lie correspondingly on the segments $AB_1$, $CA_1$ and $BC_1$?

Fig. 1.

Fig. 2.

Fig. 3.

M281. How many sides can a convex polygon have, all of whose diagonals have a length?

The solution has two parts. First, we will prove that the area of ​​the common part is not less than half the area of ​​the triangle $A_1B_1C_1$ and $KLM$, if the points $K$, $L$ and $M$ lie correspondingly on the segments $AB_1$, $CA_1$ and $BC_1$?

1) Let us denote by $Q$ the intersection point of the segments $KL$ and $C_1B_1$, and by $R$ and $T$ the intersection points of the segment $KM$ with the segment $C_1B_1$ and the continuation of the segment $CB$ (Fig. 1). Let us prove that $RQ \geq QB_1$. In fact, from the similarity of triangles $KTL$ and $KRQ$, $KLC$ and $KQB_1$ we have $\frac{TL}{RQ} = \frac{LK}{QK} = \frac{LC}{QB_1}$, that is, $\frac{RQ}{QB_1} = \frac{TC}{LC}$; but $TL \geq BA_1 = A_1C \geq LC$ means $RQ \geq QB_1$. Likewise, $FP \geq PA_1$ and $XY \geq XC_1$ (see Fig. 1).

Let's connect the points $R$, $F$ and $Y$ (Fig. 2). Obviously, $S_{RQF} \geq S_{B1QF}$ (these triangles have the same height as $RQ \geq QB_1$), $S_{FPY} \geq S_{A1PY}$ and $S_{RXY} \geq S_{C1XR}$. Therefore, $S_{B1QF} + S_{A1PY} + S_{C1XR} \leq S_{RQF} + S_{FPY} + S_{RXY} + S_{RYF}$, and since the sum of the areas of all seven triangles is equal to the area of ​​$\triangle A_1B_1C_1$, then the right side of the resulting inequality is not less than half the area of ​​this triangle.

2) The required example is built on figure 3 (point $M$ coincides with point $B$, $K$—$B_1$, point $L$—any).

So, the minimum area of ​​the common part of triangles $A_1B_1C_1$ and $KLM$ is $\frac{1}{8}$.

B. M. Ivlev

◆

Let us prove that a polygon with the indicated property cannot have more than five sides.

Let us denote by $n$ the number of the side of the polygon and assume that $n \geq 6$. Let $A_1, A_2, \dots, A_{n-1}, A_n$ be the vertices of the polygon. Let's consider the vertices $A_1, A_2, A_{n-2}, A_{n-1}$. The segments $A_1A_2$ and $A_{n-2}A_{n-1}$ are the sides, and the segments $A_1A_{n-1}, A_2A_{n-2}$ are the diagonals of our polygon (due to the assumption of the number $n$, see Fig. 4).

In a convex quadrilateral $A_1A_2A_{n-2}A_{n-1}$, the sum of the diagonals $A_1A_{n-2}$ and $A_2A_{n-1}$ is always greater than its two sides $A_1A_{n-1}$ and $A_2A_{n-2}$; and this contradicts the fact that $A_1A_{n-1} = A_1A_{n-2} = A_2A_{n-1} = A_2A_{n-2}$ according to the conditions of the problem. So, $n < 6$.

⟦folio 28⟧

⟦figure⟧
Fig. 4.

Obviously, $n>3$ (the triangle has no diagonals). For cases $n=4$ and $n=5$, polygons with the indicated property are easy to construct: they are a square and a regular pentagon.

So, the answer to the problem is: the number of sides can be 4 or 5.

G. A. Galperin

**M282.** *The cells of a rectangular table with dimensions $m \times n$ contain any natural numbers. In one move, you can double all the numbers in one row or subtract one from all the numbers in one column. Prove that in a few moves you can make all numbers equal to zero.*

**M283.** *A convex polygon has the following property: if all its sides are moved to the outside by a distance of 1, then the resulting straight lines form a polygon similar to the original one. Prove that a circle can be inscribed in this polygon.*

⟦figure⟧
Fig. 5.

⟦column⟧

Let's first turn all the numbers in the first column into zeros. If there are ones in the first column, then we will double the numbers in those rows of the table at the intersection of which with the first column there are ones, and then subtract one from all the numbers in the first column. It is clear that in this case the “old” units will remain in place, and each number different from one in the first column will decrease by one. If there are no units in the first column from the very beginning, then we will subtract one from all its numbers until units (at least one) appear; and then we will perform the operation already described. We will repeat this operation (doubling the rows whose intersection with the first column contains ones, and then subtracting one from each number in the first column) until all the numbers in the first column become ones. By then subtracting one from each number in the first column, we turn them all into zeros.

So, we have a table in which the first column contains zeros, and the remaining $n-1$ columns contain natural numbers. By turning the numbers of the 2nd, 3rd, ..., $n$ columns sequentially into zeros in the described way (note that in this case the existing zeros will not “spoil”), we get a table consisting entirely of zeros.

S. V. Konyagin

Note that the converse statement is much easier to prove: if a circle can be inscribed in a polygon, then when all its sides are moved away by the same distance (in particular, by one), a similar polygon is obtained, and the center of similarity is the center of the circle (Fig. 5).

Let us now move on to solving the problem.

FIRST PROOF. Let the polygon $P'$ be obtained from the polygon $P$ by moving the sides inside the polygon $P$ to a distance of 1 and at the same time $P'$ can be obtained from $P$ by transforming $f$ similarity with a coefficient $k<1$. Let us subject the polygon $P$ to this transformation together with the polygon $P'$ drawn inside it. Then inside $P'$ (image $P$) a new polygon $P''$ (image $P'$) will appear, similar to $P'$ (with the coefficient $k$) and $P$ (with the coefficient $k^2$), and, obviously, the sides $P''=f(P')$ can be obtained by moving the sides $P'$ inward to a distance $k$. In the same way, moving the sides another $k^2$, we get a polygon $f(P'')=P^{(3)}$ located inside $P''$ (the image of $P''$ under the transformation $f$), and so on:
$$f(P^{(3)}) = P^{(4)}, \ldots, f(P^{(n)}) = P^{(n+1)}, \ldots$$
where $P \supset P' \supset P'' \supset P^{(3)} \supset \ldots \supset P^{(n)} \supset \ldots$

Obviously, since the sides of the polygon $P^{(n)}$ decrease in the same ratio each time, their lengths tend to zero, and therefore the intersection of all polygons

⟦folio 29⟧

consists of one point (Fig. 6)*). Let's denote it by $O$.

Each side of the polygon $P'$ is successively moved away by distances $k, k^2, k^3, \dots, k^n, \dots$, so the distance from each side to the point $O$ is equal to the same number - the sum of an infinite geometric progression

$$k + k^2 + k^3 + \dots + k^n + \dots = r.$$

Thus, a circle with center $O$ and radius $r$ touches all sides of the polygon $P'$.

Note that in the above proof it was not important which sides correspond to each other under such a transformation $f$, which takes $P$ to $P'$. Meanwhile, in most solutions sent by readers, it was tacitly assumed that a natural correspondence was meant: each side $P'$ is associated with a side $P$, which is obtained from it by moving it by one. One can prove the following lemma: if the polygons $P$ and $P'$ (obtained from $P$ by moving the sides by 1) are similar - with what angular correspondence of the sides (with a “rotation” or “symmetrical reflection” of the order of the side), then there will always be a similarity with the natural order of the side - prepare for the coefficient $k$ ($0 < k < 1$). We will give a proof that is independent of the first solution at the end, but for now we give two more solutions to the problem based on this lemma (that is, implying a natural correspondence of the sides under similarity).

Second proof. Let $[AB]$ be the side of $P$, $[A'B']$ the corresponding side of $P'$, $O$ the intersection point of $(AA')$ and $(BB')$. Then (see Fig. 7)

$$\frac{|A'O|}{|AO|} = \frac{|A'B'|}{|AB|} = \frac{|B'O|}{|BO|} = k.$$

It follows that at the same point $O$ line $BB'$ also intersects line $CC'$ (BC and $B'C'$ are the corresponding sides $P$ and $P'$), and so on. In addition, it is very important that the lines $AA'$, $BB'$, $CC'$, ... are bicsectic angles $A', B', C', \dots$, of the polygon $P'$. It follows that the point $O$ serves as the center of the circle inscribed at $P'$.

Third proof. Let us cut the “shell” between the polygons $P$ and $P'$ into a straight line, polygons of height 1 with bases $A'B', B'C', C'D', \dots$ and “rhombonds” - quadrangles remaining at each vertex $A, B, C, \dots$ (Fig. 8). Obviously, from these rhombons one can construct one polygon circumscribed about a circle of radius one, and its angles are respectively congested $A, B, C, \dots$, and the lengths of the sides are equal to the differences in the lengths of the polygons $P$ and $P'$ corresponding to the sides, that is, equal to $(1-k)|AB|, (1-k)|BC|$, .... Thus, our polygon $P'$ is similar to a polygon circumscribed about a circle of radius 1, which means that a circle can be inscribed in it (the radius will be equal, very indo, $r = \frac{k}{1-k}$).

Proof of the lemma. For each side $[AB]$ of the polygon $P$ we will denote by $[A'B']$ that side $P'$ that is obtained by moving $AB$ away.

*) The fact that this intersection is not empty can be easily deduced from a similar statement for the number line. Sequence of nested segments

$$[a; b] \supset [a_1; b_1] \supset \dots \supset [a_n; b_n] \supset \dots$$

always has a common point (this statement or any equivalent to it in the axiomatic introduction of real numbers is generally accepted as an axiom).

⟦folio 30⟧

Let, in case of similarity, side $[A_1B_1]$ correspond to $[A'_2B'_2]$:
$$[A_1B_1] \rightarrow [A'_2B'_2], [A_2B_2] \rightarrow [A'_3B'_3], \dots, [A_{r-1}B_{r-1}] \rightarrow [A'_rB'_r], [A_rB_r] \rightarrow [A'_1B'_1].$$
Then $\hat{A}_1 = \hat{A}_2 = \dots = \hat{A}_r = 2\alpha$ and $\hat{B}_1 = \hat{B}_2 = \dots = \hat{B}_r = 2\beta$, and therefore the difference in length $|A_iB_i| - |A'_iB'_i| = d$ is the same length $i$ ($d = \text{ctg} \alpha + \text{ctg} \beta$). Let $k$ be the similarity coefficient, $|A_iB_i| = x_i$. Then
$$\begin{cases}
x_1 - kx_r = d, \\
x_2 - kx_1 = d, \\
x_3 - kx_2 = d, \\
\dots \dots \dots \\
x_r - kx_{r-1} = d;
\end{cases}$$
but, as is easy to prove, this system (for $0 < k < 1$) has only one solution $x_1 = x_2 = \dots = x_r = \frac{d}{1-k}$. Thus, we have proven that for any side $A_1B_1$ of the polygon $P$
$$|A'_1B'_1| = k |A_1B_1|,$$
that is, the sides of the polygons corresponding to each other (in the absence!) are proportional. Angles do not change in the absence, so the similarity of polygons with the natural correspondence $[AB] \rightarrow [A'B']$ is proven.

H. B. Vasiliev

**M284. The sum of 100 natural numbers, each of which is not more than 100, is equal to 200. Prove that from them you can choose several numbers whose sum is equal to 100.**

We will solve this problem assuming that we are given $n=2k$ natural numbers, each of which is not greater than $n$ and whose sum is equal to $2n$. Let us prove that from these $n$ numbers we can choose several numbers so that their sum is equal to $n$.

Let the averages of the given numbers $a_1, \dots, a_n$ be any two, for example the numbers $a_1$ and $a_2$, different (if all numbers are the same, then they are all equal to 2 and $k$ of them add up to $n=2k$). Let's create new $n$ numbers:

$$\begin{cases}
A_0 = a_1, \\
A_1 = a_2, \\
A_2 = a_1 + a_2, \\
\dots \dots \dots \\
A_{n-1} = a_1 + a_2 + a_3 + \dots + a_{n-1}.
\end{cases}$$

Each of these numbers is less than $2n$, but greater than 0. The average of the remainders from dividing the numbers $A_0, \dots, A_{n-1}$ by $n$ will find either zero or two equal remainders (since the remainders, like numbers, are $n$). In the first case, $A_m$, corresponding to the zero remainder, is equal to $n$ (divisible by $n$, greater than 0 and less than $2n$). In the second - $A_m = A_k + n$ ($k < m$). Moreover, $m \neq 0$ and $m \neq 1$, since the numbers $A_0$ and $A_1$ do not exceed $n$. In the case of $m=2$, either $A_0$ is equal to $n$ or $A_1$ is equal to $n$. In other cases, $A_m = A_k + a_{k+1} + \dots + a_m$, from which we obtain that $a_{k+1} + \dots + a_m = n$.

C. B. Konyazin

⟦folio 31⟧

M285. A rectangular sheet of paper with dimensions $a \times b$ is cut into rectangular strips, each of which has one side of length 1. Prove that at least one of the numbers $a$ and $b$ is an integer.

Let's call the rectangular strip that is an element of the specified partition a block. Let us denote one of the sides of the original rectangle of length $b$ by $B$; Let's call a block horizontal if its single side is parallel to side $B$, and vertical otherwise. Let us denote the line parallel to $B$, separated from $B$ by a distance $x$ and intersecting this rectangle by $L_x$ (then $x \leq a$). We will assume that straight line $B$ is left.

If a vertical block is located between straight lines $L_i$ and $L_{i+1}$ for some integer $i$, then paint it red, paint the remaining vertical blocks blue, and all horizontal blocks yellow. We denote the sum of the lengths of the red segments of the line $L_x$ by $K(L_x)$, the blue ones by $C(L_x)$ and the yellow ones by $JK(L_x)$. (If a segment separates blocks of two colors, we will assume that it has a right block.) Obviously, $JK(L_x)$ is an integer for any $x$. Let us show that if we recolor all the blue blocks yellow, then the sum of the lengths of the yellow parts of any straight line $L_x$ will remain a number of integers. To do this, it is enough for us to prove that the sum of the lengths of the numbers of the line $L_x$ (that is, $C(L_x))$ is an integer for any $x$.

Let us denote all possible distances from blue blocks to $B$ by $\alpha_1, \alpha_2, \dots, \alpha_n$, and

$$0 < \alpha_1 < \alpha_2 < \dots < \alpha_n \leq a - 1.$$

First of all, we show that it is possible to recolor blocks $C^{(1)}_1, \dots, C^{(1)}_k$ that are distant from $B$ by a distance $\alpha_1$. Let $[a]$ be the integer part of $a$. Since $\alpha_1$ is the smallest average distance of the blue blocks from the line $B$ and $[\alpha_1] < \alpha_1$, then $K(L_{\alpha_1}) = K(L_{\alpha_1}) = b - JK(L_{\alpha_1})$. Therefore, $C(L_{\alpha_1}) = b - K(L_{\alpha_1}) - JK(L_{\alpha_1}) = JK(L_{\alpha_1}) - JK(L_{\alpha_1})$, is an integer, and, therefore, the blocks $C^{(1)}_1, \dots, C^{(1)}_k$ can be recolored, since an arbitrary straight line $L_x$ either intersects all of them or does not intersect any of them.

In the same way, it is proved that from the possibility of recoloring blocks $C^{(1)}_1, \dots, C^{(1)}_k$, separated from $B$ by a distance $\alpha_s$ for all $s \leq i - 1$, it follows that it is possible to recolor blocks $C^{(1)}_1, \dots, C^{(1)}_k$. Now the statement follows from the principle of mathematical induction: $C(L_x)$ is an integer for any $x$.

So, all we have left are red and yellow blocks. If now the line $L_a$ coincides with the side of the straight line, then $a$ is an integer. If not, then

$$b = JK(L_a + \varepsilon), [a] + \varepsilon < a,$$

and since $JK(L_x)$ is an integer, it follows that $b$ is an integer.

The statement has been fully proven.

I. N. Klumova

F291. Two identical capacitors $A$ and $B$, each emcristimo $C$, and a stone with inductance $L$ are connected, as shown in figure 9. At the initial moment, the switches $K$ are open, the capacitor $A$ is charged to the difference placed $U$. The charge of the capacitor $B$ and the current in the pebble are equal to zero. Determine the maximum value of the moka in the pebble after closing the key.

If there were no capacitor $B$, then after closing the switch, electromagnetic oscillations would arise in the circuit containing capacitor $A$ and the inductor. From the law of conservation of energy one could immediately find the maximum current.

In our case, there will be a redistribution of charge between the capacitors, and then oscillations will be established in the circuit. Let's try to explain this.

A section of a circuit consisting of two capacitors and connected wires can also be considered a resonant circuit. But its inductance - the inductance of the wires - is very small (compared to $L$), therefore the natural part of the oscillation in this circuit will be very large (hiring large natural frequencies of oscillations in the circuit, which

⟦folio 32⟧

They form capacitors and an inductor). Of course, this circuit also has active resistance, but it is very small compared, for example, with inductive resistance. Therefore, for some time after the switch is closed, the oscillations in the circuit can be considered insignificant. That is, in a circuit consisting of capacitors and wires, many current fluctuations will occur while the current in the coil can still be considered zero. Due to the resistance of the wires, the oscillation in this circuit will be damped. This leads to the rapid establishment of equilibrium and redistribution of charge equally between the capacitors (since the capacitances of the capacitors are equal). In this case, part of the energy of the electric field of the charged capacitor $A$ will turn into warm energy.

Let's find what part of the energy remains in the circuit after a rapid redistribution of charge between the capacitors. The initial charge of the capacitor $A$ was equal to $Q = CU$. After the charge was redistributed between the capacitors, their charges became equal to $\frac{Q}{2}$ and their energy to $\frac{Q^2}{8C} = \frac{CU^2}{8}$. Therefore, the total energy that remains in the circuit is $\frac{CU^2}{8} + \frac{CU^2}{8} = \frac{CU^2}{4}$.

(Before the key was closed, the energy in the circuit was equal to $\frac{CU^2}{2}$. Thus, half of the initial energy was converted into heat.)

Now let's place a circuit consisting of capacitors and an inductor. The current in the coil will be maximum when the capacitors are completely discharged and their energy is converted into the energy of the magnetic field in the coil. From the law of conservation of energy it follows that

$$\frac{CU^2}{4} = \frac{LI_{\max}^2}{2}.$$

From here

$$I_{\max} = U \sqrt{\frac{C}{2L}}.$$

F292. From one point at the bottom of a horizontal steep iron, balls spread out under small angles towards the generatrix of the iron with identical velocity projections along this generatrix (Fig. 10). Will these balls meet?

Let us consider the movement of the balls in a coordinate system that moves translationally along one of its axes, coinciding with the generatrix of the iron. The speed of the system $v$ is equal to the projection of the velocities of the balls onto the generatrix of the cylinder. In this coordinate system, all the balls at any moment of time are located in the same plane $P$, perepidicular to $v$. Let us assume that the balls slide without friction along the side surface of the iron, then in the $P$ plane these balls move along the curve shown in figure 11, that is, they oscillate.

If the amplitudes of the oscillations are small (the initial components of the velocities of the balls, perepidicular to the generatrix of the iron and tangent to its surface, are small), then the oscillations of the balls are harmonic and their period does not depend on the amplitude. In this case, after half a period, all the balls meet on the same generatrix $AA'$ of the iron from which they began their movement.

If the amplitudes of the oscillations of the balls are large, then the oscillations will not be harmonic, their periods will depend on the amplitude, and the balls will hit the generatrix $AA'$ at different times. This means that the balls do not meet together.

⟦folio 33⟧

F293. Mars during anti-
distance is located at
standing $l=5,56 \cdot 10^{10}$ m from
Earth and its angular diameter
meter $\alpha=25^{\circ}$, 1. Determine
acceleration of gravity on the surface of Mars,
if it is known that the maximum catch distance between the centers of Mars and its satellite Phobos is $\beta=34^{\circ}$, 5, and the period of revolution of Phobos around Mars is $T=2,76 \cdot 10^{4}$ s.

The acceleration of gravity on the surface of Mars according to the law of universal gravitation and Newton's second law is equal to

$$g_{M} = \gamma \frac{M}{R_{M}^{2}},$$

where $\gamma$ is the gravitational constant, $M$ is the mass of Mars, $R_{M}$ is its radius.

The radius of Mars can be determined directly from the problem conditions (see Fig. 12): $R_{M} = l \ tg \frac{\alpha}{2} = l \frac{\alpha}{2}$ (since $\alpha$ is small, then $tg \frac{\alpha}{2} = \frac{\alpha}{2}$).

Fig. 12.

To find the mass of Mars, consider the movement of its satellite Phobos. For simplicity of calculations, we will assume that the satellite rotates in a circular orbit, the radius $R$ of which is equal (see Fig. 12) $R = l \ tg \beta = l \beta$. The satellite's orbital period is $T$. The centripetal acceleration $a = \omega^{2} R = \left(\frac{2\pi}{T}\right)^{2} R$ is imparted to the satellite by the gravitational force $F = \gamma \frac{mM}{R^{2}}$ (m is the mass of the satellite). Therefore $a = \frac{F}{m}$, or $\left(\frac{2\pi}{T}\right)^{2} R = \gamma \frac{M}{R^{2}}$, whence

$$\gamma M = \left(\frac{2\pi}{T}\right)^{2} R^{3} = \left(\frac{2\pi}{T}\right)^{2} (l\beta)^{3}.$$

Then finally

$$g_{M} = \gamma \frac{M}{R_{M}^{2}} = \left(\frac{2\pi}{T}\right)^{2} \frac{(l\beta)^{3}}{(l\alpha/2)^{2}} = \frac{16\pi^{2}}{T^{2}} \left(\frac{\beta}{\alpha}\right)^{2} l\beta.$$

Substituting the data of the problem into this formula and taking into account that $1^{\prime \prime} = \frac{3,14}{180 \cdot 60 \cdot 60} \ p a \delta \approx 4,9 \cdot 10^{-5} \ p a \delta$, we obtain

$$g_{M} = 3,64 \ m/c^{2}.$$

F294. The body must be brought to some device located inside the high-pressure chamber. During the experiment, the pressure in the chamber changes, and this leads to a change in the resistance of any conductive

The power released at the resistance $R_{3}$ is equal to

$$P = I_{3}^{2} R_{3} = \frac{U_{3}^{2}}{R_{3}}$$

where $I_{3}$ is the current and $U_{3}$ is the voltage across the resistance $R_{3}$. Let us denote by $R_{0}$ the total resistance of the parallel-connected

⟦folio 34⟧

ki used as a heater. figure 13 shows a diagram used in the case where it is necessary that the amount of heat supplied at the same time depends very little on pressure. Resistance $R_3$ is the heater winding, $R_1$ and $R_2$ are some constant resistances that are located outside the high-pressure chamber. At what ratio between $R_1$, $R_2$ and $R_3$ does the power dissipated in resistance $R_3$ change least when the value of resistance $R_3$ changes?

⟦figure⟧
Fig. 13.

⟦figure⟧
Fig. 14.

⟦column⟧

nal resistances $R_2$ and $R_3$; then resistances $R_1$ and $R_0$ are connected in series and $\dfrac{U_3}{R_0} = \dfrac{U_0}{R_1+R_0}$, or

$$U_3 = U_0 \dfrac{R_0}{R_1+R_0}.$$

But $R_0 = \dfrac{R_2 R_3}{R_2+R_3}$ therefore

$$U_3 = U_0 \dfrac{R_2 R_3}{R_1 R_2 + R_1 R_3 + R_2 R_3},$$

And

$$P = \dfrac{U_0^2 R_2^2 R_3}{(R_1 R_2 + R_1 R_3 + R_2 R_3)^2} =$$

$$= \dfrac{U_0^2 R_2^2}{\left[\dfrac{R_1 R_2}{\sqrt{R_3}} + \sqrt{R_3}\,(R_1+R_2)\right]^2}. \quad (*)$$

Let us examine the resulting expression. At $R_3 = 0$ $P = 0$. With $R_3$ tending to $\infty$ (that is, $R_3 \gg R_1$ and $R_3 \gg R_2$), $P$ tends to $0$. Since $P(R_3)$ is a continuous function (this is clear from physical considerations), then at some value $R_3$ the power is maximum. The graph of the dependence of $P$ on $R_3$ is shown in figure 14. From the graph it is clear that with the same change $R_3$ the change in the value $P$ is minimal just when the value $P$ itself is maximum *). Thus, we need to find at what value $R_3$ the power is maximum, or, what is the same, the denominator in the expression (*) is minimum.

As is known, for two numbers $a$ and $b$ the arithmetic mean is not less than the geometric mean: $a+b \geqslant 2\sqrt{ab}$; $a+b$ is minimal and equal to $2\sqrt{ab}$ at $a=b$. The product of the terms $\dfrac{R_1 R_2}{\sqrt{R_3}}$ and $\sqrt{R_3}\,(R_1+R_2)$ does not depend on $R_3$, therefore, according to the above, the denominator of the expression (*) is minimal, which means $P$ is maximum if

$$\dfrac{R_1 R_2}{\sqrt{R_3}} = (R_2+R_1)\sqrt{R_3}, \text{ или } R_3 = \dfrac{R_1 R_2}{R_1+R_2}.$$

It is with this ratio between $R_1$, $R_2$ and $R_3$ that the power released at resistance $R_3$ changes least when the value of resistance $R_3$ changes.

---

*) Those who are familiar with the elements of higher mathematics know that when a function takes its maximum (or minimum) value, the rate of change of the function (first derivative) is zero.

⟦folio none⟧

F295. What must be the accuracy of measuring the acceleration of gravity at the surface of the Earth in order to detect a change in this value during the day due to the gravity of the Moon? Assume that the measurement is made at a point that lies in the plane of the Moon’s orbit; neglect the rotation of the Earth.

⟦figure⟧
Fig. 15.

⟦column⟧

Under the influence of attraction to each other, the Earth and Moon rotate around their common center of mass. In the reference system associated with the center of mass of the Earth-Moon system, two forces act on a body located near the Earth’s surface -

force of attraction from the Earth $F_3 = \gamma \dfrac{M_3\, m}{R_3^2}$ and force

attraction from the Moon $F_л = \gamma \dfrac{M_л\, m}{l^2}$, where $m$ is the mass of the body, $M_3$ is the mass of the Earth, $M_л$ is the mass of the Moon, $R_3$ is the radius of the Earth and $l$ is the distance from the body to the Moon. Sum

These forces impart acceleration $\mathbf{a} = \dfrac{1}{m}\,(\mathbf{F}_3 + \mathbf{F}_л)$ to the body.

In order to find the acceleration of a body relative to the Earth, it is necessary to take into account that in our reference system the Earth itself moves with centripetal acceleration imparted to it by the gravitational force $F_{3-л}$ acting on the Earth

from the side of the Moon: $a_3 = \dfrac{F_{3-л}}{M_3} = \gamma \dfrac{M_л}{l_0^2}$ ($l_0$ is the distance

between the centers of the Earth and the Moon).

Thus, the acceleration of a free fall of a body to the Earth (acceleration relative to the Earth) is equal to $\mathbf{g} = \mathbf{a} - \mathbf{a}_3$.

Since the Earth rotates around its axis, the relative positions of the body located on the surface of the Earth, the Earth and the Moon will change over time. Consequently, the free fall acceleration $g$ will also change. (However, we will not take into account the change in acceleration $g$ due to the fact that the rotating Earth is not an inertial frame of reference.)

$a)$

At the moment when the Moon, the Earth and the body are located along the same straight line and the Earth is between the body and the Moon (Fig. 15), the forces $\mathbf{F}_3$ and $\mathbf{F}_л$ are directed in the same direction and the acceleration of free fall is equal in absolute value

$$g_1 = \gamma \dfrac{M_3}{R_3^2} + \gamma \dfrac{M_л}{(l_0+R_3)^2} - \gamma \dfrac{M_л}{l_0^2} =$$

$$= \gamma \dfrac{M_3}{R_3^2} + \gamma \dfrac{M_л}{l_0^2}\, \dfrac{1-(1+x)^2}{(1+x)^2},$$

where $x = \dfrac{R_3}{l_0}$. Since $x \ll 1$, then $1-(1+x)^2 \approx 2x$ and, in addition, we can neglect $x$ compared to $1$ in the denominator of the second term. As a result we get that

$$g_1 \approx \gamma \dfrac{M_3}{R_3^2} - 2\gamma \dfrac{M_л}{l_0^2}\,x.$$

Through half a revolution of the Earth around its axis, when the body is at point $2$ between the Earth and the Moon (Fig.). 16,

35

⟦folio 36⟧

forces $F_g$ and $F_{\pi}$ are directed in opposite directions and
$g_2 = \gamma \frac{M_3}{R_3^2} - \gamma \frac{M_{\pi}}{(l_0 - R_3)^2} + \gamma \frac{M_{\pi}}{l_0^2} \approx \gamma \frac{M_3}{R_3^2} - 2\gamma \frac{M_{\pi}}{l_0^2} x$.

That is, the acceleration of the body at these two points is practically the same: $g_1 \approx g_2$.

At those moments when the body is at points 3 and 4, that is, 1/4 and 3/4 of a revolution after the start of the reference, the forces $F_3$ and $F_{\pi}$ are directed as shown in figure 17. The acceleration of gravity at point 3 is
$g_3 = \frac{F_3}{m} + \frac{F_{\pi}}{m} - a_3$. Let's compare the second and third terms in this expression. The directions of forces $F_{\pi}$ and accelerations $a_3$ practically coincide, and the absolute values ​​of the terms are almost the same: $\frac{F_{\pi}}{m} = \gamma \frac{M_{\pi}}{l_0^2 + R_3^2} \approx \gamma \frac{M_{\pi}}{l_0^2}$ (since $R_3 \ll l_0$), $a_3 = \gamma \frac{M_{\pi}}{l_0^2}$. Therefore, we can assume that the magnitude of the acceleration of free fall at points 3 and 4 is determined only by the force of attraction to the Earth:
$g_3 = g_4 = \frac{F_3}{m} = \gamma \frac{M_3}{R_3^2}$.

As you move away from points 3 and 4, the acceleration decreases.

Thus, at points 3 and 4, the acceleration of gravity is maximum, and at points 1 and 2 it is minimum.

Let's find the ratio $\frac{\Delta g}{g_3} = \frac{g_3 - g_1}{g_3}$:

$\frac{\Delta g}{g_3} = 2 \frac{M_{\pi}}{M_3} x^3 \approx 10^{-7}$.

Obviously, this is exactly what the accuracy of measuring the acceleration of gravity at the Earth's surface should be in order to detect a change in this value due to the attraction of bodies by the Moon.

I. Sh. Slobodetsky
