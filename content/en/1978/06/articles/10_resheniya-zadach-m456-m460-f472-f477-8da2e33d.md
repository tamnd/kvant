---
id: 1978-6-resheniya-zadach-m456-m460-f472-f477-8da2e33d
issue: kvant_1978_6
year: 1978
number: "6"
title: Solutions to problems M456—M460; F472—F477
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 46
page_last: 54
page_labels: 44, 45, 48, 49, 51, 52
tag: "0012"
lang: en
source: kvant_digital
extraction: vision
content_sha256: 59ae0219407ee44f14c880f21c7cd040bfb5fbb49741c347754311660973dc94
prompt_sha256: draft-1
translated_from: content/ru/1978/06/articles/10_resheniya-zadach-m456-m460-f472-f477-8da2e33d.md
source_content_sha256: ac42567cbc590f4fea06715bd1e6e5897b3e39cd29bc3ed5bddadc319ad4c4b8
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 44⟧

Problem solutions
M456—M460; F472—F477

M456. At each vertex of a convex manifold, 3 edges converge. It is known that each of its faces is a polygon around which a circle can be described. Let us prove that a sphere can be described around this manifold.

Fig. 1.

Let $A$ be the vertex of the polygon, $AB, AC, AD$ the edges coming out of it. Since the points $A, B, C, D$ do not lie in the same plane, a sphere can be drawn through them; let us denote this sphere by $S_A$ (Fig. 1).

Let $A$ and $B$ be neighboring vertices. Let us prove that the spheres $S_A$ and $S_B$ coincide. From here it immediately follows that the spheres $S_X$ coincide for all vertices $X$, that is, all vertices lie on the same sphere.

Let $BE$ and $BF$ be edges emanating from vertex $B$. They lie in two faces $CAB$ and $DAB$, bordering the edge $AB$. For example, let edge $BE$ lie in face $CAB$, and edge $BF$ in face $DAB$ (note that point $E$ can coincide with $C$ and, similarly, point $F$ can coincide with $D$). According to the conditions, points $C, A, B, E$ lie on the same circle. In this case, three points $C, A$ and $B$ lie on a circle, which is obtained when the sphere $S_A$ intersects the plane passing through the points $C, A, B$. Since no more than one circle can be drawn through three different points, the two constructed circles coincide, that is, the point $E$ lies on the sphere $S_A$. Similarly, it is proved that the point $F$ lies on the sphere $S_A$. This means that the sphere $S_A$ passes through the points $B, A, E, F$, that is, it coincides with the sphere $S_B$, which is what was required.

I. Bernistey

M457. A non-self-cutting closed polygon is given on the plane; no three vertices of the polygon lie on the same straight line. The bet of non-adjacent links is special if the continuation of one of them intersects the other. Prove that the number of special pairs is even.

Fig. 2.

Consider some two consecutive links $AB$ and $BC$ of a broken line. Let's continue these ringing beyond the top $B$; we obtain rays $BK$ and $BL$ (Fig. 2). Let us call the circle of such two rays a knot. Such a corner can be constructed at each vertex of a broken line. It is easy to understand that the number of special pairs is equal to the number of intersections of the links with the corners. We claim that every corner intersects the broken line at an even number of points. In fact, if it passes from the polyline adjacent to $B$ vertex $A$ to another adjacent vertex $C$ from $B$, we see that our polyline goes inside the corner as many times as it goes from it (since points $A$ and $C$ are both located outside the corner). This means that the number of special pairs of rings is also even.

S. Fomin

M458. The polynomial $x^{10} + x^9 + x^8 + \dots + x^2 + x + 1$ is written. Two cerams in a dipping ceram. First, we intersect any of the asterisks with some number, then the second element with the number of any of the remaining asterisks, then again we intersect any of the asterisks

Yes, it can. Let's show how the second player should play for this.

A total of 9 stars need to be replaced with numbers - 5 for odd powers and 4 for even powers. Each move, the second player must become any coefficient at a degree that has the opposite parity in relation to the coefficient that his opponent has just placed. Then after seven moves there will be 2 stars left at powers $x^k$ and $x^l$, and at least one of the numbers $k$ and $l$ is odd, and the second player will have the move. Let $P$ be a polynomial that

⟦folio 45⟧

Number and so on (9 moves in total). If the resulting polynomial does not have real roots, then the first cerok is called, and if we have at least one root, we call the second. Can the second church win at any ceremony?

If the polynomial $f(x)$ does not end with the segment $[a,b]$ we inflate the values ​​of the numbers of signs, then with a non-history $c \in [a,b]$ it becomes $b = f(c)=0$

Fig. 3.

M459. In some countries, you can travel from each city to any other in minutes to the rest of the cities. The cost of each trip is known. Two matrices have been compiled for the cities of the country. In each of these matriroutes, each city is entered exactly once. When compiling the first matriroute, we were guided by the following principle: the starting point of the matriroute is chosen randomly, and at each next chalet in the city environment, through which the matriroute has not yet passed, the one whose trains to the comorbium from the previous city has the lowest cost is selected (if there are several maximum cities, then any of them is selected), and so on until all the cities have been passed. When compiling the second matriroute, the starting city can be chosen arbitrarily, and at each subsequent chalet in the city environment, through which the matriroute has not yet passed, the one whose train to the comorb from the previous city has the lowest cost is selected. Let us prove that the total cost of the project using the correct matrirut is not greater than the total cost of the project using the correct matrirut.

Let $a_1, a_2, \dots, a_{n-1}$ be the tickets of the first matriroute, $b_1, b_2, \dots, b_{n-1}$ be the tickets of the second matriroute ($n$ is the number of prouds). Let us denote the cost of any ticket $c$ by $\Pi(c)$, and the cost of travel from the city $A$ to the city $B$ by $\Pi(B)$. The statement will be proven if we managed to construct a mapping $f: \{a_1, \dots, a_{n-1}\} \rightarrow \{b_1, \dots, b_{n-1}\}$ that has the following two properties:

a) the mapping $f$ is one-to-one;
b) for any ticket $a$ from the first matriroute $\Pi(a) \leqslant \Pi(f(a))$.

We will indicate the method by which the mapping $f$ is constructed, which has property 6). To prove that it is one-to-one, we will show that this method leads to the construction of a mapping $g: \{b_1, \dots, b_{n-1}\} \rightarrow \{a_1, \dots, a_{n-1}\}$ such that for any ticket $a$ from the first matriroute $g(f(a)) = a$.

Method for constructing the mapping $f$. Let $a$ be some ticket of the first matriroute taken in the city $A$. Let us denote by $X_1(A)$ the set of cities that occur later than $A$ in the first matrirut, and by $X_2(A)$ the set of cities that occur later than $A$ in the second matrirut. The following two cases are possible:

1. $X_1(A) \cap X_2(A) \neq \emptyset$.
In this case, we take the ticket $a$ of the first matriroute happy and put $f(a) = b$, where $b$ is the ticket of the second matriroute, purchased in the city $A$ (see Fig. 4, a).

2. $X_1(A) \cap X_2(A) = \emptyset$.
In this case, the ground ticket $a$ of the first matrirut is unlucky. Let us choose from the set $X_1(A)$ a city $B: B \in X_1(A)$ such that $X_1(A) \cap X_2(B) = \emptyset$. It is easy to understand that the city $B$ is defined in a unique way by these two conditions. Indeed, assuming that there are two cities $B_1$ and $B_2$, such that $B_1 \in X_1(A)$, $B_2 \in X_1(A)$ and $X_1(A) \cap X_2(B_1) = \emptyset$, $X_1(A) \cap X_2(B_2) = \emptyset$, we obtain a contradiction: since from the condition of the problem it follows that for any two cities $C$ and $D$ either $C \in X_2(D)$ or $D \in X_2(C)$ must be either $B_2 \in X_1(A) \cap X_2(B_1)$ or $B_2 \in X_1(A) \cap X_2(B_2)$. Let us now put $f(a) = b$, where $b$ is the second matriroute ticket purchased in the selected city $B$ (Fig. 4, b).

⟦folio 48⟧

F472. Draw an approximate graph of the voltmeter reading versus time after opening switch K (Fig. 7). The voltmeter and inductance stone are ideal, R=100Ohm, U=300V.

Fig. 7.

Fig. 8.

F473. Figure 9 is made with a stroboscopic formula for the movement of two steel balls of the same diameters, but different masses. The arrow on figure shows the direction of movement of one of the collision balls.

1) Determine the ratio of the masses of the balls.
2) Indicate in which direction the second balls are moving.

When the switch is open, the current flowing through the circuit is $I_1 = \frac{U}{2R} = 1,5$ A. In this case, the voltmeter shows the voltage drop across resistance III: $U_1 = I_1R = 150$ V.

After the key is closed into the coil, an e.m. occurs. d.s. induction, prevailing over the change in magnetic flux through the coil, that is, overcoming the change in current $I_1$ flowing through the coil. So at the first moment after closing the key, a current flows through the coil $I_1 = 1,5$ A. Let's find the voltmeter reading at this moment. Obviously, the voltmeter changes the voltage drop across resistance II: $U_2 = I_2R$. Let's determine the value of $I_2$. From equalities

$$\begin{align*}
I_0 &= I_1 + I_2, \\
U &= I_0R + I_2R
\end{align*}$$

(see Fig. 7) is located

$$I_2 = \frac{1}{2}\left(\frac{U}{R} - I_1\right) = 0,75$$ A.

Thus, at the first moment after closing the key, the voltmeter shows

$$U_2 = I_2R = 75$$ V.

After installing the current in the circuit, the voltmeter will obviously show voltage

$$U'_2 = U - I'_0R = U - \frac{U}{R + \frac{R}{2}}R = \frac{1}{3}U = 100$$ V.

So, immediately after closing the key, the voltmeter reading will drop abruptly from 150 V to 75 V, and then gradually increase to 100 V (Fig. 8).

I. Slobodetsky

◆

Let $m_1$ be the mass of the first ball, $\vec{v}_1$ and $\vec{v}'_1$ its corresponding velocities before and after the collision, $m_2$ the mass of the second ball, and $\vec{v}_2$ and $\vec{v}'_2$ its velocities before and after the collision. According to the law of conservation of momentum

$$m_1\Delta\vec{v}_1 + m_2\Delta\vec{v}_2 = 0,$$ or $m_1\Delta\vec{v}_1 = -m_2\Delta\vec{v}_2,$

(1)

where $\Delta\vec{v}_1 = \vec{v}'_1 - \vec{v}_1$ is the change in the speed of the first ball, $\Delta\vec{v}_2 = \vec{v}'_2 - \vec{v}_2$ is the change in the speed of the second ball during a collision. From (1) we get

$$\frac{m_1}{m_2} = \frac{|\Delta\vec{v}_2|}{|\Delta\vec{v}_1|}.$$

Therefore, in order to relate the masses of the balls, it is necessary to construct the vectors $\Delta\vec{v}_1$ and $\Delta\vec{v}_2$ and then take the inverse ratio of their models.

⟦folio 49⟧

The velocities of the balls are equal to the movements of the balls during the time t between successive flashes of the lamp, divided by t. Since the value of t is the same for common balls both before and after the collision, then on a scale of 1: $\frac{1}{\tau}$ the vectors representing the velocities of the balls are simply equal to the vectors of displacement of the balls during the time between successive flashes of the lamp. Let's use this to find $\Delta v_1$ and $\Delta v_2$.

We know how one of the balls moved before the collision. In order to construct the vector $\Delta v_1$, it is also necessary to know how this ball moved after the collision - along branch II, III or IV? In order to find out, we will have to rework all possible options (there are only three of them). With the correct choice of the trajectories of the balls, the vectors $\Delta v_1$ and $\Delta v_2$, according to equality (1), should be directed in a straight line in the ignored directions.

Before proceeding with the construction, we note that $\Delta v$ does not change when “reversing” the movement of the ball, that is, if before the collision ball 1 moved along branch I, and after the collision - along branch II, then $\Delta v$ is the same as in the case if before the collision it moved along branch II, and after the collision - along branch I.

Now we can start building. Let us assume that ball 1 includes branches I and II, and ball 2 includes branches III and IV. Having constructed in this case the vectors of changes in the speeds of the balls (Fig. 10), we find that they are not directed along one straight line (at figure 10, for convenience, the vectors $v$ are constructed on a scale of 1: $\frac{1}{3\tau}$). Therefore, our assumption is not correct. Also checking other possible options, we make sure that ball 1 includes branches I and IV, and ball 2 includes branches II and III (Fig. 11). By measuring the lengths of the vectors depicted $\Delta v_1$ and $\Delta v_2$, we find:

$$\frac{m_1}{m_2} = \frac{|\Delta v_2|}{|\Delta v_1|} = \frac{1}{3}.$$

Now let's answer the second question. Let us denote by $\tau_1$ the time between the moment of collision of the balls and the last flash of the lamp before the collision. Then it is clear that the movement of the ball during this time must be $\tau_1/\tau$ part of the movement of the ball during the time t between shots. Having measured the corresponding movements of the ball, we find that $\tau_1/\tau$ is equal to 11/19. It should be the same for the second ball. By direct change we are convinced that branch III satisfies this condition. Consequently, ball 2 was moving along branch III before the collision.

I. Slovodechkiy

F474. The value shown in figure 12 is assembled from identical resistors and voltmeters. The first voltmeter reads $U_1 = 10$ B and the third reads $U_3 = 8$ B. What is the reading of the second voltmeter?

It is clear that voltmeters are not ideal - otherwise the points would not flow through the resistors, and the readings of the voltmeters would be the same.

Voltem readings are proportional to the currents flowing through them. This means that the currents flowing through resistors I, II and III are related as

$$I_1 : I_2 : I_3 = (U_1 : U_2 : U_3) : (U_2 + U_3) : U_3.$$

Since the resistors are the same, the voltage drops across them are proportional to the currents. For resistors II and III we have:

$$\frac{U_1 - U_2}{U_2 - U_3} = \frac{I_1}{I_3} = \frac{U_2 + U_3}{U_3},$$

⟦folio 51⟧

F476. Natural uranium consisting of a mixture of two isomotes with relative depreciation of 235 and 238 and a concentration ratio of 7:1000. To increase the concentration of $^{235}$U, which is placed in the shock absorbers, the gaseous compound $UF_6$ (uranium hexafluoride) is released into a vacuum through a small hole (effusion). The gas is passed through a porous-walled pipe T (Fig. 17). The gas that has filtered through the walls of the pipe is pumped out of vessel C. Determine the ratio of the concentrations of $^{235}$UF$_6$ and $^{238}$UF$_6$ in the relative mass of fluorine is 19.

F477. A rubber barb of mass m lies on the main horizontal plane. We space the barb a little so that it retains the shape of a circle and its center remains motionless. After the emoji prickly otnusk. Describe the further behavior of the ring. The coefficient of toughness of rubber iron is equal to k.

Substituting numerical values, we find
$$R_x \approx 0.22 \text{ Om}, \quad R - R_x \approx 18 \text{ Om}.$$
In this case $U_{AB} \approx 0.6 \text{ B}$, and with a change in E. d. With. E within ±1 V, the value of $U_{AB}$ changes by less than 0.03 V. The circuit we calculated can be used as a stabilizer of small voltages; However, it is practically best to use a second circuit of a light bulb and a resistor connected in reverse order together with the potentiometer.

A. Zilberman

Denotes $n_1$ and $n_2$ the number of molecules, respectively $^{235}$UF$_6$ and $^{238}$UF$_6$ per unit volume of gas $UF_6$. In time $t$, a number $N_1$ of molecules $^{235}$UF$_6$ passes through a hole of area s, equal to
$$N_1 = v_{N1}stn_1,$$
and the number $N_2$ of molecules $^{238}$UF$_6$, equal to
$$N_2 = v_{N2}stn_2,$$
where $v_{N1}$ and $v_{N2}$ are projections of the average velocities of molecules $^{235}$UF$_6$ and $^{238}$UF$_6$ onto the $x$ axis, directed perpendicular to the hole.
The ratio $N_1/N_2$—the ratio of the concentrations of molecules $^{235}$UF$_6$ and $^{238}$UF$_6$ in the gas being released—is equal to
$$\frac{N_1}{N_2} = \frac{v_{x1}n_1}{v_{x2}n_2}.$$
It is obvious that $\frac{v_{x1}}{v_{x2}} = \frac{v_1}{v_2}$, where $v_1$ and $v_2$ are the root mean square velocities of gas molecules. Since $v = \sqrt{\frac{3kT}{m}}$, where $m$ is the mass of molecules, then $\frac{N_1}{N_2} = \frac{n_1}{n_2} \sqrt{\frac{m_2}{m_1}}$ ($m_1$ and $m_2$ are the masses of molecules $^{235}$UF$_6$ and $^{238}$UF$_6$, respectively). From here
$$\frac{N_1}{N_2} = \frac{7}{1000} \sqrt{\frac{352}{349}} \approx \frac{7,03}{1000}.$$
I. Slobodetsky

From the messages of symmetrina, it seems clear that the barb will oscillate - stretch and contract, maintaining the shape of a circle, and its center will remain motionless. To verify the correctness of these ideas, it is enough to consider the movement of any one point (or small element) of the ring and make sure that it actually vibrates.

Let us select the small element A of the ring. When the barb is stretched, element A is acted upon by elastic forces $|\vec{f}|$, directed tangentially, from neighboring sections of the ring

⟦folio 52⟧

nom. The equal force $|\vec{F}|$ of these forces is directed towards the center of the bulb (Fig. 18). Under the influence of this force, element $A$ will be mixed to the equilibrium position; at the same time its length decreases. Having reached the equilibrium position by inertia (when its length is normal - the rubber is not stretched), the element continues to move towards the center. At the same time, from the side of the sections, elastic forces began to act on it, lifting it, the equal force of which is directed from the center of the bulb to the equilibrium position. Thus, the direction of the periodic force is reversed.

Let's see how the magnitudes $|\vec{F}|$ of this force and the magnitude $\Delta r$ of the element’s displacement from the equilibrium position are related.

The elastic forces $|\vec{f}|$ are proportional to the stretching (elongation) $\Delta l$ of the element, and the stretching $\Delta l$ is proportional to the displacement of the $\Delta r$ element from the equilibrium position (Fig. 19).

Therefore, the force $|\vec{F}|$ is proportional to the displacement $\Delta r$ of the element $A$ from the equilibrium position. And as is known, under the influence of such a force the body performs harmonic oscillations around the equilibrium position. This means that the real flask will oscillate around the equilibrium position - a position in which it is not stretched or sloping.

Let's find the period of these oscillations. At the moment of maximum stretching, all the mechanical energy $E_1$ of the flask is equal to its potential energy - the energy of elastic deformation:

$$E_1 = \Pi = \frac{k \Delta l^2}{2} = \frac{k [2\pi(r + \Delta r) - 2\pi r]^2}{2} = 2k\pi^2a^2$$

($a = \Delta r$ is the vibration amplitude of each point of the bulb).

When the flask passes through the equilibrium position, its total mechanical energy $E_2$ is equal to the sum of the kinetic energies of all its points:

$$E_2 = K = \sum_i \frac{m_i v_{\max}^2}{2} = \frac{mv_{\max}^2}{2}$$

($v_{\max}$ is the speed of each point of the bulb when passing through the equilibrium position). Since there is no training, then according to the law of conservation of mechanical energy $E_1 = E_2$:

$$2k\pi^2a^2 = \frac{mv_{\max}^2}{2}$$

From here we find $v_{\max}$:

$$v_{\max} = 2\pi a \sqrt{\frac{k}{m}}.$$

But with harmonic vibrations $v_{\max} = \omega$. This means $\omega = 2\pi \sqrt{\frac{k}{m}}$, and the period of oscillations of the flask point, and therefore, the period of oscillations of the entire flask is equal to

$$T = \sqrt{\frac{m}{k}}.$$

A. Abrahamyan
