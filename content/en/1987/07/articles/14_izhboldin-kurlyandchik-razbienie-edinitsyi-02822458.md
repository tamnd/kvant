---
id: 1987-7-izhboldin-kurlyandchik-razbienie-edinitsyi-02822458
issue: kvant_1987_7
year: 1987
number: "7"
title: Unit splitting
authors:
  - Ижболдин О. Т.
  - Курляндчик Л. Д.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 50
page_last: 54
page_labels: 48, 49, 51, 52
tag: 6HQS
lang: en
source: kvant_digital
extraction: vision
content_sha256: 79e63bc53ba83df21cc0325cb3718799506c5c6731a6f11c342be748098c563d
prompt_sha256: draft-1
translated_from: content/ru/1987/07/articles/14_izhboldin-kurlyandchik-razbienie-edinitsyi-02822458.md
source_content_sha256: dfbb3fecb42b52d90bde51e693f2aceebc593f10ece40718c13e09889daf1247
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 48⟧

Unity splitting

O. T. IZHBOLDIN, L. D. KURLYANDCHIK

There are many problems involving sums of numbers that are the inverses of natural numbers. Our magazine has repeatedly addressed this topic: last year, two such problems were placed in the “Problem «Kvant»” - M989 and M1010 (in «Kvant» No. 6 and No. 10). The decision of the first of them was published (see «Kvant» No. 10 of 1986); This note is devoted to the solution of the second and several other related problems. Let us recall the formulation of the problem.

The sequence $r_1, r_2, r_3, \dots$ is determined by the conditions

$$r_1 = 2, r_{n+1} = r_1 r_2 \dots r_n + 1,$$

so $r_2 = 3, r_3 = 7, r_4 = 43, \dots$

a) Prove that for any $n$

$$\frac{1}{r_1} + \frac{1}{r_2} + \dots + \frac{1}{r_n} < 1.$$

6)* Let $n$ natural numbers be such that the sum of their reciprocals is 1. Prove that this sum is not greater than

$$\frac{1}{r_1} + \frac{1}{r_2} + \dots + \frac{1}{r_n}.$$

Essentially, what is required here is to find the best approximation of one unit by sums of fractions of the form $1/n$ (by the way, such numbers are called aliquot, or Egyptian, fractions). This problem belongs to the American mathematician Kellogg. In 1915, Professor Carmike, who reported it, cited it in his book “Diophantine Analysis”. In 1922, it was solved by the American mathematician Curtis. We will give another hot shorter solution. (Speaking about the history of the problem, let us also mention that it was published as number 70 in the collection “400 Selected Problems”, published by the Mir publishing house in 1977, but without actually a solution.)

Sequence
2, 3, 7, 42, 1807, 3263443, ...

The equality defining the sequence $r_n$ in the conditions of the problem can be rewritten in the form

$$r_{n+1} = (r_n - 1) r_n + 1$$

*) There was a third point in the problem - a lemma for solving problem 6). We'll bring it up later.

⟦folio 49⟧

or
$$\frac{1}{r_{n+1}-1} = \frac{1}{(r_n-1)r_n} = \frac{1}{r_n-1} - \frac{1}{r_n}.$$
Hence,
$$\frac{1}{r_1} + \frac{1}{r_2} + \dots + \frac{1}{r_n} = \left( \frac{1}{r_1-1} - \frac{1}{r_2-1} \right) + \left( \frac{1}{r_2-1} - \frac{1}{r_3-1} \right) + \dots + \left( \frac{1}{r_n-1} - \frac{1}{r_{n+1}-1} \right) = 1 - \frac{1}{r_{n+1}-1} < 1$$
(since $r_1-1=1$). This proves statement a) of our problem. Along the way, we proved that $1/r_{n+1}$ is the lowest natural value of $r_n$ that can be added to the sum $1/r_1+...+1/r_n$ so that it remains less than 1 (by adding $1/(r_{n+1}-1)$, we would already get exactly 1). Thus, when constructing the sequence $1/r_n$, you need to “bite off the largest possible piece” each time.

Let us note, by the way, that the numbers $r_n$ appear in another problem, the external estimate is far from ours: “to describe all sets of $n$ natural numbers such that the product of any $n-1$ of them in sum with one is divisible by the rest.” Check for yourself that the numbers $r_1, ..., r_n$ satisfy this condition. The complete solution to this problem is unknown; details were discussed in the article by A. Gein “On the way to a solution” (Kvant, 1978, No. 7, p. 9).

We will not return to task M1010 and oblige,

Why is the sequence $1/r_n$ the most accurate?

Let the sum $1/a_1+...+1/a_n$, where $a_1, ..., a_n$ are natural numbers, $a_1 \leqslant a_2 \leqslant ... \leqslant a_n$, is the most accurate approximation to unity; the existence of such an approximation for each natural number $n>1$ was proven in the solution of problem M989, c) (see «Kvant» No. 10, 1986, p. 36). Let's put $\alpha_k=1/a_k$ at $k=1, 2, ..., n-1$, $\alpha_n=1-\alpha_1-\alpha_2-...-\alpha_{n-1}$. We will show that the set of numbers $a_1, ..., a_n$ satisfies the following conditions:
$$\alpha_1 \geqslant \alpha_2 \geqslant ... \geqslant \alpha_n \geqslant 0,$$
$$\alpha_1+\alpha_2+...+\alpha_n=1,$$
$$\alpha_1...\alpha_k \leqslant \alpha_{k+1}+...+\alpha_n$$
at $k=1, 2, ..., n-1$. (3)

These are the conditions of the lemma that makes up point c) of problem M1010. According to this lemma, which is proven below, the number $a_n$, i.e., the error of our approximation of unity, is not less than $1/(r_n-1)$, and $a_n=1/(r_n-1)$ only for the set $a_k=1/r_k$, $k=1, ..., n-1$. Therefore, $a_k=r_k$, which is equivalent to statement 6).

So, let's check conditions (1)–(3) for $a_1, ..., a_n$. Condition (2) is very indo; it is also clear that $a_1 \geqslant a_2 \geqslant ... \geqslant a_{n-1}$. Let us show that $a_{n-1} \geqslant a_n$. Since we consider the best approximation of unity first,

$$\frac{1}{a_1} + ... + \frac{1}{a_{n-1}} + \frac{1}{a_{n-1}-1} \geqslant 1.$$
Hence,
$$a_{k+1} + ... + a_n = 1-\alpha_1-...-\alpha_k =$$
$$= 1-\frac{1}{a_1}-...-\frac{1}{a_k} = \frac{N}{a_1...a_k} =$$
$$= N \cdot \alpha_1 \cdot ... \cdot \alpha_k,$$
where $N$ is some natural number, and therefore the last expression is not less than $a_1...a_k$.

Proof of the lemma

We must prove that the one from the set ($\alpha_1, ..., a_n$) satisfying conditions (1)–(3) for which $a_n$ is minimal coincides with the set $(1/r_1, ..., 1/r_{n-1}, 1/(r_n-1))$.

It will be more convenient to look for a set with a minimum product of elements; we will see that it will have a minimum and last element.

So, let $\beta=(\beta_1, ..., \beta_n)$ be the one from the set satisfying conditions (1)–(3) for which the product $\beta_1...\beta_n$ is minimal (we will discuss the question of why such a set exists at all later). Let us immediately note that $\beta_n>0$, and therefore, by virtue of (2) $\beta_1<1$. (If $\beta_n=0$, then from inequality (3) we consistently obtain: for $k=n-1$ - that $\beta_n=0$, for $k=n-2$ - that $\beta_{n-2}=0$, etc.; but all numbers $\beta_i$ cannot equal 0, since they add up to 1.).

Let us now prove that for the set $\beta$ all inequalities (3) turn into equalities.

For $n=2$ from (1)–(3) we immediately obtain that $\beta_1 \geqslant \beta_2 \geqslant 0$, $\beta_1+\beta_2=1$ and $\beta_1 \leqslant \beta_2$, i.e. $\beta_1=\beta_2=1/2$. Let $n>2$.

⟦folio 51⟧

Let us explain this theorem using the example of our function $f$ and the set $A$. Firstly, it is clear that the function $f$ is not discontinuous, i.e. its values ​​for two sets, the corresponding elements of which differ sufficiently little from each other, will be as close as desired. Secondly, the set $A$ is limited, i.e. the elements $\alpha_i$ of any set included in it do not exceed a certain fixed number in absolute value; we have $|\alpha_i| \leq 1$. Finally, the set $A$ is closed; this means that if an arbitrary sequence of sets from the set $A$ consists of $\alpha = (\alpha_1, \dots, \alpha_n)$ (i.e., the first elements of these sets form a sequence similar to $\alpha_1$, the second to $\alpha_2$, etc.), then the set $\alpha$ also belongs to the set $A$. The closedness of the set $A$ ensures that all inequalities in conditions (1)–(3) are non-historical.

Thus, the theorem on achieving the minimum value provides a solid foundation for the construction we are building and thereby completes the solution to problem M1010. It is quite unusual that analysis methods had to be applied to such an integer problem. However, the initial solution mentioned at the beginning of the article was purely arithmetic.

The denominator is an arithmetic progression

Let's discuss two more problems about representations of integers: do the sums of the inverses of the natural numbers $a_1, a_2, \dots, a_n$ form an arithmetic progression with a non-field difference?

Let's start with the simplest case, where the difference of the progression is 1. So, can a number be represented as a sum $1/a_1 + 1/a_2 + \dots + 1/a_n$, where the natural numbers $a_1, a_2, \dots, a_n$ form an arithmetic progression with a non-field difference?

Let's start with the simplest case, where the difference of the progression is 1. So, can a number be represented as a sum $1/a_1 + 1/a_2 + \dots + 1/a_n$, where the natural numbers $a_1, a_2, \dots, a_n$ form an arithmetic progression with a non-field difference?

Problem 2. From any arithmetic progression of natural numbers, can we choose several different numbers $a_1, a_2, \dots, a_n$ such that $1/a_1 + \dots + 1/a_n = 1$?

The answer here is a statement, but, as in task 1, we will limit ourselves to only analyzing a few examples.

⟦folio 52⟧

The easiest way is to come up with the necessary decomposition of units for the progression of four numbers 2, 4, 6...; For example:

$$1 = \frac{1}{2} + \frac{1}{4} + \frac{1}{6} + \frac{1}{12}.$$

The situation with odd numbers is somewhat more complicated: one of the possible expansions is

$$1 = \frac{1}{3} + \frac{1}{5} + \frac{1}{7} + \frac{1}{9} + \frac{1}{11} + \frac{1}{15} + \frac{1}{21} + \frac{1}{35} + \frac{1}{231}.$$

And one more construction of a more general nature - for an arbitrary progression with a difference of 1: $a, a+1, a+2, \dots$. Let $k$ be a natural number such that $2^k > a$. If we write the numerators of fractions on the right side of the equality

$$1 = \frac{1}{2^k} + \frac{3}{3 \cdot 2^k} + \dots + \frac{2^{k+1}-1}{(2^{k+1}-1)2^k}.$$

in the form of sums of various powers of twos: $2^{l+1}-1=1+2+\dots+2^l$, we get a representation of the units of the sums

Tunnel microcoppe

(For the beginning see p. 19)

An example of such a map of the surface of a silicon crystal obtained by an American scientist is shown at figure on the right. The positions of individual silicon atoms in the periodic crystal structure are clearly visible.

A scanning tunnel microcoppe was also built in our country. It is distinguished by a huge, atomic-scale scanning area of ​​10×10 microns and the ability to work in a liquid non-conducting medium. The second important reason. Typically, in experiments on a tunnel microcopper, the sample under study, for the sake of numerical surfaces, is placed in a high vacuum. However, a dense environment may also be beneficial to achieve the same goals. Thus, liquid hydrocarbon, which is used in the Soviet tunnel microcopper, protects the surface of the...

“Topographic map” of a section of the silicon surface measuring 175×115 A. The lighter area corresponds to the position of the atoms of the crystal lattice.

The scanning tunnel microcop currently appears to be not only a means of studying the surface, but also a tool for influencing it. It is assumed that the edge of a tunnel microcopma can be “drawn” on the surface of microcops with dimensions of hundreds and even ten atoms. It is possible that we will soon witness a new stage in the microminimization of electronics. And a scanning tunnel microcop will help with this.

A. P. Volodin
