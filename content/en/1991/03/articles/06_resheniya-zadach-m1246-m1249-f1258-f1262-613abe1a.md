---
id: 1991-3-resheniya-zadach-m1246-m1249-f1258-f1262-613abe1a
issue: kvant_1991_3
year: 1991
number: "3"
title: Solutions to problems M1246—M1249; F1258—F1262
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 21
page_last: 30
page_labels: 19-28
lang: en
source: kvant_digital
extraction: vision
content_sha256: 046fb7f778cada28b2cb363bbfef2031c3bdf175d3d9f8b476662f71e00ccc0c
prompt_sha256: draft-1
translated_from: content/ru/1991/03/articles/06_resheniya-zadach-m1246-m1249-f1258-f1262-613abe1a.md
source_content_sha256: 8c0e6b3b9cc65e22307bb17765b5258fcd54518df606adec3bf5d74d6f1bceeb
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 19⟧

Problem solutions
M1246—M1249, F1258—F1262

M1246. Prove that in any arithmetic progression whose members are natural numbers there are two numbers with the same sum of digits.

Let $a$ be the first term and $d$ the difference of the progression. We can, of course, assume that $d>0$. Then all terms of a progression of the form $a+10^n d$, where $n$ is large enough (so $10^n>a$), have the same sum of digits, equal to the sum of all digits $a$ and $d$.

S. Genkin

⟦folio 20⟧

---
running_head:
folio:
---

M1247. Is it possible to cover the entire plane with squares with side lengths 1, 2, 4, 8, 16, ... (without overlapping), using each square no more than a) ten times; b) once?

Fig. 1.

Answer: a) it is possible; 6) it is impossible.
a) An example of a covering (where the square on side 1 is used 4 times, and the rest - 3 times each) is given on figure 1.
6) Suppose there is a covering in which all squares are distinct. Since the sum of all numbers, without exceeding $2^n$, is less than $2^n (1+2+2^2+\ldots+2^{n-1}=2^n-1)$, then to each side of any of the square

Fig. 2.

Fig. 3.

The product of our coating should be applied to the side of a large square. It follows that each vertex of the square must lie on the side of the large square (if vertex B of the square ABCD lies on the side of the large square applying to side AB (Fig. 2), then vertex C will lie on the side of the large square applying to BC, etc.). Let us now consider the named of all coverage squares. The four squares will be applied to it as shown in figure 3. Consider the larger of these squares - let it apply to the side AB of the smallest one (at figure is the head square). Then vertex A of this square does not lie on the side of a larger square than it. We got a contradiction.

D. Fomin

M1248. A segment contains several smaller segments that cover it entirely.
a) Prove that any positions of these segments, discard any position - right or left - then the remaining positions will cover at least three times the length of the original segment.

Let us first note that it is possible to exclude segments entirely contained in other segments. Next, having numbered the segments in an arbitrary order, we will perform the following operation on each one in turn: we will replace it with the smallest segment with the same middle so that the segments still cover the original one. (In this case, the selected terms are reduced, and their union will only become smaller.) Repeating these operations, we arrive at a system in which each segment can have common internal points (intersect along the segment) with no more than one of the others. Thus, the entire original segment is divided into pieces, each of which is covered by one or two segments contained in it. Therefore, it is sufficient to prove the statement only for the case of two segments. This is not difficult in both cases.

⟦folio 21⟧

---
running_head:
folio:
---

Statement a) is obvious if the left halves of the segments do not intersect: after all, the sum of the lengths of two segments is greater than the length $d$ of their union, therefore the sum of their halves is greater than $d/2$. If the left halves intersect (Fig. 1), then the statement follows from the fact that the midpoint of the right segment lies to the right of the midpoint $C$ of the entire piece $AB$ under consideration, i.e. these halves cover $AC$.

Statement 6) is obvious if at least one of the segments is not less than $2/3$ $d$, where $d$ is the piece to be covered. In another case (Fig. 2), the distance between their midpoints $E$ and $F$ is not less than $d/3$, and the selected halves of the segments either do not intersect or cover the segment $EF$.

D. Fomin

M1249*. There are $n>6$ cities in the kingdom of Olympia, each two of which are connected by one one-way road. Moreover, it is not possible to travel from every city to any other (without violating traffic rules).
a) Prove that the king can choose one of the cities $u$, changing the direction on all roads entering and leaving it, adding a tone so that it is possible to travel from any city to any other.
b) Is this statement true for $n=6$ cities?

Let us first prove statement a) for $n=7$, cities. We will say that two cities are equivalent if it is possible to travel from each of them to the other. Then all 7 cities will be divided into groups of cities that are equivalent to each other, and of each two groups, one “majors” the other, in the sense that all roads from one group lead to another. Distance first, when there are more than two such groups. Let $y$ be the penultimate group (Fig. 1). By selecting any city $Y$ in group $y$ and changing the directions of all roads connecting it with other cities, we get what we are looking for: from $Y$ you can now get to group $a$, and from it to any other city; and vice versa, you can get to $Y$ from the last group $z$, and to it from any other city. It remains to consider first when there are only two groups (Fig. 2). Let there be $x$ cities in the group $a$, and $(7-x)$ in the group $b$. We can assume that $x$ is at least 4 (otherwise we will replace all the arrows with opposite ones). Let's look at three groups: 1) $x=4$; 2) $x=5$; 3) $x=6$. However, let us immediately replace that the group $x=5$ is impossible, since the group cannot consist of two equivalent cities.

For further purposes it is convenient to use the following lemma:
In a group of any number of $k>3$ equivalent cities, there is always a closed path passing (in the direction of the arrows) through all the cities once (“Hamiltonian cycle”).

We give the proof of the lemma at the end of the solution.

Let's look at the remaining groups. 1) At $x=4$ the group looks as shown in figure 3 (the direction of the sixth, unshown road is unimportant). As the desired city, you need to win $C$. 3) At $x=6$ the group $a$ looks as shown in figure 4 (the direction of other roads does not yet exist). Assuming that there is no city in which, if the direction of all the roads in which changes, it will be possible to get from it to any city from the group $a$, we can conclude that the roads are directed as shown in figure 5. But then any of the six cities can be chosen as the desired city.

⟦folio 22⟧

---
running_head:
folio:
---

So, for $n=7$ the statement of problem a) is proven.
For $n>7$ it can be proved by induction.
First of all, let us choose from the cities one that has at least two roads entering and from which at least two roads exit. (If there is no such city, then there are 4 cities, each of which includes no more than one road, or 4 cities, from which no more than one road exits. But this is impossible, since the six roads between the four cities have 6 “beginnings” and 6 “ends”.) Among the remaining ($n-1$) cities, by the induction hypothesis, there is one in which the desired effect can be achieved by the “formation” of all the roads. It is, very/no, suitable for all $n$ cities.
Figure 6 shows that for $n=6$ cities the statement is false, i.e. the answer to question 6) is negative.
(It is interesting that this example is the only one, so to speak, up to isomorphism.)
In conclusion, we prove the lemma on the Gallton cycle (for $k=3$ cities it is very). We will argue by induction. Let's delete any of the $k>3$ cities - city $X$. If the remaining ($k-1$) cities after this form several equivalence groups (as in figure 1, and neoctor arrows from the group $z$ go to $X$, and from $X$ to the group $a$), then since in each of the groups $a, b, ..., y, z$ there is a Galiltonian cycle by the induction assumption, they are very much composed of Gallton cycle, passing through all $k$ cities. If the remaining ($k-1$) cities form one equivalence group, then it contains a Galiltonian cycle, and among the roads connecting these cities with $X$ there are both those entering $X$ and leaving it. Going through this cycle, we can find two neighboring cities such that from the first there is a road to $X$, and in the second there is a road from $X$ (Fig. 7). So we can include $X$ in this loop.
Note that using this lemma we can prove statement a) immediately for any $n$ greater than 7, approximately in the same way as was done above for $n=7$ cities.
I. Itgenberg, D. Fomin

F1258. There is a coil of radius $R$ on a horizontal table. A thin, weightless thread is wound on a reel; the radius of the winding is $r$. The thread is passed through a small hole at a height of $h$ from the table surface ($h>R$). At the initial moment, the coil is motionless, and the thread is

It is clear that the coil positioned as shown in figure 1 starts on the right. Let us determine in what position the coil will have maximum speed.

At an arbitrary moment of time, three forces act on the coil - the thread tension force $T$, equal in magnitude to $F$, the gravity force $Mg$ and the support reaction force $F_p$ (Fig. 2). Let us consider the moments of all forces relative to the fulcrum. Forces $Mg$ and $F_p$ have zero moments, and the moment of force $T$ accelerates the rotation of the coil clockwise and, therefore, increases its speed

⟦folio 23⟧

---
running_head:
folio:
---

horizontal movement to the right. It is clear that this speed will become maximum when the continuation of the path passes through the support point (point $D$ on figure 3). With further movement, the moment of force $T$ will become freezing, after some time the coil will stop and roll back.

To calculate the maximum speed of the coil, we use the law of conservation of energy - the kinetic energy of the coil is equal to the force of external forces. The only source of energy here is the experimenter, who pulls the end of the thread with a force $F$. The work done by this force is equal to

$$A = F \Delta l,$$

where $\Delta l$ is the length of the thread stretched through the hole when the coil moves from the initial position to the position we are interested in. Let's find $\Delta l$ by comparing the “free” length of the thread in the initial and final positions (see Fig. 3).

Let point $O$ be the end of the thread at the initial moment, and point $G$ be the point of contact between the thread and the reel at the final moment. To find the continuation of this point at the initial moment, we mentally roll the coil back. In this case, the thread will be partially wound on the coils, and point $G$ will move to point $G_1$ (the intermediate point $G_2$ is obtained from $G$ by parallel transfer of the coil from the final position to the initial one). So, the length of the section of thread under consideration in the final position is $BO + OG$, in the initial position $OC + CG_1$. Equating these two expressions, we find

$$\Delta l = BO = OC + CG_1 - OG.$$

Let's calculate all the quantities included here. Directly from figure 3 we obtain

$$OC = h - R, OG = OD - DG = h / \cos \alpha - R \cos \alpha.$$

It remains to calculate the length of the thread wound on the reel. Let's divide this length into two:

$$\cup CG_1 = \cup CG_2 + \cup G_1 G_2.$$

When the coil rolls from the final position to the initial position, its angle of rotation is equal to

$$\beta = \angle G_1 E_1 G_2 = \frac{EE_1}{R} = \frac{AD - r}{R} = \frac{h tg \alpha - r}{R}.$$

For poses, the length of the thread in the area from $G_1$ to $G_2$ is

$$\cup G_1 G_2 = r \beta = r \frac{h tg \alpha - r}{R}.$$

At the same time

$$\angle CE_1 G_2 = \angle EDG = \alpha,$$

poseable

$$\cup CG_2 = r \alpha.$$

Finally we get

$$\Delta l = h - R + \frac{r}{R} (h tg \alpha - r) + r \alpha - \frac{h}{\cos \alpha} + R \cos \alpha,$$

⟦folio 24⟧

---
running_head:
folio:
---

or, expressing all functions of angle $\alpha$ in terms of $\sin \alpha = r/t$,

$$\Delta l = r \arcsin \frac{r}{R} - \frac{r^2}{R} + (h - R)(1 - \sqrt{1 - \left(\frac{r}{R}\right)^2}).$$

Let us now calculate the kinetic energy of motion with a speed of $v$, which rotates with a linear speed, also equal to $v$, therefore the kinetic energy of the coil is equal to

$$E_k = \frac{1}{2} M v^2 + \frac{1}{2} \frac{M}{2} v^2 = \frac{3}{4} M v^2.$$

Now from the law of conservation of energy $E_k = A$ we get the answer:

$$v = \sqrt{\frac{4}{3} \frac{F}{M} \left(r \arcsin \frac{r}{R} - \frac{r^2}{R} + (h - R)\left(1 - \sqrt{1 - \frac{r^2}{R^2}}\right)\right).}$$

It is interesting to note that the formula gives meaningful values ​​for $v$ and at $r = R$, although in this case the equilibrium of the moments of forces (see Fig. 3) ​​never occurs - the moment of the tension force is not always accelerated by the coil. At the same time, although the reel is infinite, only a finite section of thread passes through the hole, and the speed of the reel is limited.

A. Khodulev

F1259. The whistle emits a sound of frequency $f_0 = 2000 \Gamma$. How will the frequency of sound change if the air temperature rises from 20 to 40 degrees Celsius? What tone will a whistle produce in an air bell for underwater work, in which a breathing mixture of green and oxygen is supplied at a pressure of 1.5 atm? The partial pressure of oxygen is assumed to be 0.3 atm. How will the tone of a person’s speech change in this bell? Will it be necessary to rearrange the work so that it sounds in the bell the same as outside?

The frequency of the whistle is determined by the size of the whistle (dependence - inverse) and the speed of sound (dependence - direct). If the prebebrian changes the size of the whistle when heated from 20 to 40 degrees Celsius, then everything is determined by an increase in the speed of sound (which is proportional to the square root of the absolute temperature) by 313/293 = 1.033 times. This means that the frequency will become 2066 Hz. The difference, of course, is not very big, but it is completely unacceptable for musical instruments - especially in an orchestra. When constructing two instruments, special measures are taken so that the setting practically does not change when the temperature changes within specified limits. Think for yourself how this can be achieved.

The second question is somewhat more complicated. Let us remember that we usually breathe a mixture of oxygen (its molar mass is 32 g/mol) and nitrogen (28 g/mol). There is more nitrogen, and the resulting gas mixture has an average molar mass of 29 g/mol. A mixture of helium and oxygen has a clearly lower molar mass, and therefore the speed of sound in the mixture will be greater, and the tone of human speech will be higher (after all, the “dimensions” of the vocal apparatus remain the same). It remains to find the molar mass of the mixture of oxygen and helium. It can be done like this.

⟦folio 25⟧

---
running_head:
folio:
---

In volume $V$ the number of moles of oxygen is $v_{\kappa} = p_{\kappa}V/(RT)$, helium is $v_{\mathrm{r}} = p_{\mathrm{r}}V/(RT)$, and the total mass of the mixture is $m = m_{\kappa} + m_{\mathrm{r}} = M_{\kappa}v_{\kappa} + M_{\mathrm{r}}v_{\mathrm{r}}$. Then the molar mass of the mixture
$$M = (p_{\kappa}M_{\kappa} + p_{\mathrm{r}}M_{\mathrm{r}})/(p_{\kappa} + p_{\mathrm{r}}) = 9,6 \text{ г/моль}.$$
So, the pitch of the tone will increase $\sqrt{29/9,6} = 1,74$ times (you get the “voice of Buratino”), and the frequency of the tone becomes equal to 3480 Hz.
But you don’t have to rebuild the guitar - the frequency of vibration of the string is determined by completely different parameters.
A. Zilberman

F1260. The well-known infinite chain of resistors (Fig. 1) contains resistors $r$ and $R$. What is the resistance changed between two neighboring nodes (separated by one resistor $r$)? What is the change in resistance between two nodes that are very far apart? Find this resistance in the general case when there are $n$ resistors $r$ between the points of interest to us.

In the first case, the chain can be redrawn as shown in figure 2, where $\rho$ is the resistance of the semi-infinite chain shown in figure 3. From the correspondence
$$r + \frac{R\rho}{R + \rho} = \rho$$
easy to get
$$\rho = r(1 + \sqrt{1 + 4R/r})/2.$$
Then the resistance changed between two neighboring nodes $A$ and $B$ will be equal to
$$R_1 = R_{AB} = \frac{2R\rho r}{2R\rho + rR + r\rho} = \frac{2Rr}{\rho + 2R}.$$
If nodes $A$ and $B$ are very far from each other, then the circuit can be replaced as in Figures 4 and 5. Hence
$$R_{\infty} = R_{AB} = \frac{2\rho R}{2R + \rho}.$$
Now let there be $N$ links in the chain between $A$ and $B$. Let's apply the principle of superposition. Let's connect a battery with EMF $\mathcal{E}$ (Fig. 6) between node $A$ and the bottom wire $O$. If we take the potential of the wire as zero, then the potentials and points will be equal
$$\varphi_A = \mathcal{E}, \varphi_B = \mathcal{E}(1 - r/\rho)^N, \varphi_0 = 0, I_A = I = \mathcal{E}(1/R + 2/\rho), I_B = 0, I_0 = -I.$$
If, together with the previous one, we take a battery of the opposite polarity and connect it between $O$ and $B$, then

Fig. 1.
Fig. 2.
Fig. 3.

⟦folio 26⟧

---
running_head:
folio:
---

tactics and potentials will be equal
$$\varphi'_A = -\mathcal{E}(1 - r/\rho)^N, \varphi'_B = -\mathcal{E}, \varphi'_0 = 0,$$
$$I'_A = 0, I'_B = -I, I'_0 = I.$$

Let's add up the voltages and voltages in these two situations and get
$$\varphi''_A = \mathcal{E}(1 - (1 - r/\rho)^N), \varphi''_B = -\mathcal{E}(1 - (1 - r/\rho)^N), \varphi''_0 = 0,$$
$$I''_A = I, I''_B = -I, I''_0 = 0.$$

Since no current flows through node $O$, we can assume that the resistance between $A$ and $B$ is equal to
$$R_N = R_{AB} = \frac{\varphi''_A - \varphi''_B}{I} = \frac{2R\rho}{2R + \rho} \left(1 - \left(1 - \frac{r}{\rho}\right)^N\right).$$

Note that with $N = 1$ the answer is obtained for the first case, and with $N \to \infty$ - for the second.

P. Rodin

F1261. To a battery with a voltage of $U_0 = 4$ V, two capacitors are connected in series, the capacitance of which is $C_1 = 1$ µF and $C_2 = 3$ µF. Connect inductor $L = 1$ in parallel with capacitor $C_1$. Find the amplitude of the current in the coil. By the time the coil is connected, the voltage on the capacitors is considered to be steady. Losses in the circuit can be claimed.

To find the maximum current through the coils, the easiest way is to use the law of conservation of energy. At the moment when the current through the coils is maximum, connect the inductive emf $L = 1$ Gi in parallel with the capacitor $C_2$. Before connecting the coil, the charges of each capacitor were equal
$$q_0 = C_1 C_2 U_0 / (C_1 + C_2).$$

This means that the battery “pushed” additional charge through the circuit
$$q_{6ат} = \Delta q = C_2 U_0 - q_0 = C_2^2 U_0 / (C_1 + C_2)$$
and did the work
$$A_{6ат} = q_{6ат} U_0.$$

Let's write down the energy balance:
$$W_{нач} + A_{6ат} = W_{кон},$$

or
$$C_1 C_2 U_0^2 / (2(C_1 + C_2)) + C_2^2 U_0^2 / (C_1 + C_2) = C_2 U_0^2 / 2 + LI_M^2 / 2.$$
From here we find the maximum current value in the coil:

⟦folio 27⟧

---
running_head:
folio:
---

$$I_M = C_2 U_0 / \sqrt{L} \left( \bar{C}_1 + \bar{C}_2 \right) = 6 \cdot 10^{-3} \text{A}.$$

So through the coil it has a zero average value and changes according to the harmonic law, which means that the amplitude of the current is equal to the calculated value. Try to find an independent part of the oscillations in the system. Just in case, the answer is: approximately 80 Hz.

R. Aleksadrov

F1262. An electric fan with asynchronous movement, connected to a 220 V network, develops 1800 rpm. So that it does not hum so loudly, it is connected through an auto-former to a voltage of 127 V. At what speed will it rotate? Consider that the load on the fan blades is determined by the overcurrent effect of the “squirrel wheel” current.

In a single-phase motor, rotation of the magnetic field is achieved due to a 90° phase shift of sinusidal alternating currents of equal magnitude flowing through two mutually perpendicular stator windings.

In this case, the x-component of the magnetic field is equal to $B_x = B_0 \cos \omega t$, the y-component is $B_y = B_0 \sin \omega t$, and the resulting field $\bar{B}_0$ rotates in the XY plane counterclockwise with a frequency of $\omega$ supply currents (Fig. 1).

Let us consider the forces acting on the rotor, considering it for simplicity to be a rectangular metal frame from the sides $a$ and $b$. First, we discussed the case when the frame with the axis of rotation OZ is closed motionless in the YZ plane, and the magnetic field induction vector $\bar{B}_0$, lying in the XY plane, rotates around the axis of the frame with a frequency $\omega_0$ counterclockwise (Fig. 2). The field component perpendicular to the plane of the frame is equal to

$$B_\perp = B_0 \cos \omega_0 t,$$

parallel -

$$B_\parallel = B_0 \sin \omega_0 t.$$

Magnetic flux, arbitrary frame, is equal to

$$\Phi = B_\perp S = B_0 S \cos \omega_0 t,$$

where $S = ab$ is the area of ​​the frame. The induced emf arising in the frame is

$$\delta_i = -\Phi'(t) = B_0 S \omega_0 \sin \omega_0 t,$$

and the current in the frame is

$$I = \delta_i / R = B_0 S \omega_0 / R \sin \omega_0 t,$$

where $R$ is omniche resistance. The torque relative to the frame axis is created only by the components of the Ampere forces perpendicular to the YZ plane, acting on the sides parallel to the axis—

$$F_{1\perp} = F_{2\perp} = F = B_\parallel Ib = B_0^2 b S \omega_0 / R \sin^2 \omega_0 t.$$

The total moment of these forces

$$M = 2 F a / 2 = B_0^2 S^2 \omega_0 / R \sin^2 \omega_0 t.$$

Its average value over the period $T = 2 \pi / \omega_0$ is

$$\bar{M} = B_0^2 S^2 \omega_0 / (2 R).$$

⟦folio 28⟧

---
running_head:
folio:
---

Since the physical processes discussed above are determined only by the mutual orientation and relative angular velocity of rotation of the field and the frame, the expression for the moment of force unwinding the frame in the case of rotation of the frame behind the field with a frequency $\omega$ of the frame can be obtained by simply replacing $\omega_0 \rightarrow \omega_0 - \omega$:

$$\bar{M}_p = B_0^2 S^2 (\omega_0 - \omega) / (2R).$$

At $\omega = 0$, when the frame is motionless, the amplitudes of the induction current and Ampere forces are maximum. At $\omega = \omega_0$, when the frame rotates synchronously with the field, the induced emf, current and torque are zero, which can only happen if there is no load on the motor shaft.

As a result of the device, in particular in our fan, the rotor can be represented as a combination of several frames, however, in this case, the spinning moment of forces will be proportional to the square of the amplitude of the magnetic field induction inside the stator and the difference in the rotation frequencies of the field and the rotor. The maximum magnitude of the magnetic field induction $B_0$ is proportional to the amplitude $I$ of the alternating current flowing through the stator windings, and this value, according to the conditions, is proportional to the direction $U$ in the network. Pozny

$$\bar{M}_p \sim B_0^2 (\omega_0 - \omega) \sim I_0^2 (\omega_0 - \omega) \sim U^2 (\omega_0 - \omega).$$

Transition from circular frequencies to ordinary ones, we obtain an expression of the form

$$\bar{M}_p = \alpha U^2 (v_0 - v),$$

where $\alpha$ is a constant proportionality coefficient.

Now let's consider the action of forces causing brake deceleration, which in our case is caused by the flow driven by the influence. Let the fan create a jet of air with area $S$ moving at speed $v$. Then, in a short time $\Delta t$, a mass of air $\Delta m = \rho Sv \Delta t$ flows into the flow, where $\rho$ is the air density. The change in mechanical energy of this air is

$$\Delta E_k = \Delta m v^2 / 2 = \rho Sv^3 \Delta t / 2,$$

and the mechanical power developed by the fan is equal to

$$N = \Delta E_k / \Delta t = \rho Sv^3 / 2.$$

Since (from kinematic messages) the speed of the jet is proportional to the rotation frequency of the blades, and the power is related to the moment of forces by the correspondence $N = M\omega$, for the braking moment of forces acting on the fan blade, we obtain

$$M_T \sim \omega^2,$$ or $M_T = \beta v^2,$

where $\beta$ is a constant proportionality coefficient.

Equating the spinning and braking torque of the forces acting on the engine rotor, we obtain

$$\alpha U^2 (v_0 - v) = \beta v^2,$$ or $v^2 = k U^2 (v_0 - v),$
