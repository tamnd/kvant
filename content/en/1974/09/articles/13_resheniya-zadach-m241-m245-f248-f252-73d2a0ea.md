---
id: 1974-9-resheniya-zadach-m241-m245-f248-f252-73d2a0ea
issue: kvant_1974_9
year: 1974
number: "9"
title: Solutions to problems M241—M245; F248—F252
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 46
page_last: 51
page_labels: 44-49
tag: RCDS
lang: en
source: kvant_digital
extraction: vision
content_sha256: ada7fa3b68205fd774663d59376862ba5e911933bfea1c0a862c236497ea92e5
prompt_sha256: draft-1
translated_from: content/ru/1974/09/articles/13_resheniya-zadach-m241-m245-f248-f252-73d2a0ea.md
source_content_sha256: 00858984e06aef6a70a99234e56a0f46ed2d324fd78b6901096c0dea9f27dd52
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 44⟧

Problem solutions

M241—M245; F248—F252

M241: Let us prove that
31974 + 51974
divisible by 13.

The author of the problem, S.I. Mayzus, proposed such a clever solution. Let's write the number 31974 + 51974 as a sum
(31974 + 21974) + (51974 - 21974)

and prove that each bracket is divisible by 13.
1°. For any integer a, b and odd n, a^n + b^n is divided by a + b:
a^n + b^n = (a + b) ×
× (a^{n-1} - a^{n-2} b + ... + b^{n-1}).
Pozotomu
(3^2)^{987} + (2^2)^{987} = 9^{987} + 4^{987}

divisible by 13.
2°. For any integer a, b and natural n, a^n - b^n is divided by a - b:
a^n - b^n = (a - b) ×
× (a^{n-1} + a^{n-2} b + ... + b^{n-1}).
Pozotomu
(5^3)^{658} - (2^3)^{658} = 125^{658} - 8^{658}

divided by 125 - 8 = 117 = 9.13.

Most readers offer a more natural solution, suitable for any analogous examples.

We will monitor which remainders give powers 3 and 5 when divided by 13. Let us denote these remainders of the numbers 3^n and 5^n by r_n and r'_n, respectively. We consistently find the remainders r_n when dividing 3^n by 13:
$$\frac{n}{r_n} \left| \begin{array}{c c c c} 0 & 1 & 2 & 3 & 4 & 5 & 6 & \dots \\ 1 & 3 & 9 & 1 & 3 & 9 & 1 & \dots \end{array} \right|$$

(In order to compile such a table, you do not need to divide 3^5, 3^6, ... by 13: it is clear that if 3^n - r_n is divisible by 13, then 3^{n+1} - 3r_n is also divisible by 13, so the remainder r_{n+1} can be obtained simply as the remainder when dividing 3r_n by 13.) Thus, the remainders are repeated with a period of 3, and since 1974 is divisible by 3, then r_{1974} = r_0 = 1.

For the remainders obtained when dividing by 13 numbers 5^n, we have the following table:

$$\frac{n}{r_n} \left| \begin{array}{c c c c c c c c c} 0 & 1 & 2 & 3 & 4 & 5 & 6 & \dots \\ 1 & 5 & 12 & 8 & 1 & 5 & 12 & \dots \end{array} \right|$$

Here the period is 4, and r'_i = r'_i = 12. Thus, 31974 leaves a remainder of 12, and their sum is divided by 13.

More details about the patterns that occur in the sequence of remainders of numbers a^n (n = 0, 1, 2, ...) when divided by some prime p are described in the article by S. G. Gindikn “Fermat’s Little Theorem”, «Kvant» No. 10, 1972.

M242. Let $A_i H_i$ be the height and $A_i M_i$ the median drawn from the vertex $A_i$ of the island triangle $A_1 A_2 A_3$ (i = 1, 2, 3). Let us prove that one of the three products $|H_1 M_1| \cdot |A_2 A_3| \cdot |H_2 M_2| \cdot |A_3 A_1| \cdot |H_3 M_3| \cdot |A_1 A_2|$ is equal to the sum of the other two *). Is this statement true for triangle directlocalhost and mysqllocalhost?

Let us prove that this statement is true for any triangle. Let us express the product $|H_1 M_1| \cdot |A_2 A_3|$ in terms of the side lengths $|A_2 A_3| = a_1$, $|A_3 A_1| = a_2$, $|A_1 A_2| = a_3$.

From the Pythagorean theorem applied to $\triangle A_1 H_1 A_2$ and $\triangle A_1 H_1 A_3$ it follows that (Fig. 1) $|A_1 H_1|^2 = |A_1 A_2|^2 - |A_2 H_1|^2 = |A_1 A_3|^2 - |A_3 H_1|^2$, whence
$|A_2 H_1|^2 - |A_3 H_1|^2 = a_3^2 - a_2^2$.

Let us prove that, modulo, the difference (1) is equal to 2 $|H_1 M_1| \cdot |A_2 A_3|$.

In order not to consider separately the case of the location of point H_1 relative to points A_2, M_1, A_3, we introduce coordinate systems on straight line A_2 A_3. Let's take point M_1 as the origin. Let the coordinates of points A_2, A_3 and H_1 correspond to

*)Via |KL| denotes the length of the segment with ends K and L.

⟦folio 45⟧

Fig. 3.

are equal to $-\frac{a_1}{2}, \frac{a_1}{2}$ and $h_1$ (Fig. 2). The distance between points with coordinates $x_1$ and $x_2$ is $|x_2 - x_1|$, so

$$\left|A_2H_1\right|^2 - \left|A_3H_1\right|^2 = \left|h_1 + \frac{a_1}{2}\right|^2 - \left|h_1 - \frac{a_1}{2}\right|^2 = \left(h_1 + \frac{a_1}{2}\right)^2 - \left(h_1 - \frac{a_1}{2}\right)^2 = 2h_1a_1.$$

Since $|h_1| = |H_1M_1|$, then from (1) and (2) the equality follows

$$2|H_1M_1| \cdot |A_2A_3| = |a_3^2 - a_2^2|.$$

The equalities are proved in a similar way

$$2|H_2M_2| \cdot |A_3A_1| = |a_1^2 - a_3^2|,$$

$$2|H_3M_3| \cdot |A_1A_2| = |a_2^2 - a_1^2|.$$

But the sum of three numbers $a_3^2 - a_2^2, a_1^2 - a_3^2$ and $a_2^2 - a_1^2$ is equal to 0. Therefore, the model of one of them is equal to the sum of the model of the other two. This implies the statement of the problem.

(If the vertex designations are chosen so that $a_1 \geq a_2 \geq a_3$, then

$$\left|a_1^2 - a_3^2\right| = \left|a_1^2 - a_2^2\right| + \left|a_2^2 - a_3^2\right|$$

and it would become

$$\left|H_2M_2\right| \cdot |A_3A_1| = |H_1M_1| \cdot |A_2A_3| + |H_3M_3| \cdot |A_1A_2|.$$

N. B. Vasiliev

**M243.** $n$ segments $A_1B_1, A_2B_2, \dots, A_nB_n$ (Fig. 3) ​​are considered on the max plane, such that each of them starts on one of the two given lines, ends on the other line, and passes through the point $G$ (not lying on these lines) - the center of the plurality of unit masses placed at points $A_1, A_2, \dots, A_n$. Prove that

$$\frac{A_1G}{GB_1} + \frac{A_2G}{GB_2} + \dots + \frac{A_nG}{GB_n} = n.$$

We will slightly generalize the formulation of this problem, namely, we will assume that at points $A_i$ there are not unit masses, but masses $m_i$ (point $G$ is the center of gravity of masses $m_i$ located at points $A_i$). Let us prove that then

$$\sum_{i=1}^{n} m_i \frac{A_iG}{B_iG} = \sum_{i=1}^{n} m_i.$$

Let us place a mass $M_i = m_i \frac{A_iG}{B_iG}$ at each of the points $B_i$. Then the center of gravity of the pair of points $B_i$ and $A_i$ (for all $i$) will be at point $G$. We assume that not all points $A_1, \dots, A_n$ lie on the same line (for convenience, we denote our lines by the letters $l_1$ and $l_2$). The center of gravity of the point $A_i$ lying on the straight line $l_1$ will be denoted by $C_1$; corresponds to the center of gravity of the point $A_i$ located on the straight line $l_2$, denoted by $C_2$. Similarly, the center of gravity of the point $B_i$ lying on the straight line $l_k$ ($k = 1, 2$) will be denoted by $D_k$. We denote the corresponding masses by $P(C_1), P(C_2), P(D_1), P(D_2)$.

From the conditions of the problem it follows that the center of gravity of the points $C_1$ and $C_2$ will be at the point $G$. On the other hand, from the choice of masses $M_i$ it follows that the center of gravity of points $C_1$ and $D_2$ will also be at point $G$. Therefore it should be $P(C_2) = P(D_2)$. Similarly we get $P(C_1) = P(D_1)$; Means,

$$P(C_1) + P(C_2) = P(D_1) + P(D_2).$$

But $P(C_1) + P(C_2) = \sum_{i=1}^{n} m_i$, and $P(D_1) + P(D_2)$

$$+ P(D_2) = \sum_{i=1}^{n} M_i$$, that is

$$\sum_{i=1}^{n} m_i = \sum_{i=1}^{n} M_i = \sum_{i=1}^{n} m_i \cdot \frac{A_iG}{B_iG},$$

Q.E.D.

B. D. Ginzburg

**M244.** Data from a set of $n$ real numbers:

$a_1, a_2, \dots, a_n$ and $b_1, b_2, \dots, b_n$.

Prove that if at least one of two conditions is satisfied:

a) $u_3 a_i < a_j$ it follows that $b_i \leq b_j$;

b) $u_3 a_i < a_j$, where $a = \frac{a_1 + a_2 + \dots + a_n}{n}$, it follows that $b_i \leq b_j$,

then the inequality is true

$$n \left(a_1 b_1 + a_2 b_2 + \dots + a_n b_n\right) \geq \left(a_1 + a_2 + \dots + a_n\right) \times \left(b_1 + b_2 + \dots + b_n\right).$$

⟦folio 46⟧

Since point 6) follows from point a), we will immediately solve point 6).

Let us assume that for some values ​​of $a_1, a_2, \dots, a_n$ and $b_1, b_2, \dots, b_n$ the inequality

$$n(a_1b_1 + a_2b_2 + \dots + a_nb_n) < (a_1 + a_2 + \dots + a_n) \times (b_1 + b_2 + \dots + b_n).$$

If not all $a_i$ are equal to each other, then he will find $a_i$ and $a_j$ such that $a_i < a < a_j$. Consider the numbers $a$ and $a_i + a_j$ – a; We will replace $a_j$ with the larger of these numbers, and $a_i$ with the smaller one (it is clear that in this case $a_i$ increases, and $a_j$ decreases, and by the same amount $\Delta > 0$, so $a_i^* = a_i + \Delta$, $a_j^* = a_j - \Delta$).

The new sets $\{a_i^*\}, \{b_i\}$ will still satisfy the conditions of the problem. If in the new set $\{a_i^*\}$ not all numbers are the same, then we will repeat the instructions above again. Let's define, etc. After a finite number of steps we get a set in which all numbers $\{a_i\}$ are equal to each other and equal to $a$. Moreover, since at each step the right side of inequality (1) did not change $(a_i^* + a_j^*) = a_i + a_j)$, and the left side decreased $(a_i^*b_i + a_j^*b_j) = (a_i + \Delta)b_i + (a_j - \Delta)b_j = a_i b_i + a_j b_j + \Delta (b_i - b_j) < a_i b_i + a_j b_j$, since $b_i - b_j < 0$, and $\Delta > 0$, then for the last set inequality (1) should be satisfied. But if all $a_i$ are equal to $a$, then both the left and right sides of inequality (1) are the same and equal to $na(b_1 + b_2 + \dots + b_n)$, and this contradicts our assumption that for some values ​​of $\{a_i\}$ and $\{b_i\}$ inequality (1) holds. Thus, the solution problem: for all values ​​of $\{a_i\}$ and $\{b_i\}$ that satisfy the conditions of the problem, there will be

$$n(a_1b_1 + a_2b_2 + \dots + a_nb_n) \geq (a_1 + a_2 + \dots + a_n) \times (b_1 + b_2 + \dots + b_n).$$

L. G. Limanov

**M245. We propose to construct $N$ points on the poppy plane so that all pairwise distances between them are equal to a predetermined number: for each two points $M_i, M_j$ it is known what the distance $|M_iM_j| = r_{ij}$ should be equal to (i and j are any numbers from 1 to $N$).

a) Is it possible to construct if the distances $r_{ij}$ are given, so that any 5 of $N$ points can be constructed?

b) Is it enough to transform so that you can construct any 4 of $N$ points?

e) What will change if you build points not on a plane, but in space? What is the smallest model $K$ for which it is possible to construct points of any $K$ from given $N$ points and ensures the construction of all $N$ points?

a) Two mutually exclusive cases are possible.

1°. Any five of the $N$ points constructed in compliance with the requirements of the problem turn out to be one straight line: at least three points form a triangle; let these be points $M_1, M_2$ and $M_3$ (this can always be achieved by changing, if necessary, the numbering of numbers $r_{ij}$).

Let us first consider the more general case of 2°. Let us prove that in the case of 2° all $N$ points can be constructed. Let's construct $\Delta M_1M_2M_3$ (so that $M_1M_2 = r_{12}, M_1M_3 = r_{13}, M_2M_3 = r_{23}$). Since, by condition, any five of the $N$ points can be constructed on the plane, then four of the $N$ points can even more so be constructed (so that the distances between them are equal to a given number).

Taking advantage of this, we will construct the next point $M_4, M_5, \dots, M_N$, making sure when constructing the point $M_k$ ($4 \leq k \leq N$) only that $M_1M_k = r_{1k}, M_2M_k = r_{2k}$ and $M_3M_k = r_{3k}$.

We'll get the next one.

Lemma. These topics can be found on the plane: $A, B, C$ and $D$; $A, B$ and $C$ do not lie on the same line. Let $E$ make the point that $AE = AD, BE = BD$ and $CE = CD$. Then $E$ necessarily coincides with $D$.

Proof. $AE = AD$ and $BE = BD$; This means that if $E$ and $D$ do not coincide, then they are symmetric relative $AB$. Likewise, if $E$ and $D$ are not the same, then they are symmetrical relative $AC$ (and relative $BC$). Since two points cannot be both symmetrical and relative $AB$, and relative $AC$, it means $E = D$.

Let's return to solving our problem.

According to the lemma, the position of the point $M_k$ ($4 \leq k \leq N$) is always determined uniquely. Let us check that the points constructed in this way are the required ones: for any $i$ and $j$ the distance is $M_iM_j = r_{ij}$.

If at least one of the indices is 1, 2 or 3, then this follows from the construction. Let it have an index, $i$ and $j$, greater than 3. Let us construct five points $A_1, A_2, A_3, A_4$ and $A_5$ on the plane so that the pairwise distances between them are equal to a given number (in particular, $A_iA_j = r_{ij}$) - by condition this can be done. Let's move the spot point $A_1A_2A_3A_4$ so that $\Delta A_1A_2A_3$ coincides with $\Delta M_1M_2M_3$ (these two triangles are equal). By the lemma, the points $A_i$ and $A_j$ coincide with the points $M_i$ and $M_j$. Thus $M_iM_j = r_{ij}$, which is what needed to be proven.

In the case of 1° (when any five points are on the same line), all $N$ points can even more so be constructed, since construction, since construction, the statement:

Suppose we need to construct $N$ points on a straight line (so that pairwise distances

⟦folio 47⟧

between them equal to a given number $r_{ij}$). The numbers $r_{ij}$ are given as such that any number of $N$ lobes can be used to construct all $N$ lobes.

This statement is proved in exactly the same way as above.

6) In the general case, the possibility of constructing any four points does not imply the possibility of constructing all $N$ points. Let us give a corresponding example for $N = 5$.

Let $D$ be the center of the regular triangle $ABC$ (Fig. 4), $E$ be the point symmetrical to $D$ with respect to $BC$. Let's put $r_{12} = r_{13} = r_{23} = AB$, $r_{14} = r_{24} = r_{34} = r_{15} = r_{25} = r_{35} = AD$, $r_{45} = DE$. It is obviously impossible to construct the fifth point $M_1$, ..., $M_5$ so that $M_iM_j = r_{ij}$ for all $i$ and $j$: if 9 equalities $M_iM_j = r_{ij}$ are satisfied (all except $M_4M_5 = r_{45}$), then by Lemma $M_4 = M_5$; This means that all 10 equalities cannot be satisfied simultaneously. At the same time, any four points from the fifth can be constructed: all points except $M_4$ and all except $M_5$ form the configuration $ABCD$; the remaining three "quadruple" points form a $BDCE$ to figure configuration. 4.

In the case of constructing points not on a plane, but in space, the smallest number $K$ such that the possibility of constructing any $K$ from $N$ points ensures the construction of all $N$ points is equal to 100.

The fact that six dots are enough is proven in the same way as in point a). That the fifth point is small follows, as in point 6), from figure 5, where $E$ is the center of the regular tetrahedron $ABCD$, and $F$ is a point symmetrical to the point $E$ relative to the face $KBCD$.

M. L. Gerver

F248. A thin soft hoop of radius $R$ with very light power can be freely doctored around a horizontal axis. A small ball is attached to the hoop, the mass of which is equal to the mass of the hoop. The period of small vibrations of a hoop with a ball. For emod, you can try to find an analoe in the movement of a hoop with a ball and a mathematical magnet.

A general way to find the period of oscillation of a magnet is to write down the equation of motion of the magnet and then, using the connection between the period of oscillation and the coefficients in the equation of motion, the period itself is found. In this case, we would have to write down the equation for the rotational motion of the hoop. There is, however, another way - to compare the movements of the magnet under consideration with the movement of the mathematical magnet. Let's use this method.

Obviously, in the equilibrium position of the hoop with the ball, the ball occupies the lowest position and the radius vector connecting the ball with the axis of rotation is vertical. Let's find the speed of the ball at the moment when the radius vector makes an angle $\alpha$ with the vertical, and compare it with the speed of a mathematical magnet when its thread also forms an angle $\alpha$ with the vertical. It is natural to assume that the length of the thread of a mathematical magnet is equal to $R$ and that the maximum deviations from the equilibrium position are the same (heights $h_0$ to Fig. 6, a and 6).

From the law of conservation of energy it follows that

$$mgh_0 = mgh + \frac{mv^2}{2} + W_{BP},$$

where $mgh + \frac{mv^2}{2}$ is the energy of the ball, and $W_{BP}$ is the energy of the rotational motion of the hoop itself.

Since all points of the hoop at each moment of time are moving with the same absolute value speed $v$, then the kinetic energy $W_{BP}$ of the rotational motion of the hoop is equal to

$$W_{BP} = \frac{mv^2}{2}.$$

Pozny

And

$$mgh_0 - mgh = 2\frac{mv^2}{2}$$

$$v = \sqrt{g(h_0 - h)}$$.

In the case of a mathematical magnet we have:

$$mgh_0 = mgh + \frac{mv^2}{2},$$

⟦folio 48⟧

where

$$v = \sqrt{2g(h_0 - h)}$$

We see that for any position of the ball (that is, for any $h$), the speed of the matrix, which is a hoop with a ball, is $\sqrt{2}$ times less with the speed of the mathematical matrix. This means that any section of the ball’s trajectory passes $\sqrt{2}$ times slower than the mathematical matrix, since the average speed in this section is $\sqrt{2}$ times less. Consequently, the period of oscillation of this matrix $T_1$ is $\sqrt{2}$ times greater than the period of oscillation of the mathematical matrix $T$ and is therefore equal to

$$T_1 = \sqrt{2}T = 2\pi \sqrt{\frac{2R}{g}}.$$

F249. A weightless rod, at the end of which balls of masses $m$ and $M$ are attached, rests in the middle on a rigid stand, around which it can be freely moved in the vertical plane. At the initial moment, the rod is horizontal and its speed is zero. With what force is he pressing on the stand at this moment?

The pressure force on the stand $F_{\pi}$ is equal to the sum of the pressure forces $F_{\pi.1}$ and $F_{\pi.2}$ of the balls on the rod, since the rod itself is weightless.

Each of the balls is acted upon by two forces: gravity and the reaction force from the rod, which, according to the third law

Newton is equal in magnitude to the pressure forces of the ball on the rod (Fig. 7).

Let us write down the equations of motion of the balls:

$$Mg - F_{\pi.1} = Ma,$$

$$F_{\pi.2} - mg = ma.$$

Note that the forces $F_{\pi.1}$ and $F_{\pi.2}$ are equal. Indeed, the rotation of the rod itself relative to the axis passing through its middle is caused by the moments of forces $F_{\pi.1}$ and $F_{\pi.2}$, but since the rod is weightless, no effort needs to be expended on its rotation. Therefore, the moment of force $F_{\pi.1}$ and $F_{\pi.2}$ are the same. And since the shoulders are equal, the forces themselves are equal.

Thus, from (1) and (2), taking into account the fact that $F_{\pi.1} = F_{\pi.2}$ (since the forces are equal in magnitude to the corresponding pressure forces), we obtain

$$F_{\pi.1} = F_{\pi.2} = \frac{2Mmg}{M + m}.$$

F250. Identical charges $q$ are located at distances $a$ and $b$ from the substituted sphere of small radius $r$ (Fig. 8). The distance to the surface of the earth and other replaced objects is much greater than $a$ and $b$. Find the force with which the charges act on the sphere.

Under the influence of external charges, a certain charge $Q$ will be induced on the replaced sphere

⟦folio 49⟧

which will be distributed accordingly over the surface of the sphere. Let's find the magnitude of this sphere.

Since the sphere is grounded, its surface potential is zero. But if there are no charges inside the conducting shell, then there is no electric field there. Therefore, the potential of any point inside the sphere is equal to the potential on its surface, that is, in our case, equal to zero.

At the same time, according to the principle of superposition, the field potential at the center of the sphere (we will consider exactly this point) is equal to the sum of the field potentials of the charges $q$ and the charge of the sphere $Q$:

$$\varphi_0 = 0 = \frac{q}{4\pi\varepsilon_0 a} + \frac{q}{4\pi\varepsilon_0 b} + \varphi_Q.$$

In order to find the field potential of a charged sphere, the volume of the surface of the sphere is divided into such small areas that the charges on them can be considered exact. Potential field in the center of the sphere from an arbitrary area is equal to

$$\varphi_i = \frac{\Delta Q_i}{4\pi\varepsilon_0 r},$$

where $\Delta Q_i$ is the charge of this section. Obviously, the field potential of the entire charge $Q$ at the center of the sphere will be equal to

$$\varphi_Q = \sum \varphi_i = \frac{1}{4\pi\varepsilon_0 r} \sum Q_i = \frac{Q}{4\pi\varepsilon_0 r}.$$

Thus,

$$\frac{q}{4\pi\varepsilon_0 a} + \frac{q}{4\pi\varepsilon_0 b} + \frac{Q}{4\pi\varepsilon_0 r} = 0,$$

where

$$Q = -qr \left( \frac{1}{a} + \frac{1}{b} \right).$$

Now it is not difficult to calculate the force acting on the sphere. Since the radius of the sphere is small compared to the distances $a$ and $b$, we can assume that the charge of the sphere $Q$ is precise and located at the center of the sphere. Therefore (see Fig. 8)

$$F = \sqrt{F_1^2 + F_2^2},$$

Where

$$F_1 = \frac{Qq}{4\pi\varepsilon_0 a^2} \quad \text{и} \quad F_2 = \frac{Qq}{4\pi\varepsilon_0 b^2}.$$

Substituting the value of the charge $Q$ found above, we finally obtain

$$F = \frac{q^2 r}{4\pi\varepsilon_0} \left( \frac{1}{a} + \frac{1}{b} \right) \sqrt{\frac{1}{a^4} + \frac{1}{b^4}}.$$

F251. The formation of the bullet's strap (Fig. 9) shows sound waves that are excited when the bullet moves. (It was possible to achieve such a formation due to the fact that areas in which the air density is different refract light rays differently.) Using a ruler, determine the approximate value of the bullet’s speed. The speed of sound in air is 340 m/s.

A spherical sound wave propagates from each point in the bullet's trajectory. These waves, adding up, give a picture that significantly depends on the relationship between the speed of the bullet and the speed of sound. If the speed of sound is greater than the speed of a bullet, then the waves that are emitted at different points do not dare to catch up with each other (Fig. 10). If the speed of the bullet is greater than the speed of sound, then the wave fronts will intersect, as shown in Fig. 11, and, adding up, these waves will form “whiskers” diverging from the bullet, similar to the “whiskers” coming from the nose of the glider. These “whiskers” represent the envelope of the fronts of spherical sound waves. Similar picture
