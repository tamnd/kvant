---
id: 1977-10-egorov-uravneniya-i-predelyi-23685e69
issue: kvant_1977_10
year: 1977
number: "10"
title: Equations and limits
authors:
  - Егоров А. А.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 36
page_last: 40
page_labels: 34-38
tag: CVXP
lang: en
source: kvant_digital
extraction: vision
content_sha256: 929fcf04374b5526cafa8475ac1962fbfb052f1cdbe5b25ff5d3ee5eb951e953
prompt_sha256: draft-1
translated_from: content/ru/1977/10/articles/08_egorov-uravneniya-i-predelyi-23685e69.md
source_content_sha256: be92e8e6d81a6308c90f1c6a1da849d4cc9feb0d2c751ebcc3f4f47f342f9d15
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 34⟧

A. Egorov

Equations and previous

1. Simple example

To approximately calculate the square root of a positive number $a$ proceed as follows (see, for example, the book “Algebra and Principles of Analysis 9”, p. 83).

An arbitrary number $a_0 > \sqrt{a}$ is taken as a first approximation. The next approximation $a_1$ is found by the formula

$$a_1 = \frac{1}{2} \left( a_0 + \frac{a}{a_0} \right),$$

by $a_1$ find $a_2$:

$$a_2 = \frac{1}{2} \left( a_1 + \frac{a}{a_1} \right)$$

and in general

$$a_n = \frac{1}{2} \left( a_{n-1} + \frac{a}{a_{n-1}} \right).$$

The $\{a_n\}$ sequence kills monotonously and is limited. According to Weierstrass's theorem, it has a limit. Let $\lim_{n \to \infty} a_n = s$. Then $s > 0$ and $s = \frac{1}{2} \left( s + \frac{a}{s} \right)$, that is, $s^2 = a$, and since $s > 0$, then $s = \sqrt{a}$.

If we take a large enough $n$, then $a_n$ will differ quite little from $\sqrt{a}$.

Exercise
1. Prove that the sequence $\{a_n\}$ kills monotonically.
2. Estimate the difference $|a_n - \sqrt{a}|$.

Let us analyze our method for calculating successive approximations for $\sqrt{a}$. The sequence $\{a_n\}$ was specified recurrently: $a_n = \varphi(a_{n-1})$, where $\varphi(x) = \frac{1}{2} \left( x + \frac{a}{x} \right)$. Having established the convergence of the sequence $\{a_n\}$, we concluded that its limit $s$ satisfies the equality $s = \frac{1}{2} \left( s + \frac{a}{s} \right)$, that is, it is the root of the equation

$$\varphi(x) = x.$$

(1)

figure 1 shows the graph of the function $y = \frac{1}{2} \left( x + \frac{2}{x} \right)$, $x > 0$, and shows the first three terms of the sequence

$$\begin{cases} a_0 = 2, \\ a_n = \frac{1}{2} \left( a_{n-1} + \frac{2}{a_{n-1}} \right). \end{cases}$$

Exercise 3. Express $a_n$ in terms of $n$ if $a_0 = 1$ and a) $a_n = a \cdot a_{n-1}$; 6) $a_n = a^a_{n-1}$; 7) $a_n = \sqrt{a + a_{n-1}}$; 8) $a_n = \frac{a_{n-1}}{\sqrt{1 + a_{n-1}^2}}$; 9) $a_n = \frac{1}{1 + a_{n-1}}$.

2. Equations and previous

Let us need to solve equation (1), where $\varphi$ is some function. Let's take an arbitrary number $a_0 \in D(\varphi)$ and define the sequence $\{a_n\}: a_n = \varphi(a_{n-1})$ recurrently. Suppose $a_n \in D(\varphi)$ for all $n \in \mathbb{N}$.

Fig. 1.

⟦folio 35⟧

Theorem 1. If the sequence $\{a_n\}$ converges to s and the function φ is continuous for $x = s$, then s is the root of equation (1).

This theorem was actually applied in paragraph 1. The choice of the first approximation (or the “zero term” of the sequence) is dictated by messages of convenience - $a_0$ is natural to be closer to the original root.

As will be seen from what follows, a clever study of the solvability of equation (1) sometimes allows us to solve the question of the convergence of the corresponding sequence $\{a_n\}$.

Exercises
4. Investigate the convergence of sequences:

a) $a_n = \sqrt{a + a_{n-1}}, a_0 = 0$;
b) $a_n = \frac{1}{1 + a_{n-1}}, a_0 = 1$.
5. Indicate a method for finding the positive root of the equation
$$x^3 - x - 1 = 0.$$ (1)
6. (With an approximate method for calculating $\sqrt[3]{a}$.) The sequence $\{a_n\}$ is constructed according to the following rule:
$$\begin{cases} a_0 = a > 0, \\ a_n = \frac{1}{3}(2a_{n-1} + \frac{a}{a_{n-1}}). \end{cases}$$
Prove that $\lim_{n \to \infty} a_n = \sqrt[3]{a}$.
7. Let $a > 0, b > 0, p > 0, q > 0$. Consider the sequence
$$\frac{a}{b}, \frac{b}{pa+qb}, \frac{pa+qb}{pb+q(pa+qb)}, \dots, \frac{a_n}{b_n}, \dots$$
where $a_{n+1} = b_n, b_{n+1} = pa_n + qb_n$. Is there a limit to this sequence?
(This problem was suggested by our reader V. Fischuk.)

3. Main example

The rest of the article is devoted to the question of the convergence of the sequence
$$\begin{cases} \alpha_0 = 1, \\ \alpha_n = a^{\alpha n-1}, \end{cases}$$ (2)
that is, 1, $a, a^a, a^{a^a}, a^{a^{a^a}}, \dots$. This convergence depends, of course, on the parameter $a$.

It turns out that for large $a$ it is relatively easy to find out the existence of the limit, and for small ones -

much more difficult. Let's give a few examples.

For $a = 2$ we obtain the sequence
1; 2; 4; 16; 65536; ...
(she, very/no, disagrees).

When $a = 1,5$ is the sequence
1; 1,5; 2,106; 2,349; 2,592; ...
$\alpha_{11} \approx 10,99; \alpha_{12} \approx 86,163; \alpha_{13} > 10^{16}$
(she also diverges, but here from the very beginning it is not so much/no).

For $a = \sqrt{2} = 1,4142$ ...—sequence
1; $\sqrt{2}$; 1,632; 1,761; ...
$\alpha_8 \approx 1,966; \alpha_{25} \approx 1,9999$ (here, as we will see, the limit exists and is equal to 2).

At $a = 1$
1, 1, 1, ...
(limit, very/no, exists and is equal to 1).

At $a = 0,5$
1; 0,5; 0,707; 0,613; 0,654; ...
$\alpha_{12} \approx 0,641206; \alpha_{13} \approx 0,641177$.

At $a = 0,01$
1; 0,01; 0,955; 0,0123; 0,945; 0,013; ...
$\alpha_{15} \approx 0,013; \alpha_{16} \approx 0,941$ (we will comment on the behavior of the last two sequences at the end of the article).

From Theorem 1 we know that if $\lim_{n \to \infty} a_n = s$ then s is the root

⟦folio 36⟧

Equation
$$a^x = x$$
(the function $x \rightarrow a^x$ is continuous at all points on the number line). Consequently, if equation (3) for some $a$ has no roots, then the corresponding sequence (2) diverges.

figure 2 shows the graph of the function $y = a^x$ and the first terms of sequence (2) - for $a > 1$ and the assumption that equation (3) has roots; on figure 3 - the same with $0 < a < 1$.

4. $a > 1$
For $a > 1$, sequence (2) increases monotically (check!).

Theorem 2. For $a > 1$, sequence (2) converges moeda and molъko moeda when equation (3) has at least one root. In this case, its limit is equal to the smaller of the roots of equation (3).

Proof. We just noted that if sequence (2) converges, then its limit is the root of equation (3). Let now equation (3) have roots. Let us denote by $s_0$ the smallest root. Let us show that $\alpha_n < s_0$ for all $n \in \mathbb{N}$. It's easy to see that $s_0 > 1 = \alpha_0$. If $s_0 > \alpha_n$, then $s_0 = a^{s_0} > a^{\alpha_n} = a_{n+1}$. From Weierstrass's theorem it follows that sequence (2) converges, and, obviously, to $s_0$. The theorem has been proven.

5. $0 < a < 1$
In this case, sequence (2) is limited: $0 < \alpha_n < 1$. Unfortunately, it is not monotonous. In fact, since $0 < a < 1$, the function $y = a^x$ kills, and $\alpha_2 = a^a < 1 = \alpha_0$, therefore, if equation (3) for some $a$ has no roots, that is, $\alpha_3 > \alpha_1$. Next, $\alpha_4 = a^{\alpha_3} < a^{\alpha_1} = \alpha_2$, that is, $1 = \alpha_0 > \alpha_2 > \alpha_4$. Using the method of mathematical induction, it is easy to prove that the subsequence $\alpha_1, \alpha_3, \alpha_5, \dots, \alpha_{2n-1}, \dots$ of our sequence is monotically increasing, and the subsequence $\alpha_0, \alpha_2, \alpha_4, \dots, \alpha_{2n}, \dots$ is monotonic killing. In this case, it is always $\alpha_{2n} > \alpha_{2n-1}$. By Weierstrass's theorem, each of these subsequences has a limit. Let $\lim_{n \to \infty} \alpha_{2n-1} = s_1$ and $\lim_{n \to \infty} \alpha_{2n} = s_2$. It is clear that $s_2 \geq s_1$ and subsequence (2) will be convergent if and only if $s_1 = s_2$ (proof!).

What can you say about the numbers $s_1$ and $s_2$? Since $\alpha_{2n+2} = a^{a^{\alpha_{2n}}}$, $\alpha_{2n+1} = a^{a^{\alpha_{2n-1}}}$ and the function $x \rightarrow a^{a^x}$ are continuous at all points on the number line, the numbers $s_1$ and $s_2$ are the roots of equation (3).

Theorem 3. The numbers $s_1$ and $s_2$ are the ratio of the lesser and greater roots of equation (4).

Proof. Let $s$ be an arbitrary root of equation (4). To prove the theorem, it is enough to establish that $\alpha_{2n-1} < s < \alpha_{2n}$ for all $n \in \mathbb{N}$.

First of all, note that $s < 1$. Indeed, if $s \geq 1$, then, in view of $a^s > 0$, $a^{a^s} < 1$, that is, $a^{a^s} \neq s$. In addition, it is very convenient, $s > 0$. From $0 < s < 1$ follows $a^0 > a^s > a^1$, that is, $\alpha_0 > a^s > \alpha_1$. So, $a^{\alpha_0} < a^{a^s} < a^{\alpha_1}$, that is, $\alpha_1 < s < \alpha_2$. The induction step is done in a similar way.

Corollary 1. If equation (4) has more than one root, then sequence (2) diverges.

Corollary 2. If equation (4) has more than one root, then sequence (2) converges, and the limit

⟦folio 37⟧

Fig. 4.

this sequence is the root of equation (3).

It is easy to see that every root of equation (3) also satisfies equation (4). But for $0 < a < 1$, equation (3) obviously has a root (draw the graphs!). This means that for such $a$ equation (4) must have at least one root.

Exercise 8: Consider the sequence $\alpha_0 = x > 0, \alpha_n = a^{\alpha n-1}$. For what $x$ does this sequence converge? (Consider the case of $a > 1$ and $0 < a < 1$ separately).

So, the question about the convergence of sequence (2) coincides with the question about the number of roots of equation (3) for $a > 1$ and equation (4) for $0 < a < 1$.

6. Study of equation (3) at $a > 1$

Equation (3) is equivalent to equation

$$\frac{\ln x}{x} = \ln a.$$ (Fig. 4). This function is defined at $x > 0$, reaches a maximum of $1/e$ at $x = e$, kills at $x > e$, and returns at $0 < x < e$.

Exercise 9. Carry out a similar study of the functions $y = \frac{\ln x}{x}$.

Consequently, for $\ln a > 1/e$, that is, $a > e^{1/e}$, equation (5) has no roots.

Fig. 5.

For $0 < \ln a < 1/e$, that is, $1 < a < e^{1/e}$, equation (5) has two roots.

At $a = e^{1/e}$ it has one root.

Let us note for further that for $\ln a \leq 0$, that is, $0 < a \leq 1$, equation (5) has a single root.

7. Study of equation (4) at $0 < a < 1$

We already know that all roots of equation (4) are contained in the interval $[0; 1]$. Equation (4) is equivalent to equation $a^x = \log_a x$, $x = \log_a \log_a x$ or $x = \frac{1}{\ln a} \ln \frac{\ln x}{\ln a}$. Let us denote by $\varphi$ the function

$$\varphi(x) = \frac{1}{\ln a} \ln \frac{\ln x}{\ln a} - x.$$

We want to find out how many roots, depending on the parameter $a$, the equation $\varphi(x) = 0$ has, which is equivalent to equation (4). To do this, you need to count how many points of intersection of the graph of functions $\varphi$ there are with the abscissa axis.

First of all, we note that the point $s_0$ obviously belongs to these intersection points, where $s_0$ is the only root of equation (3), (5), see the substitutions at the end of paragraphs. 6 and 5.

Let's study the function $\varphi$.

Since $\ln a < 0$, the function $\varphi$ is defined at $0 < x < 1$. At $x \rightarrow 0$ (right) $\varphi(x) \rightarrow -\infty$; at $x \rightarrow 1$ (left) $\varphi(x) \rightarrow +\infty$.

⟦folio 38⟧

Let us find the extrema of the function $f$; To do this, we examine its derivative:

$$\varphi'(x) = \frac{1}{x \ln x \ln a} - 1.$$

Equating it to zero, we get the equation

$$x \ln x = \frac{1}{\ln a}.$$

(6)

figure 5 shows the graph of the function $y = x \ln x$.

Exercise 10. Explore the function $y = x \ln x$ and graph it.

We see that at $x = 1/e$ the function $y = x \ln x$ reaches a minimum equal to $-1/e$. Therefore, if $1/\ln a < -1/e$, that is, $\ln a > -e$ or $a > e^{-e}$, then equation (6) has no roots. So for $e^{-e} < a < 1$ the derived function $f$ is strictly greater than zero, that is, for such values ​​of $a$ the function $f$ is strictly increasing. This means that the equation $f(x) = 0$ with $e^{-e} < a < 1$ has a single root $s_0$ (an approximate graph of the function $f$ for $e^{-e} < a < 1$ is shown in figure 6).

If $a = e^{-e}$, then $\varphi'(x) = 0$ for $x = 1/e$ and $\varphi'(x) > 0$ for all others $x \in [0; 1/e] \cup [1/e; 1]$.

In this case, $f$ is also strictly increasing throughout the entire domain of definition, and the equation $f(x) = 0$ still has a single root $x = 1/e$ (the graph of the function $f$ for $a = e^{-e}$ is depicted in figure 7).

So, if $e^{-e} \leq a < 1$, equation (4) has exactly one root.

If $0 < a < e^{-e}$, then equation (6) has two roots: $x_1$ and $x_2$ (Fig. 5). Moreover, at $x \in [0; x_1]$ $x_1$ [∪] $x_2$; 1 [the derivative of $\varphi'(x)$ is positive, and at $x \in [x_1; x_2]$ it is negative, so that $x_1$ is the maximum point and $x_2$ is the minimum point of the function $f$; This means that $\varphi$ at $x \in [0; x_1]$ [increases and at $x \in [x_1; x_2]$ 1 [increases, and at $x \in [x_1; x_2]$ it decreases (figure it out!).

Let us now show that $s_0 \in [x_1; x_2]$. To do this, it is enough to prove that $\varphi'(s_0) < 0$. We have

$$\varphi'(s_0) = \frac{1}{s_0 \ln s_0 \ln a} - 1 = \frac{1}{(\ln s_0)^2} - 1$$

(since $\frac{\ln s_0}{s_0} = \ln a$). Let us prove that $\ln s_0 < -1$ (then $\varphi'(s_0) < 0$). To do this, let us turn again to the function $y = \frac{\ln x}{x}$ (Fig. 4). Since it increases at $0 < x < 1$, and $\ln a < -e$, the root $s_0$ of equation (5) lies to the left of the root of the equation $\frac{\ln x}{x} = -e$, that is, to the left of the point $e^{-1}$. So, $s_0 < 1/e$ and $\ln s_0 < -1$.

So, about the function $f$ we now know that

1) $\varphi(x) \rightarrow -\infty$ at $x \rightarrow 0$;
2) $\varphi(x) \rightarrow +\infty$ at $x \rightarrow 1$;
3) $\varphi$ increases on the interval $|0; x_1|$, at point $x_1$ has a maximum, decreases on the interval $|x_1; x_2|$, at point $x_2$ has a minimum and increases again on the interval $|x_2; 1|$;
