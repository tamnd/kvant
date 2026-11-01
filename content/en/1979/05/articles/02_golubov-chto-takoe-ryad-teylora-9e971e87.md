---
id: 1979-5-golubov-chto-takoe-ryad-teylora-9e971e87
issue: kvant_1979_5
year: 1979
number: "5"
title: What is a Taylor series?
authors:
  - Голубов Б. И.
rubric: osnovnye-stati
page_first: 4
page_last: 9
page_labels: 2, 4, 5, 6, 7
tag: GRIE
lang: en
source: kvant_digital
extraction: vision
content_sha256: 0a916b60400e65a053fd5c1a15545bbe4472b7c6d55330bca2b5ac58a3f69ee5
prompt_sha256: draft-1
translated_from: content/ru/1979/05/articles/02_golubov-chto-takoe-ryad-teylora-9e971e87.md
source_content_sha256: 3b3d444a7304e8bfa436d15d37274f9db9f2563448572a3d299b21367477d170
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 2⟧

B. Golubov

What is a Taylor series?

The name of the English mathematician Brooke Taylor entered the history of mathematics thanks to the discovery he made in 1715, at the age of 29. What is this discovery? We will try to tell you about this.

Look at figure 1-3. They show the graphs of functions $y = e^x$, $y = \frac{1}{1+x}$ and $y = \ln(1+x)$.

Number 1 on each of these figure shows the tangent to the corresponding graph at point $x = 0$, that is, the graph of some linear function $y = ax + b$ (check what exactly the corresponding function will be -

tions $y = 1+x$, $y = 1-x$ and $y = x$). Number 2 on each of these figure shows the tangent of the square triangle $y = ax^2 + bx + c$, which at point $x = 0$ is adjacent to the graph of the corresponding function “closer” than all other square triangles. More precisely, we are talking about square triangles that at the point $x = 0$ coincide with the corresponding functions along with their arbitrary first and second order. In these cases, the graphs of these square triangles are said to have a second-order tangency with the corresponding graphs (check that the corresponding square triangles $y = 1+x + \frac{x^2}{2}$, $y = 1-x + x^2$ and $y = x - \frac{x^2}{2}$ will be so).

Finally, number 3 in Figures 1-3 shows the graphs of functions $y = ax^3 + bx^2 + cx + d$, which have a third-order tangency with the graphs of the corresponding curves at point $x = 0$ (it’s easy to say that this is

⟦folio 4⟧

In this article, we will obtain the Taylor series for the function $y=\sin x$, $y=\cos x$, $y=e^x$ and $y=\ln(1+\dot{x})$.

Necessary information from the analysis

First of all, we need the Newton-Leibniz formula:

$$\int_a^b f(x) \, dx = F(b) - F(a),$$

where the function $f$ is continuous on the interval $[a; b]$, and the function $F$ is antiderivative for it on this interval.

Further, from the geometric meaning of the integral it follows that $\int_a^b f(x) \, dx \geq 0$ if $f(x) \geq 0$ is on $[a; b]$ (Fig. 5). It easily follows from this that if two continuous functions on the interval $[a; b]$ satisfy the inequality $f(x) \leq g(x)$, then $\int_a^b f(x) \, dx \leq \int_a^b g(x) \, dx$, that is, inequalities connecting irregular functions, can be interpreted, obtaining inequalities of the same sign.

Finally, we need equality

$$\lim_{n \to \infty} \frac{x^n}{n!} = 0,$$

where $x$ is any real number. Let's prove it. Given $x$, let us find a natural number $N$ such that $\frac{|x|}{N+1} \leq y=f(x)$

Fig. 5. $S = \int_a^b f(x) \, dx$.

$\leq \frac{1}{2}$. Then for all $n > N$ the inequalities will be satisfied

$$0 \leq \frac{|x|^n}{n!} = \frac{|x|}{1} \cdot \frac{|x|}{2} \cdot \dots \cdot \frac{|x|}{N} \times \times \frac{|x|}{N+1} \cdot \dots \cdot \frac{|x|}{n} \leq \frac{|x|^N}{N!} \cdot \left(\frac{1}{2}\right)^{n-N} = \frac{|x|^N \cdot 2^N}{N!} \cdot 2^{-n}.$$

Since $N$ is fixed, then for $n \to \infty$ the limit of the sequence on the right side of these inequalities is equal to zero. Hence equality (1) follows.

Taylor series representation of the function $\sin x$ and cos $x$

Let $x > 0$ be functioned. Then, integrand the inequality $\cos t \leq 1$ over the segment $[0; x]$, we obtain that

$$\int_0^x \cos t \, dt \leq \int_0^x 1 \, dt.$$

But since sin $t$ is an antiderivative of cos $t$, and $t$ is an antiderivative of 1, the previous inequality based on the Newton-Leibniz formula can be written as $sin x \leq x$. This inequality could have been written straight away, but we wanted to explain the principle of obtaining further inequalities and therefore presented its proof.

Integrating the inequality $\sin t \leq t$ over the segment $[0; x]$, we obtain that

$$\int_0^x \sin t \, dt \leq \int_0^x t \, dt.$$

Since the function - cos $t$ is antiderivative for sin $t$, and $\frac{t^2}{2}$ is antiderivative for $t$, the previous inequality based on the Newton-Leibniz formula takes the form

$$1 - cos x \leq \frac{x^2}{2} \text{ или } cos x \geq 1 - \frac{x^2}{2}.$$

Integrator is an inequality along the segment $[0; x]$ and again use the Newton-Leibniz formula to arrive at the inequality $\sin x \geq x - \frac{x^3}{3!}$.

⟦folio 5⟧

Continuing the process of sequential integration (and using the method of mathematical induction), it is easy to prove the inequalities

$$\cos x \leq 1 - \frac{x^2}{2!} + \dots + \frac{x^{4n}}{(4n)!},$$

$$\sin x \leq x - \frac{x^3}{3!} + \dots + \frac{x^{4n+1}}{(4n+1)!},$$

$$\cos x \geq 1 - \frac{x^2}{2!} + \dots - \frac{x^{4n+2}}{(4n+2)!},$$

$$\sin x \geq x - \frac{x^3}{3!} + \dots - \frac{x^{4n+3}}{(4n+3)!},$$

where $n = 0, 1, \dots, x > 0$.

Combining the first and third of inequalities (2), we obtain

$$1 - \frac{x^2}{2!} + \dots - \frac{x^{4n+2}}{(4n+2)!} \leq \cos x \leq 1 - \frac{x^2}{2!} + \dots + \frac{x^{4n}}{(4n)!}.$$

The left polynomial can be viewed as an approximation of $\cos x$ with a disadvantage, and the right one can be considered an approximation of $\cos x$ with a known value (Fig. 6). But the difference between the right and left polynomials from inequalities (3) is equal to $\frac{x^{4n+2}}{(4n+2)!}$, and at $n \to \infty$ it tends to zero based on (1). That's why

$$\cos x = \lim_{n \to \infty} \left( 1 - \frac{x^2}{2!} + \dots - \frac{x^{4n+2}}{(4n+2)!} \right) = \lim_{n \to \infty} \left( 1 - \frac{x^2}{2!} + \dots + \frac{x^{4n}}{(4n)!} \right).$$

The result is written in the form

$$\cos x = 1 - \frac{x^2}{2!} + \dots + \frac{(-1)^n}{(2n)!} x^{2n} + \dots.$$

The right side of this equality is called $prdom Teйлора функции$ $\cos x$.

When proving inequalities (3), and therefore equality (4), we assume that $x > 0$. But they are also valid for $x < 0$ due to the parity of all functions included in them. Finally, they can easily be verified for $x = 0$ and are thus valid for all real $x$.

Similarly, for $x > 0$ from (2) we have

$$\sin x = \lim_{n \to \infty} \left( x - \frac{x^3}{3!} + \dots - \frac{x^{4n+3}}{(4n+3)!} \right) = \lim_{n \to \infty} \left( x - \frac{x^3}{3!} + \dots + \frac{x^{4n+1}}{(4n+1)!} \right).$$

This result is written in the form

$$\sin x = x - \frac{x^3}{3!} + \dots + \frac{(-1)^n}{(2n+1)!} x^{2n+1} + \dots,$$

and the expression on the right side of this equality is called $prdom Teйлора функции$ $\sin x$.

Note, finally, that equality (5) remains valid for $x \leq 0$ due to the parity of all functions included in it.

Taylor series expansion of functions $e^x$

It is known that $(e^x)' = e^x$, from which it follows that for any construction $C$ the function $e^x + C$ is antiderivative of $e^x$. In addition, it is important for us to know that $e > 1$ ($e = 2,718\dots$).

Since $e > 1$, then $1 \leq e^t \leq e^a$ for all $t \in [0; a]$. Interpreting this inequality along the segment $[0; x]$, where $0 \leq x \leq a$, we obtain $x \leq e^x - 1 \leq e^ax$ or $1 + x \leq e^x \leq 1 + e^ax$. These inequalities can also be integrated over the segment $[0; x]$ by first replacing $x$ in them with $t$. As a result we get

$$x + \frac{x^2}{2!} \leq e^x - 1 \leq x + e^a \frac{x^2}{2!},$$

Fig. 6.

⟦folio 6⟧

illy

$$1 + x + \frac{x^2}{2!} \leq e^x \leq 1 + x + e^a \frac{x^2}{2!} (0 \leq x \leq a).$$

Continuing the process of sequential integration, we obtain the inequalities

$$1 + x + \frac{x^2}{2!} + \dots + \frac{x^n}{n!} \leq e^x \leq 1 + x + \frac{x^2}{2!} + \dots + \frac{x^{n-1}}{(n-1)!} + \frac{x^n}{n!} e^a,$$

where $n=0, 1, \dots, 0 \leq x \leq a$.

Thus, for each value $x$ from the segment $[0; a]$, an approximate value for the function $e^x$ with a deficiency and an excess is obtained in the form of polynomials of degree $n$. The difference between the right and left polynomials in inequalities (6) is equal to $(e^a - 1) \frac{x^n}{n!}$; at $n \to \infty$ it tends to zero based on (1). Since $a$ is an arbitrary positive number, it follows from inequalities (6) that for any $x \geq 0$

$$e^x = \lim_{n \to \infty} \left( 1 + x + \frac{x^2}{2!} + \dots + \frac{x^n}{n!} \right).$$

Let's write this as an equality

$$e^x = 1 + x + \frac{x^2}{2!} + \frac{x^3}{3!} + \dots + \frac{x^n}{n!} + \dots$$

(7)

The expression on the right side of (7) is called the Taylor series of the function $e^x$.

Exercise not 1. Justify equality (7) for $x < 0$. (Indication not. Use the fact that $e^x < 1$ is at $x < 0$).

Taylor series expansion of the function $\ln(1+x)$

The function $\ln(1+x)$ is defined as $\log_e(1+x)$, that is, the base of the logarithm is $e$. Since $\ln(1+x)^\prime = \frac{1}{1+x}$ for all $x > -1$, then for $\frac{1}{1+x}$ the function $\ln(1+x) + C$ is antiderivative on the interval $-1; +\infty$ [ for any constructed $C$. We will use this below. Note that for $t \geq 0$ the inequality

$$1 - t + \dots + t^{2n-2} - t^{2n-1} \leq \frac{1}{1+t} \leq 1 - t + \dots + t^{2n-2} - t^{2n-1} \leq \frac{1}{1+t} \leq 1 - t + \dots + t^{2n-2} - t^{2n-1} + t^{2n}.$$

(8)

(Justify them yourself.)

Interpreting inequalities (8) along the segment $[0; x]$, where $x \geq 0$, and using the Newton–Leibniz formula, we obtain the inequalities

$$x - \frac{x^2}{2} + \dots - \frac{x^{2n}}{2n} \leq \ln(1+x) \leq x - \frac{x^2}{2} + \dots - \frac{x^{2n}}{2n} + \frac{x^{2n+1}}{2n+1},$$

(9)

in which $x \geq 0$. The difference between the right and left polynomials is $\frac{x^{2n+1}}{2n+1}$. If $0 \leq x \leq 1$, then it tends to zero at $n \to \infty$. That's why

$$\ln(1+x) = x - \frac{x^2}{2} + \dots + \frac{(-1)^{n+1}}{n} x^n + \dots$$

(10)

for $0 \leq x \leq 1$.

The equation is not 2. Make sure that this equality is also true for $-1 < x < 0$. (Note not. Use that for $t > -1$ $1 - t + \dots + t^{2n-2} - t^{2n-1} \leq \frac{1}{1+t} \leq 1 - t + \dots + t^{2n-2} - t^{2n-1} + t^{2n}$ if $\lambda > \frac{1}{1+t}$.)

The expression on the right side of equality (10) is called the Taylor series of the function $\ln(1+x)$.

When finding the Taylor series of the functions $\sin x$, $\cos x, e^x$ and $\ln(1+x)$, we used various artificial techniques. In fact, there is a unified method for finding the Taylor series of a function - it is based on its sequential differentiation. We can get acquainted with him in the wonderful book by A. Ya. Khinchin “Eight Lectures on Mathematical Analysis” (M., “Nauka”, 1977).

What does the resulting assessment mean?

The estimates for the functions $\sin x$, $\cos x, e^x$ and $\ln(1+x)$ obtained above allow us to calculate them at an arbitrary point with any required accuracy.

⟦folio 7⟧

For example, if we need to find out the value of the function sin x at the point $x \in \left[ 0; \frac{\pi}{2} \right]$ with an error not exceeding the number $\varepsilon > 0$, then we first find an integer $n \geqslant 0$ such that $x^{4n+1}/(4n+1)! < \varepsilon$. Then the values ​​of the polynomials from inequalities (2) at the point $x$ give us the value of sin x up to $\varepsilon$, one with a disadvantage, the other with a difference. Calculation of values ​​at other points using formulas for reducing the property to calculations at points of the segment $\left[ 0; \frac{\pi}{2} \right]$.

A little history

B. Taylor's work “Methodus incrementorum directa et inversa” was published in 1715 in London in Latin. Taylor was a contemporary of Newton and Leibniz - the founder of differential and integral calculus. His method was based on Newton's formula, which gives an approximate representation of a function on a given segment in the form of a polynomial of degree $n$, coinciding with the given function at $n+1$ equidistant points of the segment (including its end points). Taylor made the transition to the prelude in Newton's formula for $n \rightarrow \infty$ in a completely formulaic manner, without worrying about justifying the passage to the limit.

On this occasion, the prominent German scientist and historian of mathematics F. Klein wrote: “In essence, Taylor here operates with infinitesimals (differentials) more, so to speak, frivolously than the followers of Leibniz ever did; It is interesting to note that he still... before Newton’s eyes, so deviated from the method of limits that the latter used” *).

As a result, many mathematicians from different countries were engaged in substantiating the Taylor method: Lagrange, Cauchy, Schlömlch, Roche, Peano and others. Thanks to their efforts, the method of representing a function by Taylor series and the method of approximate representation of a function by polynomials were fully justified.

Currently, the concept of a Taylor series is one of the main ones in mathematical calculations. Taylor series or their finite sums are used wherever there is a need for an exact or approximate representation of floating changing functions.

Exercise
1. Enjoy equality
$$\text{arctg} x = \int_0^x \frac{dt}{1+t^2} (-\infty < x < \infty),$$

prove that for $x \geqslant 0$ and $n = 0,1, \dots$ the following inequalities are valid:
$$x - \frac{x^3}{3} + \dots - \frac{x^{4n+3}}{4n+3} \leqslant \text{arctg} x \leqslant x - \frac{x^3}{3} + \dots + \frac{x^{4n+1}}{4n+1}.$$

If $x < 0$, then in these inequalities the sign “≤” should be replaced with “≥”.

2. Prove that for $-1 < x \leqslant 1$ the equality
$$\text{arctg} x = x - \frac{x^3}{3} + \frac{x^5}{5} - \frac{x^7}{7} + \dots$$

3. Prove equality $\frac{\pi}{4} = 1 - \frac{1}{3} + \frac{1}{5} - \frac{1}{7} + \dots$

4. Prove equality $\ln 2 = 1 - \frac{1}{2} + \frac{1}{3} - \frac{1}{4} + \dots$

5. Prove equality
$$e^{-1} = \frac{1}{2!} - \frac{1}{3!} + \frac{1}{4!} - \dots$$

6. Prove equality
$$(1+x)^{\alpha} = 1 + \alpha x + \frac{\alpha(\alpha-1)}{2!} x^2 + \dots + \frac{\alpha(\alpha-1)}{n!} x^n + \dots,$$
where $-1 < x \leqslant 1, -\infty < \alpha < +\infty$.
