---
id: 1984-5-voronin-kulagin-metod-proizvodyaschih-funktsiy-4d417cca
issue: kvant_1984_5
year: 1984
number: "5"
title: Generating function method
authors:
  - Воронин С. М.
  - Кулагин А. Г.
rubric: raznoe
page_first: 14
page_last: 17
page_labels: 12-15
tag: ZM1X
lang: en
source: kvant_digital
extraction: vision
content_sha256: f95198e556dcdc76a200752a80e8ba513c70791e0d9330c3e46a479e21567a30
prompt_sha256: draft-1
translated_from: content/ru/1984/05/articles/06_voronin-kulagin-metod-proizvodyaschih-funktsiy-4d417cca.md
source_content_sha256: 55e36a807143af254d94175b3ac53af79e38b953351e3920bd956540dfb8af20
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 12⟧

number of ways to weigh a load of $k$ grams considered by weights!

So, to solve the original problem, it remains to calculate $A_k$. And here is another unexpected move by Euler. He writes very nice things

$$\begin{align*}
(1-z) (1+z) &= 1-z^2, \\
(1-z^2) (1+z^2) &= 1-z^4, \\
(1-z^4) (1+z^4) &= 1-z^8,
\end{align*}$$

and after multiplying and reducing by common factors he gets

$$1-z (1+z) (1+z^2) (1+z^4) (1+z^8) \cdot \dots = 1,$$

that is, $(1-z) \alpha(z) = 1$, from where

$$\alpha(z) = \frac{1}{1-z} = 1+z+z^2+z^3+z^4+\dots$$

(here is written the well-known formula for the sum of a geometric progression *). Comparison of (3) with (2) shows that $A_k = 1$ for all $k$, that is, any load of an integer number of grams can be cocked in digits of 1, 2, 4, ..., $2^m$, ... grams, in a unique way.

Number partitioning problem

This is what Euler called the following problem: find the number of positive integer solutions to the equation

$$x_1 + \dots + x_m = k,$$

(4)

food $m$ and $k$ are fixed natural numbers. Here another unexpected expression leads to the goal, namely

$$\beta(z) = (1+z+z^2+z^3+z^4+\dots)^m.$$

After expanding the parentheses, $\beta(z)$ is written as

$$\beta(z) = 1+B_1z+B_2z^2+B_3z^3+\dots$$

(6)

What is $B_k$ equal to? Try to answer this question yourself, keeping in mind that $B_k$ is the coefficient of $z^k$. Yes, of course: the coefficient $B_k$ is equal to the number of ways to select one integer indicator from each of the brackets on the right side of (5), that is, $B_k$ is equal to the number of positive integer solutions to equation (4)!

Euler's problem was reduced to calculating $B_k$.

To do this, remember the formula of geometric progression, you can write

$$\beta(z) = (1-z)^{-m} = 1+B_1z+B_2z^2+B_3z^3+\dots$$

(7)

Differentiating this equality

$$m(1-z)^{-m-1} = B_1+2B_2z+3B_3z^2+\dots$$

and substituting $z=0$, we get $B_1=m$.

*) If $|z|<1$. But we will return to this later.

Differentiating again and substituting $z=0$ again, we get $B_2=m(m+1)/2$. Continuing in exactly the same way (that is, continuing equations (7) $k$ times and substituting $z=0$), we obtain, following Euler, the number of solutions to equation (4) in the form

$$B_k = \frac{m(m+1) \cdot \dots \cdot (m+k-1)}{n!}$$

Exchange problem

How many ways can you exchange a ruble with coins in denominations of 1, 2, 3, 5, 10 kopecks? This problem can be formulated differently: how many non-negative integer solutions does the equation have?

$$x_1+2x_2+3x_3+5x_4+10x_5=100?$$

In a more general form, the “exchange problem” is posed as follows: how many non-negative integer solutions does the equation have?

$$a_1x_1+a_2x_2+\dots+a_mx_m=n,$$

(8)

what if $a_i$ are positive integers and $n$ is a fixed natural number?

Consider the expression

$$\gamma(z) = (1+z^a_1+z^a_2+z^a_3+\dots) \times (1+z^a_2+z^a_2+z^a_3+\dots) \times (1+z^a_m+z^a_m+z^a_m+\dots) = 1+C_1z+C_2z^2+C_3z^3+\dots$$

If you understand the previous reasoning, you will immediately say that the number $C_n$ is equal to the number of solutions to equation (8). But how to find $C_n$? Use the formula for the sum of an infinite decreasing geometric progression (for example, $1+z^a_1+z^a_2+\dots=1/(1-z^a_1))$, you can represent $\gamma(z)$ in the form

$$\gamma(z) = \frac{1}{(1-z^a_1)(1-z^a_2)\dots(1-z^a_m)},$$

but from here it is not immediately clear how to obtain $C_n$ in the general case. However, formula (9) is already sufficient to find $C_n$ for small $n$.

Four square problem

Can every integer be represented as the sum of four squares of integers, and if so, in how many ways? In other words, how many integer solutions does the equation have?

$$x_1^2+x_2^2+x_3^2+x_4^2=m,$$

(10)

food $m$ is a given natural number?

This task is more demanding than the previous ones, although it boils down to, like them, the calculation of the coefficients of a certain “infinite polynomial”. Namely, putting

⟦folio 13⟧

$$\delta(z) = \frac{1 + 2z + 2z^4 + 2z^9 + 2z^{16} + \dots}{1 + D_1z + D_2z^2 + D_3z^3 + \dots},$$

It is easy to understand that the number of required solutions to equation (10) is equal to $D_m$. Differentiating $m$ times and substituting $z=0$, one can find $D_m$ in the form

$$D_m = \frac{1}{m!} \frac{d^m}{dz^m} \left( \delta(z) \right) |_{z=0}$$

where $\frac{d^m}{dz^m}$ denotes taking a derivative of $m$ order, and the symbol $|_{z=0}$ means that all together $z$ need to be substituted by 0. For small $m$ the number $D_m$ can be counted using this formula, but in general it is not easy. The original problem in number theory has been reduced to some problem from analysis, but the latter still needs to be solved!

From the results of the German mathematician K. G. Jacobi (1804-1851) follows a remarkable formula for $\delta(z)$

$$\delta(z) = 1 + 8 \sum_{m \neq 4k} \frac{mz^m}{1 - z^m},$$

which was also received by the Indian mathematician S. Ramanujan (1887-1920). From it we can deduce that equation (10) is always solvable and find the number of solutions to this equation.

Discussion of the method

Let us now try to understand what the general method consists of, which worked so surprisingly well in the problems analyzed. In each of them, a certain “infinite expression” containing the letter $z$ was considered (an infinite product of two people - (1), a finite power of an infinite sum - (5) and (11), a product of infinite sums - (9)). Further, this expression was written in the form of an “infinite polynomial in $z$”, that is, in the form

$$\alpha(z) = A_0 + A_1z + A_2z^2 + A_3z^3 + \dots + A_nz^n + \dots,$$

and it turned out that the coefficients $A_k$ provide the key to solving the problem. It was then possible to calculate the coefficient $A_k$ by performing various operations on infinite expressions: arithmetic operations were performed on them, they were differentiated, transformed according to the geometric progression formula...

It is natural to ask: what are the infinite expressions we are considering, and are the actions that were performed on them legal? The author of the method, Leonhard Euler, apparently did not think much about these issues - he treated infinite expressions as if they were finite, and all that was important to him was obtaining a result. Meanwhile, careless handling of infinity carries with it the danger of mistakes.

Pretentious example

Consider two "infinite polynomials"

$$\alpha(z) = 1 - z + z^2 - z^3 + z^4 - \dots,$$

$$\beta(z) = -1 + z - z^2 + z^3 - z^4 + \dots$$

and count the infinite sum

$$S(z) = \alpha(z) + \beta(z) + \alpha(z) + \alpha(z) + \dots$$

If we group the terms in $S(z)$ in pairs, starting from the first pair, we get

$$S(z) = [\alpha(z) + \beta(z)] + [\alpha(z) + \beta(z)] + \dots = \alpha(z) + 0 + 0 + \dots = \alpha(z)!$$

Not if you group differently, you can get

$$S(z) = \alpha(z) + [\beta(z) + \alpha(z)] + [\beta(z) + \alpha(z)] + \dots = \alpha(z) + 0 + 0 + \dots = \alpha(z)!$$

And if you change the order of the terms, you can come to an even stranger result, for example, $S(z) = 17z^{17}$ (think about how this can be done).

Perhaps the time has come to give precise definitions of infinite expressions and find out what operations are legal on them.

Formal degree series

Formal powers nearby is called an expression

$$\alpha(z) = a_0 + a_1z + a_2z^2 + \dots + a_nz^n + \dots,$$

where $a_i$ are real numbers (coefficients of the series (12)), and $z$ is a simple symbol (form variable of the series). Mathematicians also say that $\alpha(z)$ is the generating function for the sequence of coefficients $a_0, a_1, \dots, a_n, \dots$. One should not think, however, that in the general case we are considering, $\alpha(z)$ is a function of the variable $z$ in the general sense. When we say that $\alpha(z)$ is a generating function of the sequence $a_0, a_1, \dots, a_n, \dots$, it only means that $\alpha(z)$ is a shorthand notation of the formal expression in the correct part of (12).

For readers familiar with the concept of (educational) power of a series, it is emphasized that the formal series (12) can be considered (for some $z$ or even for all $z$), but at the same time equality (12) remains legal: after all, $\alpha(z)$ does not denote the sum of the series for a given value $z$, but the formal series itself.

The outstanding German mathematician K. Weierstrass (1815-1897), who developed and put powers of series on a different logical basis, considered only series of descending powers, and criticized Euler for commit tricks with “infinite polynomials.” The modern algebraic theory of formal power series, which we touch upon here, is fulfilled, however, in essence it is closer to the “naive” approach of Euler than to the structure of the analytical theory of Weierstrass.

Formal power series can be added and multiplied. Let, in addition to the series $\alpha(x)$ (see (12)), be given a formal

⟦folio 14⟧

power series
$$\beta(z) = b_0 + b_1z + b_2z^2 + \dots + b_nz^n + \dots$$
(13)

Then the sum and product of these series are determined by natural formulas:
$$\alpha(z) + \beta(z) = (a_0 + b_0) + (a_1 + b_1)z + \dots + (a_n + b_n)z^n + \dots,$$
$$\alpha(z) \cdot \beta(z) = a_0b_0 + (a_1b_0 + a_2b_1)z + (a_0b_2 + a_1b_1 + a_2b_0)z^2 + \dots$$
(14)
(these actions are performed according to rules similar to the usual rules for addition and multiplication of finite polynomials). Note, by the way, that an ordinary polynomial can be considered a special case of a formal power series - a nominal one in which all coefficients, starting from some, are equal to zero. In this case, the usual addition and multiplication of polynomials will, of course, coincide with their addition and multiplication as formal power series.

Further, formal power series can be differentiated and internalized. By definition
$$\frac{d}{d(z)} (\alpha(z)) = (\alpha(z))' = a_1 + 2a_2z + 3a_3z^2 + \dots + na_nz^{n-1} + \dots,$$
$$\int \alpha(z) = \int_0^z \alpha(x)dx = a_0z + \frac{a_1}{2}z^2 + \frac{a_2}{3}z^3 + \dots + \frac{a_n}{n+1}z^{n+1} + \dots$$

For addition and multiplication of infinite series defined in this way, properties similar to those of numbers or polynomials will be satisfied. Namely, the commutative, combinational and distributive laws will be fulfilled.

Like an integer, you can subtract any other series from any formal series and again obtain a formal power series. Division in the domain of formal power series is not always possible, just as division of two integers is not always possible. For example, you can’t do it on “zero”, that is, you can’t do it on a row
$$0 = 0 + 0 \cdot z + 0 \cdot z^2 + \dots + 0 \cdot z^n + \dots$$
It is impossible to divide “units”, that is, a series
$$1 = 1 + 0 \cdot z + 0 \cdot z^2 + \dots + 0 \cdot z^n + \dots$$
per row
$$z = 0 + 1 \cdot z + 0 \cdot z^2 + \dots + 0 \cdot z^n + \dots$$

Indeed, suppose that there is a series
$$\alpha(z) = a_0 + a_1z + a_2z^2 + \dots,$$
for which $\alpha(z) \cdot z = 1$, or,
$$\left(a_0 + a_1z + a_2z^2 + \dots\right) \times \left(0 + 1 \cdot z + 0 \cdot z^2 + \dots\right) = 1 + 0 \cdot z + 0 \cdot z^2 + \dots$$

But from formula (14) it then follows that $a_0 \cdot 0 = 1$, which is certainly impossible.

Similarly, one can prove that $\alpha(z) = a_0 + a_1z + a_2z^2 + \dots$ is divisible by $z^n$ if and only if $a_0 = a_1 = a_2 = \dots = a_{n-1} = 0$.

It is easy to check that 1 is divisible by $\alpha(z)$ if only $a_0 \neq 0$, and the coefficients are obtained in a series of unique definitions.

Let us find, for example, the result of dividing “units” by the series 1-z. Let $(1-z)(a_0 + a_1z + a_2z^2 + \dots) = 1 + 0 \cdot z + 0z^2 + \dots$

Then, opening the brackets and equating the coefficient for the same powers $z$, we obtain a system of equalities
$$1 \cdot a_0 = 1, a_1 - a_0 = 0, a_2 - a_1 = 0, \dots, a_n - a_{n-1} = 0, \dots,$$
where $a_0 = a_1 = \dots = a_n = \dots = 1$ comes from, that is
$$\frac{1}{1-z} = 1 + z + z^2 + z^3 + \dots + z^n + \dots$$

We have already used this formula (see (3) above and note on p. 10) under a different name; here this formula is a true equality for formal power series (and the condition $|z| < 1$ has nothing to do with it).

Infinite sums and product

In solving problems at the beginning of the study there are endless works; infinite sums are no less useful (in particular, a formal power series can be considered as an infinite sum of digits). To avoid confusion, we give the necessary definitions of these concepts.

Let $\alpha_1(z), \alpha_2(z), \dots, \alpha_k(z), \dots$ be a sequence of formal power series (in particular, polynomials). We want to define an infinite sum and an infinite product:
$$\left(\alpha_1(z)\right) + \left(\alpha_2(z)\right) + \dots + \left(\alpha_k(z)\right) + \dots,$$
(15)
$$\left(\alpha_1(z)\right) \cdot \left(\alpha_2(z)\right) \cdot \dots \cdot \left(\alpha_k(z)\right) \cdot \dots$$
(16)

in the same way as above, that is, by opening the brackets and bringing similar

⟦folio 15⟧

ny members. However, such a definition is not suitable in the general case. Indeed, if, for example, in an “infinite product”

$$(1+z)(1+z) \cdot \dots \cdot (1+z) \cdot \dots$$

we begin to open the brackets and add similar ones, we will immediately see that the coefficient, say, at $z^2$, grows and continues to grow as we open the brackets. This example is fundamentally different from the previously analyzed work

$$(1+z)(1+z^2)(1+z^4) \cdot \dots$$

$$\dots \cdot (1+z^{2m}) \cdot \dots$$

in which the initial coefficients were gradually set and changed, due to the fact that in the “distant” brackets there are no monomials with a formal variable to a “low” degree.

So, the infinite sum (15) and the infinite product (16) are determined only if the coefficients are stabilized when opening the brackets and bringing similar terms - like a formal power series with the coefficients obtained in this way.

The precise definition of “stabilization” is this: for every natural number $d$ there is a natural number $n$ such that for $n \geq N$ the series $a_n(z)$ does not contain $z$ to powers less than $d$.

This concludes our brief excursion into the theory of formal power series. We advise the reader to stop reading at this point, return to the examples at the beginning of the article and make sure that they did not perform complicated tricks with infinite polynomials, but completely legal operations with formal power series.

Generating functions

A thoughtful reader, breaking down the examples at the beginning of the article, may have noticed that the success of the method is associated with the ability to write the generating function of the formal power series $a(z)$ in a compact form. So, for example, the generating function of the sequence 1, 1, 1, ... can be written as $1/(1-z)$, or

$$\frac{1}{1-z} = 1+z+z^2+\dots+z^n+... \tag{17}$$

Starting from this correspondence, one can obtain many other specific generating functions. For example, multiplying both sides of (17) by $z$ and differentiating, we get

$$\left( \frac{z}{1-z} \right)' = 1+2z+3z^2+\dots+(n+1)z^n+... \tag{18}$$

This means that the function $(z(1-z))' = 1/(1-z)^2$ is generating for the sequence 1, 2, 3, 4, ....

Multiplying by $z$ and differentiating again, we get

$$\frac{1+z}{(1-z)^3} = 1+2^2z+3^2z^2+\dots+(n+1)^2z^n+... \tag{19}$$

We have found an explicit expression for the generating function of the sequence $1^2, 2^2, 3^2, 4^2$, ...

Readers who are skilled in dividing polynomials with a “corner” can obtain correspondence (19) in another way, namely by dividing the polynomial $1+z$ by the polynomial $1-3z+3z^2-z^3$.

Starting again from (17), but now integrating, we get

$$\int_0^z \frac{dx}{1-x} = \int_0^1 dx + \int_0^z xdx + \dots + \int_0^z x^ndx + \dots,$$

$$-\ln(1-z) = z + \frac{z^2}{2} + \frac{z^3}{3} + \dots$$

We see that the generating function of the sequence 1, 1/2, 1/3, ... will be the function $-\ln(1-z)/z$.

Let us limit ourselves to these examples and move on to problems solved by the method of generating functions.

Tasks

1. Prove that any positive integer can be represented in double notation in a unique way.

Note. Compare this problem with the weighing problem.

2. Prove that any positive integer can be represented in decimal notation in a unique way.*

Note. Use the correspondence (proving it):

$$\left( 1+z+z^2+\dots+z^9 \right) \cdot \left( 1+z^{10}+z^{20}+...+z^{90} \right) \times \left( 1+z^{100}+z^{200}+...z^{900} \right) \cdot \dots = 1+z+z^2+z^3+\dots=1/(1-z).$$

3. Prove that any integer is positive as a sum of different numbers of positive terms. (For example, for the number 6 there are even ways having $6=1+5=2+4=1+2+3$ and $1+5=3+3=1+1+1+3=1+1+1+1+1+1$.)

(For the end see p. 52)

*) The fact that you have known this fact since first grade cannot be considered a mathematical justification for its validity!
