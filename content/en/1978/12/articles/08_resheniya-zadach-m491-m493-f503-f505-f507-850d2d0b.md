---
id: 1978-12-resheniya-zadach-m491-m493-f503-f505-f507-850d2d0b
issue: kvant_1978_12
year: 1978
number: "12"
title: Solutions to problems M491—M493; F503, F505—F507
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 26
page_last: 35
page_labels: 24-33
tag: ZOFL
lang: en
source: kvant_digital
extraction: vision
content_sha256: 9d016eaade999eb185840b68068c7edebbcd1e1fdfb0c0d92442bc5afa9a557d
prompt_sha256: draft-1
translated_from: content/ru/1978/12/articles/08_resheniya-zadach-m491-m493-f503-f505-f507-850d2d0b.md
source_content_sha256: 5c475750fe0dd817338690131b4f3b2f670938a6fdff17716e937a0777ecd7c4
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 24⟧

Problem solutions
M491—M493; F503, F505—F507

M491. The distance of the geometric cut, all the parts are filled with numbers. (For example, 16, 24, 36, 54, 81.)
a) Prove that the sum of the squares of three consecutive cut goals is divisible by the sum of these goals.
b) At what natural n values ​​does the sum of the squares of n successive cut goals divide by the sum of these n goals?

We will first solve problem M491 - we will prove the statement in point a) and answer the question in point 6), and then we will formulate a statement from which both points of the problem will follow.

a) Let us denote three consecutive targets of our cutting through $a_1, a_2, a_3$ (all $a_i$ are number targets). Since $a_1 a_3 = a_2^2$, we get
$$\left( a_1 + a_2 + a_3 \right)^2 = \left( a_1^2 + a_2^2 + a_3^2 \right) + 2 a_2 \left( a_1 + a_2 + a_3 \right),$$
follow
$$a_1^2 + a_2^2 + a_3^2 = \left( a_1 + a_2 + a_3 \right) \left( a_1 - a_2 + a_3 \right)$$
- which was what needed to be proven.

6) It is easy to give an example of a geometric cutting in which the sum of the squares of four consecutive goals will not be divided by the sum of these goals: for cutting 1, 2, 4, 8, 16, ... the sum $1^2 + 2^2 + 4^2 + 8^2 = 85$ is not divisible by the sum $1 + 2 + 4 + 8 = 15$. In general, for this notch, the sum of the squares of the first 2k goals $1 + 2^2 + 2^4 + \dots + 2^{4k-2} = (2^{4k} - 1)/3$ is not divisible by the sum of these goals $1 + 2 + 2^2 + \dots + 2^{2k-1} = 2^{2k} - 1$, since $2^{2k} + 1$ is not divisible by 3 or some $k$. Therefore even $n$ are not suitable. If $n$ is odd ($n = 2k + 1$), then the sum of squares $n$ is consistently even on the 所学 cut is necessarily divided by the sum of these goals. This statement is true and follows from the presentation
$$a_1^2 + a_2^2 + \dots + a_{2k+1}^2 = \left( a_1 + a_2 + \dots + a_{2k+1} \right) \times \left( a_1 - a_2 + a_3 - a_4 + \dots - a_{2k} + a_{2k+1} \right),$$
which is easy to prove, for example, by induction.

Now let’s formulate and prove the statement mentioned above.

Theorem. If the numbers $k$ and $n$ are coprime, then the sum of $k-x$ powers $n$ successively of cutting goals, all of which are components of the number, is necessarily divided by the sum of these goals.

(Since the numbers 3 and 2 are relatively prime, this statement implies point a) of problem M491 and the answer to point b) - for odd $n$.)
Proof. Let us denote these $n$ successive cutting targets by $a_1, a_2, \dots, a_n$. We want to prove that the sum $a_1^k + a_2^k + \dots + a_n^k$ is divisible by the sum $a_1 + a_2 + \dots + a_n$ (assuming that $k$ and $n$ are coprime). Let $q$ be the denominator of the cut. Then
$$a_1 + a_2 + \dots + a_n = a_1 (1 + q + \dots + q^{n-1}),$$
$$a_1^k + a_2^k + \dots + a_n^k = a_1^k (1 + q^k + \dots + q^{(n-1)} k).$$
Let us prove that if $k$ and $n$ are coprime, then the polynomial $1 + x^k + \dots + x^{n-1}$ is divisible by the polynomial $1 + x + \dots + x^{n-1}$.*) In the proof we will need two auxiliary lemmas.

*) Here and throughout below, when speaking about the divisibility of polynomials, we mean that all coefficients of a quotient are an integer.

⟦folio 25⟧

Lemma 1. If the numbers $k$ and $n$ are coprime, then the numbers $k, 2k, 3k, \dots, (n-1)$ $k$ when divided by $n$ give different remainders.

Lemma 2. If the numbers $l$ and $m$ give the same remainders when divided by $n$, then the polynomial $x^l - x^m$ is divisible by the polynomial $1 + x + \dots + x^{n-1}$.

Lemma 1 proves the method by contradiction. In fact, if for some $i$ and $j$ ($0 < i < j < n$) the numbers $ik$ and $jk$ give the same remainder when divided by $n$, then the number $(j-i)$ $k$ is completely divisible by $n$. But the number $j-i < n$; This means that the numbers $k$ and $n$ must have a common divisor other than one, a contradiction with mutual prime.

Since the number of distinct remainders (not zero!) from division by $n$ is equal to $n-1$, it follows from Lemma 1 that if the numbers $k$ and $n$ are coprime, then among the remainders from division by $n$ the numbers $k, 2k, \dots, (n-1)$ $k$ are all numbers from $1$ to $n-1$ meet once.

Let us prove Lemma 2. Let $l > m$ and $l = m+pn$. The polynomial $x^m - x^l = (1-x^{pn})x^m$ is divisible by $1-x^n$:

$$1-x^{pn} = (1-x^n) (1+x^n+x^{2n}+\dots+x^{(p-1)n}),$$

and $1-x^n$ is divisible by $(1-x)$, and

$$(1-x^n) = (1-x) (1+x+x^2+\dots+x^{n-1}).$$

This implies the statement of Lemma 2.

Let us now proceed to prove that the polynomial $1+x^k + \dots + x^{(n-1)k}$ is divisible by $1+x + \dots + x^{n-1}$. Let us denote by $k_i$ the remainder of division by $n$ of the number $ik$. Then, by Lemma 2, the polynomial $(x^k - x^{k_1}) + (x^{2k} - x^{k_2}) + \dots + (x^{(n-1)k} - x^{k_{n-1}})$ is divisible by the polynomial $1+x + \dots + x^{n-1}$. It remains to note that, by virtue of the corollary to Lemma 1, the polynomial $1+x^{k_1} + x^{k_2} + \dots + x^{k_{n-1}}$ coincides with the polynomial $1+x + \dots + x^{n-1}$ and, therefore, is divisible by it. Thus,

$$1+x^k + x^{2k} + \dots + x^{(n-1)k} = (1+x + \dots + x^{n-1}) \times (c_0 + c_1x + c_2x^2 + \dots + c_px^p),$$

where $p = (k-1)(n-1)$ and $c_0, c_1, \dots, c_p$ are some numbers. Hence,

$$a_1^k + a_2^k + \dots + a_n^k = a_1^k (1+q^k + \dots + q^{(n-1)k}) = a_1^k (1+q + \dots + q^{n-1}) (c_0 + c_1q + c_2q^2 + \dots + c_pq^p) = (a_1 + a_2 + \dots + a_n) \times (c_0 a_1^{k-1} + c_1 a_1^{k-1} q + \dots + c_p a_1^{k-1} q^p).$$

To complete the proof of the theorem, it is enough to show that the numbers $a_1^{k-1}q, a_1^{k-1}q^2, \dots, a_1^{k-1}q^p$ are integers. Indeed, the number $a_1^{k-1}q$ is an integer, since it is represented as a product of integers: $a_1^{k-1}q = a_1^{k-2}a_2$. Likewise, $a_1^{k-1}q^2 = a_1^{k-2}a_3$, $\dots, a_1^{k-1}q^p = (a_1q^{n-1})^{k-1} = a_n^{k-1}$.

Try to construct examples showing that the requirement for mutual simplicity of $k$ and $n$ in the statement of the theorem exists.

A. Adaev, G. Gurevich, F. Kadirov

**M492. Triangle $A_1B_1C_1$ is described in triangle ABC (assuming that vertices $A_1, B_1$ and $C_1$ lie, respectively, on sides BC,**

We will present two solutions to this problem: the first is more “mechanical”, the second is more “geometric”.
First decision. Let us place masses $a, b$ and $c$ at the vertices of triangle $ABC$ so that the center of gravity of this mass system falls at point $P$. Enough for this

⟦folio 26⟧

CA and AB), and the segments AA₁, BB₁ and CC₁ intersect at one point P. Prove that the lines connecting the midpoints of the sides AB and A₁B₁, BC and B₁C₁, CA and C₁A₁ intersect at one point P, Q and the center of triangle ABC lies on the same straight line.

Fig. 1.

Fig. 2.

the fulfillment of two conditions: condition $\frac{|AB_1|}{|B_1C|} = \frac{c}{a}$, which guarantees that the center of gravity belongs to the straight line BB₁, and condition $\frac{|AC_1|}{|C_1B|} = \frac{b}{a}$, which guarantees that the center of gravity belongs to straight CC₁. (Then $\frac{|BA_1|}{|A_1C|} = \frac{c}{b}$; thereby we have successfully proved Ceva’s theorem:

$$\frac{|AB_1|}{|B_1C|} \cdot \frac{|CA_1|}{|A_1B|} \cdot \frac{|BC_1|}{|C_1A|} = 1.$$

Let us now add a load of mass $m = a + b + c$ (Fig. 1) to each vertex. The center of gravity Q of the entire system of weights can be found by connecting points P (center of gravity of the first initial system) and M (center of gravity of triangle ABC) with a segment and dividing it in the ratio $\frac{a+b+c}{3m} = \frac{1}{3}$, counting from point M.

On the other hand, the masses at the vertices A (2a+b+c), B (2b+a+c), C (2c+a+b) can be distributed into “subsystems” as follows: parts of the masses A (a+c) and B ((a+c) b/a) are replaced by the mass C₁ ((a+c) (a+b)/a); parts of masses A(a+b) and C ((a+b) c/a) - mass B₁ ((a+c) (a+b)/a). Two equal masses formed at points B₁ and C₁ have a gravity center in the middle [B₁C₁]. The masses remaining at vertices B and C also turn out to be equal (although they can also turn out to be negative, as in figure 2):

$$m+b - \frac{(a+c) b}{a} = m+c - \frac{(a+b) c}{a} = m - \frac{bc}{a},$$

and therefore their center of gravity is in the middle [BC]. This means that the center of gravity Q of the entire system lies on the straight line connecting the midpoints of the segments B₁C₁ and BC.

Similarly, it is proved that Q lies on the other two lines mentioned in the condition. To translate our mechanical solution into mathematical language, it is enough to define the “center of gravity” of the mass system. Let A₁ be points of the plane, m₁ be arbitrary numbers (i = 1, 2, ..., n), “total mass” m₁+m₂+...+mₙ = M ≠ 0. The center of the weight stack C = C {A₁(m₁)} is determined by the condition: for some (and then for any) point O of the plane $\overrightarrow{OC} = (m_1\overrightarrow{OA}_1 + \cdots + m_n\overrightarrow{OA}_n)/M$. (This definition is also valid for negative m₁.) It is not difficult to check the only fact that we obtain in the solution: if m₁ = m'₁ + m'₂, Σm'₁ = M' and Σm'₂ = M'', then the center of gravity C = C {A₁(m'₁)} lies on the straight line C'C'', where C' = C {A₁(m'₁)}, C'' = C {A₁(m'₁)}, and $\overrightarrow{OC} = (M'\overrightarrow{OC}' + M''\overrightarrow{OC'})/M$.

For more information about the “barnimetric calculus” that we used in this solution, see the book by M. B. Balk “Geometric applications of heavy stacks.” Second solution. Let us denote the midpoints of the side BC; AC and AB, corresponding through X, Y and Z, and the midpoints of the side B₁C₁, A₁C₁ and A₁B₁ - through X₁, Y₁ and Z₁ (Fig. 3). Let's place unit masses at points A, B, C and P and look for the center of gravity of this system of mathematical points.

Let X₂, Y₂ and Z₂ be the midpoints of the segments AP, BP and CP. Since the center of gravity of points B and C is at point X, and the center of gravity of points A and P is at point X₂, then the center of gravity of the entire system lies on the straight line XX₂. By similar principles, it lies on the lines YY₂ and ZZ₂. Since the center of gravity of the system of mathematical points exists, the only one that belongs to all these lines at the same time, these lines intersect at one point; let us denote it by Q (see Fig. 3)

⟦folio 27⟧

Fig. 3.

Fig. 4.

Fig. 5.

On the other hand, if $S$ is the center of gravity of triangle $ABC$ (i.e., the point of intersection of its medians), then the center of gravity of the system of points $\{A, B, C, P\}$ lies on the segment $PS$. We showed above that the center of gravity of this system is at point $Q$; means $Q \in [PS]$. Moreover, since in order to find the center of gravity of the system $\{A, B, C, P\}$ in the last way we must place a mass of three units at point $S$, point $Q$ divides the segment $PS$ in a ratio of 3:1.

If we show that the lines $XX_2, YY_2, ZZ_2$ pass through the points $X_1, Y_1$ and $Z_1$, respectively, then the problem will be solved. The last statement follows from the following theorem applied to the quadrilaterals $PA_1BC_1, PB_1AC_1$ and $PA_1CB_1$:

Gauss's theorem. If no sides of the quadrilateral are parallel, then the midpoint of the segment connecting the points of intersection of the extended and opposite lines lies on the line connecting the midpoints with a diagonal.

To prove that three points belong to a straight line, the following concepts are used, which are almost obvious: criterion (necessary and sufficient condition); prove it yourself.

Let $K$ be the interior point of parallelogram $A_1A_2A_3A_4$. Let us draw through $K$ the straight lines parallel to the sides of the parallelogram, and denote through $B_1, B_2, B_3, B_4$ the points of intersection of these lines on its side (Fig. 4). Point $K$ lies on the diagonal $A_1A_3$ of the parallelogram of the model and milk of the model when $S_{KB_1A_2B_2} = S_{KB_3A_4B_4}$ (we use $S$ here to denote the area).

Proof of Gauss's theorem. Let us denote the vertices of the quadrilateral by $A, B, C, D$, the points of intersection of the extension of its opposite sides by $E$ and $F$, and the midpoints of the diagonals $AC, BD$ and the segment $EF$, respectively, by $X, Y$ and $Z$. Let us draw through the points $D, C$ and $F$ lines parallel to the lines $AF$ and $AE$, and use the notation as in figure 5.

It is obvious that points $C, L$ and $R$ are prepared, respectively, points $X, Y$ and $Z$ with center prepared $A$ and coefficient prepared $2$. Therefore, the point $X, Y, Z$ belonging to one straight line is equivalent to the points $C, L$ and $R$ belonging to the same straight line.

⟦folio 28⟧

From the above criterion it follows that the point $L$ belongs to the line $CR$ if the equality $S_{LMPQ} = S_{LNTS}$ is satisfied. Let us prove that this is indeed the case.

Since the point $C$ belongs to the diagonals of parallelograms $AFQD$ and $ABSE$ (see Fig. 5), we have: $S_{AGCH} = S_{CNQP}$ and $S_{AGCH} = S_{CMST}$. Therefore $S_{CNQP} = S_{CMST}$, and therefore $S_{LMPQ} = S_{LNTS}$, which is what was required. The decision is legal.

F. Vayshtein, N. Vasiliev

M493. Proving inequality
$0,785n^2 - n < \sqrt{n^2 - 1} + \sqrt{n^2 - 2^2} + \dots + \sqrt{n^2 - (n - 1)^2} < 0,79n^2$.

Fig. 6.

Fig. 7.

Let's take a quarter of a circle of unit radius: $O$ is the center of the circle, $[OA]$ is the radius, $|OA| = 1$ (Fig. 6). Let us divide the segment $OA$ into $n$ congested parts ($n$ is an arbitrary natural number). On the resulting first $n - 1$ division segments (counting from point $O$), we construct a long straight line so that at the highest, the upper vertices of all rectangles lie on the arc of the circle $BA$, limiting our “quarter circle” (see Fig. 6). We get $n - 1$ rectangles, the sum of the areas of which is less than a quarter of a circle of unit radius, that is, less than $\frac{\pi}{4} < 0,79$.

Since this amount is equal
$$\frac{1}{n} \sqrt{1 - \left(\frac{1}{n}\right)^2} + \frac{1}{n} \sqrt{1 - \left(\frac{2}{n}\right)^2} + \dots +$$
$$+ \frac{1}{n} \sqrt{1 - \left(\frac{n - 1}{n}\right)^2} = \frac{1}{n^2} \left(\sqrt{n^2 - 1} + \sqrt{n^2 - 2^2} + \dots + \sqrt{n^2 - (n - 1)^2}\right),$$

From what has been said, the right inequality follows.

To prove the left inequality, we proceed as follows. Let us now construct a rectangle on all segments that received $[OA]$ during division—a total of $n$ rectangles, and so that all the upper left vertices of the rectangles lie on the arc $BA$ of the circle (Fig. 7). We will get the 7-step figure depicted in figure, the area of ​​which is already more than six quarters of a circle of unit radius, that is, more than $\frac{\pi}{4} > 0,785$.

The area of ​​a stepped figure is equal to the sum of the areas $n$ of rectangles with bases of length $\frac{1}{n}$ and heights of length
$$1, \sqrt{1 - \left(\frac{1}{n}\right)^2}, \sqrt{1 - \left(\frac{2}{n}\right)^2}, \dots, \sqrt{1 - \left(\frac{n - 1}{n}\right)^2}$$

respectively:
$$\frac{1}{n} \left(1 + \sqrt{\frac{n^2 - 1}{n^2}} + \sqrt{\frac{n^2 - 2^2}{n^2}} + \dots + \sqrt{\frac{n^2 - (n - 1)^2}{n^2}}\right).$$

So,
$$\frac{1}{n^2} \left(n + \sqrt{n^2 - 1} + \sqrt{n^2 - 2^2} + \dots + \sqrt{n^2 - (n - 1)^2}\right) > 0,785,$$

where
$$0,785n^2 - n < \sqrt{n^2 - 1} + \sqrt{n^2 - 2^2} + \dots + \sqrt{n^2 - (n - 1)^2}.$$

A. Sivachky

⟦folio 29⟧

F503. A thread of length 2l is tied to the vertical axis, at the end and in the middle of the
identical balls are attached to the swarm (Fig. 8). The axis is brought to the doctor with a
left speed $\omega$. At what value of the catch rate are the sections OA and AB
Let's start deviating from the vertical? What will be the ratio of small catches deviation
of the sections of the thread OA and AB from the vertical?

Let, at a certain catch rotation speed $\omega$, the threads OA and AB deviate from the vertical by small angles $\alpha$ and $\varphi$, respectively (Fig. 9). In this case, the balls rotate uniformly at a catch speed $\omega$ along circles lying in horizontal planes. The radii of these circles are equal to the corresponding forces applied to it - the tension force $mg$ (m is the mass of the ball), the force $\vec{N}_1$ tension of the thread OA and the force $\vec{N}_2$ tension of the thread AB. The centripetal acceleration $\omega^2 r_2$ is imparted to the lower ball by the equal forces $mg$ and $\vec{N}_2$. Let's find the forces $\vec{N}_1$ and $\vec{N}_2$.

The lower ball does not move in the vertical direction; hence,

$$|mg| = |\vec{N}_2| \cos \varphi \Rightarrow |\vec{N}_2| = \frac{|mg|}{\cos \varphi}.$$

The top ball also does not move vertically; hence,

$$|mg| + |\vec{N}_2| \cos \varphi = 2 |mg| = |\vec{N}_1| \cos \alpha \Rightarrow |\vec{N}_1| = \frac{2 |mg|}{\cos \alpha}.$$

Now let's write down the equation of motion of the balls in a circle: for the lower ball—

$$m\omega^2 l (\sin \alpha + \sin \varphi) = |\vec{N}_2| \sin \varphi = |mg| \ tg \ \varphi,$$

(1)

for the top ball—

$$m\omega^2 l \sin \alpha = |\vec{N}_1| \sin \alpha - |\vec{N}_2| \sin \varphi =$$

$$= 2 |mg| \ tg \ \alpha - |mg| \ tg \ \varphi.$$

(2)

Since angles $\alpha$ and $\varphi$ are small, we can count $\sin \alpha = \alpha$, $\sin \varphi = \varphi$, $tg \alpha = \alpha$, $tg \varphi = \varphi$. Taking this into account, from (1) and (2) we obtain

$$\omega^2 l (\alpha + \varphi) = |\vec{g}| \ \varphi, \ \omega^2 l \alpha = |\vec{g}| (2 \alpha - \varphi),$$

or

$$\omega^2 l \alpha + \varphi (\omega^2 l - |\vec{g}|) = 0,$$

$$(\omega^2 l - 2 |\vec{g}|) \alpha + \varphi |\vec{g}| = 0.$$

From these two expressions we find:

$$\frac{\alpha}{\varphi} = \frac{|\vec{g}| - \omega^2 l}{\omega^2 l} = \frac{|\vec{g}|}{2 |\vec{g}| - \omega^2 l},$$

(3)

which allows us to write the following equation for $\omega^2$:

$$(\omega^2)^2 l^2 - 4 |\vec{g}| l \omega^2 + 2 |\vec{g}|^2 = 0.$$

From here is

⟦folio 30⟧

F505. Distance of the capacitor charging circuit from the battery (Fig. 11). The capacitor is charged to battery voltage $U$, coastal energy $\frac{C_1 U^2}{2}$ and charge $q = C_1 U$. This charge is drawn from the battery, komorai, maxim, we do the work $q U = C_1 U^2$. The efficiency factor is 1/2. The name of the capacitor charge to the battery voltage with high efficiency. There is no reason to use additional energy sources.

Fig. 10.

$$\omega_1^2 = \frac{|\vec{g}|}{l} (2 \pm \sqrt{2}),$$
$$\omega_1 = \sqrt{\frac{|\vec{g}|}{l}} (2 + \sqrt{2}),$$
$$\omega_2 = \sqrt{\frac{|\vec{g}|}{l}} (2 - \sqrt{2})$$

(the values ​​$\omega'_1 = -\omega_1$ and $\omega'_2 = -\omega_2$ correspond to the expression in the opposite direction). Since $\omega_2 < \omega_1$, it is natural to assume that the magnetic threads begin to deviate from the vertical at the angular velocity of rotation $\omega = \omega_2$.

Let us find the ratio of small angles of deviation of threads $OA$ and $AB$ from the vertical. From expression (3) we have

$$\text{при } \omega = \omega_1 - \frac{\alpha}{\varphi} = -\sqrt{2},$$
$$\text{при } \omega = \omega_2 - \frac{\alpha}{\varphi} = \sqrt{2}.$$

The fact that at $\omega = \omega_1$ $\frac{\alpha}{\varphi} < 0$ means that at such an angular velocity the threads $OA$ and $AB$ are deflected from the vertical in opposite directions (Fig. 10.).

G. Budaenko

◆

I. Let's take another capacitor, the capacitance of which is $C_2 = n C_1$ ($n$ is a certain number), and connect it to the target in series with the capacitor of capacitance $C_1$ (Fig. 12). The capacitance in such a circuit is $C = \frac{C_1 C_2}{C_1 + C_2} = \frac{n}{n+1} C_1$.

The charges that the capacitors will acquire are equal to

$$q_1 = q_2 = \frac{n}{n+1} C_1 U,$$

and the voltage across the capacitors is

$$U_1 = \frac{q_1}{C_1} = \frac{n}{n+1} U,$$
$$U_2 = \frac{q_2}{C_2} = \frac{1}{n+1} U.$$

Having disconnected the charged capacitors from the battery, we assemble the circuit shown in figure 13. The voltage on the capacitors in such a circuit is $U'_1 = U'_2 = \frac{q'_1}{C_1} = \frac{q'_2}{C_2} = \frac{q'_2}{n C_1}$, where $q'_1, q'_2$ are the charges that will be established on the capacitors. According to the law of conservation of charges $q'_1 + q'_2 = \frac{2n}{n+1} C_1 U$. Having solved the system of equations

$$\begin{cases} q'_1 + q'_2 = \frac{2n}{n+1} C_1 U, \\ \frac{q'_1}{C_1} = \frac{q'_2}{n C_1}, \end{cases}$$

we find: $q'_1 = \frac{2 n}{(n+1)^2} C_1 U$, $U'_1 = \frac{2 n}{(n+1)^2} U$.

Now the capacitor $C_1$, charged to voltage $U'_1$, approaches the new battery (see Fig. 11). At the same time he

⟦folio 31⟧

will be recharged to voltage $U$. The capacitor charge will increase by
$$\Delta q = C_1 (U - U'_1) = \frac{n^2 + 1}{(n + 1)^2} C_1 U.$$
Thus, the total charge $Q$ that capacitor $C_1$ received from the battery is equal to
$$Q = q_1 + \Delta q = \frac{2 n^2 + n + 1}{(n + 1)^2} C_1 U.$$
The energy that the capacitor will acquire is equal to
$$\Pi = \frac{C_1 U^2}{2}.$$
The work $A$ performed by the battery when charging the capacitor to voltage $U$ is equal to
$$A = QU = \frac{2 n^2 + n + 1}{(n + 1)^2} C_1 U^2.$$
So the efficiency is
$$\eta = \frac{\Pi}{A} = \frac{(n + 1)^2}{2 (2 n^2 + n + 1)}.$$
For the value of $\eta$ to be greater than 1/2, it is necessary that the inequality
$$\frac{(n + 1)^2}{2 n^2 + n + 1} > 1.$$
From here we find that $n < 1$.
So, by charging capacitor $C_1$ to voltage $U$, we add more efficient use of the battery ($\eta > \frac{1}{2}$), if in the process described above we additionally use capacitor $C_2$, the capacity of which is less than $C_1$.
Those who are familiar with the method of finding extrema using an arbitrary one can find that in the descriptive process $\eta = \eta_{\max}$ at $n = 1/3$ ($\eta_{\max} \approx 57\%$).
Using not one, but two, three or more additional capacitors, you can come up with many different charging methods. With a sufficiently large number of additional capacitors, the efficiency can be made as close to unity as desired.
II. Let us describe another charging method in which an efficiency close to unity can be achieved.
Let's assemble the target shown at figure 14. When the battery is connected to the target (switch $K$ in position 1), the current through the coil begins to gradually increase. Let's wait to determine the time until the charge $\frac{CU}{2}$ flows through the target.
During this time, the battery will do work $\frac{CU^2}{2}$, part of which $-\frac{CU^2}{8}$ will go into the energy of the capacitor, and the rest will be stored in the magnetic field of the coil. The Terrier will quickly move the key $K$ to position 2. For some time, the current through the coil will continue to flow in directional mode, gradually decreasing. The capacitor will then recharge. At the moment when the current in the coil becomes zero, we quickly move the key $K$ to position 1. While the key $K$ is in position 2, the energy of the magnetic field of the coil is converted into the energy of the capacitor. Thus, since the target energy is not dissipated (we neglect the resistance of the coil, battery, etc.), all the energy $\frac{CU^2}{2}$ consumed from the battery will be converted into energy

⟦folio 32⟧

F506. Under the piston of the cylinder there is a rumv, occupying the volume $V_p$, and k moles of ideal gas. The surface area of ​​the piston is $S$. The piston and the bottom of the cylinder are made of a material that is ideally wetted by the cylinder. The volume under the piston is symmetrically relative to the cylinder axis in the form shown in figure 15. The force $F$ acts on the piston. 1) Derive the equation of state of the system rumv + eaz in the form $p = f(V, T)$, $p$ – pressure, $T$ – abscess temperature, $V$ – volume of the part of the vessel under the piston. 2) Named at which $p = 0$. Surface of the natural surface σ. We do not take into account the power of gentleness. Let us accept that the volume of the room and its surface area σ are constructed (that is, they do not depend on $T$ and $p$) and that $h \ll r$.

Fig. 15.

Fig. 16.

The forces acting on the piston are the force $\vec{F}_p$ of the liquid pressure and the force $\vec{F}_r$ of the gas pressure. $|\vec{F}_p| = p_p S_p$, $|\vec{F}_r| = p_r (S - S_p)$, where $p_p$, $p_r$ – pressure of rumv and gas, $S_p$ – area of ​​the piston, covered with rum.

The gas pressure is

$$p_r = \frac{kRT}{V_r} = \frac{kRT}{V - V_p},$$

where $V_r$ is the volume occupied by the gas. Since the surface of the rut-gas boundary is curved, the pressure “below” this surface is the gas pressure, greater than the pressure “above” it, that is, the rut pressure.

Let us consider a small section of the surface of the ruthen-gas boundary (Fig. 16). Since $r \gg h$, we can assume that this surface is the surface of a half-pylinder. Let us mentally select the parallelepid in which this surface fits (see Fig. 16). It is acted upon by gas pressure forces $|\vec{f}_r| = p_r s = p_r lh$, gas surface forces $|\vec{f}_p| = p_p s = p_p lh$ and gas surface forces $|\vec{f}_{пов}| = \sigma l$. From the equilibrium condition of this parallelepid it follows that

$$p_r lh = p_p lh + 2 \sigma l,$$

where

$$p_p = p_r - \frac{2 \sigma}{h}.$$

The forces with which the gas and the mercury press on the piston are equal

$$|\vec{F}_r| = p_r (S - S_p) = \frac{kRT}{V - V_p} (S - S_p),$$

$$|\vec{F}_p| = p_p S_p = \left( \frac{kRT}{V - V_p} - \frac{2 \sigma}{h} \right) S_p.$$

Since $h \ll r$, we can assume that $S_p = V_p/h$. Considering that $h = V/S$, we find the total force acting on the piston:

$$|\vec{F}_r| + |\vec{F}_p| = p_c p S = \frac{kRT}{V - V_p} S - \frac{2 \sigma V_p S^2}{V^2},$$

where $p_c$ is the average pressure on the piston. From here

$$p_c = \frac{kRT}{V - V_p} - \frac{2 \sigma V_p S^2}{V^2}.$$

⟦folio 33⟧

The average pressure is zero under the condition

$$\frac{kRT}{V - V_p} = \frac{2\sigma V_p S}{V^2},$$

that is, $p_{cp} = 0$ at

$$T = \frac{2\sigma V_p S (V - V_p)}{V^2 kR}.$$

S. Semenchinsky

F507. These two springs are made of the same material, which one is lined up side by side. Spring diameters are 3 mm and 9 mm, lengths are 1 cm and 7 cm, wire diameters are 0.2 mm and 0.6 mm. The stiffness of the first spring is 0.14 N/cm. The stiffness coefficient of the coil spring is the lowest.

Note that a section of the second spring 3 cm long is geometrically similar to the first spring - all its dimensions are exactly three times larger. Let's see how the stiffness of similar springs made from the same material corresponds.

The stiffness of a spring is uniquely determined by its geometric configuration and the elastic properties of the material from which it is made. We will look for a formula that determines the stiffness $k$, which is valid for any spring geometrically similar to the first. The configuration of such a spring is completely determined as soon as any one of its dimensions is specified, for example, the diameter of the coil $D$. Indeed, any other size can be obtained from the corresponding size of the first spring by multiplying by the similarity factor $n = D/D_1$, where $D_1$ is the diameter of the first spring. And the elastic properties of the material are characterized by Young’s model $E$:

Let us now use dimension messages. From the value $E$ (dimension $[E] = H/m^2$) and $D$ (dimension $[D] = m$) one can make a unique combination with dimension $k$ (dimension $[k] = H/m$): $ED$. Means,

$$k = cED,$$

where $c$ is a dimensionless quantity, depending on the parameters of the spring, that is, $c = f\left(\frac{l}{D}, \frac{d}{D}\right)$. It is impossible to determine the value of $c$ using the dimensional method. However, it is enough for us that for all springs geometrically similar to the first, the value of $c$ is the same.

This conclusion allows us to determine the stiffness $k_3$ of a spring that is geometrically similar with a similarity coefficient $n = 3$ to the first spring with a stiffness $k_1 = 0,14$ N/cm:

$$k_3 = 3k_1 = 0,42 \text{ H/cm.}$$

Now let’s compare a spring with stiffness $k_3$ and a second spring from the problem statement, whose stiffness $k_2$ must be found. All of their parameters, with the exception of length, are the same, so that fewer of them can be represented in the form of three successive springs 1 cm long, and more - in the form of seven such springs. Therefore, under the action of the same force $\vec{F}$ the removal of $x_3 = |\vec{F}|/k_3$ less than the spring and the removal of $x_2 = |\vec{F}|/k_2$ more than the spring are in the ratio 3:7. Hence,

$$k_2 = \frac{3}{7} k_3 = 0,18 \text{ H/cm.}$$

A. Kuznetsov, S. Kuznetsov
