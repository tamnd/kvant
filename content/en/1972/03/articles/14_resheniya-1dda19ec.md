---
id: 1972-3-resheniya-1dda19ec
issue: kvant_1972_3
year: 1972
number: "3"
title: Solutions to problems M89—M95; F100—F107
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 42
page_last: 51
page_labels: 40, 41, 42, 43, 46, 47, 49
tag: ER8K
lang: en
source: kvant_digital
extraction: vision
content_sha256: 0e844bca0a7b060b2ad2ecf175e21023f1725dd31489d8e2079a51be439af82e
prompt_sha256: draft-1
translated_from: content/ru/1972/03/articles/14_resheniya-1dda19ec.md
source_content_sha256: d93f46e13f286f7c2631739b298e401e4b66d59d809d98ea5a0505bed5f79911
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 40⟧

Solutions

In this issue we publish solutions to problems
M89—M95; F100—F107

M89
The solution to this problem is contained in the note by I. M. Yaglom on page 28.

M90
Prove that if $x_1 < x_2 < x_3 \dots$ are natural numbers, then
$$\frac{\sqrt{x_2-x_1}}{x_2} + \frac{\sqrt{x_3-x_2}}{x_3} + \dots + \frac{\sqrt{x_n-x_{n-1}}}{x_n} < 1 + \frac{1}{2} + \frac{1}{3} + \dots + \frac{1}{n^2} + \frac{1}{n^3} + \frac{1}{n^4}.$$

Let us first assume that $x_n \leq n^2$. Then
$$\frac{\sqrt{x_i-x_{i-1}}}{x_i} \leq \frac{x_i-x_{i-1}}{x_i} = \frac{1}{x_i} + \frac{1}{x_i} + \dots + \frac{1}{x_i}.$$
$$x_i - x_{i-1} \text{ слагаемых}$$

The last sum obviously does not exceed the sum containing the same number of terms
$$\frac{1}{x_{i-1}+1} + \frac{1}{x_{i-1}+2} + \dots + \frac{1}{x_i} + \frac{1}{x_i-1} + \frac{1}{x_i}.$$

No then
$$\sum_{i=1}^{n} \frac{\sqrt{x_i-x_{i-1}}}{x_i} < \frac{1}{x_0+1} + \dots + \frac{1}{x_1} + \frac{1}{x_1+1} + \dots + \frac{1}{x_i} + \dots + \frac{1}{x_{n-1}+1} + \dots + \frac{1}{x_n} < \frac{1}{2} + \frac{1}{3} + \dots + \frac{1}{n^2} < 1 + \frac{1}{2} + \frac{1}{3} + \dots + \frac{1}{n^2}.$$
Now suppose that among the numbers $x_0, x_1, x_2, \dots, x_n$ there are greater than $n^2$. If $x_i > n^2$, then
$$\frac{\sqrt{x_i-x_{i-1}}}{x_i} < \frac{\sqrt{x_i}}{x_i} = \frac{1}{\sqrt{x_i}} < \frac{1}{n}.$$
Thus, which term with a value $x_i$ greater than $n^2$ is less than $\frac{1}{n}$.
Consequently, the sum of all such terms (there are no more than $n$) is less than 1. But the sum of the remaining terms, as shown above, is less than $\frac{1}{2} + \frac{1}{3} + \dots + \frac{1}{n^2}$, which completes the proof of inequality(*)

Yu. I. Ionia

⟦folio 41⟧

M91
The solution to problem M91 is linked to a separate note “Environment of ten” on page 24.

M92
Petya spends the entire 90 days of his vacation in the village and strictly adheres to the following schedule: every second day (that is, every other day) he goes swimming in the lake, every third day he goes to the store for groceries, and every fifth day he solves math problems. (On the first day, Petya does this, and the other, and the third, and is very tired.) How many “pleasant” days will Petya have when he needs to swim, but does not need to go to the store and solve problems? How “boring” will it be when there will be nothing to do at all?

This problem has attracted the attention of many of our readers. Here is her detailed solution.
Let's number all the days: 1, 2, 3, ..., 90.
Let's find out how many times Petya went swimming. He did this on the first day, and then every other day. This means that he went swimming on days with odd numbers (Fig. 1). There are 90:2=45 such days. Consequently, he went swimming 45 times.

In the same way, you can find out how many days there were when he went to the store, and how many when he solved problems. He went to the store on those days whose numbers, when divided by 3, give a remainder of 1. (There are 90:3 = 30 such days (Fig. 2)). And I solved problems on those days whose numbers, when divided by 5, give a remainder of 1. (There are 90:5=18 such days (Fig. 3)).

However, in order to find out how many days there were when Petya (a) swam and went to the store, (b) swam and did math, (c) went to the store and did math, and (d) swam, went to the store and did math. In order not to solve which of these problems separately, we need such a general lemma.

Lemma. Among the natural numbers less than N, the remainder q when divided by n gives $$\frac{N-1-q}{n} + 1$$ numbers (q≠0). (Recall that [x] denotes an integer

Fig. 1.

Fig. 2.

Fig. 3.

Fig. 4.

Fig. 5.

part of a number x: the most whole number not exceeding x.)

Proof of the lemma. The remainder q when divided by n is given by the numbers

q, q+1·n, q+2·n, ..., q+kn, ...

Since we are only interested in numbers less than N, we need to find an integer k such that q+kn<N≤q+(k+1)n. Let us rewrite this inequality as follows:

$$kn \leq N-1-q < (k+1)n,$$

and finally like this: $k \leq \frac{N-1-q}{n} < k+1$. Therefore, $k = \frac{N-1-q}{n}$, and the total number of numbers less than N and giving a remainder q when divided by n is $$\frac{N-1-q}{n} + 1$$ (the one appears due to the number $q=q+0\cdot k$).

Now it's easy to get answers to questions a, b, c and d. Indeed, each of these questions can be reformulated as follows: How many natural numbers less than 91 leave remainder 1 when divided by n_i, where n_i depends on the question: $n_a=6$, $n_b=10$, $n_c=15$ and $n_d=30$. Substituting these numbers into our formula, we get that it was:

⟦folio 42⟧

15 days when Peta swam and went to the store;
9 days when Peta swam and solved problems;
6 days when Peta went to the store and solved problems;
3 days when Peta swam, went to the store and solved problems.
Now we can already calculate how many “boring” and how many “pleasant” days there were. In total, Peta spent 90 days in the village. For 3 days he was doing three things, 15+9+

Fig. 6.

Fig. 7.

Fig. 8.

42

+6=30 days - at least two things and 45+30+18=93 days - at least one thing. Therefore (see Fig. 4, 5) 90-93+30-3=24 days he did nothing. So, there were 24 “boring” days. The number of “pleasant” days is calculated in the same way: in total Peta swam for 45 days, he swam and did something else for 15 + 9 = 24 days, and finally, he did all three things for 3 days. Finally, there were 45—24+3=24 “pleasant” days.

M93
Each of the numbers $x_1, x_2, \dots, x_n$ is equal to the plane or minus one. It is known that
$$x_1x_2+x_2x_3+\dots+x_{n-1}x_n+x_nx_1=0.$$
Prove that $n$ is divisible by even.

Since the sum $x_1x_2+x_2x_3+\dots+x_nx_1$ is equal to $n$ terms, then $n$ is even—the number of minus ones in this sum is equal to the number of the plane. It remains to show that the number is minus one. To do this, let’s multiply all the terms
$$x_1x_2 \cdot x_2x_3 \cdot x_3x_4 \cdot \dots \cdot x_nx_1=x_1^2x_2^2 \cdot \dots x_n^2=1.$$
To Pozny, the number of minus ones is indeed even and $n$ is divisible by 4.

M94
Prove that there is no polyhedron with at least four edges adjacent to each vertex and each face.

Let us assume that such a polyhedron exists. Let $\alpha_1, \alpha_2, \dots, \alpha_k$ be the plane angles of its faces. Let's calculate in two different ways what their arithmetic mean is equal to. Let's group the angles by faces. Then, since each face has at least four angles, the arithmetic mean of its angles is at least 90°. From here it immediately follows that the arithmetic mean of all angles is not less than 90°. Let's group them now by vertices. Since each vertex is adjacent to at least four angles, and the sum of all angles at a vertex is less than 360°, then the arithmetic mean of the angles at a vertex is less than 90°*). But then the arithmetic mean of all angles is less than 90°. And, as we proved above, it is no less than 90°. The resulting contradiction proves that such convex polyhedra do not exist.

Another solution to the problem can be obtained based on Euler's formula**). Let

*) In this place we use the convexity of the polyhedron. As some of our readers have noticed, it is possible to construct a non-convex polyhedron with a “hole”, in which each face is a quadrilateral and four edges meet at each vertex (see Fig. 6).

**) You can read about Euler’s formula in the book: R. Courant and G. Robbins, What is mathematics?, Enlightenment, 1967.

⟦folio 43⟧

In a ring of vertices, $P$ are edges, and $\Gamma$ are faces of the polyhedron. Then for a convex polyhedron (and in general for a polyhedron without “through holes”) the following equality is true:

$$B - P + \Gamma = 2.$$

In our polyhedron, each vertex has at least four edges. Therefore $P \geq \frac{4B}{2}$. (We must divide in half because each edge is adjacent to two vertices.) Similarly, since each vertex is adjacent to at least four edges, $P \geq \frac{4F}{2}$.

Therefore, $2P \geq 2(B + \Gamma)$, that is, $P \geq B + \Gamma$, and according to Euler’s formula, $B + \Gamma = P + 2$. Thus, from the existence of a polyhedron with the indicated properties, it would follow that $P \geq P + 2$, which is contradictory.

**M95**

A trapezoid was marked on the board, the middle line $EF$ was drawn in it and the perpendicular $OK$ was dropped from the point $O$ of intersection of the diagonals to a large base. Then the trapezoid was erased. How to restore the drawing using the preserved segments $EF$ and $OK$ (Fig. 7)?

Construction of a trapezoid. Let us draw a straight line $l$ through the point $K$, parallel to the segment $EF$. Let's find the middle $M$ of the segment $EF$. Let's find the point $N$ of intersection of line $l$ and line $OM$. Let us construct a parallelgram with vertices $E$, $N$ and $F$, for which the segment $EF$ is a diagonal. Let's denote its fourth vertex by $P$. Let us draw a line $l'$ parallel to $l$ through it. Let us draw straight lines through the points $O$, parallel to the sides of the parallelgram $ENFP$. The points at which these lines intersect lines $l$ and $l'$ are the vertices of the trapezoid.

Our construction is based on the fact that the straight line $OM$ divides the bases of the trapezoid in half. We leave the proof of this simple fact and the proof of the correctness of the construction to the reader. (In addition, we took advantage of the fact that the middle line of the triangle is parallel to its side.)

Another solution to the problem can be obtained based on the fact that the point $Q$ of intersection of the extended lateral sides on the line $OM$ and the ratio of the distances to the lines $l$ and $l'$ for the point $O$ Q are the same. Using this, after the lines $l$ and $l'$ have been constructed, you can construct the point $Q$ and, connecting it with the points $E$ and $F$, find the vertices of the trapezoid.

Study. Let us examine various cases of the location of the segments $EF$ and $OK$.

1. Point $O$ lies on the segment $EF$. Then there are no solutions (if the point $O$ is the midpoint of the segment $EF$, then the line $OM$ can be drawn almost arbitrarily - any

⟦folio none⟧

Fig. 11 a.

A trapezoid is obtained only if the segment OM is shorter than the segment MN (Fig. 9, a, b). If the segments OM and MN are equal, then you get a triangle (Fig. 10). If OM is greater than MN, then a “self-intersecting trapezoid” is obtained (Fig. 11, a, b).

The correct solutions to the problems were sent by:
N. Bashkina (Kurgan-Tube) M92; S. Buu-bamrin (Glodyany MSSR) M92; A. Alyaev (Pachelmy, Penza region) M92, M95; A. Bueay (Izyaslav) M93, M95; V. Gamolin (Odessa) M93—M95; V. Goncharenko (Maykop) M95; V. Afanasyev (Kolomna) M95; O. Volkov (Sverdlovsk) M95; O. Viner (village of Gorodovka, Vinnytsia region) M92, M95; A. Dovzhkov (Leningrad) M95; V. Zubarev (Arkhangelsk) M95; I. Bramovskaya (Usolye-Sibirskoye) M92; A. Zaslavsky (Kalinin) M95; G. Zlatkus (Sovetsk, Kaliningrad region) M92; V. Zaporozhskaya (village of Sosnitsy, Chernigov region) M92, M95; A. Golbere (Moscow) M92—M95; V. Korenyako (Voronezh) M92, M94, M95; A. Nikolaev (Moscow) M92—M94; V. Gritsetsich (Chortkiv, Ternovol region) M93, M94; T. Kislitsa (village Sharanga, Gorky region) M95; S. Belchko (Dokuaevsk, Donetsk region) M95; Yu. Kisin (Staraya Russa) M95; R. Kosoy (Odessa) M92, M95; L. Knizhnerman (Moscow) M92; L. Lazareva (Leningrad) M92; V. Lozinov (Moscow) M93; T. Casanov (Tbilisi)

Fig. 11 b.

M95; A. Gritsoryan (Baku) M93, M94; M. Illarinov (Voronezh) M92, M93, M95; A. Sboev (pss. Medvedok, Kirov region) M92, M93, M95; A. Kolchtsov (Gorky) M92, M95; A. Kutsukov (Baku) M92, M93, M95; A. Slinin (Lazovaya, Kharkov region) M94; Yu. Polonsky (Zelenodolsk) M95; V. Nadezhko (Leningrad) M95; L. Rudtser (Kharkov) M95; V. Terentyev (Pavlov, Gorky region) M92; G. Makarov (Zlatoust, Chelyabinsk region) M93, M95; V. Slepchenko (Chelyabinsk) M92, M93, M95; S. Muklytsin (Novosibirsk) M92; I. Porumchikova (Sokolniki, Tula region) M92; M. Rozov (Minsk) M92—M95; M. Preeer (Tomsk) M94—M95; E. Turkevich (Chernivtsi) M92—M95; P. Sereev (Grozny) M95; A. Slikin (Moscow) M92; A. Shmaev (Moscow) M92, M93, M95; A. Udaltsov (Kaliningrad, Moscow region) M92, M93, M95; O. Khudaverdyan (Yerevan) M93, M95; R. Shtsanov (Lyubertsy, Moscow region) M92, M93; G. Fi lkovsky (Baku) M92, M95; Yu. Yakushiin (Lomonosov) M92; E. Chasovnikov (village of Parygino, Zyryanovsky district) M92; I. Yurgel (Glubokoe BSSR) M92; S. Chekmarev (Moscow) M93; N. Famkulin (Kazan) M93, M95; A. Chernyak (Minsk) M92, M93, M95; V. Malchenko (Slavyansk-on-Kuban) M92; R. Soltsas (Vilnius) M95; P. Sukhov (Saratov) M95; A. Sherstyuk (Nikolaev) M93, M95; L. Reznik (Leningrad) M92, M95.

L. Limanov

⟦folio 46⟧

F101

A ball is suspended from a hanging very thin spring with stiffness $k$. At first the spring is not stretched. What is the maximum speed the ball reaches while moving? The mass of the ball is $m$.

Let's write down the equation of motion of the ball. Two forces act on it: the gravitational force $mg$ and the spring tension force $F = kx$, where $x$ is the deformation of the spring. According to Newton's second law

$$mg - kx = ma.$$

From this equation it follows that the acceleration of the ball $a$ is initially directed downwards and decreases, then becomes equal to zero at $x = \frac{mg}{k}$, and then returns again, but is directed upwards.

The speed of the ball returns while its acceleration is directed downward, and decreases when it is directed upward. Therefore, the speed of the ball is maximum at $x = \frac{mg}{k}$.

In order to find it, we write down the law of conservation of energy. If the ball dropped to a distance $x$, then its potential energy decreased by $mgx$, and its kinetic energy increased by $\frac{mv^2}{2}$ (previously it was equal to zero). A fraction of the potential energy of the ball, equal to $\frac{kx^2}{2}$, went to increase the potential energy of deformation of the spring. That's why

$$mgx = \frac{kx^2}{2} + \frac{mv^2}{2}.$$

Hence, for $x = \frac{mg}{k}$ we get

$$v_{\text{max}} = g \sqrt{\frac{m}{k}}.$$

F102

Oxygen and helium were mixed equally in a hermetically sealed vessel. Then a hole was made in the wall of the vessel. What is the composition of the molecular beam emerging from it?

The energy of gas molecules depends only on its temperature. Since the gases in the vessels are in equilibrium and their temperatures are the same, then

$$\frac{m_{\text{O}_2}v_{\text{O}_2}^2}{2} = \frac{m_{\text{He}}v_{\text{He}}^2}{2},$$

where $v_{\text{O}_2}$ and $v_{\text{He}}$ are the average speeds of movement of gas molecules, $m_{\text{O}_2}$ and $m_{\text{He}}$ are their masses. From

46

Fig. 12.

this formula follows that

$$\frac{v_{\text{O}_2}}{v_{\text{He}}} = \sqrt{\frac{m_{\text{He}}}{m_{\text{O}_2}}}.$$

For simplicity, we will assume that gas molecules can move only in three mutually perpendicular directions and the speeds of all molecules are the same and equal to the average speed. Then one sixth of the molecules of each gas moves towards the hole. During time $\Delta t$, those gas molecules that were initially at a distance no greater than $v\Delta t$ from the hole fly out of the vessel. That is, these are oxygen molecules located in volume $v_{\text{O}_2}\Delta t \cdot s$ and hydrogen molecules located in volume $v_{\text{He}}\Delta t \cdot s$ (s is the area of ​​the hole). The total number of such oxygen molecules is $N_{\text{O}_2} = v_{\text{O}_2}sn_{\text{O}_2}\Delta t$ and gel molecules $N_{\text{He}} = v_{\text{He}}sn_{\text{He}}\Delta t$, where $n_{\text{O}_2}$ and $n_{\text{He}}$ are the number of oxygen and gel molecules per unit volume. If there are equal numbers of molecules of both gases in the vessel, then $n_{\text{O}_2} = n_{\text{He}}$ and

$$\frac{N_{\text{O}_2}}{N_{\text{He}}} = \frac{v_{\text{O}_2}}{v_{\text{He}}} = \sqrt{\frac{m_{\text{He}}}{m_{\text{O}_2}}} = \frac{1}{2\sqrt{2}}.$$

If the masses of gases in the vessel are equal, then $m_{\text{O}_2}n_{\text{O}_2} = m_{\text{He}}n_{\text{He}}$ and

$$\frac{N_{\text{O}_2}}{N_{\text{He}}} = \frac{v_{\text{O}_2}}{v_{\text{He}}} \cdot \frac{n_{\text{O}_2}}{n_{\text{He}}} = \sqrt{\frac{m_{\text{He}}}{m_{\text{O}_2}}} \cdot \frac{m_{\text{He}}}{m_{\text{O}_2}} = \frac{1}{16\sqrt{2}}.$$

F103

Two series of shots are fired from the cannon, tilting the barrel at angles $30^\circ$ and $40^\circ$ to the horizon. In what case will shell hits be more concentrated if the spread is caused by inaccurate aiming, and not by the spread of initial projectile velocities? Air resistance should be considered negligible.

Let us first find the dependence of the further flight of the projectile on the angle of its departure. Let's write it down

⟦folio 47⟧

for this, the kinematic equations of projectile motion. If the speed of the projectile is equal to $v_0$, and the angle at which the projectile flies out of the ordium is equal to $\alpha$, then in the vertical direction along the axis $y$ the projectile moves with acceleration $a=-g$ and initial speed $v_{0y}=v_0 \sin \alpha$. Therefore, the change in coordinate $y$ of the projectile is determined by the equation

$$y = v_0 t \sin \alpha - \frac{g t^2}{2}.$$

Horizontally along the $x$ axis, the projectile moves uniformly with a speed $v_x=v_0 \cos \alpha$. That's why

$$x = v_0 t \cos \alpha.$$

At the moment of falling to the ground $y=0$ and $v_0 t \sin \alpha - \frac{g t^2}{2} = 0.$

From here you can find the time of movement of the projectile. It is equal to $t = \frac{2v_0 \sin \alpha}{g}$. Now substituting this expression into the equation of horizontal motion, we find that the projectile flight range is equal to

$$x_{\max} = \frac{2v_0^2 \sin \alpha \cos \alpha}{g} = \frac{v_0^2 \sin 2\alpha}{g}.$$

This is the expression for the maximum at sin $2\alpha=1$, that is, at $\alpha=45^\circ$.

Let's draw a graph of the dependence of the projectile's flight range on $\alpha$ (Fig. 12). For small deviations $\Delta \alpha$ of the projectile departure angle, the dependence graph $x_{\max}(\alpha)$ can be replaced by a straight line - a tangent to the actual graph $x_{\max}(\alpha)$. The greater the slope of this tangent, the greater the error in the range of the projectile for the same error $\Delta \alpha$ in the angle of departure of the projectile.

From figure 12 it is clear that at small projectile departure angles the angle of inclination of the tangent to the horizon (to the $0\alpha$ axis) is greater than at large ones. This means that at small projectile departure angles, the change in range when changing the departure angle is greater than at large ones, and with an arrow with a barrel angle of $40^\circ$, the accuracy of projectiles will be higher than at an angle $30^\circ$.

The same result can be obtained using formulas. Let the error in the projectile departure angle be small and amount to $\Delta \alpha$. Then the error $\Delta x$ in the projectile range is

$$\Delta x = \frac{v_0^2}{g} \sin 2\alpha - \frac{v_0^2}{g} \sin [2(\alpha + \Delta \alpha)] = 2 \frac{v_0^2}{g} \cos(2\alpha + \Delta \alpha) \sin \Delta \alpha \approx 2 \frac{v_0^2}{g} \cos 2\alpha \cdot \Delta \alpha.$$

Thus, $\Delta x$ is proportional to $\Delta \alpha$, but the coefficient of the proportional depends on $\alpha$. The smaller the angle $\alpha$, the larger it is.

F104

In a closed container there are several drops of liquid of different sizes. What will happen to him after a long time?

The saturated vapor pressure at the surface of the drop depends on its radius. Let's show it.

Let us imagine a closed vessel in which there is a capillary tube, a non-wettable liquid. The pressure at point $B$ is greater than the pressure at point $A$ (Fig. 13) by amounts $\rho_{\pi}gh$:

$$P_B = P_A + \rho_{\pi}gh,$$

where $h$ is the difference in liquid levels in the capillary and in the vessel, $\rho_{\pi}$ is the vapor density.

Since the liquid film in the capillary is in equilibrium under the action of two forces: the tension surface force equal to $2\pi r\sigma$ (σ is the tension surface coefficient, r is the capillary radius) and the fluid pressure force at a depth $h$ equal to $\rho_{\pi}gh \cdot \pi r^2$ ($\rho_{\pi}gh$ is the liquid density), then $2\pi r\delta = \pi \rho_{\pi}ghr^2$.

From here

$$h = \frac{2\sigma}{\rho_{\pi}gr}$$

And

$$P_B = P_A + \frac{2\sigma}{r} \frac{\rho_{\pi}}{r_{\pi}}.$$

Thus, the smaller the radius of the drop, the greater the pressure above the surface of the liquid. This means that if steam is saturated above the surface of a small drop, then above the surface of a larger drop it will not be saturated. This will cause steam to condense on the large drop, thereby affecting the steam pressure at the surface of the small drop. This in turn causes the small droplet to evaporate. As a result, after some time only one large drop remains in the vessel.

The same result can be obtained from the most general reasoning. Let us assume that there is liquid in the vessel (the surface of the liquid is flat) and there is a drop.

⟦folio 49⟧

From the second equation it follows that this triangle is right-angled and the angle between the electric velocity vectors is 90°

F107

In the circuit shown in figure 16, the voltmeter changes the voltage drop across the resistance $R=300$ com. What should the voltmeter's resistance be so that its readings differ by no more than 2% from the actual value $u_R$? Internal resistance of the source of claims.

In the absence of a voltmeter, resistances $R$ and $R_1$ are switched on in series. Therefore, the voltage drop across resistance $R$ is equal to $u_R = \frac{R}{R+R_1} E$. When a voltmeter is connected, it will change the voltage drop in the section consisting of parallel-connected resistances $R$ and voltmeter resistance $r$. Voltmeter shows values

$$u' = \frac{Rr}{R+r} E$$

According to the condition, the voltmeter reading should differ by no more than 2% from the value $u_R$. That's why

$$\frac{u_R - u'}{u_R} \leq 0,02.$$

Substituting the expressions for $u_R$ and $u'$ into this equation, we find that the resistance of the voltmeter should not exceed 3675 kΩ.

Correct solutions were sent by: V. Avseikov (Sevastopol) $\Phi 103$, $\Phi 105$—$\Phi 107$; A. Alexandrov (Glazov UASSR) $\Phi 100$; P. Amosov (Yaroslavl) $\Phi 100$; S. Araslanov (Nizhne-Ivkino, Kirov region) $\Phi 103$, $\Phi 107$; V. Belov (Vologda) $\Phi 100$—$\Phi 105$, $\Phi 107$; A. Blokhin (Kiselevsk, Kemerovo region) $\Phi 106$, $\Phi 107$; L. Brachinsky (Frunze) $\Phi 101$; A. Bratkovsky (Moscow) $\Phi 103$, $\Phi 104$, $\Phi 106$; A. Budnikov (Slavyansk, Donetsk region) $\Phi 101$; A. Buzulukov (Novosibirsk) $\Phi 107$; Y. Givi Dolidze (Tbilisi) $\Phi 101$; V. Glem-

$$R_1 = 100\text{ ком}$$

Botsky (Yaroslavl) $\Phi 101$, $\Phi 102$; E. Gromak (Novokuznetsk) $\Phi 103$, $\Phi 106$; M. Dzik (village of Kratovo, Armavir district, Tyumen region) $\Phi 101$, $\Phi 103$; A. Dovspevich (Moscow) $\Phi 101$; E. Dolov (Moscow) $\Phi 100$, $\Phi 101$; E. Domov (Moscow) $\Phi 03$, $\Phi 106$; G. Zaitsev (Gagra) $\Phi 101$, $\Phi 103$, $\Phi 106$, $\Phi 107$; S. Zanetsochny (Uzhgorod, Transcarpathian region) $\Phi 101$; N. Zykov (Saratov) $\Phi 101$; O. Zamova (Moscow) $\Phi 100$; A. Ivanov (Lgov, Kursk region) $\Phi 102$; Y. Imin (Cutter of Gomel region) $\Phi 101$; A. Istomin (Podolsk, Moscow region) $\Phi 103$, $\Phi 105$; T. Casanov (Tbilisi) $\Phi 103$, $\Phi 106$; A. Karimov (Ufa) $\Phi 101$; T. Kislicina (village of Sharanga, Gorky region) $\Phi 105$, $\Phi 107$; Yu. Kisin (Staraya Russa) $\Phi 103$; L. Knizherman (Moscow) $\Phi 100$—$\Phi 103$; L. Kodan (Chernivtsi) $\Phi 101$; M. Kolodochkin (Moscow) $\Phi 101$; S. Korillov (Grozny) $\Phi 101$; V. Kolomitsev (Rostov-on-Don) $\Phi 101$; P. Konev (Plees, Ivanovo region) $\Phi 101$; V. Kamanov (village of Tsalka, GSSR) $\Phi 101$; V. Komenov (Moscow) $\Phi 101$; V. Krylov $\Phi 100$; S. Kuzmich (Zhitomir) $\Phi 103$, $\Phi 105$, $\Phi 107$; V. Kulii (Mogilno village, Brest region) $\Phi 101$; V. Kuusk (Rzhev) $\Phi 100$, $\Phi 101$, $\Phi 104$, $\Phi 106$; G. Levi (Kuibytsev) $\Phi 101$; V. Lukashin (Moscow) $\Phi 101$; Yu. Lurie (Grozny $\Phi 101$; A. Mamula (village of Dobintsy, Boguslavsky district, Kyiv region) $\Phi 101$, $\Phi 102$, $\Phi 107$; Yu. Murzanov (village Rodinkovsky, Krasnodar Territory) $\Phi 101$; M. Maron (Kuibytsev) $\Phi 100$, $\Phi 101$; I. Mats (Makeevka) $\Phi 100$; L. Menkova (Alexandrov, Vladimir region) $\Phi 101$; V. Nadezhko (Leningrad) $\Phi 101$, $\Phi 107$; A. Nikolaev (Sverdlovsk) $\Phi 107$; S. Pomashey (Ulyanovsk) $\Phi 100$, $\Phi 101$; Yu. Polonsky (Zelenodolsk TASSR) $\Phi 101$; M. Preer (Tomsk) $\Phi 100$, $\Phi 101$, $\Phi 105$, $\Phi 106$; L. Rudtser (Kharkov) $\Phi 101$, $\Phi 105$; L. Safulin (village B. Gardens of the TASSR) $\Phi 107$; P. Sergeev (Grozny) $\Phi 100$, $\Phi 101$, $\Phi 103$, $\Phi 106$, $\Phi 107$; I. Sidorov (Moscow) $\Phi 100$, $\Phi 101$; G. Simonenkov (Couns) $\Phi 106$; M. Solomonovich (Chisinau) $\Phi 101$; E. Sychudov (village of Krasnodar region) $\Phi 101$; M. Taits (Moscow) $\Phi 101$; O. Tatarinskaya (Almaty) $\Phi 101$; I. Turishche (Kropotkin, Krasnodar Territory) $\Phi 100$, $\Phi 102$, $\Phi 103$, $\Phi 105$, $\Phi 107$; A. Udaltsov (Kaliningrad, Moscow region) $\Phi 105$; V. Faimelevich (Ramavir) $\Phi 100$—$\Phi 102$; G. Fast (Karagana) $\Phi 104$; I. Fedin (Omsk) $\Phi 100$—$\Phi 103$, $\Phi 105$, $\Phi 107$; G. Furmanov (Chernivtsi, Ukrainian SSR) $\Phi 101$; M. Khomenenko (Vitebsk) $\Phi 102$; O. Khudaverdyan (Yerevan) $\Phi 103$, $\Phi 107$; S. Chekmarev (Moscow) $\Phi 100$—$\Phi 103$, $\Phi 105$, $\Phi 107$; E. Chasovnikov (parychino village, Zyknovsky district) $\Phi 101$; S. Chernikov (Sempalatinsk) $\Phi 101$; Zh. Shenemko (D.-Gorodok, Brest region) $\Phi 103$, $\Phi 104$, $\Phi 107$; A. Sherstyuk (Nikolaev Ukrainian SSR) $\Phi 107$; R. Shzaanov (Lyubertsy, Moscow region) $\Phi 101$; V. Shuvalov (Electrostal) $\Phi 101$; I. Yurenko (Kyiv) $\Phi 101$.
