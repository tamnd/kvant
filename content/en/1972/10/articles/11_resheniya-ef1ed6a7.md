---
id: 1972-10-resheniya-ef1ed6a7
issue: kvant_1972_10
year: 1972
number: "10"
title: Solutions to problems M126—M128; F142—F147
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 42
page_last: 48
page_labels: 40-46
tag: UKWM
lang: en
source: kvant_digital
extraction: vision
content_sha256: b5b1ae53a2e9ba1eee2dd7e386964fe1fffaae56f79b853394a0a264d6e03ec4
prompt_sha256: draft-1
translated_from: content/ru/1972/10/articles/11_resheniya-ef1ed6a7.md
source_content_sha256: 36cbecfceb4ff4339a0aa0afa3676eebff850ffb0987faadca261c2bff90e4f4
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 40⟧

SOLUTIONS

In this issue we publish solutions to problems M126–M128

M126

A polygon circumscribed around a circle of radius $r$ is somehow cut into triangles. Prove that the sum of the radii of the inscribed circles of these triangles is greater than $r$.

Let $S$ be the area of ​​a given polygon, $p$ be the area of ​​its perimeter; $S_i$, $p_i$, $r_i$ - respectively, the area, derivators and radii of the inscribed circles of the triangles into which it is cut ($i = 1, 2, ..., n$). Then $S = pr$, $S_i = p_i r_i$ and $p > p_i$ for all $i$ (it is not difficult to prove that the perimeter of a polygon is greater than the perimeter of any convex polygon it contains). That's why

$$r_1 + r_2 + \cdots + r_n = \frac{S_1}{p_1} + \frac{S_2}{p_2} + \cdots + \frac{S_n}{p_n} > \frac{S_1}{p} + \frac{S_2}{p} + \cdots + \frac{S_n}{p} = \frac{S}{p} = r.$$

The last equality is illustrated by figure 1.

M127

For each natural number $n$ we denote by $s(n)$ the sum of its digits (in decimal notation). Let's call a natural number $m$ special if it cannot be represented as $m = n + s(n)$, where $n$ is some natural number. (For example, the number 117 is not special because $117 = 108 + s(108) = 108 + 9$, but the number 121, as you can easily see, is special.) Is it true that there are only a finite number of special numbers?

Answer: This statement is false; There are an infinite number of special numbers.

The idea of ​​the most natural solution is as follows. Let's consider all numbers $n$ from 1 to some $N$. Among them there is a certain number of $R_N$ such $n$ for which $n + s(n) > N$. Therefore, the numbers from 1 to $N$ are certified to have no more than $N - R_N$ numbers representable as $n + s(n)$, that is, at least $R_N$ numbers are special (we are not even taking into account here that some numbers are representable as $n + s(n)$ in more than one way). It remains to make sure that by choosing $N$ accordingly, we can obtain the angle greater than $R_N$.

This idea is found in the decisions of V. Bikmashev and A. Weintrob from Moscow, A. Grigoriyan from Baku, I. Majulis from Riga and some other readers. To bring it to a complete solution, we prove that among the numbers $n$ from 1 to $N = 10^{10^k} + k$ there are significantly more $10^k$ such for which $n + s(n) > N$. Indeed, if $n < N$ and $n \geq N_1 = (10^{10^k} - 1) 10^k = 9 \dots 90 \dots 0 (10^k$ are nines and $k$ are zeros), then $n + s(n) \geq (10^{10^k} + k - 10^k) + 9 \cdot 10^k > N$,

and the number of numbers $n$ such that $N_1 \leq n \leq N$ is equal to $N - N_1 + 1 = 10^k + 1$.

⟦folio 41⟧

Another solution (it was carried out most accurately in the works of A. Pechkovsky from Moscow and L. Puets from Dnepropetrovsk) indicates a method that allows one to construct a specific sequence of special numbers. Here is one such sequence:

$$m_1 = 9 + 11 = 20,$$
$$m_2 = 20 + 101 = 121,$$
$$m_3 = 121 + 1001 = 1122,$$

where $m_k = m_{k-1} + 10^k + 1$.

Let us prove by induction that all these numbers are special. Suppose this is true for $m_{k-1}$ ($k \ge 3$), but not for $m_k$: $m_k = n + s(n)$.

Before using this assumption, let us prove that the decimal expansion of the number $m_k$ looks like this:

$$m_k = 10^k + a_{k-1} 10^{k-1} + \dots + a_0,$$

where the number is $a_{k-1} \neq 0$, that is, $11 \cdot 10^{k-1} < m_k < 2 \cdot 10^k$. The left inequality is very indo, and the right one can be verified by induction: $m_k = m_{k-1} + 10^k + 1 < 2 \cdot 10^k - 1 + 1 = 12 \cdot 10^{k-1} + 1 < 2 \cdot 10^k$.

Now we can prove that the decimal notation of the number $n$ also begins with one: $n = 10^k + b_{k-1} \cdot 10^{k-1} + \dots + b_1 \cdot 10 + b_0$, that is, that $10^k < n < 2 \cdot 10^k$. Here the right inequality is very indo, and the left one is proved by contradiction: if $n < 10^k$, then $s(n) < 9k$ and $n + s(n) < 10^k + 9k < 10^k + 10^{k-1} = 11 \cdot 10^{k-1} < m_k (9k < 10^{k-1}$ for $k \ge 3$).

Let us denote the number $n - 10^k$ (the number $n$ with the first digit equal to one discarded) by $n^*$. Then, very indo, $s (n^*) = s(n) - 1$ and therefore

$$n^* + s (n^*) = n - 10^k + s(n) - 1 = m_k - 10^k - 1 = m_{k-1}.$$

Thus, it turns out that the number $m_{k-1}$ is not special. The contradiction with the assumption proves the validity of the inductive transition from $k - 1$ to $k$. It is not difficult to establish that the numbers $m_1$ and $m_2$ are special.

**M128**

Find the ratio of the side of a triangle, one of whose medians is divided by the incircle into three equal parts.

Let $BK$ be the median of the triangle $ABC$ - the incircle is divided into equal segments $BM = MN = NK = x$, $AB = c$, $BC = a$, $CA = b$ and $T$ - the point of tangency of the incircle on the side $BC$ (Fig. 2).

Fig. 2.

The following two ABC matches are most needed:

$$a + c - b = 2BT,$$
$$2a^2 + 2c^2 - b^2 = 4BK^2$$

(the first is derived from the equalities $BT + CT = a$, $BT - CT = c - b$; the second is easy to prove by completing the triangle to form a parallelogram $ABCD$). From the second equality we find

$$2a^2 + 2c^2 - b^2 = 36x^2. \quad (1)$$

Since, since the points $B$ and $K$, very indo, are equally distant from the center of the incircle, then $BC = KC$, whence

$$b = 2a. \quad (3)$$

Substituting (3) into (1) and (2), we find

$$c^2 - a^2 = 18x^2, \quad (c - a)^2 = 8x^2.$$

From these equalities we obtain (it is clear that $c - a \neq 0$, $x \neq 0$):

$$\frac{c + a}{c - a} = \frac{9}{4},$$

whence $\frac{c}{a} = \frac{13}{5}$.

Answer: $a:b:c = 5:10:13$.

It is not difficult to check that in a triangle with such a side ratio, the median of side $b$ will indeed be divided by the incircle into three equal parts (when checking, it is convenient to use the same formulas that were used above).

Correct solutions to some of the problems M121 - M128 added: V. Ashaskiy (Moscow) M126; V. Astmankovi (Borisov BSSR) M124; V. Birch (Gorky) M122 - M123; A. Blyukhin (Kiselevsk, Kemerovo region) M123; A. Bikmatsev (Moscow) M126 - M128; A. Boedanov (Glazov, Udmurt Autonomous Soviet Socialist Republic) M128; A. Botsarov (Nikolaev) M126 - M128; L. Braetskin (Frunze) M126; A. Brutmer (Chisinau) M128; O. Burlakov (Tashkent) M128; A. Weintrob (Moscow) M126 - M128; T. Galkina (Kuibyshev) M126; L. Genriinovich (Tashkent) M126, M128; A. Gordienko (village of Poltachenko, Krasnoarsk Territory) M122, M126; A. Grigoryan (Baku) M126; V. Greenman (Moscow) M124; A. Demidov (Moscow) M124; V. Drobimko (Kherson) M126; V. Evdokimov (Yaroslavl) M123; A. Edrenkin (Moscow) M126; M. Zhukov (Baku) M128; A. Zhumadildaev (Alma-Ata) M122 - M124; V. Zarubin (Letniy settlement, separate Moscow region) M126; V. Zablochiky (Donetsk) M128; E. Zeiman (Orrey Moldavian USSR) M126; T. Zlamkus (Sovetsk, Kaliningrad region), M128; I. Nenatyev (s. Sarmanovo, Tatar Autonomous Soviet Socialist Republic) M128; M. Ilartsionov (Voronezh) M121 - M124, M126, M128; S. Ioannidi (Tbilis) M128; M. Kaul (Frunze) M121, M122, M124; A. Kvasov (Moscow) M122 - M124, M126; A. Kislenev (Moscow) M122; Yu. Kisin (Staraya Russa) M123, M124, M126; V. Kleimenov (Ulan-Ude) M126; V. Kolosov (Kyiv)

⟦folio 42⟧

In this issue we publish solutions to problems F142—F147

F142

A steel ball suspended on a thread of length l was deflected so that the thread assumed a horizontal position and released. At the moment when the thread made an angle α=30° with the vertical, the ball hit a stationary steel plate (Fig. 3). To what height does the ball rise after hitting the plate, if the impact can be considered absolutely elastic?

Let the speed of the ball at the moment of its impact on the plate be equal to v. This speed is directed perpendicular to the thread. Since the impact of the ball is absolutely elastic and, therefore, instantaneous, when it hits the ball it behaves as if it were free, not connected to the thread. Therefore, the speed of the ball upon impact changes only in direction, so that the angle of reflection of the ball from the plate is equal to the angle of incidence. This means that after hitting the plate it moves at a speed v₁=v cos 2α, perpendicular to the thread. The energy of the ball immediately after the impact is equal to $\frac{mv_1^2}{2}$; when the ball rises to a height h, it becomes equal to mgh. (Often, the total kinetic energy of the ball W = $\frac{mv^2}{2} = \frac{mv_1^2}{2} + \frac{mv_2^2}{2}$ after the impact will turn into the energy of vibration of the ball along the thread or, ultimately, in the tello. The magnitude of this loss is $\frac{mv_2^2}{2}$.

⟦folio 43⟧

According to the law of conservation of energy

$$\frac{mv_1^2}{2} = mgh \quad \text{или} \quad \frac{v^2 \cos^2 2\alpha}{2} = gh.$$

Let us now find the speed $v$ of the ball at the moment of its collision with the plate. Initially, the ball is at a height $H = l \cos \alpha$ above the plate. The change in the potential energy of the ball when moving from the first initial position to the collision with the plate is equal to the kinetic energy acquired by the ball:

$$\frac{mv^2}{2} = mgl \cos \alpha.$$

From here

$$v^2 = 2gl \cos \alpha.$$

Hence,

$$h = \frac{v^2 \cos^2 2\alpha}{2g} = l \cos \alpha \cos^2 2\alpha = \frac{\sqrt{3}}{8} l.$$

F143

The plane lands on the deck of the carrier at a speed of 100 km/h. Having aimed at the braking rope, the plane runs 50 m until it comes to a complete stop. Determine overloads if the elasticity coefficient of the rope does not change as it stretches.

When the aircraft is braking, a force $F = kx$ acts on it from the side of the rope, where $x$ is the rope extension, $k$ is its elasticity coefficient. This force increases as the rope stretches. Acceleration also increases

$$a = \frac{F}{M} = \frac{k}{M} x,$$

we report the force $F$ of the aircraft (M is the mass of the aircraft).

But the acceleration $a$ moves not only the plane, but also the pilot, held by straps on the seat. This acceleration is imparted to the pilot by the force $T$ acting on him from the belts. If the mass of the pilot is $m$, then

$$T = ma = \frac{mk}{M} x.$$

This force is maximum at $x = L = 50$ m,

$$T_{\text{max}} = \frac{mkL}{M}.$$

(1)

The expression for $T$ includes the elasticity coefficient of the rope. Let's find him.

The kinetic energy of the aircraft at the moment of landing is obviously equal to the work done by the force $F$. This force changes with the distance $x$ traveled by the aircraft when fired by the carrier. Let's draw a graph of the dependence of $F$ on $x$ (Fig. 4). Obviously, the work done by force $F$ on path $L$ is equal to the area of ​​the triangle under the graph of $F$ versus $x$, that is, $A = \frac{1}{2}kL \cdot L = \frac{kL^2}{2}$. Therefore, $\frac{kL^2}{2} = \frac{Mv^2}{2}$. Hence $k = \frac{Mv^2}{L^2}$.

Substituting the expression for $k$ into formula (1), we obtain

$$T_{\text{max}} = m \frac{v^2}{L} = mg \frac{v^2}{Lg} \approx 1,5mg.$$

From the sides of the seat and the belts, mutually perpendicular forces act on the pilot: the normal reaction force of the seat $N$ and the tension force of the belts $T$. These equally acting forces are equal in absolute value to the weight of the pilot $P$ (weight is the force with which the pilot acts on the seat and belts):

$$R = \sqrt{T_{\text{max}}^2 + (mg)^2} \approx 1,8 \text{ mg}.$$

This means that the weight of the raft is 1.8 times its weight under normal conditions.

F144

What must be the ratio of the triangle to the floor in order for it to stand as shown in figure 5? The length of the thread holding the rod is equal to the length of the rod.

⟦folio 44⟧

Since the rod is in equilibrium, the sum of the projections of all forces acting on it in the vertical and horizontal directions must be equal to zero. The forces acting on the rod are shown at figure 5. This means that
$$F_{ТР} - T \sin \alpha = 0,$$
$$N + T \cos \alpha - mg = 0.$$

Let us also write down the conditions that the rod does not rotate around point C. To do this, the sum of the moments of all forces relative to point C must be equal to zero:

$$Tl \sin \alpha - mg \frac{l}{2} \sin \alpha = 0.$$

From equation (2) it follows that $T = \frac{1}{2} mg$. Let us rewrite, taking this into account, equations (1). We also learn that at the lowest friction coefficient, when equilibrium of the rod is still possible, $F_{ТР} = kN$:

$$kN - \frac{1}{2} mg \sin \alpha = 0,$$
$$N + \frac{1}{2} mg \cos \alpha - mg = 0.$$

From here
$$kN = \frac{1}{2} mg \sin \alpha,$$
$$N = mg \left(1 - \frac{1}{2} \cos \alpha\right).$$

Hence,
$$k = \frac{\sin \alpha}{2 - \cos \alpha} = \frac{\sqrt{3}}{3}.$$

F145

An ideal gas first goes from state 1 ($P_1, V_1, T_1$) to state 2 ($P_2, V_2, T_2$). Then, from state 2, the gas slowly adapts (without supplying the calf) and passes into state 3 ($P_3, V_3, T_3$). It is known that during the transition 2→3 the gas performs work equal to the amount of work imparted to the gas during the transition 1→2. Show that $T_3 = T_1$. Draw processes 1→2 and 2→3 on the VT plane.

Since during the process $1 \rightarrow 2$ $V = V_1 =$ const, the gas does not do work and the change in the internal energy of the gas $\Delta W_1$ is equal to the amount of heat $Q$ imparted to the gas:

$$Q = \Delta W_1.$$

Process 2→3 adapts ($Q = 0$), which means that the gas does work due to internal energy. Therefore, the work $A$ done by the gas is equal to the change in its internal energy:

$$A = \Delta W_2.$$

We compare (1) and (2), we find that
$$\Delta W_1 = \Delta W_2.$$

But the internal energy of a gas is proportional to its absolute temperature. This means that during process 2→3 and process 1→2 the gas temperature changes the same. Therefore, $T_1 = T_3$.

Process graphs are shown at figure 6. Since during process 1→2 the internal energy of the gas increases, then $T_2 > T_1$. Since during the process 2→3 the gas does work, then $V_3 > V_1$.

Obviously, our answer is valid only if $V_1 \rightarrow 2 =$ const.

F146

There is a battery with e. d.s. $E = 100$ $\theta$ and internal resistance $r = 2$ $\Omega$. At the load you need to get a voltage $U = 20$ $\theta$, and when the load resistance $R$ changes from 50 $\Omega$ to 100 $\Omega$ the voltage on it should change by no more than 2%. Come up with a simple circuit to power the load and calculate the parameters of this circuit.

One of the simplest circuits is the sequential connection of resistance $R$ load, resistance $R_1$ and source (Fig. 7). In this case, if the load resistance is 50 $\Omega$, then in order for the voltage across the load to be equal to 20 $\Omega$ (that is, it is 1/5 of the emf of the source $E$), the sum of the source resistance and resistance $R_1$ must be 200 $\Omega$. But in this case, with a load resistance of 100 $\Omega$, the voltage across it will be

$$U = E \frac{R}{R_1 + R + r} = \frac{100}{3} \theta \approx 33,3\theta.$$

⟦folio 45⟧

Fig. 8.

Consequently, with such a scheme for connecting the load to the source, the change in voltage across the load is much greater than 2%.

The other circuit is the "divider" circuit (Fig. 8). It is clear that when the resistance $R_2$ is small compared to the load resistance, the total resistance of the circuit section enclosed by a frame at figure changes little when the load resistance changes. The voltage across the load also changes little.

Let's calculate the parameters of the “divider”. The load voltage is
$$U = IR_2'$$
where $I = \frac{E}{R_1 + r + R_2'}$ is the current in the circuit and $R_2' = \frac{R_2R}{R_2 + R}$ is the resistance of the area surrounded by a frame.

$$U = \frac{E}{R_1 + r + \frac{R_2R}{R_2 + R}} \cdot (1)$$

In this scheme, e. d.s. the source is divided between resistance $R_2'$ and resistance $R_1 + r$. The greater the resistance $R_2'$, the greater the voltage across the load. On the other hand, the resistance $R_2'$ increases as the load resistance $R$ increases. (The graph of $R_2'$ versus $R$ is shown in figure 9.) If with a load resistance of $R = 50$ ohms the voltage across the load is 20 $\beta$, then with a load resistance of $R = 100$ ohms the voltage across it should be 2% higher, that is, 20.4 $\beta$. Substituting the numerical values ​​of all known quantities into formula (1), we obtain two equations:

$$\begin{align*}
\frac{100}{2 + R_1 + \frac{50R_2}{R_2 + 50}} &= 20, \\
\frac{100}{2 + R_1 + \frac{100R_2}{R_2 + 100}} &= 20,4,
\end{align*}$$

and the force $F$ imparts to him the centripetal acceleration $\frac{v^2}{r}$, then

$$F = m \frac{v^2}{r},$$

or $\frac{e^2}{r^2} = m \frac{v^2}{r}$.

From this equality it follows that

$$mv^2 = \frac{e^2}{r}.$$

⟦folio 46⟧

Therefore, the kinetic energy of the electron is equal to

$$W_K = \frac{m v^2}{2} = \frac{e^2}{2 r}.$$

Now we can find the total energy of an electron in an orbit of radius $r$:

$$W = W_K + W_\pi = \frac{e^2}{2 r} - \frac{e^2}{r} = -\frac{e^2}{2 r}.$$

The energy of a photon emitted by an atom is:

$$E = W_1 - W_2 = -\frac{e^2}{2 r_1} - \left(-\frac{e^2}{2 r_2}\right) =$$

$$= \frac{e^2}{2} \left(\frac{1}{r_2} - \frac{1}{r_1}\right) = 16, 3 \cdot 10^{-12} \text{ erp}.$$

Since the energy of a photon is related to its frequency $v$ by the formula $E = hv$, where $h$ is Planck’s constant, then

$$v = \frac{E}{h} = 2, 6 \cdot 10^{15} \text{ c}^{-1}.$$

The editors received more than 600 letters. Almost all letters contain rules for solving problems $\Phi 139$, $\Phi 143$, $\Phi 144$. The correct solutions to the remaining problems are provided by the following readers: A. Hayrapemyan (Yerevan) $\Phi 142$, $\Phi 145$, $\Phi 147$; A. Andreev (Leningrad) $\Phi 145$, $\Phi 146$; Sh. Atakulov (Fergana) $\Phi 145$, $\Phi 146$; A. Alyaev (Arzamas) $\Phi 147$; A. Asasyan (Yerevan) $\Phi 147$; V. Belkov (Moscow) $\Phi 142$; I. Bramovskaya (Usolye-Sibirskoe) $\Phi 145$; A. Baevsky (Gomel) $\Phi 138$, $\Phi 142$; V. Burkin (Sterlitamak) $\Phi 147$; M. Bolyshakov (Saratov) $\Phi 146$, $\Phi 147$; A. Blinov (Moscow) $\Phi 142$; M. Brenerman (Kazan) $\Phi 145$; Bardina (Novokuznetsk) $\Phi 145$, $\Phi 147$; A. Borminkov (Krasnodar) $\Phi 142$; O. Belkin (Orenburg) $\Phi 147$; A. BakULEV (Moscow) $\Phi 142$; T. Weintraub (Chisinau) $\Phi 145$—$\Phi 147$; V. Vorobiev (Koutancy) $\Phi 147$; V. Vekshtein (Kyiv) $\Phi 145$; I. Vasitsak (Kyiv) $\Phi 140$; A. Barinov (Zhukovsky, Moscow region) $\Phi 145$; I. Vacker (Minsk) $\Phi 142$; Yu. Gorny (Khadzhensk, Krasnodar region) $\Phi 147$; S. Granin (Dzerzhinsk) $\Phi 145$; O. Glutsenenko (Glukhov, Sumy region) $\Phi 142$; A. Goffman (Moscow) $\Phi 140$; V. Gerasimov (Sarapul) $\Phi 147$; S. Grigoryan (Yerevan) $\Phi 147$; A. Grigoriev (Grozny) $\Phi 147$; S. Gorodnikov (Grozny) $\Phi 145$; S. Dick (Zhodino, Minsk region) $\Phi 145$; V. Derevezin (Donetsk) $\Phi 145$, $\Phi 147$; E. Dollov (Moscow) $\Phi 142$, $\Phi 145$; V. Dashkevich (Kirovsk, Mogilev region) $\Phi 145$; A. Davisikov (Leningrad) $\Phi 142$; A. Danizl (Leningrad) $\Phi 145$; A. Dorofeev (village of Fokino, Gorky region) $\Phi 142$; S. Egorov (Klimovsk, Moscow region) $\Phi 147$; A. Edrenkin (Moscow) $\Phi 145$, $\Phi 147$; V. Zhelezny (Leningrad) $\Phi 146$; V. Zindels (Kyiv) $\Phi 145$; A. Zboev (Medvedok village, Kirov region) $\Phi 140$; V. Zabolochkin (Donetsk) $\Phi 142$, $\Phi 147$; I. Zmukko (village of Ruzhany, Brest region) $\Phi 145$; A. Izrailevich (Sverdlovsk) $\Phi 147$; P. Kryshenik (Uzhgorod) $\Phi 147$; V. Kolesnikov (Chelyabinsk) $\Phi 142$; S. Korneev (Novokuznetsk) $\Phi 145$; A. Krechemnikov (Sumy) $\Phi 140$; V. Kadaer (Moscow) $\Phi 140$—

46
