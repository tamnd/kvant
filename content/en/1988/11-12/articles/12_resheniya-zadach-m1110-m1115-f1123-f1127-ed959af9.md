---
id: 1988-11-12-resheniya-zadach-m1110-m1115-f1123-f1127-ed959af9
issue: kvant_1988_11-12
year: 1988
number: 11-12
title: Solutions to problems M1110—M1115; F1123—F1127
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 39
page_last: 47
page_labels: 37-45
tag: 1WAA
lang: en
source: kvant_digital
extraction: vision
content_sha256: 57c1d5eb53b026d02680e03c54022c8e3432d6792440e5b347b04c3d160f8819
prompt_sha256: draft-1
translated_from: content/ru/1988/11-12/articles/12_resheniya-zadach-m1110-m1115-f1123-f1127-ed959af9.md
source_content_sha256: 29682a28003e8b9c249ec1aa805720052614cbeea5a6cdef50ea813060499666
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 37⟧

P1146. Find the resistance between the points $A$ and $B$ in the infinite sequence of elements shown on figure 6. All the elements are identical, the resistance of each is $r$. S. Zdravkovich (Yougoslavia)

P1147*. A small weight lies on a platform which is inclined by the small angle $\alpha$ to the horizontal plane. The platform's mass is much greater than that of the weight, whose distance from the lower edge of the platform is $l$ (see figure Pic. 7). The platform oscillates harmoniously about the $OO'$ axis with frequency $\omega$ and amplitude $L$. The friction coefficient between the weight and the platform is $k$. How much time will it take the weight to fall of the platform? (This time is assumed much greater than $2\pi/\omega$).

Problem solutions

M1110 — M1115, F1123 — F1127

M1110. For each natural number $n>1$ we write down the most common divisors of all possible pairs of distinct numbers from 1 to $n$. Prove that $a$ the arithmetic mean of all $n(n-1)/2$ written numbers is not limited by the distance $n$, but does not exceed $\ln n+1$; $b$ their geometric mean does not exceed 10 for any $n$.

Fig. 1.

a) Let $P_n(d)$ denote the number of pairs $(a, b)$ of natural numbers $a < b \leq n$ with the most common divisor $d=HOД(a, b)$. Each such pair can be represented as $a=dx, b=dy$, where $x<y \leq k=[n/d]$, and $x$ and $y$ are coprime. The number $P_k=P_k(1)$ of such pairs $(x, y)$ of coprime numbers is easy to estimate from above:

$$P_k \leq 1+2+\ldots+(k-1)=k(k-1)/2,$$

since for each $y \leq k$ the number $x<y$ takes at most $y-1$ values. From here

$$P_n(d)=P_{[n/d]} \leq \frac{n}{2d}\left(\frac{n}{d}-1\right) \leq \frac{n(n-1)}{2d^2}.$$

At the end of the solution we will prove the estimate SIZU $P_k \geq k(k-1)/4$; from this we obtain an estimate for $P_n(d)$:

$$P_n(d) \geq \frac{1}{4}\left(\frac{n}{d}-1\right)\left(\frac{n}{d}-2\right)=$$

$$= \frac{n^2-3nd+2d^2}{4d^2} > \frac{n(n-1)}{4d^2}-\frac{3n}{4d}.$$

The sum of the numbers $d=HOД(a, b)$ over all parameters $(a, b)$ is equal to $\sum_{d=1}^{n-1} dP_n(d)$, and their arithmetic mean $A$ is equal to $\frac{2}{n(n-1)}\sum_{d=1}^{n-1} dP_n(d)$. Using estimates for $P_n(d)$, we obtain:

$$A \leq \frac{2}{n(n-1)}\sum_{d=1}^{n-1} d\left(\frac{n(n-1)}{4d^2}-\frac{3n}{4d}\right)=$$

$$= \frac{1}{2}\left(1+\frac{1}{2}+\ldots+\frac{1}{n-1}\right)-\frac{3}{2}.$$

Next we need the following

Lemma. For any natural $n$

⟦folio 38⟧

$$\frac{1}{2} + \ldots + \frac{1}{n} < \ln n < 1 + \frac{1}{2} + \ldots + \frac{1}{n-1}.$$

To prove it, we can use the fact that $\ln n = \int_{1}^{n} 1/t \, dt$ is the area under the hyperbola $f(t) = 1/t$ on the section $1 \leq t \leq n$ (Fig. 1); you can not use the integral, but, for example, verify the validity of the inequalities

$$\frac{\alpha}{1+\alpha} \leq \ln(1+\alpha) \leq \alpha \quad \text{при} \ \alpha \geq 0$$

(noticing that at $\alpha=0$ all three terms are equal to 0 and comparing the derivatives), then substitute $\alpha=1$, $\alpha=\frac{1}{2}$, ..., $\alpha=\frac{1}{n-1}$ into them and add all the resulting inequalities.

Applying the lemma to estimates (1) and (2), we obtain

$$\frac{1}{2} \ln n - \frac{3}{2} < A \leq \ln(n-1)+1 < \ln n+1.$$

6) The logarithm of the arithmetic mean of several numbers is equal to the arithmetic mean of their logarithms. Therefore, to solve the problem, it is enough to prove that the arithmetic mean of the numbers $\ln d$ (where $d=\text{НОД} (a, b)$, $a<b \leq n$) is less than 2: after all, $e^2 < 10$, i.e. $2 < \ln 10$. Proceeding in the same way as above, we get

$$\frac{2}{n(n-1)} \sum_{d=1}^{n} \ln d \cdot P_n(d) \leq \sum_{d=2}^{n} \frac{\ln d}{d^2} < \sum_{d=2}^{n} \left( \frac{1}{d^2} \sum_{h=1}^{n} \frac{1}{h} \right).$$

Here we applied the lemma: $\ln d \leq 1 + \frac{1}{2} + \ldots + \frac{1}{d}$.

In the educational double sum of numbers of the form $\frac{1}{d^2} \frac{1}{h}$ ($1 \leq h \leq d$, $2 \leq d \leq n$), it is convenient to put together numbers with the same $h$ ($1 \leq d \leq n$ for $h=1$, $h \leq d \leq n$ for $h>1$) and evaluate $\sum_{d=h}^{n} \frac{1}{d^2}$ using an easy collapsing sum

$$\sum_{d=h}^{n} \frac{1}{d(d-1)} = \sum_{d=h}^{n} \left( \frac{1}{d-1} - \frac{1}{d} \right) = \frac{1}{h-1} - \frac{1}{n} < \frac{1}{h-1}$$

(this estimate will be needed now once for $h=2$).

Finally we get

$$\sum_{d=2}^{n} \frac{\ln d}{d^2} < \sum_{d=2}^{n} \frac{1}{d^2} + \sum_{h=2}^{n} \left( \frac{1}{h} \sum_{d=h}^{n-1} \frac{1}{d^2} \right) < 1 + \sum_{h=2}^{n} \frac{1}{h(h-1)} < 2.$$

Let us now prove the estimate $P_k \geq k(k-1)$ used in the solution of part a). Let's put $m=[k/2]$. Among all integer points $(x, y)$, where $0 < x < y \leq k$, we call those for which $x$ and $y$ are coprime (Fig. 2) red. Let us draw a ray from the origin $(0, 0)$ through each red point in triangle $x < y \leq m$. These $P_m$ rays contain, of course, all $m(m-1)/2$ integer points in the triangle $x < y \leq m$.

Consider integer points on any of the $P_h$ rays.

⟦folio 39⟧

IX kolichestvo on section $h+1 \leqslant y \leqslant k$ can exceed their kolichestvo on section $1 \leqslant y \leqslant h$ by no more than one (after all, integer points $(x, y)$ occur on the ray at equal intervals). Therefore, in the trapezoid $m+1 \leqslant y \leqslant k$, $x < y$, out of all $k(k-1)/2-m(m-1)/2$ integer points, there are no more than $m(m-1)/2+P_m$ points on the drawn rays. All other points in the trapezoid are red; thus their number

$$P_k - P_m \geqslant \frac{k(k-1)}{2} - m(m-1) - P_m,$$

where

$$P_k \geqslant \frac{k(k-1)}{2} - m(m-1) \geqslant \frac{k(k-1)}{4}$$

(the last inequality is easy to check for $k=2m$ and $k=2m+1$).

It can be shown that $\lim_{k \to \infty} \frac{P_k}{k^2} = 3/\pi^2$, i.e. the probability that a random selection of natural numbers $(x, y)$ not exceeding $k$ turns out to be coprime, tends to $6/\pi^2$ as $k \to \infty$ (see, for example, problem 30 to Chapter III in the book by I. M. Vinogradov “Introduction to Number Theory”, M.: Nauka, 1965).

N. V. Vasiliev, V. F. Lev

M1111. A circle is circumscribed around the acute triangle ABC. The tangents to the circle drawn at points A and C intersect the tangent drawn at point B, respectively at points M and N. In triangle ABC, the altitude BP is drawn (point P lies on side AC). Prove that the line BP is the bisector of the angle MPN.

Let us prove that the triangles APM and CPN are similar (see figure), and it follows that $\angle APM = \angle CPN$, i.e. $\angle MPB = \angle NPB$. Let AB=c, BC=a, $\angle BAC=a$, $\angle BCA=γ$. In an isosceles triangle AMB, the angle MAB between the tangent AM and the chord AB of a given circle is equal to half the magnitude of the arc AB, as is the inscribed angle ACB, i.e. $\angle MAB=γ$. Therefore, $\angle MAP=α+\gamma$, AM=c/(2 cos γ). Likewise, $\angle NCB=α$, $\angle NCP=γ+\alpha$, CN=a/(2 cos α). In addition, AP=c cos α, PC=a cos γ. Thus, in triangles APM and CPN the angles MAP and NCP and the aspect ratios are equal:

$$AP/AM=2 \cos α \cos γ=CP/CN,$$

which proves their similarity.

Note that the statement of the problem and its proof, with minor modifications, also applies to an obtuse triangle.

V. I. Chinik

M1112. There are two numbers written on the board: 1 and 2. It is allowed to add new numbers as follows: if there are numbers a and b on the board, then

Answer: in case a) - it is possible, in case 6) - it is impossible. Note that if $c=a+b+ab$, then $c+1=(a+1)(b+1)$. Therefore, together with the numbers written on the board, it is convenient to look at numbers that are 1 more. Then each new number is equal to the product of two existing ones. First there are the numbers $2=1+1$ and $3=2+1$; Means,

⟦folio 40⟧

Mono write the number ab+a+b. Is it possible to obtain a) the number 13121 in this way? b) the number 12131? Prove that there are an infinite number of natural numbers that cannot be represented in the form e) x+y+xy, d) x+y+2xy with natural numbers x and y.

All subsequent numbers are of the form $2^n \cdot 3^m$ ($n$ and $m$ are natural numbers). It remains to check these numbers: $13121+1=2 \cdot 3^8$, and $12131+1=2^2 \cdot 3^2 \cdot 337$.

In view of the above, it is sufficient to prove that there are an infinite number of natural numbers $n>1$ that cannot be represented in the form $(x+1)(y+1)$ with natural numbers x and y. But this condition is satisfied by all prime numbers (and only they), and, as we know, there are an infinite number of them. (Recall the included idea of ​​the proof of the infinity of the set of prime numbers: if $p_i$, ..., $p_k$ are primes, then the number $p_1 \cdot \dots \cdot p_k+1$ has a divisor that is a prime number different from $p_i$.) d) If $z=x+y+2xy$, then $2z+1=(2x+1)(2y+1)$. Reasoning in the same way as in problem c), we are convinced that our statement is equivalent to the fact that the set of prime numbers of the form $2z+1$ (i.e. odd) is infinite.

Prove on your own the statement of problems c) and d); for any natural number a, the set of numbers that cannot be represented in the form x+y+axy is infinite.

A. A. Berzins, V. G. Iltsev

M1113*. 21 years old in the country. Aviation communication between them is carried out by several airline companies, one of which serves 10 free airline companies connecting five cities via pairing (in this case, planes of several companies can fly between two cities). Every two cities are connected by at least one endless airline. At what minimum number of airlines is this possible?

Fig. 1.

Answer: At 21. Since the number of city pairs is $21 \cdot 20/2=210$, each pair is served by at least one company, and each company serves 10 pairs, the number of companies cannot be less than 210:10-21.

It remains to give an example of the servicing scheme for the cities of the 21st airline companies. Let us represent the cities with the vertices of a regular 21-gon and numbered clockwise (Fig. 1). Let the 1st company serve cities with numbers 1, 3, 8, 9, 12, the 2nd - cities with numbers 2, 4, 9, 10, 13, obtained from the first set by turning by an angle $360^\circ/21$ (clockwise) and, in general, the k-th company - city, which are obtained from the first set by turning by $(k-1) \cdot 360^\circ/21$. Any pair of vertices of a polygon will fall into one of these sets, since the average location of the points of the first set is equal to the lengths of all sides and diagonals of the 21-gon.

It is easy to check that the circuit we have constructed satisfies the following conditions: 1) any two points are included in at least one set (this is required in the problem), 2) any two sets have one and only one point. If we replace the word “set” here with the word “straight line” and add one more condition - 3) there are 4 points, no 3 of which lie on the same line - we get the axioms of the so-called (abstract) projective plane: by definition, this is an arbitrary set of points in which some subsets are identified - “straight lines” that satisfy conditions 1) - 3). In particular, our scheme is a finite projective plane of a 21-gon. It is not difficult to prove that any two finite projective plane consists of the same number of points, and if this number is equal to n, then the number of points

⟦folio 41⟧

on the plane it is equal to $n^2 - n + 1$ and such a number is straight. figure 2 shows a diagram of the smallest projective plane - seven points.

D. V. Fomin, V. N. Dubrovsky

**M1114. Prove that for any tetrahedra the inequality holds**

$$r < \frac{ab}{2(a+b)},$$

$a, b$ is the length of two crossing edges, $a, r$ is the radius of the inscribed ball.

Fig. 1.

Fig. 2.

**M1115*. a) The first line contains 19 natural numbers not exceeding 88, and the second line contains 88 natural numbers not exceeding 19. Let us use a segment of one or more consecutively written numbers on one side. Prove that you can select a segment from the given rows so that the sums of the numbers in them are equal. b) Let $n, m, k$ be natural numbers, $m \geq n$. Prove that if

$$1 + 2 + \dots + n = mk,$$

then the numbers 1, 2, ..., $n$ can be divided into $k$ groups so that

Note that the radius $r$ of the sphere inscribed in the tetrahedр is equal to $3V/S$, where $V$ is its volume, and $S$ is the surface area. (To prove it, it is enough to imagine the volume of a tetrahedron as the sum of the volumes of four tetrahedrons, the bases of which are the faces of a given tetrahedron, and the vertices coincide with the center of the sphere.) Let us estimate $V$ and $S$ through the lengths of the edges $a, b$ and the distance $h$ between the crossing lines containing these edges. Let us describe a parallelepid around the tetrahedra, for which $a$ is the edge of the lower base, and $b$ is the edge of the upper one (Fig. 1). Its height is estimated to be $h$, so its volume does not exceed $abh$. At the same time, this volume is 6 times larger than the volume of the tetrahedron, which becomes clear if we take its side face, which contains the face of the tetrahedron, as the base of the parallelepid. Thus, $V \leq abh/6$.

On the other hand, the distance from the ends of the edge $b$ tetrahedрa to the edge $a$ is not less than $h$ and at least one of them is greater than $h$ (Fig. 2), therefore the sum of the areas of the faces adjacent to the edge $a$ is greater than $ah$. Similarly, the sum of the areas of the other two faces is greater than $bh$, i.e. $S > (a+b)h$, and

$$r = \frac{3V}{S} < \frac{abh}{2(a+b)h} = \frac{ab}{2(a+b)}.$$

N. V. Vasiliev

a) Let $a_1, a_2, \dots, a_{19}$ be the numbers of the first line, $b_1, b_2, \dots, b_{88}$ the second, $A(i)=a_1+\dots+a_i, B(i)=b_1+\dots+b_i$. Assume that $A(19) \geqslant B(88)$ (the case $A(19) < B(88)$ is treated similarly). For each $i$ we denote by $n_i$ the smallest of the numbers $n$ such that $A(n)-B(i) \geqslant 0$; such $n_i$ exists due to our assumption. Consider 88 differences $A(n_i)-B(i)$; they can belong to values ​​from 0 to 87, since $A(n_i)-B(i)=A(n_i-1)-B(i)+a_{n_i} < a_{n_i} \leqslant 88$. If these differences are different, then there is 0 among them and our statement is satisfied. Otherwise, the two differences - say, for $i=l$ and $i=k$, $k<l$ - coincide. Then

$$A(n_l)-A(n_k)=B(l)-B(k),$$

i.e., the required segments are $a_{n_k+1}, \dots, a_{n_l}$ and $b_{k+1}, \dots, b_l$.

It is clear that the numbers 19 and 88 in this problem can be replaced by any natural numbers.

6) We carry out the proof by induction on $n$. For $n=1$ there is nothing to prove. Let's assume that our statement

⟦folio 42⟧

is true for all values ​​of the parameter less than $n$, and consider the set $S_n = \{1, 2, \dots, n\}$.

If $m = n$, then $(n+1)/2 = k$ is an integer and the required partition is as follows:

$$\{n\}, \{1, n-1\}, \{2, n-2\}, \dots, \{(n-1)/2, (n+1)/2\};$$

if $m = n+1$, then $n$ is even and the partition has the form

$$\{1, n\}, \{2, n-1\}, \dots, \{n/2, n/2+1\}.$$

Now let's look at case 3.

Case 1: $n+1 < m < 2n$, $m$ unclear. Select from the set $S_n$ the set $S_{m-n-1}$; the remaining $2n-m+1$ numbers can be split into pairs with a sum of $m: \{m-n, n\}, \{m-n+1, n-1\}, \dots, \{(m-1)/2, (m+1)/2\}$. The sum of the numbers in the set $S_{m-n-1}$ is equal to

$$\frac{(m-n-1)(m-n)}{2} = \frac{m^2-m(2n+1)}{2} + \frac{n(n+1)}{2} = m\left(\frac{m-2n-1}{2} + k\right)$$

and is divisible by $m$, and $m \geqslant m-n-1$, therefore these numbers, by the induction assumption, can also be divided into groups with the sum $m$ in each group.

Case 2: $n+1 < m < 2n$, $m$ even. Here we will also select the set $S_{m-n-1}$, and divide the remaining numbers into pairs with the sum $m: \{m-n, n\}, \{m-n+1, n-1\}, \dots, \{m/2-1, m/2+1\}$, and another number $m/2$. Let us represent the sum of the numbers in the set $S_{m-n+1}$ as $(m-2n-1+2k)(m/2)$. It is divisible by $m/2$, and $m/2 \geqslant m-n-1$, as well as $m/2 < n$. Therefore, the set $S_{m-n-1}$ can be divided into an odd number $m-2n-1+2k$ groups with the sum $m/2$, add $m/2$ to one of them, and combine the rest in pairs - we get groups with the sum $m$.

Case 3: $m \geqslant 2n$. We will split the set $S_n$ into $k$ groups with an equal sum, which will automatically be equal to $m$. Note that $k = n(n+1)/2m \leqslant (n+1)/4$, and therefore $n-2k \geqslant 2k-1 > 0$.

Let us select from $S_n$ the set $S_{n-2k}$. The sum of the numbers in this set

$$\frac{(n-2k)(n-2k+1)}{2} = \frac{n(n+1)}{2} - k(2n+1)+2k^2$$

is divisible by $k$, and the quotient of this division is not less than $n-2k$ since $(n-2k)(n-2k+1)/2(n-2k) = (n-2k+1)/2 \geqslant k)$.

Therefore, $S_{n-2k}$ can be partitioned by the induction assumption into $k$ groups of equal sum. The remaining $2k$ numbers are divided into $k$ pairs with an equal sum: $\{n-2k+1, n\}, \{n-2k+2, n-1\}, \dots$. It remains to unite each group with one pair.

A. V. Anzhans

F1123. To the end of the vertical water group using a short piece of rubber

Let's consider the forces acting on the horizontal nozzle (see figure). These are two forces $F$ of water pressure in the bends of the nozzle, the force of the weight of the water $\rho lSg$ and the gravity force of the nozzle itself $Mg$.

⟦folio 43⟧

A steel nozzle of mass M is attached to the tube. At what water flow will the nozzle be horizontal? The area of ​​the nozzle section is S, its length is l. Trainer to claim.

F1124. On top of a smooth horizontal beam of radius R is placed a “little book” made up of two homogeneous thin square planes on the side l=4R. The plates are fastened together using a weightless hinged rod. What angle do the plates form at equilibrium? Will this equilibrium be stable?

F1125. A vertical heat-solitized vessel containing a monatomic gas is closed by a piston of mass M. A cutter with power N is turned on in the vessel, and the piston begins to slowly move upward. How long does it take for it to rise to a height H relative to the

⟦folio 44⟧

Primary position? The capacity of the piston, trench and atmospheric pressure are taken into account.

$$N\tau = MgH + \frac{3}{2} MgH$$

we get

$$\tau = \frac{5}{2} \frac{MgH}{N}.$$

A. R. Zilberman

F1126. In the circuit shown in figure 1, key K “oscillates” between positions 1 and 2 with a frequency of $f=100\Gamma$; The key remains in each position for the same amount of time. Start the current through the resistor. $C_1=10$ µF, $C_2=30$ µF, $R=100$ kOhm.

Fig. 1.

Fig. 2.

The answer to the question of the problem is estimated: the average current through the resistor must be equal to zero. In fact, for any value other than zero, the potential of the connection point of the capacitors would also increase unlimitedly over time.

Of greater interest is the communication of current through the battery, assuming the battery voltage is $U_0=10$V.

It is easy to check that while the switch is in one of the positions - 1 or 2 - the capacitors are recharged independently. Indeed, let a capacitor with capacity $C$ be charged to voltage $U$. Let's close it to a resistor with resistance $R$. Current $I=U/R$ will flow through the circuit, as a result in a short time $t$ the charge of the capacitor will change to

$$\Delta q = I\tau = U\tau/R,$$

and the voltage is at

$$\Delta U = \Delta q/C = U\tau/(RC),$$

So

$$\frac{\Delta U}{U} = \frac{\tau}{RC} \ll 1.$$

In fact, the voltage change is even smaller, since some charge also flows from the battery.

So, the voltage of the capacitors can be considered constant. Then for the circuits shown in figure 2, we get

$$\frac{U_1}{R} - i_1 = I_1, \quad \frac{U_2}{R} - i_2 = I_2.$$

But

$$i_1\tau_1 = I_2\tau_2 \text{ и } i_2\tau_2 = I_1\tau_1,$$

or given that $\tau_1 = \tau_2 = 1/(2f)$,

$$i_1 = I_2 \text{ и } i_2 = I_1.$$

Therefore, in the established mode

$$U_1 = U_2 = \frac{U_0}{2},$$

$$I_1 + I_2 = \frac{U_0}{2R},$$

and current through the battery

$$I = \frac{I_1 + I_2}{2} = \frac{U_0}{4R} = 25 \text{ мкA.}$$

⟦folio 45⟧

It is curious that the answer did not include the capacitance values ​​of the capacitors. We only needed them to confirm the conditions RC≈1/f.

A. R. Zilberman

F1127. The flashlight emits a beam of rays, converging at a distance of $R_0=1$ m from it into a small spot. On the path of the beam, two square flat mirrors were placed so that the line of their contact intersects the beam axis at a distance of $r=70$ cm from the flashlight and redistributes this axis. The planes of the mirrors overlap each other, and one of the mirrors makes an angle of $\alpha=30^\circ$ with the axis of the beam. At what distance from the flashlight will the beam converge?

The course of the rays emitted by the flashlight F is shown at figure. Before placing mirrors in the path of the rays, the beam converged at point A.

Let's consider that part of the rays that is first reflected from mirror 1. After reflection, they go as if they were emitted by a flashlight F', which is a reflection of flashlight F in mirror 1. These rays would intersect at point $A'$ if mirror 2 did not stand in their path. After reflection from it, the rays go as if they were emitted by flashlight F', which is a reflection of F' in the mirror 2. It is easy to see that Ф'' is centrally symmetrical to Ф with respect to point O. As a result, the beam is contained at point $A''$, which is centrally symmetrical to point A and lies on the beam axis at a distance

$$x=R_0-2(R_0-r)=40 \text{ см}$$

from a flashlight.

Similar reasoning shows that the rays first reflected from mirror 2 also intersect at point $A''$. The position of this point obviously does not depend on the angle $\alpha$.

M. M. Tsypin
