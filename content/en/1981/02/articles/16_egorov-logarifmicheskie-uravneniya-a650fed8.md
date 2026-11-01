---
id: 1981-2-egorov-logarifmicheskie-uravneniya-a650fed8
issue: kvant_1981_2
year: 1981
number: "2"
title: Logarithmic equations
authors:
  - Егоров А. А.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 42
page_last: 45
page_labels: 40-43
tag: WSYQ
lang: en
source: kvant_digital
extraction: vision
content_sha256: a99644c27780effa6d12b6b7cf6de4f278c51122777c9ea75fc3c8c5bc821cca
prompt_sha256: draft-1
translated_from: content/ru/1981/02/articles/16_egorov-logarifmicheskie-uravneniya-a650fed8.md
source_content_sha256: 818e1bc23e40bf34389fd2560605fe22227d0fe72401333ecede502f45590e6d
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 40⟧

Logarithmic equations

In entrance exams, you often come across equations containing a variable under the logarithm sign. Such equations are usually called logarithmic.

The simplest logarithmic equation is an equation of the form $\log_a x = b$. If $a > 0$, $a \neq 1$ and $b > 0$, it has a single root $x = a^b$.

In what follows, we will often use the following properties of logarithms:

$$\log_a xy = \log_a x + \log_a y,$$

$$\log_a \frac{x}{y} = \log_a x - \log_a y,$$

$$\log_a x^\alpha = \alpha \log_a x,$$

$$\log_a x^\beta = \frac{1}{\beta} \log_a x,$$

$$\log_a x = \frac{\log_b x}{\log_b a}$$

(here everywhere $a > 0$, $a \neq 1$, $b > 0$, $b \neq 1$, $x > 0$, $y > 0$). It is also useful to remember this special case of formula (5):

$$\log_a x = \frac{1}{\log_x a}.$$

Let's now look at some common types of logarithmic equations.

Example 1: Solve the equation

$$\log_4 x + \log_1 x + \log_8 x^3 = 5.$$

Solution. Using property (4), we reduce all logarithms to base 2; taking into account property (3), we obtain

$$\frac{1}{2} \log_2 x - \frac{1}{4} \log_2 x + \log_2 x = 5,$$

whence $\frac{5}{4} \log_2 x = 5$, $\log_2 x = 4$, $x = 16$.

Answer. {16}.

Sometimes, after some transformations, the equation can be reduced to the form

$$f(\log_a x) = 0.$$

The solution of equation (6) after replacing $y = \log_a x$ and finding the roots of equation $f(y) = 0$ coincides with the solution of the simplest equations $\log_a x = y$. Therefore, the main task is to find transformations that bring the original equation to an equation of the form (6).

Example 2 (MIIGAiK, 1977). Solve the equation

$$(\log_x 9x^2) \cdot \log_3^2 x = 4.$$

Solution. Passing to base 3 logarithms, we obtain the equivalent equation

$$\frac{\log_3 9x^2}{\log_3 x} \cdot \log_3^2 x = 4,$$

whence $(2 + 2 \log_3 x) \cdot \log_3 x = 4$. Polling $y = \log_3 x$, we arrive at the quadratic equation $y^2 + y - 2 = 0$, from which either $y = -2$ or $y = 1$. It remains to solve the simplest equations $\log_3 x = -2$ and $\log_3 x = 1$.

Answer. $\left\{ \frac{1}{9}, 3 \right\}$.

Example 3: Solve the equation

$$x^{\lg x} = 10^2 \lg^2 x - 3 \lg x + 2.$$

Solution. Here $x$ is under the logarithm sign, and therefore $x > 0$. Taking logarithms of the left and right sides to base 10, we obtain the equivalent equation

$$\lg^2 x = 2 \lg^2 x - 3 \lg x + 2.$$

Polling $y = \lg x$, we arrive at the quadratic equation $y^2 - 3y + 2 = 0$, which has roots $y_1 = 1$ and $y_2 = 2$.

Answer. {10, 100}.

Quite often there are also equations of the form

$$\log_a f(x) = g(x)$$

or equations leading to the form (7).

Equation (7) is equivalent (for $a > 1$, $a \neq 1$) to equation $f(x) = a^{g(x)}$.

⟦folio 41⟧

Example 4: Solve the equation
$$\log_3(4 \cdot 3^{x-1}-1) = 2x-1.$$
Solution. This equation is equivalent to the following:
$$4 \cdot 3^{x-1}-1 = 3^{2x-1}.$$
Making the substitution $y=3^x$, we arrive at the quadratic equation
$$y^2-4y+3=0;$$
solving it, we find $y_1=1, y_2=3.$
Answer. {0,1}.
Equation of the form
$$\log_{g(x)}f(x)=a$$
(8)
equivalent to the system
$$\begin{cases}
f(x)=[g(x)]^a, \\
g(x)>0, \\
g(x)\neq 1.
\end{cases}$$

Example 5 (MSU, geological department, 1966). Solve the equation
$$\log_{(x+1)}(x^2+x-6)^2=4.$$
Solution. The equation is equivalent to the system
$$\begin{cases}
(x^2+x-6)^2=(x+1)^4, \\
x+1>0, \\
x+1\neq 1.
\end{cases}$$
We have $(x^2+x-6)^2-[(x+1)^2]^2=0$, from where
$$[x^2+x-6+(x+1)^2][x^2+x-6-(x+1)^2]=0,$$
so the equation of this system is equivalent to this:
$$(2x^2+3x-5)(x+7)=0,$$
from where $x_1=1, x_2=-\frac{5}{2}, x_3=-7.$
The system is satisfied only by the value $x=1$.
Answer. {1}.
In some cases, after transformation, the original equation is reduced to the form
$$\log_a f(x)=\log_a g(x).$$
(9)
It is easy to see that every root of equation (9) satisfies the system
$$\begin{cases}
f(x)=g(x), \\
f(x)>0.
\end{cases}$$

Conversely, if $x_0$ is a solution to system (9'), then $\log_a f(x_0)=\log_a g(x_0)$, so any solution to system (9') also satisfies equation (9). Thus, equation (9) is equivalent to system (9').

Example 6: Solve the equation
$$\log_8(7x^2-5x-6)=2\log_4\sqrt{3x-1}.$$
Solution. Reducing logarithms to base 2, we obtain, after simplifying, the equivalent equation
$$\log_2(7x^2-5x-6)=\log_2(3x-1),$$
which is equivalent to the system
$$\begin{cases}
7x^2-5x-6=3x-1, \\
3x-1>0.
\end{cases}$$
Solving the system, we get
$$x=\frac{4+\sqrt{51}}{7}$$
($3x_2-1<0$).
Answer. $\{\frac{4+\sqrt{51}}{7}\}$.

Let us now note some mistakes made by students when solving logarithmic equations.
Most often, these errors are associated with incorrect applications of formulas for taking logarithms of products, fractions, and powers.
For example, when solving the equation from Example 5, some schoolchildren write this:
“It follows from the condition that $2\log_{(x+1)}(x^2+x-6)=4$, whence $x^2+x-6=(x+1)^2$ or $x=-7$. But $x=-7$ does not satisfy the original equation, and therefore it has no roots.”
The reason for the loss of the root $x=1$ was the application of the formula
$$\log_a x^2=2\log_a x,$$ which is true only for $x>0$. In our case, the expression $x^2+x-6$ with $x=1$ is different.
Here we should use the formula $\log_a x^2=2\log_a|x|$, which is true for all $x \neq 0$.
Another example. Solving the equation
$$\log_2[(x+1)(x-3)]=2\log_4(x+8)-\log_1[(x+1)(x-5)],$$
the student brought him to sight
$$\log_2(x+1)+\log_2(x-3)=\log_2(x+8)+\log_2(x+1)+\log_2(x-5),$$
or
$$\log_2(x-3)=\log_2[(x+8)(x-5)].$$
(10)
After this, he obtained the quadratic equation $x^2+2x-37=0$, hence our $x_1=-1+\sqrt{38}, x_2=-1-\sqrt{38}$.

⟦folio 42⟧

The student discarded the second root as not satisfying equation (10) and received the answer $x = -1 + \sqrt{38}$.

What's wrong here? The formula $\log_a xy = \log_a x + \log_a y$ is valid only for $x > 0$ and $y > 0$. Therefore, when taking the logarithm of the product and the product, the root $x = -1 - \sqrt{38}$ is lost, which, in fact, satisfies the original equation.

To see this, note that the original equation is equivalent to the system
$$\begin{cases} \log_2(x+1)(x-3) = \\ = \log_2(x+8)(x+1)(x-5), \\ x+8 > 0, \end{cases}$$

$$\begin{cases} (x+1)(x-3) = \\ = (x+8)(x+1)(x-5), \\ x+8 > 0, \\ (x+1)(x-3) > 0. \end{cases}$$

The solutions of the last system are $\{-1 - \sqrt{38}, -1 + \sqrt{38}\}$.

The use of formulas $\log_a u^2 = 2\log_a u$ and $\log_a uv = \log_a u + \log_a v$ “from right to left”, generally speaking, leads to an expansion of the domain of definition of the equation, which may entail the use of the constructed roots. In cases where the roots of the resulting equation are quite simple and verification is not burdensome, it is not at all necessary to write out systems of equations and inequalities. You can change to equations and check at the end of the solution.

Example 7. Solve equation $\log_{\frac{1}{2}}(x-1) + \log_{\frac{1}{2}}(x+1) - \log_{\frac{1}{\sqrt{2}}}(7-x) = 1$.

Solution. Going to base 2 logarithms and rearranging the terms on the right hand side, we arrive at the equation
$$2\log_2(7-x) = \\ = 1 + \log_2(x-1) + \log_2(x+1),$$
whence we get the equation-consequence
$$(7-x)^2 = 2(x^2-1),$$
or
$$x^2 + 14x - 51 = 0.$$
The roots of this quadratic equation are $x_1 = 3, x_2 = -17$.

The second root obviously does not satisfy this equation. Substituting the value $x = 3$ into it, we make sure that $x = 3$ is its real root.

Answer. {3}.

Finally, here is another example of how students lose roots when using the formula for moving to another base.

Example 8. Solve equation $\log_{2x}x + \log_{8x^2}x = 0$.

"Solution". Going to the base $x$, we get
$$\frac{1}{\log_x 2 + 1} + \frac{1}{2 + 3\log_x 2} = 0.$$
Putting $y = \log_x 2$, we obtain the equation
$$\frac{1}{y+1} + \frac{1}{3y+2} = 0.$$
This equation has root $y = -\frac{3}{4}$. Therefore $\log_x 2 = -\frac{3}{4}$, from where
$$x_1 = 2^{-\frac{4}{3}} = \frac{1}{2^3\sqrt{2}}.$$
The value $x = \frac{1}{2^3\sqrt{2}}$ satisfies the equation. However, it is easy to see that the value $x = 1$ is also its root. What's the matter?

The root $x = 1$ was lost when moving to the base $x$, because to the base $x$, because to the base $x$, because for the rest $x$ solve as it was done.

Answer. $\{1, \frac{1}{2^3\sqrt{2}}\}$.

Generally speaking, it's best to avoid jumping to bases that depend on $x$. If the transition to such bases comes, then you need to very carefully monitor for which $x$ the transformation is possible, and check by substituting into the original equation those values ​​$x$ at which the base is equal to 1 or negative.

So, when solving the last equation, it is better to go to base 2. As a result, we get

⟦folio 43⟧

$$\frac{\log_2 x}{1 + \log_2 x} + \frac{\log_2 x}{2 + 3 \log_2 x} = 0,$$
or, after replacing $y = \log_2 x$,
$$\frac{y}{1 + y} + \frac{y}{2 + 3y} = 0.$$

Solving this equation, we will find the roots of $y_1 = 0, y_2 = -\frac{4}{3}$, after which we can easily obtain a solution to this Equation.

Now consider two problems, the solution of which uses the monotony properties of some functions.

Example 9. Solve equation $\log_5(x + 3) = 3 - x$.

Solution. It is easy to check that $x = 2$ is the root of this equation. It obviously has no other roots, since the function $\log_5(x + 3)$ returns throughout its entire domain of definition, and the function $y = 3 - x$ kills.

Answer. {2}.

Example 10. Solve equation $(x + 1)\log_3^2 x + 4x\log_3 x - 16 = 0$.

Solution. Let us set $y = \log_3 x$ and solve for $y$ the quadratic equation $(x + 1)y^2 + 4xy - 16 = 0$.

We get $y = \frac{4}{x + 1}$ or $y = -4$. There are two equations left to solve:

$$\log_3 x = \frac{4}{x + 1} \text{ и } \log_3 x = -4.$$

The second of these equations is easily solved, and to solve the first it is enough to replace that $x = 3$ satisfies the equation and the function on the left side returns at $x > 0$, and the function on the right side kills.

Answer. $\left\{\frac{1}{81}; 3\right\}$.

In conclusion, consider an equation that is solved from other considerations.

Example 11. Solve equation $3x^2 - 2x^3 = \log_2(x^2 + 1) - \log_2 x$.

Solution. The right side of the equation is defined at $x > 0$ and is equal to $\log_2\left(x + \frac{1}{x}\right)$. Since $x + \frac{1}{x} \geq 2$ at $x > 0; \log_2\left(x + \frac{1}{x}\right) \geq 1$. On the other hand, $3x^2 - 2x^3 \leq 1$ for $x > 0$ (you can verify this, for example, by examining the function using an arbitrary one). $\log_2\left(x + \frac{1}{x}\right) = 1$ at $x = 1$. Since $3x^2 - 2x^3$ is also equal to 1 at $x = 1$, the left side is equal to the right only at $x = 1$.

Answer. {1}.

Exercises
Solve the equations:
1. $\log_4 x + \log_2 x + 2\log_16 x = 5$.
2. (MSU, geology. Faculty, 1974)
$$\log_{16}(x^2 - 2x - 3)^2 - 2\log_{16}(x^2 + x - 2) = \frac{1}{2}.$$
3. (MSU, Faculty of Soil Science, 1974)
$$\left[(\log_2 x)^2 + 2\log_1/2 \frac{1}{2\sqrt{2}}\right]\left(3\log_8 x - 1\right) = \left(\log_2 x\right)^2.$$
4. (MSU, Faculty of Economics, Department of Political Economy, 1979)
$$\log_{(3 - 4x^2)}(9 - 16x^4) = 2 + \frac{1}{\log_2(3 - 4x^2)}$$
5. (MSU, Faculty of Psychology, 1978)
$$\left(\log_3 \frac{3}{x}\right)\log_2 x - \log_3 \frac{x^3}{\sqrt{3}} = \frac{1}{2} + \log_2 \sqrt{x}.$$
6. (MSU, Faculty of Economics, Department of Economics, Book Studies, 1978)
$$3 + \frac{1}{\log_3 \frac{x}{2}} = \log_2\left(\frac{75x}{4} - \frac{11}{x}\right).$$
7. (MSU, Faculty of Economics, Department of Political Economy, 1979)
$$\log_{(2x + 1)}(5 + 8x - 4x^2) + \log_{(5 - 2x)}(1 + 4x + 4x^2) = 4.$$
8. (MVTU, 1979)
$$0,5\lg(2x - 1) + \lg\sqrt{x - 9} = 1.$$
9. (MSU, Faculty of Soil Science, 1979)
$$x^2\log_6\sqrt{5x^2 - 2x - 3} - x\log_1/6\left(5x^2 - 2x - 3\right) = x^2 + 2x.$$
10. (MSU, Faculty of Chemistry, 1972)
$$\log_{(x^2 + 6x + 8)}(\log_{(2x^2 + 2x + 3)}(x^2 - 2x)) = 0.$$
11. (MSU, Faculty of Physics, 1975)
$$6\log_1/6\left(x + 3\right) = \left(\frac{1}{2}\right)\log_4(x^2 + 5x + 12).$$
12. $\log_2^2 x + (x - 1)\log_2 x = 6 - 2x.$
13. $3^x = 10 - \log_2 x.$
14. $\log_{0,5}x^2 - 14\log_{16}x^3 + 40_4x\sqrt{x} = 0.$
