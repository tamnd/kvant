---
id: 1977-1-mochalov-golovolomki-e17f4832
issue: kvant_1977_1
year: 1977
number: "1"
title: '[Puzzle]'
authors:
  - Мочалов Л. П.
rubric: smes
page_first: 44
page_last: 49
page_labels: 42, 44, 45, 46, 47
tag: G22A
lang: en
source: kvant_digital
extraction: vision
content_sha256: 732dd4337aa76002b6995b3303f27359e5d8a96d20ef3ff44f9749b766ddd27f
prompt_sha256: draft-1
translated_from: content/ru/1977/01/articles/16_mochalov-golovolomki-e17f4832.md
source_content_sha256: dcc9239c3970f0997b5572c47f4cf1c0b683477c1dd1cdcd6ecdffe6039e7bd6
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 42⟧

Here is the river. Having thrown their fishing rods into the water, the guys began to carefully monitor the floats.
- Look, you're biting.
- It's true. So... so... Yes!
Look how beautiful this perch is.
“Don’t talk so loudly, you’ll scare away all the fish.” When did you first learn to whisper? And in class we get comments all the time: conversations, conversations... Wow, I was hooked. Perch too!
In the morning the fish had a good bite, and then, when the sun got hot and the glue weakened, the guys began to count their catch.
- Look, I caught the most fish.
- Yes, your fish are all small: one ershin and a roach.
“It’s okay that his fish are small: the erwe makes delicious fish soup.”
Having finished with the calculations and the artificial, the guys went home. Everyone was in a good mood, but Petya was especially pleased - he, a beginner in fishing, caught more fish than the declared fisherman Vasya.
* * *
Have you read this story? Then try to answer two questions.
1. What is the name of Vasya's cheater of physics?
2. What is the smallest (positable!) volume in a given problem that Dirac solved?

Squares
squared

A 3x3 square contains numbers from 1 to 9. Rearrange these numbers so that the three educational three-digit numbers are perfect squares.

Star

Each letter is a number. Which one exactly?

Rebuses

Put the numbers together asterisks so that you get correctly completed multiplication examples.

L. Mochalov

⟦folio 44⟧

A very obvious statement: if all periodic functions have some property, but a given function does not have this property, then this function is not periodic.

Of course, in order for this escape route to be effective, one must have a set of general properties of periodic functions. Let us indicate several such properties.

Six properties of periodic functions

I. If the point $x_0$ belongs to the domain of definition of a periodic function $f(x)$ with period $T$, then all points $x_0 + nT$, $n \in \mathbb{Z}$ also belong to its domain of definition.

In particular, the domain of definition of the periodic function contains as much as possible positive and negative numbers in absolute value.

This property is a very consequence of the definition of a periodic function. From here, for example, it follows that a function defined only on the positive semi-axis $[0, \infty[$ cannot be periodic. Therefore, for example, the logarithmic function $y = \ln x$ is not periodic.

II. A periodic function takes on its value in an infinite number of argument values, among which there are positive and negative numbers that are much larger in absolute value.

In particular, a periodic function cannot be age-related or killing in all areas of definition.

This property follows immediately from the equality

$$f(x + nT) = f(x), \quad n \in \mathbb{Z},$$

valid for a periodic function $f(x)$ with period $T > 0$. From here, for example, it follows that a function increasing along the entire number line cannot be periodic.

When talking about the properties of the exponential function $y = ax^x$, applicants, as a rule, are not able to prove that it is not perio-

ditic. Meanwhile, this function returns (at $a > 1$) or kills (at $0 < a < 1$) on $R$ (which is proven in the textbook), and then is non-periodic.

III. If $f(x)$ is a periodic function defined on the entire number line, then the equation

$$f(x + T) = f(x),$$

If $T$ is considered as an unknown, and $x$ as a parameter, we have at least one positive solution $T = T_0$, which satisfies immediately for all values ​​of the parameter $x \in R$.

This property is actually a reformulation of the definition: after all, if the function $f(x)$ is periodic, then there is a number $T_0 > 0$ such that for any $x \in R$

$$f(x + T_0) = f(x),$$

and this means that the number $T_0$ is the root of equation (2) for any value of the parameter $x$.

Associated with the last property is the following standard way of proving the non-periodicity of functions $f(x)$: if we can also indicate two values ​​of the argument $x = a$ and $x = b$, then the equation

$$f(a + T) = f(a)$$

And

$$f(b + T) = f(b)$$

does not have a general positive solution $T = T_0$, then the function $f(x)$ is not periodic.

IV. If for a periodic function $f(x)$ with period $T$ on some interval $[\alpha, \alpha + T]$ the inequality

$$|f(x)| \leq M,$$

then this inequality holds for any value of the argument.

In particular, for a periodic function $f(x)$ defined on the entire number line, there is a number $M > 0$ such that inequality (3) holds for all $x \in R$.

Property IV follows from the following reasoning. Let the function $f$ be periodic with period $T$ and let inequality (3) be true for $x \in [\alpha, \alpha + T]$. Then, by virtue of equality (1), this inequality is valid on any segment

⟦folio 45⟧

[α+nT, α+(n+1)T], n ∈ Z. However, any value of the argument is taken to one of such segments.

V. If a periodic function is differentiable, then its product is a periodic function with the same period.

This property proves this. First of all, from the definitions of an arbitrary and periodic function it follows that if a periodic function f(x) with period T has an arbitrary f'(x) at some point x, then it also has an arbitrary one at the point x + T. In other words, if x ∈ D(f'), then x + T ∈ D(f'). It remains to make sure that

$$f'(x + T) = f'(x)$$

for x ∈ D(f'). Let us denote the function f(x + T) by g(x) and consider it as a complex function with an “internal” function x + T and an “external” function f(x). Then, according to the formula for an arbitrary complex function, we will have

$$g'(x) = f'(x + T) \cdot (x + T)' = f'(x + T).$$

But due to periodicity g(x) = f(x), so

$$g'(x) = f'(x).$$

From equalities (5) and (6) equality (4) follows. Thus, f'(x) is a periodic function with period T.

VI. If f(x) is a periodic function defined on the entire number line and omitted from a constant, then there is no limit of the function f\left(\frac{1}{x}\right) as x → 0.

This property can be obtained from several graphical considerations. Let x tend to zero while remaining positive; then the expression 1/x increases without limit. Since the periodic function f “oscillates” as the argument increases, the function g(x) = f\left(\frac{1}{x}\right) “oscillates” in the vicinity of the point x = 0 and therefore has no limit as x → 0.

We will carry out a rigorous proof of the formulation of our property by contradiction. Let's assume that

$$\lim_{x \to 0} g(x) = A.$$

First, let us make sure that the function g(x) at at least one point x > 0 takes a value different from A. Indeed, if g(x) = A for any x > 0, then f(x) = g\left(\frac{1}{x}\right) = A

for all x > 0. But then from the periodicity of the function f(x) it follows that f(x) is constant on all the number line, and this contradicts the conditions.

Therefore, there is a point x₀ > 0 such that

$$g(x₀) = \alpha \neq A.$$

Let's take ε = \frac{1}{2} |A - \alpha| > 0. By the definition of a limit, equality (7) implies the existence of a number δ > 0 such that for any x ≠ 0 satisfying the inequality |x| < δ, (8)

the inequality |g(x) - A| < ε. (9)

However, for a sufficiently large n ∈ Z the number

$$x^* = \frac{x_0}{1 + nTx_0}$$

* satisfies inequality (8), but does not satisfy inequality (9) for x = x*:

$$g(x^*) = g\left(\frac{x_0}{1 + nTx_0}\right) = f\left(\frac{1 + nTx_0}{x_0}\right) = f\left(\frac{1}{x_0}\right) = g(x_0) = \alpha,$$

and therefore

$$|g(x^*) - A| = |\alpha - A| > \frac{1}{2} |\alpha - A| = \varepsilon.$$

We have come to a contradiction with equality (7).

Examples

Let us now show with several examples how the above properties of periodic functions can be used to prove the non-periodicity of a concrete function.

Example 1. Prove non-periodic functions

$$f_1(x) = \cos \ln |x|; \quad f_2(x) = \sqrt{x(x - 1)}; \quad f_3(x) = \arcsin x.$$

If the function f₁(x) were periodic with period T > 0, then, since T ∈ D(f₁), by property

$$\frac{x_0}{1 + nTx_0} < \delta.$$

⟦folio 46⟧

I would fulfill the conditions
$$0 = T - T \in D(f_1),$$
which is obviously not true.

Let us assume that the function $f_2(x)$ is periodic with period $T$. Take an integer $n$ such that
$$x^* = \frac{1}{2} + nT > 1.$$
Then $x^* \in D(f_2)$, and by property I
$$x^* - nT = \frac{1}{2} \in D(f_2),$$
which is not true.

The function $f_3(x)$ is defined on the interval $[-1,1]$ and, therefore, is not periodic due to property I.

Example 2. Prove non-periodicity of functions
$$f_1(x) = \frac{3x^2 - x + 2}{x^2 + x + 1}, \quad f_2(x) = \cos x + \cos(x\sqrt{2}) + \cos(x\sqrt{3}),$$
$$f_3(x) = 2x - \cos x.$$
Equation
$$\frac{3x^2 - x + 2}{x^2 + x + 1} = a$$
(where $a \in \mathbb{R}$ can have, as is easy to see, no more than two roots. Therefore, the function $f_1(x)$ takes each value at no more than two points and therefore, by property II, is not periodic.

The function $f_2(x)$ at $x = 0$ takes the value 3. Solve the equation
$$\cos x + \cos(x\sqrt{2}) + \cos(x\sqrt{3}) = 3.$$
(10)

Since $|\cos t| \leq 1$, then equation (11) is equivalent to the system
$$\begin{cases} \cos x = 1, \\ \cos(x\sqrt{2}) = 1, \\ \cos(x\sqrt{3}) = 1. \end{cases}$$

But the first equation of the system is satisfied at $x = 2k\pi$, and the second - at $x = \frac{2n\pi}{\sqrt{2}}(k, n \in \mathbb{Z})$, as it is easy to see that both these series of values ​​$x$ have only a single common point $x = 0$, which obviously satisfies the third equation of the system. Therefore, equation (10) has only one root. In other words, the function $f_2(x)$ takes the value 3 only once and, by property II, is not periodic.

Let's calculate the derivative function $f_3(x)$:
$$f_3'(x) = 2 + \sin x.$$
We see that $f_3'(x) > 0$ for any $x \in \mathbb{R}$, and, therefore, the function $f_3(x)$ is increasing on the entire number line; by property II it is not periodic.

Example 3. Find out whether the function is periodic
$$f(x) = \{x\} + \sin x.$$
To solve this problem, we use the path associated with property III. Let us assume that $f(x)$ is a periodic function with period $T > 0$. Then for any value of $x$ the equality
$$\{x + T\} + \sin(x + T) = \{x\} + \sin x.$$
In particular, for $x = 0$ there is no $\{T\} + \sin T = 0,$ (11) and for $x = -T$ we obtain
$$0 = \{-T\} - \sin T.$$ (12)
Adding equalities (11) and (12), we arrive at the equality
$$\{T\} + \{-T\} = 0.$$
Recall that the fractional part $\{x\}$ of any number $x$ is non-negative. Therefore, the last equality is possible only if $\{T\} = \{-T\} = 0$, that is, if $T$ is an integer. Further, if $\{T\} = 0$, then from equality (11) it follows that $\sin T = 0$, that is, that $T = k\pi$, $k \in \mathbb{Z}$. Meanwhile, the number $k\pi$ for any integer $k \neq 0$ is not an integer, since $\pi$ is irrational, and therefore equations (11) and (12) have only one common root $T = 0$. Thus, the function $f(x)$ is not periodic.

Example 4. Prove that the function is non-periodic
$$f(x) = 2x \cos(x^2).$$
Let us assume that the function $f(x)$ is periodic and $T > 0$ is its period. Since $f(x)$ is defined on the entire number line and $|f(x)| \leq 2T$ for $x \in [0, T]$, then according to property IV for any $x \in \mathbb{R}$
$$|f(x)| = |2x \cos(x^2)| \leq 2T.$$
However, this inequality does not hold.

⟦folio 47⟧

is found at $x = \sqrt{2n\pi}$ unless the natural number $n$ is chosen so that $\sqrt{2n\pi} > T$.

Example 5. Prove non-periodicity of functions
$$f_1(x) = \sin(x^2), \quad f_2(x) = 2\sin x + \sin(x\sqrt{2}).$$

Let's calculate the product of these functions:
$$f_1'(x) = 2x\cos(x^2), \quad f_2'(x) = 2\cos x + \sqrt{2}\cos(x\sqrt{2}).$$

The function $f_1'(x)$, as shown in Example 4, is not periodic, so, by property V, the function $f_1(x)$ is not periodic either. The function $f_2'(x)$ is also not periodic (the proof of this fact was essentially carried out in Example 2) and, therefore, based on property V, the function $f_2(x)$ is not periodic.

Example 6. Prove non-periodicity of functions
$$f(x) = e^{\sqrt{\arctg|\sin(x^2)|}}.$$

This function looks rather strange, and it is not at all clear which of the properties can be played here. However, the issue can be easily resolved if the agreement “simplify” this function; in this case, of course, we will use not only childhood transformations, but the fact that if the function $f(x)$ is periodic, the function $g(f(x))$ is also periodic.

So, let the function $f(x)$ be periodic. then periodically there should be the following function:
$$f_1(x) = \ln[f(x)] = \sqrt{\arctg|\sin(x^2)|}, \quad f_2(x) = [f_1(x)]^2 = \arctg|\sin(x^2)|, \quad f_3(x) = \mathrm{tg}[f_2(x)] = |\sin(x^2)|, \quad f_4(x) = [f_3(x)]^2 = \sin^2(x^2).$$

However, the last of these functions is not periodic, but its derivative is
$$f_4'(x) = 2x\sin(2x^2)$$
is non-periodic (this is proven in the same way as in Example 4). The resulting contradiction shows that the assumption about the periodicity of the function $f(x)$ is incorrect.

Example 7. Prove that any polynomial
$$f(x) = a_0x^n + a_1x^{n-1} + \dots + a_{n-1}x + a_n$$
($a_0 \neq 0$) is not a periodic function.

Let us assume that the function $f(x)$ is periodic. Then, by property V, its product $f'(x)$ is also a periodic function. But it follows from this that $f''(x) = |f'(x)|'$ is also a periodic function, etc. In particular, the periodic function will be the $(n-1)$th derivative of the polynomial $f(x)$:
$$f^{(n-1)}(x) = n! a_0x + (n-1)! a_1.$$
However, this function returns or kills on all direct targets (it is linear!) and cannot be periodic.

Example 8. Prove that the function $f(x) = \sin(\ln(x^2+1))$ is non-periodic.
Let's calculate the derivative of this function:
$$f'(x) = \frac{2x}{x^2+1} \cos \ln(x^2+1)$$

and consider the function
$$g(x) = f'(\frac{1}{x}) = \frac{2x}{x^2+1} \cos \ln \frac{x^2+1}{x^2}.$$

It is easy to see that $|g(x)| \leq \left| \frac{2x}{x^2+1} \right| \leq 2|x|$ is missing, which is $\lim_{x \to 0} g(x) = 0$. Since the function $f'(x)$ is defined for all purposes of the line and is different from a constant, by property VI it is not periodic. Therefore, by property V, the function $f(x)$ itself is not periodic.

Emphasizing

Determine whether the following function is periodic:
1. $f_1(x) = \{x\} + \cos 2x, \quad f_2(x) = \{x\} + \sin x.$
2. $f_1(x) = \sqrt{1-x^2}, \quad f_2(x) = 2\pi x - 3e^x.$
3. $f_1(x) = \ln(\sqrt{x^2+1} - x), \quad f_2(x) = \ln(x + \sqrt{x^2+1}) + \ln(-x + \sqrt{x^2+1}).$
4. $f_1(x) = 2x^3 - 3x^2 + 1 - 5\sin x, \quad f_2(x) = (x^4 - 2x + 5)c - x.$
5. $f_1(x) = \sqrt{|\cos(x^2)|}, \quad f_2(x) = x\sin x.$
6. $f(x) = \sin \sqrt{x^2+1}.$
7. $f_1(x) = \begin{cases} \frac{\sin x}{x} & \text{при } x \neq 0, \\ x \sin \frac{1}{x} & \text{при } x \neq 0, \\ 0 & \text{при } x = 0. \end{cases}$
8. $f_1(x) = \frac{2x^2 - 3x - 1}{x^4 + 3x^3 - 2x + 10}, \quad f_2(x) = \frac{x^6 - 3x^3 + 4x^2 + x + 2}{x^4 + 2x^3 - 4x + 1}.$
