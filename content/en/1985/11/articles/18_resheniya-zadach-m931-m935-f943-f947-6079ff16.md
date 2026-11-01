---
id: 1985-11-resheniya-zadach-m931-m935-f943-f947-6079ff16
issue: kvant_1985_11
year: 1985
number: "11"
title: Solutions to problems M931—M935; F943—F947
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 38
page_last: 45
page_labels: 36, 37, 38, 39, 40, 42, 43
tag: 01IW
lang: en
source: kvant_digital
extraction: vision
content_sha256: fdf8a629f75a666bf43606f71ac1e58eb46d087a098023cc6345e65209a06702
prompt_sha256: draft-1
translated_from: content/ru/1985/11/articles/18_resheniya-zadach-m931-m935-f943-f947-6079ff16.md
source_content_sha256: 9813283dcfc837c9ef4df578907b3d0096693c33fddc145b8fd614cf02f95d02
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 36⟧

a thread $AB$ (Fig. 3, p. 34) is punctured; the thread, which had been floating freely on the film, stretches into a definite shape. Find the tension in the thread. The distance between the «directrices» is $d$, the length of the thread is $l$ ($l > \pi d/2$), the coefficient of surface tension of the soap solution is $\sigma$.

L. G. Markovich

P967. A pile of very thin metal plates, located at the same distance from each other, is charged from a battery in the following way. The negative contact of the battery is connected to the plate furthest to the right, while the positive contact is connected in sequence first to the first plate from the left, then to the second one, the third and so on until the next to last plate (the second one from the right, see Fig. 4). Find the ratio of the charge of the far right plate to that of the third from the right. Assume that the thickness of the pile is much less than its linear measurements.

E. P. Sokolov

Problem solutions

M931 — M935; F943 — F947

Consider the triangles $AA_1B_1$ and $BB_1A_1$ (Fig. 1). They have a common side $A_1B_1$ and equal sides $AA_1$ and $BB_1$. In addition, their angles $AB_1A_1$ and $BA_1B_1$ are equal, since the angles adjacent to them are the angles at the base of the equilateral triangle $A_1B_1C$ (the segments $CA_1$ and $CB_1$ are equal, like tangents drawn to a circle from one point); for the same reason, angles $AB_1A_1$ and $BA_1B_1$ are tula, therefore, the remaining angles of the triangles under consideration are acute. According to the theorem of sines

$$\sin \angle A_1AB_1 = \frac{A_1B_1}{A_1A} \sin \angle AB_1A_1 =$$

$$= \frac{A_1B_1}{B_1B} \sin \angle BA_1B_1 = \sin \angle B_1BA_1,$$

poses $\angle A_1AB_1 = \angle B_1BA_1$ (these angles are acute), which means $\angle AA_1B_1 = \angle BB_1A_1$ too. Thus, triangles $AA_1B_1$ and $BB_1A_1$ are equal (according to two sides and the angle between them). Specifically, $AB_1 = BA_1$ and $AC = AB_1 + B_1C = BA_1 + A_1C = BC$. Similarly, it is proved that $AC = AB$.

Note that, generally speaking, the criterion for the equality of triangles “by two sides and the angle opposite one of them” is not true (see Fig. 2).

V. N. Dubrovsky

M932. In a square cage on a 1 m side there is an anaconda 10 m long. Baron Munchausen claims that at any moment he can shoot an anaconda in 6 places at once with one shot. Is the baron exaggerating? (The anaconda can be considered an arbitrary broken line of length 10, located inside the square $1 \times 1$.)

⟦folio 37⟧

M933. 13 knights from k different clans (1<k<13) are sitting at a round table. Everyone holds a gold or silver cup, and there are exactly k gold cups. King Arthur ordered the knights to simultaneously pass the cups to their neighbors on the right, then do the same again, etc. Prove that at some points he will find two knights from the same clan holding golden cups.

M934. There are 2n(n≥2) points in space (so no 4 lie in the same plane) and there are n²+1 segments with endpoints at these points. Prove that the drawn segments form a) at least one triangle; b)* at least n triangles.

breaking. It is enough for the Baron to quickly shoot from this point perpendicular to the side. From the figure in the margin it is clear that the anaconda can position itself in a cage in such a way that even Munchausen will not be able to shoot it in 7 places at once.

S. V. Gashkov

◆
Let's argue by contradiction. If the statement of the problem is not true, then at any moment in time exactly one knight in each clan holds a golden cup, since the number of clans is equal to the number of cups. Let's assume that each next transfer of cups occurs in a minute. Then in 13 minutes - the time for a full revolution of the cups around the table - each knight will have to hold each of the golden cups exactly once, that is, for k minutes, and all knights of one clan together will have nk minutes, where n is the number of knights in this clan. Thus, nk=13, which is impossible for 1<k<13, since 13 is a prime number.

The resulting contradiction proves the statement of the problem.

If the total number of knights r was divisible by k: r=kn, then it would be easy to construct an example where at any moment only one knight from each clan has a golden cup: it is enough to trace the knights of each clan at the vertices of a regular n-gon, and k golden cups give k knights sitting in a row (from different clans).

S. V. Gashkov

◆
a) Choose the point from which the most number of segments emerge. Let us denote it by A₁, the ends of the segments emerging from it by B₁, ..., Bₖ, and the remaining points by A₂, ..., A₂n-k. If there are no triangles, then there are no segments between the points B₁, ..., Bₖ, so no more than 2n-k segments come out of each of them. And since from each point Aᵢ, i=1, ..., 2n-k, there are no more than k segments, the total number of segments will not exceed

$$\frac{1}{2}(k(2n-k)+(2n-k)k)=k(2n-k)\leq n^2.$$

The number of these segments is equal to n²+1, so they form at least one triangle.

For n² segments, the statement of the problem, as can be seen from figure, is not true.

b) Let us carry out the proof of induction on n. When n=2 (for 4 points and 5 segments), the statement is verified directly. Let us prove it for 2(n+1) points, considering it true for 2n points.

According to a) the drawn segments form at least one triangle ABC. At least n more triangles are needed. Let us denote the number of segments emerging from the vertices of triangle ABC (not counting its sides) by kₐ, kₑ, k₃, respectively.

⟦folio 38⟧

If $k = k_A + k_B + k_C \leq 3n - 2$, then for some two vertices of the triangle, for example $A$ and $B$, the total number of such segments $k_A + k_B$ is no more than $2n - 2$. Let's discard these points and all the segments coming from them (together with the sides of the triangle $ABC$). We get a set of points connected by at least $(n + 1)^2 + 1 - (2n - 2) - 3 = n^2 + 1$ segments, which, according to the Inductian proposal, form at least $n$ triangles.

If $k \geq 3n - 1$ and $k$ of the segments we are considering form with sides $AB, BC$ and $CA$ triangles, then $t \geq n$. In fact, let among $2n + 2 - 3 = 2n - 1$ points different from $A, B, C$ there be $n_j$ such that $j$ segments go to vertices $A, B, C$ ($j = 0, 1, 2, 3$). Then
$$n_1 + n_2 + n_3 \leq n_0 + n_1 + n_2 + n_3 = 2n - 1,$$
$$n_1 + 2n_2 + 3n_3 = k \geq 3n - 1,$$
follow, $t = n_2 + 3n_3 \geq n_2 + 2n_3 \geq (3n - 1) - (2n - 1) \geq n$.

S. V. Gashkov

**M935. (Nut problem.)** If inside there is a regular $2n$-gon with sides $a$ and center $O$ (arbitrarily place a regular $2n$-gon with sides $a/2$, then it will cover the point $O$. Prove this statement: $a)$ for $n = 2$; $b)$* for $n = 3$; $c)$* for any natural $n$.

**Fig. 1.**

**Fig. 2.**

We will argue by contradiction and immediately in the general case. Let us denote the smaller $2n$-gon by $M_1$, and the larger one by $M_2$. If the polygon $M_1$ does not contain the center $O$ of the polygon $M_2$, then, since it is convex, it has a side $AB$ such that the point $O$ and the polygon itself $M_1$ lie on opposite sides of the line $AB$ (Fig. 1). Let $CD$ be the side opposite to $AB$ of the polygon $M_1$. The distance between parallel lines $AB$ and $CD$ is equal to the radius of the inscribed circle of the polygon $M_2$, therefore line $CD$ lies outside this circle. Let us draw a tangent $MN$ to this circle (see Fig. 1), parallel to $CD$; then, as follows from what has been said,
$$CD \leq C'D' < MN,$$
where $C'D'$ is the segment along which the line $CD$ intersects with $M_2$, and the ends of the segments $C'D'$ and $MN$ lie on two adjacent sides of the polygon $M_2$.

Now it is enough to prove that $MN < a/2$ (then it turns out that $CD < a/2$, which contradicts the conditions). Let the points $M$ and $N$ lie on the sides $M_2$ emerging from the vertex $P$; $Q, R$ and $T$ are the points of tangency of these sides and the segment $MN$ with the inscribed circle $M_2$ (Fig. 2). Then
$$2MN = MT + MN + TN = QM + MN + NR < QP + PR = a,$$
which is what was required.

Note that for $(2n + 1)$-gons a similar statement is not true.

S. V. Gashkov

**F943. A small body falls to the ground at an altitude. Considering the impact of a body on the ground to be absolutely elastic,

⟦folio 39⟧

accelerate the body immediately after it bounces off the ground.

Fig. 1.

Fig. 2.

At the same speed as the body, that is, up. Since the resistance force increases with increasing speed, we will find such a height (according to the condition of the body falls from a huge height) at which the resistance force exerts a modulus of gravity (Fig. 1):

$$mg - F_c = 0, \quad mg + F_c = 0.$$

Starting from this moment, the body will fall with some constant speed $\vec{v}$.

With the same speed according to the model, but in the opposite direction, the body will bounce off the ground immediately after an abcilton elastic impact on it. At this moment, two equally directed and equal in magnitude forces (Fig. 2) act on the body, so its acceleration will be equal to

$$a = \frac{mg + F_c}{m} = \frac{2mg}{m} = 2g \approx 20 \text{ m/c}^2.$$

A. G. Shikhkerimov

F944. On a rigid body moving translationally along a rough horizontal surface, at the moment of time $t_0 = 0$, when the speed of the body is $v_0$, the force $F(t)$ begins to act, directed all the time along the vector $\vec{v}_0$ and returning in time. After time $t$, the speed of the body turns out to be equal to $v_i$, and $v_i = 5 \text{ m/c}$ if $v_0 = 1 \text{ m/c}$, and $v_i = 13 \text{ m/c}$ if $v_0 = 10 \text{ m/c}$. Determine the dependence $v_i = f(v_0)$ for all possible $v_0$.

Starting from the moment of time $t = 0$, two forces act on the body - this force $F(t)$, returning with time, and the friction force, which here can take values ​​from 0 to the maximum resting friction force, equal to the sliding friction force $F_{\tau p} = \mu mg$ (μ is the friction coefficient, $m$ is the body mass). These forces are directed opposite to each other, so it is clear that the nature of the body’s movement will be determined by the relationship between the modules of the forces acting on the body, and above all, at the initial moment. Let's distance the possibility at the beginning of the moment $t = 0$, two forces act on the body - this force $F(t)$, returning with time over a given period of time $t$ does not depend on the speed: $v_i = v_0 + C$ (where $C$ is some constant). The corresponding graph is shown on figure 1. It is easy to see that these tasks do not “fit” into this graph. So, $F(0) < \mu mg$.

Since the force $F(t)$ returns over time, at some point, let’s call it “critical”, it turns out to be equal to the maximum force of static friction: $F(t_{\kappa p}) = \mu mg$. This can happen either before the specified moment in time $t$, or after it (of course, it is possible that this should not happen, but more on that later).

Let $t_{\kappa p} < t$. Then the body first, until moment $t_{\kappa p}$, moves slowly, and then accelerates. But here, too, two cases are possible: at moment $t_{\kappa p}$ the speed of the body is either equal to zero or greater than zero. It is clear that the first case can be realized only at sufficiently low initial speeds. In this case, the speed $v_i$ does not depend on the speed $v_0$ (the body moves slowly, stops and starts moving again, “forgetting” about the initial speed $v_0$): $v_i = A$. Gradually increasing the initial speed, we will arrive at such a value, we will call it “critical”, that when

⟦folio 40⟧

$v_0 > v_{\text{кр}}$ the body will move without stopping. In this case, starting from the moment $t_{\text{кр}}$, the force $F(t) - \mu mg$ will act on the body, does not depend on the speed, therefore $v_t = v_0 + B$. Thus, at $t_{\text{кр}} < t$ the graph of $v_t = f(v_0)$ has the form shown in figure 2.

Let now $t_{\text{кр}} > t$. Carrying out similar calculations, we will arrive at the graph shown in figure 3. Obviously, this graph is also suitable for the last possible case, when the force $F(t)$ is always less than $\mu mg$ (the body will either stop until moment $t$, or will move in acceleration, independent of speed).

So, we have obtained three graphs of the dependence of the final speed of a body on its initial speed. In this case, the points specified in the conditions of the problem ($v_t = 5$ m/s at $v_0 = 1$ m/s and $v_t = 13$ m/s at $v_0 = 10$ m/s) “fit” only on the graph shown in figure 2. Thus,

$$v_t = \begin{cases} A & \text{при } v_0 \leqslant v_{\text{кр}}, \\ B + v_0 & \text{при } v_0 > v_{\text{кр}}. \end{cases}$$

“Stitching together” these two conditions, taking into account specific data, we finally obtain (Fig. 4):

$$v_t = \begin{cases} 5 \text{ м/c} & \text{при } v_0 \leqslant 2 \text{ м/c}, \\ 3 \text{ м/c} + v_0 & \text{при } v_0 > 2 \text{ м/c}. \end{cases}$$

R. L. Mkrtchyan, O. M. Khudaverdyan

◆ The efficiency of a cyclic process is defined as $\eta = A / Q$, where $A$ is the work done by the system per cycle, $Q$ is the amount of heat received by the system at the corresponding screw and during the second cycle. Let's find $Q_1$ and $Q_2$.

Let the gas temperature at point 1 be $T_1$. Using the equation of state of an ideal gas, it is easy to show that

$$T_2 = T_5 = 2T_1, T_3 = T_6 = 6T_1, T_4 = 3T_1, T_7 = 9T_1.$$

It is obvious that in the process 1-2-3-4-1 the gas received heat $Q_1$ in sections 1-2 and 2-3, and $Q_1 = A_1 + \Delta U_1$, where $A_1 = 4p_0V_0 = 4vRT_1$ is the work done by the gas in these sections, $\Delta U_1 = \frac{3}{2}vR(T_3 - T_1) = \frac{15}{2}vRT_1$ is the change in its internal energy. So

$$Q_1 = 4vRT_1 + \frac{15}{2}vRT_1 = \frac{23}{2}vRT_1.$$

In the 5-6-7-4-5 process, the gas received heat $Q_2$ in sections 5-6 and 6-7, and

$$Q_2 = A_2 + \Delta U_2 = 3p_0V_0 + \frac{3}{2}vR(T_7 - T_5) \frac{27}{2}vRT_1.$$

⟦folio 42⟧

Expressing the distances $r_1$ and $r_2$ in terms of $l$ from the triangle $ABC$ using the sine theorem, we arrive at the equation
$(\cos \beta - \cos \gamma)(\cos^2 \beta + \cos^2 \gamma + \cos \beta \cos \gamma - 1) = 0$.

If we equate the first factor to zero, we get the trivial case: $\beta = \gamma$ (both angles are acute*)), that is, the point $C$ belongs to the plane $\Pi$ itself. This case does not interest us.

Let us equate the second som factor to zero:
$$\cos^2 \beta + \cos^2 \gamma + \cos \beta \cos \gamma - 1 = 0.$$ (1)

There are two unknowns in this equation, so in principle there can be an infinite number of solutions. However, here the previously stated messages 1)-3) will be useful to us. Let us consider the lines of force emerging from the left charge and falling inside the cone with an angle $\alpha$ between the generatrix and the axis of the cone (lines $AB$). It is clear that the conditional number $N$ of these lines is proportional to the value of the solid angle $\Omega = 2\pi(1 - \cos \alpha)$ (this formula is easy to derive on your own):

$$N = K \cdot \Omega = K \cdot 2\pi(1 - \cos \alpha).$$

On the other hand, since the field lines of the resulting field do not intersect, the same number of field lines can be found if we consider the field lines created by each of the two charges separately, intersecting a circle with a diameter of $CC'$ (Fig. 3):

$$N = K \cdot 2\pi(1 - \cos \beta) - K \cdot 2\pi(1 - \cos \gamma)$$

(the difference, and not the sum, is taken here because the field lines of the left charge intersect the selected circle from left to right, and the field lines of the right charge - vice versa). So we get

$$K \cdot 2\pi(1 - \cos \alpha) = K \cdot 2\pi(1 - \cos \beta) - K \cdot 2\pi(1 - \cos \gamma),$$

or

$$1 - \cos \alpha = \cos \gamma - \cos \beta.$$ (2)

Let's combine equations (1) and (2) in the system:

$$\begin{cases}
1 - \cos \alpha = \cos \gamma - \cos \beta, \\
\cos^2 \beta + \cos^2 \gamma + \cos \beta \cos \gamma = 1.
\end{cases}$$

This system, taking into account, again, that the angles $\beta$ and $\gamma$ are acute, has a unique solution:

$$\cos \beta = \frac{\cos \alpha - 1 + \sqrt{(3 - \cos \alpha)(1 + \cos \alpha)}}{2},$$

$$\cos \gamma = \frac{1 - \cos \alpha + \sqrt{(3 - \cos \alpha)(1 + \cos \alpha)}}{2}.$$

Let us now find the required distance $x$ (see Fig. 2):

$$x = \frac{l}{2} - r_1 \cos \beta = \frac{l}{2} \left(1 - 2 \frac{\sin \gamma \cos \beta}{\sin (\beta + \gamma)}\right),$$

where the angles $\beta$ and $\gamma$ can be expressed from the previous equalities ($\beta = \arccos \beta$ and $\gamma = \arccos \gamma$). It is not difficult to “check” the received answer for two evaluated special cases: a) if $\alpha = 90^\circ$, then $x = l/2$, that is, this line of force immediately “turns” to the left; b) if $\alpha = 0^\circ$, then $x = 0$, that is, the field line first goes along the segment $l$, to the point $O$, where it suffers a “break” (at this point there is no field).

⟦folio 43⟧

stuvet), and then goes along a vertical straight line (in the Π plane).

It remains for us to find out which straight line the given field line will asymptotically approach at a large distance from the charges.*) In other words, we need to find the angle δ, and in the final case, δ' (see Fig. 2). Messages 1), 2) and 4) will help with this.

On the one hand, all lines of force that do not extend beyond the cone with an angle δ between the generatrix and the axis come from the left charge within the teleangle equal to 2π(1−cos(π−α))=2π(1+cos α). So their number

N=K·2π(1+cos α).

On the other hand, we get the same number of lines if we consider the system as one exact charge 2q located at point O:

N=2K·2π(1−cos δ).

Thus, we get

K·2π(1+cos α)=2K·2π(1−cos δ),

where

cos δ=1−cos α/2, δ=arccos(1−cos α)/2.

Angle δ' complements angle δ to 90°, so

δ'=arcsin(1−cos α)/2.

For example: if α=90°, then δ'=30°, if α=0°, then δ'=0°, if α=180°, then δ'=90°, that is, these are trivial partial cases of good “correspondence” with intuition and common sense.

V. A. Nakhshin

F947. The shell of the space station is a measured sphere, the temperature of which, due to the operation of the equipment inside the station, is T = 500 K. What will be the temperature of the shell if the station is surrounded by a thin black spherical screen of almost the same radius as the shell? The amount of heat emitted per unit surface is proportional to the fourth power of absolute temperature.

◆

The total amount of heat Q emitted into space per unit time depends only on the energy release during operation of the station equipment, therefore the presence of a screen will not change it. But now the thermal surface of the screen is emitting heat; therefore, the screen temperature must be equal to the initial temperature of the station T=500 K.

The screen, however, radiates not only to the load, but also inside, and this is the same amount of heat Q. This radiation hits the shell of the station and is absorbed by it. Thus, the amount of heat supplied to the station shell per unit time is the sum of the heat generated by the devices and radiated from the inner surface of the screen, that is, it is equal to 2Q. Exactly the same amount of heat must be radiated; Means,

$$\frac{2Q}{Q} = \frac{T^4}{T^4},$$

from where we find the desired temperature of the station shell:

$$T_x = \sqrt[4]{2} T \approx 600 \text{ K}.$$

A. I. Buadin
