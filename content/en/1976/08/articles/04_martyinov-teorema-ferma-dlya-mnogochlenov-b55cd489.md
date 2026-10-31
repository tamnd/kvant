---
id: 1976-8-martyinov-teorema-ferma-dlya-mnogochlenov-b55cd489
issue: kvant_1976_8
year: 1976
number: "8"
title: Fermat's theorem for polynomials
authors:
  - Мартынов Б.
rubric: osnovnye-stati
page_first: 14
page_last: 17
page_labels: 12, 14, 15
tag: KU23
lang: en
source: kvant_digital
extraction: vision
content_sha256: 95487dddbe40dd206f008810c9fa286067caf77aa675464ad07338dc160b1eb7
prompt_sha256: draft-1
translated_from: content/ru/1976/08/articles/04_martyinov-teorema-ferma-dlya-mnogochlenov-b55cd489.md
source_content_sha256: c9c2936e1bfe479d641e4a428778da28b852955b45dcccde71d527132b60704c
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 12⟧

You've all heard of Fermat's Last Theorem, of course; it was formulated by him for natural numbers. This article proves Fermat's theorem for polynomials. This article is difficult. Some facts used in it are beyond the scope of the school curriculum. Interested readers will find everything they need in the book “What is Mathematics” by P. Kurat and G. Robbins or in the second volume of the “Encyclopedia of Elementary Mathematics”.

Statement of the problem

The assumption made by Fermat is that the equation $x^n + y^n = z^n$ for $n > 2$ has no solution in natural numbers. A proof of this assumption for the general case has not yet been found.

However, it turns out that if we replace the natural numbers $x$, $y$ and $z$ with polynomials in one variable $t$: $x(t), y(t), z(t)$ - and write the equation

$$[x(t)]^n + [y(t)]^n = [z(t)]^n,$$

(a similar theorem has already been proven).

Let us clarify the formulation of the problem. First of all, we note that the polynomials $x(t), y(t)$ and $z(t)$ satisfy equation (1) if and only if the polynomials $p(t) \cdot x(t), p(t) \cdot y(t)$ and $p(t) \cdot z(t)$ satisfy it (here $p(t)$ is an arbitrary nonzero polynomial). Therefore, it is enough to prove that there is no triple of coprime polynomials. Polynomials are called coprime if they do not have a common factor other than a constant (a constant is a polynomial of degree zero). In addition, we must, of course, exclude the trivial solution: a triple of polynomials of degree zero, since for any $a$ and $b$ the triple

$$x(t) = a, y(t) = b, z(t) = \sqrt[n]{a^n + b^n},$$

obviously is a solution to Fermat's equation.

By the way, at $n = 1$ equation (1) has a solution in the direction $x(t) = t, y(t) = t + 1, z(t) = 2t + 1$.

It also has a solution for $n = 2$. Easy to check directions; what a three

$$x(t) = t^2 - 1, y(t) = 2t, z(t) = t^2 + 1$$

is a solution to the equation

$$[x(t)]^2 + [y(t)]^2 = [z(t)]^2.$$

The purpose of the article is to prove an analogue of Fermat’s Last Theorem for polynomials:

For $n > 2$ there are no three coprime polynomials $x(t),$

⟦folio 14⟧

Let us divide our proof into several stages.

1. From condition $1^\circ - 3^\circ$ it follows that every two of the polynomials $x, y, z$ can be woken up. Indeed, if, say, $x$ and $y$ have a common divisor $d$, then $z^n$ is divisible by $d^n$, and then $z$ is divisible by $d$, that is, $d$ is the common polynomial of the polynomials $x, y$ and $z$. This contradicts condition $1^\circ$.

2. Let $m$ be the highest degree of the polynomials $x, y, z$ (by condition $3^m > 0$). We can assume that degree $m$ has a polynomial $z$. Indeed, if desired, the original equation can be made symmetric with respect to $x, y, z$: it is necessary to replace $z$ with $\varepsilon z$, where $\varepsilon$ is a complex number, the $n$th power of which is equal to $-1: \varepsilon^n = -1$. We get

$$x^n + y^n + z^n = 0.$$

3. Let $\varepsilon_1, \varepsilon_2, \dots, \varepsilon_n$ be all distinct roots of the $n$th degree of the number $-1$. We obtain by the fact that every complex number different from zero has exactly $n$ different roots of the $n$th degree (see point 1*). Then the polynomial $x^n + y^n$ is decomposed into polynomials

$$x^n + y^n = (x - \varepsilon_1 y) (x - \varepsilon_2 y) \cdot \dots \cdot (x - \varepsilon_n y).$$

To prove it, you can construct it like this: take the polynomial $u^n + 1$, the roots of which are the numbers $\varepsilon_1, \dots, \varepsilon_n$, decompose it into polynomials: $u^n + 1 = (u - \varepsilon_1) \cdot (u - \varepsilon_2) \cdot \dots \cdot (u - \varepsilon_n)$ (item 2*), and then substitute $u$ together with the fraction $\frac{x}{y}$ and get rid of the denominator.

4. Polynomials $x - \varepsilon_i y$ are mutually awakened in pairs. Indeed, if the non-constant polynomial $d$ were a common divisor of the polynomials $x - \varepsilon_i y$ and $x - \varepsilon_j y$ ($i \neq k$), then the difference of these polynomials, equal to $(\varepsilon_h - \varepsilon_i) y$, would also be divisible by $d$, and therefore the polynomial $y$ would be divisible by $d$ (introduced $\varepsilon_h - \varepsilon_i$ is a constant non-zero). Then the polynomial $x = (x - \varepsilon_i y) + \varepsilon_j y$ would be divisible by the polynomial $d$, which contradicts the mutual primeness of $x$ and $y$ (item 1).

5. If the product is mutually extended in pairs, then each two of the polynomials is a common divisor of $d$, then $z^n$ is divisible by $d^n$, and then $z$ is divisible by $d$, that is, $d$ is the common polynomial of the polynomials $x, y$ and $z$. This contradicts condition $1^\circ$.

We provide the proof of point 5 in the addition to the statute.

6. Since $x^n + y^n = (x - \varepsilon_i y) \times (x - \varepsilon_2 y) \dots (x - \varepsilon_n y) = z^n$ and polynomials $x - \varepsilon_i y$ are pairwise mutually prosperous, each polynomial $x - \varepsilon_i y$ is a $n$-th degree of a polynomial. Let $x - \varepsilon_i y = u_i^n$, where $u_i$ is a polynomial. Let us denote the degree of the polynomial $u_i$ by $m_i$.

Let us choose among the polynomials $u_i$ the one that has the most polynomial $u_1$. We will assume that the polynomial $u_1$ has the most polynomial.

7. $m_1 < m$.

Indeed, it is obvious that $m_1 \leq m$ (recall that $m$ is a power of $z$). If equality $m_1 = m$ held, then all other polynomials $x - \varepsilon_i y$ for $i > 1$ were constants. Let's take $x - \varepsilon_2 y$ and $x - \varepsilon_3 y$ (this is possible - after all, $n \geq 3$). If $x - \varepsilon_2 y = A$, $x - \varepsilon_3 y = B$, then

$$(B - A) x - (B \varepsilon_2 - A \varepsilon_3) y = 0,$$

i.e. $x = Cy$ (input $A \neq B$ is proof), and this contradicts the mutual primeness of $x$ and $y$.

Note also that $m_1 > 0$, i.e. $u_1$, is not a constant.

We want to move from polynomials $x, y, z$ to dark polynomials without a common polynomial, satisfying Fermat and having a maximum degree less than $m$. Let us show that the polynomials $u_1, u_2$ and $u_3$ (see Section 6) multiplied by some constants can be taken as such polynomials.

⟦folio 15⟧

8. We have:

$$\begin{cases} x - \varepsilon_1 y = u_1^n, \\ x - \varepsilon_2 y = u_2^n, \\ x - \varepsilon_3 y = u_3^n. \end{cases}$$

Let us select three numbers $c_1, c_2, c_3$ (not all equal to zero) so that when adding these equalities with the coefficients $c_1, c_2, c_3$ the lying part becomes zero. It is clear that for this it is necessary that the system be executed

$$\begin{cases} c_1 + c_2 + c_3 = 0, \\ c_1 \varepsilon_1 + c_2 \varepsilon_2 + c_3 \varepsilon_3 = 0. \end{cases}$$

It is easy to find at least one non-zero solution of it - for example, put $c_3 = 1$ and solve the resulting system of two equations with two unknowns. Do this calculation yourself.

Finding $c_1, c_2$ and $c_3$ we get

$$c_1 u_1^n + c_2 u_2^n + c_3 u_3^n = 0.$$

《Driven》 the coefficients to the $n$th powers, we get:

$$\left[ \sqrt[n]{c_1} u_1 \right]^n + \left[ \sqrt[n]{c_2} u_2 \right]^n = \left[ \sqrt[n]{c_3} u_3 \right]^n.$$

It is easy to verify that the new three polynomials satisfy the same conditions as $x, y, z$. At the same time, their degree decreased most (while remaining a positive number).

Our method of proof, invented by Fermat, is called the “infinite descent” method. Unfortunately, this method does not work to prove the unsolvability of the Fermat equation in natural numbers, since the theorem on the uniqueness of decomposition into simple polynomials does not carry over to numbers of the form $x - \varepsilon_i y$, where $x$ and $y$ are integers (see paragraph 3*, p. 13). The study of this interesting question is carried out by “higher arithmetic” - the theory of algebraic numbers - a currently actively developing area of ​​mathematics.

Additional

A. Let us prove the statement formulated in paragraph 3* of the article (see p. 13), that is, we prove that any polynomial can be uniquely decomposed into a product of irreducible polynomials (up to the order of the polynomials and up to the polynomials, which is a constant). (An irreducible polynomial is the analogue of a prime number in a polynomial of natural numbers: a polynomial $q$ is called irreducible if it cannot be factored into the product of polynomials of non-zero degree other than $q$.)

First we show that every polynomial can be expanded into a product of irreducibles. Indeed, if $Q$ is irreducible, then $Q = Q_1 \cdot G_2$, where $G_1$ and $G_2$ are some polynomials. If $G_1$ and $G_2$ are irreducible, then the necessary decomposition is obtained; if any of $G_i$ ($i=1, 2$) is reducible, then again $G_i = S_1^{(i)} \cdot S_2^{(i)}$, etc. It is clear that this process will end after a finite number of steps, since the degree of the polynomial $Q$ is finite. Thus we obtain the decomposition of a polynomial into a product of irreducibles.

And now we want to prove that if for irreducible polynomials we satisfy the equality $p_1 \cdot p_2 \dots p_l = q_1 \cdot q_2 \dots q_s$, then $l = s$, and for each i there is a $k$ such that $q_i = c \cdot p_k$. To do this, we need the following statement: if the product $u \cdot v$ of two polynomials $u$ and $v$ is divisible by an irreducible polynomial $q$, then any $u, v$ is divisible by $q$. Let us divide the polynomials $u$ and $v$ by the polynomial $q$ with remainder (Euclidean creeping algorithm). We get the remainder of the polynomials $u$ and $v$, the degrees of each of which are less than the degree of the polynomial $q$, and the product $u \cdot v$ is divisible by $q$. We need to prove that any $u = 0$ (then $u$ is divisible by $q$), any $v = 0$ (then $v$ is divisible by $q$). Let us prove this statement by the method of mathematical induction (by the degree of the polynomial $q$).

Induction base. The minimal degree of a non-constant irreducible polynomial is 1. Let $q$ be a linear polynomial. Then, if neither $u \neq 0$ nor $v \neq 0$, then $u = \text{const}$ and $v = \text{const}$. But then $u \cdot v$ is also a constant, and therefore $u \cdot v$ cannot be divided by $q$. Therefore, the statement is true for linear irreducible polynomials.

Шаг иndukции. Let us assume that the statement is true for all irreducible polynomials of degree less than the degree of the polynomial $q$. Let us prove it for the polynomial $q$. Let's assume that $u \cdot v \neq 0$. Since $u \cdot v$ is divisible by $q$, we have: $u \cdot v = q \cdot q$, $q \neq 0$, and the degrees of the polynomial $q$ are strictly less than the degree of the polynomial $q$ (since the degree of the product $u \cdot v$ is less than the degree of the polynomial $q$). Let's expand $q$
