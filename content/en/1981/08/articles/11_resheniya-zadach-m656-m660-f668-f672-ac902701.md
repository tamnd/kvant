---
id: 1981-8-resheniya-zadach-m656-m660-f668-f672-ac902701
issue: kvant_1981_8
year: 1981
number: "8"
title: Solutions to problems M656—M660; F668—F672
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 42
page_last: 50
page_labels: 40, 41, 42, 44, 45, 46, 48
tag: 1Z4J
lang: en
source: kvant_digital
extraction: vision
content_sha256: ea992740b08172d2bf3fc442e00685d3cbc06bf53bb2908e6e9f3d4565a12c49
prompt_sha256: draft-1
translated_from: content/ru/1981/08/articles/11_resheniya-zadach-m656-m660-f668-f672-ac902701.md
source_content_sha256: e088df7e47142c23e7bf523cbbbc9a5f29dcbcfb796d7f4b68c8fa515cf573a5
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 40⟧

F712. A small ball moves at a constant speed $\vec{V}_0$ along a smooth horizontal surface and falls at point $A$ into a cylindrical vertical well of depth $H$ and radius $R$. The velocity vector of the ball makes an angle $\alpha$ with the diameter of the well drawn to point $A$ (Fig. 4). At what ratios between $\vec{V}_0$, $H$, $R$ and $\alpha$ can the ball “get out” of the well after elastic collisions with the walls and the house? (8)

S. Krotov

Problem solutions

M656—M660; F668—F672

Let's place the origins of all vectors at one point and construct a sphere of radius 1 with the center at this point. Let's take the points of intersection of our vectors (or their extensions) with the constant sphere and surround which of them with a cap with a “diameter” $45^\circ$ (Fig. 1) or, which is essentially the same thing, the vectors themselves with cones with a pattern $45^\circ$ (and form 1). The statement of the problem will be proven if we show that any two of these “neighborhoods”: the cap or the cone, intersect. And to do this, compare the total surface area of ​​the cap (or the total volume of the cones) with the surface area of ​​the sphere (respectively, with the volume of the ball).

The surface area of ​​the cap (see Fig. 1; $H = R(1-\cos \varphi)$ is the height of the cap) is equal to $2\pi RH = 2\pi \left(1-\cos \frac{\pi}{8}\right) = 2\pi \left(1-\frac{\sqrt{2}+\sqrt{2}}{2}\right)$ (we used the formula for the cosine of a polyvine angle). Our goal is to prove that $30 \cdot 2\pi \left(1-\frac{\sqrt{2}+\sqrt{2}}{2}\right) > 4\pi$, that is, that $\frac{\sqrt{2}+\sqrt{2}}{2} < \frac{4}{15}$. Having made several simple transformations (two of which are squaring), we arrive at the correct equivalent inequality $\frac{1}{2} < \left(\frac{167}{225}\right)^2$. It follows from this that among the caps he will find two intersecting ones; the angle between their corresponding vectors will be less than $45^\circ$.

If we compare the volumes (Fig. 2), we need to prove that the volume of each cone is greater than $\frac{4}{90}$ π. We invite you to check this for yourself.

A. Tolpieo

M657. In the table $n \times n$, filled with numbers, all lines are different. Prove that you can remove a non-voctor column from a table so that all rows in the remaining table are also distinct.

Let's assume the opposite: no matter which table we cross out, the remaining table will find at least one pair of identical rows. Let us consider $n$ “shortened” tables obtained from a given, corresponding table by deleting the first, second, ..., $n$th table. For each of these tables, mark one pair of identical rows (length $n-1$). We will now assume that the rows of the original table are points on the plane, and the points corresponding to the marked parameter in the shortened tables are connected in pairs. We got a picture of “$n$ points - $n$ segments”. It is not difficult to prove that in such a picture there will be a cycle - a closed broken line with vertices from our points. Let these vertices correspond to the lines $A_1$, $A_2$, ..., $A_m$, and let the segment $A_iA_{i+1}$ result from deleting

⟦folio 41⟧

column $B_i$ ($i=1, 2, \dots, m-1$), and segment $A_m A_1$ - column $B_m$.
Then in the original table, rows $A_1$ and $A_2$ differ only in column $B_1$, rows $A_2$ and $A_3$ - only in column $B_2$, ...
rows $A_{m-1}$ and $A_m$ are only in column $B_{m-1}$, so in column $B_m$ the same number is written in all these rows.
But this contradicts the fact that the points corresponding to rows $A_1$ and $A_m$ are connected (since, by convention, all rows in the original table are different, rows $A_1$ and $A_m$ must be different in column $B_m$).

A. Anjan

**M658. A square has a finite number of segments (Fig. 1) parallel to its side on side 1. Line segments can intersect others. The sum of the lengths of the drawn segments is 18. Prove that among the parts into which the square divides these points of the segment, there is one whose area is not less than 0.01.**

◆ The sum of the lengths of the boundaries of all parts into which the square is divided by segments is equal to $2 \cdot 18 + 4 = 40$ (the lengths of the drawn segments are included in this sum twice, the lengths of the sides of the square - once). Let for the $i$th part the sum of the lengths of the horizontal boundaries be equal to $2x_i$, the vertical ones - $2y_i$, and the area of ​​the $i$th part be equal to $c_i^2 (c_i > 0)$; then $x_i y_i \geqslant c_i^2$ (Fig. 2), so $x_i + y_i \geqslant 2\sqrt{x_i y_i} \geqslant 2c_i$. So,

$$40 = \Sigma (2x_i + 2y_i) \geqslant 4\Sigma c_i,$$

whence $\Sigma c_i \leqslant 10$ (here the sum $\Sigma$ is taken over all parts of the partition).

Fig. 1.

Fig. 2.

If $c_i^2 < 0,01$ (that is, $c_i < 0,1$) for all $i$, then $1 = \Sigma c_i^2 < \Sigma 0,1c_i = 0,1\Sigma c_i$, hence $\Sigma c_i > 10$. Contradiction. Obviously, estimate 18 is accurate: with an eighteenth-eighteenth segment of length 1, our square can be divided into 100 identical squares of area 0.01 each.

A. Berzins

**M659. Prove the following properties of the Fibonacci sequence $f_1 = 1, f_2 = 2, \dots, f_{k+1} = f_k + f_{k-1}$.**

a) Each natural number $n \geqslant 3$ is represented as a sum of different Fibonacci numbers.

b)* Let us denote the number of such representations of the number $n$ in the form of a sum of an even number of terms by $K_n$, in the form of a sum of an odd number of terms by $H_n$; then $|K_n - H_n| \leqslant 1$ for all $n$.

c)* If you overcome several persistent two-killers in a row from the sequence

$$1 - x, 1 - x^2, 1 - x^3,$$

$$1 - x^5, \dots, 1 - x^{f_k}, \dots$$

For brevity, we will say together “representation of the number $n$ as a sum of different Fibonacci numbers” as “representation of the number $n$”; we will call representations satisfying conditions d) correct.

The statement of task a) is contained in the statement of task d).

Solution to problem d). In the margin is a table of correct representations of natural numbers. This table is structured like this. Its lines are divided into groups containing the corresponding values ​​of $1, 2, \dots, f_k$, ... equalities. The first group consists of the equalities $1 = 1$, the second - from the equalities $2 = 2$ and $3 = 1 + 2$, and the group with the number $k \geqslant 3$ is obtained from the $(k-2)$th and $(k-1)$th groups by increasing the left side of the equalities included in them by $f_k$ and assigning them to the right side of the term $f_k$. The table shows that every natural number $n \geqslant 3$ has a correct representation. To prove the uniqueness of the correct representation, assume that $n$ is the smallest number for which it is unique; let

$$n = f_{i_1} + \dots + f_{i_m} (i_1 < \dots < i_m)$$

- a view that does not contain in our table. But then

⟦folio 42⟧

(indicators are Fibonacci numbers), then in the resulting polynomial all coefficients will be equal to 0, -1 or +1. The proof of statements b) and c) known to us is based on the following property:
e) For any $n \geq 3$ there is a unique representation of $n$ as a sum of different Fibonacci numbers, which together with each term $f_k(k \geq 3)$ contains at least one of the two previous Fibonacci numbers $f_{k-1}$ or $f_{k-2}$.

$$1 = 1$$
$$2 = 2$$
$$3 = 1 + 2$$
$$4 = 1 + 3$$
$$5 = 2 + 3$$
$$6 = 1 + 2 + 3$$
$$7 = 2 + 5$$
$$8 = 1 + 2 + 5$$
$$9 = 1 + 3 + 5$$
$$10 = 2 + 3 + 5$$
$$11 = 1 + 2 + 3 + 5$$
$$12 = 1 + 3 + 8$$
$$13 = 2 + 3 + 8$$

$$1 = S(1)$$
$$2 = T(1)$$
$$3 = S(2)$$
$$4 = S(1,1)$$
$$5 = T(2)$$
$$6 = S(3)$$
$$7 = T(1,1)$$
$$8 = S(2,1)$$
$$9 = S(1,2)$$
$$10 = T(3)$$
$$11 = S(4)$$
$$12 = S(1,1,1)$$
$$13 = T(2,1)$$

$$37 = S(2,2,1)$$

$$K_1 - H_1 = M(1) = -1$$
$$K_2 - H_2 = N(1) = -1$$
$$K_3 - H_3 = M(2) = 0$$
$$K_1 - H_4 = M(1,1) = 1$$
$$K_5 - H_5 = N(2) = 0$$
$$K_6 - H_6 = M(3) = 0$$
$$K_7 - H_7 = N(1,1) = 1$$
$$K_8 - H_8 = M(2,1) = -1$$
$$K_9 - H_9 = M(1,2) = 0$$
$$K_{10} - H_{10} = N(3) = 0$$
$$K_{11} - H_{11} = M(4) = 1$$
$$K_{12} - H_{12} = M(1,1,1) = 0$$
$$K_{13} - H_{13} = N(2,1) = -1$$

$$K_{37} - H_{37} = M(2,2,1) = 0$$

correct presentation
$$n - f_{i_m} = f_{i_1} + \dots + f_{i_{m-1}}$$
the same may be contained in the table, otherwise we would have to include views (1) in the table when processing the $i_m$th group. Contradiction.

Solution to problem 6). We will depict representations of natural numbers as sequences of black and white circles: a black circle at the $k$th place means that $f_k$ is included in the representation, a white one means that it is not included (we reverse the sequence at the last black circle). On figure 1, ​​six different representations of the number 37 are written in this way (these are all its possible representations). Correct ideas take on the form shown in figure 2, a or 2, 6; here $j_1, \dots, j_q$ are natural numbers. In the first case we put $n = S(j_1, \dots, j_q)$, $K_n - H_n = M(j_1, \dots, j_q)$; in the second case we put $n = T(j_1, \dots, j_q)$, $K_n - H_n = N(j_1, \dots, j_q)$. (So, 37 = S(2, 2, 1), $M(2, 2, 1) = K_{37} - H_{37} = 3 - 3 = 0$; other examples are given nearby in the margin.)

If $n = f_{i_1} + \dots + f_{i_m}$ is a representation of the number $n$, including its $f_r$ and $f_{r+1}$, but not including its $f_{r+2}$, then by replacing the terms $f_r$ and $f_{r+1}$ with the terms $f_{r+2}$, we get another representation of the number $n$. We will call this transformation (... ● ● ○ ... → ... ○ ○ ● ...) elementary simplification. Obviously, any representation of a number is obtained from correct elementary simplifications. Let it be $q = 1$ first. figure 3 shows the full set of representations of $n = S(j)$ (which is equal to $f_{j+2} - 2$). We see that $K_{S(j)}$ is the number of four from $[(j+1)/2]$ to $j$, and $H_{S(j)}$ is the number of odd x numbers on this segment. Hence,

$$K_n - H_n = M(j) = \begin{cases} 1, \text{ если } j \equiv 0 \text{ mod } 4^* \\ -1, \text{ если } j \equiv 1 \text{ mod } 4, \\ 0, \text{ если } j \equiv 2 \text{ mod } 4. \end{cases}$$

Let us now turn to the number $M(j_1, \dots, j_q)$. Let us divide the representations of the number $S(j_1, \dots, j_q)$ into two groups: representations of the form $f_{1+1} + \dots + f_{j+1} + \dots$ and the rest. The number of the representation of the first group coincides with the number of all representations of the number $S(j_2, \dots, j_q)$, only the latter has $j_1$ terms less, therefore it includes the first group in $M(j_1, \dots, j_q)$ equal to $(-1)^j M(j_2, \dots, j_q)$ (several numbers of examples or those constructing our observation are given in the margins).

Further, in order to obtain from the correct representation of the second group using elements of simplifications, it is necessary to make an elementary simplification ($f_{j_1-1}, f_{j_1}) \rightarrow f_{j_1+1}$, and one can find from it. As a result, between the first $j_1-2$ terms and the rest there may be a gap of length 2 (Fig. 4), excluding the possibility of interaction. Therefore, in the future, elementary simplifications of the first $j_1-2$ terms and the rest are independent, so that includes the second group in $M(j_1, \dots, j_q)$ is equal to $M(j_1-2) M(j_2+1, j_3, \dots, j_q)$ So,

$$M(j_1, \dots, j_q) = (-1)^j M(j_2, \dots, j_q) + M(j_1-2) M(j_2+1, j_3, \dots, j_q)$$

(see also examples in the margin)**). Let us now prove from $q$ that $M(j_1, \dots, j_q) = -1, 0$ or 1.

At $q = 1$ we already know this. Assume that $M(k_1, \dots, k_r) = -1, 0$ or 1 for $r = q$ and any $k_1, \dots, k_r$. If $j_1 \equiv 0$ or 1 mod 4, then $M(j_1-2) = 0$ (see formula (2)) and $M(j_1, \dots, j_q) = (-1)^j M(j_2, \dots, j_q) = -1, 0$ or 1.

If $j_1 \equiv 2$ or 3 mod 4, then $M(j_1-2) = (-1)^j M(j_2, \dots, j_q)$ (see formula (2)) for $q = 2$ and

*) Notation $a \equiv b$ mod $c$ (read: $a$ comparable to $b$ mod $c$), where $0 \leq b < c$, means that when $a$ is divided by $c$, the remainder $b$ is obtained.

**) Formula (3) makes sense only for $j_1 \geq 3$, but it can also be used for $j_1 = 1, 2$ by setting $M(-1) = 0, M(0) = 1$ (which does not contradict formula (2)); the proof is left to the reader.

⟦folio 44⟧

M660. Blue and red dots are placed on the circle (Fig. 1, a). It is allowed to add a new red dot and simultaneously change the color of each of the two adjacent dots (Fig. 1, ​​b), or remove the red dot and change the color of each of the neighboring dots (Fig. 1, c). Let there initially be only two red dots (there are no cuts between two dots). Is it possible to obtain on a circle by several such operations
a) two dots - blue and red;
b) 8 red dots;
c) one red and 6 blue dots;
e) two blue dots?

Fig. 1.
Fig. 2.
Fig. 3.
Fig. 4.

F668. Through a stationary block of peroxidation there is a weightless thread. A mass $m_1$ is attached to one end of the thread. To the other end on a spring

$M(n) = G(n, k)$ for $f_{k+1} > n$, and to solve problem c) - that the coefficient for $x^n$ in the product $(1-x^{j+1})\ldots(1-x^{i+k})$ is equal to 0 if $n$ is not represented as a sum of different terms chosen from the set $f_{i+1},\ldots,f_{i+k}$, and equal to $G(f_{j_1}+f_{j_2}+...+f_{j_s}, k)$ if $n=f_{i+j_1}+\ldots+f_{i+j_s}, 1 \leq j_1 <...<j_s \leq k$.

The answers to questions 6) and c) are positive.

For 6) this follows from the fact that, allowed by additions, three consecutive red dots (Fig. 2) can always be placed at any place on the circle. Then eight red dots are obtained from two red ones by inserting three red dots twice.

On the other hand, from three consecutive red dots you can always get two blue ones (by throwing out the middle dot). Therefore, by first adding a red one to the two given red dots, then adding two times three red dots, and then replacing these “red triplets” with “blue pairs”, we get a red and six blue dots.

A negative answer to question a) follows from the fact that with allowed operations the parity of the number of blue dots does not change, but it is different in the initial and required final positions.

A negative answer to question d) follows from another invariant property of our operations, the discovery of which requires greater observation and a large number of experiments. Moreover, this property is invariant only over the set of positions with an even number of blue dots.

For such arrangements, we define an alternative sum $|m_1-m_2+m_3-m_4+\ldots+m_{2k-1}-m_{2k}|$ by the length of the red dots: $m_1$ - the number of red dots enclosed between the first and second blue dots (the direction of the traversal and the first blue dot are chosen arbitrarily), $m_2$ - the number of red dots between the second and third blue dots, $m_3$ - between the third and fourth,..., $m_{2k}$ - between the last 2$k$th, and first blue dots (at figure 3 $k=2$, $m_1=2$, $m_2=3$, $m_3=1$, $m_4=5$); some $m_i$ may equal zero. If there are no blue dots in the arrangement at all, let’s set this sum equal to the number of its red dots.

It turns out that divisibility by 3 of a sum defined in this way is an invariant property. (Experiment with the arrangement shown in figure 3, and then prove the stated statement for the operation of cutting a red dot by considering the case when its “neighbors” are blue dots, red dots, dots of different colors.) But for two red dots our sum is equal to 2 (not divisible by 3), and for two blue dots it is equal to 0 (divisible by 3). This means that the second arrangement cannot be obtained from the first.

In conclusion, we note that any (finite) arrangement of red and blue points can be obtained from some two-point one or, what is the same, from any arrangement one can obtain a two-point one. This remark is almost obvious: it is enough to remove the red dots until two dots remain on the circle. If on the circle at some step there are only blue dots remaining (more than two), then by adding a red dot and then removing the one adjacent to it, we get an arrangement with the same total number of dots, containing red dots (Fig. 4).

K. Kazarnovsky

If the weights were connected by a thread without a spring, then they would begin to move with an acceleration equal in absolute value to

$$a = g \frac{m_2-m_1}{m_2+m_1}$$

⟦folio 45⟧

a load of mass $m_2$ is suspended with stiffness k. The length of the spring in the unexpanded state is $l_0$. Find the amplitude of oscillations that the load $m_2$ will perform when the system is left to itself. There is no swing across the thread.

(we assume $m_2 > m_1$). In this case, the tension force of the thread would be equal to

$$T = \frac{2m_1m_2}{m_1 + m_2} g.$$

We will assume that at the initial moment the system is kept in equilibrium with the help of an additional force applied to the load $m_1$. Then the spring tension at the initial moment

$$T_0 = m_2g \neq T,$$

so that in addition to accelerated movement, oscillations of the loads relative to each other also occur. The amplitude of the tension force during these oscillations is equal to

$$T_0 - T = \frac{m_2 - m_1}{m_2 + m_1} m_2g,$$

the maximum stretch of the spring is

$$\Delta l = \frac{T_0 - T}{k}.$$

The mixing of loads during vibrations is inversely proportional to their masses. If $l_1$ and $l_2$ are the maximum mixings of loads $m_1$ and $m_2$, respectively, then

$$l_1m_1 = l_2m_2$$

$$l_1 + l_2 = l = \frac{T_0 - T}{k} = \frac{m_2 - m_1}{m_2 + m_1} m_2g.$$

From here we find the amplitude of oscillations of the load $m_2$:

$$l_2 = l \frac{m_1}{m_1 + m_2} = \frac{m_2 - m_1}{k(m_1 + m_2)^2} m_1m_2g.$$

We considered the movement of loads under the condition that at the initial moment the load $m_2$ stretches the spring. Solve the problem yourself, assuming that the spring is not stretched at the initial moment.

G. Kotkin

F669. Turn over a thin-walled glass with a cork bottom of thickness d floats at the interface between two liquids with densities $\rho_1$ and $\rho_2$. The top of the glass is located H above the interface. The cross section of the glass is S. How far does the glass rise if a hole appears in the bottom of the glass?

After a hole appears in the bottom, the liquid separation levels inside and outside the glass will be equalized. In this case, the glass should begin to move upward, since the buoyant force increases (the pressure on the cork bottom increases, since $\rho_2 > \rho_1$). The only counteracting effect arises due to the fact that in this case the force acting upward on the end of the glass decreases (the glass is thin-walled; this means that the end area $\Delta S \ll S$). It is clear that in the case when the increase in buoyancy force is not very significant (and this will be, if necessary, the value of $H - d$), the glass, having floated to a certain distance, which we denote by x, again finds itself in equilibrium. Let us write down the increase in equilibrium in the first and second cases ($p_0$ — pressure at the liquid interface, $L$ - total height of the glass):

$$mg + (p_0 - \rho_1gH)S = [p_0 + \rho_2g(L - H)]\S + [p_0 - \rho_2g(H - d)](S - \Delta S),$$

$$mg + [p_0 - \rho_1g(H + x)]S = [p_0 + \rho_2g(L - H - x)]\Delta S + [p_0 - \rho_1g(H + x - d)](S - \Delta S).$$

Opening the brackets and bringing similar terms, we get

$$m = \rho_1HS - \rho_2HS + \rho_1dS + \rho_2L\Delta S - \rho_2d\Delta S,$$

$$m = \rho_1dS + \rho_2L\Delta S - \rho_2H\Delta S - \rho_2x\Delta S + \rho_1H\Delta S + \rho_1x\Delta S - \rho_1d\Delta S.$$

Equating the right sides, we obtain after simple transformations:

$$x = (H - d) \frac{S - \Delta S}{\Delta S}.$$

The glass will stop moving upward if the condition x < L - H is compacted, or

⟦folio 46⟧

$$H - d < \frac{\Delta S}{S} (L - d).$$

If this condition is not met, the glass will float to the surface.

A. Zilberman

F670. Show that the maximum speed that an α particle can impart to a proton upon collision is 1.6 times the initial speed of the α particle.

Let us first assume that the proton ends relative to the stationary frame of reference, and the α-particle has a speed of $\vec{v}_0$. The process of their control is described by the law of conservation of momentum

$$4m\vec{v}_0 = m\vec{v}_1 + 4m\vec{v}_2$$

and the law of conservation of energy

$$\frac{4mv_0^2}{2} = \frac{mv_1^2}{2} + \frac{4mv_2^2}{2},$$

where $\vec{v}_1$ and $\vec{v}_2$ are the velocity vectors of the corresponding proton and α-particle in the stationary frame of reference after the collision, $m$ and $4m$ are the masses of the proton and α-particle.

Let us consider the process of collision of these particles in the center of mass system, that is, in an inertial reference system moving relative to a stationary reference system with a speed of $\vec{v}' = \frac{4m\vec{v}_0}{m+4m} = \frac{4}{5}\vec{v}_0$ (the numerator of the first is the full impulse of the system, the denominator is its total mass). figure shows the vector $\vec{v}_0$ and the velocity vector of the α-particle (vector $\vec{OB}$) and proton (vector $\vec{OA}$) in the center of mass system before the collision; $|\vec{OB}| = \frac{1}{5}|\vec{v}_0|, |\vec{OA}| = \frac{4}{5}|\vec{v}_0|$.

According to the implus collision law, after the collision the vectors $\vec{OB}'$ and $\vec{OA}'$ of the velocities of the α-particle and proton must lie on the same straight line and must fulfill the correspondence $|\vec{OB}'|:|\vec{OA}'| = 1:4$ (see figure); according to the law of collision of energy, $|\vec{OB}'| = |OB|$ and $|\vec{OA}'| = |\vec{OA}|$ (show me!).

The velocities of the α-particle and proton in the stationary frame of reference are depicted by figure vectors $\vec{OC}_2 = \vec{OB}' + \vec{v}$, $\vec{OC}_1 = \vec{OA}' + \vec{v}$ respectively ($\vec{v} = \frac{4}{5}\vec{v}_0$).

To answer the question of the problem, we must determine the maximum possible length of the vector $\vec{OC}_1$, that is, in the equilibrium triangle $OA'C_1$ it is necessary to determine the maximum possible length of the base with constant lengths of the sides. Obviously, the maximum of $|\vec{OC}_1|$ is equal to $2 \cdot \frac{4}{5}|\vec{v}_0| = 1,6|\vec{v}_0|$. This situation responds to the central udur.

S. Krotov

F671. There is 1 liter of hot water with a temperature of $T_1$ and 1 liter of cold water with a temperature of $T_2$. Using hot water to warm up from cold. Is it possible to make the final temperature of water that was initially cold become higher than the temperature of water that was initially hot?

Answer: you can.

We'll show you how to do it. Let us have at our disposal a vessel $A$ with hot water (hot water temperature $T_r$), a vessel $B$ with cold water (temperature $T_x$), a vessel $C$, the walls of which are thermally conductive, and a vessel $D$, which is thermally conductive.

We heat cold water in two stages:

1) Pour some of the cold water from $B$ into $C$; lower $C$ from cold water into $A$. After some time, the water temperatures in $A$ and $C$ will become equal: $T_A = T_C = T_1$, and

$$T_r > T_1 > T_x.$$

We pour “cold” water from $C$ into a heat-conducting vessel $D$.

2) Pour the remaining cold water into $C$; we lower $C$ into $A$ (in $A$ “hot” water with a temperature of $T_1$). Through

⟦folio 48⟧

$$\approx 10^{-3}g.$$
The moon gives about the same (remember the tides).

Air resistance: drag force $F = asv^2$. The value $\alpha$ can be approximately estimated by knowing the hail speed $v_r \approx 20$ m/s at $r_r \approx 0,5$ cm:

$$\alpha \pi r_r^2 v_r^2 = m_r g = \frac{4}{3} \pi r^3 g \Rightarrow \alpha = \frac{4 \rho_r r_r}{3 v_r^2}.$$

For the core, the speed $v_r$, at which the drag force of the air is equal to the force of gravity, is determined by the conditions

$$v_r = v_r \sqrt{\frac{\rho_r r_r}{Q_r r_r}} \approx 200 \text{ m/c}.$$

This means for a given speed $F_{\text{conp}} = mg \left(\frac{12}{200}\right)^2 \approx 3 \cdot 10^{-3}mg$. (Note that at such speeds the force of high friction is greater than that of frontal friction, but it is also incorrect.)

Archimedes' power

$$F_A = \frac{\rho_B}{Q_A} mg \leq 10^{-3}mg.$$

Correction for free-fall distortion due to the rotation of the Earth

$$\Delta g_2 = \omega_2^2 R_2,$$

where $\omega_2 = 2\pi/1$ day, $R_2 = 6,3 \cdot 10^6$ cos $\varphi$ (f is the latitude of the area). At the equator $\Delta g_2 \leq 3 \times 10^{-3}g$.

The numbers in the problem are set to “round”; From simple practical reports it is clear that we require accuracy no better than 3-5%. This means that all of the above amendments are not significant, and our model is entirely reasonable. The solution to the problem is quite simple, we do not give it.

However, situations are possible when even small adjustments can have a decisive impact on the result. This can happen, for example, if we become interested in the different motions of several bodies. Consider this question for yourself: will a vertically fired projectile hit the gun barrel?

A model may turn out to be completely inapplicable if it does not reflect the essential features of the phenomenon. For example, the model of an absolute rigid body is not applicable to describe an absolute impact - deformations play an important role during an impact, and an absolutely rigid body does not deform. Another example: the inductance of conductors (or, which is the same thing, the energy of the magnetic field that arises around a conductor when current is passed through it) is often ignored; however, in the well-known problem about a capacitor, which, after charging, is short-circuited with a conductor, it is impossible to simultaneously consider the resistance of the conductor and its inductance - if the resistance is very small, then the current turns out to be very large, and even with low inductance, the energy of the magnetic field turns out to be significant. A simple analysis shows that the inductance action in different cases differs significantly from the inductance only in different cases, and the sand fills the liquid present in the body (something similar will happen when, wanting to fill the picture of draining lines of the magnetic field, we pour iron filings onto a sheet of paper and shake it to weaken the tension).
