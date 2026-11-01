---
id: 1979-4-yantarov-kommutiruyuschie-mnogochlenyi-ab390f7c
issue: kvant_1979_4
year: 1979
number: "4"
title: Commuting polynomials
authors:
  - Янтаров И.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 21
page_last: 25
page_labels: 19-23
tag: VM8V
lang: en
source: kvant_digital
extraction: vision
content_sha256: 8f2c72595cbe86283170690aff8b4f347be8d6a50c5c7ab4e31a24cdb78fa873
prompt_sha256: draft-1
translated_from: content/ru/1979/04/articles/10_yantarov-kommutiruyuschie-mnogochlenyi-ab390f7c.md
source_content_sha256: 4dc0ca05ff975b79bdac624912582dac02aeec3af88049bf535e1072875c8a13
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 19⟧

I. Yanmatov

Commuting polynomials

From the editor
Generally, mathematical problems offered to schoolchildren are either very indirectly related to new results, or concern their individual details and do not allow them to see the whole picture. This probably happens because in mathematics everything is interconnected and, as a rule, in order to fully understand even a completely elementary question, one has to draw on messages from non-elementary areas of mathematics.
The problem of commuting polynomials, which is related to this article, is considered an exception: here it is possible to get fairly close to a problem of general mathematical interest, using only elementary means.
This problem became known to us from a letter sent two years ago to «Kvant» by E. Turkevich, who wrote the first results here. This problem, supplemented by certain points, was proposed at the research type XI of the World Olympiad and was placed in Problem «Kvant» (M455).

Problem formulation
Polynomials $P$ and $Q$ in one variable are called commuting *) if $P(Q(x)) = Q(P(x))$. The written equality means that if in both sides of the equality we open all the brackets and add similar terms, then we get the same polynomials. This is equivalent to the fact that for any real number $d$ the numerical equality $P(Q(d)) = Q(P(d))$ holds.

*) From Latin commutativus - changing.

Assignment M455 considers only polynomials with leading coefficient 1; We will call such polynomials unitary. (As we will see below, the question of arbitrary commuting polynomials can be reduced to the question of polynomials with leading coefficient equal to ±1.)

a) For any number $\alpha$, find all polynomials of degree at most three that commute with the polynomial $P(x) = x^2 - \alpha$.

b) Prove that there is at most one polynomial of a given degree that commutes with the given polynomial $P$ of degree two.

b) Find all polynomials of degree 4 and 8 that commute with the given polynomial $P$ of degree two.

d) Prove that if two polynomials $Q$ and $R$ commute with some polynomial $P$ of degree two, they commute with each other.

d) Prove that there is a mass of polynomials $P_1, P_2, \dots, P_h, \dots$ that commute with each other, that the degree of the polynomial $P_h$ is equal to $k$ and $P_2(x) = x^2 - 2$.

Solving problems a)—d)

a) Let $Q(x) = x^3 + ax^2 + bx + c$. Let us write down the equality $P(Q(x)) = Q(P(x))$:
$x^3 + ax^2 + bx + c)^2 - \alpha = (x^2 - \alpha)^3 + a(x^2 - \alpha)^2 + b(x^2 - \alpha) + c$.

Before opening the parentheses, note that on the right there are only four powers $x$, and the trace coefficient at $x^5$ is equal to 2a. So, $a = 0$. But then the trace coefficient of $x^3$ is equal to 2c, so so is $c = 0$. Therefore $Q(x) = x^3 + bx$. Opening the brackets and equating the coefficients, we get the system
$$\begin{cases} 2b = -3\alpha, \\ b^2 = 3\alpha^2 + b, \\ \alpha = \alpha^3 + b\alpha. \end{cases}$$

Let $\alpha = 2\gamma$, then $b = -3\gamma$. From the 2nd equation $9\gamma^2 = 12\gamma^2 - 3\gamma$, that is $\gamma^2 - \gamma = 0$. So, $\gamma = 0$ or $\gamma = 1$. It's easy to check that both of these solutions are suitable.

⟦folio 20⟧

Thus, the 3rd degree polynomial $Q$ commuting with the polynomial $P(x) = x^2 - \alpha$ exists only for $\alpha = 0$ ($P(x) = x^2$, $Q(x) = x^3$) and for $\alpha = 2$ ($P(x) = x^2 - 2$, $Q(x) = x^3 - 3x$).

It is similarly proven that if the degree of $Q$ is equal to 2, then $Q = P$, and if it is equal to 1, then $Q(x) = x$.

This point is very simple. It was given to schoolchildren at the Olympiad so that they could better understand the conditions of the task and get a little used to it. In addition, if you carefully understand the equations that were written out, then an idea arises on how to solve point 6) - one of the key points of the problem.

6) Let $Q(x) = x^k + a_1x^{k-1} + a_2x^{k-2} + \dots + a_{k-1}x + a_k$, $P(x) = x^2 + px + q$. Let us write down the equality $(x^k + a_1x^{k-1} + \dots + a_k)^2 + p(x^k + \dots + a_k) + q - (x^2 + px + q)^k - a_1(x^2 + px + q)^{k-1} - \dots - a_k = 0$.

Equating the coefficients at $x^{2k}$, $x^{2k-1}$, ..., $x$, $x^0$ to zero, we obtain a system of equations for $a_1$, $a_2$, ..., $a_k$, $p$, $q$. Solving this system and even simply writing it down is quite difficult. However, it is easy to notice that the coefficients $b_1$, $b_2$, ..., $b_k$ for powers $x^{2k-1}$, $x^{2k-2}$, ..., $x^k$ have the following form:

$$b_1 = 2a_1 + R_1(p, q) = 0,$$
$$b_2 = 2a_2 + R_2(p, q, a_1) = 0,$$
$$b_k = 2a_k + R_k(p, q, a_1, \dots, a_{k-1}) = 0.$$

Here $R_i$ is some algebraic expression from $p$, $q$, $a_1$, ..., $a_{i-1}$. From the first equation it follows that $a_1$ is expressed through $p$ and $q$; from the second - that $a_2$ is expressed through $p$, $q$ and $a_1$, and therefore is expressed through $p$ and $q$, ... So, we see that all coefficients $a_1$, ..., $a_k$ are expressed through $p$ and $q$, that is, the coefficients of the polynomial $Q$ commuting with $P$, are uniquely expressed in terms of $p$ and $q$, which is what needed to be proven.

It is easy to verify that a similar reasoning can be verified for any polynomial $P$, as long as its degree is greater than 1 (and $Q$ is unitary), that is, the statement in paragraph 6) is true for any polynomial.

Point 6) is key to the task. Points c) and d) easily follow from it.

c) Let us prove that the polynomial $Q(x) = P(P(x))$ commutes with $P$. Indeed, $Q(P(x)) = P(Q(x))$. The polynomial $Q$ has degree four and, by virtue of 6) is the only polynomial of this degree that commutes with $P$. Similarly, it is proved that the only polynomial of degree 8 that commutes with $P$ is the polynomial $R(x) = P(P(x))$.

d) Let $S(x) = Q(R(x))$ and $T(x) = R(Q(x))$. Since $P$ commutes with $Q$ and $R$, then $P(S(x)) = P(Q(R(x))) = Q(P(R(x))) = Q(R(P(x))) = S(P(x));$ means $P$ commutes with the polynomial $S$. Similarly, it is verified that $P$ commutes with the polynomial $T$. Moreover, it is clear that $S$ and $T$ are unitary polynomials of the same degree (if $Q$ and $R$ have degrees $k$ and $l$, then the degrees of polynomials $S$ and $T$ are $kl$). From 6) it follows that $S = T$, that is, $Q(R(x)) = R(Q(x))$, which is what is required.

Same as in point 6), the statement remains true if $P$ is any polynomial of degree greater than 1, and $Q$ and $R$ are unitary.

Chebyshev polynomials.
Solution to point d)

Point d) is much more difficult than the other points. We will present several different approaches to solving it.

First way. Let $x = t + t^{-1}$. then it is easy to check that $x^k$ has the form

$$x^k = (t + t^{-1})^k = (t^k + t^{-k}) + a_1(t^k - 1 + t^{-(k-1)}) + a_2(t^k - 2 + t^{-(k-2)}) + \dots + a_{k-1}(t + t^{-1}) + a_k,$$

where $a_1$, ..., $a_k$ are some fixed numbers. By induction on $k$ it follows that $t^k + t^{-k}$ can be represented as

$$x^k + b_1x^{k-1} + \dots + b_{k-1}x + b_k,$$

where $b_1$, ..., $b_k$ are some fixed numbers. Let us denote the polynomial $x^k + b_1x^{k-1} + \dots + b_k$ by

⟦folio 21⟧

$P_k(x)$. By definition $P_k(t+t^{-1}) = t^k + t^{-k}$, so $P_k(P_l(t+t^{-1})) = P_k(t^l + t^{-l}) = t^{kl} + t^{-kl} = P_{kl}(t + t^{-1})$. Thus, $P_k(P_l(x)) = P_{kl}(x) = P_l(P_k(x))$, that is, any two of the polynomials $P_k$ commute. Since $P_2(x) = x^2 - 2$, we have constructed the required sequence of polynomials.

Second way. Let us present a method for obtaining polynomials $P_k$ using Chebyshev polynomials $T_k$. We will not give a direct definition of these polynomials, but we will give the correspondences that they satisfy (and which define them uniquely):

$$T_k(\cos t) = \cos kt.$$

It can be proven that $T_k$ is a polynomial of degree $k$. It is easy to verify that the Chebyshev polynomials commute:

$$T_k(T_m(x)) = T_{km}(x) = T_m(T_k(x))$$

- it comes down to the fact that $\cos k(mt) = \cos kmt = \cos m(kt)$. But $T_k$ is not a unitary polynomial: its leading coefficient is $2^{k-1}$. This drawback can be easily corrected by “stretching” the argument and value of the polynomial by a factor of two using a change of variable, i.e. by putting $P_k(x) = 2T_k(x/2)$. This procedure does not violate commutativity (check this!). A remarkable sequence of Chebyshev polynomials, appearing in a variety of problems in analysis (especially in the theory of approximation of functions by polynomials), turns out to be a sequence of commuting polynomials. It was in this way that the sequence $P_k$ was constructed by E. Turkev and Part.

Both described methods are based on the same idea. Let there be some function $f$ taking an infinite number of values ​​and such that for every natural number $n$

$$f(nt) = Q_n(f(t))$$

where $Q_n$ is a polynomial. Then the polynomials $Q_m$ and $Q_n$ commute. For example, if $f(t) = e^t$, then we obtain the serial commuting polynomial $F_n(x) = x^n$. If $f(t) = e^t + e^{-t}$, then we get the serial polynomial $P_n$ (this is exactly our first method of constructing the polynomials $P_n$, only $t$ is replaced here by $e^t$). If $f(t) = \cos t$, then we obtain the serial polynomial $T_n$. (For those familiar with complex numbers and the formula $\cos \varphi = (e^{i\varphi} + e^{-i\varphi})/2$, it is easy to find out why the function $e^t + e^{-t}$ and cos $t$ lead to essentially the same sequence of polynomials, up to twice the distance.)

The given solutions to point e) are very beautiful, but they have one drawback: it is completely unclear how they can be accessed. We will give another solution; it will be less short, but it will be clear how it was invented and how to quickly write out the polynomials $P_n$.

Third way. As follows from point b), there can only be one polynomial $P_k$ of degree $k$ that commutes with $P_2(x) = x^2 - 2$. Let us write down the first few such polynomials:

$$P_1(x) = x,$$
$$P_2(x) = x^2 - 2,$$
$$P_3(x) = x^3 - 3x,$$
$$P_4(x) = x^4 - 4x^2 + 2,$$
$$P_5(x) = x^5 - 5x^3 + 5x,$$
$$P_6(x) = x^6 - 6x^4 + 9x^2 - 2$$

(here $P_4(x) = P_2(P_2(x))$, $P_6(x) = P_2(P_3(x))$, $P_5(x)$ is the same as in point a)). After looking at this sequence of polynomials, we can replace that it satisfies the recurrent formula $P_{k+1}(x) = xP_k(x) - P_{k-1}(x)$. It is natural to assume that this formula is true for all $k > 1$.

So, let us define the sequence of polynomials $P_1, P_2, \dots, P_n, \dots$ by induction, assuming that

$$P_1(x) = x,$$
$$P_2(x) = x^2 - 2,$$

and at $k > 1$

$$P_{k+1}(x) = xP_k(x) - P_{k-1}(x).$$

Let us prove that all polynomials $P_k$ commute with the polynomial $P_2$; then they all commute with each other (point d)).

Let us give a proof by induction. It is clear that the polynomials $P_1$ and $P_2$ commute with $P_2$; suppose that all polynomials $P_1, P_2, \dots$

⟦folio 22⟧

..., $P_k$ commutes with $P_2$, and we prove that the polynomial $P_{k+1}$ commutes with $P_2$.

We need to show that
$$P_{k+1}(x^2-2)=(P_{k+1}(x))^2-2.$$

Substituting the recurrent formula for $P_{k+1}$ into this equality, we rewrite it in the form
$$(x^2-2)P_k(x^2-2)-P_{k-1}(x^2-2)$$
$$=(xP_k(x)-P_{k-1}(x))^2-2.$$

Now we use the induction assumption:
$$(x^2-2)(P_k(x)^2-2)-(P_{k-1}(x)^2-2)$$
$$=(xP_k(x)-P_{k-1}(x))^2-2.$$

Expanding the brackets and driving terms, we obtain the following equality:
$$-2(P_k(x)^2-xP_k(x)P_{k-1}(x))+P_{k-1}(x)^2=2x^2-8$$

or
$$P_k(x)^2-xP_k(x)P_{k-1}(x)+P_{k-1}(x)^2=4-x^2.$$

Let's denote the left side (*) by $S_k(x)$. It remains for us to prove that $S_k(x)$ does not depend on $k$ (and is equal to $4-x^2$). Indeed, let $k>2$. Then
$$S_k(x)=P_k(x)^2-xP_k(x)P_{k-1}(x)+P_{k-1}(x)^2=P_k(x)[P_k(x)-xP_{k-1}(x)]+P_{k-1}(x)^2$$
$$=-P_k(x)P_{k-2}(x)+P_{k-1}(x)^2=P_{k-2}(x)^2-xP_{k-1}(x)P_{k-2}(x)+P_{k-1}(x)^2=S_{k-1}(x),$$
i.e. $S_k(x)=S_{k-1}(x)$. Since $S_2(x)=4-x^2$, $S_k(x)=4-x^2$ for all $x \geq 2$. Thus, we have shown that $P_k$ commutes with $P_2$ for any $k$.

Problems on commuting polynomials

We want to discuss problems related to the following problem: describe all pairs of commuting (not necessarily unitary) polynomials $P$ and $Q$.

Problem 1. Prove that two polynomials $P$ and $Q$ of the first degree commute if and only if either $P(x)=x+\alpha$, $Q(x)=x+\beta$, or there exists $x_0$ such that $P(x_0)=Q(x_0)=x_0$ (a common “fixed” point).

Problem 2. Solve the general problem for the case when the degree of one of the polynomials $P$, $Q$ is equal to 1.

In what follows, we will assume that the degrees of the polynomials $P$ and $Q$ are greater than 1.

Let $P(x)=a_0x^k+a_1x^{k-1}+\cdots+a_{k-1}x+a_k$, $Q(x)=b_0x^e+\cdots+b_{e-1}x+b_e$. First of all, we show that we can reduce the general problem to the case when the coefficients $a_1$ and $b_1$ are equal to 0 (polynomials of this type are called *reduced*). To do this, we will use the following operation. Let us fix the number $a$ and use it to construct from each polynomial $R$ a new, “matched” polynomial $R^{(a)}$ using the formula $R^{(a)}(x)=R(x-a)+a$. It is clear that the polynomial $R$ can be reconstructed from the polynomial $R^{(a)}:R(x)=R^{(a)}(x+a)-a$.

Problem 3. a) Prove that if the polynomials $P$ and $Q$ commute, then $P^{(a)}$ and $Q^{(a)}$ also commute.

6) Prove that any pair of commuting polynomials $P$ and $Q$ of degree greater than 1 has the form $P=S^{(a)}$, $Q=T^{(a)}$, where $a$ is some number, and $S$ and $T$ are commuting reduced polynomials.

In what follows we will assume that the polynomials $P$ and $Q$ are given. In addition, we will assume that they are unitary, that is, their leading coefficients are equal to 1. Clearly, this is the most interesting special case. In addition, by reasoning similar to those carried out above, it is shown that it is possible to reduce the general problem to the case when the leading coefficients of the polynomials $P$ and $Q$ are equal to ±1, so that this particular case does not differ much from the general one (in these arguments it is necessary to use the “stretching” operation, which associates each polynomial $R$ with the polynomial $R^{\lambda}$ according to the formula $R^{\lambda}(x)=\lambda R(x/\lambda)$). Let us describe several series of commuting polynomials:

1. Let $R$ be a polynomial of degree $r$. Consider the series of polynomials $P_0(x)=x$, $P_1(x)=R(x)$, $P_2(x)=R(R(x))$, $P_3(x)=R(R(R(x)))$ (in general $P_{i+1}(x)=P_i(R(x))$).

It is clear that all polynomials $P_i$ commute and the degree of the polynomial $P_i$ is equal to $r^i$.

⟦folio 23⟧

2. Series of polynomials $F_k(x) = x^k$. All polynomials $F_k$ commute and the degree of the polynomial $F_k$ is $k$.

3. $\{P_k\}$ is a series of polynomials constructed when solving part e) problem M455. These polynomials are determined by the condition $P_k(t + t^{-1}) = t^k + t^{-k}$. The degree of the polynomial $P_k$ is $k$.

4. Let us define the series of polynomials $H_1, H_3, H_5, \dots$ by the following condition: $H_k(t - t^{-1}) = t^k - t^{-k}$ (k odd). It is easy to verify that such polynomials exist and are uniquely determined by the written condition. All these polynomials commute and the degree of the polynomial $H_k$ is equal to $k$.

In fact, examples 3 and 4 are special cases of servants of a more general example. To describe this general example, we make one remark about the coefficients of polynomials. Until now we have assumed that these coefficients are real numbers. However, in most algebraic questions it is better to work with complex numbers. Therefore, let's assume that the coefficients of our polynomials can be any complex numbers.

5. We fix a natural number $m$ and a complex number $\lambda$ such that $\lambda^m = 1$ (for every $m$ there is a $m - 1$ number different from 1).

Consider pairs of numbers $(u, v)$ such that $u.v = \lambda$, and put $x = u + v$. It is easy to check that $u^k + v^k = x^k + a_1x^{k-1} + \dots + a_k$, where $a_1, \dots, a_k$ are some numbers, depends on $\lambda$. Let's put $P_k(x) = x^k + a_1x^{k-1} + \dots + a_k$; the polynomial $P_k$ is characterized by the following condition: $P_k(u + v) = u^k + v^k$ if $uv = \lambda$.

Let $l$ be a number that leaves remainder 1 when divided by $m$. Then $u^lv^l = (uv)^l = \lambda^l = \lambda$, so $P_k(u^l + v^l) = u^{kl} + v^{kl}$. Thus, if $k$ and $l$ give remainder 1 when divided by $m$, then $P_k(P_l(u + v)) = u^{kl} + v^{kl} = P_l(P_k(u + v))$, that is, the polynomials $P_k$ and $P_l$ commute. Based on the number $\lambda$, we have constructed a series of commuting polynomials $P_1, P_{m+1}, P_{2m+1}$, …. All these polynomials are unitary, reduced, and the degree $P_k$ is equal to $k$.

For $m = 1$, $\lambda = 1$ we get example 3, for $m = 2$, $\lambda = -1$ we get example 4.

Examples 1–5 exhaust all known examples of commuting polynomials, so we can hypothesize that if $P$ and $Q$ are commuting unitary reduced polynomials of degrees greater than 1 with complex coefficients, then they are included in one of the series constructed in Examples 1, 2, 5.

Without solving the general problem, you can try to answer some partial questions:

1. For what $\alpha$ does the polynomial $P(x) = x^2 - \alpha$ commute with some polynomial of odd degree.

2. Let $P$ be a unitary polynomial of degree greater than 1. Let us note the degrees of all unitary polynomials $Q$ that commute with $P$. What subset of natural numbers can this result in?

For example, in example 1 this is a geometric progression; in example 5 - arithmetic.

3. Let $P, Q$ be commuting unitary polynomials of degrees $k$ and $l$. Suppose $l$ is divisible by $k$. Is it true that $Q$ has the form $Q(x) = P(R(x))$, where $R$ is a unitary polynomial commuting with $P$?

You can form a more general problem - find all commuting rational functions $P$ and $Q$. In this case, many new interesting examples appear.

The general method that we discussed in the solution to point e) for polynomials is also suitable here. Let there be a function $f$ (taking on an infinite number of values) such that

$$f(nt) = P_n(f(t)),$$

where $P_n$ is a rational function. Then for different $n$ and $m$ the functions $P_n$ and $P_m$ commute.

An interesting question arises: for what functions $f$ can we, for any $n$, choose a rational function $P_n$ such that $P_n(f(t)) = f(nt)$. For example, it is easy to check that the function $f(t) = tg t$ satisfies this condition.

It is possible to construct other examples of functions $f$ using the theory of elliptic functions. Since this is not an elementary theory, we will not describe the corresponding constructions here.

All these examples show that the problem of describing commuting polynomials (and, more generally, commuting rational functions) is directly related to very deep and rich mathematical theories. The solution to this problem will apparently reveal some new, previously unknown facts. In short, it is a task worth taking up.
