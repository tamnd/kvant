---
id: 1973-3-resheniya-zadach-m151-m154-f170-f175-b4297a3a
issue: kvant_1973_3
year: 1973
number: "3"
title: Solutions to problems M151—M154; F170—F175
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 39
page_last: 56
page_labels: 37, 38, 39, 40, 41, 43, 45, 46, 47, 48, 49, 51, 53, 54
tag: IO8C
lang: en
source: kvant_digital
extraction: vision
content_sha256: 6c25b62132f10392c0722890daff8b1c32838fe17d7b57718b02ade55242aad8
prompt_sha256: draft-1
translated_from: content/ru/1973/03/articles/10_resheniya-zadach-m151-m154-f170-f175-b4297a3a.md
source_content_sha256: 6049be7985fbc6e1d672eb567d5228cea02028bdedc9fc65ff3ed4315fdd5817
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 37⟧

Problem solutions

M151—M154; F170—F175

M151. We divide each of the nine primos into two quadrangles, the area of ​​which is in the ratio 2:3. Prove that at least three of these nine prims pass through the same point.

If a straight line intersects two adjacent sides of a square, then obviously it cuts the square into a triangle and a fifth nikk. But according to the condition of each of the 9 primos, the square is cut into quadrangles. Consequently, such a straight line intersects two opposite sides of the square, that is, it divides the square into two trapezoids (or two rectangles), the bases of which lie on the sides of the square, and the heights are equal to the side of the square. It is clear that the straight line divides the “midline” of the square in the ratio 2:3 (Fig. 1), since the ratio of the areas of these trapezoids is equal to the ratio of their midlines (lying on the midline of the square).

On the middle line of the square there are two points dividing it in a ratio of 2:3. Looking at the other two opposite sides of the square, we will find two more points on the middle line parallel to them.

As a result, we get that each of the 9 data points passes through one of the 4 specified points (Fig. 2).

Of course, at least three primos pass through one of these points. Indeed, if no more than two prims passed through each point, then in total there would be no more than 2.4 = 8 prims, which contradicts the conditions.

The reader points out a natural generalization of the problem: instead of a square, we consider a 2n-gon whose opposite

Fig. 1. Fig. 2.

opposite sides are parallel, and straight lines, each of which divides this 2n-gon into two (n + 2)-gons of fixed area.

Note that if two sides of a polygon are not parallel, then the straight lines, each of which intersects these sides and cuts off the given plane, will no longer pass through one point (prove it!), but will touch some hyperbola.

B. M. Ivlev

M152. Let a, b, m, n be natural numbers, and a is coprime to b and a > 1. Prove that if a^m + b^m is divisible by a^n + b^n, then m is divisible by n.

It turns out that the statement of the problem can be replaced by a more precise one. We will prove not only that m is divisible by n, that is, m = kn, where k is some integer, but also that k is a necessarily odd number. We will split the proof into three parts.

1°. Let m = kn, where k is an odd number. Then a^m + b^m is divisible by a^n + b^n.

2°. Let m = kn + r, where k is an odd number and 0 < r < n. Then a^m + b^m is not divisible by a^n + b^n.

3°. Let m = ln + r, where l is an odd number and 0 ≤ r < n. Then a^m + b^m is not divisible by a^n + b^n.

Note that by proving 1°, 2°, 3°, we will prove even more than in general, namely: for polychoba a^m + b^m is divisible by a^n + b^n, it is necessary and sufficient that m equals kn, where k is odd. In the proof of 2° and 3° we will use the fact that a and b are coprime, but in the proof of 1° they are not.

Proof 1°. Let c and d be arbitrary integers. Then c^k + d^k, where k > 0 is odd, is divisible by c + d. (Hence, for c = a^n and d = b^n, we get 1°.) Indeed, as is easy to see, for odd k

c^k + d^k = (c + d) (c^{k-1} - c^{k-2} d + ... - cd^{k-2} + d^{k-1}).

Proof 2°. Let's write a^m + b^m in the form a^{kn+r} + b^{kn+r} = a^r (a^{kn} + b^{kn}) + b^{kn} (b^r - a^r).

According to 1°, the first term is divisible by a^n + b^n, but the second term is not divisible by a^n + b^n, since b^{kn} is coprime to a^n + b^n and 0 < |b^r - a^r| < a^n + b^n. Therefore, the sum is not divisible by a^n + b^n.

Proof 3°. If l is an even number, then k = l - 1 is odd. Let's write a^m + b^m as a^{ln+r} + b^{ln+r} = a^{kn+r} (a^{kn} + b^{kn}) + b^{kn+r} (b^r - a^r).

The first two terms are divisible by a^n + b^n, and the last, as above, is not de-

⟦folio 38⟧

pours. Indeed, $b^{kn}a^n$ is coprime with $a^n + b^n$ and $0 < b^r + a^r < a^n + b^n$.

Give examples yourself showing that without the mutual primeness assumption of $a$ and $b$, statements $2^\circ$ and $3^\circ$ are false.

V. L. Gutenmacher

**M153. Two zerraim to the next zerra. We call one a number, and the other we insert it, at our discretion, together with one of the asterisks in the following difference:**

$$\begin{array}{c}
* \quad * \\
- \quad * \quad *
\end{array}$$

Then we call the first one another number and poppy dallee 8 times until all the asterisks are replaced with numbers. The one who calls the numbers strives to ensure that the difference is as large as possible, and the second - to make it as small as possible. Prove that a) the second one can consider the numbers in such a way that the difference cala is no more than 4000, regardless of what numbers the first one calls;
b) the first one can name the numbers so that the difference is not less than 4000, regardless of where the second one considers the number.

Let us present a solution for the general case when each line contains not 4, but $n$ asterisks. Let us prove that if there are opponents in the game, the difference turns out to be equal to $4.10^{n-1}$.

a) Strategy for the second game.

If the first number called by the first player is 4 or less, the second player puts it together with the highest digit of the minuend. After that, as soon as the first player names a number other than 0, the second player fills in the highest digit of the subtrahend. The difference turns out to be no more than $499 \ldots 9 - 100 \ldots 0 < 4.10^{n-1}$. If the first player, starting from the second move, calls 0 each time, then the difference will also be less than or equal to $4.10^{n-1}$.

If the first player starts with the number 5, 6, 7, 8 or 9, the second puts it in place of the most significant digit of the subtrahend, and then takes the most significant digit of the minuend of the first named number, other than 9. Further, if all subsequent numbers are nines, then the difference will also be not exceeding $4.10^{n-1}$.

b) Strategy for the first game.

As long as the most significant digits of the minuend and subtrahend remain free, the first player calls the numbers 4 and 5. Starting from the moment when the second player fills one of the two highest digits, and until the end of the game, the first player calls 0 if the equal digits of the minuend are filled, and 9 otherwise. It remains to clarify in which cases the first player calls number 4, and in which cases - number 5.

Before the first player makes his next move, we keep track of zeros in all unfilled digits. If after this the difference turns out to be non-negative, he announces the number 4, but if the difference is negative - the number 5.

Let us prove that the described strategy of the first player allows him to make a difference no less than $4.10^{n-1}$.

If the most significant digit of the minuend is occupied by digit 4, then the most significant digit of the minuend will be digit 9:

$$\underbrace{900 \ldots 0}_{n} - \underbrace{499 \ldots 9}_{n} > 4.10^{n-1}.$$

If the most significant digit of the minuend is filled with digit 5, then the most significant digit of the minuend will be filled with digit 0, and

$$\underbrace{500 \ldots 0}_{n} - \underbrace{099 \ldots 9}_{n} > 4.10^{n-1}.$$

Let's assume that the first player calls the number 4, and the second player fills in the most significant digit of the minuend. Before this move, the difference was non-negative, after the move it increased by $4.10^{n-1}$ and did not change anymore, since for all subsequent moves the first player calls 0.

It remains to consider the case when the first player names the number 5, and the second player fills in the highest digit of the subtrahend. Divide the numbers, called the first player, into series, combine identical numbers into a series, and match them in a row. Let us assume that the second player does not place identical numbers next to each other, otherwise they could be crossed out and not considered in further reasoning. Let us now prove that each series of fours ends like this:

$$\begin{array}{c}
* \ldots * a_m a_{m+1} \ldots a_n \\
* \ldots * 4 b_m b_{m+1} \ldots b_n.
\end{array}$$

The fact that the first series ends like this is very disappointing. Let the sth series of fours end in this way. Let us show that the s + 1st series will end in the same way. After the sth series of fours, a series of fives gives way. Let's look at the leftmost five from this series (remember that we do not consider crossed out numbers!). It is clear that it falls into the minuend in the category with a number less than m, and under it there is either an asterisk, or it falls into m - the 1st category, four. These five are the last in their series. Indeed, after it is set, the difference becomes positive and the first one will begin to announce fours. If we now consider the leftmost quadruple from the s + 1st series, then, using the same reasoning, we can be convinced that it is in the subtrahend place, more

⟦folio 39⟧

closer to the first than the last bird from the previous series, there is an asterisk above it and that it is the last in its series.

Pozny after the last quadruple is named, the following condensation will arise

$$* * * \dots * * a'_{k+1} \dots a'_n$$
$$* * * \dots * 4 b'_{k+1} \dots b'_n.$$

After this, the first player named the number 5 one or more times and, since after each of his moves, the minuend remained less than the subtrahend (when mentally replacing asterisks with zeros), the following situation arose before the announcement of nines

$$* a_2 a_3 \dots a_{k-1} a_k a'_{k+1} \dots a'_n$$
$$5 a_2' a_3' \dots a'_{k-1} 4 b'_{k+1} \dots b'_n$$

where for each $i=2, 3, \dots, k-1$ either $a_i=a'_i$ or $a'_i=5$ and $a_i$ is an asterisk, and the difference of the numbers

$$a_2 a_3 \dots a_{k-1} a_k$$
$$a_2' a_3' \dots a'_{k-1} 4$$

negative. Indeed, if it were positive, then before announcing nines the first player would announce a four, but it cannot be zero, since $a_k$ is either an asterisk or a pter. On the other hand, it is clear that if for $i < k$ $a_i$ and $a'_i$ are not asterisks, then $a_i=a'_i$; indeed, they coincided at the moment the final four were announced. Therefore, for non-final the difference is not less than $4 \cdot 10^{n-1} + 3 \cdot 10^{n-j} > 4 \cdot 10^{n-1}$. Solution problem.

Yu. I. Nonin

M154. There are 50 segments on a straight line. Prove that at least one of the following statements is true:
a) non-final difference is not less than $4 \cdot 10^{n-1} + 3 \cdot 10^{n-j} > 4 \cdot 10^{n-1}$.
b) there is a greater segment, no more than some, no more than some.

It is likely that many different theorems can be given, a special case or consequence of which is the statement of this problem. We indicate only one of them here.

Theorem. Let an arbitrary system of segments be given on a line. Let us denote by $M$ the smallest number of points on a straight line such that each of the segments of the system contains one of these points; through $m$ is the largest number of non-final segments that can be selected from the largest systems. Then $M = m$.

The inequality $M \geq m$ is obvious: it is clear that if in a system there are $m$ pairwise disjoint segments, then there cannot be less than $m$ points, one of which would contain each of the segments of the system (hereinafter, at least $m$ points must be placed on the $m$ selected segments). It remains to prove the inequality $M \leq m$.

To do this, it is enough to prove that from the system it is always possible to choose a non-finite number of points $A_1$ and the intersecting segments $A_2$, ..., $A_k$ and in each of them choose points $A_1$, $A_2$, ..., $A_k$ the maxim from the segments of the system contained one of these $k$ points.

If we manage to find such $k$ segments, then, obviously, $M \leq k$ and $k \leq m$, hence $M \leq m$. (In fact, then oblige $M = k = m$ - after all, the inequality $M < m$, as we saw, is impossible.)

Let us show how you can select such segments and points.

Let's imagine that the straight line is located horizontally in front of us. Let us choose a segment $A_1$ whose lying $A_1$ is located more to the right than the left ends of all other segments. Let us remove from the system all segments containing the point $A_1$ (in particular, $A_1$) *).

It is clear that each of the remaining segments (if there are any) is located entirely to the left of the point $A_1$ and obviously does not intersect with the segment $A_1$. The procedures described in the previous paragraph are again applied to the remaining segments - we get the segment $A_2$ and the point $A_2$, then the segment $A_3$ and $A_3$ and so on until there is not a single segment of our system left at the left of the left end $A_k$ of the segment $A_k$. The segments $A_1$, $A_2$, ..., $A_k$ and the points $A_1$, $A_2$, ..., $A_k$ satisfy all our requirements. The theorem has been proven.

Let us now solve problem M154. Let us prove that from $(pq+1)$ segments on a line one can always choose either $(p+1)$ segments that have a common point, or $(q+1)$ pairwise disjoint segments. (For $p=q=7$ this is the statement of problem M154.)

Indeed, if for a given system of $(pq+1)$ segments the value $M=m$, which is discussed in the theorem, is greater than $q$, then we can choose $m \geq q+1$ non-intersecting segments, and if this value is not greater than $q$, then we can choose a set of $M \leq q$ points that has a common point with each of $(pq+1)$ segments. Then, of course, some of these $M$ points must contain at least $(p+1)$ segments: if each point contained no more than $p$ segments, then all segments would be no more than $Mp \leq pq$.

*) We believe that the segments discussed in the problem are “closed”, that is, they contain their end points. However, the statement, as is easy to see, remains true for “open” intervals-segments that do not contain their end points.

⟦folio 40⟧

F170. In a homogeneous plasma with density (the number of charges of each sign per unit volume) n, all electrons initially located in the molecular layer x will mix along the normal to the electron layer at a distance x. Find the electron field E in section SS (Fig. 3).

Let us consider two thin layers of thickness Δx located at equal distances on opposite sides of section SS. These elephants can be considered as the plates of a flat capacitor with charges of the same size, but different. The field strength of these charges can be calculated using the formula

$$E = \frac{Q_{\Delta x}}{\varepsilon_0 s},$$

where $Q_{\Delta x}$ is the charge of each plate, s is its area.

Thus, the intensity of the charge field of the selected words does not depend on the distance between the layers. It is determined only by the magnitude of the charges.

In the SS section, the intensity of the field is equal to the sum of the intensity of the fields of similar pairs of thin words, that is, equal to

$$E_{SS} = \sum \frac{Q_{\Delta x}}{\varepsilon_0 s} = \frac{1}{\varepsilon_0 s} \sum Q_{\Delta x}.$$

Since $\sum Q_{\Delta x} = enxs$

$$E_{SS} = \frac{enxs}{\varepsilon_0 s} = \frac{enx}{\varepsilon_0}.$$

F171. On the main horizontal table there is a vertical nocturnal loop, consisting of a weightless rod with two identical small balls at the ends (Fig. 4). The impact imparts velocity v to the upper ball in the horizontal direction. At what maximum length l will the bottom ball immediately come off the table?

When the top ball is given a horizontal speed v, the balls begin

$$\frac{v^2}{2l} > g,$$

that is

$$l < \frac{v^2}{2g}$$

And

$$l_{\max} = \frac{v^2}{2g}.$$

I. Sh. Slobodetsky

F172. The conductive rod is suspended horizontally on two light wires in a vertical magnetic field with an indication of B = 1 ml (Fig. 5). Rod length l = 0.2 m, mass m = 10 g, wire length l₁ = 0.1 m. A capacitor em with C = 100 μF, charged to a voltage of U = 100 V, is connected to the wire securing pins.

a) Determine the maximum angle of deposition of the system from the equilibrium position after the discharge of the capacitor, displacing that the discharge occurs in a very short time.

b) Determine the capacitance of the capacitor C₁,

⟦folio 41⟧

when discharging, the system will deviate by an angle of $\alpha_1 = 3^\circ$, if when discharging a capacitor with a capacity of $C_0 = 10$ uF charged to the maximum voltage, the angle will deviate by $\alpha_0 = 2^\circ$.

a) When a capacitor is connected, current $i$ begins to flow through the rod, due to which a force $F = Bli$ will act on the rod, directed perpendicular to the rod and vector $B$.

The magnitude of the current gradually decreases over time from the maximum value to zero, so the strength depends on time.

Since the time $\Delta t$ of the capacitor discharge is short, we can assume that during this time the displacement of the rod from the equilibrium position is short and the rod will receive some impulse $P$ in the horizontal direction.

Having divided the time $\Delta t$ into small intervals during which the force can be considered constant, we write

$$P = \Sigma F \Delta t = B l \Sigma i \Delta t = B l q$$

And

$$v = \frac{P}{m} = \frac{B l}{m} q,$$

where $q$ is the charge passed through the rod. When the capacitor is completely discharged

$$q = CU.$$

Posetom

$$v = \frac{B l CU}{m}.$$

The angle of deviation of the system from the equilibrium position will be found from the law of conservation of energy. Let us equate the expressions for the total energy of the rod in the equilibrium position and at its maximum deflection (we will assume that the supply wires are rigid):

$$\frac{m v^2}{2} = m g l_1 (1 - \cos \alpha),$$

where

$$1 - \cos \alpha = \frac{v^2}{2 g l_1} = \frac{B^2 C^2 U^2 l^2}{2 g l_1 m^2},$$

But

$$1 - \cos \alpha = 2 \sin^2 \frac{\alpha}{2}$$

And

$$\alpha = 2 \arcsin \frac{B C U l}{2 m \sqrt{g l_1}} = 2 \arcsin 0, 1 \approx 12^\circ.$$

6) Because

$$\sin \frac{\alpha_0}{2} = C_0 \frac{B U l}{2 m \sqrt{g l_1}}$$

And

$$\sin \frac{\alpha_1}{2} = C_1 \frac{B U l}{2 m \sqrt{g l_1}},$$

That

$$C_1 = C_0 \frac{\sin \frac{\alpha_1}{2}}{\sin \frac{\alpha_0}{2}}.$$

Angles $\alpha_0$ and $\alpha_1$ are small, so

$$\sin \frac{\alpha_0}{2} \approx \frac{\alpha_0}{2} \text{ и } \sin \frac{\alpha_1}{2} = \frac{\alpha_1}{2}.$$

As a result we get

$$C_1 = C_0 \frac{\frac{\alpha_1}{2}}{\frac{\alpha_0}{2}} = C_0 \frac{\alpha_1}{\alpha_0} = 15 \text{ мкф.}$$

V. V. Svetozarov

F173. In a uniform charged ball of radius $R$ there is a spherical cavity of radius $r$, the center of which is at a distance $a$ from the center of the ball (Fig. 6). Find the direction of the electric field at various points in the cavity if the charge density is $\sigma$.

We assume that first the ball is uniformly charged throughout the entire volume, and then part of its charge located inside the cavity is removed.

According to the principle of superposition, the direction of the field at any point of a homogeneous charged ball is equal to the vector sum of the field directions of the ball with the cavity and the directions of the field of the charge removed from the cavity.

Consider an arbitrary point $A$ inside the cavity. We denote its distance from the center of the sphere as $x$, and from the center of the cavity as $y$. the direction $E_0$ of the field created by a solid ball at this point is directed along the radius of the ball and is equal in magnitude

$$E_0 = \frac{4}{3} \pi x \sigma.$$

⟦folio 43⟧

impregnated with gas is equal to

$$A = P_{cp} \Delta V = \frac{P_1 + P_2}{2} (V_2 - V_1) = \frac{\alpha R}{2} (V_2 + V_1)(V_2 - V_1) = \frac{1}{2} R (T_2 - T_1) = \frac{1}{2} R \Delta T.$$

Substituting the expression for $\Delta U$ and $A$ into formula (*), we obtain

$$C \Delta T = C_V \Delta T + \frac{1}{2} R \Delta T.$$

From here

$$C = C_V + \frac{1}{2} R.$$

It is interesting to note that if $T \sim V^n$ then $C = C_V + \frac{1}{n} R$. Those who know how to integrate will easily prove this.

In case 6) $T = \frac{\beta}{V}$ ($\beta$ is some constant). That's why

$$PV = RT = \beta \frac{R}{V} \text{ и } P = \beta \frac{R}{V^2},$$

that is, the pressure of a gas is inversely proportional to the square of its volume. In order to find the work done by the gas, we divide the interval of change in its volume into sections such that the pressure on them can be considered constant. In each of these sections, the gas performs work numerically equal to the area of ​​the rectangle on the sides $P_i$ and $\Delta V_i = V_{i+1} - V_i$ (Fig. 8). It is obvious that the total work done by the gas is approximately equal to the sum of the areas of such rectangles:

$$A = \sum \frac{\beta R}{V_i^2} \Delta V_i,$$

Fig. 8.

Moreover, the smaller the sections $\Delta V_i$, the more accurately the written sum corresponds to the amount of work done by the gas.

Since $\Delta V_i$ is small and $V_i \approx V_{i+1}$ is small, we can assume that $V_i^2 \approx V_i V_{i+1}$. Then

$$A = \sum \frac{\beta R}{V_i V_{i+1}} (V_{i+1} - V_i) = \beta R \Sigma \left( \frac{1}{V_i} - \frac{1}{V_{i+1}} \right) = \beta R \left( \frac{1}{V_A} - \frac{1}{V_1} + \frac{1}{V_1} - \frac{1}{V_2} \right) = \beta R \left( \frac{1}{V_A} - \frac{1}{V_B} \right) = \beta R \cdot \frac{1}{\beta} (T_A - T_B) = -R (T_B - T_A) = -R \Delta T.$$

Substituting this expression into formula (*), we find that

$$C = C_V - R.$$

Sweeping.

To determine the work done by a gas, you can use the analytical method.

Let's consider the work of moving a charge in a power plant field of an exact charge. The force acting on the charge in this field is equal to

$$F = \frac{q_1 q_2}{4 \pi \varepsilon_0} \cdot \frac{1}{r^2}.$$

For infinite small displacement $\Delta r$ (when the force can be considered constant), the elementary work is equal to

$$\Delta A = F \Delta r.$$

The total work on section $(r_2 - r_1)$ is equal to

$$A = \frac{q_1 q_2}{4 \pi \varepsilon_0} \left( \frac{1}{r_1} - \frac{1}{r_2} \right).$$

The gas pressure in case 6) is equal to

$$P = \frac{\beta R}{V^2},$$

that is, inversely proportional to the square of the volume.

The elementary work on gas expansion in section $\Delta V$ (where the pressure can be considered constant) is equal to

$$\Delta A = P \Delta V.$$

According to the analysis with work in the power station field, the total work on gas expansion from volume $V_1$ to volume $V_2$ is equal to

$$A = \beta R \left( \frac{1}{V_1} - \frac{1}{V_2} \right).$$

F175. The solution to this problem is contained in the article by G. L. Komkin “Collision of Balls” (pp. 19-21).

I. Sh. Slobodetsky

⟦folio 45⟧

was taken at the final written examination at the Toruń Gymnasium. Since the exam was in algebra, they mostly reduced the matter to either solving an irrational equation

$$\sqrt{2x^2 - 9} = \sqrt{x^2 - 81} + \sqrt{x^2 - 144},$$

or to solve a system of equations with unknowns:

$$\begin{cases}
x^2 - y^2 = 81, \\
x^2 - z^2 = 144, \\
2x^2 - (y + z)^2 = 9.
\end{cases}$$

It is easy to see that both paths require a significant amount of calculations.

If you come across figure, you will find that right triangles ACD and BCE have equal hypotenuses, acute angles ACD and BEC are equal, since their sides are respectively perpendicular. Thus, these triangles are congruent. Therefore, the correspondence is equal and their legs are equal. Therefore, the width of the street AB = 12 + 9 = 21 (m), and the length of the stairs is determined by the Pythagorean theorem.

The difference in the degree of complexity of the solution is palpable!

One of the manifestations of the desire to solve problems according to a pattern is the calculation of all quantities that can be used to find the unknown. This completely ignores the fact that not all of the calculated quantities are included in the final expression.

Example 3. The sides of the base of a triangular paramid are 15 cm, 16 cm and 17 cm. The side ribs are inclined to the plane of the base at angles of 45°. Find the volume of the paramid.

As a rule, the formula used to calculate the volume of the paramide and the area of ​​the base is more commonly called:

$$S = \sqrt{24 \times 9 \times 8 \times 7} = 24 \sqrt{21} (cm^2).$$

Then it is justified that the MO is perpendicular to the plane of the base.

Fig. 2.

Dit through the center of the circle described near the base (Fig. 2). It follows that the height of the paramid is equal to the radius of the circle described around the base. According to the well-known formula $R = \frac{abc}{4S}$. Means,

$$h = \frac{15 \times 16 \times 17}{4 \times 24 \sqrt{21}} = \frac{85}{2 \sqrt{21}} (cm).$$

Finally,

$$V = \frac{1}{3} \times 24 \sqrt{21} \times \frac{85}{2 \sqrt{21}} = 340 (cm^3).$$

But if you don’t rush with the calculation, you would get the following:

$$V = \frac{1}{3} SH = \frac{1}{3} SR = \frac{1}{3} S \cdot \frac{abc}{4S} = \frac{abc}{12}.$$

Thus, the calculation of $S$ and $H$ turns out to be redundant.

After the war, our schools had a written exam, during which graduates solved a stereometric problem using trigonometry. Having received the answer in general form, the participants had to carry out some research, and then bring the answer “to a number” with the specified parameter values.

Subsequently, the nature of this exam changed, in particular, calculations using tables were excluded. But the pattern remained: first solve the problem, and then explore.

For those who believe in the inevitability of this order of work, it does not hurt to know that there are many problems that do not require the solution of equations

⟦folio 46⟧

study. Let us recall several such problems.

Example 4. Two altitudes of a triangle divided it into two pairs of equal parts. Named triangles.

If in triangle ABC the altitudes AK and BM are drawn, intersecting at point O, then the triangle is divided into 4 parts: ABO, AMO, BKO and MOKC. Which ones are equal in size? There are three possible cases here: 1) ABO and BKO; AMO and MOKC; 2) ABO and AMO; BKO and MOKC; 3) ABO and MOKC; AMO and BKO.

The solution starts by exploring these possibilities. It turns out that the first two cases are excluded. Only after this should one begin to solve the problem (it is proved that triangle ABC is equilateral).

Example 5. The name of the object is parameters, development by side is a regular straight line with side a.

Here you first need to find out the shape of the base parameters. Since the angles at the vertex of the parameters are the angles of a regular pentagon (each of them is equal to 108°), there are 3 such angles. Therefore, this parameter is triangular.

The next step is to set the position of the bend ruler on the flat pattern. It turns out that one of them is the diagonal of the pentagon, the other two connect the ends of this diagonal and the middle of the parallel side. Only after this can you find the calculations.

Thus, we see that solving by template makes it difficult to obtain the original result.

By moving away from the template, you can get elegant solutions.

Here we are faced with a blue problem. Often, applicants agree that presenting rational solutions is tempting. However, they immediately raise an opportunity. In their opinion, for this to be a good solution, you need to imagine solving the problem in several ways. And this, under exam conditions, requires so much time,

which the applicant cannot afford.

If this were the case, the question of how to discover rational solutions should not be considered. Fortunately, there are possibilities for completely different detection of these paths.

A rational solution to a problem must be based on individual conditions. The decisive role is acquired not by those features on the basis of which the task belongs to a certain class of exercises, but by those that distinguish it from this class. It is attention to the numerical values ​​of the parameters, to the features of the configuration that opens the way to a simple solution.

Example 6. Simplify the expression

$$tg 20^\circ + tg 40^\circ + \sqrt{3} tg 20^\circ \cdot tg 40^\circ.$$

Obviously put - transition to sines and cosines. It requires knowledge of a number of formulas (sum of tangents, sum of cosines, difference of cosines), the values ​​of the sine and cosine of an angle of 60°, as well as the ability to perform a not very short chain of transformations.

What are the features of the condition? It includes only one function (tangent) of two angles (20° and 40°), and the expression contains the sum and product of the tangents of these angles. This combination is an integral part of the tangent of the sum of two angles formula. If we add to this that the tangent of the sum of these angles is known, it becomes clear that it is advisable to use this particular correspondence. This approach leads to the following solution:

$$tg 20^\circ + tg 40^\circ + \sqrt{3} tg 20^\circ \times tg 40^\circ = \frac{tg 20^\circ + tg 40^\circ}{1 - tg 20^\circ tg 40^\circ} (1 - tg 20^\circ \times tg 40^\circ) + \sqrt{3} tg 20^\circ tg 40^\circ = \sqrt{3} (1 - tg 20^\circ tg 40^\circ) + tg 20^\circ \times tg 40^\circ = \sqrt{3} (1 - tg 20^\circ tg 40^\circ) + tg 20^\circ \times tg 40^\circ) = \sqrt{3}.$$

⟦folio 47⟧

Example 7. The largest four-digit number according to the following data: the sum of the squares of the outer digits is 13, the sum of the squares of the middle digits is 85; If you subtract 1089 from the excluded number, you get a number written with the same numbers in reverse order.

Typically, three equations are made with four unknowns. Auxiliary inequalities allow us to establish that the difference between the extreme numbers is equal to 1. Then the task consists of solving two systems of equations (of the second degree) with two unknowns.

However, if we take into account that the digits are non-negative integers not exceeding 9, then it turns out that the extreme digits are 2 and 3 ($2^2 + 3^2 = 13$ only), and the middle ones are 9 and 2 or 7 and 6. By convention, the digits of thousands are larger digits of units, and the digits of hundreds are larger digits of tens. This means that the required number is 3922 or 3762. Direct verification shows that only the second number satisfies the condition.

Example 8: Solve the equation
$$3\sqrt{x^2 - 9} + 4\sqrt{x^2 - 16} + 5\sqrt{x^2 - 25} = \frac{120}{x}.$$
If you solve in the usual way, then after squaring complex expressions three times you get an equation of the 16th degree:
$$x^{16} - 50x^{14} - 4375x^{12} + 278800x^{10} + 1670600x^8 - 364700000x^6 + 7641610000x^4 - 54468000000x^2 + 129600000000 = 0.$$
Such an equation is hardly within the power of an applicant. We are no longer talking about the time it takes to obtain such an equation. In this case, to the peculiarity of the equation. Since the left side is non-negative, the same is true for the right side. Therefore, $x > 0$.

As $x$ increases, the left side increases and the right side decreases. Therefore, an equation can have at most one real root. Substituting the minimum possible value $x = 5$, we make sure that both sides of the equation have equal values. This means there are no other real roots.

In some cases, the solution process is achieved by using a more general body of knowledge than is provided by the program. Examiners can be picky about such decisions; beforehand they demand clarification during the oral exam as to how the applicant knows how to use a theorem or formula, whether he can prove it, etc.

Meanwhile, there is nothing wrong with this. For several years now, so-called elective classes have been introduced in our schools. By attending such classes, students learned properties and correspondences that went beyond the normal school curriculum. Students enriched with knowledge can also find unexpected (from the examiner’s point of view) solutions during the exam.

Example 9. Prove that
$$\frac{(x-a)(x-b)(x-c)}{(d-a)(d-b)(d-c)} + \frac{(x-a)(x-b)(x-d)}{(c-a)(c-b)(c-d)} + \frac{(x-a)(x-c)(x-d)}{(b-a)(b-c)(b-d)} + \frac{(x-b)(x-c)(x-d)}{(a-b)(a-c)(a-d)} = 1.$$

Having learned in elective classes (without proof) the so-called fundamental theorem of algebra and its corollaries, the student can propose such an argument.

If this equality is not a current action, then it is an equation. The degree of this equation with respect to $x$ cannot be more than three. This means that this equation cannot have more than three roots. But it is easy to check that $x = a$, $x = b$, $x = c$, $x = d$ transform this equality into a current action, which means

⟦folio 48⟧

what is being considered is equality is not an equation. Therefore, this is an identity. And this was what needed to be proven.

In the same way, the use of Ptolemy’s theorem, formulas for functions of a triple argument, etc. can lead to a simple solution. However, this path cannot be considered the main one.

It is important to study methods for solving a problem and become familiar with the conditions under which the use of these methods is advisable.

Let us recall some of them.

a) If, in the conditions of a geometric problem, the data and the required quantities are separated, it is advisable to perform geometric transformations to bring these elements closer together.

Example 10. For unit BC of a right triangle ABC with the sum of kamets m, a square with center O is constructed outside the triangle. Find the distance AO.

If we rotate triangle ABO around point O by 90°, then this triangle will take position MCO (Fig. 3). Counting the angles shows that points A, C and M lie on the same straight line. Therefore, triangle AOM is a right equilateral triangle, its hypotenuse AM is equal to m. From here the required distance is found

$$AO = \frac{m}{V^2}.$$

b) If you connect the required and given elements by geometric

Fig. 3.

conversion is not possible, then it follows the appropriate values ​​that may have a corresponding role.

Example 11. Find the volume of a regular quadruple paramid circumscribed around a ball of radius r with a plane angle α at the apex.

Since it is not easy to directly relate the quantities V, r and α, we introduce into consideration the dihedral angle φ at the base of the paramid (Fig. 4). Then

$$a = 2r \text{ctg} \frac{\varphi}{2}; \quad H = r \text{ctg} \frac{\varphi}{2} \text{tg} \varphi;$$

$$V = \frac{1}{3} \cdot 4r^2 \text{ctg}^2 \frac{\varphi}{2} \cdot r \text{ctg} \frac{\varphi}{2} \text{tg} \varphi =$$

$$= \frac{4}{3} r^3 \text{ctg}^3 \frac{\varphi}{2} \text{tg} \varphi =$$

$$= \frac{8r^3}{3 \text{tg}^2 \frac{\varphi}{2} \left(1 - \text{tg}^2 \frac{\varphi}{2}\right)}.$$

It remains to find the connection between the functions of angles φ and α. If MO is the height of the paramid and ME is the apothem, then cos φ = $\frac{OE}{ME} = \frac{AE}{ME} = \text{tg} \frac{\alpha}{2}$. That's why

$$\text{tg}^2 \frac{\varphi}{2} = \frac{1 - \cos \varphi}{1 + \cos \varphi} = \frac{1 - \text{tg} \frac{\alpha}{2}}{1 + \text{tg} \frac{\alpha}{2}} =$$

$$= \frac{\text{tg} 45^\circ - \text{tg} \frac{\alpha}{2}}{1 + \text{tg} 45^\circ \text{tg} \frac{\alpha}{2}} = \text{tg} \left(45^\circ - \frac{\alpha}{2}\right).$$

⟦folio 49⟧

The rest is already simple.

Instead of the auxiliary angle, one could consider the side of the base of the rectiline to be known, and then (by finding v) calculate this side through r and α.

in anticipation of possible exaggerations, it is often convenient to solve the calculation problem in a general form, without calculating all intermediate quantities.

This especially applies to problems about bodies of rotation.

In case of difficulties with the search for the proof of the proof, one should find an auxiliary theorem, which is said to be better considered, and at the same time the model could serve as a support for the sought-after proof.

Example 12. Prove that the sum of the sides of a convex equiangular polygon (or their extensions) from the internal point do is constructed.

Let's replace this polygon with a similar one - regular. In this case, the proof (we calculate the area of ​​the polygon as the sum of the areas of triangles with a common vertex at a given point) is almost obvious.

Let's place this polygon inside a regular polygon so that the corresponding sides of the polygons are parallel. Then it will be found that the sum of the distances from a given point M to the sides of an equiangular polygon differs from the sum of the distances to the sides of a regular polygon by a constant amount.

Now it is easy to establish the correctness of the theorem being proved.

The formulaic approach to geometric problems, in particular, is often expressed in the fact that students are limited to considering special cases and incomplete analysis of the configuration.

Example 13. Two heights are drawn from the vertex of a rhombus. The distance between the ends of the input is less than the diaeonal of the rhombus. Determine the angles of the rhombus.

Each student draws heights from the vertex of an obtuse angle ABC and considers that the distance between the ends of these heights is equal to half AC. Meanwhile, according to the condition, this distance can be equal to half BD, and besides, the heights can be drawn from the vertex of the acute corner of the rhombus. Of the four possible cases, only one is immediately excluded as a contradiction. In the remaining three calculations are successfully completed. There are two answers: 60° and 120° or 30° and 150°.

Many problems can be solved in more than one way. Sometimes these solutions differ little in degree of complexity, sometimes they differ significantly. As a rule, any student can find a fairly good solution. To do this, you need to carefully study the conditions and think about which approach to the problem is most consistent with the characteristics of its conditions.

A specific departure from the template, a specific analysis of conditions is the key to a successful solution to the problem.

Literature

1. L. M. Lopovok, Raschinal solution of the problem, “Narodna Prosveta”, Sofia, 1968.
2. D. Polya, Mathematical discovery, Nauka, M., 1970.
3. S. I. Tumanov, Ponsky solutions to the problem, “Enlightenment”, M., 1969.

⟦folio 51⟧

the action of two charges does not change in the presence of a third charge. This statement underlies the superposition principle, which, along with Coulomb’s law, is a fundamental law of electrostatics.

It is convenient to formulate the superposition principle by considering not interaction forces, but electric fields created by a system of charges: the intensity of the electric field created by a system of electric charges at a given point is a superposition (that is, the sum) of the fields created at this point by each of the charges. It must be remembered that field strength is a vector quantity; The field strengths must be added geometrically, according to the rules of vector addition.

Using this principle to calculate the fields produced by a few precise charges is usually straightforward. Therefore, we will not consider examples of this kind here. But in the case of extended charges (for example, a charged plane or several charged planes), many schoolchildren will have difficulties. Often these difficulties are associated with the very common misconception that any metal surface screens the field.

Let us first consider problems with plane geometry (a system of parallel charged planes). The field of a single charged conducting plane is uniform (the same at all points) and equal to $\frac{\sigma}{2\varepsilon_0}$, where $\sigma$ is the surface charge density (that is, the charge per unit area), $\varepsilon_0$ is the electric constant. It should be kept in mind that this result is only valid for an infinite plane. For a flat plate of finite dimensions, this is true only at distances small compared to the linear dimensions of the plate. At distances comparable to the dimensions of the plate, it is useful to use a non-uniform one, and finally, at large distances the field is indistinguishable from the field of an exact charge. We will limit ourselves to considering fields at distances small compared to the size of the plates.

Task 1. Find the field strength created by two parallel charged planes. The surface charge density on one of the planes is $\sigma_1$, on the other $\sigma_2$.

The field in the entire space is a superposition of the fields created by each plane separately. Therefore, at any point to the left of plane 1 (Fig. 1), directly at point $a$, the field strength is equal to $E_1 + E_2$ and the field lines are directed to the left (if both planes are positively charged). Between planes (for example, at point $b$) the field strength is equal to the difference $E_1 - E_2$. The direction of the field depends on the magnitude of the charges $\sigma_1$ and $\sigma_2$. If $\sigma_2 > \sigma_1$, $E_2 > E_1$ and the total field $E_b = \frac{\sigma_2 - \sigma_1}{2\varepsilon_0}$ is directed to the left. To the right of plane 2, the field strength is also equal to $E_1 + E_2$, as at point $a$, but the field lines are directed to the right.

Let's now look at a few private services:

1. The surface charge density on both planes is the same: $\sigma_1 = \sigma_2 = \sigma$. In this case, $E_1 = E_2$ and the total field between the planes is zero (Fig. 2), and to the left and right of the plane the field is $E_1 + E_2 = \frac{\sigma}{\varepsilon_0}$.

2. The charge densities on the plane are identical in value, but have

⟦folio 53⟧

Thus, uncharged plate 2 is like a flat capacitor: the entire field created by induced charges of different signs $\sigma_2$ and $\sigma_2^*$ contains the internal plates. Everywhere outside plate 2 the effect is the same as without it, that is, it is created only by charged plate 1.

Problem 3. A metal plate having a charge Q is introduced into the space between the plates of an uncharged flat capacitor, so that the orgs $l_1$ and $l_2$ (Fig. 6) are displaced between the plate and the plates of the capacitor. The areas of all plates are the same and equal to S. Determine the difference in potential between the plates of the capacitor.

Since the capacitor plates are not charged and only induced charge appears on them, they do not create a field outside. The field in the gaps is created only by the charged plate. The voltage of this field

$$E = \frac{Q}{2\epsilon_0 S}.$$

The potential difference between this plate and the left plate of the capacitor is

$$\varphi_{01} = E l_1,$$

and between the plate and the right lining -

$$\varphi_{02} = E l_2.$$

Thus, the potential difference between the plates is equal to

$$\varphi_{12} = E (l_1 - l_2) = \frac{Q}{2\epsilon_0 S} (l_1 - l_2).$$

Now we will place several problems with fields that no longer have flat, but spherical geometry.

Task 4. The routine of Cavendits, which was mentioned at the beginning of the stats, was to change the electric field of the internal charged metal sphere. Show the user with Coulomb's cacoon and the number of sovereignties that on

⟦folio 54⟧

our choice will be fair, we get, use the principle of superposition, that the total field created by the entire sphere at point A is equal to zero. But point A was chosen completely arbitrarily. This means that after any point inside a uniformly charged sphere it is equal to zero.

Task 5. An exact charge Q is placed in the circuit of a metal sphere. Determine the electric field inside and outside the sphere if the shell: a) is not charged; b) replaced.

a) On the inner and outer surfaces of a spherical object, charges will be induced by induction, identical in magnitude and different in sign (the sphere as a whole is not charged). From the reports of spherical symmetry it is clear that the induced charges are uniformly distributed over the spheres. These charges must be such that the total field in the conductor is equal to zero (Fig. 8). In accordance with the principle of superposition, the field is at any point of the shell (the outer sphere, as follows from the solution to problem 4, the field is not created within itself). The field of a uniformly charged sphere on the outside is the same as the field of a precise charge placed in the center; therefore, the condition for field compensation at point a will be satisfied if the charge inside the sphere is equal to -Q. Since the shell as a whole is not charged, a +Q charge will be induced on the outer surface. Now, using the principle of superposition, we can conclude,

Fig. 8.

that the field inside and outside the shell is equal to the field of the exact charge Q placed at its center.

6) When a conductor is replaced, its potential goes to zero. In our case, this means that the direction of the electric field outside the shell becomes zero. To do this, it is necessary that the charge disappears from the outer surface (it goes into the ground). The charge -Q is still induced on the inner surface. The field of this charge compensates the field of the exact charge Q everywhere, except for the region inside the shell. Thus, the substituted shell is an electrostatic shield.

It is interesting to note that this choice is valid for any shell shape and any charge arrangement inside it. In the case, for example, of a substituted spherical shell, but with an asymmetrical arrangement of the exact charge, the field outside is still zero, and the field inside will no longer be symmetrical. The charge -Q induced on the inner surface is no longer uniformly distributed.

If we remove the substitution and impart an additional charge Q to the shell (at the same time its total charge becomes equal to zero), then the charge must be distributed over the shell in such a way that the field in the conductor remains equal to zero. This will be achieved only with a uniform distribution of charge Q over the outer surface of the spherical shell. It follows that the outside field in the case
