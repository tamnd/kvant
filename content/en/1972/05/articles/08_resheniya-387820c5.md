---
id: 1972-5-resheniya-387820c5
issue: kvant_1972_5
year: 1972
number: "5"
title: Solutions to problems M101—M105; F116—F122
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 29
page_last: 37
page_labels: 27, 28, 29, 30, 32, 33, 34, 35
tag: RV6C
lang: en
source: kvant_digital
extraction: vision
content_sha256: 7bc477e146ce0327b310d00756125c0114caabc84a9fd9b7c8815b61c7bdde2c
prompt_sha256: draft-1
translated_from: content/ru/1972/05/articles/08_resheniya-387820c5.md
source_content_sha256: ad8b83304d95a4541af609e32f97a619d17450593a8bbf5d88f128a159393e8a
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 27⟧

SOLUTIONS

In this issue we publish solutions to problems M101–M105.

M101

A single virus enters a colony consisting of $n$ bacteria. In the first minute, it destroys one bacterium, then the virus divides into two new ones, and at the same time each of the remaining bacteria also divides into two new ones. The next minute, the two viruses that have arisen destroy the two bacteria, and then both the virus and all the other bacteria divide again, and so on.

Is this colony expected to live indefinitely or will it eventually perish?

It is easy to check that the number of bacteria and viruses will change over time according to the following law:

| Time (minutes) | Number of viruses | Number of bacteria |
| :--- | :--- | :--- |
| 0 | 1 | $n$ |
| 1 | 2 | $2(n-1)$ |
| 2 | $2^2$ | $2^2(n-2)$ |
| 3 | $2^3$ | $2^3(n-3)$ |
| ... | ... | ... |
| $t$ | $2^t$ | $2^t(n-t)$ |
| $t+1$ | $2^{t+1}$ | $2^{t+1}(n-t-1)$ |
| ... | ... | ... |

From here it is clear that at $t=n$ the number of bacteria will go to zero - the colony will die.

We received about 80 letters with a solution to this problem and one letter where the wrong answer was given.

M102

A set on the plane consisting of a finite number of points has the following property: for any two points $A$ and $B$ set there is a point $C$ set such that the triangle $ABC$ is equilateral.

How many points can such a set contain?

Let us prove that such a set can contain only three points (of course, it is assumed that it contains more than one).

Let us denote this set by the letter $\Gamma$.

Let $A$ and $B$ be two points of the set $\Gamma$, the distance between which is called $d$, the point $P$ must lie inside a circle of radius $d$ with center $A$. In the same way, it must lie inside circles of radius $d$ with centers $B$ and $C$. Thus, the set $\Gamma$ does not go beyond the common part of these circles - the curvilinear “triangle” $T$ (Fig. 1).

Further, together with the points $P$ and $A$, the set $\Gamma$ must belong to one of the two points $Q$ and $R$ - the vertices of the equilateral triangles $APQ$ and $APR$, that is, the points obtained from $P$ by rotating by $60^\circ$ (in one direction or the other) around $A$ (Fig. 2).

In order for the point $Q$ to lie inside $T$, it is necessary for the point $P$ to lie within the boundaries of the golden “petal” $AB$; Indeed, if you rotate the triangle $T$ around the point $A$ by $60^\circ$ counterclockwise, then the lobe points $AB$ and only they will not go beyond

⟦folio 28⟧

T. In the same way, in order for the point $R$ to lie inside $T$, the point $P$ must lie within the blue “petal” $AC$. So, we have proven that any point $P$ set $\Gamma$ must lie within the set $T_A$, consisting of two blue petals $AB$ and $AC$ with a common vertex $A$. But in the same way it is proved that $\Gamma$ is contained within the set $T_B$ (Fig. 3) ​​and $T_C$ (Fig. 4), and the common part of the three sets $T_A, T_B$ and $T_C$ consists of only three points $A, B$ and $C$. Therefore, no other point $P$ can belong to the set $\Gamma$.

The correct solution to the problem of adding A. Blyukhin (Klimovsk, Kemerovo region), N. Chernov (Krivoy Rog), Sh. Slepoy and E. Turkevichi (Chernovtsy), A. Merkuryev (Leningrad), M. Rozov (Minsk), A. Glushko and V. Korshenko (Voronezh) and others.

In our solution, we only used the fact that in the set $\Gamma$ we can specify two points, the distance between which is maximum. For the set $\Gamma$, consisting of a finite number of points, this is, of course, true. However, the statement of the problem remains true if we impose a weaker condition on the set $\Gamma$—the conditions of boundedness. To solve the problem in this case, additional reasoning is necessary; they can be easily verified by those who know the initial concepts of the topology of exact sets on the plane, for example, in the volume of the book: N. Steenrod and W. Chinn “First Concepts of Topology” (“World”, popular series “Modern Mathematics”). Note that the condition of limitedness cannot be abandoned.

**M103**

Explore how many solutions the control system has

$$\begin{cases} x^2 + y^2 + xy = a, \\ x^2 - y^2 = b, \end{cases}$$

where $a$ and $b$ are some real numbers.

Let's move on to new variables using the formulas

$$\begin{cases} x + y = u, \\ x - y = v, \end{cases}$$

that is

$$\begin{cases} x = \frac{u + v}{2}, \\ y = \frac{u - v}{2}. \end{cases}$$

Then this data in the system conditions will be written like this:

$$\begin{cases} 3u^2 + v^2 = 4a, \\ uv = b. \end{cases}$$

Obviously, according to formulas (1), each pale $(x, y)$ corresponds to one pair $(u, v)$, and to each pale $(u, v)$ there is a pair $(x, y)$, so we need to find out how many solutions $(u, v)$ for different values ​​of parameters $a$ and $b$ system (2) has. (It is immediately clear that for $a < 0$ there are no solutions, for $a = 0$ and $b \neq 0$ there are no solutions, and for $a = b = 0$ there is a unique solution $u = v = 0$, but this could not be noted, since our further reasoning is suitable for these cases.

Let us subtract and add to the first equation of system (2) the second equation multiplied by $2\sqrt{3}$.

We get the following system:

$$\begin{cases} (\sqrt{3}u - v)^2 = 4a - 2\sqrt{3}b, \\ (\sqrt{3}u + v)^2 = 4a + 2\sqrt{3}b \end{cases}$$

equivalent system (2). [Think about how to derive (2) from (3)]. It is clear that each set of values ​​$\sqrt{3}u - v$ and $\sqrt{3}u + v$ that are obtained from (3) corresponds to one solution $(u, v)$ of the system. It remains to take into account that (in the domain of real numbers) the equation $z^2 = c$ has two solutions: $z_1 = \sqrt{c}$, $z_2 = -\sqrt{c}$ if $c > 0$, one $z = 0$ if $c = 0$, and has no solution if $c < 0$.

Answer. There are solutions if and only if the inequalities are satisfied

$$-2a \leq b\sqrt{3} \leq 2a,$$

In Figures 1-4, the areas colored blue are bounded by two other circles of radius $d = AB$ centered at points $A, B$ or $C$. Check that these areas intersect only at points $A, B$ and $C$.

⟦folio 29⟧

Fig. 5. By turning $45^\circ$ clockwise, this figure becomes figure 6 (but on a different scale).

moreover, if it is an inequality of structure (“less”), then there are four solutions; if one of them turns into equality, then two, if it is (this is possible only for $a = b = 0$), then one.

Many readers who submitted a solution to this problem provide (usually in a slightly different form) this result, as well as explicit formulas for solving the system. They are not difficult to obtain from our calculations, but they are quite cumbersome, and we will not present them, especially since this is not required in the conditions. Instead, we point to the geometric interpretation of the system equation: the first specifies an ellipse, the second a hyperbola. The red hyperbola in Figures 5 and 6 corresponds to the values ​​of the parameters $a$ and $b$ when the curves intersect (four solutions), blue - when the hyperbola touches the ellipse (two solutions).

Some readers have also conducted research for the case where the solution system is in the domain of all complete numbers. And here our reasoning allows us to immediately give an answer: in complete numbers $(x, y)$ the system has four, two or one solution if of the two equalities $2a = b\sqrt{3}$, $2a = -b\sqrt{3}$ respectively zero, one or two are true.

M104

Inside the triangle $ABC$ there are two points $P$ and $Q$ such that the segments $AP$ and $AQ$ form equal angles with the bisector of the angle $A$ of the triangle, and the segments $BP$ and $BQ$ form equal angles with the bisector of the angle $B$.

Prove that the segments $CP$ and $CQ$ make equal angles with the bisector of angle $C$ (Fig. 7).

⟦folio 30⟧

WE WILL GET

$$\sin(C - \gamma_1) \sin\gamma_2 = \sin(C - \gamma_2) \sin\gamma_1$$ or
$$\sin C \sin(\gamma_1 - \gamma_2) = 0.$$

Since $0 < C < \pi$ and $-\pi < \gamma_1 - \gamma_2 < \pi$, it follows that $\gamma_1 = \gamma_2$.

V.N. Berezin (Moscow) reported another, purely geometric solution.

Let $P_A, P_B$ and $P_C$ be points symmetrical to points $P$ with respect to side $BC$, $AC$ $AB$ of triangle $ABC$. Note that in order for the segment $AQ$ to make angles equal to $\Rightarrow PAC = \alpha$ and $\Rightarrow PAB = A - \alpha$ with the segments $AB$ and $AC$, it is necessary and sufficient that it follow the bissertiza of the angle $P_BAP_C$ (Fig. 8).

Since $AP_B = AP_C$, this condition can also be formulated as follows: the point $Q$ must lie on the perpendicular drawn through the middle of the segment $P_BP_C$. Now it remains to prove that if $Q$ lies on the perpendiculars drawn through the midpoint of the segments $P_BP_C$ and $P_CP_A$, then $Q$ also lies on the perpendicular drawn through the midpoint of the segment $P_BP_C$. This is obvious: the points $P_A, P_B, P_C$ do not lie on the same line, and $Q$ is the center of the circle circumscribed about the triangle $P_AP_BP_C$ (Fig. 9).

Of course, it can be proven in exactly the same way that $P$ is the center of the circle circumscribed about the triangle $Q_AQ_BQ_C$, where $Q_A, Q_B, Q_C$ are points symmetrical to $Q$ with respect to the side of the triangle $BC, CA, AB$. The mapping $P \rightarrow Q$ is the same as its inverse. With this mapping, the center of the inscribed circle goes into itself, and the center of the inscribed circle and the point of intersection of the heights go into each other (check it out!).

**M105**

The sum of the digits of a number after multiplying it by 8 can decrease: $75 \cdot 8 = 600$ - the sum of the digits was $7 + 5 = 12$, but became 6. However, it cannot decrease by more than 8 times. Prove it.

In other words, prove that for any natural number $N$

$$\frac{S(8N)}{S(N)} \geq \frac{1}{8},$$

where $S(A)$ is the sum of the digits of the number $A$ (in decimal notation).

For what other natural numbers $k$ is there a positive number $c_k$ such that for all natural numbers $N$

$$\frac{S(kN)}{S(N)} \geq c_k?$$

Find the best value for $c_k$.

First note that $S(8 \cdot 125) = S(1000) = 1$.

We will need the following properties of the function $S(N)$:

1. $S(A + B) \leq S(A) + S(B)$;
2. $S(A_1 + A_2 + \dots + A_n) \leq S(A_1) + S(A_2) + \dots + S(A_n)$;
3. $S(nA) \leq nS(A)$;
4. $S(AB) \leq S(A)S(B)$.

To be convinced of the validity of your part $1^\circ$, it is enough to imagine that the numbers $A$ and $B$ add up in a “column”. Property $2^\circ$ is obtained from $1^\circ$ by simple induction. $3^\circ$ is a private sluagh $2^\circ$.

If you imagine that $A$ can be placed on $B$ in a “column” and apply $3^\circ$ to each digit of the number $B$, you will get $4^\circ$.

Now it is easy to prove the required inequality: $S(N) = S(1000N) = S(125 \cdot 8N) \leq S(125)S(8N) = 8S(8N)$, that is

$$\frac{S(8N)}{S(N)} \geq \frac{1}{8}.$$

The same reasoning works for any number $k = 2^{2^q}5^q$. Let us denote by $c_k$ the number $\frac{1}{S(2^q5^r)}$. Let us prove that for any $N$ $\frac{S(kN)}{S(N)} \geq c_k$ (for $N = 2^{2^q}5^r$ this inequality turns into equality, since

⟦folio none⟧

$$S(kN) = S(10^{r+q}) = 1$$. For any $N$
$$S(N) = S(10^{r+q}N) \leq S(2^q 5^r) S(kN) = \frac{1}{c_k} S(kN),$$
Q.E.D.

Let us now prove that for numbers $k$ of the form $Q2^r 5^q$, where $Q$ is coprime to 10, the ratio $S(KN)/S(N)$ can be less than any given $\varepsilon > 0$, that is, the required positive number $c_k$ does not exist.

We need the following lemma: there is a number $10^m-1$ (consisting of $m$ nines), done on $Q$. It is easy to prove using the “Dirichlet cause” *). Consider the remainders from division by $Q$ numbers

$$\begin{array}{c}
9 \\
99 \\
999 \\
9999 \\
\cdots
\end{array}$$

Some two of them coincide, and the difference of the corresponding numbers is divided by $Q$:

*) See article by A. I. Orlov in «Kvant» No. 7, 1971.

In this issue we publish solutions to problems F116—F122.

F116

If the temperature of the air in the cylinder shown at figure 10 is $T_0(T_0 > 0^\circ C)$, then it remains to temperature $\frac{T_0}{2}$ in approximately $\tau = 30$ sec. The piston begins to move in and out with some frequency. In what case does more ice grow around the cylinder in 50 piston strokes, if they are made: a) in 1 minute; b) in 1 hour; c) in 30 days?

The rate of change in air temperature in the cylinder is proportional to the temperature itself. This means that the temperature changes exponentially $T = T_0 e^{-\alpha t}$ ($\alpha$ is the coefficient, $t$ is time) (see «Kvant» No. 1).

Obviously, if the selected time intervals $t$ form an arithmetic progression with a difference of $\tau$, that is, $t=n\tau$, then the gas temperature forms a geometric progression with a value of $e^{-\alpha t}$. This can be easily verified by writing the formula for the dependence of gas temperature on time in the form

$$\frac{T}{T_0} = \left(e^{-\alpha t}\right)^n.$$

At $n=1$ $\frac{T}{T_0} = \frac{1}{2}$. This means $e^{-\alpha t} = \frac{1}{2}$ and $\frac{T}{T_0} = \left(\frac{1}{2}\right)^n$.

It follows that in a vessel with a stationary piston, the gas temperature will decrease by half every 30 seconds.

If a piston makes 50 strokes in 1 minute, then one stroke is made in 1.2 seconds. This time is short compared to the characteristic time of the heat transfer process - 30 seconds. Therefore, the heat released when the volume of gas decreases does not have time to dissipate and will be almost positively removed when the volume increases

⟦folio 32⟧

Fig. 11.

ma gas. Therefore, in this case, the movement of the piston will not change the rate of ice melting.

It is also clear that even with 50 strokes of the piston, in 30 days the ice will melt in the same way as it would melt with a stationary piston. Now the time of one stroke of the piston is too long compared to the time during which almost all the ice will melt and the water temperature will become equal to 0 ° C.

If the piston makes 50 strokes in 1 hour, then one stroke is made in 1.2 minutes. Thanks to this, the body released during the collapse of gas will have time to melt the ice. In this case, more ice will melt than with a stationary piston.

The correct solution to this problem was sent by M. Flerov (Moscow) and M. Weinhacher (Krivoi Por).

F117

They usually walk along the surveyed road, taking small steps. At what length of step should a person walk without fear of falling if the length of his legs is 1 meter and the coefficient of friction of the soles of his shoes on the road is 0.1?

Let the step width be 2x (Fig. 11). When a person lifts one leg, all of his weight goes to the other leg. Then the earth reaction force N is equal to mg (m is the mass of a person). This means that the maximum friction force F_TP that can act on a person’s foot without allowing it to slip is equal to kmg. The resultant force N and the friction force F_TP is directed towards the person’s center of gravity, that is, almost along the leg, and forms an angle α with the vertical:

$$\frac{F_{ТР}}{N} = \text{tg} \alpha.$$

Posetom

$$\text{tg} \alpha = \frac{kmg}{mg} = k,$$

But

$$\sin \alpha = \frac{x}{l}.$$

Hence,

$$x = l \sin \alpha = l \frac{\text{tg} \alpha}{\sqrt{1 + \text{tg}^2 \alpha}} \approx 0, 1 l = 10 \text{ cm}).$$

The width of the step that a pedestrian can take is 20 cm.

This task turns out to be the easiest. More than 50 readers submitted her correct solution.

F118

The combustion chamber of a jet engine receives a mass m of hydrogen per second and the amount of oxygen required for complete combustion. The output solution of the nozzle is S. The pressure in this section is P, the absolute temperature is T. Determine the thrust force F of the engine.

Let us find the mass of water vapor that forms mass m of hydrogen during combustion. Let us write the equation for the hydrogen combustion reaction

$$2\text{H}_2 + \text{O}_2 = 2\text{H}_2\text{O}.$$

From the reaction equation we can conclude that two hydrogen molecules combine with one oxygen molecule. The result is two molecules of water vapor. This means that the combustion of one oxygen of hydrogen requires half the oxygen of oxygen, and the reaction produces one oxygen of water. When n = \frac{m}{\mu_B} of hydrogen oxygen is burned, the same amount of hydrogen oxygen will be obtained (μ_B = 2 kE/kmol - the mass of one hydrogen oxygen). Therefore, when burning a mass m of hydrogen, the resulting mass is M = \frac{m}{\mu_B} \mu_\pi = \frac{18}{2} m = 9 m of water vapor (μ_\pi = 18 kE/kmol - the mass of one oxygen vapor). This mass of water vapor flies out of the engine nozzle in one second. Since we know the area of ​​the engine output nozzle, we can find the speed v of the gas leaving the nozzle. In one second, a volume of steam V = vS will be ejected from the engine nozzle. If the vapor density is equal to p, then the mass of this volume of vapor will be equal to vSр, therefore M = ρSv.

Hence v = \frac{M}{\rho S} = \frac{9m}{\rho S}.

This formula includes vapor density. It is not known to us, but we know the steam pressure and its temperature. Having written the Clapeyron–Mendeleev equation PV = \frac{m}{\mu_\pi} RT (R is the gas constant), we find that the vapor density is equal to

$$\rho = \frac{m}{V} = \frac{P \mu_\pi}{RT} \text{ и } v = \frac{9mRT}{P \mu_\pi S}.$$

Since during the time Δt the mass of steam MΔt is ejected from the nozzle, to which the impulse MΔtv is imparted, then the gas is acted upon

⟦folio 33⟧

$$F_1 = \frac{M \Delta t v}{\Delta t} = M v.$$

A force of the same magnitude, but in the opposite direction, acts on the engine. The total force acting on the engine (that is, the thrust force of the engine) is equal to the sum of the reactive force $F_1$ and the static pressure force $F_2 = p S$, that is

$$F = M v + p S = 81 \frac{m^2 R T}{p \mu_\pi S} + p S = \frac{9}{2} \frac{m^2 R T}{p S} + p S.$$

Typically, jet engine nozzles are designed in such a way that the pressure $p$ of the gas leaving the nozzle is low. Therefore, the second term in the expression for the engine thrust force is small compared to the first and can be neglected in calculations.

Correct solutions were sent by: V. Kuusk (Rzhev); P. Sereev (Grozny), L. Smushekevich (Magnitogorsk), I. Sidorov (Moscow), S. Araslanova (N-Ivkino, Kirov region), D. Fushman (Chernovtsy), E. Dolgov (Moscow), Y. Imin (Rechnitsa, Gomel region), V. Katenov (Moscow), G. Simonenkov (Kauns), V. Belov (Vologda), N. Fedin (Omsk), M. Fedin (Alushta), V. Kulits (Ivanovo, Brest region), S. Chernikov (Semipalatinsk), V. Korotkikh (Novokuznetsk), O. Zaumyslova (Moscow), Yu. Polyansky (Zelenodolsk TASSR), A. Redchenko (village Novopetrovka, Belopolsky district, Sumy region), S. Bozhevolny (stanitsa Kopanskaya, Krasnoarsskaya region), Y. Lurie (Grozny), E. Shakhnovich (Kalinin region), L. Bratsinsky (Frunze), Y. Shashkov (Shigri, Kursk region), A. Udaltsov (Kaliningrad, Moscow region), A. Gordienko (village of Poltavenskoye, Krasnoarssk region), V. Boyarishinov (Kolomna), A. Smirnov (Gorky), A. Mamula (village of Dybintsy, Kyiv region).

F119

A matnik $AB$ with a ball of mass $M$ is suspended from a matnik $BC$ with a ball of mass $m$ (Fig. 12). Point $A$ oscillates in the horizontal direction with period $T$. Find the length of thread $BC$ if it is known that thread $AB$ remains in a vertical position all the time.

Since the thread $AB$ remains vertical, no horizontal forces act on the ball of mass $M$ during the motion of the system. This means that horizontal forces do not act on a system consisting of two balls, $M$ and $m$, and the balls must move so that their center of mass does not move in the horizontal direction. Therefore, a ball of mass $m$ moves as if it were attached to a thread of length $x$, where $x$ is the distance from the ball to the center of mass of the system.

Fig. 12.

We. The oscillation period of such a matnik is equal to $2\pi \sqrt{\frac{x}{g}}$. This period, very long, is equal to the vibrations of the point $A$, that is, $T$:

$$T = 2\pi \sqrt{\frac{x}{g}}.$$

Now let's find $x$. The position of the center of mass of the location system is exactly the same as the position of the center of gravity:

$$xm = (l - x)M.$$

From here

$$x = l \frac{M}{m + M}.$$

Substituting this expression for $x$ into formula (1), we obtain

$$T = 2\pi \sqrt{\frac{l}{g} \cdot \frac{M}{m + M}}.$$

From here

$$l = \frac{T^2 g}{4\pi^2} \cdot \frac{m + M}{M}.$$

The correct solution to the problem was sent; L. Bratsinsky (Frunze), V. Korotkikh (Novokuznetsk), M. Premer (Tomsk), N. Fedin (Omsk), L. Smushekevich (Magnitogorsk), Y. Lurie (Grozny), P. Sereev (Grozny), E. Dolgov (Moscow).

F120

A skater on an icy road suffers from turning as close to the inside edge as possible. A cyclist on a cycle track takes a turn as far as possible from the inner edge. How can we explain this difference in the movement of a skater and a cyclist on a turn? Track profile selected on figure 13.

The centripetal acceleration is imparted to the skater by the force of friction on the ice $F_{ТP} = kN$, where $N$ is the force of normal pressure of the skater on the ice (Fig. 14). Since the skater does not move vertically

⟦folio 34⟧

direction, the force $N$ is equal in magnitude to the force of gravity $mg$ acting on the skater. Therefore $F_{TP} = kmg$ and $\frac{mv^2}{R} = kmg$.

Hence $v = \sqrt{kgR}$.

When making a turn, the skater covers a distance $\pi R$. The time $t$ it takes to turn is

$$t = \pi \sqrt{\frac{R}{kg}}.$$

(1)

The larger the radius of the circle along which the skater moves, the longer the time spent on turning. Although the increase in the degree of turn increases the maximum speed of the skater, the distance covered by him increases even more. Speed ​​is proportional to $\sqrt{R}$ and distance is proportional to $R$. That is why the skater tries to take the turn as close to the break as possible.

Now consider the movement of a hair cyclist on an inclined track. The centripetal acceleration is imparted to it by the sum of the horizontal components of the friction force $F_{TP}$ and the force $N$ of the support reaction (Fig. 15):

$$F_{TP} \cos \alpha + N \sin \alpha = \frac{mv^2}{R}.$$

(2)

Since the hair cyclist does not move in the vertical direction, the sum of the vertical components of all forces acting on the hair pedist is equal to zero:

$$N \cos \alpha - F \sin \alpha - mg = 0.$$

(3)

From equations (2) and (3), taking into account that $F_{TP} = kN$, we find the maximum speed with which the hair cyclist can move:

$$v_1 = \sqrt{gR \frac{k + tg\alpha}{1 - ktg\alpha}}.$$

This speed depends not only on the radius of the circle, but also on the angle of inclination of the track to the horizon. With the track profile shown at figure, the angle of inclination changes. At $\alpha = \arctg (1/k)$ the speed of movement of the hair cyclist can be any *).

The time required for a hair cyclist to go through a turn of radius $R$ is equal to

$$t_1 = \frac{\pi R}{v_1} = \pi \sqrt{\frac{R}{g} \cdot \frac{1 - ktg\alpha}{k + tg\alpha}}.$$

If the hair cyclist takes a turn further from the edge, then not only the radius of the turn changes, but also the angle $\alpha$ of the track’s inclination to the horizon. This reduces the turning time.

The editors received many solutions to this problem. More complete and well-founded decisions were added by E. Dollov (Moscow), V. Belov (Vologda), S. Bozhevolny (stanitsa Kopanskaya, Krasnodar Territory), A. German (Voronezh), A. Buzai (Izyaslav, Khmelnitsky region, Ukrainian SSR), A. Boyavsky (Gomel), D. Fushman (Chernovtsy) and P. Sereev (Grozny).

F121

In a hermetically sealed vessel, a piece of ice of mass $M$ floats in water, in which a lead pellet of mass $m$ is floating. How much heat must be applied for the pellet to begin to sink? The density of lead is $\rho_c = 11,3 \text{ e/cm}^3$, the density of ice is $\rho_\pi = 0,9 \text{ e/cm}^3$, the heat of fusion of ice is $\lambda = 80 \text{ кал/с}$. The temperature of the water in the vessel is $0^\circ\text{C}$.

It is not necessary for all the ice to melt for the grain to begin to sink. It is enough if the average density of ice with grain becomes equal to the density of water. If the mass of the remaining ice is denoted by $M_1$, then the condition for the pellet to begin to sink will be written as follows:

$$\frac{M_1 + m}{V} = \rho_B.$$

But the volume $V$ of ice and pellets is equal to the sum of their volumes, that is, $\frac{M_1}{\rho_\pi} + \frac{m}{\rho_c}$.

*) The speed of the hair cyclist in this case will be determined by the power, development and resistance.

⟦folio 35⟧

Pozny $M_1 + m = \rho_B \left( \frac{M_1}{\rho_\pi} + \frac{m}{\rho_c} \right)$.

From here

$$M_1 = m \frac{(\rho_c - \rho_B) \rho_\pi}{(\rho_B - \rho_\pi) \rho_c} = 8,2m.$$

The mass of ice must grow

$$\Delta M = M - M_1 = M - 8,2m.$$

This requires an amount of heat

$$Q = \lambda \Delta M = \lambda (M - 8,2m).$$

The correct solution to this problem when lining up about 40 readers.

F122

Three bodies with masses $m_1, m_2$ and $m_3$ can slide along a horizontal plane without friction (Fig. 16), and $m_1 \gg m_2$ and $m_3 \gg m_2$. Determine the maximum speeds that the two outer bodies can acquire if at the initial moment of time they accumulated, and the middle body had a speed of $v$. The impacts are considered to be absolutely elastic.

The collision of a body of mass $m_2$ with bodies of mass $m_1$ and $m_3$ will continue until its speed becomes less than the speed of one of the bodies $m_1$ or $m_3$. But in this case, the momentum and energy of a body of mass $m_2$ will be much less than the momentum and energy of these bodies (since $m_1 \gg m_2$ and $m_3 \gg m_2$) and, writing the law of conservation of energy and momentum, we can not take into account the energy and momentum
