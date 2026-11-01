---
id: 1979-8-kuzmin-shirshov-o-chisle-e-42e93c5b
issue: kvant_1979_8
year: 1979
number: "8"
title: About the number e
authors:
  - Кузьмин Е. Н.
  - Ширшов А. И.
rubric: osnovnye-stati
page_first: 5
page_last: 10
page_labels: 3, 4, 6, 7, 8
tag: 9KKE
lang: en
source: kvant_digital
extraction: vision
content_sha256: 7f7d815c6d1b1d7f40c726c6d3283fe79105559112ae0f5d7492d694cf165477
prompt_sha256: draft-1
translated_from: content/ru/1979/08/articles/03_kuzmin-shirshov-o-chisle-e-42e93c5b.md
source_content_sha256: 1f0814c7955b733281e991b0fb138da56f98c980f31e0857d49fe5f443a6ba38
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 3⟧

About the number e

1. What is e?

At school, as early as the fifth grade, you are introduced to the number π, which has a very long history, the beginning of which is lost in the mists of time, in the ancient world *). Then you meet him in eighth, ninth, tenth grade. You only come across the number e at the end of tenth grade. However, this remarkable number, which came into use in the 18th century along with the development of mathematical analysis, plays an almost more important role in modern mathematics.

In the school textbook, two definitions are given for the number e. In the second (we won’t need the first), the number e is the limit of the sequence $x_n = \left(1 + \frac{1}{n}\right)^n$. Let us prove that this limit exists.

Lemma 1. For any m, n

$$\left(1 + \frac{1}{n}\right)^n < \left(1 + \frac{1}{m}\right)^{m+1}.$$

(1)

inequality (1) is very easy to prove using the famous Cauchy inequality:

$$\sqrt[n]{a_1 \cdot a_2 \cdot \dots \cdot a_n} < \frac{a_1 + a_2 + \dots + a_n}{n},$$

(2)

where $a_1, a_2, \dots, a_n$ are positive numbers, among which there are different ones**). From (2)

$$\sqrt[n]{1 + \frac{1}{n}} \left(1 - \frac{1}{m+1}\right)^{m+1} < \frac{n \left(1 + \frac{1}{n}\right) + (m+1) \left(1 - \frac{1}{m+1}\right)}{m+n+1} = 1,$$

whence $$\left(1 + \frac{1}{n}\right)^n \left(1 - \frac{1}{m+1}\right)^{m+1} < 1$$ and $$\left(1 + \frac{1}{n}\right)^n < \left(1 + \frac{1}{m}\right)^{m+1}.$$

Lemma 2. The sequence $(x_n)$ is increasing.

Proof. Let us denote $\left(1 + \frac{1}{n}\right)^n+1$ by $y_n$. According to Lemma 1, $x_{n(n+2)} < y_{n+1}$, that is

$$\left(1 + \frac{1}{n(n+2)}\right)^{n(n+2)} < \left(1 + \frac{1}{n+1}\right)^{n+2}.$$

*) Many interesting details about the number π can be found in the book by F. Kymen and “The History of the Number π” (M., “Nauka”, 1971). See also the article by A. Zvonkin “What is π?” («Kvant», 1978, no. 11).

**) Try to prove it yourself. You can also read his proof on p. 26.

⟦folio 4⟧

Means,

$$\left(1 + \frac{1}{n(n+2)}\right)^n < 1 + \frac{1}{n+1}.$$

Therefore, $$\left(1 + \frac{1}{n(n+2)}\right)^n = \frac{(n+1)^2n}{n^n(n+2)^n} < \frac{n+2}{n+1}.$$

Therefore $$\left(\frac{n+1}{n}\right)^n < \left(\frac{n+2}{n+1}\right)^{n+1}$$ or $$x_n < x_{n+1}.$$

From Lemmas 1, 2 and Weierstrass's theorem it follows that the sequence $(x_n)$ has a limit. The notation $e$ for this limit was introduced by L. Euler (1707–1783).

Exercise. Prove that $$\lim_{n \to \infty} y_n = e$$ and that for any $m, n$

$$x_n < e < y_m.$$

The number $e$ can also be defined as the limit of the sequence $s_n = 1 + \frac{1}{1!} + \frac{1}{2!} + \dots + \frac{1}{n!}$. Let's prove it. According to Newton's formula

$$x_n = 1 + n \cdot \frac{1}{n} + \frac{n(n-1)}{2!} \cdot \frac{1}{n^2} + \dots + \frac{n(n-1) \cdot \dots \cdot (n-k+1)}{k!} \cdot \frac{1}{n^k} + \dots + \frac{1}{n^n} = 1 + 1 + \frac{1}{2!} \left(1 - \frac{1}{n}\right) + \dots + \frac{1}{k!} \left(1 - \frac{1}{n}\right) \times \left(1 - \frac{2}{n}\right) \dots \dots \left(1 - \frac{k-1}{n}\right) \times \left(1 - \frac{2}{n}\right) \dots \dots \left(1 - \frac{n-1}{n}\right).$$

(From (3) it is also clear that the sequence $(x_n)$ is increasing.) By eliminating the factors in parentheses, we will increase each term on the right side of equality (4). Therefore, $x_n < s_n$ (at $n > 1$).

We now fix an arbitrary $k > 1$. Assuming that $n > k$, we discard all terms on the right side of equality (3), starting with $(k+2)$. We get

$$x_n > 1 + 1 + \frac{1}{2!} \left(1 - \frac{1}{n}\right) + \dots + \frac{1}{k!} \left(1 - \frac{1}{n}\right) \left(1 - \frac{2}{n}\right) \dots \dots \left(1 - \frac{k-1}{n}\right).$$

For $n \to \infty$ (and fixed $k$), the right-hand side of inequality (4) tends to $s_k$. Passing to the limit in inequality (4), we obtain $e \geqslant s_k$. So, $x_n < s_n \leqslant e$. From $$\lim_{n \to \infty} x_n = e$$ we get $$\lim_{n \to \infty} s_n = e.$$ Thus,

$$e = 1 + \frac{1}{1!} + \frac{1}{2!} + \dots + \frac{1}{n!} + \dots.$$

The sequence $(s_n)$ is much more convenient to use for calculating approximate values ​​of the number $e$ than the sequence $(x_n)$. Let's estimate the difference $e - s_n$. From (5)

$$e - s_n = \frac{1}{(n+1)!} + \frac{1}{(n+2)!} + \dots =$$

$$= \frac{1}{(n+1)!} \left[ 1 + \frac{1}{n+2} + \frac{1}{(n+2)(n+3)} + \dots \right] <$$

$$< \frac{1}{(n+1)!} \left[ 1 + \frac{1}{n+2} + \frac{1}{(n+2)^2} + \dots \right] =$$

$$= \frac{1}{(n+1)!} \cdot \frac{1}{1 - \frac{1}{n+2}} = \frac{n+2}{(n+1)^2 \cdot n!} < \frac{1}{n \cdot n!}.$$

⟦folio none⟧

The result obtained can be written as the equality

$$e = s_n + \frac{\theta_n}{n \cdot n!} \quad (0 < \theta_n < 1).$$

From (6) it is easy to obtain the irrationality of the number $e$. Indeed, suppose that $e = \frac{p}{q}$. then $q!e$ is an integer. From (6) at $n=a$

$$q!e = q! + q! + \frac{q!}{2!} + \dots + \frac{q!}{q!} + \frac{\theta_q}{q}.$$

It turns out that $\frac{\theta_q}{q}$ is an integer, which is obviously false. Here are the first decimal places of the number $e$.

$$e = 2,718281828459045\dots$$

2. Problem about partitions

The number $e$, the darling of mathematical analysis and function theory, appears quite unexpectedly in some combinatorial problems. Let's consider one such problem.

Let's start with an example. The two-element set $\{a_1, a_2\}$ can be partitioned into disjoint subsets (when speaking about partitions, they are called classes) in two ways: this is a “land-by-ground” partition $\{a_1\}, \{a_2\}$ and a degenerate “integer” partition $\{a_1, a_2\}$. Similar partitions exist (for $n>2$) for any $n$-element set. At $n=3$ three more partitions are added to them (Fig. 1).

Let us denote the partition number of a $n$-element set by $\tau(n)$ *).

Obviously $\tau(0) = \tau(1) = 1$. As we just noted, $\tau(2) = 2$, $\tau(3) = 5$. What is $\tau(n)$ equal to for an arbitrary $n$? Is it possible to indicate some simple formula for $\tau(n)$?

As is often the case in combinatorial problems, it is easy to find a recurrence relation relating $\tau(n)$ to the values ​​$\tau(k)$ for $k < n$.

Let $M = \{a_1, a_2, \dots, a_n\}$. Let us sort all partitions of the set $M$ depending on the number $k$ of elements of the class in which the element $a_1$ falls for a given partition. The number $k$ can be equal to 1,2,...,$n$. For a fixed $k$, the number of such partitions is obviously equal to $C_{n-1}^{k-1}\tau(n-k)$.

Thus, $\tau(n) = \sum_{k=1}^{n} C_{n-1}^{k-1}\tau(n-k)$. It's easy to check that

$$\sum_{k=1}^{n} C_{n-1}^{k-1}\tau(n-k) = \sum_{k=0}^{n-1} C_{n-1}^{k-1}\tau(k).$$

Of course,

$$\tau(n) = \sum_{k=0}^{n-1} C_{n-1}^{k-1}\tau(k).$$

Using formula (7), it is easy to calculate that $\tau(4)=15$, $\tau(5)=52$, $\tau(6)=203$, $\tau(7)=877$, $\tau(8)=4140$—as $n$ increases, the number $\tau(n)$ increases rapidly.

*) The numbers $\tau(n)$ are called Bell numbers («Kvant», 1978, No. 7).

⟦folio 6⟧

We will use recurrent formula (7) to prove a favorite statement in which it is necessary to check the number $e$:

$$e \cdot \tau(n) = \frac{1^n}{1!} + \frac{2^n}{2!} + \dots + \frac{k^n}{k!} + \dots \quad (n \geqslant 1)$$

Proof. Let's use the method of mathematical induction. For $n=1$ (8) is true due to (5). Let us now assume that (8) is true for all numbers less than some $n$; Let us prove that then it is also true for $n$. By (5) and by the induction hypothesis, the following equalities are true:

$$e \cdot \tau(0) = 1 + \frac{1}{1!} + \frac{1}{2!} + \dots + \frac{1}{k!} + \dots$$

$$e \cdot \tau(1) = \frac{1}{1!} + \frac{2}{2!} + \dots + \frac{k}{k!} + \dots$$

$$e \cdot \tau(2) = \frac{1^2}{1!} + \frac{2^2}{2!} + \dots + \frac{k^2}{k!} + \dots$$

$$e \cdot \tau(n-1) = \frac{1^{n-1}}{1!} + \frac{2^{n-1}}{2!} + \dots + \frac{k^{n-1}}{k!} + \dots$$

(Infinite sums on the right-hand sides must, naturally, be understood as limiting partial sums.) Let us add these equalities term by term with the coefficients corresponding to $C_{n-1}^0, C_{n-1}^1, C_{n-1}^2, \dots, C_{n-1}^{n-1}$. On the left side, according to (7), we get $e \cdot \tau(n)$, on the right

$$1 + \frac{\varphi(1)}{1!} + \frac{\varphi(2)}{2!} + \dots + \frac{\varphi(k)}{k!} + \dots$$

where $\varphi(t) = C_{n-1}^0 + C_{n-1}^1 t + C_{n-1}^2 t^2 + \dots + C_{n-1}^{n-1} t^{n-1} = (1+t)^{n-1}$.

Hence,

$$e \cdot \tau(n) = 1 + \frac{2^{n-1}}{1!} + \frac{3^{n-1}}{2!} + \dots + \frac{(k+1)^{n-1}}{k!} + \dots = \frac{1^n}{1!} + \frac{2^n}{2!} + \frac{3^n}{3!} + \dots + \frac{(k+1)^n}{(k+1)!} + \dots$$

Q.E.D. From (8) we get a beautiful formula

$$\tau(n) = \frac{1}{e} \sum_{k=1}^{\infty} \frac{k^n}{k!}$$

inconvenient, however, for calculating $\tau(n)$. Below we will obtain simple (in the sense of “non-recurrent”) finite (not through a series) formulas for calculating $\tau(n)$.

Let us call the rank of a given partition the number of classes of which it consists. Let us denote by $c_{n,k}$ the partition number of rank $k$ of the $n$-element set $^*$. Obviously, the rank can only take the values ​​$1,2,\dots,n$; That's why

$$\tau(n) = \sum_{k=1}^{n} c_{n,k}.$$

For $k>n$ we set $c_{n,k}=0$.

For numbers $c_{n,k}$ it is easy to obtain a recurrence relation. Let $M=\{a_1,a_2,\dots,a_n\}, M'=\{a_2,\dots,a_n\}$. Let's divide the partitions of the set

$$^*$$

*) The numbers $c_{n,k}$ are called Stirling numbers.

⟦folio 7⟧

properties $M$ of rank $k$ into two groups: partitions containing the one-green set $\{a_1\}$ as a partition class, and those not. There are obviously as many partitions of the first type as there are partitions of the set $M'$ of rank $k-1$, that is, $c_{n-1,k-1}$; There are $k$ times more partitions of the second type than partitions of the set $M'$ of rank $k$ (the element $a_1$ can be placed in any of the $k$ classes of the partition of the set $M'$), that is, $k \cdot c_{n-1,k}$. So, at $n > 1, k > 1$

$$c_{n,k} = c_{n-1,k-1} + k \cdot c_{n-1,k}. \tag{10}$$

Let us prove that for $n \geqslant 1, k \geqslant 1$

$$c_{n,k} = \sum_{s=0}^{k-1} \frac{(-1)^s (k-s)^{n-1}}{s! (k-s-1)!}. \tag{11}$$

Let us denote the correct particular solution (11) by $b_{n,k}$. If $k=1$, then $b_{n,1} = 1 = c_{n,1}$. If $k > 1$ and $n=1$, then

$$b_{1,k} = \sum_{s=0}^{k-1} \frac{(-1)^s}{s! (k-s-1)!} = \frac{1}{(k-1)!} \sum_{s=0}^{k-1} (-1)^s C_{k-1}^s = \frac{1}{(k-1)!} (1-1)^{k-1} = 0 = c_{1,k}.$$

If, finally, $k > 1$ and $n > 1$, then

$$b_{n,k} = \sum_{s=0}^{k-1} \frac{(-1)^s (k-s)^{n-1}}{s! (k-s-1)!} = \sum_{s=0}^{k-1} \frac{(-1)^s (k-s)^{n-2} \cdot (k-s)}{s! (k-s-1)!} = k \sum_{s=0}^{k-1} \frac{(-1)^s (k-s)^{n-2}}{s! (k-s-1)!} + \sum_{s=0}^{k-1} \frac{(-1)^s+1 (k-s)^{n-2} \cdot s}{s! (k-s-1)!} = k \cdot b_{n-1,k} + \sum_{s=1}^{k-1} \frac{(-1)^s+1 (k-s)^{n-2}}{s! (k-s-1)!} = k \cdot b_{n-1,k} + \sum_{s=0}^{k-1} \frac{(-1)^s+1 (k-s)^{n-2}}{s! (k-s-1)!} = k \cdot b_{n-1,k} + b_{n-1,k-1}.$$

Thus, the numbers $c_{n,k}$ and $b_{n,k}$ satisfy the same rerent relation of the form (10); in addition, their “initial values”: for $k=1$ (and any $n \geqslant 1$) and for $n=1$ (and any $k \geqslant 1$) coincide. Therefore (Fig. 2), $c_{n,k} = b_{n,k}$ for any $n \geqslant 1$ and $k \geqslant 1$.

From (9) and (11)

$$\tau(n) = \sum_{k=1}^{n} \sum_{s=0}^{k-1} \frac{(-1)^s (k-s)^{n-1}}{s! (k-s-1)!}. \tag{12}$$

Let us denote $k-s$ by $t$; then $1 \leqslant t \leqslant n$. For a fixed $t$ in the double sum (12), $s$ can vary from 0 to $n-t$. Collecting the coefficients for $t^{n-1}$, we can use formula (12) to transform it to the form

$$\tau(n) = \sum_{t=1}^{n} \left( \sum_{s=0}^{n-t} \frac{(-1)^s}{s!} \right) \frac{t^{n-1}}{(t-1)!}.$$

⟦folio 8⟧

The numbers $c_{n,k}$, which have a clear combinatorial meaning, unexpectedly appear in an algebraic problem involving polynomials.

Let us set $x^{(1)} = x, x^{(2)} = x (x-1), x^{(3)} = x (x-1)(x-2)$, etc. The polynomials 1, $x^{(1)}, x^{(2)}, \dots, x^{(n)}$ have degrees 0, 1, 2, ..., $n$, respectively. Therefore, any polynomial of degree $x$ not higher than $n$ can be uniquely represented as a sum of these polynomials (with some coefficients). In particular,

$$x^n = a_{n,1}x^{(1)} + a_{n,2}x^{(2)} + \dots + a_{n,n}x^{(n)}$$

(13)

For some numbers $a_{n,k}$, $(n \geqslant 1, 1 \leqslant k \leqslant n)$. For $k > n$ we put $a_{n,k} = 0$. It turns out $a_{n,k} = c_{n,k}$. Let's prove it.

Setting $x = 1$ in (13), we obtain $a_{n,1} = 1 = c_{n,1}$. If $k > 1$ and $n = 1$, then $a_{1,k} = 0 = c_{1,k}$. Let now $k > 1$ and $n > 1$.

$$x^n = \sum_{k=1}^{n} a_{n,k} x^{(k)} = x \cdot x^{n-1} = x \cdot \sum_{i=1}^{n-1} a_{n-1,i} x^{(i)} = \sum_{i=1}^{n-1} a_{n-1,i} x^{(i)} \left[ (x-i) + i \right] =$$

$$= \sum_{i=1}^{n-1} a_{n-1,i} \left[ x^{(i)} (x-i) + ix^{(i)} \right] = \sum_{i=1}^{n-1} a_{n-1,i} \left[ x^{(i+1)} + ix^{(i)} \right] = \sum_{i=1}^{n-1} a_{n-1,i} x^{(i+1)} +$$

$$+ \sum_{i=1}^{n-1} a_{n-1,i} ix^{(i)}$$

Comparing the coefficients at $x^{(k)}$, we obtain $a_{n,k} = a_{n-1,k-1} + k \cdot a_{n-1,k}$. As above, it follows that $a_{n,k} = c_{n,k}$ for all $n, k$.

The law doesn't have it. Prove the equality:

$$\tau(n-1) = \sum_{t=0}^{n-1} (-1)^t C_{n-1}^t \tau(n-t).$$
