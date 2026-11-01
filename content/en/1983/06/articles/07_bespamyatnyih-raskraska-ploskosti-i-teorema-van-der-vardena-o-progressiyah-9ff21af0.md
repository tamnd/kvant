---
id: 1983-6-bespamyatnyih-raskraska-ploskosti-i-teorema-van-der-vardena-o-progressiyah-9ff21af0
issue: kvant_1983_6
year: 1983
number: "6"
title: Coloring the plane and Van der Waerden's theorem on progressions
authors:
  - Беспамятных С. Н.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 37
page_last: 40
page_labels: 35-38
tag: V5S8
lang: en
source: kvant_digital
extraction: vision
content_sha256: 178dc7ce32387c62312e3a60a463f9b2ec25aa288c4fc3ce871a68c00d9e0def
prompt_sha256: draft-1
translated_from: content/ru/1983/06/articles/07_bespamyatnyih-raskraska-ploskosti-i-teorema-van-der-vardena-o-progressiyah-9ff21af0.md
source_content_sha256: b102ac5ae0eb4e25cf0f10ad17feda4bcfe85e551bc10b85b54eeb328abce616
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 35⟧

Plane coloring and theorem
Van der Waerden on progressions
S. N. BESPOMYATNYKH

In this note we will prove the following extreme generalization of the result problem M750.

Coloring theorem. Let each cell of an infinite sheet of checkered paper be colored in one of N colors. Then for any set of cells $a_1, \dots, a_l$ there is a set of identically colored cells $b_1, \dots, b_l$, similar to the first in the sense that (see Fig. 1) $B_i B_j = d A_i A_j$ for all i, j=1, ..., l, $e d e A_1, \dots, A_l, B_1, \dots, B_l$ are the centers of cells $a_1, \dots, a_l, b_1, \dots, b_l$, respectively, and d is some natural number; in other words, the figures formed by the centers of cells $b_1, \dots, b_l$ and $a_1, \dots, a_l$ correspond to d.

Fig. 1.

Moreover, such a set of cells can be found in any square $m \times m$, where m is a sufficiently large number depending on the number of colors N and the given set $a_1, \dots, a_l$.

(Please note: “similarity of sets of cells” does not mean exactly the same thing as the usual concept of “similarity of figures”!).

The history of this theorem is interesting. In 1928, one mathematician working in a large mathematical center - Göttingen, was faced with the following question: is it possible to say that for any partition of the set of natural numbers into two parts (or into a finite number of parts), although in one of them there will be an arithmetic progression of an arbitrarily large given length? It seemed almost certain that the answer here was yes. However, despite the apparent simplicity of the problem, it was not possible to prove this, and soon it became the subject of general fascination. The first to add the module was the Dutchman B. L. Van der Waerden, who later became a famous mathematician. After several weeks of work, he found a not simple, but completely elementary proof, based on the ingenious use of mathematical induction and the “Dirichlet principle” (see, for example, «Kvant», 1977, No. 2, p. 17). In the 1940s, Van der Waerden's theorem was extended to the n-dimensional case; the coloring theorem is the case of dimension n=2.

Here is one of the formulations of Van der Waerden's theorem, somewhat generalizing the original problem.

For any numbers N and l, one can specify a number m=m (N, l) such that if a segment of a natural series of length m is arbitrarily partitioned into N classes, at least one of them contains an arithmetic progression of length l.

Let us show how this theorem can be derived from the coloring theorem. Take any m consecutive natural numbers and number the columns of the square $m \times m$ with them; dividing these numbers into N classes is comparable

⟦folio 36⟧

coloring a square in $N$ colors, in which all cells of all columns whose numbers are included in the same class receive the same color (Fig. 2). Now let $a_1, \dots, a_1$ be a horizontal row of $l$ consecutive cells. Then, according to the coloring theorem, for a sufficiently large $m$, in our square there is a set of single-link cells $b_1, \dots, b_l$, a similar set $a_1, \dots, a_l$, that is, a horizontal row of cells equally spaced from each other. It is obvious that the numbers of the columns containing cells $b_1, \dots, b_l$ form the required progression (the difference $d$ of this progression is equal to the “similarity coefficient” of the sets $a_1, \dots, a_l$ and $b_1, \dots, b_l$).

Moving on to the proof of the coloring theorem, the conditions are to consider not arbitrary sets of cells $a_1, \dots, a_l$ but “standard” netors - such as in figure 3. It is clear that this will not build generality, because any set of cells can be completed to a “standard” one, and if the statement

Fig. 2.

Fig. 3.

If the theorem is proven for the additional - “standard” - set, then it will also be complete for the original one. Sets of cells similar to “standard” sets, called similarity coefficient - series coefficient; series of squares will be called a set of congested squares consisting of cells of our infinite sheet, the lower left cells of which form a series (obviously, any corresponding cells of such squares also form a series). Finally, two congruous colored squares are called identically colored, that is, their colorings coincide during a parallel transfer that combines the squares.

Thus, we must prove that, whatever the numbers $N$ and $l$, for a sufficiently large $m = m(N, l)$ in the square $m \times m$, arbitrarily colored in $N$ colors, there will always be a monochromatic series $b_1, \dots, b_l$ of length $l$.

The proof will be by induction on $l$.

For $l=1$, obviously, we can take $m(N, 1)=1$, and for $l=2-m(N, 2)=N+1$ (the Dirichlet principle!). Let us now assume that the statement of the theorem is true for series of length $l$ for all angles greater than $N$, and we will prove it for series of length $l+1$.

Let us first explain the idea of ​​the proof. Let there be a series of $l+1$ squares $K_1, K_2, \dots, K_{l+1}$ and in each of the squares $K_i$ a series of $l+1$ cells $b_{i,1}, b_{i,2}, \dots, b_{i,l+1}$ is chosen, and these series are equally located in the squares (see Fig. 4, where $l=4$). Then from cells $b_{i,j}$ one can form another $l+1$ series of the form $b_{1,j}, b_{2,j}, \dots, b_{l+1,j}$ ($j=1, \dots, l+1$) - on figure 4 such a series for $j=l+1$ is shown in pink - and another series $b_{1,1}, b_{2,2}, \dots, b_{l+1,l+1}$ with a slightly larger coefficient - these cells on figure are circled. If it is known that the squares $K_{1,b}, \dots, K_{l,b}$ are of the same type, and the cells $b_{1,1}, b_{1,2}, \dots, b_{1,l}$ (and with them all the cells $b_{i,j}$, where $i, j \leq l$) are of the same color, then in each of the three series: $b_{1,1}, b_{1,2}, \dots, b_{1,l+1}$ (the series in the square $K_1$), $b_{1,1},$

⟦folio 37⟧

Fig. 4.

$b_{2,2}, \dots, b_{l+1,l+1}$ (framed series) and $b_{1,l+1}, b_{2,l+1}, \dots, b_{l+1,l+1}$ (“pink” series) all cells, except perhaps the last one, are single-linked, and the outermost cells are some two of the cells $b_{1,1}, b_{1,l+1}$ and $b_{l+1,l+1}$ (they are placed on figure *)). Therefore, if among these three cells we find two single-linked ones, we will get a single-linked series of length $l+1$. This will certainly be the case, according to the Dirichlet principle, in the case of two colors. In the case of $N$ colors, it is necessary to consider not a two-, but a $N$-stage design (in large squares choose a series of smaller squares, in those - even smaller squares, and so on $N$ times until you get cells). In this case, the size of the initial square should allow at each “stage” to identify the next series of $l+1$ squares, among which there are single-link ones - this is where the induction assumption should help.

Let us now give a formulaic proof of the coloring theorem. Let us define the sequence $(q_r)$, $r=0, 1, \dots, N$, by correspondences

$$q_0 = 1, \quad q_{r+1} = 2m(N^{q_r^2}, l) \cdot q_r$$

and let $m(N, l+1) = q_N(N^{q_r^2})$ be the number of colorings of the square $q_r \times q_r$ in $N$ colors; the existence of the number $m(N^{q_r^2}, l)$ is ensured by the induction assumption, $l=1, 2, \dots$).

The square $q_r \times q_r$ is called a square by the boundary $r$. Let us show that for any coloring of a square $K$ of rank $r+1$ in $N$ colors, it is possible to choose a series of squares $K_1, K_2, \dots, K_{l+1}$ of rank $r$ in which all the squares, except for the one, $K_{l+1}$, are single-colored. Let's imagine that the square $K$ is divided into large “cells”, each of which is a square of rank $r$; The “color” of such a cell will be considered to be any of the $N' = N^{q_r^2}$ ways of coloring it in $N$ colors. Divide the square $K$ into 4 equal squares and select the lower left one from them - $Q$ (Fig. 4). It consists of $m' \times m'$ “cells”, where $m' = m(N', l)$ are colored in $N'$ “colors”, and by the definition of the number $m'$ there is a series of $l$ “cells” of the same “color”, that is, a series of one-piece squares $K_1, \dots, K_l$ of rank $r$. What remains is its complement to a series of $l+1$ squares by the square $K_{l+1}$, which may not fit in $Q$, but will certainly fit in the square $K$.

Let us now prove that we can take $q_N$ as the number $m(N, l+1)$. Let $K$ be an arbitrary square on the side $m=q_N$, that is, of rank $N$, colored in $N$ colors. Let us select in it squares $K(1), \dots, K(l+1)$ of rank $N-1$, the first $l$ of which are single-linked. Let $d_1$ be the coefficient of this series. Let us select in square $K(1)$ a series of squares $K(1, 1), K(1, 2), \dots, K(1, l+1)$ of rank $N-2$, the first $l$ of which are single-linked. Let $d_2$ be the coefficient of this series and let $K(i, j)$ be the square that is obtained from $K(1, j)$ when transferred, combining $K(1)$ and $K(i)$, $i=2, 3, \dots, l+1$, that is, when transferred to the vector $d_1A_1A_i$ (recall that $A_1, A_2, \dots$ are the centers of the cells “standard” set $a_1, a_2, \dots$). Let's continue this process by selecting in square $K(1, 1)$ a series $K(1, 1, 1), K(1, 1, 2), \dots, K(1, 1, l+1)$ of squares of rank $N-3$ with a coefficient $d_3$ and “dispersing” it among our squares $K(i, j)$, etc. After $N$ steps we will obtain squares of rank 0, that is, cells - $K(i_1, i_2, \dots, i_N)$ ($i_k=1, \dots, l+1$). Each of these squares is the last link in a chain of stacked squares of higher ranks: $K(i_1) \supset K(i_1, i_2) \supset \dots \supset K(i_1, i_2, \dots, i_N)$. Taking into account the rule for constructing a series of squares from here

⟦folio 38⟧

It is easy to derive the following properties:

1) the squares $K(i_1, i_2, \dots, i_s, i_{s+1}, \dots, i_r)$ and $K(i'_1, i'_2, \dots, i'_s, i_{s+1}, \dots, i_r)$ whose first $s$ indices do not exceed $l$ (and the rest are the same) are single-valued; in particular, given $p$ and $q$ ($p, q \geqslant 0, p+q < N$) cells $b_i = K(1, \dots, 1, i, \dots, i, l+1, \dots, l+1)$ (1)

have the same color for all $i=1, \dots, l$;

2) the vector connecting the centers of the squares $K(i_1, i_2, \dots, i_r)$ and $K(j_1, j_2, \dots, j_r)$ is equal to $d_1 A_{i_1} \vec{A}_{j_1} + d_2 A_{i_2} \vec{A}_{j_2} + \dots + d_r A_{i_r} \vec{A}_{j_r}$; in particular, for cells $b_i$ and $b_j$ (see (1)) it is equal to $(d_{p+1} + d_{p+2} + \dots + d_{N-q}) A_i A_j$.

Now we are not far from the goal. Consider the following $N+1$ cells:

$K(l+1, l+1, l+1, \dots, l+1), K(1, l+1, l+1, \dots, l+1), K(1, 1, l+1, \dots, l+1), \dots, K(1, 1, 1, \dots, 1)$. According to the Dirichlet principle, at least two of them are unambiguous. To determine this, let there be cells $b_1 = K(1, 1, 1, l+1, \dots, l+1)$ and $b_{l+1} = K(1, l+1, l+1, l+1, \dots, l+1)$ (cf. (1) with $p=1, q=N-3$). Then from properties 1) and 2) it follows that the cells $b_1, b_2, \dots, b_{l+1}$, where $b_i = K(1, i, i, l+1, \dots, l+1)$, form the desired one-link series (with coefficient $d_2 + d_3$). The coloring theorem is proven.

If this topic interests you, we recommend that you refer to the book by A. Ya. Khinchin “Three Pearls of Number Theory”, which provides a detailed proof of Van Waerden’s theorem on progressions.

Exercises

1. Show that the coloring theorem allows us to solve all points of Problem M750.

2. Prove that if in Van Waerden’s theorem the word “arithmetic” is replaced with “geometric”, then it will remain true. (By the way, Van der Waerden himself proved his theorem specifically for geometric progressions.)

3. Prove that for any $n$ and for any partition of the natural series into $N$ classes at least one of them contains $n$arithmetic progressions of length $n$, the first of which form a geometric progression.

4. Give an example of partitioning a natural series into two subsets, neither of which contains:

a) infinite arithmetic progression;

b) neither an infinite arithmetic progression nor an infinite geometric progression.

5. Give an example of coloring cells in two colors, in which there is not an infinite set of vertical lines and an infinite set of horizontal lines, at the intersection of which the center of single-link cells is obtained.

6. Prove that for any coloring of cells in $k$ colors there is an infinite set of vertical lines $\{x_i\}$ and an infinite set of horizontal lines $\{y_i\}$ ($i=1, 2, 3, \dots$) such that at the intersection of lines $y_i$ and $x_j$, where $i \geqslant j$, the center of single-link cells is obtained.

Left-handed DNA helix

(For the beginning, see p. 31)
the possibility of being, as was previously thought, in the B-form.

The question arises, what will happen if in a long DNA molecule (remember that an ordinary long molecule contains decimal nucleotides) there is a section with the sequence ... CHCH ...?

Experiments have shown that when determining the conditions, such a region is indeed in the Z-form, although around it the DNA remains in its normal form. There is evidence that this is also possible inside a cell.

The discovery of the left-handed helix and the possibility of its existence in “working” DNA aroused great interest. In many laboratories around the world, it is now interesting to study a new form, the conditions under which the corresponding sections of DNA are transferred into it. Scientists are trying to figure out the role that the Z-form and the general structure of DNA changes its structure play in the functioning of this molecule in the cell.

Undoubtedly, the coming years will bring many more interesting discoveries in this area.
