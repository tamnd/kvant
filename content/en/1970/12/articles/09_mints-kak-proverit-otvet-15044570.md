---
id: 1970-12-mints-kak-proverit-otvet-15044570
issue: kvant_1970_12
year: 1970
number: "12"
title: How to check the answer
authors:
  - Минц Р. Г.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 52
page_last: 61
page_labels: 50, 51, 52, 53, 54, 56, 57, 58, 59
tag: F98E
lang: en
source: kvant_digital
extraction: vision
content_sha256: a77f29b9c65d67fdf191dc32590e7eeefa507529c1e7f120e0a6517bc6ed4f08
prompt_sha256: draft-1
translated_from: content/ru/1970/12/articles/09_mints-kak-proverit-otvet-15044570.md
source_content_sha256: 7328aaff74241cc8f3ba2f92ac8566b35f891bfdb18af9583f5e2b31a9f113dd
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 50⟧

HOW TO CHECK ANSWER

Probably, after a seemingly exhaustive solution to a problem, everyone sometimes gets the mistake that something is still wrong here. This state of mind is especially natural if the problem is fundamentally new or if the solution was cumbersome. What should you do in this case? How can you at least make sure that the answer is not completely incorrect? The most natural way to self-test in such a situation is to examine the answer. Let us note right away that there is no universal scheme for this. We can only highlight a few relatively common cases.

Pozny our story is structured as follows. First of all, four tasks are formulated. For each problem three answers are given, two of which are incorrect. We will try, without solving the problem, to determine which answer is correct. Solutions are provided at the end of the article.

Problem 1. The car passed the first level of the track at a speed of $v_1$, and the second - at a speed of $v_2$. What is the average speed automatically?

Omyems:

1) $v_{cp} = \frac{v_1 + v_2}{2v_1v_2}$.
2) $v_{cp} = v_1 + \frac{v_1v_2}{2(v_1 + v_2)}$.
3) $v_{cp} = 2\frac{v_1v_2}{v_1 + v_2}$.

The first test an answer must pass is its dimensionality. Obviously, in case 1) the situation is unfavorable in this regard. The answer has the dimension of inverse velocity $\left(\frac{cek}{cm}\right)$. Let us show that the second answer is also incorrect. Let's try to understand what's going on. For this purpose, the list is

Fig. 1.

Let's look at the conditions of the problem again. It is easy to see that in relation to the question posed, the speeds $v_1$ and $v_2$ are equal, that is, it is not clear which part of the path is automatically with the speed $v_1$, and which one with the speed $v_2$. This means that replacing $v_1$ with $v_2$ and $v_2$ with $v_1$ should not change the answer. In this case, they say that it is symmetrical with respect to $v_1$ and $v_2$. Having made the indicated replacement in the second answer, we get

$v_{cp} = v_2 + \frac{v_1v_2}{2(v_1 + v_2)} \neq v_1 + \frac{v_1v_2}{2(v_1 + v_2)}$.

Thus, the third answer is correct.

Problem 2. Two weights with masses $m_1$ and $m_2$ are suspended on a thread and thrown over a block (Fig. 1). Counting

⟦folio 51⟧

threads and block weightless and neglecting friction, determine the acceleration of the loads $a_1$ and $a_2$ and the tension of the thread $T$.

Answers:
1) $a_1 = \frac{m_1 - m_2}{m_1 + m_2} g$;
$a_2 = \frac{m_2 - m_1}{m_1 + m_2} g$; $T = 2 \frac{m_1 m_2}{m_1 + m_2} g$.
2) $a_1 = \frac{m_1 - m_2}{m_1} g$; $a_2 = \frac{m_1 - m_2}{m_1} g$;
$T = 2 \frac{m_1 m_2}{m_1 + m_2} g$.
3) $a_1 = \frac{m_1 - m_2}{m_1 + m_2} g$; $a_2 = \frac{m_2 - m_1}{m_1 + m_2} g$;
$T = (m_1 + m_2) g$.

We consider the direction indicated by the arrow at figure to be positive.

As in the previous problem, first of all we check the dimension. It is easy to verify that in all three cases the right and left sides of each formula have the same dimension. After that you can move on. Please note that if the weights $m_1$ and $m_2$ are swapped, then the tension of the thread will not change, that is, the expression for the tension force must be symmetrical with respect to $m_1$ and $m_2$. All answers pass this test as well.

It is easy to see that in the second case a mistake was made. Indeed, the weights $m_1$ and $m_2$ hang on the same thread. This means that if mass $m_1$ moves with acceleration $a_1$, then mass $m_2$ must move with acceleration $-a_1$ (kinematic connection), which is not true in the second answer.

So, we just have to make a choice between the first and third results. They differ only in the formula for the amount of thread tension. We will reason like this: let some mass, for example $m_1$, be equal to zero. It is quite obvious that in this case the second weight falls freely and the thread is not tensioned. The same result, of course, should also be obtained from

⟦folio 52⟧

3) $h = \cos^2 \alpha \frac{(Mv)^2}{2g(m+M)^2}$;

$Q = \frac{mv^2}{2} \frac{m \cos^2 \alpha + M}{M}$.

The first check, as always, is the dimension. However, let's not rush. How to do this quickly and easily? Let's reveal a little secret: it is much easier to see the dimension of the correspondence if you first transform it as follows: from the parameters included in the formula, you need to see dimensionless relationships, and do this in such a way that the remaining dimensional combination is as simple or familiar as possible.

This is exactly what the first answer looks like. Let's do a similar transformation for the second one:

$$h = \frac{(mv)^2}{2(m+M)} = \frac{mv^2}{2} \frac{m}{m+M};$$

$$Q = \frac{m^2}{2(m+M)} \left[ \left( \frac{M}{m} \right)^2 + v^2 \cos^2 \alpha \right].$$

Now we can see that both correspondences are incorrect. In the first case, the right part has the dimension of energy, and the left part has the dimension of length. In the second case, the sum of the dimensional $v^2 \cos^2 \alpha$ and dimensionless $\left( \frac{M}{m} \right)^2$ quantities is in parentheses, which should not be the case either. Using a similar transformation, make sure that the dimension of the third answer is correct. Unfortunately, unlike the two previous problems, there is no symmetry in the conditions. Let us therefore select a value of some parameter at which the answer is very clear, and check whether it can be obtained from our formulas. Let, for example, $\alpha = 0$. Then it is clear that the ball will not collapse, that is, the lifting height $h$ is zero, and all the kinetic energy will turn out to be $\frac{mv^2}{2}$ transferred to the body. Substituting the value $\alpha = 0$ into the first and third results, we get:

Fig. 3.

1) $h = 0$; $Q = \frac{mv^2}{2}$.

3) $h = \frac{v^2}{2g} \left( \frac{M}{m+M} \right)^2 \neq 0$;

$Q = \frac{mv^2}{2} \frac{m+M}{M} > \frac{mv^2}{2}$.

Thus the correct answer.

Let us also note that for self-test we can use the situation at $m = 0$ or $M \to \infty$. Try it yourself.

Task 4. A wooden cube on side $a$, whose density is $p$, floats in water. What will be the change in the depth of immersion of the cube $\Delta h$ if a layer of oil with a thickness of $l$ (Fig. 3) is poured onto the water? The densities of water and oil are $\rho_B$ and $\rho_M$ respectively.

Answers:

1) $\Delta h = \frac{\rho_M - \rho_B}{\rho} (a - l)$.

2) $\Delta h = \frac{l (\rho_B - \rho_M)}{\rho_B}$.

3) $\Delta h = l \frac{\rho_B + \rho_M}{\rho_M}$.

It is immediately clear that the dimensionality of all three answers is correct, and there is no symmetry in the problem.

Let's try to check our answers on some very unique case. If $l = 0$ (that is, there is no oil), then the immersion depth should not change ($\Delta h = 0$). It is clear that the first answer, from which

⟦folio 53⟧

case $l=0$ turns out to be $\Delta h = \frac{\rho_M - \rho_B}{\rho} a$, incorrect.

Let us now consider another possible situation. Let us assume that the density of oil is equal to the density of water. Obviously, in this case, the immersion depth of the cube will not change. The third answer, as is easy to see, does not satisfy this condition. Thus, the second answer is correct.

Now, perhaps, it’s time to draw some conclusions. How to research the answer?

We have already seen that first of all we need to make sure that the dimension is correct. It is best to do this in letter form, highlighting the corresponding dimensionless and dimensional components.

The next step is to study the symmetry of the problem. If any parameters are included in the condition equally, then they must be included in the response equally (symmetrically). Otherwise, the symmetry of the problem is easier to detect by the appearance of the answer itself. What does it mean? Imagine that the response under study is symmetrical with respect to some parameters of the same type (for example, two masses, two velocities, and so on). Then you need to check whether the problem conditions have the same symmetry. If not, then the answer is incorrect.

Another convenient way to check is as follows: the result obtained depends on the parameters of the problem (for example, mass, initial speed, angle, capacity, ...). We will try, by changing any parameter $x$, to reduce the problem to a known one or to one whose answer is very visible. Let's assume that we succeeded and we know the correct answer for $x = x_0$. Then the check consists of comparing this result with ours at $x = x_0$. Note that most often you have to resort to this method of verification. But in order to successfully apply it, you need to have a good understanding of the physical side of the problem,

Fig. 4.

Let us now present a detailed solution to the proposed problems.

Task 1. The average speed $v_{cp}$ is equal to $\frac{S}{t}$, where $S$ is the path, and $t$ is the time it took to cover this path.

$$t = \frac{S}{2v_1} + \frac{S}{2v_2} = \frac{S(v_1 + v_2)}{2v_1v_2}.$$

Substituting this expression for $t$ into the formula for $v_{cp}$, we get

$$v_{cp} = \frac{S \cdot 2v_1v_2}{S(v_1 + v_2)} = 2 \frac{v_1v_2}{v_1 + v_2}.$$

Task 2. Due to the fact that the thread is inextensible and weightless, $a_2 = -a_1 = a$ (kinematic connection) and the tension of the thread are the same everywhere (Fig. 4). Let us write down the equation of motion of the group:

$$-m_1a = m_1g - T$$ and $$m_2a = m_2g - T.$$

Solving this system for $a$ and $T$, we find

$$a = \frac{m_2 - m_1}{m_1 + m_2} g,$$

The law of temperament in the ball-bullet system is preserved.

⟦folio 54⟧

Fig. 5.

of impulse (amount of movement), we obtain $mv \sin \alpha = (M+m) v'$, where $v'$ is the speed of the bullet and the ball immediately after the bullet hits the ball (Fig. 5).

From the law of conservation of mechanical energy it follows that

$$\frac{(M+m) v'^2}{2} = (M+m) gh,$$

where

$$h = \frac{v^2}{2g} \sin^2 \alpha \left( \frac{m}{M+m} \right)^2.$$

The amount of heat released is equal to the difference between the initial kinetic energy of the bullet and the kinetic energy of the ball with the bullet after the bullet hits the ball:

$$Q = \frac{mv^2}{2} - \frac{(m+M) v'^2}{2} = \frac{mv^2}{2} \frac{m \cos^2 \alpha + M}{m+M}.$$

Task 4. A cube immersed in water and oil is subject to a buoyant force $F = \rho_M g l a^2 + \rho_B g x a^2$ (Fig. 6). This force must be equal to the force of gravity acting on the cube: $P = \rho g a^3$. Equating these two relations, we obtain $\rho_a = \rho_M l + \rho_B x$, whence the immersion depth is $h_1 = x + l = \frac{\rho a}{\rho_B} - \frac{l \rho_M}{\rho_B} + l$. If there is no oil

Fig. 6.

$(l=0)$, then the immersion depth is $h_0 = a \frac{\rho}{\rho_B}$. Thus, the change in immersion depth is equal to

$$\Delta h = h_1 - h_0 = l - l \frac{\rho_M}{\rho_B} = \frac{\rho_B - \rho_M}{\rho_B} l.$$

Now try to figure out on your own which of the answers is correct in the following problems.

1. A man of mass $m$ is on the bow of a boat that is floating on the water. Boat length $L$, weight $M$. The man moves to the stern. How far will $l$ and $b$ move the boat and the person relative to the shore?

Answers:

1) $l = \frac{L}{m+M}$, $b = \frac{LM}{m(M+m)}$;

2) $l = \frac{m}{m+M} L$, $b = \frac{M}{M+m} L$;

3) $l = \frac{M}{m+M} L$, $b = \frac{m}{m+M} L$.

2. A ball of radius $R$ and mass $m$ stands in front of the height step $h$ (Fig. 7). What is the minimum horizontal force that must be applied to the center of the ball for it to rise up the step?

Answers:

1) $F \geqslant mg \frac{\sqrt{h(2R-h)}}{R-h}$;

2) $F \geqslant mg \frac{\sqrt{h(2R-h)}}{R}$;

3) $F \geqslant mg \frac{2R-h}{R-h}$.

⟦folio 56⟧

To the task “Help the artist!”

Answer: 40 ways. Using black color 16 ways.

Indeed, we can draw a white line on a black background, or a black line on a white background, and in each of these ways we can tint the entire figure (or line and background) with any of the 8 combinations of the remaining colors (3 primary colors, each either included or not, $2^3=8$).

In other methods, the line and background must differ in exactly the same primary color (so that there are no two lines).

We get 24 ways. This can be proven, for example, like this. Let’s choose the primary color $X$, which differs between the line and the background; let's draw a white line on the background $X$ or a line of color $X$ on a white background (since there are three primary colors besides black, this figure can be made in 6 ways). There are four colors that do not contain the color $X$, namely: white, two other primary colors and one offset. Any of them can cover the entire figure. This gives $3 \cdot 2 \cdot 4=24$ more ways. And there are only 40 ways.

Check that on the cover the color transitions from the center of the concentric circles to the edge are consistent with one main color.

To the article “Once again, trying to figure out parameters”

1. a) If $a=b=0$, then $x$ is any real number other than 0 and 2;

if $a=\pm b \neq 0$, then there are no solutions;

if $a=\pm 3b$, then $x=\frac{1}{2}$;

if $a \neq \pm b$, $\pm 3b$, then $x_1=\frac{a+b}{a-b}$, $x_2=\frac{a-b}{a+b}$.

6) If $a \leq b$, then there are no solutions;

if $a>b$, then $x_1=a$, $x_2=b$.

b) If $b=0$, then for any $a$ there are no solutions;

if $a=0$, $b \neq 0$, then $x$ is any number except integers of the form $n\frac{a}{b}$ ($n=0; \pm 1; \dots$).

2. If $a=b=1$, then the solution is any pair $(x, y)$, where $x>0, y>0$;

if $0<a=b \neq 1$, then the solution is any pair $(x, y)$, where $x=y>0$;

if $ab=1, a \neq 1, a>0$, then the solution is any pair $(x, y)$, where $x>0, y=\frac{1}{x}$;

if $a \leq 0, b$ is any number or $b \leq 0$, $a$ is any number, then there are no solutions;

for other values ​​of $(a, b)$ we have $x=\frac{1}{b}, y=\frac{1}{a}$.

To the article “How to check the answer”

1. First of all, let's check the dimension of the proposed answers. It can be seen that the first answer has the wrong dimension. In order to choose between the second and third answers, we consider the limiting case $m=0$. If $m=0$, then obviously the boat should remain in place. This does not follow from the third answer; therefore the correct answer.

2. From the above formulas it is clear that they all have the correct dimension. It is also clear that there is no symmetry in the problem. Therefore, consider the case of $h=0$ and $h=R$. If $h=0$, then the minimum force is 0. Substituting this value into the formulas under study, for the third case we obtain $F \geq 2mg \neq 0$. If $h=R$, then no extremely large force applied to the center will lift the ball (Fig. 1). Satisfies this condition.

⟦folio 57⟧

Only the first answer is correct, which is correct. And indeed, at $h \rightarrow R$
$$F_{\min} = mg \frac{\sqrt{h(2R-h)}}{R-h} \rightarrow \infty.$$

3. As in the previous case, the dimensions of the answers are correct. Therefore, we will reason as follows. If $a=0$, then the force acting on the body is equal to its weight. Then it is obvious that the third answer is incorrect, because. $F(a=0)=0$. If the body falls freely, $a=-g$ and the force acting on it is equal to 0 (weightlessness). The first answer satisfies this condition.

4. It can be seen that all three answers pass the dimension test and the symmetrine problem with respect to $F_1$ and $F_2$. Check that when replacing $F_1 \rightarrow F_2$ and $F_2 \rightarrow F_1$ the answers transform into themselves.

Let's consider the case of identical lenses. It is clear that he is not distinguished by anything. However, for this case, the third answer results in an infinitely long focal length. Thus, the third result is clearly incorrect. If one lens were just a plane-parallel plate ($\phi$ocular distance of a plane-parallel plate $F_{\pi\pi}=\infty$, since a parallel beam of rays remains parallel, that is, is collected at infinity), then the system would actually be composed of one lens. Let's check whether this follows from our formulas: when $F_1 \rightarrow \infty$ we have to get that $F \rightarrow F_2$. This correspondence actually occurs for the second answer and is not true for the first, that is, the second answer is correct.

5. It can be seen that the dimension of all three answers is correct. Therefore, in order to find which answer is correct, consider the following cases: let the charges of the balls be equal, but opposite in sign: $q_1=-q_2$. Obviously, then, after connecting the balls, they will simply discharge, that is, their charges and potentials should turn to 0. Only the second and third answers satisfy this condition. In order to choose the correct one, consider the case when the balls are identical: $R_1=R_2$. It is clear that he is not distinguished by anything. On the other hand, in the second answer, the magnitude of the charges and the potential in this case turn to infinity. Thus, the third answer is correct.

Let us now give a detailed solution to the problems.

1. The momentum of a closed system does not change, and its center of mass remains at rest. Therefore, the center of mass of the human system - the boat in the coordinate system associated with water does not change when the person moves. Let us choose the origin of reference at the center of mass. Then it is clear that (Fig. 2) $l=2y$ and $b=2x$.

For $x$ and $y$ we have a system of equations

$$\begin{cases} x+y=\frac{L}{2}, \\ mx=My, \end{cases}$$

Fig. 2.

where do we get it from

$$x=\frac{L}{2} \frac{M}{m+M}, \quad y=\frac{L}{2} \frac{m}{m+M},$$

a $l=L \frac{m}{m+M}, \quad b=L \frac{M}{m+M}.$

2. We find the minimum horizontal force $F_1$ by equating the moments of force $F$ and force $P=mg$ relative to point 0. This gives

$$F(R-h) \geq P \sqrt{R^2-(R-h)^2},$$

$$F \geq mg \frac{\sqrt{h(2R-h)}}{R-h}.$$

3. We will assume that the acceleration is positive if it is directed upward. Then, in accordance with Newton’s second law, we have $ma=F-mg$, hence $F=m(g+a)$.

4. A beam of rays emerging from the focus of the first lens does not become parallel after passing through. Having passed the second lens, this beam is collected at its focus. Assuming that the system is equivalent to a lens with focal length $F$, we can write

$$\frac{1}{F}=\frac{1}{F_1}+\frac{1}{F_2}.$$

From here

$$F=\frac{F_1F_2}{F_1+F_2}.$$

5. After connection, both balls have the same potential f. From the definition of capacity we have $c_1=\frac{q'_1}{\varphi}$ and $c_2=\frac{q'_2}{\varphi}$; Taking into account the instructions for the problem, it follows that

$$\frac{q'_2}{R_2}=\frac{q'_1}{R_1}.$$

⟦folio 58⟧

On the other hand, $q'_1 + q'_2 = q_1 + q_2$ (charge law). Thus, to determine $q'_1, q'_2$ and φ we obtain a system of equations

$$\begin{cases}
q'_1 + q'_2 = q_1 + q_2, \\
\frac{q'_1}{R_1} = \frac{q'_2}{R_2}, \\
\varphi = \frac{q'_1}{c_1}.
\end{cases}$$

Solving it, we get

$$q'_1 = \frac{(q_1 + q_2)R_1}{R_1 + R_2}; \quad q'_2 = \frac{(q_1 + q_2)R_2}{R_1 + R_2};$$

$$\varphi = \frac{q_1 + q_2}{R_1 + R_2}.$$

Analysis of the “Case with the method of mathematical induction” (see «Kvant» No. 7, p. 37)

Let's put

$$P_n = \frac{1 \cdot 3 \dots (2n - 1)}{2 \cdot 4 \dots 2n} (n \geqslant 1).$$

So, proving the inequalities by mathematical induction

$$P_n < \frac{1}{\sqrt{n+1}}$$

And

$$P_n < \frac{1}{\sqrt{n}},$$

(Kolya V. encountered a curious obstruction that the inductive transition “from n to n+1” in case (1) easily coincides with checking the relation

$$\frac{P_{n+1}}{P_n} = \frac{2n+1}{2n+2} \leqslant \frac{\sqrt{n+1}}{\sqrt{n+2}},$$

while in case (2) a similar relation

$$\frac{2n+1}{2n+2} \leqslant \frac{\sqrt{n}}{\sqrt{n+1}}$$

false for any $n \geqslant 1$. Moreover, inequality (2) itself is a very visible consequence of inequality (1)!

First, let us understand that there is no formal contradiction here: the fulfillment of relation (4) is only sufficient for the validity of (2), but is by no means necessary.

Why does this happen nevertheless?

Consider the graphs of the function $y = P_x$ and $y = \frac{1}{\sqrt{x}}$ on the segment from $x=n$ to $x=n+1$ (the function $y = P_x$ is defined only at the ends of this segment).

Fig. 1.

The falsity of relation (4) implies the inequality

$$\frac{P_{n+1}}{P_n} > \frac{\sqrt{n}}{\sqrt{n+1}} = \frac{A_{n+1}B_{n+1}}{A_nB_n}.$$

In other words, the length of the segment $A_nB_n$ during the transition “from n to n+1” kills faster than the values ​​$P_n$ kill. And that's "bad."

Is it possible to change the function $y = \frac{1}{\sqrt{x}}$ so that the speed of this killing slows down?

Can. To do this, take, for example, the function $y = \frac{1}{\sqrt{x} + \alpha}$, where $\alpha > 0$. Indeed, it is not difficult to show that

$$\frac{A_{n+1}B'_n+1}{A_nB'_n} = \sqrt{\frac{n+\alpha}{n+1+\alpha}} > \sqrt{\frac{n}{n+1}} = \frac{A_{n+1}B_{n+1}}{A_nB_n}.$$

It was enough for Kolya to take $\alpha = 1$ for this replacement to work*).

Let us now solve the first problem: prove that

$$P_n < \frac{1}{\sqrt{3,1n}}.$$

Let’s immediately move on to the transition “from n to n+1”. Going to the lobby fails. Therefore, let’s replace the correct part with a more favorable expression*

*) The attentive reader probably noticed that there was also some luck here: the luck of the state is that the function $\frac{1}{\sqrt{x} + \alpha}$ not only kills slower than $\frac{1}{\sqrt{x}}$, but is also not located close to $P_x$.

⟦folio 59⟧

and select the values ​​$\alpha > 0$ so that the correspondence holds

$$\frac{2n+1}{2n+2} \leq \frac{\sqrt{3,1n+\alpha}}{\sqrt{3,1(n+1)+\alpha}},$$

or

$$\alpha \geq \frac{3,1(n+1)}{4n+3}.$$

The right side takes a maximum value of $\frac{3,1\cdot 2}{7} = 0,885\dots$ at $n=1$ (check). Consequently, for $\alpha = \alpha_0 = \frac{3,1\cdot 2}{7}$ the inductive transition reduces to the correct correspondence (6).

It remains to verify that for $n=1$ the auxiliary inequality

$$P_n < \frac{1}{\sqrt{3,1n+\alpha_0}}$$

right. By the way, why doesn’t this method of proof work in the case of a coefficient of 3.2?

Instead of proving the second inequality

$$\frac{1}{2^3} + \frac{1}{3^3} + \dots + \frac{1}{n^3} < \frac{1}{4}$$

we'll just point out that $A - \frac{B}{n^2}$ can often be used for successful rules, and leave it to you to find the appropriate coefficients $A$ and $B$.

By the way, “On two operations with real numbers” («Kvant» No. 8, p. 55)

1. Apply the method of mathematical induction.
2. Faithful. Due to the commutability of “addition” and “multiplication”, these correspondences are equivalent to formulas (2) and (3) given in the text.
3. $(a \otimes c) \otimes [(a \oplus b) \otimes c]$. Use formulas (2) and the first of formulas (5).
4. Rewrite the given value in the form $a \otimes [(a \otimes b) \oplus (a \oplus c)]$. Since $(a \otimes b) \oplus (a \oplus c) = [a \oplus (a \otimes b)] \oplus c = a \otimes c$ (see the second of formulas (5)), then, using the first of formulas (6), obtain the final expression min $(a, -a, -c)$.
5. Reduce the equality to the form $a \oplus b = a \otimes c$, that is, max $(a, b) = \min (a, -c)$. This correspondence can only take place for such real numbers $a, b, c$ that satisfy the condition $b \leq a \leq -c$.
6. This correspondence can be reduced to the form $a \oplus x = b$, or max $(a, x) = b$. If $a < b$, then $x = b$; if $a = b$, then you can take any $x \leq b$;

if $a > b$, then no real number has the required property.

To problems from the competition department of the magazine “Mathematics” («Kvant» No. 8, p. 57)

1. Let's assume that in the city $P$ there will be, for example, 6 planes taken out of $A_1, A_2, \dots, A_6$, and imagine a map of the state (Fig. 1). Since the distance between cities $A_1$ and $A_2$ must be greater than the distance from each of them to the city $P$, then the angle $A_1PA_2$ is greater than 60°. Likewise, angles $A_2PA_3, A_3PA_4, A_4PA_5, A_5PA_6, A_6PA_1$ are greater than 60°. But then the total angle around point $P$ will exceed 360°, which is impossible.

Fig. 1.

2. It is enough to prove that $l_ah_a + l_bh_b + l_ch_c \leq p^2$, where $h_a, h_b, h_c$ are the lengths of the altitudes of the triangle. As you know, Lina bisserrisa

$$l_a = \frac{2}{b + c} \sqrt{bcp(p - a)}$$

Using the inequality $b + c \geq 2\sqrt{bc}$, we obtain $l_a \leq \sqrt{p(p - a)}$. Similar to $l_b \leq \sqrt{p(p - b)}$, $l_c \leq \sqrt{p(p - c)}$. The last three inequalities and easily provable correspondences $h_a \leq l_a, h_b \leq l_b, h_c \leq l_c$ give $l_ah_a + l_bh_b + l_ch_c \leq l_a^2 + l_b^2 + l_c^2 \leq p(p - a) + p(p - b) + p(p - c) = p^2$.

3. Let's transform the original equation to the form

$$x^3\cos^2x - 2x(x + 1)\cos x \sin x + 2(x + 1)\sin^2x = 0.$$

Multiplying the left side by $x$ and isolating the perfect square, we arrive at the equivalent equation $[x^2\cos x - (x + 1)\sin x]^2 + (x - 1)(x + 1)\sin^2x = 0$. If the real number $\alpha$ is the root of this equation and at the same time $(\alpha - 1)\times(\alpha + 1) > 0$, then the equalities $\sin^2\alpha = 0, \alpha^2\cos\alpha - (\alpha + 1)\sin\alpha = 0$ must hold, which is possible only for $\alpha = 0$, but then $(\alpha - 1)(\alpha + 1) < 0$.
