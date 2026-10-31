---
id: 1974-1-gurevich-rabbot-o-veroyatnostyah-i-horoshih-chislah-39f585cf
issue: kvant_1974_1
year: 1974
number: "1"
title: About probabilities and “good” numbers
authors:
  - Гуревич Г. А.
  - Раббот Ж. М.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 37
page_last: 42
page_labels: 35, 37, 38, 40
tag: CRQ8
lang: en
source: kvant_digital
extraction: vision
content_sha256: f1662922f39a1fb69a6c2072bd87c65ea6187ce7f338fccafc141945d1d5f393
prompt_sha256: draft-1
translated_from: content/ru/1974/01/articles/09_gurevich-rabbot-o-veroyatnostyah-i-horoshih-chislah-39f585cf.md
source_content_sha256: 989f086267cd2050ad3bc4d765190ca473aad9a5517c378537ae329ea6feeac9
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 35⟧

About probabilities and “good” numbers

G. A. Gurevich, J. M. Rabbom

«Kvant» publishes many different problems in mathematics. In letters sent to the editor, the question is often asked: “How do they come up with problems?” Our note is addressed primarily to those readers who are concerned about this issue.

Despite the “elementary” nature of many interesting problems, most of them are reformulations of meaningful mathematical facts. Unfortunately, many schoolchildren often, even after solving a particular problem, are unaware of the ideas from which it arose.

The purpose of this note is to tell a little about the theory of probability, which is associated with problem M204 of the “Problem Book”, Kvant’, and to give a simple solution to this problem.

First we recall the conditions of problem M204.

Let's call a natural number “good” if the numbers 1, 9, 7, 3 appear in a row in its decimal notation, and “bad” in the promise case. Let us prove that there is a natural number n such that among all n-digit numbers there are more “good” ones than “bad” ones.

Some examples

We'll start by looking at a few examples that, at first glance, have nothing to do with our problem.

Example 1: Suppose we tossed a coin. If it is without flaws, then we can equally expect that it will land up “heads” and that it will land “tails” on top. In addition, intuition tells us that if we toss a coin twice, then our increase in the fact that at least one of these two times it lands “heads” will be much greater than in the fact that it lands “tails” once. And, probably, everyone will agree that if you toss a coin 100 times, then it is almost certain that “heads” will appear at least once, or, in other words, it is unlikely that “tails” will appear all 100 times.

Example 2. 10 red and 2 black balls were placed in a box. If you randomly take a ball out of the box, it will almost certainly be red, since there are many more red balls than black ones. But if we repeat this experiment many times (let’s say, once), each time restoring the “original position”, that is, returning the removed ball to its place and thoroughly mixing the contents of the box, then we can say with precision that sooner or later we will pull out the black ball.

Example 3. Let's take 10,000 cards and write down on them all the natural numbers from 0 to 9999 (one number on each card). If a card contains a single-digit, two-digit or three-digit number, then we will add three, two or one zero to the left of it, respectively. Thus, all numbers written on the cards will become four-digit. Place all the cards in a pack and mix thoroughly. We will now carry out the next experiment.

⟦folio 37⟧

container), it consists of two elementary ones: “retrieving black ball No. 1” and “retrieving black ball No. 2”.

In example 3, removing a card is an elementary event. The total number of elementary events here is 10,000. But the extraction of a card on which “true” is written, a four-digit number (that is, a number whose first digit on the left is not zero) is an event consisting of 9000 elementary ones: “retrieving a card with the number 1000”, “retrieving a card with the number 1001”, “retrieving a card with the number 1002”, ..., “retrieving a card with a number 9999.”

To which of the elementary events $e_1, e_2, \ldots, e_n$ will we assign (set in correspondence) the number $\frac{1}{n}$, which we call the probability of its elementary event.

Note that we assigned each of the elementary events a certain equal probability. This serves as an expression that they are all “equal”.

The elementary events that make up this event $A$ are called outcomes favorable to this event. The probability $p(A)$ of an event $A$ consisting of $m$ elementary events is defined as follows:

$$p(A) = \frac{m}{n},$$

where $m$ is the number of favorable events $A$ outcomes, $n$ is the total number of outcomes.

In practice

1. When throwing dice, 1, 2, 3, 4, 5, 6 points are equally probable. What is the probability that when throwing a dice you get:

a) an even number of points;
b) an odd number of points;
b) 3 or 5 points;
g) prime number of points?

2. What is the probability that the number written on the chosen card in example 3 has the following properties:

a) four-digit;
b) divisible by 5;

b) there is a perfect square;
g) is not a four-digit number?

Obviously, with this definition, the probability of any event lies between 0 and 1: $0 \leq p(A) \leq 1$.

An event whose probability is equal to 1 is called reliable. He is favored by all outcomes without exception.

An event that favors the empty set of event elements (in other words, one that will never happen) by this definition has a probability of 0 and is called impossible.

Operations on events

Let $A$ be an event. Let us denote by $\bar{A}$ the event opposite to $A$, that is, an event that favors all those elementary outcomes that are not included in $A$.

Let $A$ and $B$ be two events. Let $A + B$ denote an event consisting of outcomes that favor at least one of the outcomes $A$ and $B$.

Let $A \cdot B$ denote an event consisting of outcomes favorable to $A$, but not favorable to $B^*$).

In practice

3. Prove that: a) $p(\bar{A}) = 1 - p(A)$;
b) $p(A + B) \leq p(A) + p(B)$; c) $p(A \cdot \bar{A}) = 0$; d) $p(A + \bar{A}) = 1$; e) $p((\bar{A})) = p(A)$;
e) $p((A \setminus B) + (A \cdot B)) = p(A)$;
g) $p((A \setminus B) \cdot B) = 0$.

4. Let the event $A$ be the extraction of a four-digit number on the card in example 3, the event $B$ be the extraction of a number, done on 5. Formulate what each of them means

*) Those who read the article: Gindkin S.G., How many operations on a set are there? «Kvant», 1973, No. 7, of course, noticed that operations on events are defined in exactly the same way as operations on a set (only together $A \cap B$, $A \cup B$ are denoted as $AB$, $A + B$).

⟦folio 38⟧

Fig. 1.

events in brackets below and find:
a) $p(\overline{A})$; b) $p(\overline{B})$; c) $p(A + B)$; d) $p(A \cdot B)$;
e) $p(A + \overline{B})$; f) $p(A \cdot \overline{B})$; g) $p(A \setminus \overline{B})$;
h) $p(B \setminus A)$.

5. Prove that for any two proper $A$ and $B$ the equality
$$p(A + B) = p(A) + p(B) - p(A \cdot B).$$

In part, on figure 1 the set of proper elements consists of 16 elements, depicted by black dots. In this case, $p(A) = 5/8$, $p(B) = 3/8$, $p(A \cdot B) = 3/16$, $p(A + B) = 13/16$.

A series of independent tests

In our examples, we were talking not only about single tests (tossing a coin, pulling out a ball or card), but also about series of several such tests. How to calculate probabilities in such cases? Here we get into combinatorial problems. The scheme of action is as follows: first you need to find the set of elements of your own and determine the number $N$ of its elements, then determine the number $M$ of outcomes favorable to $A$, and use the formula $p(A) = \frac{M}{N}$ to find the answer.

Let's solve, for example, the following problem. Let us ask you toss a coin. What is the probability that the loss of “heads” and “tails” will be the probability of the second toss does not depend on the result of the first (independent test), then all these four outcomes are equally probable.

Similarly, if we throw a coin three times, then the outcomes of this throw will be all kinds of triplets from O and P. To each outcome we assign the same probability equal to $1/8$, and the event of interest to us “falling out O and P through an arc” consists of two elements of its own; its probability is $2 \cdot \frac{1}{8} = \frac{1}{4}$ (Fig. 2).

In the general case, if a single experiment allows $n$ elements of outcomes, then the number of all possible elements of the outcomes of a double experiment is obviously equal to $n^2$ (any of the $n$ outcomes of the first experiment can be independently

⟦folio 40⟧

The general term of the geometric progression $\left(\frac{9999}{10000}\right)^k$ with a value $\frac{9999}{10000}$ less than 1, with unlimited increase $k$ tends to zero. Therefore, it will find such a $k_0$, the beginning of which is $\left(\frac{9999}{10000}\right)^{k_0} < \frac{1}{2}$, that is, $1 - \left(\frac{9999}{10000}\right)^{k_0} > \frac{1}{2}$.

At $k > k_0$ among 4$k$-digit numbers there will be more “good” ones than “bad” ones.

From our solution we obtain the following estimate for the minimum $n = n_0$, starting with which among the $n$-digit numbers there are more good ones than bad ones: $n_0 > 4\lg 2/\lg \left(\frac{10000}{9999}\right) \approx 30000$.

This estimate is, of course, quite rough.

It is worth noting a number of letters (N. Sherbin, Dnepropetrovsk; A. Kurlyandchik, Leningrad; A. Grigoryan, Baku), in which a more accurate estimate was found. The most interesting way here is this. Let $G(n)$ be the number of good $n$-digit numbers: $G(1) = G(2) = G(3) = 0$, $G(4) = 1$, $G(5) = 19$, $G(6) = 280, \dots$

Let us prove that for $n > 5$
$G(n) = 9 \cdot 10^{n-5} + 10G(n-1) - G(n-4)$. (*)

Indeed, there are $9 \cdot 10^{n-5}$ $n$-digit numbers ending in 1973; the good ones that remain good after crossing out the last digit are $10G(n-1)$, and the numbers belonging to this set are very conveniently $G(n-4)$.

From the current relation (*) it is easy to deduce that the minimum $n_0$ lies between 5000 and 10000. And if you use a computer (as our reader L. Kurlyandchik’s brother did), then you can quickly find the exact value $n_0$: it is equal to 6933.

The main mistake that most instructional readers have made is the following. Instead of estimating from above the number of suckers and x numbers, as was done
