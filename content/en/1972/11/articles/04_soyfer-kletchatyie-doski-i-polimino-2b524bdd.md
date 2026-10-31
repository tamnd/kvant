---
id: 1972-11-soyfer-kletchatyie-doski-i-polimino-2b524bdd
issue: kvant_1972_11
year: 1972
number: "11"
title: Checkered boards and polyominoes
authors:
  - Сойфер А. Ю.
rubric: osnovnye-stati
page_first: 6
page_last: 12
page_labels: 4, 5, 6, 9, 10
tag: QK13
lang: en
source: kvant_digital
extraction: vision
content_sha256: 0829e77622bc4143309bae2d2e4e2636bd7e4acabcf28492157666d408271f5e
prompt_sha256: draft-1
translated_from: content/ru/1972/11/articles/04_soyfer-kletchatyie-doski-i-polimino-2b524bdd.md
source_content_sha256: 111e7195ece68b60bfabdf7e6a177d03d3bb8d11ee9593049e2335e97c37d457
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

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
