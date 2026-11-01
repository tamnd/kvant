---
id: 1978-8-fomin-biletyi-i-yaschiki-f1b08221
issue: kvant_1978_8
year: 1978
number: "8"
title: Tickets and boxes
authors:
  - Фомин С. В.
rubric: raznoe
rubric_sub: Разное
page_first: 46
page_last: 48
page_labels: 44-46
tag: Z5UL
lang: en
source: kvant_digital
extraction: vision
content_sha256: 384ec3b17058125696e2149e489ee6ec7b1c3dc01679755e6c5900672da04ef7
prompt_sha256: draft-1
translated_from: content/ru/1978/08/articles/10_fomin-biletyi-i-yaschiki-f1b08221.md
source_content_sha256: 9ecb63663755b100b05dd9b7861988eedfb67562d576c9c8da21105d73999807
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 44⟧

S. Fomin

Tickets and boxes

This note solves the problem by proposing in 1977 the second (research) type XI All-Union Olympiad in mathematics. This problem was placed in the “Assignment for Quanta” («Kvant», 1977, No. 9, M465). Let us recall its formulation.

There are a thousand tickets with numbers 000, 001, ..., 999 and one hundred boxes with numbers 00, 01, ..., 99. The ticket is cut and placed in the box, if the box number can be obtained from the number of this ticket by crossing out one of the numbers. Prove that

a) you can put all the tickets into 50 boxes;
b) it is impossible to distribute all tickets into less than 40 boxes;
b) it is impossible to distribute all tickets into less than 50 boxes.

Let there be 10^k tickets with k-digit numbers from 00...0 to 99...9. The ticket is cut downwards
put it in the box, the number of which can be obtained from the number of this ticket; cross out one of the numbers. Prove that

1. Function F(k, N)

Let's start with a question that, at first glance, is not related to our task.

Let k and N be two natural numbers. Let us consider all possible sets of k non-negative integers whose sum is equal to N. For each such set we find the sum of the squares of the numbers included in it (Fig. 1). We denote the smallest of these sums by F(k, N). Let it correspond to the set A = {a₁, a₂, ..., aₖ}.

Lemma. Each digit included in set A differs by no more than 1.

Proof. Let's assume the opposite. Let, say, a₂ > a₁ + 1. Consider the set A' = {a₁ + 1, a₂ - 1, a₃, ..., aₖ}.

Since

$$\left( a_1 + 1 \right)^2 + \left( a_2 - 1 \right)^2 = a_1^2 + a_2^2 - 2 \left( a_2 - a_1 \right) < a_1^2 + a_2^2,$$

the sum of the squares of the numbers included in the set A' is less than the similar sum for A. The opposite obtained proves the lemma.

Now it is clear how to calculate F(k, N). You need to divide N by k with a remainder and select k numbers so that each of them is either equal to the quotient or 1 greater than it, and the sum of these numbers is equal to N.

On figure 2 there is a table of values ​​of the functions F(k, N) for small k and N.

What is the "geometric" interpretation of F(k, N)? Let for simplicity let k = 3. Then the problem of finding F(k, N) can be perceived as follows: find in the triangle ABC defined in the space of equations x₁ + x₂ + x₃ = N and the inequalities x₁ ≥ 0,

⟦folio 45⟧

Fig. 2.

$x_2 \geq 0, x_3 \geq 0$ (Fig. 3), power $M$ with integer coordinates, least distant from the origin $O$ (the sum of squares we are interested in is nothing more than the square of the distance from the point $O$ to $M$). Naturally, we need to take this point to the base of the redistribution lowered from $O$ to the plane of the triangle $ABC$, that is, to the point $\left(\frac{N}{3}; \frac{N}{3}; \frac{N}{3}\right)$.

For $k > 3$ similar expansions are possible using the concept of $k$-dimensional space.

Let's consider another interpretation of $F(k, N)$. Let $k = 2$ for simplicity. Then the sets under consideration have the form $|a, N - a|(a - \text{целое неотрицательное})$, and we are faced with the task of finding the minimum of the function $x \rightarrow x^2 + (N - x)^2$ defined on the set of integers from intervala $[0, N]$. This function is a quadratic trinomial; the minimum is reached at point $x = \frac{N}{2}$. Therefore $F(2, N)$ is equal to $\frac{N^2}{2}$ or $\frac{N^2 + 1}{2}$ depending on the parity of $N$ (Fig. 4).

For $k > 2$ one needs to consider the corresponding function of $k - 1$ variables and find its minimum.

2. Solving problems a) and b)

Let's arrange all the boxes in the form of a square $10 \times 10$, as shown in Fig. 5, $a$. On Fig. 5, $b$ this square $Q_0$ is drawn in the form familiar to us; Let's assume that each of its cells is a box with a corresponding number. Let's number the rows and columns of this square with numbers from 1 to 9. Since all the numbers in the conditions of the problem are equal, the rows and columns of the square $Q_0$ can be rearranged.

We need to select a certain number of boxes and put all the tickets into these boxes. Let's agree to paint the cells corresponding to the selected boxes as $Q_0$. Let the minimum number of cells

⟦folio 46⟧

CURRENT, namely $n_0$, is shaded in the zero line; we can consider these to be the first $n_0$ cells of the line. Let us now distance the square $Q_1$ obtained from $Q_0$ by crossing out the first $n_0$ rows and the first $n_0$ columns (Fig. 6). Let us show that all cells $Q_1$ must be shaded. To do this, take boxes numbered $xy$, where $x \geq n_0$, $y \geq n_0$. It must include ticket $0xy$: it cannot be placed in boxes $0x$ and $0y$, since the corresponding cells are not filled in. This means that the cell with number $xy$ must be shaded for all $x \geq n_0$, $y \geq n_0$.

After the topic, how many cells are shaded in our square $Q_0$. Each line of the rectangle $\Pi_0$ (see Fig. 6) has at least $n_0$ cells shaded. In $Q_1$ all $(10-n_0)^2$ cells are shaded. Thus, at least $n_0^2 + (10-n_0)^2$ cells are shaded in $Q_0$. The smallest of these sums is $F(2, 10)$ 50. So, in any case, at least 50 cells are shaded in $Q_0$. On the other hand, fifty boxes with numbers written out at figure 7 are enough: having crossed out a number in the number of each ticket so that two digits of the same parity remain, we will place this ticket in the corresponding box. These two messages complete the solution to points a) and b) of the problem.

3. Solution to problem d)

Now let the tickets be $k$-digit. We will assume that we have not 10 digits, but $N$, where $N$ is some arbitrary natural number (as if

we adopted the $N$-ary number system).

The rows of the square $Q_0$ will now enumerate the numbers from 0 to $N-1$; thus there are $Q_0$ total $N^2$ cells.

As before, we will assume that in the zero row there are $n_0$ filled cells, and in any other row there are no less than $n_0$. Let us similarly construct the square $Q_1$. Let's do with $Q_1$ the same way as we did with $Q_0$ - we select the row in it that has the least number of shaded cells (let this be its first row, i.e. the row with number $n_0$ in the original square), denote the number of shaded cells in it by $n_1$ and, throwing out the first ones from $Q_1$ $n_1$ rows and columns, we get a square $Q_2$. We will build with it in the same way, and so on, up to the square $Q_{k-2}$ (Fig. 8). Primogolniki similar to $\Pi_0$ will be denoted by

Fig. 7.
