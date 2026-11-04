---
id: 2024-11-12-resheniya-zadach-m2806-m2809-f2813-f2816-6ff48fdb
issue: kvant_2024_11-12
year: 2024
number: 11-12
title: Solutions to problems M2806—M2809; F2813—F2816
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 22
page_last: 30
page_labels: 20-28
tag: D51Y
lang: en
source: kvant_digital
content_sha256: da0e1223e684b5a217ca8a498ddd66e25802b213f509a4e730e6a968e527e882
prompt_sha256: draft-1
translated_from: content/ru/2024/11-12/articles/05_resheniya-zadach-m2806-m2809-f2813-f2816-6ff48fdb.md
source_content_sha256: 97d4757641827ce5368f7452d00ebded38b15ca86654b8230cf33ac4afd57c92
translation_model: draft
translation_run: en-draft-2026-11-03
translation_quality: draft
---

⟦folio 20⟧

Solutions to problems M2806–M2809, F2813–F2816

⟦column⟧

M2806. Is it possible to draw a closed 20-link broken line on a plane and number its links with numbers 1, 2, 3, ..., 20 in traversal order so that for each positive integer i = 1, 2, 3, ..., 10 links with numbers i and 10 + i intersect each other and do not intersect the remaining links?

Answer: no. Assume the opposite, and let $A_{1} A_{2}$ ... $A_{20}$ be the given broken line. Let A be the intersection point of links $A_{1} A_{2}$ and $A_{11} A_{12}$. It follows from the condition that the first 10 links of the broken line do not have common points, except for the ends, then we have a closed non-self-intersecting broken line $AA_{2} A_{3} A_{4}$ ... $A_{11} A$, let's call this broken line C (Fig. 1). At the same time

⟦figure⟧

Fig. 1

the vertices $A_{1}$ and $A_{12}$ will be either simultaneously inside or simultaneously outside the contour C. Further, the link $A_{12} A_{13}$ intersects the contour C exactly once, which means that the vertices $A_{12}$ and $A_{13}$ lie in different parts of the plane relative to the contour C: one is inside, the other is outside. We reason similarly with pairs of vertices $A_{13}$ and $A_{14}, A_{14}$ and $A_{15}$, …, $A_{20}$ and $A_{1}$. It turns out that $A_{12}, A_{14}$, …, $A_{20}$ lie in one part of the plane relative to contour C, and $A_{13}, A_{15}$, …, $A_{19}, A_{1}$ – in another. But this contradicts our previous conclusion that $A_{1}$ and $A_{12}$ are in the same part of the plane with respect to C. This completes the solution. Let's give a diagram of another solution. Let us use the following well-known theorem about coloring of domains (which actually generalizes the concepts of “outside” and “inside” for self-intersecting broken lines).

⟦folio 21⟧

---
running_head:
folio:
---

Theorem. Let several closed broken lines be drawn on the plane so that the set of intersection points and the intersection itself is finite (i.e. the broken lines form a plane graph in which the arrow of each vertex is the center). Then the areas on which the plane is divided can be colored black and white so that the areas that have a common boundary segment are colored in different colors.

Let's return to the problem and assume that the broken line $A_1 \dots A_{20}$, which is discussed in the conditions, exists. Let us use the coloring of the region from the theorem. Let's start traversing the broken line, starting from the first link $A_1 A_2$ from the point $A$ of the intersection of links $A_1 A_2$ and $A_{11} A_{12}$.

In the process of walking around, we will encounter the intersection points of the 2nd and 12th links, the 3rd and 13th, etc. Let us start the walk so that the black area is on the right side relative to the direction of movement $\overrightarrow{AA_2}$ (Fig. 2). Note that after passing the self-intersection point, this situation changes to the opposite: if the black area is on the right side relative to the direction, then after passing the next self-intersection point, the black area will be on the left side and vice versa. Then, after passing point $A$, the 11th point of self-intersection, the black area should again be on the right side of the direction. But the 11th self-intersection point is again point $A$. It turns out that after passing point $A$ again, the black area is on the right side of the direction of movement $\overrightarrow{AA_{12}}$, which is incorrect. Contradiction.

It is not difficult to solve the general problem of a $(2n)$-link broken line in which only pairs of links $i$ and $i + n$ ($i=1, 2, \dots, n$) intersect. Moreover, $n$ results in a contradiction, as above with $n=10$. For odd $n \geq 3$ it is easy to construct an example and verify that such broken lines exist.

In conclusion, we note that this problem is actually a special case of the following statement, known as Gauss’s theorem (see, for example, the article by S. Tabachnikov “On plane curves” in «Kvant» No. 11-12 for 1988, exercise 11):

Let a closed broken line have a finite set of points of intersection of pairs of links. Zanuterum (in an arbitrary manner) these mocks. Next, we will go around the broken line and write down the numbers of the intersection points sequentially in the order in which they are encountered during the traversal process. The result is a sequence of numbers in which each number appears twice. Then in this sequence between any two identical numbers there is an integer number of numbers.

I. Efremov, P. Kozhevnikov

M2807. The natural numbers $a, b$ and from the top of our minds that $a^2 + b^2 + c^2 + u a^3 + b^3 + c^3$ are divisible by $a + b + c$. In addition, GCD $(a + b + c, 6) = 1$. Prove that $a^5 + b^5 + c^5$ is divisible by $(a + b + c)^2$.

For every non-negative integer $k$ we denote $p_k = a^k + b^k + c^k$. In particular, $p_0 = 3$, $p_1 = a + b + c$. We need to prove that $p_5$ is divisible by $p_1^2$.

Let's write down the equality
$p_1^2 = (a + b + c)^2 = (a^2 + b^2 + c^2) -$
$-2(ab + bc + ca) = p_2 - 2(ab + bc + ca)$.

Since, according to the conditions, $p_2$ is divisible by $p_1$, then $2(ab + bc + ca)$ is also divisible by $p_1$; and since $p_1$ is coprime with 2, $(ab + bc + ca)$ is divisible by $p_1$.

Let's use the expansion
$a^3 + b^3 + c^3 - 3abc =$
$= (a + b + c)(a^2 + b^2 + c^2 - ab - bc - ca)$.

We see that $p_3 - 3abc$ is divisible by $p_1$, and since $p_3$ is divisible by $p_1$, we get that

⟦folio 22⟧

---
running_head:
folio:
---

and $3abc$ is divisible by $p_1$. According to the conditions of the problem,
3 is coprime with $p_1$, so $abc$ is divisible by $p_1$.

So, we have obtained that each of the expressions $s_1 = p_1 = a + b + c$, $s_2 = ab + bc + ca$, $s_3 = abc$ is divisible by $p_1$. (The expressions $s_1, s_2, s_3$ are called elementary symmetric functions of $a, b, c$.)

Then we use the equality $p_4 = s_1p_3 - s_2p_2 + 3s_3p_1$ (it can be verified directly). We see that each term on the right side is divisible by $p_1^2$, which means $p_4$ is divisible by $p_1^2$.

Further, from the equality $p_5 = s_1p_4 - s_2p_3 + 3s_3p_2$ (which can also be verified directly) it also follows that $p_5$ is divisible by $p_1^2$, which completes the solution.

Note that the solution can be obtained in other ways, for example, by expressing $p_5$ explicitly in terms of elementary symmetric functions. The formulas that we used in the solution are special cases of the so-called Newton points connecting the symmetric functions $p_i$ and $s_j$ of three variables $a, b, c$. We can continue the sequence of these points $p_k = s_1p_{k-1} - s_2p_{k-2} + 3s_3p_{k-3}$ (for $k = 6, 7, \dots$) and show that in the conditions of the problem $p_{3m}, p_{3m-1}$ and $p_{3m-2}$ are divided by $p_1^m$ for all $m = 1, 2, \dots$.

A. Antropov, A. Golovanov,
P. Kozhevnikov

M2808. Some participants murrn others among themselves, and each has at least one friend. Each participant in the tournament was given a T-shirt with the number of others in the tournament written on it. Prove that although a participant has the average of the numbers written on the T-shirts of his others, it is not less than the average of the numbers on all T-shirts.

The number of participants is 1, 2, ..., $N$, and participant number $i$ is empty, the number of others is $n_i$ (i.e. his T-shirt says $n_i$).

Let us put $s_i = \frac{n_t + \dots}{n_i}$, where the sum in the numerator is taken over all parts $t$ that are friends with $i$. Let's assume the opposite: each $s_i$ is less than the average of the others: $s_i < \frac{n_1 + n_2 + \dots + n_N}{N}$. Then, summing over all parts $i$, we get that $S = s_1 + s_2 + \dots + s_N$ is less than $2E = n_1 + n_2 + \dots + n_N$, so $E$ is the number of others (i.e. $E$ is the number of edges in our others graph). Having rearranged the terms in the sum $S$, we see that $S$ is equal to the sum of the brackets $\left(\frac{n_t}{n_i} + \frac{n_i}{n_t}\right)$ over all parameters $i - t$.

Each such bracket is at least 2 (as the sum of its reciprocal positive numbers), and since the number of others is $E$, we get $S \geq 2E$. But this contradicts the previously established inequality $S < E$.

P. Kozhevnikov

M2809. Points $M$ and $N$ are chosen respectively on sides $AC$ and $BC$ of triangle $ABC$ such that $AM = BC$ and $CM = BN$ (see figure). Let $O$ be the intersection point of the segments $AN$ and $BM$. Find angle $ACB$ if it is known that it is twice as large as angle $AOM$.

The solution to the problem is given in the article “Variations on a Theme of a Geometric Problem.”

F2813. In a vessel I put a piece of ice with mass $m_\pi$ and filled with a portion of water with mass $m_B$. The diagram (Fig. 1) shows areas indicating the final state of the contents of the vessel depending on the temperature of a piece of ice $t_\pi \in [-100^\circ C; 0^\circ C]$ and the temperature of portions of water $t_B \in [0^\circ C; 100^\circ C]$. It is known that in the range $[-100^\circ C; 0^\circ C]$ the specific temperature of ice depends on its temperature according to the law $c_\pi(t_\pi) = c + \alpha t_\pi$, where $c = 2100$ J/(kg °C), $t_\pi$ is the ice temperature in degrees Celsius, and $\alpha$ is some constant value. The specific temperature of water is $2c = 4200$ J/(kg °C), and the specific melting temperature of ice is $\lambda = 336$ kJ/kg = 2cT, where $T = 80^\circ C$. Ten capacity of the vessel and chalk rooms remain.

⟦folio 23⟧

---
running_head:
folio:
---

1) Identify $\alpha$ and $\gamma = m_{\pi}/m_B$.
2) Quality intention is a similar diagram of the final state of the contents of the vessel depending on the temperature of a piece of ice $t_{\pi} \in [-100^\circ C; 0^\circ C]$ and the temperature of a portion of water $t_B \in [0^\circ C; 100^\circ C]$, for equal masses of ice and water $m_{\pi} = m_B$. Indicate characteristic points on the diagram.

1) The line on the diagram dividing the states "ice" and "mixture of water and ice" corresponds to ice at the melting point $0^\circ C$. Let us derive the equation of this line. The amount of heat that water gives off when it remains until $0^\circ C$ and crystallizes is
$$Q_{\text{отд}} = 2cm_Bt_B + m_B\lambda.$$
The average specific heat of ice when heated from $t_{\pi}$ to $0^\circ C$ is
$$c_{\text{cp}} = \frac{c + (c + \alpha t_{\pi})}{2} = c + \frac{\alpha t_{\pi}}{2}.$$
Then the amount of heat required to heat the ice to $0^\circ C$ is
$$Q_{\text{получ}} = c_{\text{cp}}m_{\pi}(-t_{\pi}) = -\left(c + \frac{\alpha t_{\pi}}{2}\right)m_{\pi}t_{\pi}.$$
Since there is no heat loss,
$$Q_{\text{отд}} = Q_{\text{получ}}.$$
Using the notations $\gamma = m_{\pi}/m_B$ and $\lambda = 2cT$, we obtain the required dependence:
$$t_B(t_{\pi}) = -T - \frac{\gamma t_{\pi}}{2} - \frac{\alpha \gamma t_{\pi}^2}{4c}.$$

Substituting into this equation the points $(-95; 80)$ and $(-55; 20)$ from the diagram, in which the dividing line of good falls on the nodes of the coordinate grid, we obtain
$$\gamma = 4,0, \alpha = 7,0 \text{ Дж}/\left(\kappa \Gamma \cdot (\deg C)^2\right).$$
2) See Fig. 2.
D.Rubtsov

F2814. A straight solid non-conducting truncated cone is charged along the lateral surface, so that its surface charge density depends on the distance to the vertex O of the whole cone as $\sigma(x) = A/x$, where $A$ is a known pole constant. The bases of the truncated cone are charged uniformly with surface densities $\sigma_1$ and $\sigma_2$ (see figure). The length of the generatrix and the positive angle of the distance of the cone, the additional truncated cone to the whole, are equal to $l$ and $\alpha = 30^\circ$ of the corresponding, the length of the generatrix of the truncated cone is $l$.

⟦folio 24⟧

---
running_head:
folio:
---

1) Let $\sigma_1 = -\sigma_2 = \sigma_0$, where $\sigma_0$ is a known quantity. Find the directionality vector $\vec{E}_O$ at point O.
At the end, a small channel was drilled so that the test negative charge $-q(q > 0)$ could move massively along the symmetry axis of the cone without any pretense. Further, $\sigma_1 = \sigma_2 = \sigma_0$ is true.
2) Prove that there is an equilibrium position of the test charge that does not depend on the value of $\sigma_0$. Find this equilibrium position. As an answer, give consideration from it to point O.
3) At what values ​​of $\sigma_0$ will the found equilibrium position be stable? For values ​​corresponding to stable equilibrium, find the period of small oscillations of the test charge in the circle of the equilibrium position.
Note. The cone is fixed, the dielectric capacity of a successful cone $\varepsilon = 1$, the influence of gravity and the phenomena of magnetism is claimed.

1) Let's break the lateral surface into rings and start integrating:
$$E_1 = \int_1^{2l} k \frac{2\pi x \sin \alpha}{x^2} \frac{A}{x} \cos \alpha \cdot dx = \frac{\sqrt{3} A}{8 \varepsilon_0} \int_1^{2l} \frac{1}{x^2} dx = \frac{\sqrt{3}}{16} \frac{A}{\varepsilon_0 l}.$$
The total directionality from the bases $E_2$ is zero. Then
$$E_O = E_1 = \frac{\sqrt{3}}{16} \frac{A}{\varepsilon_0 l}.$$
2) The distance from the equilibrium position $F$ to point O is
$$OF = \frac{2\sqrt{3}}{3} l.$$
3) The equilibrium position is stable in the case
$$\sigma_0 < \frac{A}{2l},$$
and the period of oscillation is equal to
$$T = \frac{8\pi}{3} \sqrt{\frac{2}{\sqrt{3}} \frac{m\varepsilon_0 l}{q} \left(\frac{A}{l} - 2\sigma_0\right)^{-1}},$$
where $q$ is the test charge.
G. Rastorguev

F2815. The electrical circuit is represented by a memrahedron, in the two promiscuous-false edges of which there are the feather and the second ideal sources of constant voltage with EMF $\varepsilon_1$ and $\varepsilon_2$ of the corresponding voltage along the axis of symmetry of the cone. Next, $\sigma_1 = \sigma_2 = \sigma_0$ is true.

The significant EMF produced by one of the resistors is known:
$\varepsilon_1 = 6$ B, $\varepsilon_2 = 12$ B,
$R_2 = 3$ Ohm. The magnitude of the power of the current through the feather source is equal to $I_1 = 1$ A and does not change when the polarity of connecting this source is adjusted. The magnitude of the current flow through the second source with the polarity indicated on figure is equal to $I_2 = 2$ A. The resistance of the connected wires can be determined.

1) What will be the magnitude of the moka force through the second source if the polarity of the first source is changed?
2) Find the magnitude of the moka force through the second source to remove from the circuit; b) replace the first source with a per jumper with zero resistance.
3) What are the resistances of resistors $R_1$, $R_3$ and $R_4$?

1) Let's use the current superposition method. We will look for current strengths in the branches of the circuit as a superposition of current strengths flowing in these branches under the influence of one source, provided that the other source, by virtue of its ideality, is replaced by an ideal jumper. Let the jumper replace the second source. Let us denote the strength of the currents flowing through the feathers and the second sources by $I_{11}$ and $I_{21}$ corresponding to Fig. 2. Then, when taking into account the polarity

⟦folio 25⟧

---
running_head:
folio:
---

connection of the first source, the direction of current $I_{11}$ will change to the opposite, and the magnitude of the current will remain unchanged. Now let's replace the first source with a jumper. Let us denote the strength of the currents flowing through the first and second sources by $I_{12}$ and $I_{22}$, respectively (Fig. 3). If the current strength $I_{12}$ is not zero, then maintaining the value of the total current through the first source when changing its polarity is impossible. This means that the current strength $I_{1}$ is zero. This is only possible if the seats are balanced. Then we have the following correspondence between resistances:
$$\frac{R_1}{R_2} = \frac{R_3}{R_4}.$$
Note that this condition is also a condition for balancing the place to which the first source is connected when the second is replaced by jumper $CD$. This means that the current $I_{21}$ is also zero. From this we can conclude that the strengths of the currents flowing through the first and second sources are determined only by the EMF values ​​of the corresponding sources and the polarities of their connections. Thus, the current strength $I'_2$ flowing through the second source when the polarity of the connection of the first source changes is equal to
$$I'_2 = I_2 = 2 \text{ A}.$$
2) The magnitudes of currents $I_{2a}$ and $I_{26}$ in case a) and b) respectively will be determined by the resistance of the place connected to terminals $C$ and $D$ of the second source:
$$I_{2a} = \frac{\varepsilon_2}{r_a}, I_{26} = \frac{\varepsilon_2}{r_6}.$$
Because the site is balanced, removing jumper $AB$ will not change the resistance of the site between nodes $C$ and $D$. Then the site resistances $r_a$ and $r_6$ will be the same and equal to the resistance of the equivalent source
$$r_0 = \frac{R_2 R_4}{R_2 + R_4} + \frac{R_1 R_3}{R_1 + R_3},$$
found when solving the first point, i.e. $I_{2a} = I_{26}$. Since $I_2 = \varepsilon_2/r_0$, then
$$I_{2a} = I_{26} = I_2 = 2 \text{ A}.$$
3) The current strengths $I_1$ and $I_2$ flowing through the first and second sources, respectively, are determined by the expressions
$$\varepsilon_1 = I_1 \left( \frac{R_1 R_2}{R_1 + R_2} + \frac{R_3 R_4}{R_3 + R_4} \right),$$
$$\varepsilon_2 = I_2 \left( \frac{R_2 R_4}{R_2 + R_4} + \frac{R_1 R_3}{R_1 + R_3} \right).$$
Let us introduce two notations: $R_1 = kR_2, R_4 = \alpha R_2$. Then $R_3 = \alpha kR_2$ and for current strengths $I_1$ and $I_2$ we have
$$I_1 = \frac{\varepsilon_1}{R_2} \frac{1+k}{k(1+\alpha)}, I_2 = \frac{\varepsilon_2}{R_2} \frac{1+\alpha}{\alpha(1+k)},$$
$$I_1 I_2 = \frac{\varepsilon_1 \varepsilon_2}{R_2^2 \alpha k}, \alpha k = \frac{\varepsilon_1 \varepsilon_2}{I_1 I_2 R_2^2} = 4.$$
Note that from the problem conditions it follows
$$\frac{\varepsilon_1}{I_1} = \frac{\varepsilon_2}{I_2}.$$
From this correspondence and the expressions for $I_1$ and $I_2$ we obtain
$$\frac{\alpha(1+k)}{1+\alpha} = \frac{k(1+\alpha)}{1+k}, \alpha(1+k)^2 = k(1+\alpha)^2,$$
$$\alpha + 2\alpha k + k^2\alpha = k + 2\alpha k + \alpha^2k,$$
$$\alpha + 4k = k + 4\alpha, \alpha = k.$$
Given that $\alpha k = 4$, we have $k = \alpha = 2$. Then
$$R_1 = R_4 = 2R_2 = 6 \text{ Om}, R_3 = 4R_2 = 12 \text{ Om}.$$
A. Apolonsky

F2816. In a thick cast made of non-conductive hard material, perpendicular to the surface, a small diameter is drilled, the depth of which is less than powerful litma (Fig. 1). One end of an elastic band with a stiffness coefficient is attached to the “bottom” of the rejection

⟦folio 26⟧

---
running_head:
folio:
---

tic. The length of the undeformed elastic band in the monostim is equal to the depth of the hole. A bead of mass m, charged with a positive charge q, is attached to the other end of the rubber band. Plyma is located horizontally in the field of softness. The surface of the plasma is smooth. A uniform magnetic field is switched on perpendicular to the surface planes, the induction vector of which is directed opposite to the acceleration vector of free pressure. The magnitude of the magnetic field induction is equal to B. When calculating the rubber, the bead is mixed along the surfaces of the plate at a distance of $r_0$ from the axis of the hole and with a punch, giving it a magnetic perpendicular rubber speed, so that the bead moves in a circle.
1) Determine the angular speeds of movement of the bead when it is rotated clockwise and counterclockwise (if you watch its movement from above).
The force acting on the bead also depends on its speed in a linear manner. Therefore, if there are two different laws of motion $\vec{r}_1(t)$ and $\vec{r}_2(t)$, describing certain movements of the bead, then equation $\vec{r}(t) = \alpha \vec{r}_1(t) + \beta \vec{r}_2(t)$ for any constant α and β typically describes the law of physical implementation of the motion of this bead under the influence of the same forces (after all, the speed and acceleration of the bead at any moment of time will be described by the same combination maxims).
For example, if a bead is released from the same initial position as in point 1 without an initial speed, then the law of its movement can be found as a result of the imposition (superposition) of the laws of medicine studied in this point.
2) What is the minimum distance to which the bead approaches the axis of the hole after being nibbled without an initial speed from a distance $r_0$ from the hole?
3) After what time t, after removing the bead, will we find ourselves at a distance $r_0$ from the axis of the hole?
4) Image of the bead trajectory for case $q^2 B^2 / (mk) = 1/2$. How long will it take after the bead is removed for the first time to find ourselves at the starting point?

1) The equation of motion of a bead on an elastic band in a magnetic field $\vec{B}$ has the form
$$m\vec{a} = -k\vec{r} + q[\vec{v} + \vec{B}],$$
i.e. it is a linear and homogeneous equation with respect to the law of motion $\vec{r}(t)$. When moving along a circle of radius $r_0$, the centripetal acceleration of the bead is created by the elastic force of the rubber band and the Lorentz force, and depending on the direction of rotation, the Lorentz force is directed either towards the center of the circle or away from it. This means that the angular velocity of the bead is found from the equation
$$m\omega^2 r_0 = kr_0 \pm qB\omega r_0,$$
$$\omega^2 = \pm \frac{qB}{m}\omega - \frac{k}{m} = 0.$$
Next, we introduce the notations $\Omega = \frac{qB}{2m}$ and $\omega_0^2 = \frac{k}{m}$. Then, choosing a positive root for each case, we come to the conclusion that when rotating clockwise the magnitude of the angular velocity
$$\omega_1 = \sqrt{\omega_0^2 + \Omega^2} + \Omega = \sqrt{\frac{k}{m} + \frac{q^2 B^2}{4m^2}} + \frac{qB}{2m},$$
and when rotating counterclockwise
$$\omega_2 = \sqrt{\omega_0^2 + \Omega^2} - \Omega = \sqrt{\frac{k}{m} + \frac{q^2 B^2}{4m^2}} - \frac{qB}{2m} < \omega_1.$$
2) Let $\vec{r}_1(t)$ be the law of motion of a bead rotating along a circle of radius $r_0$ clockwise, and $\vec{r}_2(t)$ be the law of motion of a bead rotating along that circle counterclockwise. The modules of the movement speeds of the bead during these movements differ: $|\vec{v}_1| = \omega_1 r_0$, and $|\vec{v}_2| = \omega_2 r_0$. If we write the superposition of these laws of motion in the form
$$\vec{r}(t) = \frac{\omega_2}{\omega_1 + \omega_2}\vec{r}_1(t) + \frac{\omega_1}{\omega_1 + \omega_2}\vec{r}_2(t),$$
then, in accordance with the linearity and homogeneity of the equation of motion, this law also satisfies the equation of motion. It is easy to determine the initial conditions that it corresponds to: since $\vec{r}_1(0) = \vec{r}_2(0) = \vec{r}_0$ and for different directions of rotation $|\vec{v}_1(0)| = \omega_1 r_0 = \frac{\omega_1}{\omega_2}|\vec{v}_2(0)|$, then $\vec{r}(0) = \vec{r}_0$ and $\vec{v}(0) = 0$. Therefore, according to

⟦folio 27⟧

---
running_head:
folio:
---

the resulting law describes the motion of a bead launched without an initial speed from a distance $r_0$ from the hole, and the coordinate vector of such a bead can be found at any time as the sum of a vector $\frac{\omega_2}{\omega_1 + \omega_2} \vec{r}_1(t)$ with a constant length $\frac{\omega_2}{\omega_1 + \omega_2} r_0$, rotating with an angular velocity $\omega_1$ clockwise, and a vector $\frac{\omega_1}{\omega_1 + \omega_2} \vec{r}_2(t)$ with a constant length $\frac{\omega_1}{\omega_1 + \omega_2} r_0$, rotating with angular velocity $\omega_2$ counterclockwise from the same initial position (Fig. 2). Note that the angle between these vectors at time $t$ is equal to $\varphi(t) = (\omega_1 + \omega_2) t$. Therefore, according to the coine theorem, at this moment in time the distance from the bead to the hole satisfies the equation
$$r^2(t) = \left( \frac{\omega_2}{\omega_1 + \omega_2} r_0 \right)^2 + \left( \frac{\omega_1}{\omega_1 + \omega_2} r_0 \right)^2 + 2 \frac{\omega_2}{\omega_1 + \omega_2} r_0 \frac{\omega_1}{\omega_1 + \omega_2} r_0 \cos \left( (\omega_1 + \omega_2) t \right).$$
Means,
$$r(t) = \frac{r_0}{\omega_1 + \omega_2} \sqrt{\omega_1^2 + \omega_2^2 + 2\omega_1\omega_2 \cos \left( (\omega_1 + \omega_2) t \right)}.$$
Thus, the cyclic frequency of change in the distance from the bead to the equilibrium position is equal to $\omega_1 + \omega_2 = 2\sqrt{\omega_0^2 + \Omega^2}$, taking the minimum value
$$r_{\min} = \frac{\omega_1 - \omega_2}{\omega_1 + \omega_2} r_0 = \frac{\Omega}{\sqrt{\omega_0^2 + \Omega^2}} r_0$$
distance takes at a time
$$t_n = \frac{\pi}{\sqrt{\omega_0^2 + \Omega^2}} \left( n + \frac{1}{2} \right),$$ where $n = 0, 1, 2, \dots$.

Note that to find $r_{\min}$ it is not necessary to study the law of change in distance $r(t)$: it is enough to understand that the distance from the bead to the hole is minimal when the vectors of the “component” vectors of our superposition are directed in opposite directions. Then it is clear that $r_{\min}$ is equal to the difference of their models.

3) From the formula for $r(t)$ it is clear that the maximum distance from the bead to the hole is equal to the initial one: $r_{\max} = r_0$, and it is achieved at the time
$$t'_n = \frac{\pi}{\sqrt{\omega_0^2 + \Omega^2}} n,$$ where $n = 0, 1, 2, \dots$.

As you can see, for the first time after release this will happen at the moment of time
$$\tau = \frac{\pi}{\sqrt{\omega_0^2 + \Omega^2}}.$$

4) With such a correspondence of parameters, $\Omega^2 = \omega_0^2/8$, therefore, $\omega_1 = \omega_0\sqrt{2}$, and $\omega_2 = \omega_0/\sqrt{2}$. This means that the ratio of angular velocities is $\omega_1: \omega_2 = 2:1$, i.e. the general motion is periodic and the trajectory turns out to be closed. In this case
$$\vec{r}(t) = \frac{1}{3}\vec{r}_1(t) + \frac{2}{3}\vec{r}_2(t),$$
the lengths of the vectors whose sum gives $\vec{r}(t)$ are equal to $r_0/3$ and $2r_0/3$, and the law of change in distance looks like this:
$$r(t) = \frac{r_0}{3}\sqrt{5 + 4\cos(3\omega_2 t)}.$$
It is clear that the period of motion is the smallest common multiple of the period of the two components of motion, which in our case is equal to the period less than the frequency $\omega_2$. Therefore, for the first time after being released, the bead finds itself at the starting point in time.
$$T_1 = \frac{2\pi}{\omega_2} = \frac{2\pi\sqrt{2}}{\omega_0} = 2\pi\sqrt{\frac{2m}{k}},$$
and the period of change in distance from the hole
$$T = \frac{2\pi}{\omega_1 + \omega_2} = \frac{2\pi\sqrt{2}}{3\omega_0} = \frac{1}{3}T_1.$$

⟦folio 28⟧

KVANT 2024/No. 11-12

Therefore, during one period of movement, the bead reaches the maximum distance $r_{0}$ three times, and the minimum distance $r_{0} 3$ three times. Thus, the trajectory for a full revolution around the axis of the hole passes three times from a circle with radius $r_{0}$ to a circle with radius $r_{0} 3$ and back, and near common points with a larger circle the bead moves along the radius (the trajectory touches the radius), at common points with a smaller circle the radial speed of the bead becomes zero at a non-zero angular velocity - the bead moves perpendicular to the radius and its trajectory touches the smaller circle at common points. Using this information, it is possible to fairly correctly depict the type of trajectory (Fig. 3). A. Apolonsky, K. Parfenov
