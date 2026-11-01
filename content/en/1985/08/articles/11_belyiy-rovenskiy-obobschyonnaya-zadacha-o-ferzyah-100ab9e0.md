---
id: 1985-8-belyiy-rovenskiy-obobschyonnaya-zadacha-o-ferzyah-100ab9e0
issue: kvant_1985_8
year: 1985
number: "8"
title: Generalized queen problem
authors:
  - Белый С. Б.
  - Ровенский Е. А.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 28
page_last: 29
page_labels: 26-27
tag: E7MN
lang: en
source: kvant_digital
extraction: vision
content_sha256: af144cacedf833925a7defd97280d40b0794cdddedf2555de3d058db95bc059c
prompt_sha256: draft-1
translated_from: content/ru/1985/08/articles/11_belyiy-rovenskiy-obobschyonnaya-zadacha-o-ferzyah-100ab9e0.md
source_content_sha256: 6b4d13b5b98ebfc2522b15cdbe2a0555492c82dbfc91aecc10af9d7b0f8ff7cd
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 26⟧

Generalized queen problem

S. V. BELY,
E. A. ROVENSKY

The queen problem - placing the maximum number of queens on a chessboard so that they do not threaten each other, and finding the number of all such placements - has long become a classic one. In the 19th century, the great German mathematician Carl Friedrich Gauss (1777–1855) dealt with this problem, and in our century, the outstanding American mathematician and cyberNETIK Kolod Shenon (b. 1916) pointed out its direct relevance to the issues of noise-resistant coding.

Recently, an interesting generalization of this problem concerning the arrangement of the maximum number of queens has appeared (Science and Life, 1982, No. 3, p. 73; «Kvant», 1983, No. 1, 3rd page of the region): on a chessboard, arrange the maximum number of queens p so that each of them attacks exactly k queens (1≤k≤4). This problem was posed by American mathematician Scott Kim and published in J. Recreational Mathematics, 1979-80, vol. 12, no. 1, p. 53 (an American magazine that publishes articles and problems of a borrowing nature in mathematics). When k=0 we get a classic problem for which p_max=8. Think about why the constraint k≤4 was made in the problem statement. Kim managed to solve a particular problem (J. Recreational Mathematics, 1980-81, vol. 13, no. 1, p. 61-62). Named:

$$p_{\text{max}} = 10 \text{ для } k = 1,$$
$$p_{\text{max}} = 14 \text{ для } k = 2.$$

Examples of corresponding arrangements are shown in Figures 1 and 2.

For k=3 and k=4, arrangements were found to be p=16 (ibid.) and p=21 (Scientific American, 1981, vol. 245, no. 6, p. 19), respectively, but it remained unknown whether these numbers were the maximum.

In this problem we will prove that $p_{\text{max}} = 18$ for k=3, (3)
$p_{\text{max}} = 21$ for k=4. (4)

Figure 3 and 4 show that formations with this number of queens exist. Note that the arrangement with p=18 for k=3 was not known. Let's now try to find an upper bound for p.

Let p be the number of queens, and q the number of rows (verticals, horizontals and diagonals) on which at least one queen stands. Then, if the queens did not attack each other, then q=4p. But since the total number of battles is equal to pk (each queen attacks exactly k queens), then

$$q = 4p - \frac{pk}{2} \text{ или } r = \frac{2k}{8-k}.$$

Let us now prove (3). The total number of verticals, horizontals and diagonals on the n×n board is 6n−2, so

$$q \leq 6n-2.$$

From (5) and (6) for an 8×8 board we obtain p≤18.

⟦folio 27⟧

Let's prove (4). Since the corner squares of the board cannot be occupied by queens (why?), we get
$$q \leq 6n - 6.$$

From (5) and (7) for board $8 \times 8$ we find $p \leq 21$.

So, Kim's problem is completely solved. It only remains for us to add that the maximum arrangements of queens shown in Figures 3 and 4 were found using a computer (this took about 30 minutes of calculations on a computer with the number of operations of 200 thousand per second). Readers who know how to program can try their hand at creating such a program.

Research problem.
A natural generalization of S. Kim’s problem is the following problem:
On the chessboard $n \times n$ place the maximum number of queens $p_{\max} = p(n, k)$ so that each of them attacks exactly $k$ queens ($0 \leq k \leq 4$), and find the number $N = N(n, k)$ that

Discovery of X-rays

(For the beginning, see p. 25)

given more intense radiation (essentially it was the first X-ray tube).

Roentgen summarized the results obtained in the brochure “On a New Kind of Rays,” published in early January 1896. At the same time, he sent out the first X-ray images to the world's leading physicists, including images of his wife's hands. Please, not a single physical discovery has aroused such enormous and universal interest as the discovery by X-rays of rays passing through walls and allowing one to see the invisible. Physicists immediately began to repeat amazing experiments, journalists filled the pages of newspapers with sensational reports. In 1901, Roentgen became the first Nobel Prize winner in physics.

Modern areas of application of X-rays are difficult to even list - medicine, genetics, defectology, X-ray structural analysis, X-ray spectral analysis, studies of ancient paintings, forensics...

The discovery of X-rays occupies an outstanding position in the history of science - it was with it that the dawn of atomic and nuclear physics began. “At the beginning of 1896, on the very day when in Paris it became known about Roentgen’s experiments and the need for light rays emitted by liminescent walls... work,” said A. Becquerel, “I decided to use whether any other liminescent substance also emits rays.” The assumption turned out to be incorrect, but radioactivity was discovered in Becquerel's experiments.

And J. J. Thomson recalled: “I had been investigating for some time the conductivity of gases under the influence of electrical forces, but it was becoming difficult to find any method of producing conductivity that was efficient and reliable. New rays removed this difficulty... Experiments that were incredibly difficult before the discovery of rays became easy.” The result of these “light experiments” was Thomson’s discovery (in the spring of 1897) of the electron.

V. E. Yavelov
