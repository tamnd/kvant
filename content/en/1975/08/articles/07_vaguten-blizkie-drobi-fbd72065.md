---
id: 1975-8-vaguten-blizkie-drobi-fbd72065
issue: kvant_1975_8
year: 1975
number: "8"
title: Close fractions
authors:
  - Вагутен В. Н.
rubric: osnovnye-stati
page_first: 35
page_last: 41
page_labels: 33-39
tag: 5SIO
lang: en
source: kvant_digital
extraction: vision
content_sha256: 9c65dde6763d4c7387393aecc48576aa2bd3e4521cd17e27b9214eca65ae2506
prompt_sha256: draft-1
translated_from: content/ru/1975/08/articles/07_vaguten-blizkie-drobi-fbd72065.md
source_content_sha256: a938a9309f5b5c69437d37941b4bde15e2263a927ce326c44925c1b542fb74e0
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 33⟧

This note talks about some interesting sequences of dobes and solves problem M298 from the “Problem Book «Kvant». Although at the end the lesson requires familiarity with the method of coordinates, vectors and the principle of mathematical induction, most of the note will be understandable even to those who have only recently become acquainted with the subject. The author hopes that high school students and teachers will find here convenient material for classes with students in grades 5-6. Exercises involve the existing condition.

1. Farey series. Observations

Let's write down all the regular dobies whose denominator is no more than 7:

$$\frac{1}{2}, \frac{1}{3}, \frac{2}{3}, \frac{1}{4}, \frac{3}{4}, \frac{1}{5}, \frac{2}{5}, \frac{3}{5}, \frac{4}{5}, \frac{1}{6},$$

$$\frac{5}{6}, \frac{1}{7}, \frac{2}{7}, \frac{3}{7}, \frac{4}{7}, \frac{5}{7}, \frac{6}{7}$$

(we have omitted the abbreviated dobies: $\frac{2}{4}, \frac{2}{6}, \frac{3}{6}$ and $\frac{4}{6}$ - from the dobies representing the same number, we choose the same dobie, namely the one with the smallest numerator and denominator).

Now let’s write the same dobies in ascending order:

$$\frac{1}{7}, \frac{1}{6}, \frac{1}{5}, \frac{1}{4}, \frac{2}{7}, \frac{1}{3}, \frac{2}{5}, \frac{3}{7}, \frac{1}{2},$$

$$\frac{4}{7}, \frac{3}{5}, \frac{2}{3}, \frac{5}{7}, \frac{3}{4}, \frac{4}{5}, \frac{5}{6}, \frac{6}{7}.$$

(1)

Check that in row (1) each addition is real greater than the previous one

$$\frac{1}{6} - \frac{1}{7} = \frac{1}{6.7}, \frac{1}{5} - \frac{1}{6} = \frac{1}{5.6},$$

$$\frac{1}{4} - \frac{1}{5} = \frac{1}{4.5}, \frac{2}{7} - \frac{1}{4} = \frac{1}{4.7}, \dots$$

In this case, an interesting pattern is observed: the number of points of the difference between two neighboring additions always turns out to be equal to one, or more precisely,

A. For any two neighboring additions $\frac{a}{b}, \frac{c}{d}$ ($2\delta e \frac{a}{b} < \frac{c}{d}$) the equality

$$bc - ad = 1.$$

What other patterns are inherent in a number of dobes (1)?

It is not difficult to discover that the sum of two dobes standing symmetrically in this row is equal to 1. I wonder if the reader has noticed that

B. Each doub is obtained from the two dobes adjacent to it in the following way: you need to add their numbers and divide the resulting number by the sum of the denominator.

In fact,

$$\frac{1}{6} = \frac{1 + 1}{7 + 5}, \frac{1}{5} = \frac{1 + 1}{6 + 4},$$

$$\frac{1}{4} = \frac{1 + 2}{5 + 7}, \frac{2}{7} = \frac{1 + 1}{4 + 3}, \frac{1}{3} = \frac{2 + 2}{7 + 5},$$

$$\frac{2}{5} = \frac{1 + 3}{3 + 7}, \frac{3}{7} = \frac{2 + 1}{5 + 2}, \frac{1}{2} = \frac{3 + 4}{7 + 7}$$

and so on!

⟦folio 34⟧

Table 1. Farey series.

In the same way as line (1) is written out from proper fractions with a denominator not exceeding 7, one can write out, in ascending order, fractions with a denominator not exceeding $n$. Let us also arrange the rows for $n=1, 2, \dots, 7$ in a row in the form of Table 1.

The first row and the side walls of fractions $\frac{0}{1}$ and $\frac{1}{1}$ give our table a more complete look.

Exercise 1. Check that patterns A and B, which we noticed in the next row of the table, also occur in all previous rows.

We have highlighted new fractions in each line in red.

For new fractions, observe B, you can clarify: for a fraction arising between two old ones, the numerator is equal to the sum of their numerator, the denominator is equal to the sum of their denominators. Thus, we can propose a simple rule by which a new $n$-th row is obtained.

B. It is necessary to note in the $(n-1)$th line all such pairs of leading fractions $\frac{a}{b}, \frac{c}{d}$, in which the sum of the denominator is equal to $n$, and between them there are fractions $\frac{a+c}{b+d}$ (they always turn out to be non-reducible).

Let's do this operation with the next pair of lines. Let's mark the pairs as gray

they are fractions whose sum has a denominator of 8. These are such pairs

$\frac{0}{1}$ and $\frac{1}{7}$; $\frac{1}{3}$ and $\frac{2}{5}$; $\frac{3}{5}$ and $\frac{2}{3}$; $\frac{6}{7}$ and $\frac{1}{1}$.

Let's insert the fractions $\frac{1}{8}, \frac{3}{8}, \frac{5}{8}, \frac{7}{8}$ between them, respectively, and get the eighth line

$$\frac{0}{1} \frac{1}{8} \frac{1}{7} \frac{1}{6} \frac{1}{5} \frac{1}{4} \frac{2}{7} \frac{1}{3} \frac{3}{8} \frac{2}{5} \frac{3}{7} \frac{1}{2}$$

$$\frac{4}{7} \frac{3}{5} \frac{5}{8} \frac{2}{3} \frac{5}{7} \frac{3}{4} \frac{4}{5} \frac{5}{6} \frac{6}{7} \frac{7}{8} \frac{1}{1}$$

Exercise 2. Perform a similar operation with the eighth line and check that this way you get a line of all non-reducible fractions with a value of no more than 9, in ascending order.

Exercise 3. Check that patterns A and B are satisfied in the eighth and ninth lines.

The row of all non-reducible fractions $\frac{p}{q}$, for which $1 \leq p \leq q \leq n$ ($n$ is a given natural number), arranged in increasing order, has a special name in number theory - the Farey series, and is sometimes denoted by $F_n$. The name of the mathematician Farey was given to such lines by the great French mathematician Cauchy. Farey was interested in the regularities in this series of fractions, and Cauchy, paying attention to Farey's observations, published their proof in 1816. However, it is entirely possible that these patterns were known to mathematicians before.

Let us give two definitions related to our observations.

Definition 1. Let us call two fractions $\frac{a}{b}, \frac{c}{d}$ close if $bc$-ad is equal to 1 or -1.

Exercise 4. Select from fractions (1) all pairs of close fractions.

⟦folio 35⟧

Definition 2. Let us take the mediant of two fractions $\frac{a}{b}, \frac{c}{d}$ to be the fraction $\frac{a+c}{b+d}$.

(The mediant of irreducible fractions may be a reducible fraction; give an example.)

2. Properties of close fractions

Now our hypotheses can be briefly formulated as follows: in any $n$th Farey series ($n$th row of Table 1)

A. Neighboring fractions are close to another fraction.

B. Each new fraction $m/n$ is the mediant of its neighboring fractions.

In problem M298 from the “Problem Book «Kvant»” it was precisely necessary to prove property A: if $p/q < r/s$ are neighboring fractions of the series $F_n$, then $qr - ps = 1$. But it turns out that it is significant that it is easy to prove both properties at the same time - both A and B. We outline below as many as three different proofs: one - in paragraphs 3-4, the second - in paragraph 5, the third - in paragraph 6. We indicate several simple properties that characterize close fractions and mediants.

a) For any two fractions $a/b$ and $c/d$ their difference modulo is not less than 1/bd:

$$\left| \frac{a}{b} - \frac{c}{d} \right| \geq -\frac{1}{bd},$$

(2)

and the equality sign in (2) is obtained if and only if the fractions $a/b$ and $c/d$ are close. (This explains the choice of term: close fractions.)

6) The mediant of two fractions is always contained between them, m. e.

if $\frac{a}{b} < \frac{c}{d}$, then

$$\frac{a}{b} < \frac{a+c}{b+d} < \frac{c}{d}.$$

b) If two fractions are close fractions to each other, then both of them are irreducible.

r) If two fractions are close fractions to each other, then their mediant is close to each of them.

d) If two fractions are close fractions to each other, then their values ​​are coprime and their numerical values ​​are coprime *).

e*) Of all the fractions contained between two close fractions, their mediant is called the denominator.

Exercise 5. Prove properties a) - d).

Let us now assume that the reader not only completed exercise 2 - received 2 from use - but, continuing to act further according to rules B, receives the tenth line, the same, and so on.

From properties 6), B), r) it follows that in all new lines the following regularities are also preserved:

1) the mediant fractions that we insert will be irreducible;
2) fractions are in ascending order;
3) any two adjacent fractions are close to another.

The remaining more difficult question is this. According to rules B, will all irreducible fractions with value $n$ be included in the $n$th row, or may it turn out that some will be missed? It turns out that all such fractions will necessarily be inserted, i.e. we will actually get the entire string $F_n$. At this point, we advise the reader to leave and try to come up with a proof on their own (one of the ways is to prove the property e, marked with an asterisk).

For now, we will make a short absence and discuss the question:

How many fractions are there in the $n$th row of our table?

*) Integers $a$ and $b$ are called coprime if they do not have common factors greater than 1.

⟦folio 36⟧

3. Euler function.
Number of red fractions

Let us have a natural number $n$. Let's consider all natural numbers not exceeding $n$, and choose from them those that are coprime to the number $n$. The number of these numbers will be denoted by $\varphi(n)$.

For example, for $n=8$ such numbers will be 1, 3, 5, 7, and thus $\varphi(8)=4$.

So, each natural number $n$ is associated with the number $\varphi(n)$. This correspondence $\varphi$ is called the Euler function.

Let us list some properties of Euler functions:
1) $\varphi(n) < n$.
2) If $n = p$ is a prime number, then $\varphi(p) = p-1$.
3) For $n > 2$ the number $\varphi(n)$ is even.
4) If $n = p^d$ is a power of the prime number $p$, then

$$\varphi(p^\alpha) = p^\alpha - p^{\alpha-1} = p^\alpha \left(1 - \frac{1}{p}\right).$$

5*) If $m$ and $n$ are coprime, then $\varphi(mn) = \varphi(m) \cdot \varphi(n)$.
6) The general formula for $\varphi(n)$ is:

$$\varphi(n) = n \left(1 - \frac{1}{p_1}\right) \left(1 - \frac{1}{p_2}\right) \dots \left(1 - \frac{1}{p_r}\right);$$

here $p_1, p_2, \dots, p_r$ are all prime numbers divisible by $n$. (This formula was proven in the article “Fermat’s Little Theorem”, «Kvant», 1972, No. 10.)

We invite the reader to prove all these properties. Let us explain only property 3). All numbers less than $n$ and coprime to $n$ can be divided into pairs: each pair consists of numbers $q$, $s$ such that $q+s=n$. Thus, the number $\varphi(n)$ is even.

The number of red fractions in the $n$th line $F_n$, very indo, is equal to $\varphi(n)$, since there are as many irreducible fractions $m/n$ ($0 \leqslant m/n \leqslant 1$) with value $n$ as there are natural numbers $m$, less than $n$, and coprime with $n$.

The question of how many total terms the $n$th Farey series $F_n$ contains is discussed by reader «Kvant» in his letter. A. Kitaev from Leningrad. It is clear that this number - let's denote it $\varphi(n)$ - is equal to

$$\varphi(n) = 1 + \varphi(1) + \varphi(2) + \varphi(3) + \dots + \varphi(n),$$

since $\varphi(1) = 2$ and $\varphi(n) = \varphi(n-1) + \varphi(n)$ (see Table 2). There appears to be no simple formula for $\varphi(n)$. But it is interesting that, despite the extremely irregular behavior of the Euler function $\varphi(n)$ (relative to

$$n \quad 1 \quad 2 \quad 3 \quad 4 \quad 5 \quad 6 \quad 7 \quad 8 \quad 9 \quad 10 \quad 11 \quad 12 \quad 13 \quad 14 \quad 15 \quad 16 \dots$$

$$\varphi(n) \quad 1 \quad 1 \quad 2 \quad 2 \quad 2 \quad 6 \quad 4 \quad 6 \quad 4 \quad 10 \quad 4 \quad 12 \quad 6 \quad 8 \quad 8 \dots$$

$$\varphi(n) \quad 2 \quad 3 \quad 5 \quad 7 \quad 11 \quad 13 \quad 19 \quad 23 \quad 29 \quad 33 \quad 43 \quad 47 \quad 59 \quad 65 \quad 73 \quad 81 \dots$$

Table 2. Euler's function and the number of fractions $F_n$.

the solution $\frac{\varphi(n)}{n}$ is arbitrarily close to 0 and to 1), for $\varphi(n)$ one can prove the following limit relation:

$$\lim_{n \to \infty} \frac{\varphi(n)}{n^2} = \frac{3}{\pi^2} \approx 0,305 \dots,$$

i.e. $\varphi(x)$ for large $x$ increases “approximately along a parabola”: $\varphi(x) \approx \frac{3}{\pi^2} x^2$.

This is one of the beautiful theorems obtained by the original mathematician F. Mertens (1874).

4. Adjacent denominators

Let us now return to the question posed at the end of paragraph 3 and explain why, acting according to rules B, we will obtain all $\varphi(n)$ irreducible fractions with denominator $n$. Let's make one more observation.

Let us pay attention to the denominators of fractions in table 1. For convenience, let us compose a new table 3 from them. Rule B allows us to continue the “table of denominators” (without worrying about numerals) as follows.

IN'. It is necessary to mark in the $(n-1)$th line all pairs $q$, $s$ of neighboring numbers, the sum of which is $n$, and look at $n$ between them.

As we have already said, the neighboring values ​​$q$ and $s$ in Table 3 are relatively prime (see property D, point 2). Let us now note that, entering the sums $q+s=n$ into the $n$th line, we encounter which of the $\varphi(n)$ possible representations $n$ in the form of a sum of coprime numbers (and exactly one). For example, in a binary string:

36

⟦folio 37⟧

Table 3. Denominator of Farey series

$$9 = 1 + 8, \quad 9 = 5 + 4, \quad 9 = 7 + 2,$$
$$9 = 2 + 7, \quad 9 = 4 + 5, \quad 9 = 8 + 1.$$

Exercise 6. Add three more lines of Table 3 and check that all φ (n) represented by the denominator n as the sum of two adjacent denominators n = q + s occur exactly once.

We formulate the observation made in Exercise 6 as follows.
D. In the nth row of Table 3, each number that is coprime to n is a former “neighbor” exactly twice: once on the trail and once on the right.

Exercise 7. Prove that if property Γ holds in all previous rows of Table 3, then it must also hold in the nth row obtained by rule B'.

It follows from Exercise 7 (according to the principle of mathematical induction) that if new rows of Table 3 are obtained according to rule B', then in all rows property Г will be satisfied, and therefore, in the nth row there will be exactly f (n) new terms!

Exercise 8. Let us, starting from line $\left(\frac{0}{1}, \frac{1}{1}\right)$, perform the following operation several times: between two already written fractions we insert their mediant. Prove that for any string that can be obtained in this way, properties A and B are satisfied.

From the result of this problem, in particular, it follows that properties A and B are satisfied for each line of table 4, where a mediant is inserted between each and two fractions in the next line.

Exercise 9. Prove that in Table 4, in each line, starting from the nth, all irreducible fractions with denominator n appear, each one occurring once.

Table 4. 《Accelerated》 Farey series.

Table 4 of the dough is associated with the table of integers, which is considered in problem M233 by G. A. Galperin from “Problem Book «Kvant»”. This table 5 appears not only in the denominators of the fractions of table 4, but also in their numerals (in the second “half” of table 4, starting from the second line, in the second “quarter,” starting from the third line, and so on!)!

5. Second proof

Let us give a short proof of properties A and B using the Farey series $F_n$, based on property a) of close fractions (such a proof is given in the book [2]).

The proof is also carried out by induction. Suppose that for all rows $F_1, F_2, \dots, F_{n-1}$ preceding $F_n$, properties A and B are proven. Let some fraction $m/n$ (so denominator n) be enclosed between neighboring fractions $p/q$ and $r/s$ from $F_{n-1}, p/q < r/s$ (hence $qr - ps = 1$).

Then

$$\frac{m}{n} - \frac{p}{q} \geq \frac{1}{qn}$$

And

$$\frac{r}{s} - \frac{m}{n} \geq \frac{1}{sn}.$$

Adding these inequalities, we get

$$\frac{r}{s} - \frac{p}{q} \geq \frac{q + s}{nqs};$$

⟦folio 38⟧

$$\frac{q+s}{n} \leq qr - ps = 1;$$
$$q+s \leq n.$$

The second inequality $q+s < n$ cannot be satisfied: in this case, the fraction $(p+r)/(q+s)$ would occur between $p/q$ and $r/s$ already in $F_{n-1}$ (further in $F_{q+s}$).

Hence,
$$n = q+s,$$
(4)
and therefore inequalities (3) must also be equalities, whence
$$mq-np = 1, nr-ms = 1.$$ (5)
From (4) and (5) it follows that $m = p+r$.

So, we have proven that $m/n$ is the mediant of the fractions $p/q$ and $r/s$ and is close to each of them. (Essentially, we have here proved property e) of close fractions.) This means that properties A and B are also true for $F_n$.

Tension 10. Prove that:
a) if the fractions $m/n$ and $p/q$, where $q < n$ are close, then they are neighboring fractions in $F_n$;
b) any fraction close to $m/n$ is equal to one of the fractions $(m+kr)/(n+ks)$, or $(m+kp)/(n+kq)$, where $k = 0, 1, 2, \dots$, and $p/q$ and $r/s$ are neighbors of $m/n$ in $F_n$.

Tension 11. Let in the sequence of fractions $\frac{1}{1} \leq \xi_1 \leq \dots \leq \xi_N \leq \frac{1}{1}$ every two adjacent fractions be close to each other. Prove that these sequences can be obtained using the procedure described in Exercise 8.

The geometric interpretation to which we turn means to clarify the simple principles of patterns A and B, and at the same time suggests the idea of ​​​​another proof.

6. Lattices and parallelograms

Let's take a sheet of checkered paper and introduce a coordinate system on it. We take two perpendicular grid lines as coordinate axes, and the side of the cell as a unit of scale.

Let us correspond to each fraction $m/n$ ($0 \leq m/n \leq 1, n > 0$) with a point with coordinates $(n, m)$. (On figure 1 there are black dots.) Instead of “dot” we will sometimes say “fraction”.

Irreducible fractions on figure 1 are circled in blue, and those whose names are no more than 4 are connected by blue segments to the origin O.

Let's formulate several properties of fractions in geometric language. Let $p/q$ and $r/s$ be two fractions, $A(q, p)$ and $B(s, r)$ their corresponding points.

a) $p/q = r/s$ if and only if points A and B lie on the same ray as the origin O. The node closest to O on this ray corresponds to an irreducible fraction.

Next we assume that $p/q \neq r/s$.

6) $p/q > r/s$ if ray OA makes a larger angle with the horizontal coordinate axis than ray OB.

⟦folio 39⟧

C) The fraction $(p+r)/(q+s)$ corresponds to the four vertex $C(p+r, q+s)$ of the parallelogram $OACB$ (Fig. 2). For those familiar with vectors, let's write it like this: $\overrightarrow{OC} = \overrightarrow{OA} + \overrightarrow{OB}$. (We see that the consonance of the terms “medianta” and “mediana” is not accidental: the segment $OC$ goes exactly along the median of the triangle $OAB$.)

d) $|qr-ps|$ is equal to twice the area $\Delta AOB$, that is, the area of ​​the parallelogram $OACB$.

e*) Inside and on the sides of this parallelogram $OACB$ if and only if there are no nodes (except for vertices) when $|qr-ps|=1$.

e*) In this case, the point $C$ is the node closest to $O$ on the grid lying inside the corner $AOB$.

Right 12. Prove properties a)—r).

The key to explaining the regularity of the Farey series is properties d) and e*).

Let us visualize figure 2 and 3. On them, the interior of the angle $AOB$ is cut by straight lines into parallelograms congruent to the parallelogram $OACB$. All their vertices lie in the nodes of checkered paper. But on figure 2 (where the area of ​​$OACB$ is greater than 1) many nodes of the internal angle $AOB$ are not the vertices of these parallelograms. And on figure 3 (here the area $OACB$ is equal to 1) any node of the internal angle $AOB$ is the vertex of such a parallelogram, i.e. for any such node $M(n, m)$ there are natural numbers $x$ and $y$ for which

$$\overrightarrow{OM} = x \cdot \overrightarrow{OA} + y \cdot \overrightarrow{OB}.$$

(6)

Vector equality (6) is equivalent to the system of equations

$$\begin{cases} px + ry = m, \\ qx + sy = n. \end{cases}$$

*). They can be proven based on the properties of lattices on the plane (see articles by A. A. Egorov and N. B. Vasiliev, «Kvant», 1974, No. 12.

13. a) Prove that if $|qr-ps|=1$, where $p, q, r, s$ are integers, then system (7) for any integers $m$ and $n$ has a solution in the integers $x$ and $y$.

b*) Form and prove the converse theorem.

b) Deduce from a) that for two close fractions $p/q < r/s$ any fraction $m/n$, where $p/q < m/n < r/s$, can be represented as $\frac{px+ry}{qx+sy}$, where $x$ and $y$ are natural numbers.

d) Prove the properties of e* from points 2 and 5 and derive the laws A and B from the Farey series.

Conclusion

We have outlined several ways to construct a small but beautiful theory of Farey series.

This theory can be built at the very beginning of the study of integers, without relying on the fundamental theorem of arithmetic (on the uniqueness of factorization). This theorem itself can be derived from the properties of Farey series. From these properties it is also easy to obtain solutions in integers to the equation $ax-by=1$, where $a$ and $b$ are simple: it is enough to consider the fraction $\frac{a}{b}$ and take any of its neighboring fractions in the Farey series.

Farey series, as well as the representation of fractions on a lattice, are also useful in more subtle questions of approximating real numbers by fractions with small values.

Literature

1. N. B. Vasiliev. Solution problem M233. «Kvant», 1974, No. 7, p. 39.
2. I. M. Vinogradov. Fundamentals of number theory. M., “Science”, 1965.
3. K. Chandraekharan. Introduction to analytic number theory. M., "Mir", 1974.
4. D. B. Fuks, M. B. Fuks. "On the best approximations." «Kvant», 1971, nos. 6 and 11.
