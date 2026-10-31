---
id: 1972-11-golomb-fragment-stati-shahmatnyie-doski-i-polimino-f07c4eb2
issue: kvant_1972_11
year: 1972
number: "11"
title: '[Fragment of the article “Chessboards and polyominoes”]'
authors:
  - Голомб С.
rubric: osnovnye-stati
page_first: 4
page_last: 12
page_labels: 4, 5, 6, 9, 10
tag: YZZS
lang: en
source: kvant_digital
extraction: vision
content_sha256: 74ef8e05a4988a662d85ba7e0a0ff4ca855584b683a6df8bd2f81508753ef62d
prompt_sha256: draft-1
translated_from: content/ru/1972/11/articles/03_golomb-fragment-stati-shahmatnyie-doski-i-polimino-f07c4eb2.md
source_content_sha256: af4c354d434cf6e7e80c507e0412b1b8aa5f3c02aba0f7bfc64235e09d313881
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio none⟧

Klemchaty sovereign and polyomino

A. Yu. Soifer

Professor at the University of Southern California S. Golomb is the author of a number of works on information theory, coding theory, mathematical statistics and their applications to the theory of mathematical machines and genetics. But it was not these works, which are of unconditional interest for specialists, that determined the wide popularity of professional names in the game, more precisely, a whole series of games associated with the so-called “polyominoes”. Golomb published the book "Polyominoes" in 1965, containing many interesting and interesting mathematical problems. Some of these and similar problems are known to our readers from Martin Gardner’s recently published book “Mathematical Puzzles and Entertainment”* (chapters 12 and 46), as well as from a series of publications in the “Psychological Practice” section of the journal “Nuka and Life” for 1967-1968, where, in particular, Gololov’s games “pentamino” and “hexatrion” and a number of related games are described tasks.

The “history” of polyominoes begins with Golomb’s article “Chess Docs and Polyominoes,” which he, while still a graduate student at Harvard University, published in 1954 in the American Mathematical Monthly. The published excerpt from this article (“A. M. M.”, 61 No. 10. Translation by I. I. Yaglom) will introduce you to the basic concepts associated with polyominoes and give examples of “typical” problems on polyominoes. In the next article we will talk about some more general problems on the same topic. So, over to S. Golomb.

We'll start with a well-known problem:
a chess dock is given, from which a pair of promion whole cells (Fig. 1) is cut out, and a dokino box is given, like a space that covers two cells of the chess dock with bark. Is it possible to cover this dokka with the 31st dokino spacer?

The answer to this question is “No”; To prove it, it is enough to look at the general coloring of the chess doki (Fig. 1). Any Dokino space placed on the dock and covering two squares will cover one light and one dark square,

*) Publishing house "Mir", M., 1971.

and n domino bones are n light and n dark squares, that is, an equal number of both. But the chess dock shown in figure 1 contains more dark cells than light ones. That's why it can't be covered with domino seeds.

We will still use the general 8 × 8 chess dock as the “playing field”, but we will generalize dominoes into “polyominoes” - and our theorems will cover all the simplest types of polyominoes depicted in figure 2. More precisely: we will define n-mino as a set of n squares of a chess dock, grouped “on the rook principle”, that is, so that bet on any square n-mino rook can

⟦folio none⟧

In a finite number of moves, move to any other cell of the same $n$-mino.

First we'll look at triminoes. It is clear that a chessboard of size $8 \times 8$ cannot be covered with triminoes, since 64 is not divisible by 3. Let us instead try to cover the chessboard with 21 triminoes and one monomino.

The chessboard cannot be covered with 21 prime triminoes and one monomino located in the upper left corner of the board. To prove this, we will now color the board in three colors: $a$, $b$ and $c$ (Fig. 3). As you can see, we have 21 fields of color $a$, 22 fields of color $b$ and 21 fields of color $c$. Each prime trimino covers one field of color $a$, one field of color $b$, and one field of color $c$, that is, prime triminos always cover the same number of $a$-cells, $b$-cells, and $c$-cells. The upper left corner is a $a$-cell and after covering it with monominos we will be left with an unequal number of $a$-, $b$- and $c$-cells. Therefore, it is impossible to cover the remaining 63 cells with prime triminoes.

In the same way, we make sure that after covering any $a$-or $c$-cell with a monomino, the remaining part of the board cannot be covered with a prime trimino. It remains to consider only $b$-cells. But if a monomino covers, for example, a $b$-cell located in the lower left corner, then due to the symmetry of the board relative to the prima $x$ shown in figure 3, we come to the already considered problem of covering with a prima triomino the board in the upper left corner of which lies a monomino. The top left corner of the board is a $a$-square, in which case covering is not possible; This means that it is impossible even when the monoomino lies in the lower left corner.

Thus, it is established that in order for a covering to be possible, a monoomino must necessarily cover a $b$-cell that is relatively prime $x$ and $y$ (see Fig. 3). symmetrine also to $b$-cells. The only such cells

⟦folio 4⟧

Fig. 4. Fig. 5.

Fig. 6.

Fig. 7.

ki are those that are shaded on figure 4. And from figure 5 it follows that if a monomino covers one of these cells, then the rest of the real monomino can be covered with straight triminoes.

So, a necessary and sufficient condition for the occurrence of a covering of a chess monomino and the 21st straight trimino is that the monomino covers one of the cells shaded on figure 4.

So far we have been dealing with “proofs of impossibility.” The next result is of the opposite nature: regardless of which cell of the chess monomino, the remaining cells can be covered by the 21st rectangular trimino.

The proof is carried out according to the industrial principle and for a chess monoki of “general form” of size $2^n \times 2^n$. For monoki $2 \times 2$ it is clear that wherever a monomino lies on it, the remaining three cells can be covered with a rectangle trimino (Fig. 6, a). Now taking a monoka of size $4 \times 4$, we will divide it into four parts, each size $2 \times 2$ (Fig. 6, b). Let the monomino cover the cell of, say, the yellow part at figure 6, b. Since each quarter of a monoki is a doka of size $2 \times 2$, it can be covered with one trimino and one monomino covering an arbitrary cell of this monoki. There is already a monomino in the yellow part; As for the remaining three quarters, we will place monominos on them in the central (for large monos) cells - after this we can replace our monomino with one rectangular trimino (see the same figure 6, b). So, we have covered a chess monopole of size $4 \times 4$ with one (randomly placed) monomino and a fifth with rectangular triminoes.

The case of monoki $8 \times 8$, as well as the most general case, is treated similarly (see figure 6, c).

Now let's move on to Terramino. It is easy to completely cover a chess monoca with straight, square, G-terminal or G-terminal - this is clear from figure 7. On the other hand, it is impossible to cover a monoca cosmittermino - after all, oblique terraminos cannot be placed on the dock even so as to completely cover a row of squares straight to any side of the monoca...

⟦folio 5⟧

Let's continue our polymology lesson, starting with the articles of Professor Golomb.

You have already seen that some problems on polynomials do not necessarily assume that we are talking about a “standard” chessboard $8 \times 8$; we also considered boards $2^n \times 2^n$ for an arbitrary natural number $n$. So now let’s move on and talk about arbitrary square doors $n \times n$ and, moreover, about arbitrary rectangular doors $m \times n$.

Problem 1. Name a pair of natural numbers $(m, n)$ such that the clematic board $m \times n$ could be filled with a linear $k$-mino.

1st solution.

If at least one of the numbers $m, n$ is divisible by $k$, then the board $m \times n$ can be filled with a linear $k$-mino (check!).

Suppose that none of the numbers $m, n$ is divisible by $k$, and the board $m \times n$ is nevertheless laid out with a linear $k$-mino. Paint the board $k$ with colors in a diagonal way, cyclically changing colors: 1st, 2nd, ..., $k$th, 1st, 2nd, ... (Fig. 8).

A board colored in this way has an interesting property: no matter how the linear $k$-mino is placed on it, horizontal or vertical, it covers exactly one square of each of the $k$ colors. So, by assumption, the board is covered with a linear $k$-mino, and each $k$-mino covers the same number of squares of each color (one square each)

Fig. 8. Diagonal coloring at $k=3$.

⟦folio 6⟧

equal number of cells of each color.

But, on the other hand, there are always colored diagonals in such a board

$$r_2 + r_1 - 1 \leq \frac{k}{2} + \frac{k}{2} - 1 < k,$$

so that it will not contain a single cell of at least one of the colors used for coloring. Contradiction!

So, the board $m \times n$ can be laid out with a linear $k$-minо if and only if at least one of the numbers $m, n$ is divisible by $k$.

This problem can be solved using a different coloring.

2nd solution.

Suppose that none of the numbers $m, n$ is divisible by $k$, and the board $m \times n$ is laid out with a linear $k$-minо.

Divide with remainder $m$ and $n$ by $k$:

$$m = kq_1 + r_1; \quad 0 < r_1 < k,$$
$$n = kq_2 + r_2; \quad 0 < r_2 < k.$$

Color the board $k$ with colors as follows: 1st column - 1st color, 2nd - 2nd, ..., $k$th - $k$th, $(k+1)$th - 1st, etc., $m$th - $r_1$th color (Fig.9).

Colored in this way, the board has the following property: if the linear $k$-minо is placed vertically on the board, then it will cover $k$ cells of the same color, and if horizontally, it will cover exactly one cell of each color. The board is supposed to be laid out $k$-minо; That's why

$$S_1 \equiv S_2 \equiv \dots \equiv S_k \pmod{k},$$

where $S_1(l=1, 2, \dots, k)$ is a number

**Fig. 9. Column coloring at $k=4$.**

cells of the $l$ color contained in the board.

On the other hand, how easy it is to calculate

$$S_{r_1} - S_{r_1+1} = n;$$

follow,

$$S_{r_1} - S_{r_1+1} \equiv r_2 \pmod{k},$$

So

$$S_{r_1} \neq S_{r_1+1} \pmod{k}.$$

The resulting contradiction shows that for the existence of the desired arrangement, $m: k$ or $k^*$) is necessary.

Have you thought that solving problems about laying a board polymnically is not necessarily connected with one way or another of coloring the board? Nothing of the kind!

3rd solution.

Suppose that the board $m \times n$ is laid out with linear $k$-minо and

$$m = kq + r_1; \quad 0 < r_1 < k;$$
$$n \equiv r_2 \pmod{k}; \quad 0 < r_2 < k.$$

We will say that $k$-minо “grows from the $l$th column” if it is located horizontally and begins in the $l$th column (Fig. 10).

Let us denote by $t_l$ the number of $k$-minо growing from the $l$th column. By assumption, the board is laid out $k$-minо; That's why

$$t_1 \equiv r_2 \pmod{k},$$
$$t_2 \equiv 0 \pmod{k},$$
$$t_3 \equiv 0 \pmod{k},$$
$$\dots$$
$$t_k \equiv 0 \pmod{k},$$
$$t_{k+1} \equiv r_2 \pmod{k},$$
$$t_{k+2} \equiv 0 \pmod{k},$$
$$\dots$$
$$t_{kq+1} \equiv r_2 \pmod{k}.$$

*) $m: k$, as usual, means that $m$ is divisible by $k$.

⟦folio none⟧

Fig. 11.

On the other hand, it is clear that the $k$-mino growing from the $(kq+1)$th column will “grow” beyond the rectangle, from where $t_{kq+1} = 0$ comes. Here too we have arrived at a contradiction, showing that for the existence of a $m \times n$ $k$-mino board layout, at least one of the numbers $m, n$ must be divisible by $k$.

For further tasks we will need a “coordinate system” on the board; we will draw the rows and columns of the board (see Fig. 11).

Each cell is now specified by a pair of numbers $(x, y)$, where $x$ and $y$ are, respectively, the numbers of the row and column in which this cell is located.

Problem 2. There is a rectangular checkered board $m \times n$ and a linear $k$-mino. We will call a board cell $(x, y)$ “well-placed” if the piece $F$ obtained from the board as a result of cutting this cell can be made with a linear $k$-mino. Name $M$ of all well-placed squares on the board.

For $k = 1$, obviously, $M$ coincides with the set of all squares on the board. Let's assume that $k = 2$. Suppose that one square is cut out of a rectangle and the resulting figure $F$ is laid out as a domino; then $(mn-1)$ —

Fig. 12.

Fig. 13.

Fig. 14.

⟦folio none⟧

cells $(x, y)$, which is $x \equiv y$ (mod 2); if at least one of the numbers $m, n$ is a multiple of 2, then the board $m \times n$ does not have well-placed cells.

Let now $k > 2$. In this case $1 \neq -1$ (mod $k$).

Let us assume that the resulting figure $F$ after cutting out the cell $(x, y)$ is laid out by a linear $k$-mino. Let us arrange a columnar cyclic coloring of $k$ colors on this board (see Fig. 9). We have already noted the property of a board colored in this way: if a linear $k$-mino is located vertically on the board, then it covers $k$-cells of the same color, and if horizontally, it covers exactly one square of each color. By assumption, the figure $F$ is laid out with a linear $k$-mino; That's why

$$P_1 \equiv P_2 \equiv \dots \equiv P_k \pmod{k},$$

(1) where $P_l (l = 1, 2, \dots, k)$ is the number of cells of the $l$ color in the figure $F$.

Let

$$m = kq_1 + r_1 \quad (0 \leqslant r_1 < k),$$
$$n = kq_2 + r_2 \quad (0 \leqslant r_2 < k).$$

Let us denote by $S_l (l = 1, 2, \dots, k)$ the number of cells of the $l$ color in the entire board. It's easy to calculate that

$$S_1 = \dots = S_{r_1} = n(q + 1),$$

(2a)
$$S_{r_1+1} = \dots = S_k = nq.$$

The figure $F$ contains exactly one cell less than the entire board, so from correspondence (1) and (2) it follows that there are only two possibilities: either $r_1 = 1$ and a cut-out cell of the first color, or $r_1 + 1 = k$ and a cut-out cell of the $k$ color.

1 sluay. The cut cell $(x, y)$ is of the first color, that is, $y \equiv 1 \pmod{k}, r_1 = 1, m \equiv 1 \pmod{k}$, and in addition,

$$S_1 - 1 \equiv S_2 \equiv S_3 \equiv \dots \equiv S_k \pmod{k},$$

whence $n(q + 1) - 1 \equiv nq$. (mod $k$), that is, $n \equiv 1 \pmod{k}$.

So, $m \equiv n \equiv y \equiv 1 \pmod{k}$.

2nd layer. The cut out cell $(x, y)$ is the $k$ color, that is, $y \equiv 0 \pmod{k}, r_1 = k - 1,$

$$m \equiv -1 \pmod{k}$$ and, in addition,

$$S_1 \equiv S_2 \equiv \dots \equiv S_{k-1} \equiv S_k - 1 \pmod{k},$$

whence $nq - 1 \equiv n(q + 1) \pmod{k}$, that is $n \equiv -1 \pmod{k}$.

So,

$$m \equiv n \equiv -1 \pmod{k}; y \equiv 0 \pmod{k}.$$

Let us now turn this board to $90^\circ$, that is, consider the board $n \times m$ and apply the above reasoning to it. Here are the final conclusions: if $m \equiv n \equiv 1 \pmod{k}$, then the coordinates of the distantly located cell $(x, y)$ must satisfy the correspondence $x \equiv y \equiv 1 \pmod{k}$. If $m \equiv n \equiv -1 \pmod{k}$, then the coordinates of the distantly located cell $(x, y)$ must satisfy the correspondence $x \equiv y \equiv 0 \pmod{k}$.

$x \equiv y \equiv 0 \pmod{k}$.

In other cases, the board $m \times n$ does not have remotely located cells.

Figure 15 and 16 show that if $m \equiv n \equiv 1 \pmod{k}$ then any cell

⟦folio 9⟧

ka $(x, y)$, for which $x \equiv y \equiv 1$ (mod $k$), is well located; if $m \equiv n \equiv -1$ (mod $k$), then any cell $(x, y)$ for which $x \equiv y \equiv 0$ (mod $k$) is well located.

So, the solution problem.

It is convenient to write the answer in the form of a table (see table above).

We see that if the board $m \times n$, at $k > 2$, contains well-placed cells, then their number $v$ is small compared to the number of all cells on the board; prove that

$$v = \frac{[m + (-1)^r(k - 1)][n + (-1)^r(k - 1)]}{k^2},$$

where $r = 1$ if $m \equiv n \equiv 1$ (mod $k$), and $r = -1$ if $m \equiv n \equiv -1$ (mod $k$).

But the number of such cells can be increased! Let's glue a couple of opposite sides of our board: we get a checkered cylinder (Fig. 17).

Task 3.
a) A cylinder was glued from a rectangular checkered board $m \times n$. Most of all are well located -

ny cells of the cylinder for the linear $k$-mino.

b) If $m \neq n$, then depending on which pair of opposite sides we glued together, we can get two different cylinders. Which of these cylinders has a greater number of well-placed cells?

Let's now go further and glue the bases of our cylinder (Fig. 18).

The resulting figure, called a pestilence, has an unconditional “advantage” compared to a checkered board or a checkered cylinder: all its cells are equally valid. In particular, if a checkered torus has at least one well-placed cell, then all its cells are well-placed.

The torid checkered board has other advantages. Let us solve, for example, the following problem.

Task 4.
a) Find all natural numbers $n$ such that the square board $n \times n$ can be laid into the rectangle shown in figure 19.

Fig. 17.
Fig. 18.

⟦folio 10⟧

Fig. 19, 20, 21.

6) The most natural numbers are also $n$, so that the moral board obtained from the square square of the board $n \times n$ can be laid out with the triminoes depicted on figure 19.

Since a trimino consists of three cells, for the formation of the board $n \times n$ trimino to occur, it is necessary that $n$ be a multiple of 3.

A rectangle of size $2 \times 3$, of course, can be laid as a trimino (Fig. 20). It is more difficult to lay a rectangle of size $5 \times 9$ (Fig. 21). Now it doesn’t seem very difficult to prove (prove it!) that the square $n \times n$ can be arranged as a trimino at $n = 3k$, where $k = 2, 3, \dots$.

Prove that the square $3 \times 3$ cannot be fitted with our triminoes. As for a toridal board glued together from a square $n \times n$, it can be laid as a trimino for any $n$ divisible by 3.

Fig. 22.

To prove this fact, it remains for us to show that the toridal board $3 \times 3$ can be arranged as a trimino. Figure 22 shows possible such arrangement (when gluing the torus together, the red cells will come together to form a trimino of the required type).

Exercises

1. There is a rectangular checkered “good” one, if the figure resulting from the board as a result of cutting out these two squares can be laid as a domino. These are all good pairs of cells.

2. There is a rectangular checkered board $m \times n$ and a natural number $k$, $k < \frac{mn}{2}$.

I'm playing before. The first player crosses out any cell on the board, then the second player crosses out any cell other than crossing out any cell on the board other than the one previously crossed out. After the players have made their move, the winner is determined. The second one wins if the piece obtained after cutting out all the crossed out cells can be stacked with dominoes; otherwise, the first player is removed as the winner.

Find a game strategy for one of the players that allows him to win regardless of the winner’s cerra.

3. a) They are also all natural numbers $n$ such that the square cell of the board $n \times n$ can be laid out T-meterwise (see Fig. 2).

6) Will the result change if the boards are laid together cylindrically? moral?

4. a) They are also all natural numbers $n$ such that a square cell of a board $n \times n$ can be laid out T-meterwise.

6) Will the result change if the boards are laid together cylindrically? moral?

5. a) A cylinder was glued from a primugular square of board $m \times n$. Under what conditions can it be laid with a linear k-mino?

6) If $m \neq n$, then from the board $m \times n$ you can glue two different Möbius strips. Is it possible that one of them can be laid down with a linear k-mino, but the other cannot?

Fig. 23.

6. A rectangular board (on which there is a checkered seed on both lines) is bent and glued, as shown in figure 23. The result is a Möbius strip.

a) Under what condition can a Möbius strip glued together from a board $m \times n$ be arranged with a linear k-mino?

6) If $m \neq n$, then from the board $m \times n$ you can glue two different Möbius strips. Is it possible that one of them can be laid down with a linear k-mino, but the other cannot?
