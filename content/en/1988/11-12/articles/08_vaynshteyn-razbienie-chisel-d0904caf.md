---
id: 1988-11-12-vaynshteyn-razbienie-chisel-d0904caf
issue: kvant_1988_11-12
year: 1988
number: 11-12
title: Number partitioning
authors:
  - Вайнштейн Ф. В.
rubric: raznoe
page_first: 21
page_last: 27
page_labels: 19, 22, 23, 24, 25
tag: ER1M
lang: en
source: kvant_digital
extraction: vision
content_sha256: bbfc359362ee9fd10581c69bf33928e311302f3b9284e1643d2ddf1c41fd1d8a
prompt_sha256: draft-1
translated_from: content/ru/1988/11-12/articles/08_vaynshteyn-razbienie-chisel-d0904caf.md
source_content_sha256: e6cbe1e0e535df33a378ae6253c20bcf6f5bbdd60ba874003b5c0721efb77db6
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 19⟧

SPLITING NUMBERS

F. V. WEINSTEIN

A partition is a natural number represented as a sum of natural terms, and the terms themselves are called parts of the partition. The order of the terms does not matter; so the partitions 3=1+2 and 3=2+1 are not different. We will write down the partitions, listing their parts separated by commas in non-increasing order. For example, the partition 4=2+1+1 is written as (2, 1, 1).

Let $p(n)$ denote the number of all partitions of the natural number $n$. For small $n$ it is easy to calculate $p(n)$ simply by writing out all the partitions. For example, $p(5)=7$. Here are all 7 divisions of the number 5: (5), (4, 1), (3, 2), (3, 1, 1), (2, 2, 1), (2, 1, 1, 1), (1, 1, 1, 1, 1). However, it is unthinkable to obtain, say, $p(100)=190\ 569\ 292$ in this way without the help of a computer. Meanwhile, $p(100)$ was known back in the last century. We will introduce you to many interesting properties of partitions and teach you how to find $p(n)$ without writing out all the partitions of $n$.

The problem of calculating $p(n)$ is quite old. It was first formulated by Leibniz in 1654, and in 1740 it was proposed by the German mathematician Philipp Naudet to Leonard Euler. While studying partitions, Euler discovered a number of their properties, among which the famous “pentagonal theorem” occupied the main place. Euler's research begins the history of partition theory, in the development of which the greatest mathematicians of subsequent generations took part.

⟦folio 22⟧

le, etc., until you reach the number $k_q$.

For example, dividing the number 25 into odd parts (9, 9, 5, 1, 1) will correspond to the picture depicted at figure 1. It consists of angles symmetrical with respect to the diagonal, so that in the uppermost corner there are $2k_1+1$ points, in the next $2k_2+1$ points, etc., and in total there will be $n$ points. Now let’s draw lines on the same map as shown in figure 2, count the number of points on each of these lines and the partition numbers obtained in this way. It turns out that all parts of this partition are different.

Exercise 5. Prove this statement.

In our example, the partition will be (9,6,5,4,1). Think about how to construct a partition into odd parts from a partition into different parts, i.e., restore the original symmetric map from such a partition.

Digression: solving problem M1065

This section uses a more complex technique than the rest of the article. If you wish, you can skim through it without going into details and continue reading from the next section. So, let's solve problem M1065 from “Problem «Kvant»” (1987, No. 9). Let us recall its formulation.

We consider vectors $(x, y)$ with integer non-negative coordinates, and at least one of the coordinates is different from 0. We call such a vector a generator if $|x-y|=1$.

a) Prove that the vector $(x, y)$ under consideration can be represented as a sum of different generators (or itself as a generator) if and only if the quantity $k(x, y)=x+y-(x-y)^2$ is non-negative.

b) Prove that the number $N(x, y)$ of different (up to order) represented by the vector $(x, y)$ as a sum of different generators depends only on the number $k=k(x, y)$. Find $N(13, 18)$.

The solution to the problem begins with finding the general form of integer solutions to the inequality $k(x, y) \geq 0$. The numbers $x+y$ and $x-y$ have the same parity, so $k(x, y)$ is an even number for any integer $x, y$. Therefore, for any integer $m \geq 0$ it is sufficient to find integer solutions to the equation $x+y-(x-y)^2=2m$. Let's put $x-y=q$. Then $x+y=2m+q^2$. From these two equalities we immediately obtain:

$$\begin{align*}
(x, y) &= (m+q(q+1)/2, \\
m+q(q-1)/2),
\end{align*}$$

where $q$ is any integer, and $m \geq 0$.

The meaning of the numbers $m$ and $q$ becomes more important if we imagine vectors of the form (3) at $m=0$ as points with integer coordinates of the paraboles $k(x, y)=0$ lying in the plane $(x, y)$. (Do you understand why this is a parabola?) Then the integer solutions of the inequality $k(x, y) \geq 0$ that we obtained show that all points with integer coordinates lying on the parabola $k(x, y)=0$ and inside it are obtained by shifting the integer points of this parabola onto the vectors $(m, m)$ (Fig. 3). It is convenient to assume that the number $m(m=0, 1, 2, ...)$ is the number of the parabola on which the point $(x, y)$ lies, and $q=x-y=0, \pm 1, \pm 2, ...$ is the number of the point on this parabola.

Since symmetry problems are relative to the permutation of coordinates of vectors, it is sufficient to derive all statements for vectors $(x, y)$ such that $x \geq y$, i.e. for vectors of the form (3) with $q \geq 0$.

Let us prove the sufficient condition in paragraph a) of the problem. Using the formula for the sum of an arithmetic progression

$$\begin{align*}
1+2+\dots+(q-1)+m+q &= m+q(q+1)/2; \\
0+1+\dots+q-2+m+(q-1) &= m+q(q-1)/2.
\end{align*}$$

⟦folio 23⟧

Posny's formulas $(x, y) = (1, 0) + (2, 1) + \dots + (q-1, q-2) + (m+q, m+q-1)$ for $q > 0$ and $(m, m) = (1, 0) + (m-1, m)$ for $q = 0$, $m > 0$ give representations of $(x, y)$ as a sum of different generators.

Proving the necessity of the condition is also easy. Let
$x = r_1 + \dots + r_a + s_1 + \dots + s_b$
$y = r_1 + \dots + r_a - a + s_1 + \dots + s_b + b$
poseable $x - y = a - b$. Let's put $q = x - y$ and
$m = (r_1 - q) + (r_2 - (q - 1)) + \dots$
$\dots + (r_q - 1) + r_{q+1} + \dots + r_a +$
$+ s_1 + \dots + s_b = x + y - q(q + 1)/2$
(here we again used the formula for the sum of an arithmetic progression). From inequalities (4) it follows that $r_a \geq 1, r_{a-1} \geq 2, r_{a-2} \geq 3, \dots$ and in general $r_i \geq q - i + 1$. Pozny $m \geq 0$, i.e. $(x, y)$ is a vector of the form (3), which is what was required.

In geometric terms, statement 6) means that the number

$$N(x, y)$$ depends only on the number $m$ of the parabola and does not depend on the number $q$ of the point on the parabola.

Let $T(m, q)$ be the set of representations of vector (3) as a sum of different generators and $t(m, q)$ be the number of such representations. The problem will be solved if we prove that for any integer $q$ the equality $t(m, q) = t(m, q - 1)$ holds (this means that $t(m, q)$, and with it $N(x, y)$, does not depend on $q$). We set aside above the set $T(m, q)$ with the set of pairs of sequences satisfying inequalities (4) such that $r_1 + \dots + r_a + s_1 + \dots + s_b = m + q(q + 1)/2$ for $q = a - b$. We will write such a pair in the form $(r_1, \dots, r_a | s_1, \dots, s_b)$.

Consider the mapping $\varphi$ from the set $T(m, q)$ into the set $T(m, q - 1)$ given by the formula
$$\varphi(r_1, \dots, r_a | s_1, \dots, s_b) = \begin{cases} (r_1 - 1, \dots, r_a - 1 | s_1 + 1, \dots, s_b + 1, 0), \\ \text{если } r_a > 1, \\ (r_1 - 1, \dots, r_{a-1} - 1 | s_1 + 1, \dots, s_b + 1), \\ \text{если } r_a = 1. \end{cases}$$

Exercise 6. Check that $\varphi(r_1, \dots, r_a | s_1, \dots, s_b) \in T(m, q - 1)$.

To prove that $\varphi$ is a one-to-one mapping, we construct the inverse mapping $\psi$: $T(m, q - 1) \rightarrow T(m, q)$, reading the rule given by $\varphi$, we follow:

$$\psi(r_1, \dots, r_a | s_1, \dots, s_b) = \begin{cases} (r_1 + 1, \dots, r_a + 1, 1 | s_1 - 1, \dots, s_b - 1), \\ \text{если } s_b > 0, \\ (r_1 + 1, \dots, r_a + 1 | s_1 - 1, \dots, s_b - 1), \\ \text{если } s_b = 0. \end{cases}$$

The constructed mappings are mutually inverse, therefore $\varphi$ is a one-to-one correspondence. This means $t(m, q) = t(m, q - 1)$, as stated.

To learn how to calculate the values ​​of $N(x, y)$, set between the numbers $t(m, q)$ and $p(m)$.

Statement: $t(m, q) = p(m)$.

We already know that $t(m, q) = t(m, 0)$, so it is enough to prove that $t(m, 0) = p(m)$. Let's use a simple and useful graphical tool called a Younes diagram.

⟦folio 24⟧

I appreciate it. Consider, for example, the partition (6, 4, 4, 2, 1). His Young diagram is shown on figure 4 (the first line has 6 dots, the second - 4, the third - 4, the fourth - 2, the fifth - 1). Any partition can be depicted in the form of a Young diagram and the partition can be written along the entire Young diagram.

Let's draw a diagonal on the Young diagram - a black line on figure 4. Let $r_1$ be the number of points in the first line lying on the diagonal and to the right of it, $r_2$ the number of points in the third line lying on the diagonal and to the right of it, etc.; $s_1$ is the number of points of the first column under the diagonal, $s_2$ is the number of points of the second column under the diagonal, etc. Let us put in accordance with the Young diagram, the partition of the number $m$, a pair of the sequence

$$\left( r_1, r_2, \dots | s_1, s_2, \dots \right),$$
$$r_1 + r_2 + \dots + s_1 + s_2 + \dots = m,$$

i.e., an element of the set $T(m,0)$. For example, the diagram at figure 4 corresponds to the pair (6, 3, 2|4, 2, 0). Know a couple of sequences, you can easily reconstruct the Young diagram. Consequently, we have established a one-to-one correspondence between the set of partitions and the set $T(m,0)$. The statement has been proven.

Now it costs nothing to answer the last question of the problem - about the value of $N(13,18)$. Since $13 = 3 + 5 \cdot 4/2$, $18 = 3 + 6 \cdot 5/2$, point (13,18) lies on the third parabola. So, $N(13,18) = t(3,0) = p(3) = 3$.

The following exercises are about using the Young diagram.

Exercises

7. The number of partitions $n$ with no more than $k$ parts is equal to the number of partitions $n$ with parts not exceeding $k$. Hint: Reflect the Young diagram in relation to the diagonal.

8. The number of partitions $n$ with different parts is equal to the number of partitions $n$ whose Young diagram is symmetric about the diagonal. Hint: remember Sylvester's correspondence.

Gauss-Jacobi formula

We did a lot of work in solving the M1065 problem. Is it possible to use arbitrary functions again and extract some red identity from the equality $t(m,q) = p(m)$?

$N(x,y)$ is the number of ways that the vector $(x,y)$ can be represented as the sum of different generators of the form $(k,k-1)$ and $(k-1,k)$. Reasoning in the same way as when deriving the formula for an arbitrary function of the number of partitions with different parts, we will write an arbitrary function for $N(x,y)$ (this is a series of two variables $u$ and $v$):

$$\prod_{k=1}^{\infty} \left( 1 + u^{k-1} v^k \right) \left( 1 + u^k v^{k-1} \right) = \sum_{x,y=0}^{\infty} N(x,y) u^x v^y.$$

Since $N(x,y) = t(m,q)$, where $x = m + q(q+1)/2, y = m + q(q-1)/2$, the equality can be divided:

$$\sum_{q=-\infty}^{\infty} \left( \sum_{m=0}^{\infty} t(m,q) u^m v^m \right) \times u^{q(q+1)/2} v^{q(q-1)/2}.$$

Let us now use that $t(m,q) = p(m)$ and continue the equality:

$$\sum_{q=-\infty}^{\infty} \left( \sum_{m=0}^{\infty} p(m) u^m v^m \right) \times u^{q(q+1)/2} v^{q(q-1)/2}.$$

The series in parentheses is an arbitrary function of the numbers of the partition $p(m)$, which we know (formula (1)), so we continue:

$$\prod_{k=1}^{\infty} \left( 1 - u^k v^k \right)^{-1} \sum_{q=-\infty}^{\infty} u^{q(q+1)/2} v^{q(q-1)/2}.$$

Now let’s equate the left side of the first and the right side of the last equality, multiplying both sides by $\Pi(1 - u^k v^k)^{-1}$. We get the final result:

$$\prod_{k=1}^{\infty} \left( 1 + u^{k-1} v^k \right) \left( 1 + u^k v^{k-1} \right) =$$

⟦folio 25⟧

$$\sum_{q=-\infty}^{\infty} u^{q(q+1)/2} v^{q(q-1)/2}.$$

This sameness is the goal of our transformations. It is called the Gauss-Jacobi formula. From this wonderful identity with two variables one can obtain many different identities with one variable.

Exercise 9. Substitute $u=-t$, $v=-t^2$ into the Gauss-Jacobi formula and obtain Euler's pentagonal theorem.

Now let’s substitute $u=v=-t$ into the Gauss–Jacobi formula. On the left side you get:

$$\prod_{k=1}^{\infty} (1-t^{2k-1})^2 (1-t^{2k}) = \prod_{k=1}^{\infty} (1-t^{2k-1}) \prod_{k=1}^{(1-t^k)}.$$

Replacing the product $\Pi(1-t^{2k-1})$ with $\Pi(1+t^k)^{-1}$ according to formula (2), we transform the left-hand side into $(1-t)(1-t^2)(1-t^3).../(1+t)(1+t^2)(1+t^3)...$.

When substituting $u=v=-t$, the right-hand side of the Gauss-Jacobi formula turns into $\sum_{-\infty}^{\infty} (-1)^q t^q$. We get the following formula:

$$\frac{(1-t)(1-t^2)(1-t^3)...}{(1+t)(1+t^2)(1+t^3)...} = 1-2t+2t^4-2t^9+2t^{16}-...$$

Substituting $u=t$, $v=1$ into the Gauss–Jacobi formula similarly leads to the formula:

$$\frac{(1-t^2)(1-t^4)(1-t^6)...}{(1-t)(1-t^3)(1-t^5)...} = 1+t+t^3+t^6+t^{10}+...$$

These two formulas were obtained by Gaus. Needless to say, these are amazingly beautiful formulas!

Rogers–Ramanujan identities

In conclusion, I want to introduce you to two meanings of the identities of partition theory, for which arbitrary proofs have not yet been found, although this problem remains in the sphere of interests of many mathematicians.

The first identity. The number of partitions of the natural number $n$ in which the difference between any two parts exceeds one is equal to the number of partitions of the number $n$ into parts that give a remainder of 1 or 4 when divided by 5.

Second identity. The number of partitions of the natural number $n$ in which the difference between any two parts and each part exceeds one is equal to the number of partitions of the number $n$ into parts that give a remainder of 2 or 3 when divided by 5.

Of course, the pattern established by these identities is extremely beautiful and non-trivial, and it is not surprising that the greatest English mathematician of the century, G. Hardy, who learned about them from Ramanujan’s letter dated January 16, 1913, was delighted.*)

When reading this article, you may have the impression that the theory of partitioning fills a cabinet of curiosities, in which various exotic experiments are carefully collected, and are in no way, or almost in no way, connected with each other. Until recently this was the case. The situation changed radically only in the 70s of the century, when the English mathematician I. MacDonald managed to find a unified approach to proving a large class of identities of the theory of partitioning and discover many new ones, combining them into a coherent theory (the Gauss-Jacobi identity is included in it).**) For the Rogers-Ramanujan identities and many similar identities, a general approach has not been found, although algebraic methods for them have recently appeared evidence.

So, understanding the true nature of these identities, it is believed, is still to come.

*) You can read about the life and work of the remarkable Indian mathematician in the article by S. G. Gindikin “The Riddle of Ramanujan” («Kvant», 1987, No. 10).

**) You can find more detailed information about this in the article by D. V. Fuchs “On opening brackets, about Euler, Gauss and MacDonald and about missed opportunities” («Kvant», 1981, No. 8).
