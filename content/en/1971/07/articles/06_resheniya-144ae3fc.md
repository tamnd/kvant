---
id: 1971-7-resheniya-144ae3fc
issue: kvant_1971_7
year: 1971
number: "7"
title: Solutions to problems M39—M49; F45, F59—F65
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 26
page_last: 41
page_labels: 24, 25, 28, 29, 30, 31, 32, 33, 34, 35, 36, 37, 38, 39
tag: TOTZ
lang: en
source: kvant_digital
extraction: vision
content_sha256: eefb2d853c616b32274ea229b674ab054da5114143bcb1399ff79d605625756c
prompt_sha256: draft-1
translated_from: content/ru/1971/07/articles/06_resheniya-144ae3fc.md
source_content_sha256: e1a3fbdb757005486ff829983ef70add42079516e3e900a92be749f36af4d3b3
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 24⟧

SOLUTIONS

In this issue we publish solutions to problems M39—M49.

M39

Prove that non-negative integers $x, y$ satisfy the equation $x^2 - mxy + y^2 = 1$ (where $m$ is the given integer greater than one) if and only if $x$ and $y$ are adjacent terms of the sequence $\varphi_0 = 0, \varphi_1 = 1, \varphi_2 = m, \varphi_3 = m^2 - 1, \varphi_4 = m^3 - 2m, \varphi_5 = m^4 - 3m^2 + 1$, ..., in which $\varphi_{k+1} = m\varphi_k - \varphi_{k-1}$ for all $k \ge 1$.

For example, all solutions to the equation

$$x^2 - 3xy + y^2 = 1$$

(1)

in integers $(x, y)$, $0 \leq x < y$, are pairs

$$(0, 1), (1, 3), (3, 8), (8, 21), \dots$$

(2)

neighboring terms of the sequence $0, 1, 3, 8, 21, \dots$ defined by the conditions $\varphi_0 = 0, \varphi_1 = 1, \varphi_{k+1} = 3\varphi_k - \varphi_{k-1}$ for all $k \ge 1$.

Let us solve this problem for $m = 3$ (for other $m > 1$ the solution is similar.) We must prove that, firstly, all pairs of numbers (2) satisfy equation (1) and, secondly, no other pairs of non-negative numbers satisfy this equation. (Note that this second and more difficult part of the solution was largely overlooked by the readers who sent letters.)

In sequence (2), each pair $(x, y)$ is followed by a pair $(x_1, y_1)$, which can be obtained from $(x, y)$ using the following transformation:

$$x_1 = y, y_1 = 3y - x.$$

(3)

We denote this transformation $(x, y) \rightarrow (y, 3y - x)$ by the letter $T$. Not difficult

⟦folio 25⟧

check that if the pair $(x, y)$ satisfies equation (1), then the pair $(x_1, y_1) = T(x, y)$ also satisfies it:

$$x_1^2 - 3x_1y_1 + y_1^2 = y^2 - 3y(3y - x) + (3y - x)^2 = y^2 - 3xy + x^2.$$

(4)

From here it is immediately clear that all pairs (2) satisfy equation (1): after all, the pair (0, 1) satisfies it, and all the others are obtained from it using a finite transformation number $T$.

Let us now prove that there are no other solutions $(x, y)$ in integers subject to the conditions $0 \leq x < y$ of equation (1). Let $(x_1, y_1)$ be one of such solutions. Let us find a pair $(x, y)$ from which these $x_1$ and $y_1$ are obtained using formulas (3) - for this it is enough to express $x$ and $y$ in terms of $x_1$ and $y_1$:

$$x = 3x_1 - y_1, y = x_1.$$

(5)

We will denote such a transition from $(x_1, y_1)$ to $(x, y)$—the inverse transformation *) to $T$—by $T^{-1}$. From equalities (4) it follows that if the pair $(x_1, y_1)$ satisfies equation (1), then the pair $(x, y) = T(x_1, y_1)$ also satisfies it. Let us show that if, in addition, $0 < x_1 < y_1$, then

$$0 \leq x < y.$$

(6)

Let us represent the equality $x_1^2 - 3x_1y_1 + y_1^2 = 1$ of the following in two ways:

$$x_1^2 + y_1(y_1 - 3x_1) = 1,$$

$$x_1(x_1 - y_1) + y_1(y_1 - 2x_1) = 1.$$

(7)

From equality (7) it immediately follows ($x_1$ and $y_1$ are positive!) that $-x = y_1 - 3x_1 \leq 0$, and if $y_1 - 3x_1 = 0$, then $x_1 = 1$ and $y_1 = 3$. From equality (8), in turn, it follows that $y - x = y_1 - 2x_1 > 0$ (after all, $x_1 - y_1$ is negative). Inequalities (6) have been proven. Note that they can be rewritten like this:

$$0 \leq x < x_1,$$

(9)

since $x_1 = y$. So, any solution $(x_1, y_1)$, $0 < x_1 < y_1$, after the transformation $T^{-1}$ goes into the solution $(x, y)$, for which $0 \leq x < y$. If at the same time $x > 0$, then we can apply $T^{-1}$ one or more times, obtaining new (smaller in magnitude) solutions. Indeed, as (9) shows, the magnitude of the integer $x$ decreases with each transformation. Therefore, after a certain finite number of steps we must stop, and we can stop only when we obtain the solution $(x, y)$, which has $x = 0$ and, therefore, $y = 1$. Thus, we have proven that from each solution $(x_1, y_1)$ for a finite number transformed $T^{-1}$ a solution (0, 1) is obtained. It follows from this that each solution from (0, 1) is transformed by a finite number $T$ (that is, that there are no other solutions different from (2). The problem is completely solved.

This solution can be presented more clearly as follows. We will represent the pair of numbers $(x, y)$ as usual, as a point on the plane. Then the equation $x^2 - 3xy + y^2 = 1$ defines a curve on the plane called a “sperbola”. (On the cover there is a whole family of hyperbolas given by the equations $x^2 - 3xy + y^2 = c$ with different values ​​of the parameter $c$, and the one we are interested in is yellow.) Solving this equation in integers means indicating all the points with integer coordinates that lie on the hyperbola. However, such a point is easy to indicate: it is a black point with coordinates (0, 1). All the rest (within the angle $0 \leq x < y$), as we have proven, are obtained from it by successive application of the transformation $T : (x, y) \rightarrow (y, 3y - x)$. This transformation of the $T$ plane has the following properties:

1) Transforms every straight line in the plane back into a straight line (such transformations are called linear).

*) The concept of an inverse transformation was discussed in the article by A. N. Kolmogorov “What is a function?” («Kvant» No. 1,1970).

⟦folio 28⟧

Fig. 2. Among the $m+k+1$ elements, first select one (such that there are at least $k$ elements to the left of it and to the right of it), draw a line along it, and then select $k$ elements to the left of the line and to the right of the line. On ours figure $m=9, k=3, m+k+1=13$.

la certain $k+m$ elements, and then another $k$ elements from the remaining $n-m$ elements. What has been said can be found like this. Let's place the data of $n+k$ elements “in a line” and draw a vertical line separating $k+m$ elements on the left from $n-m$ elements on the right. Let's somehow select $k$ elements to the left of the bar and $k$ elements to the right of the bar, and then form a connection of each of these “right” selections. There will obviously be $C_{k+m}^k \cdot C_{n-m}^k$ such connections.

Now it is not difficult to prove that

$$C_k^k \cdot C_n^k + C_{k+1}^k \cdot C_{n-1}^k + C_{k+2}^k \cdot C_{n-2}^k + \dots + C_n^k \cdot C_k^k = C_{n+k+1}^k \cdot C_{n-k+1}^k.$$

To do this, it is enough to establish a one-to-one correspondence between samples of $n+k+1$ elements of $2k+1$ and samples of $n+k$ elements of the following form: “$k$ elements to the left of the line; trait; $k$ elements to the right of the line,” the total number of which is equal to the sum on the left side of equality (2). So, the required amount is

$$(k!)^2 \cdot C_{n+k+1}^2 = \frac{(n+k+1)!(k!)^2}{(2k+1)!(n-k)!}.$$

In particular, for the first task M40 we have $k=1$ and therefore the sum will be $C_{n+2}^3 = \frac{(n+2)(n+1)n}{6}$.

If the above reasoning seems difficult to you, and even more so if it seems interesting to you, we recommend that you look into N. Ya. Vilenkin’s book “Combinatorics” (M., “Nauka”, 1969). There, in particular, on page 57, formula (24), similar to formula (2), is proven.

V. N. Berezin

M41

Given a circle, its diameter $AB$ and a point $C$ on this diameter. Construct two points $X$ and $Y$ on the circle, symmetrical with respect to the diameter $AB$, for which the line $YC$ is perpendicular to the line $XA$.

Let $K$ be the intersection point of the segments $XY$ and $AB$; by condition $XY \perp AB$ and $XK = KY$. For any point $X$ on circle $\Rightarrow AXB = 90^\circ$. Therefore, requirement $YC \perp AX$ is equivalent to each of the following conditions:

$$YC \parallel BX, \Rightarrow YCB = \Rightarrow CBX,$$

$$\triangle CYK = \triangle KBX, \quad CK = KB.$$

Thus, if we use the perpendicular to the line $AB$ in the middle of the segment $CB$, we will obtain two required points at its intersection with the circle (any of them can be taken as $X$, then the other will play the role of $Y$).

⟦folio 29⟧

M42

The digits of some seventeen-digit numbers are written in reverse order. The resulting number is added to the original. Prove that at least one of the digits of their sum is even.

Let us prove indica by $n$ that this statement is true for any $(4n+1)$-digit number. At $n=0$ it is obvious. Suppose that for some $n$ it is false, that is, there is a number $a_1 a_2 a_3 \dots a_{4n-1} a_{4n} a_{4n+1}$ such that in total

$$\frac{a_1}{a_{4n+1}} + \frac{a_2}{a_{4n}} + \dots + \frac{a_{4n-1}}{a_{4n}} + \frac{a_{4n+1}}{a_{4n}}$$

all numbers are odd. Then the sum of the digits $a_1 + a_{4n+1}$ is odd and in the places indicated by arrows will not carry over the unit to the next digit. Therefore, in the sum of $(4n-3)$-digit numbers

$$\frac{a_3 \dots a_{4n-1}}{a_{4n-1} \dots a_3}$$

Also, all digits are odd, therefore, our statement is not true for $(n-1)$. The proof is complete (think about why the usual “indication step” - “if true for $n$, then it is true for $(n+1)$” - can be replaced by a step in the opposite direction: “if false for $n$, then false for $(n-1)$”!).

Note that the proven statement cannot be simplified: for numbers in which the number of digits is even or has the form $(4n+3)$, the statement of the problem may not be true:

$$11 \ 112 \ 222 + 22 \ 221 \ 111 = 33 \ 333 \ 333, \ 72 \ 727 \ 262 \ 626 + 62 \ 626 \ 272 \ 727 = 135 \ 353 \ 535 \ 353.$$

M43

Which side of a regular triangle is divided into $n$ equal parts. Straight lines parallel to the sides are drawn through the division points. As a result, the triangle was broken into $n^2$ small triangles. Known as a “chain” is a sequence of triangles in which none appears twice and each subsequent one has a common side with the previous one. What is the maximum possible number of triangles in the chain?

Answer: $n^2 - n + 1$. To prove that they are often found on odnomas, it is enough to take one unexpected step: color the triangles in a checkerboard pattern, as was done on figure. The rest is quite simple.

In the entire triangle, the red triangles are $n$ larger than the yellow ones (in each horizontal row, the red ones are one larger), and in the chain the color must be black, so there can only be one red ones larger than the yellow ones.

One of the chains of the maximum possible length is shown at figure. (From what was said above, it is clear that in order for a chain to have length $n^2 - n + 1$, it is necessary and sufficient that it begins and ends in red triangles and passes through all yellow triangles without exception.)

⟦folio 30⟧

Prove that for every natural number $K$ there are an infinite number of natural numbers $T$ that do not contain zeros in decimal notation and such that $T$ and $KT$ have the same sum of digits.

Let there be $k$ digits in the number $K$ (in decimal notation). Then in the role of $T$ you can take any number 999...99, written $n$ by nines, where $n \geqslant k$; then both the sum of the digits $T$ and the sum of the digits $KT$ are equal to 9$n$ (in the number $KT = K(10^n-1)$, digits spaced $n$ digits apart add up to 9; for example, $743\ 552 \cdot 99\ 999\ 999 = 743\ 552 \cdot (10^8-1) =$
$= 74\ 355\ 200\ 000\ 000-743\ 552 = 74\ 355\ 199\ 256\ 448$;

We leave the almost obvious proof for the general case to the reader).

M45

Prove that from any 200 integers you can choose 100 whose sum is divisible by 100.

Try to generalize this problem: prove that from any $2n-1$ integers we can choose $n$ whose sum is divisible by $n$, where $n \geqslant 2$.

Lemma. If the statement of the problem is true for $n = a$ and for $n = b$, then it is also true for $n = ab$.

Note that the property “the sum $n$ of integers $x_1, \ldots, x_n$ is divisible by $n$” can also be formulated as follows: “the arithmetic mean $\frac{x_1 + \ldots + x_n}{n}$ is an integer.”

So, let arbitrary $2ab-1$ integers be given. Since the statement is true for $n = b$ and $2ab-1>2b-1$, from the given $2ab-1$ numbers we can choose $b$ whose sum is divisible by $b$. Then from the remaining ones (if there are at least $2b-1$) we choose another $b$ numbers that have this property, and so on.

Since
$$2ab-1 = (2a-1)b + (b-1),$$
then this operation can be repeated $2a-1$ times and obtain $2a-1$ sets of $b$ numbers, in each of which the arithmetic mean of $b$ numbers is an integer. Since the statement is true for $n = a$, from these $2a-1$ arithmetic means we can choose $a$, the sum of which is divisible by $a$. It is clear that then the $ab$ numbers that make up the corresponding $a$ sets of $b$ numbers each have the desired property: their sum is divisible by $ab$. The lemma is proven (this lemma, as well as the problem, was invented by Yu. I. Nonin).

So, in order to prove the statement of the problem for arbitrariness $n = a_1a_2\ldots a_k$, it is enough to prove it for individual factors $n = a_1$, $n = a_2$, ..., $n = a_k$ (and apply the lemma several times). Therefore, it is enough to learn how to prove this statement for prime factors of the number $n$. For example, to prove for $n = 100$, it is enough to prove two statements: “from any 3 integers one can choose 2 whose sum is divisible by 2” and “from any 9 integers one can choose 5 whose sum is divisible by 5.” The first is obvious, and the second can be proven with a not very long search. We give the reader the opportunity to verify this, and also try to come up with a proof that would be suitable immediately for any simple $n$. However, we will present such proof in the next issue of the journal.

⟦folio 31⟧

M46

How many sides can a convex polygon have that are equal to the largest diagonal?

Answer: two, one or none.

It is not difficult to construct examples for each of these cases. A polygon in which three or more sides are equal to the largest diagonal does not exist, since two sides equal to the largest diagonal must necessarily have a common vertex (Fig. 5), and three sides, each two of which have a common vertex, can only be in a triangle, and it has no diagonals.

M47

From the digits 1 and 2, five $n$-digit numbers were made so that each two numbers coincided in $m$ digits, but not all five numbers coincided in any one digit. Prove that $\frac{2}{5} \leq \frac{m}{n} \leq \frac{3}{5}$.

Let's write the numbers one below the other. Each digit (“column”) has 5 digits. Of these, you can make 10 (unordered) pairs. For all $n$ columns there will be 10 $n$ such pairs. Let's find out how many of them there are that consist of identical numbers, that is, pairs (1, 1) and (2, 2). There are either 4 or 6 such pairs in each column. Therefore, the total number of such pairs is not less than 4 $n$ and not more than 6 $n$. On the other hand, the number of such pairs is equal to 10 $m$, since when comparing any two numbers across all $n$ digits, according to the condition, the result is equal to $m$ such pairs, and all possible pairs of 5 numbers are 10.

So, $4n \leq 10m \leq 6n$, which is what needed to be proved (see Fig. 6).

M48

In an acute triangle $ABC$ bicsectrix $AD$, median $BM$ and altitude $CH$ intersect at one point. Prove that angle $BAC$ is greater than 45°.

It is not difficult to prove that for a given $\Rightarrow BAC = \alpha < \frac{\pi}{2}$ there is exactly one (up to subdivision) triangle $ABC$ in which the height is $CH$, bicsectrix $AD$ and median $BM$

⟦folio 32⟧

Diana $BM$ intersect at one point. Indeed, having distinguished the (arbitrary) segment $AC$ on one side of the angle $\Rightarrow A = \alpha$, dropping the perpendicular $CH$ to the other side of the angle and designating its point of intersection with the bisector of the angle $A$ through $O$, we will find the point $B$ of intersection of the second side of the angle and the line $OM$ (where $M$ is the midpoint of the segment $AC$) and thereby construct the required triangle $ABC$; it is obvious that given $\Rightarrow A$ and $AC$ it is defined in a unique way. Note that in this case the angle $B$ is acute (since the point $H$ - the base of the height - lies on the side $AB$).

Let us prove that if $\Rightarrow A < \frac{\pi}{4}$, then $\Rightarrow ACB > \frac{\pi}{2}$. Let us plot the segment $HB_1 = AH$ on the straight line $AB$. Then the bisector $B_1F$ of the angle $B_1$ of the isosceles triangle $AB_1C$ will pass through the point $O$. Since $\frac{AF}{FC} = \frac{AB_1}{B_1C} > 1$, the point $M$ lies between $A$ and $F$, so $B_1$ lies between $A$ and $B$ and $\Rightarrow BCA > \Rightarrow B_1CA > \frac{\pi}{2}$.

In this problem, you can get a more accurate result: find an exact estimate for the angle $\alpha$, provided that $\Rightarrow ACB = \gamma < \frac{\pi}{2}$. To do this, we express $\gamma$ as a function of $\alpha$. Let's draw $HE \parallel BM$ (E is the point on $AC$). Then (Fig.7)

$$\frac{EM}{MC} = \frac{HO}{OC} = \frac{AH}{AC} = \cos \alpha, \quad \frac{HB}{AH} = \frac{EM}{AE} = \frac{\cos \alpha}{1 - \cos \alpha}, \quad \frac{HB}{HC} = \frac{\cos^2 \alpha}{\sin \alpha (1 - \cos \alpha)},$$

$$\gamma = \gamma(\alpha) = \frac{\pi}{2} - \alpha + \arctg \frac{\cos^2 \alpha}{\sin \alpha (1 - \cos \alpha)}.$$

From here it is clear that the function $\gamma = \gamma(\alpha)$ on the segment $0 < \alpha < \frac{\pi}{2}$ monotonically decreases (the more $\alpha$, the greater the sin $\alpha$ and the less cos $\alpha$, and therefore the fraction under the arc sign is always smaller). Let us now find $\alpha$ for which $\gamma(\alpha) = \frac{\pi}{2}$. This property equation is: $0 < \alpha < \frac{\pi}{2}, \sin^2 \alpha (1 - \cos \alpha) = \cos^3 \alpha$, whence cos $\alpha = \frac{\sqrt{5} - 1}{2}$. So, if $\gamma < \frac{\pi}{2}$, then $\alpha > \alpha_0 = \arccos \frac{\sqrt{5} - 1}{2} \left( \alpha_0 > \frac{\pi}{4} \right)$, since $\frac{\sqrt{5} - 1}{2} < \frac{\sqrt{2}}{2}$; as you can see from the tables, the angle corresponding to $\alpha_0$ in degrees is approximately $51^\circ 50'$).

M49

The cards contain numbers from 11,111 to 99,999 inclusive. Then these cards are placed one whole at a time in random order. Prove that the resulting 444,445-digit number cannot be a power of two.

⟦folio 33⟧

It is easy to prove that this number is divisible by 11,111, resulting in the fact that the numbers $10^5A$ and $A$ for any integer $A$ give the same remainders when divided by 11,111, and the sum $11 111+11 112+\dots+99 998+99 999$ is divisible by 11,111. But if the number is divisible by 11,111, then it, of course, cannot be a power of two. (This immediately follows, for example, from the theorem on the uniqueness of factorization.)

Nearly more successful solutions to the problems were sent to us by E. Turkevich from Chernivtsi (he found a precise estimate for the angle $\alpha$ in problem M48, solved problem M46 and M49) and R. Akhmetshin from Osh (M42, M44, M47).

N. B. Vasiliev

In this issue we publish solutions to problems F45, F59—F65

Let's return once again to problem F45. She has a pretty simple and red solution.

F45

A spherical capacitor filled with a dielectric and charged to a certain potential difference is discharged through its dielectric. What will be the magnetic field of the discharge currents in the space between the spheres?

Since at any point of the dielectric all directions in the plane perpendicular to the radius are equal, then the vector $\vec{B}$ inductance of the magnetic field cannot have a component lying in this plane. Therefore, the vector $\vec{B}$ can only be directed along the radius. But all points of the insulator are equal. This means that the vectors $\vec{B}$ and the magnetic field lines either converge or exit from the center of the sphere. But the magnetic field lines must be closed. This means it is impossible, and $\vec{B} = 0$. The magnetic field of the capacitor discharge currents is zero.

F59

Which edge of the wire cube should be removed so that the resistance between points $A$ and $B$ (Fig. 8) changes as much as possible? The resistances of all edges of the cube are the same.

Number all the edges of the cube and its vertices. The current flowing along edge 1 branches at vertex 1 into two flows, which then follow along edges 7 and 8.

Similarly, the current flowing along edge 2 branches into two equal flows at vertex 2 and so on. Through edge 4 the current flows through edges 7 and 12... Edge 4 is equivalent to edges 5 and 6. This means that through edges 1, 2, 3, 4, 5 and 6 the current flows twice as much as through edges 7, 8, 9, 10, 11 and 12. It is clear that the resistance of the circuit will change the most if the conductor carrying the most current is removed from the circuit. From the wire cube you need to remove one of the edges 1, 2, 3, 4, 5 or 6.

Make sure of this by calculating the resistance of the corresponding circuits.

⟦folio 34⟧

Some tips. The resistance of the cube between vertices A and B is easy to calculate. To do this, you just need to note that, due to symmetry, vertices 1, 2 and 3 have the same potential. Therefore, the resistance of the circuit will not change if they are connected together. Of course, vertices 4, 5 and 6 also have the same potential and can also be connected. After this, you will receive a chain (Fig. 9), the resistance of which is very easy to calculate. If we take the resistance of one edge equal to 1 ohm, then the resistance of the chain will be equal to 5/6 ohms. It is not difficult to find the resistance of the circuit when one of the edges 1, 2, 3, 4, 5 or 6 is removed. Here you can also find equivalent points, connecting which you get a circuit of series and parallel connections. But before finding the resistance of the circuit after removing one of the ribs 7, 8, 9, 10, 11 or 12, read the article by A. R. Zilberman “Transformation of Electric Circuits” in «Kvant» No. 3 for 1971. You will need the method explained in this article.

F60

An image of a candle is visible in a flat mirror. What will happen to it if a plane-parallel glass plate is placed between the mirror and the candle?

Having drawn the course of several rays, it is not difficult to verify that after placing a plane-parallel glass plate between the candle and the mirror, the image of the candle will approach the mirror (Fig. 10). Blue lines show the path of the ray without a plate, red lines - with a plate.

F61

A cube sliding without friction on a smooth horizontal floor hits a vertical glass with one of its side faces. The coefficient of friction between the cube and the glass is k. At what angle to the glass will the cube bounce if before colliding with it it was moving in a direction making an angle α with the glass?

When the cube is removed from the glass, two forces act: the force N of the normal reaction of the stack and the friction force Ftr (Fig. 11). Let us decompose the speed of the cube before and after colliding with the stack into components parallel to these forces. The velocities v1 = v sinα and u1 are perpendicular to the glass, and the velocities v2 = v cosα and u2 are parallel to it. In the direction perpendicular to the glass, between the cube and the glass, as usual, an absolutely elastic impact occurs, as a result of which the component of the speed of the cube, perpendicular to the glass, changes to the opposite: u1 = −v1 = −v sinα. It means:

Fig. 10.
Fig. 11.

⟦folio 35⟧

It means that the component of the cube's momentum perpendicular to the wall changes to $2mv\sin\alpha$ ($|u_1-v_1| = 2v\sin\alpha, m - \text{masca кубика})$.

If the time of keeping the cube with the wall is denoted by $\tau$, and the average value of the reaction force of the wall is equal to $N_{cp}$, then, according to Newton’s second law, the change in the component of the cube’s momentum perpendicular to the wall is equal to the force impulse $N_{cp}$, that is

$$2mv\sin\alpha = N_{cp}\tau.$$

If the friction force did not act on the cube, then the component of the cube’s momentum parallel to the wall would not change and the cube would bounce off the wall at the same angle $\alpha$ at which it moved towards it before the impact. However, due to the action of the friction force in our case, the component $v_2$ of the speed of the cube also changes. Let us first assume that the average friction force $F_{\tau p,cp} = N_{cp}k$ acting on the cube is such that during the interaction of the cube with the wall, the component of the cube’s velocity parallel to the wall does not have time to decrease to zero. In this case, according to Newton's second law,

$$mu_2 - mv_2 = -F_{\tau p,cp}\tau,$$ or $mu_2 = mv\cos\alpha - N_{cp}k\tau$.

But $N_{cp}\tau = 2mv\sin\alpha$, therefore

$$mu_2 = mv\cos\alpha - 2kmv\sin\alpha,$$

or

$$u_2 = v(\cos\alpha - 2k\sin\alpha).$$

Now let's find the angle at which the cube will bounce:

$$tg\beta = \frac{|u_1|}{u_2} = \frac{v\sin\alpha}{v(\cos\alpha - 2k\sin\alpha)} = \frac{tg\alpha}{1 - 2ktg\alpha}.$$

This answer was received by V. Goncharenko from Maikol, Krasnoarsk region, M. Gilburg from Borislav, Lviv region, N. Smirnov from Gorky, V. Zakass from Usolye-Sibirsky, Irkutsk region, I. Gritsik from David-Gorodok, Brest region, A. Senyavin from Moscow, A. Anishchenko from Sarapula, UASSR, and Kudek from Rzhev.

However, this is not a complete solution to the problem. This was noticed by readers A. Vlasov from Valdai, B. Shparberg from Mogilev on the Dnieper, A. Zhukov from Kirovsk, Donetsk region and I. Berman from Chernivtsi.

Obviously, our solution is valid if $u_2 > 0$, that is, $2ktg\alpha < 1$.

At $tg\alpha \rightarrow \frac{1}{2k}$ $tg\beta \rightarrow \infty$ and $\beta \rightarrow \frac{\pi}{2}$. What does this mean?

If $tg\alpha = \frac{1}{2k}$, then $u_2 = v(\cos\alpha - 2k\sin\alpha) = v\left(\cos\alpha - \frac{1}{tg\alpha}\sin\alpha\right) = 0$.

During the interaction of the cube with the wall, the component of the cube's velocity parallel to the wall becomes zero. But how will a collision with a wall occur if $tg\alpha > \frac{1}{2k}$?

In this case, the cube will slide relative to the wall not during the entire impact, but until the component of its velocity parallel to the wall becomes zero. Together with it, the friction force acting on the cube will also go to zero, and the cube will bounce off at an angle $90^\circ$ to the wall.

So,

$$\beta = \begin{cases} \arctg\left(\frac{tg\alpha}{1 - 2ktg\alpha}\right) & \text{при } tg\alpha < \frac{1}{2k}, \\ \frac{\pi}{2} & \text{при } tg\alpha \geq \frac{1}{2k}. \end{cases}$$

⟦folio 36⟧

A thin, non-stretchable rope consists of two parts. The mass per unit length of one of the parts is $\rho_1$, and the other is $\rho_2$. The rope encloses a very light hoop of radius $R$, the mass of which is negligible compared to the mass of the rope enclosing it, the ends are attached to the floor (Fig. 12). A piece of rope with mass per unit length $\rho_1$ rolls with a speed $v_1$. At what speed will the hoop roll along the second section of the rope?

As the hoop moves from one section of the rope to another, the potential energy of the rope changes. Indeed, when the hoop moves along a section of rope with linear density $\rho_1$, the potential energy of the rope bulb is equal to $m_1 g R = \rho_1 2 \pi R g R = 2 \pi \rho_1 R^2 g$ (the center of mass of the bulb is at its center). When the hoop moves along a section of the rope with linear density $\rho_2$, it is equal to $m_2 g R = 2 \pi \rho_2 R^2 g$. The correspondence changes and the kinetic energy of the rope flask. Since there are no losses, we can use the law of conservation of energy.

However, for this we need to know the kinetic energy of a flask of mass $m$ moving without slipping along the plane with a speed $v$. You can use the result obtained in the article by A.K. Kikon, Rotational motion of bodies》（Kvant No. 1, 1971):

$$K = \frac{mv^2}{2} + \frac{I \omega^2}{2} = \frac{mv^2}{2} + \frac{mR^2 \omega^2}{2} = \frac{mv^2}{2} + \frac{mv^2}{2} = mv^2.$$

But we will get this formula using a simple trick.

A flask moving without piercing at any moment of time rotates around the instantaneous center of rotation - the point of contact with the plane (Fig. 13). Angular speed of rotation of the bulb $\omega = \frac{v}{R}$. This means that the speed of the point $A$ bulb is perpendicular to the segment $OA$ and is equal to $OA \cdot \omega$. From $\triangle OAD$ $OA = 2R \cos \alpha$. Therefore $v_A = 2R \cos \alpha = 2v \cos \alpha$. Similarly, the speed of point $B$, diametrically opposite to point $A$, is $v_B = 2v \cos (90^\circ - \alpha) = 2v \sin \alpha$. Kinetic energy of small areas with masses $\Delta m$ near points $A$ and $B$

$$K_{A+B} = \frac{\Delta mv_A^2}{2} + \frac{\Delta mv_B^2}{2} = \frac{1}{2} \Delta m (4v^2 \cos^2 \alpha + 4v^2 \sin^2 \alpha) = 2\Delta mv^2.$$

$K_{A+B}$ is independent of $\alpha$. This means that any other pair of diametrically opposite points on the bulb has exactly the same energy. Therefore, the kinetic energy of the entire flask is $mv^2$. Let us now write the law of conservation of energy:

$$m_1 v_1^2 + m_1 g R = m_2 v_2^2 + m_2 g R;$$

from here

$$v_2 = \sqrt{\frac{m_1}{m_2} v_1^2 + g R \left(\frac{m_1}{m_2} - 1\right)} = \sqrt{\frac{\rho_1}{\rho_2} v_1^2 + g R \left(\frac{\rho_1}{\rho_2} - 1\right)}.$$

⟦folio 37⟧

Now let's see what we got. If $\rho_1 > \rho_2$, then $\frac{\rho_1}{\rho_2} - 1 > 0$ and under the root there is a positive number for any value $v_1$, even for $v_1 = 0$. The answer at $v_1 = 0$ has the following meaning: if the hoop stands as shown in figure 14, and for random reasons begins to move to the right at an infinitesimal speed, then when the red rope is unwound from it and wound up, it will have a speed $v_2 = \sqrt{gR\left(\frac{\rho_1}{\rho_2} - 1\right)}$.

If $\frac{\rho_1}{\rho_2} < 1$, then at $v_1^2 < gR\left(\frac{\rho_1}{\rho_2} - 1\right)\frac{\rho_2}{\rho_1}$ the radical expression becomes negative. This means that at this speed the hoop will not be able to move to a rope with a linear density of $\rho_2$. He will reel in some of the heavier rope (Fig. 15), leave and begin to move in the opposite direction.

The correct solution was sent by V. Yakir from Chisinau, A. Vlasov from Valdya, Novgorod region, I. Berman from Chernivtsi, Ukrainian SSR, B. Shparbere from Mogilev, BSSR, A. Anishchenko from Sarapul, UASSR, E. Gubarev from Moscow.

F63

The man, in order not to be on a sea-buckthorn hill, runs away from it. Why is this appropriate?

There are two forces acting on a person on a slide: the force of gravity $\vec{F}_T = mg$ and the force $\vec{F}_p$, equal to the sum of the friction force $\vec{F}_{tp}$ and the force $\vec{N}$ - the normal reaction of the slide (Fig. 16, a).

Since the moment of the gravitational force relative to the person’s center of mass is zero, the person will maintain balance and not “turn over” only if the force $\vec{F}_p$ passes through his center of mass.

If the friction of shoe soles on a hill is great and a person is standing on a hill, then the sum of the forces acting on the person is zero. That is, the force $\vec{F}_p$ is directed vertically and is equal to the gravitational force.

It's a different matter if there is little training. Let us first examine the limiting case: $\vec{F}_{tp} = 0$. Then the person will not fall if he is perpendicular to the slide (Fig. 16, b). Only in this case the force $\vec{N}$ of the slide reaction passes through the person’s center of mass. But the equilibrium $\vec{R}$ of forces $\vec{N}$ and $mg$ will be equal to zero. It is directed parallel to the inclined plane and is equal to $mg\sin\alpha$. Therefore, the person must descend with acceleration $a = g\sin\alpha$.

If the friction factor is small, but not equal to zero, then the person’s acceleration should be less. Having written down Newton's II law, we find that it is equal to $a = g\sin\alpha - \frac{F_{tp}}{m}$.

⟦folio 38⟧

Fig. 16.

So, a person can maintain balance if he is restrained by acceleration $a = g \sin \alpha - \frac{F_{\text{тр}}}{m}$, making a certain angle with the slide, determined by the magnitude of the friction force. Essentially, in this case, the person, just as during normal walking, falls on his forward leg (Fig. 16, θ). Equilibrium is maintained, as it were, “on average” for a time much longer than the time of one step.

F64

Four experiments are carried out with a wooden ball and a tall vessel with water: in the first experiment they are weighed when the ball floats in the vessel (Fig. 17, a), in the second experiment, when weighing, the ball is tied to the bottom of the vessel (Fig. 17, b), in the third experiment it is held in the vessel using a thin rod (Fig. 17, θ) and, finally, in the fourth experiment the ball floats up during weighing (Fig. 17, f). In which experiment is the mass of the weight balancing the container with the ball greater?

Fig. 17.

⟦folio 39⟧

In the first and second experiments, the answer is very clear: the mass of the weight should be equal to the mass of the vessel with water and the ball. In the second experiment, the water level is higher than in the first, and, therefore, the force of water pressure on the bottom of the vessel is greater, but the force acting on the bottom from the side of the ball through the thread is upward.

In the third experiment, in addition to the force of gravity acting on the vessel, water and ball, the force acting on the system from the rod is also added. This means that the mass of the weight should be greater than in the first and second experiments.

If a ball immersed in water begins to float, then its speed increases until the resistance force (it depends on the speed) becomes equal to the difference between the Archimedean buoyancy force and the force of gravity. After this, the ball will move evenly. Let's consider the beginning of the last case. Since the ball moves uniformly, the forces acting on it are balanced, that is, the force $F$ acting on the ball from the side of water is directed upward and is equal in magnitude to the forces of gravity and $mg$. According to Newton's III law, this means that the force acting on the water from the side of the ball is $F$, equal to $mg$. Thus, a force will act on the scales that is equal in magnitude to the sum of the forces of gravity acting on the ball, the vessel and the water. That is, the mass of the weight should be the same as in the first and second experiments.

Let us now consider the case when the ball floats up at an accelerated rate. Moreover, at the moment when the ball just begins to float up and there is no resistance force acting on it (proportional at low speeds of the ball), the container with the ball weighs the same as in the third experiment. Indeed, according to Newton’s III law, only the force $F_0$, equal to the buoyant Archimedean force acting on the ball from the water, acts on the water from the side of the ball in this case, both in the third and fourth experiments. It is equal to $\rho gV$, where $V$ is the volume of the ball and $\rho$ is the density of water. This means that in both cases the force of pressure on the scale pan is equal to the sum of the gravitational forces acting on the water, the vessel, and the force $F_0$.

When the acceleration of the ball in the fourth experiment decreases due to the resistance of the water, the force acting on the water from the side of the ball also decreases: in this case, the force is equal in magnitude to the difference between the Archimedean force and the resistance force.

We received many letters with a solution to this problem, but only two readers fully understood it: N. Fedin from Omsk and N. Smirnov from Gorky.

F65

The plates of a flat capacitor are charged to potentials $+\varphi$ and -$\varphi$ relative to the ground. The capacitance of the capacitor formed by the plates is $C$, and the capacitance of the capacitors that form each of the plates with the ground is $C_1$. How many times will the field voltage change between the plates if one of them is grounded?

Let's draw an equivalent circuit diagram (Fig. 18). Since the potential difference between the plates of the capacitor $C$ is equal to $2\varphi$, then the charge of each of the plates is equal

$$q = C \cdot 2\varphi = 2C\varphi.$$

In this case, on the plates of capacitors with capacity $C_1$ there are charges $q_1 = C_1\varphi$. This means that the charge of the plates $II$ is equal to

$$Q = q + q_1 = (2C + C_1)\varphi.$$
