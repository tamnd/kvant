---
id: 1970-10-margulis-mordkovich-radunskiy-reshaya-neravenstvo-s-parametrom-214ec59c
issue: kvant_1970_10
year: 1970
number: "10"
title: Solving inequality with parameter...
authors:
  - Маргулис А. Я.
  - Мордкович А. Г.
  - Радунский Б. А.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 55
page_last: 61
page_labels: 53-59
tag: 3JN9
lang: en
source: kvant_digital
extraction: vision
content_sha256: 5f33a262e4dae1fbab9f1c2e6206eba49e8e9e9782e325367e0fd74b7ec62113
prompt_sha256: draft-1
translated_from: content/ru/1970/10/articles/10_margulis-mordkovich-radunskiy-reshaya-neravenstvo-s-parametrom-214ec59c.md
source_content_sha256: 532b7243d436ece7ff876473d88fa0bbf53fc9c46b0ac7b99432a42b7c547864
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 53⟧

1. RESEARCH ALL CASES CAREFULLY

Suppose we need to solve the following linear inequality for $x$:

$$\frac{3ax + 4}{3a + 9} < \frac{x}{a + 3} + \frac{3a - 5}{3a - 9}.$$

It would seem, what could be simpler? Following the well-known school rule, we collect all terms containing $x$ on the left side of the inequality, and free terms on the right:

$$\frac{3ax}{3a + 9} - \frac{x}{a + 3} < \frac{3a - 5}{3a - 9} + \frac{4}{3a + 9},$$

and forgive the resulting inequality:

$$\frac{a - 1}{a + 3} x < \frac{a^2 - 1}{a^2 - 9}.$$

(1)

Now all that remains is to divide both sides of the inequality by the coefficient of the unknown.

But it is precisely at this step - when dividing both sides of inequality (1) by the coefficient of the unknown - that you need to be extremely careful, or the inequality contains a parameter.

An inequality with a parameter is essentially a set of inequalities, each of which is obtained from a parameter given at a specific value. Imagine that a friend asked you to solve an inequality with a parameter, and he himself thought of a specific number for the value of the parameter. You do not know the intended meaning, and your task is not to let yourself be taken by surprise, to carefully examine all the cases that may present themselves. Once you've solved the inequality, and buddy

announced to you the value of the parameter he intended, you must find in your answer a case that relates specifically to this value.

Let's return to our example. There may be 4 cases:

1) one or both parts of the inequality do not make sense;
2) the coefficient for the unknown is equal to;
3) the coefficient for the unknown is positive;
4) the coefficient for the unknown is negative.

The first case will occur at $a = \pm 3$. For these values ​​of the parameter, inequality (1) has no solutions.

The second case will occur at $a = 1$. In this case, the value of the parameter inequality (1) takes the form $0 \cdot x < 0$ and obviously has no solutions.

The third case will occur at $a < -3$ or at $a > 1$, $a \neq 3$. Dividing both sides of inequality (1) by the positive number $\frac{a - 1}{a + 3}$, we obtain:

$$x < \frac{a + 1}{a - 3}.$$

The fourth case will occur at $-3 < a < 1$. Dividing both sides of inequality (1) by the negative number $\frac{a - 1}{a + 3}$, we obtain: $x > \frac{a + 1}{a - 3}$.

Combining the results obtained, we write down

Answer: if $a = 1$, $a = \pm 3$, then there are no solutions;

if $a < -3$, $1 < a < 3$, $a > 3$, then

$$x < \frac{a + 1}{a - 3};$$

⟦folio 54⟧

if $-3 < a < 1$, then $x > \frac{a+1}{a-3}$.

The given answer contains a solution to inequality (1) for any value of the parameter. This is precisely the main goal when solving an inequality with a parameter.

Using figure 1, solve the inequality $\cos x \geq a$ and prove that the answer is:
if $a \leq -1$, then $-\infty < x < \infty$;
if $-1 < a < 1$ then $m_1 + 2k\pi \leq x \leq m_2 + 2k\pi$,
where $m_1 = -\arccos a$, $m_2 = \arccos a$;
if $a = 1$, then $x = 2k\pi$;
if $a > 1$, then there are no solutions.
($k = 0, \pm 1, \dots$)

2. DON'T RUSH TO CONCLUSIONS

Let's look at another simple example. Let's solve the inequality $\sqrt{x} > a$. It is tempting to write $x > a^2$ and claim that this entry contains all the solutions to the inequality. But one should not rush to conclusions when solving an inequality with a parameter: after all, $a$ can be less than zero; then the solution to the inequality $\sqrt{x} > a$ will be any non-negative value $x$; if $a \geq 0$, then squaring both sides of the inequality $\sqrt{x} > a$ is an equivalent transformation; having polished it, we get $x > a^2$.

Answer: if $a < 0$, then $x \geq 0$;
if $a \geq 0$, then $x > a^2$.

Now let's move on to more complex examples.

Example 1. Solve inequality $\sqrt{x^2 + x} < a - x$. (2)

Solved and e. The range of admissible values ​​of the unknown definition of inequalities $x^2 + x \geq 0$. In addition, it is clear that if $a - x \leq 0$, then inequality (2) has no solution, so we restrict ourselves to the ray $a - x > 0$. But if the condition is met
$$\begin{cases} x^2 + x \geq 0, \\ a - x > 0 \end{cases}$$ (3)

both sides of inequality (2) can be

⟦folio 55⟧

enter into a square (this will not lead to the appearance of construction solutions). After squaring and bringing similar terms, we get:
$$ (1+2a)x < a^2. $$
(4)

Inequality (4) has the following solutions:

$$ \text{ если } a = -\frac{1}{2}, $$
$$ \text{ то } -\infty < x < \infty; $$
$$ \text{ если } a > -\frac{1}{2}, \text{ то } x < \frac{a^2}{1+2a}; $$
$$ \text{ если } a < -\frac{1}{2}, \text{ то } x > \frac{a^2}{1+2a}. $$

But one should not rush to conclusions and assume that this has resulted in solutions to inequality (2). From the found solutions to inequality (4), it is necessary to display those that satisfy conditions (3). To facilitate further work, let us solve for $x$ the system of inequalities (3) for any value $a$.

The first inequality of system (3) has solutions $x \leq -1$ or $x \geq 0$. The second inequality has solutions $x < a$. Further reasoning depends on how the number $a$ is positioned relative to the numbers $-1$ and $0$.

Having analyzed the cases $a \leq -1$, $-1 < a \leq 0$, $a > 0$, we obtain the following solutions to system (3):

a) if $a \leq -1$, then $x < a$;
b) if $-1 < a \leq 0$, then $x \leq -1$;
b) if $a > 0$, then $x \leq -1$ or $0 \leq x < a$.

Let us now select from the solutions to inequality (4) found above those that satisfy the just obtained conditions $a$), $6$), $b$). These will be the solutions to the original inequality (2).

For $a = -\frac{1}{2}$, inequality (4) is satisfied by all real numbers. Condition (6) forces us to limit ourselves to the values ​​of $x \leq -1$. So, if $a = -\frac{1}{2}$, then inequality (2) has solutions: $x \leq -1$.

For $a > -\frac{1}{2}$, inequality (4) has solutions $x < \frac{a^2}{1+2a}$. Let us consider, in accordance with conditions (6) and (b), two cases:

$$ -\frac{1}{2} < a \leq 0 \text{ и } a > 0. $$

In the first case, we need to find all $x$ satisfying the system of inequalities $x \leq -1$ and $x < \frac{a}{1+2a}$. Thus the values ​​of $x \leq -1$.

So, if $-\frac{1}{2} < a \leq 0$, then inequality (2) has solutions $x \leq -1$.

In the second case, that is, for $a > 0$, we need to take such $x$ that satisfy one of the systems of inequalities:

$$ \begin{cases} x < \frac{a^2}{1+2a}, \\ x \leq -1, \end{cases} $$
$$ \begin{cases} x < \frac{a^2}{1+2a}, \\ 0 \leq x < a. \end{cases} $$

The first of these systems has solutions $x \leq -1$. To solve the second system, you need to compare the numbers $a$ and $\frac{a^2}{1+2a}$. Let's make the difference $a - \frac{a^2}{1+2a} = \frac{a(a+1)}{1+2a}$.

It is clear that for $a > 0$ this difference is positive, hence $\frac{a^2}{1+2a} < a$. This means that the second system has the following solutions: $0 \leq x < \frac{a^2}{1+2a}$.

So, if $a > 0$, then inequality (2) has solutions $x \leq -1$;
$$ 0 \leq x < \frac{a^2}{1+2a}. $$

For $a < -\frac{1}{2}$, inequality (4) has solutions $x > \frac{a^2}{1+2a}$. Let us consider, in accordance with conditions (6) and (b), two cases:

$$ a \leq -1 \text{ и } -1 < a < -\frac{1}{2}. $$

⟦folio 56⟧

In the first case, we need to solve the following system of inequalities:
$$\begin{cases} x > \frac{a^2}{1+2a}, \\ x < a. \end{cases}$$

But from equality (5) it follows that for $a \leq -1$ the inequality $a \leq \frac{a^2}{1+2a}$ is valid, so the system has no solution. Thus, if $a \leq -1$, then inequality (2) has no solution.

In the second case, that is, for $-1 < a < -\frac{1}{2}$, we need to solve the following system of inequalities:
$$\begin{cases} x > \frac{a^2}{1+2a}, \\ x \leq -1. \end{cases}$$

Let's compare the numbers $\frac{a^2}{1+2a}$ and $-1$, for which we make up the difference
$$\frac{a^2}{1+2a} - (-1) = \frac{(a+1)^2}{1+2a}.$$

For $-1 < a < -\frac{1}{2}$ this difference is negative, which means $\frac{a^2}{1+2a} < -1$.

But then the last system of inequalities has the following solutions:
$$\frac{a^2}{1+2a} < x \leq -1.$$

This is what the solutions to inequality (2) look like in the case of $-1 < a < -\frac{1}{2}$.

Combining the results obtained, we write down

Answer: if $a \leq -1$, then there is no solution;

if $-1 < a < -\frac{1}{2}$, then
$$\frac{a^2}{1+2a} < x \leq -1;$$
if $-\frac{1}{2} \leq a \leq 0$ then $x \leq -1;$
if $a > 0$ then $x \leq -1;$
$0 \leq x < \frac{a^2}{1+2a}$.

3. BE CAREFUL

Example 2. Solve inequality
$$\frac{1}{x} + ax > 1.$$

Solved and e. Let us transform the inequality to the form
$$\frac{ax^2 - x + 1}{x} > 0.$$ (6)

Let's factorize the numerator by first finding its roots:
$$x_1 = \frac{1 + \sqrt{1-4a}}{2a};$$
$$x_2 = \frac{1 - \sqrt{1-4a}}{2a}.$$

Here you need to be careful not to miss the case of a negative discriminant of a quadratic trinomial.

This will be at $a > \frac{1}{4}$. But then $ax^2 - x + 1 > 0$ for all $x$ and, therefore, inequality (6) in this case has a solution $x > 0$.

For $a = \frac{1}{4}$, $x_1 = x_2 = 2$, and inequality (6) can be rewritten as follows:
$$\frac{(x - 2)^2}{4x} > 0.$$

After it, the inequality has a solution $0 < x < 2$, $x > 2$.

Let now $a < \frac{1}{4}$. Then inequality (6) is transformed to the form
$$\frac{a(x - x_1)(x - x_2)}{x} > 0$$ (7)

and we replace that two cases should be distinguished: $a > 0$ or $a < 0$ (the case where $a = 0$ is considered).

If $0 < a < \frac{1}{4}$, then inequality (7) takes the form
$$\frac{(x - x_1)(x - x_2)}{x} < 0,$$
whence (taking into account that for $a < 0$ $x_1 < 0 < x_2$) we obtain $x < x_1; 0 < x < x_2$.

⟦folio 57⟧

For $a=0$ the original inequality takes the form
$$\frac{1}{x} > 1.$$
Solving this inequality, we get:
$$0 < x < 1.$$
Combining all the results obtained, we write down
Answer: if $a < 0$, then $x < \frac{1 + \sqrt{1-4a}}{2a}$ or $0 < x < \frac{1 - \sqrt{1-4a}}{2a}$;
if $a=0$, then $0 < x < 1$;
if $0 < a < \frac{1}{4}$, then $x > \frac{1 + \sqrt{1-4a}}{2a}$, or $\frac{1 - \sqrt{1-4a}}{2a} > x > 0$;
if $a = \frac{1}{4}$, then $0 < x < 2$, or $x > 2$;
if $a > \frac{1}{4}$, then $x > 0$.

Example 3. Solve inequality $\log_{1/2}(x^2 - 2x + a) > -3$.
Solution i.e. This inequality is equivalent to the system of inequalities
$$\begin{cases} x^2 - 2x + a > 0, \\ x^2 - 2x + a < 8. \end{cases}$$
Let's rewrite the system as follows:
$$\begin{cases} (x-1)^2 > 1-a, \\ (x-1)^2 < 9-a. \end{cases}$$
Let us denote $x-1$ by $y$ and rewrite the resulting system in the form of a chain of inequalities:
$$1-a < y^2 < 9-a.$$
If we now pay attention, we will notice that for $a \geq 9$ this chain has no solution, and for $a > 1$ the inequality $y^2 > 1-a$ is satisfied for all $y$, therefore the solutions to the chain in the case of $1 < a < 9$ will be solutions to the inequality $y^2 < 9-a$, that is, $-\sqrt{9-a} < y < \sqrt{9-a}$.
If, finally, $a \leq 1$, then, solving the chain, we get
$$-\sqrt{9-a} < y < -\sqrt{1-a};$$
$$\sqrt{1-a} < y < \sqrt{9-a}.$$

Answer: if $a \leq 1$, then
$$1 - \sqrt{9-a} < x < 1 - \sqrt{1-a},$$
or $1 + \sqrt{1-a} < x < 1 + \sqrt{9-a}$;
if $1 < a < 9$, then
$$1 - \sqrt{9-a} < x < 1 + \sqrt{9-a};$$
if $a \geq 9$, then there are no solutions.
Example 4. Solve inequality
$$\cos x - \frac{1}{\cos x} \leq a (a > 0).$$
(Physics Department of Moscow State University, 1966)
Solved i.e. We note first of all that the inequality is satisfied by all $x$ for which $\cos x > 0$ (then $\frac{1}{\cos x} \geq 1 \geq \cos x$).
We will now look for solutions of averages $x$ for which $\cos x < 0$.
In this case, inequality (8) takes the form
$$\cos^2 x - a \cos x - 1 \geq 0,$$
from where we get $\cos x \geq \frac{a + \sqrt{a^2 + 4}}{2}$ or $\cos x \leq \frac{a - \sqrt{a^2 + 4}}{2}$. Since we are considering the case $\cos x < 0$, we discard the inequality $\cos x \geq \frac{a + \sqrt{a^2 + 4}}{2}$.

So, $\cos x \leq \frac{a - \sqrt{a^2 + 4}}{2}$. Our conclusion should not escape the fact that for some values ​​of $a$ the number $\frac{a - \sqrt{a^2 + 4}}{2}$ may turn out to be less than -1 (after all, in this case the last inequality will not have a solution). Therefore, we still have to compare the numbers $\frac{a - \sqrt{a^2 + 4}}{2}$ and -1. It's easy to show that $\frac{a - \sqrt{a^2 + 4}}{2} > -1$ (check it out!).

Answer: $-\frac{\pi}{2} + 2k\pi < x < \frac{\pi}{2} + 2k\pi$, or агссos $\frac{a - \sqrt{a^2 + 4}}{2} + 2k\pi \leq x \leq 2\pi - \frac{\pi}{2}$
arccos $\frac{a - \sqrt{a^2 + 4}}{2} + 2k\pi (k = 0, \pm 1, \pm 2, \ldots)$

⟦folio 58⟧

4. DON'T FORGET ABOUT THE GRAPHIC METHOD

Example 5. Solve inequality
$$2\sqrt{x+a} > x+1.$$

Solution. The ODZ is determined by the inequality $x+a \geq 0$. Correspondence on figure 2 the half-plane under the line $x+a=0$ is shaded in this color (the region in which there cannot be solutions). The sign of the right side of inequality (9) is unknown; it is impossible to square both sides of the inequality. Let's consider two cases:
1. $x+1 < 0$ or $x < -1$ — inequality (9) is satisfied automatically. On figure 2 the corresponding part of the ODZ is painted in orange color and designated I.
2. $x+1 \geq 0$ or $x \geq -1$. In this case, you can square both sides of inequality (9). We get $4(x+a) > x^2+2x+1$, whence $a > \frac{1}{4}(x-1)^2$. At figure 2 the parabola $a = \frac{1}{4}(x-1)^2$ is drawn by point and only at $x \geq -1$ (in accordance with the conditions of case 2). Region,

where $a > \frac{1}{4}(x-1)^2$ on figure 2 is also colored orange, but is designated II.

Thus, the region colored by Orzhekov on figure 2 gives a set of pairs $(x; a)$ satisfying inequality (9). To obtain a solution to inequality (9) when determining the value of $a$, let us draw a straight line parallel to the axis $Ox$ through the corresponding point on the axis $Oa$. The abscissas of the points of the segment of this line, enclosed in the “Org region”, will be the solutions to inequality (9) for the selected value of the parameter. To write the answer, we need to rewrite the equation for the linear constraint of the “orjekvuo region” as follows: $x = -a$; $x = 1 - 2\sqrt{a}$ (equation of the parabola branch on the segment $-1 \leq x \leq 1$); $x = 1 + 2\sqrt{a}$ (equation of the parabola branch at $x \geq 1$). Equations $x = 1 - 2\sqrt{a}$ and $x = 1 + 2\sqrt{a}$ are derived from equation $a = \frac{1}{4}(x-1)^2$.

Answer: if $a \leq 0$, then there is no solution;

if $0 < a \leq 1$, then
$$1 - 2\sqrt{a} < x < 1 + 2\sqrt{a};$$
if $a > 1$, then $-a \leq x < 1 + 2\sqrt{a}$.

Note that with this method, the solutions $x$ and $a$ are completely equal, and only to formalize the answer we had to “distribute roles” between them *).

Example 6. Solve inequality
$$\log_{\sqrt{2a}}(a + 2x - x^2) < 2.$$

Solution. The CL of inequality is determined by the following conditions:
$a > 0$, $a \neq \frac{1}{2}$, $a > x^2 - 2x$.

*) Example 5 is taken from the book by M. I. Bashmakov and Z. I. Borevich “Competition problems in mathematics” (LSU Publishing House, 1968). In this book the reader will find a number of examples of inequalities with a parameter, many of which are solved graphically.

⟦folio 59⟧

Fig. 3.

Correspondence on figure 3 those areas are shaded and those lines are drawn dotted, all points of which do not belong to the ODZ and therefore cannot be solutions to inequality (10).

If $0 < a < \frac{1}{2}$, then inequality (10) transforms to the form
$$a + 2x - x^2 > (\sqrt{2a})^2,$$
where
$$a < -x^2 + 2x.$$

This means that in this case, inequality (10) is satisfied by those pairs $(x; a)$ that serve as solutions to the following system:

$$\begin{cases} a > 0, \\ a < \frac{1}{2}, \\ a > x^2 - 2x, \\ a < -x^2 + 2x. \end{cases}$$

These solutions fill zone I at figure 3.

If $a > \frac{1}{2}$, then inequality (10) transforms to the form
$$a + 2x - x^2 < (\sqrt{2a})^2,$$
from where $a > -x^2 + 2x.$

This means that in this case, inequality (10) is satisfied by those pairs $(x; a)$ that serve as solutions to the following system:

$$\begin{cases} a > \frac{1}{2}, \\ a > x^2 - 2x, \\ a < -x^2 + 2x. \end{cases}$$

These solutions will fill zone II by figure 3.

Answer: if $a \leq 0$ or $a = \frac{1}{2}$, then there are no solutions;

if $0 < a < \frac{1}{2}$, then
$$1 - \sqrt{1 - a} < x < 1 + \sqrt{1 - a};$$
if $\frac{1}{2} < a \leq 1$, then
$$1 - \sqrt{1 + a} < x < 1 + \sqrt{1 - a};$$
$$1 + \sqrt{1 - a} < x < 1 + \sqrt{1 + a};$$
if $a > 1$, then
$$1 - \sqrt{1 + a} < x < 1 + \sqrt{1 + a}.$$

5. CONCLUSION

When solving an inequality with a parameter, carefully examine all cases, do not rush to conclusions, be careful and do not forget about the graphical method.

Exercises

Solve the following inequalities for $x$:

1. $2x + 3(ax - 8) + \frac{x}{3} < 4(x + \frac{1}{2}) - 5.$
2. $\frac{2ax + 3}{5x - 4a} < 4.$
3. $\left| \frac{ax - 5}{3} + x \right| < 3.$
4. $\sqrt{x} - \sqrt{x - 1} > a.$
5. $tg x + ctg x \leq a (a > 0).$
6. $\lg^2 x - 2a \lg x - a^2 + 2 > 0.$
7. $\sqrt{a^2 - x^2} + \sqrt{2ax - x^2} > a$ (use graphical method).
8. $\log_x(x - a) > 2$ (use graphical method).
