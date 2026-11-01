---
id: 1985-6-priven-ne-beda-chto-net-funktsiy-d0285ef9
issue: kvant_1985_6
year: 1985
number: "6"
title: It doesn't matter that there are no functions
authors:
  - Привень А. И.
rubric: osnovnye-stati
page_first: 22
page_last: 23
page_labels: 20-21
tag: 98KK
lang: en
source: kvant_digital
extraction: vision
content_sha256: c9903a3f72670a04fbbf6508c850dd13e6a03702413721564a9e008b1a5cef6a
prompt_sha256: draft-1
translated_from: content/ru/1985/06/articles/05_priven-ne-beda-chto-net-funktsiy-d0285ef9.md
source_content_sha256: afbc0fb7973d3f52ed2058a81911e87181b9e64736e91051958fa0fe67bc76b8
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 20⟧

It doesn't matter that there are no functions

A. I. PRIVEN

— Dad, you know, Masha Sidorova’s parents bought a brand new “Electronic BZ-36” with functions. And other guys have it...
— What, your “Electronic BZ-30” doesn’t work well?
“It works, but it has no functions: it only does arithmetic operations and depicts roots.” And in the ninth grade we have all snus and cosines, logarithms, exponential functions. I can’t carry Bradis tables with me everywhere!
— It doesn’t matter that there are no functions. You want to be a mathematician with us, so you have to report. Have you been told about the Taylor series on semolina? Well then listen...

How to calculate a logarithm

First, a little theory. Of course you know that

$$\lim_{x \to 0} (1+x)^{1/x} = e.$$

This equality is satisfied with sufficient accuracy if $x$ is close to 0. Then we obtain $(1+x)^{1/x} \approx e$, or $1+x \approx e^x$, whence

$$\ln(1+x) \approx x,$$

(1) that is, by subtracting one from the number, we obtain its natural logarithm. What about large numbers?
Quite simple. After all

$$\ln a = \ln (a^{N/N}) = N \ln (a^{1/N}).$$

If $N$ is large enough (we'll talk about specific values ​​later), then $a^{1/N} \approx 1$ and $\ln (a^{1/N}) \approx a^{1/N} - 1$.

On a machine, $a^{1/N}$ is easy to calculate if $N=2^n$ - you only need to press the $\sqrt{}$ key $n$ times. And then to find the original logarithm you need to subtract one and multiply by the corresponding two:

$$\ln a = \ln a^{N/N} = N \ln a^{1/N} \approx (a^{1/N} - 1) \cdot N.$$

All that remains is to find the optimal value $N$. From equality (1) it follows

$$\ln (1+x)^{1/2} = \frac{1}{2} \ln (1+x) \approx \frac{1}{2} x \approx \ln \left(1 + \frac{1}{2} x\right),$$

that is

$$\left(1+x\right)^{1/2} = \sqrt{1+x} \approx 1 + \frac{1}{2} x.$$

To evaluate the accuracy of this equality, use the Taylor formula*. The first three terms are enough for us:

$$f(a+x) = f(a) + xf'(a) + \frac{x^2}{2!} f''(a) + \dots$$

In our case $a=1$; $f(a+x) = \sqrt{1+x}$;

$$f(a) = \sqrt{a} = 1; f'(a) = \frac{1}{2\sqrt{a}} = \frac{1}{2};$$

$$f''(a) = -\frac{1}{4a^{3/2}} = -\frac{1}{4},$$

that is, $\sqrt{1+x} \approx 1 + \frac{x}{2} - \frac{x^2}{8}$;

the remaining terms at $x \to 0$ can be discarded.

Thus, the error of formula (3) is approximately equal to $x^2/8$. Let us set the error value $\Delta = 5 \cdot 10^{-9}$. These are the most values ​​that do not affect the readings of an 8-digit calculator.

Then it’s simple: $\Delta = \frac{x^2}{8} = 5 \cdot 10^{-9}$, $x=2 \cdot 10^{-4}$. This value $x$ should provide a minimum of error. Thus, the value of $ln 2$, calculated using the formula $\ln 2 = 2^{12} (2^{1/2^12} - 1) = 4096 \times 0.0001691$, is equal to 0.693207, together with the table 0.693147.

However, there is one purely “machine” effect here: root extraction (like other calculations) is carried out with a deficiency in the last sign, and this error increases each time. Eventually it overlaps the quantities $\frac{x^2}{8}$, and the formula for $\Delta$ becomes inapplicable. This effect is replaced by $n > 10$, where $n = \log_2 N$ is the number of root extractions. As a result, the same $\ln 2$, calculated using the same formula on the BZ-30 microcalculator, is equal to 0.69263... By-

*) For the Taylor formula, see the article by V. R. Pochuev in the previous issue of Kwan.

⟦folio 21⟧

Therefore, in the case of $n > 10$ it is advisable to accept $x = (3,5 \div 7) \cdot 10^{-4}$.

The same ln 2, calculated on the same machine at $n = 11$, is equal to 0.69304 with a relative error of 0.014%.

So, we have found an algorithm for calculating ln $a$:

$$\ln a = \frac{\ln a}{\ln 10} = \frac{\ln a}{2,303}.$$

For $2 < a < 10$ quite accurate results are given by the expression

$$\lg a \approx (a^{2/10} - 1) \cdot 445,$$

where $445 \approx \frac{2^{10}}{\ln 10}$.

How to calculate an exponential function

To calculate the function $e^x$, we transform the expression obtained for ln $a$. We have ln $a \approx N (a^{1/N} - 1)$, with large $N$, which means

$$a \approx \left( \frac{\ln a}{N} + 1 \right)^N.$$

Making the replacement $x = \ln a$, we get $a = e^x$ and therefore

$$e^x \approx \left( \frac{x}{N} + 1 \right)^N = \left( \frac{x}{N} + 1 \right)^{2n}.$$

To quickly use this correspondence on a simple calculator, it is advisable to turn it into an integer algorithm, that is, an algorithm in which there is no need to write down intermediate results. To do this, exponentiation $N$ (or $n$ times squared) must be performed by repeating the sequence of commands $\times =$ for model B3-30 or

$$\dots \times 1 \times = \dots ,$$

for model type B3-14. In this case, the result remains in the “temporary memory” of the calculator all the time, and therefore does not need to be re-entered into the machine after each iteration. Thus, the algorithm for finding $e^x$ looks like this (below $n$ is a natural number, moreover $N = 2^n$):

$$x : 2^n + 1 \times =$$

The calculation of the function $10^{xn}$ differs only in that after typing $2^n$ the result is multiplied by ln $10 \approx 2,303$.

What remains is the function $x^y$. Let's continue with it:

$$\ln (x^y) = y \ln x = Ny \ln (x^{1/N}) \approx Ny (x^{1/N} - 1).$$

Hence, according to formula (4)

$$x^y = e^{\ln (x^y)} \approx e^{Ny (x^{1/N} - 1)} \approx \left[ \frac{Ny (x^{1/N} - 1)}{N} + 1 \right]^N = [y (x^{1/N} - 1) + 1]^N.$$

Formula (5) is represented by the program:

How to calculate trigonometric functions

Here Taylor's formula gives two convenient expressions for sine and cosius

$$\sin x \approx x - \frac{x^3}{6} = \frac{(x^2 - 6)x}{6};$$

$$\cos x \approx 1 - \frac{x^2}{2} + \frac{x^4}{24} = 1 + \frac{(x^2 - 12)x^2}{24}.$$

The first holds sufficiently for $x \leq \frac{\pi}{4}$; the same can be said about the second. The value $\frac{x^4}{24}$ begins to have a noticeable effect at $x \geq \frac{\pi}{6}$, at $x < \frac{\pi}{6}$ you can simplify the formula for cos $x$ by discarding the third term:

$$\cos x \approx 1 - \frac{x^2}{2}.$$

The $x \leq \frac{\pi}{4}$ constraint is not dangerous, since trigonometric functions can always be reduced to an argument less than $\frac{\pi}{4}$.

* * *

As you can see, just a little mathematics - and the simplest microcalculator becomes ready to calculate practically all “school” functions.
