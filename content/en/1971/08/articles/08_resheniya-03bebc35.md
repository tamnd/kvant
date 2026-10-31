---
id: 1971-8-resheniya-03bebc35
issue: kvant_1971_8
year: 1971
number: "8"
title: Solutions to problems M50—M60, M45 (end); F66—F71
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 37
page_last: 52
page_labels: 35, 36, 37, 38, 40, 41, 42, 43, 44, 45, 46, 47, 48, 49
tag: 8MA1
lang: en
source: kvant_digital
extraction: vision
content_sha256: 6e6ab72e7dab273e885a29a2e275494b1acecbb906b1ee49387fce410916f56d
prompt_sha256: draft-1
translated_from: content/ru/1971/08/articles/08_resheniya-03bebc35.md
source_content_sha256: 54cdc9046bf3a255926094c4d6f446f7c16dbfec8155d7cf8680696411e52ecc
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 35⟧

SOLUTIONS

In this issue we publish the solution to problems M50--M60 and the end of the solution problem M45.

M50

The vertices of a regular $n$-gon are shown in several colors (each with one color) so that points of the same color serve as vertices of a regular polygon. Prove that among these polygons find equal ones.

Suppose that the vertices of some regular $n$-gon are removed by coloring so that all identically shown vertices form different regular polygons: $m_1$-gon, $m_2$-gon, $m_3$-gon, ..., where $m_1 < m_2 < m_3 < ...$. The smallest of these numbers $m_1$ will play a special role in our reasoning, and we will simply denote it by $m$.

Let us draw vectors from the center of the $O$ $n$-gon to all its vertices; Let's denote them in order: $a_1, a_2, a_3, ..., a_n$ (Fig. 1a). Then

$$\vec{a}_1 \vec{a}_2 = \vec{a}_2 \vec{a}_3 = \ldots = \vec{a}_{n-1} \vec{a}_n = \vec{a}_n \vec{a}_1 = \frac{2\pi}{n}.$$

Here and below, by $\vec{ab}$ we denote the magnitude of the (smallest non-negative) angle at which the vector $a$ must be rotated counterclockwise so that it coincides with the vector $b$; always $0 \leqslant \vec{ab} < 2\pi$.

We will say that vectors $c_1, c_2, c_3, ..., c_q$ on the plane drawn from the point $O$ form a regular system if they have equal lengths and form equal angles with each other:

$$\vec{c}_1 \vec{c}_2 = \vec{c}_2 \vec{c}_3 = \ldots = \vec{c}_{q-1} \vec{c}_q = \vec{c}_q \vec{c}_1 = \alpha > 0.$$

We will need the following almost very significant fact (its proof is given at the end of the solution).

Lemma. The sum of the vectors forming a regular system is zero.

⟦folio 36⟧

Fig. 1. Imagine that the colored dots on figure $a$ are beads strung on a wire, arranged in a spiral. We look at this spiral from above, and therefore the two red beads $A'$ and $A''$ project for us into one point $A$. If we now fasten one of the beads - $A'$, and $A''$ against the wire for another 2 turns, then we will arrive at figure $b$, at which the angles between adjacent vectors have increased 3 times.

Before using the lemma, let's do the following transformation with our vectors. We will assume that the vector $a_1$ goes to one of the vertices of the $m$-gon. Let's simply denote it by $a$ and count all angles from it (in the positive direction, that is, counterclockwise). Let us denote by $b_i$ the vector that is obtained from $a$ by rotation by an angle $m \rightarrow aa_i$ (for each $i=1,2,\dots,n$). When processing $a_i \rightarrow b_i$, which we just constructed*) (at figure 1, $\delta$ such a mapping is depicted for $m=3$), the angles between the vectors increase by $m$ times; more precisely: if $m \rightarrow a_i a_j < 2\pi$, then $\rightarrow b_i b_j = m \rightarrow a_i a_j$. Therefore, this mapping again transforms the regular system of vectors with angle $\alpha < \frac{2\pi}{m}$ into a regular system of vectors. In particular, the sum of all vectors $b_1, b_2, \dots, b_n$ is equal to zero.

Let's calculate this sum in another way: we first find the sum of vectors corresponding to the vertices of each color, and then add all these sums. Let's first consider all the vectors $a_i$, look at the vertices of the $m_h$-gon, where $m_h > m$. This is a regular system of vectors with angle $\frac{2\pi}{m_h} < \frac{2\pi}{m}$. After mapping, it will again form a correct system, and the sum of the resulting vectors will be equal to zero.

Now consider the vectors, look at the vertices of the $m$-gon. The angle between adjacent vectors is equal to $\frac{2\pi}{m}$ in this case, and after mapping all these $m$ vectors coincide with the $a$ vector, so their sum will be $m$ (at figure 1 this is the case with red and black vectors).

So, we have a contradiction: on the one hand, the sum of all $b_i$ is equal to zero, on the other hand, it is equal to $m$. Therefore our assumption is incorrect.

*) For those who are familiar with complexes of numbers, note that if the point $O$ represents zero on the complex plane, and the end of the vector $a$ represents one, then this mapping is a raising to the power $m: z \rightarrow z^m$.

⟦folio 37⟧

Proof of the lemma. A physicist would say that this statement is obvious from the symmetry messages. One way to turn these messages into rigorous evidence is as follows. Let's assume that $c_1 + c_2 + \dots + c_n = s$. Let's rotate all vectors $c_1, c_2, \dots, c_n$ around point $O$ by angle $\alpha$. Then, of course, their sum will also rotate through the angle $\alpha$. But according to the condition, the entire system of $n$ vectors after rotation by an angle $\alpha$ will coincide with itself ($c_1$ will fall into place $c_2, c_2$ - into place $c_3, \dots, c_n$ - into place $c_1$). Therefore, the vector $s$ after rotation through the angle $\alpha$ should not change. This can only be the case if $s = 0$.

It can be proven that a regular system of $q$ vectors in the general case consists of $q = dr$ vectors drawn from the point $O$ to the vertices of a regular $r$-gon, so that at each vertex there are $d$ equal vectors (if we include here “doublegons”—pairs of opposite vectors, corresponding to $m = 2$); Moreover, $\alpha$ can be equal to any of the numbers $\frac{2\pi l}{r}$, where $l$ and $r$ are coprime, $0 < l < r$. We left this remark at the end, since formulaically in the proof we dispensed with a detailed explanation of how the correct system of vectors $b_i$ is structured. But, of course, understanding the proof “in essence”, it is useful to find out this.

The idea of ​​the solution to the problem presented here was proposed by A. Livshits (Leningrad). Having carefully understood this solution, we can prove that any partition of the vertices of a regular $n$-gon into several sets corresponding to (not necessarily different) regular polygons can be obtained in this way: first, partition the $n$-gon into several $m$-gons (for this it is necessary that $n$ is divisible by $m$), then partition one of the resulting regular polygons again into several regular polygons (see Fig. 1) and so on several times. For readers who want to understand this in more detail, we also advise you to consider the connection between our “one-dimensional” problem and the “two-dimensional” problem M3, the formulation of which was discussed in «Kvant» No. 7 for 1970 (pp. 54-55) and, first of all, to establish the equivalence of our problem M50 to the following: prove that the set of all integers can be divided into a finite number of arithmetic products (infinite in both directions), the differences of which are distinguished in pairs.

M51

Prove that if the product of three positive numbers is equal to one, and the sum of these numbers is strictly greater than the sum of their reciprocals, exactly one of these numbers is greater than one.

Let $a, b, c$ be the given numbers. Then $abc = 1$ and $(a - 1)(b - 1)(c - 1) = abc - ab - bc - ac + a + b + c - 1 = a + b + c - \frac{1}{a} - \frac{1}{b} - \frac{1}{c} > 0$, therefore, of the three numbers $(a - 1), (b - 1), (c - 1)$, two are negative and one is positive (all three cannot be positive, since $abc = 1$).

M52

The five segments are such that any three can be used to form a triangle. Prove that at least one of these triangles is acute.

A triangle can be formed from the segments $x \leq y \leq z$ if $z < x + y$, and it will be acute if $z^2 < x^2 + y^2$. Suppose that there are five segments $a_1 \leq a_2 \leq a_3 \leq a_4 \leq a_5$ such that any three form a non-acute triangle. Then

$$a_5^2 \geq a_4^2 + a_3^2, \quad a_4^2 \geq a_3^2 + a_2^2, \quad a_3^2 \geq a_2^2 + a_1^2,$$

and therefore

$$a_5^2 \geq 2a_3^2 + a_2^2 \geq 3a_2^2 + 2a_1^2 \geq 2a_1a_2 + a_1^2 = (a_2 + a_1)^2,$$

that is, $a_5 \geq a_2 + a_1$ and, therefore, it is impossible to form a triangle from the segments $a_1, a_2, a_5$.

⟦folio 38⟧

M53

In triangle ABC, through the midpoint M of side BC and the center O of the inscribed circle in this triangle, draw a straight line MO, which intersects the height AH at point E. Prove that the segment AE is equal to the radius of the inscribed circle.

Let us denote the lengths of the sides of the triangle opposite the vertices A, B, C by a, b, c, respectively. We can assume that b>c (b≠c, since otherwise the lines MO and AH would not intersect, but coincide). Let us drop the perpendicular OP=r to BC (Fig. 2). Then

$$MC = \frac{a}{2}, \quad PC = \frac{a+b-c}{2}, \quad HC = \frac{a^2+b^2-c^2}{2a}.$$

$$\frac{EH}{OP} = \frac{HM}{PM} = \frac{HC-MC}{PC-MC} = \frac{2HC-a}{b-c} = \frac{a^2+b^2-c^2-a^2}{a(b-c)} = \frac{b+c}{a},$$

$$\frac{AE}{r} = \frac{AH}{r} - \frac{EH}{r} = \frac{a+b+c}{a} - \frac{b+c}{a} = 1.$$

Another, geometric solution to this problem is based on the following lemma: if we extend the radius PO to the diameter PQ of the inscribed circle and draw the straight line AQ to the intersection at point R on the side BC, then the segments BP and CR will be equal. We leave it to the reader to prove and use this lemma.

M54

Two equal rectangles are located so that their contours intersect at eight points. Prove that the area of ​​the common part of the rectangles is greater than half the area of ​​each of them.

Let the lengths of the sides of the rectangles a and b. Note that on the sides of each of the rectangles there are exactly two points of intersection with two adjacent sides of the other. (It is easy to prove that if there are 8 points of intersection in total, then each side must contain at least two points and that the intersection of the sides of one rectangle with two parallel sides of another is impossible). Let A and C be the points at which the sides of different rectangles, equal to a, intersect; B and D are the points where sides equal to b intersect. Then, obviously, the segment AC serves as the bicsettrix of the angle between sides of length a passing through point A (to prove it, it is enough to drop perpendiculars from point C to these sides and consider the pair of equal triangles formed in this case). Similarly, BD is the bicsetris of the angle between sides of length b passing through point B. Therefore, AC⊥BD, and therefore the area

⟦folio 40⟧

and check that for each individual $l$ the sums of terms of the form $X^{k-l}y^l$ on the right and left sides of the equality are equal to $^*$) (we do not write the coefficient $C_k^l$):

| | Numbers with an odd sum of digits | Numbers with an even sum of digits |
| :--- | :--- | :--- |
| Sum of terms of the form $X^k$ | $5 \cdot 10^{n-1} \Sigma A^k + 5 \cdot 10^{n-1} \Sigma B^k$ | $5 \cdot 10^{n-1} \Sigma A^k + 5 \cdot 10^{n-1} \Sigma B^k$ |
| Sum of terms of the form $X^{k-l}y^l$ $1 \leq l \leq k-1$ | $\Sigma A^{k-l}b^l + \Sigma B^{k-l}a^l = \Sigma b^l \Sigma A^{k-l} + \Sigma a^l \Sigma B^{k-l} = s_l (\Sigma A^{k-l} + \Sigma B^{k-l})$ | $\Sigma A^{k-l}a^l + \Sigma B^{k-l}b^l = \Sigma a^l \Sigma A^{k-l} + \Sigma b^l \Sigma B^{k-l} = s_l (\Sigma A^{k-l} + \Sigma B^{k-l})$ |
| Sum of terms of the form $y^k$ | $5 \Sigma b^k + 5 \Sigma a^k$ | $5 \Sigma a^k + 5 \Sigma b^k$ |

Note that our initial calculation for $n=2$ can be written using similar notation as follows:
$$\Sigma (A+b) + \Sigma (b+a) = 5\Sigma A + 5\Sigma a + 5\Sigma b + 5\Sigma a, \quad \Sigma (A+a) + \Sigma (B+b) = 5\Sigma A + 5\Sigma a + 5\Sigma B + 5\Sigma b$$
at $k=1$ only the first and last terms corresponding to $l=0$ and $l=k$ will remain).

It is easy to see that the statement of the problem is valid not only in decimal, but also in any other number system with the base $d$, where $d$ is an even number (think where in our solution the parity of the base $d=10$ is used). If we take $d=2$, we get the following curious series of equalities:
$$\begin{array}{l}
1+2=3 \\
1+2+4+7=3+5+6 \\
1^2+2^2+4^2+7^2=3^2+5^2+6^2 \\
1+2+4+7+8+11+13+14=3+5+6+9+10+12+15 \\
1^2+2^2+4^2+7^2+8^2+11^2+13^2+14^2=3^2+5^2+6^2+9^2+10^2+12^2+15^2 \\
1^3+2^3+4^3+7^3+8^3+11^3+13^3+14^3=3^3+5^3+6^3+9^3+10^3+12^3+15^3
\end{array}$$

**M56**

Four ones and five zeros are written in random order on the circle. Then a zero is written between two identical numbers, a one is written between different numbers, and the original numbers are erased. Prove that no matter how many times we repeat the process, we will never get a set of $N$ zeros. Indeed, suppose that at some $t$th step we first received a set of only zeros. Then at the $(t-1)$th step all $N$ digits were the same, and not all were equal to 0, so they were all equal to 1, and at the $(t-2)$th step every two adjacent digits should be different, but since $N$ is odd, then such an arrangement of 0 and 1 on the circle does not exist.

At the same time, we answered (so far only for odd $N$) the question that remained unanswered in the solution M19 («Kvant» No. 11, 1970, pp. 37-38); in this problem, zeros are called “resting cells”, ones are called “excited cells”, and the correct

*) We do not need to know the formulas for calculating $C_k^l$ (the so-called “binomial coefficients”). The only important thing is that these are numbers that do not depend on the variables $X$ and $y$.

**) Those who solved this problem before may have noticed that we swapped the words “ones” and “zeros” in the wording. This, of course, does not change the existence of problem M19 and M56, which will be discussed below.

⟦folio 41⟧

the transitions are exactly the same. In these terms, our result is formulated as follows: if $N$ is odd, and at the initial moment not all cells are excited (and not all are at rest), then the excitation will never die out.

What will happen with other $N$? To find out this, we use the following lemma (it can be proved by induction on $k$; it is valid for both the problem on a line and for a circle); if at $t=0$ in place $2^{k-1}-M$ there are identical numbers on either side of a given number $a$, then after $t=2^k$ steps there will be a zero in place $a$, and if e are different, then one. It immediately follows that if $N=2^m$, where $m$ is a natural number, then from any set in $N$ steps a set of only zeros will be obtained.

Let now $N=2^m L$, where $L$ is odd. Let's follow the changes that occur every $T=2^m$ steps. For each $L$ digits spaced $2^m$ apart (“at the vertices of a regular $L$-gon”), these changes will be exactly the same as if only these $L$ digits were placed around the circle, the same process was repeated with them, and we followed each step. From here it is not difficult to obtain the answer in the most general case: the “all zeros” state is achieved if and only if the initial sequence of 0 and 1 was periodic with period $2^m$ (see Fig. 4).

**M57**

a) Find a number $k$ that is divisible by 2 and 9 and has a total of 14 divisors (including 1 and $k$).

b) Prove that if you replace 14 with 15, then the problem will have several solutions, but if you replace 14 with 17, there will be no solutions at all.

Let $M=p_1^{\alpha_1}p_2^{\alpha_2}\dots p_r^{\alpha_r}$ be the decomposition of the number $M$ into prime factors; for the definition we will assume that $\alpha_1 \geqslant \alpha_2 \geqslant \dots \alpha_r \geqslant 1$. The divisors of the number $M$ have the form $p_1^{\beta_1}p_2^{\beta_2}\dots p_r^{\beta_r}$, where each $\beta_i$, independently of the others, can belong to the values 0, 1, ..., $\alpha_i$, and therefore the total number of divisors $M$ (including 1 and $M$) is equal to $(\alpha_1+1)(\alpha_2+1)\dots(\alpha_r+1)$ (see the solution to Problem 1 in the article “Combinatorics” in «Kvant» No. 1, 1971, p. 19).

a) 14 can only be factored one way: $14=7 \cdot 2$, so if $M$ has 14 factors, then $r=2$, $\alpha_1=6$, $\alpha_2=1$. We also know that 3 is included in the expansion $M$ with an exponent greater than 1, and 2 - with an exponent greater than 0. It follows that $M=3^6 \cdot 2=1458$.

b) For 15 divisors, the possible answers are $M=3^2 \cdot 2^4$ and $M=3^4 \cdot 2^2$, and 17 divisors can only have numbers of the form $M=p^{16}$, where $p$ is a prime.

**M58**

There are three bottoms on the plane, intersecting at one point. A dot is marked on one of them. It is known that the primaries are bissertrices of a certain triangle, and the marked point is one of its vertices. Construct this triangle.

First decision. Suppose that $O$ is the intersection point of bissertrices $AK$, $BL$ and $CM$ of triangle $ABC$ (Fig. 5); Then

$$\angle MOB = \angle OCB + \angle OBC = \frac{1}{2} (\angle ACB + \angle ABC) = \frac{\pi}{2} - \angle CAK,$$

that is, $\angle CAK = \frac{\pi}{2} - \alpha$. Therefore, if the lines $AK$, $BL$, $CM$ and the point $A$ are given, then by constructing angles equal to $\varphi = \frac{\pi}{2} - \alpha$ on one and the other side of the ray $AO$. We will find the required vertices $B$ and $C$ (provided that $\varphi > 0$.

⟦folio 42⟧

Fig. 5. Fig. 6.

φ<β and φ<γ). It is also necessary to prove that the constructed triangle ABC has lines BL and CM along the bisectors. Angles ABL and ACM are easy to calculate—they are equal to the correspondence of $\frac{\pi}{2} - \beta$ and $\frac{\pi}{2} - \gamma$. The difficulty lies only in proving that $\Rightarrow LBC = \frac{\pi}{2} - \beta$ and $\Rightarrow MCA = \frac{\pi}{2} - \gamma$ (although it is clear that their sum is $\alpha$); it can be preflighted, for example, like this: if $\Rightarrow LBC < \Rightarrow ABL$, then the bisector of the angle ABC intersects the segment AO, therefore the bisect of the angle ACB also intersects it, and therefore $\Rightarrow MCB < \Rightarrow ACM$, so the sum $\Rightarrow LBC + \Rightarrow MBC$ is less than $(\frac{\pi}{2} - \beta) + (\frac{\pi}{2} - \gamma) = \alpha$. In the same way it can be shown that the case $\Rightarrow LBC > \Rightarrow ABL$ is impossible.

Second solution. Let us construct the points $A'$ and $A''$, symmetrical to the given point $A$ with respect to bisectors not passing through $A$. It is clear that both points $A'$ and $A''$ must lie on the line BC - on the side of the desired triangle ABC (or on its extension). By drawing a straight line through $A'$ and $A''$, we will thereby find the required points B and C (Fig. 6).

Note that although the second solution is more effective, with this approach it is more difficult to write down the conditions under which the problem has a solution *). These conditions are: $\alpha < \frac{\pi}{2}$, $\beta < \frac{\pi}{2}$, $\gamma < \frac{\pi}{2}$ (since $\alpha + \beta + \gamma = \pi$, they can also be written like this: $\alpha + \beta > \frac{\pi}{2}$, $\beta + \gamma > \frac{\pi}{2}$, $\gamma + \alpha > \frac{\pi}{2}$). If they are fulfilled, then the solution is unique. Think about how you can obtain these conditions for each of the above solution methods.

M59

There are several weights with weights 1 e, 2 e, 3 e,..., n e. They need to be divided into three piles of equal weight. At what $n$ was this possible?

Let us show that this can be done if and only if $n > 3$ and one of the numbers $n$ or $n+1$ is divisible by 3 (that is, with $n$ equal to 5, 6, 8, 9, 11, 12, 14, 15, ...).

*) It may turn out that two of these lines are bisectors of external, and not internal, angles of the constructed triangle; this does not eliminate us.

⟦folio 43⟧

The necessity of these conditions, since the total weight of the mushroom $1 + 2 + 3 + \dots + n = \frac{n(n+1)}{2}$ must be divided by 3.

For the proof, it is enough first that partitioning is possible with $n$ equal to 5, 6, 8 and 9 (this is shown in Fig. 7). All other values ​​of $n$ that interest us are obtained from these four by adding a certain number of sixes, and any group of six consecutive integers $a+1, \dots, a+6$ is easily divided into three pairs of numbers giving equal sums: $a+1$ and $a+6$, $a+2$ and $a+5$, $a+3$ and $a+4$.

Fig. 7.

M60

Let's consider all natural numbers whose decimal notation includes only the digits 1 and 0. Divide these numbers into two groups so that the sum of any two different numbers from the same group contains at least two units in its decimal notation.

Let us assign to one group all the numbers whose notation has an odd number of ones, and to the other group all the numbers whose notation has an even number of ones. Then it is clear that two numbers cannot fall into one group; the cession is excellent only in one digit, therefore such a division satisfies the requirements of the problem (units appear in those digits of the sum where one number has a 1 and the other does not).

Many readers have provided reasoning to prove that the described partition:

first group: 1, 10, 100, 111, 1000, 1011, 1101, 1110, ...
second group: 11, 101, 110, 1001, 1010, 1100, 1111, 10001, ...

the only one that satisfies the conditions of the problem.

More complete solutions to the problems discussed above were sent to us by V. Didenko from cela Vesely Kut, Odessa region, E. Turkevich from Chernivtsi, A. Rubin from cela Ukladovka, Vinnitsa region, A. Slinkin from Moscow, Y. Tomsinsky from Leningrad, M. Perelmuter from Kyiv, O. Khudaverdyan from Yerevan.

M45

(Continued. For the beginning of the solution, see «Kvant» No. 7, p. 30.)
We just have to prove this fact.

Theorem. From 2$p$-1 any integers we can choose $p$, the sum of which is divisible by $p$ (an arbitrary prime number).

We present here the proof suggested by S. Voronin (Moscow).

It is clear that in the proof we can consider all numbers “modulo $p$”, that is, we are only interested in which of the remainders 0, 1, 2, ..., $p-1$ gives this or that number when divided by $p$. It is convenient to imagine (especially when talking about “addition modulo $p$”) that these $p$ remainders are considered in a circle (Fig. 8).

Lemma. Let data $r$ integers $b_1, b_2, \dots, b_r$; $0 < b_i < p$ for all $i=1, 2, \dots, r$ and $0 < r < p$ (prime). Then from these numbers it is possible to compose at least $r+1$ sums that give different remainders when divided by $p$ (in this case, it is allowed to be the sum of the “empty set of terms”, which is considered equal to zero, the sum of one term, of two,..., of all $r$ terms).

Proof. For $r=1$ this is obvious: the sums give remainders 0 and $b_1$. Suppose this is true for $r=k<p-1$ and false for $r=k+1$, and we arrive at a contradiction. Let the sums of $k$ terms $b_1, b_2, \dots, b_k$ give $k+1$ different remainders 0, $s_1, \dots, s_k$. Then,

⟦folio 44⟧

Fig. 8. To find the sum of $a+b$ modulo $p$, you need to count $b$ units from $a$ counterclockwise (this figure, corresponding to $p=11$, shows the sum 8+8, which modulo 11 is equal to 5).

Since after adding $b=b_{k+1}$ the number of different sums should not increase, all sums

$$0+b, s_1+b, \ldots, s_k+b$$

(modulo $p$) are contained in the set

$$\{0, s_1, \ldots, s_k\}.$$

In other words, if you add $b$ to any element of this set, you will again get an element of the same set (try to imagine such a set on figure 8). Thus, this set depends on and contains the elements 0, $b$, $2b$, $3b$, $\ldots$, $(p-1)b$. But it is clear that all these elements are different (in absolute value): the difference

$$ib-jb=(i-j)b,$$

where $0<i-j<p$ and $0<b<p$ cannot be divided by $p$ since $p$ is prime. Thus, we have proven that the set $\{0,s_1, \ldots, s_k\}$ contains all $p$ distinct elements, although we assumed that

$$k+1<p.$$

The lemma is proven.

Proof of the theorem. Let

$$a_1 \leqslant a_2 \leqslant \ldots \leqslant a_p \leqslant a_{p+1} \leqslant \ldots \leqslant a_{2p-1}$$

— remainders from dividing the given $2p-1$ numbers by $p$. Let's consider $p$ more such numbers:

$$a_{p+1}-a_2, a_{p+2}-a_3, \ldots, a_{2p-1}-a_p.$$

(*)

If any one of them is zero, for example

$$a_{p+1}-a_{l+1}=0,$$ is then $a_{l+1}=a_{l+2}=a_{l+3}=\ldots=a_{l+p}$, and the sum of the corresponding $p$ numbers is divisible by $p$. It remains to consider the case when all numbers (*) are different from zero.

Let's find the remainder $x$ when the sum $a_1+a_2+\ldots+a_p$ is divided by $p$. If $x=0$, then everything is clear. If $x\neq 0$, then, using the lemma, we can compose from the differences (*) sums that give the remainder $p-x$ when divided by $p$. By adding the appropriate differences to $a_1+a_2+\ldots+a_p$ and making obvious cancellations, we get the sum of $p$ terms dividing by $p$.

Using the result problem M45, it is not difficult to establish that the statement “From any $a$ integers we can choose $b$ numbers whose sum is divisible by $c$” (where $a, b, c$ are specific natural numbers) is true if and only if $b$ is divisible by $c$ and $a \geq b+c-1$.

N. B. Vasiliev

In this issue we publish solutions to problems F66—F71.

F66

To the battery with e. d.s. 9 V with an unknown internal resistance, an amperor and a voltmeter (Fig. 9) are connected in series. The resistances of the devices are unknown. If a resistance is connected in parallel with the voltmeter (its value is also unknown), then the ampere reading is doubled, and the voltmeter reading is doubled. What was the voltmeter reading after connecting the resistance?

The voltmeter shows the presence of voltage on itself, and the amperor shows the flow through it. According to Ohm's law for a complete circuit e. d.s. battery is equal to the sum of the voltage in the sections of the circuit: $U$ - on the voltmeter and $U_1$ - on the internal resistance of the source and the ampere:

$$E=U+U_1.$$

⟦folio 45⟧

Fig. 9. Fig. 10.

After connecting the resistance, the voltage drop across the voltmeter and the resistance connection in parallel with it became equal to $U' = \frac{U}{2}$ (voltmeter readings). At the same time, the voltage drop across the source resistance and ammeter doubled and became equal to $U'_1 = 2U_1$. Indeed, the resistance of this section has not changed, but the current flowing through it has doubled. Pozotomu

$$E = \frac{U}{2} + 2U_1.$$

(2)

Solving equations (1) and (2) together, we find that $U = 6\ \theta$. Therefore, after connecting the resistance, the voltmeter showed voltage

$$U' = \frac{U}{2} = 3\theta.$$

The correct solution was sent by N. Fedin (Omsk), S. Ivanov (Moscow), E. Gubarev (Moscow), V. Sytsev (Alga Aktobe region), N. Smirnov (Gorky), A. Anishchenko (Sarapul, Udmurt Autonomous Soviet Socialist Republic), A. Braverman (Perm), A. Senyavin (Moscow), V. Pomatsev (Gorky), V. Kalinichev (Moscow), M. Praeger (Tomsk).

F67

The buffer device (Fig. 10) consists of a rod $A$, a spring $B$ placed on the rod, and a guide bushing $C$. The bushing can move inside a channel made in a solid wall $D$. When the bushing moves between its outer surface and the wall, a constant friction force $F_{Тр}$ acts. The bushing rod and the spring move along the rod without friction.

A ball of mass $m$ is placed on the end surface of the rod $A$, having a speed $v_0$ before the collision. At what speed will the ball fly away?

The masses of the rod, spring and bushing are negligible compared to the mass of the ball. Spring stiffness coefficient $k$.

When the ball is removed, the rod begins to move, releasing the spring. In this case, a force $F = kx$ acts on the bushing from the side of the deformed spring, where $x$ is the deformation of the spring. If the initial speed of the ball is high enough that the deformation of the spring reaches a maximum value $x_{\max}$, at which the spring acts on the bushing with a force equal to the friction force of the bushing against the wall. After this, the bushing begins to move, and during the movement of the bushing the spring will not deform: the force pushing it off does not change and is equal to $F_{Тр}$. Since when the bushing moves, a friction force acts on it, the kinetic energy of the system turns into heat, and after some time the ball and rod are left. Then the spring begins to straighten. This, of course, will not cause the bushing to move - the force with which the action.

⟦folio 46⟧

a spring blows on it, less than $F_{\tau p} = kx_{\max}$, since $x < x_{\max}$. So there will be no further energy losses in the system. When the spring straightens, its potential deformation energy $W_{\pi} = \frac{kx_{\max}^2}{2}$ will turn into the kinetic energy of the ball.

Reception, the potential energy of the ball is zero.
Let us now write down the law of conservation of energy

$$\frac{mv^2}{2} = \frac{kx_{\max}^2}{2},$$

where $v$ is the speed of the ball after it bounces off the wall.

Considering that $x_{\max} = \frac{F_{\tau p}}{k}$, we get $v = \sqrt{\frac{F_{\tau p}^2}{km}}$.

At a sufficiently high speed $v_0$, the speed of the ball that bounces off the rod does not depend on its initial speed. The system “eats” the entire energy reserve above the value $W = \frac{kx_{\max}^2}{2}$.

Let us now find out what “sufficiently high speed $v_0$” means. This is the speed at which the force acting from the spring on the bushing reaches a value of $F_{\tau p}$, and, therefore, the deformation of the spring reaches a value of $x_{\max} = \frac{F_{\tau p}}{k}$. It is clear that for this the initial kinetic energy of the ball must be greater than the value $\frac{kx_{\max}^2}{2} = \frac{F_{\tau p}^2}{2k}$:

$$\frac{mv^2}{2} > \frac{F_{\tau p}^2}{2k}.$$

This condition gives us the limit of “sufficiently high speed”:

$$v_0 > \sqrt{\frac{F_{\tau p}^2}{km}}.$$

How will a collision occur if the initial speed of the ball is less than this value or equal to it?

In this case, the spring deformation is less than $x_{\max}$ and the spring will not move the bushings. This means that there will be no loss of energy and the ball will bounce back, having the same kinetic energy, and therefore the same speed, as before the collision. So,

$$v = \begin{cases} v_0 \text{ при } v_0 \leqslant \sqrt{\frac{F_{\tau p}^2}{km}}, \\ \sqrt{\frac{F_{\tau p}^2}{km}} \text{ при } v_0 > \sqrt{\frac{F_{\tau p}^2}{km}}. \end{cases}$$

The correct solution was sent by P. Mkrtchyan (Yerevan), Kutsek (Rzhev), N. Fedin (Omsk), I. Grishik (David-Gorodok, Brest region, BSSR), A. Vyrodov (Gagra), P. Zaitsev (Gagra), M. Premer (Tomsk).

F68

The stacks of the vessel in which the gas is located have a temperature of $T$. Gas temperature $T_1$. In which case is the gas pressure on the sides of the vessel greater: when the sides of the vessel are colder than the gas ($T < T_1$), or when the temperature ($T > T_1$)?

The temperature of a gas is determined by the average kinetic energy of its molecules: $\frac{mv^2}{2} = \frac{3}{2} kT$ ($k$ is Boltzmann’s constant). This means that than

⟦folio 47⟧

The higher the temperature of the gas, the greater the average speed of movement of its molecules, that is, the greater the average momentum of the molecule.

If the temperature of the wall coincides with the temperature of the gas, then the molecule, hitting the wall, changes its momentum $p_0$ to $-p_0$. This means that the change in momentum is $2p_0$.

When $T > T_1$, the gas heats up. This means that gas molecules bounce off the wall with a higher speed than they fly into, and therefore with a greater impulse (Fig. 11, a). The change in momentum in this case will be greater than $2p_0$.

If $T_1 < T$, then the gas cools, that is, the gas molecules bounce off the wall with less momentum than they hit it (Fig. 11, b). It is clear that in this case the change in the momentum of the molecule is smaller than in the case of $T_1 > T$. Since, in accordance with Newton’s II law, the change in momentum is proportional to the average force acting on the molecule from the side of the wall, and in accordance with Newton’s III law, the average force acting on the molecule is numerically equal to the average force acting on the wall, then at $T_1 < T$ the gas pressure on the wall is greater than at $T_1 > T$.

The correct solution was sent by V. Chupin (Torzhok), N. Fedin (Omsk), V. Kalintsev (Moscow), S. Ivanov (Moscow).

The shape of the liquid surface must be such that the reaction force N of the surrounding liquid acting on an element of the liquid volume with mass $\Delta m$ at the surface is directed perpendicular to the surface. Otherwise, the force N will have a component directed along the surface of the liquid, and the liquid will not be able to be in equilibrium.

Let us now look at how the force N is directed. It must balance two forces: the force $F_1$ of the Earth's attraction, directed towards the center of the Earth, and the additional force $F_2$ of the ball's attraction, directed towards the center of the ball (at figure 12 the force $F_2$ is made disproportionately large compared to the force $F_1$). The force N must be numerically equal and opposite in direction to the forces $F_1$ and $F_2$ equal to Q. This means that it is deviated to the right from the vertical and the surface of the water above the ball is convex.

Let us estimate the magnitude of the “swelling” of the water surface. Consider a point B lying at a small distance x from the vertical AO passing through the center of the ball ($x \ll r$, where r is the radius of the ball), O is the center of curvature and BO = R is the radius of curvature of the water surface.

$Q \approx F_1$ (since $F_2 \ll F_1$), and $Q \sin \alpha = F_2 \sin \beta$. Since the angles α and β are small ($x \ll r$, $x \ll R$), then

$$\sin \alpha \approx \mathrm{tg} \alpha \approx \frac{x}{R}$$

Pozny can be considered that

$$Q(x/R) = F_2(x/r)$$

⟦folio 48⟧

or
$$R = r \frac{Q}{F_2} = r \frac{F_1}{F_2}.$$

But
$$F_1 = \gamma \frac{\left( \frac{4}{3} \pi R_3^3 \rho \right) \Delta m}{R_3^2} = \frac{4}{3} \pi \gamma r R_3 \rho \Delta m$$
($R_3$ is the radius of the earth, $\rho$ is its density), and
$$F_2 = \gamma \frac{\frac{4}{3} \pi r^3 (\rho_1 - \rho_0) \Delta m}{r^2} = \frac{4}{3} \pi \gamma r (\rho_1 - \rho_0) \Delta m$$
($\rho_1$ is the density of the ball, $\rho_0$ is the density of water). That's why
$$R = r \frac{\frac{4}{3} \pi \gamma R_3 \rho \Delta m}{\frac{4}{3} \pi \gamma r (\rho_1 - \rho_0) \Delta m} = R_3 \frac{\rho}{\rho_1} \approx R_3 \frac{\rho}{\rho_1}$$
(since $\rho_1 \gg \rho_0$). Substituting the values ​​$R_3 = 6,4 \cdot 10^6 m$, $\rho = 5,5 e/cm^3$ and $\rho_1 = 11,3 e/cm^3$ here, we find $R \approx 3,2 \cdot 10^6 m$.

Assuming that the swelling extends to a distance $x$ from the point $A$ (this estimate is highly dependent!), we find its height
$$h = x \lg \alpha \approx \frac{r^2}{R}.$$

If the radius of the lead ball is 1 m, then $h \approx 3 \cdot 10^{-7} m$.

This means that the swelling effect cannot be observed experimentally even with the help of integration of methods. After all, the length of light is several thousand angstroms ($1 \text{Å} = 10^{-10} m$), that is, greater than the magnitude of the rise.

The correct solution was sent by $H$. Fedin (Omsk).

F70

A cyclist easily develops a traction force of 10 kg. The force does not exceed 5 kg. It would seem that in a few hours a bicycle can reach escape velocity. However, this has not yet been possible. Why?

The force with which a bicycle can press on the pedals is not constant and depends on the speed of the bicycle (Fig. 13). It is maximum at $v = 0$ and becomes equal to zero at a speed at which the pedal rotation period becomes equal to the cycling reaction speed. After this, the cycling speed can no longer increase.

Many readers argue this way: the power that a bicycle develops cannot exceed a certain maximum value. But

⟦folio 49⟧

$N = F \cdot v$, so the speed value cannot become greater than

$$v = \frac{N_{\text{max}}}{F - F_{\text{trp}}}.$$

This, of course, is true and is due precisely to the fact that the dependence of the force with which a person presses on the pedals on the speed of movement is as shown in figure 13.

F71

There is a uniformly charged segment $AB$. What is the direction of the electric field created by this segment at point $C$: along the median of triangle $ABC$? according to his bissertika? in height? on none of these lines?

The field voltage is a vector, and in our problem there are only four selected directions: along the median, bissertic or altitude of the triangle $ABC$ and parallel to the segment $AB$. The field direction vector must be directed in one of these directions. It is clear that it cannot be parallel to the segment $AB$: the direction of the field of the charged segment is equal to the sum of the directions of the fields of the parts of the segment, and they are all directed towards the segment or away from it (depending on the sign of the charge of the segment).

The height of the triangle $ABC$ is also not suitable: for example, if the point $C$ is located away from the segment, at a distance much greater than the length of the segment, then it is clear that the direction of the field at the point should be directed towards the segment $AB$, and not perpendicular to it.

So, we are left with the median and bissertis. the directionality $E$ of the field of a segment is equal to the sum of the directions of the fields of its parts. In order for the vector $E$ to be directed along the median, it is necessary that segments of equal length $\Delta x$, located at equal distances from the middle of the segment, create the same field at point $C$.

Only in this case the sum of vectors $\Delta E$ will be directed along the median of the triangle $ABC$. However, this is impossible: segments of equal length have the same charge $\Delta Q = \sigma \Delta x$ (σ is the linear charge density, that is, the charge per unit length of the segment), and the distances to the point $C$ are different.

⟦folio none⟧

This means that the vector $E$ is directed along the bisector of the triangle $ABC$.
Let's make sure of this. Let us find the directionality of the field of the segment $\Delta x$ such that the straight line drawn from it to the point $C$ forms an angle $\alpha$ with the altitude of the triangle and $\Delta x \ll r$ (Fig. 14). $\Delta E = \frac{\Delta x \sigma}{r^2}$. If the segment $\Delta x$ is visible from the point $C$ at an angle $\Delta \alpha$, then $\Delta x_1 = r \Delta \alpha$ (the angle $\alpha$ is small, so $tg \frac{\Delta \alpha}{2} = \frac{\Delta \alpha}{2}$, and $\frac{\Delta x_1}{2} = r tg \frac{\Delta \alpha}{2}$) and $\Delta x = \frac{\Delta x_1}{\sin(90^\circ - \alpha)} = \frac{r \Delta \alpha}{\cos \alpha}$. Therefore $\Delta E = \frac{r \Delta \alpha \sigma}{r^2 \cos \alpha} = \frac{\Delta \alpha \sigma}{r \cos \alpha}$. But $r \cos \alpha = h$.
That's why
$$\Delta E = \frac{\Delta \alpha \sigma}{h}.$$

The field voltage of the segment, which is visible from the point $C$ at an angle $\Delta \alpha$, does not depend on the angle $\alpha$. All segments that are visible from point $C$ at the same angle create a field of the same size in it. But for any segment $\Delta x$ located to the left of the bisector $CD$ of triangle $ABC$, one can find a segment to the right of it such that it is visible from the point $C$ at the same angle $\Delta \alpha$ as the segment $\Delta x$, and the angle $\beta$ is formed by the primo connecting it with point $C$, the same as the segment $\Delta x$. Since these segments create the same field at point $C$, the vector $\Delta E$ of the sum of vectors $\Delta E_1$ and $\Delta E_2$ of the directional fields of the segments is directed along the diagonal of the rhombus built on the vectors $\Delta E_1$ and $\Delta E_2$, that is, along the bisector $CD$. This is true for any angle $\beta$, that is, for any pair of segments. This means that the directivity vector of the field of the segment $AB$ is directed along the bisector of the triangle $ABC$.

The correct solution was sent by N. Fedin (Omsk) and I. Grichik (David-Gorodok, Brest region).

I. Sh. Slobodetsky.

To “Problems on squared paper”

1. Add two dots to the cross from each of the four ends. The number of possible squares with vertices at the highlighted nodes will increase by 10 (four small red squares (see Fig.]), four squares whose pattern is colored black; two squares, one of which is highlighted blue).

The cross in the problem can be considered as an additional row of nodes to the central square, allowing only one square. It allows the construction of $10 \cdot 8 + 1 = 81$ different squares.
