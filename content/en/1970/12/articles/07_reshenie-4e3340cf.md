---
id: 1970-12-reshenie-4e3340cf
issue: kvant_1970_12
year: 1970
number: "12"
title: Solutions to problems M16—M20; F24—F28
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 36
page_last: 46
page_labels: 34, 36, 37, 38, 42, 43, 44
tag: Y83H
lang: en
source: kvant_digital
extraction: vision
content_sha256: 29adcadae36d6057cebda2a8e189edbb4989b67ef869e8eb35264bcfe929e61d
prompt_sha256: draft-1
translated_from: content/ru/1970/12/articles/07_reshenie-4e3340cf.md
source_content_sha256: c57bf6ba28335510d96377239002b96cac0c15fc3f55a499149028c68ba19b2a
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 34⟧

SOLUTION

M16. Prove that a polynomial $p(x)$ with integer coefficients, which takes the value 1 for three different integer values ​​of $x$, cannot have any integer roots.

Solution i.e. Note that for any polynomial $p(x)$ with integer coefficients and for any two integers $a$ and $b$ the difference $p(b) - p(a)$ is divisible by $b - a$, since for any natural number $m$ the difference $b^m - a^m$ is divisible by $b - a$:

$$b^m - a^m = (b - a) (b^{m-1} + b^{m-2}a + b^{m-3}a^2 + \ldots + ba^{m-2} + a^{m-1}).$$

If there are four integers $c_1, c_2, c_3$ and $a$ such that $p(c_1) = p(c_2) = p(c_3) = 1$ and $p(a) = 0$, then

$$p(c_1) - p(a) = p(c_2) - p(a) = p(c_3) - p(a) = 1,$$

and therefore each of the numbers $c_1 - a, c_2 - a, c_3 - a$ can only equal 1 or -1, which means that all these numbers cannot be different. This decision was added by A. Veselov from the village of Volchkovo, Kalinin region, I. Suprunenko from Minsk and other readers.

The beginning of the solution can be stated somewhat differently if you know what division of polynomials is *). Let us divide the polynomial $p(x)$ by “angle” by $x - a$, where $a$ is the integer root of the polynomial. Then $p(x) = (x - a)q(x)$, where $q(x)$ is also a polynomial with integer coefficients. Indeed, since the coefficient of the polynomial $x - a$ is equal to 1, then when we divide the polynomial by $x - a$ with a corner, all the coefficients of the polynomials will be obtained from the already existing operations of addition, subtraction and multiplication, that is, they will also be integers. The remainder is zero because $a$ is the root of the polynomial: $p(a) = 0$. Thus, $(a - c_1)q(c_1) = (a - c_2)q(c_2) = (a - c_3)q(c_3) = 1$, and further the reasoning is exactly the same as in the first solution.

M17. The peasant, approaching the fork of two roads, diverging at an angle of $60^\circ$, asked: “How to get to the village NN?” They answered him: “Go along the left road to the village N - this is eight miles from here - there you will see that a large level road goes off to the right at a right angle - this is exactly the road to NN. Or you can go the other way: now along the right road; when you reach the railway, it means you’ve walked half the way; here turn left and either follow the sleepers all the way to NN.” - “Well, which way will be shorter? - “It doesn’t matter whether it’s this way or that way, it makes no difference.” And the peasant went along the right road.

How many miles will he have to walk to NN? More than ten or less? What if you go straight from the fork to NN? (All roads are considered straight.)

Solution i.e. Let $A$ be the fork in the road, $B$ be the village $N$, $C$ be the village NN, $D$ be the point where the right road enters the railway track. According to the conditions (distances are measured in versts) $AB = 8$, $\angle A = 60^\circ$, $AD = DC$, $\angle B = 90^\circ$, $AB + BC = 2AD$. Let $AD = 2x$, $DH \perp AB$ and

*) See the article “Reduction of algebraic fractions” by A. N. Vilenkin («Kvant» No. 11).

⟦folio none⟧

DK⊥BC (Fig. 1). Then AH = x, KD = BH = 8 - x, AB + BC = 2AD = 4x, BC = 4x - 8, BK = DH = x√3, KC = |BC - BK| = |4x - 8 - x√3| and to fulfill all the conditions of the problem*) it is necessary and sufficient to fulfill the equality CK² + KD² = AD² or (4x - 8 - x√3)² + (8 - x)² = 4x²,

where 8 - x > 0 and 4x - 8 > 0, that is, 2 < x < 8. After transformation, we get (2 - √3)x² - 2(5 - √3)x + 16 = 0.

Let us denote the trinomial on the left side by f(x). It is easy to verify that the conditions 0 < x < 8 are satisfied only by the smaller root x₀ of the equation f(x) = 0 (Fig. 2). It can be written in the form

x₀ = (5 - √3 - √6√3 - 4) / (2 - √3) = 7 + 3√3 - √44 + 26√3.

The peasant will have to go the 4x₀ route. It's easier to figure out whether the number is greater than 10 or less directly from the equation. Since f(5/2) = 1/4(14 - 5√3) > 0, it is clear that x₀ > 5/2, that is, 4x₀ > 10. Let us show that the distance AC in the direction is less than 10. Indeed, the inequality √8² + (4x₀ - 8)² < 10 for 2 < x₀ < 8 is equivalent to: (4x₀ - 8)² < 36, 4x₀ - 8 < 6, x₀ < 7/2. As above, we are convinced that f(7/2) = 1/4(22 - 21√3) < 0, whence x₀ < 7/2, and therefore AC < 10.

The solution to this problem was sent to us by M. Preezer from Tomsk, A. Mikhailov from Ekibastuz and other readers.

S. Berkolaiko (Belgorod region) found a short proof that AB + BC > 10. In our notation it looks like this:

*) In fact, it is easy to prove that the base of the perpendicular K lies outside the segment BC (as shown in figure), but this is not used in our solution.

⟦folio 36⟧

by the cosine theorem from triangle ABD
$$BD^2 = 4x_0^2 + 64 - 16x_0;$$
on the other hand, the triangle inequality gives
$$BD < BC + CD = 6x_0 - 8,$$
where
$$4x^2 + 64 - 16x < (6x - 8)^2, 2x^2 - 5x > 0,$$
and taking into account $2 < x_0 < 8$ we obtain $x_0 > \frac{5}{2}$. A more accurate value of the distance $AB + BC$, according to the author of this letter, is: 11.044 versts.

Some readers misunderstood the conditions of the problem and believed that $\angle D = 90^\circ$, that is, that triangle ADC is equilateral and right-angled. This is, of course, not true.

M18. a) Prove that for any point $M$ of the circle circumscribed about a regular triangle ABC, one of the three segments MA, MB, MC is equal to the sum of the other two.
6) When equal, the circles $\gamma_1, \gamma_2, \gamma_3$ touch each other in pairs, and a circle $\gamma$ is described around them, which touches all three: $\gamma_1, \gamma_2$ and $\gamma_3$. Prove that for any point $M$ of circle $\gamma$, the tangent drawn from point $M$ to one of the three circles $\gamma_1, \gamma_2, \gamma_3$ is equal to the sum of tangents drawn from point $M$ to the other two circles.

Solution a) Let the point $M$ lie on the arc $AB$ of the circumscribed circle. Let's rotate triangle AMB around point $A$ by $60^\circ$ so that it takes position AKC (Fig. 3). Since angles MBA and MCA are equal (they rest on the same arc AM), point $K$ lies on segment MC. Since AM = AK and $\angle MAK = 60^\circ$ (by construction), the triangle AMK is equilateral, therefore MK = AM. So,
$$MA + MB = MK + KC = MC.$$

Another solution is obtained immediately from Ptolemy’s theorem, according to which in any cyclic quadrilateral the product of the diagonals is equal to the sum of the product of the opposite sides: if in the equality $MC \times AB = MA \cdot BC + MB \cdot AC$ we replace $BC$ and $AC$ by $AB$, we obtain $MC \times AB = (MA + MB) AB$, whence $MC = MA + MB$.

Our readers have solved this problem a lot. A. Braverman from Perm, A. Veselov from the Kalinin region, V. Metlitsky from Angarsk, N. Mirolyubova from Aktyubinsk, O. Khudaverdyan from Evrev even added several solutions.

6) Let us prove a more general fact. Let the centers of three circles of radius $r$ be the vertices of an equilateral triangle $C_0C_1C_2$ and $O$ the center of a circle of radius $a$ circumscribed around it. Then for any point $M$

⟦folio 37⟧

of a circle of radius $R = a + r$ with center $O$, the tangent drawn from the point $M$ to one of the two circles of radius $r$ is equal to the sum of the tangents drawn from the point $M$ to the other two circles. Note that for $r = 0$ the result of problem a) is obtained.

Let the radius $OM$ form angles $\alpha_k = \alpha_0 + k \cdot 120^\circ$ (Fig. 4) with the radii $OC_k$ ($k = 0, 1, 2$); then $MC_k^2 = R^2 + a^2 - 2Ra \cos \alpha_k^*$), and the square of the tangent drawn from the point $M$ to the corresponding circle is $MC_k^2 - r^2 = R^2 + a^2 - 2Ra \cos \alpha_k - (R - a)^2 = 2Ra (1 - \cos \alpha_k)$.

Therefore the tangents are equal to $2\sqrt{Ra} \sin \frac{\alpha_k}{2} \left( \sin \frac{\alpha_k}{2} \geq 0, \text{ поскольку } 0 \leq \alpha_k < 2\pi \right)$. It remains to check the equality $\sin \frac{\alpha_0}{2} + \sin \frac{\alpha_2}{2} = \sin \frac{\alpha_1}{2}$. It's already simple: $\sin \frac{\alpha_0}{2} + \sin \frac{\alpha_2}{2} = 2 \cos 60^\circ \cdot \sin \frac{\alpha_0 + \alpha_2}{4} = \sin \frac{\alpha_1}{2}$.

M. Preezer sent a solution to this problem using analytical geometry. A. Braverman sent us an interesting proof (using Ptolemy's theorem) of the following generalization of problem a): let $M$ be a point on the arc $A_1A_{2n+1}$ of a circle circumscribed about a regular ($2n + 1$)-gon $A_1A_2A_3 \dots A_{2n}A_{2n+1}$; Then

$$MA_1 + MA_3 + \dots + MA_{2n+1} = MA_2 + MA_4 + \dots + MA_{2n}.$$

(The solution is to write the Ptolemaic equations for the quadrilaterals $MA_1A_2A_3, MA_2A_3A_4, \dots, MA_{2n-1}A_{2n}A_{2n+1}, MA_{2n+1}A_{2n}A_1, MA_{2n+1}A_2A_1$, placing all terms containing $MA_{2k}$ on the left side of the equality, and all terms containing $MA_{2k+1}$ on the right side, and then adding all the equalities.) Consider how to prove this statement and a similar generalization of problem 6) using trigonometric functions.

M19. In an endless chain of faithful cells, each cell can be in one of two states: “rest” and “excitement”. If at a given moment a cell is excited, then it sends a signal that, after a unit of time (say, one millisecond), reaches both cells neighboring it. Each cell excites if and only if it receives a signal from one of its neighboring cells; if the signal arrives simultaneously from both sides, then they are extinguished, and the cell does not excite.

Let only one cell be excited at the initial time $t = 0$. How many cells will be in an excited state after 15 months? in 65 months? in 1000 months? in $t$ months?

What will happen if the chain is not infinite, but contains only $N$ cells connected in a circle - will the excitation remain infinite for a long time or will it die out?

Solution. It is enough to trace how the excitation from a single cell spreads above ten to fifteen clock cycles (Fig. 5) to notice the following patterns.

1. At time $t = 2^k$, where $k = 0, 1, 2, \dots$, only two cells are excited: $x = -2^k$ and $x = 2^k$.

2. At time $t = 2^k - 1$, $2^k$ cells from $x = -2^k + 1$ to $x = 2^k - 1$ are excited, with $x$ odd.

3. Let $0 \leq t < 2^k$. then at time $2^k + t$ there are twice as many excited cells as at time $t$.

To prove these regularities (by induction on $k$), we can use the fact that the “excitation waves” generated by each of the two cells active at time $2^k$ do not overlap until time $t = 2^{k+1} - 1$ and therefore each of them is structured exactly the same as the excitation wave from one cell at $t < 2^k$.

*) $\cos(2\pi - \alpha) = \cos \alpha$, so the formula is also valid for $\alpha > \pi$.

⟦folio 38⟧

Fig. 5.

Now it’s easy to answer the questions posed in the problem. After 15 months, as can be seen from figure, there will be 16 possible cells. After 64 = 2⁶ there will be two of them, so after 65 there will be four. For an arbitrary specific t, we can calculate f(t)—the number of possible cells at time t—by applying Property 3 several times in succession: each time we can subtract the greatest possible power of two from t; this will reduce f(t) by half. For example:

$$1000 - 2^9 = 1000 - 512 = 488, \quad f(1000) = 488 - 2^8 = 488 - 256 = 232, \quad = 2f(488) = 232 - 2^7 = 232 - 128 = 104, \quad = 4f(232) = 104 - 2^6 = 104 - 64 = 40, \quad = 8f(104) = 40 - 2^5 = 40 - 32 = 8, \quad = 16f(40) = 8 - 2^3 = 8 - 8 = 0, \quad = 32f(8) = 64.$$

f(t) is equal to 2ⁿ, where m is the number of units in the notation of the number t according to the double number system.

This rule is easy to prove by induction, and for the first t you can check it - on figure 5 on the right you can see the double expansions of the numbers t.

Probably, readers of the magazine who remember the article by D.B. Fuchs and M.B. Fuchs “Arithmetic of biomial coefficients**”, drew attention to the fact that the location of possible cells on figure 5 exactly coincides with the location of units in Pascal’s triangle modulo two (the image on the cover «Kvant» No. 6). Thus, we simultaneously solved the following problem: how many units are in the t-th row of Pascal’s triangle modulo 2, in other words, how many of the environment of biomial coefficients Cᵢᵢ (k = 0, 1,..., t) are odd?

The answer to the second question posed in the conditions of the task - what will happen if N cells are arranged in a circle? - depends, of course, not only on N, but also

***) (See I. M. Yaglom’s article “Number Systems” («Kvant» No. 6) or S. V. Fomin’s brochure of the same name.
***) («Kvant» № 6.

⟦folio none⟧

the life was not stretched, and the potential energy arrived at the moment when the maximum stretch came: in addition to the force of gravity and the tension force, the reaction force of the stand also acted on the body. The work done by this force is obviously not zero. This is after the body has come off the stand, we can assume that the total energy of the body and arrivals do not change.

Let's write down the expression for the energy coming from the load at the moment when the load comes off the stand. At this moment the load had a speed of $V = at$
$$a \sqrt{\frac{M(g-a)}{k \cdot a}}.$$

kinetic energy $\frac{MV^2}{2} = \frac{M^2(g-a)a}{k}$ and potential energy $Mg(x_0-x) = Mgx_0 - \frac{M^2(g-a)g}{k}$ (we consider the potential energy of the load to be zero when the arrival of the maximum is stretched).

Since at this moment the arrival was stretched to a length of $x = \frac{M(g-a)}{k}$, the potential deformation energy of the arrival is equal to $\frac{kx^2}{2} = \frac{M^2(g-a)^2}{2k}$.

Adding up the energy of the body and arrivals, we find that their total energy is equal to
$$W_1 = \frac{M^2(g-a)a}{k} + Mgx_0 - \frac{M^2(g-a)g}{k} + \frac{M^2(g-a)^2}{2k} = Mgx_0 - \frac{M^2(g-a)^2}{2k}.$$

At the moment when the arrival of the maximum is stretched, the speed of the load, and therefore its kinetic energy, are equal to zero. Therefore, the energy of the load and arrivals will be equal to $W_2 = \frac{kx_0^2}{2}$.

Writing down that $W_1 = W_2$, we obtain the equation
$$\frac{kx_0^2}{2} - Mgx_0 + \frac{M^2(g-a)^2}{2k} = 0.$$

Solving it, we find
$$x_0 = \frac{Mg}{k} \pm \frac{M\sqrt{a(2g-a)}}{k}.$$

The maximum stretching must be greater than its stretch when the body is in equilibrium, when the force of gravity $Mg$ acting on the body is balanced by the tension force $T = kx_1$: when passing through the equilibrium position, the body will have a certain speed, so it will definitely calculate it. Therefore, since $x_1 = \frac{Mg}{k}$ and $x_0 > x_1$, then
$$x_0 = \frac{Mg}{k} + \frac{M\sqrt{a(2g-a)}}{k}.$$

Does the second meaning of $x_0$ have physical meaning? Yes, but it gives not the maximum, but the minimum stretching gains when the body oscillates. If we consider that the potential energy of a body is equal to zero when stretching arrives by magnitudes $x_0$, then with minimal stretching comes, writing the law of conservation of energy, we would obtain the same equation as with maximum.

It is not difficult to determine the amplitude of body vibration. It is equal to the value of the roots of the equation for $x_0$, that is
$$\frac{2M\sqrt{a(2g-a)}}{k}.$$

If $a \geq g$, then the body will come off the stand as soon as the stand begins to move. Having written down the law of conservation of energy, we find that in this case the maximum stretching of the arrivals is equal to $\frac{2Mg}{k}$

The correct solution to this problem was sent by N. Fedin from Omsk.

⟦folio 42⟧

Fig. 8.

F25. If the potential of the anode of the photocell is higher than the potential of the cathode, then current $I_0=10\text{ ma}$ (so called) flows through the photocell. Otherwise, no current flows through the photocell. Neglecting the internal resistance of the batteries, find the voltage across the photocells in the circuits shown in figure 8 (resistance values ​​are indicated in figure in kilums).

Solved and e. Let us first consider the first scheme. Let's assume that no current flows through the photocell. In this case, current $I = \frac{200\theta}{1\text{ кОм} + 2\text{ кОм}} = \frac{1}{15}a$ will flow through resistances of 1 and 2 kilolumes. In this case, the voltage drop across a resistance of 2 kilometers is equal to $2 \cdot 10^3\text{ ом} \cdot \frac{1}{15}a \approx 133\theta$. This means that in this case the photocell cathode potential is $200\theta - 133\theta = +67\theta$. But the anode potential is $+100\theta$, that is, it is higher than the cathode potential. We have come to a contradiction, since in this case current must flow through the photocell. This means that current $I_0 = 10\text{ ma}$ flows through the photocell. Let's find the potential difference between the anom and the cathode. The potential of the anode is $+100\theta$ (we assume that the potential of point $P$ is zero). Therefore, we need to find the cathode potential. To do this, you need to determine the voltage drop across a resistance of 1 kilometer.

Assuming that the current through the resistances goes in the directions shown by the arrows on figure, and denoting them $I_1$ and $I_2$, we can write that $I_0 + I_2 = I_1$.

In order to find $I_1$ and $I_2$, we need to create another equation. Let's go around the circuit consisting of resistance and a source with e. d.s. 200$\theta$. Since the work of transferring a charge in an electric field is equal to the potential difference multiplied by the magnitude of the charge, we can write that

$$E - u_1 - u_2 = 0$$

or

$$E = I_1 \cdot R_1 + I_2 \cdot R_2.$$

Solving equations (1) and (2) together, we find that $I_1 \approx 73\text{ ma}$. This means that the cathode potential is $I_1R_1 = 73\theta$ and the potential difference between the anom and cathode is 27$\theta$.

Let's look at the second scheme in the same way. If we, as in the first case,

⟦folio 43⟧

Suppose that no current flows through the photocell, then we can assume that we have two chains, one of which consists of resistances of 1 and 3 kilolums connected in series, and the second - of resistances of 2 and 4 kilolums, with both chains connected in parallel and connected to a source with e.m. With. 100 $\beta$. Then, current $I = \frac{100\beta}{4 \cdot 10^3 \text{ ом}} = 2,5 \cdot 10^{-2} a = 25 \text{ мa}$ will flow through resistances of 1 and 3 kilolumes, and the voltage drop across a resistance of 1 kilometer will be equal to 25 $\beta$. This means that the anode potential is $\varphi_A = 100\beta - 25\beta = 75\beta$. Similarly, you can find the cathode potential. In this case it is equal to $33\frac{1}{3} \beta$. It turns out that the anode potential is higher than the cathode potential, and current must flow through the photocell.

We will assume that the current flows through all resistances from top to bottom, and through the photocell from left to right. Then we can write the following equations:

$$I_4 + I_0 = I_2,$$
$$I_1 - I_0 = I_3,$$
$$I_1R_1 + U_0 - I_4R_4 = 0,$$
$$E = I_1R_1 + I_3R_3,$$
$$E = I_2R_2 + I_4R_4.$$

Here $U_0$ is the voltage drop across the photocell.

Just like for the previous scheme, the first two equations in this system express the law of conservation of charge. Indeed, for example, at the point of connection of resistances of 4 kohms and 2 kohms and a photocell, per unit time charge $I_0 + I_4$ flows in, and $I_2$ flows out.

Solving this system, we obtain $U_0 \approx 20,8\beta$.

F26. Two horizontal half-planes, located at a height $h$ one above the other, smoothly transform into each other, as shown in figure 9. Along the upper half-plane at an angle $\alpha$ to the direction of descent, a small block moves at a speed $v$. How will it move along the lower half-plane?

Assume that the block is not undermined, that is, it moves without leaving the surface of the descent. Let's make a claim.

Fig. 9.

Solution. Let us decompose the speed of the block into two components: $v_2 = v \cos \alpha$ in the downhill direction and $v_1 = v \sin \alpha$ in the perpendicular direction (Fig. 10). Since no external forces act on the block in direction $v_1$, this component of the block’s velocity does not change. The component $v_2$ increases. Thanks to this, the speed of the bar also increases.

Let's find what speed $u$ the block will have after it reaches the lower half-plane

⟦folio 44⟧

bones. To do this we can use the law of conservation of energy
$$\frac{mv^2}{2} + mgh = \frac{mu^2}{2}.$$
Hence $u = \sqrt{v^2 + 2gh}$.

Now you can find the angle at which the block will move on the bottom
half-plane:
$$\sin \beta = \frac{v_1^2}{u} = \frac{v}{\sqrt{v^2 + 2gh}} \sin \alpha.$$
This solution was sent by G. Zaitsev, a 9th grade student from Gagra, GSSR.

F27. The hemispherical bell, lying tightly on the table, is poured through the hole.
at the top of the water Fig. 11. When the water reaches the hole, it lifts the bell and begins to flow out. Find the mass of the bell if its radius is $R$ and the density of water is $\rho$.

Solved and e. The force of pressure on the table is equal to the sum of the forces of gravity acting on the bell and water: $F = Mg + \frac{4}{3} \pi R^3 \rho g$. But at the moment when the water comes
lifts the bell and begins to leak, the bell itself does not press on the table. Therefore, the force of pressure on the table is equal to the water pressure multiplied by the area
base of the vessel. The water pressure on the table is the same at all points and
equals $\rho g R$, so $F = \rho g R \cdot \pi R^2$.

This means $\pi R^3 \rho g = Mg + \frac{4}{3} \pi R^3 \rho g$. Hence $M = \frac{1}{3} \pi R^3 \rho$.

An interesting idea for a solution was proposed by Anatoly Vorovlyansky from Gorky.

Suppose the bell is placed in a cylindrical vessel of radius and height. Let's fill this vessel with water and assume that the mass of the bell is negligible.
It is easy to report that since the pressure on the bell equipment and from the inside at all points
equal to each other (this follows from Pascal’s law and from the conditions that the bell is very thin),
then the balance of water will not be disturbed, if the bell is at all. Water pressure on the table
In this case it won't change either. But this means that the force of water pressure that we put into a cylindrical vessel acts in the same way as a bell, which means that the mass of the bell is exactly equal to the mass of the added water

$$M = (V \text{ цилиндра} - V \text{ полушара}) \rho = \left( R \pi R^2 - \frac{2}{3} \pi R^3 \right) \rho = \frac{1}{3} \pi R^3 \rho.$$
