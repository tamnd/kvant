---
id: 1980-11-avramov-arifmeticheskie-progressii-v-treugolnike-paskalya-5ee09e49
issue: kvant_1980_11
year: 1980
number: "11"
title: Arithmetic progressions in Pascal's triangle
authors:
  - Аврамов А.
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 29
page_last: 30
page_labels: 27-28
tag: SI4T
lang: en
source: kvant_digital
extraction: vision
content_sha256: c67fb4991fd1ca6e0c51f1de05f4ea9dffad41550f7c7142cbe0d4027c66f043
prompt_sha256: draft-1
translated_from: content/ru/1980/11/articles/08_avramov-arifmeticheskie-progressii-v-treugolnike-paskalya-5ee09e49.md
source_content_sha256: faeb8640ef35bb5c08608eea88cb1ef29ecf5262ce1887a3c2e5468906fbda66
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 27⟧

F612. What amount of heat Q must be imparted to m=0.1 kk of neon to cut it at Δt=5°C, if during cutting the neon pressure is directly proportional to its volume?

According to the first thermodynamics
$$Q = \Delta U + A,$$

where ΔU is the change in the internal energy of neon; A is the work done by the gas when cutting it.
Neon is a monatomic gas. That's why
$$\Delta U = \frac{3}{2} v R (\Delta T) = \frac{3}{2} \frac{m}{M} R (\Delta T)$$
(v = $\frac{m}{M}$ is the number of neon, M=20·10⁻³ kg/mol is its molar mass).

The work A of a gas is equal to the product of the average pressure $p_{cp}$ and the change in volume:
$$A = p_{cp} V = p_{cp} (V_2 - V_1),$$

where $V_2$ is the final volume, $V_1$ is the initial volume of gas. Since when cutting gas the pressure is proportional to the volume, the average pressure is equal to the arithmetic mean of the initial $p_1$ and final $p_2$ pressure. That's why
$$A = \frac{1}{2} (p_2 + p_1) (V_2 - V_1).$$

This formula can be transformed as follows:
$$A = \frac{1}{2} (p_2 V_2 - p_1 V_1) + \frac{1}{2} (p_1 V_2 - p_2 V_1).$$

The neon pressure during cutting is directly proportional to its volume, that is, $p_1 = \alpha V_1$, $p_2 = \alpha V_2$, where α is the proportionality coefficient. Therefore $p_1 V_2 - p_2 V_1 = \alpha V_1 V_2 - \alpha V_2 V_1 = 0$.
Thus,
$$A = \frac{1}{2} (p_2 V_2 - p_1 V_1) = \frac{1}{2} \Delta(pV),$$

where Δ(pV) is the change in the product pV. According to the gas state equation pV = $\frac{m}{M} RT$, therefore Δ(pV) = $\frac{m}{M} R (\Delta T)$ and
$$A = \frac{1}{2} \frac{m}{M} R (\Delta T),$$

Substituting the values ​​of ΔU and A into expression (*), we find
$$Q = 2 \frac{m}{M} R (\Delta T) \approx 41,5 \text{ Дж.}$$

I. Slovodetsky

A. Avramov

Arithmetic progressions in Pascal's triangle

The problem that is discussed in this note (M602 - «Kvant», 1980, No. 2) is related to Pascal’s triangle - a number triangle, the nth row of which (n=0,1,2,3,...) consists of n+1 numbers

$$C_n^0, C_n^1, C_n^2, ..., C_n^n$$

($C_n^m$ is the number of combinations from n to m*).

On figure (p. 28) the first eight lines of Pascal’s triangle are given (n=0,1,2,...,7). The eighth line (n=7) consists of numbers
1, 7, 21, 35, 35, 21, 7, 1.

It is replaced by the fact that in it the second, third and fourth (as well as the fifth, sixth and seventh) numbers form an ariffmetic progression.

Are there other lines in Pascal's triangle with similar

*) About Pascal’s triangle, see the manual “Algebra and the beginnings of analysis 9”, paragraphs 7, 8. In addition, in 1979, the Nuka publishing house published the 2nd edition of V. A. Uspensky’s brochure “Pascal’s Triangle” in the series “Popular Lectures on Mathematics”.

⟦folio 28⟧

Property, that is, lines in which three numbers standing next to each other would form an arithmetic progression?

Let us assume that there are natural numbers $n$ and $k$ such that the triple of numbers $C_n^{k-1}, C_n^k, C_n^{k+1}$ is an arithmetic progression. This means that

$$2C_n^k = C_n^{k-1} + C_n^{k+1}$$

($1 \leq k \leq n-1$),

that is

$$\frac{2n!}{k!(n-k)!} = \frac{n!}{(k-1)!(n-k+1)!} + \frac{n!}{(k+1)!(n-k-1)!},$$

from where we get the equation

$$4k^2 - 4nk + n^2 - n - 2 = 0,$$

(1)

which must be solved in natural numbers.

Let's solve it as a quadratic equation for $k$:

$$k_{1,2} = \frac{n \pm \sqrt{n+2}}{2}.$$

Let us put $n+2 = t^2$, where $t$ is some natural number. We get

$$k_1 = \frac{(t+1)(t-2)}{2},$$

$$k_2 = \frac{(t-1)(t+2)}{2},$$

and for $t \geq 3$ both $k_1$ and $k_2$ are natural numbers, $1 < k_1 < n-1$, $1 < k_2 < n-1$.

So, if the natural numbers $n$ and $k$ satisfy equation (1), then they are found by the formulas

$$\begin{cases} n = t^2 - 2, \\ k_{1,2} = \frac{t^2 + t - 2}{2}, \end{cases}$$

where $t$ is a natural number and $t \geq 3$.

In addition, for all natural numbers $t \geq 3$, each pair of numbers $n$ and $k$ obtained by formulas (2) satisfies equation (1) - make sure of this.

These documents show that in Pascal's triangle there are infinitely many lines containing three-term arithmetic progressions of consecutive numbers. Moreover, each line contains two progressions. This is not surprising: after all, Pascal’s triangle is symmetrical. Therefore, both of these progressions consist of the same numbers: the first (obtained at $k=k_1$) increases, and the second (at $k=k_2$) kills.

At $t=3$ we get $n=7$ - we started our observations with this line. For $t=4$ we get $n=14$, $k_1=5$, $k_2=9$. This corresponds to the fifteenth line of Pascal's triangle: 1, 14, 91, 364, 1001, 2002, 3003, 3432, 3003, 2002, 1001, 364, 91, 14, 1; here the highlighted numbers form an arithmetic progression.

What happens if $t < 3$? $t=1$, very indo, is not suitable, but with $t=2$ we get $n=2$, $k_1=0$, $k_2=2$. This corresponds to the third row of the triangle, which contains the numbers 1, 2, 1. If we add zero to the left and right of them and there are no numbers from zero, we again get two arithmetic progressions: 0, 1, 2 and 2, 1, 0.

It is easy to see that in Pascal's triangle there is not a single line in which there would be an arithmetic progression consisting of more than three terms (and ones in a row). In fact, if such a line were found, then it would contain at least two three-term arithmetic progressions consisting of different terms. But above we showed that each line with an arithmetic progression (in which the numbers are in a row) is structured like this: neurally there are two progressions made up of the same numbers.

We invite you to verify for yourself that there is not a single line in Pascal’s triangle that contains an arithmetic progression consisting of more than three terms (and one in a row).
