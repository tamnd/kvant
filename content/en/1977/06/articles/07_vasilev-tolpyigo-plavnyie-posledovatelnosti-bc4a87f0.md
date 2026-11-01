---
id: 1977-6-vasilev-tolpyigo-plavnyie-posledovatelnosti-bc4a87f0
issue: kvant_1977_6
year: 1977
number: "6"
title: Smooth Sequences
authors:
  - Васильев Н. Б.
  - Толпыго А. К.
rubric: osnovnye-stati
page_first: 32
page_last: 36
page_labels: 30-34
tag: 8MQ9
lang: en
source: kvant_digital
extraction: vision
content_sha256: 097674be88fb2d36ccda98342c773bd87682e15acc2849073cf185f80ee70030
prompt_sha256: draft-1
translated_from: content/ru/1977/06/articles/07_vasilev-tolpyigo-plavnyie-posledovatelnosti-bc4a87f0.md
source_content_sha256: 9d92c6b8e941d2b2e140b8e752b4ffb4dc45e547f08e53992ae3a77d246b92e6
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 30⟧

Smooth Sequences

In this note, we will discuss characteristic considerations that arose when solving problems where some local orphans are imposed on a sequence or function - it is forbidden to change sharply or rotate the circle - and it is necessary to estimate how large the oscillation as a whole may turn out to be.

Racing game and second differences

Probably many of our readers know the racing game described in the book by M. Gardner. "Mathematical Novels".

Let us recall the rules of the game. A more or less arbitrary curved area (track) is drawn on checkered paper; at one edge of the track, a point from the tart is placed for each player, and a line φ and sha is placed at the other edge. Motorists take turns making moves to one of the grid nodes, and changing the speed is only allowed by one: if the previous move was automatically $\overrightarrow{AB}$, then the next move $\overrightarrow{BC}$ is either exactly the same ($\overrightarrow{BC} = \overrightarrow{AB}$), or ends in one of the memories with $C$ nodes. You can only walk along segments that lie entirely within the track: the one who “got too fast” and flew out of bounds skips a move and starts at unit speed (the start is carried out in the same way, Fig. 1).

Compared to other games on checkered paper (for example, with “sea boom”), this game is remarkable not only for its closeness to the real situation -

ting, but also variety: after all, every new track is a new game.

Finding the most successful path on a difficult track is not an easy task. Such problems are very typical for optimal control theory, a relatively young and rapidly developing field of mathematics. We will not touch upon the general messages related to this theory, but will consider one specific task, the eyer game of “race”.

Problem 1. On checkered paper, on one horizontal line of the seed $l$, a segment $A_0A_1$ of length 1 (the side of one cell) is offset. It is necessary, starting with the emodog of the segment, to build a path in which:

1) each next step $A_kA_{k+1}$ is either the same as the previous one $\overrightarrow{A_kA_{k+1}} = \overrightarrow{A_{k-1}A_k}$, or differs from it by one unit in its rhili in i and z (unlike “races”, the speed of shift to the right always remains the same: 1 cell for each step);

2) the last segment $A_nA_{n+1}$ lies on the same spicy line as the first $A_0A_1$.

What is the highest height, given $n$, that the poppy path above the spicy l can rise to?

This task is, of course, easy to form without checkered paper. If we assume that the segments $A_0A_1$ and $A_nA_{n+1}$ are the segments [0, 1] and [$n, n+1$] of the axis $Ox$ (Fig. 2), then the path is completely

⟦folio 31⟧

is not determined by the sequence of coordinates $y_0, y_1, y_2, \dots, y_{n-1}, y_n, y_{n+1}$ of points $A_k = (k; y_k)$, and this sequence must satisfy the following conditions:

a) the difference between the differences $y_{k+1} - y_k$ and $y_k - y_{k-1}$ of neighboring members of the sequence, i.e. the second difference
$$y_{k+1} - 2y_k + y_{k-1} = (y_{k+1} - y_k) - (y_k - y_{k-1})$$
for each $k$, $1 \leq k \leq n$, does not exceed 1;

6) $y_0 = y_1 = y_n = y_{n+1} = 0$, and all other $y_k$ are integers. The problem asks what the most meaning of this sequence can be.

The path referred to in the first formulation is, in a sense, the “graph” of the sequence $\{y_k\}$. Next, we would start immediately with an algebraic formulation; it would be very useful to “invent” it: it helps to find and present the meaning of condition a).

Let's move on to solving the problem.

To satisfy conditions 1), the “top” of the broken line $A_m A_{m+1}$ must be horizontal. It is clear that only symmetric paths can be considered: if $A_m A_{m+1}$ is the topmost link, then the longer of the parts $A_1 \dots A_m$ and $A_{m+1} \dots A_n$ can be shortened by replacing it with a symmetric reflection of the other part relative to the middle of the perpendicular to the segment $A_m A_{m+1}$.

So, it is enough to consider only the area along the smoke (by allocating more than $n/2 - 1$ inclined steps to it) - the start-up will be exactly the same.

By the way, it is clear from here that for the even number $n$ the maximum height of rise - let’s denote it $h_n$ - will be the same as for the next odd number: $h_n = h_{n+1}$.

If you rise and fall at an angle $45^\circ$, then the maximum height, as is easy to check, will be $[n/2] - 1$. But this method will only work up to $n = 7$ (Fig. 3, a). figure 3b shows the path for $n = 8$, which goes up to height 4 (not $[8/2] - 1 = 3$).

Symmetrine messages will once again help us find the optimal path. It is clear that at first it is beneficial to increase the ascent speed as much as possible: $1 + 2 + 3 + \dots$; but - in order to have time to slow down - this can only be done until the middle of the ascent section [1; $m$] (Fig. 4, 5).

These messages can be strictly formatted like this. Let's estimate the differences between the sections simultaneous on both sides:

$$y_1 - y_0 = 0, \quad y_{m+1} - y_m = 0, \quad y_2 - y_1 \leq 1, \quad y_m - y_{m-1} \leq 1, \quad y_3 - y_2 \leq 2, \quad y_{m-1} - y_{m-2} \leq 2, \quad y_4 - y_3 \leq 3, \quad y_{m-2} - y_{m-3} \leq 3, \dots$$

Now, in order to obtain an estimate for the highest height $h_n$ of the rise, i.e. value $y_m - y_0 = y_{m+1} - y_0$, we need to add up the estimates of the first differences. Thus,

for $n = 4k - 2$ (e.g. $n = 18$, Fig. 4)

Fig. 2.

Fig. 3.

⟦folio 32⟧

$$h_n \leq 1 + 2 + \dots + (k - 1) + (k - 1) + \dots + 2 + 1 = k(k - 1);$$
for $n = 4k$ (e.g. $n = 20$, Fig. 5)

$$h_n \leq 1 + 2 + \dots + (k - 1) + k + (k - 1) + \dots + 2 + 1 = k(k - 1) + k = k^2.$$

It is clear - from the same figure - that these estimates are accurate, i.e. that such a lifting height can be realized. Specifically, $h_{18} = 20, h_{20} = 25$.

So, we have found the highest height $h_n$ for any $n$. Check that the answer can be written in this compact form: $h_n = [n/4] \times [(n + 2)/4]$, or, even shorter, $h_n = [[n/2]]^2/4$. (Recall that $h_{n+1} = h_n$ for even $n$.) Hence, for any $n$ a sufficiently accurate upper bound for $h_n$ is given by the inequality $h_n \leq n^2/16$.

Let us also note that the vertices of the optimal trajectory in each of its fourth parts lie on the same parabola. This doesn't happen by accident. After all, if the sequence $x_0, x_1, \dots, x_m$ is an arithmetic progression (in part, a segment of the natural series), and the sequence $y_0, y_1, \dots, y_m$ has equal second differences $y_{k+1} - 2y_k + y_{k-1}$, then the points $(x_0; y_0), (x_1; y_1), \dots, (x_m; y_m)$ lie on the same parabola*). This is exactly the situation in our case (Fig. 4, 5): in the first and last quarters of the trajectory $y_{k+1} - 2y_k + y_k-1 = 2y_k + n^2/16$.

*) Wed. «Kvant», 1973, No. 2, p. 28-29.

$+y_{k-1} = 1$, and in the middle quarters $y_{k+1} - 2y_k + y_{k-1} = -1$.

We will see that in other problems where restrictions are imposed on second differences, the optimal trajectory is also glued together from a parabola.

Continuous analysis.
Speeds and accelerations

Task 2. Electrical replacement in urine $O$, skipping from a place, but having given a “reverse”, after $n$ seconds it returned again in urine $O$ and remained in it. What is the maximum distance $h$ that he can move away from the urine $O$ during this time, if the absolute value of his acceleration at no time exceeds a cm/sec$^2$?

This problem is a complete analysis of 1, with the difference that instead of a discrete sequence $y_0, y_1, \dots, y_n$ now solve for the function $y(t)$ continuously in it the argument $t$ (here $t$ is time; we will assume that $t$ runs the segment from 0 to $n$). The analogue of the first differences is speed (the first product is $y'(t)$ of the coordinate $y(t)$), the analogue of the second differences is acceleration (the second product $y''(t) = (y'(t))'$). We will solve this problem using physical terms; those who are already familiar with derivatives and integrals will easily translate the conditions of the problem and its solution into the language of mathematical analysis.

Let us prove that the answer to this problem is: $an^2/16$ (cm).

⟦folio 33⟧

Let the electric locomotive access the furthest position $M$ from point $O$ at some point in time $m$, $0 \leqslant m \leqslant n$. It is clear that its speed at this moment is zero. We can assume that $m \leqslant n/2$ (in the case of $m > n/2$ we will monitor the movement of the electric locomotive in the time interval from $m$ to $n$, and not from $0$ to $m$ - after all, before and after the moment $m$ the movement will occur in a completely similar way).

Let us estimate the speed of the electric locomotive $v(t)$ at $0 \leqslant t \leqslant m$. Since $v(0) = 0$, then $v(t) \leqslant at$. On the other hand, since $v(m) = 0$, then $v(t) \leqslant a(m-t)$. It follows that displacement $h = |OM|$—the area under the velocity graph $v(t)$ on the time interval $[0, m]$—does not exceed the area of ​​a triangle with base $m$ and height $am/2$, i.e. $h \leqslant am^2/4 \leqslant an^2/16$. It is clear that this estimate is exact, and the graph of the optimal displacement in each quarter of the segment $0 \leqslant t \leqslant n$ is a parabola (Fig. 6, a-c).

We see that for the “continuous” option (task 2) the answer and solution are simpler than for the “discrete” option (task 1).

Most implementations of optimal control problems, when formulated mathematically, also allow for both continuous and discrete options. However, continuous models are usually easier to study theoretically, and the results are more beautiful in form. But sometimes the discreteness of the problem is discrete in nature or simplifies the correct formulation of the mathematical problem; and for calculations on digital computers one usually has to switch to some discrete approximation of a continuous problem.

In the next paragraph we will return to the discrete problem, but now the sequence numbers will be located on a circle.

Numbers on a circle.
Formulation of the result

Task 3. There are $n$ real numbers on a circle, one of which is equal to 1, and the sum of all is equal to 0. Prove that:

a) find two adjacent numbers that differ by at least 4/n;
b) find a number that differs from the arithmetic mean of its two neighbors by at least $16/n^2$.

Next, we will very briefly present a solution that allows us to obtain for each $n$ point in the estimates in statements a) and b). These best estimation possibilities are:

a) the maximum of the differences between neighboring numbers is not less than $\frac{4}{n}$ if $n$ is even, and not less than $\frac{4n}{n^2-1}$ if $n$ is odd (note that $\frac{4n}{n^2-1} > \frac{4}{n}$);
b) the maximum deviation of a number from the arithmetic mean of its two neighbors is not less than the corresponding $\frac{16}{n^2}, \frac{16n}{n^3+n-2}$, $\frac{16}{n^2+4}$ or $\frac{16n}{n^3+n+2}$, if $n$ gives a remainder of 0.1, 2 or 3 when divided by 4.

Figures 7 and 8 show the optimal sequences (at $n=30$):

⟦folio 34⟧

for a sequence on figure 7, the difference between any two adjacent numbers is not less than 2/15 (this is 4/n for n=30); for the sequence on figure 8, the deviation of each number from the arithmetic mean of two neighbors is not less than 2/113 and, as in the first problem, the points in each quarter of the segment lie on the same parabola. We will carry out the proof of results a) and 6) below the fox for n=30 (for other n it is approximately the same). Thus, we will obtain a solution to the cycle of problems M398 from the “Problem Book «Kvant»”).

Let us denote these numbers by $y_{-14}, y_{-13}, \dots, y_{15}$ so that $y_0=1$. For problem a) it is not difficult to obtain the required estimate: if $|y_{k+1}-y_k| \leq \alpha$ for all $k=-14, \dots, 15$, then, summing up the estimates of the differences, as in Problem 1, we obtain $y_k \geq 1-|k|\alpha$. But the sum of $\Sigma y_k$ is zero, so

$$0 = \Sigma y_k \geq 30 - 2(1+2+\dots+14)\alpha - 15\alpha = 30 - 15^2\alpha,$$

whence $\alpha \geq 2/15$.

Let's move on to task 6). Note that in the line $\frac{y_{k+1}+y_{k-1}}{2}-y_k$ we need to evaluate are simply the “second difference” positions $(y_{k+1}-y_k)-(y_k-y_{k-1})$.

Normalization and repetition. Let's try using a two-step application of problem a).

Let $y_{k+1}-y_k=y'_k$, $\max_k |y'_k|=\alpha^{**}$. According to a), $\alpha \geq 2/15$. To the sequence $z_k=y'_k/\alpha$ we can again apply a) (it is easy to verify that the sum of all 30 numbers $z_k$ is equal to zero and that the maximum of $z_k$ is equal to one); therefore $\max_k |z_{k+1}-z_k| \geq 2/15$, and therefore

$$\max_k \frac{|y_{k+1}-2y_k-y_{k-1}|}{2} = (\alpha/2) \max_k |z_k-z_{k-1}| \geq (1/15)\alpha \geq 2/225.$$

This estimate is approximately worse than the required one (in the general case, the same estimate will be $8/n^2$ together with $16/n^2$).

The idea of ​​a more refined estimate is simple: it is necessary, based on the estimate $|y_{k+1}-2y_k+y_{k-1}| \leq 2\beta$ for the second differences, to more accurately estimate the first differences, then to estimate the numbers themselves $y_k$ (using the fact that $y_0=1$) and, finally, from the equality $\Sigma y_k=0$ to obtain an estimate for β.

Symmetrization and combination of estimates. Before moving on to the implementation of our plan, we note that we can limit ourselves to considering only symmetric sequences: those for which $y_k=y_k-1$. Indeed, from any sequence $y_k$ satisfying the condition $y_0=1$, $\Sigma y_k=0$, $|y_{k+1}-$

*) See «Kvant», 1976, No. 8.

**) Here and below k the value $-14 \leq k \leq 15$ runs through. For k=15 we assume $y_{k+1}=y_{-14}$, because the number adjacent to $y_{15}$ on the circle is $y_{-14}$.

$-2y_k+y_{k-1} \leq 2\beta$, we can obtain a symmetric sequence $z_k = \frac{y_k+y_k-1}{2}$, which, as is easy to verify, satisfies all these conditions. (In our notation $y_0=y_{-0}=y_{15}=y_{-15}=1$.)

Now we have:

$$y_0-y_1=(2y_0-y_1-y_{-1})/2 \leq \beta, y_{14}-y_{15} \leq \beta, y_1-y_2 \leq 3\beta, y_{13}-y_{14} \leq 3\beta, y_2-y_3 \leq 5\beta, y_{12}-y_{13} \leq 5\beta,$$

$$y_6-y_7 \leq 13\beta, y_7-y_8 \leq 15\beta, y_8-y_9 \leq 13\beta,$$

From the first seven inequalities we find

$$y_k \geq 1-k^2\beta$$ at $0 \leq k \leq 7$;

from the rest

$$y_k \geq 1-(7^2+8^2)\beta+(15-k)^2\beta$$ at $7 \leq k \leq 15$. Summing up all $y_k$ (recall that $y_k=y_{-k}$), we find $0 \geq 30-15(7^2+8^2)\beta$, hence $\beta \geq 2/113$.

In conclusion, there are several tasks, in one way or another relative connection with those discussed above.

1. In the sequence $a_0, a_1, \dots, a_n$, the numbers $a_0$ and $a_n$ are equal to zero, and the pattern of the difference between each number and the arithmetic mean of its two neighbors does not exceed one. Prove that $a_k \leq k(n-k)$.

2. It is known that $a_0, a_1, \dots, a_n$ > $a_k$, and $a_k+1=3a_k-2a_k-1$ for all $k>1$. Prove that $a_{100}>2^{99}$.

3. Given the number $a_1, \dots, a_7$. It is known that their sum is zero and that the lowest of them in terms of abscylotic value is $a_1=2$. Estimate the maximum abscillometric value of the second differences.

4. Given a certain set of numbers $a_1, \dots, a_n$. It is known that

$$0 \leq a_1 \leq a_2 \leq 2a_1,$$

$$0 \leq a_2 \leq a_3 \leq 2a_2,$$

etc. Prove that the sum $S=\pm a_1 \pm a_2 \pm \dots \pm a_n$ could have a sign so that the inequality $0 \leq S \leq a_1$ holds.

5. a) Let $x_0, x_1, \dots, x_n$ and $y_0, y_1, \dots, y_n$ be two sequences such that their “second differences” are constant: $x_{k+1}-2x_k+x_{k-1}=a, y_{k+1}-2y_k+y_{k-1}=b(1 \leq k \leq n-1)$. Prove that the points $(x_0;y_0), (x_1;y_1), \dots, (x_n;y_n)$ lie on the same parabola in the plane $Oxy$.

6) Prove that the points $(x;y)$, where $x=a_1t^2+b_1t+c_1, y=a_2t^2+b_2t+c$, lie on the same parabola.

7. Let the function f be periodic with period T, have the first (a in task 6) and the second (derivative, not discontinuous) periodic, except for a finite number of points; f is continuous on [0, n].

8. Let f be defined on the interval [0, n], $f(0)=f(n)=0$. What is the maximum value that f can reach if a) $f'(x) \leq M_1$, 6) $|f''(x)| \leq M_2$? (Derivatives are continuous except for a finite number of points; f is continuous on [0, n].).

9. Let the function f be periodic with period T, have the first (a in task 6) and the second (derivative, not discontinuous) periodic, except for a finite number of points; f is continuous on [0, n].

10. Let f be defined on the interval [0, n], $f(0)=f(n)=0$. What maximum value can hardness f have if a) $f'(x) \leq M_1$, 6) $|f''(x)| \leq M_2$? (Derivatives are continuous except at a finite number of points; f is continuous on [0, n].)
