---
id: 1974-7-belaga-vyichislenie-mnogochlenov-ot-nyutona-do-nashih-dney-7dbd1783
issue: kvant_1974_7
year: 1974
number: "7"
title: Calculation of polynomials - from Newton to the present day
authors:
  - Белага Э. Г.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 31
page_last: 34
page_labels: 29, 31, 32
tag: G5OY
lang: en
source: kvant_digital
extraction: vision
content_sha256: 101c79e0b7ca0945f56fd456f1c2b142f82986b3073d643bb76c3f80694bd87a
prompt_sha256: draft-1
translated_from: content/ru/1974/07/articles/10_belaga-vyichislenie-mnogochlenov-ot-nyutona-do-nashih-dney-7dbd1783.md
source_content_sha256: c08b56a7575cf14514993e3c69910db4f3f03777e17fbba1d9fc60c6b586dce6
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 29⟧

§ 1. Polynomials - a calculator's tool

Well, let's begin! When we get to the end of this story, we will know more rather than less.

G. H. Andersen

In the invisible kingdom of functions, polynomials occupy, at first glance, a very modest place. However, this first impression is deceiving.

Polynomials are indeed extremely simple: algebraic notation
$$f(x) = x^n + a_1x^{n-1} + a_2x^{n-2} + \dots + a_{n-1}x + a_n$$ (1)
is at the same time a formula for calculating the values ​​of the polynomial $^*$). Although expressions like $\cos x$, $\sqrt[5]{x}$, $10^x$ or $\log_2 x$ are much more concise, from a computational point of view they are meaningless: to calculate, say, the numbers $\cos 17^\circ$, $\sqrt[5]{2}$, $10^{0.13}$ or $\log_2 7$, you need special approximate formulas (or tables compiled using the same formulas). As a rule, polynomials appear in such formulas: for example,
$$\cos x \approx 1 - \frac{x^2}{2!} + \frac{x^4}{4!} - \frac{x^6}{6!} + \frac{x^8}{8!}$$

(the error in the interval $0 \leq x \leq \pi/4$ is less than one ten-millionth!).

*) To simplify the calculations, we will limit ourselves to polynomials with unit coefficient for the leading term ($a_0 = 1$); where necessary, we will show how to proceed in the general case ($a_0 \neq 1$).

But trigonometric, power, etc. (elementary) functions are the simplest of the functions of analysis, studied and used by mathematicians, physicists, and engineers. The famous computational mathematician writes in his book *): “Because polynomials are easy to handle, most classical numerical analysis is based on approximation by polynomials.”

Since you often have to calculate polynomials, it is important to learn how to do it as simply as possible. We will talk about the evolution of methods for calculating the values ​​of polynomials since their inception (17th century). However, the word “evolution” is not entirely appropriate here: the history of these methods is rather a very long novel with an interesting but short plot, monotonous action and an unexpected ending.

§ 2. Horner's scheme

To be honest, a doubt will arise here, or rather a question that cannot be minimized without raising it and answering it.

A. Dante. Feast (1303)

The now generally accepted method of calculating polynomials goes back to Newton and is called Horner's scheme. This universal (that is, applicable to any polynomial) scheme is extremely simple and elegant. It is obtained from formula (1)

*) R. W. Hemming. Numerical methods. M., “Science”, 1972.

⟦folio 31⟧

Such schemes could be sought either based on the characteristics of an individual polynomial (by skillfully combining its coefficients), or by constructing a universal method for constructing schemes that are much more economical than Horner’s scheme, but perhaps not the best for some polynomials. The disadvantage of the first approach is that for each polynomial we will have to come up with our own techniques, and there is no guarantee that we will always succeed; Later (in § 10) we will see that the second is more reliable in all respects.

It goes without saying that both of these methods reduce only in cases where a particular polynomial comes up in time and effort to build a good circuit for it. “One-time use” polynomials are easier to calculate, say, using Horner’s scheme.

Perhaps similar reasoning led in 1955 to the discovery of a universal scheme of perfect type for a polynomial of the sixth degree. We will illustrate the main idea of ​​this scheme using a simpler scheme for polynomials of degree 4. Let
$$f(x) = x^4 + ax^3 + bx^2 + cx + d;$$
let's put
$$\begin{cases} p_1 = x \cdot (x + A); \\ p_2 = (p_1 + B)(p_1 + x + C) + D \\ f(x) = p_2 \end{cases}$$
where A, B, C and D are parameters.

Example. The polynomial $x^4 + 3x^3 + 6x^2 + 3x + 2$ can be calculated using the scheme: $p_1 = x(x + 1), f(x) = (p_1 - 1)(p_1 + x + 5) + 7$, containing two (instead of three according to Horner) multiplications and five (instead of four) $(\pm)$-operations; here A = 1, B = -1, C = 5, D = 7.

Let us write down an explicit expression for $p_2(x)$:
$$p_2(x) = x^4 + (2A + 1)x^3 + (A^2 + A + B + C)x^2 + (AB + B + AC)x + BC + D;$$
equating the coefficients $f(x)$ and $p_2(x)$, we express the parameters included in form (5) through coefficients (4):
$$A = (a - 1)/2;$$
$$B = c - b \cdot A + A^2(A + 1);$$
$$C = b - B - A(A + 1);$$
$$D = d - BC.$$
From these formulas it is clear that scheme (5) is universal.

We will call operations (6) transformative processing of the coefficients of the polynomial; Of course, they are not included in the number of circuit operations: after all, for each given polynomial they are performed only once, and our task is to learn how to quickly calculate the values ​​of an arbitrary but fixed polynomial for different $x$.

§ 5. Universal scheme of degree n

“I thought,” said Piglet thoughtfully, “that if everyone was under the tree, and Pooh stood on his back, and I stood on Pooh’s shoulders...
“And if Na-Na’s back suddenly became sad, we would all have a great laugh,” said Na.

A. A. Mill. Winnie the Pooh

In 1958, a general universal scheme with transformative processing of coefficients was found. The structure of this scheme for a polynomial of even degree ($n = 2k$) resembles a pyramid - at the base lies scheme (5) (we have already seen its “strength”), contained in a scheme of degree 6, which is contained in a scheme of degree 8, etc.:
$$\begin{cases} p_1 = x(x + b_1), \\ p_2 = (p_1 + b_2)(p_1 + x + b_3) + b_4, \\ p_3 = p_2(p_1 + b_5) + b_6, \\ \dots \\ p_k = p_{k-1}(p_1 + b_{2k-1}) + b_{2k}, \\ f(x) = p_k, \end{cases}$$

scheme (7.2) is exactly scheme (5). The result of scheme (7.k) is a polynomial $p_k(x)$ of degree $n = 2k$; a polynomial of odd degree $n = 2k + 1$ can be represented in the following form:
$$f(x) = x(x^2k + a_1x^{2k-1} + \dots + a_{2k}) + a_{2k-1};$$
the polynomial in parentheses is calculated using scheme (7.k). In the end

⟦folio 32⟧

the circuit contains $k$ multiplications and $2k+1$ additions for a polynomial of even degree $n=2k$ and $k+1$ multiplications and $2k+2$ additions for a polynomial of odd degree $n=2k+1$ (taking into account (7.k) and (8.)).

Exercises
4. Find formulas for preliminary processing of coefficients, similar to formulas (6), for scheme (7.3) for calculating polynomials of the sixth degree.
5. Prove by induction on $k \geq 2$ the universal scheme (7.k).

Starting from the third line, diagram (7.k) is very similar to Horner's diagram (3); the only difference is that now after each multiplication the degree increases not by one, but by two.

So, we managed to reduce the number of multiplications by half compared to Horner’s scheme. At what cost? From the solution to Exercise 5 it is clear that the process of calculating the parameters $b_1, b_2, \dots, b_{2k}$ from the coefficients $a_1, a_2, \dots, a_n$ is very complex - it involves solving a series of equations with one unknown power $k-1, k-2, \dots$. This means, in particular, that for $k \geq 6$ ($n \geq 12$) there are no formulas for calculating the parameters *), although, of course, their values ​​can be found by approximate methods with any degree of accuracy.

Here another difficulty arises, although it turns out that it can be solved. Until now, we have not specified which polynomials we are calculating - real or complex. Horner's scheme is applicable in both cases, while scheme (7.k)

*) A formula is usually understood as a set of arithmetic operations, roots, powers. You probably know that E. Galou and N. Abel, brilliant (and both died very early) mathematicians of the 19th century, proved that such general formulas do not exist for finding the roots of polynomials of the fifth and higher powers (see «Kvant», 1973, No. 10, pp. 3-12).

mainly “complex” - complex parameters can correspond to real coefficients. The appearance of complex numbers in the calculation of real polynomials greatly increases the number of arithmetic operations *). Fortunately, in 1960, scheme (7.k), which needed to be more complicated, was turned into a real one; however, complete proofs in this case are already very difficult.

§ 6. About schemes in general...

“Just a minute, just a minute,” the sound of ears of corn was heard. — Please avoid scientific terms, use popular terms...
- Right! - the others confirmed. - Speak more clearly. What is a forest?
Ya. Osenka. Country walk in 2050.

It's time to ask if there are any schemes that are more economical than scheme (7.k)? But then the question is inevitable - what is a scheme?

Defined. (I). A scheme with preliminary processing of coefficients is a sequence of arithmetic operations that involve the variable $x$, parameters $b_1, b_2, \dots, b_m$ and the results of previous operations. We call the result of the last operation `результатом схемы`. (II). If, for some set of parameter values ​​$b_1, \dots, b_m$, the result of the scheme is a given polynomial of degree $n$, then we say that the scheme is `представляем этот многочлен`. (III). If the circuit is represented by a polynomial, then the process of calculating the corresponding set of parameter values ​​from its coefficients is called `предварительной обработкой коэффициентов`. (IV). A scheme is called `supersal degree $n$ if it is represented by any polynomial of degree $n$ of the form (1).

*) One “complex” addition is two “real” ones, one “complex” multiplication is four (!) multiplications and two additions.
