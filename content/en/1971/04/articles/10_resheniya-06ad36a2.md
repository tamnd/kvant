---
id: 1971-4-resheniya-06ad36a2
issue: kvant_1971_4
year: 1971
number: "4"
title: Solutions to problems M28—M30; F41, F42, F44—F47
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 37
page_last: 44
page_labels: 35-42
tag: SHZH
lang: en
source: kvant_digital
extraction: vision
content_sha256: 73d0fe24423bd5aaa8d98a6a541e586d985fabb5232c54a827621dad20ac6638
prompt_sha256: draft-1
translated_from: content/ru/1971/04/articles/10_resheniya-06ad36a2.md
source_content_sha256: 0e1c17b796bb8be52d46a94c5f226f916906f17a0db41766594bff265bc2448d
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 35⟧

SOLUTIONS

In this issue we publish the solution to problems M28–M30

M28

(Continuation of the solution, see “Quant” No. 3, p. 33). Let us recall that through $f_1(n)$ we denote the smallest integer greater than or equal to $\log_2 n$ (it is equal to the smallest number of checks, after which it is possible to check, for which one can choose one radioactive ball from $n$), through $f_2(n)$ - the smallest number that $f_2(11) \geq 7$. Below we will very briefly prove that $f_2(6) \geq 5$;

Fig 1.

choose one radioactive ball from $n$), through $f_2(n)$ - the smallest number that $f_2(11) \geq 7$. Below we will very briefly prove that $f_2(6) \geq 5$;

⟦folio 36⟧

$f_2(8) \geq 6; \quad f_2(11) \geq 7; \quad f_2(10) \leq 6;$
$f_2(15) \leq 7; \quad f_2(21) \leq 8.$

Readers who wish to verify that all the numbers in the bottom row of the table on page 35 are correct will have to prove, in addition, that $f_2(16) \geq 8;$
$f_2(22) \leq 8; \quad f_2(23) \geq 9; \quad f_2(25) \leq 9$ (indeed, it is clear that the function $f_2$ is non-decreasing, that is, $m > n,$ then $f_2(m) \geq f_2(n)$, therefore it is enough to correctly indicate those values ​​$n,$ for which $f_2(n+1)$ is strictly greater than $f_2(n).$

Before proving the promised inequalities, note that determining the exact value of $f_2(n)$ for any $n$ in this problem; as in many other tasks, it is not very interesting. The point is that the appropriate method for selecting balls is apparently very complicated. On the other hand, it is easy to indicate very simple algorithms for selecting balls, requiring only a slightly larger number of checks than $f_2(n),$. For example, if they first produce one radioactive ball, then grow it and choose another from the remaining ones, then this will take no more than $f_1(n)+f_1(n-1)$ checks, and, as is not difficult to show, the difference $f_1(n)+f_1(n-1) - f_1(C_n^2)$ is always no more than 2, therefore, the difference $f_1(n)+f_1(n-1)-f_2(n)$ is also no more than 2. In practical problems like this, if the number of checks $k$ is not too small, one or two extra checks will most likely play a role special role, if only the verification method was simpler (say, for $n=15$ we can no longer reduce a diagram similar to figure 1 on the magazine page, and it becomes difficult to understand the description of the verification method).

Below we use the following notation: the “-” sign means that there are no radioactive balls in the pile being checked, and the “+” sign means that there are some.

In 4 checks it is impossible to select 2 balls out of 6

Let the first group of 6-q balls be checked, where $q=2, 3, 4$ or 5. Then the outcome “-” corresponds to $C_q^2$ options (both radioactive balls among $q$ others), the outcome “+” corresponds to $(C_6^2-C_q^2)$ options. However, of these numbers, $2^3=8$ is greater.

In 5 checks it is impossible to select 2 balls out of 8

If
$C_q^2 < 2^4 = 16$ and $C_8^2 - C_q^2 < 16,$ then $q$ can only be equal to 6. If the outcome is “-”, then it remains to select 2 balls out of 6, which is impossible in 4 checks.

In 6 checks it is impossible to select 2 balls out of 11

If $C_q^2 < 2^5 = 32$ and $C_{11}^2 - C_q^2 < 32,$ then $q=8,$ but $f_2(8) \geq 6$.

For 6 checks you can select 2 balls out of 10

The first check is a pile of 4 balls {1-4}. “-” for 5 checks of 2 balls out of 6 {5-10}. “+” check {4-6}. “+-” for 4 checks of 2 balls out of 7 {1-3, 7-10}, if it is known that {1-3} give “+” (see left half Fig. 1). “++” check {5, 6}. “++-” for 3 checks 1 ball from {1-3, 7-10}. “+++” for 1 check 1 ball from {5, 6} and for 2-1 from {1-4}.

For 7 checks you can select 2 balls out of 15

First check {1-5}. “+” check {5-9}. “+-” for 5 checks 2 balls out of 10 {1-4, 10-15}, among which {1-4} give “+” (see 10 balls, “+”). “++” check {5}. “++-” for 4 checks 1 of {1—4, 6—15}. “++-” for 2 checks 1 from {1-4} and for 2 checks 1 from {6-9}.

After 8 checks you can select 2 balls out of 21

First check {1-6}. In addition to those indicated on figure and very important checks, “+-” is also indicated for 6 checks 2 out of 15 {1-5, 12-21}, among which {1-5} give “+” (see 15 balls, “+”). “++-” for 2 checks 1 from {1-4} and for 2 checks 1 from {8-11}.

⟦folio 37⟧

Fig. 2.

M29

n identical coins lie on the table, forming a closed chain (see Fig. 2). How many revolutions will a coin of the same size make before it is crimped once around the outside of the entire chain, as shown in figure?

How would the answer change if coin $M$ had a radius $k$ times different from the radius of each coin in the chain?

Taking the radius of the coins that make up the chain as one. From figure 3 it is clear that during the time that a coin of radius $k$ rolls along the arc $\alpha$ of a stationary circle of radius 1, it will rotate through an angle $\alpha (1+1/k)$: at this point figure the radii $MA$ and $M'A''$ are parallel, $\angle A''M'B = \angle AOB = \alpha$

Fig. 3.

and, since the arcs $\widehat{A'B}$ and $\widehat{AB}$ are equal in length, $\angle BMA' = \alpha/k$, therefore the entire angle $\angle A''MA'$ at which to turn the coin $M$ is equal to $\alpha + \alpha/k$ (in particular, at $k=1$ this angle is $2\alpha$).

Now let's find the sum of arcs consisting of points of fixed coins that the coin $M$ touched while rolling along the chain. Let $O_1, O_2, \ldots, O_n$ be the centers of the coins in the chain. The sum of the arcs lying inside the polygon $O_1O_2 \ldots O_n$ is equal to the sum of its internal angles, that is, $\pi (n-2)$. The sum of the arcs lying outside the polygon is therefore equal to $2\pi n - \pi (n-2) = \pi (n+2)$. You also need to subtract from it

Fig. 4, a.

Fig. 4, b.

⟦folio 38⟧

Fig. 5.
the sum of arcs lying in the depressions between two adjacent coins in which $M$ does not fall. In each of the $n$ recesses, the sum of two such arcs is equal to $2\pi/3$ for $k=1$ (Fig. 4a) and $2\arccos \frac{1}{k+1}$ in the general case (Fig. 4, 6). So, the sum of the arcs along which the coin $M$ will roll is equal to $\pi(n+2)-2\pi n/3$ (in the general case $\pi(n+2)-2n\arccos \frac{1}{k+1}$). To find out the required number of revolutions, you need to multiply this value by 2 (in general, by $1+1/k$) and divide by 2π.

Answer. $\left(\frac{n}{3} + 2\right)$
revolution at $k=1$;
$\frac{k+1}{2k}\left(n - \frac{2}{\pi}n\arccos \frac{1}{k+1} + 2\right)$
turnover in the general case ($n \geqslant 3$).

Fig. 6.

In this solution we took advantage (by counting the "losses" in the indentations between coins) that the $M$ coin is rolled over all $n$ coins in a row, without exception. As a rule, reader A. Virovyansky from Gorky, who sent us a solution, noted that this condition is necessary for the problem to have a definite answer. For a chain with “narrow gaps” (see Fig. 5), of course, it is impossible to find out how much the coin $M$ will turn just by the number $n$. A sufficient but not necessary condition for the problem to be solvable is the following: multilevel $O_1$, $O_2...O_n$ vipucles.

Think about how to get the answer if, together with a closed chain, there is simply one coin, two coins touching each other, and generally an open chain of $n$ coin $O_1,...,O_n$, in which $O_k$ touches $O_{k+1}$, arranged so that $M$ can roll back and forth over all the coins in this order:

$O_1$, $O_2,...,O_{n-1}$, $O_n$, $O_{n-1},...,O_1$ (Fig. 6) (Indication: In the formulas written above, it is enough to close $n$ to $2n-2$.).

M30

Prove that $N$ points in a plane can always be covered by several non-intersecting circles whose sum of diameters is less than $N$ and the distance between any two of which is greater than 1. (Under consideration between two search circles is the distance between their closest points.)

We will need the following obvious lemma.

If two circles of diameters $a'_1$ and $a'_2$ intersect (have a common point), then they can be folded into one circle of diameter no more than $a'_1+a'_2$ (Fig. 7, a, 6).

Let's construct a circle with a center at each of the given $N$ points, having a radius $a$ (and slightly larger than $1/2$; more precisely, the value $a$ will be chosen below). If among these circles they turn out to be intersecting, then, using my lem, we replace any two intersecting circles (no matter which ones) with one circle covering them. If among the obtained circles there are still intersecting ones, we will again use lemmy, etc. In general, let there be some system of circles that: 1) cover all given points together with circles of radius $a$ with centers at these points and 2) have a sum of diameters no more than $N \cdot 2a$. Then if among them there are intersecting ones, then we can

⟦folio 39⟧

Let us use the lemma and construct a new system of fewer circles that satisfies the same conditions 1), 2), and so on until we obtain a system of $k$ circles, no two of which intersect.

Let us now reduce the radius of each of these $k$ circles by amounts $b$, leaving their centers in place ($b$ is greater than $1/2$ and less than $a$; the exact value of $b$ is indicated below). Then the resulting $k$ circles:

1) contain all point data,
2) have a sum of diameters no more than $N \cdot 2a - k \cdot 2b \leq 2Na - 2b$,
3) are separated from each other by no less than $2b$.

It is clear that if we choose $a$ and $b$ so that the inequalities $b < a$; $2Na - 2b < N$, $2b > 1$, then all the requirements of the task will be satisfied. It was enough, for example, to take $a = \frac{1}{2} + \frac{1}{2N}$ and $b = \frac{1}{2} + \frac{1}{4N}$ from the very beginning.

Of course, such $a$ and $b$ were needed only because the conditions required satisfying strict inequalities: the sum of the diameters is less than $N$, the distance between the circles is greater than 1. If we took a simple $a = b = 1/2$, then it would be proven that our $N$ points can be covered (for some $k$) by circles so that the distance between there were at least 1 circles, and the sum of their diameters was no more than $N - k$. Note that since this statement can be proven for any unified dimension, then (by choosing this united one a little less) from it we can

In this issue we publish the solution problem F41—F47 *)

F41

How many times less is the security on a moonlit night at half a beam than on a sunny day? The height of the Moon and the Sun above the horizon is the same. Assume that the illuminated hemisphere of the Moon uniformly scatters light into space.

The radius of the Moon is taken to be 2000 km, and the distance from the Moon to the Sun is 400,000 km.

Since the distances from the Sun to the Earth and the Moon are large compared to the diameter of the Sun, then in calculations we can assume that the Sun is an accurate source of light, uniformly emitting light energy throughout space. Let us assume that the luminous intensity of this source, that is, the energy emitted by the Sun into a unit solid angle in 1 second, is equal to $I$. Then the illumination of the Earth's surface on a bright sunny day will be equal to $E_c = \frac{1}{L^2}$, where $L$ is the distance from the Sun to the Earth.

The Moon illuminates the Earth with reflected sunlight. Since the distance from the Sun to the Moon can be taken equal to the distance from the Sun

*) Solution problem F43 will be published in «Kvant» No. 5

⟦folio 40⟧

to the Earth, then the illumination of the lunar surface at half moon is also equal to $\frac{I}{L^2}$. Light energy reaches the entire surface of the Moon

$$W = \frac{I}{L^2} \pi r^2.$$

Since this energy then dissipates evenly in all directions along the “hemisphere”, energy is emitted into a unit solid angle

$$I_\pi = \frac{I \pi r^2}{L^2 \cdot 2\pi}$$

(full solid angle is 4 π, half is 2π). Now it is easy to find the illumination of the Earth's surface during the full moon. Considering the Moon to be an exact source with luminous intensity $I_\pi$, we obtain

$$E_\pi = \frac{I r^2}{2 L^2 l^2},$$

where $l$ is the distance from the Moon to the Earth.

The ratio of the illuminance of the Earth at half moon and on a sunny day is equal to

$$\frac{E_\pi}{E_c} = \frac{1}{2} \left( \frac{r}{l} \right)^2 = \frac{1}{80 000}.$$

F42

The rope will be thrown over the block, with part of the rope lying on the table and part on the floor. After the rope was released, it began to move. Find the speed of steady uniform motion of the rope. The height of the table is $h$ (Fig. 8).

Fig. 8.

The easiest way to solve the problem is to use Newton's second law.

During time $\Delta t$, a piece of rope of length $\Delta l = v \Delta t$ is involved in motion. If the mass of a unit length of rope is denoted by $\mu$, then the mass of a piece of rope $\Delta l$ is equal to $\Delta m = \mu \Delta l = \mu v \Delta t$. During the time $\Delta t$, the mass $\Delta m$ of the rope is given an impulse (amount of motion) equal to $\Delta mv = \mu v^2 \Delta t$. It is clear that this change in momentum appears due to the difference in gravitational forces acting on the left and right parts of the rope. This difference is equal to $mgh$.

According to Newton's second law, we can write

$$\mu v^2 \Delta t = \mu gh \Delta t.$$

From here

$$v = \sqrt{gh}.$$

The correct solution was sent by N. Ezhov from Odessa and A. Viktorov from Tula.

F44

Two dolphins swim towards each other. However, they produce a sound of frequency $\omega$. What frequency does the other dolphin hear if the speeds of the dolphins relative to the water are the same and equal to $v$? The speed of sound in water is $u$.

Using the result obtained in the “Doppler Effect” table, we find that the second dolphin will hear sound with a frequency

$$\omega_2 = \omega \frac{u + v}{u - v}.$$

Indeed, since the first dolphin is moving, the frequency of the sound waves that are received by the motionless receiver in front is equal to

$$\omega_1 = \frac{\omega}{1 - \frac{v}{u}} = \frac{\omega u}{u - v}.$$

⟦folio 41⟧

Fig. 9.

Thanks to the movement of the second dolphin, it will pour out the sound with a frequency

$$\omega_2 = \omega_1 \left( 1 + \frac{v}{u} \right) = \omega_1 \frac{u + v}{u} = \omega \frac{u + v}{u - v}.$$

F45

A spherical capacitor filled with a dielectric and charged to a certain potential difference is discharged through its dielectric. What will be the magnetic field of the discharge currents in the space between the spheres?

Let us select a narrow end “conductor” in the insulator. It is clear that for any point $A$ (Fig. 9) we can always find a “conductor” with another concept, such that the current flowing through it creates a field at point $A$, the direction of which is equal to the directionality of the current field of the “conductor” we have selected and has the opposite direction. This means that the magnetic field of the discharge currents between the spheres is zero.

F46

A cube falls onto a ball from a height of 1 m, and then jumps almost 1 m. To what height does the ball jump?

To what height will the ball jump if exactly the same ball falls on it from a height of 1 m?

At the moment when the cube leaves the ball, the speed of the cube is equal to the speed of the top point of the ball. Let's denote this speed $v$. Then the cube moves freely. Therefore, having written down the law of conservation of energy for it

$$\frac{Mv^2}{2} = Mgh$$

($h — высота подъема$), we find that $v = \sqrt{2gh}$.

The speed of the bottom point of the ball at the moment when the cube comes off it is zero, which means the speed of the center of the ball is $\frac{v}{2}$. Having written down the law of conservation of energy for the ball

$$\frac{m \left( \frac{v}{2} \right)^2}{2} = mgh_1$$

where $h_1$ is the height of the cube, we find

$$h_1 = \frac{h}{4} \approx 25 \text{ cm}$$

You will figure out for yourself how to create the flow of balls.

⟦folio 42⟧

If the ABC process (Fig. 10) is performed on an ideal gas, then the amount of heat Q is imparted to it. What amount of heat is imparted to the gas during the ADC process?

The heat that is imparted to the gas goes to increase its internal energy W and to the work done during the expansion of the gas. Since the initial and final states, and therefore the temperatures of the gas, are the same for both processes, the changes in the internal energy of the gas are also the same. As for the work done during gas expansion, in the first case it is equal to $P_2(V_2-V_1)$, and in the second: $P_1(V_2-V_1)$.

From the law of conservation of energy it follows that

$$Q = W + P_2(V_2-V_1)$$

And

$$Q_1 = W + P_1(V_2-V_1),$$

where $Q_1$ is the amount of heat during the process

$$A \rightarrow D \rightarrow C.$$

From these equations it is easy to find that

$$Q_1 = Q - P_2(V_2-V_1) + P_1(V_2-V_1) = Q - (P_2-P_1)(V_2-V_1).$$

The value $(P_2-P_1)(V_2-V_1)$ is numerically equal to the area of ​​rectangle ABCD. Therefore, our result is quite natural.

The difference $Q-Q_1$ should obviously be equal to the difference in the work done during the expansion of the gas, and the work during the expansion of the gas is numerically equal to the area of ​​the figure formed by the graph of the dependence $P$ on $V$ and the explanation $V$.

The correct solution was sent by A. Rozozin from Izhevsk.

I. Sh. Slobodetsky
