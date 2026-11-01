---
id: 1978-1-kurlyandchik-rozenblyum-metod-beskonechnogo-spuska-ef7f8d4d
issue: kvant_1978_1
year: 1978
number: "1"
title: Infinite descent method
authors:
  - Курляндчик Л. Д.
  - Розенблюм Г.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 26
page_last: 29
page_labels: 24-27
tag: R8FB
lang: en
source: kvant_digital
extraction: vision
content_sha256: 05870d0e63c2224b2f37554241a4b2afb3f0e315b8ed624bc120ff9f372e4e58
prompt_sha256: draft-1
translated_from: content/ru/1978/01/articles/09_kurlyandchik-rozenblyum-metod-beskonechnogo-spuska-ef7f8d4d.md
source_content_sha256: 49b13da1db47c770c6ffd3fb68de08ebed5ecca5abc6bda004116401c09ad0e0
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 24⟧

Infinite descent method

Which irrational number is itself “old”? Without a doubt, $\sqrt{2}$. We don’t know exactly who was the first to prove the irrationality of this number, but we are convinced that it was done something like this.

Proof of the first

Let us assume that the number $\sqrt{2}$ is irrational. Geometrically, this means that the diagonal of a square of length $c$ is commensurate with its side of length $a$, that is, it will find a segment of length $d$ and integers $m$ and $n$ such that $c=dm$, $a=dn$. Let us mark $m-1$ points on the diagonal $AC$ and $n-1$ points on the side $DC$, dividing these segments into pieces of length $d$. Let us put aside the segment $AK: |AK|=|AD|;$ at $|AC|$ and the segment $DE: |DE|=|KC|$ at $|DC|$. Points $K$ and $E$ will fall into the offset points

Fig. 1.

Proof two

The irrationality of $\sqrt{2}$ means that the equation $x^2=2y^2$ has no solution in natural numbers $x, y$. Let us assume that there are such solutions, and $x=m$, $y=n$ is one of them.

From the equation it follows that $m$ is an even number, $m=2m_1$. Substituting $m=2m_1$ into the equation, we obtain $n^2=2m_1^2$, that is, $x=n$, $y=m_1$ are also a solution. Let us note that $n<m$, $m_1<n$. Now it is clear that $n$ is an even number, $n=2n_1$, therefore $m_1^2=2n_1^2$. Thus

⟦folio 25⟧

at once, $x = m_1, y = n_1$ is the solution of the equation, and $m_1 < n, n_1 < m_1$. We can build further in the same way, obtaining a smaller and smaller solution to the equation. But here there is already a contradiction. After all, all numbers $m, n, m_1, n_1, \dots$ are natural numbers, $m > n > m_1 > n_1 > \dots$, and there cannot be an infinite decreasing sequence of natural numbers! This means that our assumption was wrong, and the number $\sqrt{2}$ is irrational.

Both arguments essentially followed the same pattern: assuming that the problem had a solution, we built some kind of endless process, while according to the very meaning of the problem, this process should end somewhere. This method is called the infinite descent method $^*$.

Often the descent method is used in a simpler form. Assuming that we have already added to the natural end of the process, we see that it cannot “stop”.

Proof three

Let $x = m, y = n$ be the solution of equation $x^2 = 2y^2$ with the smallest possible $x$. The number $m$ must be even, $m = 2m_1$, therefore $x = n, y = m_1$ is also a solution to our equation. However, $m > n$, which contradicts the choice of solution $m, n$ as the “smallest”.

From this version of the proof it is clear that the descent method is an average method of mathematical induction. Both methods are based on the fact that any infinite set of natural numbers has a minimal element. The descent method is most convenient for proving the “negation” of theorems.

Descent method in problems

Problem 1. Prove the unsolvability of the equation in natural numbers

$$8x^4 + 4y^4 + 2z^4 = t^4.$$

*) The method of infinite descent was apparently invented by an ancient Greek mathematician. There is reason to believe that Fermat is trying to prove his Great Theorem using precisely this method.

Solution. Let us assume that there is a solution, and $x = m, y = n, z = p, t = r$ is the solution with the smallest possible $x$. From the equation we can see that $r$ is an even number, $r = 2r_1$.

Substituting this solution into the equation and multiplying by 2, we get

$$4m^4 + 2n^4 + p^4 = 8r_1^4.$$

Now it is clear that $p$ is even, $p = 2p_1$, therefore

$$2m^4 + n^4 + 8p_1^4 = 4r_1^4.$$

Then it works the same way: $n = 2n_1$, $m^4 + 8n_1^4 + 4p_1^4 = 2r_1^4$.

Finally, $m = 2m_1$, $8m_1^4 + 4n_1^4 + 2p_1^4 = r_1^4$.

Thus, $x = m_1, y = n_1, z = p_1, t = r_1$ is the solution to our equation. But it’s $m_1 < m$! We received a contradiction with the choice of solution $m, n, p, r$ as the “smallest”.

Let's consider the problem more complicated.

Problem 2. Prove the unsolvability of the equation in natural numbers

$$x^2 + y^2 + z^2 + u^2 = 2xyzu.$$

Solution. Let $x, y, z, u$ be the solution.

Since $x^2 + y^2 + z^2 + u^2$ is an even number, then the average numbers $x, y, z, u$ are an even number of odd ones, that is, either even, or two, or zero. If all numbers are odd, then $x^2 + y^2 + z^2 + u^2$ is not divisible by 4, and $2xyzu$ is not divisible. If there are only two odd numbers, then $x^2 + y^2 + z^2 + u^2$ is not divisible by 4, but $2xyzu$ is divisible. Therefore all numbers, that is, $x = 2x_1, y = 2y_1, z = 2z_1, u = 2u_1$. Substituting these values ​​into the equation, we get

$$x_1^2 + y_1^2 + z_1^2 + u_1^2 = 8x_1y_1z_1u_1.$$

As before, we see that all even numbers cannot be odd, otherwise $x_1^2 + y_1^2 + z_1^2 + u_1^2$ is not divisible by 8. Likewise, even numbers cannot be odd, or even then $x_1^2 + y_1^2 + z_1^2 + u_1^2$ is not divisible by 8. So, we get that all numbers are odd, that is

$$x_1 = 2x_2, y_1 = 2y_2, z_1 = 2z_2, u_1 = 2u_2.$$

⟦folio 26⟧

Because

$$x_2^2 + y_2^2 + z_2^2 + u_2^2 = 32x_2y_2z_2u_2.$$
Reasoning as before, we find that $x_2, y_2, z_2, u_2$ are even numbers, and so on. It is easy to understand that for every natural s

$$x_s^2 + y_s^2 + z_s^2 + u_s^2 = 2^{2s+1}x_sy_sz_su_s,$$

and

$$x_k = 2x_{k+1}; y_k = 2y_{k+1};$$

$$z_k = 2z_{k+1}; u_k = 2u_{k+1}; k \geqslant 1.$$

That is, for any natural number s, the numbers $\frac{x}{2^s}, \frac{y}{2^s}, \frac{z}{2^s}, \frac{u}{2^s}$ are integers. Well, this is impossible for any natural x, y, z, u.

And here is an equation that has an infinite number of solutions, but which is studied using the same method.

Problem 3. Find all solutions in natural numbers to the equation

$$x^2 - 2y^2 = 1.$$

Solution e. Obviously, $x_1 = 3, y_1 = 2$ is a solution to this equation. Let us prove that if the pair x, y is a solution, then the pair 3x + 4y; 2x + 3y is also a solution. This follows exposition

$$(3x + 4y)^2 - 2(2x + 3y)^2 = x^2 - 2y^2.$$

Thus,

$$x_2 = 3 \cdot 3 + 4 \cdot 2 = 17,$$

$$y_2 = 2 \cdot 3 + 3 \cdot 2 = 12;$$

$$x_3 = 99, y_3 = 70,$$ and so on.

We indicate an infinite sequence of solutions $x_1, y_1; x_2, y_2; \dots$ Let us now prove that there are no other numbers satisfying the equation.

Let x, y be some solution. In this case, 3x - 4y, 3y - 2x is also a solution, or

$$(3x - 4y)^2 - 2(3y - 2x)^2 = x^2 - 2y^2.$$

From condition 9 = 9x^2 - 18y^2 > -2y^2 it follows that 3x > 4y; and for y > 2, from the condition 4 = 4x^2 - 8y^2 < y^2 it follows that 3y > 2x. That is, for y > 2, from the solution x, y we obtain the solution $x^{(1)}, y^{(1)}$ in natural numbers, and $x^{(1)} < x, y^{(1)} < y$. Since this process cannot continue indefinitely (any non-empty set of natural numbers has a smallest element!), then someday we will get the solution $x^{(n)}, y^{(n)}$, where $y^{(n)} \leqslant 2$. Since $y^{(n)}$ obviously cannot equal 1, then $y^{(n)} = 2$. So, $x^{(n)} = 3$.

And this means that the numbers x and y belong to the sequence constructed earlier.

Until now we have only considered equations. Let’s solve the problem using our “text” method.

Problem 4. There are 2n + 1 digits, each of which weighs an integer number of grams. It is known that any 2n of them can be decomposed into a number of weights, n for each, so that equilibrium is achieved. Prove that all numbers have equal weight.

Solution e. It is clear that all weights simultaneously have either even or odd weight: the weight of any 2n weights is even. Let us now subtract the weights of all the weights from the weight of the lightest weight (or the lightest, if there are several of them). The new system of weights, very indo, also satisfies the conditions of the problem, and among the weights there are “weights” of zero weight. Therefore, we again find that the weight of all weights is even, and so on. From the “infinite descent” it follows that all “weights” are zero, which means that all initial weights have the same weight.

The idea of ​​infinite descent allows us to solve non-ctoral problems of geometry combinators.

Problem 5. Is it possible to cut a cube into neotorko different cups?

Solution e. Let us first make one very remark. Let the square P be divided into a finite number of different squares. Then the smallest square is not adjacent to the boundary of square P.

Let us now assume that the cube Q has been cut into different cubes Q_j; let P be one of the faces of Q. The cubes Q_j adjacent to P generate a partition of P into pairwise distinct squares. Let P_1 be the smallest of these squares, Q_1 is the one corresponding to the boundary of P, therefore it is surrounded by large squares. The corresponding cubes form a “well” in which cube Q_1 lies.

⟦folio 27⟧

Let $P_1'$ be the “upper” face (opposite to face $P_1$) of the cube $Q_1$. Cubes adjacent to $P_1'$ generate a partition of $P_1'$ into different squares. Again the smallest one, $P_2$, is located inside $P_1'$, hence the cubes surrounding the corresponding cube $Q_2$ are larger than $Q_2$ and again form a “well”. Continuing the construction further, we will get an endless “tower” consisting of ever-decreasing cubes, and this is impossible.

In conclusion, a problem on checkered paper.

Problem 6. Given a sheet of terminal paper. Prove that for $n \neq 4$ there is no regular $n$-street with vertices at nodes. Indeed, let $a$ be the length of the side of this triangle; then $a^2$ is an integer by the Pythagorean theorem. The area of ​​the triangle is $\frac{a^2 \sqrt{3}}{4}$, that is, irrational. On the other hand, it is very important that the area of ​​any polygon with vertices at nodes is rational.

Since a regular hexagon can be written as a regular triangle with vertices at its vertices, the statement is also proven for $n=6$.

Let $n \neq 3,4,6$. Let us assume that $P_1, P_2, \dots, P_n$ is a $n$-walker with vertices at the nodes. Let us plot from the points $P_1, P_2, \dots, P_n$ the vectors corresponding to the vector $\overrightarrow{P_2}P_3; \overrightarrow{P_3}P_4; \dots, \overrightarrow{P_1}P_2$ (Fig. 2). The new points will again fall into the lattice nodes and form a regular $n$-space inside the first equal one. With the new $n$-retreat you can build the same, and so on, endlessly. However, the square of the length of the sides of the $n$-walker is an integer, and in our constructions it decreases all the time!

Do you get married?

1. Prove that the base and side of an equilateral triangle with vertex angle $36^\circ$ are immeasurable.
2. Prove that the number 7 cannot be represented as the sum of the squares of three rational numbers.
3. Solve the equations in whole numbers:
   a) $x^3 - 3y^3 - 9z^3 = 0$;
   b) $5x^3 + 11y^3 + 13z^3 = 0$.
4. Prove that the equation
   a) $x^2 + y^2 + z^2 = 2xyz$;
   b) $(x+1)^3 - x^3 = y^2$.
5. Solve the following equations in natural numbers:
   a) $x^2 + (x+1)^2 = y^2 + 1$;
   b) $3x^2 - 7y^2 + 1 = 0$;
   b) $(x+1)^3 - x^3 = y^2$.
6. Prove that the lowest number of the form $4^n(8k-1)$, where $k$ and $n$ are natural numbers, is not a perfect square and cannot be represented as the sum of two or three squares of numbers.
7. $a_1, a_2, \dots, a_n$ is a set of pairwise distinct natural numbers ($n > 2$). It makes a new set $\frac{a_1 + a_2}{2}, \frac{a_2 + a_3}{2}, \dots, \frac{a_{n-1} + a_n}{2}, \frac{a_n + a_1}{2}$;
from it - the next, according to the same rule, and so on. Prove that after a few steps you will definitely get a set in which not all numbers are integers.
8. Given a convex polygon and a point inside it. Prove that at least one of the perpendiculars to the planes of the faces drawn through this point intersects with the corresponding face. Is this fact true for a non-convex polygon?
9. Let $a_1, a_2, \dots, a_{2n}$ be an arbitrary set of natural numbers. Prove that if we form a new set $b_1, b_2, \dots, b_{2n}$ from it according to the rules $b_k = |a_k+1 - a_k|$, $k=1, 2, \dots, 2^n$, $a_{2n+1} = a_1$, then from the set $b_1, b_2, \dots, b_{2n}$ according to the same rule we form a set $c_1, c_2, \dots, c_{2n}$, then after a certain number of steps we will arrive at a set consisting only of zero.
