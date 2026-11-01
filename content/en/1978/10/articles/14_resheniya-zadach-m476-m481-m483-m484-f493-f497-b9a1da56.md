---
id: 1978-10-resheniya-zadach-m476-m481-m483-m484-f493-f497-b9a1da56
issue: kvant_1978_10
year: 1978
number: "10"
title: Solutions to problems M476—M481, M483, M484; F493—F497
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 42
page_last: 58
page_labels: 40, 41, 42, 44, 45, 46, 47, 48, 49, 50, 51, 52, 53, 55, 56
tag: 3TCO
lang: en
source: kvant_digital
extraction: vision
content_sha256: 003f58fafbc7509509be7f41a4d557d6f498fa8b889a8f7bb1edbab5b87bfdb3
prompt_sha256: draft-1
translated_from: content/ru/1978/10/articles/14_resheniya-zadach-m476-m481-m483-m484-f493-f497-b9a1da56.md
source_content_sha256: 455199d6ea1431677282b64b233b471e3857fcf2a60a2d57ed42459a2d17fc46
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 40⟧

Problem solutions
M476—M481, M483, M484; F493—F497

M476. a) Prove that if the vertices of a convex n-уzelbnika lie in the nodes of the glued paper, and there are no other nodes inside or on its sides, then n≤4.
b) Let the space be divided primarily by families of parallel planes into identical cubes. The tops of the cups are called nodes. Prove that if all n vertices of a convex polyhedron lie in nodes, and there are no other nodes on its edges, boundary or inside the polyhedron, then n≤8.

Fig. 1.

M477. Given a polynomial P(x) with integer coefficients such that for each named x the inequality P(x)>x holds. Let's define the sequence {b_n} as follows: b_1=1, b_{k+1}=P(b_k) for k≥1. It is known that for any named d, a member of the sequence {b_n} dividing by d was named. Prove that P(x)=x+1.

Note first that if the integers x and y give the same remainder when divided by a natural number d, then P(x) and P(y) also give the same remainder when divided by d. This follows from the fact that when x and y are substituted into a polynomial P, the corresponding terms will have the same remainder when divided by d. (In fact, x^k-y^k for any natural k is divisible by x-y, since x^k-y^k=(x-y)(x^{k-1}+x^{k-2}y+x^{k-3}y^2+...+y^{k-1}); therefore, if x-y is divisible by d, then x^k-y^k is too.)

Let P(x) be different from x+1. Since the sequence {b_n} is made up of natural numbers, and P(x)>x for each named x, for some natural number n there will be b_{n+1}>b_n+1. Let's take the minimum such n. We have: b_1=1, b_2=2,...,b_n=n, b_{n+1}>n+1. Let's put d=b_{n+1}-1. The remainders from the division of the terms of the sequence on d will initially be equal to 1, 2,...,n, and then, due to the replacement and choice of d, they will periodically repeat: b_{n+1} gives remainder 1, b_{n+2} gives 2,...,b_{2n} gives n, b_{2n+1} again 1, etc. None of the terms of the sequence, subject to the conditions of the problem, will divide on d. Therefore P(x)=x+1.

⟦folio 41⟧

M478. In the volleyball tournament, each two teams played one match.
a) Prove that if for any two teams there is a triangle that wins over these two, then the number of teams is at least seven.
b) Prove that if for any three teams there is a triangle that wins against these three, then the number of teams is at least seven.
6) Construct an example of a seven-team tournament.
b) Prove that if for any three teams there is a triangle that wins against these three, then the number of teams is at least seven.

Fig. 2.

M479. Are there a) six, 6) 1000 maximum office numbers such that for any two a and b of them, the sum a + b is divisible by the difference a - b?

M480. The sequence $c_n$ is constructed according to the following rule: $c_1 = 2$, $c_{n+1} = [3c_n/2]$ for $n \geq 1^*$). Prove that there are infinitely many cyclic numbers in this sequence.

*) Here [x] is the integer part of the number x.

a) Considering an arbitrary team $A$ together with one of the teams $B$, which $A$ lost, we see that $B$ must lose to at least one team from among those that $A$ won. In other words, all teams that won against $A$ lost at least one match when playing against each other. This means that the number of teams that won against $A$ is at least three. But among all our teams there must be a team that won at least as many matches as it lost (the total number of victories). This team lost at least three times and won at least three times, which is possible in the case when the number of the team is at least seven.

6) Let us associate each of the teams with a vertex of a convex heptagon. The victory of team $A$ over team $B$ is denoted by an arrow drawn from point $A$ to point $B$. Our figure 2 shows the possibility of satisfying the conditions of the problem.

b) Let team $A$ win at least as many matches as they lost. By checking that the conditions of the problem are satisfied for all possible triangles composed of team $A$ and two teams that won against it, we see that the team that won $A$ form a set that satisfies the conditions of problem a). Therefore, there are at least seven of them. Team $A$ won at least seven matches and lost at least seven; Therefore, in total, at least 15 teams participated in the tournament.

In a similar way, it is easy to prove that if (for a given $m$) for any $m$ there is a team that has not lost to them all, then the number of the team is at least $2^{m+1} - 1 = a_m$ (the sequence $a_1 = 3$, $a_2 = 7$, $a_3 = 15$, ... satisfies the conditions of problem a). Therefore, there are at least seven of them. Team $A$ won at least seven matches and lost at least seven; Therefore, in total, at least 15 teams participated in the tournament.

In a similar way, it is easy to prove that if (for a given $m$) for any $m$ there is a team that has not lost to them all, then the number of the team is at least $2^{m+1} - 1 = a_m$ (the sequence $a_1 = 3$, $a_2 = 7$, $a_3 = 15$, ... satisfies the conditions of problem a). Therefore, there are at least seven of them. Team $A$ won at least seven matches and lost at least seven; Therefore, in total, at least 15 teams participated in the tournament.

Point a) is a consequence of point 6) in this successful form: the sequence $e_n$ starting from some place is periodic, that is, that $e_{n+T} = e_n$ for some natural number $T$ for all $n$ starting from some $N$. This means that for any $n \geq N$ the numbers $c_n$ and $c_{n+T}$ have the same parity. It follows that

$$\frac{3}{2} c_n - \left[ \frac{3}{2} c_n \right] = \frac{3}{2} c_{n+T} - \left[ \frac{3}{2} c_{n+T} \right],$$

⟦folio 42⟧

sat down and infinitely many non-cem-
numbers;
b) sequentially $e_n = (-1)^{c_n}$ non-periodic;
c) there is a number $\gamma$,
What
$$c_n = \left[ \left( \frac{3}{2} \right)^n \gamma \right] + 1.$$

and therefore $c_{n+1} - c_n = \frac{3}{2} (c_{n+1} - c_n)$. But it's clear
that there is no infinite sequence of numbers
numbers in which each number is half a mora times larger
previous one. (In fact, if some term consistently has the form $2^k \cdot r$, where $r$ is an odd number, then $k + 1$ steps after it we should encounter
the term $\frac{3^k + 1}{2}$ is not an integer.) A contradiction.

c) It is easy to check that for any $n$
$$c_{n+1} \leq \frac{3}{2} c_n, c_{n+1} - 1 \geq \frac{3}{2} (c_n - 1).$$

Posetom
$$\frac{c_n - 1}{(3/2)^n} \leq \frac{c_{n+1} - 1}{(3/2)^{n+1}} < \frac{c_{n+1}}{(3/2)^{n+1}} \leq \frac{c_n}{(3/2)^n}.$$

The length of the segment $\left[ \frac{c_n - 1}{(3/2)^n}; \frac{c_n}{(3/2)^n} \right]$ is equal to $(2/3)^n$, - it
tends to zero as $n \to \infty$, so all these segments have a single common point. Let's denote it by $\gamma$.

From the definition of $\gamma$ it follows that $(3/2)^n \gamma \in [c_n - 1; c_n]$.
Moreover, the equality $(3/2)^N \gamma = c_N$ is impossible for any $N$: it would follow from it that $(3/2)^n \gamma = c_n$ for any
integer $n \geq N$, or $c_{n+1} = \frac{3}{2} c_n$ for any integer $n \geq N$,

which contradicts what was said above. This means $[(3/2)^n \gamma] = c_n - 1$, which is what needed to be proved.

In solving this problem, we used the important principle of contractible segments, according to which the sequence of plane segments
$$[a_1; b_1] \supset [a_2; b_2] \supset [a_3; b_3] \supset \dots,$$

the length $|a_n - b_n|$ of which tends to 0, we always have a unique real number; this principle (or any equivalent) is taken as an axiom. It clearly expresses the very special property of the “density” of the number line, the absence of “holes” in it. This principle can be proven based on Weierstrass's theorem on the limit of a monotonic bounded sequence.

In our problem, it is easy to indicate the right ends of the $n$-th segment for the first few $n$ and thereby approximately calculate $\gamma$; for example, with two decimal places: $\gamma \approx 0,81$.

S. Konyatsin

**M481. In the sequence of natural numbers $a_1, a_2, a_3, \dots$, each term $a_{k+1}$ is equal to the sum of the squares of the number $b$ in the decimal notation of the number $a_k (k \geq 1)$. Let us prove that for any $a_1$ the number 1 or the number 89 will end up in this sequence.**

It is clear that the sum of the squares of the digits of the number $x$ - let's denote it $f(x)$ - for a sufficiently large $x$ is significantly less than the number $x$ itself. So, if $x$ is a four-digit number, that is, $10^3 \leq x < 10^4$, then $f(x) \leq 4.9^2 = 364 < 10^3 \leq x$. In general, if $10^{n-1} \leq x < 10^n$ and $n > 3$, then $f(x) \leq 81n < 10^{n-1}$. (The last inequality is easy to prove by induction: $81n < 10^{n-1} \Rightarrow 81 (n + 1) = 81n + 81 < 10^{n-1} + 81 < 10^n$.) Let us prove that for any three-digit $x$ there is also $f(x) < x$. If the first digit of the number $x$ is equal to $p > 1$, then $f(x) < p^2 + 2 \cdot 81 = 162 + p^2 < 100p$ (this is easy to verify for each $p = 2, 3, 4, \dots, 9$). If the first digit $x$ is 1 and the second $q$, then $f(x) \leq 1 + q^2 + 81 < 100 + 10q \leq x$ for any $q = 1, 2, \dots, 9$.

⟦folio none⟧

Thus, for any natural number $a_1, a_2, a_3, \dots$, where $a_{n+1} = f(a_n)$, (*)

encounter a number not exceeding 99. For two-digit and single-digit numbers, one comes to study the corresponding sequences (*) by brute force. The calculations are aided by a table with the sum $i^2 + j^2$ at the intersection of the $i$th row and the $j$th column - this table is placed above. For any $x \leq 99$ there will be $f(x) \leq 162$; thus, the set $X = \{1, 2, \dots, 162\}$ is mapped into itself: $f(x) \leq 162$ for all $x \leq 162$.

How the mapping $f$ to the set $X$ is arranged is shown in figure 3: from each number $x$ there is an arrow to the number $f(x)$. From

Fig. 3.

⟦folio 44⟧

figure 3 it is clear that for any $a_1$ the sequence (*) will either enter the “fixed point” 1: for some $N$ the result will be $a_N = 1$ (and then $a_{N+1} = a_{N+2} = \dots$), or will fall into the “cycle” (period) ... $\rightarrow$ $89 \rightarrow$ $145 \rightarrow$ $42 \rightarrow$ $20 \rightarrow$ $4 \rightarrow$ $16 \rightarrow$ $37 \rightarrow$ $58 \rightarrow$ $89 \rightarrow \dots$ (Thus, the number 89 in the conditions could be replaced by any of the seven other numbers of this cycle; 89 is notable only because it is adjacent to the most powerful “branch” on figure.) This implies the statement of problem M481.

For a similar problem, in which instead of the sum of squares of digits one is simply concerned with the sum of the digits, a simpler result is obtained: after several applications of the map “$x \rightarrow$ the sum of the digits $x$”, the numbers $a_1$ that are multiples of nine will yield 9, and any number $a_1$ that is not a multiple of nine will yield the remainder when dividing $a_1$ by 9. Thus, there are nine fixed points here 1, 2, ..., 9, and by $a_1$ we can immediately tell which one we will fall into.

Of course, we can take together $f$ other functions, say, the sum of cubes, or four stems of digits, etc. For these mappings it can also be proven that $f(x) < x$ for a sufficiently large $x$, which means that sequences of the form (*) sooner or later enter one of a finite number of “cycles” - in particular, perhaps, they end up in a “cycle of length 1”, that is, in a fixed point. Although fans of digital discs may get satisfaction from stumbling upon such fixed points as $1^3 + 5^3 + 3^3 = 153$ (V. Panfilov) or $1^4 + 6^4 + 3^4 + 4^4 = 1634$ (G. Gurevich), searching for all the cycles here is quite a tedious task, even if you have a computer at hand.

**M483**). a) Prove that the ratio of the square of the radius of the inscribed circle of a right triangle to the sum of the squares of the length of medians drawn from acute angles does not exceed 1/20. b) Find the maximum value that this ratio can take.

Let $a$ and $b$ be the lengths of the legs of the triangle, $c = \sqrt{a^2 + b^2}$ the length of the hypotenuse, $r$ the radius of the inscribed circle. Since the sum of the squares of the length of the medians, which is mentioned in the conditions, is equal to

$$\left(\frac{a}{2}\right)^2 + b^2 + \left(\frac{b}{2}\right)^2 + a^2 = \frac{5}{4} (a^2 + b^2) = \frac{5}{4} c^2,$$

The problem requires estimating the ratio $4r^2/5c^2$. Note that

$$r = \frac{ab}{a+b+c} = \frac{ab}{a+b+\sqrt{a^2+b^2}} < \frac{a^2+b^2}{2\sqrt{a^2+b^2}} = \frac{c}{4},$$

since $ab \leq (a^2+b^2)/2$ and $a+b > \sqrt{a^2+b^2}$. From here we get result a):

$$\frac{4r^2}{5c^2} < \frac{4}{5\cdot 4^2} = \frac{1}{20}.$$

A more precise estimate (it uses the inequalities $a + b \geq 2\sqrt{ab}$ and $c^2 = a^2 + b^2 \geq 2ab$, which become equalities for $a = b$):

$$\frac{r^2}{c^2} = \frac{a^2b^2}{(a+b+\sqrt{a^2+b^2})^2c^2} \leq \frac{ab}{2(2\sqrt{ab}+\sqrt{2ab})^2} = \frac{1}{4(1+\sqrt{2})^2},$$

where we get result 6):

$$\frac{4r^2}{5c^2} \leq \frac{1}{5(3+2\sqrt{2})} = \frac{3-2\sqrt{2}}{5}$$

(at $a = b$ we obtain equality, that is, the estimate is the best).

⟦folio 45⟧

This problem allows other solutions using geometric messages. Let's give two solutions.

1°. If we continue the diagonal of the square by figure 4 until it intersects the hypotenuse, we obtain the bissertis of a right angle; let's denote its length by $l$. Therefore $r + r\sqrt{2} \leq l$. But the bissertis in any triangle is located between the height $h$ and the median, the length of which in a right triangle with a hypotenuse of length $c$ is $c/2$. Hence $r(1 + \sqrt{2}) \leq c/2$, from where we get the result.

2°. Let us fix a segment $AB$ of length $c$. Let $C$ be any point of a semicircle with diameter $[AB]$ (then $ACB = 90^\circ$) and $M$ be the incircle center of triangle $ABC$. By searching for $AMB = 135^\circ$, points $M$ lie on the arc at $90^\circ$ with ends $A$, $B$, and therefore the distance from $M$ to straight line $AB$ (radius $r$ of the inscribed circle) will be greatest when $M$ falls in the middle of this arc, i.e. when the right triangle $ABC$ is equilateral.

N. Vasiliev

M484. With kikh p sucestium vipukly p-uezdnik, which can be cut into several regular polygons (not necessarily identical)?

Fig. 4.

We will now prove that for $3 \leq n \leq 12$ also n-districts are sucestium, but for $n > 12$ they are not.

Let us denote the split $n$-gon by $M$. A right polygon participating in the tiling $M$ is called good if at least one of its vertices is a vertex of the polygon $M$.

(Further, when speaking about tiling polygons, by the word polygon we will always mean a regular polygon.)

Our proof will consist of several points.

1°. Note that at the vertex of the polygon $M$ no more than two regular polygons can converge, and these are either two triangles, or a triangle and a square, or a triangle and a rectangle.

This statement immediately follows from the fact that the magnitude of each angle $M$ is less than $180^\circ$, and the magnitude of the angle of an arbitrary regular polygon is not less than $60^\circ$, and, in addition, only the following combinations are possible: $60^\circ + 60^\circ$, $60^\circ + 90^\circ$, $60^\circ + 108^\circ$.

From our remark it follows that if a regular $k$-gon $c$ $k \geq 6$ is adjacent to the vertex of a polygon $M$, then its sides go along the sides $M$.

2°. Let us prove that a regular $k$-gon for $k > 6$ cannot be good. Let's assume the opposite. Then, if it is good and if all its vertices coincide with the vertices of $M$, then it coincides with $M$, and we assume that $M$ is divided into at least two polygons. If he finds two neighboring vertices $A$ and $B$ of a k-gon, one of which ($A$) is a vertex $M$, and the other ($B$) is not (Fig. 5), then at the vertex $B$ an angle is drawn that is smaller in magnitude than $60^\circ$ (by figure 5 it is shaded), which cannot be filled with the corners of regular polygons. Contradiction.

3°. Since a regular hexagon can be divided into regular triangles, we will assume that hexagons are not involved in the division.

Under this condition, we get that triangles, squares and rectangles can be good.

4°. Let us prove that if in the tiling $M$ there is a good rectangle (we denote it by the letter $П$) it cannot be an interior point of the side of either the polygon $M$ or any polygon of the tiling (otherwise at this point

⟦folio 46⟧

a “bad” angle would be formed, not filled by regular polygons - see figure 6, a, 6). Therefore, each vertex $P$ is either a vertex $M$, or lies strictly inside $M$ and is a common vertex of some other polygons of the partition.

Let us assume that there are two neighboring vertices $P$, one of which $(A)$ is the vertex $M$, and the other $(B)$ lies strictly inside $M$. Let us show that this cannot be. In fact, since $B$ is a common vertex of polygons, one of which is a pentagon, we need to fill the angle at $360^\circ - 108^\circ = 252^\circ$ with regular polygons. It is not difficult to say that this angle cannot be filled with four (or more) polygons: four triangles are not enough, but three triangles and one square are already too many $(4.60^\circ = 240^\circ < 252^\circ; 3.60^\circ + 90^\circ = 270^\circ > 252^\circ)$. This means that we can try to fill the angle at $252^\circ$ with two or three tiling polygons.

If there are three polygons, then one of them is necessarily a triangle $(3.90^\circ = 270^\circ > 252^\circ)$; so in this case there is an angle of $252^\circ - 60^\circ = 192^\circ$ left to fill with two polygons. Let these be some $k$- and $m$-gons. Then

$$180^\circ \left(1 - \frac{2}{k}\right) + 180^\circ \left(1 - \frac{2}{m}\right) = 192^\circ,$$

$$\frac{1}{k} + \frac{1}{m} = \frac{7}{15},$$

and if $k \leq m$, then $\frac{2}{k} \geq \frac{7}{15}$, hence $k \leq \frac{30}{7} < 5$ (and $k \geq 3$).

For $k = 4$ we get $m = \frac{60}{13}$ - not an integer; therefore, the square cannot participate in filling the angle of magnitude $192^\circ$. For the same reason, the triangle cannot participate in its filling: for $k = 3$ we get $m = \frac{15}{2}$. This means that the angle at $192^\circ$ is “bad”, and thus the angle at $252^\circ$ cannot be filled in triangles.

If there are two polygons, then

$$180^\circ \left(1 - \frac{2}{k}\right) + 180^\circ \left(1 - \frac{2}{m}\right) = 252^\circ (k \leq m),$$

where

$$\frac{1}{k} + \frac{1}{m} = \frac{3}{10}.$$

See for yourself that for the purposes of the number $k, m, k \leq m$ this equation has only the following solutions: $k = 5, m = 10$ and $k = 4, m = 20$. Let us show that none of them is suitable. Indeed, at the vertex $B$, neither a pentagon, nor a decagon, nor a decagon can be applied to the side $[AB]$ of a pentagon $P$ (they have “bad” external angles - $72^\circ, 36^\circ$ and $18^\circ$, respectively); This means that at vertex $B$ a square must be applied to $[AB]$. It is easy to understand that then all polygons adjacent to $[AB]$ must be squares (Fig. 7), which is impossible, since the vertex of the “free” angle at vertex $A$ is less than $72^\circ < 90^\circ$.

This means that a good pentagon cannot have a vertex inside $M$. This proves Statement 4: if a pentagon participating in the tiling $M$ is good, then all its vertices are vertices $M$.

$5^\circ$ It is easy to understand that polygons cannot apply partitions to state sides (beginning at the common vertex of these polygons, which, according to what has been proven, is also the vertex in the angle $M$, at least three polygons would converge, one of which is a pentagon, and the sum of the angles

⟦folio 47⟧

Fig. 9.

Fig. 10.

Fig. 11.

Fig. 12.

would be no less than 108° + 2·60° > 180°). Thus, tiling polygons can only be applied to non-adjacent sides of a good rectangle. Let $[AB]$ be the side of the pentagon $I$, to which some other tiling polygons are applied (Fig. 8). Let $A_1$ and $B_1$ be the second ends of the side of the polygon $M$, emerging from the vertices $A$ and $B$ respectively ($A_1$ and $B_1$ are not the vertices of the pentagon $I$; it is possible that $A_1 = B_1$). Let us denote by $C$ the point of intersection of $(AA_1)$ with $(BB_1)$. Then $\triangle ACB$ is a regular triangle, inside which all the tiling polygons lying above $[AB]$ are located (if $\Pi$ is located under $[AB]$, as in figure 8).

6°. Let us prove that all polygons of the partition lying inside $\triangle ABC$ (Fig. 8) are triangles.

Let's assume the opposite - let there be "non-triangles". (We will assume that side $[AB]$ is horizontal.) Consider the vertex of the non-triangle closest to $[AB]$ (lowest); if there are several such vertices, then take the rightmost middle one. Let us denote this “lowest” and rightmost” vertex by $D$. Point $D$ cannot lie on side $[AB]$: if the “non-triangle” is located as on figure 9, $a$, then one of the angles no larger than $\frac{180° - 90°}{2} = 45°$ is “bad”; if it is as in figure 9, $b$, and “non-triangle” is “non-square”, then again we get a “bad” angle (we agreed that “non-triangle” is “not hexagon”); if the “non-triangle” is a square, then on the right to the vertex $D$ the square (Fig. 9, $\theta$) is applied again, and, therefore, the vertex $D$ is not the rightmost one. The point $D$ cannot lie on the sides $[AA_1]$ and $[BB_1]$ of the polygon $M$: the ends $A_1$ and $B_1$ are not closest to $[AB]$, and if $D$ is the internal point $[AA_1]$ or $[BB_1]$, then the “non-triangle” must be entirely located inside the 60° angle (Fig. 10, $a$, $\theta$), which is impossible.

So, the points $D$ are the interior point of the region $AA_1 \dots B_1B$ of the polygon $M$. Since all “non-triangles” converging at $D$ must be located no lower than the angles at the vertex $D$ no more than 180°. This means that these are either two squares, or there is only one “non-triangle” with the vertex at $D$. If these are two squares, then since only horizontally - as in figure 11; but then the vertex $D$ is not the rightmost vertex of the “non-triangles”. If there is only one “non-triangle” in $D$ (for example, $k > 4$, $k \neq 6$), and the remaining polygons of the partition are triangles, then

$$360^\circ - 180^\circ \left(1 - \frac{2}{k}\right) = 60^\circ n$$

(n - natural). Hence $k = \frac{6}{n - 3}$. In natural numbers, this equation also has a solution: $n = 4, k = 6$;

⟦folio 48⟧

Fig. 13.
Fig. 14,
Fig. 15.
Fig. 16.
Fig. 17.
Fig. 18.
Fig. 19.
Fig. 20.
Fig. 21.
Fig. 22.

$n = 5, k = 3; n = 6, k = 2; n = 9, k = 1$. None of them suits us (we have $k > 4$ and $k \neq 6$). The resulting contradiction proves statement $6^\circ$: all polygons of the partition lying inside $\Delta ABC$ are triangles.

$7^\circ$. Let us prove that if among good polygons there is a rectangle, then $M$ has at most nine sides (maybe $n \leq 9$).

Indeed, if $A_1 \neq B_1 \neq C$, then $M$ has angles at vertices $A_1$ and $B_1$ equal in magnitude to $120^\circ$ (at vertices $A_1$

⟦folio 49⟧

and $B_1$ triangle converge - one or two; there cannot be one either at $A_1$ or at $B_1$, since in this case the sum of the magnitude of the angles at the vertices $A_1$ and $B_1$ is equal to either $360^\circ - 2\cdot 60^\circ = 240^\circ$ or $360^\circ - 60^\circ - 120^\circ = 180^\circ$, and it must be strictly less than $180^\circ$). Since the polygon $M$ is convex, this means that the segment $[A_1B_1]$ is its side.

Thus, if a good pentagon is involved in the division of the polygon $M$, then a polygon can be applied to at most two sides of this pentagon, and this is either a regular triangle or an equilateral trapezoid (Fig. 12). Statement $7^\circ$ follows from this.

$8^\circ$. Let us now prove that if the convex polygon $M$ can be divided into regular polygons, then it has at most twenty sides (that is, $n \leq 12$). Let us assume the opposite: let $n > 12$. then from points $3^\circ$ and $7^\circ$ it follows that among the good polygons participating in the division of polygon $M$ there are only triangles and squares. Therefore, the value of each of its angles has the form $90^\circ k + 60^\circ m$ ($k \geq 0, m \geq 0, k \in N, m \in N$) and is divided by 30; since $90^\circ k + 60^\circ m < 180^\circ$, the magnitude of each angle $M$ is at most $150^\circ$. Consequently, the value of each of its external angles is not less than $30^\circ$, and then the sum of all its external angles is not less than $13\cdot 30^\circ > 360^\circ$ - a contradiction.

Examples of split polygons with trays, four, ..., twelve sides are shown in Figures 13-22.

S. Mironov

F493. What influence does the Moon have on the trajectory of the Earth around the Sun?

Fig. 23.

As is known, under the influence of gravitational forces, the Moon and the Earth rotate around the axis of the point $P$ (Fig. 23). The center of the Moon moves along a circle of radius $r_\perp \approx 380\ 000$ km, and the center of the Earth moves along a circle of radius $r_3 \approx 4700$ km. Under the influence of the gravitational forces of the Sun, the Earth-Moon system rotates around the point $P$, then on the other. When moving around the otectori point $P$, the Center of the Earth covers a distance of $S = 2\pi r_3 \approx 29\ 500$ km, and its linear speed $v = S/T_\perp \approx 12.5$ m/s slightly exceeds the record speed of a person ($\approx 10$ m/s). The linear speed of the orbital motion of point $P$ is equal to $V \approx 30$ km/s.

The section of the trajectory traversed by the point $P$ in a relatively short time can be considered rectilinear. (In one day, the radius vector of point $P$ rotates through an angle $\alpha \approx \frac{2\pi}{365} \approx 0.99^\circ$, and the arc traversed by point $P$ can be considered a straight line segment.) In other words, the speed of point $P$ for a short period of time can be considered constant in direction. Over a short period of time, the projection of speed $v$ onto the direction of movement along the main trajectory can be written in the form $v_0 = v \sin(\omega t + \varphi_0)$, where the rotation frequency is $\omega = v/r_3$, and the initial phase $\varphi_0$ is associated only with the choice of the beginning of the timing $t$. Model of the speed of the Earth's center relative to the Sun over a short period of time.

⟦folio 50⟧

Fig. 25.

F494. In the circuit shown at figure 26, $R_2=90$ Ohm, $R_3=300$ Ohm, $R_4=60$ Ohm, $L_2=90$ G. What are the values of $R_1$ and $L_1$ if no current flows through the galvanometer $G$ regardless of whether it is connected to terminals a and b source of slop or alternating juice?

Fig. 26.

F495. Three non-displaceable liquids with densities $\rho_1$, $\rho_2$ and $\rho_3$ fill a closed monoculindrical tube, forming a ring, the plane of which is vertical.

$$\vec{V}_3 = V + v_0 = V + v \sin(\omega t + \varphi_0).$$

Thus, over a short period of time, the trajectory of the Earth around the Sun is a sine wave (section of a sine wave). The entire trajectory of the Earth during a full revolution of the point $P$ around the Sun can be approximately represented as successive sections of a sine wave, “bent” into a circle. The number of oscillations made by the Earth around the main trajectory in one year is obviously 1 year/$T_\pi \approx 13.5$. So after a year, the center of the Earth is no longer in “last year’s” position.

We see that, to be precise, there is no repeatability in the movement of the Earth, that is, for the movement of the Earth around the Sun it is impossible to introduce the concept of a period of revolution. From a mathematical point of view, the movement of the Earth-Moon system as a whole is periodic.

At figure 25 the trajectory of the Earth's center around the Sun is schematically presented.

A. Dozorov

The fact that no current flows through the galvanometer means that the potentials and their phases at points $c$ and $d$ are the same. Hence $u_{cn} = u_{dn}$, $u_{cm} = u_{dm}$ and $\frac{u_{cn}}{u_{cm}} = \frac{u_{dn}}{u_{dm}}$. Since the ratio of directional differences in successive sections of the circuit is proportional to the ratio of the impedances of these sections, then

$$\frac{R_3}{\sqrt{R_1^2 + \omega^2 L_1^2}} = \frac{R_4}{\sqrt{R_2^2 + \omega^2 L_2^2}},$$

or

$$R_1^2 R_4^2 - R_2^2 R_3^2 + \omega^2 \left(L_1^2 R_4^2 - L_2^2 R_3^2\right) = 0.$$

This equality must hold for any values ​​of $\omega$. This means that the coefficient of $\omega^2$ must be equal to zero, that is

$$L_1^2 R_4^2 - L_2^2 R_3^2 = 0,$$

and therefore,

$$R_1^2 R_4^2 - R_2^2 R_3^2 = 0.$$

(It is easy to check that in this case $\frac{L_1}{R_1} = \frac{L_2}{R_2}$, so the phases of the potentials at points $c$ and $d$ are the same.)

From the last equations we find:

$$L_1 = L_2 \frac{R_3}{R_4} = 450 \Gamma,$$

$$R_1 = \frac{R_2 R_3}{R_4} = 450 \Omega.$$

The pressure inside the tube at points $A$ and $B$ is the same; the pressure at points $C$ and $D$ is also the same. This means $\rho_1 gh_1 = \rho_2 gh_2 + \rho_3 gh_3$.

But $h_3 = h_1 - h_2$. Using this relation, we obtain $(\rho_1 - \rho_3) h_1 = (\rho_2 - \rho_3) h_2$. (I)

⟦folio 51⟧

(Fig. 27). A liquid with density $\rho_1$ fills a ring arc with an angle $\alpha_1$, a liquid with a density $\rho_2$ fills a ring arc $\alpha_2$. What angle $\alpha$ does the vertical radius of the ring drawn to the boundary of these liquids require? Superficial effects cannot be ignored.

Fig. 27.

F496. The cylindrical capacitor at point A admits a trace of a diverging beam of positive-molecular units with a small detuning angle $\alpha$ (Fig. 28). All of them in the beam have the same energy. Those whose velocity vector at point A is directed perendicularly to AO move along a circle of radius $AO=r_0$, concentric with the plates of the capacitor. Prove that the Yun beam will be focused at point B by makoi, which is $\widehat{AOB} = \pi/\sqrt{2}$. Determine the maximum beam length.

Fig. 28.

Fig. 29.

From figure we can see: $h_1 = R \cos \alpha + R \cos (\pi - \alpha - \alpha_1) = R [\cos \alpha - \cos (\alpha + \alpha_1)]$ and $h_2 = R \cos \alpha - R \cos (\alpha_2 - \alpha)$, where $R$ is the radius of the ring. Substituting these expressions for $h_1$ and $h_2$ into equality (1), we find $(\rho_1 - \rho_3) [\cos \alpha - \cos \alpha \cos \alpha_1 + \sin \alpha \sin \alpha_1] = (\rho_2 - \rho_3) [\cos \alpha - \cos \alpha_2 \cos \alpha - \sin \alpha_2 \sin \alpha]$, or $(\rho_1 - \rho_3) (1 - \cos \alpha_1 + \sin \alpha_1 \tg \alpha) = (\rho_2 - \rho_3) (1 - \cos \alpha_2 - \sin \alpha_2 \tg \alpha)$. Solving this equation, we find $\tg \alpha = \frac{(\rho_1 - \rho_3) (1 - \cos \alpha_1) - (\rho_2 - \rho_3) (1 - \cos \alpha_2)}{(\rho_1 - \rho_3) \sin \alpha_1 + (\rho_2 - \rho_3) \sin \alpha_2}$.

In order to be able to study the motion of a cylindrical capacitor, it is necessary first of all to find out what force acts on it in the power field of a cylindrical capacitor, that is, to find out what the direction of the power field of the capacitor is.

The field voltage is proportional to the density of the plum lines. If $n$ plum lines pass through an arc with a unit angle, then $N = n\varphi$ plum lines pass through an arc with an angle $\varphi$. The density of plum lines intersecting an arc of radius $r$ is equal to the ratio of the number $N$ to the length $r\varphi$ of the arc, that is, equal to $\frac{n}{r}$ (Fig. 29).

Therefore, the field voltage of the capacitor $\frac{1}{r}$:

$$E = -\frac{b}{r}, b = \text{const.}$$

In such a field, the charge $q$, located at a distance $r$ from the capacitor, is acted upon by a force $\vec{F}$ such that

$$|\vec{F}| = \frac{bq}{r}.$$

This force imparts to the charge an acceleration $a$ equal modulo

$$|\vec{a}| = \frac{bq}{rm},$$

where $m$ is the charge mass.

Let us denote by $x$ its deviation from the main trajectory of radius $r_0$ (this trajectory is shown on figure by the 28th red line). Then $r = r_0 + x$, and

$$|\vec{a}| = \frac{bq}{m(r_0 + x)}.$$

Let us consider the movement of it in the cut-off system, expressed around the axis of the capacitor so that its angular velocity at each moment is equal to the angular speed $\omega$ of the deviated one. In this system, the acceleration is no longer equal to $a$, since all points also move with some acceleration relative to the stationary cutoff system associated with the axis of the capacitor. A point located at a distance $r_0 + x$ from the axis moves with a central acceleration $\|\vec{a}_\mu\| = \omega^2(r_0 + x)$.

⟦folio 52⟧

Therefore, in the rotating reporting system, the acceleration is equal to

$$\left| \vec{a}_{\text{OTH}} \right| = - \left| \vec{a} \right| + \left| \vec{a}_{\text{II}} \right| = - \frac{bq}{m(r_0+x)} + \omega^2(r_0+x).

$$\text{From the law of conservation of angular momentum it follows that}

$$m(r_0+x)^2\omega = mr_0^2\omega_0,

$$\text{where } \omega_0 \text{ is the angular velocity of the nano at point } A. \text{ It is also equal to the angular speed of the nano moving along the “red” trajectory. But centripetal acceleration } \left| \vec{a}_0 \right| = \omega_0^2 r_0 \text{ inu moving along the “red” trajectory of radius } r_0, \text{ communicates the force } \vec{F}, equal in magnitude } \frac{bq}{r_0}, \text{ therefore}

$$\omega_0^2 r_0 = \frac{bq}{mr_0}, \text{ и } \omega_0^2 = \frac{bq}{mr_0^2}.

\text{Takим образом,}

$$\left| \vec{a}_{\text{OTH}} \right| = - \frac{bq}{m(r_0+x)} + \frac{bq}{mr_0^2}(r_0+x) \frac{r_0^4}{(r_0+x)^4} =

= \frac{bq\left[r_0^2-(r_0+x)^2\right]}{m(r_0+x)^3} = \frac{bq\left(-2r_0x-x^2\right)}{m(r_0+x)^3}.

\text{At } x << r_0

$$\left| \vec{a}_{\text{OTH}} \right| = -2 \cdot \frac{bq}{mr_0^2} x.

\text{Мы видим, что}

$$m\left| \vec{a}_{\text{OTH}} \right| = -kx, \text{ where } k = 2 \cdot \frac{bq}{r_0^2}.

\text{As is known, with such a dependence of the acceleration of the body on the displacement, the body performs harmonic oscillations with a period } T = 2\pi\sqrt{\frac{m}{k}}. \text{ Consequently, they are beams whose speed at point } A \text{ makes a small angle } \alpha \text{ with the speed of ins moving along the main trajectory will perform radial harmonic oscillations with a period relative to the main trajectory}

$$T = 2\pi\sqrt{\frac{mr_0^2}{2bq}}.

\text{Этот период одинаков для всех инов. Значит, после того как инов попадают в конденсатор в точке } A \text{ через времена } t_n = n\frac{T}{2}(n=1,2,3,\dots), \text{ все инов будут оказаться в одной и той же точке основной траектории — будут фокусироваться. Нетрудно найти угол } \varphi_0 \text{ между последовательными фокусами:}

$$\varphi_0 = \omega_0 t = \omega_0 \frac{T}{2} = \sqrt{\frac{bq}{mr_0^2}} \cdot \pi \sqrt{\frac{mr_0^2}{2bq}} = \frac{\pi}{\sqrt{2}}.

\text{Thus, if } \widehat{AOB} = \pi/\sqrt{2}, \text{ then the ions will be focused at point } B.

\text{Now let's find the maximum width of the beam. To do this, we take advantage of the fact that the maximum abscissistic value of the speed of a body performing harmonic oscillations and the amplitude } x_{\text{max}} \text{ of its coupling oscillations}

⟦folio 53⟧

compliance

$$|\vec{v}|_{\max} = x_{\max} \Omega,$$

where $\Omega = 2\pi/T$ is the oscillation frequency. In our case
$$|\vec{v}|_{\max} \text{ равно значению радиальной проекции скорости в точке } A \text{ иона (рис. 30):}$$
$$|\vec{v}|_{\max} = |\vec{v}_0| \sin \frac{\alpha}{2} = \omega r_0 \sin \frac{\alpha}{2} \approx \frac{1}{2} \omega r_0 \alpha$$
(since $\alpha$ is small, $\sin \frac{\alpha}{2} \approx \frac{\alpha}{2}$). Pozny
$$\frac{1}{2} \omega r_0 \alpha = x_{\max} \frac{2\pi}{T}.$$

Therefore, the maximum width $d$ of the beam is equal to
$$d = 2x_{\max} = \frac{\omega r_0 \alpha T}{2\pi} = \frac{r_0 \alpha}{\sqrt{2}}.$$

F497. A disk of radius $r$, moving with an angular velocity $\omega$, is thrown with a speed $v$ at an angle $\alpha$ to the horizontal. The plane of the disk remains vertical during its movement. The radus is the curvature of the trajectory of the highest point of the disk at the moment when the disk reaches its maximum height of rise.

At the moment when the disk reaches the maximum height of its rise, the speed of the center of the disk will be directed horizontally and its absolute value will be equal to $|\vec{v}| \cos \alpha$. Since the disk is moving around the center with an angular velocity of $\omega$, the linear speed of the points of the disk in a coordinate system moving horizontally at the same speed as the center of the disk is equal to $\omega r$, and their acceleration is equal in magnitude to $\omega^2 r$ and is directed towards the center of the disk. In a coordinate system related to the ground, the speed $u$ of the highest point of the disk at the moment when the disk reaches its maximum lifting height is directed horizontally, and $|\vec{u}| = |\vec{v}| \cos \alpha + \omega r$. The acceleration $a$ of this point at this moment is directed vertically, and $|\vec{a}| = \omega^2 r + |\vec{g}|$. Consequently, at this moment the point is moving along a circular path, the radius of which is determined by the relation

$$|\vec{a}| = \frac{u^2}{R}.$$

From here

$$R = \frac{u^2}{|\vec{a}|} = \frac{\left(|\vec{v}| \cos \alpha + \omega r\right)^2}{\omega^2 r + |\vec{g}|}.$$

I. Slobodetsky

⟦folio 55⟧

Limitation

To the concept of a bounded sequence introduced in the textbook (section 26), it is useful to add two more: the sequence $(x_n)$ is called bounded from above if there is a number $M$ such that for all $n$
$x_n \leqslant M$;
 subsequence $(x_n)$ is called limited sizu if there is such a number $m$that's for everyone $n$
$x_n \geqslant m$.

Obviously, the sequence $(x_n)$ is bounded if and only if it is bounded above and below.

At the wife's

5. Give four examples of sequences: bounded from above, but not from below; limited bluish, but not from above; not limited either below or above; limited both below and above.

6. Prove that any non-decreasing sequence is bounded below, and any non-increasing sequence is bounded above.

The existence will become clearer if we depict it in the form of a table. Any sequence has (the + sign in the table below) or does not have (the - sign) each of the two properties indicated above the “input” columns of the table. Thus, four possibilities will arise. In three cases, the theorems formulated above make it possible to assert the existence (+ sign in the “output” column of the table) or non-existence (- sign) of the limit. In the fourth case (third line of the table), nothing can be said about the definite (see Exercise 7).

Existence of a limit

The textbook proves that if a sequence has a limit, then it is bounded (section 26). Therefore, if a sequence is not limited, then it has no limit.

In addition, the textbook formulates the theorem mentioned at the beginning of the article. Weierstrass: if a sequence is monotonous and bounded, then it has a limit (item 32).

⟦folio 56⟧

Weierstrass's theorem saves many mathematical calculations that otherwise would have turned out to be lax. Let's compare the two calculations.

Example 1. Let's put

$$x = \sqrt{2 + \sqrt{2 + \sqrt{2 + \ldots}}}$$

(the number of radicals is infinite). Note that under the first radical there is 2+x. Solving the equation

$$x = \sqrt{2 + x},$$

we get $x=2$.

Example 2. Let's put

$$x = 1 + 2 + 4 + 8 + 16 + 32 + \ldots$$

(the number of terms is infinite). Note that

$$x = 1 + 2 + 4 + 8 + 16 + \ldots = 1 + 2(1 + 2 + 4 + 8 + \ldots) = 1 + 2x.$$

Solving the equation

$$x = 1 + 2x,$$

we get $x=-1$.

The reasoning is similar, but in the second example we got an obvious nonsense. Let's try to save (make strict) the first calculation. To do this, using the concept of a limit, we give a precise meaning to the “infinite expression” (1). Consider the sequence

$$\begin{cases} x_1 = \sqrt{2}, \\ x_n = \sqrt{2 + x_{n-1}}. \end{cases}$$

By expression (1) it is natural to understand the limit of this sequence, if it exists. This is where Weierstrass's theorem comes in handy. It is easy to check that for all $n$, firstly, $x_n < 2$ (by induction) and, secondly, $x_n > x_{n-1}$ (see Exercise 4). This means that by Weierstrass’s theorem the sequence $(x_n)$ has a limit. Thus, the notation $x$ for expression (1) is correct. From equality $x_n = \sqrt{2 + x_{n-1}}$, passing to the limit, we obtain (2). The reasoning of example 1 is saved *).

*) Regarding the understanding of “infinite expressions”, see also «Kvant», 1977, No. 10, p. 60.
