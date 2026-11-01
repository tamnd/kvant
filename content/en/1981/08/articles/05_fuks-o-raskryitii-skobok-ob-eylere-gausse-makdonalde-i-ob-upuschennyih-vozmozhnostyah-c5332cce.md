---
id: 1981-8-fuks-o-raskryitii-skobok-ob-eylere-gausse-makdonalde-i-ob-upuschennyih-vozmozhnostyah-c5332cce
issue: kvant_1981_8
year: 1981
number: "8"
title: About opening parentheses, about Euler, Gauss, Macdonald and missed opportunities
authors:
  - Фукс Д. Б.
rubric: osnovnye-stati
page_first: 14
page_last: 19
page_labels: 12-17
tag: AIB9
lang: en
source: kvant_digital
extraction: vision
content_sha256: 604f1a0d2009052d89cde3bb3885ec682af02c092c5034362b43f0fef3a46e87
prompt_sha256: draft-1
translated_from: content/ru/1981/08/articles/05_fuks-o-raskryitii-skobok-ob-eylere-gausse-makdonalde-i-ob-upuschennyih-vozmozhnostyah-c5332cce.md
source_content_sha256: b757a9cbbc511e2cbade9b3169d3898bf25e65068795e425b7075c164815f178
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 12⟧

D. Fuchs

About opening parentheses
about Euler, Gauss, Macdonald
and about missed opportunities

How many times have each of you had to open brackets in a work? Thousands, or maybe ten thousand? If there is anything attractive in this activity, it is the hope that the result of multiplication, after adding similar terms, will take a favorable form, like, say,

$$\begin{align*}
(a+b) (a-b) &= a^2 - b^2, \\
(1-a) (1+a + \dots + a^n) &= 1 - a^{n+1}.
\end{align*}$$

Below we will talk about similar equalities, only much less extreme and much more profound. They are the result of more than two centuries of work by the world's leading mathematicians. I advise my readers to arm themselves with a pen and paper and repeat all the calculations after me: this will help not only understand the content of the article, but also evaluate the degree of non-triviality of its results.

1. Euler's identity

In the middle of the 18th century - it was in 1748 or several years earlier - Leonhard Euler became interested in the coefficients of the polynomial

$$\varphi_n(x) = (1-x) (1-x^2) (1-x^3) \dots (1-x^n).$$

He opened the brackets in the work - and received a shocking re-

⟦folio 13⟧

Result. Let's do this calculation too:

$$\varphi_1(x) = 1 - x,$$
$$\varphi_2(x) = 1 - x - x^2 + x^3,$$
$$\varphi_3(x) = 1 - x - x^2 + x^4 + x^5 - x^6,$$
$$\varphi_4(x) = 1 - x - x^2 + 2x^5 - x^8 - x^9 + x^{10},$$
$$\varphi_5(x) = 1 - x - x^2 + x^5 + x^6 + x^7 - x^8 - x^9 - x^{10} \dots,$$
$$\varphi_6(x) = 1 - x - x^2 + x^5 + 2x^7 - x^9 - x^{10} \dots,$$
$$\varphi_7(x) = 1 - x - x^2 + x^5 + x^7 + x^8 - x^{10} \dots,$$
$$\varphi_8(x) = 1 - x - x^2 + x^5 + x^7 + x^9 \dots,$$
$$\varphi_9(x) = 1 - x - x^2 + x^5 + x^7 + x^{10} \dots,$$
$$\varphi_{10}(x) = 1 - x - x^2 + x^5 + x^7 \dots$$

Multi-point denote parts of the polynomials $\varphi_n(x)$ containing $x$ to a degree greater than 10 (the journal format does not allow these polynomials to be written out completely: the polynomial $\varphi_{10}(x)$, for example, has a degree of 55).

Let's start with another but important observation: the coefficients of the polynomial $\varphi_n(x)$ “stabilize” as $n$ increases, that is, each of them does not change starting from some $n$. This is easily obligatory: the transition from $\varphi_{n-1}(x)$ to $\varphi_n(x)$, consisting of multiplication by $1 - x^n$, has no effect on the coefficients of $1, x, \dots, x^{n-1}$, so that at $n > k$ the coefficient of $x^k$ in the polynomial $\varphi_n(x)$ does not depend on $n$. (For example, the calculations of the polynomial $\varphi_{10}(x)$ will not change if instead of $\varphi_{10}$ we take $\varphi_{11}, \varphi_{12}$, etc.) In view of this, we can talk about an “infinite product”

$$\varphi(x) = (1 - x)(1 - x^2)(1 - x^3)(1 - x^4) \dots,$$

The concept behind this, of course, is not a polynomial, but a “power series,” that is, an expression of the form

$$a_0 + a_1x + a_2x^2 + a_3x^3 + a_4x^4 + \dots,$$

where $a_0, a_1, a_2, a_3, a_4 \dots$ are numbers; in our case, $a_0, a_1, a_2, a_3, a_4$ are stabilizing coefficients. Our calculation shows that

$$a_0 = a_5 = a_7 = 1,$$
$$a_1 = a_2 = -1,$$
$$a_3 = a_4 = a_6 = a_8 = a_9 = a_{10} = 0.$$

$\varphi(x)$ is called the Euler function.

The word “function” is not used here by chance: for $-1 < x < 1$ the values ​​of $\varphi(x)$ can be calculated (similar to how the sum of an infinite geometric progression is calculated).

Now is the main thing. After opening our brackets, a lot is destroyed, one might say almost everything. For example, the result of opening the parentheses in the product $(1 - x)(1 - x^2) \dots (1 - x^{10})$ contains, before the reduction of similar ones, 43 terms with $x$ to powers less than or equal to 10, including 24 terms with $x$ to the powers of 8, 9, 10. After reduction of similar ones, only 5 of these 43 terms remain, including none with $x$ to the power of 8, 9; 10. More precisely, as we have seen, among the coefficients $a_0, a_1, a_2, \dots, a_{10}$ three are equal to 1, two are equal to -1 and six are equal to 0. Let us make a cautious hypothesis: the coefficients $a_k$ are always equal to 0, 1 or -1, and most of them are equal to 0. Further calculation, which the reader can check for himself if he wishes, not only confirms this hypothesis, but also allows us to clarify it. Here, for example, is a part of the series $\varphi(x)$ containing $x$ to powers not exceeding 100:

$$\varphi(x) = 1 - x - x^2 + x^5 + x^7 - x^{12} - x^{15} + x^{22} + x^{26} -$$
$$- x^{35} - x^{40} + x^{51} + x^{57} - x^{70} - x^{77} + x^{92} + x^{100} \dots$$

It must be assumed that Euler, who was not afraid of long calculations and was excellent at calculations, calculated approximately the same number of terms of the series $\varphi(x)$. And then he simply could not help but notice that the coefficients other than 0 were equal to 1 or -1, and at the same time they placed ones and minus ones.

⟦folio 14⟧

The wives are not haphazard, but in a strictly defined order: two units, two minutes one, two minutes one, etc. *). The table contains exponents of power $x$, at which there are non-zero coefficients.

It is easy to guess what these indicators are: in the $n$th column of our table, the top line contains the number $\frac{3n^2 \pm n}{2}$, and the bottom line contains the number $(-1)^n$. If this is true for all $n$, we arrive at the equality

$$(1-x)(1-x^2)(1-x^3) \ldots = 1-x-x^2+x^5+x^7 \ldots +(-1)^n x^{\frac{3n^2-n}{2}} + (-1)^n x^{\frac{3n^2+n}{2}} + \ldots$$

or, use the abbreviated symbol used in mathematics,

$$\prod_{n=1}^{\infty} (1-x^n) = 1 + \sum_{n=1}^{\infty} (-1)^n \left( x^{\frac{3n^2-n}{2}} + x^{\frac{3n^2+n}{2}} \right).$$

This is Euler's identity. The subsequent testimony of mathematicians provides several proofs of this identity. However, some of them are given in paragraph 3. (A reader who is more interested in facts than in proofs can skip this paragraph without training to understand further.) And now I will talk about one remarkable application of Euler’s identity, which adorns all combinatorics textbooks.

2. Euler's identity and the number of partitions

Let $n$ be a natural number. Let us denote by $p(n)$ the number of ways that $n$ can be represented as a sum of natural terms (in this case, the terms in the sums can be repeated, and representations that differ only in the order of the terms are considered the same).

For example:

$$p(1) = 1;$$
$$p(2) = 2 \quad (2=2; 2=1+1);$$
$$p(3) = 3 \quad (3=3; 3=2+1; 3=1+1+1);$$
$$p(4) = 5 \quad (4; 3+1; 2+2; 2+1+1; 1+1+1+1);$$
$$p(5) = 7 \quad (5; 4+1; 3+2; 3+1+1; 2+2+1; 2+1+1+1+1).$$

The numbers $p(n)$ appear in many mathematical formulas and are useful to reduce. But how to do this? Try, for example, finding $p(10)$. You'll have to do a fair bit of tinkering, and if you're lucky, you'll find the correct answer: 42. What if you need to know, say, $p(50)$? Euler's identity comes to the rescue.

*) Euler’s memoir on this topic is given in full in the book by D. Poya “Matematika and plausible reasoning” (M., “Nauka”, 1975, p. 111). Reading this topic, as well as other chapters of Polya's books, will undoubtedly give you more comfort.

⟦folio 15⟧

First, a little “theory”. Let's put
$$\pi(x) = 1 + p(1)x + p(2)x^2 + p(3)x^3 + \dots = 1 + x + 2x^2 + 3x^3 + 5x^4 + 7x^5 + \dots$$

Like $\varphi(x)$, $\pi(x)$ is a function defining at $-1 < x < 1$. But, again, we are only interested in it as a power series.

Theorem. The series $\varphi(x)$ and $\pi(x)$ are mutually inverse, that is
$$\varphi(x) \cdot \pi(x) = 1.$$

Do you understand what is the meaning of this equality? Power series can be multiplied:
$$(a_0 + a_1x + a_2x^2 + \dots) (b_0 + b_1x + b_2x^2 + \dots) = a_0b_0 + a_0b_1x + a_0b_2x^2 + \dots$$
$$+ a_1b_0x + a_1b_1x^2 + a_1b_2x^3 + \dots + a_2b_0x^2 + a_2b_1x^3 + a_2b_2x^4 + \dots$$
$$= a_0b_0 + (a_0b_1 + a_1b_0)x + (a_0b_2 + a_1b_1 + a_2b_0)x^2 + \dots;$$

our statement means that if we multiply the series $\varphi(x)$ and $\pi(x)$ in this way, then the resulting product will be reduced to 1: the coefficients of $x, x^2, x^3, \dots$ will be equal to zero.

Proof.
$$\frac{1}{\varphi(x)} = \frac{1}{1-x} \cdot \frac{1}{1-x^2} \cdot \dots \cdot \frac{1}{1-x^k} \cdot \dots =$$
$$= (1+x+x^2+x^3+\dots) (1+x^2+x^4+x^6+\dots) \times \dots$$
$$\dots \times (1+x^k+x^{2k}+x^{3k}+\dots) \dots$$

When opening the brackets in the last product, we get the sum of all possible expressions of the form
$$x^{a_1}x^{2a_2} \dots x^{ka_k},$$

where $a_1, \dots, a_k$ are non-negative integers. Thus, $x^n$ will be included in this sum as many times as in how many ways $n$ can be represented as
$$a_1 + 2a_2 + \dots + ka_k.$$

But this representation can be rewritten like this:
$$\underbrace{1 + \dots + 1}_{a_1} + \underbrace{2 + \dots + 2}_{a_2} + \underbrace{k + \dots + k}_{a_k}.$$

We see that the number $n$ represented in the form of $a_1 + 2a_2 + \dots + ka_k$ is the same as its represented as the sum of natural terms, that is, $p(n)$. Thus, the coefficient of $x^n$ in our product is equal to $p(n)$, that is, $\frac{1}{\varphi(x)} = \pi(x)$. The theorem has been proven.

Putting $p(0) = 1$ for convenience, we write
$$(1-x-x^2+x^5+x^7-\dots) (p(0) + p(1)x + p(2)x^2 + \dots) = 1$$

(coefficients in the first factor are written according to Euler's theodest!). Let's open the brackets and set the coefficients of $x, x^2, x^3, \dots, x^n$ on the left side equal to zero. We get:
$$p(1) - p(0) = 0;$$
$$p(2) - p(1) - p(0) = 0;$$
$$p(3) - p(2) - p(1) = 0;$$
$$p(n) - p(n-1) - p(n-2) + p(n-5) + p(n-7) - \dots = 0$$

(on the left side of the last formula you need to write terms as long as the argument y p remains non-negative). So,
$$p(n) = p(n-1) + p(n-2) - p(n-5) - p(n-7) + \dots$$

This formula allows you to quickly create a fairly long table of numbers $p(n)$. Here's practical advice on how to do it. Take a sheet of checkered paper - a double terrader sheet is best. Cut a strip 3-4 squares wide along its length side. Place this strip vertically in front of you and put some sign, say an asterisk, in the bottom cell. Then, marveling upward,

⟦folio 16⟧

put + in the first cell, + in the second, - in the fifth, - in the seventh, + in the twelfth, + in the fifteenth, etc., as long as the length of the strip is sufficient (Fig. 1). Place the remaining part of the sheet vertically in front of you and, 10-15 cells away from its left side, draw a vertical line on it - from top to bottom. In the cells adjacent to the line on the left, marveling from top to bottom, write down the numbers $p(n)$ already known to you, starting with $p(0)$: 1, 1, 2, 3, 5, 7. To find the next value, attach the cut strip to the right to the vertical line so that the asterisk is opposite the first empty cell. Now, from the sum of the numbers opposite the flats, write down the sum of the numbers opposite the negatives. Write what happens in the cell opposite the asterisk: this is the next value of the function $p(n)$. Lower the strip one square down and repeat the same thing. And so on. In a few minutes you will have a column of numbers $p(n)$ as tall as your sheet.

Using this sieve, I found the numbers $p(n)$ for $n \leq 50$. This took - purely, according to the clock - 17 minutes. (I give the first few steps of the calculation for figure 2; the red numbers are the new values ​​of $p(n)$.) In particular,

$$p(50) = 204226.$$

Imagine how much time it would take to find this number using a homemade method!

3. Proof of the Euler point

Let's open the brackets in our work

$$(1-x)(1-x^2)(1-x^3)(1-x^4)$$

The result is a sum (infinite) in which $x^n$ appears as many times as in the number of ways $n$ is represented as the sum of a regenerating sequence of natural numbers: $n=n_1+n_2+\dots+n_k$, $n_1<n_2<\dots<n_k$; in this case, the sign at $x^n$ will be + if $k$ is even, and - if $k$ is odd. Below in this section, the set 们 $(n_1, \dots, n_k)$ with $n_1+\dots+n_k=n$ and $n_1<\dots<n_k$ are simply called “partitions”.

We will distinguish between three types of partitions. For the partition $(n_1, \dots, n_k)$, let us denote by $s$ the most number such that $n_k-n_k-s+1=s-1$, that is, $s$ of numbers $n_k-s+1, \dots, n_k$ are in a row (obviously, $s \leq k$). For example, for the partition $12=2+4+6$ $s=1$, for the partition $12=1+5+6$ $s=2$, for the partition $33=4+5+7+8+9$ $s=3$. We will say that the partition $(n_1, \dots, n_k)$ takes

*first type*, if $n_1 \leq s$, excluding the case of $n_1=s=k$;
*second type*, if $n_1>s$, excluding the case of $n_1=s+1$, $s=k$;
*third type* in exceptional cases, that is, if $s=k$ and $n_1$ are equal to $s$ or $s+1$.

Let us now associate the partition $(n_1, \dots, n_k)$ of the first type of partition

$$\begin{cases}
(n_2, \dots, n_k-n_1, n_k-n_1+1+1, \dots, n_k+1), \text{ если } k-n_1 \geq 2, \\
(n_2+1, \dots, n_k+1), \text{ если } k-n_1=1,
\end{cases}$$

which belongs, very much, to the second type (check!)

⟦folio 17⟧

Fig. 2

Moreover, in this way a one-to-one correspondence is obtained between partitions of the first and second type: the inverse mapping matches the partition $(n_1, \dots, n_k)$ of the second type with the partition
$$\begin{cases}
(s, n_1, \dots, n_{k-s}, n_{k-s+1}-1, \dots, n_k-1), \text{ если } k-s \geqslant 1, \\
(s, n_1-1, \dots, n_k-1), \text{ если } k-s=0
\end{cases}$$

(the designation $s$ retains the same meaning), belongs to the first type (check!). Since our connection correspondence gives partitions in which the numbers of terms differ by 1, the corresponding partitions $x^n$ are destroyed, and only terms corresponding to partitions of the third type remain in our sum. And partitions of this type, by definition, have the form
$$\begin{align*}
(k, k+1, \dots, 2k-1), \\
(k+1, k+2, \dots, 2k),
\end{align*}
$$
and they correspond to $(-1)^k x^{\frac{3k^2-k}{2}}, (-1)^k x^{\frac{3k^2+k}{2}}$ (as you know, $k+(k+1)+\dots+(2k-1)=\frac{3k^2-k}{2}$ and $(k+1)+(k+2)+\dots+2k=\frac{3k^2+k}{2}$).

The proof is over.

4. Gauss identity

Some 70 years had passed since Euler's discovery, and another great mathematician, Carl-Friedrich Gauss, took the next step with a better theory (for reasons we won't go into) called the theory of modular forms. He discovered that if the Euler function was cubed, the result was a series perhaps even more remarkable than the Euler series:
$$\varphi(x)^3 = (1-x)^3(1-x^2)^3(1-x^3)^3\dots = 1-3x+5x^3-7x^6+9x^{10}-11x^{15}\dots$$
(I advise you not to be lazy and calculate as many coefficients of the series $\varphi(x)^3$ or
$$\prod_{n=1}^{\infty} (1-x^n)^3 = 1 + \sum_{n=1}^{\infty} (-1)^n (2n+1)x^{\frac{n(n+1)}{2}}.$$
This Gauss identity is all the more surprising since the square of the Euler function apparently does not apply:
$$\varphi(x)^2 = 1-2x-x^2+2x^3+x^4+2x^5-2x^6-2x^8-2x^9+x^{10}\dots$$
