---
id: 1991-4-resheniya-zadach-m1251-m1255-f1263-f1267-94c0f3df
issue: kvant_1991_4
year: 1991
number: "4"
title: Solutions to problems M1251—M1255; F1263—F1267
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 27
page_last: 35
page_labels: 25-33
lang: en
source: kvant_digital
extraction: vision
content_sha256: f5266f33a19c4372f1f8fc26c81db9be5c833ba6b0bc5eb5d31ef5c74c4cc3f3
prompt_sha256: draft-1
translated_from: content/ru/1991/04/articles/10_resheniya-zadach-m1251-m1255-f1263-f1267-94c0f3df.md
source_content_sha256: da0b1849cf8b7003667a887d40b24ab118effeb6f18e667e98bd1515c32baa46
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 25⟧

Problem solutions
M1251 — M1255, F1263 — F1267

Answer: the required point $M$ lies on the bissertrix of the angle, and $AM=AP=AQ$ (A is the vertex of the angle; Fig. 1) - these conditions allow us to construct $M$ in a very special way.

We will start with arbitrary points $M$, $P$ and $Q$, for which the sum $PM+MQ$ is given, and in several steps we will move them so that we get the location indicated in the answer, and the area $APMQ$ will increase at each step (more precisely, not decrease).

1°. Let's replace the quadrilateral $APMQ$ and make it convex (if it is initially small).

To do this, replace $M$ with the point $M'$, symmetrically $M$ relative to the middle of the segment $PQ$. It is clear that $M'$ lies inside the angle (and even inside the parallelogram $APA'Q$; Fig. 2), $PM+MQ=PM'+M'Q$, and the area of ​​the quadrilateral increases.

2°. Fix $\Delta PQM$ and move it inside the corner so that $AP=AQ$.

It is more convenient to divide not the triangle, but the vertex of the angle $A$, preserving its values, i.e. along the arc of the circle $PAQ$ (Fig. 3). Area $\Delta APQ$ becomes most important.

3°. Let us move $M$ parallel to $PQ$ to the bissertrix of angle $A$ and subject the entire figure to preparation from the center

⟦folio 26⟧

---
running_head:
folio:
---

rum $A$ so that the given value of the sum $PM + MQ$ (Fig. 4) is restored.

With a shift $M$, the area $APMQ$ does not change, but the sum of the distances $PM$ and $MQ$, generally speaking, will decrease. (Recall that the smallest value of $PM + MQ$ for points $M$ on a given line $m$ is achieved when $PM$ and $MQ$ make equal angles $c$ $m$, since $PM + MQ = P'M + MQ$, where point $P'$ is symmetrical $P$ relative to $m$.) Consequently, with subsequent homothety of area $APMQ$ can only increase.

It remains to note that the “deltoid” $APMQ$ obtained after step $3^0$ consists of two equal triangles $APM$ and $AQM$, in which the base: $PM = QM = (PM + QM)/2$ and the angle at the vertex: $\angle PAM = \angle QAM = \angle A/2$ are known. And we have already seen (step $2^0$) that under these conditions the area of ​​the triangle is maximum when it is equilateral, i.e. when $AP = AM = AQ$.

N. Vasiliev, V. Senderov

M1252. Let $a$ and $n$ be natural numbers. Prove that the number of proper irreducible fractions with value $a^n - 1$ is divisible by $n$.

Let $x = x_n x_{n-1} \dots x_1$ be a record of the number $x < a^n - 1$ in the number system in base $a$, i.e. $x = x_n \cdot a^{n-1} + x_{n-1} \cdot a^{n-2} + \dots + x_1 \cdot a^0$, where $0 \leqslant x_i \leqslant a-1$, $i=1, \dots, n$ (the record may start with zeros). Let us show that if $x$ is coprime with the number $A = a^n - 1$, then all numbers obtained by cyclic permutations of digits in the $a$-ary notation $x$) are coprime with $A$ and $2$) are different. (It follows from this that all such numbers are divided into non-intersecting groups of $n$ pieces each, which means their number is divisible by $n$.)
1) Let's check that when rearranging the first $a$-ary digit $x_n$ of the number $x$ to the end of the word, the result is mutually simple with $A$ the number:
$$x_{n-1} \dots x_1 x_n = x_n x_{n-1} \dots x_1 0 - x_1 0 \dots 00 + x_1 = ax - x_1 (a^n - 1) = ax - Ax_1$$
this number is mutually prime with $A$, since $a$ and $x$ are mutually prime with $A$.
2) Let us assume that with some cyclic rearrangement of digits the original number $x$ was obtained, i.e.

⟦folio 27⟧

---
running_head:
folio:
---

$$x = x_n \dots x_1 = x_k x_{k-1} \dots x_1 x_n \dots x_{k+1}.$$

Then
$$x(a^k - 1) = x_k \dots x_1 x_n \dots x_{k+1} \cdot a^k - x_n \dots x_1 = x_k \dots x_1 \cdot a^n - x_k \dots x_1 = x_k \dots x_1 \cdot A.$$

But $x$ and $A$ are coprime, therefore, $a^k - 1$ is divisible by $A = a^n - 1$, i.e. $k = n$, and our permutation is the same. (It is possible to show in an unrepresentative way that if the notation $x$ transforms into itself during an unexpected cyclic permutation, then it consists of a group of digits repeated several times, and then $x$, very/no, is not coprime with $a^n - 1 = (a - 1) \cdot 11 \dots 1.$)

K. Kokhas

M1253*. A convex polygon $M$ is drawn on the plane, divided into several convex polygons - a “map” of several “countries”. We will say that such a map is realized in space if it is a projection of a “convex cap,” that is, if there is a convex polygon in which one of the faces is $M$, and the projection of the remaining faces onto the plane of face $M$ is the country of this map (and, perhaps, sides $M$).
a) Construct an example of a map from triangles that do not allow implementation in space.
Prove that the map admits a convex implementation in each of the following services:
b) all countries are acute triangles, b) each country is an inscribed polygon containing the center of a circumscribed circle within itself.

M1254. A rectangle of $m \times n$ cells is drawn on checkered paper,

The formulation of problem M1253 raised some unanswered questions among some readers. Here is a more precise formulation; The deadline for sending decisions continues until June 15, 1991.

(This formulation can be understood to mean that the edges of the “cap” are adjacent to the sides of the polygon, that is, the polyhedron does not have “vertical” side faces; in this case, statement 6) and c) are very/no incorrect. However, it would be interesting to obtain necessary or sufficient conditions for “realizability” in this narrower sense.)

⟦folio 28⟧

---
running_head:
folio:
---

$m \ge n > 1$. Prove that it can be cut into figures of four cells in the shape of the letter L if and only if mn is divisible by 8.

cut into L-shaped shapes from 4 cells. Then the number of these figures is $N = mn/4$. However, among numbers - say, the number of rows $m$ is even. Let's color the lines alternately white and black. Each figure D of 4 cells contains either one or three black cells. Since the total number of black cells $mn/2 = 2N$ is even, then the number $N$ figure must be even (otherwise the sum of $N$ terms equal to 1 or 3 would be odd). Since $mn/4$ is even, mn is divisible by 8.

To prove it in essence, you just need to make sure that you can cut the rectangle $3 \times 8$ (see Fig.ok). The fact is that any rectangle of the form $8k \times n$, where $n$ is odd, can be composed of rectangles $3 \times 8$ and $2 \times 4$, and a rectangle $m \times n$, where $m$ and $n$ are even, can be divided into rectangles $2 \times 4$. The latter, obviously, are cut into two “letters G”.

N. Vasiliev, V. Ginzburg

M1255. Let $h$ be the smallest height of the tetrahedron, $d$ be the smallest distance between its two crossing edges. Prove inequalities $1/2 < d/h < 3/2$.

Consider a parallelepid described around a given tetrahedron $T$, as shown in Fig.ok 1. The heights $h_i$ ($i = 1, 2, 3, 4$) of the tetrahedron and the distances $d_k$ ($k = 1, 2, 3$) between its opposite edges can be expressed in terms of the volume $V$ of the parallelepid, the areas of its faces and the area faces of the tetrahedron. Indeed, the quantities $d_k$ are the heights of the parallelepid, therefore $V = d_k \cdot S_k$, where $S_k$ are the areas of its corresponding faces. On the other hand, the $T$ tetrahedron is obtained from a parallelepid by cutting off four tetrahedra, each of which obviously has a volume of $V/6$. Consequently, the volume of the tetrahedron is equal to $(1 - 4/6)V = V/3$, and therefore $V = h_i \cdot s_i$, where $s_i$ is the area of ​​the tetrahedron face perpendicular to the height $h_i$, $i = 1, 2, 3, 4$. So,

$$h_i = V/s_i, \quad d_k = V/S_k.$$

Let, for the purpose of definition, $h_1 = h$ and $d_1 = d$ be the smallest of the quantities $h_i$ and $d_k$, respectively. Consider the one of the four tetrahedra complementary to $T$ along the area face $s_1$. The areas of its three other faces are equal to $S_1/2, S_2/2$ and $S_3/2$ and their sum is greater than $s_1$, since their projections onto the face $s_1$ completely cover it:

$$s_1 < (S_1 + S_2 + S_3)/2 \leq 3S_1/2$$

($S_1$ is the smallest of the areas $S_k$). From here

$$d_1 < 3h_1/2.$$

Let us now prove that

$$2S_1 < (s_1 + s_2 + s_3 + s_4),$$

from here it will follow that $S_1 < 2s_1$ ($s_1$ is the smallest of the areas $s_i$), i.e., that $h_1 < 2d_1$. To do this, consider the outline of a tetrahedron by a plane parallel to

⟦folio 29⟧

---
running_head:
folio:
---

new grime of area $S_1$ parallelepiped and equal-
distant from them (Fig. 1, 2). It's easy to see what it is
parallelogram $\Pi$ whose sides are parallel
diagonals of these faces and half as long as them. That's why
its area adb is $S_1/2$. Now let's look at four
coal paramid with the top in the center of one of
these faces and the base $\Pi$ (Fig. 2). The areas of its lateral faces are obviously equal to $s_i/4$, $i=1, 2, 3, 4$, and their sum is greater than the area of ​​the base, i.e.

$$S_1/2 < (s_1 + s_2 + s_3 + s_4)/4,$$

Q.E.D.

The proven inequalities for areas can be calculated
lead from the equalities connecting the vectors $\bar{s}_1, \bar{s}_2, \bar{s}_3, \bar{s}_4$, equal in length to the areas $s_i$ of the faces of the tetrahedron, redistributive corresponding to the faces and on-
ruled outside the tetrahedron, and similar vectors
$S_1, \bar{s}_2, \bar{s}_3, \bar{s}_4 = -\bar{s}_1, S_5 = -\bar{s}_2, \bar{s}_6 = -\bar{s}_3$ for parallelepiped. Namely, if the faces of the tetrahedron and para-
llelepiped are numbered so that the common edge is $i$th and
The 4th face of the tetrahedron is the diagonal of the $i$ face
parallelepiped ($i=1, 2, 3$), then $\bar{s}_i + \bar{s}_4 = \bar{s}_i$. (Prove this by considering the orthogonal projection along
this edge.) From here, in particular, it follows that
$$S_1 < s_1 + s_4$$ and, similarly, $S_4 = S_1 < s_2 + s_3$, i.e.
$$S_1 < (s_1 + s_2 + s_3 + s_4)/2.$$

On the other hand, adding the three equalities $\bar{s}_i + \bar{s}_4 = \bar{s}_i$ and taking into account that $\bar{s}_1 + \bar{s}_4 + \bar{s}_2 + \bar{s}_3 = \bar{S}_1 + \bar{S}_4 = 0$, we get: $2\bar{s}_1 = \bar{S}_1 + \bar{S}_2 + \bar{S}_3$. This
equality gives the estimate $s_1 < (S_1 + S_2 + S_3) 2$.

V. Dubrovsky, A. Skopenkov

F1263. As a rocket accelerates, its mass decreases. At what rocket speed will its kinetic energy be maximum if fuel consumption is constant? The speed of gases relative to the rocket is $v_0$, the initial speed of the rocket is zero. Razzon is produced far from the Earth, so the influence of gravity can be neglected.

At the moment when the kinetic energy of the rocket $E_k = Mv/2$, where $M$ is the mass, $v$ is the rocket speed, is maximum, its time derivative is equal to zero:

$$E_k' = \frac{1}{2}(M \cdot v^2)' = \frac{1}{2}M' \cdot v^2 + \frac{1}{2}M \cdot 2vv' = 0,$$

or

$$v = -2\frac{M}{M'}v' = 2\frac{M}{M'}v'.$$

Since $M' = \mu$ is the fuel consumption, which by condition is constant, we find that the speed of the rocket $v$, corresponding to its maximum kinetic energy, depends on the acceleration of the rocket $a = v'$ at this moment in time. Let's find him.

Let's choose a very short time interval $\Delta t$ and write the law of conservation of momentum (see figure):

$$\mu \Delta t(v - v_0) + (M - \mu \Delta t)(v + \Delta v) = Mv.$$

After several transformations, taking into account that $\mu \Delta t \ll M$, we obtain

$$a = \frac{\Delta v}{\Delta t} = \frac{\mu}{M}v_0.$$

⟦folio 30⟧

---
running_head:
folio:
---

Thus, the required speed is equal to
$$= 2 \frac{M}{\mu} v' = 2 v_0.$$
D. Alexandrov

F1264. Calculate the diameter, mass and length of the tungsten filament of a 220 V, 100 W light bulb. Working temperature of the filament is 2700 °C. At this temperature, the resistivity of tungsten is $\rho = 90 \cdot 10^{-6}$ Ohm cm, and the radiation power per unit surface of the thread is $W = 153$ W/cm². The density of tungsten is 19 times the density of water. Consider that the thread is made from round wire.

Let the thread have radius $R$ and length $l$. Then her resistance
$$r = \rho \frac{l}{S} = \rho \frac{l}{\pi R^2}.$$
On the other hand, the power of the light bulb is $P = U^2/r$, whence
$$r = \frac{U^2}{P}.$$
Thus, we obtain the correspondence
$$\frac{U^2}{P} = \rho \frac{l}{\pi R^2}.$$ (1)
All power is radiated from the surface of the filament, so
$$P = W 2 \pi R l.$$ (2)
Dividing correspondence (1) by correspondence (2), we find
$$\frac{U^2}{P^2} = \frac{\rho}{2 \pi^2 R^3 W} \Rightarrow R^3 = \frac{\rho P^2}{2 \pi^2 W U^2}.$$
Therefore, the radius of the thread
$$R = \sqrt[3]{\frac{\rho P^2}{2 \pi^2 W U^2}} = 0,018 \text{ mm},$$
its diameter
$$d = 2 R = 0,036 \text{ mm},$$
thread length
$$l = \frac{P}{2 \pi R W} = 57 \text{ cm},$$
its mass
$$m = D \pi R^2 l = 19 D_B \pi R^2 l = 0,011 \text{ г.}$$
M. Tsypin

F1265*. In a uniform magnetic field, an electron travels in a circular orbit. The field induction is slow (in a time of many

The Lorentz force acts on the electron from the magnetic field, which imparts centripetal acceleration to it. According to Newton's second law,
$$\frac{mv^2}{R} = evB,$$

⟦folio 31⟧

---
running_head:
folio:
---

where do we get it from
$$\frac{mv}{R} = eB.$$ (*)

The slow change in the magnetic field leads to the fact that the quantities $B$, $R$ and $v$ begin to depend on time, although the correspondence (*) is still satisfied.

A changing magnetic field generates an output electric field, the direction of which is equal to
$$E_{\text{инд}} = \frac{\mathcal{E}_{\text{инд}}}{2\pi R} = \frac{\pi R^2 \frac{\Delta B}{\Delta t}}{2\pi R}.$$

This field creates force
$$F_{\text{инд}} = eE_{\text{инд}}.$$

The work done by this force in a short time $\Delta t$ is equal to the change in the kinetic energy of the electron:
$$\frac{1}{2} Rev \cdot \Delta B = \Delta \left( \frac{mv^2}{2} \right) \approx mv \cdot \Delta v,$$

where the change in speed will be equal to
$$\Delta v \approx \frac{Re}{2m} \cdot \Delta B.$$

On the other hand, from the correspondence (*)
$$v = \frac{eBR}{m} = \Delta v \approx \frac{e}{m} (\Delta B \cdot R + B \cdot \Delta R).$$

Thus, we get
$$\frac{1}{2} R \cdot \Delta B \approx \Delta B \cdot R + B \cdot \Delta R \Rightarrow B \cdot \Delta R + \frac{1}{2} \Delta B \cdot R = 0 \Rightarrow \Delta B \cdot R + 2B \cdot \Delta R = 0 \Rightarrow \Delta B \cdot R^2 + 2B \cdot R \Delta R = 0 \Rightarrow \Delta (BR^2) = 0.$$

This means that when the magnetic field changes, the value of $BR^2$ remains the same. Therefore, increasing the magnetic field induction by three times leads to a decrease in the electron orbital radius by $\sqrt{3}$ times.

M. Tsypin

F1266. Two metal spheres of radius $R$ each are removed from each other at a large distance and connected to each other by a very thin conductor, in the gap of which an inductive coil $L$ is connected. An electric charge is placed on one of the spheres. After what time will the charge of this sphere decrease by half?

When an electric charge $Q$ is placed on one of the spheres, it will acquire potential
$$\varphi_0 = \frac{Q}{4\pi F_0 R}.$$

Since there is no charge on the second sphere at first (instantaneous charge flow will not occur, otherwise the current through the coils would be infinitely large, which is impossible), its potential is zero. Due to the presence of a potential difference between the spheres, a current will appear in the inductor coil, varying in accordance with the formula

⟦folio 32⟧

---
running_head:
folio:
---

After what time will the charge again become the same as at the first moment?

$$LI' = U.$$

The concept that this system is equivalent to an oscillatory circuit - the spheres play the role of capacitor plates. But the difference between such a circuit and a conventional one is that the total charge of the capacitor here is not zero, which leads to a change in its effective capacitance. Let's find her.

Let us represent the charge $Q$ on the first sphere at the initial moment as the sum of $+Q/2$ and $+Q/2$, and the zero charge on the second sphere as $+Q/2$ and $-Q/2$. In this case, the potential difference from charges $+Q/2$ on both spheres is equal to zero, and from the remaining charges $+Q/2$ and $-Q/2$ (their sum is zero) it is equal to $U_{\max} = \varphi_0$. Thus, the effective charge of the capacitor flowing between the spheres is $Q_{\alpha\phi} = Q/2$ and

$$C_{\alpha\phi} = \frac{Q_{\alpha\phi}}{U_{\max}} = 2\pi\varepsilon_0R.$$

Since the inductance of the coil is $L$, oscillations occur in the circuit with a period

$$T = 2\pi\sqrt{LC_{\alpha\phi}} = 2\pi\sqrt{2\pi\varepsilon_0RL}.$$

Obviously, this is the time after which the charge on the first sphere will again become the same as at the first moment (Fig. 1).

Now it is easy to find the time after which the charge of the first sphere will decrease by half. Indeed, at this moment the charges on both spheres should be equal to $+Q/2$, and the direction between the spheres should be zero. This means that the desired moment of time corresponds to a quarter of the oscillation period:

$$\tau = \frac{T}{4} = \frac{\pi}{2}\sqrt{2\pi\varepsilon_0RL}.$$

Note that this problem can be solved in a more formal way. Let $q_2$ be the charge transferred to the second sphere at time $t$ (Fig. 2). then the charge of the first sphere will be $q_1 = Q - q_2$. In this case, the direction to the coil is equal to the potential difference created by the charges on the spheres:

$$U = \varphi_1 - \varphi_2 = \frac{q_1}{4\pi\varepsilon_0R} - \frac{q_2}{4\pi\varepsilon_0R} = \frac{Q/2 - q_2}{2\pi\varepsilon_0R}.$$

Let us write down the law of change of current through the coils: $LI' = U$, or, since $I = q'_2$,

$$Lq'_2' = \frac{Q/2 - q_2}{2\pi\varepsilon_0R}.$$

Let's move on to the variable $q_3 = Q/2 - q_2$ and we get

$$q'_3' = -\frac{1}{2\pi\varepsilon_0RL}q_3.$$

This is the equation of harmonic oscillations with period $T = 2\pi\sqrt{2\pi\varepsilon_0RL}$. The charge on the first sphere differs from the charge $q_3$ only by a constant amount, which means it oscillates with the same period.

A. Vytsko

⟦folio 33⟧

---
running_head:
folio:
---

F1267. A point source of alpha particles emits them uniformly in all directions. At a distance of 10 cm from the source, a photoplastic with a size of 20x20 cm was placed; after 10 seconds of extocycin, 200 traces of trapped particles appeared on it. How many particles does the source emit per hour?

The point where the source is located is very well located: it is located in the center of the cube, one of the faces of which is photoplastic. This means that in 10 seconds the source emitted 6 200 = 1200 particles. Then in one hour he will emit

$$N = 1200 \cdot 3600 / 10 = 432000 \text{ частиц.}$$

However, this answer is not entirely accurate. The fact is that during radioactive decay, particles are emitted chaotically, so our answer is of an evaluative nature. Think for yourself how good this solution would be if the conditions included a number significantly less than 200, for example 10.
