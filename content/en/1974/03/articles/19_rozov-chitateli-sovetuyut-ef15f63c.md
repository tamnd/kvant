---
id: 1974-3-rozov-chitateli-sovetuyut-ef15f63c
issue: kvant_1974_3
year: 1974
number: "3"
title: Readers advise
authors:
  - Розов Н. Х.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 50
page_last: 53
page_labels: 48-51
tag: CTEA
lang: en
source: kvant_digital
extraction: vision
content_sha256: 38233fcf0633e8cce4aac0326505b48f009b988c7736a09d5aebd2dbd8759458
prompt_sha256: draft-1
translated_from: content/ru/1974/03/articles/19_rozov-chitateli-sovetuyut-ef15f63c.md
source_content_sha256: 712e6e2f929fa971a1b6c3a945008ee5e5abef44c15de03cc938cbeeb0d9ee0f
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 48⟧

Reader advise
N. Kh. Rozov

In the general editorial mail «Kvant» there are many letters that discuss certain theoretical issues of the school course in mathematics and physics, propose methods for solving certain types of problems, and contain individual comments and observations of a methodological nature. Although the messages and tasks given by readers are not always new and original, a number of issues raised in the letters, in our opinion, are of interest to applicants.

Therefore, today the required article is published in the “Applicant's Workshop”: the editors are publishing a selection of materials on mathematics, compiled according to ideas and suggestions from readers’ letters. We hope that collections like these provide timely experiences and ideas.

At entrance exams, they often offer tasks of this type: find out (do not use tables) which is greater: $\log_a M$ or $\log_b N$, where $a, b, M, N$ are the given numbers, and, naturally, $a > 0, a \neq 1, b > 0, b \neq 1, M > 0, N > 0$. In the “Applicant's Workshop” (see «Kvant», 1972, No. 3) examples of solving similar problems have already been given. Reader V.A. Grubyan (Berezniki, Perm region) draws attention to the possibility of using the following example to compare the magnitude of logarithms of two numbers.

The solution problem is quite simple if we can find an integer $k$ such that, say,

$$\log_a M < k, k < \log_b N.$$

Therefore, the most interesting case is when

$$k - 1 < \log_a M < k,$$
$$k - 1 < \log_b N < k.$$

In this case, one should strive to choose a natural number $n$ such that between $n$ and $n \log_b N$ there is a certain integer $p$. The selection of the number $n$ with the specified property is carried out by successive trials.

Example 1. Compare $\log_3 4$ and $\log_7 10$.

It is easy to check that $1 < \log_3 4 < 2, 1 < \log_7 10 < 2$, but from here it is not clear which of the proposed logarithms is greater. Let's take $n = 2$; we get $2 \log_3 4 = \log_3 16, 2 \log_7 10 = \log_7 100$. Since $2 < \log_3 16 < 3$ and $2 < \log_7 100 < 3$ (make sure of this!), then the value $n = 2$ does not have the required property. Similarly, we check that the value $n = 3$ does not suit us.

For $n = 4$ we get:

$$4 \log_3 4 = \log_3 256, 4 \log_7 10 = \log_7 1000.$$

Since $3^5 = 243, 3^6 = 729$ and $7^4 = 2401, 7^5 = 16807$, then $5 < 4 \log_3 4 < 6, 4 < 4 \log_7 10 < 5$, so the value $n = 4$ has the required property (the role of $p$ is played by the number 5). From here we get that

$$\log_3 4 > \log_7 10.$$

Example 2. Which of the two numbers is greater: $\log_{\sqrt{2}} \frac{6}{11}$ or $\log_{2/5}$?

It is directly verified that both numbers are between -2 and -1. Taking $n = 2$ we get

⟦folio 49⟧

$$2 \log_2 \frac{6}{11} = -\log_2 \frac{11^4}{6^4},$$

where is it easy to find what
$$-4 < 2 \log_2 \frac{6}{11} < -3.$$

On the other side,
$$2 \log_2 \pi = \log_2 \pi^2,$$
and a simple calculation shows that
$$-3 < \log_2 \pi^2 < -2.$$

Thus, $\log_2 \frac{6}{11} < \log_2 \pi$.

Of course, the number of trials required to select the required $n$ varies in different problems (and can be large), but the important thing is that there will always be such a $n$. Namely, we will prove the following statements, which are the theoretical basis for the technique used: if $\log_a M \neq \log_b N$, then there is a natural number $n$ such that between $n \log_a M$ and $n \log_b N$ there is some integer.

Let $\alpha = \log_a M$ and $\beta = \log_b N$, and $\alpha \neq \beta$. Let us assume, for example, that $\alpha > \beta$ (the case $\alpha < \beta$ is treated similarly). Then $\alpha - \beta$ is a positive number, and therefore there is a natural number $n$ such that the fraction $1/n$ is less than this positive number: $\frac{1}{n} < \alpha - \beta$ or $n\alpha - n\beta > 1$. But the last inequality means that the numbers $n\alpha = n \log_a M$ and $n\beta = n \log_b N$ differ by more than one, which means that there must be some integer between these numbers.

In conclusion, let us recall one general method for determining the sign of inequality between numbers (or expressions) $\alpha$ and $\beta$: it is important to choose a number (expression) $\gamma$ for which, for example, $\alpha < \gamma$ and at the same time $\gamma < \beta$. The one described above is essentially a variant of this method: the role of $\gamma$ is played here by the number $p/n$.

Exercises

1. (MSU, Faculty of Psychology, 1969). Prove, without using tables, that $\log_3 7 > \log_7 27$.

2. (MSU, Faculty of Philology, 1969). Prove, without using tables, that $\log_5 14 > \log_7 18$.

3. (MSU, Faculty of Economics, 1972). Do not use tables, determine which is greater: $\log_4 60$ or $\log_3 30$.

When proving, algebraic identities and, in particular, the identities
$$a^n - b^n = (a - b) (a^{n-1} + a^{n-2} b + \dots + ab^{n-2} + b^{n-1}),$$
where $n$ is a natural number, and $a$ and $b$ are real numbers. 10th grade student L. Davitidze (village of Shukhevi, Georgian USSR) invites readers of the magazine to use this identity (by proving it) to solve the next exercise.

4. Prove; that if $m$ is a natural number and $c \ge 1$, then the inequality is true
$$m^2 - c + 1 + m^2 - c - 1 < 2m^2 - c.$$
The solution to some problems can be significantly simplified if we apply a successful trigonometric substitution. The flexibility of trigonometric formulas allows, in some cases, to facilitate transformations, get rid of radicals, and obtain simpler and more understandable expressions. This issue is addressed in letters from our readers V.V. Pikan (Kyiv) and D.P. Dorozhin (Pavlovskaya Sloboda, Moscow region).

The essence of trigonometric substitution is that the variable $x$, included in the expressions appearing in the conditions for specifying, is considered as the value of some trigonometric function of the auxiliary variable angle $φ$, and they try to select this function so that the proposed expressions are written more compactly.

Example 3: Calculate the value of an expression
$$A = \left[ \frac{(x^2 + a^2)^{-1/4} + (x^2 - a^2)^{-1/4}}{(x^2 + a^2)^{-1/4} - (x^2 - a^2)^{-1/4}} \right]^{-3} \tag{1}$$

⟦folio 50⟧

$$npu x = a \left( \frac{m^2 + n^2}{2mn} \right)^{1/2},$$
$$\varepsilon de a < 0, n > m > 0.$$

Since the value $x$ that interests us is negative, we first of all simplify expression (1), assuming that $x < a$. (Note that (1) makes sense only for $|x| > |a|$, and prove that the value $x$ specified in the condition does not satisfy this inequality!). The presence of binomials $x^2 \pm a^2$ suggests the idea of ​​putting $x = a \mathrm{tg} \varphi$, which allows us to write these binomials in the procedure:

$$x^2 + a^2 = \frac{a^2}{\cos^2 \varphi},$$
$$x^2 - a^2 = -\frac{a^2 \cos 2\varphi}{\cos^2 \varphi}.$$

We apply trigonometric substitution to Pozny:

$$x = a \mathrm{tg} \varphi, \frac{\pi}{4} < \varphi < \frac{\pi}{2}.$$

Simple transformations show that then

$$A = \left( \frac{\sqrt{4 - \cos 2\varphi} - 1}{\sqrt{4 - \cos 2\varphi} + 1} \right)^3, \frac{\pi}{4} < \varphi < \frac{\pi}{2}.$$

Further, it is easy to calculate that if $x = a \mathrm{tg} \varphi = a \left( \frac{m^2 + n^2}{2mn} \right)^{1/2}$, then

$$\cos 2\varphi = \frac{1 - \mathrm{tg}^2 \varphi}{1 + \mathrm{tg}^2 \varphi} = -\frac{(n - m)^2}{(n + m)^2},$$

and then at the specified value $x$

$$A = \frac{(4n^2 - m^2) \sqrt{n^2 - m^2} - (4n^2 - 3m^2)n}{m^3}.$$

Example 4: Solve the equation

$$\sqrt{1 + \sqrt{1 - x^2}} \left[ \sqrt{(1 + x)^3} - \sqrt{(1 - x)^3} \right] = 2 + \sqrt{1 - x^2}.$$

The range of acceptable values ​​for this equation is the set $|x| \leq 1$. If we use the trigonometric substitution $x = \cos \varphi, 0 \leq \varphi \leq \pi$, then it is easy to check that from radicals we can use the principle of the form

$$\left( \cos \frac{\varphi}{2} + \sin \frac{\varphi}{2} \right) \cdot 2\sqrt{2} \times \left( \cos^3 \frac{\varphi}{2} - \sin^3 \frac{\varphi}{2} \right) = 2 + \sin \varphi.$$

From here, in turn, we obtain the equation

$$\sqrt{2} \left( 1 + \frac{1}{2} \sin \varphi \right) \cos \varphi = 1 + \frac{1}{2} \sin \varphi$$

or

$$\left( \sqrt{2} \cos \varphi - 1 \right) \left( 1 + \frac{1}{2} \sin \varphi \right) = 0,$$

which is controlled only at $\cos \varphi = \sqrt{2}/2$. Therefore, the original equation has root $x = \sqrt{2}/2$.

Example 5. Find the smallest and largest values ​​of a function

$$y = \frac{1 + x^4}{(1 + x^2)^2}.$$

The argument of this function runs over all real numbers, and therefore we can consider $x$ as the value of the tangent of the auxiliary variable angle $\varphi$, varying over the interval $-\pi/2 < \varphi < \pi/2$. The prigonometric substitution $x = \mathrm{tg} \varphi, -\pi/2 < \varphi < \pi/2$ allows, together with function (2), to study the function

$$y = 1 - \frac{1}{2} \sin^2 2\varphi$$

at $-\pi/2 < \varphi < \pi/2$. Since $0 \leq \sin^2 2\varphi \leq 1$, it is obvious that the smallest value of function (3) is equal to $\frac{1}{2}$ and is achieved at $\varphi = -\pi/4$ and at $\varphi = \pi/4$, and the largest is equal to 1 and is achieved at $\varphi = 0$. From here we conclude that the smallest value of function (2) is equal to $\frac{1}{2}$ and is achieved at $x = -1$ and at $x = 1$, and the largest is equal to 1 and is achieved at $x = 0$.

Note that examples of using trigonometric substitutions to solve the equation have already been discussed.

⟦folio 51⟧

looked at in the “Enrollee's Workshop” (see «Kvant», 1971, No. 1).

At the yarn
5. Simplify an expression
$$B = \frac{(m+x)^{3/2} - (m-x)^{3/2}}{(m+x)^{3/2} + (m-x)^{3/2}}, \quad m > 0.$$

6. Find the most and most values ​​of a function
$$y = \frac{(x+1)^2}{x^2+1}.$$

9th grade student V. Olasyuk (Tulup, Irkutsk region) invites readers of the magazine to solve the following problem.

7. The face of the paper shows the coordinate axes and a parabola, which is the graph of the function $y = x^2$. However, the same length used when constructing a graph to measure distances along the axes is not indicated. How to restore this single length?

***

When solving an equation, a successful replacement of the unknown often allows us to consider a simpler one instead of the complex original equation. However, “seeing” the need for a replacement is not always easy, and only reality, acquired experience and the meaning of the most common replacements can help here.

Our reader I.A. Gavrilov (Fryazino, Moscow region) in his letter recalled one type of substitutions for solving algebraic equations. These replacements can rightfully be called “symmetrizations.”

Let us show what “symmetrization” consists of using the example of two fourth-degree equations.

If the equation
$$(x-a)^4 + (x-b)^4 = c$$
enter a new unknown instead of the unknown $x$
$$y = x - \frac{a+b}{2},$$
We can obtain a biquadratic equation.

It is clear that for any $x$ the number $x - \frac{a+b}{2}$ is the midpoint of the segment with ends at the points $x-a$ and $x-b$. If in equations
$$(x-a)(x-b)(x-c)(x-d) = p$$ (4)
if any pairs of numbers $a, b, c, d$ coincide, for example, $a-b = c-d$, then replacing the unknown
$$y = x - \frac{b+c}{2}$$
leads to a biquadratic equation (check it out!). Note that if $a-b = c-d$, then the binomial $x-a - \frac{b+c}{2}$ serves in some “centrosity” of the factors $x-a, x-b, x-c, x-d$, which is clearly seen from the geometric interpretation of these equations by points of the number axis (see figure).

The idea of ​​“symmetrization” is successfully used in solving a number of other algebraic equations and systems of equations.

At the yarn
8. Solve equation $x^2 + \frac{25x^2}{(x+5)^2} = 11$.
9. Solve the equation
$$4\sqrt{x} + \sqrt{4-x^2} = 4+x.$$
10. Find real solutions to the system of equations
$$\begin{align*}
(x+y-2)^4 + (x+y)^4 &= 82, \\
x^2-y^2 &= 3.
\end{align*}$$
11. (UDN, 1973). Solve the equation
$$(x^2-4x)^2 + 2(x-2)^2 = 43.$$
12. (UDN, 1973). Solve the equation
$$\frac{5}{x^2+3x} + \frac{6}{(x+1)(x+2)} = 1.$$
