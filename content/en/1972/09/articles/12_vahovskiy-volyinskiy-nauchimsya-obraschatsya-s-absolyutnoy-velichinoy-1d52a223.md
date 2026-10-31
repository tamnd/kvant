---
id: 1972-9-vahovskiy-volyinskiy-nauchimsya-obraschatsya-s-absolyutnoy-velichinoy-1d52a223
issue: kvant_1972_9
year: 1972
number: "9"
title: Let's learn to handle absolute value
authors:
  - Ваховский Е. Б.
  - Волынский А. Б.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 47
page_last: 50
page_labels: 45-48
tag: 47WC
lang: en
source: kvant_digital
extraction: vision
content_sha256: 82d637d089e9623d975bf8e14d1c7463354bf38d9233c442b2d5cdb025c82657
prompt_sha256: draft-1
translated_from: content/ru/1972/09/articles/12_vahovskiy-volyinskiy-nauchimsya-obraschatsya-s-absolyutnoy-velichinoy-1d52a223.md
source_content_sha256: 26405ab24cee8dc14681c254465a6ebfb9f26d7c217876d1dff8d982dd08e7ea
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 45⟧

LET'S LEARN TO HANDLE ABSOLUTE QUANTITY

E.B.Vakhovsky, A.B.Volynsky

There is an exam in progress. The applicant is offered a trigonometric equation:

$$\sqrt{\cos^2 x - \cos 2x} - 1 = \sin x.$$

In the process of solving it, the applicant writes out the following equation:

$$\sqrt{\cos^2 x - \cos^2 x + \sin^2 x} - 1 = \sin x,$$

$$\sin x - 1 = \sin x, -1 = 0.$$

The resulting false numerical equality means, the applicant says, that this equation has no solution.

The answer is incorrect. This can be easily verified by substituting the number $x = -\frac{\pi}{6}$ into the original equation, which turns out to be the root.

The applicant’s mistake, by the way, a very common one, is that not for every actionable $a$

$$\sqrt{a^2} = a$$

(1)

(in this example, in particular, the applicant believed that $\sqrt{\sin^2 x} = \sin x$).

In fact, the only true truth is the same

$$\sqrt{a^2} = |a|,$$

(2)

while equality (1) is valid only for $a \ge 0$ (see E. S. Kochetkov, E. S. Kochetkov “Algebra and elementary functions”, § 77).

Thus, by solving the above equation, the applicant should get

$$|\sin x| - 1 = \sin x.$$

If $\sin x \ge 0$, then the last equation will be written as follows: $\sin x - 1 = \sin x$, hence $-1 = 0$, and in this case there is no solution.

If $\sin x < 0$, then $|\sin x| = -\sin x$, and we get $-\sin x - 1 = \sin x$, whence $\sin x = -\frac{1}{2}$, which is in accordance with the conditions $\sin x < 0$.

Answer: $x = (-1)^{n+1} \frac{\pi}{6} + \pi n$ where $n=0, \pm 1, \pm 2, \dots$.

Let us now take a closer look at the concept of absolute value.

First of all, note that the graphs of the number model $x$ are the simple distance from the point $x$ of the number axis to the beginning of the report (see Fig. 1).

The above message makes it easier to solve a large class of inequalities.

Example 1. Solve inequalities

$$|x| < a \quad (a > 0),$$

(3)

$$|x| > a \quad (a > 0).$$

(4)

Solution. Inequality (3) is satisfied only by those points on the numerical axis, the distances from which to the beginning of the report are less than $a$, that is, points lying between $-a$ and $a$ (Fig. 2).

Answer: $-a < x < a$. This means that $x$ satisfies the system

⟦folio 46⟧

inequalities

$$\begin{cases} x > -a, \\ x < a. \end{cases}$$

For similar reasons, solutions to inequality (4) are values ​​of $x$ that satisfy the combination of two inequalities: $x < -a; x > a$ (Fig. 3).

It should be noted that for $a \leq 0$ inequality (3) has no solution. Inequality (4) for $a < 0$ is satisfied by all real numbers, and for $a = 0$ - all but $x = 0$.

Therefore, in examples of this type, we must first of all be interested in the sign of the right-hand side. So, for example, the inequality $|x| < |a|$ is often automatically solved by analyzing the case of $a \geq 0$ and $a < 0$, assuming that this is necessary since the number $a$ is under the modulus sign. However, the easiest thing to notice here is that $|a| > 0$ at $a \neq 0$. From here we easily get the answer: if $a \neq 0$, then $|a| < x < |a|$, if $a = 0$, then there are no solutions.

To inequalities of type (3) and (4) there are some inequalities that do not contain absolute value signs.

Example 2. Solve inequality $4 < x^2 < 9$.

Solution. Let us extract the square root of all three parts of the inequality (arithmetic). The resulting equivalent inequality $2 < |x| < 3$ is easily solved using a graphical representation (Fig. 4).

Answer: $-3 < x < -2; 2 < x < 3$.

Example 3 (MSU, mek.mat., 1966). Solve inequality

$$|3^{tg\pi x} - 3^{1-tg\pi x}| \geq 2.$$

Solution. This inequality is equivalent to the combination of two inequalities: $3^{tg\pi x} - 3^{1-tg\pi x} \leq -2; 3^{tg\pi x} - 3^{1-tg\pi x} \geq 2$.

Denoting $3^{tg\pi x}$ by $y$, we obtain a set of inequalities:

$$y - \frac{3}{y} \leq -2; y - \frac{3}{y} \geq 2 (y > 0).$$

⟦folio 47⟧

Solution. First of all, we need to get rid of the signs of absolute magnitude. However, to do this, you need to know what sign the numbers $1 - x$ and $x^2 - x - 6$ under the modulus sign have. But what the number $x$ is is not known in advance, so it is necessary to analyze several cases. In order to do this in the most economical way, we factorize the trinomial $x^2 - x - 6$ and represent this inequality in the form

$$\frac{6x - |x+2| |x-3|}{|x-1|} \leq 3 + 5x.$$

Since always $|x-1| \geq 0$, this inequality is equivalent to the system

$$\begin{cases} 6x - |x+2| |x-3| \leq \\ \leq (3+5x) |x-1|, \\ x \neq 1. \end{cases}$$

To solve system (5), plot the points $-2, 1$ and $3$ (Fig. 5) on the number axis, which will divide it into even regions. For the number $x$, from each such region it is clear what sign the numbers $x+2, x-1, x-3$ have.

For example, if the point $x$ lies in the leftmost region $(x < -2)$, then $|x+2| = -(x+2), |x-1| = 1 - x, |x-3| = 3 - x$. Thus, our inequality is equivalent to a combination of four systems:

$$\begin{cases} x < -2, \\ 6x - (x+2)(x-3) \leq (3+5x)(1-x); \\ -2 \leq x < 1, \\ 6x + (x+2)(x-3) \leq (3+5x)(1-x); \\ 1 < x \leq 3, \\ 6x + (x+2)(x-3) \leq (3+5x)(x-1); \\ x > 3; \\ 6x - (x+2)(x-3) \leq (3+5x)(x-1). \end{cases}$$

The first system has no solution. Solutions for the rest of the system:

$$-\frac{3}{2} \leq x < 1, \quad 1 < x \leq 3, \quad x > 3$$

respectively. Final answer: $$-\frac{3}{2} \leq x < 1, \quad x > 1.$$

Let's move on to the next type of problems related to absolute value.

Consider an inequality of the form $|A| \leq B$, where $A$ and $B$ are some expressions containing the unknown $x$.

Due to the messages that we gave in Example 1, this inequality is equivalent to either the system

$$\begin{cases} B \geq 0, \\ -B \leq A \leq B, \end{cases}$$

or the totality of the system:

$$\begin{cases} A \geq 0, \\ A \leq B; \quad A < 0, \\ -A \leq B. \end{cases}$$

In the same way, the inequality $|A| \geq B$ is equivalent to either the totality of the system

$$\begin{cases} B < 0, \\ A - \text{любое}; \quad B \geq 0, \\ A \leq -B, \quad A \geq B, \end{cases}$$

or the totality of the system

$$\begin{cases} A \geq 0, \\ A \geq B; \quad A < 0, \\ -A \geq B. \end{cases}$$

In each specific example of this type, one must identify the most useful path.

Example 5. Solve inequality

$$5 + 2 \cos 2x \leq 3 \quad |2 \sin x - 1|.$$

Solution. The first method is directed here, since $5 + 2 \cos 2x > 0$ is for all $x$. The proposed inequality is equivalent to a set of inequalities:

$$3 (2 \sin x - 1) \leq -5 - 2 \cos 2x; \quad 3 (2 \sin x - 1) \geq 5 + 2 \cos 2x.$$

Each of these inequalities, after substituting $\cos 2x = 1 - 2 \sin^2 x$, becomes square with respect to sin $x$. Solving them taking into account the inequality $|\sin x| \leq 1$, we arrive at the set

$$\sin x \leq -\frac{1}{2}, \quad \sin x \geq 1.$$

⟦folio 48⟧

Answer: $2\pi n - \frac{5}{6} \pi \leqslant x \leqslant -\frac{\pi}{6} + 2\pi n, \quad x = \frac{\pi}{2} + 2\pi k, \quad \text{где } n, \quad k = 0, \quad \pm 1, \dots$

Example 6. Solve inequality $|x^3 - 8| \leqslant x^3 + x + 8$.

Solution. Here the first method is simply not applicable, since we do not have the opportunity to solve the inequality $x^3 + x + 8 \geqslant 0$. The second method reduces the problem to the totality of the system

$$\begin{cases} x^3 - 8 \geqslant 0, \\ x^3 + x + 8 \geqslant x^3 - 8; \\ x^3 - 8 < 0, \\ x^3 + x + 8 \geqslant -x^3 + 8, \end{cases}$$

which in turn comes down to the totality of the system

$$\begin{cases} x \geqslant 2, \\ x \geqslant -16; \end{cases}$$

$$\begin{cases} x < 2, \\ x(2x^2 + 1) \geqslant 0. \end{cases}$$

Solution of the first: $x \geqslant 2$, solution of the second: $0 \leqslant x < 2$.

Answer: $x \geqslant 0$.

It is easy to check that the equation $|A| = B$ can also be solved in two ways; it is equivalent to the system

$$\begin{cases} B \geqslant 0, \\ \pm B = A, \end{cases}$$

or

$$\begin{cases} A \geqslant 0; \\ A = B; \end{cases}$$

$$\begin{cases} A < 0, \\ -A = B. \end{cases}$$

Example 7 (MAI, 1970). Solve the equation:

$$x - \frac{|3x - 2|}{5} = 3 - \frac{2x - 5}{3}$$.

Solution. After simple transformations we get

$$3 |3x - 2| = 25x - 70$$.

Let's use the first method. After the equation is equivalent to the totality of the system

$$\begin{cases} 25x - 70 \geqslant 0, \\ 3(3x - 2) = 25x - 70; \\ 25x - 70 \geqslant 0, \\ 3(3x - 2) = -25x + 70. \end{cases}$$

Solution of the first system $x = 4$; the second system is incompatible.

Answer: $x = 4$.

Example 8 (MSU, Faculty of Physics, 1963). The most common solutions to the equation are:

$$\begin{cases} x^2 - \frac{3}{2}x - 1 = -x^2 - 4x + \beta. \end{cases}$$

Solution. In this case, the first method, including the sign of the right-hand side, is inconvenient, since the parameter $\beta$ will appear not only in the equation, but also in the corresponding inequality. Let's use the second method.

The proposed equation is equivalent to the following set of systems:

$$\begin{cases} x^2 - \frac{3}{2}x - 1 \geqslant 0, \\ x^2 - \frac{3}{2}x - 1 = -x^2 - 4x + \beta; \end{cases}$$

$$\begin{cases} x^2 - \frac{3}{2}x - 1 < 0, \\ -(x^2 - \frac{3}{2}x - 1) = -x^2 - 4x + \beta. \end{cases}$$

The first system is reduced to the system

$$\begin{cases} x \leqslant -\frac{1}{2}, x \geqslant 2, \\ x_1 = \frac{-5 - \sqrt{57 + 32\beta}}{8}, \\ x_2 = \frac{-5 + \sqrt{57 + 32\beta}}{8}. \end{cases}$$

Since $x_1 < 0$, we must satisfy the inequalities $x_1 \leqslant -\frac{1}{2}, x_2 \leqslant -\frac{1}{2}, x_2 \geqslant 2$.

Substituting their expressions for $x_1$ and $x_2$ and solving irrational inequalities with respect to $\beta$, we obtain
