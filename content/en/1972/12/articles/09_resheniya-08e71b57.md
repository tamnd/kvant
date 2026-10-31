---
id: 1972-12-resheniya-08e71b57
issue: kvant_1972_12
year: 1972
number: "12"
title: Solutions to problems M135—M140; F153—F158
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 38
page_last: 50
page_labels: 37, 38, 39, 41, 44, 45, 46, 47, 48
tag: 8WRM
lang: en
source: kvant_digital
extraction: vision
content_sha256: 1e22b85bc6cf59cbf1dc282345989691409c26312c55c86a23814e8add83a86a
prompt_sha256: draft-1
translated_from: content/ru/1972/12/articles/09_resheniya-08e71b57.md
source_content_sha256: 326704e86248fd1cdab4d33395c9f41c4239e4ee072c9a13beb2590d750774ea
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio none⟧

Solutions

In this issue we publish solutions to problems M135—M140

M135
Prove that for every natural number $n>1$ the same formula is true

$$\sin x \sin \left( x + \frac{\pi}{n} \right) \sin \left( x + \frac{2\pi}{n} \right) \times \cdots$$
$$\cdots \times \sin \left( x + \frac{(n-1)\pi}{n} \right) = c_n \sin nx,$$
where $c_n$ is some number (depending on $n$), and find $c_n$.

First we prove the following lemma.
Lemma. $$\sin nx = \sin x \cdot A_n (\cos x),$$
food $A_n (x)$ is a non-comoral polynomial of degree $(n-1)$ with the first coefficient $2^{n-1}$, $$\cos nx = B (\cos x),$$
food $B_n (x)$ is a non-comoral polynomial of degree $n$ with the first coefficient $2^{n-1}$.

It is clear that for $n=1$ the statement of the lemma is true. Let it be true for $n=k$. Then

$$\sin (k+1) x = \sin x \cdot \cos kx + \cos x \cdot \sin kx = \sin x \cdot \left( B_k (\cos x) + \cos x \cdot A_k (\cos x) \right);$$
$$\cos (k+1) x = \cos x \cdot \cos kx - \sin x \cdot \sin kx = \cos x \cdot B_k (\cos x) + \left( \cos^2 x - 1 \right) A_k (\cos x).$$

It is therefore clear that $A_{k+1} (x) = B_k (x) + x A_k (x)$ and $B_{k+1} (x) = x B_k (x) + \left( x^2 - 1 \right) A_k (x)$ are polynomials with the first coefficient equal to the sum of the first coefficients of the polynomials $A_k (n)$ and $B_k (n)$, that is, with the first coefficient equal to $2^{k-1} + 2^{k-1} = 2^k$. The lemma is proven.

Let's put $f(x) = \sin \left( x + \frac{\pi}{n} \right) \times \cdots \times \sin \left( x + \frac{\pi (n-1)}{n} \right)$. Struppirum pairwise terms of the form $\sin \left( x + \frac{\pi i}{n} \right)$ and $$\sin \left( x + \frac{\pi (n-i)}{n} \right),$$ where $0 < i < \frac{n}{2}$.

If $n$ is even, then the product will still have a term

$$\sin \left( x + \frac{\pi \frac{n}{2}}{n} \right) = \sin \left( x + \frac{\pi}{2} \right) = \cos x.$$

Let's transform pairwise products:

$$\sin \left( x + \frac{\pi i}{n} \right) \cdot \sin \left( x + \frac{\pi (n-i)}{n} \right) = \frac{1}{2} \left( -\cos (2x + \pi) + \cos \left( \frac{2\pi i}{n} - \pi \right) \right) = \frac{1}{2} \left( \cos 2x - \cos \frac{2\pi i}{n} \right) = \frac{1}{2} \left( 2 \cos^2 x - 1 - \cos \frac{2\pi i}{n} \right) = \cos^2 x - d_i,$$
where $d_i$ are some constants.

So, $f(x) = D_n (\cos x)$, where $D_n (x)$ is a non-comorous polynomial of degree $(n-1)$ with the first coefficient 1.

It remains for us to prove that $A_n (x) = 2^{n-1} D_n (x)$ (in particular, it will follow from here that the constant $c_n$ in the conditions of the problem is equal to $\frac{1}{2^{n-1}}$).

To do this, we use the theory that a polynomial of degree $k$ has at most $k$ distinct roots. (We will recall below how it is proved.)

⟦folio 37⟧

Consider the polynomial $F(x) = A_n(x) - 2^{n-1}D_n(x)$. Its degree is less than $(n-1)$, since the coefficients of $x^{n-1}$ for the polynomials $A_n(x)$ and $2^{n-1}D_n(x)$ are equal. This means that either $F(x)$ is identically equal to 0, or $F(x)$ has a root less than $(n-1)$.

Consider the points $x_1 = -\frac{\pi}{n}, x_2 = -\frac{2\pi}{n}, \ldots, x_{n-1} = -\frac{\pi(n-1)}{n}$ and the path $t_i = \cos x_i$. It is clear that $f(x_i) = 0$, and therefore $D_n(t_i) = 0$; in addition, $\sin(n \cdot x_i) = 0$, and $\sin x_i \neq 0$, means $A_n(\cos x_i) = A_n(t_i) = 0$. Note that all points $t_i$ are distinct since cos $x$ returns on the segment $[-\pi, 0]$.

So, the polynomial $F(x)$ vanishes at the $(n-1)$ point $t_1, t_2, \ldots, t_{n-1}$ and, therefore, $F(x)$ is an identical zero. Thus, $A_n = 2^{n-1}D_n$, that is

$$\sin x \cdot \sin \left(x + \frac{\pi}{n}\right) \times \cdots \times \sin \left(x + \frac{\pi(n-1)}{n}\right) = \frac{1}{2^{n-1}} \sin nx.$$

Let us now recall how it is proved that a polynomial of degree $k$ has at most $k$ roots. For $k = 1$ this is obvious. Let this statement be true for $k = l-1$ and let the path $P(t) = a_l t^l + a_{l-1} t^{l-1} + \ldots + a_1 t + a_0$ be a polynomial of degree $l$ ($a_l \neq 0$). Let $\alpha$ be the root of the polynomial $P$ (if $P$ has no roots, then everything is proven): $P(\alpha) = a_l \alpha^l + \ldots + a_0 = 0$. Therefore $P(t) = P(t) - P(\alpha) = a_l (t^l - \alpha^l) + a_{l-1} (t^{l-1} - \alpha^{l-1}) + \ldots + a_1 (t - \alpha).$ It is easy to check that $t^l - \alpha^l = (t - \alpha)(t^{l-1} + \alpha t^{l-2} + \alpha^2 t^{l-3} + \ldots + \alpha^{i-2} t + \alpha^{i-1}).$ Therefore $P(t) = (t - \alpha)[a_l (t^{l-1} + \ldots + \alpha^{l-1}) + a_{l-1} (t^{l-2} + \ldots + \alpha^{l-2}) + \ldots + a_1] = (t - \alpha) H(t)$, where $H(t)$ is a non-octoral polynomial of degree $l-1$.

By assumption, $H(t)$ has at most $(l-1)$ roots. This means that $P$ has at most $l$ roots ($\alpha$ and the roots of the polynomial $H(t)$).

Our statement has been proven for all $k$.

I. N. Bernishtein

**M136**

Is it possible to increase 50 stones from a quarry, the weights of which are 370 ke, 372 ke, 374 ke, ..., 468 ke (all form an arithmetic progression with a difference of 2 ke), on seven three horses?

Answer: no.

If the stones were to be enlarged, then 8 stones would have to be placed on some three-wheeler, but even 8 of the lightest stones weigh

$$370 + 372 + 374 + 376 + 384 + 382 + 380 + 378 = 4.754 = 3016$$

kilograms - more than three tons.

⟦folio 38⟧

Fig. 2.

are long and have a large area (Fig. 1), then it is clear that it is enough to prove inequalities a), 6) for a convex quadrilateral. Therefore, we will consider only convex quadrilaterals.

So, the path in the convex quadrilateral $ABCD$ (Fig. 2) $AB = a, BC = b, CD = c, DA = d$, the area of ​​$ABCD$ is $S$. The area of ​​a triangle always does not exceed half the product of its two sides (Fig. 3). That's why

$$2S(\Delta ABC) \leq ab \text{ и } 2S(\Delta CDA) \leq cd. \tag{1}$$

Adding these inequalities, we get

$$2S \leq ab + cd. \tag{2}$$

Equality here is achieved in the case when it is achieved simultaneously in general inequalities (1), that is, if and only if the elements $B$ and $D$ are both flush. Of course, in this case the quadrilateral $ABCD$ can be written in a circle (and the diagonal $AC$ is the diameter). From the above it also follows that a quadrilateral for which $2S = ab + cd$ can be composed of segments $a, b, c, d$ if and only if their lengths satisfy the condition

$$a^2 + b^2 = c^2 + d^2. \tag{3}$$

Problem 6) is somewhat more difficult. It can be solved “head-on” by applying various formulas for the areas of triangles. But there is also a very simple geometric solution.

Let's cut the quadrilateral, as before, the diagonal $BD$ into two triangles and one of them - say, the triangle $BCD$ - “turn it over to the opposite side” and again apply the side $BD$ to the triangle $BAD$. In other words, we replace $\triangle BCD$ with the triangle $BC'D$, symmetric to it with respect to the perpendicular passing through the middle of the segment $BD$ (Fig. 4). It is clear that the area of ​​the quadrilateral $S$ will not change. But now we can use the result of problem a):

$$2S \leq AB \cdot BC' + C'D \cdot DA$$

or

$$2S \leq ac + bd. \tag{4}$$

Equality in (4) is achieved if the “rebuilt” quadrilateral $ABC'D$ has right angles $B$ and $D$, that is, if the original quadrilateral $ABCD$ has angles that the diagonal $BD$ forms with each pair of opposite sides, adding up to $90^\circ$:

$$\angle ABD + \angle BDC = \angle ADB + \angle DBC = 90^\circ \tag{5}$$

From here, of course, it follows that $\angle ABC + \angle ADC = 180^\circ$, that is, the quadrilateral $ABCD$ is inscribed (this is also clear from the fact that $\angle A + \angle C = \angle A + \angle C' = 180^\circ$). (Note that the quadrilateral for which

$$2S = ac + bd, \tag{6}$$

can be composed of segments $a; b, c, d$ if and only if

$$a^2 + c^2 = b^2 + d^2; \tag{7}$$

this follows from (3) applied to $ABC'D$.

One more note. Don't you think that the necessary and sufficient condition (5) for equality (6) is “non-ismetric”? After all, in (6) both pairs of opposite vertices participate equally - why is diagonal $BD$ better than $AC$? She is, of course, no better. We will now see that condition (5) can be replaced by a symmetry and therefore, as is often the case, simpler.

⟦folio 39⟧

Fig. 4.

It is easy to check (Fig. 5) that condition (5) is equivalent to simply this: the quadrilateral ABCD is vipsan and AC⊥BD.

Now we can formulate our result as follows: in order to satisfy equality (6), it is necessary and sufficient that the quadrilateral ABCD be inscribed and have mutually perpendicular diagonals.

(Along the way, we also proved that for such quadrilaterals condition (7) is satisfied. Remember how to do this!).

Fig. 5.

In addition to the solution with “inverting the triangle,” another simple solution to problem 6) is based on Pmolemy’s inequality, that is, on the following theorem (see “Quant” No. 4, 1972, p. 45, solution M99):

In any quadrilateral ABCD

$$AC \cdot BD \leq AB \cdot CD + AD \cdot BC,$$

(8)

Moreover, the equality here is sufficiently moeda and molko moeda, when the quadrilateral ABCD is vipsan.

From this theorem it follows that (φ is the angle between the diagonals)

$$S = AC \cdot BD \cdot \sin \varphi \leq AB \cdot CD + AD \cdot BC = ac + bd.$$

In this way, the conditions of equality are immediately obtained in a “symmetry” form (but it is more difficult to obtain condition (7)).

M138

Prove that if m and n are integers and 1 ≤ m < n, then

$$\sum_{k=1}^{n} (-1)^k k^m C_n^k = 0,$$

where $C_n^k$ are biomp coefficients, that is, polynomial coefficients

$$(1+x)^n = \sum_{k=0}^{n} C_n^k x^k.$$

(For example, if n = 4, then $C_4^0 = 1, C_4^1 = 4, C_4^2 = 6, C_4^3 = 4, C_4^4 = 1$ and the equalities are true:

$$-1 \cdot 4 + 2 \cdot 6 - 3 \cdot 4 + 4 \cdot 1 = 0,$$

$$-1^2 \cdot 4 + 2^2 \cdot 6 - 3^2 \cdot 4 + 4^2 \cdot 1 = 0,$$

$$-1^3 \cdot 4 + 2^3 \cdot 6 - 3^3 \cdot 4 + 4^3 \cdot 1 = 0.$$)

The reader added ten elements for solving this problem (using the method of mathematical induction). Let us present one of the shortest proofs, sent by V. Frischling (Tbilisi).

It is easy to verify that the equalities being proved are true for n=2, 3, 4 (see the example in the text of the problem). Let us assume that for l<n-1 the equalities $\sum_{j=0}^{l-1} j^l C_{n-1}^l = 0$ are true. Taking advantage of equality

$$C_n^k = \frac{n!}{k!(n-k)!} = \frac{n}{k} \cdot \frac{(n-1)!}{(k-1)!(n-k)!} = \frac{n}{k} C_{n-1}^k,$$

*) We write here and below the summation sign in a not entirely familiar way

$$\sum_{k=0}^{n} \text{вместо «старого образца»} - \sum_{k=0}^{n} \text{чтобы сэкономить место и упростить работу наборщика. Так делают сейчас во многих научных журналах.}$$

⟦folio 41⟧

In this case, we will use the operation $A'$ or $B'$ every time, as soon as possible, in order to, if possible, reduce our number at each step. We get:

$$1972 \rightarrow 3944 \rightarrow 394 \rightarrow 78 \rightarrow 156 \rightarrow 312 \rightarrow 624 \rightarrow 62 \rightarrow 124 \rightarrow 12 \rightarrow 24 \rightarrow 2 \rightarrow 4.$$

It is clear that by reading this sequence from end to beginning, we will get the desired result. (The $B'$ operation is not used here.)

6) Let us prove that if we do with each number $N$ the same way as we did with the number 1972 (use the operation $A'$ or $B'$, and if this is not possible - $B'$), then after a few steps we will arrive at the number 4.

To do this, it is enough to prove that in the resulting sequence, each number turns into a smaller number (or into the number 4) after several steps. It will follow from this that in the end we will definitely come to the number 4, since it is impossible to construct an infinite sequence of natural numbers in which there are fewer numbers behind each number.

So, let’s make sure that each number can be reduced in several operations $A'$, $B'$, $B'$ (or come from it to 4; we do not particularly discuss this last case further).

If the last digit of a number is 0 or 4, then after applying $A'$ or $B'$ it is reduced by at least 10 times.

Let the last digit of the number be different from 0 and 4. Table 1 shows how the last digit changes when using $B'$ (operation $B'$, that is, notifying the number by 2 times, indicated by a black arrow; it is possible to use $A'$ or $B'$ - with a red arrow):

$$\begin{array}{c}
0 \rightarrow \\
1 \rightarrow 2 \rightarrow 4 \rightarrow \\
2 \rightarrow 4 \rightarrow \\
3 \rightarrow 6 \rightarrow 2 \rightarrow 4 \rightarrow \\
4 \rightarrow \\
5 \rightarrow 0 \rightarrow \\
6 \rightarrow 2 \rightarrow 4 \rightarrow \\
7 \rightarrow 4 \rightarrow \\
8 \rightarrow 6 \rightarrow 2 \rightarrow 4 \rightarrow \\
9 \rightarrow 8 \rightarrow 6 \rightarrow 2 \rightarrow 4 \rightarrow
\end{array}$$

From this table it is clear that if the number $N$ turns out to be any digit except 9, then after no more than three times of applying $B'$, that is, after notifying no more than 8 times, you can apply $A'$ or $B'$ to it, that is, reduce it by at least 10 times. As a result, $N$ will result in a number not exceeding $\frac{8}{10}N < N$.

It remains to consider only the numbers $N$ ending in 9, which are notified 16 times before moving on to $A'$. Note that whatever the previous digit of the number $N$ before 9, the penultimate digit of the number

$$16N = 16(10a+9) = 160a+144$$

always etna.

If this digit is not 8, then 16$N$ after $A'$ and at most two operations $B'$ will turn back into a number with a 0 or 4 at the end, which we can reduce by at least 10 times. As a result, $N$ will result in a number not exceeding $\frac{16 \cdot 4N}{100} < N$.

There remains the case when 16$N$ ends up on 84. Note that whatever the previous digit of this number before 8, after operations

$$16N = \dots \quad 84 \rightarrow 10b+8 \rightarrow \rightarrow 80b+64 \rightarrow 8b+6$$

we get a number ending in an even digit.

If this digit is not 8, then in no more than two operations $B$ we obtain a number with a digit 0 or 4 at the end, discard it and ultimately obtain from $N$ a number not exceeding $\frac{16 \cdot 8 \cdot 4}{1000}N < N$.

Our statement has been proven and the problem has been solved.

Try, having understood this solution, to convert using the operations $A$, $B$, into the number 4 in 1249 (this is one of the most “unpleasant” numbers).

Many readers who solved the problem $M140$ this way did not notice or did not fully understand the case when the number $N$ ends up on 9.

A much shorter solution was invented by $A$. Astmaov (Lviv), $A$. Arsasyan (Kamo), $\Gamma$. Visotskaya (Krasnoirsk). They prove that from any four numbers it is possible to obtain a smaller number using the operations $A'$, $B'$, $B'$ (clearly, this is enough to solve the problem). Here it is enough to consider 5 cases:

1) $10k \rightarrow k$,
2) $10k+2 \rightarrow 20k+4 \rightarrow 2k$,
3) $10k+4 \rightarrow k \rightarrow 2k$,
4) $10k+6 \rightarrow 20k+10+2 \rightarrow 40k+20+4 \rightarrow 4k+2$,
5) $10k+8 \rightarrow 20k+10+6 \rightarrow 40k+30+2 \rightarrow 80k+60+4 \rightarrow 8k+6$.

Below we publish a list of readers who sent us correct solutions

⟦folio 44⟧

In this issue we publish solutions to problems F153—F158

F153
Why do rivers flowing across flat, homogeneous soil bend?
For simplicity, consider a river flowing along the equator.

The meandering flow of rivers is due to the fact that their straight flow is unstable. This means that if a small bend or irregularity in the flowing river accidentally forms, for example, due to a tree falling into the water, the resulting bend in the river will increase. In order to figure out why this happens, let's consider. . . a glass of tea with chunks floating in it. If you “spin” tea in a glass with a spoon, causing the liquid to rotate, and then remove the spoon from the glass, then after a while all the chunks will gather along the axis of the glass. This is connected with this.

When a liquid rotates in a glass, each part of the liquid is acted upon by the other parts surrounding it by a force such that the resultant of this force and the force of gravity is directed horizontally and imparts centripetal acceleration to the particle

$$a = \omega^2 R,$$

where $\omega$ is the angular velocity of rotation of the fluid and $R$ is the distance at which the part is located from the axis of rotation. The greater the distance $R$, the greater the acceleration of the particle, which means that the greater should be the horizontal component of the force acting on this part from other parts. Therefore, the surface of the rotating liquid takes the shape of a parabolon. (Recall that the force acting on a particle of liquid that is located near the surface from other parts is peredicular to the surface. Otherwise, the component of this force, parabolic to the surface, would cause the movement of the liquid particles.) Due to this shape of the liquid surface, the pressure in it at the same distance from the day increases as it approaches the stacks of the glass.

After the spoon is removed from the glass, the speed of the liquid particles at the walls of the glass and at the bottom begins to decrease due to friction. In this case, the acceleration imparted to these particles by the slimy acting on them turns out to be greater than the centripetal one, and a fluid flow will arise in the glass, as shown in figure 7. Due to friction, the speed of this current at the surface is less than its speed at a certain depth. This flow carries the chunks to the axis of rotation of the liquid.

A similar circular flowing influence occurs in the river where the river makes a turn (Fig. 8). These sand particles are transported from the day and the disturbed bank of the river to its inner bank. Thus, the circular current increases the bend of the river, eroding its undisturbed bank. Moreover, erosion - the destruction of the bank and the day - turns out to be stronger near the disturbed bank of the river. Therefore, up to the river it takes the profile shown in figure 9.

F154
Estimate how many droplets of water there are in 1 m³ of fog if visibility is 10 m and the fog settles after 2 hours. Fog height 200 m.

The force of air resistance acting on a drop of water of radius $R$ (m), moving at a speed $v$ (m/sec), is equal to 4.3 Rv (n).

For evaluation, we will assume that the fog drops are identical opaque balls of radius $R$. Each of these drops has a cross-sectional area $s = \pi R^2$. This means that $n$ drops located in 1 m³

⟦folio 45⟧

air and located chaotically, “overlap” an area equal to approximately $S = n\pi R^2$. In this assessment, we do not take into account that the capitals partially overlap each other. However, for assessment - getting an approximate answer - this is not important.

Since visibility is 10 m, the fog caps, which are located in a rectangular parallelepiped with a base area of ​​$1\ m^2$ and a length of 10 m, must “overlap” an area of ​​$1\ m^2$. There are 10 n drops in this parallelepiped, and the area covered is

$$10\pi nR^2 = 1\ m^2.$$

From here you can find $n$:

$$n = \frac{1}{10\pi R^2}.$$

This formula includes the unknown radius of the drop. Let's find him. A drop of fog is acted upon by two forces: gravity, which is constant, and upward air resistance, which increases with increasing speed of the drop's fall. When a drop falls, a moment certainly comes when these forces become equal to each other. After this, the speed of the drop stops changing, and the drop falls uniformly at a speed that can be found from the condition of equality of gravity and air resistance:

$$mg = 4,3Rv$$

$$(m = \frac{4}{3}\pi R^3\rho - \text{масса капли},$$

$$\rho = 10^3\ k\epsilon/m^3 - \text{плотность воды}).$$

From here

$$\frac{4}{3}\pi R^3\rho g = 4,3Rv$$

And

$$R^2 = \frac{3}{4}\frac{4,3v}{\pi\rho g} \approx \frac{v}{\rho g} m^2.$$

Since the fog settles in 2 u, and the height of the fog layer is 200 m, then the speed of the drop is equal to

$$v = \frac{200\ m}{2\cdot 3600c} \approx 0,028\ m/c.$$

Substituting this value of the drop falling speed into formula (2), we find the radius of the drop:

$$R = \sqrt{\frac{0,028}{10^4}} \approx 1,7\cdot 10^{-3}\ m.$$

Now from formula (1) we can find $n$:

$$n = \frac{1}{10\cdot 3,14\cdot(1,7)^2\cdot 10^{-6}} \approx 1,1\cdot 10^4.$$

F155

One mole of gas is skimmed so that its volume during the skimming process is proportional

Fig. 10.

pressure $V = \alpha P$. The gas pressure increases from $P_1$ to $P_2$. Find the coefficient $\alpha$ if the heat capacity of this gas at constant volume is $c_V$ and during the process the amount of heat lost from air is imparted to the gas:

$$Q = \Delta W_{BH} + A.$$

From the law of conservation of energy it follows that the amount of heat retained by the gas during the process is equal to the sum of the changes in the internal energy of the gas $\Delta W_{BH}$ and the work $A$ performed by the gas during the process:

$$\Delta W_{BH} = c_V \Delta T.$$

Pozny

$$Q = c_V \Delta T + A.$$

The work done by the gas is equal to the area of ​​the trapezoid under the graph of $P$ versus $V$ (Fig. 10):

$$A = (V_2 - V_1) \frac{(P_2 + P_1)}{2} =$$

$$= \frac{(\alpha P_2 - \alpha P_1)(P_2 + P_1)}{2} = \frac{\alpha (P_2^2 - P_1^2)}{2}.$$

Thus,

$$Q = c_V \Delta T + \frac{\alpha (P_2^2 - P_1^2)}{2}.$$

Let's express $\Delta T$ in terms of $P_1$ and $P_2$. Let us write the equation of the gas state for the initial and final states of the gas:

$$P_1V_1 = RT_1,$$

$$P_2V_2 = RT_2,$$

$$\alpha P_1^2 = RT_1,$$

$$\alpha P_2^2 = RT_2.$$

⟦folio 46⟧

Subtracting the first equality from the second, we find

$$\Delta T = T_2 - T_1 = \frac{\alpha (P_2^2 - P_1^2)}{R}.$$

Now, substituting this expression for $\Delta T$ into formula (3), we obtain

$$Q = \frac{c_V \alpha}{R} \left( P_2^2 - P_1^2 \right) + \frac{\alpha}{2} \left( P_2^2 - P_1^2 \right).$$

From here

$$\alpha = \frac{2QR}{(2c_V + R) (P_2^2 - P_1^2)}.$$

F156
There is an endless wire mesh with a rectangular cell. The resistance of each of the wires that make up the mesh cell is $r$. Find the grid resistance between points $A$ and $B$ (Fig. 11).

Let a source with a potential difference at terminals $U$ be connected to points $A$ and $B$ (the internal resistance of the source is insignificant and can be considered equal to zero). Let the current flowing through the supply wires be equal to $I$. Then $U = IR$, where $R$ is the resistance of the chain between points $A$ and $B$. On the other hand, if current $I_1$ flows through conductor $AB$, then according to Ohm’s law $U = I_1 r$. This means that

$$I_1 r = IR \text{ и } R = \frac{I_1}{I} r.$$

Thus, in order to find the resistance of the chain, it is necessary to find the connection between points $I$ and $I_1$.

Thus, in order to find the resistance of the chain, it is necessary to find the connection between points $I$ and $I_1$.

Thus, in order to find the resistance of the chain, it is necessary to find the connection between points $I$ and $I_1$.

Thus, in order to find the resistance of the chain, it is necessary to find the connection between points $I$ and $I_1$.

Thus, in order to find the resistance of the chain, it is necessary to find the connection between points $I$ and $I_1$.

Thus, in order to find the resistance of the chain, it is necessary to find the connection between points $I$ and $I_1$.

Thus, in order to find the resistance of the chain, 缺损, associated with the center of the hoop, the acceleration of each of the points of the hoop is equal to the sum of the centripetal acceleration $a_ц = \frac{v^2}{R}$ (v is the linear speed of the points of the hoop) and the tangential (tangential) acceleration (Fig. 12, a). Since the hoop does not slip, the linear speed of the points of the hoop at any time is equal to the speed of its center in the coordinate system associated with the Earth. This means that the change in the linear speed of the hoop per unit time, that is, the tangential acceleration of the points of the hoop, is equal to the acceleration of the center of the hoop, that is, $a$.

In order to calculate the centripetal acceleration of the hoop points after time $t$ after the start of movement, you need to know their linear speed at this moment. It is equal

$$v = v_0 + at.$$

Pozny

$$a_ц = \frac{(v_0 + at)^2}{R}.$$

In order to find the acceleration of the hoop points in the coordinate system associated with the Earth, you need to add the acceleration vector $a$of the center of the hoop (Fig. 12, b) to the acceleration vector of the points. Thus we find:

$$a_A = \sqrt{a^2 + (a_ц + a)^2} =$$

$$= \sqrt{a^2 + \left[ \frac{(v_0 + at)^2}{R} + a \right]^2},$$

$$a_B = \sqrt{(2a)^2 + a_ц^2} =$$

$$= \sqrt{4a^2 + \frac{(v_0 + at)^4}{R^2}},$$

$$a_C = \sqrt{a^2 + (a_ц - a)^2} =$$

$$= \sqrt{a^2 + \left[ \frac{(v_0 + at)^2}{R} - a \right]^2},$$

$$a_D = a_ц = \frac{(v_0 + at)^2}{R}.$$

⟦folio 47⟧

Fig. 12.

F158

A dumbbell located horizontally falls from a height $h$ and hits one of its ends on the table (Fig. 13). How far will the dumbbell travel after the impact before it becomes horizontal again?

The dumbbell consists of two identical heavy balls mounted on a weightless rod of length $l$. The impact of the dumbbell on the table is absolutely elastic. The table is immediately removed after the impact.

Having fallen from a height $h$, the dumbbell had a speed of

$$v = \sqrt{2gh}.$$

Since the impact of the dumbbell ball on the table can be considered instantaneous, the influence of the second ball on the collision with the table can be ignored. This means that the steel ball interacts with the table in the same way as if it were alone and not attached to the rod: upon impact, the speed and momentum of this ball are reversed, but the momentum and speed of the second ball do not change.

Let us consider the movement of a dumbbell in a coordinate system associated with the center of the rod—the center of mass of the system. This coordinate system moves downward with acceleration $g$ and immediately after the ball hits the table it has a speed equal to 0. In this system, the velocities of the balls after hitting the table are equal in absolute value $v$ and are directed in different directions. This means that in the coordinate system associated with the center of mass, the dumbbell will rotate after so many steps with the table, and the linear speed of rotation of the balls is equal to $v$. The dumbbell will again become horizontal when the balls make half a revolution around the center of the rod, that is, after a while

$$t = \frac{\pi \frac{l}{2}}{v} = \frac{\pi l}{2v} = \frac{\pi l}{2\sqrt{2gh}}.$$

During this time, the center of the rod will cover the distance

$$H = \frac{gt^2}{2} = \frac{1}{16} \frac{\pi^2 l^2}{h}.$$

The editors received about 400 letters with solutions to problems F148 - F158. Almost all readers successfully completed problem F158. The correct solutions to the remaining problems were added by: A. Hayrapemyan (Yerevan) F149; O. Azanina (Moscow) F152, F155; M. Aksman (Rostov-on-Don) F152; Sh. Amakulov (Fergana) F152; A. Baevsky (Gomel) F148, F152; Y. Belenko (Namangan) F155; V. Belov (Vologda) F148, F149, F151, F155, F156; A. Blyukhin (Kiselevsk, Kemerovo region) F149 - F152; L. Bradisky (Frunze)

⟦folio 48⟧

Couples birthdays

For what minimum number of people in a company is the probability that even though two of them were born on the same day, is it at least 1/2?

(Years of birth may not be the same.)

On the edge of a cliff

The drunkard stands one step away from the edge of the abyss. He steps as follows: either to the edge of the cliff or not to it. At each step the probability of this being away from the edge is 2/3, and a step towards the edge of the cliff has a probability of 1/3. How do drunkards avoid falling?

Buffon's needle

Parallel lines are drawn on the plane, spaced from each other at a distance of 2a. A needle of length 2l (less than 2a) is thrown at random onto a plane. What is the probability that it will cross one of the lines?
