---
id: 1974-9-gerver-ot-peremenyi-mest-slagaemyih-7f4e5509
issue: kvant_1974_9
year: 1974
number: "9"
title: From changing the places of terms...
authors:
  - Гервер М. Л.
rubric: osnovnye-stati
page_first: 16
page_last: 20
page_labels: 14, 15, 17, 18
tag: 2N6D
lang: en
source: kvant_digital
extraction: vision
content_sha256: 9a3b1334270ff6a0666b5dcc31844d5de2ddf5868e69743eaa0e887479ea64a1
prompt_sha256: draft-1
translated_from: content/ru/1974/09/articles/06_gerver-ot-peremenyi-mest-slagaemyih-7f4e5509.md
source_content_sha256: 2f91f393a389d5004080e70a36ec848800f1a660249edd52d711c73e62a098f1
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 14⟧

Some things in «Kvant» are difficult to talk about, not because they are difficult in themselves, but because to understand them it would be good to know something in advance besides the school curriculum. Not even apart from it, but a little deeper. High school students know, for example, what a sequence limit is, but they know it in person rather superficially. Namely, this material must be fluent in order to understand the proposed article, where Riemann’s replacement theorem on permutations of conditions for convergent series is proved.

In «Kvant» No. 3 for 1974, we offered readers 20 problems on limits. Anyone who has completed the tasks can safely take on this article.

However, after solving the problems, do not put pen and paper aside: the main text of the article contains numerous exercises; Only by solving them yourself can you truly understand everything.

Sum of series

Let's start with very simple exercises.

1. a) Find the sum $S_n$ of the first $n$ terms of the geometric progression

$$\frac{1}{2}, \frac{1}{4}, \frac{1}{8}, \frac{1}{16}, \dots$$

6) Same for progression

$$\frac{1}{2}, -\frac{1}{4}, \frac{1}{8}, -\frac{1}{16}, \dots$$

Answer: a) $S_n = 1 - \frac{1}{2^n}$; 6) $S_n = \frac{1}{3} \left[ 1 - \left( -\frac{1}{2} \right)^n \right]$.

2. Find the sums $S^{(1)}$ and $S^{(2)}$ of infinitely killing geometric progressions (1) and (2).

Answer: $S^{(1)} = 1, S^{(2)} = \frac{1}{3}$.

The sums $S^{(1)}$ and $S^{(2)}$ can be found using the ready-made formula $S = \frac{b_1}{1-q}$ (where $b_1 = 1-1$ is the term and $q$ is the denominator of the infinite killing geometric progression):

$$S^{(1)} = \frac{1}{2} \cdot \frac{1}{1-\frac{1}{2}} = 1,$$

$$S^{(2)} = \frac{1}{2} \cdot \frac{1}{1+\frac{1}{2}} = \frac{1}{3}$$.

You can do it differently, use Exercise 1. Let’s find, for example, $S^{(1)}$ this way. For $n = 1, 2, 3 \dots$ we obtain partial sums:

$$S_1 = 1 - \frac{1}{2}, \quad S_2 = 1 - \frac{1}{2^2},$$

$$S_3 = 1 - \frac{1}{2^3}, \dots, \quad S_n = 1 - \frac{1}{2^n}, \dots$$

Sequence (3) tends to the limit $S^{(1)} = 1$. This limit, by definition, is called the sum of projections (1).

The above two solutions are essentially the same: the formula $S = \frac{b_1}{1-q}$ is obtained from the formula

⟦folio 15⟧

Let's represent $S_n = b_1 \cdot \frac{1 - q^n}{1 - q}$ as a transition. We will give a simple solution to fill certain sums of an infinite decreasing geometric progression. And we needed this in order to give the following general definition.

Definition. Let $a_1, a_2, a_3, \dots$ be an arbitrary number in the sequence. The expression $a_1 + a_2 + a_3 + \dots$ has a special name: $p$rd. We form a sequence of partial sums:

$$S_1 = a_1, S_2 = a_1 + a_2, S_3 = a_1 + a_2 + a_3, \dots, S_n = S_{n-1} + a_n, \dots$$

If this sequence has limit $S$, then it is said that $p$rd

$$a_1 + a_2 + a_3 + \dots + a_n + \dots = S.$$

If $p$rd $a_1 + a_2 + a_3 + \dots$ does not converge, then it is said to be divergent.

Exercises
3. Give examples of divergent series:
a) come up with a series whose partial sums tend to infinity;
b) come up with a series for which the sequence of partial sums does not tend to any number and does not tend to infinity.
4. Prove that the series
$$1 + \frac{1}{1!} + \frac{1}{2!} + \frac{1}{3!} + \dots + \frac{1}{n!} + \dots$$
converges. Its sum is the valued number $e^*$ (the base of natural logarithms). Prove that $2 < e < 3$. Prove that $e$ is an irrational number.
5. Prove that the series
$$1 + \frac{1}{2^2} + \frac{1}{3^2} + \dots + \frac{1}{n^2} + \dots$$
converges, and its sum is $S < 2$. For what natural numbers $k$ does the series converge?
$$1 + \frac{1}{2^k} + \frac{1}{3^k} + \dots + \frac{1}{n^k} + \dots$$?

Note. If all terms of the series are positive (as in Exercises 4 and 5),

*) See the article by L. G. Limanov “On the number $e$ and $n!$”, «Kvant», 1972, No. 5.

then, to prove the convergence of a series, it is enough to check that all partial sums are less than some (same) number $C$; then the convergence of the sequence of partial sums follows from the fact that any possibility of determining the sequence has a limit.

6. Does the series converge?
$$1 - \frac{1}{2} + \frac{1}{3} - \frac{1}{4} + \frac{1}{5} - \frac{1}{6} + \dots + \frac{1}{2n-1} - \frac{1}{2n} + \dots$$

Is it possible to sum up positive and negative terms separately?

You have already found the sum of the series
$$\frac{1}{2} - \frac{1}{4} + \frac{1}{8} - \frac{1}{16} + \dots$$

(it is equal to $\frac{1}{3}$). Is it possible to calculate it like this: first sum up all the positive terms of the series, then all the negative ones, and then add the results?

Why not? Let's try:
$$\frac{1}{2} + \frac{1}{8} + \frac{1}{32} + \dots = \frac{1}{2} \cdot \frac{1}{1 - \frac{1}{4}} = \frac{2}{3},$$
$$-\frac{1}{4} - \frac{1}{16} - \frac{1}{64} - \dots = \left(-\frac{1}{4}\right) \cdot \frac{1}{1 - \frac{1}{4}} = -\frac{1}{3},$$
$$\frac{2}{3} - \frac{1}{3} = \frac{1}{3}.$$

The answer, in any case, turns out to be correct. He asks: is it always possible to act this way?

Exercises
7. The series $a_1 + a_2 + a_3 + \dots$ converges. Its sum is $S$. Is it possible to calculate it like this: first sum all the positive terms $a_n$, then all the negative ones, and then add the results?
8. The series $a_1 + a_2 + a_3 + \dots$ converges. Its sum is $S$. It is given that if we sum all the positive terms $a_n$ the number $q$. Can we say that $p + q = S$?

⟦folio 17⟧

Exercises

11. Could it be that series (8) converges and series (7) diverges?

12. How does series (5) converge - conditionally or absolutely?

13. Prove that the series from Exercise 8 converges absolutely.

14. What happens if the sum of series (5) is calculated using the retty suggested in exercise 7?

15. Prove that the sum of an absolutely convergent series can be calculated using the grid indicated in Exercise 7.

16. Prove the following theorem about the permutation of terms of an absolutely convergent series. Let the series $a_1 + a_2 + a_3 + \dots$ be absolutely convergent. Let's randomly rearrange its members. Then the new series can converge absolutely, and the sums of both series are the same.

Riemann's theorem

By rearranging the terms of any condition of a convergent series, one can obtain a divergent series and one can obtain a convergent series, the sum of which is equal to an arbitrary predetermined number.

To prove this theorem we need the following

Lemma. If the series $a_1 + a_2 + a_3 + \dots$ converges conditionally, then the series composed of its positive terms diverges, and the series composed of its negative terms may diverge.

Exercises

17. Prove this lemma (remember Exercises 8, 13 and 15).

18. Let $a_1 + a_2 + a_3 + \dots$ be a convergent series. Prove that then the sequence $\{a_n\}$ tends to zero:
$$\lim_{n \to \infty} a_n = 0.$$

Proof of Riemann's theorem

A. Let us indicate how the terms of the series $a_1 + a_2 + \dots$ must be rearranged in order to obtain a divergent series whose partial sums tend to infinity.

First, we will write down only the positive terms of the series - until their sum becomes greater than 1 (according to the lemma, this is possible). Then we write out the first negative term. Next, we will again write down the positive terms until the sum of all the written numbers becomes less than 1, then less than -1.

B. Let us now indicate how the terms of the series $a_1 + a_2 + a_3 + \dots$ must be rearranged so that the new series turns out to be convergent to a predetermined sum S.

First, we will write down only the negative terms of the series until the sum of all the written numbers becomes S; then we'll add one

⟦folio 18⟧

several positive terms so that the whole sum becomes greater than $S$.

Let's continue writing out negative terms until the sum of all written terms becomes less than $S$ again; as soon as this happens, we add a second group of positive terms so that the entire sum exceeds $S$, and so on.

At the $n$-th stage, the next group of negative terms is written out (until the sum of all written numbers becomes less than $S$), and then the next group of positive terms (until the entire sum becomes more than $S$). According to the lemma, the terms of each sign are “enough”.

According to the construction, the partial sums of the new series behave like this: they kill until they become less than $S$, and immediately begin spreading until they become more than $S$; they kill again and so on. Each time a “jump” through $S$ is achieved by adding one single term. Thus, since $\lim_{n \to \infty} a_n = 0$, the deviations of the partial sums from $S$ also tend to zero, that is, the new series converges to $S$, which is what needed to be proved.

Example. Row
$$-\frac{1}{2} + \frac{1}{2} - \frac{1}{4} + \frac{1}{4} - \frac{1}{4} + \frac{1}{4} - \dots - \frac{1}{2^n} + \frac{1}{2^n} - \dots$$
converges to zero. Let's rearrange its members so that their numbers form the sequence 1, 3, 2, 5, 7, 4, 9, 11, 6, ... (two odd - one even). We obtain the series $-\frac{1}{2} - \frac{1}{4} + \frac{1}{2} - \frac{1}{4} + \frac{1}{2} - \dots$, which converges to $-\frac{1}{2}$; this becomes immediately clear if you arrange the brackets as follows:
$$-\frac{1}{2} + \left(-\frac{1}{4} + \frac{1}{2} - \frac{1}{4}\right) + \left(-\frac{1}{8} + \frac{1}{4} - \frac{1}{8}\right) + \dots$$

Analogues and generalizations

Be careful with parentheses! In the last example, we placed parentheses to ensure that the series converges to $-1/2$. In this case, we acted correctly (it’s easy to justify), but in general we need to place brackets with caution. Simplest example: divergent series $1-1+1-1+...$ after the following placement of brackets
$$(1-1) + (1-1) + \dots$$
turns into a series converging to zero.

This example is not very interesting. The following fact deserves great attention: there are divergent series, which, with suitable placement of brackets, become converging to any predetermined number.

Law 19. a) Give an example of a series that has the property just indicated.

6) Prove that any series obtained from a convergent series by placing parentheses converges and has the same sum as the original series.

c) Let $S_n$ be the partial sums of the divergent series $a_1 + a_2 + a_3 + \dots$, which is obtained by rearranging terms from some conditions of the divergent series. Let $a < b$ be the limit points of the sequence $\{S_n\}^*$, and let $S$ be an arbitrary point of the segment $[a, b]$: $a \leqslant S \leqslant b$. Prove that there then exists an arrangement of brackets such that the series $a_1 + a_2 + a_3 + \dots$ becomes convergent to $S$.

ČERO can be achieved by changing signs. Let $a_1 + a_2 + a_3 + \dots$ be an arbitrary conditionally convergent series. Let us change the signs of some of the terms $a_n$ (leaving the rest $a_n$ unchanged). In other words, let us replace the series $a_1 + a_2 + a_3 + \dots$ with the series $a_1b_1 + a_2b_2 + a_3b_3 + \dots$, where $|b_n| = 1$.

The rule has 20. Prove that for any number $S$ and for any condition of the series $a_1 + a_2 + a_3 + \dots$ one can choose the numbers $b_1, b_2, b_3, \dots$ in this way

*) For the definition of the limit point, see «Kvant», 1974, No. 3, p. 30.
