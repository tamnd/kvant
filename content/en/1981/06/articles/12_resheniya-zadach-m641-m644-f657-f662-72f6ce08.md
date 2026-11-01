---
id: 1981-6-resheniya-zadach-m641-m644-f657-f662-72f6ce08
issue: kvant_1981_6
year: 1981
number: "6"
title: Solutions to problems M641—M644; F657—F662
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 35
page_last: 42
page_labels: 33-40
tag: J2DA
lang: en
source: kvant_digital
extraction: vision
content_sha256: bd7ed5a942c648078903f98b1c8dcfc27042fc7e996b6d2bd0d90a032cadad7f
prompt_sha256: draft-1
translated_from: content/ru/1981/06/articles/12_resheniya-zadach-m641-m644-f657-f662-72f6ce08.md
source_content_sha256: 1d56150f0ae82d3d6cd55cb307b7ecd8efed30752fcacf85c08087e449c0749e
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 33⟧

Problem solutions

M641. Given a regular hexagon ABCDEF with center O. Points M and N are the midpoints of sides CD and DE. Lines AM and BN intersect at point L. Prove that
a) triangle ABL and quadrilateral DMLN have equal areas;
b) ALO = OLN = 60°;
c) OLD = 90°.

All statements of the problem can be easily obtained from one observation: when rotated by 60° around the center O, the quadrilateral AMCB is mapped onto the quadrilateral BNDC.
Indeed, when turning $R_0^{60°}$ (counterclockwise), point A goes to point B, point B to point C, side CD is mapped to side DE, so that the middle M of side CD goes to the middle N of side DE (see figure). Therefore, the quadrilaterals AMCB and BNDC are congested, so their areas are equal. Subtracting the area of ​​the quadrilateral BCML from these equal areas, we obtain equal areas, that is, the triangle ABL and the quadrilateral DMLN are equal in size.

Since with rotation $R_0^{60°}$ ray AM is mapped onto ray BN, the angle between the directions of these rays is equal to the angle of rotation, that is, $ALB = 60°$. Therefore, $ALN = 120°$. We present two proofs that $ALO = OLN = 60°$ and $OLD = 90°$.

1°. Let's use this obvious fact: if two lines intersecting at point K are equidistant from point P, then line PK serves as the bicector of the angle between these lines (containing point P). Since the point O is equidistant from the lines AM and BN, OL is the bicsectrix of the angle ALN, that is, $ALO = OLN = 60°$. Since point D is equidistant from straight lines AM and BN equally (at the same distance as C is from straight line AM), $NLD = DLM = 30°$, that is, $OLD = 90°$.

2°. A circle can be described around the quadrilateral DMON, since the angles at its vertices M and N are right angles. Point L also belongs to this circle. This follows from the fact that in the quadrilateral DMLN the sum of the angles at vertices D and L is equal to 180°. Noticing that $ODN = 60°$, we apply the inscribed angle theorem. Then we get $OLN = ODN = 60°$ and $OLD = OMD = 90°$.

E. Gotman

M642. Prove that every natural number can be represented in the form $a_0 + 2a_1 + 2^2a_2 + \dots + 2^n a_n$, where each of the numbers is $a_k = 0, -1$ or 1, and $k \cdot a_{k+1} = 0$ for all $0 \leq k \leq n-1$, and such a representation is unique.

Considering Required Views
$$A = a_0 + 2a_1 + 2^2a_2 + \dots + 2^n a_n$$
(*)
($a_k = 0, -1$ or 1, $a_k \cdot a_{k+1} = 0$) for several natural numbers, it is easy to see that
1) last sign+stop at $2^n$ (most significant digit $a_n = +1$) for numbers A from $2^n - 2^{n-2} - 2^{n-4} - \dots$ to $2^n + 2^{n-2} + 2^{n-4} + \dots$ (for example, in our table in the margins last sign+stop at $2^3$ for numbers A from $2^3 - 2 = 6$ to $2^3 + 2 = 10$, at $2^4$ for numbers A from $2^4 - 2^2 = 1 = 11$ to $2^4 + 2^2 + 1 = 21$, etc.);
2) the first sign (minor digit $a_0 \neq 0$) is repeated periodically with a period of 4, that is, it depends only on the remainder when dividing A by 4 ($a_0 = 0$ is repeated even more often - with a period of 2).

Two proofs of the desired representation (*) and its uniqueness are built on these two observers. Both of these proofs are carried out by induction, that is, a valid statement for a given number A is deduced from its validity for all numbers A.

1°. Let us denote by $M_n$ the number $2^n + 2^{n-2} + 2^{n-4} + \dots$ (the last term here is $2^1 = 2$ for odd $n$ and $2^0 = 1$ for even $n$). Let us prove that each number $A \leq M_n$ is represented in the form (*) in a unique way, and $a_n = 1$ for numbers
$$2^n - M_{n-2} \leq A \leq 2^n + M_{n-2} = M_n.$$

⟦folio 34⟧

MB43. Cards with numbers 1, 2, ..., 32 are stacked in order. It is allowed to remove any number of cards from above and place them between some of the remaining ones or under it, without changing the order of both, but otherwise arbitrarily.

This operation is called moving the em.

1. Prove that in 5 moves you can a) rearrange the cards in reverse order;
6) arrange the cards in any order.
11. Prove that not every order of cards can be obtained in 4 moves.

Fig. 1.

We can (since we prove by induction) consider our statement proven for numbers $A$ not exceeding $M_{n-2}$. Using this, we obtain a representation (*) for any integer $A$ from the interval (1). Indeed, either $A=2^n$, or $1 \leqslant A-2^n \leqslant M_{n-2}$, or $1 \leqslant 2^n-A \leqslant M_{n-2}$. By adding the representation of the number $A-2^n$ to $2^n$ or subtracting the representation of the number $2^n-A$ from it, we obtain the representation (*) for $A$.

Note that

$$2^n-M_{n-2}-1=M_{n-1};$$

this equality becomes very strong if it is written like this:

$$2^n-1=M_{n-2}+M_{n-1}=2^{n-1}+2^{n-2}+2^{n-3}+\dots+1.$$

As can be seen from equality (2), intervals (1) for $n=1, 2, 3, \dots$ do not overlap and fill the entire set of natural numbers $N$, therefore representation (*) exists for any $A$. From here its uniqueness is also clear: given $A \in \mathbb{N}$ the digit $n$ of the leading digit $a_n=1$ is uniquely determined, and the addition $|2^n-A|$ is represented in a unique way by the assumption of induction.

$$2^\circ.$$ If $A$ is even, then $a_0=0$ and the representation (*) of the number $A=2m$ is obtained from the representation of the smaller number $m$ “shifted” by one digit. If $A$ is odd, then $a_0=\pm 1$ and $a_1$ must equal zero; therefore, the number $A-a_0$ is divided by 4 and the representation (*) of the number $A=4m+a_0$ is obtained from the representation of the smaller number $m$ by “swiggling” into two digits and adding the number $a_0$ to the left. In all these cases, the uniqueness of the representation of the number $A$ follows from the uniqueness of the representation of the number $m$.

The only representation of the number 1 is very similar: if $n>1$ and $|a_n|=1$, then $|a_0+a_1 \cdot 2+\dots+a_n \cdot 2^n| \geqslant 2^n-(2^{n-2}+2^{n-4}+\dots) \geqslant 2$.

N. Vasiliev

◆

We present two solutions to this problem.

First decision. We will assume that the cards in the pile are arranged in random order. Let us prove that they can be ordered in five movements, but not always in four. Thus the problem will be solved.

Let's call a segment a group of cards lying in a row, the numbers of which increase with distance from the top of the stack. The length of a segment will be the number of cards included in it.

If there are two segments, then it is always possible, without changing the order of the cards in each of them, by moving them to obtain a segment consisting of cards from these segments and only from them. We will say that such a segment is obtained by merging two segments. It is clear that the length of the merging result is equal to the sum of the lengths of the merging segments.

Let’s first mark 32 segments of a single length in a stack of cards and then make the movements like this:

1) divide the stack in half;
2) merge the corresponding segments from the first and second halves of the stack in pairs;
3) Let us note the segments resulting from the merging of point 2).

We will repeat this operation five times (at figure 1 it is shown what happens to the segments obtained after the second merging). The lengths of the segments swollen before the transfer are half the length of the segments swollen after it (see Fig. 1). Consequently, after the fifth operations, the length of the (only!) swollen segment will be equal to $2^5=32$. This proves statements a) and b) of the problem (for point a) the required movements are given in the margins).

To prove that randomly placed cards cannot be ordered in 4 moves, we introduce

⟦folio 35⟧

here is one concept. Let's make the two adjacent cards in the stack a defective pair if the card with a higher number is higher than the card with a lower number.

Lemma. If there are $n > 1$ defective pairs in a stack, then after moving there will be at least $m = \left[ \frac{n}{2} \right]$ defective pairs in it.

Proof. Dividing the stack into two, we obtain at least $m$ defective pairs in at least one of the stacks. Indeed, let there be $k$ and $l$ defective pairs in one stack. If we assume that $k \leq m - 1$ and $l < m$, then $k + l < 2m - 1 \leq n - 1$. However, there must be $k + l \geq n - 1$, since at most one defective pair could “diverge” when the stack was split. So, either $k \geq m$ or $l \geq m$.

Note now that if any cards are inserted between the cards of a defective pair, then at least one defective pair is formed (make sure that this is the same card being inserted). This proves the lemma.

Now let there be more than 15 defective pairs in the stack. Applying the proven lemma four times, we find that after four moves, at least one defective pair remains in the stack.

In connection with the last lemma, an interesting problem arises: knowing the number of defective pairs of an arrangement, determine exactly the minimum number of movements required to achieve this arrangement from an ordered stack. It turns out that if $N$ is the number of defective location pairs, then $\left[ \log_2 N \right] + 1$ movements are necessary.

Second solution. I 6) Consider the reverse operation of moving: we draw several cards from arbitrary places in the stack and place them on top. In this case, the relative order of both the drawn out environment and the rest of the cards does not change. Let us prove a more general statement: $2^n$ cards, arranged in any order, can be ordered in $n$ reverse movements.

We carry out the proof by induction.

To order two cards ($n = 1$), one reverse move is enough. Let it already be proven that to order the $2^k$ card, $k$ reverse movements are sufficient. Let us prove that a $2^{k+1}$ card can always be ordered in $k+1$ reverse moves.

Consider some arrangement of $2^{k+1}$ cards in a stack. Stacks of cards numbered 1 to $2^k$ (call this stack red) and numbered $2^k + 1$ to $2^{k+1}$ (call this stack blue) - with the relative position of the card within each stack the same as in a stack of $2^{k+1}$ cards - can be ordered by induction in $k$ reverse moves. Let's denote these movements by $A_1, A_2, \dots, A_k$ for the red stack and $B_1, B_2, \dots, B_k$ for the blue one.

Let us now perform $k$ reverse movements of a large stack (of $2^{k+1}$ cards) as follows: during the $i$-th reverse movement, we draw out red cards, which should be pulled out when moving $A_i$, and blue cards, which should be pulled out when moving $B_i$, after which we put both of them on the top of the stack - one under the other (Figure 2 will help you understand what is happening). After $k$ such operations, the red and blue piles are ordered. It remains for the last, $(k+1)$th move to draw out the cards of the red pile and place them on top.

II. Let us prove that if there are more than $2^n$ cards in a stack, then in $n$ moves they cannot be arranged in the reverse order - in descending order of numbers.

We carry out the proof by induction. At $n = 1$ the number of cards in the stack is at least three. Since when moving we either take at least two cards from above or leave at least two, after one move we will find two cards whose relative order has not changed.

Let the statement of the problem be true for $n = k$. For $n = k + 1$ we assume the opposite, that is, we assume that for $k + 1$

⟦folio 36⟧

moved managed to reverse the order in a stack containing more than $2^{k+1}$ cards. Let's see what's happening.

During the first move, at least $2^{k+1}$ cards are either removed from above or left unchecked, so there is a stack of $2^{k+1}$ cards whose relative order does not change after the first move. But by the induction hypothesis, for the remaining $k$ moves, the cards in this pile cannot be arranged in the reverse order. The resulting contradiction proves the statement of the problem.

Yu. Lysov, V. Turchininov

M644. a) Prove that there is a convex 1980-unit with side lengths 1, 2,..., 1980, all of whose edges are equal in size.
6) Does such a 1981 weekend exist?

Let us prove that if $n$ is not a power of a prime number, that is, $n = p \cdot q$, $n > 3$ and $p$ and $q$ are coprime numbers different from one, then it is always possible to construct a $n$-gon with sides of length 1, 2,..., $n$, parallel to the sides of the $n$-gon. Since $1980 = 4 \cdot 495$ and $1981 = 7 \cdot 283$, these will solve the problem.

Consider a regular $n$-gon ($n = p \cdot q$). Let us select among its vertices $p$ pieces that form a regular $p$-gon (on figure $n=15$, $p=3$, $q=5$). Now consider $p$ sets of $q$ vertices of our (regular) $n$-gon such that in each set these vertices form a regular $q$-gon, and the first vertex of the $i$-th set coincides with the $i$-th vertex of the selected $p$-gon (see. figure). Because the numbers $p$ and $q$ are mutually prime, these sets do not intersect. Therefore, we are looking to exhaust all the vertices of the $n$-gon.

Now we will “arrange” $p$ sets of $q$ vectors. We arrange the first $q$ vectors with lengths 1, 2,..., $q$ as follows: place the beginning vector at the successive vertices of the first $q$-gon, and take the direction of each vector to coincide with the direction of the side of the $n$-gon, adjacent to the corresponding vertex of the $q$-gon (the direction of the traversal is fixed). Let us denote the sum of vectors of the first set by $\vec{b}_1$.

The second set of $q$ vectors is obtained in the same way as the first, only it is “generated” by the vertices of the second $q$-gon. The sum of the $\vec{b}_2$ vectors of the second set is obviously obtained from the $\vec{b}_1$ vector by rotating through an angle $360^\circ/p$ around the center of the $n$-gon. By increasing the length of each vector of the second set by $q$ one, we do not change the sum $\vec{b}_2$, since such an increase is the addition of $q$ vectors forming a regular $q$-gon (their sum is $\vec{0}$).

So we can get $p$ sets of $q$ vectors: the directions of the vectors of the $i$-th set are determined by the vertices of the $i$-th $q$-gon, and their lengths are $1+q(i-1)$, $2+q(i-1)$,..., $qi$. The sum $\vec{b}_i$ of these vectors is obtained from $\vec{b}_1$ by rotating through an angle $360^\circ \cdot (i-1)/p$ around the set of $n$-gons.

From the above it follows that the vectors $\vec{b}_i$ form a regular $p$-gon. Consequently, their sum is equal to zero, and therefore the sum of $pq=n$ constructed vectors is equal to zero, the directions of which correspond to the direction of the sides of our right $n$-gon, and the lengths cover all natural numbers from 1 to $n$. What remains is a sequential arrangement of these $n$ vectors so that their directions correspond to the directions of successive sides of a regular $n$-gon.

For $n=p^k$, where $p$ is prime, it is impossible to construct such a $n$-gon, but we do not know an elementary proof of this fact.

Yu. Lysov

F657. The radiuses of curvature of two identical soap bubbles spin opposite each other are equal to $R$. After the conversation
36

⟦folio 37⟧

line between the bubbles lonnyla, one bubble of radius $R_1$ was formed. Find atmospheric pressure. The surface tension coefficient of the soap solution is σ.

Fig. 1.

Fig. 2. $\overrightarrow{OAB} = 30^\circ$;
$$|OB| = \frac{1}{2}|OA| = \frac{1}{2}R;$$
$$r = \sqrt{R^2 - \frac{R^2}{4}} = \frac{R\sqrt{3}}{2};$$
$$h = |OD| - |OB| = R - \frac{R}{2} = \frac{R}{2}.$$

F658. From a balloon containing highly rarefied potassium vapor, a beam of atoms emerges through a narrow horizontal tube. Determine the vapor temperature if on a horizontal path of length $l = 50$ cm the average vertical displacement of atoms is $h = 3,2$ µm.

where $p_0$ is atmospheric pressure, $4\sigma/R$ is excess pressure in the bubbles under a curved surface of radius $R$ (before σ stone the coefficient is 4, not 2, since the soap film has two surfaces). The condition of equal pressure to the right of the septum means that the septum is flat (otherwise the pressure in the bubbles must differ from one another by the amount of excess pressure under the curved surface of the septum). Since the bubbles are identical, the partition plane is located at equal distances from the centers of the bubbles.

Three forces act on any part of the film surface, the receiving film and the partition: two tension forces from the films that form their own bubbles, and a tension force from the partition film. Since the absolute values ​​of these forces are the same, under equilibrium conditions these forces are directed at angles $120^\circ$ to each other (Fig. 1).

Thus, in the initial state of air in bubbles at pressure $p = p_0 + 4\sigma/R$, the volume $V = 2\left(\frac{4}{3}\pi R^3\right) - V'$ occupies, where $V' = 2 \cdot \frac{1}{6} \pi h (3r^2 + h^2)$ is the volume of two spherical segments “cut off” by a partition from the bubbles (Fig. 2). As can be seen from figure 2, the radius of the partition is $\tau = R\sqrt{3}/2$, the height of the ball segment is $h = R/2$ and

$$V' = \frac{1}{3} \pi \frac{R}{2} \left(3 \frac{3R^2}{4} + \frac{R^2}{4}\right) = \frac{5}{12} \pi R^3,$$

$$V = \frac{8}{3} \pi R^3 - \frac{5}{12} \pi R^3 = \frac{9}{4} \pi R^3.$$

After the partition bursts, the air in the bubble of radius $R_1$ occupies a volume $V_1 = \frac{4}{3} \pi R_1^3$ at a pressure $p_1 = p_0 + \frac{4\sigma}{R_1}$.

We will assume that the air temperature in the bubbles remains unchanged (equal to the ambient temperature). Then $\frac{p}{p_1} = \frac{V_1}{V}$, or

$$\frac{p_0 + \frac{4\sigma}{R}}{p_0 + \frac{4\sigma}{R_1}} = \frac{16}{27} \frac{R_1^3}{R^3}.$$

From here we find the atmospheric pressure:

$$p_0 = \frac{4\sigma(16R_1^2 - 27R^2)}{27R^3 - 16R_1^3}.$$

(From the expression for $p_0$ it follows that the radius $R$ and $R_1$ are related by

$$\frac{3^3\sqrt{4}}{4} < \frac{R_1}{R} < \frac{3\sqrt{3}}{4}.$$

See for yourself.)

T. Petrova

◆

The temperature of the vapor is determined by the average (more precisely, average) speed of the vapor molecules:

$$T \approx \frac{\mu v^2_{cp}}{3R}.$$

To determine the temperature, you need to find $v_{cp}$.

Vertical mixing occurs as a result of the tension force. The time t of the movement of molecules, the length $l$ of the traversed names during this time are the beams and the vertical mixing of $h$ molecules by the ratios $\tau = l/v_{cp} = \sqrt{2h/g}$, from which

$$v_{cp} = l \sqrt{\frac{g}{2h}}.$$

⟦folio 38⟧

Substituting (2) into (1), we find
$$T \approx \frac{\mu l^2 g}{6 R h} \approx 6 \cdot 10^2 \text{ K}.$$
(Greater accuracy of calculations is not needed, since we rather roughly estimated the average speed of movement of molecules, using the average velocity.)

A. Zilberman

F659. A small machine weighing $m=200$ kg cuts during operation due to the heterogeneity of the heavy mass, cutting at an angular speed of 600 rps. To simplify the choice of floor chain in the workshop in which the machine is installed, an elastic gasket with a thickness of $h=10$ cm made of materials with an elasticity model of $E=3,1 \times 10^8 \text{ H/m}^2$ was placed under the frame. The base area of ​​the bed is $S=2 \text{ m}^2$. Will installing a spacer lead to a reduction in the selectable overlap?

Machine oscillations caused by the rotation of an unbalanced machine lead to the appearance of a harmonic force $F=F_0 \sin \omega t$ acting from the machine on the support ($F_0$ - amplitude, $\omega=2\pi f$ - circular frequency, $f$ - force frequency). The interaction of the machine and the ceiling, separated by an elastic spacer, can be used on the basis of a simplified system of two precise masses $m$ and $M$, connected by a spring with a stiffness $k$ (see figure; the role of the masses is played by the correspondence of the machine and the ceiling, the spring imitates the spacer between them). The stiffness $k$ of the spring (stiffness of the gasket) is equal to
$$k = \frac{ES}{h}.$$

The weight of the floor $M$ is much greater than the weight of the machine $m$. Indeed, if the floor is made of reinforced concrete (density about 2500 kg/$\text{m}^3$) and has a thickness of approximately 0.2 m, then the mass of just one square meter (surface density) of the floor is 500 kg, which is already much greater than the weight of the machine (according to 200 kg).

Let $x_1$ and $x_2$ be the mixtures of masses $m$ and $M$ along the $OX$ axis relative to the coordinates of the masses in the unexcited state. Then the mass accelerations, according to Newton’s second law, can be written in the form
$$\vec{a}_1 = x_1'' = -\frac{k \Delta h}{m} + \frac{F}{m} = \frac{k}{m} (x_2 - x_1) + \frac{F_0}{m} \sin \omega t,$$
$$\vec{a}_2 = \frac{k \Delta h}{M} = \frac{k}{M} (x_1 - x_2).$$

For harmonic vibrations $x_1 = A_1 \sin \omega t$, $x_2 = A_2 \sin \omega t$, $a_1 = -\omega^2 A_1 \sin \omega t$, $a_2 = -\omega^2 A_2 \sin \omega t$, where $A_1, A_2$ are the vibration amplitudes of masses $m$ and $M$, respectively. Substituting these expressions into (2), we get
$$\left( -\omega^2 + \frac{k}{m} \right) A_1 - \frac{k}{m} A_2 = \frac{F_0}{m},$$
$$- \frac{k}{m} A_1 + \left( -\omega^2 + \frac{k}{m} \right) A_2 = 0,$$

or
$$- \omega^2 A_1 + \frac{k}{m} \left( A_1 - A_2 \right) = \frac{F_0}{m},$$
$$- \omega^2 A_2 - \frac{k}{m} \left( A_1 - A_2 \right) = 0.$$

From here is
$$A_1 - A_2 = \frac{F_0}{m} \cdot \frac{1}{-\omega^2 + \frac{k(m+M)}{mM}} = \frac{F_0}{m(\omega_p^2 - \omega)},$$
Where
$$\omega_p = \sqrt{\frac{k(m+M)}{mM}}$$

- resonant circular frequency of harmonious oscillations of a system of masses connected by a spring. At $M \gg m$
$$\omega_p \approx \sqrt{\frac{k}{m}}.$$

From (2') (2'') we determine the amplitude of mass mixing $M$:

⟦folio 39⟧

$$A_2 = \frac{F_0}{(m+M)\omega^2} \cdot \frac{1}{\left(\frac{\omega}{\omega_p}\right)^2 - 1}.$$

In the absence of a spacer, the force $F$ imparts acceleration to the system machine - overlap with mass $m+M$

$$|\vec{a}_0| = \frac{|\vec{F}|}{m+M}.$$

The amplitude $A_0$ of oscillations in this case is found from the condition $a_0 = -\omega^2 A_0$ sin $\omega t$:

$$A_0 = -\frac{F_0}{(m+M)\omega^2}.$$

Thus, the ratio of the amplitudes of floor mixing after installation of the gasket and before is equal to

$$\frac{A_2}{A_0} = \frac{1}{1 - \left(\frac{\omega}{\omega_p}\right)^2} = \frac{1}{1 - \left(\frac{f}{f_p}\right)^2},$$

(4)

Where

$$f_p = \frac{1}{2\pi} \omega_p \approx \frac{1}{2\pi} \sqrt{\frac{k}{m}} = \frac{1}{2\pi} \sqrt{\frac{ES}{hm}} \approx 885 \text{ Гц}$$

(see (1) and (3)). Since according to the conditions $f = 600$ Hz, from (4) we find

$$\frac{A_2}{A_0} = \frac{1}{1 - \left(\frac{600}{885}\right)^2} \approx 1,85,$$

that is, vibrations after installing the gasket will be successful.

How to reduce the impact on the floor? As can be seen from formula (4), this can be achieved by choosing the gasket parameters in such a way that the condition $f_p \ll f$ is satisfied, that is, you should choose a material for the gasket with a small Young model or increase the thickness of the gasket. So, if $E = 3,1 \cdot 10^6$ N/m$^2$, that is, 100 times less than according to the conditions of the problem, then we can get

$$\left|\frac{A_{20}}{A'_{20}}\right| \approx 0,02,$$

that is, vibration is significantly reduced.

R. Vinokur

F660. The float, made of a homogeneous material, has the shape of a lentil - a body, limited by two spherical surfaces of radii $R_1 = R_2 = R = 3$ cm. The maximum thickness of the chechevitsa is $h = 4$ cm; the mass of the lentil is $m_1 = 5$ cm. A knitting needle with a length of $l = 10$ cm and a mass of $m_2 = 3$ cm is inserted into the float along the entire thickness along the axis of symmetry. Is the position of the float stable when it floats on the surface of the water of the chechevy? Consider that less of the lentil is immersed in the liquid.

To make sure that less of the lentils are immersed in the liquid, you can use the data given in the conditions of the problem. The equilibrium condition for the float in the “knitting needle up” position is $\vec{F}_T + \vec{F}_A = \vec{0}$, or $\vec{F}_T - \vec{F}_A = \vec{0}$, where $\vec{F}_T = (m_1 + m_2) |\vec{g}|$ is the force of gravity acting on the float with the knitting needle, $\vec{F}_A = \varrho_B |\vec{g}| V'$ is the buoyant force ($V'$ is the volume of the part of the float immersed in the water). From equality

$$(m_1 + m_2) |\vec{g}| = \varrho_B |\vec{g}| V'$$

let's define $V'$:

$$V' = \frac{m_1 + m_2}{\varrho_B} = 8 \text{ см}^3.$$

The volume of the poling lentil (volume of the spherical segment) is equal to

$$V = \frac{1}{6} \pi h_1 (3r^2 + h_1^2) \approx 29 \text{ см}^3$$

(see Fig. 1). Condition $V' < V$ means that a smaller part of the Chechevtsy is immersed in the water.

Now consider the question of the stability of the float in the “knitting needle up” position. We will assume that with a small deviation of the float, when the spokes make a small angle $\alpha$ with the vertical (Fig. 2), the part of the float immersed in the water

⟦folio 40⟧

still has the shape of a spherical segment and the float draft does not change. (The deflection of the float is its rotation around the point $O$, that is, around the center of the sphere, limiting the lower part of the float.) This condition means that, as before, $\vec{F}_{\tau} + \vec{F}_{\mathrm{A}} = 0$. If, as a result of the deviation, moments of force appear that tend to return the float to its previous position, this position - “knitting needle up” - is stable; if the moment of force is such that the float will continue to deflect, the “spoke up” position is unstable.

While the float was in the equilibrium position, the forces $\vec{F}_{\tau}$ and $\vec{F}_{\mathrm{A}}$ were applied along one straight line - the vertical passing through the spoke. Force $\vec{F}_{\tau}$ is applied at point $C$ - at the center of mass of the float with a spoke, and force $\vec{F}_{\mathrm{A}}$ is applied at point $O$ (force $\vec{F}_{\mathrm{A}}$ is the result of pressure forces acting from the water on the float). Point $C$ is located at a distance $x = |DC|$ (see Fig. 2) from the bottom of the float such that

$$m_1 \left( \frac{l}{2} - x \right) = m_2 \left( x - \frac{h}{2} \right);$$

from here

$$x = \frac{m_1 l/2 + m_2 h/2}{m_1 + m_2} = 3,125 \text{ cm.}$$

Point $O$ is located at a distance of $|DO| = R = 3$ cm from the bottom of the float. Therefore, the point $C$ lies above the point $O$.

With a small deflection of the float (when rotating around $O$), the points of application of force $\vec{F}_{\mathrm{A}}$ remain the same - point $O$; the point $C$ will be mixed with the vertical $DC$. Thus, when the float deflects, a couple of forces act on it; the moment of these forces tends to rotate the float towards further deviation from the equilibrium position (at figure 2 - counterclockwise).

Consequently, the float “with its spoke up” is a position of unstable equilibrium.

D. Kuznetsov

F661. figure shows the current-voltage characteristics of two non-captive resistors $R_1$ and $R_2$. What will be the point, suffocation through resistors and a source with EMF $\varepsilon = 10$ V and internal resistance $r = 2$ Ohm, if it connects resistors to the source, connecting them a) in series, b) in parallel?

If the resistors are connected in series, then at each point value the voltage $U_{\mathrm{noc}}$ on the section of the circuit containing the resistors is equal to the sum of the voltage on each of them. With a parallel connection, the current in the circuit at each voltage value $U_{\mathrm{nap}}$ across the resistors is equal to the sum of the currents flowing through each of them. Dependency $I(U_{\mathrm{noc}})$ and $I(U_{\mathrm{nap}})$ are built on figure.

The voltage $U_6$ at the terminals of the battery changes when the point in the circuit changes:

$$U_6 = \varepsilon - r I = 10 - 2 I.$$

The dependency $I(U_6)$ is also built on figure. The points of intersection of straight line $I(U_6)$ with curves $I(U_{\mathrm{noc}})$ and $I(U_{\mathrm{nap}})$ give the values ​​of currents and voltages in the corresponding circuit for series and parallel connection of resistors.

From figure there is:

a) $I_1 = I_2 = I_6 = 0,25$ A; $U_1 = 5,5$B, $U_2 = 3,9$B;
