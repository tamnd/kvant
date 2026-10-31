---
id: 1974-11-dorofeev-predelyi-posledovatelnostey-b99bc085
issue: kvant_1974_11
year: 1974
number: "11"
title: Sequence limits
authors:
  - Дорофеев Г. В.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 56
page_last: 61
page_labels: 54-59
tag: QELK
lang: en
source: kvant_digital
extraction: vision
content_sha256: f6d311f257116ae32dc232ddee28efa42997c8293582a0c44f526a335646059b
prompt_sha256: draft-1
translated_from: content/ru/1974/11/articles/14_dorofeev-predelyi-posledovatelnostey-b99bc085.md
source_content_sha256: 40d89f63645eae38546eea61e7907c3e831dff337f0e3242314347c489a17c6f
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 54⟧

Sequence limit
G. V. Dorofeev

Unlike most articles published in the “Applicant Practice” section, this article does not indicate in which particular task will be proposed.
This is not difficult to explain: the concept of a limit in the school course is used exclusively for theoretical purposes, and any computational problems related to limits are not solved in school. Naturally, therefore, there are no tasks of this kind in the written exam options offered to applicants.
However, in the tickets for the oral exam, the concept of a limit appears partly and, what is especially important, in all of them. For the well-prepared reader, we also recommend that you familiarize yourself with the articles of M. L. Gerver “20 problems to the limit” («Kvant», 1974, No. 3).

If we turn to the program for those building universities, then we will encounter the word “limit” in it only once - in paragraph 5 of section 1 “Arithmetic, algebra and elementary functions.” However, you can count more than ten questions included in the program, the very basis of which is precisely the concept of limit. These are, first of all, geometric questions related to the circumference, area of ​​a circle, surface area and volume of a cylinder, cone, sphere and its parts. In addition, the concept of limit is used in determining the degree of a positive number with an irrational exponent and the sum of an infinite killing geometric progression.

In fact, the list of questions in which the concept of limit is used is much wider; we have given only those where the use of limits is completely standard and familiar to schoolchildren. The concept of a limit is used, for example, in proving the main lemma on the similarity of triangles, formulas for the area of ​​a straight line and the volume of a straight line of a parallelepid, to prove the existence of roots of a natural degree of positive numbers, the existence of logarithms of positive numbers, etc. We dwell on one of these questions at the end of the article.

Applicants often have a question: how much knowledge is required of them about the limits of the sequence. At the same time, many people believe that there is no need to know any theorems about limits - after all, in the section of the program “Basic formulas and theorems” the concept of a limit is not mentioned!

However, this is not entirely the case - when proving some formulas and theorems included in the program, various limit theorems are clearly used, and therefore it is necessary to know at least the formulations of these theorems, and I will discuss the proofs later.

Consider, for example, calculating the sum of an infinite killing geometric progression. As is known, the sum of such a cut-through is the limit S sequentially

⟦folio 55⟧

stim $(S_n)$, food $S_n$ — sum $n$ of the first members of the progression: $S = \lim_{n \to \infty} S_n$. This is the determination of the amount. And to prove that the sum of such progression always exists (after all, not every sequence has a limit!), and to calculate this sum, the following calculation is carried out:

$$\lim_{n \to \infty} S_n = \lim_{n \to \infty} a_1 \frac{1-q^n}{1-q} =$$

$$= \lim_{n \to \infty} \left( \frac{a_1}{1-q} - \frac{a_1}{1-q} q^n \right) =$$

$$= \frac{a_1}{1-q} - \frac{a_1}{1-q} \lim_{n \to \infty} q^n = \frac{a_1}{1-q}.$$

The following theorems are used in this calculation:

(1) if the sequence $(a_n)$ has a limit, then for any number $c$
$$\lim_{n \to \infty} (c-a_n) = c - \lim_{n \to \infty} a_n;$$

(2) if the sequence $(a_n)$ has a limit, then for any number $c$
$$\lim_{n \to \infty} c a_n = c \lim_{n \to \infty} a_n;$$

(3) for any number $q$ it is maximum that $|q| < 1$
$$\lim_{n \to \infty} q^n = 0.$$

Note, in addition, that together with statement (1) when carrying out the first transformation, two theorems of a more “universal” nature can be used: the limit of the difference of two sequences is equal to the difference of their limits and the limit of a constant sequence (c) (that is, a sequence in which all terms are equal to the same number $c$) is equal to $c$:

(4) if the sequences $(a_n)$ and $(b_n)$ have a limit, then
$$\lim_{n \to \infty} (a_n-b_n) = \lim_{n \to \infty} a_n - \lim_{n \to \infty} b_n;$$

(5) $$\lim_{n \to \infty} c = c.$$

Note that when answering a question with the sum of an infinite decreasing geometric progression, it is checked how clearly the applicant understands exactly which theorems and in which exact place of the proof he is using - without such an explanation, the calculation done looks like a “photograph” from a textbook and, of course, cannot satisfy the examiners.

However, this may not be enough, especially when entering a university with an advanced mathematics program. In fact, if we carefully read the same program for applicants, we will find in it that the applicant must master the mathematical concepts mentioned in section 1. And mastery means being able not only to formulate a definition, but also to apply it in the simplest cases. And the proofs of statements (1)-(5), except, unfortunately, statement (4), can be fully described to such simple cases: they require no artificial calculations, no ingenuity and are accessible to anyone who knows and understands the definition of a limit. Let's look at this evidence.

Let us first recall that a number a is called the limit of the sequence $(a_n)$ if for any positive number $\varepsilon$ there is a maxim number $N$ such that all members of the sequence, starting with $a_{N+1}$, are in the interval between the numbers $a-\varepsilon$ and $a+\varepsilon$; in other words, for all $n>N$ the inequality $a-\varepsilon<a_n<a+\varepsilon$, or, what is the same, $|a_n-a|<\varepsilon$, holds.

From this definition, a scheme for direct proof of the statement $a=\lim_{n \to \infty} a_n$ immediately follows: it is necessary to show how, for an arbitrary positive number $\varepsilon$, find the number $N$ that has the required property. In this case, it is necessary to consider not some specific numerical value $\varepsilon$ (as it sometimes comes to merge, “let’s take an arbitrary number $\varepsilon$, for example $\varepsilon=1/2$), but rather an arbitrary value, that is, consider $\varepsilon$ as a parameter.

⟦folio 56⟧

Of course, in the vast majority of cases, the desired number $N$ will depend on $\varepsilon$.

Let us first prove the simplest statement (5).

Let a sequence with a common term $a_n=c$ be given. Let's take an arbitrary positive number $\varepsilon$ and start looking for a number $N$ such that for all $n>N$ the inequality $c-\varepsilon<a_n<c+\varepsilon$, that is, $c-\varepsilon<c+c+\varepsilon$, holds. You won’t have to search for long - this double inequality is always true (since $\varepsilon>0$), so you can take any number, in particular 1, as $N$.

Now let's prove statement (3).

Let $|q|<1$; Let's take an arbitrary number $\varepsilon>0$ and start looking for a number $N$ such that for all $n>N$ the inequality $-\varepsilon<q^n<\varepsilon$ or, which is the same thing, $|q^n|<\varepsilon$ or $|q|^n<\varepsilon$ holds. The last inequality is easy to solve: it holds for all $n>\log|q| \varepsilon$ (note that $|q|<1$). Therefore, $N$ can be any natural number greater than $[\log|q| \varepsilon]$, for example $1+[\log|q| \varepsilon]$.

When proving the considered statement in the exam, there is no need to reproduce all the above explanations of a methodological nature; It's better to check the proof more concisely:

“Let $\varepsilon$ be an arbitrary positive number; let's put $N=1+[\log|q| \varepsilon]$, moeda, if $n>N$, then $n>\log|q| \varepsilon$, maybe $|q|^n<\varepsilon$, or $-\varepsilon<q^n<\varepsilon$. Therefore, $\lim_{n\to\infty} q^n=0$". There is no need to be afraid that the examiners will not understand where this value $N$ came from, or will reproach you for taking it “out of thin air”.

In the examples discussed, we were able to actually explicitly specify the original number $N$. Otherwise we have to confine ourselves to proving the existence of such a number - this is also quite sufficient!

Let us prove statement (2).

Let $\lim_{n\to\infty} a_n=a$; Let's take an arbitrary number $\varepsilon>0$ and look for a number $N$ such that for any number $n>N$ the inequality $|ca_n-ca|<\varepsilon$ or $|c|\cdot|a_n-a|<\varepsilon$ holds.

Since $c=0$ the statement being proved is obviously true (by virtue of statement (5)), we will assume that $c\neq0$ and rewrite the above inequality in the form

$$|a_n-a|<\frac{\varepsilon}{|c|}.$$

Since $\varepsilon/|c|$ is some positive number and $a=\lim_{n\to\infty} a_n$, then, by the definition of the limit, there is a number $N'$ such that for $n>N'$ inequality (*) is satisfied. Let us set $N=N'$, then for $n>N$ inequality (*) is valid, hence the equivalent inequality $|ca_n-ca|<\varepsilon$.

So, we have proven that for an arbitrary $\varepsilon>0$ there is a number $N$ such that for $n>N$ the inequality $|ca_n-ca|<\varepsilon$ holds, and this means that $\lim_{n\to\infty} ca_n=ca$, which is what we needed to prove.

The proof of statement (4) is somewhat more complicated. We will prove a similar statement for the sum of sequences, leaving the proof of statement (4) as an exercise.

Let $\lim_{n\to\infty} a_n=a$, $\lim_{n\to\infty} b_n=b$, take an arbitrary $\varepsilon>0$. Then there is a number $N_1$ such that for $n>N_1$ the following inequality holds:

$$a-\frac{\varepsilon}{2}<a_n<a+\frac{\varepsilon}{2}.$$

On the other hand, there is a number $N_2$ such that for $n>N_2$ the inequality

$$b-\frac{\varepsilon}{2}<b_n<b+\frac{\varepsilon}{2}.$$

For $n$, large both $N_1$ and $N_2$, both obtained double inequalities are satisfied, and therefore

⟦folio 57⟧

and inequality

$(a+b) - \varepsilon < a_n + b_n < (a+b) + \varepsilon,$

obtained by their term-by-term addition.

Let us put $N$ equal to the larger of the numbers $N_1$ and $N_2$, $N = \max(N_1, N_2)$, then for $n > N$ inequality (**) will be satisfied. Thus, given $\varepsilon$, we found the value $N$ required by the definition and thereby proved that $\lim_{n \to \infty} (a_n + b_n) = a + b$.

Let us note that in the formulation of statements about limits there is often a restriction that the sequences appearing in them have a limit; Without this limitation, statements (1), (2), (4) are simply meaningless. To prevent these limitations from hanging in the air, it is useful to know that not every sequence has a limit.

An example of a sequence that has no limit is the sequence

$$0, 1, 0, 1, 0, 1, \dots$$

In fact, suppose the opposite, let this sequence have limit $a$. Let us put $\varepsilon = 1/3$, then we must find $N$ such that all terms of the sequence with numbers greater than $N$ lie in the interval $(a-1/3, a+1/3)$. Therefore, the distance between such terms (on the numerical axis) does not exceed 2/3. However, in our sequence there are terms 0 and 1, no matter how far apart, the distance between which is equal to 1, that is, more than 2/3.

Let us now find the limit of the sequence with a common term

$$c_n = \frac{1^2 + 2^2 + 3^2 + \dots + n^2}{6n^3},$$

which is used when calculating volume parameters using stepped bodies. To calculate this limit, we transform the expression for $c_n$:

$$c_n = \frac{n(n+1)(2n+1)}{6n^3} = \frac{(1 + \frac{1}{n})(2 + \frac{1}{n})}{6}.$$

Now the calculation of this limit is related to the calculation of the limit of the product $d_n = \left(1 + \frac{1}{n}\right)\left(2 + \frac{1}{n}\right)$, and for this process we use the following statement:

(6) if the sequences $(a_n)$ and $(b_n)$ have a limit, then

$$\lim_{n \to \infty} a_n b_n = \lim_{n \to \infty} a_n \cdot \lim_{n \to \infty} b_n.$$

However, the proof of this statement is much more complicated than all the previous ones: it requires preliminary proof of several more theorems about limits. At the same time, the calculation of our limit can be carried out directly, without using this general theorem. Let us prove that this limit is equal to 2 (“you can guess” that this is so from intuitive messages or on the basis of the same general Theorem 6—after all, for this it is not necessary to prove it!). It is necessary to show that for every $\varepsilon > 0$ there is a number $N$ such that for all $n > N$ the inequality

$$-\varepsilon < d_n - 2 < \varepsilon$$

$$-\varepsilon < \frac{3}{n} + \frac{1}{n^2} < \varepsilon.$$

It is clear that the left inequality holds for any $n$, and the inequality $\frac{3}{n} + \frac{1}{n^2} < \varepsilon$ is not difficult to solve, but we will proceed in an inverted manner. From inequality $\frac{1}{n^2} \leq \frac{1}{n}$ it follows that $\frac{3}{n} + \frac{1}{n^2} \leq \frac{4}{n}$, and inequality $\frac{4}{n} < \varepsilon$ holds for all $n > \frac{4}{\varepsilon}$.

Pozny, if we take as $N$ any natural number greater than $\frac{4}{\varepsilon}$, then at $n > N$ there will be $n > \frac{4}{\varepsilon}$, that is, $\frac{4}{n} < \varepsilon$, and therefore

$$\frac{3}{n} + \frac{1}{n^2} \leq \frac{4}{n} < \varepsilon.$$

⟦folio 58⟧

Thus, for an arbitrary $\varepsilon > 0$ we indicated the required number $N$, therefore $\lim_{n \to \infty} d_n = 2$, and $\lim_{n \to \infty} c_n = 1/3$.

In conclusion, let us turn our attention to another range of issues related to the concept of limit, namely, to the application of the so-called Weierstrass theorem. Let us recall its formulation: every monotonically increasing operation sequence has a limit. A similar statement is true for monotonically decreasing sequences.

We will not dwell on the standard applications of this theorem (for example, when determining the circumference of a circle); we will indicate some of its other applications.

Everyone knows that you cannot take the square root of a negative number, and they can easily prove it. Everyone also knows that a square root can be taken from any positive number, but how can one prove that it exists? This is established using Weierstrass's theorem.

Indeed, let a positive number $c$ be given; then there exists a non-negative integer $a_0$ such that

$$a_0^2 \leq c < (a_0 + 1)^2$$

($a_0$ is an integer approximation of the square root of $c$ with a deficiency, $a_0 + 1$ with an excess). Next, we can find an integer $a_1$ from 0 to 9 such that

$$\left( a_0 + \frac{a_1}{10} \right)^2 \leq c < \left( a_0 + \frac{a_1 + 1}{10} \right)^2$$

(that is, obtain an approximation of the square root of $c$ with an accuracy of 1/10).

Continuing this process, we get two sequences:

$$(a_n) = \left( a_0, a_0 + \frac{a_1}{10}, a_0 + \frac{a_1 + 1}{100}, \dots \right)$$

And

$$(b_n) = \left( a_0 + 1, a_0 + \frac{a_1 + 1}{10}, a_0 + \frac{a_1 + 1}{100}, \dots \right).$$

The first of these sequences is increasing and bounded - all its terms are less than, for example, $a_0 + 1$; by Weierstrass's theorem it has a certain limit $a$. The second sequence similarly has some limit $b$. By virtue of statement (6)

$$\lim_{n \to \infty} a_n^2 = a^2, \lim_{n \to \infty} b_n^2 = b^2.$$

On the other hand, by the very construction of these sequences there are inequalities

$$a_n^2 \leq c < b_n^2,$$

whence it follows (see exercise 9) that

$$a^2 \leq c \leq b^2.$$

Finally, we obtain statements (4) and (3), we obtain

$$a - b = \lim_{n \to \infty} a_n - \lim_{n \to \infty} b_n =$$

$$= \lim_{n \to \infty} \left( a_n - b_n \right) = \lim_{n \to \infty} (1/10)^{n-1} = 0.$$

Thus, $a = b$, and therefore $a^2 = c$. In other words, $a$ is the square root of $c$, and we demand that the statement is proven.

We see that proving such an “obvious” statement as the existence of a square root of a positive number actually requires the use of a large number of limit theorems. Therefore, its structure proof (and the proof of statements similar to it: the existence of logarithms of positive numbers, the existence of a power of a positive number with an irrational exponent, the existence of the arcsine value for any numbers from -1 to 1, etc.) is not included in either the school curriculum or the program for building a university. We have considered this issue only to show the true difficulty of proving such statements and to give an elementary idea of ​​​​the method of proving them.

⟦folio 59⟧

At the yarn
1. Prove that the limit of the sequence $1, -\frac{1}{2}, \frac{1}{3}, -\frac{1}{4}, \frac{1}{5}, -\frac{1}{6}, \dots$ is 0.
2. Prove that $\lim_{n \to \infty} \frac{1}{n} = 1$.
3. Let the sequences $(a_n)$ and $(b_n)$ have limits, and for any $n$ the inequality $0 \leq a_n \leq b_n$ holds. Prove that if $\lim_{n \to \infty} b_n = 0$ then also $\lim_{n \to \infty} a_n = 0$.
4. Let the sequence $(a_n)$ have limit $a$, and the sequence $(b_n)$ obtained from it:
   a) by throwing out a finite number of terms;
   b) throwing away an infinite number of terms (for example, all terms with even numbers);
   b) the addition in some places of a finite number of new members;
   g) by adding in some places an infinite number of new members.
   In each of these cases, what can be said about the limit of the sequence $(b_n)$?
5. Calculate the limit of a sequence with a common term:
   a) $a_n = \frac{1}{n^2 + 2}$;
   b) $a_n = \frac{4n}{3n^3 - 5n - 4}$.
6. Prove that the sequences $1, 0, \frac{1}{2}, \frac{1}{2}, \frac{2}{3}, \frac{1}{3}, \frac{3}{4}, \frac{1}{4}, \frac{4}{5}, \frac{1}{5}, \dots$ and $1, 0, 2, 1, 0, 2, 1, 0, 2, \dots$ have no limits.
7. Prove that if the sequences $(a_n)$ and $(b_n)$ have limits, then $\lim_{n \to \infty} (a_n - b_n) = \lim_{n \to \infty} a_n - \lim_{n \to \infty} b_n$.
8. What can we say about the limit of the sequence $(a_n + b_n)$ if the sequences $(a_n)$ and $(b_n)$:
   a) both have limits;
   b) both have no limits;
   b) one has a limit and the other does not?
9. Prove that if all terms of the sequence $(a_n)$ are less than the number $c$, then the limit of this sequence is not greater than $c$. Can we say that this limit is less than $c$?

Assignment about graphs and fairy tale “Ivan Tsarevich and the Gray Wolf”
(End. See p. 23 for beginning)

2. You can’t go along the same road; if you erase that road, we’ll see that it’s no longer possible to get to the capital from some city. (Such a road is called an isthmus).

If we follow equal to 2, then at any moment the roads are not yet erased and the cities form a connected graph. Let us show that we can always follow a path equal to 2, that is, that, arriving at any city $N$, we will have at our disposal a road that is not an isthmus.

Let us first note that if the road from $N$ turns out to be an isthmus, then there are also roads leaving from $N$. Let's assume the worst - all these roads turned out to be isthmuses at that moment. Suppose we erased two of them; one connected the city $N$ with the city $N_1$, the other - with the city $N_2$. Obviously, in this case, from these parts there must be another city with an odd number of roads. But this cannot be, since at this time on the map with an odd number of roads, in addition to the cities $N_1$ and $N_2$, only the capital remains.

Let us finally prove that, following rules 1 and 2, we must go around all the roads once. Let's assume that we returned to the capital without going through all the roads. This means that cities remain unerased on the map. The distance is the unerased city $M$ that we passed last. Obviously, the road along which we left it was an isthmus: it is not to the capital (otherwise we would have gotten to the capital directly from $M$, and the city $M$ would have been erased on the map - see rule 1), and by erasing this road, we cut off all routes from $M$ to the capital. But by virtue of rule 2, we cannot go along such roads. We received opposition.

Thus, Euler's theorem is completely proven.
