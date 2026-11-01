---
id: 1985-7-chvanov-zadacha-o-dominirovanii-ferzey-33f9bc6f
issue: kvant_1985_7
year: 1985
number: "7"
title: Queen domination problem
authors:
  - Чванов В. Г.
rubric: igry-i-golovolomki
rubric_sub: Игры и головоломки
page_first: 62
page_last: 64
page_labels: 60-62
tag: 24HD
lang: en
source: kvant_digital
extraction: vision
content_sha256: 207be2634addc7a4030930f6ed54ea57c72e54613076cc1061e1c80c4186ce4d
prompt_sha256: draft-1
translated_from: content/ru/1985/07/articles/17_chvanov-zadacha-o-dominirovanii-ferzey-33f9bc6f.md
source_content_sha256: 3745b926816893366d3269346f6e14018c88ede7457e3bf6ed8de9c88d656dd3
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 60⟧

Queen Domash Problem

V. G. CHVANOV

In the article by M. Mamikon in «Kvant» 1977, No. 12, the following problem was considered:

The homemaking problem. What is the minimum number of queens $F(n)$ that can be placed on the chessboard $n \times n$ so that they attack all its free squares?

The numbers $F(n)$ are known only for small $n (n \leq 11)$, given in Table 1.

Table 1

| $n$ | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | 12 | ... |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| $F(n)$ | 1 | 2 | 3 | 3 | 4 | 5 | 5 | 5 | 5 | ? | ... |

On figure 1 the placements of queens on boards $3 \times 3$, $8 \times 8$, $11 \times 11$ are given, for which $F(n)$ are equal to 1, 5 and 5, respectively. For large $n$ the problem has its own solution.

The article by M. Mamikon provides the following estimates for $F(n)$:

$$F(n) \geq \frac{n-1}{2},$$

$$F(n) \leq \frac{5}{8} n + 16 \sqrt{n}.$$

Our goal is to provide some examples to improve these estimates and formulate problems associated with them, in the hope that the reader will independently progress in solving the homework problem.

The first geometric idea - punching the border

The placement of queens on the board $n \times n$, for which $F(n) = (n-1)/2$ (the lower bound of M. Mamikon is realized), is called ideal.

Examples include the placements shown at figure 1 (at $n=3$ and $n=11$).

After applying 4 $(n-1)$ cells located along its edge. With an ideal placement (see Fig. 1a, 6) each queen will have exactly 8 squares on each of these squares, its square cannot be penetrated by two queens, so the number of queens is 4 $(n-1):8=(n-1)/2$, which gives us the lower estimate (1). The complete proof of this is in the article by M. Mamikon.

Problem 1 (unsolved). Are there ideal placements other than the two listed? Is there a finite number of ideal placements? (Hyotesis: the answer to the last question is yes.)

A necessary condition for home mashing, placed, is home mashing on the border. Therefore, it is interesting to know for which boards it is possible to homework on the border $(n-1)/2$ with queens. M. Mamikon proved that such boards are boards $n \times n$ with $n=2(k^2+l^2)+1$, where $k$ and $l$ are coprime numbers of different parities. But the boards do not exhaust this list either. An example would be placement on figure 2 $(n=15)$; I came up with another such placement for the board $n \times n$, $n=27$. These placements are used in that they maintain the numerical equality of the ferrules located only in opposite squares formed by the intersection of the main diagonals.

⟦folio 61⟧

The second geometric idea is to move the $k$-queen outside the central square

Consider the $k$-queen on figure 4,6 and replace the four corner queens with two queens lying outside the central square $m \times m$ ($m=5$) as shown in figure 5. We then get a $k$-queen from the $2m-1$ pieces dominating the board $3m \times 3m$. Further reduction in the number of figures is impossible, since the square $m \times m$ has $2m-1$ diagonals.

However, when we move the pieces along their diagonals outside the central square, it turns out that it is possible to get a $k$-queen dominating a board larger than $3m \times 3m$ by increasing the number of attackable ranks and files (see figure on the fourth cover page). Naturally they will ask.

Problem 4. What is the maximum size of a square dominated by a $k$-queen out of $2m-1$ pieces?

I don’t know the answer to this question, but another series of $k$-queens are given as examples, which allow measurably to improve the upper bound for $F(n)$. In particular, for any $m$ from the series $m=12c+9$ ($c=0,1,2,...$), one can construct a $k$-queen from $2m-1$ pieces that dominates the $n \times n$ board, where $n=42c+31=(7m-1)/2$. Thus, for all $n$ from the series $n=42c+31$ ($c=0,1,2,...$), we get the estimate

$$F(n) \leq \frac{4n-5}{7}.$$

Note that the number of verticals (as well as horizontals), as well as such $k$-queens, is equal to $l=(3m-1)/2$.

The $k$-queen shown on the cover is one of the $k$-queens in this series (at $c=0$). Let's take a closer look at it. It consists of 3 groups of figures that have certain “constructive” advantages. Each group, taken separately, attacks in all directions a column of rows, as many figures as it contains. Moreover, in the vertical and one of the dia-

⟦folio 62⟧

In gonal directions the rows are attacked without breaks, in another - every third row is attacked, in horizontal - every second. The outer groups contain $\frac{2}{3}m-1$, and the middle one contains $\frac{2}{3}m$ pieces, placed by sequential knight moves along parallel lines 1-1, 2-2, 3-3. The 1-1 line runs through the center square of the board. The distances between lines 2-2, 3-3 and lines 1-1 are chosen so that outside the board $m \times m$ on its 2 sides (see figure on the cover) there are $\frac{m-1}{4}$ pieces of each extreme group. But at the same time, part of the figures of each group leaves the blue zone and a gap is formed in it (shown in green) in a continuous diagonal opening. Pieces that leave the blue zone are returned to it by parallel transfer along their diagonals so as to close the gap that has formed.

Improving the lower bound for $F(n)$

Now let's return to the lower estimate $F(n)$. It can be improved by placing a score of $F(n)$ for boards $n \times n$ comparable modulo 4.

Problem 5. Prove for each type of board $n \times n$ the following estimates $F(n)$:

$$n = 4k \quad F(n) \geq \frac{n}{2},$$

(4)

Note. The number of squares on the edge of the board dominated by $\frac{n-1}{2}$ queens is a multiple of 8; number of figures in ideal arrangement $F(n) = 2k+1$.

Problem 6. Given $\frac{n-1}{2}$ vertical, horizontal, ascending and descending diagonal lines. Indicate all the values ​​$n$ for which it is possible to cross out all the cells of the board $n \times n$ with these lines (they go through the centers of the cells).

Problem 7 (unsolved). Is there a finite number of boards for which estimates (4), (5), (6) are performed? Hypothesis: the number of such boards is finite.

Estimates (4), (5), (6) allow us to expand Table 1. Indeed, taking them into account, we can write that $F(12) \geq 6$; $F(13) \geq 7$; $F(17) \geq 9$; $F(12)=6$ and $F(13)=7$ are easy to obtain by delivering placements $F(11)=5$ (Fig. 1 "6") to sizes $12 \times 12$ and $13 \times 13$ with an additional piece placed in the corner square of the board. The placement of $F(17)=9$ is shown on figure 6.

It is convenient to evaluate the “quality” of one or another dominant placement using the relation $\mu = \frac{F(n)}{n}$. So, our results can be presented in the form of Table 2.

Table 2 is worth following, but we leave its analysis to the reader. Let us only note the following that the board $8 \times 8$ is the most suitable and formal for the placement of $F(n)$ allowing us to answer this question for now.

Problem 8 (about external dominance). What is the maximum number of queens that can be placed on an infinite chessboard so that all boards $n \times n$ are attacked?
