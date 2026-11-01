---
id: 1977-12-mamikon-zadacha-o-ferzyah-1e91c0c9
issue: kvant_1977_12
year: 1977
number: "12"
title: Queen problem
authors:
  - Мамикон М.
rubric: osnovnye-stati
page_first: 24
page_last: 28
page_labels: 22, 23, 25, 26
tag: WEXQ
lang: en
source: kvant_digital
extraction: vision
content_sha256: 6309454979d96ee3effe62161ead03d3e09216277ccd49ba38fc356db16c9ef8
prompt_sha256: draft-1
translated_from: content/ru/1977/12/articles/06_mamikon-zadacha-o-ferzyah-1e91c0c9.md
source_content_sha256: 3a8f453f68351f3e459f657882eec18e8e916ce87b1e5b9033d73576542811e3
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 22⟧

M. Mamikon

Queen problem

1. Statement of the problem
On a general 8x8 chessboard, five queens can be placed so that they cover all the squares of the board. Four queens are not enough for this (prove it!). A 3x3 board will have one queen placed on the center square. For a 6x6 board, its field is equal. So, $F(11) \leq 5$. From figure 2 it can be seen that $F(10) \leq 5$ and $F(9) \leq 5$.

Finding the exact $F(n)$ for large $n$ is quite difficult. Further, a perfect fast-running computer cannot, in a reasonable time, go through all the options for placing, say, ten queens on a 20x20 board.

It seems interesting to Pozny to find at least estimates—upper and lower—for $F(n)$. This will be our formulation of the queen problem.

2. Score
If on the board $n \times n$ we place $n$ queens along one of the main diagonals, and then remove the two outermost queens, then the remaining $n-2$ queens will also be all squares of the board. Means,

$$F(n) \leq n-2.$$

If, in an arrangement of $F(n)$ queens, in which each square is captured, there is not a single queen on the edge of the board, then the $4(n-1)$ edge squares forming the boards must be queens from inside this frame. Since each queen will be in the same direction, it will be exactly 8 cells of this frame. Even if all the queens were different squares of the frame, then it would be necessary to have $$\frac{4(n-1)}{8} = \frac{n-1}{2}$$

Fig. 1.

Three queens (Fig. 1) are enough, two are not enough.

Let us denote by $F(n)$ the minimum number of queens such that, if properly placed on the board $n \times n$, each of its squares is under attack (a square occupied by a queen is considered captured). For $3 \leq n \leq 8$ the number $F(n)$ is known:

| $n$ | 3 | 4 | 5 | 6 | 7 | 8 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| $F(n)$ | 1 | 2 | 3 | 3 | 4 | 5 |

On figure 2 there is a board $11 \times 11$ and 5 queens on it, each

⟦folio 23⟧

$$\frac{1}{2}n - \frac{1}{2} \text{ферзей. Итак, в этом случае}$$
$$F(n) \geq \frac{1}{2}n - \frac{1}{2}. \quad (2)$$

Estimate (2) is also correct in the general case. Prove it. (Indication: From (1) it follows that for any arrangement of $F(n)$queens on the remaining board, there are at least two free queen files and two free ranks.)

From (2) $F(11) \geq 5$. In paragraph 1 we indicated that $F(11) \leq 5$. So, $F(11) = 5$. $F(10) = 5$ is obtained similarly. It is curious that the equality $F(9) = 5$ cannot be obtained in this way. Prove it yourself!

Fig. 3.

Fig. 4. $k = 3, l = 1$.

Let's now work on improving the upper bound (1).

3. $\langle k, l \rangle = \text{решетка}$
Let's place the queens on an infinite chessboard with the left move of the $\langle k, l \rangle$-knight (the usual chess knight is the $\langle 2, 1 \rangle$-knight), namely: first put the queen on an arbitrary square; then we will place four more queens as shown in figure 3; We will do the same with each of the placed queens, etc. The resulting arrangement of an infinite number of queens is called a queen $\langle k, l \rangle$-lattice. Each $\langle k, l \rangle$-lattice is a square lattice, rotated relative to the chessboard (Fig. 4).

Moving along the row $^*$), we will periodically meet queens. Let us denote the length of the lattice period along the row by $W_p$. For example, for a $\langle 3, 1 \rangle$-lattice $W_p = 10$ (Fig. 4).

Moving along the diagonal, we will also encounter queens periodically. Let us denote the diagonal length of the lattice period by $W_\partial$. For a $\langle 3, 1 \rangle$-lattice $W_\partial = 5$ (Fig. 4).

Exercises

1. For a $\langle k, l \rangle$-lattice $W_p = \frac{k^2 + l^2}{d}$, where $d$ is the most common divisor of the numbers $k$ and $l$.
2. For a $\langle k, l \rangle$-lattice $W_\partial = \frac{k^2 + l^2}{c}$, where $c$ is the most common divisor of the numbers $k + l$ and $k - l$.
3. If $k$ and $l$ are relatively prime numbers of different parities, then $W_p = W_\partial = k^2 + l^2$.
4. The periods of the $W' \langle tk, tl \rangle$-lattice and the periods of the $W \langle k, l \rangle$-lattice are related by the relations $W_p = tW_p$ and $W_\partial = tW_\partial$.

4. Fundamental Queen Setup
Let $k$ and $l$ be coprime numbers of different parities. Let's consider the $\langle k, l \rangle$-lattice. For her, both periods $W_p, W_\partial$ are equal to $W_0 = k^2 + l^2$ (exercise 3).

Let's cut a square board $W_0 \times W_0$ from our infinite board so that the queen gets into the central

$^*)$ Row is vertical or horizontal.

⟦folio 25⟧

Let us prove that broken cells are symmetrical with respect to any main diagonal.

If a broken cell is gray (Fig. 6), then a symmetrical (relative to the distance of the main diagonal) cell is also gray, and all cells are broken. If the broken cell is white, then there is a queen on one of the diagonals passing through it. If this is the diagonal of the perendicule and the cul-de-sac of the main diagonal under consideration, then the symmetrical cell of interest to us will be the same queen. If it is paired with a centrally symmetric queen (see the green diagonal at figure 6).

From the fact that with symmetry relative to the main diagonal and a rotation of 90°, broken cells turn into broken ones, it easily follows that the set of broken cells is symmetrical relative to the central vertical and the central horizontal (why?).

This means that from the point of view of broken or unbroken cells, all eight octants into which the board is divided by central rows and main diagonals are equal (on figure 7 one of such octants is designated by the letter O).

6. Additional queens

At the end of paragraph 4, we noted that all four diagonals of the board are queens of the Fundamental setup. Therefore, it remains to consider only diagonals with odd numbers.

The number of odd diagonals of one direction on the entire board without the main diagonal and corner “single-square” diagonals (beating with the central queen) is 2 ($W_0-1$); on one side of the main diagonal there will be $W_0-1$, and in one octant there will be two times less: $\frac{W_0-1}{2}$.

This number coincides with the number of queens in the Fundamental setup, located on one side of the main diagonal of the highlighted direction. Each queen shaded on figure will place 7 on one of the odd diagonals passing through the octant $O$. Therefore, among the odd diagonals of the octaent there are “empty” diagonals (on which there are no queens), very indo, as many as there are queens in the corner triangle $T$. Let's denote this number by $\varphi(n)$.

Consider one of the empty diagonals of the octaent $O$. Complement it to a symmetrical cross-shaped figure (Fig. 8). Due to the symmetrical cells, there are also no queens on the other three diagonals of this figure. To capture the cells of this figure, it is enough to place two additional queens in the symmetrical cells $A$ and $B$ of the central horizontal line (Fig. 8).

Since the number of empty diagonals in one octant is $\varphi(n)$, it is enough to place $2\varphi(n)$ additional queens.

⟦folio 26⟧

Fig. 9. $k = 3, l = 2$.

So,
$$F(n) \leqslant W_0 + 2\varphi(n).$$

7. Queens and squares

To estimate from above the number $\varphi(n)$ of queens in the angular triangle $T$ (Fig. 7), recall that the functional distance queens are located at lattice nodes on the side of length $\sqrt{(2k)^2 + (2l)^2} = 2\sqrt{k^2 + l^2}$ (the length of the board square is taken as one), rotated relative to the chessboard (Fig. 4, 6).

Let's move this lattice so that the queens are in the centers of the squares (Fig. 9). Then the number of queens in triangle $T$ will not exceed the number of “shifted squares” whose centers lie in $T$. Since each such square lies entirely in the $\frac{d}{2}$-neighborhood of the triangle $T$ (Fig. 10; $d$ is the length of the diagonal of the square), their number does not exceed the area of ​​the square relative to the area of ​​this neighborhood.

Exercise 5. The $\varepsilon$-neighborhood of a plane figure $F$ is the union of circles of radius $e$ with centers at each point of the figure $F$. Prove that the area of ​​the $\varepsilon$-neighborhood of a convex polygon is equal to $S + P\varepsilon + \pi e^2$, where $S$ is the area of ​​the polygon, $P$ is its perimeter.

The length of the triangle $T$ is equal to $\frac{n}{2}$. The side of the square from which the lattice is constructed is $2\sqrt{k^2 + l^2} = 2\sqrt{\frac{n-1}{2}} = \sqrt{2}\sqrt{n-1}$.

This means that the required area ratio is equal to
$$\frac{n^2}{8} + \left(1 + \frac{\sqrt{2}}{2}\right)n\sqrt{n-1} + \pi(n-1) \over 2(n-1)$$.

Since $W_0 = k^2 + l^2 = \frac{n-1}{2}$, from (3)
$$F(n) \leqslant \frac{5}{8}n + \left(1 + \frac{\sqrt{2}}{2}\right)\frac{n}{\sqrt{n-1}} + \frac{1}{8(n-1)} + \pi - \frac{3}{8}.$$

Due to the fact that $\frac{n}{\sqrt{n-1}} < 2\sqrt{n}$ and $\frac{1}{8(n-1)} < 1$, with $n \geqslant 2$ and $1 + \frac{\sqrt{2}}{2} < 2$, we obtain for boards on the side of $2(k^2 + l^2) + 1$ cells, where $k$ and $l$ are relatively prime numbers of different parities, the final upper bound:
$$F(n) \leqslant \frac{5}{8}n + 4\sqrt{n} + 5.$$

8. Custom boards

Let us now have a board $n \times n$, where $n \geqslant 11$. Let's take a natural $m$ such that $8m^2 + 3 \leqslant n < 8(m+1)^2 + 3$. Since $n \geqslant 11$, there is such a $m$. Note that $8m^2 + 3 = 2[(2m)^2 + 1^2] + 1 = 2(k^2 + l^2) + 1$, where $k = 2m, l = 1$.
