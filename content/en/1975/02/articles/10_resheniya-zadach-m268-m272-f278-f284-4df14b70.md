---
id: 1975-2-resheniya-zadach-m268-m272-f278-f284-4df14b70
issue: kvant_1975_2
year: 1975
number: "2"
title: Solutions to problems M268—M272; F278—F284
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 30
page_last: 42
page_labels: 28-40
tag: U8NV
lang: en
source: kvant_digital
extraction: vision
content_sha256: 7c373a98ebc92a94202ee874547fe503d9096090c19771f657702a2be7e54d87
prompt_sha256: draft-1
translated_from: content/ru/1975/02/articles/10_resheniya-zadach-m268-m272-f278-f284-4df14b70.md
source_content_sha256: 173c37f53fc9c5b9acce90821eff3299d4047a9f1e0e079cff8aa655f39e34c3
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 28⟧

Problem solutions

M268. In the corner of the chessboard, stosht ftsurra. The first cerok can move it twice in a row as a regular knight (two squares in one direction, one in a perpendicular direction), and the second can move it once as a knight with an extended move (three squares in one direction and one in a perpendicular direction). So they take turns. The first one strives to place the ftsurra in the opposite corner, and the second one tries to place it in it. Which of them can withstand (the dimensions of the board are $n \times n$, where $n \geq 4$)?

Let the knight first be in the lower left corner of the board. It is clear that the first player, with his first move, can take the knight out of the corner of the board and place it on the diagonal (see figure 1 - the blue cross is the result of the first player's move). Let us prove that the first player can, as if on his own, return to the diagonal, and higher and higher.

Let the first player place the knight on some square of the diagonal of the board (Fig. 2). The squares into which the second player can move the knight from the diagonal are placed on figure 2 with black and red crosses. From the squares marked with red crosses, the first player can return the knight to the diagonal of the board, moving it up exactly one square (in the direction of the desired angle). From the cells placed with black crosses, the first player can also return the knight to the diagonal, but not to the next cell, but after one. However, it is clear that at the end of the game the second player will not be able to place the knight in the cells placed with black crosses: the board is limited, and when one or two squares remain to the upper corner, the upper and right borders of the board will be “cut off” from the resulting configuration by black crosses - cells (Fig. 3); the second player will be forced to start placing the knight in the squares placed with red crosses. It is clear that in this case the first player will achieve the goal.

I. N. Klumova

M269. Let us denote by $T_k(n)$ the sum of the products of $k$ numbers from 1 to $n$. For example, $T_2(4) = 1.2 + 1.3 + 1.4 + 2.4 + 3.4 = 35$.

a) Find the general formula for $T_2(n)$ and $T_3(n)$.
b) Prove that $T_k(n)$ is expressed as a polynomial in $n$ powers of $2k$ (for every natural number $k \geq 2$).
b) State a method for finding the polynomials $T_k(n)$ ($k = 2, 3, 4, \dots$) and apply it to find the polynomials $T_4(n)$ and $T_5(n)$.

We will prove that $T_2(n), T_3(n), T_4(n)$ and $T_5(n)$ are respectively equal
$$\frac{(n+1)n(n-1)(3n+2)}{24}, \frac{(n+1)^2n^2(n-1)(n-2)}{48},$$
$$\frac{(n+1)n(n-1)(n-2)(n-3)(15n^3+15n^2-10n-8)}{5760}$$

And
$$\frac{(n+1)^2n^2(n-1)(n-2)(n-3)(3n^2-n-6)}{11520}$$

(try to directly prove that these numbers are integers for any integer $n$), and also that for any $k$ the numbers $T_k(n)$ is the value of the polynomial $T_k$ of degree $2k$ (with the leading coefficient $\frac{1\cdot 3\cdot 5\cdots(2k-1)}{1\cdot 2\cdot 3\cdot 4\cdots(2k)}$), for which the numbers - 1, 0, 1, ..., $(k-1)$ serve roots.

Note by the way that $T_1(n)$ — the sum of the products of numbers from 1 to $n$ “one at a time” — is equal to
$$\sum i = 1 + 2 + \ldots + n = \frac{n(n+1)}{2}.$$

⟦folio 29⟧

First way. You can find formulas for $T_k(n)$ using the well-known formulas for sums of powers of natural numbers:

$$\Sigma i^2 = 1^2 = 2^2 + \dots + n^2 = \frac{n(n+1)(2n+1)}{6},$$

$$\Sigma i^3 = 1^3 + 2^3 + \dots + n^3 = \frac{n^2(n+1)^2}{4} \text{ и т. д.}$$

(see, for example, articles by V. S. Abramovich in «Kvant» No. 5, 1973 and No. 6, 1974). For example, from the equality

$$(\Sigma i)^2 = \Sigma i^2 + 2 \sum ij$$

it follows that $T_2(n)$ is equal to

$$\sum_{i<j} ij = \frac{n(n+1)}{2} \left( \frac{n^2+n}{4} - \frac{2n+1}{6} \right) =$$

$$= \frac{n(n+1)(n-1)(3n+2)}{24}$$

(check that $T_2(2) = 2$, $T_2(3) = 11$, $T_2(4) = 35$, $T_2(5) = 85$).

From equality

$$(\Sigma i)^3 = \Sigma i^3 + 3 \sum ij^2 + 6 \sum ijk,$$

$$i \neq j \quad i < j < k$$

$$(\Sigma i)(\Sigma j^2) = \Sigma i^3 + \sum ij^2$$

follows $T_3(n) = \sum ijk = i < j < k$

$$= \frac{1}{6} \left( (\Sigma i)^3 - 3(\Sigma i)(\Sigma j^2) + 2\Sigma i^3 \right) = \frac{n^2(n+1)^2}{6} \times$$

$$\times \left( \frac{n(n+1)}{8} - \frac{2n+1}{4} + \frac{1}{2} \right) = \frac{n^2(n+1)^2(n-1)(n-2)}{48}.$$

Below we will show how you can find $T_k(n)$ without obtaining a formula for sums of powers.

Recurrence formula. If all the terms of the sum $T_k(n)$ are divided into two groups: one includes those products that include $n$, the other includes the rest, then the following basic formula will be obtained:

$$T_k(n) - T_k(n-1) = nT_{k-1}(n-1)$$

(1)

She, along with another equality

$$T_k(k) = 1 \cdot 2 \cdot \dots \cdot k = k!$$

allows you to consistently determine all numbers $T_k(n)$ for $n \geq k$, if $T_{k-1}(n)$ are already known. (Note that if $T_k$ and $T_{k-1}$ are polynomials, then formula (1) must be satisfied for all $n$, and not just for integer $n$ greater than $k$; obtaining this, it is easy to verify that $T_k(n)$ must equal 0 for integer $n$ from $(-1)$ to $(k-1)$, and find the values of $T_k(n)$ for integers $n$, indicated in Table 1.) From formula (1) one could deduce that $T_k(n)$ is a polynomial of degree $2k$, if on the right is a polynomial $nT_{k-1}(n-1)$ of degree $2k-1$ from $n$ (see articles V. S. Abramovich, mentioned above, or the article by V. N. Vaguten in «Kvant» No. 2, 1972); however, we will not prove this separately, but will immediately obtain formulas for the polynomials $T_k(n)$.

⟦folio 30⟧

This table shows the numbers $T_k(n)$ (the numbers $T_k(k)=k$ are enclosed in the red frame!

Second way. Let's put

$$C_x^m = \frac{x(x-1)\ldots(x-m+1)}{1\cdot 2\cdot 3\cdot \ldots m}$$

(3a)

We will consider $C_x^m$ as a polynomial of degree $m$ in $x$. It is easy to check that for all $x$

$$C_{x+1}^m = C_x^m + C_x^{-1}, (x-m)C_x^m = (m+1)C_x^{m+1}$$

(36)

Note that

$$T_1(n) = \frac{(n+1)n}{2} = C_{n+1}^2$$

(4a)

Suppose that for some $b_0^{k-1}, b_1^{k-1}$

$$T_{k-1}(n) = \Sigma b_m^{k-1} C_{n+1}^m$$

(46)

and choose $b_m^k$ so that for polynomials (46) and

$$T_k(n) = \Sigma b_m^k C_{n+1}^m$$

(5)

equality (1) was satisfied; since, according to (36),

$$T_k(n) - T_k(n-1) = \Sigma b_m^k (C_{n+1}^m - C_n^m) =$$

$$= \Sigma b_m^k C_{n+1}^m - \Sigma b_m^{k+1} C_n^m, nT_{k-1}(n-1) = n\Sigma b_m^{k-1} C_n^m =$$

$$= \Sigma b_m^{k-1}(n-m)C_n^m + \Sigma b_m^{k-1}mC_n^m =$$

$$= \Sigma b_m^{k-1}(m+1)C_{n+1}^{m+1} + \Sigma b_m^{k-1}mC_{n+1}^{m}$$

(6)

Moreover, according to (4a)

$$b_2^1 = 1; b_1^m = 0, m \neq 2.$$

(7)

Make a table of numbers $b_m^k$ and prove that

$$b_m^k = 0, m \leq k \text{ и } m \geq 2k+1; b_2^k = 1\cdot 3\cdot 5\ldots (2k-1);$$

$$b_{k+1}^k = k!.$$

Posny equality (2) for the polynomial (5) is also satisfied. It follows that $T_k(n)$ real is given by formula (5), in which the coefficients $b_m^k$ are found from equalities (6), (7).

In exactly the same way one can be convinced that

$$T_k(n) = \Sigma d_m^n C_{n+m-k}^m$$

(9)

where the coefficients $d_m^k$ are determined by the conditions

$$d_2^1 = 1; d_1^m = 0, m \neq 2;$$

$$d_{k+1}^k = -(m-k+1)d_{k+1}^{k-1} + md_{k+1}^{k-1}.$$

(10)

⟦folio 31⟧

Although formulas (10) for the coefficients $d_m^k$ are less convenient than (6) for $b_m^k$, the numbers themselves are somewhat smaller, therefore, from formula (9) it is convenient to obtain $T_4(n)$ and $T_5(n)$ in the form in which they are indicated at the beginning of the solution. For example, finding the number $d$ and using correspondences (3), we get

$$T_4(n) = \left( \left( \frac{105}{8} - 105 \right) \frac{n+3}{7} + 25 \right) \frac{n+2}{6} - 1 C_{n+1}^5 = C_{n+1}^5 (15n^3 + 15n^2 - 10n - 8)/48.$$

The formula for $T_5(n)$ is transformed in a completely similar way.

The numbers $T_k(n)$ are quite common in various combinatorics and algebra problems; perfectly disappears from them with the sign of the number $(-1)^{n+k-1} T_k(n)$ and has a special name: Stirling numbers.

The applications of these numbers and the identities connecting them are described, for example, in the book by J. Riordan “Introduction to Combinatorial Analysis” (M., IL, 1963).

◆

First of all, a clarification needs to be made in the conditions: the chords $AB$ and $CD$ must be irregular (in this case, the position of the points $K$ and $H$ is determined uniquely), and the lines $AD$ and $BC$ are also irregular (we denote their intersection point by $E$).

First we prove that the line $KH$ passes through the center of the circle. Let the point $M$ move uniformly along the straight line $KH$; Let us denote by $M(t)$ its position at time $t$ through $M'(t)$ and $M''(t)$—the projections of the point $M(t)$ onto the lines $AB$ and $CD$, respectively. We choose the origin and unit of time so that $M(0) = K$, $M(1) = H$; then $M'(0) = A$, $M'(1) = B$, $M''(0) = C$, $M''(1) = D$. It is clear that each of the points $M'(t)$ and $M''(t)$ is uniformly digitized along its own straight line.

At $t = \frac{1}{2}$, the points $M'(t)$ and $M''(t)$ fall into the midpoints of the segments $AB$ and $CD$, therefore, the point $M\left(\frac{1}{2}\right)$ falls into the center of the circle - the intersection point of the perpendiculars to the chords $AB$ and $CD$, restored at their midpoints.

Let us now prove that the line $KH$ passes through the point $E$. For any location of the points $A$, $B$, $C$ and $D$ on the circle, the triangles $AEB$ and $CED$ are similar (at two angles), and the vertex $A$ corresponds to the vertex $C$, the vertex $B$ corresponds to the vertex $D$. It is clear that under the similarity transformation that takes $\Delta AEB$ to $\Delta CED$, each point $M'(t)\in(AB)$ projects to the point $M''(t)\in(CD)$ (with the same value $t$). But the base $E'$ of the height $EE'$ of the triangle $AEB$ in this case goes into the base of the height $EE''$ of the triangle $CED$, that is, for some $t=t_0$ simultaneous $M'(t_0)=E'$ and $M''(t_0)=E''$, therefore, $M(t)=E$.

N. B. Vasiliev

◆

Let us prove that the required arrangement is possible.

If the integer $b$ is equal to the integers $a$ and $c$, then $a+c$ is an even number, so the numbers $a$ and $c$ have the same parity, that is, either they are even or they are odd. Therefore, if you arrange the numbers 1, 2, ..., $n$ in such a way that all even numbers come first, and then all odd numbers, then the number $b$ can be equal to we get me standing in different

⟦folio 32⟧

sides of the numbers $a$ and $c$ only if all these three numbers have the same parity. Thus, it remains to prove that both the even numbers from 1 to $n$ and the odd ones can be arranged in the required manner.

But it is easy to understand that the numbers 2, 4, 6, are located. . ., $2k$ or the numbers 1, 3, 5, . . ., $2k-1$ can be in the same order as the numbers 1, 2, . . ., $k$. Indeed, if $2b = \frac{2a+2c}{2}$ or $2b-1 = \frac{(2a-1)+(2c-1)}{2}$, then $b = \frac{a+c}{2}$.

Thus, the problem is reduced to ordering the required numbers 1, 2, . . ., $k$ ($k = \frac{n}{2}$ if $n$ is even, and $k = \frac{n+1}{2}$ if $n$ is odd). Since the statement being proved is true for $n = 1$, it is true for any natural $n$ and follows from the principle of mathematical induction.

The above reasoning gives a specific way to construct the required arrangement of numbers 1, 2, . . ., $n$. As an example, we will carry out such a construction for $n=16$.

1
2 1
4 2 3 1
8 4 6 2 7 3 5 1
16 8 12 4 14 6 10 2 15 7 11 3 13 5 9 1

**M272. Given two circles of radii $R$ and $r$, externally tangent. Constructing various ABCD boundaries so that each of the circles touches the common lateral sides and the same zone from the bases of the boundaries. Find the shortest possible side length AB.**

Fig. 4.

Without loss of generality, we can assume that $R>r$ (if $R=r$, the trapezoid ABCD becomes a rectangle with side AB equal to $2(R+r)=4r$). The center of a circle of radius $R$ is denoted by $O_1$, and the center of a circle of radius $r$ by $O_2$. In addition, we will assume that circle $O_1$ touches the base AD, and circle $O_2$ touches the base BC. Let $PQ$ be the common external tangent to these circles (point $P$ lies on circle $O_1$, and point $Q$ lies on circle $O_2$, see Fig. 1). It is easy to calculate that the length of the segment $PQ$ is equal to $2\sqrt{Rr}$.

Let us plot the segments $PA$ and $QB$ on the line $PQ$ outside the segment $PQ$ and find out under what correspondence between the lengths of these segments the tangent $AA'$ to the circle $O_1$ (different from $AP$) is parallel to the tangent $BB'$ to the circle $O_2$ (different from $BQ$).

These tangents are parallel provided that the sum of the angles $BAA'$ and $ABB'$ is equal to $180^\circ$, that is, $O_2BQ$ and $Q_1AP$ complement each other to a right angle. The last condition means the equality of angles $BO_2Q$ and $O_1AP$ and, therefore, proportionality

$$\frac{|BQ|}{|O_2Q|} = \frac{|O_1P|}{|AP|}.$$

By placing $x=[BQ]$, $x'=[AP]$, the condition for parallel tangents $AA'$ and $BB'$ can be written as follows: $x \cdot x' = R \cdot r$. The length of the segment $AB$ is equal in this case to $x + \frac{Rr}{x} + 2\sqrt{Rr}$.

If the parallelism condition is satisfied, then, denoting by $D$ and $C$ the points of intersection of the second external tangent $O_1$ and $O_2$ with parallel lines $AA'$ and $BB'$, we obtain a trapezoid ABCD, satisfying

⟦folio 33⟧

Satisfying the conditions of the task. However, this statement, which seems disordered when looking at figure 4, needs clarification. Look at figure 5. If the number $x$ is too large, you won’t be able to get a trapezoid. It is clear that the number $x$ must be less than the length of the segment $QB$ by figure 6. Prove that $|QB| = \frac{2r}{R-r} \sqrt{Rr}$.

Thus, it remains to solve the following problem: find the smallest value of the function $f(x) = x + \frac{Rr}{x} + 2\sqrt{Rr}$ on the interval $0 < x < \frac{2r}{R-r} \sqrt{Rr}$. Instead of this function, we can take the function $g(x) = x + \frac{Rr}{x}$, whose graph (at $x > 0$) is shown at figure 7. It kills at $0 < x \leq \sqrt{Rr}$ and returns at $x \geq \sqrt{Rr}$ (prove this). Thus, if $\frac{2r}{R-r} \cdot \sqrt{Rr} > \sqrt{Rr}$, then the smallest value of the side length $AB$ is $f(\sqrt{Rr}) = 4\sqrt{Rr}$. If $\frac{2r}{R-r} \cdot \sqrt{Rr} \leq \sqrt{Rr}$, then the function $f$ does not have the smallest value on the interval $]0, \frac{2r}{R-r} \sqrt{Rr}$.

The inequality $\frac{2r}{R-r} \sqrt{Rr} \leq \sqrt{Rr}$ is equivalent to translating $R \geq 3r$. Thus, if $r < R < 3r$, the exclusive minimum is $4\sqrt{Rr}$, but if $R \geq 3r$, the minimum value $|AB|$ does not exist: the length of the side $|AB|$ can take any value greater than $f\left(\frac{2r}{R-r} \times \sqrt{Rr}\right) = \frac{(R+r)^2}{2r(R-r)} \sqrt{Rr}$, but this value itself does not reach.

Yu. I. Ionin.

For simplicity, we will assume that the speed of the satellite changes over a very short period of time (small compared to the period of revolution of the satellite in a circular orbit). The minimum distance from the Earth's surface to the elliptical orbit is equal to the radius of the original circular orbit, that is, both satellite orbits have a common point (point $I$ on figure 8), at which the satellite’s speed changed. Let us find the speeds $v_0$ and $v_1$ of the satellite at this point in a circular and elliptical orbit, and then the change in speed $\Delta v = v_1 - v_0$.

First, we determine the speed $v_0$ of the satellite when moving in a circular orbit. Since the centripetal acceleration $a = \frac{v_0^2}{R+h}$ ($R$ is the radius of the Earth) is imparted to the satellite by the force of gravity $F_T = \gamma \frac{mM}{(R+h)^2}(M$ is the mass of the Earth, $m$ is the mass of the satellite), then, according to Newton’s II law, $\frac{mv_0^2}{R+h} = \gamma \frac{mM}{(R+h)^2}$. From this equality we can directly find,

⟦folio 34⟧

$$v_0 = \sqrt{\gamma \frac{M}{R+h}}.$$

In order to determine the speed $v_1$ of a satellite when it moves in an elliptical orbit at an altitude $h$ above the Earth, we use the law of conservation of energy and Kepler's III law*). From the analogy between gravitational and electrostatic fields, we can conclude that at the moment when the satellite is at a distance of $h$ from the Earth, it has a potential energy of $\Pi_1 = -\gamma \frac{mM}{R+h}$. In addition, the satellite has a kinetic energy of $K_1 = \frac{mv_1^2}{2}$. At an altitude of $H$ from the Earth, the satellite has a potential energy of $\Pi_2 = -\gamma \frac{mM}{R+H}$ and a kinetic energy of $K_2 = \frac{mv_2^2}{2}$, where $v_2$ is the speed of the satellite at an altitude of $H$. According to the law of conservation of energy,

$$\frac{mv_1^2}{2} - \gamma \frac{mM}{R+h} = \frac{mv_2^2}{2} - \gamma \frac{mM}{R+H}.$$

According to Kepler's second law, the areas swept by the radius vector of the satellite in equal periods of time are equal. At figure 8 these are the areas of the shaded figures. If the time interval $\Delta t$ is small, the satellite’s speeds greater than points 1 and 2 can be considered constant. Then, instead of sectors, we can consider the corresponding equilateral triangles. Let us write down the equality of their areas:

$$\frac{1}{2} v_1 \Delta t (R+h) = \frac{1}{2} v_2 \Delta t (R+H).$$

From the last two equalities we find

$$v_1 = \sqrt{\frac{2\gamma M}{2R+H+h} \frac{R+H}{R+h}}.$$

Then the change in satellite speed

$$\Delta v = v_1 - v_0 = \sqrt{\frac{\gamma M}{R+h}} \left( \sqrt{\frac{2(R+H)}{2R+H+h}} - 1 \right) \approx \frac{2\kappa M}{c}.$$

Now let us determine the period $T$ of the satellite’s revolution in an elliptical orbit. According to Kepler's III law, the ratio of the squares of the satellite's orbital periods is equal to the ratio of the cubes of the semimajor axes of its orbits. That's why

$$\frac{T^2}{T_0^2} = \frac{(2R+h+H)^3}{8(R+h)^3},$$

where $T_0 = \frac{2\pi (R+h)}{v_0}$ is the period of revolution of the satellite in a circular orbit of radius $R+h$. Hence,

$$T = \pi (2R+H+h) \sqrt{\frac{2R+H+h}{2\gamma M}} \approx 12\mu.$$

*) See, for example, the article by E. P. Kuznetsov “Space problems in entrance exams”, «Kvant», 1974, No. 11.

⟦folio 35⟧

F279. The cylinder, made of non-melt-conductive material, is divided by a non-melt-conductive partition into two parts, the volume of which is $V_1$ and $V_2$. The first part contains gas at a temperature of $T_1$ under a pressure of $p_1$. The second part contains the same gas, but at a temperature of $T_2$ and under a pressure of $p_2$. What gas temperature will be established in the cylinder if the partition is removed?

Since the walls of the cylinder are made of non-solid-conducting material, then, regardless of what process occurs with the gas in the cylinder when it moves, it follows from the law of conservation of energy

$$cm_1(T - T_1) = cm_2(T_2 - T).$$

Here $c$ is the specific heat of the gas, $m_1$ and $m_2$ are the masses of the gas corresponding in the first and second parts of the cylinder, and $T$ is the temperature that is established in the cylinder after equilibrium occurs. From this formula (heat balance equation), after simple transformations, we obtain

$$T = \frac{(m_1/m_2)T_1 + T_2}{1 + \frac{m_1}{m_2}}.$$

The ratio $\frac{m_1}{m_2}$ is not difficult to find by completing the equation of gas state. For the gas in the part of the cylinder before the partition was removed, we can write

$$p_1V_1 = \frac{m_1}{\mu}RT_1 \quad p_2V_2 = \frac{m_2}{\mu}RT_2.$$

Dividing the first equality by the second, we get

$$\frac{m_1}{m_2} = \frac{p_1V_1T_2}{p_2V_2T_1}.$$

Then finally

$$T = \frac{T_1T_2(p_1V_1 + p_2V_2)}{p_1V_1T_2 + p_2V_2T_1}.$$

F280. The light source is at a distance of 3a from the line with focal length $a$. How many times does the average illumination of a spot on the screen, which is located at a distance of 1.5 a from the line, change if a flat glass plate of 0.5 a is placed between the line and the source? The refractive index of glass is $n$.

⟦folio 36⟧

Let's find separately the illumination in the first and second cases, and then their ratio.

In the first case, the source is located at a distance $d_1 = 3a$ from the line. From the lens formula $\frac{1}{d} + \frac{1}{f} = \frac{1}{F}$ we find that the source image is located at a distance $f_1 = \frac{Fd_1}{d_1 - F} = \frac{3}{2}a$ from the line, that is, exactly on the screen.

Let the source area be small and equal to $\Delta S$ (the actual dimensions of the source should be small compared to the distance from it to the line, since using the lens formula, we consider only rays close to the main optical axis). Then we can assume that the luminous flux, depicted with units of source area in a unit solid angle - let's denote it $I$ - is a constant value. Thus, the luminous flux $\Phi_1 = I\Delta S\Omega_1$ falls on the line from the source, where $\Omega_1$ is the solid angle at which the line of source points is visible. The angle $\Omega_1$ is measured by the ratio $\frac{S}{d_1^2}$ ($S$ is the area of ​​the line, $d_1$ is the distance from the line to the source). This light flux after the lens hits the screen. The image area $\Delta S_1$ on the screen is related to the source area as $\frac{f_1^2}{d_1^2}$, that is

$$\frac{\Delta s_1}{\Delta S} = \frac{f_1^2}{d_1^2} = \frac{1}{4}.$$

Then the screen illumination in the first case is equal to

$$E_1 = \frac{\Phi_1}{\Delta S_1} = I \frac{S}{d_1^2} \frac{\Delta S}{\Delta S_1} = \frac{4}{9} \frac{IS}{a^2}.$$

After a plane-par plate was placed between the source and the lens, the image of the source given by the plate became the source for the lens. Let's find the position of this image (distance $x$ by figure 9).

To do this, we will construct the path of two rays emerging from the point $A$ of the source, for example. Let one ray be perpendicular to the plate, and the second ray form a small angle $\alpha$ with the first. From triangle $A'CK$ the segment $CK$ is equal to

$$CK = A'K \mathrm{tg} \alpha = \left(l - x + \frac{a}{2}\right) \mathrm{tg} \alpha.$$

On the other side,

$$CK = CD + KD = \frac{a}{2} \mathrm{tg} \beta + l \mathrm{tg} \alpha.$$

Hence,

$$\left(l - x + \frac{a}{2}\right) \mathrm{tg} \alpha = \frac{a}{2} \mathrm{tg} \beta + l \mathrm{tg} \alpha.$$

Hence $x = \frac{a}{2} \left(1 - \frac{\mathrm{tg} \beta}{\mathrm{tg} \alpha}\right)$. Since angles $\alpha$ and $\beta$ are small, then $\frac{\mathrm{tg} \beta}{\mathrm{tg} \alpha} = \frac{\sin \beta}{\sin \alpha} = \frac{1}{n}$ and $x = \frac{a}{2} \left(1 - \frac{1}{n}\right)$. Thus, the image of the source given by the plate is at a distance of $d_2 = 3a - x = \frac{a}{2} \left(5 + \frac{1}{n}\right)$.

⟦folio 37⟧

In this case, the dimensions of the image are the same as the source (see Fig. 9). The luminous flux $\Phi_2$ incident on the lens from this new source is equal to $\Phi_2 = I \Delta S \Omega_2 = I \Delta S \frac{S}{d_2^2}$.

Now, from the lens formula, find the position of the image of this source:

$$f_2 = \frac{Fd_2}{d_2 - F} = a \frac{5n + 1}{3n + 1}.$$

It is clear that a clear image is not on the screen, but a blurred spot is visible on the screen. However, since for glass $n$ lies in the range from 1.5 to 2, then $f_2$ takes values ​​from 1.54 a to 1.57 a. This is the image located from the screen at a distance of approximately 0.05 a. This distance is small compared to the distance of 1.5 a from the screen to the lens. In addition, the size of the object and the diameter of the lens are also small (note again that we are considering only narrow paraxial beams). Therefore, we can assume that the size of a clear image does not differ from the size of the spot on the screen (Fig. 10) and $\frac{\Delta s_2}{\Delta S} = \frac{f_2^2}{d_2^2} = \frac{4n^2}{(3n + 1)^2}$.

Then the illumination $E_2$ screen in this case is equal to

$$E_2 = \frac{\Phi_2}{\Delta s_2} = \frac{I S \Delta S}{d_2^2 \Delta s_2} = \left( \frac{3n + 1}{5n + 1} \right)^2 \frac{I S}{a^2},$$

and illumination ratio

$$\frac{E_2}{E_1} = \frac{9}{4} \left( \frac{3n + 1}{5n + 1} \right)^2.$$

Initially, the potential difference between the plates of the capacitor is $E_2$, and the charge of the capacitor is $q_1 = CE_2$. After closing the key, the current will flow through the circuit, and the potential difference between the capacitor plates (the potential difference between points $B$ and $A$) will be equal to $U_2 = E_2 - Ir_2$, where $I$ is the current flowing through the circuit. Let's find this current.

From the current-voltage characteristic of the diode it follows that when current flows through the diode, the voltage across it is always equal to $U_2 = 1\epsilon$. Let's write Ohm's law for the complete circuit:

$$E_2 - E_1 = U_{\pi} + Ir_1 + Ir_2.$$

From here

$$I = \frac{E_2 - E_1 - U_{\pi}}{r_1 + r_2}.$$

Then, after closing the key, the potential difference between the capacitor plates will be equal to

$$U_2 = E_2 - \frac{E_2 - E_1 - U_{\pi}}{r_1 + r_2} r_2,$$

*) In «Kvant» No. 6 for 1974, in conditions problem F281 there was a typo.

⟦folio 38⟧

and its charge

$$q_2 = CU_2 = CE_2 - Cr_2 \frac{E_2 - E_1 - U_\pi}{r_1 + r_2}.$$

Consequently, the charge of the capacitor will change by the amounts

$$\Delta q = q_2 - q_1 = -Cr_2 \frac{E_2 - E_1 - U_\pi}{r_1 + r_2} = -\frac{2}{3} \cdot 10^{-6} \text{ мкф.}$$

F282. The name is the frequency of the “symmetrical” oscillations of the system shown in figure 12, a. The masses of all balls are m, the elasticity coefficients of the springs are k.

First of all, let's find the force acting on each ball when it is mixed from the equilibrium position (Fig. 12, 6). Let us denote the initial distance of the ball from the center of the system (point O) as $x_0$, the new distance as $x$, the displacement of the ball from the equilibrium position as $\Delta x$, the initial length of the spring as $l_0$, its length in the stretched state as $l$, and the change in the length of the spring as $\Delta l$.

Fig. 12.

As can be seen from figure 12, 6,
$$l_0 = 2x_0 \cos 30^\circ \text{ и } l = 2x \cos 30^\circ.$$
Then each of the springs, when mixing the balls, turns out to be stretched by amounts

$$\Delta l = l - l_0 = 2(x - x_0) \cos 30^\circ = \sqrt{3} \Delta x.$$

Consequently, each ball will be acted on by two forces equal in abscylotic magnitude from the side of the springs: $F = k\Delta l = \sqrt{3}k\Delta x$.

The equal force of these forces is directed to the equilibrium position of the ball and is equal in abscillot value (Fig. 12, 6) $F' = 2F \cos 30^\circ = 3k\Delta x$, that is, it is proportional to the displacement of the ball from the equilibrium position. This means that the system is equivalent to a system of three common spring magnets connected at point O and each having a stiffness of $k' = 3k$. Therefore, the oscillation frequency of the system will be equal to

$$\omega = \sqrt{\frac{k'}{m}} = \sqrt{\frac{3k}{m}}.$$

F283. Charged balls with the same mass, located at a distance l from each other, negative

The balls move away from each other under the action of the electric repulsion force F, equal to (in the SGSE system of units)

$$F = \frac{q^2}{r^2},$$ where $q$ is the charge of each ball, $r$ is the distance

⟦folio 39⟧

(without initial speed). After t seconds, the distance between them is notified. After what time will the distance between the balls be known if they are released from a distance of 3l?

$$\frac{\Delta x_2}{\Delta x_1} = 3$$

Let $k$ change by the values ​​$\Delta k = \frac{\Delta x}{x_0}$. then the displacement of each ball in the first case ($\text{когда } 2x_0 = l$) is $\Delta x_1 = \Delta k \frac{l}{2}$, and in the second case ($\text{когда } 2x_0 = 3l$) is $\Delta x_2 = \Delta k \frac{3}{2} l$. The ratio of the balls' movements is equal to

$$\frac{\Delta x_2}{\Delta x_1} = 3.$$

Now let's compare the average speeds of the balls. To do this, we will use the law of conservation of energy. At the initial moment, the balls have only the potential energy of electrical interaction $\Pi_0 = \frac{q^2}{2x_0}$ (in the SGSE system). At the moment when the distance between the balls is $2x$, they have potential energy $\Pi = \frac{q^2}{2x}$ and kinetic energy $K = 2 \frac{mv^2}{2}$ (m is the mass of the ball). According to the law of conservation of energy $\frac{q^2}{2x_0} = \frac{q^2}{2x} + mv^2$. From here

$$v = \sqrt{\frac{q^2}{2m} \frac{x-x_0}{xx_0}} = \sqrt{\frac{q^2}{2x_0 m} \frac{k-1}{k}}.$$

We see that for the same relative displacement $k$ the speed of the ball in the first case is $\frac{\sqrt{q^2/ml}}{\sqrt{q^2/3ml}} = \sqrt{3}$ times greater than the speed of the ball in the second case.

It is clear that when $k$ changes by values ​​$\Delta k$, the average speeds of the balls will differ by $\sqrt{3}$ times: $\frac{v_{\text{cp.1}}}{v_{\text{cp.2}}} = \sqrt{3}$.

The time taken to move to $\Delta x_1$ in the first case and to $\Delta x_2$ in the second case are equal, respectively

$$\Delta t_1 = \frac{\Delta x_1}{v_{\text{cp.1}}} \text{ и } \Delta t_2 = \frac{\Delta x_2}{v_{\text{cp.2}}}.$$

From here

$$\frac{\Delta t_2}{\Delta t_1} = \frac{\Delta x_2}{\Delta x_1} \frac{v_{\text{cp.1}}}{v_{\text{cp.2}}} = 3 \sqrt{3},$$

that is, for any change in the value $k$, the time of movement in the first case is $3 \sqrt{3}$ times greater than the time of movement in the second case.

Therefore, when the distance between the balls

⟦folio 40⟧

$$\frac{t_2}{t_1} = 3\sqrt{3}$$

First, consider the case when the plate falls vertically downward with a constant speed $v$. The electrons falling together with the plate are acted upon by the magnetic field by the Lorentz force (Fig. 13) $F_\pi = evB$ (e is the charge of the electron). As a result, electrons will mix towards the right side of the plate. The redistribution of electrons inside the plate leads to the appearance of an electric field directed from left to right (see Fig. 13). The mixing of electrons will occur until the left Lorentz force is balanced with the force $F_3$ acting from the electric field: $F_\pi = F_3$, or $evB = eE$. Hence the directionality of the electric field $E = vB$.

Since the thickness of the plate is much smaller than its radius, the electric field inside the plate can be considered uniform (edge ​​effects can be neglected). This means that the plate can be considered a flat capacitor, between the plates of which the potential difference is $u = Ed = Bvd$, the charge of which is equal to

$$q = Cu = \frac{\varepsilon_0 S}{d} Bvd = \varepsilon_0 SBv$$

($S = \pi R^2$ is the area of ​​the plate).

This charge depends on the speed of the plate. When the plate moves with some acceleration, along with the speed of the plate over time, the charges on the sides of the plate will also change. Consequently, when the speed of the plate changes, an electric current will arise in it

$$I = \frac{\Delta q}{\Delta t} = \varepsilon_0 SB \frac{\Delta v}{\Delta t} = \varepsilon_0 SB a$$

where $a$ is the acceleration of the plate. But, as we know, a force $F = BId$ acts on a conductor with current in a magnetic field and is directed vertically upward. So, in addition to the gravitational force, a force $F$ will also act on the plate when it falls from the magnetic field. Let us write down the equation of motion of the plate:

$$ma = mg - BId$$ or $ma = mg - B^2 d\varepsilon_0 a\pi R^2$.

From here

$$a = g \frac{1}{1 + \frac{B^2 d\varepsilon_0 \pi R^2}{m}}.$$

I. Sh. Slobodetsky
