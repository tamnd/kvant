---
id: 1990-5-zatakavay-reshenie-neravenstv-metodom-intervalov-270c2c09
issue: kvant_1990_5
year: 1990
number: "5"
title: Solving inequalities using the interval method
authors:
  - Затакавай В. В.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 65
page_last: 67
page_labels: 63-65
lang: en
source: kvant_digital
extraction: vision
content_sha256: 369aefd76af9f7376c7b77abeac32a069fc6c2844de7fbb1817bf5feec365fa1
prompt_sha256: draft-1
translated_from: content/ru/1990/05/articles/19_zatakavay-reshenie-neravenstv-metodom-intervalov-270c2c09.md
source_content_sha256: 6776b800ecbdd8d2803462daff8586e33f596bb3a7261c3435c9bb9fa208c60f
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 63⟧

---
running_head:
folio:
---

Solution
inequalities
method
intervals

Candidate of Pedagogical Sciences
B. LOCK UP

This article is addressed to high school students (grades 10-11) and can be used in preparing for university entrance exams.

When solving inequalities, two standard approaches are usually used. Let's consider them using the example of a simple inequality

$$\frac{x-1}{x-2} > 0.$$

This inequality applies to two systems:

$$\begin{cases} x-1 > 0, \\ x-2 > 0 \end{cases}$$ or $$\begin{cases} x-1 < 0, \\ x-2 < 0. \end{cases}$$

From the first system we get $x > 2$, or $(2; +\infty)$. From the second - $x < 1$, or $(-\infty; 1)$. Solution to the original inequality: $(-\infty; 1) \cup (2; \infty)$.

Another method is the well-known interval method. His idea is very simple. So, in this case, the numerator of the fraction $\frac{x-1}{x-2}$, turning to 0 at $x=1$, retains the minus sign on the half-line $(-\infty; 1)$ and the plus sign on the half-line $(1; \infty)$.

The denominator of the fraction, turning to 0 at $x=2$, retains the “minus” sign on the half-line $(-\infty; 2)$ and the “plus” sign on $(2; \infty)$. Thus, a fraction can change sign only when passing through the points $x=1$ and $x=2$ and, therefore, retains one or another sign

Fig. 1.

⟦folio 64⟧

---
running_head:
folio:
---

at each of three intervals:
$(-\infty; 1), (1; 2)$ and $(2; +\infty)$ (Fig. 1).

With such a simple example, it is easy to recall the idea of ​​the invertal method, but it is impossible to see any of its noticeable advantages. More complex inequalities are another matter.

Example 1.

$$\frac{1}{x-1} + \frac{1}{x-2} \geq \frac{1}{x-3}.$$

Solution. After rearranging the fraction $\frac{1}{x-3}$ to the left side and bringing it to a common denominator, we obtain:

$$\frac{x^2 - 6x + 7}{(x-1)(x-2)(x-3)} \geq 0.$$

The first approach to solving this inequality - using a system of inequalities - leads to the consideration of a fairly large number of the system. The interval method in this case of the city is more rational. The function $f(x) = \frac{x^2 - 6x + 7}{(x-1)(x-2)(x-3)}$ is defined on the entire number line with the exception of the “zeros” of the denominator - points 1, 2, 3. The zeros of the numerator are $3 - \sqrt{2}$ and $3 + \sqrt{2}$. Let's name all the points on the axis. On each of the six intervals formed, the function $f(x)$ retains one or another sign.

The answer is actually “drawn” (Fig. 2), all that remains is to write it down carefully.

Fig. 2.

Answer: $(1; 3 - \sqrt{2}) \cup (2; 3) \cup [3 + \sqrt{2}; +\infty)$.

In the example considered, the signs in the intervals of constant sign of the function are crossed. However, one should not, of course, make a “generalization” that this will always happen.

Example 2.

$$\frac{(x+2)^2}{x-1} \geq 0.$$

Solution. This inequality scales is “insidious.” People often solve it as follows: since $(x+2)^2 \geq 0$ for all $x$, the sign of the fraction depends on the sign of the denominator, which gives us $x > 1$. The answer is very unclear: the isolated point $x = -2$ also satisfies the non-stringent inequality. The invertal method, with its “compactness”, helps to a greater extent to avoid this type of error (Fig. 3).

Fig. 3.

It remains to write down the intervals and points at which the function $f(x) = \frac{(x+2)^2}{x-1}$ takes non-negative values.

Answer: $\{-2\} \cup (1; +\infty)$.

Note that in this example, when passing $x = -2$, the sign of the function did not change. This is due to the “multiplicity” of the zero of the function. Obviously, if the multiplicity of zero is even (in this case, the multiplicity of zero $x = -2$ is two), then the sign of the function does not change when passing such a point; if the multiplicity of zero is odd, then the sign of the function changes to the opposite. At school, as a rule, they find out the sign of a function on each of the intervals of constant sign. This is reasonable, but in the practice of entrance exams there are “inconvenient” intervals on scales: determining the sign on them is associated with computational difficulties. Therefore, taking into account the multiplicity of the root often makes decisions easier.

The acceptability of the inverseval method is not limited to solving rational inequalities. The universal method is based on a fairly clear property of continuous functions: “If on the interval $(a; b)$ the function $f(x)$ is continuous and does not vanish, then it retains a constant sign on this interval”*).

Let's look at a few more examples.

*) See, for example, the textbook “Algebra and the beginnings of analysis 9-10”, M.: Prosveshchenie, 1988, p. 98.

⟦folio 65⟧

---
running_head:
folio:
---

$$\frac{\sqrt{2-x} + 4x - 3}{x} \geqslant 2.$$

Solution. Domain $x \leqslant 2$, $x \neq 0$. Let us reduce the inequality to the form
$$\frac{\sqrt{2-x} + 2x - 3}{x} \geqslant 0.$$

In order to find the zero of the numerator, it is necessary to solve the irrational equation $\sqrt{2-x} = 3 - 2x$. When solving irrational equations, due to squaring, construction of solutions may arise that need to be eliminated (in this case, $x = 1\frac{3}{4}$ - construction of the solution).

So the numerator is zero at $x = 1$. The solution to the inequality is presented in figure 4.

Fig. 4.

Answer: $(-\infty; 0) \cup [1; 2]$.
Example 4.
$$\frac{1}{3 + \sqrt{9-x^2}} + \frac{1}{3 - \sqrt{9-x^2}} > \frac{1}{x}.$$

Solution. The scope of definition is found from the following conditions:
$$9 - x^2 \geqslant 0, 3 - \sqrt{9-x^2} \neq 0, x \neq 0, t. e. [-3; 0) \cup (0; 3].$$ Moreover, in this case it is important to know, since already at the preparatory stage after the estimated transformations, the expression $\sqrt{9-x^2}$ disappears, and the resulting inequality $\frac{6-x}{x^2} > 0$ has cities that are “wider” both in the scope of definition and in solutions.

The solution to the inequality $\frac{6-x}{x^2} > 0$, namely $(-\infty; 0) \cup (0; 6)$, limited by the domain of the original one, leads to the answer: $[-3; 0) \cup (0; 3]$.

Example 5.
$$\log_2 \sqrt{7-x} \cdot \log_{(x-1)} 4 \leqslant 2.$$

Solution. The domain of definition is given by the conditions $7-x > 0, x-1 > 0, x-1 \neq 1$, i.e. $(1; 2) \cup (2; 7)$.

At the preparatory stage we get:
$$\frac{\log_2 \sqrt{7-x}}{\log_4(x-1)} \leqslant 2,$$
and further,
$$\frac{\log_2(7-x) - 2\log_2(x-1)}{\log_2(x-1)} \leqslant 0.$$

The last inequality, taking into account the previously found domain of definition, is equivalent to the original inequality.

The zeros of the numerator are determined from the equation
$$\log_2(7-x) = 2\log_2(x-1).$$

When solving a logarithmic equation, there is a danger of acquiring roots: $7-x=(x-1)^2$, or $x^2-x-6=0$. Here the solution $x=3$ is the root of our logarithmic equation, and the solution $x=-2$ is the constructed root, since $-2-1=-3<0$.

Zero denominator $x=2$.

At figure 5 the solution to the original inequality is presented.

Fig. 5.

Answer: $(1; 2) \cup [3; 7)$.
Example 6.
$$\log_{(x^2-2x+1)} (3-x) \leqslant 1.$$

Solution. The example contains a “cunning” hint: the complete square of the difference at the base of the logarithm conveys the desire to get rid of the square:
$$\frac{1}{2}\log_{|x-1|} (3-x) \leqslant 1.$$

The considered logarithmic inequalities containing the sign of the model are associated with well-known difficulties. In my opinion, it is more rational to reduce the logarithm to some specific base, say to the base $e$, and use the interactive method.

The conditions $x^2-2x+1 \neq 0, x^2-2x+1 \neq 1, 3-x > 0$ give the domains of definition: $(-\infty; 0) \cup (0; 1) \cup (1; 2) \cup (2; 3).$
