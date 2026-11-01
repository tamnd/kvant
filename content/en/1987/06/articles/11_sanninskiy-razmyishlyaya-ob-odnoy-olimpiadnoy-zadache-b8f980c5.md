---
id: 1987-6-sanninskiy-razmyishlyaya-ob-odnoy-olimpiadnoy-zadache-b8f980c5
issue: kvant_1987_6
year: 1987
number: "6"
title: Thinking about one Olympiad problem
authors:
  - Саннинский В. Я.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 39
page_last: 40
page_labels: 37-38
tag: 5QAX
lang: en
source: kvant_digital
extraction: vision
content_sha256: 85b5cef58271b8574bb925a3af326259f52abc4a8c4b1f3cd3a7c3b93a63c556
prompt_sha256: draft-1
translated_from: content/ru/1987/06/articles/11_sanninskiy-razmyishlyaya-ob-odnoy-olimpiadnoy-zadache-b8f980c5.md
source_content_sha256: e498202e358dcd84820292eb889f1a4f7906a286fbc97929217c0967d3c94e8d
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 37⟧

This means that if you were going to make constructions with a compass and a ruler and forgot the ruler at home, it doesn’t matter - you can get by with just a compass; if you forgot the compass, ask his friend and draw one circle with it, having previously marked its center; after that you can build anything with one ruler. (It’s worse, of course, if you forgot both a compass and a ruler at home - here science is powerless to help you.)

Thinking about one optimal problem

V. Y. SANNINSKY

Olympic problems are useful not only for testing mathematical abilities under tough competition conditions. In a more capable field, when there is time to think, a competition problem can become a source of a little independent research, somewhat reminiscent of service mathematical creativity.

I illustrate this with the following proof problem, which appears in many competition books:

If all prime numbers starting with 5 are entangled in ascending order, then each entangled prime number will be greater than its morning number.

Try to prove it yourself. It's not very difficult; for example, I came up with the proof quite quickly*. However, after that I did not give up the problem, but began to think about its formulation. And the question immediately arose: what does the numbers 5 and 3 have to do with it, is it possible to take other numbers? This suggests an assessment of the problem - together pairs of numbers (3, 5) separate an arbitrary pair $(k, p)$, where $k$ is a natural number and $p$ is a prime. The result was a statement that I called

$Y(k, p)$: if all prime numbers starting with $p$, confuse in order

*) I took advantage of the fact that the averages of consecutive numbers $9n, 9n+1, \dots, 9n+8, n=1, 2, 3, \dots$ can occur at most three primes.

increasing, then each entangled prime number is greater than its number multiplied by $k$.

One problem. This statement is not always true (not for all $k$ and $p$). For example, $Y(3,3)$ is false (the prime number 13 is less than its triple number: $13 < 3 \times 5 = 15$). On the other hand, we know that $Y(3,5)$ is true (this is the statement of our exclusion problem). Well, then the problem arises of describing all good pairs $(k, p)$, that is, those pairs for which $Y(k, p)$ is true.

To solve it, I started trying various small pairs, and quickly found a few minor ones (like $(4,5), (6,3)$) and some good pairs $(\langle 1,2\rangle, (2,3), (2,5), (3,7))$. I advise the reader to stop reading at this point and also try small pairs.

Further, the reader did not follow my advice; he will easily realize that justice $Y(k, p)$ implies justice $U(k', p')$ if $k' \leq k$ and $p' \geq p$. I also quickly noticed this and therefore decided not to look for all the good pairs, but to look only for the unimprovable pairs $(k, p)$, that is, those for which $Y(k, p)$ is true, but $Y(k', p')$ is false for $p' > k$ and false $Y(k', p')$ for $p' < p$. Thus a new task arose: to find all unimprovable pairs.

Exercise 1. Prove that the pairs $(1,2), (2,3) и (3,5)$ are unimprovable.

I proved this, as probably the reader did, without much difficulty and without looking at the next couple - $(4,7)$. It turned out to be not good: $7 > 4 \cdot 1, 11 > 4 \cdot 2, 13 > 4 \cdot 3, 17 > 4 \cdot 4$, but it is not true that $19 > 4 \cdot 5$. I moved on to the next pair - $(4,11)$ - and started trying $11 > 4 \cdot 1, 13 > 4 \cdot 2, \dots, 29 > 4 \cdot 6, 31 > 4 \cdot 7, \dots$. I soon got tired of this and decided that I had a plausible hypothesis: the pair $(4,11)$ is unimprovable. I confess that I had to tinker a lot before I was able to establish the validity of this hypothesis.

⟦folio 38⟧

I thought this way. Let $p_1 = 11, p_2 = 13, ..., p_n, ...$ integration be necessary for us. To prove $Y(4, 11)$, we need to establish the inequality $p_n > 4n$ for all $n \in \mathbb{N}$. Let's take the number $m = 210 = 2 \cdot 3 \cdot 5 \cdot 7$ (the product of all prime numbers less than 11) and divide the set of natural numbers $n \geq 11$ into $m$ classes, depending on the remainder when dividing them by $m$. Namely, to the $r$th class $K_r$, $r = 0, 1, ..., m - 1$ we include all numbers of the form $n = tm + r$, where $t \in \mathbb{N}$. then every natural number $n$ falls into exactly one class $K_r$ - namely, into the class with number $r$, equal to the remainder of the division of $n$ by $m = 210$. Let us remove from the list $K_0, K_1, ..., K_{m-1} = K_{209}$ all classes whose numbers are composite numbers. In other words, we will leave in the list only those classes whose numbers are coprime to $m$. Note that all the prime numbers $p_1, p_2, ..., p_n$ ... under consideration are in the remaining classes (why?). Let us denote the numbers of the remaining classes by $a_1, a_2, a_3, ...$, for example, $a_1 = 11, a_2 = 13, ..., a_{47} = 209$.

Exercise 2. Find all numbers (their $\varphi(m) = \varphi(210) = 48$) of the remaining classes and check that the inequality $a_n > 4n$, where $n = 1, 2, ..., 48$.*

Let us now put in ascending order all the numbers in the remaining classes. This list begins with the numbers already known to us $a_1, a_2, a_3, ...$, but does not end at $a_{48} = 211$, but goes further: $a_{49} = 217, a_{50} = 221, ...$. Then it is very indo that $a_n \leq p_n$ for all $n = 1, 2, ...$ (after all, our prime numbers $p_1, p_2, ...$ are among the remaining numbers $a_1, a_2, ...$). Therefore, it is enough for us to prove the inequality $a_n > 4n$ (for all $n$). For the first 48 numbers $a_1, ..., a_{48}$ it has already been verified (Exercise 2), for the further $n$ we will prove it by induction. Induction will be carried out on the auxiliary parameter $t$ with fixed $r$ ($r = 1, 2, ..., 48$), that is, we will check the proof for all numbers from the class with number $a_r$. Any number $a_s$ from this class is represented as $a_s = t \cdot 210 + r$. The beginning of induction already exists (we checked that at $t = 0$ the number $a_r$ satisfies the inequality $a_r > 4r$). Let (inductive sentence), $a_s = 210 \cdot t + r > 4s$. We need to establish the inequality $210(t + 1) + r > 4(s + 48)$, or $s + 48$ - the number of the next number $210(t + 1) + r$ from the class under consideration (with number $a_r$). But it immediately follows from the induction proposition and the very strong inequality $210 > 4 \cdot 48$. Statement $Y(4, 11)$ has been proven.

Exercise 3. Check that for $k > 5$ the statement $Y(k, 11)$ is false.

Since $Y(4, 7)$ is also false, we have established that the pair $(4, 11)$ is real unimprovable.

Let's move the problem forward - we'll look for an unimprovable pair of the form $(5, p)$.

Exercise 4. Check that the pairs $(5, p)$ are not good for $p < 23$, neither is the pair $(6, 23)$.

Investigation of the pair $(5, 23)$ $(23 > 5 \cdot 1, 29 > 5 \cdot 2, 31 > 5 \cdot 3$, etc.) leads to

*) The classes $K_0, K_1, ..., K_{m-1}$ are called residue classes modulo $m$. The number of these classes with numbers coprime to $m$ is denoted $\varphi(m)$; the function $\varphi$ is called the Euler function.

another hypothesis: *pair* $(5, 23)$ is unimprovable.

It is fair to say that the hypothesis can be established by reasoning in the same way as for the pair $(4, 11)$. That is, take $m = 2 \cdot 3 \cdot 5 \cdot 7 \cdot 11 \cdot 13 \cdot 17 \cdot 19 = 9699690$, consider the classes of residues modulo $m$, from them select $\varphi(m) = 1658880$ classes coprime to $m$, occupy all numbers (starting from 23) from the selected classes in ascending order $(a_1, a_2, ...)$ and prove by induction that the inequality $a_n > 5n$ (from which it follows $p_n > 5n$ for the chosen number prime numbers $p_1 = 23, p_2 = 29, ...$) is true for any number $a_n$ from a given class if it is true for number $a_n$ of that class. Then all that remains is to check that the inequality $a_n > 5n$ holds for all $n$ from 1 to $\varphi(m) = 1658880$. Of course, this check is of no use to humans. I had to entrust it to the machine; EC computer - 1045 in 6 minutes for response; indeed, $a_n > 5n$ at $n = 1, 2, ..., \varphi(m)$. The conjecture about the unimprovability of the pair $(5, 23)$ is established.

This happens often in modern mathematics: with logical reasoning, a mathematician sets up the task of checking an infinite set of statements (in our case, inequalities) against a finite (but large) set, and the statements of this set are checked by a computer.

What are the future prospects? Searching for the next unimprovable pair (of the type $(6, p)$) leads to numbers, at the limit of the EC computer's capabilities - 1045, and pairs of the type $(7, p)$ - are not completely suitable for our approach. Then I tried to generalize the original problem differently and came to the following formulation:

Torema. Prime numbers grow quickly any linear function of their number; in other words, if $p_1 = 2, p_2 = 3, ..., p_n, ...$ is a sequence of all prime numbers in ascending order, then for any $k$ and $b$ the inequality $p_n > kn + b$ holds for all $n$ greater than some $n_0$ (depending on $k$ and $b$).

Try and prove this well-known further? For example, one could try to prove that prime numbers grow more slowly than polygons of the second degree of their number. But this is already a difficult task: we are approaching the cutting edge of science, and we can move further only by studying the works of our great predecessors - Euler, Lagrange, Gauss, Riemann, Chebyshev.
