---
id: 1971-4-demyanov-trigonometricheskie-neravenstva-1981b658
issue: kvant_1971_4
year: 1971
number: "4"
title: Trigonometric inequalities
authors:
  - Демьянов В. Б.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 45
page_last: 52
page_labels: 43-50
tag: DE7Y
lang: en
source: kvant_digital
extraction: vision
content_sha256: 6e5300077d6cd9b65413bb1ad808aaa28f90ee679cdd139fb6463b0a9c8aa976
prompt_sha256: draft-1
translated_from: content/ru/1971/04/articles/11_demyanov-trigonometricheskie-neravenstva-1981b658.md
source_content_sha256: 5f6558d13eaba12d914dd6c05975be07e6696d3a29dae4b831d91183ce1b7fe6
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 43⟧

We will call trigonometric inequalities those containing the unknown $x$, which is part of the arguments of trigonometric functions. Solving a trigonometric inequality means, as always, finding all the values ​​of the unknown that satisfy this inequality.

Solving the simplest trigonometric inequalities does not require any special knowledge beyond the school curriculum. Namely, in the examples discussed below, in addition to the properties of trigonometric functions, only the concept of the absolute value of a number (example 4), the rules for solving quadratic inequalities (examples 5-8) and the properties of a logarithmic function (examples 9, 10) are used. This information is sufficient to cope with the examples given at the end of the article for independent solutions.

From the outset, however, one fundamental point must be noted. In trigonometric inequalities, the arguments of trigonometric functions are treated not as angles or arcs, but as real numbers. Since experience shows that many high school graduates do not have complete clarity on this issue, let us dwell on it in a little more detail. The current applicant is advised to carefully consider what is said below in this regard.

Generally trigonometric functions are introduced first as functions of an angle (more precisely, even just an acute angle). Then the concept of an argument of a trigonometric function is expanded - they begin to consider arc functions. It turns out that it is convenient not to limit the arcs contained within one revolution, that is, having values ​​from $0^\circ$ to $360^\circ$, but to consider arcs whose magnitudes are expressed by any number of degrees (both positive and negative). With this understanding of the argument, trigonometric functions turn out to be periodic. The next step is to move from the hail measurement of arcs to the radian measurement. And finally, he comes to the concept of a trigonometric function in 6th numbers. Namely, the value of the trigonometric function of a number is understood as the value of a given function for that arc, the value of which in radians is expressed by this number.

In physics, trigonometric functions of a numerical argument naturally appear when describing various periodic processes, that is, processes whose character is completely repeated at certain intervals. That is why in mathematics it is advisable to consider trigonometric functions of a numerical argument. In fact, we do this already when we build graphs of trigonometric functions. In fact, we plot the values ​​of real numbers along the abscissa axis.

Let us now consider some trigonometric inequalities

⟦folio 44⟧

STV, let's start with the simplest example.

Example 1. Solve inequality $tg x < 1$.

Solution. First, we will show how not to “solve” this inequality, that is, we will analyze some of the incorrect answers to the question.

Another applicant, noticing that $tg \frac{\pi}{4} = 1$ and that near the value $x = \frac{\pi}{4}$ the function $tg x$ increases with increasing $x$, writes the answer in the form: $x < \frac{\pi}{4}$. Already by the appearance of the answer, we can say that it is incorrect, since it does not reflect the periodicity of the function $y = tg x$. It is easy to indicate specific values ​​of $x$ that satisfy the condition $x < \frac{\pi}{4}$, but do not satisfy the given inequality. For example, with $x = -\frac{2\pi}{3}$ we have: $-\frac{2\pi}{3} < \frac{\pi}{4}$, but $tg\left(-\frac{2\pi}{3}\right) = \sqrt{3} > 1$; at $x = -\frac{\pi}{2}$ the lying part of the inequality does not make sense, therefore, this value does not satisfy the inequality either, although again $-\frac{\pi}{2} < \frac{\pi}{4}$.

It also happens that an applicant tries to take into account the frequency, but at the same time shows helplessness. Namely, often the “answer” is given in the form: $x < \frac{\pi}{4} + k\pi$, where $k = 0, \pm 1, \pm 2, \dots$.

This “answer” is even worse because it makes no sense at all. It is easy to verify that there are simply no numbers $x$ satisfying the condition $x < \frac{\pi}{4} + k\pi$ for all $k = 0, \pm 1, \pm 2, \dots$.

To get the correct answer, it is useful to consider the graph of the function $y = tg x$ (Fig. 1), since this will make the reasoning more geometrically clear.

The inequality $tg x < 1$ is satisfied by those and only those values ​​$x$ for which the corresponding points of the graph lie below the dotted horizontal line $y = 1$. Further, from figure 1 it is clear that if we find all the solutions belonging to some specific interval of length $x$, then all other solutions will differ from those found by shifting to the right or left by $\pi, 2\pi, 3\pi$, etc. The reason for this is that the number $x$ is the period of the function $y = tg x$.

⟦folio 45⟧

In order for the answer to be written down as briefly as possible, it is advisable to choose the initial interval of length $l$ so that the solutions belonging to it fill, in turn, some one continuous interval. From figure it is again clear that this will be the case if, for example, the interval from $-\frac{\pi}{2}$ to $\frac{\pi}{2}$ is taken as the initial interval. On this interval below example $y = 1$ lie those points of the graph that correspond to the values ​​$x$ satisfying the inequality $-\frac{\pi}{2} < x < \frac{\pi}{4}$. Therefore the final answer is
$$-\frac{\pi}{2} + k\pi < x < \frac{\pi}{4} + k\pi$$
($k = 0, \pm 1, \pm 2, \dots$).

The answer is thus a set of intervals, each of which is obtained at some fixed value $k$.

The situation is similar in the answers to all further examples.

Example 2: Solve inequality
$$\sin x \geq -\frac{1}{2}.$$

Solution. Consider the graph of the function $y = \sin x$ (Fig. 2). The inequality $\sin x \geq -\frac{1}{2}$ is satisfied by those values ​​$x$ for which the corresponding points of the graph lie no lower than the point line $y = -\frac{1}{2}$ (if the point of the graph lies on this line itself, then the value $x$ satisfies the given inequality, since it is “not strict”, it allows equality of the left and right parts). The function $y = \sin x$ has a period $2\pi$. Therefore, let us first consider some interval of length $2\pi$, for example the interval from $-\frac{\pi}{2}$ to $\frac{3\pi}{2}$. From figure 2 it is clear that the following values ​​of $x$ satisfy the inequality $\sin x \geq -\frac{1}{2}$ in this interval: $-\frac{\pi}{6} \leq x \leq \frac{7\pi}{6}$.

Taking into account the periodicity, we get the answer:
$$-\frac{\pi}{6} + 2k\pi \leq x \leq \frac{7\pi}{6} + 2k\pi$$
($k = 0, \pm 1, \pm 2, \dots$).

Example 3. Solve inequality
$$\cos(3x + 2) > -\frac{\sqrt{2}}{2}.$$

Solution. Let us introduce the auxiliary unknown $t = 3x + 2$. Then with respect to $t$ we obtain the inequality $\cos t > -\frac{\sqrt{2}}{2}$. Since it is completely similar to the inequality from examples 1 and 2 (to solve it you can consider the graph of the function $y = \cos t$), we immediately answer for $t$:
$$-\frac{3\pi}{4} + 2k\pi < t < \frac{3\pi}{4} + 2k\pi$$
($k = 0, \pm 1, \pm 2, \dots$).

⟦folio 46⟧

or, returning to the unknown $x$,
$$-\frac{3\pi}{4} + 2k\pi < 3x + 2 < \frac{3\pi}{4} + 2k\pi$$
($k = 0, \pm 1, \pm 2, \dots$).

Expressing $x$ from here, we obtain the answer for the given inequality:
$$-\frac{2}{3} - \frac{\pi}{4} + \frac{2k\pi}{3} < x < -\frac{2}{3} + \frac{\pi}{4} + \frac{2k\pi}{3}$$
($k = 0, \pm 1, \pm 2, \dots$).

Example 4. Solve inequality
$$|\sin x| > \frac{\sqrt{3}}{2}$$.

Solution. Freeing ourselves from the abscille sign, we obtain that the given inequality will be satisfied by those and only those values ​​of $x$ that satisfy one of the inequalities
$$\sin x > \frac{\sqrt{3}}{2}, \sin x < -\frac{\sqrt{3}}{2}$$.

Solving each of them using the distance method in Examples 1 and 2, we obtain the answer for inequality $\sin x > \frac{\sqrt{3}}{2}$:
$$\frac{\pi}{3} + 2k\pi < x < \frac{2\pi}{3} + 2k\pi$$
($k = 0, \pm 1, \pm 2, \dots$),

and for inequality $\sin x < -\frac{\sqrt{3}}{2}$ the answer is:
$$-\frac{2\pi}{3} + 2m\pi < x < -\frac{\pi}{3} + 2m\pi$$
($m = 0, \pm 1, \pm 2, \dots$).

Therefore, the answer for the given inequality is
$$|\sin x| > \frac{\sqrt{3}}{2}$$ can be written as two "series":
$$\frac{\pi}{3} + 2k\pi < x_1 < \frac{2\pi}{3} + 2k\pi$$
($k = 0, \pm 1, \pm 2, \dots$),
$$-\frac{2\pi}{3} + 2m\pi < x_2 < -\frac{\pi}{3} + 2m\pi$$
($m = 0, \pm 1, \pm 2, \dots$).

Note that since
$$-\frac{2\pi}{3} = \frac{\pi}{3} - \pi$$
And
$$-\frac{\pi}{3} = \frac{2\pi}{3} - \pi$$,
the second series can be written differently
$$\frac{\pi}{3} + (2m - 1)\pi < x_2 < \frac{2\pi}{3} + (2m - 1)\pi$$
($m = 0, \pm 1, \pm 2, \dots$).

Now both series can be combined with one formula:
$$\frac{\pi}{3} + n\pi < x < \frac{2\pi}{3} + n\pi$$
($n = 0, \pm 1, \pm 2, \dots$),

Moreover, for even $n$ we obtain integrates of the first series, and for odd $n$ we obtain integrates of the second series.

Example 5. Solve inequality
$$\cos^2 x < \frac{3}{4}$$

Solution. Let us introduce the auxiliary unknown $y = \cos x$. The inequality will take the form
$$y^2 < \frac{3}{4}$$
From here
$$-\frac{\sqrt{3}}{2} < y < \frac{\sqrt{3}}{2}$$
or
$$-\frac{\sqrt{3}}{2} < \cos x < \frac{\sqrt{3}}{2}$$

Thus, the given inequality has been reduced to a system of inequalities
$$\left\{ \begin{array}{l}
\cos x < \frac{\sqrt{3}}{2} \\
\cos x > -\frac{\sqrt{3}}{2}
\end{array} \right.$$

We underline the difference between the current situation and the one that took place in example 4. There, in order to satisfy the given inequality, it was necessary for at least one of the two inequalities to be satisfied
$$\sin x > \frac{\sqrt{3}}{2}$$ or $$\sin x < -\frac{\sqrt{3}}{2}$$

Here, the given inequality will be satisfied by those values ​​of $x$ that

⟦folio 47⟧

satisfies simultaneously each of the inequalities $\cos x < \frac{\sqrt{3}}{2}$ and $\cos x > -\frac{\sqrt{3}}{2}$.

Since the function $y = \cos x$ has a period $2\pi$, let us first consider the values ​​$x$ lying in the interval from $-\pi$ to $\pi$. Let us construct a graph of the function $y = \cos x$ (Fig. 3) for this integral. System

$$\begin{cases} \cos x < \frac{\sqrt{3}}{2}, \\ \cos x > -\frac{\sqrt{3}}{2} \end{cases}$$

satisfies those values ​​$x$ for which the corresponding points of the graph fall inside the horizontal strip bounded above by the dotted line $y = \frac{\sqrt{3}}{2}$ and below by the dotted line $y = -\frac{\sqrt{3}}{2}$.

From figure it is clear that this conditionally satisfies the following meanings of $x$: firstly, $\frac{\pi}{6} < x < \frac{5\pi}{6}$, secondly, $-\frac{5\pi}{6} < x < -\frac{\pi}{6}$. Given the periodicity, we can now write the answer in the form of two series:

$$\frac{\pi}{6} + 2k\pi < x_1 < \frac{5\pi}{6} + 2k\pi$$

($k = 0, \pm 1, \pm 2, \dots$).

$- \frac{5\pi}{6} + 2m\pi < x_2 < - \frac{\pi}{6} + 2m\pi$

($m = 0, \pm 1, \pm 2, \dots$).

As in example 4, these two series can be combined with one formula:

$$\frac{\pi}{6} + n\pi < x < \frac{5\pi}{6} + n\pi$$

($n = 0, \pm 1, \pm 2, \dots$).

Note that the inequality $\cos^2 x < \frac{3}{4}$ can be solved more easily if we first transform it to the form

$$\frac{1 + \cos 2x}{2} < \frac{3}{4}$$

whence $\cos 2x < \frac{1}{2}$. Polling $2x = t$, we get that

$$\frac{\pi}{3} + 2n\pi < t < \frac{5\pi}{3} + 2n\pi$$

($n = 0, \pm 1, \pm 2, \dots$).

From here

$$\frac{\pi}{6} + n\pi < x < \frac{5\pi}{6} + n\pi$$

($n = 0, \pm 1, \pm 2, \dots$).

However, the first solution method, based on reduction to a quadratic inequality, has greater generality, as we will see below (examples 6, 7, 8).

Example 6. Solve inequality $\mathrm{tg}^2 x - (1 + \sqrt{3}) \mathrm{tg} x + \sqrt{3} \leq 0$.

⟦folio 48⟧

Solution. By fielding $y = \text{tg} x$, we, as in the previous example, arrive at the quadratic inequality: $y^2 - (1 + \sqrt{3}) y + \sqrt{3} \leq 0$.
Solving it, we find that $1 \leq y \leq \sqrt{3}$. Thus, the question again came down to solving the system of inequalities
$$\begin{cases} \text{tg} x \leq \sqrt{3}, \\ \text{tg} x \geq 1. \end{cases}$$

The period of the function $y = \text{tg} x$ is equal to $\pi$. Reasoning in the same way as in Example 5, we first find for the integral from $-\frac{\pi}{2}$ to $\frac{\pi}{2}$ the following values ​​$x$:
$\frac{\pi}{4} \leq x \leq \frac{\pi}{3}$. Taking into account the periodicity, we get the final answer:
$$\frac{\pi}{4} + k\pi \leq x \leq \frac{\pi}{3} + k\pi$$
($k = 0, \pm 1, \pm 2, \dots$).

All the examples analyzed so far were selected so that the answers included “round” values ​​of arguments like $\frac{\pi}{6}, \frac{\pi}{4}, \frac{\pi}{3}$.

However, in principle this is not at all necessary, since the answer can always be written using the symbols of inverse trigonometric functions. To use this, consider an example that differs from example 6 only in the values ​​of the numerical coefficients.

Example 7. Solve inequality $\text{tg}^2 x - 5\text{tg} x + 6 \leq 0$.

Solution. Reasoning verbatim in the same way as in Example 6, we arrive at the system of inequalities
$$\begin{cases} \text{tg} x \leq 3, \\ \text{tg} x \geq 2. \end{cases}$$

The answer will now be written in the form
$$k\pi + \text{arctg} 2 \leq x \leq k\pi + \text{arctg} 3$$
($k = 0, \pm 1, \pm 2, \dots$).

Example 8. Solve inequality $12\sin^2 x - 19\sin x + 5 < 0$.

Solution. By removing $y = \sin x$, we obtain the quadratic inequality $12y^2 - 19y + 5 < 0$, whence $\frac{1}{3} < y < \frac{5}{4}$. Thus the unknown $x$ must satisfy all hex values ​​$x$. Therefore, in fact, only the second inequality $\sin x > \frac{1}{3}$ needs to be solved. It is easy to verify that the following values ​​of $x$ satisfy it:
$$2k\pi + \text{arcsin} \frac{1}{3} < x < (2k + 1)\pi - \text{arcsin} \frac{1}{3}$$
($k = 0, \pm 1, \pm 2, \dots$).

This is the final answer for the given inequality. It would be a very serious mistake if, in connection with the inequality $\sin x < \frac{5}{4}$, the “expression” $\text{arcsin} \frac{5}{4}$ appears in the “answer”. Since $\frac{5}{4} > 1$, the symbol $\text{arcsin} \frac{5}{4}$ has no meaning.

Example 9. Solve inequality $\log_2 \sin x < -1$.

Solution. Let us introduce the auxiliary unknown $y = \sin x$. The inequality then takes the form $\log_2 y < -1$. Since $-1 = \log_2 \frac{1}{2}$ and with a base greater than 1, a larger number corresponds to a larger logarithm, we get that $y < \frac{1}{2}$. However, it is also necessary to take into account (when solving such inequalities this is often forgotten!) that for negative values ​​of the argument the logarithmic

⟦folio 49⟧

The function is not defined at all. Therefore, in the final form the solution to inequality $\log_2 y < -1$ will be written as follows:
$$0 < y < \frac{1}{2}.$$
We thus arrive at a system of inequalities
$$\begin{cases} \sin x < \frac{1}{2}, \\ \sin x > 0. \end{cases}$$

Reasoning in the same way as we did in Example 5, we get the following answer, containing two series:

$$\begin{cases} 2k\pi < x_1 < \frac{\pi}{6} + 2k\pi \\ (k = 0, \pm 1, \pm 2, \dots), \\ \frac{5\pi}{6} + 2m\pi < x_2 < \pi + 2m\pi \\ (m = 0, \pm 1, \pm 2, \dots). \end{cases}$$

Unlike examples 4 and 5, here it is no longer possible to give a simple formula combining these two series into one.

Example 10. Solve inequality
$$\log_x tg x > 0.$$

Solution. This example is more complicated than the previous ones, since the unknown $x$ appears here simultaneously in two different roles: both as the base of logarithms and as an argument of the trigonometric function. Thanks to this, the fact that we must understand $x$ as chi and s lo is especially clear here.

Note first that since $x$ is the base of logarithms, $x > 0$ and $x \neq 1$ are necessary. Since the properties of logarithms depend significantly on whether their base is greater or less than 1, we will consider these cases separately.

Let $0 < x < 1$ first. Since, with a base less than 1, the positive logarithm has numbers between 0 and 1, we arrive at the system of inequalities $0 < tg x < 1$. Solving it, we get
$$k\pi < x < \frac{\pi}{4} + k\pi$$
($k = 0, \pm 1, \pm 2, \dots$).

But we are still bound by the conditions $0 < x < 1$. From figure 4 it is clear that inequalities $0 < x < 1, 0 < tg x < 1$ are simultaneously satisfied only by the following values ​​$x$: $0 < x < \frac{\pi}{4}$.

Let now $x > 1$. Considering that with a base less than 1, the positive logarithm has numbers greater than 1, we obtain that $tg x > 1$, from which
$$\frac{\pi}{4} + k\pi < x < \frac{\pi}{2} + k\pi$$
($k = 0, \pm 1, \pm 2, \dots$).

Now we learn the conditions $x > 1$. From figure 5 we see that both inequalities $x > 1$ and $tg x > 1$ are simultaneously

⟦folio 50⟧

satisfies the following values ​​of $x$: firstly, $1 < x < \frac{\pi}{2}$, secondly
$$\frac{\pi}{4} + k\pi < x < \frac{\pi}{2} + k\pi$$
where $k$ is a positive integer, that is, $k = 1, 2, 3, \dots$.

Collecting all the values ​​of $x$ found when considering both cases, we obtain the following final answer:

$$0 < x_1 < \frac{\pi}{4},$$
$$1 < x_2 < \frac{\pi}{2},$$
$$\frac{\pi}{4} + k\pi < x_3 < \frac{\pi}{2} + k\pi$$
($k = 1, 2, 3, \dots$).

In conclusion, we provide a number of examples for independent solutions.

Solve the inequalities:

1. $\cos x \geq \frac{1}{2}$.
2. $\sin 2x < \frac{1}{\sqrt{2}}$.
3. $\sin \frac{x}{5} \geq -\frac{1}{2}$.
4. $\lg(3x - 1) < \frac{1}{\sqrt{3}}$.
5. $|\lg x| \geq \sqrt{3}$.
6. $|\cos x| < \frac{1}{2}$.
7. $\sin^2 x < \frac{1}{4}$.
8. $\lg^2 x \geq \frac{1}{3}$.
9. $2\sin^2 x \leq \sin x$.
10. $2\cos^2 x + \cos x < 1$.
11. $\log_3(\lg x) \geq \frac{1}{2}$.
12. $\log_{\frac{1}{2}}(\cos x) \leq 1$.
