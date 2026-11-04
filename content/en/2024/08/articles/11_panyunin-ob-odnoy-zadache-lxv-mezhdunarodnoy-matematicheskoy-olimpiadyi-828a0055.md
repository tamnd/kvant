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
page_last: 43
page_labels: 39-41
tag: QFTK
lang: en
source: kvant_digital
content_sha256: 0ca3920548dcd30cdbfc25e0296ae925db07baf52f5b56793582a27f29f4f1dd
prompt_sha256: draft-1
translated_from: content/ru/2024/08/articles/11_panyunin-ob-odnoy-zadache-lxv-mezhdunarodnoy-matematicheskoy-olimpiadyi-828a0055.md
source_content_sha256: 47da04533019c965033d5fe97ef70e170898acf57990514969bd1bc2c8e2f0de
translation_model: draft
translation_run: en-draft-2026-11-03
translation_quality: draft
---

⟦folio 39⟧

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

also all the cells of the column under the monster. Then, having used one more try to understand whether there is a monster in the yellow cells, in no more than the third attempt Turbo will reach the goal along one of the blue paths. However, the above reasoning does not work in the case when the detected Turbo monster is located at the edge of the second line, for example, on the left (Fig. 2). In this case, if Turbo checks to see if the yellow square is empty, she may run into a monster, thus wasting her second try. But bypass this cell, as in the case

⟦column⟧

with the monster not on the edge, it won’t work: there’s a wall on the left. Thus, it may take four attempts to get to the bottom line: two have already been used, and Turbo is guaranteed to only get to the third line. If she continues to act in this way, then in the case of a diagonal arrangement of monsters (Fig. 3), the number of attempts will increase. Is it possible to do something differently? The decisive consideration in this case is to avoid checking monsters in extreme positions. Now let's move on to presenting the solution. Let Turbo act as follows. During the first attempt, Turbo checks all cells of the second row, except the outermost ones 2,1 and 2,11. If there is a monster in one of them, then Turbo already knows how to reach the bottom line in no more than three attempts. If not, then, leaving the outermost cells as suspicious (Fig. 4), Turbo will check the cells of the third row. Again, not all, but starting from 3.3 and up to 3.9. If there is a monster in these cells, then again Turbo knows how to reach the last line in no more than three attempts.

⟦figure⟧

Fig. 2

⟦figure⟧

Fig. 4

Fig. 3

Fig. 5

⟦folio 41⟧

---
running_head:
folio:
---

If not, then Turbo will check the cells of the fourth row, starting from (4,4) to (4,8). And so on until checking in line number 6 of cell (6,6) (Fig. 5).

If there is a monster in cell (6,6), then Turbo will be added again three attempts before the last line. If not, then we are in a situation where the cells marked green at figure 5 have been checked and there are no monsters in them. In addition, there are suspicious cells that we considered unprofitable to check, since if a monster is found there in three attempts, Turbo is not added to the bottom. These cells are marked in yellow.

Now you need to stay and think about what to do next. Let's do this. Let Turbo figure out exactly where the monster is in the 6th line. To do this, she will have to spend one try. Let's say the monster is on the left side of the 6th line in the cell marked in red (Fig. 6). This means that the remaining cells in this row are free of monsters.

Then have Turbo check all the cells to the right of the yellow one in the 7th row (Fig. 7). If there is a monster there, then the Turbo of the next, third, attempt is added to the bottom line, for example, along the path indicated by blue

Fig. 8

lines. If there is no monster there, then have Turbo check cells from (8,8) to (8,11). If there is a monster there, then again on the third attempt you can find the exit along a path similar to figure 7, and if not, then proceed to check the cells of the next line from (9,9) to (9,11). And so on.

As a result, either Turbo will get a situation like at figure 8, and then in two attempts she will find a way out, or she will come across a monster to the right of the yellow cells figure 8 and then exit on the third attempt along a path similar to that at figure 7.

It remains to be seen why two attempts are not enough. We leave this as an exercise for the reader.

So, the answer to the problem is 3 attempts.

The author of this problem is four-time international Olympiad medalist from Hong Kong Chu Cheuk Hei. The history of its origin is interesting.

In an English exam, the author of the problem and his classmate were given a game on a 6x6 checkered field, in which there was a snail and there were monsters. And the examinee had to understand the rules of the game by listening to texts in English. The game, according to Chokhei, was pretty stupid. However, Chheukhei and his classmates adjusted the rules and the task turned out to be. First on a 6x6 field, and then on a 2023x2024 field - in the form in which it appeared at the Olympiad.

Choekhei notes that the task did not seem difficult to him. And he was very surprised that it ended up on IMO, especially at number 5. Many participants say that they expected the answer from this problem to be 2024, 2024/2, log₂2024 or something similar, but not CONSTANT, regardless of the size of the game board.
