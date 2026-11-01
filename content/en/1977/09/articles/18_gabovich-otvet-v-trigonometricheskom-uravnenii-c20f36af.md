---
id: 1977-9-gabovich-otvet-v-trigonometricheskom-uravnenii-c20f36af
issue: kvant_1977_9
year: 1977
number: "9"
title: Answer in trigonometric equation
authors:
  - Габович И. Г.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 55
page_last: 57
page_labels: 53-55
tag: FRLD
lang: en
source: kvant_digital
extraction: vision
content_sha256: b9ef5d45f01b89e6eb00e64b4c0e0dc497165dd533bb36bd100d2a165ff57a0b
prompt_sha256: draft-1
translated_from: content/ru/1977/09/articles/18_gabovich-otvet-v-trigonometricheskom-uravnenii-c20f36af.md
source_content_sha256: 492e6b37de7a9a2d39c55fc08132eef73cee9ed68da19350ca5217565e467067
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 53⟧

Answer
in trigonometric equation

Writing the answer to a trigonometric equation is primarily related to the concepts of unions and intersections of a set. Typically, when solving such equations, a series of roots is obtained, and in the final form the answer is written as a combination of these series. But what about life if these series intersect? Should duplicate decisions be excluded or can this not be done?
Related to the clear intersections of the set is another, apparently the most important question: the answer should not contain values ​​of the variable for which the expressions on the left or right side of the equation are not defined. Such values, if they appeared during the solution process, must be excluded. And for this you need to be able to find the intersection of different series.

This article is devoted to these issues.

One example
Let's consider solving the following problem.

Example 1: Solve the equation
$$\frac{1}{\sin x} - \frac{1}{\sin 2x} = \frac{1}{\sin 4x}.$$ (1)

Valid values ​​for the condition definition variable are: sin x ≠ 0, sin 2x ≠ 0, sin 4x ≠ 0. This gives us x ≠ πk, x ≠ πm/2, x ≠ πn/4 (k, m, n∈Z). It is easy to see that these three conditions can be replaced by one: x ≠ πn/4 (n∈Z). This can be seen both from the considered trigonometric circle (the series x = πn/4 contains the series x = πk and x = πm/2), and purely algebraically: for even n, from the series x = πn/4 the series x = πm/2 is obtained, and for n multiples of four, the series x = πk is obtained. Such k can also be excluded. After it the equation
$$\sin 2x \sin 4x - \sin x \sin 4x = \sin x \sin 2x,$$
equal to the original one on the range of permissible values ​​of the variable. Transforming this equation, we get:
$$\sin 2x \sin 4x = \sin x (\sin 2x + \sin 4x),$$
$$\sin 2x \sin 4x = 2 \sin x \sin 3x \cos x,$$
$$\sin 2x \sin 4x = \sin 2x \sin 3x,$$
$$\sin 2x (\sin 4x - \sin 3x) = 0,$$
$$\sin 2x \cdot \sin \frac{x}{2} \cdot \cos \frac{7x}{2} = 0.$$

There are three cases left to consider:
$$\sin 2x = 0, \sin \frac{x}{2} = 0, \cos \frac{7x}{2} = 0.$$

The equation sin 2x = 0 does not give us the roots of the original equation, since in the region under consideration there must be sin 2x ≠ 0.

The equation sin $\frac{x}{2} = 0$ and cos $\frac{7x}{2} = 0$ give us the series correspondence $x_1 = 2\pi k$ and $x_2 = \frac{\pi}{7} (2k + 1) (k \in Z)$.

It remains to check whether they lie in the region $x \in \mathbb{R}$, x ≠ πn/4, n∈Z. The series $x_1$ is easy to check: since $x \neq \pi n/4$, and for n multiples of n = 8l, it turns out just x ≠ 2πl, the entire series $x_1$ is excluded. The situation is more complicated with episodes $x_2$. Here we need to find out for what integer k there is an n that is satisfied by the equation
$$\frac{\pi (2k + 1)}{7} = \frac{\pi n}{4},$$
and exclude such k. After it, the equation

⟦folio 54⟧

vaguely brought to mind
$$8k + 4 = 7n,$$
Moreover, this equation must be solved for numerical purposes.

Linear diffant equations in two variables
Linear diffant equations with two variables are called equations of the form
$$ax + by = c,$$
(2)
where $a$ and $b$ are non-zero integers, $c$ is an arbitrary integer, and only integer solutions need to be found.
We can assume that the numbers $a, b$ and $c$ in equation (2) are coprime (we can always reduce both sides of equation (2) by gcd $(a, b, c) \neq 1$).
But if the numbers are mutually prime, they may not be pairwise coprime (example: 6, 10, 15). Obviously, if the numbers $a$ and $b$ in equation (2) are not coprime, then this equation does not have integer solutions. Indeed, putting $a = ka_1$, $b = kb_1$, we get $(a_1x + b_1y) = c$, which opens $(a_1x + b_1y = c/k)$, and if $x$ and $y$ are integers, then $c/k$ is an integer, and this is impossible, since $c$ is not divisible by $k$ (we assumed that $a, b$ and $c$ are relatively prime numbers).

If $a$ and $b$ in equation (2) are relatively prime numbers, then the equation has integer solutions. We will not dwell on the proof of this fact, but will only show how to find all solutions if at least one of them is known (it must be searched for by selection).

Let $(x_0, y_0)$ be some integer solution to equation (2):
$$ax_0 + by_0 = c.$$
Let us subtract this equality term by term from equation (2); we get
$$a(x - x_0) + b(y - y_0) = 0,$$
where
$$x = x_0 - \frac{b(y - y_0)}{a}.$$

For $x$, defined by formula (3), to be an integer, it is necessary and sufficient that the number $\frac{b(y - y_0)}{a}$ is also an integer. But, by assumption, $a$ and $b$ are coprime, therefore $\frac{y - y_0}{a}$ must be an integer. Denoting the relation $\frac{y - y_0}{a}$ by the letter $t$, we obtain:
$$x = x_0 - bt,$$
$$y = y_0 + at,$$
where $t \in \mathbb{Z}$.

Continuation of the example
So, we need to solve for number purposes the equation
$$7n - 4 = 8k.$$
It is immediately clear that $n$ must be divisible by even; putting $n = 4$, we find $7 \cdot 4 - 4 = 24 = 8k$, opening $k = 3$. We managed to quickly find one solution to the equation: $k = 3$, $n = 4$. The general solution is then written as $k = 3 + 7t$, $n = 4 + 8t$ ($t \in \mathbb{Z}$).

It follows that in the series $x_2$ (see p. 53) it is necessary to exclude all $k$ of the form $3 + 7t$, that is, the answer to example 1 can be written in the form
$$x = \frac{\pi}{7}(2k + 1), k \neq 7t + 3, t \in \mathbb{Z}$$
or
$$\left\{\frac{\pi}{7}(2k + 1)\right| k \neq 7t + 3; k, t \in \mathbb{Z}\}.$$

Equation $8k + 4 = 7n$ can be solved without using the general theory. It follows that $n = 4l$ (since the left side of the equation is divisible by even). Substituting $n = 4l$ into the equation, we get: $8k + 4 = 28l$, opening $2k + 1 = 7l$. Next, $l$ must be odd, $l = 2t + 1$; therefore $2k + 1 = 14t + 7$, $k = 7t + 3$. Here is the solution: $k = 7t + 3$, $n = 4l = 4(2t + 1) = 8t + 4$.

Recording a response
Now let's look at another problem.
Example 2: Solve the equation
$$\sin^2 2x + \sin^2 3x + \sin^2 4x + \sin^2 5x = 2.$$
Using known data points, we get:
$$\frac{1 - \cos 4x}{2} + \frac{1 - \cos 6x}{2} + \frac{1 - \cos 10x}{2} = 2,$$
with $4x + \cos 6x + \cos 8x + \cos 10x = 0,$
$2 \cos 5x \cos x + 2 \cos 9x \cos x = 0,$

⟦folio 55⟧

cos x (cos 5x + cos 9x) = 0,
cos x cos 2x cos 7x = 0.

Considering three cases, we obtain three series of roots ($k, l, m \in \mathbb{Z}$):

1) cos x = 0, $x_1 = \frac{\pi}{2} + \pi k$;
2) cos 2x = 0, $x_2 = \frac{\pi}{4} + \frac{\pi l}{2}$;
3) cos 7x = 0, $x_3 = \frac{\pi}{14} + \frac{\pi m}{7}$.

How to write down the answer? Do I need to list all three episodes? Let's see if these series intersect or not. Here you can act in different ways.

Geometric method. The “period” of the series is equal to π. Let us consider those roots from the series $x_1, x_2, x_3$ that fall in the interval [0; π]. It will be

$$x_1 : \pi/2;$$
$$x_2 : \pi/4, 3\pi/4;$$
$$x_3 : \pi/14, 3\pi/14; 5\pi/14, \pi/2, 9\pi/14, 11\pi/14, 13\pi/14.$$

It is immediately clear that the series $x_1$ is contained in the series $x_3$, and the series $x_2$ and $x_3$ do not intersect. This means that the answer can be written in the form

$$\left\{ \frac{\pi}{4} + \frac{\pi k}{2}; \frac{\pi}{14} + \frac{\pi k}{7} \mid k \in \mathbb{Z} \right\}.$$

Algebraic method. The common denominator in the series $x_1$ and $x_2$ will be 4:

$$x_1 = \frac{\pi(2+4k)}{4}, \quad x_2 = \frac{\pi(1+2l)}{4}.$$

If $x_1 = x_2$, then $2+4k = 1 + 2l$, but it follows an even number, and on the right - an odd one. Equality is impossible, the series $x_1$ and $x_2$ do not intersect. Similarly, we find that the series $x_2$ and $x_3$ also do not intersect. But for the series $x_1$ and $x_3$ we get the formulas

$$x_1 = \frac{\pi(7+14k)}{14}, \quad x_3 = \frac{\pi(1+2m)}{14}.$$

From the equality 7 + 14k = 1 + 2m we obtain $m = 7k + 3$. This means that for every $k$ there is an integer $m$ such that the equality 7 + 14k = 1 + 2m is satisfied, that is, every root from the series $x_1$ occurs in the series $x_3$, therefore the series $x_1$ is contained in the series $x_3$, and there is no need to pin it in the answer.

Example 3. Solve equation $\cos 7x (\sin 5x - 1) = 0$.

We immediately get two cases ($k, n \in \mathbb{Z}$):

1) cos 7x = 0, $x_1 = \frac{\pi}{14} + \frac{k\pi}{7}$;
2) sin 5x = 1, $x_2 = \frac{\pi}{10} + \frac{2n\pi}{5}$.

Do these series overlap? Advice

$$\frac{\pi}{14} + \frac{\pi k}{7} = \frac{\pi}{10} + \frac{2\pi n}{5}$$

followed by $5k = 14n + 1$. This equation has solutions. However, one of them is found by selection: $k = 3, n = 1$, and the general one then has the form $k = 3 + 14t, n = 1 + 5t$.

The answer can be written in the form

$$\left\{ \frac{\pi}{14} + \frac{\pi k}{7}; \frac{\pi}{10} + \frac{2\pi n}{5} \mid k \neq 3 + 14t; \right.$$
$$k, n, t \in \mathbb{Z}$$

or in the form

$$\left\{ \frac{\pi}{14} + \frac{\pi k}{7}; \frac{\pi}{10} + \frac{2\pi n}{5} \mid n \neq 1 + 5t; \right.$$
$$k, n, t \in \mathbb{Z}$$.

Sweeping. Otherwise, the combination of series looks rather more complicated than the smaller series. In such cases, it can be useful to break these series into “chunks”. For example, the union of the series $x_1 = \frac{\pi k}{2}$ and $x_2 = \frac{\pi}{6} + \frac{\pi k}{3}$ can be written as

$$\left\{ \frac{\pi k}{2}; \frac{\pi}{6} + \pi k; \frac{5\pi}{6} + \pi k \mid k \in \mathbb{Z} \right\}.$$

Systems

When solving some trionometric equations, they are replaced by a system of equations,
