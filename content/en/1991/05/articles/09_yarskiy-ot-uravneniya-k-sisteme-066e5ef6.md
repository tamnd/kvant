---
id: 1991-5-yarskiy-ot-uravneniya-k-sisteme-066e5ef6
issue: kvant_1991_5
year: 1991
number: "5"
title: From equation to system
authors:
  - Ярский А. С.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 64
page_last: 66
page_labels: 62, 64
lang: en
source: kvant_digital
extraction: vision
content_sha256: 859ea3420350ee501f0f26abe87853f4aca9a954e70eb2178433e548ff1bfb7b
prompt_sha256: draft-1
translated_from: content/ru/1991/05/articles/09_yarskiy-ot-uravneniya-k-sisteme-066e5ef6.md
source_content_sha256: d023ff93d767442bbf6bc6a84c9d9ec3eb0c3ffaa8847f3c1bba03a3db0d801d
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 62⟧

---
running_head:
folio:
---

From equation to system
Candidate of Physical and Mathematical Sciences A. YARSKY

Let's start with an example that is fairly typical for entrance exams.
Problem 1 (MIEM, 1982). Solve the equation
$$\sqrt{x+2} - \sqrt{x-a+2} = 1.$$
Obviously examples of this type are solved by squaring them twice. In this case, it becomes necessary to obtain readings acquired as a result of squaring extraneous roots, which, if there is a parameter in the equation, turns out to be a rather difficult task. We'll try to do things differently.
Solution. Let's introduce new unknowns
$$\begin{cases} u = \sqrt{x+2} \geq 0, \\ v = \sqrt{x-a+2} \geq 0. \end{cases}$$
The unknowns $u$ and $v$ are related by equality
$$u^2 - v^2 = a,$$
and the original equation takes the form
$$u - v = 1.$$
Thus, from the equation we came to the system
$$\begin{cases} u - v = 1, \\ u^2 - v^2 = a, \end{cases}$$
which is easily solved:
$$\begin{cases} u - v = 1, \\ (u - v)(u + v) = a \iff \begin{cases} u - v = 1, \\ u + v = a \iff \end{cases} \\ u = (a + 1)/2, \\ v = (a - 1)/2.$$
So,
$$\begin{cases} \sqrt{x+2} = (a+1)/2 \geq 0, \\ \sqrt{x-a+2} = (a-1)/2 \geq 0, \end{cases}$$
where do we get it from

Answer: $x = \frac{(a+1)^2}{4} - 2$ for $a \geq 1,$ for $a < 1$ there are no solutions.
Problem 2: Solve the equation
$$\sqrt[3]{2-x} + \sqrt{x-1} - 1 = 0.$$
Solution. Let's introduce the unknowns
$$u = \sqrt[3]{2-x}, v = \sqrt{x-1} \geq 0.$$
Then
$$\begin{cases} u^3 + v^2 = 1, \\ u + v = 1. \end{cases}$$

Hence,
$$u^3 + u^2 - 2u = 0,$$
whence $u \in \{0, 1, -2\}$, so system (1) has 3 solutions: (0; 1), (1; 0), (-2; 3), after which it is found.
Answer: 2; 1; 10.
Of course, to find the value of $x$ there is no need to consider both correspondences of system (6) at the final stage. But in this case, verification will be required to complete the solution.
When moving from an equation to a system, generally speaking, several unknowns may arise, a complex system has emerged, it is not clear what is taken to be new unknowns, etc.
Problem 3: Solve the equation
$$\sqrt[4]{97-x} + \sqrt[4]{x-15} = 4.$$
Solution. By entering unknowns
$$u = \sqrt[4]{97-x} \geq 0, v = \sqrt[4]{x-15} \geq 0,$$
we come to the system
$$\begin{cases} u^4 + v^4 = 82, \\ u + v = 4. \end{cases}$$

Next,
$$u^4 + v^4 = ((u + v)^2 - 2uv)^2 - 2u^2v^2,$$
and since $u + v = 4$, then
$$u^4 + v^4 = (16 - 2uv)^2 - 2u^2v^2.$$
We get a quadratic equation for $t = uv$:
$$(16 - t)^2 - 2t^2 = 82.$$
Hence $t = 29$ or $t = 3$. Taking into account (2) we obtain

⟦folio 64⟧

---
running_head:
folio:
---

$$y = x^2 + 1,$$
let's reduce the equation to the form
$$\frac{y(y + 2x) + x^2}{y^2 - x^2} = \frac{y}{x}.$$

After replacing $y/x = t$ we get the equation
$$\frac{t(t + 2) + 1}{t^2 - 1} = t,$$ or $t + 1 = t(t - 1),$
having roots $t_{1,2} = 1 \pm \sqrt{2}$.
So, $\frac{x^2 + 1}{x} = 1 \pm \sqrt{2},$
i.e. $x^2 - (1 \pm \sqrt{2})x + 1 = 0$, from where we get

Answer: $(1 + \sqrt{2} \pm \sqrt{2\sqrt{2} - 1})/2.$

The introduction of additional unknowns is especially useful when solving systems of equations.

Problem 8. Solve the system
$$\begin{cases}
2x^2 + xy = 1, \\
\frac{9x^2}{2(1-x)^4} = 1 + \frac{3xy}{2(1-x)^2}.
\end{cases}$$

Solution. In the second equation of the system it is convenient to put
$$z = \frac{3x}{(1-x)^2}.$$

Then
$$z^2 = 2 + zy.$$ (4)

Now, dividing the first equation by $x^2$, we reduce it to the form
$$\left(\frac{1}{x}\right)^2 = 2 + \left(\frac{1}{x}\right)y$$ (5)

$(x \neq 0)$. What follows next: subtracting equation (5) from equation (4), we obtain
$$\left(z - \frac{1}{x}\right)\left(z + \frac{1}{x}\right) = \left(z - \frac{1}{x}\right)y,$$
from where either $z = 1/x$ or $z + 1/x = y$. In the first case we get
$$\frac{3x}{(1-x)^2} = \frac{1}{x},$$ i.e. $x = \frac{1}{2}(-1 \pm \sqrt{3}),$
$y = 2.$

In the second case, $xz + 1 = xy$, which together with the first equation of the original system gives $2x^2 + xz + 1 = 1$. And since $x \neq 0$, then $2x + z = 0$, i.e.

$$\frac{3x}{(1-x)^2} + 2x = 0.$$

This equation has no non-zero roots.
Answer: $((-1 \pm \sqrt{3})/2; 2).$

In conclusion, we suggest that you solve the following equations yourself.

Exercises
1. Solve equations
a) (MIEM, 1979) $\sqrt{x + 1} - \sqrt{a - x} = 1$;
b) $2\sqrt{3x - 1} + \sqrt{27 - 14x} = 1$;
r) $x = \sqrt{a - x} \sqrt{b - x} + \sqrt{b - x} \sqrt{c - x} + \sqrt{c - x} \sqrt{a - x}$;
d) $7\sqrt{4x^2 + 5x - 1} - 14\sqrt{x^2 - 3x + 3} = 17x - 13$;
e) $(x^2 + 3x - 4)^3 + (2x^2 - 5x + 3)^3 = (3x^2 - 2x - 1)^3$;
j) (LSU, physics, 1974)

$$\frac{x^2}{x - 1} + \sqrt{x - 1} + \frac{\sqrt{x - 1}}{x^2} = \frac{x - 1}{x^2} + \frac{1}{\sqrt{x - 1}} + \frac{x^2}{\sqrt{x - 1}};$$

3) (MAY 1973) $\sqrt{3 - x} - \sqrt{\frac{1 - x}{2 - x}} = 1$;
i) (MIREA, 1986) $\sqrt{7x^2 + 8x + 10} - \sqrt{7x^2 - 8x + 10} = 2x$;
j) $(x^2 + 2x - 5)^2 + 2(x^2 + 2x - 5) = x + 5$;
l) $\sqrt{a - \sqrt{a + x}} = x$;
m) $\frac{(x - 1)^2x}{(x^2 - x + 1)^2} = \frac{2}{9}$;
n) $\frac{x^2 - 10x + 15}{x^2 - 6x + 15} = \frac{3x}{x^2 - 8x + 15}$;
o) $\frac{1}{x} + \frac{1}{\sqrt{1 - x^2}} = \frac{35}{12}$;
n) $\frac{x^4 + 4}{x^2 + 2} = 5x$;
p) $x^2 + \frac{25x^2}{(x + 5)^2} = 11.$

2. Solve inequalities
a) $\sqrt{x - \frac{1}{x}} - \sqrt{1 - \frac{1}{x}} > \frac{x - 1}{x}$;
b) $\sqrt{12 - \frac{12}{x^2}} + \sqrt{x^2 - \frac{12}{x^2}} < x^2.$

3. Solve Systems of Equation
a) (NSU, geology. Faculty, 1976)

$$\begin{cases}
\sqrt{-1 - x} - \sqrt{2y - x} = 1, \\
\sqrt{1 - 2y} + \sqrt{2y - x} = 4;
\end{cases}$$
