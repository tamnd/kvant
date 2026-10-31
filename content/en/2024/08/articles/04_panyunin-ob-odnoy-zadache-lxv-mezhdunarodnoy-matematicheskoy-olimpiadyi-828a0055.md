---
id: 2024-8-panyunin-ob-odnoy-zadache-lxv-mezhdunarodnoy-matematicheskoy-olimpiadyi-828a0055
issue: kvant_2024_8
year: 2024
number: "8"
title: About one problem of the LXV International Mathematical Olympiad
authors:
  - Панюнин Н. М.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 41
page_last: 42
page_labels: 39-40
tag: QFTK
lang: en
source: kvant_digital
extraction: native
content_sha256: 050ddd7a3a81c480475af3bb354f256eab46158dd16c1a4b29fca9d2e23b4749
prompt_sha256: draft-1
translated_from: content/ru/2024/08/articles/04_panyunin-ob-odnoy-zadache-lxv-mezhdunarodnoy-matematicheskoy-olimpiadyi-828a0055.md
source_content_sha256: 5ef19846bfabba4e78993ceb195729d0e460eb816682c49c155ff5cd7b75235a
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 39⟧

MATHEMATICAL

Thus, points P, Q in Problem 2 are Humpty points, and since they are isogonally conjugate, they are also Humpty points. To summarize, we note that in fact in problems 1 and 2 the equivalence of the following statements was proven: x in triangle ABC the segments AC and BC are equal; x Brocard points lie on the medians of vertices A and B;

About one problem of the LXV International Mathematical Olympiad

N. PANYUNIN

This article will talk about one nice problem from the last International Mathematical Olympiad. Here is her condition. Snail Turbo plays the following game on a board that has 2024 rows and 2023 columns. There are monsters hiding in 2022 squares of the board. Turbo initially doesn't know where any of the monsters are, but she does know that there is exactly one monster in each row except the first and last, and that there is at most one monster in each column. Turbo makes a series of attempts to get from the first row to the last. On each attempt, she can choose any cell in the first row as the starting one, and then makes a series of movements from the cell to an adjacent cell that has a common side. (She is allowed to return to previously visited cells.) If she visits a cell with a monster, then her

DOI: https://doi.org/10.4213/kvant20240805

CIRCLE

⟦column⟧

x Brocard points lie on the simedians of vertices A and B; x Humpty’s A-point coincides with Dumpty’s B-point; x Brocard's points are Humpty's points; x Brocard points are Dumpty points. Perhaps readers will be able to discover other properties of the design discussed.

the attempt ends and she is moved back to the front row to begin a new attempt. The monsters don't move, and Turbo remembers whether there's a monster in every cell she visits. If she reaches any square in the last row, her attempt is completed and the game ends. Determine the minimum value of n such that Turbo has a strategy that, regardless of the monsters' locations, guarantees reaching the last row in n tries or less. Even if you are an eighth or seventh grader, try solving the problem on your own first. It is possible that after reading the solution or even seeing the answer, you will realize that you could have found the solution yourself. Note, however, that both participants and even leaders of some traditionally strong teams had difficulty with this task. The children from the Russian team received the highest total number of points for this task – 38. Let's first examine the problem. Let's number the rows from top to bottom, and the columns from left to right. The cell located in the i-th row and j-th column will be denoted by i, j. Green will indicate fields where there are definitely no monsters, red - where there are monsters, yellow - suspicious fields. Instead of a 2023 u 2024 board, consider a field with 11 columns and 12 rows. This will not change the essence of the solution, and we will leave the general case to the reader. Let Turbo discover the monster in the second line, spending one try (Fig. 1) on this. Note that in this case, all other cells of the second row, to the left and right of the monster, are free from monsters, and

⟦folio 40⟧

KVAN T 2024/No.8

⟦figure⟧

Fig. 1

also all cells of the column under the monster. Then, having used one more try to understand whether there is a monster in the yellow cells, in no more than the third attempt Turbo will reach the goal along one of the blue paths. However, the above reasoning does not work in the case when the detected Turbo monster is located at the edge of the second line, for example, on the left (Fig. 2). In this case, if Turbo checks to see if the yellow square is empty, she may run into a monster, thus wasting her second try. But bypass this cell, as in the case

⟦column⟧

with the monster not on the edge, it won’t work: there’s a wall on the left. Thus, it may take four attempts to get to the bottom line: two have already been used, and Turbo is guaranteed to only get to the third line. If she continues to act in this way, then in the case of a diagonal arrangement of monsters (Fig. 3), the number of attempts will increase. Is it possible to do something differently? The decisive consideration in this case is to avoid checking monsters in extreme positions. Now let's move on to presenting the solution. Let Turbo act as follows. During the first attempt, Turbo checks all cells of the second row, except the outermost ones 2,1 and 2,11. If there is a monster in one of them, then Turbo already knows how to reach the bottom line in no more than three attempts. If not, then, leaving the outermost cells as suspicious (Fig. 4), Turbo will check the cells of the third line. Again, not all, but starting from 3.3 and up to 3.9. If there is a monster in these cells, then again Turbo knows how to reach the last line in no more than three attempts.

⟦figure⟧

Fig. 2

⟦figure⟧

Fig. 4

Fig. 3

Fig. 5
