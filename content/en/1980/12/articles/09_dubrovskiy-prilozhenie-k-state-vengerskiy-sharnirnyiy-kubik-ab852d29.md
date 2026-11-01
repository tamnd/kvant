---
id: 1980-12-dubrovskiy-prilozhenie-k-state-vengerskiy-sharnirnyiy-kubik-ab852d29
issue: kvant_1980_12
year: 1980
number: "12"
title: '[Appendix to the article “Hungarian articulated cube”]'
authors:
  - Дубровский В. Н.
rubric: smes
page_first: 23
page_last: 23
page_labels: "21"
tag: 66OK
lang: en
source: kvant_digital
extraction: vision
content_sha256: 4ee0ea5d9d6da6d4c61a5627155601f7b7658d2d36c3ca816daeb23a1aa9ba2b
prompt_sha256: draft-1
translated_from: content/ru/1980/12/articles/09_dubrovskiy-prilozhenie-k-state-vengerskiy-sharnirnyiy-kubik-ab852d29.md
source_content_sha256: bd15af4de5cc2f68cda6d7c7bfad3324dc2707140783f29611953f58ce30ed76
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 21⟧

If only two dice are rotated incorrectly, they cannot both require rotation in the same direction. Otherwise, we would jointly rotate them and another cube - a situation would appear with one incorrectly rotated cube, which is impossible due to III.

So, two incorrectly rotated dice require rotation in different directions. Let's turn one of these cubes and two cubes that were previously standing correctly in the right direction. And then - in the other direction - these two new cubes and the second one from earlier are turned incorrectly. As a result, all the cubes will be in the correct position!

Application*)

Let us denote by $S_0$ the correct state of the cube. Let us enclose the numbers $i=1, 2, ..., 8$ of its vertices (corner cubes) and the numbers $j=1, 2, ..., 12$ of its edges (middle cubes). On the edges, we will select (and fill) any orientation (and direct the corresponding arrows on the middle cubes) so that the parallel edges are aligned.

Let us assume that in a certain state**) $S$ of the cube $j$ the middle cube falls on edge $j'$; Let's compare the orientation of edge $j'$ (which we filled in) with the arrow pointing on the $j$ cube. Let us denote by $n_j(S)$ the values ​​equal to 0 if the indicating orientations coincide, and equal to 1 otherwise. If the amount

$$n_1(S) + n_2(S) + ... + n_{12}(S)$$

is even, we assume $n(S)=0$, otherwise $n(S)=1$; we can say that $n(S)$ is “the parity of the total rotation of the middle cups.” Prove that

1. The quantity $n$ is an invariant, that is, it is the same for all states of the cube: $n(S)=n(S_0)=0$. (Hint: It is enough to show that $n(S)$ does not change with any rotation of one casting).

2. In the law, the state of the cube cannot be rotated equal to one middle cube (property I, p. 19). (Hint: In this state $n(S)=1$).

Let us remember that the position of the central cube in space does not change when rotated; for determination, assume that the lower central cube is green, the upper one is blue; We will consider these two colors to be seen. Let's take the $i$th corner cube of our cube, which is in the $S$ state. Exactly one cell of the corner cube is highlighted (why?). If this cell is horizontal, we set (by definition) $N_i(S)=0$; if this cell becomes horizontal when rotating the cube by $120^\circ$ (clockwise) around the diagonal of the large cube, put $N_i(S)=1$; if the horizontal is obtained by turning by $240^\circ$, then $N_i(S)=-1$. If the amount

$$N_1(S) + N_2(S) + ... + N_8(S)$$

when divided by 3, the remainder is 0, 1, 2, we set the values ​​of $N(S)$ equal to 0.1, -1, respectively. We can say that the quantity $N$ is “the direction of the total rotation of the corner cups.” Prove that

3. The quantity $N$ is an invariant, that is, it is the same for all states of the cube: $N(S)=N(S_0)=0$.

4. In the law, the state of the cube cannot be rotated equal to one middle cube (property III, p. 19).

Suppose that in state $S$ the middle cubes with numbers 1, 2, ..., 12 are occupied with numbers $j_1, j_2, ..., j_{12}$, respectively, and the corner cubes 1, 2, ..., 8 are occupied with places $i_1, i_2, ..., i_8$. The sets $I(S)=(i_1, i_2, ..., i_8)$ and $J(S)=(j_1, j_2, ..., j_{12})$ are simply cup numbers written in a different order; Mathematicians also call sets permutations. A permutation is called even if it has an even number of disorder, that is, an even number of pairs of digits not in ascending order, and odd otherwise. We can say that $\epsilon$ is “the evenness of the arrangement of all cups.” Prove that

5. The quantity $\epsilon$ is an invariant, while $\epsilon(S)=\epsilon(S_0)=0$ for any law state $S$. (Hint: Show that with any rotation of the caster the parity $I$ and parity $J$ change).

6. Exactly one corner cube cannot be interchanged (property II, p. 19).

7*. The state $S$ of a cube is by the law of tosyada and only tosyada, when

$$n(S)=N(S)=\epsilon(S)=0$$.

8*. All states (including those obtained by disassembling and assembling the cube are developed into 12 classes; in this case, two states $S, S'$ are converted into each other by turns lit tosyada and only tosyada when $n(S)=n(S')$, $N(S)=N(S')$, $\epsilon(S)=\epsilon(S')$.

*) Author of the Appendix - V. Dubrovsky.
**) That is, in the state obtained from the correct turns of the casts (without repainting the cells or disassembling the cube).
