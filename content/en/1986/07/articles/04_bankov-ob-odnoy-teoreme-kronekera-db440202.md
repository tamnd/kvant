---
id: 1986-7-bankov-ob-odnoy-teoreme-kronekera-db440202
issue: kvant_1986_7
year: 1986
number: "7"
title: About one Kronecker theorem
authors:
  - Банков К. Г.
rubric: osnovnye-stati
page_first: 7
page_last: 9
page_labels: 5-7
tag: 57C8
lang: en
source: kvant_digital
extraction: vision
content_sha256: 2f1b215c0382daa91f715701ea25310fcee3a61a5727f4f3cc7b09bf44f31104
prompt_sha256: draft-1
translated_from: content/ru/1986/07/articles/04_bankov-ob-odnoy-teoreme-kronekera-db440202.md
source_content_sha256: 5fd8f7e68c8753d423f508c22b42d4ee9ccb69b8d06963a288d02f02ecf87577
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 5⟧

About one theorem
Kronecker

K. G. BANKOV (NRB)

The theorem discussed here plays a prominent role in number theory. However, it is interesting to us for another reason: with its help, it is possible to simply solve elementary formulated, but essentially difficult problems. Before presenting the theorem itself, we will consider two such problems.

Problem 1. Prove that there is a power of 2 whose decimal notation begins with the digits 1986.

To solve this problem, we need to find a degree $m \in N$ such that $10^n \cdot 1986 < 2^m < 10^n \cdot 1987$ for some $n$. Taking logarithms to base 10, we get

$$\lg 1986 + \lg 10^n < \lg 2 < \lg 1987 + \lg 10^n,$$

or

$$\lg 1986 < \lg 2 - n < \lg 1987.$$

The problem will be solved if we manage to find natural numbers $n$ and $m$ such that one of the numbers of the form

$$\lg 2 - n, m, n \in N$$

(1)

fell into a small interval (lg 1986, lg 1987).

Problem 2. At the vertices of an integer square grid there are drawn

identical small cats (Fig. 1). Prove that the ray $y = kx$, $x \geq 0$ will intersect, in addition to the central one, at least one more cat if the number $k$ is irrational.

Let $2\varepsilon_0$ be the “width of the cat”, in other words, let the central cat intersect the axis $Ox$ along the segment $[-\varepsilon_0; \varepsilon_0]$. To determine this, we assume that the beam is located in the first square (the remaining cases are similar). Then the ray intersects straight lines $y = 1, 2, \dots, n, \dots$ at points with abscissas $\alpha, 2\alpha, \dots, n\alpha, \dots$, where $\alpha = 1/k$. The problem will be solved if we find natural $n$ and $m$ such that

$$m - \varepsilon_0 < n\alpha < m + \varepsilon_0,$$

or

$$-\varepsilon_0 < n\alpha - m < \varepsilon_0,$$

⟦folio 6⟧

that is, we can establish that one of the numbers of the form
$$n\alpha - m, n, m \in \mathbb{N},$$
(2)
serves in a small interval $(-\varepsilon_0, \varepsilon_0)$.

The remarkable idea of ​​Kroneckar's theorem*) is that sets such as (1) and (2) contain numbers lying in any interval at all. To give a precise formulation of this theorem, we need one definition.

A number set $A \subset \mathbb{R}$ is said to be everywhere dense (in $\mathbb{R}$) if any interval contains an element of this set. In other words, $A$ is everywhere dense in $\mathbb{R}$ if for any numbers $x, y \in \mathbb{R}$, $x < y$ there exists $a \in A$ such that $x < a < y$.

Exercise
1. Indicate which of the following sets are everywhere dense in $\mathbb{R}$: a) all rational numbers; b) all irrational numbers; c) all numbers of the form $n + 5m/17$ ($n, m \in \mathbb{Z}$); d) all numbers of the form $n + k/m$ ($n, k, m \in \mathbb{Z}$).
2. Let the set $A$ be everywhere dense in $\mathbb{R}$ and $r \neq 0$ a real number. Prove that then the sets
$$B = \{a + r; a \in A\}, C = \{ra, a \in A\}$$
the same is everywhere dense in $\mathbb{R}$.

**Kronekar's theorem.** For an arbitrary irrational number $a \neq 0$ the set
$$\{m\alpha + n; m, n \in \mathbb{Z}\}$$
(3) dense everywhere in $\mathbb{R}$.

Proof. We need to establish that for any two numbers $x, y$ for which $x < y$, there exist numbers of the form $m\alpha + n$, where $m, n \in \mathbb{Z}$ is such that $x < m\alpha + n < y$. Let us denote by $\delta$ the length of the interval $\Delta = (x; y)$ and divide the interval [0; 1] into a finite number of intervals $\Delta_1, \Delta_2, \dots, \Delta_n$, each of which has a length less than $\delta$. Let us now note that for any integer $m$, very large, there is an integer $n$ for which the number $m\alpha + n$ lies on the interval [0; 1]. Since there are infinitely many integers, and the segment [0; 1] is divided into a finite number of intervals, there are integers $m_1, m_2, n_1, n_2$ for which $m_1 \neq m_2$ and the numbers $m_1\alpha + n_1$ and $m_2\alpha + n_2$ lie in the same interval $\Delta_i$. This means that the number $a = (m_1 - m_2)\alpha + (n_1 - n_2)$ is smaller in abscylotic value than $\delta$. Moreover, the equality $a = 0$ cannot be true because it implies that $a = \frac{n_2 - n_1}{m_1 - m_2}$ is a rational number. From the above it follows that some multiple of $a$, which also has the form $m\alpha + n$, not an integer, will belong to $\Delta = (x; y)$; the theorem is proven.

Comment. The theorem remains true if set (3) is replaced by the set
$$\{m\alpha - n; m, n \in \mathbb{N}\}.$$

This is easily deduced from the proven theorem; we leave the conclusion as an exercise to the reader.

Returning now to the set (1) and (2), we see that they satisfy the conditions of the theorem: problems 1 and 2 are thereby solved. (We consider it known that the number lg 2 is irrational; however, this is not difficult to prove.)

Exercise 3. Show that in the cat problem the irrationality condition $k$ cannot be omitted.

Let's consider a few more problems whose solutions use Kroneckar's theorem.

Problem 3. Prove that there is a square of a natural number whose descriptive notation begins with any predetermined digits.

Solution. Let's find the square of a natural number whose first decimal digits are $-a_0a_1...a_s$. Let us denote by $A$ the number $A = a_0a_1...a_s$. We will now look for a natural number $n$ such that for some natural number $k$ the inequalities are true
$$A \cdot 10^k < n^2 < (A + 1) \cdot 10^k,$$
or lg $A < 2\lg n - k < \lg (A + 1)$.
If we choose the number $n$ to be equal to $n = 2^m$, and the number $k$ to be even, $k = 2t$, then lg $A < 2mlg 2 - 2t < \lg (A + 1)$. (5)

According to the theorem, substitution (see (4)) and Exercise 2, the set
$$\{2mlg 2 - 2t; m, t \in \mathbb{N}\}$$ is everywhere dense, and therefore there are numbers $m$ and $t$ for which (5) is true. Problem solution.

To solve the following problems we also need the following statement:

Lemma. If two continuous functions take the same values ​​when the arguments are elements of the same everywhere dense set, then they coincide everywhere.

This lemma is "geometrical"; its formulaic proof is unattractive (although not difficult), so we do not present it.

Problem 4. Prove that the function
$$f(x) = \sin x + \sin \pi x$$
non-veroid.

Solution. Let us assume that the function $f$ is nonveroidal, and denote by $T \neq 0$ one of

⟦folio 7⟧

ee periods. Then equality
$$\sin \pi(x+T) + \sin \pi\sqrt{2}(x+T) = \sin \pi x + \sin \pi\sqrt{2}x$$
(6)
true for any real number $x$. If in this equality we replace $x$ with an arbitrary fourREM number $2m$, we get
$$\sin \pi T + \sin \pi\sqrt{2}(2m+T) = \sin (\pi\sqrt{2} \cdot 2m).$$
Using again the periodicity of the functions sin, we obtain the equality
$$\sin \pi T + \sin \pi\sqrt{2}\left(2m + \frac{2n}{\sqrt{2}} + T\right) = \sin \pi\sqrt{2}\left(2m + \frac{2n}{\sqrt{2}}\right),$$
which is true for any two integers $m$ and $n$. According to the theorem of Exercise 2, the set
$$\left\{ 2m + \frac{2n}{\sqrt{2}}; m, n \text{ — целые числа} \right\}$$
is apparently dense. This means that the function $\sin \pi T + \sin \pi\sqrt{2}(x+T)$ and sin $\pi\sqrt{2}x$ take the same values ​​when their arguments are elements of the same dense set and, therefore (by the lemma), coincide in every way, that is, the equality
$$\sin \pi T + \sin \pi\sqrt{2}(x+T) = \sin \pi\sqrt{2}x$$
(7)
true for any real number $x$. Subtracting (7) from (6), we get
$$\sin \pi(x+T) \sin \pi T = \sin \pi x.$$
In the last equality we put $x = T$; we get
$$\sin 2\pi T - \sin \pi T = \sin \pi T,$$
or
$$\sin \pi T(\cos \pi T - 1) = 0.$$
From the last equality it follows that $T$ is an integer. Then from (7) it follows
$$\sin \pi\sqrt{2}(x+T) - \sin \pi\sqrt{2}x = 0,$$
or
$$\sin \pi\sqrt{2}\frac{T}{2}\cos \pi\sqrt{2}\left(x + \frac{T}{2}\right) = 0.$$
Since there are values ​​of $x$ for which
$$\cos \pi\sqrt{2}\left(x + \frac{T}{2}\right) \neq 0,$$ then $\sin \pi\sqrt{2}\frac{T}{2} = 0$; it follows that $\sqrt{2}\frac{T}{2}$ is an integer. But, on the other hand, $T$ is also an integer and $T \neq 0$, which means $\sqrt{2}$ is a rational number, which is false. The resulting contradiction proves that the function $f$ is non-periodic.

Here is another task related to the functions discussed above.
Problem 5. Prove that the function
$$f(x) = \sin \pi x + \sin \pi\sqrt{2}x$$
cannot take the value 2, but takes values ​​as close as possible to the number 2.
Solution. If we assume that $f(x) = 2$ for some $x$, then the simultaneous equality will hold
$$\sin \pi x = 1$$ and $\sin \pi\sqrt{2}x = 1$, whence it is not represented that the number $\sqrt{2}$ is rational, but this is false. Therefore, $f(x) < 2$ for any number.
If $x$ is an arbitrary number of the form $2m + \frac{1}{2}$, where $m$ is an integer, the function $f$ takes the form
$$f(x) = 1 + \sin \pi\sqrt{2}\left(2m + \frac{1}{2}\right).$$
Let us show that it is possible to find an integer $m$ for which
$$\sin \pi\sqrt{2}\left(2m + \frac{1}{2}\right)$$ is arbitrarily close to the number 1. Bearing in mind the continuity of the function sin, it is sufficient to find integers $m$ and $n$ such that the number $\sqrt{2}\left(2m + \frac{1}{2}\right)$ is arbitrarily close to the number $2n + \frac{1}{2}$. Therefore, it is sufficient to prove that for any positive $\varepsilon$ there are integers $m$ and $n$ for which
$$2n + \frac{1}{2} - \varepsilon < \sqrt{2}\left(2m + \frac{1}{2}\right) < 2n + \frac{1}{2} + \varepsilon.$$
Let us transform the last integer inequalities to the form
$$1 - 2\varepsilon - \sqrt{2} < 4m\sqrt{2} - 4n < 1 + 2\varepsilon - \sqrt{2}.$$
Now we all follow from the theorem and Exercise 2.
Problem 6. Find all continuous real functions $f$ for which $f(x) = f(x+1) = f(x+\sqrt{2})$.
Solution. Let $f$ be a continuous function for which $f(x) = f(x+1) = f(x+\sqrt{2})$. This means that the numbers 1 and $\sqrt{2}$ are periods of the functions $f$. Then the period of the function $f$ is also all numbers of the form $m + n\sqrt{2}$, where $m$ and $n$ are integers, that is, for any two integers $m$ and $n$ the equality $f(x + m + n\sqrt{2}) = f(x)$ is true. The last equality means that $f(x + y)$ and $f(x)$ take the same values ​​when $y$ belongs to a flat multi-check
$$\{m + n\sqrt{2}; m, n \text{ — целые числа}\}.$$
Then, according to the lemma, we obtain that the equality $f(x + y) = f(x)$ is true for every number $y$, that is, every (real) number is a period of the functions $f$. Now, if $x_1$ and $x_2$ are two different numbers, we put $y = x_2 - x_1$, and then
$$f(x_1) = f(x_1 + (x_2 - x_1)) = f(x_2).$$
Therefore, the solution to Problem 6 will be all functions of the form $f(x) = a$, where $a$ is a constant.
