---
id: 1978-10-kurlyandchik-lisitskiy-summyi-i-proizvedeniya-37d585e8
issue: kvant_1978_10
year: 1978
number: "10"
title: Sums and products
authors:
  - Курляндчик Л. Д.
  - Лисицкий А. Д.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 33
page_last: 38
page_labels: 31, 32, 33, 34, 36
tag: YV0W
lang: en
source: kvant_digital
extraction: vision
content_sha256: 04e607a8336c7abdd902e3b1c6b74d672670700907f1a215b9bd1ee476e14c98
prompt_sha256: draft-1
translated_from: content/ru/1978/10/articles/11_kurlyandchik-lisitskiy-summyi-i-proizvedeniya-37d585e8.md
source_content_sha256: d340c61fc65a50b5870a361dae1a98d95aa1c38e7d1ab91e7e431a9f05157d41
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 31⟧

We write formulas, as a rule, briefly, using the notation

$$\sum_{k=1}^{n} a_k = a_1 + a_2 + \dots + a_n,$$

$$\prod_{k=1}^{n} b_k = b_1 \cdot b_2 \cdot \dots \cdot b_n,$$

$$n! = 1 \cdot 2 \cdot \dots \cdot n.$$

We advise those who have not yet learned how to use them to describe the calculations in more detail.

1. Residual extreme

This title is explained by the following next equality:

$$(a_2 - a_1) + (a_3 - a_2) +$$

$$+ (a_4 - a_3) + \dots + (a_n - a_{n-1}) +$$

$$+ (a_{n+1} - a_n) = a_{n+1} - a_1$$

(1)

or

$$\sum_{k=1}^{n} (a_{k+1} - a_k) = a_{n+1} - a_1,$$

(1')

from which, by choosing the sequence $(a_k)$ in different ways, we can obtain many not very good equalities.

Example 1. Putting $a_k = -\frac{1}{k}$, we get $\sum_{k=1}^{n} \frac{1}{k(k+1)} = \frac{n}{n+1}$; It is difficult to find an algebra problem book that does not contain this example.

Example 2. Put $a_k = k(k-1)d/2$. Since $a_{k+1} - a_k = kd$, equality (1) takes the form $\sum_{k=1}^{n} kd = (n+1) \cdot n \cdot d/2$. By adding $a - d$ to each member of the trace sum, and $n(a - d)$ to the sum on the right, we obtain the well-known formula for the sum of $n$ terms of an arithmetic progression: $a + (a + d) + \dots + (a + (n-1)d) = n(a - d) + (n+1)nd/2 = na + n(n-1)d/2$.

Exercise 1. Take $a_k = (2k-1)^3/24$ in (1) and get the formula for $\sum_{k=1}^{n} k^2$.

⟦folio 32⟧

Example 3. Let $m$ be a natural number. Let's put $a_k = \frac{1}{(m+2)} \times (k-1)k(k+1) \dots (k+m)$. Then $a_{k+1} - a_k = \frac{1}{m+2}k \cdot (k+1) \dots (k+m) + 1 + m) - \frac{1}{m+2}(k-1)k \dots (k+m) = k(k+1) \dots (k+m)$. In this case, equality (1) is written as follows:
$$\sum_{k=1}^{n} k(k+1) \dots (k+m) = \frac{1}{m+2}n(n+1) \dots (n+m+1).$$
Equality (1) can be used in another way. Let us need to prove that
$$\sum_{k=1}^{n} f(k) = g(n).$$
Let's try to prove the equality
$$g(k) - g(k-1) = f(k).$$
If we succeed, then (2) will also be proven. Indeed, consider the auxiliary sequence
$$\left\{ \begin{array}{l} a_1 = 0, \\ a_{k+1} = g(k). \end{array} \right.$$
For this sequence, equality (1) has the form
$$\sum_{k=1}^{n} [g(k) - g(k-1)] = g(n),$$
which, in view of (3), is equivalent to (2).
Let us prove, for example, in this way the equality
$$\sum_{k=1}^{n} C_{l+k-1}^{l+1} = C_{l+n}^{l+1}.$$
In accordance with what has been said, for this it is enough to check the equality $C_{l+n}^{l+1} - C_{l+n-1}^{l+1} = C_{l+n-1}^{l+1}$ or $C_{l+n-1}^{l+1} + C_{l+n-1}^{l+1} = C_{l+n}^{l+1}$, which follows from the well-known point $C_n^m + C_n^{m+1} = C_n^{m+1}$ (“Algebra and principles of analysis 9”, paragraph 8). In Section 3 we will prove point (4) in a different way.
All of the above applies to the work. Let us first write the multiplicative analogue of equality (1):
$$\frac{a_2}{a_1} \cdot \frac{a_3}{a_2} \cdot \frac{a_4}{a_3} \dots \frac{a_n}{a_{n-1}} \cdot \frac{a_{n+1}}{a_n} = \frac{a_{n+1}}{a_1}$$
(*) $n!!$ denotes the product of natural numbers from 1 to $n$ that have the same parity as $n$. For example, $8!! = 2 \cdot 4 \cdot 6 \cdot 8, 9!! = 1 \cdot 3 \cdot 5 \cdot 7 \cdot 9$.

⟦folio 33⟧

4. $$\sum_{k=1}^{n} k \cdot k! = (n+1)! - 1.$$
5. $$\prod_{k=1}^{n} k^k \cdot k! = (n!)^{n+1}.$$
6. $$a_1 + (a_1+1) a_2 + (a_1+1) (a_2+1) \times a + \ldots + (a_1+1) (a_2+1) \ldots (a_{n-1}+1) \times a_n = (a_1+1) (a_2+1) \ldots (a_n+1) - 1.$$
7. $$\sum_{k=1}^{n} \frac{1}{k(k+1) \ldots (k+m)} = \frac{1}{m} \left( \frac{1}{m!} - \frac{1}{(n+1)(n+2) \ldots (n+m)} \right).$$
8. $$\sum_{k=1}^{n} \frac{x^k \cdot k!}{(x+1)(2x+1) \ldots (kx+1)} = \frac{1}{x-1} \frac{x^{n+1}(n+1)!}{(x+1) \ldots (nx+1)} + \frac{x}{1-x}.$$
9. $$\sum_{k=0}^{n-1} \frac{p_0 \cdot p_1 \ldots p_k q_{k+1}}{(p_1+q_1) \ldots (p_{k+1}+q_{k+1})} = 1 - \frac{p_1 p_2 \ldots p_n}{(p_1+q_1) \ldots (p_n+q_n)}.$$
(Here $(p_k)$ and $(q_k)$ are two sequences and $p_0 = 1$.)
Unfortunately, the indicating method is only suitable in the case when in the sum $$\sum_{k=1}^{n} b_k$$ the terms $b_k$ do not depend on $n$. In the next section we will prove equalities in which the terms depend on $n$.

2. Back and forth method

The name of this method (but not the method itself) is the invention of the author. Historians of mathematics claim that it was with his help that little Gaussoudi beat his school teacher by quickly finding the sum of natural numbers from 1 to 100. Let us demonstrate the use of the “back and forth” method with examples.

Let us prove that for odd $n$
$$\sum_{k=0}^{n} (-1)^k \sqrt{C_n^k} = 0.$$
Let's write the sum $S_n$ in two ways
$$S_n = \sqrt{C_n^0} - \sqrt{C_n^1} + \sqrt{C_n^2} - \ldots + \sqrt{C_n^{n-1}} - \sqrt{C_n^n} \text{ (туда)},$$

$$S_n = -\sqrt{C_n^0} + \sqrt{C_n^1} + \ldots - \sqrt{C_n^n} + \sqrt{C_n^0} \text{ (назад)}$$

In our sum there is a minus sign before $$\sqrt{C_n^n}$$ because $n$ is odd. Let's add the two resulting expressions:

$$2S_n = \left( \sqrt{C_n^0} - \sqrt{C_n^n} \right) + \left( -\sqrt{C_n^1} + \sqrt{C_n^{n-1}} \right) + \ldots + \left( -\sqrt{C_n^n} + \sqrt{C_n^0} \right).$$

It is easy to tell that each parenthesis contains a zero, since $C_n^m = C_n^{n-m}$. Therefore $2S_n = 0$, hence $S_n = 0$.

Another example:

$$\sum_{k=0}^{2n+1} \frac{(-1)^k}{C_{2n+1}^k} = 0.$$

It works the same way:

$$S_n = \frac{1}{(C_{2n+1}^0)^2} - \frac{1}{(C_{2n+1}^1)^2} + \ldots - \frac{1}{(C_{2n+1}^n)^2} \text{ (туда)},$$

$$S_n = -\frac{1}{(C_{2n+1}^0)^2} + \frac{1}{(C_{2n+1}^1)^2} - \ldots + \frac{1}{(C_{2n+1}^n)^2} \text{ (назад)}$$

Adding these expressions and taking into account that $C_{2n+1}^k = C_{2n+1}^{2n+1-k}$, we obtain $2S_n = 0$. Hence $S_n = 0$.

And here is a more complex, but also more interesting example on the same topic:

$$\sum_{k=0}^{n} \frac{(-1)^k}{C_n^k} = \frac{n+1}{n+2} (1 + (-1)^n).$$

Solving this problem is as simple as the previous two, without deleting. Let us denote $$\sum_{k=0}^{n} \frac{(-1)^k}{C_n^k}$$ by $S_n$. If $n$ is odd, you can easily prove that $S_n = 0$. The case of even $n$ will be reduced to odd. Watch carefully how this is done.

⟦folio 34⟧

Let us denote $\sum_{k=0}^{n} \frac{(-1)^k (k+1)}{C_n^k}$ by $T_n$.

Let's write $T_n$ in two ways:

$$T_n = \frac{1}{C_n^0} - \frac{2}{C_n^1} + \dots + \frac{n+1}{C_n^n} \text{ (туда)},$$

$$T_n = \frac{n+1}{C_n^n} - \frac{n}{C_n^{n-1}} + \dots + \frac{1}{C_n^0} \text{ (назад)}.$$

Adding, we get $2T_n = (n+2) \times \left( \frac{1}{C_n^0} - \frac{1}{C_n^1} + \dots + \frac{1}{C_n^n} \right) = (n+2) \times S_n$. On the other hand, $T_n = \sum_{k=0}^{n} \frac{(-1)^k (k+1) k! (n-k)!}{n!} = (n+1) \sum_{k=0}^{n} \frac{(-1)^k}{C_n^{k+1}} = (n+1) (1 - S_{n+1})$.

But since $S_{n+1} = 0$ ($n+1$ is odd), $T_n = n+1$. We have already proven that $S_n = \frac{2}{n+2} T_n$. So, $S_n = \frac{2(n+1)}{(n+2)}$.

It remains to note that $\frac{n+1}{n+2} (1 + (-1)^n) = \left\{ \begin{array}{l} 0, n нечетно, \\ \frac{2(n+1)}{n+2}, n четно. \end{array} \right.$

Proof of equality

$$\sum_{k=0}^{n} \frac{1}{C_n^k} = \frac{n+1}{2^{n+1}} \sum_{k=1}^{n+1} \frac{2^k}{k}. \tag{9}$$

more difficult than all the previous ones, but it is also instructive.

Let us introduce the following notation:

$$\sum_{k=0}^{n} \frac{1}{C_n^k} = D_n; \quad \sum_{k=0}^{n} \frac{k+1}{C_n^k} = E_n;$$

$$\frac{n+1}{2^{n+1}} \sum_{k=1}^{n+1} \frac{2^k}{k} = F_n.$$

First, using the “back and forth” method, we write down the amount twice

$$E_n = \frac{1}{C_n^0} + \frac{2}{C_n^1} + \dots + \frac{n+1}{C_n^n} \text{ (туда)},$$

$$E_n = \frac{n+1}{C_n^n} + \frac{n}{C_n^{n-1}} + \dots + \frac{1}{C_n^0} \text{ (назад)}.$$

Let's add these equalities: $2E_n = (n+2) \times \sum_{k=0}^{n} \frac{1}{C_n^k} = (n+2) D_n$. So, $D_n = \sum_{k=0}^{n} \frac{1}{C_n^k} = (n+2) E_n$. Now, continuing calculations similar to those we carried out when solving the previous problem, we will express $E_n$ through $D_{n+1}$.

Namely, $E_n = \sum_{k=0}^{n} \frac{k+1}{C_n^k} = (n+1) \times \sum_{k=0}^{n} \frac{1}{C_n^{k+1}} = (n+1) (D_{n+1} - 1)$, and we can express $D_{n+1}$ in terms of $D_n$:

$$D_{n+1} = \frac{2}{n+2} E_n = \frac{2}{n+2} (n+1) (D_{n+1} - 1),$$

where

$$D_{n+1} = 1 + \frac{n+2}{2(n+1)} D_n.$$

Now, user of mathematical induction, let us prove that $D_n = F_n$ for all integers $n \geqslant 0$. It is easy to see that $D_0 = 1$ and $F_0 = 1$. Let's assume that $D_s = F_s$. Then $D_{s+1} = 1 + \frac{s+2}{2(s+1)} D_s = 1 + \frac{s+2}{2(s+1)} F_s = 1 + \frac{s+2}{2(s+1)} \cdot \frac{s+1}{2^{s+1}} \sum_{k=1}^{s+1} \frac{2^k}{k} = 1 + \frac{s+2}{2^{s+1}} \sum_{k=1}^{s+1} \frac{2^k}{k} = F_{s+1}$.

This means $D_n = F_n$ for all integers $n \geqslant 0$. Solution problem.

Having proved equalities (8) and (9), we solved problem M470 («Kvant», 1977, No. 10). Equality (9) allows us to propose a new solution problem M434 («Kvant», 1977, No. 12).

Let $\sum_{k=1}^{n} \frac{2^k}{k} = \frac{p_n}{q_n}$, where $p_n, q_n$ be mutually prime. Let us denote by $v(n)$ the highest power of 2 by which $p_n$ is divisible. Let us prove that $v(n) \geqslant \frac{n-3}{2}$.

From (9) $\sum_{k=0}^{n} \frac{1}{C_n^k} = \frac{n+1}{2^{n+1}} \frac{p_{n+1}}{q_{n+1}}$. That's why $\frac{p_{n+1}}{q_{n+1}} = \frac{2^{n+1}}{n+1} \sum_{k=0}^{n} \frac{1}{C_n^k}$ or $\frac{p_n}{q_n} = \frac{2^{n}}{n} \sum_{k=0}^{n-1} \frac{1}{C_n^k}$. Hence $\frac{p_n}{q_n} = \frac{2^{n}}{n}! \times ((n-1)! + 1! (n-2)! + 2! (n-3)! + \dots + (n-1)!)$. In $n!$ the number 2 is included in the power $\left[ \frac{n}{2} \right] + \dots \leqslant$

⟦folio 36⟧

polynomial
$$f(x) = (1+x)^n (x+1)^n = \left( C_n^0 + C_n^1 x + C_n^2 x^2 + \dots + C_n^n x^n \right) \times \left( C_n^0 x^n + C_n^1 x^{n-1} + C_n^2 x^{n-2} + \dots + C_n^n \right).$$

The coefficient of $x^n$ in this product is obviously equal to $\sum_{k=0}^{n} \left( C_n^k \right)^2$.

On the other hand, $f(x) = (1+x)^2n$. The coefficient of $x^n$ in it is equal to $C_{2n}^n$. By the theorem we obtain that $\sum_{k=0}^{n} \left( C_n^k \right)^2 = C_{2n}^n$.

Now let's find $\sum_{k=0}^{n} (-1)^k \left( C_n^k \right)^2$.

When solving the previous problem, we considered the polynomial $f(x) = (1+x)^n (x+1)^n$. Here, apparently, it is necessary to take a positive polynomial, but so that the signs of the coefficients in it are linear. Let's try to consider the polynomial $g(x) = (1+x)^n (x-1)^n = \left( C_n^0 + C_n^1 x + \dots + C_n^n x^n \right) \left( C_n^0 x^n - C_n^1 x^{n-1} + \dots + (-1)^n C_n^n \right)$.

The coefficient of $x^n$ in this product is equal to $\sum_{k=0}^{n} (-1)^k \left( C_n^k \right)^2$. On the other hand, $g(x) = (1+x)^n (x-1)^n = (-1)^n (1-x^2)^n = (-1)^n \times \sum_{k=0}^{n} (-1)^k C_n^k x^{2k}$. In this sum, the coefficients for odd powers $x$ are equal to 0. Therefore, if $n$ is odd, then the coefficient for $x^n$ is equal to 0. If $n$ is even, then the coefficient for $x^n$ is equal to $(-1)^{n+\frac{n}{2}} C_n^{\frac{n}{2}} = (-1)^{\frac{n}{2}} C_n^{\frac{n}{2}}$. So, $\sum_{k=0}^{n} (-1)^k \left( C_n^k \right)^2 = \left\{ \begin{array}{l} 0, n \text{ нечетно}, \\ (-1)^{\frac{n}{2}} C_n^{\frac{n}{2}}, n \text{ четно}. \end{array} \right.$

Exercises

14. Find the sum $\sum_{k=0}^{n} \frac{C_n^k}{k+1}$. (Answer: $\frac{2^{n+1}-1}{n+1}$.)

15. Let us denote by $B_n^k$ the coefficient of $x^k$ in the polynomial $(1+x+x^2)^n$. Find the sum $\sum_{k=0}^{2n} \left( B_n^k \right)^2$. (Answer: $B_{2n}^n$).

At first glance, this method looks very artificial, because everyone doesn’t understand how to learn to choose the right polynomial. Unfortunately, in this article we cannot go into more detail on this issue.

However, we think that after solving the suggested exercises, you can solve similar problems on your own.

4. Abel transformation

Let us be given the sum $S_n = a_1 b_1 + a_2 b_2 + \dots + a_n b_n$, where $a_1, a_2, \dots, a_n, b_1, b_2, \dots, b_n$ are two sequences. Let us denote the sums of $b_1, b_1 + b_2, \dots, b_1 + b_2, \dots, b_1 + b_2 + \dots + b_n$ corresponding by $B_1, B_2, \dots, B_n$. Then $b_1 = B_1, b_k = B_k - B_{k-1}$ with $k > 1$ and $\sum_{k=1}^{n} a_k b_k$ can be transformed as follows:

$$\sum_{k=1}^{n} a_k b_k = a_1 B_1 + a_2 (B_2 - B_1) + \dots + a_n (B_n - B_{n-1}) = (a_1 - a_2) B_1 + (a_2 - a_3) B_2 + \dots + (a_{n-1} - a_n) B_{n-1} + a_n B_n = \sum_{k=1}^{n-1} (a_k - a_{k+1}) B_k + a_n B_n.$$

This transformation is called the Abel transformation (for the remarkable order of the mathematician Nils Henrik Abell, see «Kvant» No. 5 for 1976).

Using the Abel transformations, we find the sum $\sum_{k=1}^{n} kq^{k-1}$.

Let us set $a_1 = 1, a_2 = 2, \dots, a_n = n; b_1 = 1, b_2 = q, \dots, b_n = q^{n-1}$ at point (10). Then $B_k = \frac{q^k - 1}{q-1}$ and $a_1 - a_2 = a_2 - a_3 = \dots = a_{n-1} - a_n = -1$. Pozotomu

$$\sum_{k=1}^{n} kq^{k-1} = \sum_{k=1}^{n-1} (-1) \frac{q^k - 1}{q-1} +$$
