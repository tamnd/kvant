---
id: 1980-11-resheniya-zadach-m605-m608-f608-f612-490ab0ef
issue: kvant_1980_11
year: 1980
number: "11"
title: Solutions to problems M605—M608; F608—F612
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 23
page_last: 28
page_labels: 21-26
tag: 61XD
lang: en
source: kvant_digital
extraction: vision
content_sha256: 25fac897ad4baba8576dfad29ed7fe836b4532b39c0e202f0761cc6d21e63971
prompt_sha256: draft-1
translated_from: content/ru/1980/11/articles/07_resheniya-zadach-m605-m608-f608-f612-490ab0ef.md
source_content_sha256: 89f79ece3ac68abfd63564f902240d67c09253d239f24e120026b7be2d04e513
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 21⟧

Problem solutions

M605. There are 2n+1 different points marked on the plane. Let us number them by numbers 1, 2, ..., 2n+1 and consider the following transformation of the R plane: first, symmetry is made with respect to the first point, then with respect to the second, etc., up to the (2n+1)th point.

a) Show that this transformation R has a single “fixed point” (a point that maps onto itself).

Let's consider all possible ways of naming as many as 2n+1 points (by numbers 1, 2, ..., 2n+1). Each such name corresponds to its own transformation of the plane R and its own fixed point. Let F be the set of fixed points of all these transformations.

6) Specify the set F for n=1.

c) What is the maximum and what is the minimum number of points that the set F can contain for each n=2, 3, ...?

We fix an arbitrary coordinate system.

Let the points A(x; y) and A*(x*; y*) be symmetrical with respect to the point A'(x'; y'). Then x' = (x+x*)/2, y' = (y+y*)/2, whence x* = 2x' - x, y* = 2y' - y.

Thus, a point with coordinates (x; y) with symmetry relative to a point with coordinates (x'; y') goes into a point with coordinates (2x' - x; 2y' - y).

With our transformation R, a point with coordinates (x; y) will go to a point with coordinates (-x+2x1 - 2x2+...+2x2n+1; y+2y1 - 2y2+...+2y2n+1), where (x_i; y_i) are the coordinates of the i-th of the given 2n+1 points.

a) For a fixed point (x; y) of the transformation R, these coordinates are determined uniquely from the condition

$$\begin{cases} -x+2x_1-2x_2+\dots+2x_{2n+1}=x, \\ -y+2y_1-2y_2+\dots+2y_{2n+1}=y \end{cases}$$

and are equal to (x_1-x_2+\dots-x_{2n}+x_{2n+1}; y_1-y_2+\dots-y_{2n}+y_{2n+1}) or

$$\left( \sum_{i=1}^{2n+1} (-1)^{i-1} x_i; \sum_{i=1}^{2n+1} (-1)^{i-1} y_i \right).$$

Statement a) has been proven.

6) Let first the given points X1, X2, X3 not lie on the same line. If points A1 after the symmetrical points X1, X2, X3 are mapped into themselves (see figure), then X1, X2, X3 are the midpoints of the segments A1A2, A2A3, A3A1, where A2 = S_{X1}(A1), A3 = S_{X2}(A2). This means that [A1X2], [A2X3], [A3X1] are the medians of triangle A1A2A3, so points A1, A2, A3 can be obtained from points X1, X2, X3 ready-made with center O and coefficient (-2). It is easy to see that if the given points X1, X2, X3 lie on a straight line, the answer is, in a sense, the same.

c) Looking at the expression (*), it is not difficult to say that in the set F there are no more points than the number of ways to generate from 2n+1 given points those n points whose abscissa in the expression (*) will be preceded by a minus sign, that is, no more than C2n+1. Obviously, this estimate is exact (take, for example, 2n+1 points on the same line with integer coordinates 1, 2, 2^2, ..., 22n).

Let us now estimate the number of fixed points. Let us project these 2n+1 points onto a straight line so that no two points fall into one. On this line we enter coordinates and change the points in ascending order of coordinates: x1 < x2 < ... < x2n+1. Let's put n minus in front of the first n numbers and consider the sum - x1 - x2 - ... - xn + xn+1 + ... + x2n+1; it will correspond to some fixed point from our set F. Next, we perform the following operation: choose a pair of numbers x_i and x_i+1 such that x_i is preceded by a minus, and x_i+1 is preceded by a plus, and change their signs (in the first step, estimatedly, i=n). Each such operation leads to a sum corresponding to a fixed point from the set F, and since after each operation the sum decreases, all these fixed points are different. We can perform all such operations (regardless of their order) n(n+1), which already gives us

⟦folio 22⟧

M606. The function $f$ is such that for all real $x$ $f(x+1)+f(x-1)=\sqrt{2}f(x)$. Prove that $f$ is a periodic function.

M607. a) Cut the square into equilateral trapezoids. b) Cut an equilateral right triangle into equilateral trapezoids. c) Prove that any polygon can be cut into equilateral trapezoids.

Fig. 1.

Fig. 2. Fig. 3.

$n(n+1)+1$ fixed points. This means that there are at least $n(n+1)+1$ points in $F$. Exactly this number of fixed points will be obtained if, for example, we again take $2n+1$ points on a straight line with integer coordinates $-n$, $-(n-1)$, ..., $-1$, 0, 1, 2, ..., $n-1$, $n$. With all possible ways of placing $n$ “minuses” in front of some of them, the maximum value of the sum of these numbers is $2 \cdot (1+2+\dots+n)=n(n+1)$, the minimum value is $-n(n+1)$, and the sum can take any even value between the numbers $-n(n+1)$ and $n(n+1)$ - a total of $n(n+1)+1$ values.

I. Klumova, A. Talai

◆
By condition, for any real $x$ the equality
$$f(x+2)+f(x)=\sqrt{2}f(x+1)=\sqrt{2}(\sqrt{2}f(x)-f(x-1))=
=2f(x)-\sqrt{2}f(x-1),$$
that is
$$f(x+2)=f(x)-\sqrt{2}f(x-1).$$
Pozny
$$f(x+4)=f(x+2)-\sqrt{2}f(x+1)=
=f(x)-\sqrt{2}(f(x-1)+f(x+1))=-f(x).$$
Hence,
$$f(x+8)=-f(x+4)=f(x)$$
for any $x \in \mathbb{R}$, so $f$ is a periodic function whose period is 8.
Note that functions that satisfy the original equation exist, for example, $f(x)=\sin \frac{\pi x}{4}$.

E. Turkevich

◆
Note that a regular triangle is easily divided into equilateral trapezoids (Fig. 1); Therefore, it is enough to bring the partition to a regular triangle.
Now we can propose our next task:
a) The required partitions can be, for example, such as in Figures 2, 3.
b) An opposite right triangle can be cut, for example, as shown in Figures 4 and 5. Each of these partitions gives new ways of partitioning a square.
Other ways of cutting these figures are obtained from point c).
b) It is obvious which polygon is divided into convex polygons, and which convex polygon is cut into triangles by diagonals coming from any vertex. Any triangle can be divided into two right-angled triangles with a height lowered to one of the sides; finally, which right triangle can be cut into two equilateral triangles connected by the hypotenuse to the vertex of the right angle.
It is enough for Pozny to prove the statement for an arbitrary equilateral triangle.
For brevity, we will call an equilateral triangle with angle $\alpha$ at the base a “$\alpha$-triangle”.
Let's consider three cases.
1°. $30^\circ \leq \alpha < 60^\circ$. The required cutting is shown in figure 6.
2°. $0 < \alpha < 30^\circ$. As can be seen from figure 7, if a $2\alpha$-triangle can be cut, then a $\alpha$-triangle can also be cut. From here and from 1° we successively obtain cut equilateral triangles with angles at the base
$15^\circ \leq \alpha < 30^\circ$, $7,5^\circ \leq \alpha < 15^\circ$, $3,75^\circ \leq \alpha < 7,5^\circ$...

⟦folio 23⟧

M608. On the checkered paper (side of square 1) there is drawn a p-bar, all sides of which lie on the grid lines and have an odd length.
a) Prove that n is divisible by 4.
b) Prove that for n=100 the area of ​​this n-sleeve is necessarily odd. Find out what the parity of the area is for each n.

Since any α, 0°<α<30°, falls very much into one of the indicated intervals, we obtain that for α<30° any α-triangle can also be cut in the required way.

3°. 60°≤α<90°. The proof is similar to case 2° (Fig. 8). Obviously, $\widehat{BAB'}=45^\circ-\frac{\alpha'}{2}<45^\circ$ ($B'$ is the center of the circumcircle of triangle ABC), and therefore triangles BAB' and BCB' are “cuttable”.

Continuing this process for triangles AB'C (point B''), AB''C, ..., we will obviously sooner or later obtain an equilateral triangle with a base angle less than 60°.

V. Lev

◆ a) Obviously, this polygon has as many horizontal sides as vertical ones, because the horizontal and vertical sides intersect. This means n=2k, where k is the number of vertical (or horizontal) sides. It is also obvious that the sum of the lengths of the vertical sides is even, since we “go down” by the same amount as we “go up”. But the length of each segment is odd; this means that the vertical sides are an even number, that is, k=2m. Therefore n=4m is divisible by 4.
b) Let's introduce a coordinate system so that the Ox and Oy axes contain the bottom-most and left-most sides of our 4m-gon. Then the coordinates of the vertices of our polygon will be equal
$ (a_1; b_1), (a_2; b_1), (a_2; b_2), (a_3; b_2), (a_3; b_3), ..., (a_{2m-1}; b_{2m-1}),$
$ (a_{2m}; b_{2m-1}), (a_{2m}; b_{2m}), (a_1; b_2m),$
where $a_i, b_i$ are non-negative integers, and all differences $a_{i+1}-a_i, b_{i+1}-b_i$ ($i=1, 2, ..., 2m$) are odd; here and below $a_{2m+1}=a_1, b_{2m+1}=b_1$. It is easy to express the area S of the polygon through these coordinates, presenting it as the sum and difference of the areas of rectangles $|a_{i+1}-a_i| \times b_i$:

$$S = \left| \sum_{i=1}^{2m} (a_{i+1}-a_i) b_i \right|.$$

Since all differences $a_{i+1}-a_i$ are odd, the sum S has the same parity as the sum $b_1+b_2+\dots+b_{2m}$. The parities of the numbers $b_1, b_2, ..., b_{2m}$ are intersecting (since all differences $b_{i+1}-b_i$ are odd), so all m sums $b_1+b_2, b_3+b_4, ..., b_{2m-1}+b_{2m}$

⟦folio 24⟧

F608. A spacecraft with a mass of $M=12$ t moves around the Moon in a circular orbit at an altitude of $h=100$ km. To transfer to the landing orbit, the jet propulsion unit is turned on for a short time. The speed of gases leaving the rocket's solarium is $u = 10^4$ m/s. The radius of the Moon is $R_\pi = 1,7 \cdot 10^3$ km, the free acceleration at the surface of the Moon is $g_\pi = 1,7$ m/s².
1) What amount of fuel must be consumed so that when the braking motion is activated at point A of the ship's trajectory, it descends to the Moon at point B (Fig. 1)?
2) In the second variant of landing, an impulse is given to the ship at point A in the direction of the center of the Moon in order to transfer the ship into an orbit touching the Moon at point C (Fig. 2). How much fuel should be consumed in this case?

Fig. 1.

Fig. 2.

1) When a ship moves around the Moon in a circular orbit, the centrostrimental acceleration of the ship is imparted by the force of gravity. Because

$$\frac{Mv^2}{R} = \gamma \frac{MM_\pi}{R^2},$$

where $v$ is the speed of the ship in a circular orbit, $M_\pi$ is the mass of the Moon and $R = R_\pi + h$ is the radius of the ship's orbit. From this equation we find

$$v = \sqrt{\gamma \frac{M_\pi}{R}} = \sqrt{g_\pi \frac{R^2_\pi}{R}} \approx 1,65 \cdot 10^3 \text{ м/c.}$$

After changing the speed of the ship at point A, the ship will move to an elliptical orbit. Let us denote by $v_A$ and $v_B$ the speeds of the ship, respectively, at points A and B of this orbit. According to the law of conservation of energy

$$-\gamma \frac{M_\pi M_1}{R} + \frac{M_1 v_A^2}{2} = -\gamma \frac{M_\pi M_1}{R_\pi} + \frac{M_1 v_B^2}{2}$$

(1)

$-\gamma \frac{MM_\pi}{R}$ is the potential energy of a body of mass $M$ in a circular orbit in the gravitational field of the Moon, $M_1$ is the mass of the descent vehicle); according to the law of conservation of angular momentum (or, what is the same, according to Kepler’s second law)

$$v_A R = v_B R_\pi.$$

(2)

Solving equations (1) and (2) together, we find

$$v_A = \sqrt{2\gamma \frac{M_\pi R_\pi}{(R_\pi + R)}} = v \sqrt{\frac{2R_\pi}{R + R_\pi}}.$$

Therefore, to transition from a circular orbit to an elliptical one at point A, the speed must be changed by

$$\Delta v = v - v_A = v \left( 1 - \sqrt{\frac{2R_\pi}{R + R_\pi}} \right) = v \left( 1 - \sqrt{\frac{2R_\pi}{h + 2R_\pi}} \right) = v \left( 1 - \frac{1}{\sqrt{1 + \frac{h}{2R_\pi}}} \right) = v \frac{h}{4R_\pi} \approx 24 \text{ м/c.}$$

Since the propulsion system is in circular time, we can assume that the momentum of the “landing vehicle - fuel” system is conserved. Therefore, we can use the law of conservation of momentum, which gives

$$(M - m) \Delta v = mu,$$

where $m$ is the mass of the propellant. From here

$$m = \frac{\Delta v}{\Delta v + u} M \approx \frac{\Delta v}{u} M \approx 29 \text{ кг.}$$

2) In the second case, the speed $v$ of the ship at point A changes by values ​​$\Delta v$, and the speed $v_A$ in the new orbit is the same as $v_A^2 = v^2 + (\Delta v)^2$ (since $\Delta v \perp v$).

From the law of conservation of energy (an expression similar to (1), with $v_B$ replaced by $v_C$) and the law of conservation of angular momentum ($v_A R = v_C R_\pi$) we find

$$\Delta v = \sqrt{g_\pi \frac{(R - R_\pi)^2}{R}} = \sqrt{g_\pi \frac{h^2}{R_\pi + h}} \approx 97 \text{ м/c.}$$

⟦folio 25⟧

The mass of fuel consumed in this case is equal to
$$m \approx \frac{\Delta v}{u} M \approx 116 \text{ кг}.$$
I. Slobodetsky

F609. The part, made of aluminum, is weighed on an analytical balance using brass.zip. During one weighing, the air inside the scale is dry, and during the other, it is wet, the water vapor pressure in which is equal to $p_{B,\pi} = 15,2$ mmHg. Art. The external pressure ($p = 760$ mm Hg) and temperature ($t = 20^\circ C$) of the air are the same in both cases.
At what mass of the part can the difference in the scale readings be replaced if their color value is $m_0 = 0,1$ m? Density of aluminum $Q_1 = 2,7 \text{ e/cm}^3$, brass $Q_2 = 8,5 \text{ e/cm}^3$.

Let us write down the equilibrium conditions for weighing in dry air:
$$m_1 g - F_{A1} = m_2 g - F_{A2}.$$
Here $m_1 = Q_1 V_1$ is the mass of the part ($V_1$ is its volume); $m_2 = Q_2 V_2 g$ — mass of weights ($V_2$ — their volume); $F_{A1} = Q_{c,B} V_1 g$, $F_{A2} = Q_{c,B} V_2 g$ - Archimedean forces acting respectively on the part and on the weight from the side of dry air ($Q_{c,B}$ - density of dry air). Thus, in a state of equilibrium when suspended in dry air
$$(Q_1 - Q_{c,B}) V_1 - (Q_2 - Q_{c,B}) V_2 = 0.$$ (1)

In order to be able to detect the deviation of the scales from equilibrium in humid air (with the same mass of weights), the following conditions must be met:
$$(Q_1 - Q_{c,B}) V_1 - (Q_2 - Q_{c,B}) V_2 \geq m_0,$$ (2)

where $Q_{c,B}$ is the density of moist air.
FROM (1) and (2) we find the conditions that the mass of the part must satisfy:
$$m_1 = Q_1 V_1 \geq m_0 Q_1 \frac{Q_2 - Q_{c,B}}{(Q_{c,B} - Q_{c,B}) (Q_2 - Q_1)}.$$ (3)

Let us express the quantities $Q_{c,B}$ and $Q_{c,B}$ through the parameters specified in the conditions of the problem - $T = 293$ K, $p \approx 10^5$ Pa, $p_{B,\pi} \approx 2 \cdot 10^3$ Pa.

From the equation of gas state $pV = \frac{m}{M} RT$ it follows that
$$Q_{c,B} = \frac{p_{c,B} M_{c,B}}{RT} = \frac{p M_{c,B}}{RT},$$
where $M_{c,B} = 29 \cdot 10^{-3}$ kg/mol is the molar mass of dry air. The density of moist air is
$$Q_{c,B} = Q'_{c,B} + Q_{c,\pi},$$
where $Q'_{c,B}$ is the density of dry air present in volume $V$ of moist air; $Q_{c,\pi}$ is the density of water vapor present in volume $V$ of moist air. According to the equation of gas state
$$Q_{c,\pi} = \frac{p_{c,B} M_{c,B}}{RT},$$
$$Q'_{c,B} = \frac{(p - p_{c,B}) M_{c,B}}{RT},$$
where $M_{B,\pi} = 18 \cdot 10^{-3}$ mg/mol is the molar mass of steam, $(p - p_{c,B})$ is the partial pressure of dry air in the volume $V$ of moist air. Thus,
$$Q_{c,B} = \frac{(p - p_{c,B}) M_{c,B}}{RT} \approx 43,2 \text{ г}.$$

V. Belonukin

F610. In the Soviet-French experiment on optical location of the Moon, pulsed radiation from a ruby ​​laser at a wavelength of $\lambda = 0,69$ µm was directed using a telexan with a mirror diameter of $D = 2,6$ m onto the lunar surface. A reflector was installed on the Moon,

1) The accuracy of setting the optical axis of the telexan is determined by the diffraction divergence of the beam:
$$\delta \varphi \approx \frac{\lambda}{D} = 2,6 \cdot 10^{-7} \text{ рад} = 0,05''.$$
2) The radius of the light spot on the Moon is $\frac{\lambda}{D}$. Therefore, the fraction of laser energy hitting the reflector is
$$K_1 = \frac{d^2}{4(L\lambda/D)^2} = \left(\frac{dD}{2\lambda L}\right)^2.$$

⟦folio 26⟧

which worked as an ideal mirror with a diameter of $d = 20$ cm, reflecting light exactly in the opposite direction. The reflected light is captured by the same telescope and focused on a photodetector.

1) With what accuracy should the optical axis of the telescope be set in this experiment?

2) Neglecting light losses in the Earth's atmosphere and in the telescope, estimate what fraction of the laser light energy will be detected by the photodetector after reflection from the Moon.

3) Can a reflected light pulse be detected by the naked eye if the sensitivity of the eye is equal to $n = 100$ light quanta, and the energy emitted by the laser during the pulse is equal to $W = 1$ J?

4) Evaluate the benefit that comes from using a reflector. Assume that the surface of the Moon scatters $\alpha = 10\%$ nadauce of light uniformly into a solid angle $2\pi$ cf. The distance from the Earth to the Moon is $L = 380 \cdot 10^3$ km. The diameter of the laser screen is set to $d_{3p} = 5$ mm. Planck's constant $h = 6,6 \cdot 10^{-34}$ J・s.

F611. The acrobat, being on the side surface of a cylinder lying on a very rough floor, moves through positions and moves at a constant speed to the right. Considering the friction coefficient of the acrobat's boots on the surface of the cylinder to be equal to $\mu$, determine the limiting angle $\alpha$ that can be made with the vertical radius of the cylinder drawn to the point at which the acrobat is located. What will be the friction between the acrobat's boots and the cylinder?

The forces acting on the acrobat are the gravity force $\vec{mg}$, the friction force $\vec{F}_{\tau p}$ and the normal reaction force $\vec{N}$ (see figure). According to the conditions of the problem, the acrobat moves at a constant speed. Therefore, according to Newton's II law, the vector sum of the forces $\vec{mg}, \vec{F}_{\tau p}$ and $\vec{N}$ is equal to zero. Let us write this condition in projections on the axes $X$ and $Y$, directed in the same way as on figure (the coordinate system $XOY$ moves to the right at the same speed as the acrobat; the origin coincides with the point at which the acrobat is located):

in projections onto the axis $X$ —
$$mg \sin \alpha - F_{\tau p} = 0;$$

in projections onto the axis $Y$ —
$$N - mg \cos \alpha = 0.$$

Considering that $F_{\tau p} \leq \mu N$, from (1) and (2) the angle $\alpha = \alpha_0$ is found:

$$\alpha_0 = \arctg \mu.$$

The magnitude of the friction force at $\alpha = \alpha_0$ is equal to
$$F = mg \sin \alpha_0 = mg \frac{\mu}{\sqrt{1 + \mu^2}}.$$

S. Krotov
