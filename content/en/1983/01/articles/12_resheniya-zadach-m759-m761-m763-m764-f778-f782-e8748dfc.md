---
id: 1983-1-resheniya-zadach-m759-m761-m763-m764-f778-f782-e8748dfc
issue: kvant_1983_1
year: 1983
number: "1"
title: Solutions to problems M759—M761, M763, M764; F778—F782
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 44
page_last: 50
page_labels: 42, 44, 45, 46, 47, 48
tag: T2KW
lang: en
source: kvant_digital
extraction: vision
content_sha256: 0873fa9a67a79177bed65f4f116ea8dec61412b7c30807ce7bc20d1f251796a1
prompt_sha256: draft-1
translated_from: content/ru/1983/01/articles/12_resheniya-zadach-m759-m761-m763-m764-f778-f782-e8748dfc.md
source_content_sha256: d9ea29ac3b0b7d720951419e197f8090b20432cfccdb9e24e9361f7f9eb5742e
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 42⟧

Problem solutions

M759. Inside a quadrilateral vynucle for which the sum of six pairwise distances between the vertices (that is, the sum of the lengths of all sides and diagonals) is equal to $S_1$, there is another for which this sum is equal to $S_2$.
a) Can the value $S_2$ be greater than $S_1$?
b) Prove that $S_2 < 4S_1/3$.
c) Prove that if inside an arbitrary tetrahedron with the sum of edge lengths $S_1$ there is another tetrahedron for which this sum is equal to $S_2$, then $S_2 < 4S_1/3$.

For any four points $A, B, C, D$ of a plane or space (not necessarily different), we denote by $P_{ABCD}$ the sum of the lengths of the segments connecting these points in pairs.
a) Answer: maybe. One of the examples is shown at figure 1: the first quadruple $ABCD$ is strongly elongated along the diagonal $AC$, with $|AB| = |AD| = |AC| = a$, the second - $ABCN$ - is inscribed in the first so that its vertex $N$ lies on the segment $AD$ near the point $A$. It is clear that $S_2 = P_{ABCD} > S_1 = P_{ABCD}$. Moreover, if the lengths of segments $BD$ and $AN$ are to zero, then $S_2$ will tend to $4a$, and $S_1$ to $3a$, so $S_2:S_1$ will tend to $4/3$.
b) The proof of the inequality $S_2 < 4S_1/3$ for tetrahedra is easy to obtain by slightly modifying the proof given below for tetrahedra*).
c) The solution is based on the following
Lemma (Fig. 2). If the point $H$ lies on the segment $H_1H_2$, then for any three points $E, F, G$ $P_{EFGH} \leq P_{EFGH_1}$ or $P_{EFGH} \leq P_{EFGH_2}$.

*) See also the article by V. M. Tikhomirov “On one optipad problem (p. 22).”

⟦folio 44⟧

M760. With a closed broken line $A_1A_2...A_m$, where $m$ is odd, the following operation is performed: the midpoints of its links are connected $m$ by segments through one (the middle $A_1A_2$ - with the middle $A_3A_4$, $A_2A_3$ - with $A_4A_5$, ..., $A_{m-1}A_m$ - with $A_1A_2$, $A_mA_1$ - from $A_2A_3$). The same operation is performed again with the resulting broken line, etc. Prove that from any $m$-link broken line $a$) at $m=5$ - in two steps.
b) at $m=7$ - in three steps,
c) for any odd $m$ - after a certain number of steps (depending on $m$) a broken line will be obtained, similar (further prepared) to the first initial one.

We fix an arbitrary point $O$ (we will specify its position during the solution process), then any point $A$ can be specified by the vector $\overrightarrow{OA}$ - the vector of the point $A$. If we denote the vectors of vertices of a given broken line $J$ by $\bar{a}_1 = \overrightarrow{OA}_1$, ..., $\bar{a}_m = \overrightarrow{OA}_m$, then the vectors of vertices of the broken line $J_1$, which is obtained from $J$ as a result specified in the given operation, are equal
$$\frac{1}{2} (\bar{a}_1 + \bar{a}_2), \frac{1}{2} (\bar{a}_3 + \bar{a}_4), \dots$$
$$\dots, \frac{1}{2} (\bar{a}_m + \bar{a}_1), \frac{1}{2} (\bar{a}_2 + \bar{a}_3), \dots, \frac{1}{2} (\bar{a}_{m-1} + \bar{a}_m).$$

since the vector of the middle of the segment is equal to the resulting vectors of its ends. Similarly, the vertex vectors of the next polyline are equal
$$\frac{1}{4} (\bar{a}_1 + \bar{a}_2 + \bar{a}_3 + \bar{a}_4), \frac{1}{4} (\bar{a}_5 + \bar{a}_6 + \bar{a}_7 + \bar{a}_8), \dots$$
$$\dots, \frac{1}{4} (\bar{a}_{m-3} + \bar{a}_{m-2} + \bar{a}_{m-1} + \bar{a}_m).$$

To summarize, to find the vectors of the vertices of the broken line $J_k$ you need to write down the sequence of vectors of the vertices of the broken line $J$ $2^k$ times:
$$\bar{a}_1, \bar{a}_2, \dots \bar{a}_m, \bar{a}_1, \bar{a}_2, \dots, \bar{a}_m, \dots, \bar{a}_1, \bar{a}_2, \dots, \bar{a}_m,$$
add the first $2^k$ vectors of this row, the next $2^k$ vectors, and so on, and then divide each of the resulting $m$ sums by $2^k$.

a) Using the derived rule, we find the vectors of vertices of the broken line $J_2$ for $m=5$:
$$\frac{1}{4} (\bar{a}_1 + \bar{a}_2 + \bar{a}_3 + \bar{a}_4), \frac{1}{4} (\bar{a}_5 + \bar{a}_1 + \bar{a}_2 + \bar{a}_3), \dots$$
$$\dots, \frac{1}{4} (\bar{a}_2 + \bar{a}_3 + \bar{a}_4 + \bar{a}_5)$$
or, assuming $\bar{a}_1 + \bar{a}_2 + \bar{a}_3 + \bar{a}_4 + \bar{a}_5 = \bar{a}$:
$$\frac{1}{4} (\bar{a} - \bar{a}_5), \frac{1}{4} (\bar{a} - \bar{a}_4), \frac{1}{4} (\bar{a} - \bar{a}_3), \frac{1}{4} (\bar{a} - \bar{a}_2), \frac{1}{4} (\bar{a} - \bar{a}_1).$$

Now note that the point $O$ can always be chosen so that the sum $\bar{a}$ of the vectors of the vertices of the broken line $J$ is equal to $\overrightarrow{O}$ (see the end of the solution). In this case, the vectors of the vertices of the broken line $J_2$ will be equal to $-\frac{1}{4} \bar{a}_5, -\frac{1}{4} \bar{a}_4, -\frac{1}{4} \bar{a}_3, -\frac{1}{4} \bar{a}_2, -\frac{1}{4} \bar{a}_1$, so the vertices themselves will be ready.

vertices of the broken line $J$ relative to the point $O$ with a coefficient $-1/4$ (see figure): the 1st vertex of the broken line $J_2$ corresponds to the 5th vertex $A_5$ of the broken line $J$, the 2nd - corresponds to $A_4$, the 3rd - $A_3$, 4th - $A_2$ and 5th - $A_1$. In this case, the order of connecting vertices $J_2$ will be the same as for the corresponding vertices $J$, although the direction of their traversal will be opposite.

b), c) You can always choose $k$ such that the number $2^k-1$ is divisible by the odd number $m$. (In particular, in task 6) $m=7$, and $k=3$. Indeed, the averages of numbers 1, 2, $2^2$, ... are obliged to find duya, $2^l$ and $2^n$ ($l<n$), which give the same remainders when divided by $m$. Their difference $2^n-2^l=2^l(2^n-l-1)$ is divisible by $m$ without remainder. And since $m$ is odd, it follows that at $k=n-l$ the number $2^k-1$ is divisible by $m$; let $2^k-1=mp$.

Then $2^k=mp+1$, and according to our rule for finding the vectors of vertices of the broken line $J_k$ they are represented in the form
$$\frac{1}{2^k} (p\bar{a} + \bar{a}_1), \frac{1}{2^k} (p\bar{a} + \bar{a}_2), \dots, \frac{1}{2^k} (p\bar{a} + \bar{a}_m),$$

where $\bar{a}=\bar{a}_1+\dots+\bar{a}_m$. If the point $O$ is chosen so that $\bar{a}=\overrightarrow{OA}_1+\dots+\overrightarrow{OA}_m=\overrightarrow{O}$, then the vectors of the vertices of the polyline $J_k$ are equal to $2^{-k}\bar{a}_1, \dots, 2^{-k}\bar{a}_m$, and therefore it is prepared by the polyline $J$ with the center of preparation $O$ and the coefficient $2^{-k}$.

⟦folio 45⟧

It remains to explain how to find the point $O$ we need—the homothety center. The sum of vertex vectors can be written as
$$\bar{a} = \overrightarrow{OA}_1 + \overrightarrow{OA}_2 + \dots + \overrightarrow{OA}_m = \overrightarrow{OA}_1 + (\overrightarrow{OA}_1 + \overrightarrow{A}_1\overrightarrow{A}_2) + \dots$$
$$\dots + (\overrightarrow{OA}_1 + \overrightarrow{A}_1\overrightarrow{A}_m) = m \cdot \overrightarrow{OA}_1 + (\overrightarrow{A}_1\overrightarrow{A}_2 + \dots + \overrightarrow{A}_1\overrightarrow{A}_m),$$
posnomu, if $\overrightarrow{A}_1\overrightarrow{O} = \frac{1}{m} (\overrightarrow{A}_1\overrightarrow{A}_2 + \dots + \overrightarrow{A}_1\overrightarrow{A}_m)$, then $\bar{a} = \overrightarrow{0}$. (This point $O$ is the center of gravity of identical masses placed at points $A_1, A_2, \dots, A_m$).

A. V. Kelarev, N. B. Vasiliev, A. N. Zemlyakov

**M761. Through an arbitrary point $P$ on side AC of triangle ABC, parallel to its medians AK and CL, lines are drawn intersecting sides BC and AB at points E and F, respectively (see figure).

Prove that the medians AK and CL divide the segment EF into three equal parts.

**M763*. Given a parallelogram ABCD, different from a rhombus. A straight line symmetrical to straight AB relative to diagonal AC intersects at point Q a straight line symmetrical to straight DC relative to diagonal DB. Find the relation $|QA|:|QD|$ if the relation $|AC|:|BD| = k$ is known.

Let's put $AQO = OQD = \varphi$, $QAO = \alpha$, $QDO = \beta$. Then $AOD = 2\pi - \alpha - \beta - 2\varphi$. At the same time, $AOD$ is the external angle of triangle ODC, in which $OCD = OAB = \alpha$, $ODC = \beta$ (see figure). Therefore, $AOD = \alpha + \beta$, that is, $2\pi - \alpha - \beta - 2\varphi = \alpha + \beta$. It follows that $\alpha + \beta + \varphi = \pi$ means $AOQ = \pi - \alpha - \varphi = \beta - ODQ$. Since triangles $AQO$ and $OQD$ have corresponding equal angles, they are similar with a similarity coefficient of $|AO|:|OD| = |AC|:|BD| = k$. Thus,

$$\frac{|QA|}{|QD|} = \frac{|QA|}{|QO|} \cdot \frac{|QO|}{|QD|} = k^2.$$

Comment. It is worth exploring the origin of this seemingly rather artificial task. The point is that $Q$ is a fixed point of a similarity transformation (one of two possible ones), which takes the point $A$ to $O$, and $O$ to $D$. It can be represented as a composition of turning around the point $Q$ by an angle $\varphi$ (on our figure - clockwise) and preparing $H^k_Q$. Transformations of this type are called sub-rotary numbers or spiral similarities. Thus, the construction described in the conditions of the problem allows us to find the spiral similarity $F$ if points $A, F(A) (= O)$ and $F(F(A)) (= D)$ are given. Second similarity transformation, taking points $A$ and $O$ to $O$

⟦folio 46⟧

and $D$ respectively, is a composition of axial symmetry and homotype centered on its axis. Think about how to construct its fixed point.*)

V. N. Dubrovsky

**M764**. Prove that each of the equations $a) x^2 + y^2 = z^5$; $b) x^2 + y^2 + z^5 = t^7$ has an infinite number of solutions in natural numbers.

**a) Let's try to look for solutions among powers of the same natural number $a: x = a^k, y = a^e, z = a^m$ ($k, e, m$ are natural).

Substituting such $x, y, z$ into the equation gives the equality $a^{2k} + a^{3e} = a^{5m}$. It is easy to see that for $2k \neq 3e$ such equality is impossible. Therefore $2a^{2k} = a^{5m}$. It follows that $a = 2$.

We approach $x = 2^{3n}, y = 2^{2n}$, while $x^2 + y^2 = 2^{6n+1}$, and, therefore, the number $6n+1$ must be divisible by 5.

And since $6n+1$ is divisible by 5 only at $n = 5s+4$ ($s \geq 0$), we get an infinite series of solutions:

$$x = 2^{15s+12}, y = 2^{10s+8}, z = 2^{6s+5}, s \in Z, s \geq 0.$$

b) Solved similarly to $a$). We need to look for solutions for which $x = 3^{15n}, y = 3^{10n}, z = 3^{6n}$. After substituting into the equation we get $3^{30n+1} = t^7$, but $30n+1$ is divisible by 7 for $n = 7s+3$, $s \geq 0$, $s \in Z$. We have obtained an infinite series of solutions $x = 3^{105s+45}, y = 3^{70s+30}, z = 3^{42s+18}, t = 3^{30s+13}$.

It is easy to see that in general the equation $x^2 + x^2 + \dots + x^n = y^b$ has an infinite number of solutions in integers if the least common multiple $M$ of the numbers $a_1, a_2, \dots, a_n$ is simply subtracted from $b$. As in points $a$ and $b$), solutions can be sought in the form of powers of the number $n$.

We approach $x_1 = n^{M_t}, \dots, x_n = n^{a_n}$, where $t \in N$. After substituting $x_1, x_2, \dots, x_n$ into the equation, we get the equality $n^{M_t+1} = y^b$, and since $M$ and $b$ are simply subtracted, there is an infinite number of $t$ for which $M_t+1$ is divisible by $b$.

O. V. Mazurov

**F778. The ring of mass $m$, loosely fastening two thin hoops of mass $M$, begins to contract downward; In this case, the hoop is cut in different directions along the rough horizontal surface. Determine the acceleration of the ring at the initial moment of time if uell $AO_1O_2$ (see figure) is equal to $a$. There is no friction between the ring and the hoops.**

Let us assume that in a short period of time $\Delta t$ after the system began to move, the ring descended to a distance $\Delta x$ from point $A$ and acquired a speed $v$. The speed of translational movement of the hoops at this moment should be equal to $u = vtg\alpha$ ($\Delta t$ is so small that the angle $\alpha$ has practically not changed). Therefore, the linear speed of all points of the hoops is the same. According to the law of conservation of energy,

$$mg \cdot \Delta x = 2Mu^2 + m \frac{v^2}{2} = 2Mv^2tg^2\alpha + m \frac{v^2}{2}$$

($Mu^2$ is the total kinetic energy of each hoop at a given moment). From this equality we find,

$$a = g \frac{1}{1 + 4\frac{M}{m}tg^2\alpha}.$$

S. S. Krotov

*) More information about similarity transformations and their applications in geometry can be read in the following books: I. M. Yaglom “Geometric transformations”, vol. 1, (M., Gostekhtoridat, 1955) and G. S. M. Koketer, S. L. Greytzer “New encounters with geometry” (M., “Hayka”, 1978).

⟦folio 47⟧

F779. A square consisting of two halves whose mass ratio is equal to two is located on a rough surface. At what angle α to the interface between the halves must the surface plane be pulled in order for the square to move forward? The point of application of the force lies at the intersection of the side of the square and the interface.

Let the square move forward and at the same time the thread makes an angle α with the straight line AB (see Fig.nok). The friction force acting on the left half of the square is directed against the movement of the square and passes through the center of mass of the left half (we assume that the normal pressure force is evenly distributed over the contact surface of the square with the horizontal plane). The absolute value of this force is equal to

$$F_1 = \mu m_1 g,$$

where μ is the friction coefficient, $m_1$ is the mass of the left half of the square. The friction force acting on the right half of the square passes through the center of mass of the entire square. Consequently, the lines of action of the force with which the rope is pulled must pass through the center of mass of the square (point O on Fig.н), that is, the rope must make an angle α with the lines AB such that (see Fig.н)

$$tg \alpha = x/a.$$

The value of x is found from the condition of equality of the moments of forces $F_1$ and $F_2$ relative to the center of mass of the square:

$$\mu m_1 g \left( \frac{a}{2} - x \right) \cos \varphi = \mu m_2 g \left( \frac{a}{2} + x \right) \cos \varphi,$$

where

$$x = \frac{a (m_1 - m_2)}{2 (m_1 + m_2)}.$$

Considering that $m_1/m_2 = 2$, we find tanα:

$$tg \alpha = \frac{x}{a} = \frac{1}{6}.$$

E. S. Aliev

F780. A cylindrical vessel of height 2h, equally divided by a partition, contains water in the upper part (its density Q) and air at atmospheric pressure $p_0$ in the lower part. A small hole opens in the partition so that water begins to flow into the lower part of the vessel. How thick will the layer of water be at the bottom of the vessel when air begins to flow upward from the hole? The temperature is constant. The acceleration of the force of the weight is g.

Air from the bottom of the vessel begins to pass upward through the hole when its pressure exceeds the hydraulic pressure of water at the level of the hole, that is, at pressure

$$p = p_0 + \varrho g (h - x),$$

where x is the lowering of the water level in the upper part of the vessel and, accordingly, the thickness of the water layer in the lower part of the vessel. Since the air temperature does not change, according to the Boyle-Mariotte law

$$p_0 h S = p (h - x) S,$$

where S is the area of ​​the bottom of the vessel.

Thus,

$$p_0 (h - x) + \varrho g (h - x)^2 = p_0 h,$$

where

$$\varrho g x^2 - (2 \varrho g h + p_0) x + \varrho g h^2 = 0.$$

Solving this equation, we find x:

$$x = h + \frac{p_0}{2 \varrho g} \left( 1 - \sqrt{1 + \frac{4 \varrho g h}{p_0}} \right).$$

(The solution x = h + \frac{p_0}{2 \varrho g} \left( 1 + \sqrt{1 + \frac{4 \varrho g h}{p_0}} \right) is not suitable, since x < h is completed.)

⟦folio 48⟧

F781. Between two independent metal concentric spheres of radii a and b there is an exact charge q at a distance c from the center of the sphere. What charge will flow through a thin conductor if the spheres are closed with it?

At first the small sphere was not charged. After the sphere is closed, a neoctor charge is transferred to it, which is distributed unevenly over its surface. Let us denote the magnitude of this charge $q_1$. In this case, a charge $q_2$ will appear on the inner surface of the large sphere, which is also unevenly distributed over this surface. The field lines created by the charge q end on the small sphere and on the inner surface of the large sphere. Therefore, the charge of $q_2$ must be equal to

$$q_2 = -(q + q_1).$$

Since these drain lines do not penetrate the disturbance through just the large sphere, the charge on the outer surface of this sphere is distributed evenly and does not create a field between the inner and outer spheres. This means that by equating the potentials of the inner and outer spheres (the spheres are connected by a conductor), this charge can be ignored, and the potential of the outer sphere can be taken equal to zero. Then the potential at the center of the sphere will also be equal to zero (there is no field inside the small sphere and the potential of the small sphere is equal to the potential at the center of the sphere).

Thus,

$$\frac{q_1}{4\pi\varepsilon_0 a} + \frac{q_2}{4\pi\varepsilon_0 b} + \frac{q}{4\pi\varepsilon_0 c} = 0.$$

Substituting $q_2 = -(q + q_1)$, from this condition we find $q_1$:

$$q_1 = -q \frac{\frac{1}{c} - \frac{1}{b}}{\frac{1}{a} - \frac{1}{b}}.$$

It is clear that the magnitude of the charge $q_1$ does not depend on the initial charges of the sphere and is determined only by the magnitude of q and the dimensions of the system. All the “extra” charge will be located on the outer surface of the large sphere, determining the potential of the conductor as a whole. It is interesting to note that when the charge q moves (as c changes), the value of $q_1$ (and therefore both $q_2$ and $q_{\text{внешш}}$) can change; therefore, the field outside can also change. The internal field of such a spherical “screen” does not depend on the magnitude and location of external charges.

V. I. Komov

F782. The capacitor was charged to a voltage of $U_0 = 100$ V and a resistor was connected to it. At the same time, over a certain time interval, $W_1 = 1$ J of veal was released, and over the same interval, $W_2 = 0,3$ J of energy was released. Determine the capacitance of the capacitor.

Let the voltage across the capacitor decrease to $U_1$ by the end of the first interval. According to the law of conservation of energy,

$$\frac{CU_0^2}{2} = W_1 + \frac{CU_1^2}{2},$$

where

$$U_1 = U_0 \sqrt{1 - \frac{2W_1}{CU_0^2}}.$$

It is clear that if the initial voltage on the capacitor was n times less than $U_0$, then during the same time interval, veal would be released on the resistor $n^2$ times less than $W_1$. This means that

$$\frac{W_2}{W_1} = \frac{U_1^2}{U_0^2}$$

($U_1$ is the initial voltage for the next time interval). Substituting the previously obtained value $U_1$ into this expression, we find C:

$$C = \frac{2W_1}{U_0^2 \left(1 - \frac{W_2}{W_1}\right)} \approx 29 \text{ мкФ}.$$

A. R. Zilberman
