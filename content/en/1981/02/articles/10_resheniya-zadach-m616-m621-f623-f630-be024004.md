---
id: 1981-2-resheniya-zadach-m616-m621-f623-f630-be024004
issue: kvant_1981_2
year: 1981
number: "2"
title: Solutions to problems M616—M621; F623—F630
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 26
page_last: 33
page_labels: 24, 25, 26, 27, 28, 30, 31
tag: Q8IX
lang: en
source: kvant_digital
extraction: vision
content_sha256: d0ca849e7bdf470a01857ef86449b96343cbacb4e3102cc45364b0f16b19caba
prompt_sha256: draft-1
translated_from: content/ru/1981/02/articles/10_resheniya-zadach-m616-m621-f623-f630-be024004.md
source_content_sha256: 0a6929746dcdd516efff9e335e9cf2ea63bf011b2f2a17dc00a75967540c9fb3
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 24⟧

signal at the antenna input required for normal operation, $P_{\min} = 1 \cdot 10^{-13}$ W.
Estimate the maximum detection range of an aircraft whose reflected surface area is $S = 5$ m$^2$. Assume that the power of the reflected signal is $n = 10$ times less than the power of the incident signal and reflection occurs uniformly in all directions.

A. Zilberman

Problem solutions

M616. Is it possible to divide the numbers 1, 2, ..., 30 into groups a) of five numbers, b) of six numbers so that the sums of the numbers in all groups are the same?

c) For what n and k can the numbers 1, 2, ..., nk be divided into n groups of k numbers each so that the sums of the numbers in all groups are the same?

Fig. 1.

Fig. 2.

Fig. 3.

Let us call a partition that satisfies the conditions of the problem correct. The answer to the general question c) of the problem is given by

Theorem. For the set {1, 2, ..., nk} to admit a regular partition into k-element subsets, it is necessary and sufficient that either k be even or nk odd.

The need for these conditions is obvious. In fact, empty partitions exist; then the sum of the numbers $\frac{nk(nk+1)}{2}$ is divided by n (the number of the subset), that is, the number $k(nk+1)/2$ is an integer; therefore either k is even or nk+1 is even, that is, nk is odd.

This shows that the answer to question a) of the problem is negative ($k=5$ is odd, and $n=6$ is even).

To prove it, let us simply formulate the theorem in a more clear form:

In order for nk numbers {1, 2, ..., nk} to be arranged in a table of k rows and n columns in the correct way (the sums of the numbers in all columns are the same), it is necessary and sufficient that either k be even or nk odd.

Let k be even. Then the numbers can be arranged in a “snake” pattern in the table (Fig. 1; for each two consecutive rows, the sum of the numbers in any column is the same).

Let nk be odd. Let's arrange the numbers {1, 2, ..., 3n} “correctly” in the three top rows of the table (the remaining numbers, starting with the number 3n+1, can be arranged in the table $(k-3) \times n$ with a snake, since $k-3$ is even - Fig. 2). How to do this with $n=3, 5, 7$ is shown in Figures 3, a-c. In a similar way, you can construct a table $3 \times n$ for any odd $n=2m+1$ (Fig. 4; check that it contains every number from 1 to $3n=6m+3$ once).

It is easy to see that a trivial generalization of the proven theorem is true: the numbers nk numbers {a+1, a+2, a+3, ..., a+nk} could be arranged in a table of k rows and n columns in the correct way, which is necessary and sufficient for either k to be even or nk to be odd.

This generalization suggests another way to “correctly arrange” a straight line $3 \times n$: you need to divide a straight line $3 \times n$ into a straight line $3 \times 3, 3 \times 5$ (or an odd

⟦folio 25⟧

the number $n \geqslant 9$ can be represented in the form $n=3p+5q$, where $p, q$ are non-negative integers) and correctly arrange segments of the series $\{1, 2, \dots, 3n\}$ in them - respectively, from 9 and 15 numbers - as in the ready-made tables in Figures 3, a, b (in this case, in each rectangle you will have to add a constant to the number $a$).

Think about this more complex question: for what $k < n$ there is a “magic rectangle” of numbers 1, 2, ..., $nk$, in which the sums of numbers in all rows are equal and the sums of numbers in columns are also equal. A magic square exists for any $n \geqslant 3$ (see the book by M. M. Postnikov “Magic Squares”, M., “Hayka”, 1964).

S. Berkolaiko, N. Vasiliev

**M617. Inside the triangle there are circles $a, b, \gamma$, δ of the same radius so that each of the circles $a, b, \gamma$ touches two sides of the triangle and circle $b$. Prove that the center of the circle δ belongs to the line passing through the centers in the given triangle of the circle and the circle circumscribed about it.**

Let $ABC$ be a given triangle and $O_1, O_2, O_3$ be the centers of congested circles tangent to pairs of its sides, and $O_4$ be the center of the fourth circle - the one that touches these three (see figure). The lengths of their radii are denoted by $q$. Triangle $O_1O_2O_3$ is prepared for triangle $ABC$, since its sides are respectively parallel to the sides of triangle $ABC$. It is not difficult to see that the center of this homothety will be the point $N$, which is both the center of the circle inscribed in the triangle $ABC$ and the center of the circle inscribed in the triangle $O_1O_2O_3$. Indeed, the lines $AO_1, BO_2, CO_3$ are bissertrices of the angles of both the triangle $ABC$ and the triangle $O_1O_2O_3$, and the point $N$ is the intersection point of these bissertrices.

Now note that the point $O_4$ is the center of a circle circumscribed around the triangle $O_1O_2O_3$ (its distance to each of the vertices of this triangle is 2$q$).

Consider a homothety centered at $N$ that maps triangle $O_1O_2O_3$ to triangle $ABC$. The point $O_4$ goes into a certain point $M$ lying on the line $NO_4$. We already know that the point $O_4$ was the center of a circle circumscribed around the triangle $O_1O_2O_3$; therefore, its image - the point $M$ - will be the center of a circle circumscribed around the triangle $ABC$. So, the center of the circle described around the triangle $ABC$ lies on the same straight line with the point $O_4$ and with the center of the circle described in the triangle $ABC$. This proves the statement of the problem.

It is not difficult to calculate the q values ​​of these four circles in terms of $r$ and $R$—the radii of the inscribed circle in the triangle and the circumcircle.

Note that the radius of the circle inscribed in triangle $O_1O_2O_3$ is $r-q$, and the radius of the circle circumscribed around this triangle is $2q$.

Let $k$ be the coefficient of the homothety considered above. Then $(r-q)k=r$ and $2qk=R$. Expressing $k$ from each correspondence and equating the resulting expressions, we find

$$\frac{r}{r-q} = \frac{R}{2q},$$

where

$$q = \frac{rR}{R+2r}.$$

A. Savin

⟦folio 26⟧

M618. a) Prove that there are infinitely many natural numbers n such that n! is divisible by $n^2+1$.

b) Prove that for any a>0 there are an infinite number of positive integers n such that $[\alpha n]!$ is divisible by $n^2+1$. (Here m!=1·2·...·m; [x] is the integer part of the number x.)

Let us show, for example, that there are infinitely many n for which $n^2+1$ has the form $5m^2$. In other words, the equation $n^2-5m^2=-1$ has an infinite number of natural solutions. This statement follows from the following two facts, each of which can be verified directly: the pair $n=2$, m=1 satisfies this equation, and if n=a, m=b is its solution, then so does the pair $n=9a+20b$, m=4a+9b (how these formulas do this is explained in N. Vaguten’s article “Number Conjugation”, «Kvant», 1980, No. 2).

This immediately gives us a proof of the statement of problem a). Indeed, for the found values ​​of n we have $n^2+1=5m^2$, $m=\sqrt{\frac{n^2+1}{5}}<\frac{n}{2}$ and n! is divisible by $n^2+1$, since for n>5 the product 1·2·3·...·n contains the numbers 5, m and 2m.

The same can be done in the general case 6). But for this we would have to prove that there are an infinite number of natural D such that the number of natural solutions to the equation $n^2-Dm^2=-1$ is infinite (having then chosen D so that the inequality $D\geqslant5/\alpha^2$ holds, we would obtain the required values ​​of n). This statement is true, but its elementary proof is very difficult, so we will take a different route.

We will look for the n we need among numbers of the form $2k^2$. In this case, $n^2+1$ is decomposed into the product $n^2+1=4k^4+1=(2k^2+2k+1)(2k^2-2k+1)$, but this is not yet sufficient. Let us show how to obtain many k such that the numbers $P(k)=2k^2+2k+1$ and $Q(k)=2k^2-2k+1$ are composite (factorizable). Let's take the natural product c and put p=P(c), q=Q(c). Then for any l the number P(c+lpq) is divisible by q (prove it!). Let $P(c+lpq)=p\cdot r$ and $Q(c+lpq)=q\cdot s$. By taking c large enough, we can make p=P(c) and q=Q(c) greater than 5/a (this follows from the fact that P(k) and Q(k) increase indefinitely as k increases). In this case, $n^2+1=4k^4+1=P(k)\cdot Q(k)=p\cdot q\cdot r\cdot s$, where $k=c+lpq$, $r=P(k)/p<\frac{P(k)}{5/\alpha}<\frac{an}{4}$ (for k>5) and $s=Q(k)/q<\frac{Q(k)}{5/\alpha}<\frac{an}{4}$ (for k>5). Now choosing l so that p and q are less than an/4, we find that in the sequence 1, 2, 3, ..., [an] there are four distinct numbers, one of which is divisible by p, another by q, a third by r, and a fourth by s. Thus, we have constructed an infinite multiresponse n such that [an] is divisible by $n^2+1$.

Other solutions to this problem are also possible. The shortest one seems to be based on the decomposition

$$64m^{12}+1=(4m^4+1)(4m^4-4m^3+2m^2-2m+1)\times(4m^4+4m^3+2m^2+2m+1)$$

(this solution was proposed by our reader V. Yudakov).

A. Weintrob

Figure to M619.

M619. Prove that if the equation $|CD|=|AD|+|BC|$ holds for a hanging quadrilateral ABCD, then the bicsectrices of its angles A and B intersect on the side CD.

The problem essentially requires proving the existence of an infinite number of positive integers n such that $n!$ is divisible by $n^2+1$.

Let us show, for example, that there are infinitely many natural n such that the number of natural solutions to the equation $n^2-Dm^2=-1$ is infinite (if we then chose D so that the inequality $D\geqslant5/\alpha^2$ holds, we would obtain the required values ​​of n). This statement is true, but its elementary proof is very difficult, so we will take a different route.

Take a point K on side CD so that $|DK|=|AD|$, $|KC|=|BC|$ (see figure), and describe a circle around triangle ABK. Let M be the second point of intersection of this circle with [CD]. Let us show that [AM] and [BM] are bicsectrices of the corresponding angles. For example, for [AM] we have $BAM=BKC=90^\circ-\frac{BCK}{2}=90^\circ-\frac{1}{2}(180^\circ-DAB)=\frac{1}{2}DAB$, which is what was required.

I. Sharyn

⟦folio 27⟧

M620. Let $x_1, x_2, \dots, x_n$ be real numbers such that $x_1^2 + x_2^2 + \dots + x_n^2 = 1$. Prove that the sum of the models of $2^n$ numbers

$$\pm x_1 \pm x_2 \pm \dots \pm x_n$$

(so with all possible combinations of the signs “+” and “-”) does not exceed $2^n$.

Let us first prove that if $a_1^2 + a_2^2 + \dots + a_k^2 = k$, then $a_1 + a_2 + \dots + a_k \leq k$. Indeed, let $a_i = 1 + a_i$ ($i = 1, 2, \dots, k$). Then

$$a_1^2 + a_2^2 + \dots + a_k^2 = k + 2(a_1 + \dots + a_k) + (a_1^2 + \dots + a_k^2),$$

where

$$a_1 + a_2 + \dots + a_k = -\frac{1}{2} (a_1^2 + a_2^2 + \dots + a_k^2) \leq 0.$$

Posetom

$$a_1 + a_2 + \dots + a_k = k + (a_1 + a_2 + \dots + a_k) \leq k.$$

Let us now denote the sum of models $2^n$ numbers

$$\pm x_1 \pm x_2 \pm \dots \pm x_n$$

(so all possible combinations of signs “+” and “-”) through $S$. It is easy to check that the sum of the squares of all $2^n$ numbers included in the sum $S$ is equal to $2^n (x_1^2 + x_2^2 + \dots + x_n^2) = 2^n$. Let's denote the $2^n$ numbers included in $S$ by $a_1, a_2, \dots, a_{2^n}$. Then $a_1^2 + a_2^2 + \dots + a_{2^n} = 2^n$, and from the statement proved above, we obtain the estimate $a_1 + a_2 + \dots + a_{2^n} \leq 2^n$, which is what we needed to prove.

As our reader A. Heiftz from Rostov-on-Don rightly replaced, problem M620 is a special case of the following promise by M. Klamkin (American Mathematical Monthly, 1975, 82, No. 8, p. 829-830):

Let $x_1, x_2, \dots, x_n$ be any real numbers. Then for $\lambda \geq 2$ and for $\lambda \leq 0$ the inequality holds

$$\sum |\pm x_1 \pm x_2 \pm \dots \pm x_n|^\lambda \geq 2^n \left( \sum_{i=1}^{n} x_i^2 \right)^{\lambda/2},$$

and for $0 < \lambda < 2$ - an inequality of the opposite meaning. (Summing arbitrary combinations of “+” and “-” signs on the left side.) We invite you to think about proving this statement yourself.

I. Klumova

M621. A p-wall is described around the circle. An arbitrary point $P$ inside a circle is connected to all its vertices and points of tangency. The resulting 2n triangles are surrounded by a variable in red and blue. Prove that the product of the areas of the red triangles is equal to the product of the areas of the blue triangles.

F623. Variable capacitor with initial em-bone $C_0$, charged to direction $U$, shorted to a resistor with resistance $R$ (see Fig.ok). How should the em-bone of condensate change over time?

◆ Let $A_1 A_2 \dots A_n$ be the circumscribed $n$-gon, $t_1, t_2, \dots, t_n$ be the lengths of the tangent segments drawn to the circle from the point of tangency by the segments, then the product $n$ of the lengths of the segments that fall in the blue triangle is equal to the product $n$ of the lengths of the segments that fall in the blue triangle. For the proof, it is enough to note $T_{k-1} T_k$, equal to the ratio of the areas of triangles $PT_{k-1} A_k$ and $PT_k A_k$.

◆ The current in the circuit is determined by the voltage across the resistor equal to the voltage across the capacitor: $I = U/R$. Since the current must be constant, the voltage on the capacitor must also be constant, that is

$$\frac{q_0}{C_0} = \frac{q_0 - \Delta q}{C},$$

⟦folio 28⟧

torus, so that there is current in the gap circuit? What power is developed by external forces, due to which the capacitance of the capacitor changes?

F624. In the process of the vessel, closed by a flat piston with a diameter of $D=5$ cm, there is a small amount of water (see figure). The diameter of the process is $d=2$ mm. If at a constant temperature $t=20^\circ C$ the piston is lowered by $H=10$ cm, then the water level in the process increases by $h=1$ mm. Find the saturated vapor pressure of water at temperature $t=20^\circ C$.

F625. The jet engine shown in figure is made from eggshells. The area of ​​the hole in the shell is $s=3\text{ mm}^2$. What is the maximum strength of this engine if the temperature of the water in the shell is maintained at $100^\circ C$?

Where $q_0$ is the initial charge of the capacitor, $\Delta q=It/R$ is the charge passed through the circuit during time $t$, $C$ is the capacitance of the capacitor at time $t$. From here

$$C = C_0 \left( 1 - \frac{\Delta q}{q_0} \right) = C_0 \left( 1 - \frac{t}{RC_0} \right).$$

To determine the power $N$ developed by external forces, we use the law of conservation and change of energy: the change in the energy of the system over time $t$ is equal to the equal to the external forces, that is

$$\left( \frac{CU^2}{2} - \frac{C_0U^2}{2} \right) + I^2Rt = Nt.$$

From here, taking into account the dependence of capacitance on time, we find the power of external forces:

$$N = \frac{U^2}{2R}.$$

P. Zubkov

◆

Since there is water in the process from the very beginning, the water vapor in the vessel is saturated. When the piston is lowered, its pressure does not change, and the weight of the vapor located in the “disappearing” volume

$$V = \pi D^2/4H,$$

condenses. The mass of condensed water is

$$m = \varrho p d^2/4h,$$

where $\varrho = 10^3 \text{ кг/m}^3$ is the density of water.

From the Mendeleev-Clapeyron equation, saturated steam is found:

$$p = \frac{m}{\mu} \frac{RT}{V} = \varrho \left( \frac{d}{D} \right)^2 \frac{h}{H} \frac{RT}{\mu} = 2,16 \text{ кПа.}$$

Sweeping. In the resulting formula, the quantities $d$ and $D$, $h$ and $H$ form dimensionless combinations. Consequently, the values ​​of these quantities can be substituted in any, but necessarily identical, units of measurement. For example, $d$ and $D$ are in millimeters, $a$ and $H$ are in centimeters. Provided that the remaining quantities ($\varrho$, $R$, $T$ and $\mu$) are expressed in SI units, the answer will be in pakaleh.

V. Belonukkin

◆

According to the law of conservation of momentum, the reactive force acting on the shell is equal in modulo to the difference in the momentum of the molecules flying out of the shell per unit time and flying into the shell in the same time. On the other hand, the pressure of a gas on a wall is nothing more than twice the momentum of molecules hitting a unit surface area of ​​the wall per unit time. Thus, the momentum of molecules emitted from a hole with an area of ​​$s$ per unit time is equal to $ps/2$, the momentum of emitted molecules is $p_0s/2$ (where $p$ and $p_0$ are the pressures inside and outside the shell, corresponding), and the desired force

$$F = \frac{ps}{2} - \frac{p_0s}{2} = (p - p_0) \frac{s}{2}.$$

The maximum pressure that can theoretically be obtained inside the shell is slightly greater than twice the atmospheric pressure. Indeed, if the water in the shell heats up so quickly that the air mass does not have time to change, the pressure will be the sum of the air pressure (which at $100^\circ C$ is slightly greater than atmospheric) and the pressure of saturated water vapor (which at $100^\circ C$ is equal to atmospheric). In this case

$$F_{\text{max}} = (p_{\text{max}} - p_0) \frac{s}{2} = p_0 \frac{T}{T_0} \frac{s}{2} \approx 0,2 \text{ H}.$$

⟦folio 30⟧

the tallow will cool quickly, but the soot will continue to remain hot. If the pan is cooled from the inside, the carbon will cool slowly, the temperature of the metal will have time to follow the temperature of the carbon and there will be practically no temperature difference.

Do forces promoting the separation of carbon deposits arise during slow cooling, that is, practically when the temperatures of the metal and carbon deposits are equal? Yes, since metal and carbon deposits have different coefficients of linear expansion. But it turns out that these forces are not sufficient to destroy the soot layer and separate it from the bottom of the pan.

L. Ashkinazi

F628. In a vertical tube $H=152$ cm long, sealed at the lower end, there is so much air $h=76$ cm high, locked in so much mercury (Fig. 1). The atmospheric pressure is $10^5$ Pa, and the temperature is $t_0=17^\circ$ C. To what temperature $t_1$ should the air in the tube be raised so that all the mercury is released?

Fig. 1.

Fig. 2.

The initial air pressure in the tube is the sum of the hydrostatic pressure of so much mercury with a height of $H-h=76$ cm and atmospheric pressure. Atmospheric pressure according to the condition is equal to $10^5$ Pa≈76 cm of mercury. Art. Thus, the initial air pressure in the tube is approximately equal to twice the atmospheric pressure.

We will assume that the mercury flows out slowly, so that the system at each moment can be considered to be in a state of equilibrium. In the final state, when almost all the mercury has flowed out, the air pressure in the tube will be equal to atmospheric pressure, that is, half the pressure. The air volume $HS$ (S is the cross-sectional area of ​​the tube) will be twice as large as the impudent volume $hS$. According to the ideal gas equation of state, this means that the temperature in the final state should be the same as in the initial one!

Of course, without increasing the temperature, mercury will not flow out of the tube at all. Therefore, the obtained result means that in order to answer the question of the problem, we limit ourselves to considering only the initial and final state, but we need to follow the entire process.

Let us find out how the temperature of the air in the tube must change so that the mercury is released gradually and at each moment of time the system can be considered to be in a state of equilibrium.

Let us denote the height of that much air at some point in time by $z$. Then the air pressure in the tube $p(z)$ is equal to

$$p(z) = p_0 + \rho g(H-z),$$

where $\rho$ is the density of mercury, and $p_0$ is atmospheric pressure, which, according to the conditions of the problem, is approximately equal to the pressure of so much mercury at height $H/2$:

$$p_0 = \rho g H/2.$$

Substituting (2) into (1), we get

$$p(z) = \rho g \left( \frac{3}{2} H-z \right).$$

Since we assume that the air in the tube is in a state of thermodynamic equilibrium at any $z$, then the pressure $p(z)$ of the air, the volume it occupies $Sz$ and the temperature $T(z)$ are related by the equation of state of an ideal gas:

$$\frac{p(z) Sz}{T(z)} = \frac{2 p_0 SH/2}{T_0},$$

where $T_0$ is the initial temperature, $2 p_0$ is the initial air pressure in the tube, $SH/2$ is the initial air volume. Substituting $p(z)$ from (3) and $p_0$ from (2) into (4), we find the dependence of the temperature on the height of the air in the tube:

$$T(z) = T_0 \frac{(3H-2z)z}{H^2}.$$

The graph of the function $T(z)$ is shown in figure 2. The process of mercury pouring out corresponds to the area with points $z=H/2$ and $z=H$, depicted by a solid linear line. It can be seen that for a slow (quasi-equilibrium) process the temperature should begin to rise to a value of $T_1=(9/8)T_0$ (in this case

⟦folio 31⟧

Fig. 3.

F629. A ball of mass m is suspended on a spring of stiffness k (spring magnet). The suspension point of the spring performs vertical harmonic oscillations with amplitude a and frequency $\omega$. How does the ball move during steady oscillations?

F630. An element of an atomic battery is a capacitor, on one of the plates of which a radioactive prenarate is applied, emitting α-particles at a speed of $v_0=2,2 \cdot 10^6$ m/s. Determine the emf of this element. The ratio of the charge of an α-particle to its mass is k=4.8 $\cdot 10^7$ C/kg.

half of the first amount of mercury will fly out), and then shrink to the initial value $T_0$. Therefore, to completely burn out the mercury, the air in the tube must be heated to a temperature of $T_1 \approx 326$ K. At this temperature, it is necessary to maintain contact with a heater having a temperature of $T_1$. Further, the mercury will be squeezed out, and this process will no longer be quasi-equilibrium.

To better understand this, it is useful to consider the process on the $p-V$-diagram (Fig. 3). The equilibrium process of mercury outflow corresponds to a linear dependence of the air pressure in the tube on z, described by formula (3) and shown as a solid line between the values ​​$z=H/2$ and $z=H$. This same figure shows images of the corresponding temperatures $T_0$ and $T_1$. The initial and final states lie on the same isotherm. It can be seen that at a temperature above $T_1$, not a single isotherm intersects the straight line $p(z)$, that is, equilibrium of the air in the tube is not possible at any value of the column height z. Therefore, if the air temperature is maintained at least above the value $T_1$, all the mercury will inevitably be pushed out of the air.

E. Butikov, A. Bykov, A. Kondratev

figure shows the position of the system at some point in time t. Point O is the equilibrium position of the suspension point; x is the deviation of the ball from the equilibrium position at which the length of the spring is equal to $l_0+mg/k$ ($l_0$ is the length of the spring in the unexpanded state).

Let's write down the equation of motion of the ball:

$$mg-k\Delta X=m\ddot{x}.$$

Substituting $\Delta X=\frac{mg}{k}+x+a\sin \omega t$ (full lengthening of the spring), we get:

$$m\ddot{x}+kx=-ka\sin \omega t.$$

Forced oscillations of the ball occur with the frequency of the forced force, that is, with the frequency $\omega$. In the steady state, there are no natural oscillations, the frequency of which is $\omega_0=\sqrt{k/m}$.

We will look for solution (1) in the form

$$x=A\sin \omega t+B\cos \omega t,$$

where A and B are some constant coefficients that need to be determined. Taking an arbitrary one from (2) twice and substituting (2) into (1), we get:

$$(-A\omega^2 m+kA)\sin \omega t+(-B\omega^2 m\cos \omega t+kB)\cos \omega t$$

$$=-ka\sin \omega t.$$

This equality must hold at any point in time.

Taking $t_1=0$ and $t_2=\pi/2\omega$, we find $B=0$, $A=\frac{ka}{\omega^2 m-k}=\frac{a}{\omega^2-\omega^2}=1$.

Substituting the found values ​​of A and B into (2), we obtain:

$$x=\frac{a\sin \omega t}{\omega^2-\omega^2}-1.$$

A. Zilberman

The electromotive force of the source is equal to the ratio of the work done by external forces to move a charge along the circuit to the magnitude of this charge. The maximum EMF will be when α-particles no longer reach the opposite plate of the capacitor. In other words, when the work of the force side is equal to the kinetic energy of the emitted α-particles:

$$\mathcal{E}=\frac{mv_0^2}{2q}=\frac{v_0^2}{2k}\approx 5 \cdot 10^5 \text{ B}=500 \text{ kB}.$$

A. Grizorenko, 10th grade student, Makeev, Donetsk region.
