---
id: 1974-5-lyudmilov-lyudmilova-pravdopodobnyie-rassuzhdeniya-i-matematika-fbae6c89
issue: kvant_1974_5
year: 1974
number: "5"
title: Plausible Reasoning and Mathematics
authors:
  - Людмилов Д. С.
  - Людмилова С. Д.
rubric: raznoe
page_first: 45
page_last: 49
page_labels: 43-47
tag: J448
lang: en
source: kvant_digital
extraction: vision
content_sha256: 0fc7b7a724acd738e07a5942bce116c7b81eed5f64a8b0065fe3abd3e0840d55
prompt_sha256: draft-1
translated_from: content/ru/1974/05/articles/10_lyudmilov-lyudmilova-pravdopodobnyie-rassuzhdeniya-i-matematika-fbae6c89.md
source_content_sha256: af303c822711c19aa5cc96cb9bd9dfe75df1ebc5aa787d7c55f050e68e03b292
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 43⟧

Plausible reasoning and mathematics

D. S. Lyudmilov, S. D. Lyudmilova

“Having written that something is very indo, you probably thought so. But when, after a month, or two, or six, you are inside the manuscript and re-read it again, do you still continue to count? ...
When you owe it to a friend or at a seminar, was the place perceived as very indo? Or did anyone ask questions and ask the question after your notifications? Did you convince him or confuse him? Answers to these rhetorical questions are limited to the use of the word “obviously.” If there is another rule, the main thing is that we know it; Violation of this rule is the most common source of mathematical errors: making sure that the “obvious” is true.”
P. R. Halmos. How to write mathematical texts.

Plausible reasoning, prompted by intuition, plays a significant role in mathematical research, in the search for a solution to a problem. It would be more difficult for a mathematician to find solutions to new mathematical problems if he did not receive “hints” from his mathematical intuition.

The same can be said about a student who has a way to solve a problem. Finding a solution is the formulation of various hypotheses and their consistent mathematical testing.

No... be careful! Mathematical rigor should not be underestimated and intuition should not be overestimated. What is very intuitive is not always true.

Crossing

Let's look at one respectable example that demonstrates why mathematicians strive to rigorously prove the “obvious.”

There is such a problem in the book by P. Yu. Germanovich “Collection of problems in mathematics on communication” (M., Uchpedgiz, 1960).

The 3.5 m wide channel has a turn (Fig. 1). How to organize a crossing through it if there are two

Fig. 1.
Fig. 2.

⟦folio 44⟧

boards, but the length of each board is only 3 m?

The author's solution to the problem is shown in figure 2. Judging by this figure, the author assumes that

(1) edges A and B of the first board should rest against the edges of the ditch (we assume that the boards do not bend);
(2) the first board AB should form 45° angles with the edges of the ditch;
(3) the second board CD must be perpendicular to AB (point C is the vertex of the opposite corner of the ditch).
(4) any arrangement of boards of the specified dimensions is possible (and, therefore, ensures crossing).

All of these hypotheses are intuitively plausible, right? But... let's check it out.

First surprise

Let's start with hypothesis 4. It is very easy to believe in its validity: is it really impossible to get an insufficient 0.5 m (3.5 m - 3 m) using the extra 2.5 m (6 m - 3.5 m) of the board using the method indicated in figure 2?

However, let's do the calculations. From figure 2 we have:

$$OC = 3,5\sqrt{2} \text{ m}, \quad OD = \frac{1}{2}AB = 1,5 \text{ m},$$

$$CD = OC - OD = (3,5\sqrt{2} - 1,5) \text{ m}.$$

The crossing is possible if the inequality is satisfied

$$3,5\sqrt{2} - 1,5 \leq 3$$

Fig. 3.

Fig. 4.

or 3.5\sqrt{2} \leq 4.5, whence 7\sqrt{2} \leq 9, but this is incorrect. Therefore in reality CD > 3 m!

Does it follow from this that it is impossible to cross? Not yet, because this choice was made on the assumption that the first three hypotheses are satisfied. Perhaps there is another arrangement of boards that provides crossing?

Second surprise

From figure 3 it is clear that hypothesis 1 is correct: indeed, if one of the ends A of the first board (or both its ends) does not lie on the very edge of the ditch, then this board can be moved to a higher position.

It is not difficult to confirm hypothesis 3: if the second board CD is not perpendicular to AB (see Fig. 4), then it will have to be longer.

Fig. 5.

⟦folio 45⟧

Fig. 6.

It remains to test hypothesis 2.
At first glance, it seems that this hypothesis is confirmed. Indeed, consider two positions of the first board (Fig. 5): $MN$ ($\Rightarrow MNO = 45^\circ$) and $AB$ ($\Rightarrow ABO \neq 45^\circ$). Let $CD \perp MN$, $CP \perp AB$, $K$ be the intersection point of $CP$ and $MN$. It is clear that $CP > CD$, since $CP > CK$ and $CK > CD$ (the hypotenuse is greater than the leg).

However, the segments $MN$ and $CP$ may not intersect; the corresponding location of the board is indicated on figure 6. Please note that on this figure $CD \geq CP$. The previous reasoning does not work. Apparently, it is not easy to test Hypothesis 2 non-presidentially geometrically.

Let's try to do this algebraically. Let us denote the width of the channel by $a$, the length of each board by $l$ ($a > l$), $\Rightarrow ABO$ by $\alpha$ (Fig. 7) and we will consider the values ​​$a$ and $l$ constant, and the values ​​$\alpha$ variable. Hypothesis 2 states that the minimum length of the segment $CP$ ($CP \perp AB$) is achieved at $\alpha = 45^\circ$. Therefore, we need to express $y = CP$ as a function of $\alpha$.

Let's carry out $ECF \parallel AB$ and $OLK \perp AB$ (Fig. 7). Then

$$EF = EC + CF = \frac{a}{\cos \alpha} + \frac{a}{\sin \alpha}; \quad OF = EF \cos \alpha = a + \frac{a \cos \alpha}{\sin \alpha}; \quad OK = OF \sin \alpha = a \sin \alpha + a \cos \alpha; \quad OB = AB \cos \alpha = l \cos \alpha; \quad OL = OB \sin \alpha = l \cos \alpha \sin \alpha; \quad y = LK = CP = OK$$

$-OL = a \sin \alpha + a \cos \alpha - l \sin \alpha \cos \alpha$.

Let's examine the function $y(\alpha)$ for maximum and minimum. Let

$$x = \sin \alpha + \cos \alpha = \sqrt{2} \sin (45^\circ + \alpha).$$

Then $x^2 = 1 + 2 \sin \alpha \cos \alpha$,

$$\sin \alpha \cos \alpha = \frac{x^2 - 1}{2},$$

$$y(x) = ax - \frac{l(x^2 - 1)}{2} = \frac{-lx^2}{2} + ax + \frac{l}{2}.$$

If the domain of definition of the function $y(x)$ were not limited, then it would not have a minimum, but would have a maximum at $x = \frac{a}{l}$ (Fig. 8).

This maximum is equal to

$$\frac{1}{2} \left( -l \frac{a^2}{l^2} + 2a \frac{a}{l} + l \right) = \frac{a^2 + l^2}{2l}.$$

However, the domain of definition of the function $y(x)$ is limited, as are $x = \sqrt{2} \sin (\alpha + 45^\circ)$ and $0 \leq \alpha \leq 90^\circ$.

The function $x(\alpha)$ has a minimum of $x = 1$ at $\alpha = 0^\circ$ (this minimum is achieved when $\alpha = 0^\circ$—the board $AB$ is always on the same bearer) and a maximum of $x = \sqrt{2}$ at $\alpha = 45^\circ$. From here comes the definition of the function $y = f(x)$: $1 \leq x \leq \sqrt{2}^*$.

*) In fact, with $\alpha$, close to $0^\circ$ ($90^\circ$) and $AB$, less than $\alpha$, the point $P$ on figure 7 will be on the continuation $AB$, that is, on the bereru a board of length less than $CP$ will be required, but if the end $P$ of the board $CP$ lies on the bereru, then $CP$ is the smallest at $\alpha = 0^\circ$ and coincides with $y(x)$ at $x = 1$.

⟦folio 46⟧

Point $x = 1$ on the abscissa axis is always located between points $x = 0$ and $x = \frac{a}{l}$ ($a > l$). The point $x = \sqrt{2}$ can occupy two positions: to the left of the point $x = \frac{a}{l}$ (Fig. 9) or to the right of this point (Fig. 10).

In both cases, the graph of the function $f(x)$ is an arc $AB$ parabolic between the points $x = 1$ and $x = \sqrt{2}$.

In the first case $\left(\frac{a}{l} \geq \sqrt{2}\right)$ the function $y(x)$ at $x = \sqrt{2}$ ($\alpha = 45^\circ$) reaches a maximum (!) equal to $a\sqrt{2} - \frac{l}{2}$, and at $x = 1$ it reaches a minimum equal to $a$ (Fig. 9; crossing in this case is impossible, since for any $1 < x \leq \sqrt{2}$ there will be $y > a$).

We got a result that is exactly the opposite of what was intuitively expected! Figure 6 not directed to pump sources. If $\frac{a}{l} \geq \sqrt{2}$, then at $\alpha = 45^\circ$ the distance $CP$ from point $C$ to the first access is not the smallest, but the largest! According to myself, the intuition that suggested hypothesis 2 deceived us very beautifully. In addition, the impossibility of crossing at $l \leq \frac{a\sqrt{2}}{2}$ (for example, at $a = 3,5$ m, $l \approx 2,4$ m) is difficult to predict intuitively, although it is clear that there should be some kind of restriction on $l$, for very small $l$ the crossing is impossible.

Let's continue the research

Let's see if crossing is always possible if $1 < \frac{a}{l} < \sqrt{2}$. In this case, the function $y(x)$ has a maximum equal to $\frac{a^2 + l^2}{2l}$ (Fig. 10). I'm not interested in the minimum of this function. The function reaches a minimum at $x = 1$ or at $x = \sqrt{2}$. Let $y(1) \leq y(\sqrt{2})$ (Fig. 10). Since $y(1) = a$, $y(\sqrt{2}) = a\sqrt{2} - \frac{l}{2}$, then $a\sqrt{2} - \frac{l}{2} \geq a$, hence $\frac{a}{l} \geq \frac{\sqrt{2} + 1}{2}$. So, at $\frac{\sqrt{2} + 1}{2} \leq \frac{a}{l} < \sqrt{2}$ the crossing is not feasible, since at $1 < x \leq \sqrt{2}$ there will be $y(x) > a$ (Fig. 9). It remains to consider case $1 < \frac{a}{l} < \frac{\sqrt{2} + 1}{2}$.

In this case $y(\sqrt{2}) = a\sqrt{2} - \frac{l}{2} - \frac{l}{2} < a = y(1)$, the minimum of the function $y(x)$ is $a\sqrt{2} - \frac{l}{2}$ (Fig. 11) and is achieved at $x = \sqrt{2}$, $\alpha = 45^\circ$. A crossing has occurred if this minimum does not exceed the length $l$ of the second point, that is, at $a\sqrt{2} - \frac{l}{2} \leq l$, or $\frac{a}{l} \leq \frac{3\sqrt{2}}{4} (< \frac{\sqrt{2} + 1}{2})$.

Preparing, we find that crossing is impossible at $\frac{a}{l} > \frac{3\sqrt{2}}{4}$

⟦folio 47⟧

and is possible with

$$\frac{a}{l} \leq \frac{3\sqrt{2}}{4}.$$ (*)

The relation $\frac{a}{l} = \frac{3,5}{3}$ does not satisfy condition (*) since $\frac{3,5}{3} > \frac{3\sqrt{2}}{4}$.

From inequality $\frac{3,5}{l} \leq \frac{3\sqrt{2}}{4}$ we find that crossing is possible if $l \geq \frac{7\sqrt{2}}{3} \approx 3,3$ m.

The impossibility of a geometric crossing will indicate that the set of points “swept out” by the first and second docks do not intersect (Fig. 12).

If $\frac{a}{l} = \frac{3\sqrt{2}}{4}$, then these sets have only one common point.

If $\frac{a}{l} < \frac{3\sqrt{2}}{4}$, then the area of ​​intersection of the indicated sets contains an infinite set of points.

If $\frac{a}{l}$ is closer to 1 than to $\frac{3\sqrt{2}}{4}$ (the area of ​​intersection of the sets is large enough), the first dock can be placed not at an angle $45^\circ$ to the shores, and the second dock - not perpendicular to the first, you can even move its end away from the top of the angle (point $C$).

Results

What conclusion can be drawn from all that has been said? Does all of our reasoning support the fact that the intuitive prediction of Hypothesis 2 is correct?

We have seen that hypothesis 2 in the formulation

a) the first board is at our distance from $C$, if $\alpha = 45^\circ$,
not true. In the wording

b) if crossing is possible ($\frac{a}{l} \leq \frac{3\sqrt{2}}{4}$), then the first board is at our distance from $C$, if $\alpha = 45^\circ$,

Hypothesis 2 is true. However, this result is difficult to predict intuitively.

In connection with the problem considered, new interesting problems arise. Here are some of them.

Exercises

1. At what minimum length of two identical boards (channel width is 3.5 m) is crossing possible if the margin of coverage for each dock should be 20 cm (10 cm for each end)?

2. Derive the condition for the possibility of crossing a channel of width $a$ using two boards of different lengths: $m$ and $n$ ($m < a$, $n < a$). In particular, find out whether the crossing is possible if $a = 3,5$ m and $m + n = 6$ m.

3*. You can cross the food channel using three planks. At what lengths $a$, $b$, $c$ boards is this possible? Are three boards of 3 m each enough?*)

4*. The two branches of the channel have different widths: $a$ ($m$) and $b$ ($m$) ($a > b$), and there are two docks of the same or different lengths: $m$ and $n$ - which one is smaller than $b$. Derive a necessary and sufficient condition for the possibility of crossing.

5*. The branches of the channel form an arbitrary (and not right) angle $\varphi$, their width is $a$ and $b$, the docks are of different lengths ($m$ and $n$). Under what conditions is crossing possible?

Literature

1. D. Polya, Mathematics and Plausible Reasoning, IL, 1957.

2. D. Polya, Mathematical discovery, M., “Science”, 1970.

3. D. Polya, How to solve a problem, M., Uchredgiz, 1957.

4. G. D. Balk, M. B. Balk, Tests of plausibility. «Kvant», 1972, No. 1.

*) It is not necessary to solve tasks 3-5; their solutions are very difficult, cumbersome, and require knowledge that goes beyond the school curriculum.
