---
id: 1990-5-shevelev-latinskie-pryamougolniki-1f85e4c6
issue: kvant_1990_5
year: 1990
number: "5"
title: Latin rectangles
authors:
  - Шевелёв В. С.
rubric: osnovnye-stati
page_first: 8
page_last: 11
page_labels: 6-9
lang: en
source: kvant_digital
extraction: vision
content_sha256: 5542b01c7d5ce07559dd75c130a12aeb073cb681bb80048a006cfddcbea06d76
prompt_sha256: draft-1
translated_from: content/ru/1990/05/articles/03_shevelev-latinskie-pryamougolniki-1f85e4c6.md
source_content_sha256: 9acee75f390098ce2277ff9b03514dc3122dbf3ac5b7187dc05e819ab4835c81
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 6⟧

---
running_head:
folio:
---

Candidate of Physical and Mathematical Sciences
V. SHEVELEV

What is this article about?
In this article we will talk about rectangles “populated” by various natural numbers. If you divide a rectangular block into $m \times n$ equal squares by straight lines, parallel to its bases, and “settle” in this $mn$-apartment $m$-storey “house” with $n$ “entrances” to each “apartment” one of the natural numbers 1, 2, ..., $n$, so that all the numbers on each “floor” and in each “entrance” were different, then we get a rectangular book, which mathematicians call “Latin”. In it, each of the numbers 1, 2, ..., $n$ is repeated $m$ times, i.e. “families” of ones, twos, threes, etc. occupy $m$ “apartments”, but always on different “floors” and in different “entrances”. Previously, letters of the Latin alphabet were “infused” into this “house” together with numbers, which is why they called it “Latin”.

There is a mathematical discipline concerned with counting the number of different sets and configurations. This science is called combinatorial.*) The task of listing Latin rectoliters also belongs to combinatorial

*) You can read about many interesting combinatorial problems in the wonderful book by N. Ya. Vilenkin “Popular Combinatorial Science” (M., Nauka, 1975).

⟦folio 7⟧

---
running_head:
folio:
---

binatorics. However, in general terms this task is extremely difficult. Despite the fact that it was studied by the greatest mathematicians, more than 200 years passed between counting the number of “two-story” and “three-story” rectangles, the first of which were first listed by the Frenchman Montmortz in 1713, and the second by the American mathematician Riordan just 40-odd years ago. In addition to the red explicit formulas of Montmore and Riordan, which we will discuss below, convenient recurrent formulas were also found for these rectangles by Euler (we will prove his formula) and the Indian Keravala. It is interesting that Keravala refuted the erroneous recurrent formulas of the English mathematician Jacob for the number of “three-story” Latin rectilinears that “lasted” for 12 years (from 1930 to 1941). Well, when solving difficult problems, this also happens in mathematics!

Existence of Latin Rectogols

Theorem 1. For any numbers $m \leqslant n$ there is a Latin $m \times n$-rectangle.

Proof. We will “populate” our $m$-storey “house” from the top floor. On the $m$th floor we will “settle” the numbers 1, 2, 3, ..., $n$ in their natural order. On the $(m-1)$ floor we will teach “settling” from twos: 2, 3, ..., $n,1$; on the $(m-2)$th floor - from three: 3, 4, ..., $n,1,2$, and so on; finally, on the 1st floor we will teach “settling” from the number $m: m, m+1, ..., n,1,2,..., m-1$. Then the “house” will be “populated” as it is done in the table. It is clear that with such “settlement” there are no two identical “tenants” on the same “floor” or in the same “entrance”. Consequently, we have before us an “m-storey” Latin rectangular with a length of $n$. This means that $m \times n$-rectangles exist.

Two floors

Let us now move on to counting the number of Latin rectangulars. The problem for unambiguous rectangles is especially easy to solve.

Theorem 2. The number of Latin $1 \times n$-rectangles is equal to $n! = 1 \cdot 2 \cdot ... \cdot n$.

Proof. A Latin $1 \times n$-rectangle is a simple arbitrary permutation of $n$ numbers. There are only $n!$ such permutations (any of the $n$ numbers was placed in the first place, any of the $n-1$ remaining numbers were placed in the second place, any of the $n-2$ numbers remaining after that were placed in the third place, etc.).

Let's move on to the $2 \times n$-rectangle. The top line of this rectangle is any permutation. The bottom line is a permutation in which each place has a number that is not equal to the number in the same place in the first permutation. If we arbitrarily rearrange the columns of our rectangle, it will remain Latin, and at the same time any upper rearrangement can be made. From this it is clear that no matter what specific permutation we take, the number of Latin rectagons whose top line coincides with this particular permutation will be the same for all permutations. Let us say that a Latin $2 \times n$-rectangle is normalized if its top line of numbers contains the order: 1, 2, 3, ..., $n-1, n$. From the above it is clear that the number of $L(2, n)$ Latin $2 \times n$-rectangles is equal to the number $D_n$ of normalized Latin $2 \times n$-rectangles multiplied by the number of permutations of $n$ numbers, i.e.

$$L(2, n) = n! \cdot D_n.$$

There are several elegant formulas for the number $D_n$ of normalized Latin $2 \times n$-rectangles.

Theorem 3. (Euler's formula.) $D_n = (n-1)(D_{n-1} + D_{n-2})$.

Table

| 1 | 2 | 3 | ... | $n-1$ | $n$ |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 2 | 3 | 4 | ... | $n$ | 1 |
| .. | .. | .. | .. | .. | .. |
| $m$ | $m+1$ | $m+2$ | ... | $m-2$ | $m-1$ |

⟦folio 8⟧

---
running_head:
folio:
---

as they say, a recurrent formula: if we know $D_1$ and $D_2$, and, obviously, $D_1=0$ and $D_2=1$, then we can use it to find the subsequent $D_n$:

$$D_3=2 \cdot (1+0)=2,$$
$$D_4=3 \cdot (2+1)=9,$$
$$D_5=4 \cdot (9+2)=44,$$
$$D_6=5 \cdot (44+9)=265$$

etc.

Proof. Any permutation can be written as a system of cycles. It's done like this. Let, say, $k_1$ be in 1st place, we write $1 \rightarrow k_1$. If the $k_1$-th place is $k_2$, we write $1 \rightarrow k_1 \rightarrow k_2$. Then $1 \rightarrow k_1 \rightarrow k_2 \rightarrow k_3$ and so on until we reach ones again (Fig. 1). (It cannot happen that in our sequence one of the already passed numbers will appear earlier than one. Let's say, if there is... $\rightarrow k_9 \rightarrow k_{10} \rightarrow k_5$, then $k_5$ is in the $k_{10}-m$ place and in the $k_4-m$ place, which means $k_{10}=k_4$, in the same way $k_9=k_3$, ..., $k_6=1$.) Then We take the smallest number not included in our cycle and build a cycle starting from it. Eventually all $n$ numbers end up in cycles (Fig. 2).

The number of cycles can be any from 1 to $n$, and the length of the cycle can be any from 1 to $n$. Our condition - that no number is in its place - prohibits cycles of length 1.

Now, using our permutation, we will construct a permutation of length $n-1$ or $n-2$ and also without cycles of length 1. Let’s find the number $n$ (Fig. 3) on one of the cycles. If the length of this loop is greater than two, we will simply throw out $n$ and short-circuit $p$ with $q$ (Fig. 4). If $n$ is part of a cycle of length 2, such as the one shown in figure 5, we simply discard this cycle and decrement all numbers from $k+1$ to $n-1$ by one: $k+1 \rightarrow k$, $k+2 \rightarrow k+1$, ..., $n-1 \rightarrow n-2$. In the first case, you get a permutation of $n-1$ numbers, in the second case, a permutation of $n-2$ numbers. In how many ways can we get a permutation of $n-1$ numbers? It is clear that there are $n-1$ ways: to return to a permutation of length $n$, we must break any $p \rightarrow q$ arrow (and theirs is $n-1$) and put $n$ there: $p \rightarrow n \rightarrow q$. In how many ways can a permutation of $n-2$ numbers be obtained? Again in $n-1$ ways: we add a cycle $n \rightarrow k$, where $k$ is any number from 1 to $n-1$, and increase the numbers $k$, $k+1$, ..., $n-2$ by one. Means,

$$D_n = (n-1)D_{n-1} + (n-1)D_{n-2},$$

which is what was required.

And here is another permutation formula for $D_n$, much simpler.

Theorem 4. $D_n=nD_{n-1}+(-1)^n$.

Proof. Let $D_n=nD_{n-1}=E_n$. From Euler's formula $E_n=D_n-nD_{n-1}=(n-1)D_{n-1}+(n-1)D_{n-2}-nD_{n-1}=-D_{n-1}+(n-1)D_{n-2}=-E_{n-1}$. Means,

$$E_n=-E_{n-1}=E_{n-2}=\dots=(-1)^nE_2.$$

But $E_2=1-2 \cdot 0=1$ means $E_n=(-1)^n$ and $D_n=nD_{n-1}+(-1)^n$.

From the last formula, nothing stands on it, not a recurrent, but an explicit formula for $D_n$.

Theorem 5. (Monmore formula.)

$$D_n=n!\left(\frac{1}{2!}-\frac{1}{3!}+\frac{1}{4!}-\frac{1}{5!}+\dots+\frac{1}{n!}\right).$$

⟦folio 9⟧

---
running_head:
folio:
---

Proof.
$$D_n = nD_{n-1} + (-1)^n = n((n-1)D_{n-2} + (-1)^{n-1}) + (-1)^n = n(n-1)D_{n-2} + (-1)^{n-1}n + (-1)^n = n(n-1)(n-2)D_{n-3} + (-1)^{n-2}n(n-1) + (-1)^{n-1}n + (-1)^n = ... = n(n-1)(n-2) \cdots 3 \times D_2 - n(n-1) \cdots 4 + n(n-1) \cdots 5 - ... + (-1)^{n-1}n + (-1)^n = n! \left( \frac{1}{2!} - \frac{1}{3!} + ... \right) + (-1)^n \frac{1}{n!}.$$

The last expression in parentheses may seem familiar to those of you who learned the beginnings of analysis in school. It also seems familiar to us, but we will postpone its “identification” until the final section of the article.

As for Montmore's formula itself, it was proven earlier than the two above formulas. Its direct proof is based on the inclusion-exclusion formula; readers familiar with this formula will deduce Montmore's formula from it without much difficulty, and we will turn to three-layer Latin rectangles.

Three floors

Attempts to find the number $L(3, n)$ of Latin $3 \times n$-rectangles ended in 1944, when the American mathematician Riordan, relying on the results of a long chain of predecessors, finally wrote out the final formula. We do not present here not only the derivation of the formula (which went far beyond the scope of the school curriculum), but also the formula itself, which is also quite cumbersome. We will limit ourselves to presenting a recurrent formula, which is called the Keraval–Riordan formula: if $K_n = \frac{1}{n!}L(3, n)$, then
$$K_n = n^2K_{n-1} + n(n-1)K_{n-2} + 2n(n-1)(n-2)K_{n-3} + (-1)^n(e_n + 2ne_{n-1}) (n \geqslant 4),$$
where $e_n$ is found from its recurrent formula (reminiscent of the formula for $D_n$):
$$e_0 = 1, e_n = ne_{n-1} + (-2)^n.$$
Using these formulas and the fact that $K_1 = K_2 = 0, K_3 = 2$, we can find $K_n$ for all $n$. For example,
$$K_5 = 552, \quad K_7 = 1073760;$$
Already from these equalities it is clear that the numbers $K_n$ are growing rapidly; the numbers $L(3, n)$, of course, grow even faster.

Approximate formulas

The expression $\frac{1}{2!} - \frac{1}{3!} + ... + (-1)^n \frac{1}{n!}$ seemed familiar to us because it resembles the power series for $e^x$:
$$e^x = 1 + x + \frac{x^2}{2!} + \frac{x^3}{3!} + ...$$

In particular,
$$\frac{1}{2!} - \frac{1}{3!} + ... + (-1)^n \frac{1}{n!} \approx 1 - 1 + \frac{1}{2!} - \frac{1}{3!} + ... = e^{-1},$$
Moreover, the error in absolute value does not exceed $\frac{1}{(n+1)!}$.

Means,
$$D_n \approx n!e^{-1} = \frac{n!}{e},$$
and the error does not exceed $\frac{1}{n+1}$. (Since $D_n$ is an integer, it can be reconstructed uniquely from these data.) Generalizing this formula, P. Erdős and I. Kaplansky in 1946 obtained an elegant

(For the end see p. 25)
