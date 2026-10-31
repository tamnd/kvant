---
id: 1989-10-resheniya-zadach-m1161-m1164-f1173-f1177-91d1db8b
issue: kvant_1989_10
year: 1989
number: "10"
title: Solutions to problems M1161—M1164; F1173—F1177
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 32
page_last: 38
page_labels: 30-36
tag: 89L0
lang: en
source: kvant_digital
extraction: vision
content_sha256: bd36a5131ebf229bc934ecc23449509fa48c28747f35c8d50113d6e0f7586bc1
prompt_sha256: draft-1
translated_from: content/ru/1989/10/articles/07_resheniya-zadach-m1161-m1164-f1173-f1177-91d1db8b.md
source_content_sha256: 465cf1b8b2b906668af6606ceadee59801b63e1bf26c142f4669fbf59cb3f3dc
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 30⟧

Problem solutions
M1161 — M1164, F1173 — F1177

M1161. In most cases, 10 balls are performed. Prove that if 9 balls are placed in it, then there will definitely be room for the tenth (i.e., the centers of 9 balls will be located on a triangular grid).

Taking the diameter of the ball as 1. The problem is equivalent to the following: prove that if 9 points $K_1, K_2, ..., K_9$, the pairwise distances between which are at least 1, are placed in a regular triangle with side 3, then they are necessarily located at the vertices of a triangular lattice with side 1 (in 9 out of 10 black points on figure). It is enough to prove that 6 (or 7) of the points $K_i$ are located within the red hexagon, and they are necessarily located at its vertices or in the center $O$ - after all, in each corner triangle with side 1 (not on the red side) there can only be one of the points $K_i$, and if there is another point $K_j$ on its red side, then $K_i$ lies at the vertex of the large triangle.

It is clear that if one of the 6 points $K_i$ inside the hexagon coincides with $O$, then the rest lie at the vertices. If all of them are different from $O$, then the segments $OK_i$ drawn to these points form angles $60^\circ$ with each other (if $\angle K_iOK_j < 60^\circ$, $OK_i \leq 1$, $OK_j \leq 1$, then $K_iK_j < 1$) and $OK_i = 1$.

Apparently, the following fact is also true: if you remove one ball from 1+2+...+$n=n(n+1)/2$ balls closely placed in a triangular box, then the rest will necessarily be located in a triangular grid - so the removed ball can be put back in place.

N. P. Dolbin

M1162. Find all integer solutions to the equations
$$x^3 - 13x \cdot y + y^3 = 13.$$

Let's introduce new variables $s = x + y$ and $t = xy$. Then the equation will take the form $s^3 - 3st - 13t = 13$, or
$$t = \frac{s^3 - 13}{3s + 13},$$
(*)

and therefore
$$27t = \frac{27s^3 - 13 \cdot 27}{3s + 13} = 9s^2 - 39s + 169 - \frac{13^3 + 13 \cdot 27}{3s + 13}.$$

From here we get that the number 3s+13 must be a divisor of the number 2548=13·196. Further, since $s^2 - 4t = (x - y)^2 \geq 0$, then
$$s^2 - 4 \frac{s^3 - 13}{3s + 13} = \frac{3s^3 + 13s^2 - 4s^3 + 52}{3s + 13} \geq 0$$
and, therefore,
$$\frac{s^2(13 - s) + 52}{3s + 13} \geq 0.$$

Hence we have $s \leq 13$ and $s \geq -4$ (otherwise the value of the fraction is negative). Therefore, 3s+13 lies within the interval 1 when divided by 3. The number 2548 = 2 2 7 7 13 has seven such divisors: 1, 4, 7,

⟦folio 31⟧

13, 28, 49, 52. They give the values ​​of $s$ respectively: $-4, -3, -2, 0, 5, 12, 13$ and the values ​​of $t$ (from equation (*)): $-77, -10, -3, -1, 4, 35, 42$. Solving for each of these pairs of systems

$$\begin{cases} x+y=s, \\ xy=t \end{cases}$$

- for this it is enough to find the roots of the quadratic equation $z^2-sz+t=0$ - we get 7 pairs of solutions (7; 5), (7; 6), (7; -11), (1; -3), (1; -1), (1; 4), (-5; 2). Naturally, due to the symmetry of the original equation with respect to $x$ and $y$, the numbers in pairs can be swapped, so that the equation has 14 solutions in total. In general, it is easy to see that the equation $x^3-kxy+y^3=m$ for integers $k$, $m$ has a finite number of solutions in integers if $k^3+27m \neq 0$. Note that the equation

$$x^3-kxy+y^3=k$$

always has a standard solution (1; -1) and, if $k=2p+1$, also a solution $(p; p+1)$. However, the coefficient $k=13$ is, in some senses, almost "unique": all valid values ​​of $s$ (mapped by the inequality $s^2-4t \geq 0$) result in quadratic equations having integer solutions. One can notice another comparatively simple property of equation (***), which can be traced in this example: if $(a; b)$ and $(a; c)$ are solutions to this equation, then the pair $(a; -b-c)$ is a solution to this equation (this easily follows from Vieta’s theorem).

D. V. Fomin

M1163. Cherenakha left point $A$ and arrived at point $B$, moving along an arbitrary trajectory at an arbitrary speed. Following it, a second cherenakh emerged from point $A$, which at each moment of time moved in the direction of the feather (at an arbitrary speed) and eventually also came to point $B$. Prove that let, eaten by the second stalk (by the time both of them arrive at $B$), does not exceed the path of the feather.

Let by the moment of time $t$ the 1st cherenakh has passed the path $L(t)$, the second - $P(t)$, and the distance between them at this moment is $D(t)$. Let us prove that over time the quantities

$$f(t)=L(t)-P(t)-D(t)$$

does not kill, i.e. $f(t) \geq f(t')$ with $t > t'$. From here the statement of the problem will follow: let the 1st cherenakh begin movement at $t=0$, and the 2nd one finish it at $t=T$, then $f(0)=0$, $D(T)=0$ and if $f(T)=L(T)-P(T) \geq f(0)$, then $L(T) \geq P(T)$.

The main statement about $f(t)$ can be proven in different ways. (For example, using an arbitrary one.) The difficulty stems from the fact that the problem involves arbitrary trajectories and arbitrary speeds. We will get around this difficulty in this way: we will replace the trajectories of the cuttings with broken lines close to them.

Let $M_i$ be the position of the 1st cherenach at time $t_i=i\tau$, $\tau=T/n$ ($i=0, 1, ..., n$; $M_0=A$, $M_n=B$); $u_i$ is the speed of the 2nd Cherenakh at time $t_i$. Suppose that the 1st cherenakh in the time interval between $t_i$ and $t_{i+1}$ passes the segment $M_iM_{i+1}$, and the 2nd traverses the segment $N_iN_{i+1}$ of length $u_i\tau$, directed to the point $M_i$ (Fig. 1;

⟦folio 32⟧

We believe that $u_0 = 0$, $N_0 = N_1 = A$; if $u_i \tau \geq M_i N_i$, then $N_{i+1} = M_i$). Let during this movement along the broken lines by the moment $t_i$ the paths $L^*(t_i)$, $P^*(t_i)$ have passed through and are at a distance $D^*(t_i)$ from each other. (On each interval $[t_i, t_{i+1}]$ we consider these functions to be linear.) Let us set $f^*(t) = L^*(t) - P^*(t) - D^*(t)$. Because (see figure 2)

$$D^*(t_i) = N_i M_i, L^*(t_{i+1}) = L^*(t_i) + M_i M_{i+1},$$
$$P^*(t_{i+1}) = P^*(t_i) + N_i N_{i+1}, D^*(t_{i+1}) = N_{i+1} M_{i+1},$$

we get

$$f^*(t_{i+1}) - f^*(t_i) = M_i M_{i+1} - N_i N_{i+1} + M_{i+1} N_{i+1} - N_i M_i = N_{i+1} M_i + M_i M_{i+1} - N_{i+1} M_{i+1} \geq 0.$$

So, the function $f^*(t)$ is non-decreasing. It follows that $f(t)$ is non-decreasing: for a sufficiently large $n$, the broken lines $M_0 M_1 \dots M_n$ and $N_0 N_1 \dots N_n$ will be as close as possible to the trajectories through, and the function $L^*$, $P^*$ and $D^*$, $f^*$ - respectively to the functions $L$, $P$, $D$ and $f$, and if it turned out that $f(t) > f(t')$ for some $t > t'$, then it must be $f(t_{i+1}) > f(t_i)$ for some $i$ (for a sufficiently large $n$).

S. Yu. Orvekov, A. Kh. Shen

**M1164. A natural number $n$ is called perfect if it is equal to the sum of all its divisors less than $n$ (for example: $28 = 1 + 2 + 4 + 7 + 14$). Prove that an odd perfect number (if such a number exists) cannot be divisible by 3, 5, and 7 at the same time.**

Let $n = p_1^{k_1} \dots p_r^{k_r}$ be the factorization of the number $n$ into prime factors. Then the sum of $S(n)$ of its divisors, including 1 and $n$, is equal to $(1 + p_1 + \dots + p_1^{k_1})(1 + p_2 + \dots + p_2^{k_2}) \dots (1 + p_r + \dots + p_r^{k_r})$. (*)

Since $n$ is perfect, $S(n) - n = n$, i.e. $S(n) = 2n$. If $n$ and all its prime factors $p_1, p_2, \dots, p_r$ are odd, then in the product (*) one of the sums in parentheses is even, and the rest are odd. Let $k_1 = 2m + 1$, then

$$1 + p_1 + \dots + p_1^{2m + 1} = (1 + p_1)(1 + p_1^2 + \dots + p_1^{2m}).$$

$p_1 \neq 3$ and $p_1 \neq 7$ (otherwise $S(n)$ is divisible by 4). If the average number $p_1, p_2, p_3, \dots, p_r$ occurs 3, 5 and 7, and $p_1$ is different from 3 and 7, then

$$\frac{S(n)}{n} \geq \left(1 + \frac{1}{p_1}\right)\left(1 + \frac{1}{p_2} + \frac{1}{p_2^2}\right) \dots \left(1 + \frac{1}{p_r} + \frac{1}{p_r^2}\right) \geq$$

$$\geq \left(1 + \frac{1}{5}\right)\left(1 + \frac{1}{3} + \frac{1}{9}\right)\left(1 + \frac{1}{7} + \frac{1}{49}\right) =$$

$$= \frac{6 \cdot 13 \cdot 57}{5 \cdot 9 \cdot 49} > 2.$$

This contradicts the equality $S(n) = 2n$.

V. V. Shabunin

**F1173. Length irregular noeed, composed of a large number of va-**

As you ascend into the “dead loop,” the speed of the train decreases. It reaches its lowest value $v$, when the “loop” is completely filled with the composition (and then

⟦folio 33⟧

onov, rides at a constant speed along horizontal rails, and then howls into a “dead loop” (Fig. 1). Train length L, loop radius R (R is significantly larger than the dimensions of the car, but L>2πR). At what initial speed will it travel and overcome the transition so that during movement not a single car stops pushing on the rails?

Fig. 1.

Fig. 2.

Fig. 3.

will not change). Let us write down the law of conservation of energy for this and the initial moments:

$$\frac{Mv_0^2}{2} = \frac{Mv^2}{2} + \left( M \frac{2\pi R}{L} \right) gR,$$

(1)

where M is the mass of the entire train, v₀ is its initial speed, M(2πR/L) is the mass of the cars located in the “loop,” R is the height of their center of mass.

While the car is in contact with the rails, a reaction force acts on it from the side of the rails. The highest point of the “loop” corresponds to the lowest reaction force. In the limiting case, the reaction force is zero. In this case, the trailer (Fig. 2) is subject to gravitational forces mg (m is the mass of the trailer) and tension forces T from the couplings with two adjacent trailers. The resultant of these forces is directed vertically downwards and imparts to the carriage the necessary centripetal acceleration v²/R:

$$2T(\alpha/2) + mg = mv^2/R.$$

Here we taught the smallness of the angle α=l/R, at which a carriage of length l is visible from the center of the “dead loop”, and replaced the sine of the small angle with a symmetric angle. Note also that m=(l/L)M=(αR/L)M (if we neglect the gaps between the cars). Then the previous equation can be written as

$$T + \frac{R}{L}Mg = M\frac{v^2}{L}.$$

(2)

Now let’s find the tension force T. Let’s consider the part of the train that gets into the “dead loop” (Fig. 3). Let the composition of the mixer for a small distance be Δx, then the force T has performed the work A=TΔx. But since the speed of the train has not changed, this work must be equal to the change in the potential energy of a section of the train with length Δx and mass Δm=(M/L)Δx, rising to a height of 2R (see Fig. 3). So,

$$T\Delta x = 2\frac{M}{L}\Delta xRg,$$

and T = \frac{2MRg}{L}.

(3)

Combining equalities (1) - (3) in the system, we find the initial initial speed of the train:

$$v_0 = \sqrt{Rg(3+4\pi R/L)}.$$

A. I. Buzdin

F1174. In a cubic sauce with a volume of V = 1 liter there is m = 0.01 g of whole at a temperature of T = 300 K. Let's observe one of the molecules. How many times will it hit the top wall of the sauce in time t=1 min?

If the time specified in the task is long enough (this should be checked), then all molecules will collide with the selected sauce wall equally often. Then the required number of hits

$$n_{уд} = \frac{n_{уд обш}}{N},$$

where n_{beat total} is the total number of hits on the wall, N is the number of molecules in the sauce.

⟦folio 34⟧

To estimate $n_{yd}$ we proceed as follows. Let us denote the wall area by $S$ ($S=(\sqrt[3]{V})^2$) and the concentration of molecules by $n$ ($n=N/V$). It is obvious that in time $t$ all those molecules that are located at a distance $\bar{v}_x t$ from it will hit the wall ($\bar{v}_x$ is the average value of the molecules corresponding to the velocity components) and moved towards the wall, i.e.

$$n_{yd} = \frac{1}{2} n \bar{v}_x t S.$$

Now let's evaluate $\bar{v}_x$:

$$\bar{v}_x = \sqrt{\bar{v}_x^2} = \sqrt{\frac{1}{3} v^2} = \sqrt{\frac{RT}{M}},$$

where $R=8,31$ J/(mol K) is the universal gas constant, $M=4 \cdot 10^{-3}$ kg/mol is the molar mass of helium.

Thus, we finally get

$$n_{yd} = \frac{n \bar{v}_x t S}{2N} = \frac{1}{2V} \sqrt{\frac{RT}{M}} t V^{2/3} = \frac{\sqrt{RT/M} t}{2V^{1/3}} \approx 2,5 \cdot 10^5.$$

In other words, if we do not take into account the molecules colliding with each other, then $n_{yd} = (v_x t)/(2a)$, where $2a=2V^{1/3}$ is the path of the molecule “from ceiling to ceiling”.

We now need to justify the chosen model. To do this, let’s estimate the free length of a molecule, i.e., the average distance traveled by a molecule between two collisions with other molecules:

$$\lambda \approx \frac{V/N}{\pi d^2} = \frac{1}{\pi d^2 n},$$

where $d \sim 10^{-10}$ m is the diameter of the molecules. Under normal conditions, 1 m$^3$ of any gas contains $\approx 2,7 \cdot 10^{25}$ molecules. Therefore, $\lambda \approx 10^{-6}$ m and the average displacement of a molecule during time $t$ is equal to

$$\bar{x} = \sqrt{\lambda v_x t} \approx 1 \text{ м},$$

which is significantly larger than the size of the vessel. This means that stirring really effectively “levels out” the molecules.

A. R. Zilberman

F1175. The UFO flies over the Earth at a constant, very high speed $v$. What speed will be recorded by ground samples of the tracking station at the moment when the direction to the object makes an angle $\varphi$ with the vertical (Fig. 1)?

Let time $t$ pass from the moment the UFO flew close to the observed point $A$ (Fig. 2) to this moment (to point $B$), and this time was absent according to the fixed clock, we are at point $B$. Let us denote the altitude of the UFO over the Earth by $l$. Then the path traveled by the object from $A$ to $B$ is

$$vt = l \ tg \ \varphi.$$

Observe and see a luminous object at point $B$ a little later (due to the finite speed of light propagation $c$), and its clock will show the time

⟦folio 35⟧

F1176. Charges +Q and –Q of mass M each are attached to a weightless beam of length 2L, which can rotate without friction around a vertical axis. Under the yoke, along the continuation of the rotation axis, there is a small diopole - charges +q and -q at a distance of 2a from each other (a≪L). At the initial moment, the yoke is in a state of stable equilibrium (Fig. 1).
a) The diopole causes rotation with angular velocity ω. At what ω will the beam “accompany” the rotation of the diopole?
b) The diopole is motionless. For these periods of small oscillations, the steering gear.

$$t_1 = t + \frac{l/\cos \varphi}{c}.$$

(2)

Obviously, the speed of the UFO changing the observable is equal to

$$v_1 = \frac{dx}{dt_1} = \frac{dx}{dt} \frac{dt}{dt_1} = \frac{v}{dt_1}.$$

From equality (2)

$$\frac{dt_1}{dt} = 1 + \frac{l \sin \varphi}{c \cos^2 \varphi} \frac{d\varphi}{dt},$$

and from equality (1)

$$\frac{d\varphi}{dt} = \frac{v \cos^2 \varphi}{l},$$

Posibly, the finally sought speed is equal to

$$v_1 = \frac{v}{1 + \frac{v}{c} \sin \varphi}.$$

S. S. Krotov

F1176. Charges +Q and –Q of mass M each are attached to a weightless beam of length 2L, which can rotate without friction around a vertical axis. Under the yoke, along the continuation of the rotation axis, there is a small diopole - charges +q and -q at a distance of 2a from each other (a≪L). At the initial moment, the yoke is in a state of stable equilibrium (Fig. 1).
a) The diopole causes rotation with angular velocity ω. At what ω will the beam “accompany” the rotation of the diopole?
b) The diopole is motionless. For these periods of small oscillations, the steering gear.

a) Let's move to a non-inertial reporting system associated with a diopter. In this system, the yoke at the initial moment rotates with angular velocity ω. It will “accompany” the dioplom if its energy is not enough to make a full revolution. In other words, if its initial energy is less than the energy at its worst disadvantage:

$$2 \frac{M(L\omega)^2}{2} + 2 \left( -\frac{Qq}{4\varepsilon_0(L-a)} + \frac{Qq}{4\varepsilon_0(L+a)} \right) < \quad < 2 \left( -\frac{Qq}{4\varepsilon_0(L+a)} + \frac{Qq}{4\varepsilon_0(L-a)} \right).$$

As a result we get

$$\frac{M(L\omega)^2}{2} < 2 \frac{Qq}{4\varepsilon_0} \left( \frac{1}{L-a} - \frac{1}{L+a} \right) = 2 \frac{Qq}{4\varepsilon_0} \frac{2a}{L^2-a^2} \approx \frac{Qqa}{\varepsilon_0 L^2},$$

where

$$\omega < \frac{1}{L} \sqrt{\frac{2Qqa}{\varepsilon_0 M}}.$$

6) Let us distance the deviation of the yoke from the equilibrium position by a small angle α (Fig. 2). Each charge of the beam is acted upon by forces from each charge of the diopole. Since L≪α, we can assume that the modules of all forces are the same and equal to F=Qq/(4\varepsilon_0 L^2), and their shoulders are equal to αα. Let us write down the equation of motion of the steering arm (a similar equation to Newton’s second law for the translational motion of a body):

$$2ML^2\alpha'' = -4 \frac{Qq}{4\varepsilon_0 L^2} \alpha\alpha,$$

⟦folio 36⟧

Pis. 1.

F1177. The oscillating circuit consists of a coil with inductance $L = 1$ Gi and resistance $R = 1$ Ohm and a capacitor with a capacity of $C = 1$ µF. The capacitor is not ideal - its insulation resistance $R_x$ is finite. At what value $R_x$ in the coil is released in the form of heat 1/3 of the initial energy of the circuit?

Fig. 1.

Fig. 2.

LET'S CLEAR THE QUESTION ABOUT CIRCUIT DAMPING, first without taking into account losses in the capacitor (Fig. 1). If we consider the current fluctuations in the coil to be harmonics, then over the period the losses in the coil will be

$$\Delta W = \frac{I_0^2 R}{2} T,$$

where $I_0$ is the amplitude of the current in the coil, $T = 2\pi\sqrt{LC}$ is the oscillation period. The maximum circuit energy is $W = \frac{LI_0^2}{2}$.

Then $$\frac{\Delta W}{W} = \frac{I_0^2 RT}{LI_0^2} = 2\pi R \sqrt{\frac{C}{L}}.$$

In our case

$$\frac{\Delta W}{W} \approx 6 \cdot 10^{-3} \ll 1,$$

that is, the vibrations can really be considered harmonious.

Note that the result will not change even taking into account the additional losses in the capacitor, which, according to the conditions of the problem, are only twice as large as the losses in the coil. So, in this case (Fig. 2) the losses in the coil are

$$\Delta W_2 = \frac{I_0^2 R}{2} T,$$

losses in the capacitor -

$$\Delta W_2 = \frac{U_0^2}{2R_x} T,$$

where $U_0$ is the voltage amplitude across the capacitor. Considering that $\Delta W_2 = 2\Delta W_1$ and $$\frac{LI_0^2}{2} = \frac{CU_0^2}{2},$$ we get

$$\frac{U_0^2}{2R_x} = \frac{CU_0^2 R}{L},$$

where does the resistance come from

$$R_x = \frac{L}{2CR} = 5 \cdot 10^5 \text{ Ом.}$$

Z. A. Rafailov
