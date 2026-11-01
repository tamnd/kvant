---
id: 1986-7-resheniya-zadach-m971-m975-f983-f987-7acaf4b3
issue: kvant_1986_7
year: 1986
number: "7"
title: Solutions to problems M971—M975; F983—F987
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 39
page_last: 46
page_labels: 37-44
tag: ZYPJ
lang: en
source: kvant_digital
extraction: vision
content_sha256: 42d76865634142c70be3f3841c40d5a1420ab6316dd3e8ad9a2c6cce4fb3f851
prompt_sha256: draft-1
translated_from: content/ru/1986/07/articles/13_resheniya-zadach-m971-m975-f983-f987-7acaf4b3.md
source_content_sha256: 6c77df924fe272135f886792fc7dfc23653e439f2d2d63e4680e35e6b038a8c8
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 37⟧

pe write the words: "KVANT'S PROBLEMS" and the numbers of all the solved problems; in your letter enclose an unstamped self addressed envelope — we shall use it to send you the correction results. At the end of the academic year we sum up the results of the Kvant problem contest. If you have an original problem to propose for publication, please send it to us under separate cover, in two copies (in Russian or in English), including the solution. On the envelope write NEW PROBLEM IN PHYSICS (or MATHEMATICS).

Problems M991—M995 were proposed to us by the Bulgarian magazine «Matematika».

P1004. A thin uniform rod which can rotate freely in the vertical plane about a horizontal axis passing through its upper extremity hangs motionless above water (see figure Pisc. 2); the length of the rod is $l$, its density $\rho$ ($\rho$ is less than the density of water). Slowly lowering the axis, the rod is immersed in water. Find and plot the dependence between the angle formed by the rod with the vertical and the distance from the axis to water level.

D. V. Belov

P1005. A heater in which a constant temperature $T_1$ is maintained and a refrigerator with inner temperature $T_0 < T_1$ contain coils of wire. The wire from the coil in the refrigerator comes out of it and goes into the heater to the other coil. The coils rotate so that the wire from the cold coil moves toward the hot coil with velocity $v$. The wire section area is $s$, the volume specific heat is $c$. In order to keep the temperatures $T_0$ and $T_1$ constant, it was necessary to increase the power of the heater by $\Delta E_x$ and decrease the production of cold by the refrigerator by the same magnitude. Find $\Delta E_x$.

D. V. Pavlov

P1006. Determine the resistance of the resistor circuit shown on figure Pisc. 3. The resistances are given in ohms.

S. S. Krotov

P1007. A light ray falls on a solid sphere made out of two glass hemispheres of refraction indices $n_1$ and $n_2$ ($n_1 > n_2$). The sphere is rotated with angular velocity $\omega$ about an axis perpendicular to the ray (see figure Pisc. 4). Find the maximal size of the spot obtained on a screen placed directly behind the sphere.

L. G. Markovich

Problem solutions

M971—M975; F983—F987

Since the total number of wins of all teams is equal to the number of losers and each team played 7 matches, the average number of wins per team is 3.5. Consequently, at least one of the teams - let's call it $A$ - won at least 4 matches. Similarly, for each of the 4 teams that lost $A$, there is an average of 1.5 wins in matches between them, so one of them - let's call it $B$ - won against at least two. Of these two teams, one ($C$) beat the other ($D$). Teams $A, B, C, D$ form the required four.

It is easy to see that the statement of the problem can be generalized: if the $2^{n-1}$ team participated in the tournament, then it is always possible to win the n team $A_1, \dots, A_n$ so that each of them beats the team with higher numbers.

It is interesting to find out at what minimum $N$ (depending on $n$) the selected condition is satisfied for any tourer with the participation of the $N$ team. The tour diagrams shown in Figures 1 and 2 (where arrows are drawn from the winning team to the losing team) show that at $n=3, N=3$ and $n=4, N=7$ our condition is no longer met. (Note that in both figures all commands are equal, and at figure 1.) Therefore, in these two cases the smallest permissible value $N$ is $2^{n-1}$. Readers are asked to answer the question whether this is true for $n=5, 6, \dots$.

A. T. Ukraintsev

⟦folio 38⟧

M972. The sequence $x_1, x_2, \dots$ is given by the conditions $x_1 = 1/2, x_{n+1} = x_n^2 + x_n(n=1, 2, \dots)$. Find the whole part of a number
$$\frac{1}{x_1+1} + \frac{1}{x_2+1} + \dots + \frac{1}{x_{100}+1}.$$

Answer: 1. It is clear that
$$\frac{1}{x_n+1} = \frac{1}{x_n} - \frac{1}{x_n(x_n+1)} = \frac{1}{x_n} - \frac{1}{x_{n+1}},$$
By definition, the sum under consideration is equal to $1/x_1 - 1/x_{100} = 2 - 1/x_{100}$. The sequence $x_n$ obviously returns both $x_2 = 3/4$ and $x_3 = (3/4)^2 + 3/4 > 1$, hence also $x_{100} > 1$, i.e. $1 < 2 - 1/x_{100} < 2$.

A. A. Anjans

M973. In triangle ABC, the altitude AH and the bisector BE are drawn. Prove that if $\angle BEA = 45^\circ$ then also $\angle EHC = 45^\circ$.

Fig. 1.

Fig. 2.

It is enough to prove that HE is the bisector of angle AHC.
Let's draw a perpendicular to AC from point E; let D be its point of intersection with BC (Fig. 1). Triangles BEA and BED are equal in side BE and angles ($\angle BEA = \angle BED = 45^\circ$), therefore AE=ED. And since the points A, E, H and D lie on the same circle (for the sum of the angles AHD and AED is equal to $90^\circ + 90^\circ = 180^\circ$), the angles AHE and EHD are equal as inscribed angles subtended by equal chords AE and ED.

Another solution is based on the well-known bisector theorem: if BE is a bisector of triangle ABC, then AE:EC=AB:BC (see, for example, “Quant”, 1985, No. 2, p. 29). It is easy to see that the converse theorem is also true, so it is enough to prove that AH:HC=AB:BC. Denoting the angles of the triangle at the vertices A, B, C by α, β, γ, we obtain that AH:HC=tg γ and by the theorem of sines AB:BC=γ:sin α. But sin α=sin ($\beta + \gamma$)=sin ($90^\circ - \gamma$)=cos γ (since β/2+γ=∠AEB=45°), that is, sin γ:sin α=tg γ.

Let us also note that the triangle considered in the problem can be characterized by the fact that the center O of the circle passing through points B, H and E coincides with the projection of point B onto the line AC (Fig. 2). (This circle is the so-called Apollorian circle for points A and C, that is, for its points X the relative AX:XB is constructed.) From here one more solution can be obtained.

I. F. Sharytsin,
V. N. Dubrovsky

M974. Two people are playing chess with a clock. After both had made 40 moves, both clocks showed 2 hours 30 minutes.
a) Prove that there was a moment in the game when one zone’s clock marked the others’ clocks for more than 1 minute 50 seconds.
b) Is it possible to say that at some points the time difference was at least 2 minutes?

a) Let the absolute value of the difference between the clock readings at no moment exceed t=1 minutes 50 s. Then the time spent by the first chess player on the first move does not exceed t, and the time spent on any of the following moves does not exceed 2t (if the thinking time for a move is more than 2t, then at the beginning or at the end of this period of time the difference in clock readings will be greater than t). Thus, the total duration of the game, equal to 5 hours = 300 minutes, does not exceed 80 2t-t = 159t, that is, t≥300/159 min>1 minute 50 s. The resulting contradiction shows that in

⟦folio 39⟧

At some points the difference in clock readings will exceed 1 min 50 s.

6) Answer: no. If the very first move (more precisely, in chess terminology, “half-move”) in the game took $t_0=300/158$ minutes, each of the next 78 - $2t_0$, and the 80th, last - $t_0$, then the total thinking time for each chess player is $39 \cdot 2t_0 + t_0 = 79t_0 = 2$ hours 30 minutes, and the difference in clock readings at any moment does not exceed $t_0 < 2$ min; The difference graph is shown on page 38.

S. V. Fomin

M975. There are 20 different pieces on the “chessboard” $n \times n$ fields. It is known that each figure from any field will have no more than 20 fields.
a) Prove that for $n=100$ these figures can be rearranged so that they do not belong to each other.
b) Let it be additionally known that if there are twelve figures, then the set of fields that it is also moves in parallel (to the same vector). Prove that for $n=30$ these 20 figures can be arranged so that they are not each other.

a) Using the distance, it is possible to arrange our 20 pieces on the board $100 \times 100$ and estimate the fraction $p$ of those arrangements in which at least one piece will be some other one. It is easy to estimate the proportion of formations in which a given piece $A$ will be a given piece $B$: for any position $A$ for pieces $B$ has $100^2-1=9999$ free fields, of which no more than 20 are under attack by pieces $A$; therefore, this fraction does not exceed $20/9999$. And since the number of (ordered) pairs of figures $(A, B)$ is $20 \cdot 19=380$,

$$p \leq 380 \cdot \frac{20}{9999} < 1,$$

poses there are positions in which no figure will be different (their fraction is equal to $1-p>0$).

Note that our estimate is quite rough - we taught positions in which several figures were different, as many times as there were such pairs of figures in them.

6) We will place the pieces on the board sequentially. If the first piece has already been placed, then the second cannot be placed on 1) the field occupied by the first piece, 2) the fields under attack by the first (there are no more than 20), 3) the fields from which the second piece will be the first. Let us show that the 3rd group also has no more than 20 fields.

Let $\vec{v}_1, \dots, \vec{v}_k$ be the vectors connecting the center of the field occupied by the 2nd figure with the centers of the fields it is. This set of vectors does not change when the piece is moved; one of them may go beyond the edges of the board (the figures show such vectors for two positions of the chess knight). The fields from which the 2nd figure is the 1st are obtained by setting aside the vectors $-\vec{v}_1, -\vec{v}_2, \dots, -\vec{v}_k$ from the field occupied by the 1st figure - there are no more than 20 of them.

Thus, for the 2nd piece the number of forbidden fields does not exceed 41. Let us place it on one of the remaining fields, then for the 3rd piece there will be no more than $2 \cdot 41=82$ forbidden fields, etc. For the 20th piece the number of forbidden fields does not exceed $19 \cdot 41=779<900$, therefore it can also be placed on the board in compliance with the conditions of the problem.

Pay attention to the fundamental solution to two points of our problem: in contrast to the solution to problem 6), the solution to problem a) does not help in any way to find the desired arrangement - this is, as they say, “a pure proof of existence.”

A. K. Tolytso

⟦folio 40⟧

F983. A block of mass $m=1$ kg lies on a rough table; static friction coefficient of the block on the table $\mu_0=1$, sliding friction coefficient $\mu=0.9$. A spring with a stiffness of $k=1$ N/m is attached to the block. The spring begins to sink in the horizontal direction so that its free end moves at a constant speed of $v=1$ m/s (Fig. 1). How will the block move?

We will consider the movement of the system in stages.

First stage: the block is motionless, the spring is spaced. This occurs until at some point in time $t_1$ the spring tension force ($|kx_1|$) reaches the value of the maximum static friction force ($\mu_0mg$); from this moment the block begins to move.

Let's find $t_1: kx_1=\mu_0mg$, or $k(vt_1)=\mu_0mg$, from where

$$t_1=\mu_0\frac{mg}{kv} \approx 10\text{ c}.$$

Let us introduce the notation $k/m=\omega^2$. Then

$$t_1=\mu_0g/v\omega^2.$$

At this moment the spring distance

$$x_1=vt_1=\mu_0\frac{g}{\omega^2}.$$

Second stage. From time $t_1$ the block begins to move. Let's consider this movement in a coordinate system that moves with speed $\vec{v}$. In this system (let's denote it $c$), at time $t_1$ the block has a speed $-\vec{v}$ and a coordinate $x=0$, the spring has a distance of $x_1=vt_1$. Further movement of the block occurs under the action of the elastic force $f_{\text{упр}}=kx_1$ and the sliding friction force $f=\mu mg$, directed in the direction opposite to the direction of the vector $\vec{v}$ (this is the direction of the speed of the block relative to the table, which in the system $c$ has a constant speed $-\vec{v}$). Let us remember that under the action of elastic force and constant force (in this case, friction), the body undergoes harmonious oscillation:

$$x_c=x_{c\text{max}} \sin(\omega t+\varphi)+x_0(\omega=\sqrt{\frac{k}{m}}),$$

where $x_0$ is the equilibrium position, which is determined by the conditions

$$k(x_1-x_0)-\mu mg=0 \Rightarrow$$

$$x_0=x_1-\frac{\mu mg}{k}=x_1-\mu\frac{g}{\omega^2}=\Rightarrow \Delta\mu\frac{g}{\omega^2},$$

where $\Delta\mu=\mu_0-\mu$.

The speed of the block changes according to the law

$$v_c=\dot{x}_c'=x_{c\text{max}} \omega \cos(\omega t+\varphi).$$

Let's find the value of $x_{c\text{max}}$ and $\varphi$. To do this, let’s substitute the values ​​$t=t_1$, $x_c=x(t_1)=0$, $x'(t_1)=-v$ into (1) and (2):

$$0=x_{c\text{max}} \sin(\omega t_1+\varphi)+\Delta\mu\frac{g}{\omega^2},$$

$$-v=x_{c\text{max}} \omega \cos(\omega t_1+\varphi).$$

Let's rewrite these equations in this form:

$$x_{c\text{max}} \sin(\omega t_1+\varphi)=-\Delta\mu\frac{g}{\omega^2},$$

$$x_{c\text{max}} \cos(\omega t_1+\varphi)=-\frac{v}{\omega}.$$

By squaring (3) and (4) and adding the resulting expressions, we find:

⟦folio 41⟧

$$x_{c \max}^2 = \frac{(\Delta \mu)^2 g^2}{\omega^4} + \frac{v^2}{\omega^2} \approx 2 \text{ m}^2, \quad x_{c \max} \approx 1,4 \text{ m}.$$

Dividing (3) by (4), we get:

$$tg(\omega t_1 + \varphi) = \Delta \mu \frac{g}{v \omega}$$

$$(\sin(\omega t_1 + \varphi) < 0, \cos(\omega t_1 + \varphi) < 0)$$

where

$$\varphi = \pi + \arctg \frac{\Delta \mu \cdot g}{v \omega} - \omega t_1 \approx \frac{5 \pi}{4}.$$

Let us now move to a stationary reference system (at the moment of time $t_1$ the origins of coordinates in both systems coincide):

$$x = x_c + v(t - t_1) = x_{c \max} \sin(\omega t + \varphi) + v(t - t_1) + \Delta \mu \frac{g}{\omega^2} = \sqrt{2} \sin((t - 10) + \frac{5 \pi}{4}) + (t - 10) + 1 \text{ (м)},$$

$$x' = x_{c \max} \omega \cos(\omega t + \varphi) + v = \sqrt{2} \cos((t - 10) + \frac{5 \pi}{4}) + 1 \text{ (м/c)}.$$

These equations describe the motion of the block from the moment of time $t_1$ to the moment $t_2$, when the speed of the block becomes equal to 0 and the sliding friction force is replaced by the static friction force. At moment $t_2$

$$x' = x_{c \max} \omega \cos(\omega t_2 + \varphi) + v = 0.$$

Recall that angle $\theta = \omega t_1 + \varphi$ is in the third quarter. With further growth $t (t > t_1)$ the angle will increase, cos $(\omega t + \varphi)$ will also increase, therefore, the speed will increase, remaining positive. When $(\omega t + \varphi)$ ends up in the second (sixth) quarter, cos $(\omega t + \varphi)$ will be negative, and when it becomes cos $(\omega t_1 + \varphi)$, the speed of the block becomes zero. Thus,

$$t_2 = t_1 + \frac{2 \left( \pi - \arctg \frac{\Delta \mu \cdot g}{v \omega} \right)}{\omega} \approx 15 \text{ c},$$

$$x(t_2) \approx 7 \text{ m}.$$

Note that the tension forces of the spring at moments $t_2$ and $t_1$ are related to the relations

$$f(t_1) - \mu mg = -(f(t_2) - \mu mg) \Rightarrow f(t_2) = 2 \mu mg - f(t_1).$$

But $f(t_1) = \mu_0 mg$; That's why

$$f(t_2) = mg(2 \mu - \mu_0) < \mu_0 mg.$$

This means that at moment $t_2$ the block remains and will not move until moment $t_3$, when $f(t_3)$ becomes equal

⟦folio 42⟧

modulo $\mu_0 mg$. The time interval $t_3 - t_2$ is obviously equal to

$$t_3 - t_2 = \frac{f(t_3) - f(t_2)}{kv} = \frac{2(\mu_0 - \mu)g}{v\omega^2} \approx 2\text{ c.}$$

Then the cycle repeats, so that $t_4 - t_3 = t_2 - t_1$, etc. The graphs of the function $x(t)$ and $x'(t)$ are shown in Figures 2 and 3 (see p. 41).

I. I. Mazin

F984. When kolke drove, the torop sometimes gets stuck in the splitting of the log. In such cases, it should be done as shown in figure 1, or as shown in figure 2. Which method is more effective?

Fig. 1.

Fig. 2.

Fig. 3.

As the ax enters the log, the split between the log halves on both sides of the ax increases: these flaps experience slopes in directions perpendicular to the “necks” of the ax; there is an accumulation of spring deformation in the tree. The rupture (splitting) of the log occurs at the moment when this deformation reaches a certain “maximum withstandable” value.

We will assume that before hitting the “anvil” in the first and second cases, the ax + log system has the same energy. When hitting the anvil, some of this energy turns into heat. In the first case (tree below) the impact is inelastic, in the second it is elastic. This means that in the first case, the energy loss during impact ($\Delta E_1$) is greater than in the second ($\Delta E_2$). The remaining energy is spent on work against friction forces during the mutual movement of the ax and the log and on increasing the energy of spring deformation in the log. Let's write down this energy balance:

$$E'_1 = E - \Delta E_1 = A_1 + U_1,$$
$$E'_2 = E - \Delta E_2 = A_2 + U_2.$$

From the above it is clear that $E'_2 > E'_1$, that is, $A_2 + U_2 > A_1 + U_1$.

It is clear that if $U_2 > U_1$, then the second method is more effective.

For the same movement of the ax relative to the log from the same initial positions, that is, for the same value $A$ ($A_1 = A_2$), obviously $U_2 > U_1$. Let us show that the quantities $A$ and $U$ are proportional to each other.

The work $A$ is performed against the friction force, which changes when the ax is moved relative to the log, since the normal reaction force $N_t$ (Fig. 3). Energy $U_t$ is equal to the work done by the force of normal pressure of the ax on the tree. This force at any moment of time is numerically equal to the normal reaction force $N_t$. From all that has been said, it is clear that the condition $A_2 + U_2 > A_1 + U_1$ means that both $A_2 > A_1$ and $U_2 > U_1$, and therefore the second method - hitting the anvil with an ax - is more effective.

T. S. Petrova

F985. An inverted test tube $A$ is immersed in a vessel filled with liquid ether. They immediately start from it

⟦folio 43⟧

bubbles come out. The bubbles are “collected” in test tube B, which is initially completely filled with ether (see Fig.nok), the length of which is twice as long as the length of test tube A. In this case, 2/3 of the first initial volume of ether is displaced from test tube B. The temperature in the room is maintained at 20 °C, the pressure is equal to normal atmospheric pressure. Explain the process occurs a few mm pt. Art.). The bubbles will stop coming out when the evaporation of the ether inside test tube A stops, that is, when the pressure of the test tube there becomes equal to the saturated vapor pressure $p_H$ and the total pressure is $p_H + p_B = p_0$, where $p_B$ is the air pressure.

A similar condition must be met in test tube B. In this case, the air that occupies volume $V_0$ in test tube A will occupy volume $\frac{4}{3}V_0$ in test tube B. Using the Boyle-Marutt law, we can write:

$$p_0V_0 = p_B(V_0 + \frac{4}{3}V_0) = \frac{7}{3}p_BV_0,$$

where do we find $p_B = \frac{3}{7}p_0$. It is now easy to determine the saturated vapor pressure of ether:

$$p_H = p_0 - p_B = \frac{4}{7}p_0 \approx 430 \text{ мм pt. ст.}$$

A. I. Buzdin

The metal atoms (tungsten and platinum) located on the surface of the plate and the carbon atoms in the CO molecule have unsaturated chemical bonds. The interaction of carbon oxyhydroxide with a clean metal surface results in the formation of a strong chemical bond between the C atom and the surface metal atom. This reaction is accompanied by the release of heat. In this case, carbon oxynium forms a monolayer on the metal surface, and for each metal atom located on the surface of the plate, there is one CO molecule and the axis of the molecules is perpedicular to the metal surface (Fig. 1).

Near the surface of the platelet, two planes $P_1$ and $P'_1$ can be identified, located at a distance $l$ from each other and passing through the centers of the carbon and oxygen atoms, respectively. We will assume that positive charges (dipole charges $+\Delta q$) are located in the $P_1$ plane from the surface of the charge plane $+\sigma_1$, and negative charges are located in the $P'_1$ plane from the surface of the charge plane $-\sigma_1$ (Fig. 2).

Similarly, near the surface of the tungsten plate there are two differently charged planes $P_2$ and $P'_2$ from the surface of the charge plane $+\sigma_2$ and $-\sigma_2$, respectively.

Thus, the calculation of the potential difference $U$ between the tungsten plates and the plate is reduced to determining the potential difference between two parameters of different charged planes:

$$U = \frac{\sigma_1}{\varepsilon_0} l - \frac{\sigma_2}{\varepsilon_0} l = \frac{\sigma_1 - \sigma_2}{\varepsilon_0} l. \tag{1}$$

⟦folio 44⟧

The average number of atoms of a metal, their location on a unit area of ​​its surface (surface density of atoms γ), is determined through the volumetric density of atoms ratio

$$\gamma = n^{2/3},$$

where $n$ is the volume density of metal atoms. In turn, the volume density of atoms is equal to

$$n = \frac{\rho N_A}{M},$$

where $\rho$ is the density of the metal, $N_A$ is Avogadro’s number, $M$ is the molar mass of the metal. It's clear that

$$\sigma = \Delta q \gamma.$$

Taking into account relations (2)—(4), we represent the desired potential difference in the form

$$U = \frac{\Delta q \cdot l}{\varepsilon_0} N_A^{2/3} \left( \left( \frac{\rho_W}{M_w} \right)^{2/3} - \left( \frac{\rho_{Pt}}{M_{Pt}} \right)^{2/3} \right).$$

Substituting the numerical values ​​($\varepsilon_0 = 8,85 \times 10^{-12} \text{ Ф/m}$, $N_A = 6,02 \cdot 10^{23} \text{ mol}^{-1}$, $\rho_W = 19,1 \times 10^3 \text{ кг/m}^3$, $\rho_{Pt} = 21,5 \cdot 10^3 \text{ кг/m}^3$, $M_W = 0,184 \text{ кг/mоль}$, $M_{Pt} = 0,195 \text{ кг/mоль}$), we get $U = 24 \text{ мВ}$.

In conclusion, it should be noted that a simplification was made in solving the problem - we did not teach that in the crystal structure the atoms of tungsten and platinum are located in a certain order and, therefore, in different environments, a different number of metal atoms appears on its surface. Therefore, formula (2) requires clarification for each specific case of the arrangement of atoms on the metal surface. In addition, in different planes of the surface, atoms have different valencies, and this must also be taken into account.

E. N. Yunosov, I. V. Yaminsky

F987. In I. Levitan’s painting “March,” the shadows on the snow cast by the trees on a clear sunny day are blue. Wouldn't it be more correct (from a physical point of view) to direct them dark, colorless (black or gray)?

The illumination of any area of ​​the earth's surface is created by both direct sunlight and sunlight scattered in the atmosphere. As you know, the shadow boundary defines the area where direct sunlight does not reach. If in general rays did not fall into this area, then the corresponding areas would be colorless (black).

On a clear sunny day (when there are almost no clouds in the sky), the diffused sunlight coming to the earth “has a blue tint” (the color of the sky). Falling into the area of ​​​​"direct" shadow, this light is reflected from the white snow cover without significant absorption (this is the property of white snow) and gives the shadow a blue color. The described effect is all the more obvious the clearer the snow cover.

A. S. Butov
