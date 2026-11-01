---
id: 1979-3-resheniya-zadach-m504-m506-m507-f513-f516-f517-aed8c727
issue: kvant_1979_3
year: 1979
number: "3"
title: Solutions to problems M504, M506, M507; F513, F516, F517
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 36
page_last: 41
page_labels: 34-39
tag: E2WJ
lang: en
source: kvant_digital
extraction: vision
content_sha256: 071a962990e835af8cd1a083c9ef29f56be90ee0139b9ab9988130df25695a87
prompt_sha256: draft-1
translated_from: content/ru/1979/03/articles/10_resheniya-zadach-m504-m506-m507-f513-f516-f517-aed8c727.md
source_content_sha256: d246add8c37575fd96b1ee545269351ceccdc4ed4e2398d59530cc3e9770fadf
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 34⟧

Problem solutions
M504, M506, M507; F513, F516, F517

M504. On a chessboard of $n \times n$ cells there are $k$ plimks of size $2 \times 1$ laid, and it is impossible to place the $(k+1)$th plimka without moving the existing plimks. Prove that there are no more than $a) (n^2+n+1)/3$ free cells left;
$b) (n^2+2)/3$;
$c) n^2/3$.

Is it possible to obtain an even more powerful estimate for some $n$?

Fig. 1.

Fig. 2.

This cage must be free

Fig. 3.

Fig. 4.

Let there be $x$ free cells.

a) Let us associate each free cell that does not lie on the upper horizontal of the board with a tile “covering” it from above (Fig. 1). It is clear that each tile is associated with at most one cell (so the number of free cells that do not lie on the top horizontal of the board is at most one number of $\frac{n^2-x}{2}$ tiles laid out as stated in the problem). Let there be $x_1$ free cells on the top horizontal of the board; then $x_1 \leq \frac{n+1}{2}$. We have $x-x_1 \leq \frac{n^2-x}{2}$, that is

$$3x \leq n^2+2x_1 \leq n^2+n+1,$$

where

$$x \leq (n^2+n+1)/3.$$

6) Let us denote by $x_1$ the number of free cells inside the board, by $x_2$ the number of free cells on the border of the board, not counting the corner cells; finally, by $x_3$ we denote the number of free corner cells of the board. Then $x=x_1+x_2+x_3$. By $y_1$ we denote the number of l and tok located strictly inside the board; through $y_2$—the number of tiles that extend to the edges of the board in at least one square; then $y_1+y_2 = \frac{n^2-x}{2}$.

Let's calculate how many spaces a free cell has - its border is plimka. On the one hand, there are $4x_1+3x_2+2x_3$ of them. On the other hand, since the tiles are laid in such a way that it is no longer possible to add a single one, there are no more than $4y_1+3y_2$ of these pairs (each tile facing the edges of the board borders no more than a third square, and each tile strictly inside the board borders no more than four). Pozny

$$4x_1+3x_2+2x_3 \leq 4y_1+3y_2.$$

Since two free cells on the board boundary are separated by a tile, we have

$$x_2+x_3 \leq y_2.$$

Adding inequalities (1) and (2), we obtain

$$4x_1+4x_2+3x_3 \leq 4(y_1+y_2),$$

or

$$x-\frac{1}{4}x_3 \leq \frac{n^2-x}{2}.$$

But $x_3 \leq 4$; means $x \leq \frac{n^2-x}{2} + 1$ or $3x \leq n^2+2$, hence $x \leq (n^2+2)/3$.

c) Note that if inequality (1) is strict, then we get what we need in point c): the strict inequality $x < \frac{n^2-x}{2} + 1$ is equivalent in this way:

$$x \leq \frac{n^2-x}{2}, \text{откуда } x \leq \frac{n^2}{3}.$$

Pozny, if we assume that $x > \frac{n^2}{3}$, then in any case it is necessary that each tile must be adjacent to the maximum number of free cells. In particular, any side of a tile of length 1 that does not fit into the edge of the board must be adjacent

⟦folio 35⟧

Free cell. Therefore, the tiles must be arranged in “rows” (Fig. 2), and the “rows” can neither abut each other nor intersect with each other, since in both cases the picture depicted in figure 3 will appear until it reaches the edge. This means that all “rows” must be parallel, which is only possible when $n$ is divisible by 3. In this case, the number of tiles is $n^2/3$ (the corresponding example is shown in figure 4). So, for boards $n \times n$, where $n=3k$, the estimate $\frac{n^2}{3}$ is exact.

S. Fomin

Without loss of generality, we can assume that $0 < a \leq b \leq c \leq d$. Adding three further inequalities
$$a(a-b)(a-c)(a+2d) \geq 0,$$
$$a(a-b)(a+2c)(a-d) \geq 0,$$
$$a(a+2b)(a-c)(a-d) \geq 0,$$
we get
$$3a^4 - 3a^2(bc + bd + cd) + 6abcd \geq 0,$$
or
$$a^4 - a^2(bc + bd + cd) + 2abcd \geq 0.$$

On the other hand, inequality
$$b^4 + c^4 + d^4 - a^2(b^2 + c^2 + d^2 - bc - bd - cd) - b^2c^2 - b^2d^2 - c^2d^2 \geq 0$$
equivalent to the next
$$[(b+c)^2 - a^2](b-c)^2 + [(b+d)^2 - a^2](b-d)^2 + [(c+d)^2 - a^2](c-d)^2 \geq 0.$$

Adding inequalities (1) and (2), we obtain the statement of the problem.
Let us present a solution to this problem using mathematical analysis. We need the following geometric estimate
Lemma. If the function $f$ is non-negative arbitrary at each point of the loop $[x_0; +\infty[$, then it is non-decreasing on this loop.
Note that if any two of the numbers $a, b, c, d$ coincide, then the inequality proving is true. In fact, let us direct, $a = d$. then our inequality can be rewritten as follows:
$$a^4 + 2(bc - b^2 - c^2)a^2 + b^4 + c^4 - b^2c^2 \geq 0.$$

The left-hand side of inequality (3) is a quadratic trinomial with respect to $a^2$ with non-positive discrimination $-2bc(b-c)^2$, therefore (3) is valid.

Let us now rewrite the required inequality in this form:
$$d^4 - (a^2 + b^2 + c^2)d^2 + 2abcd + a^4 + b^4 + c^4 - a^2b^2 - a^2c^2 - b^2c^2 \geq 0$$

and consider the left-hand side of (4) as a function of $d$; Let's denote this function by $f$. We need to prove that $f(d) \geq 0$ for $d \geq c$ (and $0 < a \leq b \leq c$). We have:
$$f'(d) = 4d^3 - 2(a^2 + b^2 + c^2)d + 2abc,$$
so $f'(c) = 2c^3 - 2(a^2 + b^2)c + 2abc \geq 0 (0 < a \leq b \leq c)$.
Next,
$$f''(d) = 12d^2 - 2(a^2 + b^2 + c^2) \geq 0$$

at $0 < a \leq b \leq c$. Therefore, by Lemma $f'(d) \geq f'(c) \geq 0$ for $d \geq c$. Using the fact that $f(c) \geq 0$ (see remark above) and $f'(d) \geq 0$ for $d \geq c$, and applying the lemma again, we obtain the inequality $f(d) \geq 0$ for $d \geq c$, which is what was required.

An interesting generalization of this inequality was invented by F. Schleöfer (Ryazan): for any $a_1, \dots, a_n$
$(n-1)(a_1^2 + a_2^2 + \dots + a_n^2) + n\sqrt{a_1^2 \cdot a_2^2 \cdot \dots \cdot a_n^2} \geq (a_1 + a_2 + \dots + a_n)^2$.

For $n=4$, $a_1=a^2$, $a_2=b^2$, $a_3=c^2$, $a_4=d^2$ we obtain the statement of our problem.

V. Senderov, E. Turkevich

⟦folio 36⟧

M507. Let $a_1 < a_2 < \dots < a_n < 2n$ be a finite sequence of natural numbers ($n \ge 6$).
a) Let us prove that
$$\min [a_i, a_j] \leq 6 \left( \left[ \frac{n}{2} \right] + 1 \right),$$
$[a_j, a_j]$ also means the least common multiple of the numbers $a_i$ and $a_j$, and the minimum is taken over all parameters of the numbers $a_i, a_j$.
b) Let us prove that
$$\max (a_i, a_j) > \frac{38n}{147} - c,$$
else $c$ does not depend on $n$, and $(a_i, a_j)$ means the least common divisor of $a_i$ and $a_j$.
The estimates in problems a) and b) cannot be improved (we can replace coefficient 6 with a smaller one, and $\frac{38}{147} - \text{большим}$).

Below we will prove a more general statement. Let $a_1 < a_2 < \dots < a_n \leq 2n$.
a) Let us prove that we require that the inequality holds for $n \ge 5$. Let among the elements of the sequence $a_1, a_2, \dots, a_n$ there is a number $a \leq n$. If the number 2a also belongs to this sequence, then
$$\min [a_i, a_j] \leq [a, 2a] = 2a \leq 2n \leq 6 \left( \left[ \frac{n}{2} \right] + 1 \right),$$
which gives a solution to the problem. If 2a does not belong to the sequence, then we remove the number $a$ from it and replace it with 2a. It is clear that $\min [a_i, a_j]$ for the new sequence is no less than for the original one. Applying the same reasoning to each element $a \leq n$, we will eventually arrive at the sequence $n + 1, n + 2, \dots, 2n$, and
$$\min [a_i, a_j]$$ for this sequence is not less than the corresponding minimum for any other sequence from which it was obtained, in particular for the original one.
Let us now prove that for the sequence $n + 1, n + 2, \dots, 2n$ at $n \ge 5$ the equality
$$n + 1 \leq a < b \leq 2n$$
And
$$[a, b] = 6k + 6 = 6 \left( \left[ \frac{n}{2} \right] + 1 \right).$$

Now let’s check that for any pair of numbers $c, d$ satisfying the condition $n + 1 \leq c < d \leq 2n$, the inequality $[c, d] \geq 6 \left( \left[ \frac{n}{2} \right] + 1 \right)$ holds. Indeed, $[c, d] = pd = qc$, where $q > p > 1$. In this case, either $p = 2$ and $q \ge 3$, or $q \ge 4$. In the first case, $c$ is an even number, thus $c \ge 2 \left( \left[ \frac{n}{2} \right] + 1 \right)$ and $[c, d] = qc \ge 3c \ge 6 \left( \left[ \frac{n}{2} \right] + 1 \right)$. In the second case $[c, d] = qc \ge 4 (n + 1) \ge 6 \left( \left[ \frac{n}{2} \right] + 1 \right)$. This completes the proof of statement a).

6) Let's consider a more general problem: let $a_1 < a_2 < \dots < a_k \leq B$ be a sequence of natural numbers; Let's try to estimate the strength of $max (a_i, a_j)$. For this purpose, the inverse problem is useful: let $A, B$ be positive (not necessarily an integer) numbers; determine the maximum $k$ for which there is a sequence of $k$ distinct natural numbers $a_1, a_2, \dots, a_k$ maxims such that
(1) which element of the sequence does not exceed $B$;
(2) $(a_i, a_j) \leq A$ for any distinct elements $a_i, a_j$.
We will denote this maximum quantity by $k (A, B)$. To solve the original problem, you need to choose $A$ so that $k (A, 2n)$ is approximately equal to $n$. Indeed, if for each $A$
$$k (A, 2n) < n,$$
then for any sequence $a_1 < a_2 < \dots < a_n \leq 2n$ there will be
$$max (a_i, a_j) > A;$$
if $k (A, 2n) \ge n$, then there is a sequence $a_1 < a_2 < \dots < a_n \leq 2n$ such that
$$max (a_i, a_j) \leq A.$$
Let $a_1, \dots, a_k$ be a sequence satisfying conditions (1) and (2). If some element $a_i$ of this sequence has a divisor $d > A$ that is not identical with $a_i$, then by condition (2) $d$ is not an element of the sequence. Then, replacing

⟦folio 37⟧

$a_i$ by $d$, we obtain a new sequence of the same length, also satisfying conditions (1) and (2). Proceeding in the same way, we will eventually obtain a sequence in which no element has its own divisors greater than $A$. We call such a sequence irreducible.

Let us now consider the set $M$ of all natural numbers that do not exceed $B$ and do not have proper divisors greater than $A$. M is an irreducible sequence satisfying conditions (1) and (2), and every other irreducible sequence is contained in $M$. Therefore it is clear that $k(A, B)$ is simply equal to the number of elements $M$.

To count the number of elements of the set $M$, we separately calculate the number of four elements, the number of odd elements divisible by 3, etc. More precisely, let $M_2$ consist of all four elements of the set $M$, $M_3$ consist of all four elements of $M$ divisible by 3, $M_5$ consist of all four elements $M$, divisible by 5, but not divisible by either 2 or 3. And in general, for any prime number $p$, the set $M_p$ consists of those elements of the set $M$ that are divisible by $p$ and have no prime factors less than $p$.

Let's count the number of elements of the set $M_p$. Any element from $M_p$ has the form $pc$, where $c \leqslant A$ (since $M$ is an irreducible set), $pc \leqslant B$ and $c$ have no prime factors less than $p$. If $pA \leqslant B$, then the condition $pc \leqslant B$ can be ignored, and the number of elements $M_p$ is equal to the number of natural elements $c \leqslant A$ that do not have prime factors smaller than $p$ (we will denote such a number by $m_p(A)$). If $pA > B$, then the number of elements $M_p$ is equal to $m_p\left(\frac{B}{p}\right)$ and does not exceed $m_p(A)$.

Let us fix a prime number $p$. The sets $M_2, M_3, M_5, \dots, M_p$, generally speaking, do not exhaust the sets $M$. Let us denote by $N$ the set of all remaining elements of $M$. They have no divisors among the numbers 2, 3, 5, ..., $p$, so their number does not exceed the number $m_q(B)$, where $q$ is the next prime number after $p$. Thus,

$$k(A, B) \leqslant m_2(A) + m_3(A) + \dots + m_p(A) + m_q(B).$$

If $pA \leqslant B < qA$, then this inequality turns into equality. Indeed, it is clear that each $M_r$ contains exactly $m_r(A)$ elements. On the other hand, every number $c \leqslant B$, which has no divisors smaller than $q$, thereby has no divisors greater than $A$ (if $c = df$, where $d > A$ and $c \leqslant B < qA$, then $f < q$), and therefore is included in $N$; hence $N$ contains $m_q(B)$ elements.

Now let's start estimating numbers of the form $m_r(C)$. Firstly, $m_2(C)$ is equal to the number of all natural $l \leqslant C$, that is, equal to $[C]$, and differs from $C$ by less than 1. Next, $m_3(C) = m_2(C) - m_2\left(\frac{C}{2}\right)$ (the number of all $l \leqslant C$ is less than 1, then $m_3(C)$ differs from $C$ $\left(1 - \frac{1}{2}\right)$ by less than 2).

Reasoning in the same way, we get that if $p$ and $q(p < q)$ are two neighboring prime numbers, then $m_q(C) = m_p(C) - m_p\left(\frac{C}{p}\right)$, from which indication it turns out that $m_q(C)$ differs from the number $C\left(1 - \frac{1}{2}\right)\left(1 - \frac{1}{3}\right) \dots \dots \left(1 - \frac{1}{p}\right)$ by less than $2^{i-1}$, where $i$ is the number of the prime number $q$. In other words, denoting by $Z_q$ the product of all numbers of the form

⟦folio 38⟧

$$\left(1 - \frac{1}{r}\right),$$
where $r$ is a prime number less than $q$ (and putting $Z_2 = 1$), we get

$$|m_q(C) - C \cdot Z_q| < 2^{i-1}$$

($i$ is the number of the prime number $q$). Thus, the following estimates are true for the number $k(A, B)$:

$$k(A, B) \leq m_2(A) + \ldots + m_p(A) + m_q(B) < A(Z_2 + Z_3 + \ldots + Z_p) + B \cdot Z_q + 1 + 2 + \ldots + 2^{i-1} = A(Z_2 + \ldots + Z_p) + B \cdot Z_q + (2^i - 1);$$

if $pA \leq B \leq qA$, then

$$k(A, B) = m_2(A) + \ldots + m_p(A) + m_q(B) > A(Z_2 + \ldots + Z_p) + B \cdot Z_q - (2^i - 1).$$

(3)

Let us now return to the original problem and find out for which $A$ $k(A, 2n) < n$. To do this, it is sufficient to solve for $A$ the inequality

$$A(1 + Z_3 + \ldots + Z_p) + 2n \cdot Z_q + (2^i - 1) \leq n.$$

Taking $p$ equal to 3.5 or 7, we get, respectively,

$$A \leq \frac{2}{9}n - \frac{14}{3}, \quad A \leq \frac{14}{55}n - \frac{90}{11},$$

$$A \leq \frac{38}{147}n - \frac{310}{21}.$$

At $p = 7$ there is a tinny factor $\frac{38}{147}$, the largest of the three. Taking $p \geq 11$ is pointless, since $11 \cdot \frac{38}{147}n \geq 2n$, and the inequalities for $k(A, 2n)$ will be less accurate. So, we have proven that for $n \geq 2$ for any sequence $a_1 < a_2 < \ldots < a_n \leq 2n$

$$\max(a_i, a_j) > \frac{38}{147}n - \frac{310}{21}.$$

To prove that the coefficient $\frac{38}{147}$ cannot be mutilated, we take $A = \frac{38}{147}n + \frac{310}{21}$. Then at $n \geq 543$ there will be $7A \leq 2n < 11A$, and, using inequality (3), we obtain $k(A, 2n) \geq n$. Therefore, for $n \geq 543$ there is always a sequence $a_1 < a_2 < \ldots < a_n \leq 2n$ for which

$$\max(a_i, a_j) \leq \frac{38}{147}n + \frac{310}{21}.$$

If we estimate $m_r(C)$ carefully, we can obtain more accurate inequalities: for $n \geq 2$ for any sequence $a_1 < a_2 < \ldots < a_n \leq 2n$

$$\max(a_i, a_j) \geq \frac{38}{147}n - \frac{73}{49};$$

and, in addition, there is a sequence $a_1 < a_2 < \ldots < a_n \leq 2n$ for which

$$\max(a_i, a_j) \leq \frac{38}{147}n + \frac{73}{49}.$$

(the remarkable thing is that the constant $\frac{73}{49}$ in these inequalities can no longer be reduced).

D. Bernishtein

⟦folio 39⟧

F513. On a clear sunny day, when the Sun is in the horizon, get on a smooth screen, to the right, on a white wall, straightening the edges of a piece of cardboard. If you bring your finger to the sheet of cardboard, as shown in figure 5, then on the screen I will shoot my finger from me, thrown off by the sheet of cardboard, and dry me with the second finger. Carry out this experiment and explain its result.

It is impossible to use the concept of diffraction to describe the phenomenon, since the dimensions of the diffraction pattern at such distances are small.

The solution to the adult problem is only when we take into account that the Sun is not an exact source of light, but has finite angular dimensions.

To understand how an oncoming shadow appears, refer to figure 6.

Since the Sun as a light source has some angular dimensions (about half a degree), the shadows of all objects on a sunny day are placed. The size of the edge of the shadow depends on the distance from the object to the surface where the shadow is observed. Although in the above experiment it appears that the edge of the shadow of an object is sharply defined, in fact this is not the case. In addition to the full shadow area, there is also a partial shade area. When a finger, approaching an object, blocks part of the rays falling into the penumbra region, an oncoming shadow appears on the screen. The merging of the shadow and the counter shadow with further downward movement of the finger occurs at the border of the penumbra and the illuminated part of the screen.

By measuring the distances between the object and the screen, between the finger and the object, and the size of the oncoming shadow in front of the direct shadow, we can estimate the angular size of the Sun based on simple geometric considerations.

G. Solovyanok

Fig. 5.

F516. A heavy disk of radius R rolls on two inextensible threads wrapped around it. The free ends of the threads are secured (Fig. 7). The threads are constantly engaged when the disk moves. At some point, the speed of the disk is $\omega$, and the speed between the threads is $\alpha$. What is the speed of the center of the disk at this moment?

Consider the movement of the points $c$ and $d$, at which they touch the disk, in a coordinate system whose origin coincides with the point $O$, at which the center of the disk is located, when the angle between the threads is $\alpha$, and the axes $OX$ and $OY$ make an angle $\alpha$ with each other and are parallel to the threads (Fig.7). In this coordinate system (as in any fixed system), the velocities of the point $c$ and $d$ are equal, respectively

$$v_c = v_0 + v_{c0}, \quad v_d = v_0 + v_{d0}.$$

where $v_0$ is the speed of the disk center, $v_{c0}$ and $v_{d0}$ are the velocities of points $c$ and $d$ relative to the center of the disk. Obviously, $|v_{c0}| = |v_{d0}|$, and at the angular speed of rotation of the disk $\omega$

$$|v_{c0}| = |v_{d0}| = \omega R = u.$$

From the condition of inextensibility of the threads it follows that, when they form an angle $\alpha$, the projections $v_{dx}$ and $v_{cy}$ of the velocities $v_d$ and $v_c$ on the axis $OX$ and $OY$ are equal to zero:

$$v_{dx} = v_{0x} - u = 0, \quad v_{cy} = v_{0y} - u = 0.$$

From here

$$v_{0x} = v_{0y} = u.$$

This means that the vector $v_0$ of the speed of the disk center is directed
