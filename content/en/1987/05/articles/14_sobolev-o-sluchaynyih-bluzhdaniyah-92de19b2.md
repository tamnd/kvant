---
id: 1987-5-sobolev-o-sluchaynyih-bluzhdaniyah-92de19b2
issue: kvant_1987_5
year: 1987
number: "5"
title: About random walks
authors:
  - Соболев С. И.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 47
page_last: 50
page_labels: 45-48
tag: YQUU
lang: en
source: kvant_digital
extraction: vision
content_sha256: 7b6fe8e71585793909c826ff58fda12b535eb8b0be6ef25048abfb5421caec42
prompt_sha256: draft-1
translated_from: content/ru/1987/05/articles/14_sobolev-o-sluchaynyih-bluzhdaniyah-92de19b2.md
source_content_sha256: 7debb2e706e90d3f16db5e6954bd9423960b2d60c62dbb6d945961ca65b27ab8
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 45⟧

About random walks

Candidate of Physical and Mathematical Sciences
S. I. SOVOLEV

In a radio broadcast based on Gianni Rodari’s fairy tale “Cipollino and His Friends,” detective Mr. Carrot is searching for the recovered Cipollino according to the principle:

"Step back, step forward,
The robber will not leave us.”

This search principle could be considered a joke by the author if its effectiveness did not follow from a theorem of probability theory. Our note is related to this theorem and related problems.

Random walks through the wilderness

Let's mark the integer points on the line, take a coin and a chip. Let's imagine that at time 0 there is a token at point $a \in Z$. Let's toss a coin. If it lands as a coat of arms, move the chip 1 to the right, if it lands on tails, then move the chip 1 to the left. And then we throw the coin again and act according to this rule, etc. If the coin has no defects, then the chip, at the moment of time $t$ ($t = 0, 1, 2, \dots$) standing at point $k \in Z$, at the next moment of time $t + 1$ with probability 1/2 will end up at point $k + 1$ or with the same probability will end up at point $(k - 1)*$.

The described process is called a symmetric random walk over the set $Z$ of integer points on the line starting at the point $a$. This kind of walk is called symmetrical because the coin has a head and a tail that have equal rights.

Slightly clarifying the situation from the fairy tale by Gianni Rodari, we will assume that the detective Carrot, in search of Cipollino, performs a symmetric random walk through the set $Z$ (with the help of a coin).

*) Probability $p(x)$ of event $x$ is a certain numerical characteristic of the possibility of the occurrence of this event. The probability of an impossible event is taken to be equal to 0, of a reliable event to be equal to 1, and in general $0 \leq p(x) \leq 1$. In complex situations, probability is determined axiomatically, but in this note, axiomatic theory will be replaced by a small dose of common sense. In particular, if several events are equally possible, then their probabilities are the same; for example, the probability of getting a deuce (or a patter) on a non-cheating dice is, of course, 1/6, the probability of getting a head on a non-cheating coin is 1/2.

⟦folio 46⟧

Task 1. Take a coin and a chip, place the chip at point 0. Throw a coin, move the chip and write down its position. Repeat up to 10 times. As a result, you should get a string of sequential chip positions.

A specific walk can be visualized by drawing its trajectory. The position of the token at time $t$ at point $k$ will be marked by point $M_t$ with coordinates $(t; k)$ on a plane with a rectangular Cartesian coordinate system. By connecting the point $M_t$ with the point $M_{t+1}$ ($t = 0, 1, 2, \dots$) with an arrow, we get a visual image of the trajectory of the chip.

For example, if, when tossing a coin, $\Gamma, \Gamma, P, \Gamma, P$ was paid out in sequence, and the initial position of the chip was at point 0, then the successive positions are also:

| time | 0 | 1 | 2 | 3 | 4 | 5 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| chip position | 0 | 1 | 2 | 1 | 2 | 1 |

and the trajectory looks like shown in figure 1.

Task 2. Draw a trajectory depicting the walk of the chip from task 1.

Probability of hitting a given point

Let the token's walk along a straight line begin at point 0. An interesting question is with what probability at time $t$ the token ends up in position $k$. In other words, with what probability does the $t$-link trajectory arrive at the point $(t; k)$? Let us denote this belief $P_t(k)$. The answer to the question posed depends on the number $S_t(k)$ of trajectories leading from point $(0; 0)$ to point $(t; k)$.

Near each point $(t; k)$, at which at least one trajectory arrives, we write the number $S_t(k)$, showing how many trajectories lead to this point for $t = 0, 1, 2, 3$ (Fig. 2).

Task 3. Continue figure 2 for $t = 4, 5, 6$.

The following can be noted. Arrows can only go to point $(t; k)$ from points $(t - 1; k - 1)$ and $(t - 1; k + 1)$, and there is nowhere else. Therefore $S_t(k) = S_{t-1}(k-1) + S_{t-1}(k+1)$.

The table consisting of numbers $S_t(k)$, the beginning of which we drew, turns out to be the so-called Pascal triangle. It always, column by column, generates conditions $S_0(0) > 1$ and correspondence (1). For example:

$$\begin{align*}
S_1(-1) &= S_0(-2) + S_0(0) = 0 + 1 = 1, \\
S_1(1) &= S_0(0) + S_0(2) = 1 + 0 = 1, \\
S_2(-2) &= S_1(-3) + S_1(-1) = 0 + 1 = 1, \\
S_2(0) &= S_1(-1) + S_1(1) = 1 + 1 = 2, \\
S_2(2) &= S_1(1) + S_1(3) = 1 + 0 = 1,
\end{align*}$$

and so on.

Of course, there are twice as many $t$-link trajectories as $(t - 1)$-link ones - after all, each $(t - 1)$-link trajectory generates two $t$-link ones. Therefore, there are 2 single-link trajectories, 4 two-link trajectories, and so on, $t$-link trajectories – $2^t$.

All $2^t t$-link trajectories are equally possible trajectories of the movement of the chip (since head $\Gamma$ and tail $P$ are equally possible outcomes of tossing a coin), of which $S_t(k)$ trajectories come to point $(t; k)$. Therefore, the probability $P_t(k)$ with which the $t$-link trajectory arrives at the point $(t; k)$ is equal to $S_t(k)/2^t$. Near the point $(t; k)$, at which at least one trajectory arrives, we write down the probability $P_t(k)$. Let's call the resulting table a triangle of credences. Dividing equality (1) by $2^t$, we obtain the law

⟦folio 47⟧

$$P_t(k) = \frac{1}{2} P_{t-1}(k-1) + \frac{1}{2} P_{t-1}(k+1),$$

generating (using the conditions $P_0(0) \geq 1$) the entire probability triangle (Fig. 3).

Task 4. Continue the probability triangle $P_t(k)$ to the right, writing it out for $t = 4, 5, 6$.

Formula (2) takes into account that:

1) A piece can be in position $k$ at time $t$ only if it was in one of the neighboring positions $k - 1$ or $k + 1$ at time $t - 1$;

2) transitions from position $k - 1$ to position $k + 1$ or from position $k + 1$ to position $k$ occur with probabilities $1/2$ (positions before $P_{t-1}(k - 1)$ and $P_{t-1}(k + 1)$ and cost coefficients $1/2$).

The next two problems are intended for those who are familiar with certain number combinations and know the binomial formula.

Task 5. Prove that

$$P_n(k) = C_n^{\frac{n+k}{2}}/2^n,$$

another $C_n^m$ number of combinations of $n$ elements by $m$.

Task 6. a) Check for $t = 1, 2, 3, 4$ that the coefficient of $x^k$ in the expansion of the polynomial

$$\frac{1}{2^n} \left( x + \frac{1}{x} \right)^t$$

in powers $x$ is equal to $P_t(k)$. 6) Prove the statement of part a) for any natural number $t$.

Will Cipollino get caught?

Let there be a spratic Cipollino at point 0 on the straight line, and at point $k$ there is a Morkovu bridge. We assumed that the detective, looking for Cipollino, performs a symmetric random walk starting at time 0 at point $k$ on the line. With what probability will Morkova's master ever find Cipollino, i.e. will he end up at point 0?

Let's denote this probability $P(k)$. Like any probability, $P(k)$ is some part of one:

$$0 \leq P(k) \leq 1.$$

Note that $P(0) > 1$ (if $k = 0$, then already at time 0 the detective and Cipollino are at the same point,

remember - a reliable event, and its probability is equal to 1). If $k \neq 1$, then since from point $k$ the detective can ever get to point 0 only by going at the next moment of time after leaving point $k$ through neighboring points $k - 1$ and $k + 1$, the same law of half-sum turns out to be valid:

$$P(k) = \frac{1}{2} P(k - 1) + \frac{1}{2} P(k + 1).$$

Here it is taken into account that the transition per unit time from point $k$ to point $k - 1$ occurs with probability $1/2$; the same is true for moving from point $k$ to point $k + 1$.

Consider the points $M_k(k; p(k))$ on a plane with a right-angle Cartesian coordinate system $xOy$. Since the midpoint of the segment connecting points $(x_1; y_1)$ and $(x_2; y_2)$ is the point $\left( \frac{x_1 + x_2}{2}; \frac{y_1 + y_2}{2} \right)$, it is clear that the point $M_k$ (where $k \neq 0$) is the midpoint of the segment $M_k - 1M_k + 1$. Consequently, points $M_k$, where $k \geq 0$, lie on one ray, and points $M_k$, where $k \leq 0$, lie on one ray. Both of these rays come out from the point $M_0(0; 1)$ (since $P(0) > 1$) and lie in the strip $0 \leq y \leq 1$ (since $0 \leq P(k) \leq 1$ for any $k$) enclosed by figure 4. Therefore, they constitute the straight line $y = 1$. All points $M_k(k; P(k))$ lie on this line, so $P(k) \geq 1$ for any $k$.

So, we have proven that the detective will sooner or later find Cipollino with probability 1, no matter from which point $k$ he starts his wandering!

The reader may ask - what if, when throwing a coin, one always falls out, because then the detective will be to the right in a straight line and will not find any Cipollino? Of course, such a walk is logically possible, but the probability that a walk will occur that does not lead to point 0 is equal to 0. This is the theorem we have proven. The question of its application

⟦folio 48⟧

Random walks on a plane and in space

Consider a triangular mesh on the plane; Let's take a chip and an (undeformed) die. We will denote six directional movements on the grid by the numbers 1, 2, 3, 4, 5, 6 as shown in figure 5. Let's put a chip in one of the nodes of the grid and throw a die. Let's move the chip to the adjacent node in the direction corresponding to the indication of the bone. And then we throw the dice again and act according to this rule, etc. This process is called symmetric random walk on a flat triangular grid.

Suppose that Cipollino is hidden in one of the grid nodes, and the detective Mr. Morkovu performs random symmetric walks on the grid; will he find Cipollino? It turns out that in this case too the detective finds his victim with probability one. This is also a mathematical theorem from probability theory, known as “all roads lead to Rome.” We do not present its proof - it is somewhat more complicated than the proof of the theorem about a random walk on a line. The result will be the same for a flat square grid (instead of a regular dice you will have to use a “dice” in the shape of a regular terrahedron).

However, if we go to a cubic grid in space and similarly define a symmetric random walk on it (here again
Fig. 5.

Fig. 7.

If you use an ordinary dice - after all, six edges come out of each vertex of the cubic grid), then the result turns out to be completely different. If Cipollino hides far from the detective, then the probability of getting hit becomes negligible. This is already a difficult theorem; we will not say anything about its proof.

Two words about applications

The playful nature of this note should not mislead the reader. The theory of random walks is an important and very useful branch of probability theory. It is successfully used in the study of various development processes (in physics, chemistry and even in economics). Especially in recent years, when random processes are easily simulated on a computer using random number sensors. It receives effective and unexpected applications in the practical finding of solutions to specific differential equations using the so-called Monte Carlo method. But this is a subject for a separate story.

In conclusion, we propose two tasks.

Task 7. Cipollino will hide at point 0, at point N there is an abyss, and detective Morkov is at point k (k∈Z, 0<k<N). The detective quotes Cipollino in the same way. If he hits point 0, he will find Cipollino, and if he hits point N, he will fall into the abyss (Fig. 6). What is the probability of the detective finding Cipollino? How likely is it for a detective to fall into the abyss?

Hint: Prove that (in the original notation)

$$P(k) = \frac{1}{2} P(k-1) + \frac{1}{2} P(k+1),$$
