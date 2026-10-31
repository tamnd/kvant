---
id: 1972-9-resheniya-69f4a9d0
issue: kvant_1972_9
year: 1972
number: "9"
title: Solutions to problems M123—M125; F138—F142
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 41
page_last: 46
page_labels: 39-44
tag: ACHD
lang: en
source: kvant_digital
extraction: vision
content_sha256: 8f03fc812712958749b9130b7a19cc50c12fea9d7d85d9fbebeffe18d6a4e40d
prompt_sha256: draft-1
translated_from: content/ru/1972/09/articles/11_resheniya-69f4a9d0.md
source_content_sha256: 9f82188341c5205e25ba96b1ba57d7a605b16a610030bba3230c64793594f5d1
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 39⟧

SOLUTIONS

In this issue we publish solutions to problems M123—M125

M123
Find all natural numbers m for which
$$1! \cdot 3! \cdot 5! \dots (2m-1)! = \frac{m(m+1)}{2}!$$
(n! denotes the product 1·2…·n).

The solutions to the equation are the numbers 1, 2, 3, 4. This is easy to verify by simple substitution. Let us prove that there are no other solutions. (This problem, number 76, was published in the collection “Mathematical Education” No. 4 for 1935; at that time no reader was able to find “convincing proof that the equation has no other solutions” - this was written in No. 8 of this collection for 1936). The simple proof that we propose is based on the following theorem (“Bertrand’s procedure”, which I talk about in «Kvant» No. 5 for 1971 and No. 5 for 1972): between the numbers a and 2a, where a>1, there is always at least one prime number.

Let p be a prime number between 2x-1 and 2(2x-1). If the equation were true
$$2(2x-1) < \frac{x(x+1)}{2},$$
it turns out that the number p is included in the prime factorization of the right side of the equation, since it is less than $\frac{x(x+1)}{2}$, and at the same time cannot be included in the expansion of the left side, since it is greater than (2x-1). And this, according to the theorem on the uniqueness of decomposition into prime factors, is impossible. Therefore it is obligatory
$$2(2x-1) \geq \frac{x(x+1)}{2}.$$

From this inequality it turns out that x≤6. But x=5 and x=6, as is easy to see, do not satisfy the equation.

V. P. Beshkarev

M124
Given triangle ABC. Find a point O inside it that has the following property: for any line passing through the point O and the intersecting line of the triangle AB at the point K and BC at the point L, the equality holds
$$\frac{AK}{KB} + \frac{CL}{LB} = 1.$$

In general, prove that if p and q are an arbitrary given positive number, then inside the triangle ABC you can also indicate a point O, that for any line KL passing through this point (K lies on AB, L on BC),

$$p \frac{AK}{KB} + q \frac{CL}{LB} = 1.$$

The easiest way to solve this problem is to use the concept of center of gravity*).

*) See the article by B. Yu. Kogan “Physics helps geometry”, «Kvant» No. 5, 1971 and the book by M. B. Balk “Geometric applications on the center of gravity”, Fizmatlit, 1959.

⟦folio 40⟧

In our proof, we will use the following property of the center of gravity: if in a system of $n$ weights $p_1, p_2, \dots, p_n$ two weights $p_1$ and $p_2$ are replaced by a weight $p=p_1+p_2$ placed at their center of gravity, then the position of the center of gravity of the system will not change (statements that follow from this property are highlighted in bold).

Let us place unit weights $a, b$ and $c$ at the vertices $A, B$ and $C$ of the triangle. then the center of gravity $O$ of weights $a, b$ and $c$ is the intersection point of the medians. Let us now take the point $K$ on the side $AB$, for which $\frac{AK}{KB} \leq 1$, and represent the weight $b$ as the sum of two weights: $b_1 = \frac{AK}{KB}$ and $b_2 = 1 - \frac{AK}{KB}$. The center of gravity of weights $a$ and $b_1$ is at point $K$. then $L$ is the center of gravity of weights $c$ and $b_2$, then $\frac{CL}{LB} = 1 - \frac{AK}{KB}$, and the center of gravity $O$ of weights $a, b$ and $c$ lies on the straight line $KL$. Therefore, for any line passing through the point $O$ and intersecting the sides $AB$ and $BC$, the first equality holds.

It is similarly proven that if $O'$ is the center of gravity of the weights $a=p, b=1$ and $c=q$, then for any line passing through the point $O'$ and intersecting the sides $AB$ and $BC$ of the triangle, the second equality holds. Indeed, let us take a point $K$ on the side $AB$, for which $\frac{AK}{KB} \leq \frac{i}{p}$, and represent the weight $b$ as the sum of two weights $b_1 = p\frac{AK}{KB}$ and $b_2 = 1 - p\frac{AK}{KB}$. then $L$ is the center of gravity of weights $b_2$ and $c$, then $1 - p\frac{AK}{KB} = q\frac{CL}{LB}$, and points $O'$, $K$ and $L$ lie on the same straight line.

The proof is legal.

A similar solution to the problem was sent to us by F. Schmiedel from Moscow.

L. G. Makarov

M125

a) Is there an infinite sequence of natural numbers with the following property:

None of these numbers is divisible, but among each three numbers you can choose two, the sum of which is divisible by the third?

b) If not, how many numbers could there be in a set that have this property?

b) Solve the same problem with the additional condition: only odd numbers are allowed to be included in the set.

Here is one example of such a set of four numbers: 3, 5, 7, 107. Here, among the three numbers 3, 5, 7, the sum 5+7 is divisible by 3; in the triple 5, 7, 107, the sum 107+5 is divided by 7; in the triple 3, 7, 107, the sum 7+107 is divided by 3; finally, in the triple 3, 5, 107, the sum 3+107 is divided by 5.

Let's solve problem b) first.

To the sequence of four numbers 3, 5, 7, 107 given in the condition, you can add five numbers 10693: 10693+5 is divisible by 3, 10693+3 is divisible by 7, 10693+7 is divisible by 5, 10693+107 is divisible by 3 and 5, 10693+7 is divisible by 107.

Let us show that from six odd numbers we can form a sequence that satisfies the conditions of the problem. Let $a_1, a_2, a_3, a_4, a_5, a_6$ be odd numbers such that none of them is divisible by the other, but among any three we can choose two whose sum is divisible by the third.

Let's make some preliminary values.

1. If $a, b, c$ are three numbers in our sequence, $a>b>c$, then $b+c$ is not divisible by $a$.

Indeed, $b+c<2a$ and $b+c\neq a$, since $a$ is an odd number.

2. If $a, b$ are two numbers in our sequence, $a>b$, then $a+b$ is divisible by all numbers in the sequence less than $b$, except perhaps one.

Indeed, if $a+b$ is not divisible by two numbers $c$ and $d$, less than $b$, then $a+c$ and $a+d$ are divisible by $b$, but then $c-d$ is also divisible by $b$, which is impossible.

3. If $a, b, c$ are the even numbers of our sequence, $a+b$ and $a+c$ are divisible by $d$, then $b+c$ is not divisible by $d$.

Indeed, since $a+b$ and $a+c$ are divisible by $d$, then $2a+(b+c)$ is divisible by $d$, while $2a$ is not divisible by $d$ (d is an odd number and $a$ is not divisible by $d$).

Let $a_1>a_2>a_3$ be the three most of the six numbers $a_1, a_2, \dots, a_6$.

Which of the numbers $a_1+a_2, a_1+a_3, a_2+a_3$, according to Remark 2, is divisible by at least two of the numbers $a_4, a_5, a_6$. At the same time, Remark 3 shows that these numbers do not have a common divisor among the numbers $a_4, a_5, a_6$. Therefore, each of the numbers $a_1+a_2, a_1+a_3, a_2+a_3$ is divisible by two of the numbers $a_4, a_5, a_6$ and not divisible by the third.

Let

$a_1+a_2$ is divisible by $a_4$ and $a_5$ and not divisible by $a_6$;
$a_1+a_3$ is divisible by $a_4$ and $a_6$ and not divisible by $a_5$;
$a_2+a_3$ is divisible by $a_5$ and $a_6$ and not divisible by $a_4$.

Then the numbers $a_1+a_5$ and $a_2+a_4$ are divisible by $a_3$. Therefore, the number $(a_1+a_2)+(a_4+a_5)$ is also divisible by $a_3$.

At the same time, $a_1+a_2$ is divisible by three of the numbers $a_3, a_4, a_5, a_6$, and since $a_1+a_2$ is not divisible by $a_6$, then $a_1+a_2$ is divisible by $a_3$, whence it follows that $a_4+a_5$ is divisible by $a_3$. We received a contradiction with remark 1.

Thus, a sequence of odd numbers with the intersuccess property can consist of at most five numbers, problem b) is solved.

If a sequence consists of only four numbers, then, without violating the conditions, we can divide them all by 2. We will therefore assume that there are odd numbers in the sequence.

⟦folio 41⟧

Due to problem c) there are no more than five of them.

Remarks 1–3 are now valid under some additional assumptions.

Remark 1 requires that $a$ not equal $b+c$; 2 is valid if the number $a$ is not equal to the sum of the lower two terms of the sequence, and 3 is valid if $d$ is an odd number.

If the terms of the sequence $a, b, c$ are even and $d$ is odd, then the numbers $a+d, b+d$ and $c+d$ are not divisible by either $a$, $b$, or $c$. Therefore, the numbers $a+b, a+c$ and $b+c$ are divisible by $d$, which contradicts Remark 3.

Thus, there are at most two even numbers in our sequence. Let there be two of them: $a$ and $b$ ($a>b$). then the number $a+b$ is divisible by all odd terms of the sequence and, therefore, the number $a$ is the most in the sequence.

If the number $a$ is not equal to the sum of the lower sequences, then, discarding the number $b$, we obtain a sequence for which Remarks 1, 2, 3 are valid without any restrictions. The solution to problems c) shows that in such a sequence there are no more than five terms, that is, in the original sequence there are no more than two even numbers. Let there be two of them: $a$ and $b$ ($a>b$). then the number $a+b$ is divisible by all odd terms of the sequence and, therefore, the number $a$ is the most in the sequence.

An astronaut weighing 100 kg is in a spacecraft whose mass is 5 m, on a halyard 64 m long. Starting to tighten the halyard if the ship is between the astronaut and the Earth on the line connecting their centers of gravity.

When calculating, assume that the ship is moving in a circular orbit, the height of which from the Earth’s surface is negligible compared to the radius of the Earth ($R=6400$ km).

There are two forces acting on the spaceship: the gravitational force towards the Earth $F_1=\gamma \frac{MM_3}{R_1^2}$ ($M$ is the mass of the ship, $M_3$ is the mass of the Earth,

$$R_1 = \text{radius of koraбля, } \gamma = \text{gravitation constant}$$
and the halyard tension force is $T$ (Fig. 1). Under the influence of these forces, the ship moves in a circle. If the angular velocity of the ship is equal to $\omega$, then the ship moves with a centripetal acceleration $a_1=\omega^2R_1$, which is imparted to it by the resultant forces $F_1$ and $T$. According to Newton's second law $F_1-T=M\omega^2R_1$, or

$$\gamma \frac{MM_3}{R_1^2}-T=M\omega^2R_1.$$

Let's consider the forces acting on space. This is the tension force of the halyard $T$ and the force of gravity of space towards the Earth

$$F_2=\gamma \frac{MM_3}{R_2^2},$$

where $m$ is the mass of space, $R_2$ is the radius of its orbit. Under the influence of these forces, the ship moves in a circle of radius $R_2$, with an angular velocity $\omega$, that is, with a centripetal acceleration $a_2=\omega^2R_2$. Since both forces acting on space are directed towards the center of the Earth, then $F_2+T=m\omega^2R_2$, or

$$\gamma \frac{MM_3}{R_2^2}+T=m\omega^2R_2.$$

⟦folio 42⟧

Eliminating w from equations (1) and (2), we obtain

$$\left( \gamma \frac{MM_3}{R_1^2} - T \right) \frac{1}{MR_1} =$$

$$= \left( \gamma \frac{mM_3}{R_2^2} + T \right) \frac{1}{mR_2},$$

or

$$\gamma M_3 \frac{R_2^3 - R_1^3}{R_1^2 R_2^2} = T \frac{mR_2 + mR_1}{mM}.$$

(3)

But $R_2 \approx R_1 \approx R$ and therefore:

$$R_1 R_2 \approx R^2,$$

$$R_2^3 - R_1^3 = (R_2 - R_1) (R_2^2 + R_1^2 + R_1 R_2) \approx 3lR^2$$

(l is the length of the halyard),

$$mR_2 + MR_1 = (m + M) R.$$

This means that equality (3) can be written as follows:

$$3\gamma \frac{M_3}{R^2} l = TR \frac{m + M}{mM}.$$

From here we get:

$$T = 3\gamma \frac{M_3}{R^2} \frac{l}{R} \frac{mM}{m + M}.$$

If a body of mass $m$ is on the surface of the Earth, then it is affected by force $F = \gamma \frac{mM_3}{R^2} = mg$. This means that the acceleration $g$ of free fall is equal to the value $\gamma \frac{M_3}{R^2}$. Therefore, we can rewrite the expression for the tension force of the halyard as follows:

$$T = 3 \frac{l}{R} \frac{mM}{m + M} g.$$

Substituting the numerical values ​​$R, g, m$ and $M$ into this formula, we find

$$T \approx 0,03n.$$

F139

The football player hit the ball, giving it speed $v$ at an angle $\alpha$ to the horizon, and hit the bottom corner of the ball. If a football player hit the ball in the same place on the football field and the ball flew at the same angle to the horizon, but with a speed 5% greater than the speed $v$, then it would hit the upper horizon. Find the speed with which the ball begins to move if the height of the ball is $h = 2m$ and the angle is $\alpha = 30^\circ$.

Let's write down the kinematic equations of the ball's motion. Horizontally - along the $X$ axis, the ball moves uniformly at a speed $v_1 = v \cos \alpha$ (Fig. 2); its coordinate $x$ changes with time according to the law

$$x = vt \cos \alpha.$$

Along the $Y$ axis (vertically), the ball moves with uniform acceleration $g$, directed downwards. That's why

$$y = vt \sin \alpha - \frac{gt^2}{2}.$$

At the moment $t_0$ falls to the ground $y = 0$ and $x = l$, where $l$ is the flight range of the ball. That's why

$$l = vt_0 \cos \alpha,$$

$$0 = vt_0 \sin \alpha - \frac{gt^2}{2}.$$

If the ball began to move at a speed 5% greater than the speed $v$, that is, at a speed of 1.05 $v$, then its coordinates $x$ and $y$ would change over time as follows:

$$x = 1,05 vt \cos \alpha$$

and $$y = 1,05 vt \sin \alpha - \frac{gt^2}{2}.$$

At the moment of impact of the ball on the upper surface of the vertical, its coordinate $x$ would be equal to $l$, and the coordinate $y$ would be equal to the height of the vertical $h$. Therefore, at the moment $t_1$ of hitting the shield, the

$$l = 1,05 vt_1 \cos \alpha,$$

$$h = 1,05 vt_1 \sin \alpha - \frac{gt_1^2}{2}.$$

Let us now solve the system of equations (1) - (4). From equation (2) it is not difficult to find the flight time $t_0$ of the ball in the first case. Since $t_0 \neq 0$, then dividing this equation by $t_0$, we find:

$$t_0 = \frac{2v \sin \alpha}{g}.$$

Next, dividing equation (3) by equation (1), we obtain:

$$1 = 1,05 \frac{t_1}{t_0}.$$

From here

$$t_1 = \frac{t_0}{1,05} = \frac{2v \sin \alpha}{1,05g}.$$

Now, substituting the expression for $t_1$ into equation (4), we find

$$v = \sqrt{\frac{gh}{0,2 \sin^2 \alpha}}.$$

⟦folio 43⟧

F140

Will other barometers give correct quality readings if part of the tube (below the level of the tubes) is made of very soft rubber?

The pressure above the level of the pipes in a barometric tube is negligible compared to the atmospheric pressure - this is the pressure of the saturated vapor of the pipes. Therefore, we can consider it equal to zero. At the level of the tube in the cup, the pressure in the barometric tube is equal to the atmospheric pressure. Consequently, regardless of the diameter of the barometric tube and how its diameter changes with height, the height of the tube table is balanced by atmospheric pressure $p_0$:

$$p_0 = \rho g H$$

(ρ is the density of the pipes).

This means that the barometer will give correct readings.

It is interesting to find out what will happen to the rubber tube, what its shape will be. Since the pressure outside the tube is equal to atmospheric pressure, and the pressure inside the tube is equal to $\rho g h$, that is, less than atmospheric pressure (atmospheric pressure is equal to the values ​​$\rho g H$, and $H > h$), the tube will collapse, as shown in figure 3.

F141

Three wires have been removed from the “black box” containing an unknown electrical circuit. Two of them are connected to ground and then the current induce through the third wire is dependent on the potential difference between the end of this wire and the ground. Connecting different pairs of pins to ground, graphs are drawn for three possible options for switching on the circuit. These graphs are shown at figure 4. The current is considered positive if it goes “to the box”, and imprinted otherwise. Come up with a simple diagram of the contents of the “black box” and determine its parameters.

Consider the graphs of voltage versus current shown in figure 4. From the first graph it follows that the current between pin 1 and closed pins 2 and 3 is zero when the voltage of the external source is - 38. This is only possible if a current source (or sources) is (or are) switched on between pins 1 and 2 or between pins 1 and 3.

From the second graph it is clear that between points 2 and 3 and between points 2 and 1 there can only be resistance. Only in this case, the current between pin 2 and the connected pins 3 and 1 will be zero at $U = 0$.

From the third graph it follows that inside the box there is a source that includes either between points 3 and 1, or between points 3 and 2 (and possibly both).

⟦folio 44⟧

Fig. 5.

The circuit of the internal “black box” can be as shown in figure 5. Let us determine the parameters of this circuit.

From Ohm's law for the circuit section $U=IR$ it follows that the change in the potential difference at the ends of the circuit section is associated with a change in the current through the section according to

$$\Delta U = R \Delta I.$$

This means that the resistance of the circuit section is equal to

$$R = \frac{\Delta U}{\Delta I},$$

that is, equal in magnitude to the tangent of the slope of the drain voltage dependence graph.

In the first case, when pins 2 and 3 are replaced, the contents of the “box”, when the voltage $U$ of the external source changes, should behave like two parallel resistances $R_1$ and $R_2$, the total resistance of which is $2/3$ ohms. That's why

$$\frac{R_1 R_2}{R_1 + R_2} = \frac{2}{3}$$

(Resistances $R_1$ and $R_2$ must be expressed in ohms).

In addition, we know that the current in the external circuit is zero when $U=3\theta$. This means that when the current is zero and the internal box circuit is not connected to the source, the voltage drop across the resistance $R_2$ is 3 $\theta$. But in this case, resistances $R_1$ and $R_2$ are connected in series with the source, therefore, the current through them is equal to $\frac{E}{R_1 + R_2}$ and the voltage drop across resistance $R_2$ is equal

$$\frac{R_2 E}{R_1 + R_2} = 3(\theta).$$

In the second case, the inside of the box should behave like two resistances $R_2$ and $R_3$ connected in parallel, the total resistance of which is 6 ohms. That's why

$$\frac{R_2 R_3}{R_2 + R_3} = 6(om).$$

In the third case, parallel-connected resistances $R_1$ and $R_3$ are “connected” to an external source, their total resistance is 2 ohms:

$$\frac{R_1 R_3}{R_1 + R_3} = 2(om).$$

Moreover, since in this case the current is zero at $U=4\theta$, then

$$\frac{R_3 E}{R_1 + R_3} = 4(\theta).$$

We received a system of 5 equations with 4 unknowns: $R_1, R_2, R_3$ and $E$. Let's check if it's compatible. Dividing equation (1) by equation (2), we find:

$$\frac{E}{R_1} = 2(\theta/om).$$

Similarly, dividing equation (4) by equation (5), we obtain exactly the same correspondence between $E$ and $R_1$. This means that our system is cooperative.

Let us now find the resistances $R_1, R_2$ and $R_3$. To do this, we need to solve a system of three equations (1), (3) and (4). First, let’s cross it over, “turn over” each of the equations:

$$\frac{R_1 + R_2}{R_1 R_2} = \frac{3}{2},$$ or $$\frac{1}{R_1} + \frac{1}{R_2} = \frac{3}{2},$$

$$\frac{R_2 + R_3}{R_2 R_3} = \frac{1}{6},$$ or $$\frac{1}{R_2} + \frac{1}{R_3} = \frac{1}{6},$$

$$\frac{R_1 + R_3}{R_1 R_3} = \frac{1}{2},$$ or $$\frac{1}{R_1} + \frac{1}{R_3} = \frac{1}{2}.$$

Taking $\frac{1}{R_1}, \frac{1}{R_2}$ and $\frac{1}{R_3}$ as new unknowns and solving the resulting system, we find:

$$\frac{1}{R_1} = \frac{1}{2}, \frac{1}{R_2} = \frac{1}{6} \text{ и } \frac{1}{R_3} = 0.$$

It follows that

$$R_1 = 2 \text{ ом}, R_2 = 6 \text{ ом}, R_3 = \infty \text{ и } E = 4 \text{ e}.$$

I. Sh. Slovodechkiy
