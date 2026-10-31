---
id: 1971-6-resheniya-2ec5edef
issue: kvant_1971_6
year: 1971
number: "6"
title: Solutions to problems M34—M38; F52—F58
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 37
page_last: 47
page_labels: 35, 36, 37, 38, 40, 41, 42, 43, 44, 45
tag: GCCN
lang: en
source: kvant_digital
extraction: vision
content_sha256: d3327527fd42d4e7d434c44c1e07e3f514451ec2acc22391d13f8a4ea6fb9a07
prompt_sha256: draft-1
translated_from: content/ru/1971/06/articles/11_resheniya-2ec5edef.md
source_content_sha256: a54702f559c4a03b80cb5b09ac40cef6ad3c8a5bc1d5790a344105c3c1765c79
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 35⟧

SOLUTIONS

In this issue we publish solutions to problems M34—M38.

M34

Prove that if a natural number is divisible by 10 101 010 101, then in its decimal notation at least six digits are different from zero.

The problem can be solved very easily if the number $A$ is divisible by 10 101 010 101 and has no more than 12 digits; then it necessarily has the form $ababababab$, and the problem is solved.

It remains to come up with some way to reduce the problem to this case.

We denote the number 10 101 010 101 by $M$. Let us prove that if the number $A$ is divisible by $M$, then we will find a twelve-(or less) digit number $C$, which is also divisible by $M$ and has no more non-zero digits than $A$.

Lemma. If $A$ is divisible by $M$ and has more than 12 digits (counting zero), it will find the number $B$, also divisible by $M$, less than $A$ and having no more non-zero digits than $A$.

Let's prove it. Let $A = a_1a_2a_3\dots a_n$; cross out its first digit $a_1$ and add it 12 digits lower, for example:

$$123\ 456\ 789\ 123\ 456 \rightarrow 23\ 456\ 789\ 123\ 456$$
$$+\frac{1}{23\ 456\ 789\ 123\ 556}$$

The resulting number will certainly be smaller than the original: it is easy to check that we are simply calculating $a_1 \cdot (10^{n-1} - 10^{n-13})$. In parenthesis

⟦folio 36⟧

kah is the product $10^{n-13} \times (10^{12}-1)$; the second factor is obviously divisible by $A$. It remains to replace that the resulting number of significant (non-zero) digits is no more than the original one. In our example, their number even decreased by one; This could, however, not be accidental if there had been a 0 in the 13th place or if there had been a sufficiently large number there and a 0 in the previous place, as in the example

$$888 888 888 880 421 \rightarrow 88 888 888 880 421$$
$$+\frac{8}{88 888 888 881 221}$$

(you have not yet considered the case when the transfer occurs in the 12th digit, but it is easy to see that then the number of significant digits will even decrease). The lemma is proven.

Now if $A$ is divisible by $M$, subtract from $A$ its first digit multiplied by $10^{n-13} \cdot (10^{12}-1)$. With the resulting number, we sell the same operation and will do this until we add to the 12-digit number. Since it has at least six significant digits, $A$ also has at least six significant digits.

Most solvers tried to consider part of the division $A$. on $M$;

but solving it in this way is very difficult, since when this quotient is multiplied back by 10 101 010 101, its digits “stick together” with each other, a lot of transfer of units in digits can occur, and it is almost impossible to figure out what happens. The idea behind the solution is to look at these transfers one at a time.

A. K. Tolpieo

M35

A sharp 19-sided face is described near a sphere of radius 10. Prove that there are two points on its surface the distance between which is greater than 21.

First decision. Let us assume the opposite, that is, that the distance between any two points on the surface of our 19-hedron is no more than 21. Then this polyhedron lies inside a sphere of radius 11, concentric to a sphere of radius 10, and each of its faces lies between the spheres. It is clear that the area of ​​each face is not too large, namely, it does not exceed the area of ​​\u200b\u200bthe circle shown at figure 1, the radius of which is $\sqrt{21}$. Our polyhedron has 19 faces, so the area $S$ of its surface does not exceed $19\left[\pi\left(\sqrt{21}\right)^2\right]=\pi\left(20^2-1^2\right)=399\pi$.

No polyhedron is described around a sphere of radius 10. Hence, its surface area is greater than the area of ​​this sphere $4\pi\left(10\right)^2$*. So, on the one hand, $S<399\pi$, on the other hand, $S>400\pi$. The resulting opposite solves the problem. (A similar solution was sent to us by D. Grisoriev from Leningrad.)

In this (non-rigorous) solution, we missed the proofs of three statements that begin with the three words highlighted above: moeda, pozmotu, hence. We leave these simple proofs to the reader, but we want to warn that although the required statement is easy to prove for a convex polyhedron

*) Recall that for a ball of radius $R$ the volume is $\frac{4}{3}\pi R^3$, the area of ​​a segmented surface with height $h$ is $2\pi Rh$ and, in particular, the area of ​​the sphere is $4\pi R^2$.

⟦folio 37⟧

nik by comparing its volume with the volume of a sphere *), nevertheless, the intuitively clear and correct statement that our polyhedron is convex is difficult to prove strictly, since the strict definition of a polyhedron itself is very complex. (Look, for example, at the book by I. Lakatok “Proofs and Refutations”, M., “Science”, 1967).

Second solution. Let us pose a more general question: what is the maximum number of faces that a polyhedron can have that is described around a sphere of radius $r$ and lies entirely in a concentric sphere of radius $R > r$. (Here is an everyday situation that prompted the author to solve this problem: with what maximum number of straight strokes can you use the top layer of the husk of an orange without destroying a single piece of the pith? Obviously, after weeding the entire top layer of the kokura, the remainder will be a polyhedron, since there will not be a single rounded section on its surface, so this question is equivalent to the previous one.) We do not know the exact answer to this more general question, but we will prove it for a number faces of some inequalities, which for $r = 10$, $R = 11$ shows that $N > 22$. Thus, we will prove that if under conditions problem M35 we take a 22-hedron together with a 19-hedron, then the statement of the problem remains valid.

So, let the $N$-hedron be described near a sphere of radius $r$ and lie entirely inside a sphere of radius $R$. Some edge of it at a distance.

A plane passing through it cuts off a cap (segmental surface) of height $R - r$ from the sphere. It is clear that if we build caps for all the faces of our polyhedron, then their union will cover the entire outer sphere. Each of $N$ caps

*) Indeed, the volume of a polygon is equal to $\frac{R \cdot S}{3}$, where $R$ is the radius of the inscribed sphere, and $S$ is its surface area.

A natural surface has height $R - r$, and therefore has area $2\pi R (R - r)$. The sum of the areas of all caps is greater than the area of ​​the sphere. Therefore, $N \cdot 2\pi R (R - r) > 4\pi R^2$, hence $N > \frac{2R}{R - r}$, in particular, for $R = 11$, $r = 10$ we obtain $N > 22$.

It is interesting that for any set of caps that completely cover the outer sphere, it is possible to construct a polyhedron described around the inner sphere. (Prove it!) Therefore, our question about the minimum number of faces is completely equivalent to the following question. What is the minimum number $N = N(h)$ of caps of height $h$ that completely cover spheres of radius 1? (In problem $M35 h = \frac{1}{11}$).

Obviously $N(h) > \frac{2}{h}$, but this incorrectness simply reflects the fact that the sum of the areas of the caps is larger than the area of ​​the sphere, while intuitively it is clear that for $h < 1$ the caps should overlap quite a lot. Indeed, it can be proven that for sufficiently small $h$ $N(h) > 1,2 \frac{2}{h}$. Try to prove for yourself, for example, that for $h < 1$

$N(h) > 1,001 \frac{2}{h}$.

(The solutions to this problem and other similar problems can be found in the book by L. F. Toth. “Location on a plane, on a sphere and in space.” M., Fizmatgiz, 1958).

A. G. Kushirienko

M36

Prove that it is impossible to arrange seven lines and seven points on a plane so that three lines pass through each point and three points lie on each line.

Let us assume that such an arrangement of seven points and seven straight lines

⟦folio 38⟧

Fig. 2. The convex hull of a set of a finite number of points is a convex polygon with vertices at some of these points (or a segment if all points lie on the same line).

marches. First of all, we prove that every two of these points lie on one of the given lines. Indeed, if $A$ is one of these points, then three lines pass through $A$, and each of them contains two of these points (not counting $A$); thus $A$ and any of the six points other than $A$ lie on one of the given lines. In the same way, it is proved that every two of the given lines intersect at one of the given points: if $a$ is one of the lines, then through each of the three points lying on it there are two straight lines (not counting $a$), and therefore each of these lines intersects with $a$ at one of the given points.

Let us now consider the convex hull of the set of our seven points - the smallest convex figure containing these seven points.

Fig. 3. This configuration almost completely satisfies the requirements of problem M36, only one “straight” had to be bent.

This will be some convex $n$-gon, where $n \leqslant 7$ (it can be obtained like this: be at the given seven points of nails and then stretch a rubber thread covering all these nails; the nitka will stretch along the contour of a polygon with vertices at some $n$ of the given points, and all other ($7-n$) points will lie inside or on the border of this polygon; see Fig. 2). It is clear that the $n \geqslant 4$ case is impossible - after all, on each side of the $n$-gon there must be one more third point, in addition to the vertices, and there are seven points in total. The case $n=3$, when the convex hull is some triangle $ABC$, the same is impossible. Indeed, if $E$ and $F$ are points (from among the given seven) that lie on the sides $AB$ and $BC$, then $EF$ and $AC$ - two of the given lines - must intersect at one of the given seven points, and they will intersect on the continuation of side $AC$, that is, outside the triangle $ABC$. We got a contradiction.

Figure 3 will help find the error for those who sent us the wrong solution to this problem.

M37

A certain number is inscribed in each cell of an infinite sheet of checkered paper so that the sum of the numbers in any square (the sides of which follow the grid lines) does not exceed one in absolute value. Prove that then there exists a number $c$ such that the sum of the numbers in any rectangle (whose sides follow the grid lines) is not greater than $c$; in other words, that the sums of numbers in all rectangles are limited. Prove that this is true for $c=4$. You may be able to improve this estimate (for example, prove that our statement is true for $c=3$ or even for $c=2$).

The solution we present is close to proposal $A$. Klimov (Moscow).

Let's prove that $c$ equal to 4 is suitable.

Suppose that in some rectangle with sides $a$ and $b$ the modulo sum is $4+\epsilon$, where $\epsilon > 0$ ($a < b$). Let's build four squares, each of which has three sides along certain three hundred

⟦folio 40⟧

Fig. 6. Let $k_n = \frac{a_n}{b_n}$. Then $k_{n+1} = f(k_n)$, where $f(k) = \frac{|1-2k|}{2-k}$. Here is a graph of this function on the segment $0 \leq k \leq 1$. When solving the problem, we obtain that for any point $M$ on the right half of the graph $MQ/MP > 2$; if $0 \leq k \leq \frac{1}{2}$, then $0 \leq f(k) \leq \frac{1}{2}$, and $f(f(k)) = k$, that is, the function $f$ on the segment $0 \leq k \leq \frac{1}{2}$ coincides with its inverse function, and its graph is symmetrical with respect to the bisector of the angle between the coordinates.

Fig. 7. All unfilled cells contain zeros.

Secondly, if $\frac{a_n}{b_n} > \frac{1}{2}$, then

$$\frac{1 - \frac{a_{n+1}}{b_{n+1}}}{1 - \frac{a_n}{b_n}} = \frac{1 - \frac{2a_n - b_n}{2b_n - a_n}}{1 - \frac{a_n}{b_n}} = \frac{3b_n}{2b_n - a_n} > \frac{3b_n}{2b_n - \frac{b_n}{2}} = 2;$$

Thus, the value of $1 - \frac{a_n}{b_n}$ in the transition from $n$ to $n+1$ is mutilated by at least two times until we arrive at the rectangle with $\frac{a_n}{b_n} \leq \frac{1}{2}$. Therefore, how could we consider that it is already $\frac{a_1}{b_1} < \frac{1}{2}$.

At the same time

$$a_3 = b_2 - 2a_2 = (2b_1 - a_1) - 2(b_1 - 2a_1) = 3a_1,$$

$$b_3 = 2b_2 - a_2 = 2(2b_1 - a_1) - (b_1 - 2a_1) = 3b_1.$$

Therefore, in general, $a_{2k+1} = 3^k a_1$ and $b_{2k+1} = 3^k b_1$, and the sum of the numbers in this rectangle $3^k a_1 \times 3^k b_1$ is greater than $4 + 9^k e$, that is, by choosing $k$ large enough, we can make it angle-wise large. Now it is not difficult to obtain a contradiction: it is clear that any rectangle $Na_1 \times Nb_1$, where $a_1$, $b_1$ and $N$ are integers, can be divided into $a_1b_1$ squares (from the side $N$), and therefore the sum of the numbers in it cannot exceed the absolute value of the number $a_1b_1$.

Figure 6 shows the second glaze of the proof. figure 7 shows an example for which the sum of the numbers in some rectangles is equal to those. Thus, for $c = 2$ the statement of the problem is false. It is very plausible that the exact estimate is $c = 4$, but we do not know of examples showing that $c > 3$.

N. B. Vasiliev

⟦folio 41⟧

M38

A circle constructed at the height AD of a right triangle ABC as a diameter intersects the leg AB at point K, and the leg AC at point M. The segment KM intersects the height AD at point L. It is known that the segments AK, AL and AM form a geometric progression (that is, $\frac{AK}{AL} = \frac{AL}{AM}$).

It is not difficult to prove that AKDM is a rectangle and L is its center (Fig. 8). Let us lower the redistribution of AP to KM.

Then
$$AL^2 = AK \cdot AM = KM \cdot AP = 2AL \cdot AP,$$
$$AL = 2AP, \angle PLA = 30^\circ,$$

and since $AL = KL = ML$, it follows that the acute angles of triangle AKM are $15^\circ$ and $75^\circ$. Triangle ABC has the same acute angles: $\angle C = \angle BAD = \angle AKM$.

Fig. 8.

This decision was added by S. Komanov from Tbilisi and V. Krivitsky from the village of Kletnoye, Minsk region.

L. M. Lopovok

In this issue we publish solutions to problems F52—F58

F52

The ball is thrown vertically upward. What is greater: the rise time or the fall time?

The kinetic energy of the ball at any height during the bet is greater than when the ball is dropped. Indeed, if there were no air resistance, then these energies would be equal. Due to air resistance during descent, the kinetic energy of the ball is less than during the rebound by the amount of work spent on overcoming air resistance. This means that at any height, the speed of the ball on the upswing is greater than on the downswing. Obviously, the average speed of the ball is also high. Therefore, the time it takes to pick up the ball is less than the time it takes to fall.

F53

The vessel contains two immiscible liquids with densities $\rho_1$ and $\rho_2$ and thicknesses $h_1$ and $h_2$, respectively. A small streamlined body is lowered from the surface of the liquid into a vessel, which reaches the bottom just at the moment when its speed becomes zero. What is the density of the materials from which the body follows?

Let us take advantage of the fact that the potential energy possessed by the body on the surface of the upper liquid is spent when the body moves to overcome resistance. That's why
$$mg(h_1 + h_2) = A_1 + A_2,$$
(*)

where $m$ is the mass of the body, $g$ is the acceleration of free fall, $A_1$ is the work of resistance forces in the upper fluid and $A_2$ is the work of resistance forces when the body moves in the lower fluid. Since the body is streamlined, the drag force is the Archimedean buoyant force: $F_1 = \rho_1Vg$ in the upper fluid and $F_2 = \rho_2Vg$ in the lower fluid (V is the volume of the body). That's why
$$A_1 = \rho_1Vgh_1$$ and $A_2 = \rho_2Vgh_2$.

Substituting these expressions for $A_1$ and $A_2$ into equation (*) and taking into account that $m = V \cdot \rho$ (ρ is the density of the body), we obtain $\rho (h_1 + h_2) = \rho_1h_1 + \rho_2h_2$.

⟦folio 42⟧

From here
$$\rho = \frac{\rho_1 h_1 + \rho_2 h_2}{h_1 + h_2}.$$

The correct solution to add V. Kalintsev from Moscow, Yu. Polonsky from Zelenyodolsk TASSR and other readers.

However, a great reader solved the problem in a more complex way.

A body moving in a fluid is acted upon by two forces: the gravity force, equal to $mg = \rho Vg$, and the Archimedean buoyant force (equal to $F_1 = \rho_1 Vg$, when the body moves in a fluid with a density of $\rho_1$, and $F_2 = \rho_2 Vg$, when it moves in a fluid with a density of $\rho_2$).

Since the body is streamlined, the forces acting on it while moving in each fluid do not change. Consequently, the body moves uniformly accelerated. Let's write down the equation of motion of the body. In the upper fluid: $mg - F_1 = ma_1$ (acceleration is directed downward), in the lower fluid: $F_2 - mg = ma_2$ (acceleration is directed upward). From these equations we find that in a fluid with density $\rho_1$ the body moves with acceleration $a_1 = g \frac{\rho - \rho_1}{\rho}$, and in fluid with density $\rho_2 - c$ with acceleration $a_2 = g \frac{\rho_2 - \rho}{\rho}$.

Having passed the first liquid, the body will acquire speed $V_0 = a_1 t_1$, where $t_1$ is the time of movement. This time can be found from the kinematic equation $h_1 = \frac{a_1 t_1^2}{2}$. Therefore $V_0 = \sqrt{2 a_1 h_1}$. At this speed the body begins to move in the lower liquid. Since the speed of the body at the end of the movement should become equal to zero, then $V_0 - at_2 = 0$, where $t_2$ is the time of movement of the body in the second fluid.

Hence $t_2 = \frac{V_0}{a_2}$. During this time, the body will travel a distance $h_2$ in the second liquid. Therefore $h_2 = V_0 t_2 - \frac{a_2 t_2^2}{2}$.

Substituting the expressions for $V_0$, $a_2$ and $t_2$ into the last equation, we obtain
$$h_2 = \frac{V_0^2}{a_2} - \frac{1}{2} \frac{V_0^2}{a_2} = \frac{1}{2} \frac{V_0^2}{a_2} = \frac{a_1 h_1}{a_2}.$$

⟦folio 43⟧

It is equal to 7.5 ohms. In Pozny, current $I_0 = \frac{30 \, \theta}{7,5 \, \omega} = 4 \, a$ flows through the source.

The current going through the source is the sum of the current going through the ammeter and the current $I_1$ going through the resistance $R_1$. Let's find the current $I_1$.

At point $A$ the current $I_0$ is divided equally between the upper and lower branches of the circuit. Posny through resistance $R_2$ current $I_2$, equal to 2$a$. At point $B$ this current is again divided equally between equal resistances $R_1$ and $R_3$. To Posny, current 1$a$ flows through resistance $R_1$. Now you can find the current flowing through the ammeter. It is equal to $I_0-I_1=3a$.

F55

Estimate the height $H$ of an arrow shot vertically upward from a child’s bow. Arrow weight $m=20 \, \text{г}$, string length $AB=1 \, \text{м}$. The bowstring is pulled back to $h_0=5 \, \text{см}$. The bowstring tension is considered constant and equal to 250 $\text{н}$.

The energy acquired by the arrow when fired is equal to the work done by the force acting on the arrow from the bowstring. This force is obviously equal to the equal $F$ string tension force $T$ (Fig. 11). If the angle formed by the bowstring at points $A$ and $B$ with lines $AB$ is $\alpha$, then it is not difficult to find that $F=2T\sin \alpha$. So, the force acting on the arrow depends on how much the bowstring is pulled back. Since the bowstring is pulled back to a distance that is small compared to its length, the angle $\alpha$ is small, that is, $\sin \alpha \approx tg\alpha \approx \alpha$. Pozny $F=2T\alpha$.

Since $tg\alpha = \frac{h}{AB}$ ($h$ is the height of the bowstring deflection), then

$$F = 4T \frac{h}{AB}.$$

So, the force acting on the arrow is proportional to $h$ (Fig. 12).

It is not difficult to find the work of this force. It is equal to the area of ​​the figure between

⟦folio 44⟧

Fig. 13.

container theory of flight and waves on water" in «Kvant» No. 5 for 1970. The behavior of the flag is explained in the same way as the formation of a wave on water.

Let's assume that the flag is slightly curved at some point (Fig. 13). In this case, at the top, when flowing around the protrusion, the wind speed is greater, and at the bottom, in the area of ​​concavity of the flag, the wind speed is less than away from the flag. From Bernoulli's law it follows that the air pressure at point A is greater than the pressure at point B. Therefore, the formation of a protrusion should increase. Also, since the formation behind the bump causes the pressure behind it to be less than the pressure in front of the bump, the bump will get mixed up towards the end of the flag. So, by chance the formation of the concavity of the flag will increase. If we also take into account that, due to the formation of an outlet when flowing around even a flat flag with a uniform wind, the pressure on different sides of the flag may be different and therefore small bends in the surface will easily form, it becomes clear why the flag “flashes” in the wind.

F57

Two identical balls, connected by a weightless spring, move along a smooth horizontal floor at the same speed, perpendicular to the vertical wall. Describe how the collision of the system with the wall will occur. How will the balls move after the impact? The impact of the ball on the wall is absolutely elastic, the time of impact is short compared to the period of oscillation of the ball outside.

Since the speeds of the balls are initially identical and constant, the torus is not deformed. Indeed, otherwise, a force would act on each of the balls from the side of the spring, imparting acceleration to it, and the speed of the ball would change with time. After the first ball hits the wall, its speed is reversed. The balls begin to move towards each other with

⟦folio 45⟧

equal in speed (see Fig. 14), the spring is released. The kinetic energy of the balls turns into potential energy of deformation of the spring. Then the spring begins to straighten, imparting speeds of equal magnitude and opposite direction to the balls. In this case, just as during the roll of the spring, the center of mass of the system is motionless relative to the wall - no horizontal forces act on the system. From the law of conservation of energy it follows that at the moment when the ball hits the wall correctly, the speeds of the balls are equal to the initial speed of the system. After the ball collides with the wall, its speed again changes to the opposite and the balls move away from the wall at the same speeds. Since the spring is not deformed at the moment the ball hits the wall, it does not deform during further movement of the system.

F58

In a magnetic field, a ring with a diameter of $d$ and a resistance of $R$ falls from a great height. The plane of the ring is always horizontal. Find the steady speed of the fall of the ring if the field induction varies with height according to the law

$$B = B_0 (1 + \alpha H).$$

The force acting on the ring in a magnetic field is proportional to the current inducting through the ring, the current is proportional to e. d.s. induction excited in the ring during its movement, and e. d.s. induction, in turn, is proportional to the rate of change of the magnetic flux, proportional to the plane of the ring, and therefore proportional to the speed of the ring. Consequently, at a certain speed of movement of the ring, the force acting on it in the magnetic field becomes a cell. This speed is the speed of steady motion of the ring.

Since the kinetic energy of the ring does not change when the ring moves, the change in potential energy must be equal to the heat losses in the ring.

Let the speed of the ring be $v$. E.m.f. the induction excited in the ring during its movement is equal in magnitude

$$E = k \frac{\Delta \Phi}{\Delta t},$$

where $\Phi$ is the magnetic flux, an arbitrary ring, and $k$ is the proportionality coefficient.

$$\Phi = \frac{\pi d^2}{4} B = \frac{\pi d^2}{4} B_0 (1 + \alpha H),$$

$$\frac{\Delta \Phi}{\Delta t} = \frac{\pi d^2}{4} B_0 \alpha \frac{\Delta H}{\Delta t}.$$

But $\frac{\Delta H}{\Delta t} = v$, therefore

$$E = k \frac{\pi d^2}{4} B_0 \alpha v$$

and current flows through the ring

$$I = \frac{E}{R} = \frac{k \pi d^2 B_0 \alpha v}{4 R}.$$

Let us now write down the law of conservation of energy. Let the mass of the ring be $m$. During time $t$, heat equal to $I^2 Rt$ is released in the ring. If during this time the ring drops to a height of $h$, then

$$mgh = I^2 Rt.$$

Since $\frac{h}{t} = v$, then

$$mgv = I^2 R,$$

$$mgv = \frac{k^2 \pi^2 d^4 B_0^2 \alpha^2 v^2}{16 R}.$$

From here

$$v = \frac{16 Rmg}{k^2 \pi^2 d^4 B_0^2 \alpha^2}.$$

I. Sh. Slovodetsky
