---
id: 1980-2-resheniya-zadach-m551-m556-f563-f567-2a9a4ff0
issue: kvant_1980_2
year: 1980
number: "2"
title: Solutions to problems M551—M556; F563—F567
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 38
page_last: 44
page_labels: 36-42
tag: CA2F
lang: en
source: kvant_digital
extraction: vision
content_sha256: 54ad6cd1c4a145a552785f1bdda1de82e8b73f55aea259953bd8b72447c1bcec
prompt_sha256: draft-1
translated_from: content/ru/1980/02/articles/14_resheniya-zadach-m551-m556-f563-f567-2a9a4ff0.md
source_content_sha256: 0312f8de6a2f1b5a5f68859734d5eebb70f01dcd02c2a37f461669272aacf94c
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 36⟧

Problem solutions

M551. a) What is the smallest number of points that need to be marked inside a convex pentagon so that the inside of any triangle with vertices at the vertices of the pentagon contains at least one marked point?
b) The same question for a convex p-pleasure.

M552. a) Find at least one pair (p; q) of non-zero integers for which the triangles $x^2+px+q$ and $x^2+qx+p$ have integer roots.
b) Find all such pairs (p; q).

Let's immediately solve problem 6). Answer. $n-2$.

It is clear that it is necessary to put at least $n-2$ points, since a $n$-gon can be cut into $n-2$ triangles and each must contain a point. Let's show how to arrange the points in the $n$-gon $A_0A_1...A_{n-1}$ as needed.

Let us place the $k$th point $B_k$ ($k=1, 2,...,n-2$) near the vertex $A_k$ inside the angle $A_0A_kA_n$ (see Fig.), more precisely, at the intersection of this angle with the half-plane bounded by the straight line $A_{k-1}A_{k+1}$ and containing the point $A_k$. It is clear that the triangle $A_iA_kA_j$, where $0 \leq i < k < j \leq n-1$, contains the point $B_k$: the angle $A_iA_kA_j$ contains the angle $A_0A_kA_n$, and the diagonal $A_{k-1}A_{k+1}$ intersects the segments $A_iA_k$ and $A_kA_j$.

N. Vasiliev

We will immediately solve point 6). Let $x_1, x_2, y_1, y_2$ be the integer roots of triangles $x^2+px+q$ and $x^2+qx+p$ respectively. By Vieta's theorem

$$x_1+x_2=-p, y_1+y_2=-q, x_1x_2=q, y_1y_2=p.$$

Dividing the product of the first two equalities by the product of the other two ($pq \neq 0$), we obtain:

$$\left(\frac{1}{x_1}+\frac{1}{x_2}\right)\left(\frac{1}{y_1}+\frac{1}{y_2}\right)=1.$$

Without loss of generality, we can assume that $\left|\frac{1}{x_1}+\frac{1}{x_2}\right| \geq 1$ and $\left|\frac{1}{x_1}\right| \geq \frac{1}{2}$, that is, $|x_1| \leq 2$.

There are two possible cases: $|x_1|=1$ and $|x_1|=2$.

1°. Let $|x_1|=1$. Then from inequality $\left|\frac{1}{x_1}+\frac{1}{x_2}\right| \geq 1$ we obtain $|x_2|=n$, where $n \in \mathbb{N}$, $x_1x_2>0$. From here, by Vieta’s theorem, for the first triangle we obtain $p=\pm(n+1)$, $q=n$. The triangular $x^2+nx-(n+1)$ has whole roots for all $n \in \mathbb{N}$, and the triangular $x^2+nx+n+1$ has whole roots only for $n=5$. Indeed, the discriminant of this triangle $(n-2)^2-8$ must be a perfect square: $(n-2)^2-8=b^2$, that is, $(n-2)^2-b^2=8$; hence $(n-2-b)(n-2+b)=8$, and $n \in \mathbb{N}$ and $b \in \mathbb{N}$. That's why

$$\begin{cases} n-2-b=2 \\ n-2+b=4 \end{cases} \Rightarrow n=5.$$

2°. Let $|x_1|=2$. Then from inequality $\left|\frac{1}{x_1}+\frac{1}{x_2}\right| \geq 1$ it follows that $|x_2| \leq 2$. The case $|x_2|=1$ is, up to notation, the distances above, and the case $|x_2|=2$ leads to the parameter $(4,4)$ and $(-4,4)$, the second of which is not suitable (the polynomial $x^2+4x-4$ does not have integer roots).

⟦folio 37⟧

M553. Given a triangle ABC, and $|BC| < |AC| < |AB|$. On the moons BA and CA the segments BD and CE are also deposited, which is $|BD| = |CE| = |BC|$. Prove that the radius of the circumscribed circle of triangle ADE is equal to the distance between the centers of the circumscribed circle of triangle ABC and the circumscribed circle of it.

Let $O$ be the center of the circumscribed circle of triangle ABC, $O_1$ be the center of the circumscribed circle of triangle ADE, $K$ be the center of the circumscribed circle of $\triangle ABC$ (see Fig.). We need to prove that $|KO| = |O_1A|$.

Let $|BC| = |BD| = |CE| = a, |AC| = b, |AB| = c$.

Consider a circle with center at point $K$ of radius $|KO|$. Let's draw the chords $[OM] \parallel [AC]$ and $[ON] \parallel [AB]$. Let us prove that triangles OMN and ADE with angles congruent at vertices $O$ and $A$ are congruent.

Let us drop from the centers $O$ and $K$ the perpendiculars $OO'$ and $KK'$ to the side $AB(L = [ON] \cap [KK'])$. It's easy to check that

$$|AK'| = \frac{a+b+c}{2} - a = \frac{b+c-a}{2},$$

$$|O'K'| = |AK'| - |AO'| = \frac{b+c-a}{2} - \frac{c}{2} = \frac{b-a}{2},$$

$$|ON| = 2|OL| = 2|O'K'| = b - a = |AE|.$$

It can be proved in a similar way that $|OM| = |AD|$.

Thus, triangles OMN and ADE are congruent on both sides and the angle between them. Therefore $|KO| = |O_1A|$.

S. Maidman

M554. A natural number $n$ is good if there are also natural numbers $a_1, a_2, ..., a_k$ (not necessarily distinct), such that

$$a_1 + a_2 + ... + a_k = n$$

It is known that all numbers from 33 to 73 are good. Prove that all numbers greater than 73 are also good.

The statement of the problem immediately follows from two lemmas:

1°. if the number $n$ is good, then $u$ $2n + 2$ is good;
2°. if the number $n$ is good, then $u$ $2n + 9$ is good.

Let's prove them.

From equalities

$$n = a_1 + a_2 + ... + a_k,$$

$$\frac{1}{a_1} + \frac{1}{a_2} + ... + \frac{1}{a_k} = 1$$

should

$$2n + 2 = 2a_1 + 2a_2 + ... + 2a_k + 2,$$

$$\frac{1}{2a_1} + \frac{1}{2a_2} + ... + \frac{1}{2a_k} + \frac{1}{2} = 1$$

— thereby proving $1^\circ$;

$$2n + 9 = 2a_1 + 2a_2 + ... + 2a_k + 3 + 6,$$

$$\frac{1}{2a_1} + \frac{1}{2a_2} + ... + \frac{1}{2a_k} + \frac{1}{3} + \frac{1}{6} = 1$$

— thus proving $2^\circ$.

Using $1^\circ$ and $2^\circ$, very strong induction (starting with $2 \cdot 36 + 2 = 74$ for even $n$ and with $2 \cdot 33 + 9 = 75$ for odd $n$) we prove that any number greater than 73 is good, in particular, to check the correctness of the premise expressed in the condition. It can be easily proven that $k^2$ is always a good number and that if $m$ and $n$ are a good number, then $mn$ is also a good number.

⟦folio 38⟧

4 = 2²
9 = 3²
10 = 2 • 1 + 8 = 4 • 1 + 6
11 = 3 • 1 + 8 = 6 • 1 + 5
16 = 4²
17 = 2 • 4 + 9 = 4 • 1 + 13
18 = 3 • 4 + 6
20 = 3 • 4 + 8
22 = 4 • 4 + 6
24 = 2 • 11 + 2
25 = 5²
26 = 2 • 9 + 8
27 = 2 • 9 + 9
28 = 2 • 10 + 8
29 = 2 • 10 + 9
30 = 2 • 11 + 8
31 = 2 • 11 + 9
32 = 2 + 3 + 9 + 18
33 = 3 • 9 + 6
34 = 2 • 16 + 2
35 = 3 • 9 + 8
36 = 4 • 9
37 = 2 + 5 + 10 + 10 + 10
38 = 3 • 10 + 8
39 = 3 • 11 + 6
40 = 4 • 10

M555. Intersection distance
a) two;
b) three
cylinders of the same radius r, the axes of which are mutually perpendicular and pass through one point. How many planes of symmetry does this intersection have? What is its volume?

Fig. 1.

Fig. 2.

good. In addition, similarly to how it was done in 1° and 2°, it is checked that if n is good, then the following are also good: 2n+8(8=4+4), 2n+20(20=4+8+8), 3n+6(6=3+3), 3n+8(8=2+6), 4n+6(6=2+4), 4n+13(13=3+4+6), 6n+5(5=2+3).

Using this, as well as selecting representations for “insufficient” numbers, it is easy to prove that the numbers 1, 4, 9, 10, 11, 16, 17, 18, 20, 22 and all numbers from 24 to 73 are good (these proofs will impinge on the formulas in the margins).

Think about how you can test whether the numbers 19, 21, and 23 are good numbers. Perhaps those in our Programming Correspondence School will find it more useful to write a program that tests whether the system has

$$\begin{cases} x_1 + \ldots + x_k = 23, \\ \frac{1}{x_1} + \ldots + \frac{1}{x_k} = 1 \end{cases}$$

solution in natural numbers. (If there is a solution, then the program must print at least one solution; if not, print “0.”) You can consider this as an additional task for the next programming lesson; allowed, it is also useful to estimate the operating time (number of cycles) and ensure that it is as short as possible.

◆

a) The section of our body Ф by the plane α₀ passing through the axes of the cylinders (we will assume that α₀ is horizontal, Fig. 1) is a square on the side 2r. The body Ф has, very much in fact, the same five planes of symmetry as the square Ф∩α₀: these are the plane α₀ and four more perpendicular α₀ planes passing through the symmetry axes of the square. And the section of the body Ф by the horizontal plane αₓ, hence there is no α₀ at a distance |x| ≤ r, is a square on the side of length $2\sqrt{r^2-x^2}$: each of the cylinders intersects with this plane along a strip of width $2\sqrt{r^2-x^2}$ (Fig. 2, 3), and the intersection of two such strips with mutually perpendicular edges gives a square (Fig. 2). Therefore, the volume of our body is equal to

$$\int \limits_{-r}^{r} 4(r^2-x^2)dx = 8r^3 - 8r^3/3 = 16r^3/3,$$

To find the volume of a body F, it is not at all necessary to calculate the integral. It is only necessary to note that the section of a ball of radius r (which, of course, can hang in the body Ф) by the plane αₓ is a circle of area π(r²-x²). Therefore, the ratio of the required volume to the volume of a ball of radius r is equal to 4/π. Hence the volume of the body Ф is equal to 16r³/3 (the volume of the ball is 4πr³/3).

b) To imagine the intersection Ψ of three cylinders, it is convenient to construct it this way: take a cube (with a diagonal face of length 2r, that is, with an edge r√2) and draw a cylindrical surface (Fig. 4) through each four parallel edges. Ψ has nine symmetry planes like the cube. In the upper cubes, three cylindrical surfaces will intersect, and “above” each there will be a culoy having the same shape as the part of the body Ф located above the plane α_r√2/2. The volume of one dome is equal to

$$\int \limits_{r\sqrt{2}/2} 4(r^2-x^2)dx = 4r^3 \left[ \left( 1 - \frac{\sqrt{2}}{2} \right) - \left( \frac{1}{3} - \frac{\sqrt{2}}{3\cdot4} \right) \right] = r^3 (8-5\sqrt{2})/3,$$

⟦folio 39⟧

The dome poles are $r^3(16 - 10\sqrt{2})$, the cube $2r^3\sqrt{2}$, so the volume of the body we need is $(16 - 8\sqrt{2})r^3 \approx 4,69r^3$ (the volume of a ball of radius $r$, which, of course, can be inscribed in the body $\Psi$, is equal to $4\pi r^3/3 \approx 4,18r^3$).

You can also calculate the surface area of ​​the body $\Phi$ and $\Psi$. To do this, it should be noted that if a strip of paper with a width of $2\pi$ is rolled into a cylindrical tube (radius 1), this cylinder is cut with a plane at an angle of $\pi/4$ to the axis and the paper is again unfolded onto the plane, then its edge will have the shape of a sinusoid. To make a paper model of the body $\Phi$, you need to take four “petals” of area $2r^2\int_0^\pi \sin \varphi d\varphi = 4r^2$ each (Fig. 5, a), so that its total surface is $16r^2$, and a paper model of the body $\Psi$ can be made from two “petals” of area $4r^2\int_0^\pi \sin \varphi d\varphi = (4-2\sqrt{2})r^2$ each (Fig. 5, b), so that the surface area body $\Psi$ is equal to $(48-24\sqrt{2})r^2$.

N. Vasiliev

M556. Is it necessary to construct two acute-angled isosceles triangles with equal lateral sides and equal radii of inscribed circles?

Answer. Generally speaking, not necessarily.

Let $ABC$ (Fig. 1) $|AB| = |AC| = 1$, $\widehat{BAC} = 2\alpha$, $O$ be the center of the inscribed circle and $r$ its radius in an equilateral triangle.

To calculate the radius, we use the well-known formula $S = rp$, where $S$ is the area of ​​the triangle, $p$ is its half-perimeter. In our case

$$S = \frac{1}{2} |AB| \cdot |AC| \sin 2\alpha = \frac{1}{2} \sin 2\alpha,$$

$$p = \frac{|AB| + |BC| + |AC|}{2} = 1 + \sin \alpha.$$

Thus,

$$r(\alpha) = \frac{S}{p} = \frac{1}{2} \cdot \frac{\sin 2\alpha}{1 + \sin \alpha}.$$

The triangle $ABC$, according to the conditions, must be acute, so we will be interested in the values ​​$\alpha$ belonging to the interval $]0; \pi/4[$. We need to find out whether the function $r = r(\alpha)$ on $]0; \pi/4[$ is monotonous or whether it takes certain values ​​twice on this interval.

Let's study the function $r$ using an arbitrary one. Compute

⟦folio 40⟧

Taking the derivative, we get:

$$r'(\alpha) = \frac{1 - \sin \alpha - \sin^2 \alpha}{1 + \sin \alpha}$$

(make sure of this). Equating $r'(\alpha)$ to zero, we get $\sin^2 \alpha + \sin \alpha - 1 = 0$,

and, since $\alpha \in [0; \pi/4]$, $\sin \alpha = \frac{\sqrt{5} - 1}{2}$ or $\arcsin \frac{\sqrt{5} - 1}{2} = \alpha_0 \approx 38.2^\circ$.

It is easy to see that $r'(\alpha) > 0$ for $0 < \alpha < \alpha_0$ and $r'(\alpha) < 0$ for $\alpha_0 < \alpha < \pi/4$. Thus, $r$ returns at $\alpha \in ]0; \alpha_0[$ and kills at $\alpha \in ]\alpha_0; \pi/4[$, that is, $\alpha_0$ is the maximum point of the function $r$ (its approximate graph is shown in figure 2).

Now it is clear that inside the interval $]0; \pi/4[$ there are $a_1$ and $a_2$ for which $r(a_1) = r(a_2)$ (see Fig. 2).

A. Egorov

F563. In the middle of the barometric tube there is a column of air. At temperature $t_0 = 0^\circ C$ the length of the column is $t_0 = 10$ cm. What will be the length of the column at $t = 20^\circ C$?

F564. A car moves along a bend in a road with radius $R$. Suddenly the driver saw the dirty people on the road and began to slow down. What distance will the car travel before stopping if its speed is $v_0$, the friction coefficient of the wheels on the road is $k$ and the car brakes with the maximum possible formation?

The pressure in a column of air is equal to the weight of the column of liquid above the air divided by the cross-sectional area of ​​the tube. When the temperature changes, both the height of the liquid column and its density will change. But the rest of the balance remains the same. The weight of the column will remain the same, and therefore the air pressure will not change. Therefore, the ratio of the volumes of the air column at temperatures $T = 293$ K and $T_0 = 273$ K is equal to the relative temperature, and therefore,

$$\frac{l}{l_0} = \frac{T}{T_0}.$$

From here

$$l = l_0 \frac{T}{T_0} \approx 10.7 \text{ см.}$$

The only external force acting on the car in the horizontal plane is friction. Since the wheels of the car do not slip relative to the road, this is the force of static friction. This force imparts to the car an acceleration $\vec{a}$ such that the model of the projection $\vec{a}$ onto the radius drawn to the point at which the car is located is equal to the centripetal acceleration $a_1 = v^2/R$; the projection model of $\vec{a}$ onto the tangent to the road is $a_2 = \sqrt{a^2 - a_1^2}$. “Linear” acceleration $\vec{a}_2$ provides a decrease in vehicle speed. According to the conditions of the problem, $a_2$ remains constant and the maximum possible. At the moment of braking $a_2 = \sqrt{a^2 - v_0^4/R^2}$. This value is maximum at $a = kg$ (maximum value of static friction $kmg$).

Consequently, the car slows down with a constant “linear” acceleration $a_2 = \sqrt{(kg)^2 - v_0^4/R^2}$. The distance $l$ traveled by the car to the stop is equal to

$$l = \frac{v_0^2}{2a_2} = \frac{v_0^2 R}{2 \sqrt{(kgR)^2 - v_0^4}}.$$

⟦folio 41⟧

F565. On figure, taken from Milliken’s work, the dependence of the retarding voltage on the frequency of light in experiments is given according to the formula:

$$hv = A + \frac{mv^2}{2},$$

where $A$ is the work function of the electron leaving the cathode and $mv^2/2$ is the kinetic energy that the emitted electron has. The maximum voltage between the anode and the cathode, at which an electron can still reach the anode, is the delay

$$hv = A + U_3e.$$

For two frequencies of light $v_1$ and $v$ we can write:

$$hv_1 = A + U_{31}e, \quad hv_2 = A + U_{32}e.$$

Subtracting the second from the first equality, we get

$$h\Delta v = e\Delta U_3,$$

where

$$\frac{h}{e} = \frac{\Delta U_8}{\Delta v}.$$

Determining the corresponding values ​​$\Delta U_3$ and $\Delta v$ from the graph, we find:

$$\frac{h}{e} \approx 4.10^{-15} \text{ B}\cdot\text{c}.$$

F566. An atom moving with speed $v$ ($v \ll c$) emits a photon at a small angle a to the direction of its motion. Prove that if $\omega$ is the frequency of radiation of an atom at rest, and $\omega$ is the frequency of a photon, then for visible light $\frac{\omega_0 - \omega}{\omega} \approx \frac{v}{c}$ cos $\alpha$.

As a result of photon radiation, the momentum of the atom, its kinetic energy and internal energy change.

According to the law of conservation of momentum $mv = mv_1 + \vec{p}_\phi$ ($\vec{mv}_1$ is the momentum of the atom after radiation, $\vec{p}_\phi$ |= $\hbar\omega/c$ is the momentum of the emitted photon), that is

$$(mv_1)^2 = (mv)^2 + \left(\frac{\hbar\omega}{c}\right)^2 - 2mv \frac{\hbar\omega}{c} \cos \alpha.$$

According to the law of conservation of energy

$$\frac{mv^2}{2} = \frac{mv_1^2}{2} + \hbar\omega + \Delta E$$

($\hbar\omega$ is the energy of the emitted photon, $\Delta E$ is the change in the internal energy of the atom).

The change $\Delta E$ in the internal energy of an atom is the change in the energy of the first initial atom after the emission of a photon with energy $\hbar\omega_0$. After radiation, the atom, according to the law of conservation of momentum, acquires a momentum $\vec{m}\vec{u}$ such that

⟦folio 42⟧

that $m\vec{u} + (\hbar\omega_0/c) = \vec{0}$ and $m\mu = \hbar\omega_0/c$. So the change in internal energy.atoma, according to the law of conservation of energy, is equal to

$$\Delta E = - \left[ \hbar\omega_0 + \frac{(\hbar\omega_0)^2}{2mc^2} \right] = - \hbar\omega_0 \left( 1 + \frac{\hbar\omega_0}{2mc^2} \right)$$

($\Delta E < 0$, since the internal energy.atoma has decreased).

Substituting the value $\Delta E$ into (2) and excluding $v_1$ from (1) and (2), we obtain:

$$\omega \left( 1 + \frac{\hbar\omega}{2mc^2} - \frac{v}{c} \cos \alpha \right) = \omega_0 \left( 1 + \frac{\hbar\omega_0}{2mc^2} \right).$$

At relatively small frequencies $\omega$ and $\omega_0$ (on the order of optical), the values ​​$\hbar\omega/2mc^2$ and $\hbar\omega_0/2mc^2$ are much less than unity. Neglecting these quantities, from (3) we find that at small angles $\alpha$ (when $\cos \alpha \approx 1$)

$$\frac{\omega - \omega_0}{\omega} \approx \frac{v}{c}.$$

F567. figure 1 shows the dependence of the current through an automatic light bulb on the voltage across it. The light bulb is connected to the circuit shown in figure 2. Find the power released by the light bulb.

To find the power released by a light bulb, you need to determine the voltage across the light bulb and the current flowing through it.

If the voltage across the light bulb and across the resistor with resistance $R_2$ is $U$, then across the resistor with resistance $R_1$ the voltage is $U - U$. The current flowing through $R_1$ is $I_1 = (\mathcal{E} - U)/R_1$; the current flowing through $R_2$ is equal to $I_2 = U/R_2$. Therefore, the current flowing through the light bulb at a voltage across it $U$ is equal to

$$I = I_1 - I_2 = \frac{\mathcal{E} - U}{R_1} - \frac{U}{R_2} = \frac{\mathcal{E}}{R_1} - U \left( \frac{1}{R_1} + \frac{1}{R_2} \right).$$

The light bulb lights up only if the values ​​$U$ and $I$, related relations (*), correspond to a point on the voltammer characteristic of the light bulb. These values ​​determine the intersection point of the graph of the function $I = 5 - \frac{5}{6} U$ (we substituted numerical values ​​in (*)) with the voltammer characteristic of the light bulb. Having built a graph (see Fig. 1), we find: $U \approx 4,8$ B, $I \approx 1$ A.

Thus, the power released by the light bulb is

$$P = IU \approx 4,8 \text{ Вт.}$$

I. Slovodechkiy
