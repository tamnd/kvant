---
id: 1985-10-resheniya-zadach-m926-m930-f938-f942-45d16cd9
issue: kvant_1985_10
year: 1985
number: "10"
title: Solutions to problems M926—M930; F938—F942
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 36
page_last: 42
page_labels: 34, 35, 36, 38, 39, 40
tag: J2MN
lang: en
source: kvant_digital
extraction: vision
content_sha256: 4f9b43cbb50345d26ce60c1df6753e54c4d3be806c23d3062914935f97741def
prompt_sha256: draft-1
translated_from: content/ru/1985/10/articles/15_resheniya-zadach-m926-m930-f938-f942-45d16cd9.md
source_content_sha256: d745215f88c949040a89a51b98e6c2e6bda145266b9f12eb9d23465960cfa2c1
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 34⟧

in sequence? How much water must be used when one heater of power $P=100$ Wt is working? The temperature of the water source is $t_1=10^\circ\text{C}$, the aquarium water temperature is $27^\circ\text{C}$, its water mixes very rapidly.

A. R. Zilberman

P962. Point sources, located on the principal optical axis of a lens, constitute a uniformly lighted string (passing through the lens' focus). Find the rule $E(x)$ expressing the luminosity at points of the optical axis on the opposite side of the lens, when the distance $x$ from the lens is large ($x \gg F$, where $F$ is the lens' focal distance).

M. A. Vorontsov, V. E. Kunitsin

Problem solutions

M926 — M930; F938 — F942

It is convenient to represent the problem condition geometrically. Let us mark the points $A(x; y)$ and $B(u; v)$ on the coordinate plane $Oxy$. Angle $AOB$ is right because $OA \cdot OB = xu + yv = 0$. In addition, $OA^2 = x^2 + y^2 = 1$ and $OB^2 = 1$, so point $B$ is obtained from point $A$ by rotating around $O$ by $\pm 90^\circ$ (see figure) and $x = \cos \alpha$, $y = \sin \alpha$, where $\alpha$ is the angle between the vector $OA$ and axis $Ox$, which means $u = \cos (\alpha \pm 90^\circ) = \pm \sin \alpha = \mp y$, $v = \sin (\alpha \pm 90^\circ) = \pm \cos \alpha = \pm x$. Hence,

$$x^2 + u^2 = x^2 + y^2 = 1,$$
$$y^2 + v^2 = y^2 + x^2 = 1,$$
$$xy + uv = xy - xy = 0.$$

Let us present one more, purely algebraic, solution. Same action

$$(x^2 + y^2 - 1)^2 + (u^2 + v^2 - 1)^2 + 2(xu + yv)^2 = x^4 + y^4 + u^4 + v^4 + 2 - 2(x^2 + y^2 + u^2 + v^2) + 2(x^2y^2 + u^2v^2 + x^2u^2 + y^2v^2) + 4xuyv = (x^2 + u^2 - 1)^2 + (y^2 + v^2 - 1)^2 + 2(xy + uv)^2$$

the left side, by condition, is equal to zero; Consequently, the right side is also equal to zero, that is, the three equalities being proved are true.

Try to generalize our problem to the three-dimensional case - prove that if three vectors of length 1 in space with coordinates $(x_1; x_2; x_3)$, $(y_1; y_2; y_3)$, $(z_1; z_2; z_3)$ are pairwise perpendicular, then the vectors $(x_1; y_1; z_1)$, $(x_2; y_2; z_2)$ and $(x_3; y_3; z_3)$ also have length 1 and are pairwise perpendicular.

S. V. Duzhin

a) Let us prove that through a finite number of operations of “type a” - replacing the intersecting segments $AC$ and $BD$ with non-intersecting segments $AB$ and $CD$ - we will arrive at a configuration in which there will no longer be intersecting segments.

Let us consider the sum $s$ of the lengths of the configuration segments. For each operation of type $a$ it decreases:

$$AB + CD < AC + BD$$

(for the trigons $APB$ and $CPD$, where $P$ is the intersection point of $AC$ and $BD$ - Fig. 1, the inequalities $AB < AP + PB$ and $CD < CP + PD$ are satisfied; adding them, we obtain (*)).

On the other hand, the quantities $s$ can take only a finite number of values, because

⟦folio 35⟧

since there are only a finite number of different configurations of segments with vertices at given points. Therefore, in a finite number of steps we will arrive at a configuration with which it is no longer possible to perform an operation that reduces s.

This solution gives a very deep upper bound for the maximum number of $T_n$ operations that can be performed on a configuration at $n$ points - we can only say that it is less than the number of all configurations, that is, $2^{n(n-1)^2}$ ($n(n-1)/2$ is the number of different segments with endpoints at these $n$ points).

Let us present an idea for another solution that gives a significantly better estimate. Let us consider an arbitrary partition $f$ of these points into two non-empty sets, each of which lies entirely on one side of some line $l$. There are infinitely many such straight lines for a given partition, finitely, but one of them can always be obtained by rotating clockwise the straight line connecting two rolled points $A$ and $B$ at a very small angle around the middle of the segment $AB$ (Fig. 2); Let's denote this line $l_f$. The number of straight lines $l_f$, and hence the number of distances of “convex” partitions does not exceed the number of pairs of points $n(n-1)/2$.

Let us call the balance of a configuration the total number $b$ of intersections of its segments with all lines $l_f$; it is clear that $0 \leq b \leq (n(n-1)/2)^2$. In an operation of type $a$, the number of intersections of any line $l_f$ with segments of the configuration does not increase, and for at least one line it decreases by 2. Therefore, $T_n \leq n^2(n-1)^2/8$. It would be interesting to obtain an even more precise estimate for $T_n$.

6) Let us give an example showing that for an operation “type $\delta$”—replacement of intersecting segments $AC$ and $BD$ with $AB$ and $BC$ having a common end—the process can “go in cycles” and thus continues indefinitely. Let's place 18 points at the vertices of a regular 18-gon and denote by $D(k,l)$ a configuration of 36 segments, in which each of the 18 points is connected to the $k$th and $l$th from it in a row.

To complete the path $D(4,8) \rightarrow D(5,9) \rightarrow D(6,7) \rightarrow D(4,8)$ (Fig. 3) in 54 operations, it is enough to perform each of the operations depicted in figure 4 18 times (rotating the picture by $20^\circ$ each time).

Apparently, there are also examples with a significantly smaller number of points $n$ and cycle length $T$ than $n=18$ and $T=54$.

N. B. Vasiliev, V. E. Kolosov

⟦folio 36⟧

M928. In the cinema $N+1$ place. At first, $N$ people with tickets indicating a seat (including Igor) sat down in random $N$ seats, not eating their tickets. The $(N+1)$ spectator who came last wants to take his place; if it is occupied - on the one hand there, he does the same and so on until the place needed by consciousness is free. What is the probability that Igor will have to change seats? (In other words, what proportion of the environments of all possible placements of spectators are invisible to Igor?)

Answer: 1/2. Let us prove that there are as many beneficial placements for Igor as there are unprofitable ones, and a mutual correspondence has been established between the two.

Suppose that with some initial placement of $P$ $N$ spectators in $N+1$ seats, Igor moved to a free seat. then you get a new placement $P'$. Thus, all possible placements are divided into pairs $(P, P')$ and it is enough to show that in each pair one placement is beneficial for Igor (it is not worth it), and the other is unprofitable.

If $P$ is an advantageous placement, then the last spectator participating in transfers (that is, having a ticket for an empty seat) at placement $P'$ is worth Igor. This means that $P'$ is an invisible placement. If $P$ is a non-visual placement, then the spectator who is worth Igor will have no one worth it at placement $P'$, so the transfers will end there, that is, $P'$ is a placement beneficial for Igor.

I. V. Alekseev-Astafev

M929. Natural numbers $a, b, c, d$, e satisfy the condition $a^4 + b^4 + c^4 + d^4 = e^4$. Prove that at least $a$ three of them are even, $b$ three are divisible by 5, $b$ two are divisible by 10.

Fermat's Little Theorem
For any integer $n$ and prime $p$, the number $n^p - n$ is divisible by $p$.

ANSWER: 1/2. Let us prove that there are as many beneficial placements for Igor as there are unprofitable ones, and a mutual correspondence has been established between the two.

Suppose that with some initial placement of $P$ $N$ spectators in $N+1$ seats, Igor moved to a free seat. then you get a new placement $P'$. Thus, all possible placements are divided into pairs $(P, P')$ and it is enough to show that in each pair one placement is beneficial for Igor (it is not worth it), and the other is unprofitable.

If $P$ is an advantageous placement, then the last spectator participating in transfers (that is, having a ticket for an empty seat), at placement $P'$ there will be no one standing, so transfers will end there, that is, $P'$ is an advantageous placement for Igor.

I. V. Alekseev-Astafev

a) Note that the number $n^4$ when $n$ is even is divisible by 16, and when $n$ is odd it gives a remainder of 1 when divided by 16. (Indeed, when $n=2k+1$
$n^4-1=(n-1)(n+1)(n^2+1)=$
$=8k(k+1)(2k^2+2k+1)$,
and $k(k+1)$ is always divisible by 2.)
Therefore, the remainder of $a^4+b^4+c^4+d^4+e^4$ divided by 16 is equal to the number of odd numbers among $a, b, c, d$. And since it must coincide with a similar remainder for $e^4$, we find that the condition of the problem can only be satisfied if all the numbers are even, or if the number $e$ and exactly one of the remaining numbers are odd. This also proves statement a).

6) For the remainder when dividing the number $n^4$ by 5, a statement similar to that proved in point a is true: this remainder is equal to 0 or 1, depending on whether $n$ is divisible by 5 or not. (Indeed, if $n=5k±1$, then $n^2-1=5k(5k±2)$ is divisible by 5; if $n=5k±2$, then $n^2+1=5k(5k±4)+5$ is divisible by 5. Therefore, $n^4-1=(n^2-1)(n^2+1)$ is always divisible by 5 if $n$ is not a multiple of 5. This statement is a special case of the so-called Fermat’s little theorem, the formulation of which is given in the margin.)

Now, in exactly the same way as in the solution to part a), proves that either all numbers $a, b, c, d, e$ are divisible by 5, or the number $e$ and exactly one of the other numbers are not divisible by 5, which implies 6).
c) Consider three cases.

1) The number $e$ is even. From the solution to problem a) it follows that all other numbers are also even, and from the solution to problem 6) it follows that at least three of them are divisible by 5, and therefore by 10.

2) The number $e$ is divisible by 5. This case is treated in the same way as the previous one: all

⟦folio 38⟧

for $f_0 = e_1 - e_0$ and $f_1 = e_2 - e_0$ from the set $F$, the difference $f_1 - f_0 = e_2 - e_1$ of which must also belong to the set $F$, which contradicts our assumption.

The resulting contradiction proves the statement of the problem.

Arguing in the same way as in the above solution, it is not difficult to show that the statement of the problem is satisfied for any partition of the first $N$ numbers $1, 2, ..., N$ into $k$ sets for

$$N = N_k = k! \left( 1 + \frac{1}{1!} + \frac{1}{2!} + \dots + \frac{1}{k!} \right)$$

($n! = 1 \cdot 2 \cdot \dots \cdot n$). The values ​​of $N_k$ for $k = 1, ..., 6$ are calculated in the margin. It is obvious that for any $N \geqslant N_k$ the statement of the problem will be true for the $k$ set; in our case $1985 > 1957 = N_6$. Note that the sum in parentheses on the right side of (3) at $k \to \infty$ will very quickly be reduced to the base of natural logarithms - the number $e = 2,718$... It can check that $N_k = [k! e]$, but this beautiful formula, unfortunately, does not give the smallest suitable value $N$ for a given $k$; for example, for $k = 3$ the smallest value is 14, not 16. There may be an interesting, but apparently difficult, problem of estimating this smallest value for sizu. Is it true, for example, that it is always greater than $ck!$, where $c$ is some constant? The best known estimate so far remains $(3^k - 1)/2$ by A. Khodlev (see decision problem M540, «Kvant» No. 12, 1979, p. 23).

A. D. Valtsev, V. N. Dubrovsky

F938. The pilot of a spacecraft moving at a speed of $v = 1$ km/s, then at the rate of an astrofood with a diameter of $d = 7$ km, when a distance of $l = 8,5$ km remained to its surface. The astronaut immediately turned on the emergency engines, which in a short time imparted to the ship an additional speed of $\Delta v = 300$ m/s, the direction of which was set by the astronaut. Is it possible for a ship to avoid a collision?

♦

To avoid a collision, the astronaut must also change the speed of the ship so that the angle between the original direction “toward the asterid” and the new course is greater than the angle $\alpha_0$ determined by the conditions (Fig. 1)

$$\sin \alpha_0 = \frac{d/2}{l + d/2} = \frac{d}{2l + d} \approx 0,292.$$

The maximum deviation from the initial initial course when imparting additional speed $\Delta v$ to the ship is ensured in the case when the vector $\vec{\Delta v}$ turns out to be perpendicular to the vector $\vec{v}_1 = \vec{v} + \vec{\Delta v}$ (Fig. 2), that is, when

Fig. 1.

Fig. 2.

$$\sin \alpha = \frac{\Delta v}{v} = 0,3.$$

This means that when the emergency engines are turned on, the astronaut can change the ship’s course by an angle of $\alpha > \alpha_0$, and a collision with the asterid will not occur.

A. V. Andrianov

F939. The bottom of the vessel is inclined at an angle $\alpha = 45^\circ$ to the horizon. The bottom has a hemispherical convexity with radius $R$

♦

Consider a body shaped like half a ball of radius $R$. Let us assume that it is located Q and is oriented in the direction

⟦folio 39⟧

(figure 1). The height of this amount of liquid above the convexity is equal to N. What vertical force is exerted by the liquid on the convex section of the bottom? The density of the liquid is q.

Fig. 1.

Fig. 2.

Stran's dots are the same as the bulge in the bottom of a given vessel.

According to Archimedes' law, this body is acted upon by a buoyancy force $\vec{F}$, directed vertically upward and equal in modulo

$$F = \varrho g V = \varrho g \frac{1}{2} \cdot \frac{4}{3} \pi R^3 = \frac{2}{3} \varrho g \pi R^3.$$

On the other hand, force $\vec{F}$ can be represented as the resultant of two pressure forces from the liquid: force $\vec{F}_1$, acting on the “base” of half the ball, and force $\vec{F}_2$, acting on its side surface (two possible comparisons are shown in figure 2):

$$\vec{F} = \vec{F}_1 + \vec{F}_2.$$

We are interested in the projection of force $\vec{F}_2$ onto the vertical axis (we denote it by X and direct it upward):

$$F_{2x} = F - F_{1x} \quad (\text{для одного сличая})$$

or

$$F_{2x} = F_{1x} - F \quad (\text{для другого сличая}).$$

To find the modulus and projection of force $\vec{F}_1$, we note that pressure increases linearly with depth and therefore we can use its average value:

$$F_1 = p_{cp} S = \varrho g (H + R) \pi R^2,$$
$$F_{1x} = \varrho g (H + R) \pi R^2 \cos \alpha.$$

Then for the exception we get

$$F_{2x} = F - F_{1x} = \frac{2}{3} \varrho g \pi R^3 - \varrho g (H + R) \pi R^2 \cos \alpha$$

or

$$F_{2x} = F_{1x} - F = \varrho g (H + R) \pi R^2 \cos \alpha - \frac{2}{3} \varrho g \pi R^3.$$

At angle $\alpha = 45^\circ$ the first comparison turns out to be impossible: $2/3 < \cos \alpha = \sqrt{2}/2$, therefore $F_{2x} < 0$, which cannot be in this situation. Thus, the second comparison remains:

$$F_{2x} = \varrho g \pi R^2 \left( (H + R) \cos \alpha - \frac{2}{3} R \right).$$

L. G. Markovich

F940. Why is clay mortar used in brick kilns for bending bricks, and not, for example, cement (although it is harder)?

Large and uneven temperature differences in time and volume are possible in the oven. If bricks and mortar are made of different materials (that is, from materials with different coefficients of thermal expansion), then when the temperature changes (cooling, heating), they will change in volume differently (expand, shrink). This will lead to the emergence of large internal stresses at the brick-mortar contact points; As a result, the oven will crack.

V. A. Ilyin

F941. In a magnetic field of direct rectilinear current we find a square frame ABCD (see.

⟦folio 40⟧

figure). The frame is moved to a new position, shown in figure by the dotted line. This can be done in two ways: by uniform rotation around the CD side or by uniform parallel translation along AD. Which method will generate more heat if the time it takes to move the frame to a new position is generally the same?

F942. A plane light wave falls normally on the screen E. How will the illumination of the screen at point M change (see figure) if a semi-insonant opaque plate P is placed on the path of the wave, parallel to the screen?

The wave surface of a plane wave is a plane perpendicular to the direction of wave propagation. Light falls normally on plate P, so the plane in which the plate is placed is one of the wave surfaces, and it can be considered as a set of identical secondary sources oscillating in phase. The resulting vibration at point M on the screen is a superposition of vibrations coming from these sources.

When introducing the plate, half of the secondary sources will be closed. Therefore, the amplitude of the resulting oscillation at point M will decrease by 2 times. The illumination of the screen at point M is proportional to the square of this amplitude. Consequently, when the plate is introduced, the illumination will decrease by 4 times.

D. A. Kuptsov

It was as if the earth was wearing away and nowhere was visible solid soil on which to build. It has always seemed convenient to me that this oscillating and full of contradictions basis was enough to allow Bohr - a man with great intuition and a subtle sense - to find the most important laws of spectral lines and electron shells of atoms, including their significance for chemistry. I have achieved this quality even now. This is called musicality in the field of thought.

A. Einstein

In the entire world of science in our history there was no person with such influence on the natural as Bohr. Of all the theoretical theories, Bohr's was the most significant.

P. Kapitsa

I came to the USSR to meet old friends and find new ones, because the content of scientists from different countries helps not only the development of science, but also the cause of peace.

N. Bor

I still learn when I look at a nuclear reactor.

N. Bor

If I can do anything very skillfully, then perhaps think... N. Bohr

Quantum theory does not bleibt me to its problems. Now the primary problem is to find a way to prevent a nuclear wave!

N. Bor
