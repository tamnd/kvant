---
id: 1970-6-fuks-fuks-arifmetika-binomialnyih-koeffitsientov-2ab8fad6
issue: kvant_1970_6
year: 1970
number: "6"
title: Arithmetic of binomial coefficients
authors:
  - Фукс Д. Б.
  - Фукс М. Б.
rubric: osnovnye-stati
page_first: 19
page_last: 27
page_labels: 17, 18, 19, 20, 23, 24, 25
tag: 8T3Q
lang: en
source: kvant_digital
extraction: vision
content_sha256: 1c29fbe42c003d7e19828db3a732a546c5f35088cbc9f0d3682d26eb6f52e775
prompt_sha256: draft-1
translated_from: content/ru/1970/06/articles/05_fuks-fuks-arifmetika-binomialnyih-koeffitsientov-2ab8fad6.md
source_content_sha256: d7fd194a99b8095fd31569d0bd9046a4573f576085ca39a4c75103b5bce53158
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 17⟧

ARITHMETIC
BINOMIAL
ODDS

D. B. Fuks, M. B. Fuks

$(1+x)^2=1+2x+x^2$
$(1+x)^3=1+3x+3x^2+x^3$

Any schoolchild knows these formulas. Numbers 1, 2, 1; 1, 3, 3, 1, as well as numbers obtained in a similar way when raised to the power of 4, 5, ..., are called biomial coefficients. This article talks about the various properties of biomial coefficients. The first paragraph sets out the “general theory”: most of the theorems proved here were also included in the school curriculum. In the second paragraph we will show how you can very easily find the remainder when dividing any of the biomial coefficients by any prime number. Some of the statements in this paragraph are formulated as hypotheses. Perhaps readers «Kvant» will try to prove them.

⟦folio 18⟧

§ 1. Definition and simplest properties of binomial coefficients

If the binomial (binomial) $1+x$ is weighed by some natural power $n$, then, obviously, the result is a polynomial of the $n$ degree (i.e., the highest degree to which $x$ appears in this polynomial will be equal to $n$). For example:

$$(1+x)^0 = 1,$$
$$(1+x)^1 = 1+x,$$
$$(1+x)^2 = 1+2x+x^2,$$
$$(1+x)^3 = 1+3x+3x^2+x^3,$$
$$(1+x)^4 = 1+4x+6x^2+4x^3+x^4,$$
$$(1+x)^5 = 1+5x+10x^2+10x^3+$$
$$+5x^4+x^5,$$

The coefficients of these polynomials are called binomial. There is special notation for them: the coefficient of $x^m$ in $(1+x)^n$ is denoted by $C_n^m$. For example, $C_2^1=2$, $C_4^2=6$, $C_5^3=10$. In old algebra textbooks, the number $C_n^m$ is called "the number of combinations of $n$ through $m$". There are reasons for this, but we don't

From here it is easy to obtain that

$$(a+x)^n = C_n^0a^n + C_n^1a^{n-1}x\ldots$$
$$\ldots + C_n^nx^n$$

(it is enough to apply formula (1) to the calculation of $(1+x)a^n$ and multiply both sides of the resulting equality by $a^n$). The last formula is called Newton's binomial. Hence the name of the coefficients - binomial.

It is clear that $C_n^m$ are non-negative integers and that $C_n^m=0$ for $m>n$ (the polynomial $(1+x)^n$ has degree $n$, and $x^m$ with $m>n$ is not included in it). It is easy to verify further that $C_n^0=C_n^1=1$. Other binomial coefficients $C_n^m$, where $0<m<n$, can be found by raising $1+x$ to various powers. Their values ​​for $n\leqslant10$ are given in the table.

We see that binomial coefficients are quite rapidly growing numbers. An observant reader will notice a number of patterns in the arrangement of these numbers. As a rule, such patterns are easily derived from the definition of binomial coefficients. We will prove here only the main ones. Let's start with the most important of all - the so-called Pascal identity.

We will highlight in them: for us this is not important. So,

$$(1+x)^n = C_n^0+C_n^1x+C_n^2x^2+\ldots$$
$$\ldots +C_n^nx^n.$$

(1)

Theorem 1 (Pascal's identity).

$$C_n^m = C_{n-1}^m+C_{n-1}^{m-1}$$

(2)

for any natural $n, m$.

⟦folio 19⟧

Proof. By definition, $C_n^m$ is the coefficient of $x^m$ in the polynomial $(1+x)^n$. In order to find this coefficient, you need to multiply $n$ polynomials equal to $1+x$. Multiplying $n-1$ of them, we obtain the polynomial $1+C_{n-1}^1x + C_{n-1}^2x^2 + \dots + x^{n-1}$. Performing the last multiplication, we get

$$(1+x)(1+C_{n-1}^1x + C_{n-1}^2x^2 + \dots + x^{n-1}) = 1 + C_{n-1}^1x + C_{n-1}^2x^2 + \dots + x^{n-1} + x + C_{n-1}^1x^2 + C_{n-1}^2x^3 + \dots + x^n = 1 + (C_{n-1}^1 + 1)x + (C_{n-1}^2 + C_{n-1}^1)x^2 + \dots + x^n.$$

In the resulting expression, the coefficient of $x^m$ is equal to $C_{n-1}^m + C_{n-1}^{m-1}$. Thus,

$$C_n^m = C_{n-1}^m + C_{n-1}^{m-1}.$$

Pascal's identity is convenient to use to calculate biomial coefficients. For example, if we want to add one more line (eleventh) to our table, then we just need to add in pairs the numbers next to each other in the previous (tenth) line:

$$C_{11}^0 = 1 \quad C_{11}^1 = C_{10}^1 + C_{10}^0 = 11 \quad C_{11}^2 = C_{10}^2 + C_{10}^1 = 55 \quad C_{11}^3 = C_{10}^3 + C_{10}^2 = 165 \quad C_{11}^4 = C_{10}^4 + C_{10}^3 = 330 \quad C_{11}^5 = C_{10}^5 + C_{10}^4 = 462$$

This shows that it is convenient to write biomial coefficients in the form of a triangular table (see

3*

⟦folio 20⟧

Thus, formula (3) holds for $n=1$, and from its validity for $n-1$ it follows that it is true for $n$. This proves formula (3) for any $n$.

We recommend that the reader, having become acquainted with formula (3) for the first time, deduce from it the already known equalities $C_n^0 = C_n^n = 1$ and $C_n^m = 0$ for $m>n$.

Formula (3) is interesting because the fraction on its right side is equal to a whole number, that is, all the numbers in its denominator will cancel with the numbers in the numerator.

The following theorem will be used further.

Theorem 3. If the numbers $n$ and $m$ are coprime (that is, the greatest common divisor of the numbers $n$ and $m$ is 1), then $C_n^m$ is divisible by $n$.

Proof:

$$C_n^m = \frac{n(n-1)\ldots(n-m+1)}{1\cdot2\ldots m} = \frac{n}{m} \cdot \frac{(n-1)\ldots(n-m+1)}{1\cdot2\ldots(m-1)} = \frac{n}{m} \cdot C_{n-1}^m$$

Thus,

$$mC_n^m = nC_{n-1}^m$$

i.e. the number $mC_n^m$ is divisible by $n$. But since $m$ and $n$ are coprime, i.e. $m$ is not divisible by any prime divisor of $n$, then $C_n^m$ is divisible by $n$.

For example, $C_9^4 = 126$ is divisible by 9, $C_{10}^3 = 120$ is divisible by 10.

Let us indicate a few more properties of biomial coefficients:

1. $C_n^m = C_{n-1}^m$
2. $C_n^m + C_{n+1}^m + \ldots + C_{m+k}^m = C_{m+k+1}^m$
3. $C_n^0 + C_n^1 + \ldots + C_n^n = 2^n$
4. $C_n^0 + C_n^2 + C_n^4 + \ldots = C_n^1 + C_n^3 + C_n^5 + \ldots$

We leave the proof of these properties to the reader.

§ 2. Residues from dividing biomial coefficients by prime numbers

In this (and in the next) paragraph we will often have to use the form “the numbers $a$ and $b$ have equal remainders when divided by $p$”. Generally, this form is replaced by the abbreviated notation "$a \equiv b$ (mod $p$)". In other words, the formula “$a \equiv b$ (mod $p$)” means that $a-b$ is divisible by $p$. For example, $4 \equiv 1$ (mod 3), $999999 \equiv 222222$ (mod 7), etc. The formula “$a \equiv b$ (mod $p$)” is sometimes read like this: “the number $a$ is comparable to the number $b$ modulo $p$” (however, we will not use expressions either).

Here are two very properties of the symbol ≡:

1. If $a \equiv b$ (mod $p$) and $k$ are integers, then $ka \equiv kb$ (mod $p$).

Indeed, if $a-b$ is divisible by $p$, then $ka-kb = k(a-b)$ is also divisible by $p$.

2. If $a \equiv b$ (mod $p$) and $b \equiv c$ (mod $p$), then $a \equiv c$ (mod $p$).

Indeed, if $a-b$ is divisible by $p$ and $b-c$ is divisible by $p$, then $a-c = (a-b)+(b-c)$ is also divisible by $p$.

Let us recall that any natural number $a$ can be divided by a natural number $p$ “with a remainder”, i.e. $a$ can be uniquely written in the form $a=bp+c$, where $b$, $c$ are integers such that $0 \leq c < p$.

The main goal of this section is to prove the following statement.

Theorem 4. Let $p$ be a prime number, $m$ and $n$ be natural numbers. Let, further, $k$ and $l$ be the partials of dividing the numbers $m$ and $n$ by $p$, and $s$ and $t$ be the remainders (i.e. $m=kp+s$, $n=lp+t$, where $k$, $l$, $s$, $t$ are integers and $0 \leq s < p$, $0 \leq t < p$). Then

$$C_n^* = C_l^* \cdot C_s^* \pmod p.$$

As we will see below, this theorem allows us to find remainders from dividing biomial coefficients by prime numbers, almost without performing any calculations.

⟦folio 23⟧

in such a way that $C_{119}^{33} \equiv 0$ (mod 3), i.e. $C_{119}^{33}$ is divisible by 3 without remainder.

Note that if we apply our Theorem 4 to $C_n^m$, where $n \geq m$, then by writing $m = kp + s$, $n = lp + t$ we will of course have $l \geq k$; however, it is impossible to predict which of the numbers $s$, $t$ will be larger. If there is $s > t$, then according to our theorem $C_n^m \equiv C_l^k C_s^t = 0$ (mod $p$), i.e. $C_n^m$ is divisible by $p$. As we have seen, to determine the remainder when dividing the number $C_n^m$ by $p$ one usually comes to use Theorem 4 several times; and every time a phenomenon similar to that described above can occur, and whenever this happens, this means that a similar number $C_n^m$ is divisible by $p$. Similarly, we got that $C_{119}^{33}$ is divisible by 3.

We see that the larger $n$, the more likely the number $C_n^m$ is divisible by $p$. It is easy to prove the following, more precise statement: the total number of numbers $C_n^m$ with $0 \leq n \leq p^r$, $0 \leq m \leq n$ there are $\frac{p^r (p^r + 1)}{2}$, of which is not divisible by $p$ exactly $\frac{p^r (p + 1)^r}{2^r}$ (here $p$ is simple, $r$ natural; the proof is based only on Theorem 3, we leave it to the reader). It is emphasized that for large $r$ the number $\frac{p^r (p + 1)^r}{2^r}$ is many times smaller than the number $\frac{p^r (p^r + 1)}{2}$.

So, for example, of the numbers $C_n^m$ with $0 \leq n \leq 3^5$, $0 \leq m \leq n$ approximately 26.2% are not divisible by 3; if $0 \leq n \leq 3^{10}$, then approximately 3.6%, and if $0 \leq n \leq 3^{15}$, then approximately 0.45%.

In conclusion, let’s say a few words about the weight of the visual interpretation of Theorem 4, which can be obtained by considering the so-called “Pascal’s triangle according to the $p$ model”. This is the name of the triangular table that will be obtained from Pascal’s triangle if each number in it is replaced by its remainder when divided by $p$. We do not prove any theorems about this triangle, but we invite the reader to look at two pictures (on the cover and on page 22) that depict Pascal’s triangles modulo 2 and 3. Think about how these triangles are arranged in the part that is not visible on figure. Try to formulate Theorem 4 in such a way that it becomes a theorem about the structure of Pascal's triangle modulo $p$.

§ 3. A little about remainders from dividing biomial coefficients by powers of prime numbers

We do not consider in any general way the question of remainders from dividing biomial coefficients into composite numbers. (However, the reader can think about this for himself; what, for example, is the remainder of dividing the number $C_{119}^{33}$ by 4: one or trem?) We will limit ourselves to talking about one amazing phenomenon that has not been fully explained by us.

Let's start with some calculations. Using the formula for biomial coefficients (see § 1, formula (2)), we obtain

$$C_2^1 = 2,$$
$$C_4^2 = 6,$$
$$C_8^4 = 70,$$
$$C_{16}^8 = 12870,$$
$$C_{32}^16 = 601080390.$$

(Everyone knows, of course, that 1, 2, 4, 8, 16, 32, ... are successive powers of two.) The resulting numbers themselves should not be used in any special way; their successive differences, however, reveal striking properties. Let's look at them:

$$6 - 2 = 4 = 2^2,$$
$$70 - 6 = 64 = 2^6,$$
$$12870 - 70 = 12800 = 2^9 \cdot 25,$$

⟦folio 24⟧

---
running_head:
folio:
---

$$601\ 080\ 390 - 12\ 870 = 601\ 067\ 520 = 2^{12} \cdot 146\ 745.$$

We see that these differences are divided into high powers of two - so large that this phenomenon does not cause harm. It is possible to prove a theorem that explains it at least partially.

Theorem 5. If $n > 1$, then the number
$$\alpha_n = C_{2n+1}^{2n} - C_{2n}^{2n-1}$$
is divisible by $2^{2n+2}$.

Sweeping.
1°. The assumption that $n > 1$ is significant since $\alpha_1$ is equal to 4 and is not divisible by $2^{2n+2} = 2^4 = 16$.
2°. One might expect that $\alpha_n$ for $n > 1$ is even divisible by $2^{3n}$: this is true for $n = 2, 3, 4$. But we don’t know how to prove this.

Proof. Let's start with the general observation that if the number $r$ is odd, then $C_{2n}^{r}$ is divisible by $2^n$. In fact, since $r$ is odd, and $2^n$ has no prime divisors other than two, then the numbers $r$ and $2^n$ are coprime and the statement we need follows from Theorem 3.

Let us put the theory
$$P(x) = (1+x)^{2n+1} - (1-x^2)^{2n}.$$

The polynomial $P(x)$ contains $x^{2n}$ with coefficient $C_{2n+1}^{2n} - C_{2n}^{2n-1} = \alpha_n$ (here we use the fact that $n > 1$: when $(1-x^2) = 1 + (-x^2)$ appears to the power $2^n$, we obtain with coefficient $C_{2n}^{2n-1}$ not $x^{2n}$, but $(-x^2)^{2n-1} = (-1)^{2n-1}x^2^n$, while the number $(-1)^{2n-1}$ is 1 at $n > 1$ and equal to $-1$ at $n = 1$.

On the other side,
$$P(x) = (1+x)^{2n+1} - (1+x)^{2n} = (1+x)^{2n}[(1+x)^{2n} - (1-x)^{2n}].$$

At the same time
$$(1+x)^{2n} - (1-x)^{2n} = (1+x)^{2n} - (1+(-x))^{2n} = 1 + C_{2n}^{1}x + C_{2n}^{2}x^2 + C_{2n}^{3}x^3 + \dots + x^{2n} - 1 - C_{2n}^{1}(-x) - C_{2n}^{2}(-x)^2 - C_{2n}^{3}(-x)^3 - \dots - (-x)^{2n} =$$
(since $(-x)^k$ is equal to $x^k$ when $k$ is even and equal to $-x^k$ when $k$ is odd)
$$= 2\left(C_{2n}^{1}x + C_{2n}^{3}x^3 + C_{2n}^{5}x^5 + \dots + C_{2n}^{2n-1}x^{2n-1}\right).$$

We emphasize that the resulting polynomial $x$ appears only in odd powers.

We want to know with what coefficient $x^{2n}$ enters $P(x)$, i.e., into the product
$$(1+x)^{2n}[(1+x)^{2n} - (1-x)^{2n}] = 2\left(1 + C_{2n}^{1}x + C_{2n}^{2}x^2 + C_{2n}^{3}x^3 + \dots + x^{2n}\right) \times \left(C_{2n}^{1}x + C_{2n}^{3}x^3 + C_{2n}^{5}x^5 + \dots + C_{2n}^{2n-1}x^{2n-1}\right).$$

Obviously, $x^{2n}$ can be obtained by multiplying $x^{2n-1}$ from the first factor and $x$ from the second, by multiplying $x^{2n-3}$ from the second factor and $x^3$ from the second, etc. Thus, the coefficient in $P(x)$ for $x^{2n}$, equal, as we know, to $\alpha_n$, is also equal
$$2\left(C_{2n}^{1}C_{2n}^{2n-1} + C_{2n}^{3}C_{2n}^{2n-3} + \dots + C_{2n}^{2n-1}C_{2n}^{1}\right).$$

As we know, each of the numbers $C_{2n}^{1}, C_{2n}^{3}, \dots, C_{2n}^{2n-1}$ is divisible by $2^n$. Therefore, each term in brackets is divided by $2^n \cdot 2^n = 2^{2n}$; in addition, the two comes before the entire expression,

⟦folio 25⟧

and besides, each term in brackets occurs twice. Thus, $\alpha_n$ is divisible by $2^{2n+2}$, as required.

So, the strange phenomenon of divisibility of numbers $\alpha_n$ into high powers of two is to some extent explained. But nothing similar is observed if you replace the two with a three, five, seven. Really,

$$C_9^3 - C_3^1 = 84 - 3 = 81 = 3^4;$$

$$C_{27}^9 - C_9^3 = 4686825 - 84 = 4686741 = 3^7 \cdot 2143;$$

$$C_{81}^{27} - C_{27}^9 = 2306279447501851002720 - 4686825 = 2306279447501846315895 = 3^{10} \cdot 39057044954221855;$$

$$C_{25}^5 - C_5^1 = 43130 - 5 = 43125 = 5^5 \cdot 69;$$

$$C_{49}^7 - C_7^1 = 85900584 - 7 = 85900577 = 7^5 \cdot 5111.$$

In short, it seems to be true that for prime $p$ the number

$$C_{pn+1}^{p^n} - C_{pn}^{p^n-1}$$

is divisible by a high power of the number $p$. But we don’t know how to prove this.

By the way, if $p$ is not prime, then nothing like this is observed. For example,

$$C_{16}^4 - C_4^1 = 1820 - 4 = 1816$$

not even divisible by $4^2$;

$$C_{36}^6 - C_6^1 = 1947792 - 6 = 1947786$$

is not even divisible by $6^2$.

We believe that one of the readers of «Kvant» can understand this complex issue of biomial coefficient arithmetic.
