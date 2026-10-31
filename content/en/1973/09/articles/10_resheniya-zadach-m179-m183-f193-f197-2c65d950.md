---
id: 1973-9-resheniya-zadach-m179-m183-f193-f197-2c65d950
issue: kvant_1973_9
year: 1973
number: "9"
title: Solutions to problems M179—M183; F193—F197
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 29
page_last: 39
page_labels: 27, 28, 30, 31, 32, 33, 34, 36, 37
tag: MP96
lang: en
source: kvant_digital
extraction: vision
content_sha256: 85d8019dca56c0ec3439e3b0beb2b23ee095872cd041faa75caaea18d133e911
prompt_sha256: draft-1
translated_from: content/ru/1973/09/articles/10_resheniya-zadach-m179-m183-f193-f197-2c65d950.md
source_content_sha256: f25b808aad68a4139c0b2a1d9811d574fccfae0cada82efd14ec7d82278299eb
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 27⟧

Problem solutions
M179—M183; F193—F197

M179. For each non-direct useful triangle $T$ we denote by $H(T) = T_1$ the triangle whose vertices are the bases and heights of the triangle $T$; through $T_2 = H(T_1)$ a triangle, the vertices of which are the bases of the triangle $T_1$; let further $T_3 = H(T_2)$, $T_4 = H(T_3)$, ...

What should the angles of triangle $T$ be in order to
a) was the triangle $H(T)$ acute?
b) in the sequence $T_1, T_2, T_3, \dots$ we draw a right triangle $T_n$ (in this case $H(T_n) = T_{n+1}$ is not defined)?
c) was triangle $T_1 = H(T)$ similar to triangle $T$?
e)* for each $n = 1, 2, 3, \dots$ we indicate how many dissimilar other triangles $T$ exist for which $T_n$ is similar to $T$.

Let $AA_1, BB_1$ and $CC_1$ be the altitudes of triangle $T$. The angles $\alpha_1, \beta_1, \gamma_1$ at the vertices $A_1, B_1, C_1$ (respectively) of the triangle $A_1B_1C_1$ are expressed in terms of the angles $\alpha, \beta, \gamma$ at the vertices $A, B, C$ of the triangle $ABC$ as follows:

$$\alpha_1 = \pi - 2\alpha, \quad \beta_1 = \pi - 2\beta, \quad \gamma_1 = \pi - 2\gamma,$$

(11)

Fig. 1.

Fig. 2.

⟦folio 28⟧

s ($\alpha, \beta, \gamma$). It is clear that we can only consider the case
$$\alpha \geqslant \beta \geqslant \gamma$$
(2).

The angles of any triangle can be denoted by the letters $\alpha, \beta$ and $\gamma$, so that inequalities (2) are satisfied.

If $\alpha < \frac{\pi}{2}$ (all angles are acute), then, since inequalities $2\pi - \alpha \leqslant 2\pi - \beta \leqslant 2\pi - \gamma$ follow from (2), for the similarity of triangles $T_1$ and $T$ the equality system must be satisfied
$$\pi - 2\alpha = \gamma, \quad \pi - 2\beta = \beta, \quad \pi - 2\gamma = \alpha,$$
where
$$\alpha = \beta = \gamma = \frac{\pi}{3}.$$

If $\alpha > \frac{\pi}{2}$, then from (2) we can only use the fact that $2\beta \geqslant 2\gamma$, and must consider three possible relationships between the angles $\alpha_1, \beta_1$ and $\gamma_1$: $2\beta \geqslant 2\gamma \geqslant 2\alpha - \pi, \quad 2\beta \geqslant 2\alpha - \pi \geqslant 2\gamma$ and $2\alpha - \pi \geqslant 2\beta \geqslant 2\gamma$. The first of these leads to the system
$$2\beta = \alpha, \quad 2\gamma = \beta, \quad 2\alpha - \pi = \gamma,$$
where we find an interesting solution:
$$\alpha = \frac{4\pi}{7}, \quad \beta = \frac{2\pi}{7}, \quad \gamma = \frac{\pi}{7},$$

and the other two, as is easy to check, lead to “expressed” solutions (one of the angles is formed at zero), which do not suit us, as they say, “do not fall within the range of permissible values.”

As readers interested in solving this problem write, for $n = 2, 3, 4$ and in general for any $n$ solutions can be obtained by a similar, but much more cumbersome search. Indeed, in principle we have reduced the problem to an algebraic one. Let us outline the possibility of a plan for further expansion (for an arbitrary natural $n$). From (1) by induction we can obtain formulas for the angles of a triangle

$$\begin{cases}
\alpha_n = s2^n & \alpha + p\pi \\
\beta_n = s2^n & \beta + q\pi \\
\gamma_n = s2^n & \gamma + r\pi,
\end{cases}$$

where $s$ is equal to $+1$ or $-1$, $p, q$ and $r$ are integers (prove that given $\alpha, \beta$ and $\gamma$ and with the additional condition $\alpha_n \geqslant 0, \beta_n \geqslant 0, \gamma_n \geqslant 0$, $\alpha_n + \beta_n + \gamma_n = \pi$ the parameters $p, q, r$, $s$ are determined from (3) uniquely!). Let's write six systems, equating ($\alpha_n, \beta_n, \gamma_n$) to different permutations ($\alpha, \beta, \gamma$), and solve each of them. From the solutions obtained (depending on the parameters $p, q, r, s$), we select those that satisfy the conditions $\alpha \geqslant \beta \geqslant \gamma$. To answer the question: how many solutions exist (for a given $n$), you will need to find out how many integer solutions $p, q, r, s$ (where $s = \pm 1$) have six resulting inequality systems. To implement this plan,

⟦folio 30⟧

“yes” answers: the number $n$ always turns out to be greater than or equal to the next $x$. It is clear that the next $x$ must be taken more than all those already used (otherwise this question will be the only one).

Thus, at the beginning of the game, you must notify $x$ all the time - until the person who made the wish says “no” for the first time. Let $x_1 < x_2 < x_3 < \dots$ be the sequence that the guesser decided to name until he receives the first answer “no”. It must be infinite, since $n$ can be as large as you like.

Let now the second game come: to the $k$th question, the one who asked for the first time answered “no”. Thus,

$$x_{k-1} \leq n < x_k.$$

Then you can apply a strategy similar to the strategy $S_n$ described above, dividing the remaining gap in half all the time. Obviously, this will require up to $|\log_2(x_k - x_{k-1})|$ questions.

Let’s assume that at the second stage of the game, that is, after the first answer “no,” we have and play like this. It remains to choose a monotonically increasing sequence $x_k$ to completely define the strategy.

Let's look at three specific strategies, differing only in the choice of the sequence $x_k$.

1. Strategy $T^1$: $x_k = 10k$. Then, as stated in the conditions, $f_T(n)$ grows approximately as much as $\frac{n}{10}$.

2. Strategy $T^2$: $x_k = 2^k$. Then the number of questions at the first stage is no more than $|\log_2 n|$, and the number of questions at the second stage is no more than $|\log_2 \frac{n}{2}|$. In total there are approximately $2\log_2 n$ questions.

3. Strategy $T^3$: $x_k = 2^{2k}$. Now the number of questions at the first stage has sharply decreased. In fact, let

$$2^{2k-1} \leq n < 2^{2k}.$$

Then the number of questions at the first stage of the game is equal to $k$ and does not exceed

$$k \leq \log_2 \log_2 n + 1,$$

which for large $n$ is significantly less than $\log_2 n$. In the second stage we will consume approximately

$$\log_2(2^{2k} - 2^{2k-1}) \approx \log_2 2^{2k} = 2^k$$

 questions. Is this good or bad? It depends on the number $n$. It turns out that for the most $n$ in the interval (2) this strategy is significantly better than for the most $n$ in the same interval.

Let $n = 2^{2k} - 1$.

Then

$$f_T(n) \approx \log_2 \log_2 n + 2^k \approx \log_2 n + \log_2 \log_2 n,$$

For large $n$, the second term is much smaller, and the ratio of $f_T(n)$ to the lower estimate $\log_2 n$ (see formula (1)) is close to 1.

Let now $n = 2^{2k-1}$. Then the value $f_T^3(n)$ is the same, and expressed through $n$ it is

$$f_T^3(n) \approx \log_2 \log_2 n + 2^k \approx 2\log_2 n + \log_2 \log_2 n,$$

that is, approximately two exceeds the lower estimate (1). Thus, for these values ​​of $n$, strategy $T^3$ is no better than strategy $T^2$.

This position is illustrated by the graph at figure 7. On this graph, the red line conventionally depicts the lower estimate proven above: $\log_2 n$ (the graph is of a qualitative, sketchy nature and does not pretend to be accurate).

The stepped black line represents the graph of the function $f_T^3(n)$. This function is constant on each interval of type (2). By the end of such an interval, the lower estimate almost catches up with it, but here $f_T^3(n)$, let’s say, is crippled and becomes approximately twice as large.

The question arises: is there a strategy $T^4$ for which $f_T^4(n)$ for all $n$ does not differ too much from the lower bound? (The estimated schedule $f_T^4(n)$ is given in the following paragraph.)

We now describe a strategy $T^4$ such that

$$\lim_{n \to \infty} \frac{f_T^4(n)}{\log_2 n} = 1,$$

that is, the relative excess of $f_T^4(n)$ over the lower bound $\log_2 n$ for large $n$ strategies to zero.

The first stage of the game, as preceded by a sequence of numbers

$$x_k = 2^{2k}.$$

Suppose we received the answer “no” to the $k$th question for the first time, where did

$$2^{2k-1} \leq n < 2^{2k}.$$

Let us describe the strategy $T^4$ for the second stage of the game. Let us assign $n$ to each in the interval (2)

Fig. 7.

⟦folio 31⟧

"weight" equal to $\frac{1}{n}$. We will now ask questions in such a way as to divide approximately in half not the number of values ​​that $n$ can still take, but the sum of their weights.

Let's calculate approximately how many questions it will take to debug an arbitrary $n$ in interval (2). Let's put $m=2^{2k-1}$. Initially, the sum of the weights is approximately equal to

$$\frac{1}{m} + \frac{1}{m+1} + \cdots + \frac{1}{m^2} \approx$$

$$\approx \left(1 + \frac{1}{2} + \cdots + \frac{1}{m^2}\right) -$$

$$- \left(1 + \cdots + \frac{1}{m}\right) \approx \ln(m^2) - \ln m =$$

$$= \ln m \leqslant \ln n.$$

If we guess $n$, then we will bring the sum of the weights to the value $\frac{1}{n} \cdot$, which means that the sum of the weights will decrease by approximately $n\ln n$ times. Let's assume that we manage to divide it exactly in half every time. Then it was spent

$$\log_2 n\ln n = \log_2 n + \log_2 \ln n \approx \log_2 n$$

Vortsov (the second term for large $n$ is significantly less than the first). Since, as a rule, it was not possible to accurately divide the sum of the weights in half, the number of questions is actually somewhat larger. It can be shown (but this is more difficult) that it still does not exceed

$$\log_2 n + \text{const}\log_2 \log_2 n$$

vortsov. (Here const means a constant number that we did not evaluate.) By adding here the number of questions in the first stage of the game, we only indicate the coefficient in the second term. Thus, we have built a strategy that allows us to debug any $n$ in no more than

$$\log_2 n + \text{const}\log_2 \log_2 n$$

vortsov.

It is easy to show that this function satisfies conditions (3), which we promised to fulfill.

J. M. Bardzin, A. L. Toom

**M 181. What is the minimum length of a piece of cork so that it can be used to form the frame of a cube with an edge of 10 cm?** (A cork can pass along one edge twice, depending on $90^\circ$ and $180^\circ$, but it cannot be broken.)

Answer. You need at least 150 cm of cork.

How, according to the cork frame, is of this length - shown in figure 8. Now we need to prove that the cork frame is less than the length of a cube with an edge of 10 cm?

(Let us assume for a moment that we are allowed to bend the cork only at the vertices of the cube, and that we have made some kind of frame, and the cork begins and ends

Fig. 8.

at the vertices of the cube. Let's count the number of edges in this frame. We, of course, will not count the edges of the cube - there are 12 of them - but the edges made of holes. In the frame there is exactly one vertex at which the hole begins and one at which the hole ends (these vertices may coincide). We will call these vertices end vertices, and all the rest - passing vertices. Each passing vertex is adjacent to an even number of edges. Indeed, a bug, having entered this vertex, must necessarily come out of it. Therefore, at least four ribs are adjacent to it. At least three ribs are adjacent to the terminal vertex. Therefore, the total number of edges is no less than $\frac{6 \cdot 4 + 2 \cdot 3}{2} = 15$. Indeed, each edge is adjacent to two vertices, so if a vertex with number $i$ is adjacent to $c_i$ edges ($i = 1, 2, \ldots, 8$), then $c_1 + c_2 + \ldots + c_8$ is equal to twice the number of edges. Thus, there are at least 15 ribs in the frame, and since the length of one rib is 10 cm, at least 150 cm of holes will be required.

Now we need to prove that if we bend the plugs at the internal points of the ribs, then it is still impossible to make less than 150 cm of frame plugs. This problem can be reduced to the previous one as follows: without notifying the length of the holes, any frame can be re-cut so that all the posts end up at the vertices. We will not describe this alternation, but will only show several pictures of it that appear (see Fig. 9, $a - \delta$; they depict a certain edge of the cube, and the hole covering it is expanded for clarity).

⟦folio 32⟧

Fig. 9.

$$\frac{a}{b+c+d} + \frac{b}{a+c+d} + \frac{c}{a+b+d} + \frac{d}{a+b+c} \geq \frac{4}{3};$$

c) $a_1, a_2, a_3, \dots, a_n$ - positive numbers ($n \geq 2$), can

$$\frac{a_1}{a_2+a_3+\dots+a_n} + \frac{a_2}{a_1+a_3+\dots+a_n} + \dots + \frac{a_n}{a_1+a_2+\dots+a_{n-1}} \geq \frac{n}{n-1}.$$

Let's solve problem (c) right away. We denote the sum $a_1 + a_2 + \dots + a_n$ by $s$, and the numbers $s - a_i$ by $b_i$. In this notation we need to prove that

$$\frac{s - b_1}{b_1} + \frac{s - b_2}{b_2} + \dots + \frac{s - b_n}{b_n} \geq \frac{n}{n-1}.$$

This inequality is equivalent to:

$$s \left( \frac{1}{b_1} + \frac{1}{b_2} + \dots + \frac{1}{b_n} \right) \geq \frac{n}{n-1} + n = \frac{n^2}{n-1}.$$

(1)

Let us now use the well-known relationship between the arithmetic mean and the geometric mean (see «Kvant», 1970, No. 8, p. 33): if $c_1, c_2, \dots, c_n$ are non-negative numbers, then

$$\frac{c_1 + c_2 + \dots + c_n}{n} \geq \sqrt[n]{c_1 c_2 \dots c_n}.$$

(2)

It immediately follows from this that

$$\left( \frac{1}{b_1} + \frac{1}{b_2} + \dots + \frac{1}{b_n} \right)^n \geq \frac{1}{b_1 b_2 \dots b_n}$$

and that $b_1 b_2 \dots b_n \leq \left( \frac{b_1 + b_2 + \dots + b_n}{n} \right)^n$.

From these two inequalities it follows that

$$\left( \frac{1}{b_1} + \frac{1}{b_2} + \dots + \frac{1}{b_n} \right)^n \geq \left( \frac{n}{b_1 + b_2 + \dots + b_n} \right)^n$$

and finally,

$$\frac{1}{b_1} + \frac{1}{b_2} + \dots + \frac{1}{b_n} \geq \frac{n^2}{b_1 + b_2 + \dots + b_n}.$$

But

$$b_1 + b_2 + \dots + b_n = ns - a_1 - a_2 - \dots - a_n = (n-1)s,$$

where

$$s \left( \frac{1}{b_1} + \frac{1}{b_2} + \dots + \frac{1}{b_n} \right) \geq \frac{sn^2}{s(n-1)} = \frac{n^2}{n-1}.$$

Inequality (1) has been proven.

Let us now present some messages with the help of which we can prove relation (2). Let $c_1 + c_2 + \dots + c_n = 1$. (This does not limit the generality.) Let us assume that for these numbers relation (2) is violated, that is

$$\frac{c_1 + c_2 + \dots + c_n}{n} < \sqrt[n]{c_1 c_2 \dots c_n}.$$

Let the averages of the numbers $c_i$ be unequal. Then in the middle $c_i$ there are two numbers - we can assume that these are $c_1$ and $c_2$ - such that $c_1 < \frac{1}{n}$, $c_2 > \frac{1}{n}$. Note $c_1$ on $c'_1 = \frac{1}{n}$, and $c_2$ on $c'_2 = c_1 + c_2 - \frac{1}{n}$. Then for numbers $c'_1 = \frac{1}{n}, c'_2 = c_1 + c_2 - \frac{1}{n}$, relation (2) will also be violated. The proof of this fact is evidenced by the inequality $\frac{1}{n} \left( c_1 + c_2 - \frac{1}{n} \right) > c_1 c_2$ (at $c_1 < \frac{1}{n}, c_2 > \frac{1}{n}$), - you can easily cope with this inequality yourself.

In proposing these substitutions, we must do the set $c_1 = c_2 = \dots = c_n = \frac{1}{n}$. Thus, if relation (2) is violated for some set $c_1, c_2, \dots, c_n$, then it will also be violated for the set $\frac{1}{n}, \frac{1}{n}, \dots, \frac{1}{n}$. However, by indefinite substitution we make sure that in this case it holds. This means that it is also true for the original set.

Here is another solution to our problem, based on the relationship between the average

⟦folio 33⟧

Fig. 10.

arithmetic and geometric mean for two numbers.
We must prove that
$$ (n-1) \left( \frac{s-b_1}{b_1} + \dots + \frac{s-b_n}{b_n} \right) \geq n. $$
Note that $b_1 + \dots + b_n = (n-1) s$. That's why
$$ (n-1) \frac{s-b_1}{b_1} = \frac{b_1 + b_2 + \dots + b_n - (n-1) b_1}{b_1} = \frac{b_2 + \dots + b_n}{b_1} - (n-2) = \frac{b_2}{b_1} + \frac{b_3}{b_1} + \dots + \frac{b_n}{b_1} - (n-2). $$
We also transform the remaining $(n-1) \frac{s-b_i}{b_i}$ terms and add all $n$ terms.

Then we group the fractions $\frac{b_i}{b_j}$ in pairs and use the inequality:
$$ \frac{b_i}{b_j} + \frac{b_j}{b_i} \geq 2 $$
Since the total pairs $i$ and $j$ ($1 \leq i < j \leq n$) will be
$$ C_n^2 = \frac{n(n-1)}{2}, $$
then as a result we get:
$$ (n-1) \left( \frac{s-b_1}{b_1} + \dots + \frac{s-b_n}{b_n} \right) \geq C_n^2 \cdot 2 - (n-2) n = n^2 - n - n^2 + 2n = n. $$
From both the first and second solutions it is immediately clear that the inequalities turn into equalities only at $b_1 = \dots = b_n$, that is, at $a_1 = \dots = a_n$
L. G. Limanov

Fig. 11.

M183. Find the height of a trapezoid whose bases are $a$ and $b$ ($a < b$), the angle between the diagonals is $90^\circ$, and the angle between the extensions of the side lines is $-45^\circ$.

Most readers submitted a solution to this problem using trigonometry. Here is one of the shortest solutions, sent by L. and S. Pizzkov.

Let (Fig. 10) in the trapezoid $ABCD$, where $AB \parallel CD$ $AB = a$, $CD = b$, $BC = x$, $AD = y$, the point $E$ based on $CD$ is such that $ABCE$ is a parallelogram: $AE = x$, $DE = b - a$. Twice the area of ​​triangle $ADE$ is
$$ xy \sin 45^\circ = (b - a) h, $$
(1)
where $h$ is the height of the trapezoid. Next, using the cosine theorem, we obtain that
$$ (b - a)^2 = x^2 + y^2 - 2xy \cos 45^\circ. $$
(2)
Finally, using the Pythagorean theorem applied to the four right triangles $AOB$, $BOC$, $COD$, $DOA$, we deduce that
$$ x^2 + y^2 = a^2 + b^2 $$
(3)
Let us now substitute (3) and (1) into (2) ($\cos 45^\circ = \sin 45^\circ$):
$$ (b - a)^2 = a^2 + b^2 - 2(b - a)h. $$
Thus,
$$ h = \frac{ab}{b - a}. $$

Our reader N.I. Berezovsky and some others give a method for constructing a trapezoid, which is discussed in the conditions, according to data a and b (Fig. 11). The study shows that such a trapezoid exists for $\frac{b}{a} \geq 1 + \sqrt{2}$.
N. B. Vasiliev

F193. There are two systems of lines with the same formation distances. The optical axes of the lines coincide. The first system of lines consists of collecting lines, in the second there are collecting lines through an angle with a scattering one. Named lines in each of the systems, if the distance between the lines is much higher than the formal one.

⟦folio 34⟧

Let us consider a parallel beam of rays running along the main optical axis of the system, consisting of collecting lenses. Having passed the first lens, the beam becomes converging, having passed the second - even more converging, and so on. If the number of lenses is large enough, then somewhere inside the system the beam is contained in a point. After this, the beam becomes divergent, but its divergence will become less and less until it becomes parallel; then everything will be repeated. Approximate course of rays dan at figure 12, a.

For the second case, when the system consists of alternating collecting and diverging lenses (see Fig. 12, b), the “period” of the ray trajectory is much greater than in the first case, since the actions of the collecting and diverging lenses on the light beam are opposite.

For determination, the distance between the lenses is taken equal to $1/3$ focal length. All discrepancies in principle remain the same both for an arbitrary beam and for other relationships between the focal length and the distance between the lenses.

F194. A charge is placed between the plates of a flat capacitor. How will it move if a sinusoidal voltage with an initial phase of $\varphi_0 = 0$ is applied to the capacitor?

Let the initial charge velocity be zero.

If a voltage $u = U_0 \sin \omega t$ is applied to the plane of the capacitor, then the direction of the field inside the capacitor changes with time according to the law $E = E_0 \sin \omega t$. Since the charge $q$ is acted upon by a force $F = Eq$ in an electric field, its acceleration

⟦folio 36⟧

at the moment when the elastic force of the wound spring becomes equal to the weight of the lower cube.

Or it can also be done so that the upper cube stops at the moment when the force of the elastic spring is less than the weight of the lower cube. Then the lower cube will stop in place, and it will be enough to consider the movement of only one upper cube.

Let us write down the law of conservation of energy for this case:

$$\frac{k(l_0 - l)^2}{2} = \frac{k(l_1 - l_0)^2}{2} + m_1g(l_1 - l)$$

($l_1$ is the maximum length of the spring).

From here

$$l_1 = l_0 - \frac{m_1g}{k} + \sqrt{\left(l_0 - \frac{m_1g}{k}\right)^2 + l\left(l - 2l_0 + \frac{2m_1g}{k}\right)}$$

The height of the upper cube is equal to

$$\Delta l = l_1 - l$$

and the center of mass of the system is

$$\Delta x_{\text{цм}} = \frac{\Delta l m_1}{m_1 + m_2}$$

F196. In the accelerator chamber, a very thin bundle of spring moves along a circle of radius $R$. The magnitude of the moka at the initial moment is $I_0$, the total number of particles in the chamber is $n$. The maximum flux through a constant beam orbit changes at a rate of $\varphi$. What will be the size of the moka after mine, when the particles make one revolution? The speed of the particle remains much less than the speed of light.

The magnitude of the current $I$ depends on the particle speed as follows:

$$I = en_0 v S$$

where $e$ is the spring charge, $n_0$ is the number of protons per unit volume, $S$ is the cross-sectional area of ​​the beam, $v$ is the speed. We will assume that the protons are uniformly distributed throughout their orbit, therefore (taking into account that the beam is very narrow)

$$n_0 = \frac{n}{2\pi RS}$$

Then

$$I = \frac{en}{2\pi R} v$$

Thus, to find the current, you need to find the speed of the springs. We know the initial speed. It is equal

$$v_0 = \frac{2\pi R I_0}{ne}$$

Since the magnetic flux in the accelerator chamber changes, it induces e. d. c. induction equal (in abscillot value) to the rate of change of magnetic flux $\varphi$, that is

$$E = \varphi$$

When the proton makes one revolution, the electric field will do work on it equal to $Ee$, which is affected by the change in the kinetic energy of the proton:

$$\frac{mv^2}{2} - \frac{mv_0^2}{2} = Ee$$

($m$ is the proton mass $^*$).

From here we find the speed of the proton after it makes one revolution in the accelerator chamber:

$$v = \sqrt{v_0^2 + \frac{2Ee}{m}}$$

Then the current in the chamber will be like this:

$$I = \frac{ne}{2\pi R} \sqrt{\left(\frac{2\pi R}{ne} I_0\right)^2 + 2\varphi \frac{e}{m}} = I_0 \sqrt{1 + \frac{n^2 e^3 \varphi}{2\pi^2 R^2 m I_0^2}}$$

I. Sh. Slobodetsky

F197. On a chalk of mass $m$, lying on the horizon of a rough surface with a spring coefficient $k$, at the moment of time $t = 0$ a force proportional to time began to act at an angle $\alpha$ to the horizon. Determine the speed $v$ of the body’s movement after t second.

Considering the body a material point, the distance of the force acting on it (Fig. 15). This is the gravitational force mg, the support reaction force $N$, the force $f = At$ (it is more convenient to talk about its components $f_1 = At$ cos $\alpha$ and $f_2 = At$ sin $\alpha$)

*) Since the speed of protons remains much less than the speed of light, the proton mass can be considered a constant value.

Fig. 15.

⟦folio 37⟧

and friction force $f_{\text{Tp}} = kN$. Horizontal acceleration of a body can only be imparted by force $f_1$, but for this it must become greater than the friction force $f_{\text{Tp}} = kN = k(mg - At \sin \alpha)$, which also depends on time $t$.

Let us construct graphs of the dependence of the horizontal forces acting on the body on time $t$ (Fig. 16).

From 0 to moment $t_1$ the body is not yet moving, since the static friction force balances the force $f_1$, that is

$$At_1 \cos \alpha = kmg - kAt_1 \sin \alpha,$$

where

$$t_1 = \frac{kmg}{A(\cos \alpha + k \sin \alpha)}.$$

There is also a second time limit $t_2$ for the movement specified in the task. At this moment, the ground reaction force becomes zero and the body rises

$$N = mg - At_2 \sin \alpha = 0$$

And

$$t_2 = \frac{mg}{A \sin \alpha}.$$

Thus, the movement of the body on the surface arose for time $\tau$, contained in the interval: $t_1 < \tau < t_2$.

Note that if $kA \sin \alpha \geq A \cos \alpha$, then the interval $t_2 - t_1$ becomes narrower, but all reasoning remains valid.

Let's write the equation of motion for the moment of time $\tau = t_1 + t'$ ($t'$ is the current time, absent from the moment $t_1$)

$$A (t_1 + t') \cos \alpha + kA (t_1 + t') \sin \alpha - kmg - ma,$$

where $a$ is the acceleration of the body.

Fig. 17.

Substituting the expression for $t_1$, we find

$$a = \frac{A \cos \alpha + kA \sin \alpha}{m} t'.$$

Let's draw a graph of the dependence $a(t)$ (Fig. 17). The desired speed $v$ at moment $\tau = t_1 + t'$ is numerically equal to the area of ​​the selected triangle:

$$v = \frac{a(\tau - t_1)}{2} = \frac{(A \cos \alpha + kA \sin \alpha)(\tau - t_1)^2}{2m} = \frac{[\tau A(\cos \alpha + k \sin \alpha) - kmg]^2}{2mA(\cos \alpha + k \sin \alpha)}.$$

If you change the direction of the acting force, as shown in figure 18, then the support reaction force $N = mg + At \sin \alpha$ will continuously increase (as will the friction force $f_{\text{Tp}}$).

The time $t_1$, after which the body moves, is found from the condition

$$At_1 \cos \alpha - kmg - kAt_1 \sin \alpha = 0;$$

Then

$$t_1 = \frac{kmg}{A \cos \alpha - kA \sin \alpha}.$$

However, in this case, the positive value $t_1$ only occurred if $A \cos \alpha > kA \sin \alpha$. At $A \cos \alpha \leq kA \sin \alpha$ the time is $t_1 < 0$, and no movement happens.

An increase in the $f_2$ component can lead to the destruction of the body (this can happen before the time $t_1$). If the body does not collapse and $t_1$ has a finite value, then for the speed $v$ at moment $\tau = t_1 + t'$ we obtain the value:

$$v = \frac{[\tau A(\cos \alpha - k \sin \alpha) - kmg]^2}{2mA(\cos \alpha - k \sin \alpha)}.$$

A. V. Ustinova
