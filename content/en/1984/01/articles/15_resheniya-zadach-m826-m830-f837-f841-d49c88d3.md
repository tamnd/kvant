---
id: 1984-1-resheniya-zadach-m826-m830-f837-f841-d49c88d3
issue: kvant_1984_1
year: 1984
number: "1"
title: Solutions to problems M826—M830; F837—F841
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 47
page_last: 53
page_labels: 45-51
tag: K6I8
lang: en
source: kvant_digital
extraction: vision
content_sha256: fa3a8af8a89a36c9f2642d94aff796807e08d9f9b1ffda80ab13f0dcf1cb7bef
prompt_sha256: draft-1
translated_from: content/ru/1984/01/articles/15_resheniya-zadach-m826-m830-f837-f841-d49c88d3.md
source_content_sha256: d41f615c70b9a8c3a3830c238cf50a9f1c864ec76e737a214e99802a7f1767a6
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 45⟧

and supply them with reasonable numerical values yourself and obtain a numerical answer.

E. I. Palchikov

P855. A charged plate is introduced all the way between the plates of a flat capacitor parallel to them at a distance $b$ from one of the plates (see figure Pisc. 4). The capacitor is connected to the poles of a battery of EMF $6$. Find the force acting on the charged plate if its charge is $q$. The weight of the plate is negligible. The area of the plates is $S$, the distance between them is $d$.

V. P. Borodin, A. P. Ershov

P856. Direct current circulates through a heating spiral of constant resistance. What will be the percentage change in the mean amount of heat emitted by the spiral per second if an alternative (sinusoidal) current, whose amplitude is 10% of the direct current’s value, is also sent through the spiral?

V. G. Dudnikov

P857. A shiny can has a dent which reflects light on a screen. A cooled liquid is poured into the can. The reflected signal noticeably weakens. Explain this phenomenon.

V. G. Dudnikov

Problem solutions

M826—M830; F837—F841

Answer: a) no, 6) yes. Let us first note that if the original numbers were 2, 2, 2 or 3, 3, 3, or in general any numbers greater than 1, then all subsequent numbers will be greater than 1, and the largest number in each new triple is always 1 less than the sum of the other two. This message allows you to use the last three numbers to restore all previous ones, except the very first one.

Indeed, let $a, b, c$ be in the triple to define $a \leq b \leq c$. Then $c = a + b - 1$ and the previous triple has the form $a, b, x$. The largest number in it can be considered $b$ (if $x > b$, then $x = a + b - 1 = c$). But then $b = a + x - 1$. Therefore, the triple $a, b, c$ with $a \leq b \leq c$ is obtained from the triple $a, b, b - a + 1$.

Using this rule, we will restore all the entries on the board, starting from the end:

(17, 1967, 1983) $\leftarrow$ (17, 1967, 1951) $\leftarrow$ (17, 1935, 1951) $\leftarrow$ ... $\leftarrow$ (17, 15, 31) $\leftarrow$ (17, 15, 3) $\leftarrow$ (13, 15, 3) $\leftarrow$ ... $\leftarrow$ (5, 7, 3) $\leftarrow$ (5, 3, 3).

According to our rule, the triple 5, 3, 3 must be preceded by the triple 1, 3, 3 containing 1, which is impossible. Therefore, 5, 3, 3 is the triple obtained in the first step. (Obviously, the remaining triples cannot arise at the first step.) It is clear that the triple 5, 3, 3 can be obtained from 3, 3, 3, but cannot from 2, 2, 2.

A. Berzins

M827. It is known that four synchronous ones on Fig. 1 are of equal size.
a) Prove that the three red four-levels on this figure are also of equal size.

We will need the following application part:

Lemma. Let $P$ be a point on side KL of triangle KLM. Then the ratio of the areas of triangles MKP and MPL is equal to

$$S_{MKP} : S_{MPL} = |KP| : |PL|.$$

(To prove it, it is enough to know that

⟦folio 46⟧

6) Find the area of ​​one quadrilateral if the area of ​​one blue triangle is 1.

Fig. 1.

Fig. 2.

Fig. 3.

M828 *. Is it possible in the cells of an infinite sheet of checkered paper so that the sum of the numbers in each rectangle of size 4 × 6 cells, the sides of which go along the grid lines, is equal to a) 10; b) 1?

a) Let us introduce the notation as in figure 1. Note that the triangles $A_0C_0$ and $AA_0C_1$ are equal in size (each of them is composed of the triangle $AA_0B_0$ and one of the synchronous triangles). These triangles have a common base $AA_0$, so their vertices $C_0$ and $C_1$ are equal to the line $AA_0$, that is, lines $AA_0$ and $C_1C_0$ are parallel. Likewise, $BB_0 \parallel A_1A_0$ and $CC_0 \parallel B_1B_0$. Let's look at the trapezoid $AA_0C_0C_1$ (Fig. 3). Its diagonals intersect at point $B_0$, and the continuations of the sides - at point $B$. These points lie on the line connecting the midpoints $D$ and $E$ of its bases $AA_0$ and $C_1C_0$. (Indeed, $B_0$ is the homothety center of triangles $B_0AA_0$ and $B_0C_0C_1$, and $B$ is the homothety center of triangles $BAA_0$ and $BC_1C_0$.) And since this line is parallel to $A_1A_0$, point $B_0$ is the midpoint of the segment $A_1A$. By lemma it follows that $S_{AB_0C_0} = S_{B_0A_1C}$. Therefore (see Fig. 1), the areas of the quadrilaterals $AB_0A_0B_1$ and $CA_0C_0A_1$ are equal. It is similarly proven that the third red quadrilateral $BC_0B_0C_1$ has the same area.

Think about whether the statement of this point of the problem will remain true if you require equality of the areas of only three angular synchronous triangles.

6) Answer: area of ​​the red quadrilateral $s = 1 + \sqrt{5}$. To create an equation for finding the original area s, we express the relation $|BC_1|:|C_1A|$ in two ways using the lemma:

$$|BC_1|:|C_1A| = S_{CBC_1}:S_{CC_1A} = (2s+2):(s+2) = S_{B_0BC_1}:S_{B_0C_1A} = (s/2):1.$$

(Explanation here requires only the equality $S_{B_0BC_1} = s/2$. As was shown above, the point $E$ is the midpoint of $C_0C_1$ (Fig. 3). From here, again using the lemma, it is easy to deduce that the triangles $B_0BC_1$ and $B_0BC_0$ are equal in size. And together they form a quadrilateral $BC_0B_0C_1$ of area s). So s satisfies the equation:

$$s^2 - 2s - 4 = 0,$$

whence $s = 1 + \sqrt{5}$.

B. I. Chinik, V. N. Dubrovsky

◆

Answer: a), 6) possible. In both cases, the desired arrangement can be obtained by combining two simpler arrangements.

a) Let’s put ones on parallel diagonals of the grid, spaced 4 cells apart from each other (horizontally or vertically), and put zeros in the remaining cells (Fig. 1, a). Then the sum of the numbers in each rectangle $4 \times 6$ will be equal to 6. This is the first arrangement. The second is arranged in the same way, but in it the distances between diagonals with units are 6 cells (Fig. 1, ​​6); for it, the sum of the numbers in any rectangle $4 \times 6$ is equal to 4. Now let’s superimpose one arrangement onto another and add up the numbers that fall into one cell; very indo, for the final arrangement the sum of the numbers is considered to be equal to 10.

6) Let's take the same arrangements as in point a), but on the diagonals along with the units - 6 cells (Fig. 1, 6); the sum of the numbers in any rectangle $4 \times 6$ will be equal to 4. Now let’s superimpose one arrangement onto another and add up the numbers that fall into one cell; very indo, for the final arrangement the sum of the numbers is considered to be equal to 10.

We invite readers, using the same ideas, to prove the following general statement: in the cells of an infinite flat lattice, integers can be arranged in such a way that the sum of the numbers in any rectangle of given dimensions takes on the same given value. The same is true for

⟦folio 47⟧

M829. Prove that for any 2m+1 distinct integers whose modulus does not exceed 2m−1, there are three numbers whose sum is equal to 0.

Let us prove the statement of the problem by induction on m.
When m=1 it is obvious (the edinventive triple of numbers that satisfies the condition is 0, 1 and -1).
Let us assume that it has been proven for 2m−1 numbers and consider any set A of 2m+1 numbers whose modulus does not exceed 2m−1. If it contains 2m−1 numbers whose modulus does not exceed 2m−3, then the statement follows from the induction hypothesis. Otherwise, the set A contains at least three of the numbers ±(2m−2) and ±(2m−1). By changing the signs of all numbers from A, if necessary, you can ensure that these are the numbers 2m−1, 2m−2, as well as −2m+1 (1st case) or −2m+2 (2nd case).

1st case. Let us divide all the numbers from 1 to 2m−2 into pairs that add up to 2m−1:(1, 2m−2), (2, 2m−4), ..., (m−1, m), and the numbers from 0 to −2m+1 into pairs that add up to −2m+1:(0, −2m+1), ..., (−m+1, −m). The result is 2m−1 pairs containing all 2m numbers of set A, except 2m−1. Therefore, although one pair is included in the set A and its constituent numbers add up to c −2m+1 or c 2m−1 to 0.

2nd case. Let us now consider m−2 pairs (1, 2m−3), (2, 2m−4), ..., (m−2, m) with the sum of the numbers 2m−2 and m pairs (0, −2m+1), ..., (−m+1, −m) with the sum of the numbers −2m+1. These 2m−2 pairs contain all the numbers of the set A, except 2m−1, 2m−2 and m−1, that is, 2m−1 numbers from A. Therefore, one of them again enters the set A and gives the zero sum c −2m+2 or 2m−1.

N. V. Kartatsov

M830 *. A student practices solving quadratic equations. Having written out some equation x²+p₁x+q₁=0, he solves it u, making sure that it has two roots, composes the second equation x²+p₂x+q₂=0, in which p₂ is the smaller and q₂ is the larger root of the first equation. From the second equation he makes up the third, if possible, etc.

a) Prove that this exercise cannot continue indefinitely.
b) Find the longest finite sequence of quadratic trinomials satisfying the equation satisfying the equation.

a) The solution is based on studying the signs of the coefficients of the equation. Let fₙ(x)=x²+pₙx+qₙ=0 be the th equation in the sequence under consideration. Let us prove the following statement:
if n≥3 and the equation fₙ(x)=0 is not the last one, then the numbers pₙ and qₙ are either both positive or both negative.
Using Vieta, we express the coefficients of the quadratic trinomial fₙ−1(x) in terms of pₙ and qₙ.
$$p_{n−1} = -(p_n + q_n), q_{n−1} = p_n q_n.$$

By condition pₙ<qₙ и pₙ−1<qₙ−1, то есть −(pₙ+qₙ) < <pₙqₙ или qₙ> −pₙ(1+qₙ). Adding to these inequalities the equation of the positive discriminant of the trinomial fₙx, we obtain the system
$$q_n > p_n$$
$$q_n > -p_n(1+q_n)$$
$$4q_n < p_n^2,$$

which is solved graphically in the margins. Our statement immediately follows from the graph. (However, it is not difficult to prove it algebraically: the case pₙ≥0≥qₙ is impossible (qₙ>pₙ); if pₙ≤0≤qₙ, then from (2) and (3) we obtain that qₙ²>pₙ²(1+qₙ)²>4qₙ(1+qₙ)² or 4qₙ³+7qₙ²+4qₙ<0, which is also impossible for qₙ≥0).

⟦folio 48⟧

Now let us assume that the number of equations in the sequence is at least five. If equation $f_5(x) = 0$ is not the last, then from the proven statement and correspondences (1) it follows that only two cases are possible: either $0 < p_5 < q_5$ and then $p_4 < 0 < q_4$, or $p_5 < q_5 < 0$ and then $0 < p_4 < q_4$, and $p_3 < 0 < q_3$. Both of these contradict our statement. Consequently, the equation sequence in question will always be declared, and no later than the fifth step.

6) Answer: The longest sequence of quadratic trinomials is 5.

From the solution to problem a) it is clear that it is impossible to compose more than a fifth of the equation according to the indicated law. The following example shows that a sequence of length 5 exists (it is written from the end - in the order in which it is more convenient to construct it using formulas (1)): $f_5(x) = x^2 - \frac{1}{2}x + 4$, $f_4(x) = x^2 - \frac{7}{2}x - 2$, $f_3(x) = x^2 + \frac{11}{2}x + 7$, $f_2(x) = x^2 - \frac{25}{2}x + \frac{77}{2}$, $f_1(x) = x^2 - 26x - \frac{1925}{4}$.

M. V. Sapir

F837. To change the speed of a part, a laser anemometer is used, in which moving particles are illuminated by two intersecting laser coefficients of the equation, which are neither the first, nor the second, nor the last in the sequence under consideration.

F837. To change the speed of a part, a laser anemometer is used, in which moving particles are illuminated by two intersecting laser coefficients of the equation, which are neither the first, nor the second, nor the last in the sequence under consideration.

Let us choose the coordinate system $XOY$ as shown in figure 2, and for an arbitrary point $a$ with coordinates $x$ and $y$ we find the phase difference $\Delta\varphi$ for two plane waves corresponding to our beams and arriving at this point. Let the phase of the first wave at the point with coordinates $x = 0$ and $y = 0$ be equal to $\varphi_0$, that is, $\varphi_1(0, 0) = \varphi_0$. The front of this wave is depicted on figure 2 straight line $N_{10}$, passing through the point (0; 0); the front of this wave passing through the point (x; y) is depicted by the straight line $N_1$. It is obvious that the path difference $\Delta_1$ for the rays corresponding to this wave arriving at points (0; 0) and (x; y) is equal to the distance between straight lines $N_{10}$ and $N_1$, that is, equal to the segment $OB$. From simple geometric considerations this segment and, therefore, $\Delta_1$ are found:

$$\Delta_1 = |OB| = x \sin \frac{\alpha}{2} + y \cos \frac{\alpha}{2}.$$

Therefore, the phase of the wave at point $(x; y)$ is equal to $\varphi_1(x, y) = \varphi_0 - \frac{2\pi}{\lambda} (x \sin \frac{\alpha}{2} + y \cos \frac{\alpha}{2})$,

where $\lambda$ is the wavelength.

In exactly the same way, let us put the phase of the wave corresponding to the second beam at a point with coordinates $(d; 0)$ equal to $\Psi_0$, that is, $\varphi_2(d, 0) = \Psi_0$ (here $d$ is the distance between points $O$ and $O'$). At figure 2, the front of the second wave passing through the point $(d; 0)$ is depicted by the straight line $N_{20}$, and the front of the second wave passing through the point $(x; y)$ is depicted by the straight line $N_2$. The path difference $\Delta_2$ is equal to the segment $O'C$, that is, equal to

$$\Delta_2 = |O'C| = (d - x) \sin \frac{\alpha}{2} + y \cos \frac{\alpha}{2}.$$

Therefore, the phase of the second wave at point $(x, y)$ is equal to

⟦folio 49⟧

$$\varphi_2(x, y) = \Psi_0 - \frac{2\pi}{\lambda} \left( (d - x) \sin \frac{\alpha}{2} + y \cos \frac{\alpha}{2} \right).$$

The phase difference $\Delta\varphi(x, y)$ between the waves of two beams at point $(x: y)$ is equal to

$$\Delta\varphi(x, y) = \varphi_1(x, y) - \varphi_2(x, y) = \varphi_0 - \Psi_0 - \frac{2\pi}{\lambda} \left( 2x \sin \frac{\alpha}{2} - d \sin \frac{\alpha}{2} \right).$$

As can be seen from the resulting expression for $\Delta\varphi(x, y)$, the phase shift between the waves of two light beams depends only on the coordinate $x$. Let the amplitudes of the waves of both beams be equal to each other and equal to $A$. The distribution of light intensity in the area where the beams intersect will have the form $I(x) = 2A^2(1 + \cos \Delta\varphi) = 2A^2 \left( 1 + \cos \left( \varphi_0 - \Psi_0 - \frac{2\pi}{\lambda} \left( 2x \sin \frac{\alpha}{2} - d \sin \frac{\alpha}{2} \right) \right) \right).$

This periodic function has a period $\Delta x$ along the $X$ axis, which is found from the condition

$$\frac{2\pi}{\lambda} 2 \cdot \Delta x \cdot \sin \frac{\alpha}{2} = 2\pi \Rightarrow \Delta x = \frac{\lambda}{2 \sin \frac{\alpha}{2}}.$$

If the particle size is less than $\Delta x$ and the particle moves uniformly with a speed $v$ along the $X$ axis, then the intensity of the light reflected from the particle and captured by the photocell will periodically change with time with a period $T = \Delta x/v$ or with a frequency $v = v/\Delta x$. Substituting the found expression for $\Delta x$, from the last equality we find:

$$v = \frac{\lambda v}{2 \sin \frac{\alpha}{2}} = \frac{0.63 \times 10^{-6} \cdot 320 \cdot 10^3}{2 \cdot 0.5} \text{ m/c} \approx 0.2 \text{ m/c}.$$

V. V. Mozhaev

F838. In 1844, the eminent mathematician and astronomer Bessel discovered that Sirius’s own (not related to the movement of the earth’s hablodator) movement follows approximately a sinusoid (Fig. 1). Maximum increase from straight path $a = 2,3''$, period $T = 50$ years. Bessel proposed (18 years later this was confirmed by direct observation) that the curvature of the path of Sirius is caused by the polishing of the satellite - a weaker star. Find the ratio of the mass $m$ of the satellite (Sirius $B$) to the mass $M_C$ of the Sun, if the mass of the main star (Sirius $A$) is $M = 2,3M_C$. It is known that the radius of the earth's orbit is visible from Sirius at an angle of $\beta = 0,376''$. Assume that the orbits are star-friend, and the plane

From the conditions of the problem it is clear that $a$ is the angular size of the radius of the Sirius orbit $A$ when observed from the Earth. Taking into account the smallness of the angles $a$ and $\beta$, we can write down the correspondence between the orbital radii of Sirius $A$ ($R$) and the Earth ($R_0$) (see Fig. 2):

$$\frac{R}{R_0} = \frac{a}{\beta}.$$

The components of the Sirius system revolve around the center of mass. The radius $r$ of the orbit of Sirius $B$ is

$$r = \frac{M}{m} R.$$

The distance between the components is thus equal to $R + r$.

Let's write the equation of motion (Newton's II law) for Sirius $A$ and for the Earth (Earth mass $m_0$, Earth year $T_0$):

$$M \left( \frac{2\pi}{T} \right)^2 R = G \frac{Mm}{(R+r)^2},$$

$$m_0 \left( \frac{2\pi}{T_0} \right)^2 R_0 = G \frac{M_C m_0}{R_0^2}.$$

Let's divide equation (3) by equation (4):

⟦folio 50⟧

$$\left(\frac{T_0}{T}\right)^2 \frac{R}{R_0} = \frac{m}{M_C} \frac{R_0^2}{(R+r)^2}.$$

It is convenient to introduce dimensionless quantities $\mu = \frac{m}{M_C}$, $\tau = \frac{T}{T_0}$, $\varrho = \frac{R}{R_0}$. Then equation (5), taking into account correspondence (2), is transformed to the form

$$\frac{(\mu + M/M_C)^2}{\mu^3} = \frac{\tau^2}{\varrho^3}.$$

No $M/M_C = 2,3$, $\varrho = \alpha/\beta \approx 6,1$ (corresponding to (1)), and $\tau = 50$. Hence,

$$\frac{(\mu + 2,3)^2}{\mu^3} = \frac{\tau^2}{(\alpha/\beta)^3} \approx 11.$$

The selection is:

$$\mu = m/M_C \approx 1.$$

V. E. Belochukin

F839. If a hexagonal pencil is placed on an inclined plane making an angle a from the horizontal surface, perpendicular to its generatrix (the line of intersection of the plane with the horizontal surface), the pencil will wobble. If you put it parallel to the generatrix, it will roll up. Under what conditions φ between the axis of the pencil and the generatrix of the inclined plane (Fig. 1) will the pencil be in equilibrium?

From the problem conditions it follows that the sliding friction coefficient $\mu$ of a pencil on an inclined plane satisfies the condition $\mu \geqslant \text{tg} \alpha$. Indeed, a pencil placed perpendicular to the generatrix is ​​in equilibrium, which means that $mg \sin \alpha = F_{\tau p}$, where $mg$ is the gravity force, $F_{\tau p}$ is the friction force. But $F_{\tau p} \leqslant \mu mg \cos \alpha$. Therefore, $mg \sin \alpha \leqslant \mu mg \cos \alpha$, hence $\mu \geqslant \text{tg} \alpha$.

This means that at any value of the angle $\varphi$ the pencil will not slide along the inclined plane.

The pencil may sometimes roll down at such an angle $\varphi_0$, when the vector of the gravity force “goes” beyond the area of ​​contact between the pencil and the inclined plane (at figure 2 this area is protected). To find this angle, we project the center of mass of the pencil onto the inclined plane - point $A$ on figure 2 - and mark the point of intersection of the vertical passing through the center of mass with the inclined plane - point $B$. Obviously, with different orientations of the pencil, if its center of mass remains in place, the points $A$ and $B$ will be motionless, and if the side of the hexagonal cross-section of the pencil is equal to $2a$, then $|AB| = 2a \sin \alpha$.

As long as point $B$ lies in the hexagonal area, the pencil will not roll.

Let us write down the conditions for the rolling part:

$$\frac{|AD|}{\cos \varphi_0} = |AB_0|,$$

or $$\frac{\alpha}{\cos \varphi_0} = a\sqrt{3} \text{tg} \alpha.$$

From here

$$\varphi_0 = \arccos \frac{1}{\sqrt{3} \text{tg} \alpha}.$$

Thus, if the angle $\varphi$ satisfies the condition

$$\arccos \frac{1}{\sqrt{3} \text{tg} \alpha} \leqslant \varphi \leqslant \frac{\pi}{2},$$

⟦folio 51⟧

The pencil is in balance. Obviously, the expression for the angle $\varphi_0$ makes sense under the condition $tg\alpha > \frac{1}{\sqrt{3}}$. The fact that a pencil placed parallel to the generatrix rolls down means that $tg\alpha > \frac{1}{\sqrt{3}}$ (show this yourself).

S. S. Krotov

F840. In a horizontal arrangement of a flat box measuring $10 \times 10$ cm, $N=1000$ small steel balls of mass $m=0,5$ m each lie randomly. The box begins to move at a speed of $v_0=10$ m/s perpendicular to one of the side walls. Considering the impacts of the balls on the walls of the box and others on others to be absolutely elastic, determine: a) what impulses the balls will transmit to each of the side walls in the first 10 seconds; b) what impulses do the walls receive over the next 10 seconds after the box is sharply braked.

When the box begins to move and hit the balls, they gain speed $2\vec{v}_0$, and after time $\tau_1 = a/v_0$ (a is the side of the box) all the balls begin to move (this time is actually somewhat less, since some balls may, due to mutual collisions, begin to move before the wall reaches them). After many collisions of the balls with each other and with the walls, the velocities of the balls will have the most arbitrary directions.

It is more convenient to consider what follows in the frame of reference associated with the box. In this system, the average speed of the ball (vector) is zero, and since the speed of the box does not change by condition, the total energy of the balls remains constant, and on average each ball will have energy $mv_0^2/2$. This is all very similar to the behavior of gas molecules flying through a small hole into an empty vessel and initially having uniformly directed velocities, and after some time they are already moving completely chaotic.

It remains to be seen whether the time specified in the task conditions (10 seconds) is long enough for the motion of the balls to become xotic. To do this, we find the approximate average time between collisions of the balls. We will assume that during this time $\tau_{cp}$ a ball of diameter $d$ moved in a straight line with a speed $v_0$. Then he “sweeps” the area $S = 2dv_0\tau_{cp}$, in which (on average) the center of only one ball falls out of the randomly located others. These remaining balls account for an area of ​​$a^2$ (a is the side of the box). This means that the conditions for the uniqueness of a collision in time $\tau_{cp}$ look like this:

$$\frac{a^2}{N-1} = 2dv_0\tau_{cp} \Rightarrow \tau_{cp} = \frac{a^2}{2dv_0(N-1)}$$

Let's find the diameter of the ball, knowing its mass and steel density:

$$d = \sqrt[3]{\frac{6m}{\pi q}} \approx 5 \cdot 10^{-4} \text{ м} = 0,5 \text{ мм}$$

So, the average time between collisions is $\sim 1 \cdot 10^{-3}$ s. It is clear that taking into account the time $\tau_1 = a/v_0 = 10^{-2}$ s, the “chaotization” time does not exceed 0.015-0.020 s, that is, it is a small part of the given interval of 10 s. Therefore, we can approximately assume that the balls are in xotic motion all the time. Then the number of impacts on each of the walls is the same. To count impacts, the movement of the ball perpendicular to the wall intersecting us is essential. Let's denote the speed of the ball in this direction $v_x$. The number of blows in a short time $\Delta t$ is equal to

$$\Delta n = \frac{v_x \cdot \Delta t \cdot a}{a^2} \cdot \frac{1}{2} N = \frac{v_x N}{2a} \cdot \Delta t.$$

This means that in time $T = 10$ s the number of blows is equal to
