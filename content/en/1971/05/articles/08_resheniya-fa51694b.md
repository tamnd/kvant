---
id: 1971-5-resheniya-fa51694b
issue: kvant_1971_5
year: 1971
number: "5"
title: Solutions to problems M31—M33; F43, F48—F51
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 34
page_last: 40
page_labels: 32-38
tag: P8XZ
lang: en
source: kvant_digital
extraction: vision
content_sha256: 525593f9e87b0957af1709b679fad474277e192403201edc4957ec2df4f06fae
prompt_sha256: draft-1
translated_from: content/ru/1971/05/articles/08_resheniya-fa51694b.md
source_content_sha256: 4cbd00a132c3c5f38a5b2b221a0ed5acd080708b33e16812a1191668c89e420b
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 32⟧

Solutions

In this issue we publish solutions to problems M31–M33

M31

A square sheet of paper is cut straight into two parts. One of the resulting parts is again cut into two parts, and this is done many times. What is the smallest number of cuts that need to be made so that the resulting parts turn out to be exactly twenty-decagons?

With each cut, the total number of pieces of paper increases by 1 (since one piece disappears and two new ones appear), so after $n$ cuts there will be $(n+1)$ pieces of paper.

Let us now calculate what the total number of vertices in all pieces together can be after $n$ cuts. With each cut, the total number of vertices increases either by 2 (if you cut through the vertices), or by 3 (if you cut through the vertex and side), or by 4 (if you cut through 2 sides). Since at first there were 4 vertices, then after $n$ cuts there will be no more than $4n+4$ vertices in all pieces together.

Let's assume that after $N$ cuts there are 100 dacagons. Since in this case the total number of pieces obtained will be $N+1$, then, in addition to these decadagons, there will be another $N+1-100$ pieces. Each of these pieces will have at least three vertices, so the total number of vertices in all pieces will be at least $100\cdot 20+(N-99)\cdot 3$. As was proven earlier, this number is no more than $4N+4$. Means,

$$4N+4 \geq 100\cdot 20+(N-99)\cdot 3 = 3N+1703,$$

whence $N \geq 1699$.

So, we have proven that it is impossible to get 100 bidecagons by making fewer than 1699 cuts. This is the main and most difficult part of the proof.

Let us now show how you can get 100 bidecagons by making 1699 cuts. Here is one way: cut the square into 100 rectangles (99 cuts) and turn each rectangle into a 20-sided triangle in 16 cuts, cutting off triangles from the corners (1600 cuts). There will be 1699 cuts in total.

Answer. Can get 100 decanagons by making 1699 cuts, and by making fewer cuts, 100 dedecagons.

In the same way, you can find out what is the smallest number of cuts you need to make to get exactly $k$ l-gons.

The exact solution to this problem was sent by D. Grigoriev from Leningrad and V. Livits from Zaporozhye.

I. N. Bernistey

M32

In all cells of the table $100 \times 100$ is a plane. It is allowed to simultaneously change the signs in all cells of one row or one column. Is it possible, by continuing the operations several times, to obtain a table with exactly 1970 minutes?

Let us change the sign $x_i$ times in the $i$th row, and $y_k$ times in the $k$th column. Then in the cell located at the intersection of the $i$th row and $k$th column, the sign will change $x_i+y_k$ times. Consequently, this cell will contain a minutec if and only if $x_i+y_k$ is odd. Thus, about

⟦folio 33⟧

The exact number of minuses in the resulting table depends only on the parity of the numbers $x_i$ and $y_k$; on figure 1, ​​zeros are placed together with even numbers, and ones are placed together with odd numbers. Let $x$ be the number of odd numbers among $x_i$; $y$ is the number of odd numbers $y_k$ (on figure $x = 5, y = 4$). Then, as is easy to calculate, the total number of minuses in the table will be equal to

$$x(100-y)+(100-x)y = 100x+100y-2xy,$$

where $x, y$ are integers.

Now let's return to our problem and prove that the answer is negative, i.e. it is impossible to get 1970 minuses. Let's assume that we managed to get 1970 minuses. Then $1970 = 100x+100y-2xy$, from where

$$xy - 50x - 50y + 2500 = 1515.$$

Factoring the left-hand side, we get

$$(x-50)(y-50) = 1515 = 15 \cdot 101.$$

We have

$$-50 \leq x-50 \leq 50, -50 \leq y-50 \leq 50.$$

Since 101 is a prime number, then either $x-50$ or $y-50$ is divisible by 101 (after all, their product is divisible by 101). But from the previous inequalities it then follows that either $x-50$ or $y-50$ is equal to 0. So, we have a contradiction that proves that exactly 1970 minutes of obtaining the impossible.

The correct solution was sent by D. Grigoriev.

A. V. Zelevinsky

M33

There is a natural number $n > 1000$. Let's take the remainders from dividing the number $2^n$ by the numbers 1, 2, 3,..., $n$ and find the sum of these remainders. Prove that this sum is greater than $2^n$.

Let us denote the sum of remainders from dividing $2^n$ by the numbers 1, 2,..., $n$ by $S_n$. We will succeed in the statement of the problem and prove that for $n > 1000$ $S_n > 3,5n$. Along the way, we will prove the same method as

$$S_n > \frac{n}{2} (\log_2 n - 4)$$

for any $n$.

We follow mainly the decision of D. Grigoriev from Leningrad. The solution is based on a very simple consideration: $2^n$ is not divisible by an odd integer other than 1, which means that the remainder of division of $2^n$ by such a number is not less than 1. From here it is easy to deduce that for any odd $k > 1$ the remainder of division of $2^n$ by $2^l k$ is not less than $2^l$. Indeed, let the remainder of the division of $2^{n-l}$ by $k$ be equal to $r$, that is, $2^{n-l} = mk + r$, where $0 \leq r < k$, then $2^n = m(2^l k) + 2^l r$, where $0 \leq 2^l r < 2^l k$, that is, the remainder of the division of $2^n$ by $2^l k$ is equal to $2^l r$, and since $r \neq 0$, then this remainder is not less than $2^l$.

It follows that in any case

$$S_n \geq 1 \cdot (\text{количество не превышших } n \text{ чисел вида } 2k + 1, k > 1) + 2 \cdot (\text{количество не превышших } n \text{ чисел вида } 2(2k + 1), k > 1) + 2^2 \cdot (\text{количество не превышших } n \text{ чисел вида } 2^2(2k + 1), k > 1) + \dots$$

+ $2^l \cdot (\text{количество не превышших чисел вида } 2^l(2k + 1), k > 1), (*)$

⟦folio 34⟧

where $l$ is determined by the condition $3 \cdot 2^l \leq n$, $3 \cdot 2^{l+1} > n$ (there is no point in taking more than $l$, since then the expression in the bracket will be equal to zero).

What can you say about the right side of this inequality?

Let's consider the $(i+1)$-th term: $2^i(\ldots)$. The number in the bracket is obviously equal to the number of non-exceeding $n$ terms of the arithmetic progression $3 \cdot 2^i$, $5 \cdot 2^i$, $7 \cdot 2^i$, ..., that is, a progression with the first term $3 \cdot 2^i$ and the difference $2 \cdot 2^i$. The number of such terms is no less than $\frac{n-3 \cdot 2^i}{2^{i+1}}$ and, therefore, the $i$ term on the right side of the inequality is no less than $\frac{n}{2} - \frac{3}{2} \cdot 2^i$. Basically, the solution to the problem is over. Everything else is various transformations of the right side (*) using the obtained inequalities. Let us replace, for example, the sum on the right side (*) when washed with eight terms. Then we will get

$$S_n > 8 \cdot \frac{n}{2} - \frac{3}{2} \sum_{i=0}^{7} 2^i >$$

$$> 8 \cdot \frac{n}{2} - \frac{3}{2} \cdot 2^8 = 3,5n + \left(\frac{n}{2} - 384\right).$$

For $n > 1000$ the expression in the bracket is positive and, therefore, we have proven that $S_n > 3,5n$ for $n > 1000$. Thus problem M33 is completely solved.

However, a more precise inequality can be obtained. Let's sum up all the terms on the right side (*); we get:

$$S_n > (l+1) \frac{n}{2} - \frac{3}{2} \sum_{i=0}^{l} 2^i >$$

$$> (l+1) \frac{n}{2} - \frac{3 \cdot 2^{l+1}}{2}.$$

Using the inequalities $3 \cdot 2^l \leq n$, $3 \cdot 2^{l+1} > n$, we find that

$$S_n > \frac{n}{2} \log_2 \frac{n}{3} - n =$$

$$= \frac{n}{2} \left(\log_2 \frac{n}{3} - 2\right) > \frac{n}{2} \left(\log_2 n - 4\right).$$

This formula shows, for example, that if $n > 2^{1004}$ then $S_n > 500 n$.

Task. The sum of the remainders from dividing the numbers $2^{l+1}$, $2^{l+L}$ by the odd number $m > 1$ is greater than $\frac{m}{2} \left(\frac{L}{\log_2 2m} - 1\right)$.

Using this problem, the solution of which will be given below, one can prove that for an infinite number of values ​​of $n$ the sum of $S_n$ is actually larger than $\frac{n}{2} \left(\log_2 n - 4\right)$, that is, one can prove that the estimate of $S_n > \frac{n}{2} \left(\log_2 n - 4\right)$ is very larger for an infinite number of values ​​of $n$. This is not surprising, since our method of proof does not take into account multi-wanted numbers other than zero, while these remainders are often large. At the same time, the value of $S_n$ cannot grow too quickly with the growth of $n$, since there are too many of those of $S_n \leq 1 + 2 + \ldots + (n-1) = \frac{n(n-1)}{2}$.

We believe that the following hypothesis is true:

Hypothesis 1. For sufficiently large $n$ the inequality $S_n \leq \frac{n^2}{4}$ is true;

6) there is a positive number $c > 0$ such that $cn^2 \leq S_n$.

We can neither prove nor verify these statements. Moreover, we do not know whether the weaker one is fair.

Conjecture 2. There is a positive number $c > 0$ such that the inequality $cn^2 \leq S_n$ holds for an infinite number of values ​​of $n$.

If you managed to prove or test one of these hypotheses, send us your reasoning. If they turn out to be interesting, we will publish them in one of the issues of the magazine. As a weak test of Hypothesis 2, the following can be proven.

Theorem. For an infinite number of values ​​of $n$ the following inequality holds:

$$S_n > \frac{n^2}{132 \log_2 n}.$$

The theorem is derived from the problem as follows. Consider the sum $\Sigma_k$ of the remainders from dividing the numbers $2^{k+1}$, ..., $2^n$ by the number $k$. According to the problem, if $k$ is odd, the sum $\Sigma_k$ is residually large, therefore the number $\Sigma_1 + \Sigma_2 + \ldots + \Sigma_n$ is also large. But how easy it is for*

*) The number $\frac{n^2}{132 \log_2 n}$ for large $n$ cities is greater than the number $\frac{n}{2} \left(\log_2 n - 4\right)$. It is not difficult to prove, for example, that for a sufficiently large $n$ the ratio of these numbers is greater than $\sqrt{n}$.

⟦folio 35⟧

tag, $S_1 + S_2 + \dots + S_n = \Sigma_1 + \dots + \Sigma_n$,
poznym, the amount worth the left side is also
is large and, therefore, one of the terms, say $S_l$, is also large. We leave the careful execution of the proof to the reader. Let us now move on to solving the problem.

Solving the problem. Let's write down the remainders from dividing the numbers $2^{l+1}, \dots, 2^l + L$ by $m$ and put a “tick” between two consecutive remainders if the first is greater than the second. Then, firstly, the remainder before the checkmark is greater than $\frac{m}{2}$, and secondly, the number of numbers between two consecutive checkmarks is less than $\log_2 2m$, since the remainders between two checkmarks form a geometric progression with value 2 (indeed, $2\log_2 2m - 1 = m > m - 1$, and every remainder is not greater than $m - 1$). Thus, the number of spaces between the checkmarks is greater than $\frac{L}{\log_2 2m} - 1$ and since at the end of each gap there is a number greater than $\frac{m}{2}$, then everything is proven.

A. G. Kushiirenko

In this issue we publish solutions to problems F43, F48—F51

F43

Find the pressure at the center of a liquid planet of radius $R$ if the liquid is incompressible and has a density $\rho$.

Divide the volume of the planet into thin spherical elephants with thickness $\Delta r$. It is easy to show that the equilibrium of the granitization forces acting from the side of the layer on the particle inside this layer is equal to zero. Indeed, for this purpose, consider a cone with a small angle at the apex, in which part of the mass $m$ is placed. The cone cuts out areas of areas $s_1$ and $s_2$ (Fig. 1) from the layer. If the mass of the substance per unit surface of the layer is equal to $\mu$, then the granitonic forces acting on the mass $m$ from sections $s_1$ and $s_2$ are equal

$$F_1 = \gamma \frac{m\mu s_1}{r_1^2}, \quad F_2 = \gamma \frac{m\mu s_2}{r_2^2};$$

But

$$\frac{s_1}{r_1^2} \cos \alpha_1 = \frac{s_2}{r_2^2} \cos \alpha_2 = \Omega$$

(Ω is the solid angle at the vertex of the cone), and $\alpha_1 = \alpha_2$; protected triangles are similar, that is, $\angle OA_1 M_1 = \angle OA_2 M_2, \angle OA_1 B_1 = \angle OA_2 B_2$ (they rest on the same arc) and $\alpha_1 = \angle OA_1 B_1 - \angle OA_1 M_1 a\alpha_2 = \angle OA_2 B_2 - \angle OA_2 M_2$.

Pozny $\frac{s_1}{r_1^2} = \frac{s_2}{r_2^2}$. Thanks to this

$$F_1 = F_2,$$ that is, these forces mutually balance each other. Carrying out a similar consideration for other parts of the layer, we will prove the statement made.

The force with which the layer element $\Delta s\Delta r$ bends to the center of the planet is equal to

$$F = \gamma \frac{4}{3} \pi r^3 \rho \Delta s \Delta r\rho$$,

where $r$ is the distance from this element to the center of the planet. From here we find that the increase in pressure in a section of thickness $\Delta s$ is equal to

$$\Delta p = \frac{F}{\Delta s} = \frac{4}{3} \pi \gamma \rho^2 r \Delta r.$$

Posny pressure at a distance $r_0$ from the center of the planet will be equal to

$$p = p_0 + \frac{4}{3} \pi \gamma \rho^2 \Sigma r \Delta r.$$

Since the sum $r\Delta r$ is equal to the area

⟦folio 36⟧

The figure bounded by the graph $y=r$ and the axis $r$ (Fig. 2), then

$$\sum r \Delta r = \frac{(R+r_0)(R-r_0)}{2} = \frac{R^2-r_0^2}{2}.$$

Because

$$p = p_0 + \frac{2}{3} \pi \rho^2 (R^2-r_0^2);$$

$p_0$ is the pressure on the surface of the planet, which can be taken equal to zero. Then

$$p = \frac{2}{3} \pi \rho^2 (R^2-r_0^2).$$

At the center of the planet ($r_0=0$) the pressure will be equal to

$$p_\mu = \frac{2}{3} \pi \rho^2 R^2.$$

F48

A rope is wound around the armature shaft of the dynamo, to which a weight is attached. As the weight descends, it rotates the anchor. When the armature was sufficiently untwisted, a load resistance was attached to the adhesives of the dynamo. Draw on a graph the dependence of the speed of rotation of the anchor on the time from the moment the load begins to move.

Since before the load is connected, the moment of external forces acting on the armature is constant, the armature rotates with constant angular acceleration and its speed increases in proportion to time.

After connecting the load, current will flow through the armature winding. Due to this, a moment of force will act on the armature in the magnetic field of the stator, proportional (like the force acting on a conductor with current in a magnetic field) to the magnitude of the current. This moment of force slows down the rotation of the armature. Since the current flowing through the armature winding is proportional to the em.d.c. induction occurring in the winding, and ed.d.c. induction, in turn, is proportional to the rate of change of the magnetic flux propagating the winding, that is, the angular speed of rotation of the armature, then at a certain angular speed $\omega_0$ the moment of force acting on the armature from the side of the load will be equal to the moment of the braking force acting on the armature in the magnetic field. $\omega_0$ is the speed of steady rotation of the armature.

The graph of the dependence of the armature rotation speed on time is shown in Fig. 4. The cool line is for the case when the armature rotation speed at the moment the load was connected was less than $\omega_0$, and the blue line—when it was more than $\omega_0$.

F49

The U-shaped tube is filled with water (Fig. 4). Air has been removed from one elbow; the air pressure in the other leg at temperature $T_0=20^\circ C$ is equal to atmospheric pressure. Both ends of the tube are full. What will be the difference in water levels in the elbows if the tube is heated to $T=100^\circ C$?

⟦folio 37⟧

Fig. 4.

The pressure in the left knee is equal to the saturated vapor pressure. The right elbow contains both air and water vapor, and the pressure is equal to the sum of the partial pressures of air and steam. Moreover, the steam in the right vessel is also saturated, and its partial pressure is equal to the steam pressure in the left knee. Therefore, when considering the equilibrium of water, we can not take into account the vapor pressure in the left and right elbows.

Let us write down the equilibrium condition for water in the tube at $T_0=20^\circ\text{C}$:

$$\rho gh_0 = P_0, \quad P_0 = 1 \text{ amm.}$$

From here

$$h_0 = \frac{P_0}{\rho g} \approx 10 \text{ m.}$$

At $100^\circ\text{C}$, the air pressure in the right knee becomes $P$, and the difference in water levels in the knees becomes $h$. At the same time

$$\rho gh = P. \quad (*)$$

$P$ is related to $P_0$ by the combined gas law:

$$\frac{P_0 V_0}{T_0} = \frac{PV}{T},$$

and $l - l_0 = \frac{1}{2} (h - h_0)$. Since $V_0 = l_0 s$, $V = ls$ (s is the cross-sectional area of ​​the tube), then from here we find

$$P = P_0 \frac{T}{T_0} \frac{l_0}{l} =$$

$$= P_0 \frac{T}{T_0} \frac{l_0}{l_0 + \frac{1}{2} (h - h_0)}.$$

Substituting this expression into equation (*), we get

$$h = \frac{P_0}{\rho g} \frac{T}{T_0} - \frac{l_0}{l_0 + \frac{1}{2} \Delta h},$$

or

$$h = h_0 \frac{T}{T_0} \frac{l_0}{l_0 + \frac{1}{2} \Delta h}.$$

Assuming that $1/2 \Delta h \ll l_0$, we get

$$h = h_0 \frac{T}{T_0} \approx 13 \text{ m};$$

$\Delta h \approx 3 \text{ m}, \frac{1}{2} \Delta h \approx 1,5 \text{ m} \ll l_0 = 15 \text{ m}$. This means that, comparing $1/2 \Delta h$ with $l_0$, we got a result that is not very different from the exact one.

F50

On a smooth horizontal table lie two identical cubes with masses $m$, connected by a spring of stiffness $k$ and length $l_0$ into a non-growth system. A force $F$, constant in magnitude and direction, will begin to act on the left cube (Fig. 5). Find the minimum and maximum distance between the cups as the system moves further.

Let the distance $l$ between the cups be minimum or maximum (we will say “extreme”). Then both cubes move with the same speed $v$, and the kinetic energy of the system is $2 \frac{mv^2}{2} = mv^2$. At the same time

⟦folio 38⟧

Time, the potential energy of the system is equal to the potential energy of the sloped spring, that is, $kx^2/2$, where $x$ is the change in the length of the spring ($x$ can be either positive - then the length of the spring $l = l_0 - x$ is less than $l_0$, or negative - then the length of the spring is greater than $l_0$). The total energy of the system is equal to the sum of the kinetic and potential energy, that is, $mv^2 + kx^2/2$. Since the system acquired this energy thanks to the force $F$, we can write that

$$FL = mv^2 + \frac{kx^2}{2}.$$

(*)

$L$ is the distance traveled by the left cube at the moment when the length of the spring became extreme (Fig. 6): $L = S + \frac{l_0}{2} - \frac{(l_0 - x)}{2} = S + \frac{x}{2}$ ($S$ is the distance traveled by the center of mass of the system).

The speed of the $v$ cups is equal to the speed of the center of mass of the system. A constant external force acts on the system, and it moves with uniform acceleration $a = F/2m$. Therefore, if we denote by $t$ the time from now

Fig. 7.

movement began until the moment when the length of the spring became equal to $L$, then $v = at$ and $L = \frac{at^2}{2} + \frac{x}{2}$. Substituting these expressions for $v$ and $L$ into equation (*), we obtain

$$F \left( \frac{at^2}{2} + \frac{x}{2} \right) = ma^2 t^2 + \frac{kx^2}{2}.$$

Hence $\frac{F^2 t^2}{4m} + \frac{x}{2} F = \frac{F^2 t^2}{4m} + \frac{kx^2}{2}$ or $Fx = kx^2$. Therefore, $x_1 = 0$, $x_2 = F/k$.

Thus, the minimum distance between a group is $l_{\min} = l_0 - x_2 = l_0 - \frac{F}{k}$, and the maximum is $l_{\max} = l_0 - x_1 = l_0$.

F51

Photographing a tiger from a distance of 20 meters is dangerous. What size should a 1mm pinhole camera be to make the tiger in the photo look striped? The distance between the stripes on a tiger's skin is 20 cm.

A camera obscura is a box of responsibility. The photographic film placed in the camera receives a wide beam of rays from every point of the photographed object (Fig. 7). In order for a tiger to appear striped in a photograph, it is necessary that the areas on which the rays falling from the nearest points of neighboring stripes on the tiger’s pelt fall do not intersect. To do this, it is necessary that the film be located at a distance $x$ from the answer, more than $d/tg\alpha$.

Because

$$tg\alpha = \frac{l/2}{L + x},$$ then $x > \frac{2d(L + x)}{l}$.

Hence $x > \frac{2dL}{l\left(1 - \frac{2d}{l}\right)}$. $\frac{2d}{l} \ll 1$, therefore, neglecting $2d/l$ compared to 1 in the denominator of the formula, we get $x > \frac{2dL}{l} = 20$ cm. The chamber size must be greater than 20 cm.

I. Sh. Slovodechkiy
