---
id: 1981-5-resheniya-zadach-m636-m640-f647-f655-9321fcf9
issue: kvant_1981_5
year: 1981
number: "5"
title: Solutions to problems M636—M640; F647—F655
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 24
page_last: 31
page_labels: 22-29
tag: 1EJ7
lang: en
source: kvant_digital
extraction: vision
content_sha256: 658fa20b602f486fd6da54aa66d6212f18ea46a31194fd9c53635d6692c6855a
prompt_sha256: draft-1
translated_from: content/ru/1981/05/articles/10_resheniya-zadach-m636-m640-f647-f655-9321fcf9.md
source_content_sha256: 98ab2b3b955ea1f492961b7a83e7d5bf9e7b2a90d4edf27eabe9c8f7c0c414a0
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 22⟧

A beam of light enters the layer. At what values ​​of the angle α (see Fig. 4) will the beam return to an optically denser medium? At what value of the angle α₀ is the distance between the entry and exit points of the beam maximum?

P. Kalutsin, 10th grade student. (Moscow, village No. 444)

Problem solutions

M636—M640; F647—F655

The set {1, 2, 3, 5, 10, 20, 25, 50, 100} satisfies the conditions of the problem. This means that the required set contains no more than nine elements. Let's arrange its elements in ascending order:

$$1 = k_1 < k_2 < \dots < k_n = 100, n \leqslant 9.$$

Since $k_j \leqslant 2 \cdot k_{j-1}$ ($j=2, 3, \dots, n$), for any $j$ we have $k_j \leqslant 2^{j-1}$. Let $r$ be the most index such that $k_r \neq 2k_{r-1}$. Then $100 = k_n = 2^{n-r} \cdot k_r \leqslant 2^{n-r}(k_{r-1} + k_{r-2}) \leqslant 2^{n-r} \cdot 2(2^{r-2} + 2^{r-3}) = 3 \cdot 2^{n-3}$. From the inequality 100 $\leqslant 3 \cdot 2^{n-3}$ it follows that $n \geqslant 9$. So, $n=9$ and the set {1, 2, 3, 5, 10, 20, 25, 50, 100} is excludable.

Note that there are other sets of nine elements that satisfy the conditions of the problem. For example, the set {1, 2, 4, 6, 10, 20, 30, 50, 100} is also suitable.

Yu. Nesterenko

M637. Given a regular triangle ABC. Some line parallel to line AC intersects lines AB and BC at points M and P respectively. Point D is the center of triangle PMB, point E is the midpoint of segment AP. Determine the angles of triangle DEC.

Fig. 1.

Fig. 2.

Fig. 3.

Fig. 4.

⟦folio 23⟧

Fig. 5.
Fig. 6.
A)
B=M=P=D
x=0
b)
x=1
Fig. 7.
x=1
Fig. 8.

M638. Some cells of an infinite sheet of checkered paper are colored red, the rest blue, so that each rectangle of 6 cells of size 2x3 contains exactly two red cells. How many red cells can a rectangle of 99 cells of size 9x11 contain?

Accuracies $D$ and $D_1$ as the centers of triangles $MBP$ and $M_1BP_1$ respectively lie on the segment $MP_1$ and divide it into three equal parts. Therefore, $D_1E_1$ is the middle line in the triangle $DP_1C$, $|D_1E_1| = \frac{1}{2}|DC| = |DE|$, and $[D_1E_1] \parallel [DC]$. But $[D_1E_1]$ is obtained from $[DE]$ by rotating by 60°; hence $EDC = 60^\circ$. The rest is obvious.

Third solution (algebraic, but almost without calculations).

Let 1 be the length of the side of the triangle $ABC$, $x$ the length of the side of the triangle $MBP$ (Fig. 6). At $x=0$ and $x=1$ (see Fig. 7)

$$|DC|^2 - |DE|^2 - |EC|^2 = 0.$$ (1)

Equality (1) can be easily verified for $x = \frac{1}{2}$ (Fig. 8). At this point we need to increase it a little: let’s draw $(DH) \parallel (AB)$ and $(DF) \parallel (AC)$. We have $|DH| = \frac{1}{3}, |HE| = \frac{1}{12}, |EK| = \frac{1}{4}, |DF| = \frac{1}{6}$, and each of the angles $DHE, EKC$ and $DFC$ is 120°. By the cosine theorem in triangles $DHE, EKC$ and $DFC$

$$|DE|^2 = \frac{1}{9} + \frac{1}{144} + \frac{1}{36} = \frac{21}{144}, |EC|^2 = \frac{1}{16} + \frac{1}{4} + \frac{1}{8} = \frac{63}{144}, |DC|^2 = \frac{1}{36} + \frac{4}{9} + \frac{1}{9} = \frac{84}{144},$$

whence follows (1).

The left side of correspondence (1) is a square triangle from $x$ (the squares of the side lengths can be expressed from the corresponding triangles using the cosine theorem). Due to the above, this triangle at three points ($x=0, x=\frac{1}{2}$ and $x=1$) vanishes. This means that it is also effectively zero.

Consequently, (1) is satisfied for all $x$, that is, for all $x$ the triangle $DEC$ is rectangular: $DEC = 90^\circ$.

Similarly, one can check that a square is triangular.

$$|DE|^2 - \frac{1}{4} \cdot |DC|^2$$ (2)

at three points ($x=0; \frac{1}{2}, 1$) also takes on a zero value, and therefore is also effectively zero. So, $|DE| = \frac{1}{2}|DC|$, that is, $CDE = 60^\circ$.

Another, fourth, solution is based on the following observation: the triangle $DPC$ is obtained from the triangle $DKE$ by the following central subgrom: the composition of a rotation through an angle of 60° with the center $D$ and prepares with a coefficient of 2. Try to write this solution so that it is suitable for all three cases at once (see Fig. 1, 2, 3).

L. Kuptsov

◆

Answer. Any rectangle $9 \times 11$ contains 33 red cells.

Proof. Consider an arbitrary red cell $K_0$ and consider a square $3 \times 3$ centered on that cell. Cells adjacent to $K_0$ horizontally or vertically cannot be red: if, for example, as in figure 1, cell $K$ is red, then in the right or left rectangle $2 \times 3$ there will be no more red cells, so such a rectangle will have only one red cell ($K_0$) - a contradiction with the conditions. So, the cells adjacent to $K_0$ belong to the tit.

Next, in the right rectangle there should be at least one red cell - empty, for example, it will be cell $K_1$, as in figure 2. Considering the top or left rectangle

⟦folio 24⟧

Fig. 1. Fig. 2.

Fig. 3.

Fig. 4.

M639. In a tetrahedron ABCD (AC) ⊥ (BC) and (AD) ⊥ (BD). Prove that the cosine of the angle between lines AC and BD is less than |CD|/|AB|.

M640. The number $x \in [0; 1]$ is written as an infinite decimal. By rearranging its first 5 digits after the decimal point in any order, we get a new infinite decimal fraction corresponding to some number $x_1$. By rearranging the decimal notation of the number $x_1$ from the 2nd to 6th digits after the decimal point, we obtain the decimal notation of the number $x_2$. In general, the tenth square $2 \times 3$, from the conditions of the problem we deduce that in the corner of the square $3 \times 3$, opposite the cell $K_1$, there should also be a red cell - $K$, and the red cells in this square are located diagonally. Considering such squares with centers in cells $K_1$ and $K$ and moving these squares further along the “red diagonal”, from the above calculation we obtain that the entire diagonal row $KK_0K_1$ consists of red cells, and two diagonal rows above and below red are made of blue cells, as shown in figure 3. Reasoning similarly (see Fig. 3), we find that the next two (above and below) cells, and since the rectangle $9 \times 11$ can be divided into 9 squares $3 \times 3$ and 3 rectangles $2 \times 3$, we conclude that in this rectangle $9 \cdot 3 + 3 \cdot 2 = 33$ there are red cells.

It is easy to see that the coloring figure 4 satisfies the conditions of the problem. Moreover, each square $3 \times 3$ contains exactly three red cells, and since the rectangle $9 \times 11$ can be divided into 9 squares $3 \times 3$ and 3 rectangles $2 \times 3$, we conclude that in this rectangle $9 \cdot 3 + 3 \cdot 2 = 33$ there are red cells.

In the above deconstruction we have proved more than was required by the conditions of the problem - in fact, we have described all possible colorings.

Most readers got it right: the rectangle $9 \times 11$ is easily divided into 16 rectangles $2 \times 3$, after which the strip $1 \times 3$ will remain. From the condition it is easy to see that this strip can contain only one red cell, so there are only $16 \cdot 2 + 1 = 33$ red cells in the entire rectangle. After this, it is enough to give an example of a coloring that satisfies the conditions of the problem.

Note that in this problem it is not at all necessary to color the entire plane—we could limit ourselves to coloring 99 cells of the rectangle $9 \times 11$.

A. Zemlyakov

Let's draw $(BE) \parallel (CA)$ and $(AE) \parallel (CB)$ (see figure). The cosine of the angle between lines AC and BD is $|\cos DBE|$.

On the other hand, the quadrilateral $ACBE$ is a rectangle, so $|AB| = |CE|$ and $|CD|/|AB| = |CD|/|CE|$.

Note that the vertices of right angles $ACB, ADB, AEB$ lie on a sphere with diameter $AB$. The segment $CE$ is also the diameter of this sphere, therefore the angle $CDE$ is a straight line and $|CD|/|CE| = \cos DCE$. The required inequality now takes the form $|\cos DBE| < \cos DCE$.

Let $R$ be the radius of the sphere and $r$ the radius of the circle resulting from the section of the sphere by the plane $BDE$. Since this plane does not pass through the center of the sphere, $r < R$ and from the equalities $2r \cdot \sin DBE = |DE| = 2R \cdot \sin DCE$ we obtain $\sin DBE > \sin DCE$. So, $|\cos DBE| < |\cos DCE| = \cos DCE$.

Yu. Nesterenko

M640. The number $x \in [0; 1]$ is written as an infinite decimal. By rearranging its first 5 digits after the decimal point in any order, we get a new infinite decimal fraction corresponding to some number $x_1$. By rearranging the decimal notation of the number $x_1$ from the 2nd to 6th digits after the decimal point, we obtain the decimal notation of the number $x_2$. In general, the tenth square $2 \times 3$, from the conditions of the problem we deduce that in the corner in the areas of digits with numbers $10^n < k < 10^n + 5$ with all natural $n$: together with 1010 in these places we put 1100. Parts of digits from the number -

⟦folio 25⟧

the notation of the number $x_{k+1}$ is obtained by rearranging the numbers in the notation $x_k$ from $(k+1)$ to $(k+5)$ after the decimal point.
a) Prove that no matter how the numbers on each number are rearranged, the resulting sequence of numbers $x_k$ always has some limit.
Let us denote this limit by $y$.
b) Find out whether it is possible to obtain the irrational number $y$ from the rational number $x$ using the described process.
b) Come up with a fraction $x$ for which this process always leads to irrational numbers, no matter what the permutations of the digits of fives are on each line.

C) Let $y$ fractions $x$ in places with numbers $10^n < k \leq 10^n+5$ for all natural $n$ be units, the remaining numbers are zeros. Let us show that under no movement does the fraction $x$ become periodic. Let's assume the opposite: with some sequential movement of the digits of fives, the resulting periodic fraction $y$ is obtained. Note that when moving, the number of a given digit (zero or ones) cannot decrease by more than even numbers. Among the numbers from the first to the $(10^n+5)$th after the decimal point there are only $5n$ units, and, due to the previous replacement, their number in this section cannot increase. If in the period of the fraction $y$ there were $p$ digits and among them $q>0$ units, then with a sufficiently large $n$ in the section of digits with numbers $1 \leq k \leq 10^n$ there would be at least $q \cdot \left[ \frac{10^n-N}{p} \right]$ units, where $N$ is the number of digit $y$, with which the periodicity begins. Thus, we obtain the inequality $q \cdot \left[ \frac{10^n-N}{p} \right] \leq 5n$, which is not true when large $n$ are achieved. Consequently, one cannot, starting from a certain place, there must be only zeros.

Now we will show that for any movement of the fraction $x$ any number of divisions from the decimal point, units must remain. Among the digits of the fraction $x$ from the first to the $(10^n+1)$th decimal point there are a number of zeros. Since zeros farther from the decimal point have numbers starting with $10^n+6$, after moving they cannot fall into the indicated area; the number of zeros on it will not increase, and the number of ones corresponding to it will not decrease. Consequently, the digits with numbers $10^n+1 \leq k \leq 10^n+5$ units in the fraction $x$ cannot move all of them to the right - at least one unit must remain in the area from the first to the $(10^n+1)$th digit. On the other hand, they also cannot shift to the right than into fourth places, so for any $n$ in the section of the digit with numbers $10^n-3 \leq k \leq 10^n+1$ the fraction $y$ would have one unit remaining. Obviously, this contradicts the fact that the period of the fraction consists only of zero.

A. Zemlyakov

F647. A large raindrop left the clouds on a windless ride at a higher altitude. At the moment when the acceleration of the drop was 7.5 m/s², its speed was 20 m/s. Nearby, a drop fell at a constant speed $u$, hitting the side glass automatically, leaving a mark on it at an angle $30^\circ$ to the vertical. Will the GAN inspector fault a driver for speeding if the permitted speed is automatically 60 km/h? Consider the air resistance force to be proportional to the speed of the drop.

♦

Let's write down Newton's second law for the moment when the acceleration of the drop is $a=7,5$ m/s², and the speed is $v_1=20$ m/s:

$$ma=mg-kv_1^2,$$

where $kv_1^2$ is the value of the resistance force at this moment.

Near the ground, the drop moves with some constant speed $v_2$, therefore:

$$mg=kv_2^2.$$

Since the trace left by a drop on the glass makes an angle $\alpha=30^\circ$ with the vertical, the speed of the drop and the speed of the automatic $v$ are related by the relation

$$v=v_2tg\alpha.$$

From equation (1) - (3) we find the automatic speed:

$$v=\frac{v_1tg\alpha}{\sqrt{1-a/g}} \approx 23,8\text{ м/c} \approx 85,7\text{ км/ч}.$$

The fine adds to the flame.

B. Belonukin

⟦folio 26⟧

F648. The hinge structure consists of three rhombuses, the sides of which are in the ratio 3:2:1 (Fig. 1). The vertex $A_3$ moves in the horizontal direction at a speed $v_0$. Determine the speed of the vertices $A_1, A_2, B_1$ at the moment when all structures are straight.

Fig. 1.

Fig. 2.

F649. There is a mixture of water and ice in the bucket. The mass of the mixture is 10 kg. The bucket was brought into the room and they immediately began to change the temperature of the mixture. The resulting graph of $t(\tau)$ is depicted in figure. The specific temperature of water $c_B = 4200$ J/(kg K) and the temperature of ice $\lambda = 3,4 \cdot 10^5$ J/kg are known. Determine how much ice was in the bucket when it was brought into the room. Neglect the heat capacity of the bucket.

F650. To obtain a voltage, the value of which depends little on temperature, a circuit is assembled according to figure 1. The voltmeter characteristics of diode D at three different ambient temperatures $t_1 = 125^\circ C$, $t_2 = 25^\circ C$, $t_3 = -60^\circ C$ are given.

From the conditions of the problem it follows that during the movement of the structure between the lengths $l_1, l_2, l_3$ of the segments $A_0A_1, A_0A_2, A_0A_3$ the correspondence is maintained

$$l_1:l_2:l_3 = 3:5:6.$$

Therefore, the velocities of points $A_1, A_2, A_3$ correspondence

$$|\vec{v}_{A1}|:|\vec{v}_{A2}|:|\vec{v}_{A3}| = 3:5:6,$$

and therefore,

$$|\vec{v}_{A1}| = \frac{v_0}{2}, |\vec{v}_{A2}| = \frac{5v_0}{6}.$$

Let us now consider the movement of the middle link ($A_1B_2A_2C_2$) at the moment when the angles of the structure are right. In a reporting system moving with speed $\vec{v}_{A1}$, at this moment the speed $\vec{v}'_{B2}$ of point $B_2$ is directed along side $B_2A_2$; the speed of point $A_2$ is directed horizontally and is equal to

$$|\vec{v}'_{A2}| = |\vec{v}_{A2} - \vec{v}_{A1}| = \frac{v_0}{3}.$$

From the condition of inactivity of the rod $B_2A_2$ it follows (Fig. 2, a):

$$|\vec{v}'_{B2}| = |\vec{v}'_{A2}| \sin 45^\circ = \frac{v_0 \sqrt{2}}{6}.$$

We will find the speed of the point $B_2$ relative to the stationary reporting system using the cosine theorem (Fig. 2, b):

$$|\vec{v}_{B2}|^2 = |\vec{v}_{A1}|^2 + |\vec{v}'_{B2}|^2 + 2 \frac{\sqrt{2}}{2} |\vec{v}_{A1}| |\vec{v}'_{B2}| = \frac{17}{36} v_0^2,$$

$$|\vec{v}_{B2}| = \frac{v_0}{6} \sqrt{17}.$$

S. Krotov

◆

As can be seen from the graph, for the first 50 minutes the temperature of the mixture did not change and remained equal to 0°C. All this time, the heat received by the mixture from the room was used to draw ice. After 50 minutes, all the ice melted and the water temperature began to rise. Over 10 minutes (from $\tau_1 = 50$ min to $\tau_2 = 60$ min), the temperature increased by $\Delta t = 2^\circ C$. The heat supplied to the water from the room during this time is equal to $q = c_B M \Delta t = 8,4 \cdot 10^4$ J ($M = 10$ kg - the mass of water). This means that during the first 50 minutes of the mixture, the amount of heat $Q = 5q = 42 \cdot 10^5$ J came from the room. This heat was used to pull the mass $m$ of ice: $Q = \lambda m$. Thus,

$$m = \frac{Q}{\lambda} \approx 1,23 \text{ кг}.$$

A. Buzdin

◆

The diode is connected to a source in series with resistors whose resistance is $R_{06\mu}$ = $5,2 \cdot 10^3$ Ohm. Therefore, at any moment of time (at any temperature) the current in the circuit is equal to

$$I = \frac{U - U_0}{R_{06\mu}}.$$

where $U, U_0$ are the voltage values ​​at the source and at the diode at a given moment.

⟦folio 27⟧

Let us construct figure2 graphs of the dependence $I(U_\pi)$ for three different temperatures:

$$t_1 = +125^\circ C - U_{125} = 8,5 \text{ B}, \quad I_{125} = \frac{8,5 - U_{\pi,125}}{5,2} \text{ мА};$$

$$t_2 = +25^\circ C - U_{25} = 6 \text{ B}, \quad I_{25} = \frac{6 - U_{\pi,25}}{5,2} \text{ мА};$$

$$t_3 = -60^\circ C - U_{-60} = 3,875 \text{ B}, \quad I_{-60} = \frac{3,875 - U_{\pi,-60}}{5,2} \text{ мА}.$$

The intersection points of these graphs with the current-voltage characteristics of the diode (for the corresponding temperatures) determine the voltage values ​​​​on the diode and the current in the circuit at a given temperature. From figure 2 one finds (approximately, of course):

$$U_{\pi,125} = 0,77 \text{ B}, \quad I_{125} = 1,48 \text{ мА};$$

$$U_{\pi,25} = 0,8 \text{ B}, \quad I_{25} = 1 \text{ мА};$$

$$U_{\pi,-60} = 3,875 \text{ B}, \quad I_{-60} = 0,58 \text{ мА}.$$

Voltage value correspondence $U_{AB} = U_\pi + I \cdot 0,2$ (V) between terminals $A$ and $B$ —

$$U_{AB,125} = 1,07 \text{ B};$$

$$U_{AB,25} = 1 \text{ B};$$

$$U_{AB,-60} = 0,94 \text{ B}.$$

Thus, the temperature coefficient characterizing the relative (relative $U_{AB,25}$) change in voltage $U_{AB}$ when the temperature changes from $-60^\circ C$ to $+125^\circ C$ is equal to

$$\alpha = \frac{\Delta U_{AB}}{\Delta t \cdot U_{AB,25}} \approx 7 \cdot 10^{-4} \text{ град}^{-1}.$$

Compared to the original temperature coefficient $\alpha_0 = \frac{25 \cdot 10^{-3}}{6} \approx 4 \cdot 10^{-3} \text{ град}^{-1}$, the resulting value $\alpha$ is approximately 6 times smaller.

Think about how to change the resistance of the resistors in order to almost completely compensate for the temperature instability of the source.

A. Zilberman

F651. A science fiction story describes an emergency situation in which an astronaut of mass $M = 100$ kg finds himself at a distance of $l = 100$ m from a ship with a glass of frozen water. Ensuring sublimaria (evaporation) of ice, the astronaut returns to the ship. Is this method of return realistic? Estimate how long it takes for the astronaut to return to the spacecraft. Consider that ice sublimation occurs at a constant temperature of $T = 272$ K. The saturation vapor pressure at this temperature is $p_H = 550$ Pa. The universal gas constant is $R = 8,3 \times 10^3$ J/(kmol K). Set the dimensions of the glass and the mass of ice yourself.

If the glass is tightly closed, then the number of molecules falling on the ice surface per unit time will be equal to the number of molecules sublimating from the surface (dynamic equilibrium); under this condition, the saturation vapor pressure $p_H$ is changed. Both indicated mass flows are equal according to the model $\frac{1}{6} \rho_H \bar{v} S$ (kg/s), where $\rho_H = p_H \mu/RT$ is the density of saturated vapors, $S$ is the density of the ice surface, $\mu$ is the molar mass of ice, $\bar{v} \approx \sqrt{3RT/μ}$ is the average speed of molecules, the multiplier $1/6$ (or, more precisely, $1/4$) takes into account the direction of movement “in one direction out of six possible.” When the glass is opened, the flow of molecules flying away is the same, but there are no molecules returning; the pressure terrr is $1/2p_H$. Let us estimate the time of complete evaporation by substituting the initial mass of ice $m \approx 0,2$ kg, the density of the glass $S \approx 30$ cm$^2$, $\mu = 18$ kg/kmol:

$$\tau \sim \frac{m}{\frac{1}{6} \rho_H \bar{v} S} \approx \frac{6m}{p_H S} \sqrt{\frac{RT}{3\mu}} \approx \frac{6 \cdot 0,2}{550 \cdot 3 \cdot 10^{-3}} \sqrt{\frac{8,3 \cdot 10^3 \cdot 272}{3 \cdot 18}} \approx 150 \text{ c}.$$

Note that as a result, the evaporation time will be longer, since the probability for molecules caught on the ice surface to “stick” to it is equal to the so-called condensation coefficient and, naturally, less than 1; Accordingly, a factor must be introduced into the evaporation flow, less

⟦folio 28⟧

1. Further, perhaps not all molecules, having evaporated, can immediately fly away to infinity; Some of them can return back due to colliding in the vapor phase. Thus, we obtained an estimate for the evaporation time of sizu.

While the ice is evaporating, the astronaut's acceleration is $a = p_H S/2M$. During this time he will fly a distance $L = a\tau^2/2 \approx 100\text{ m} = l$.

Considering the approximate nature of our estimates, we can say that the astronaut will return to the ship in time $\gtrsim 100\text{ c}$.

A. Stasenko

F652. The circuit shown in figure consists of two identical resistors $R_2 = R_3 = R$ and two identical non-linear resistors $R_1$ and $R_4$, the voltemeric characteristic of which has the form $U = \alpha I^2$, where $\alpha$ is the neocotary eternal constant coefficient. At what direction of the power source $U_0$ is the current through the galvanometer $\Gamma$ equal to zero?

F653. Some elements Z, connected to a battery with emf $\varepsilon = 10\text{ B}$ and internal resistance $r = 10\text{ K}\Omega$, are connected to an external current source as shown in figure 1. The voltmeter characteristic of such a circuit is shown in figure 2 (black curve). Plot the voltemeric characteristic of element Z.

Fig. 1. Fig. 2. $I_6(U)$

F654. The mass M stand is placed on the main table. A ball of mass m is attached to a tripod on a thin thread of length l. The thread is deflected by a small angle a and released (Fig. 1). Narip

Let current flow through a branch of the circuit I. Since both linear and nonlinear resistors are the same, the same currents flow in the branches of the circuit. The voltage of the power supply is

$$U_0 = IR + \alpha I^2.$$

So through the galvanometer is zero when the potential of point A is equal to the potential of point B. Therefore

$$IR = \alpha I^2 \Rightarrow I = \frac{R}{\alpha}.$$

Substituting this current value into equation (*), we find the direction of the source at which the current through the galvanometer is zero:

$$U_0 = 2 \frac{R^2}{\alpha}.$$

V. Skorovarov

Let's construct the voltage meter characteristic of the battery. According to Ohm's law for a complete circuit, the direction $U_6$ on the battery and the current $I_6$ flowing through the battery are related by

$$U_6 = \varepsilon - I_6 r.$$

Since the Z cell and the battery are connected in parallel, $U_6 = U_2 = U$ (U is the direction of the external source).

At figure 2 the voltmeter characteristic of the battery is blue straight.

The current $I_2$ flowing through element Z is equal to the algebraic difference $I - I_6$. To construct the voltemer characteristic of element Z, for each fixed direction value $U$, find the value $I_2$ by subtracting the ordinate $I_6$ of the corresponding point of the voltemer characteristic $I_6(U)$ from the ordinate of the corresponding point of the voltemer characteristic of the circuit.

At figure 2, the voltemeric characteristic $I_2(U)$ is the red curve.

V. Mozhaev

At a small deflection angle α, the movement of the ball differs little from horizontal. In the horizontal direction, no external forces act on the system, and the momentum of the system (more precisely, the projection of the momentum on the horizontal axis) remains constant - equal to zero. Therefore, when the ball moves, the shin moves in the opposite direction

⟦folio 29⟧

corresponds to a graph of the speed of the shativa versus time. The collided ball with the base of the shativa is absolutely elastic.

Fig. 1.
$$\begin{align*}
|AO|: |OB| &= m : M; \\
A'O'|: |O'B| &= m : M \\
A'O'| + |O'B| &= l
\end{align*}$$

$$\Rightarrow |O'B| = l \frac{M}{m+M}.$$

Fig. 2. $\tau = \frac{\pi}{2} \sqrt{\frac{l}{g} \frac{M}{m+M}}$.

F655. Currently, solenoids with superconducting windings are used. Such solenoids can create a magnetic field for a long time without consuming energy. However, if for any reason a section of the solenoid winding loses its superconducting properties, an accident will occur. In this area, a large amount of current will be released and an explosion will occur. Come up with the simplest device to eliminate such accidents (do not try to come up with any circuits with a relay that opens the circuit - they will not help).

side; The absolute values ​​$v$ and $u$ of the velocities of the shark and the shativ (more precisely, the projections of the corresponding velocities on the horizontal axis) are related by the relation

$$mv = Mu.$$

The center of mass of the system (point $O$ on figure 1) remains stationary; This means that the point $O'$ also remains fixed.

Thus, the movement of the ball is the oscillation of a magnet with the length of the thread

$$l' = |O'B| = l \frac{M}{m+M}$$

(cm. Fig. 1). The frequency of these oscillations is

$$\omega = \sqrt{\frac{g}{l'}} = \sqrt{\frac{g}{l} \frac{m+M}{M}};$$

ball speed -

$$v = v_M \sin \sqrt{\frac{g}{l}} \frac{m+M}{M} t,$$

where $v_M = \omega x_M = \sqrt{\frac{g}{l}} \frac{m+M}{M} l \sin \alpha$ is the maximum (in my opinion) speed value, $x_M = l \sin \alpha$ is the amplitude of the Shark mixture.

Using the relation (*), we find the speed of the shativa:

$$u = \left( \frac{m}{M} \sqrt{\frac{g}{l}} \frac{m+M}{M} l \sin \alpha \right) \sin \sqrt{\frac{g}{l}} \frac{m+M}{M} t =$$

$$= u_M \sin \sqrt{\frac{g}{l}} \frac{m+M}{M} t.$$

After each elastic collision, the directions of velocities $v_M$ and $u_M$ are reversed (check this).

A graph of the shativ speed versus time is shown on figure 2.

A. Zilberman

◆

The simplest way to prevent an accident when any part of the winding is connected to a superconducting connection is to joke the winding. Previously, massive copper conductors were used as jesters, which were placed outside the winding.

Currently, a superconducting winding is made from a bundle of thin superconductor strands enclosed in a matrix of metal with high electrical and thermal conductivity—copper or aluminum. When a superconducting connection is established in any part of the winding, the current flows through a massive copper conductor with low resistance.

G. Myakshev
