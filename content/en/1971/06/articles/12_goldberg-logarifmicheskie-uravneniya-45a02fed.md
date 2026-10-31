---
id: 1971-6-goldberg-logarifmicheskie-uravneniya-45a02fed
issue: kvant_1971_6
year: 1971
number: "6"
title: Logarithmic equations
authors:
  - Гольдберг В. В.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 48
page_last: 53
page_labels: 46-51
tag: 975A
lang: en
source: kvant_digital
extraction: vision
content_sha256: b812fcc3724bedbd7b3c6d3905ae6cb7ccc60d22c3b3a7f3d471d60b18715c91
prompt_sha256: draft-1
translated_from: content/ru/1971/06/articles/12_goldberg-logarifmicheskie-uravneniya-45a02fed.md
source_content_sha256: b79d2832634f1a72b4b29c1d048a564071ae93936e93364c592741f825b90190
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 46⟧

Logarithmic equations
V. V. Goldberg

Logarithmic equations are usually called equations containing an unknown quantity under the logarithm sign.
Solving the simplest logarithmic equation

$$\log_a x = b$$

(1)
is based on the following property of logarithms: if the logarithms of two (positive) numbers to the same base $a(a > 0, a \neq 1)$ are equal, then these numbers themselves are equal.

Having written equation (1) in the form $\log_a x = \log_a a^b$ and using the indicated property, we obtain the answer: $x = a^b$.

This technique is also applicable to solving more complex logarithmic equations of the form

$$\log_a f(x) = b.$$

(2)
For equation (2) we obtain $f(x) = a^b$.

Example 1: Solve the equation

$$\log_5 [2 + \log_3(3+x)] = 0.$$

Solution e. First we find that

$$2 + \log_3(3+x) = 5^0, \quad 2 + \log_3(3+x) = 1, \quad \log_3(3+x) = -1.$$

Next we find: $3 + x = 3^{-1}, x = \frac{1}{3} - 3, x = -\frac{8}{3}$.

Some logarithmic equations are easily properties of the simplest. Thus, equations of the form

$$f(\log_a x) = 0$$

(3)
by replacing $\log_a x = y$ they are added to the equation $f(y) = 0$. If $y_1, \dots, y_k$ are the roots of the last equation, then we obtain a set of simple logarithmic equations:

$$\log_a x = y_1, \dots, \log_a x = y_k.$$

Example 2. Solve equation $\lg^3 x - \lg^2 x - 6 \lg x = 0$.

Solution e. Let us denote $\lg x$ by $y$. Then we obtain a cubic equation for $y$:

$$y^3 - y^2 - 6y = 0.$$

Let's solve it: $y(y^2 - y - 6) = 0, y_1 = 0, y_2 = 3, y_3 = -2$. We consider three possible cases:

a). $\lg x = 0, x_1 = 1$; 6) $\lg x = 3, x_2 = 1000$; b) $\lg x = -2, x_3 = 0,01$.

Exponential-logarithmic equations are similar to equations of the form (3), if they are first polygonalized.

⟦folio 47⟧

Technique 3. Solve the equation $x^2 + \log_3 x = 3^8$.

Solution. Since both sides of the equation are positive (ODZ: $x > 0$), we equate their logarithms to base 3: $\log_3 x^2 + \log_3 x = \log_3 3^8$, which means that $(2 + \log_3 x) \log_3 x = 8$. Denoting $\log_3 x$ by $y$, we arrive at the quadratic equation $y^2 + 2y - 8 = 0$ with roots $y_1 = -4, y_2 = 2$. Let's break down two cases:

a) $\log_3 x = -4, x_1 = 1/81$ 6) $\log_3 x = 2, x_2 = 9$.

Technique 4. Solve the equation $9x^{\lg x} + 91x^{-\lg x} = 60$.

Solution. Let us introduce the notation $x^{\lg x} = y$; then $x^{-\lg x} = \frac{1}{y}$, otherwise the property equation to the following equation with respect to $y$: $9y^2 - 60y + 91 = 0$. The roots of the latter are $y_1 = \frac{13}{3}, y_2 = \frac{7}{3}$. We are considering both possibilities:

a) $x^{\lg x} = \frac{13}{3}$; taking logarithm, we get $\lg x^{\lg x} = \lg \frac{13}{3}, \lg^2 x = \lg \frac{13}{3}$, whence $\lg x = \pm \sqrt{\lg \frac{13}{3}}, x_1 = 10^{\sqrt{\lg \frac{13}{3}}}, x_2 = 10^{-\sqrt{\lg \frac{13}{3}}}$;

b) $x^{\lg x} = \frac{7}{3}$; similarly to how it was done in the first case, we find $x_3 = 10^{\sqrt{\lg \frac{7}{3}}}, x_4 = 10^{-\sqrt{\lg \frac{7}{3}}}$.

When solving logarithmic equations, it is often a matter of properties to solve an equation of the type

$$\log_a f(x) = \log_a g(x).$$

Here, using potentiation, we need to go to the equation

$$f(x) = g(x).$$

But it should be borne in mind that with the maximer we are expanding the ODZ equation, and therefore the appearance of extraneous roots is possible. Therefore, it is necessary to check whether each of the roots of equation (5) is included in the ODZ of equation (4).

Technique 5. Solve the equation $\log_2(2x^2 - 2) = \log_2(5x - 4)$.

Solution. Finding ODZ:

$$\begin{cases} 2x^2 - 2 > 0, \\ 5x - 4 > 0, \end{cases}$$

that is, $$\begin{cases} x < -1, x > 1, \\ x > \frac{4}{5}. \end{cases}$$

Therefore, ODZ: $x > 1$. The potency of this equation, we get $2x^2 - 2 = 5x - 4$, or $2x^2 - 5x + 2 = 0$, from where we find $x_1 = 2, x_2 = 1/2$.

Since $x_2 = 1/2$ is not included in the ODZ, the equation has only one solution: $x = 2$.

The following properties of logarithms of numbers are well known:

$$\log_a(AB) = \log_a A + \log_a B \quad (A > 0, B > 0, a > 0, a \neq 1),$$

$$\log_a \frac{A}{B} = \log_a A - \log_a B \quad (A > 0, B > 0, a > 0, a \neq 1),$$

$$\log_a A^p = p \log_a A \quad (A > 0, p - \text{любое действительное число}),$$

$$\log_a q^p = \frac{p}{q} \log_a A \quad (A > 0, q \neq 0).$$

⟦folio 48⟧

How should these properties of logarithms be used when solving logarithmic equations when the expressions $A$ and $B$ contain an unknown?

To answer this question, we note that the ODZ of the left and right parts of these formulas are different: for example, the right side of formula (6) makes sense only for $A > 0$ and $B > 0$, and the left side of this formula is defined both for $A > 0$ and $B > 0$, and for $A < 0$, $B < 0$.

Similarly, for other formulas, the ODZ of the left side may turn out to be wider than the ODZ of the right side (in this case, in formula (9) it is necessary to consider the permissible values of the value $a$ included in the base. This means that if we use formulas (6)-(9) “from right to left", then as a result we will obtain an equation that is a consequence of the original one (its ODZ may turn out to be wider). At the same time, we are guaranteed that we will not consume roots. But in this case, we can acquire the construction of roots. Therefore, all the obtained roots must be checked (if the construction of roots could only appear as a result of using formulas (6)-(9), then it is enough to check whether the obtained roots are included in the ODZ of the original equation).

Example 6: Solve the equation

$$\log_{\frac{1}{6}}(x-1) + \log_{\frac{1}{6}}(5x+3) = -2.$$

Solution. Finding ODZ:

$$\begin{cases} x-1 > 0, \\ 5x+3 > 0. \end{cases} \quad \begin{cases} x > 1, \\ x > -\frac{3}{5}. \end{cases}$$

Therefore, the ODZ is: $x > 1$.

Applying formula (6) to the left side of the equation, we obtain

$$\log_{\frac{1}{6}}[(x-1)(5x+3)] = -2,$$

where we find $(x-1)(5x+3) = 36$, or $5x^2-2x-39=0$. The roots of a quadratic equation are $x_1=3$, $x_2=-13/5$.

Since the construction of the roots could only appear due to the use of formula (6), it is enough to check whether the solutions obtained are included in the ODZ of equation (10). Therefore, we are convinced that the equation has a unique solution $x=3$. Note that the value $x=-13/5$, which is not equation (10), will be a solution to equation (11), the ODZ of which is wider: $x > 1$, $x < -3/5$.

What should we do if, when solving a logarithmic equation, we are faced with the need to use formula (6)–(9) “from left to right”? After all, if the formulas are used in the form in which we wrote them out, we will arrive at an equation whose ODZ may turn out to be narrower than the ODZ of the original equation! But then we may lose some of our roots!

To prevent this from being an accident, we must use more general formulas:

$$\log_a(AB) = \log_a|A| + \log_a|B| \quad (AB > 0,a > 0,a \neq 1),$$

$$\log_a\frac{A}{B} = \log_a|A| - \log_a|B| \quad (AB > 0,a > 0,a \neq 1),$$

$$\log_aA^{2p} = 2p\log_a|A| \quad (A \neq 0,p - целое число),$$

$$\log_a^{2q}A = \frac{1}{2q}\log_a|A| \quad (A > 0,q \neq 0 - целое число).$$

⟦folio 49⟧

The left and right parts of formulas (6′) and (7′), as well as formulas (6) and (7), have different restrictions on A and B: the left parts make sense when A and B are of the same sign, and the right parts - for any non-zero A and B.

Therefore, the use of formulas (6′) and (7′) “from left to right” will lead to an equation whose OA may be wider. But this is already less strange than the existence of ODZ, or now we cannot lose our roots, but can only gain a structure. As we have already noted, in this case it becomes necessary to check the resulting solutions (sometimes it is enough to check whether they are included in the ODZ of the original equation).

Example 7: Solve the equation
$$\lg(x+1)^2 + \lg(x+9)^2 = 2\lg 9.$$ (12)

To prevent some of the errors encountered, we first present the incorrect solution.

Using formulas (8) we find that $2\lg(x+1) + 2\lg(x+9) = 2\lg 9$, or
$$\lg(x+1) + \lg(x+9) = \lg 9.$$ (13)

Applying formula (6), obtaining data
$$\lg[(x+1)(x+9)] = \lg 9,$$ (14)

from where we find $(x+1)(x+9) = 9$, or $x^2 + 10x = 0$ and then $x_1 = 0, x_2 = -10$. Checking shows that the root satisfies equation (12).

Let us now give the correct solution to equation (12).

Solution. We find the ODZ of equation (12): $x \neq -9, x \neq -1$. Using formula (7′), we obtain $2\lg|x+1| + 2\lg|x+9| = 2\lg 9$, from which we find that $\lg|(x+1)(x+9)| = \lg 9$ and further $|x^2 + 10x+9| = 9$.

The last equality holds in any of the following cases:

a) $x^2 + 10x+9 = 9, x^2 + 10x = 0, x_1 = 0, x_2 = -10$;
b) $x^2 + 10x+9 = -9, x^2 + 10x+18 = 0, x_3 = -5 + \sqrt{7}, x_4 = -5 - \sqrt{7}$.

Thus, equation (12) has four roots.

The error in the above incorrect solution, as you have obviously already proven, was that formula (8) was applied, not (8′). This is reduced to equation (13) with a narrower ODZ: $x > -1$. In the next step, this quotient was compensated: the ODZ of equation (14) is wider than the ODZ of equation (13) - this includes both $x > -1$ and $x < -9$. The latter should have lost the root $x_2 = -10$, but the roots $x_3, 4 = -5 \pm \sqrt{7}$ turned out to be lost.

Example 8: Solve the equation
$$\lg[(x-2)(x+3)] + \lg[(x+3)/(x-2)] = 1.$$ (15)

Solution. Let's find the ODZ: $(x-2)(x+3) > 0$, or $x < -3$ and $x > 2$.

To solve, use formulas (6′) and (7′):
$$\lg|x-2| + \lg|x+3| + \lg|x+3| - \lg|x-2| = 1.$$

Bringing similar terms, we obtain $\lg|x+3| = 1/2$, from which we find:
$$|x+3| = \sqrt{10}, x+3 = \pm \sqrt{10}, x_1 = -3 + \sqrt{10}, x_2 = -3 - \sqrt{10}$$.

Checking shows that $x = -3 - \sqrt{10}$ will be the only solution to equation (15).

Using formulas (6) and (7) we would have
$$\lg(x-2) + \lg(x+3) + \lg(x+3) - \lg(x-2) = 1,$$
$$\lg(x+3) = \frac{1}{2}, x+3 = \sqrt{10}, x = -3 + \sqrt{10}.$$

With this solution, we first narrowed the ODZ, which led to the loss of the root $x = -3 - \sqrt{10}$, and then, after eliminating similar terms, we expanded the ODZ, which led to the construction of the root $x = -3 + \sqrt{10}$.

⟦folio 50⟧

Another source of extraneous roots is the use of the basic logarithmic method

$$a^{\log_a b} = b \quad (b > 0, a > 0, a \neq 1)$$

in the case where $a$ and $b$ contain an unknown.

Example 9. Solve equation $x^{\log_x(x^2+1)} = 2$.

Solution. Using toskedness (16), we obtain $x^2+1=2$, whence $x_1=-1, x_2=1$. But the values ​​of $x=\pm 1$ cannot be the base of logarithms, that is, they are not included in the ODZ. Therefore the equation has no solutions.

If the equation includes logarithms with different bases, you need to apply the formula for moving from one logarithm base to another:

$$\log_b A = \frac{\log_a A}{\log_a b} \quad (A > 0, a > 0, b > 0, a \neq 1, b \neq 1)$$

and its special case

$$\log_b a = \frac{1}{\log_a b} \quad (a > 0, b > 0, a \neq 1, b \neq 1).$$

Example 10. Solve the equation

$$\log_3 x \frac{3}{x} + \log_3^2 x = 1.$$

Solution. We find the ODZ: $x > 0, x \neq \frac{1}{3}$. Using formula (17), let us move to base 3 in the first term; then we get

$$\frac{\log_3 \frac{3}{x}}{\log_3(3x)} + \log_3^2 x = 1,$$ or $$\frac{1-\log_3 x}{1+\log_3 x} + \log_3^2 x = 1.$$

Let's denote it by $\log_3 x$. through $y$, then the equation takes the form

$$\frac{1-y}{1+y} + y^2 = 1$$ or $$y^3 + y^2 - 2y = 0,$$

where do we find $y_1=0, y_2=-2, y_3=1$. We are considering three possibilities:

a) $\log_3 x=0, x_1=1$; b) $\log_3 x=1, x_3=3$.

Example 11. Solve the equation

$$20 \log_ax \sqrt{x} + 7 \log_a^2 x^3 = 3 \log_x x^2 \quad (a > 0, a \neq 1).$$

Solution. We find the ODZ: $x > 0, x \neq \frac{1}{a}, x \neq \frac{1}{a^2}, x \neq \sqrt{a}$. Since $x > 0$, we can apply formula (8), which gives

$$10 \log_ax x + 21 \log_a^2 x = 6 \log_x x.$$

Now it is most convenient to use formula (18) to go to the same base $x$. But when $x$ is at the base of logarithms, the ODZ of the equation becomes narrower,

⟦folio 51⟧

since $x$ cannot be equal to one after this. Therefore, before moving on to the root $x$, let’s check whether $x=1$ is the root of the equation. It is easy to see that $x_1=1$ is a root. Let's now move on to the base $x$:

$$\frac{10}{\log_x(ax)} + \frac{21}{\log_x(a^2x)} = \frac{6}{\log_x\frac{x}{\sqrt{a}}}.$$

Let us denote $\log_x a$ by $y$. Then we get

$$\frac{10}{1+y} + \frac{21}{1+2y} = \frac{6}{1-\frac{1}{2}y}.$$

After simple transformations we arrive at the quadratic equation $13y^2-3y-10=0$, whose roots are $y_1=1, y_2=-\frac{10}{13}$. In the first case we get $\log_x a=1, x_2=a$, and in the second case $\log_x a=-\frac{10}{13}, x^{-\frac{10}{13}}=a, x_3=a^{-\frac{13}{10}}$.

Answer: $x_1=1, x_2=a, x_3=a^{-\frac{13}{10}}$.

When solving logarithmic equations, it is sometimes convenient to use the following formula:

$$A^{\log_a B}=B^{\log_a A} (A>0, B>0, a>0, a\neq1).$$

The proof of formula (19) is very simple: since both sides of this formula are positive, we find the logarithms to the base $a$ of $A^{\log_a B}$ and $B^{\log_a A}$. It is easy to verify that these logarithms are equal to the same expression $\log_a A \log_a B$; From the equality of logarithms we deduce the validity of formula (19).

Example 12. Solve equation $3^{\log_a x}+3x^{\log_a 3}=2 (a>0, a\neq1)$.

Solution. ODZ: $x>0$. By virtue of (19) $x^{\log_a 3}=3^{\log_a x}$.

The pose equation can be written in the form $3^{\log_a x}+3\cdot3^{\log_a x}=2$, from which it is found that $4\cdot3^{\log_a x}=2$, that is, $3^{\log_a x}=\frac{1}{2}$. Next we have $\log_a x=-\log_3 2, x=a^{-\log_3 2}$.

Exercises

Solve equations:

1. $\log_3(3^x-1) \log_3(3^{x+1}-3)=6$.
2. $x^{\log_x(x+3)^2}=16$.
3. $x^{\log_3 x-\log_3 x}=3^{3\log_2 V^2+4}$.
4. $15^{\log_6 3} x^{\log_5(9x)}+1=1$.
5. $\lg(3x-11)+\lg(x-27)=3$.
6. $\frac{1}{\log_6(3+x)}+\frac{2\log_0.25(4-x)}{\log_2(3+x)}=1$.
7. $\lg\sqrt{1+x}+3\lg\sqrt{1-x}=\lg\sqrt{1-x^2}+2$.
8. $\log_x x^2-14\log_{16x}x^3+40\log_{4x}\sqrt{x}=0$.
9. $\log_x 10+2\log_{10x}10+3\log_{100x}10=0$.
10. $3x^{\log_6 2}+2^{\log_5 x}=64$.
11. $\lg x^2+\lg(x+10)^2=2\lg 11$.
12. $\lg[x(x+9)]+\lg\frac{x+9}{x}=0$.
