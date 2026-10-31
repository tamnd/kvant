---
id: 1989-9-resheniya-zadach-m1156-m1160-f1168-f1172-b7bbc62d
issue: kvant_1989_9
year: 1989
number: "9"
title: Solutions to problems M1156—M1160; F1168—F1172
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 33
page_last: 39
page_labels: 31-37
tag: 99RU
lang: en
source: kvant_digital
extraction: vision
content_sha256: 63be97d80b2aebd9a0cc541b84e4b666dfd709553e1a43ca1bd93835585715bb
prompt_sha256: draft-1
translated_from: content/ru/1989/09/articles/04_resheniya-zadach-m1156-m1160-f1168-f1172-b7bbc62d.md
source_content_sha256: 923b672f73894e5b03a7ad1fe7ac696b733858c0c9e7bb39fd76a0dcec06973d
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 31⟧

F1189. The large room is kept at a constant temperature $T_k=+15^\circ\text{C}$ in winter by three central heating radiators connected in series (Fig. 2), through which hot water is pumped. In this case, the temperature of the first radiator is $T_1=+75^\circ\text{C}$, and the last (third) is $T_3=+30^\circ\text{C}$. What is the temperature of the second radiator? Consider that the heat exchange - both between the radiator and the room, and between the hot water and the radiator - is proportional to the corresponding temperature difference.

A. V. Andrianov

F1190. Two identical capacitors are connected in series to a battery with internal resistance $r=1$ Ohm. A resistor $R=1000$ Ohm is connected in parallel to one of them, and a certain amount of heat is released in the circuit. How much of this heat will be released into the internal resistance of the battery?

A. R. Zilberman

F1191. Is a thin-walled conducting sphere of radius $R$ connected to the source by thin wires (Fig. 3) ​​connected at points $A$ and $B$ ($AO \perp OB$, $O \perp OB$)? Let's make two marks on the sphere near point $C$, so that the distance between them is $R/1000$, and the segment connecting them turns out to be perpendicular to the direction of the charges. What fraction of the total current flows through the sphere between these marks?

L. G. Markovich

F1192. At the end of the cylindrical solenode there is a thin sheet of cardboard, on it there is a small superconducting ring made of thin wire, the diameter of which $d_1$ is significantly smaller than the diameter of the ring $D$. When connecting the solenode to the source in series with the capacitor (Fig. 4), the ring is undermined at $U>U_0$. What should be the source voltage in a similar experiment with a colute of the same diameter, but made of wire $d_2$ thick? The inductance of such a loop can be estimated with sufficient accuracy for practice using the formula $L=kD \ln(1,4D/d)$. The solenoid resistance should be considered low.

V. V. Mozhaev

Problem solutions
M1156—M1160, F1168—F1172

We will prove that the team that scores 11 points is guaranteed to reach the final four. Let's assume the opposite: let some 5 teams score at least 11 points. In 10 games between themselves, these 5 teams scored a total of 20 points, and in games with the other 3 - no more than $2 \cdot 3 \cdot 5=30$, i.e. in total they scored no more than $50<5 \cdot 11$ points. This contradicts our assumption.

⟦folio 32⟧

About points.) What is the lowest number of points that guarantees reaching the final four?

On the other hand, 10 points does not guarantee access to the finals. Indeed, if some 5 teams draw all their matches, and win the other 3 teams, then each of them will score 4+6=10 points, but may not get into the final four.

In the same way, it can be proven that in a one-round tournament of teams, the minimum number of points that guarantees reaching the top $k$ of the $n$ participants ($k < n$) is $2n-k-1$.

S. Khodzhiev

M1157. Three triangles - white, red and green - have a common interior point M. Prove that you can choose one vertex of each triangle so that point M is inside or on the border of a triangle with vertices at selected points of three different colors.

Let's consider all possible angles formed by segments going from $M$ to some two vertices of different colors. Let the most of these angles be $\alpha = \angle AMB \leq 180^\circ$, with $A$ being the red point and $B$ being the white point. then there are no green points inside the corners $AMB'$ and $BMA'$ adjacent to $\alpha$ (see figure). Therefore, in the vertical angle $A'MB'$ relative to $\alpha$ there must be one green vertex $C$ (otherwise all 3 green vertices would be inside the angle $\alpha$, and the green triangle would not contain the point $M$). The triangle $ABC$ is the one we are looking for: it contains the point $M$, since $M$ lies on the same side as $C$ of the straight line $AB$, and the segments $AC$ and $BC$ intersect the continuations of the segments $BM$ and $AM$.

Try to come up with an analogue for stating this problem in space.

I. Barani

M1158. Find the smallest value of the expression $(x+y)(x+z)$ if $x, y, z$ are positive numbers and $xyz(x+y+z)=1$.

Answer: The smallest value is 2.

Put $a=y+z, b=x+z, c=x+y$ and consider the triangle from the side $a, b, c$; it exists because each of the numbers $a, b, c$ is less than the sum of the other two (see figure). The perimeter of this triangle is $2p=a+b+c=2(x+y+z)$, and the area, according to Heron’s formula

⟦folio 33⟧

$$S = \sqrt{p(p-a)(p-b)(p-c)} = \sqrt{(x+y+z)xyz} = 1.$$
On the other hand, $2S = bc \sin \alpha$, where $\alpha$ is the angle between sides $b$ and $c$, so
$$(x+z)(x+y) = bc \geqslant 2S = 2,$$
Moreover, equality is achieved for a right triangle, i.e., under the condition $a^2 = b^2 + c^2$, equivalent to this: $x(x+y+z) = yz$. (In particular, $(x+y)(x+z) = 2$ at $x+y=x+z=\sqrt{2}$, $y+z=2$, i.e. $y = z=1$, $x=\sqrt{2}-1$.)
Having guessed when equality is achieved, it is easy to find a short algebraic proof using the inequality $p+q \geqslant 2\sqrt{pq}$:
$$(x+y)(x+z) = x(x+y+z) + yz \geqslant 2\sqrt{xyz}(x+y+z) \geqslant 2.$$
O. Khristenko

M1159. Using a double-sided ruler, construct an angle of magnitude $30^\circ$. The following operations are allowed: (1) drawing a straight line through two points, (2) drawing a straight line parallel to the line at a distance equal to the width of the ruler.

Fig. 1.

Fig. 2.

Fig. 3.

4. We mark three nodes of this grid $A, B, C$, forming a right triangle with legs $AB=\sqrt{3}, BC=\sqrt{6}$ and hypotenuse $AC=3$ (Fig. 3).
5. Drawing a line parallel to $AB$ at a distance of 1 from it, we find a point $D$ on the segment $BC$ such that $BD=1$. Then $\angle BAD=30^\circ$.
Of course, there are other solutions.
Another possibility of a double-sided ruler is more widely understood: it allows you to draw two parallel straight lines at a distance of 1 through two given points $A$ and $B$ ($AB \geqslant 1$; Fig. 4). It can be shown that in this case, using a double-sided ruler,

⟦folio 34⟧

All the same construction problems are solved as with the help of a compass and a ruler (see, for example, the book by I. I. Aleksandrov “Collection of geometric construction problems”, M.: Uchrednitsa, 1952). Consider whether this is true for the two operations from the conditions of our problem.

A. V. Poleb

M1160. At one end A of the straight road AB, gather 10 kangaroos and begin to leapfrog. They jump in turns: the first one jumps wherever he wants each time; the second jumps over the first so that the first is exactly halfway between the beginning and end of the jump, the third jumps over the second in the same way, etc., the tenth jumps over the ninth, then a new series of jumps begins according to the same rules.

a) After 10 series of jumps, can all the kangaroos be collected at point B?
b) Can they collect ravshe there?

0 $x_1(1)$ $x_1(2)$ ... 1
0 $x_2(1)$ $x_2(2)$ ... 1
0 $x_3(1)$ $x_3(2)$ ... 1
0 $x_{10}(1)$ $x_{10}(2)$ ... 1

Table 1.

0 1/512 10/512 ... 1
0 1/256 9/256 ... 1 1
0 1/4 3/4 1 ... 1 1
0 1/2 1 1 ... 1 1
0 1 1 1 ... 1 1

Table 2.

Answer: a) yes, 6) no.

We will set the position of the $i$th kangaroo after the $k$th jump by coordinate $x_i(k)$ on the AB axis, taking point A as 0, and $B$ as 1. Then

$$x_{i-1}(k) = \frac{x_i(k-1)+x_i(k)}{2},$$

(1)

or

$$x_i(k-1) = 2x_{i-1}(k)-x_i(k).$$

(2)

Consider a table in which at the intersection of the $i$th row and $k$th column there is the number $x_i(k)$; add a “zero” column given the initial position: $x_1(0)=x_2(0)=\dots=x_{10}(0)=0$. By virtue of (1), each number in the table, except for the numbers in the zero column and the last (10th) row, is equal to the two in the next row - in the same column and in the previous one (see Table 1). If all the kangaroos are once collected at point $B$, then the last column consists of ones and from (2) it follows that the entire regular angle consists of only ones, as in Table 2. It immediately follows that the number of series of jumps must be at least 10, and the $i$th kangaroo ($i=2,3,\dots,10$) must remain at the point $B$, the last $i-1$ series. jumping on the spot. (Of course, the conditions assume that such jumps are allowed, i.e. several kangaroos can be at one point.)

Using the same table, 2 of 10 rows and 11 columns show how kangaroos must jump in order to fall to point $B$ in 10 series. The 10th kangaroo already in the first series should fall into $B$, and according to formula (1) sequentially find (other than 1) the numbers $x_i(k)$, starting from the bottom line: for $i=9$, then $i=8$, etc. To indicate the jumps ($i-1$ of the kangaroo, you need to mark the midpoints of the vectors on which it jumps $i$th kangaroo (see figure).

Compiling a table of these jumps - 1; $\frac{1}{2}$ and $\frac{1}{2}$; $\frac{1}{4}$, $\frac{2}{4}$ and $\frac{1}{4}$; $\frac{1}{8}$, $\frac{3}{8}$, $\frac{3}{8}$ and $\frac{1}{8}$, etc. - it is easy to see that they are expressed through the biominal coefficients $C_n^m = \frac{n(n-1)\dots(n-m+1)}{1\cdot2\cdot\dots\cdot m}$, participating in the formula *)

*) See the brochure “Pascal’s Triangle” by V. A. Uspensky (M.: Nauka, 1979) or the corresponding articles in the “Encyclopedic Dictionary of an Equestrian Mathematician” (recently republished: M.: Pedagogika, 1988).

⟦folio 35⟧

$$ (a+b)^n = C_n^0 a^n + C_n^1 a^{n-1} b + \ldots + C_n^k a^{n-k} b^k + \ldots + C_n^0 b^n. $$

Namely, for the $k$th jump of the $i$th kangaroo ($1 \leq k \leq 11-i, i=10, 9, \ldots, 1$) is equal to

$$ x_i(k) - x_i(k-1) = C_{10-i}^{k-1}/2^{10-i}; $$

the sum $11-i$ of these jumps (over all $k$ from 1 to $11-i$) for each $i$ is equal to 1.

S. L. Eliseev

F1168. Estimate the maximum speed of the Lunokhod - a self-propelled vehicle operating on the Moon, controlled from the Earth.

Let’s assume that at some point the lunar rover’s telephone “discovered” an unevenness on the lunar surface and “reported” this to Earth. Until the command is received, how does time move on?

$$ t = 2 \frac{l}{c} + \tau = 2 \frac{380 \cdot 10^3 \text{ км}}{300 \cdot 10^3 \text{ км/c}} + 0,1 \text{ с} \sim 2,6 \text{ с}. $$

Here $l$ is the distance from the Earth to the Moon, $c$ is the speed of radio signal propagation, $\tau$ is the duration of the operator’s decision making.

To estimate the speed of movement of the lunar rover, we will assume that it is as many times less than the speed $v \sim 20$ km/h of automatic movement on a flat earthly road as the time $t$ of “decision making” by the lunar rover is greater than the time $\tau$ of the reaction of the earthly driver. Therefore, the maximum speed of the Lunokhod

$$ v_\pi \sim v \frac{\tau}{t} \sim 1 \text{ km/ч}. $$

V. I. Shelest

F1169. The tonearm maker is a light straight rod of length $L$ (see Fig.ok), at one end of which (at point B) a sound generator with a target is attached, and the other end is fixed in a hinge, which can be adjusted without friction relative to the vertical axis $A$, passing at a distance $R$ ($R > L$) from the axis of treatment O of the disk tearer. The image is placed on a flat, uniform surface of a uniform healing disk. Nauti installed at the site between the tonar and the lyceum of the joint-stock company.

It is clear that the tonearm from the side of the healing disk is subject to a friction force, directed, as usual, against the relative speed of the tonearm and disk, in a steady position - perpendicular to the segment connecting points $B$ and $O$.

In a state of equilibrium, the moment of the friction force relative to the $A$ axis should be equal to zero. This means that the friction force is directed along the tonearm, i.e. angle $ABO$ is a right angle, triangle $ABO$ is a right angle, and angle $a$ is such that

$$ \cos \alpha = \frac{L}{R}. $$

It is characteristic that this equilibrium is stable (show this yourself).

Now let the needle be placed on the record. In general, when designing a blaster, choose $L \approx R$. Then, when the plate is torn, a layer constantly acts on the needle, tending to shift it towards the center of the disk, which leads to uneven wear of the plate. Therefore, high-class manufacturers are warned

⟦folio 36⟧

F1170. Estimates of the Galaxy's mass obtained by various methods give different results. Thus, according to visual estimates, within the distance $R = 3 \cdot 10^9 R_0$ ($R_0$ is the radius of the Earth’s orbit) from the center of the Galaxy, mass $M_1 = 1,5 \cdot 10^{11} M_0$ ($M_0$ is the mass of the Sun) is concentrated. Meanwhile, the period of revolution of stars located at the indicated distance from the center of the Galaxy is $T = 3,75 \cdot 10^8$ years. Determine the “hidden mass” of the Galaxy, i.e. the mass of invisible objects of the inner sphere with a radius of $R$. When calculating the motion of stars, the mass of the Galaxy can be considered concentrated at its center.

F1171. An electric diopole - two particles with identical masses $m$ and charges $+q$ and $-q$, enclosed at the ends of a rigid weightless diopole rod $l$ - moves with an angular velocity $\omega$ in the horizontal plane around a vertical axis passing through the center $O$ of the diopole (Fig. 1). At some points, a constant magnetic field is turned on with inductance $B$ directed vertically. Describe the steady motion of the diopole.

For a body moving in a circle of radius $r$ with a speed $v$ under the influence of the attraction of a central body of mass $m_\pi$, the centripetal acceleration $v^2/r$ is equal to the gravitational acceleration $Gm_\pi/r^2$ (G is the gravitational constant):

$$\frac{v^2}{r} = \frac{Gm_\pi}{r^2}.$$

Hence, using the expression $t = 2\pi r/v$ for the period of revolution, for the mass of the central body we obtain

$$m_\pi = \frac{4\pi^2 r^3}{Gt^2}.$$

Comparing the movement of the Earth around the Sun (with a period of $T_0 = 1$ year) with the movement of the stars considered in the task, we find the total mass $M$ of the Galaxy inside a sphere whose radius is $R$:

$$M_0 = \frac{4\pi^2 R_0^3}{GT_0^2}, \quad M = \frac{4\pi^2 R_3^3}{GT^2},$$

$$M = M_0 \frac{R^3}{R_0^3} \frac{T_0^2}{T^2} = 1,9 \cdot 10^{11} M_0.$$

Thus, the “hidden mass” of the Galaxy is equal to

$$\Delta M = M - M_1 = 4 \cdot 10^{10} M_0.$$

When the magnetic field is turned on, each particle will be affected by the Lorentz force (Fig. 2), directed along the rod and equal to

$$F_{\pi} = qvB = q\omega \frac{l}{2} B.$$

The force acting on the diopole as a whole is

$$F = 2F_{\pi} = q\omega lB.$$

⟦folio 37⟧

This force is constant in magnitude, but its direction in space changes: the vector $F$ rotates together with the rod with an angular velocity $\omega$. Consequently, the center of the diopole - point $O$ - will rotate with an angular velocity $\omega$ around a circle with radius $r$, which can be determined from Newton’s second law:

$$F = 2m\omega^2 r \Rightarrow r = \frac{F}{2m\omega^2} = \frac{qlB}{2m\omega}.$$

S. Edravkovic (SFRY)

F1172. The inner surface of the sphere is covered with a diffuse reflector with a reflectance coefficient of $r = 0,9$. The conditional distribution of light reflected by a diffuse reflector is described by Lambert's law:

$$\Delta N = \frac{N}{\pi} \cdot \cos \theta \cdot \Delta \Omega,$$

where $N$ is the total number of reflected backgrounds, $\Delta N$ is the number of reflected backgrounds in a small solid angle $\Delta \Omega$, making an angle $\theta$ with normal to the reflecting area. A precise light source flashes at the center of the sphere. What fraction of backgrounds will come out through the very small rejection present in the sphere?

Through rejection in the sphere, there will be released, firstly, those photons that will be rejected immediately immediately after the flash of the source, and secondly, those that will be rejected as a result of multiple reflections from the inner surface of the sphere.

Let us calculate what fraction $p$ of the backgrounds reflected from the plane $\Delta S'$ will fall on the plane $\Delta S$ (see figure). According to Lambert's law,

$$p = \frac{\Delta N}{N} = \frac{1}{\pi} \cos \theta \cdot \Delta \Omega,$$

where $\Delta \Omega = \Delta S \frac{\cos \theta}{AB^2}$ (with $\theta$ takes into account the area $\Delta S$ “visible” from point $A$). Since $AB = 2R$ cos $\theta$,

$$p = \frac{\Delta S}{4\pi R^2}.$$

Thus, the fraction of backgrounds that fall on the plane $\Delta S$ from the plane $\Delta S'$ depends only on the ratio of $\Delta S$ to the plane of the sphere and does not depend on the relative position of the selected planes. This in turn means that if the rejection plane is $s$, and the sphere plane is $S$, then after reflection from the sphere, a fraction of reflected backgrounds equal to $s/S$ will come out through the rejection. For evaluation, let's put $s/S = 0,1\%$.

Since the reduction in the number of backgrounds due to the surface of the sphere with stacks is two orders of magnitude greater than due to leakage through rejection (10% of backgrounds are lost at each reflection, and 0.1% are lost through rejection after each reflection), the reduction in the number of $N_0$ backgrounds in the sphere due to leakage through rejection can be neglected. then immediately after the flash (before the first reflection) $N_0 s/S$ backgrounds will be released through rejection, after the first reflection $-rN_0 s/S$ backgrounds, after the second $-r^2 N_0 s/S$, etc. The fraction of backgrounds that will eventually be released through rejection is equal to

$$\alpha = \frac{s}{S} (1 + r + r^2 + \dots + r^n) = \frac{s}{S} \frac{1}{1-r} = 1\%.$$

S. A. Khorozov
