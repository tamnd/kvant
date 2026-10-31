---
id: 1971-12-gerver-zadacha-o-chislah-v-tablitse-b0009d5c
issue: kvant_1971_12
year: 1971
number: "12"
title: Problem about numbers in a table
authors:
  - Гервер М. Л.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 26
page_last: 28
page_labels: 24-26
tag: 551W
lang: en
source: kvant_digital
extraction: vision
content_sha256: 1ce92535dce984ca66098b15e7e11f708cb674a978da33f60072fef0ef7c6e20
prompt_sha256: draft-1
translated_from: content/ru/1971/12/articles/05_gerver-zadacha-o-chislah-v-tablitse-b0009d5c.md
source_content_sha256: d00ac8e132264ce4b1b8f10d31a604c1646e78980d5dc6a2e5e74325cc4b5d3a
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 24⟧

Problem about numbers in a table

M. L. Gerver

In «Kvant» No. 7 of 1971, on page 21, the following problem was formed.

In the square table $6 \times 6$ the numbers 1, 2, 3, ..., 36 are arbitrarily considered. Prove that there are two average numbers a and b, standing in adjacent cells, and also that a—b $\geq 5$.

Several years ago, a similar problem was proposed at the Moscow Mathematical Olympiad: to prove that in the table $9 \times 9$, filled with polar numbers, there are two adjacent numbers with a difference greater than or equal to 6.

Below we will solve the general problem for the table $n \times n$, and we will obtain an exact (unimprovable) estimate for the maximum difference between neighboring numbers.

Problem formulation

In the table $n \times n$ the numbers 1, 2, ..., $n^2$ are arbitrarily considered. Prove that there are two adjacent numbers whose difference is not less than n.

Explanation. Let us clarify the term “neighboring numbers”. We call two numbers adjacent if the cells of the table in which they appear have a common side.

Preliminary remarks

It is easy to consider the numbers 1, ..., $n^2$ in the table $n \times n$ so that the difference of any two adjacent ones does not exceed 了她. Examples of such an arrangement at $n=5$ are given in Tables 1 and 2.

From Table 1 it is possible (by rearranging the columns) to obtain another 119 = 5!—1 tables in which the difference between adjacent numbers is not

Table 1.

1 2 3 4 5

6 7 8 9 10

11 12 13 14 15

16 17 18 19 20

21 22 23 24 25

Table 2.

1 3 6 10 15

2 5 9 14 19

4 8 13 18 22

7 12 17 21 24

11 16 20 23 25

ascending 5. In table 2, without increasing the maximum difference between adjacent numbers, you can rearrange the numbers located further from the diagonal going from the lower left to the upper right corner of the table; for example, you can swap 1 and 2 or 23 and 24, etc. Completely similar examples can be constructed for any n.

There are many ways to consider the numbers 1,..., $n^2$ in the table $n \times n$ such that the maximum difference between adjacent numbers is n. He asks, is it possible to consider numbers so that the maximum difference is less than n?

It turns out that this cannot be done - this is exactly what we are going to prove.

⟦folio 25⟧

Solution of the problem for $n=4$

The idea on which the solution is based is especially easy to present with small $n$. Let's take table $4 \times 4$, select 4 cells in it, which contain the numbers 1, 2, 3 and 4. Let's put asterisks in those of the remaining cells of the table that are adjacent to the selected ones (Table 3). Note that even if the selected cells are on the edge or corner of the table, there will be no less than four stars (check this yourself). Now, no matter how we arrange the numbers 5, 6, ..., 16 in the table, one of the cells with an asterisk will contain the number $a$, greater than or equal to 8 (since there are at least 4 asterisks, and there are only three numbers less than 8 left: 5, 6 and 7). This cell is adjacent to at least one of the cells containing the numbers 1, 2, 3 and 4. So, the number $a \geq 8$ is adjacent to some number $b \leq 4$. Thus $a-b \geq 4$.

We have proven that for any arrangement of the numbers 1, 2, 3, 4, ..., 16 in the table, $4 \times 4$ will find two neighboring numbers $a$ and $b$ such that $a-b \geq 4$.

What's next?

The above can lead to the following final conclusion.

Let us select cells in the table $n \times n$ that contain the numbers 1, 2, ..., $n$. Let's put stars in those of the remaining cells that are adjacent to the selected ones. Let's give them $n$ some stars. Therefore, no matter how you put the numbers $n+1$, ..., $n^2$ in the table, there will be a number $a \geq 2n$ that falls into the cell with an asterisk and turns out to be adjacent to some number $b \leq n$. The difference of the numbers $a-b$ is obviously greater than or equal to $n$.

There is one error in the above reasoning: the statement printed in italics is incorrect. It is already incorrect for $n=5$: if we arrange the numbers 1, ..., $n^2$. Then there is a number $m$ ($1 < m < n^2$), which has the following property: if we mark the mouse cells in which the mouse is on the edge or in the corner of the table, then there will be no less than four stars (check this yourself). Now, no matter how we arrange the numbers 5, 6, ..., 16 in the table, one of the cells with an asterisk will contain the number $a$, greater than or equal to 8 (since there are at least 4 asterisks, and there are only three numbers less than 8 left: 5, 6 and 7). This cell is adjacent to at least one of the cells containing the numbers 1, 2, 3 and 4. So, the number $a \geq 8$ is adjacent to some number $b \leq 4$. Thus $a-b \geq 4$.

Lemma. Let the numbers 1, ..., $n^2$ be arranged in the table $n \times n$. Then there is a number $m$ ($1 < m < n^2$), which has the following property: if we mark the mouse cells in which the mouse is on the edge or in the corner of the table, then there will be no less than four stars (check this yourself). Now, no matter how we arrange the numbers 5, 6, ..., 16 in the table, one of the cells with an asterisk will contain the number $a$, greater than or equal to 8 (since there are at least 4 asterisks, and there are only three numbers less than 8 left: 5, 6 and 7). This cell is 相邻 in the table of numbers 1, ..., $n^2$, there is a number $a \geq 2n$ that falls into the cell with an asterisk and turns out to be adjacent to some number $b \leq n$. The difference of the numbers $a-b$ is obviously greater than or equal to $n$.

1 case. Each column contains a number not exceeding $k-1$, but there is a row that does not contain any of the numbers 1, ..., $k-1$.

⟦folio 26⟧

Table 5.

| 1 | 2 | 3 | 4 | 5 |
| :---: | :---: | :---: | :---: | :---: |
| 6 | 7 | 8 | 9 | 10 |
| 11 | 12 | 13 | 14 | 15 |
| 16 | 17 | 81 | 19 | 20 |

Table 6.

| 1 | 2 | 4 | 6 | 8 |
| :---: | :---: | :---: | :---: | :---: |
| 3 | * | * | * | * |
| 5 | * | | | |
| 7 | * | | | |

In this case, we put $m=k-1$ (for example, $m=20$ in Table 1 and $m=8$ in Table 4).

Let us show that $m$ satisfies the requirements of the lemma.

Let's mark the cells containing the numbers 1, ..., $m=k-1$, and put asterisks in those of the remaining cells that are adjacent to the marked ones (Tables 5, 6).

Each column contains check boxes. In addition, each column has at least one unchecked cell (since the entire row does not contain marked cells). Therefore, there is at least one asterisk in each column. All columns $n$; this means that the asterisk is at least $n$.

Psluay. Each line contains a number not exceeding $k-1$, but there is a line that does not contain any of the numbers 1, ..., $k-1$.

This case will coincide with the one already discussed: it is enough to reflect the table relative to the main diagonal (this operation is called *painting*).
